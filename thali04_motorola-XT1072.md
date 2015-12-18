#### Test 50650278bcecc5c_thali04_motorola-XT1072 Logs


```
--------- beginning of main
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
D/AndroidRuntime( 6614): 
D/AndroidRuntime( 6614): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6614): CheckJNI is OFF
D/AndroidRuntime( 6614): Calling main entry com.android.commands.am.Am
--------- beginning of system
I/ActivityManager(  883): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
I/ActivityManager(  883): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6633 uid=10391 gids={50391, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 6614): Shutting down VM
V/ActivityManager(  883): Display changed displayId=0
W/ContextImpl( 1478): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
W/ContextImpl( 1478): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,I/WebViewFactory( 6633): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 6633): Time to load native libraries: 3 ms (timestamps 3475-3478)
,I/LibraryLoader( 6633): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 6633): Binding Chromium to main looper Looper (main, tid 1) {459897f}
,I/LibraryLoader( 6633): Expected native library version number "",actual native library version number ""
,I/chromium( 6633): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 6633): Initializing chromium process, singleProcess=true
,W/art     ( 6633): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 6633): ApplicationContext is null in ApplicationStatus
,W/chromium( 6633): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 6633): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 6633): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 6633): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 6633): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 6633): Build Date: 10/28/14 Tue
I/Adreno-EGL( 6633): Local Branch: 
I/Adreno-EGL( 6633): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 6633): Local Patches: NONE
I/Adreno-EGL( 6633): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,W/ActivityManager(  883): Activity pause timeout for ActivityRecord{12069eda u0 com.test.thalitest/.MainActivity t3}
,D/BluetoothManagerService(  883): Message: 20
D/BluetoothManagerService(  883): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@aca3e39:true
,W/BroadcastQueue(  883): Skipping deliver [background] BroadcastRecord{2f2ab1d7 u0 com.motorola.blur.service.blur.Actions.CHECKIN} to ReceiverList{1df119f0 2647 com.motorola.ccc/10000/u0 remote:3dd63233}: process crashing
W/BroadcastQueue(  883): Skipping deliver [background] BroadcastRecord{2f2ab1d7 u0 com.motorola.blur.service.blur.Actions.CHECKIN} to ReceiverList{bb7be8f 2647 com.motorola.ccc/10000/u0 remote:2f3a19ee}: process crashing
,W/art     ( 6633): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 6633): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 6633): CordovaWebView is running on device made by: motorola
,W/art     ( 6633): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 6633): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 6633): Render dirty regions requested: true
,D/Atlas   ( 6633): Validating map...
,W/chromium( 6633): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/OpenGLRenderer( 6633): Initialized EGL, version 1.4
,D/OpenGLRenderer( 6633): Enabling debug mode 0
,I/LaunchCheckinHandler(  883): Displayed com.test.thalitest/.MainActivity,cp,ca,1030
I/ActivityManager(  883): Displayed com.test.thalitest/.MainActivity: +961ms (total +1s30ms)
,E/Adreno-ES20( 6633): <check_framebuffer_attachment:854>: Invalid texture format! Returning error!
E/Adreno-ES20( 6633): <check_framebuffer_object_status:1237>: Framebuffer color attachment incomplete. Returning GL_FRAMEBUFFER_INCOMPLETE_ATTACHMENT!
,W/BindingManager( 6633): Cannot call determinedVisibility() - never saw a connection for the pid: 6633
,D/JsMessageQueue( 6633): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 6633): JniHelper::setJavaVM(0xb7c8c310), pthread_self() = -1207849976
D/JX-Cordova( 6633): jxcore cordova android initializing
,V/AlarmManager(  883): send {2716923a, *walarm*:com.google.android.intent.action.SEND_IDLE}
,V/AlarmManager(  883): done {2716923a, *walarm*:com.google.android.intent.action.SEND_IDLE} [8ms]
,W/jxcore-log( 6633): Initializing JXcore engine
W/jxcore-log( 6633): JXcore engine is ready
,W/jxcore-log( 6633): Starting JXcore engine
,W/.test.thalitest( 6633): type=1400 audit(0.0:4): avc: denied { ioctl } for uid=10391 path="socket:[6851]" dev="sockfs" ino=6851 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,W/.test.thalitest( 6633): type=1400 audit(0.0:5): avc: denied { ioctl } for uid=10391 path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2122 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
W/.test.thalitest( 6633): type=1400 audit(0.0:6): avc: denied { ioctl } for uid=10391 path="socket:[9496]" dev="sockfs" ino=9496 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/.test.thalitest( 6633): type=1400 audit(0.0:7): avc: denied { ioctl } for uid=10391 path="socket:[29652]" dev="sockfs" ino=29652 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,W/jxcore-log( 6633): Platform android
W/jxcore-log( 6633): 
,W/jxcore-log( 6633): Process ARCH arm
W/jxcore-log( 6633): 
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:32000 mC
,I/jxcore-log( 6633): JXcore Cordova bridge is ready!
I/jxcore-log( 6633): 
W/jxcore-log( 6633): JXcore engine is started
I/chromium( 6633): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 6633): Toggling radios to true
I/jxcore-log( 6633): 
,D/BluetoothAdapter( 6633): enable(): BT is already enabled..!
,D/WifiService(  883): New client listening to asynchronous messages
,D/WifiService(  883): setWifiEnabled: true pid=6633, uid=10391
E/WifiService(  883): Invoking mWifiStateMachine.setWifiEnabled
,I/jxcore-log( 6633): Radios toggled
I/jxcore-log( 6633): 
,D/BluetoothManagerService(  883): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/jxcore-log( 6633): Got Device Bluetooth address: 44:80:EB:7B:5A:05
I/jxcore-log( 6633): 
I/jxcore-log( 6633): Perf Test app loaded loaded
I/jxcore-log( 6633): 
,I/jxcore-log( 6633): check test folder
I/jxcore-log( 6633): 
I/jxcore-log( 6633): found test : ./testFindPeers.js
I/jxcore-log( 6633): 
,I/wpa_supplicant( 1442): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
,D/MDMCTBK (  291): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-DISCONNECTED 
D/MDMCTBK (  291): Event received = CTRL-EVENT-DISCONNECTED 
D/MDMCTBK (  291):  STA Disconnected !!
,I/MDMCTBK (  291): checkDefaultInst, current pid is = 291
I/MDMCTBK (  291): checkDefaultInst, pid match
I/MDMCTBK (  291): get_property_value, Enter
I/MDMCTBK (  291): get_property_value, Values read from property=1,0,0,0,0,0,1,0,0,1,1,0, length=23
I/MDMCTBK (  291): get_property_value, Exit
I/MDMCTBK (  291): MdmCutbackHndler,wifiDisconnected wifi_dis=1, current_wifi=1
I/MDMCTBK (  291): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=0, mf=0, wfd=0
I/MDMCTBK (  291): set_property_value, Enter
I/MDMCTBK (  291): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
D/TCMD    (  474): NL - Read 1004 bytes from update socket.
D/TCMD    (  474): NL - message type is RTM_NEWLINK
D/TCMD    (  474): Listening for incoming client connection request
D/TCMD    (  474): NL - Read 68 bytes from update socket.
D/TCMD    (  474): NL - message type is RTM_NEWLINK
D/TCMD    (  474): Listening for incoming client connection request
D/TCMD    (  474): NL - Read 68 bytes from update socket.
D/TCMD    (  474): NL - message type is RTM_NEWLINK
D/TCMD    (  474): Listening for incoming client connection request
,D/Tethering(  883): InitialState.processMessage what=4
,I/MDMCTBK (  291): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  291): set_property_value, Exit
I/MDMCTBK (  291): MdmCutbackHndler, setWifiCutback, No Wifi
I/MDMCTBK (  291): MdmCutbackHndler,Wifi disconnected !!!
I/MDMCTBK (  291): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=0, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  291): set_property_value, Enter
I/MDMCTBK (  291): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
,I/wpa_supplicant( 1442): wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=WORLD
,I/MDMCTBK (  291): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  291): set_property_value, Exit
E/MDMCTBK (  291): MdmCutbackHndler,Airplane Mode Enabled !! =1
D/MDMCTBK (  291): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  291): Event received = CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  291): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-REGDOM-CHANGE
D/MDMCTBK (  291): Event received = CTRL-EVENT-REGDOM-CHANGE
,W/Settings(  883): Setting tether_dun_apn has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,E/WifiStateMachine(  883): WifiStateMachine: Leaving Connected state
E/Tethering(  883): ApnList is empty for checkDunConfigured()
D/Tethering(  883):  upstream interface types: 
D/Tethering(  883):  1
D/Tethering(  883):  5
D/Tethering(  883):  7
D/Tethering(  883):  0
,E/WifiStateMachine(  883): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$8800 - exit - invokeExitMethods
E/WifiStateMachine(  883): handleNetworkDisconnect any config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  883): handleNetworkDisconnect "NG700" nid=0
E/WifiConfigStore(  883): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,I/wpa_supplicant( 1442): wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=US
D/Tethering(  883): sendTetherStateChangedBroadcast 0, 0, 0
D/MDMCTBK (  291): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-REGDOM-CHANGE
D/MDMCTBK (  291): Event received = CTRL-EVENT-REGDOM-CHANGE
,E/WifiStateMachine(  883): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/WifiStateMachine(  883): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/native  (  883): do suspend true
,D/WifiP2pService(  883): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  883): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,E/wpa_supplicant( 1442): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
,D/CommandListener(  289): Clearing all IP addresses on wlan0
,D/TCMD    (  474): NL - Read 60 bytes from update socket.
D/TCMD    (  474): NL - ignore NL message, type = 21
D/TCMD    (  474): Listening for incoming client connection request
,V/NativeCrypto( 1740): Read error: ssl=0xb7eefd10: I/O error during system call, Connection timed out
,I/jxcore-log( 6633): found test : ./testSendData.js
I/jxcore-log( 6633): 
V/NativeCrypto( 1740): SSL shutdown failed: ssl=0xb7eefd10: I/O error during system call, Broken pipe
D/ConnectivityService(  883): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10016
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  883): ValidatedState{ when=0 what=532488 arg1=10016 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  883): DefaultState{ when=0 what=532488 arg1=10016 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  883): Forcing reevaluation
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  883): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  883): Checking http://clients3.google.com/generate_204 on "NG700"
,E/WifiStateMachine(  883): setDetailed state, old =CONNECTED and new state=DISCONNECTED hidden=false
E/WifiStateMachine(  883): setDetailed state send new extra info<unknown ssid>
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  883): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
,I/ActivityManager(  883): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6694 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/SBar.MotoNetworkCtrlr( 1293): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1293): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
D/WifiMetrics(  883): connected time updated 129851
,D/ConnectivityService(  883): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService(  883): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
,D/Checkin (  883): publish the event [tag = MOT_WIFI_L1 event name = CONNECT]
I/SBar.MotoNetworkCtrlr( 1293): refreshSignalCluster[0]: wifi: mWifiConnected=true Wifi=0x7f02012a=com.android.systemui:drawable/stat_sys_wifi_signal_0_fully Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
,D/Checkin (  883): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,E/wpa_supplicant( 1442): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
E/WifiStateMachine(  883): Start Disconnecting Watchdog 1
,I/wpa_supplicant( 1442): wlan0: CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  291): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  291): Event received = CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  291): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  291): Event received = CTRL-EVENT-SCAN-STARTED 
D/Checkin (  883): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,E/WifiStateMachine(  883): ConnectModeState: Network connection lost 
,I/SBar.MotoNetworkCtrlr( 1293): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1293): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1293): refreshSignalCluster[0]: wifi: mWifiConnected=false Wifi=0x7f020133=com.android.systemui:drawable/stat_sys_wifi_signal_null Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
I/SBar.MotoNetworkCtrlr( 1293): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1293): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,E/WifiStateMachine(  883): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$8800 - processMessage - processMsg
E/WifiStateMachine(  883): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/WifiStateMachine(  883): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/native  (  883): do suspend true
,D/WifiP2pService(  883): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  883): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,E/wpa_supplicant( 1442): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
,W/ResourcesManager( 6694): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/CommandListener(  289): Clearing all IP addresses on wlan0
,D/ConnectivityService(  883): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
D/Nat464Xlat(  883): requiresClat: netType=1, connected=false, hasIPv4Address=true
D/CSLegacyTypeTracker(  883): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  883): EvaluatingState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  883): DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  883): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  883): Disconnected - quitting
E/WifiStateMachine(  883): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
,D/ConnectivityManager.CallbackHandler( 1293): CM callback handler got msg 524292
D/ConnectivityService(  883): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
I/ModemStatsDSDetect( 1537): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
,I/SBar.MotoNetworkCtrlr( 1293): onReceive: CONNECTIVITY_ACTION_IMMEDIATE Recieved, mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/ConnectivityService(  883): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,E/ConnectivityService(  883): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,I/ModemStatsDSDetect( 1537): INET_CONDITION=0 ,activeNet=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ModemStatsDSDetect( 1537): onReceive() - done, currentInetCondition=0
,I/ModemStatsDSDetect( 1537): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
,I/SBar.MotoNetworkCtrlr( 1293): updateConnectivity[0]: NetworkInfo: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false], raw inetCondition= 0
I/ModemStatsDSDetect( 1537): INET_CONDITION=0 ,activeNet=null
I/ModemStatsDSDetect( 1537): onReceive() - done, currentInetCondition=0
,I/SBar.MotoNetworkCtrlr( 1293): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1293): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1293): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1293): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1293): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1293): onReceive: CONNECTIVITY_ACTION_IMMEDIATE Recieved, mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/Checkin (  883): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
I/SBar.MotoNetworkCtrlr( 1293): updateConnectivity[0]: NetworkInfo: null, raw inetCondition= 0
I/SBar.MotoNetworkCtrlr( 1293): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1293): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1293): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/chromium( 6633): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
E/WifiStateMachine(  883): SUPPLICANT_STATE_CHANGE_EVENT state=DISCONNECTED -> state= DISCONNECTED debouncing=false
E/WifiStateMachine(  883): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
,E/WifiStateMachine(  883): Link configuration changed for netId: -1 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  883): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
,E/WifiStateMachine(  883): Link configuration changed for netId: -1 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  883): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
,E/WifiStateMachine(  883): Link configuration changed for netId: -1 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  883): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
D/WifiNetworkAgent(  883): NetworkAgent: NetworkAgent channel lost
E/WifiStateMachine(  883): SUPPLICANT_STATE_CHANGE_EVENT state=SCANNING -> state= SCANNING debouncing=false
E/WifiStateMachine(  883): setDetailed state, old =DISCONNECTED and new state=SCANNING hidden=false
E/WifiStateMachine(  883): setDetailed state send new extra info"NG700"
I/SBar.MotoNetworkCtrlr( 1293): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1293): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/Checkin (  883): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,I/SBar.MotoNetworkCtrlr( 1293): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1293): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/Checkin (  883): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,I/art     (  883): Explicit concurrent mark sweep GC freed 53179(2MB) AllocSpace objects, 3(230KB) LOS objects, 33% free, 21MB/31MB, paused 1.641ms total 153.845ms
,I/Babel_SMS( 6694): MmsConfig: mnc/mcc: 0/0
,I/Babel_SMS( 6694): MmsConfig.loadMmsSettings
I/Babel_SMS( 6694): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
I/Babel_SMS( 6694): MmsConfig.loadFromDatabase
,E/Babel_SMS( 6694): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 6694): MmsConfig.loadFromResources
,E/Babel_SMS( 6694): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 6694): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/Settings( 6694): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 6694): startup - clean
,I/Babel   ( 6694): deleted: false for 0
,I/ActivityManager(  883): Start proc com.motorola.context for broadcast com.motorola.context/.publisher.location.LocationReceiver: pid=6732 uid=10008 gids={50008, 9997, 3001, 3002, 3003} abi=armeabi-v7a
,D/MDMCTBK (  291): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  291): Event received = CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  291): reply_len: 40 reply is = IFNAME=wlan0 <3>WPS-AP-AVAILABLE 
D/MDMCTBK (  291): Event received = WPS-AP-AVAILABLE 
D/TCMD    (  474): NL - Read 56 bytes from update socket.
D/TCMD    (  474): NL - message type is RTM_NEWLINK
D/TCMD    (  474): Listening for incoming client connection request
,E/WifiStateMachine(  883): [1,450,461,235,066 ms] noteScanEnd no scan source
,I/wpa_supplicant( 1442): wlan0: Trying to associate with SSID 'NG700'
D/MDMCTBK (  291): reply_len: 40 reply is = IFNAME=wlan0 <3>Trying to associate with
,D/MDMCTBK (  291): Event received = Trying to associate with
D/WifiMonitor(  883): didn't find BSSID Trying to associate with SSID 'NG700'
,E/wpa_supplicant( 1442): DSDS: eapol_sm_notify_config config->sim_num = 1
,D/MDMCTBK (  291): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  291): Event received = CTRL-EVENT-STATE-CHANGE 
E/WifiStateMachine(  883): wifi setScanResults statecom.android.server.wifi.WifiStateMachine$DisconnectedState@1b7e2ac3 sup_state=SCANNING debouncing=false
,E/WifiStateMachine(  883): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATING -> state= CONNECTING debouncing=false
E/WifiStateMachine(  883): setDetailed state, old =SCANNING and new state=CONNECTING hidden=false
E/WifiStateMachine(  883): setDetailed state send new extra info0x
,I/SBar.MotoNetworkCtrlr( 1293): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1293): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1293): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1293): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/Checkin (  883): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,W/VideoCapabilities( 6694): Unrecognized profile 2130706433 for video/avc
,W/ResourcesManager( 6732): Asset path '/system/framework/com.motorola.motosignature.jar' does not exist or contains no resources.
,W/AudioCapabilities( 6694): Unsupported mime audio/amr-wb-plus
,W/VideoCapabilities( 6694): Unsupported mime video/mpeg2
,I/ActivityManager(  883): Killing 6384:com.google.android.apps.docs/u0a57 (adj 15): empty #7
,I/VideoCapabilities( 6694): Unsupported profile 4 for video/mp4v-es
,D/TCMD    (  474): NL - Read 312 bytes from update socket.
D/TCMD    (  474): NL - message type is RTM_NEWLINK
D/TCMD    (  474): Listening for incoming client connection request
D/TCMD    (  474): NL - Read 192 bytes from update socket.
D/TCMD    (  474): NL - message type is RTM_NEWLINK
,D/TCMD    (  474): Listening for incoming client connection request
D/TCMD    (  474): NL - Read 68 bytes from update socket.
D/TCMD    (  474): NL - message type is RTM_NEWLINK
D/TCMD    (  474): Listening for incoming client connection request
D/TCMD    (  474): NL - Read 1004 bytes from update socket.
D/TCMD    (  474): NL - message type is RTM_NEWLINK
D/TCMD    (  474): Listening for incoming client connection request
D/TCMD    (  474): NL - Read 80 bytes from update socket.
D/TCMD    (  474): NL - message type is RTM_NEWLINK
D/TCMD    (  474): Listening for incoming client connection request
D/TCMD    (  474): NL - Read 80 bytes from update socket.
D/TCMD    (  474): NL - message type is RTM_NEWLINK
D/TCMD    (  474): Listening for incoming client connection request
D/TCMD    (  474): NL - Read 68 bytes from update socket.
,D/TCMD    (  474): NL - message type is RTM_NEWLINK
D/TCMD    (  474): Listening for incoming client connection request
I/wpa_supplicant( 1442): wlan0: Associated with c0:ff:d4:d3:aa:48
D/MDMCTBK (  291): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  291): Event received = CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  291): reply_len: 40 reply is = IFNAME=wlan0 <3>Associated with c0:ff:d4
D/MDMCTBK (  291): Event received = Associated with c0:ff:d4
D/MDMCTBK (  291): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  291): Event received = CTRL-EVENT-STATE-CHANGE 
E/WifiStateMachine(  883): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATED -> state= CONNECTING debouncing=false
E/WifiStateMachine(  883): setDetailed state, old =CONNECTING and new state=CONNECTING hidden=false
E/WifiStateMachine(  883): SUPPLICANT_STATE_CHANGE_EVENT state=FOUR_WAY_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine(  883): setDetailed state, old =CONNECTING and new state=AUTHENTICATING hidden=false
,E/WifiStateMachine(  883): setDetailed state send new extra info"NG700"
,D/Tethering(  883): exception when get active network info: java.lang.NullPointerException: Attempt to invoke virtual method 'int android.net.NetworkInfo.getType()' on a null object reference
,W/Settings(  883): Setting tether_dun_apn has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/Tethering(  883): ApnList is empty for checkDunConfigured()
,D/Tethering(  883):  upstream interface types: 
,D/Tethering(  883):  0
,D/Tethering(  883):  1
,D/Tethering(  883):  5
,D/Tethering(  883):  7
,D/MDMCTBK (  291): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  291): Event received = CTRL-EVENT-STATE-CHANGE 
I/wpa_supplicant( 1442): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 1442): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
D/TCMD    (  474): NL - Read 1004 bytes from update socket.
D/TCMD    (  474): NL - message type is RTM_NEWLINK
D/TCMD    (  474): Listening for incoming client connection request
D/MDMCTBK (  291): reply_len: 40 reply is = IFNAME=wlan0 <3>WPA: Key negotiation com
D/MDMCTBK (  291): Event received = WPA: Key negotiation com
,D/MDMCTBK (  291): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-CONNECTED - C
D/MDMCTBK (  291): Event received = CTRL-EVENT-CONNECTED - C
D/MDMCTBK (  291):  STA Connected !!
E/MDMCTBK (  291): cmd: IFNAME=wlan0 ASSOCFREQ, reply: 2412, reply_len: 4, ret: 0
D/MDMCTBK (  291): get_freq !!, resp=2412
I/MDMCTBK (  291): get_freq !!, Strip data
I/MDMCTBK (  291): get_freq !!, band = 2, freq = 2412
,I/MDMCTBK (  291): checkDefaultInst, current pid is = 291
I/MDMCTBK (  291): checkDefaultInst, pid match
I/MDMCTBK (  291): get_property_value, Enter
I/MDMCTBK (  291): get_property_value, Values read from property=1,0,0,0,0,0,0,0,0,1,1,0, length=23
I/MDMCTBK (  291): get_property_value, Exit
I/MDMCTBK (  291): MdmCutbackHndler,UpdateWifiBand band=2, current_band=2
I/MDMCTBK (  291): MdmCutbackHndler,UpdateWifiBand set mWifi to True, call setWifiCutback and sendSarCtrl!!!
I/MDMCTBK (  291): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=1, mf=0, wfd=0
I/MDMCTBK (  291): set_property_value, Enter
I/MDMCTBK (  291): set_property_value, Values updated in the property=1,0,0,0,0,0,1,0,0,1,1,0
I/MDMCTBK (  291): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  291): set_property_value, Exit
I/MDMCTBK (  291): MdmCutbackHndler,setWifiCutback, Wifi_cbk_Used= 0, Wifi_band=2, p2p0 = 1, wlan0 = 1, data=0
I/MDMCTBK (  291): MdmCutbackHndler,WifiBand =2, MifiBand =-1, tx_pwr=18
I/MDMCTBK (  291): MdmCutbackHndler, set WIFI TX pwr !!
I/MDMCTBK (  291): checkDefaultInst, current pid is = 291
I/MDMCTBK (  291): checkDefaultInst, pid match
I/MDMCTBK (  291): get_property_value, Enter
I/MDMCTBK (  291): get_property_value, Values read from property=1,0,0,0,0,0,1,0,0,1,1,0, length=23
I/MDMCTBK (  291): get_property_value, Exit
I/MDMCTBK (  291): create_thread_wpa_supplicant: Started WPA thread for wifi_set_tx_pwr thread -1194156720
I/MDMCTBK (  291): return from set_get_from_wpa_supplicant
I/MDMCTBK (  291): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=1, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  291): set_property_value, Enter
D/MDMCTBK (  291): wifi_set_tx_pwr: SETTXPOWER = 18
I/MDMCTBK (  291): set_property_value, Values updated in the property=1,0,0,0,0,0,1,0,0,1,1,0
E/MDMCTBK (  291): cmd: IFNAME=wlan0 DRIVER SETTXPOWER 18, reply: OK
E/MDMCTBK (  291): , reply_len: 3, ret: 0
E/MDMCTBK (  291): MdmCutbackHndler, resp=OK
E/MDMCTBK (  291): 
I/MDMCTBK (  291): set_property_value, Values updated in the property file Successfully
D/MDMCTBK (  291): wifi_set_tx_pwr: Exit
I/MDMCTBK (  291): set_property_value, Exit
E/MDMCTBK (  291): MdmCutbackHndler,Airplane Mode Enabled !! =1
W/VideoCapabilities( 6694): Unrecognized profile 2130706433 for video/avc
D/MDMCTBK (  291): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  291): Event received = CTRL-EVENT-STATE-CHANGE 
W/VideoCapabilities( 6694): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6694): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6694): Unrecognized profile 2130706433 for video/avc
,W/libprocessgroup(  883): failed to open /acct/uid_10057/pid_6384/cgroup.procs: No such file or directory
,D/Tethering(  883): sendTetherStateChangedBroadcast 1, 0, 0
,I/ActivityManager(  883): Killing 6421:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,I/vclib   ( 6694): onServiceConnected
,W/Babel   ( 6694): Attempted to change video mute state without an active call.
,I/SBar.MotoNetworkCtrlr( 1293): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1293): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,W/libprocessgroup(  883): failed to open /acct/uid_10090/pid_6421/cgroup.procs: No such file or directory
,I/SBar.MotoNetworkCtrlr( 1293): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1293): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
E/WifiStateMachine(  883): SUPPLICANT_STATE_CHANGE_EVENT state=GROUP_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine(  883): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING hidden=false
,E/WifiStateMachine(  883): Network connection established
E/WifiStateMachine(  883): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR hidden=false
,I/SBar.MotoNetworkCtrlr( 1293): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1293): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1293): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1293): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,E/WifiStateMachine(  883): setDetailed state, old =OBTAINING_IPADDR and new state=CONNECTING hidden=false
,I/SBar.MotoNetworkCtrlr( 1293): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1293): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/ConnectivityService(  883): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
,D/ConnectivityService(  883): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
E/WifiStateMachine(  883): L2ConnectedState any config "NG700"WPA_PSK config.bssid any
,E/WifiStateMachine(  883): L2ConnectedState "NG700" nid=0
,E/WifiConfigStore(  883): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,E/WifiStateMachine(  883): enter ObtainingIpState netId=0 "NG700"WPA_PSK  roam=0 static=false watchdog= 1
E/WifiStateMachine(  883): ObtainingIpAddress any config "NG700"WPA_PSK config.bssid any
,E/WifiStateMachine(  883): ObtainingIpAddress "NG700" nid=0
E/WifiConfigStore(  883): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,D/CommandListener(  289): Setting iface cfg
,E/WifiStateMachine(  883): Start Dhcp Watchdog 2
,E/WifiStateMachine(  883): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  883): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES
,E/WifiStateMachine(  883): setSuspendOptimizationsNative: 1 false -want true stack:setSuspendOptimizationsNative - handlePreDhcpSetup - processMessage - processMsg
E/native  (  883): do suspend false
,E/wpa_supplicant( 1442): wpa_driver_nl80211_driver_cmd: failed to issue private commands
,E/WifiStateMachine(  883): Unexpected BatchedScanResults :null
E/wpa_supplicant( 1442): wpa_driver_nl80211_driver_cmd: failed to issue private commands
D/WifiP2pService(  883): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@32abe53e target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  883): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@32abe53e target=com.android.internal.util.StateMachine$SmHandler }
,E/DHCPCD  ( 6758): fopen `/system/etc/dhcpcd/dhcpcd.conf': m
,I/DHCPCD  ( 6758): version 5.5.6 starting
,E/DHCPCD  ( 6758): fopen `/system/etc/dhcpcd/dhcpcd.conf': m
,D/DHCPCD  ( 6758): wlan0: using ClientID 01:44:80:eb:7b:5a:06
D/DHCPCD  ( 6758): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
,D/DHCPCD  ( 6758): wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
,I/DHCPCD  ( 6758): wlan0: rebinding lease of 192.168.1.123
D/DHCPCD  ( 6758): wlan0: sending REQUEST (xid 0xd4e912d), next in 4.11 seconds
,I/DHCPCD  ( 6758): wlan0: acknowledged 192.168.1.123 from 192.168.1.1
,I/DHCPCD  ( 6758): wlan0: leased 192.168.1.123 for 86400 seconds
,D/DHCPCD  ( 6758): wlan0: adding IP address 192.168.1.123/24
,D/DHCPCD  ( 6758): wlan0: adding route to 192.168.1.0/24
D/DHCPCD  ( 6758): wlan0: adding default route via 192.168.1.1
D/DHCPCD  ( 6758): wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
D/TCMD    (  474): NL - Read 60 bytes from update socket.
D/TCMD    (  474): NL - ignore NL message, type = 20
D/TCMD    (  474): Listening for incoming client connection request
,D/DHCPCD  ( 6758): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
,E/WifiStateMachine(  883): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
,E/WifiStateMachine(  883): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES v4
,E/WifiStateMachine(  883): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,fe80::4680:ebff:fe7b:5a06/64,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
,E/WifiStateMachine(  883): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES v4
,E/WifiStateMachine(  883): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
E/WifiStateMachine(  883): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
E/native  (  883): do suspend true
,D/WifiP2pService(  883): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  883): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,E/WifiStateMachine(  883): WifiStateMachine DHCP successful
,E/WifiStateMachine(  883): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,fe80::4680:ebff:fe7b:5a06/64,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,fe80::4680:ebff:fe7b:5a06/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,E/WifiStateMachine(  883): updateLinkProperties nid: 0 state: CONNECTING reason: DHCP_SUCCESS v4 v4r v4dns isprov
E/WifiStateMachine(  883): Calling ARP set with IP = 192.168.1.123
,E/WifiStateMachine(  883): setDetailed state, old =CONNECTING and new state=CAPTIVE_PORTAL_CHECK hidden=false
,I/SBar.MotoNetworkCtrlr( 1293): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1293): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1293): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
E/WifiStateMachine(  883): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED hidden=false
D/ConnectivityService(  883): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
I/SBar.MotoNetworkCtrlr( 1293): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/ConnectivityService(  883): Adding iface wlan0 to network 101
,I/SBar.MotoNetworkCtrlr( 1293): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1293): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1293): refreshSignalCluster[0]: wifi: mWifiConnected=true Wifi=0x7f020129=com.android.systemui:drawable/stat_sys_wifi_signal_0 Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
,D/Checkin (  883): publish the event [tag = MOT_WIFI_L1 event name = CONNECT]
,I/SBar.MotoNetworkCtrlr( 1293): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1293): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,E/ConnectivityService(  883): Unexpected mtu value: 0, wlan0
,D/ConnectivityService(  883): Adding Route [fe80::/64 -> :: wlan0] to network 101
,D/ConnectivityService(  883): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,D/ConnectivityService(  883): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,D/ConnectivityService(  883): Setting Dns servers for network 101 to [/192.168.1.1]
E/WifiStateMachine(  883): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,E/WifiStateMachine(  883): ConnectedState Enter  mScreenOn=false scanperiod=20000
,D/Checkin (  883): publish the event [tag = MOT_WIFI_L1 event name = CONNECT]
,D/Nat464Xlat(  883): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  883): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  883): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  883): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  883):    accepting network in place of null
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  883): DefaultState{ when=-2ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  883): Connected
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  883): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  883): Checking http://clients3.google.com/generate_204 on "NG700"
,D/ConnectivityService(  883): UpdateTcpBufferSizes: same sizes as current, ignore operation
,D/CSLegacyTypeTracker(  883): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/ConnectivityService(  883): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityService(  883): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,fe80::4680:ebff:fe7b:5a06/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
,D/ConnectivityService(  883): UpdateTcpBufferSizes: same sizes as current, ignore operation
D/ConnectivityService(  883): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityManager.CallbackHandler( 1293): CM callback handler got msg 524290
I/SBar.MotoNetworkCtrlr( 1293): onReceive: CONNECTIVITY_ACTION_IMMEDIATE Recieved, mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/ModemStatsDSDetect( 1537): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
I/ModemStatsDSDetect( 1537): INET_CONDITION=0 ,activeNet=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ModemStatsDSDetect( 1537): onReceive() - done, currentInetCondition=0
,I/SBar.MotoNetworkCtrlr( 1293): updateConnectivity[0]: NetworkInfo: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false], raw inetCondition= 0
,I/SBar.MotoNetworkCtrlr( 1293): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1293): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1293): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  883): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 18 Dec 2015 17:53:57 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1450461237498], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1450461237477]}
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  883): Don't send network conditions - lacking user consent.
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  883): Validated
D/ConnectivityService(  883): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  883): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  883): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService(  883): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityService(  883): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,I/ModemStatsDSDetect( 1537): onReceive() -Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) }
,D/ConnectivityManager.CallbackHandler( 1293): CM callback handler got msg 524290
I/SBar.MotoNetworkCtrlr( 1293): onReceive: INET_CONDITION_ACTION Recieved, mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/ModemStatsDSDetect( 1537): INET_CONDITION=100 ,activeNet=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/ModemStatsDSDetect( 1537): Inetcondition changed, white->blue
I/ModemStatsDSDetect( 1537): onReceive() - done, currentInetCondition=100
I/SBar.MotoNetworkCtrlr( 1293): updateConnectivity: The netConditon[0] for netType 1=WiFi is updated as 1=good by android.net.conn.INET_CONDITION_ACTION, icon color should be white (on KK); without "!" (on L).
,I/SBar.MotoNetworkCtrlr( 1293): updateConnectivity[0]: NetworkInfo: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false], raw inetCondition= 1
,I/SBar.MotoNetworkCtrlr( 1293): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1293): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1293): refreshSignalCluster[0]: wifi: mWifiConnected=true Wifi=0x7f02012a=com.android.systemui:drawable/stat_sys_wifi_signal_0_fully Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
,I/SBar.MotoNetworkCtrlr( 1293): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/ConnectivityService(  883): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  883): MasterInitialState.processMessage what=3
,W/BroadcastQueue(  883): Skipping deliver [background] BroadcastRecord{1f1b5df2 u-1 android.net.conn.CONNECTIVITY_CHANGE} to ReceiverList{32ff701a 2647 com.motorola.ccc/10000/u0 remote:5f0bec5}: process crashing
W/BroadcastQueue(  883): Skipping deliver [background] BroadcastRecord{1f1b5df2 u-1 android.net.conn.CONNECTIVITY_CHANGE} to ReceiverList{14a831e9 2647 com.motorola.ccc/10000/u0 remote:38053a70}: process crashing
,W/BroadcastQueue(  883): Skipping deliver [background] BroadcastRecord{1f1b5df2 u-1 android.net.conn.CONNECTIVITY_CHANGE} to ReceiverList{d2fc6da 2647 com.motorola.ccc/10000/u0 remote:2b653885}: process crashing
,W/BroadcastQueue(  883): Skipping deliver [background] BroadcastRecord{1f1b5df2 u-1 android.net.conn.CONNECTIVITY_CHANGE} to ReceiverList{10566fa9 2647 com.motorola.ccc/10000/u0 remote:1632d730}: process crashing
D/ConnectivityService(  883): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Central_PollingManager( 1478): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/ContextImpl( 1478): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1469 android.content.ContextWrapper.sendBroadcast:381 com.motorola.blur.service.blur.BSUtils.sendBroadcast:94 com.motorola.blur.service.blur.BSUtils.sendBroadcast:90 com.motorola.ccc.plm.pollingmanager.PollingManagerService$MyConnectivityReceiver.onReceive:491 
,I/ActivityManager(  883): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=6826 uid=10080 gids={50080, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/BroadcastQueue(  883): Skipping deliver [background] BroadcastRecord{3072ec43 u-1 android.net.conn.CONNECTIVITY_CHANGE} to ReceiverList{32ff701a 2647 com.motorola.ccc/10000/u0 remote:5f0bec5}: process crashing
W/BroadcastQueue(  883): Skipping deliver [background] BroadcastRecord{3072ec43 u-1 android.net.conn.CONNECTIVITY_CHANGE} to ReceiverList{14a831e9 2647 com.motorola.ccc/10000/u0 remote:38053a70}: process crashing
W/BroadcastQueue(  883): Skipping deliver [background] BroadcastRecord{3072ec43 u-1 android.net.conn.CONNECTIVITY_CHANGE} to ReceiverList{d2fc6da 2647 com.motorola.ccc/10000/u0 remote:2b653885}: process crashing
D/Tethering(  883): MasterInitialState.processMessage what=3
W/BroadcastQueue(  883): Skipping deliver [background] BroadcastRecord{3072ec43 u-1 android.net.conn.CONNECTIVITY_CHANGE} to ReceiverList{10566fa9 2647 com.motorola.ccc/10000/u0 remote:1632d730}: process crashing
W/BroadcastQueue(  883): Skipping deliver [background] BroadcastRecord{23bd32c0 u0 com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY} to ReceiverList{2de23b0d 2647 com.motorola.ccc/10000/u0 remote:552e1a4}: process crashing
W/BroadcastQueue(  883): Skipping deliver [background] BroadcastRecord{23bd32c0 u0 com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY} to ReceiverList{8a38241 2647 com.motorola.ccc/10000/u0 remote:c84b528}: process crashing
W/BroadcastQueue(  883): Skipping deliver [background] BroadcastRecord{23bd32c0 u0 com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY} to ReceiverList{1c20293b 2647 com.motorola.ccc/10000/u0 remote:a413ca}: process crashing
W/BroadcastQueue(  883): Skipping deliver [background] BroadcastRecord{23bd32c0 u0 com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY} to ReceiverList{255b8d9c 2647 com.motorola.ccc/10000/u0 remote:2250b90f}: process crashing
W/BroadcastQueue(  883): Skipping deliver [background] BroadcastRecord{23bd32c0 u0 com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY} to ReceiverList{f503ccd 2647 com.motorola.ccc/10000/u0 remote:3514d264}: process crashing
,D/Central_PollingManager( 1478): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/Central_PollingManager( 1478): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
,W/BroadcastQueue(  883): Skipping deliver [background] BroadcastRecord{23bd32c0 u0 com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY} to ReceiverList{2845d801 2647 com.motorola.ccc/10000/u0 remote:407c9e8}: process crashing
W/BroadcastQueue(  883): Skipping deliver [background] BroadcastRecord{23bd32c0 u0 com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY} to ReceiverList{bb7be8f 2647 com.motorola.ccc/10000/u0 remote:2f3a19ee}: process crashing
,I/art     (  307): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 302us total 25.071ms
,I/art     (  307): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 240us total 20.234ms
,I/art     (  307): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 242us total 19.508ms
,I/ActivityManager(  883): Start proc com.google.android.apps.plus for service com.google.android.apps.plus/.service.EsSyncAdapterService: pid=6843 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,W/ResourcesManager( 6843): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/MusicStore( 6826): Database version: 120
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6826): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6826): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6826): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,W/ResourcesManager( 6826): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6826): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 6826): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 6826): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 6826): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@3483b44b: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6826): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 6826): GMSCore installation verified
,I/ConfigStore( 6826): Config Database version: 1
,I/MediaRouter( 6826): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 6826): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/NetworkMonitor( 6826): type=WIFI subType= reason=null isConnected=true
,I/NetworkMonitor( 6826): type=WIFI subType= reason=null isConnected=true
,D/ConnectivityService(  883): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,I/ActivityManager(  883): Start proc com.android.mms for broadcast com.android.mms/.transaction.MmsSystemEventReceiver: pid=6884 uid=10023 gids={50023, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/GHttpClientFactory( 6826): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 6826): Using platform SSLCertificateSocketFactory
,I/ActivityManager(  883): Killing 6323:com.android.vending/u0a32 (adj 15): empty #7
,W/libprocessgroup(  883): failed to open /acct/uid_10032/pid_6323/cgroup.procs: No such file or directory
,V/Mms     ( 6884): mnc/mcc: 
,V/Mms     ( 6884): tag: int value: recipientLimit - 20
,V/Mms     ( 6884): tag: int value: smsToMmsTextThreshold - 6
,V/Mms     ( 6884): tag: int value: emergencySmsTimeout - 30
V/Mms     ( 6884): tag: int value: maxSubjectLength - 80
,V/Mms     ( 6884): tag: bool value: smsForceShowEncodingMenu - true
V/Mms     ( 6884): tag: bool value: enableGroupMms - false
V/Mms     ( 6884):  mUserAgent = MOT-XT1072/Mms-5.0,  mUaProfUrl = http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,I/ActivityManager(  883): Killing 6694:com.google.android.talk/u0a70 (adj 15): empty #7
,W/libprocessgroup(  883): failed to open /acct/uid_10070/pid_6694/cgroup.procs: No such file or directory
,W/ResourcesManager( 6884): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/ActivityManager(  883): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=6916 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  883): Killing 6732:com.motorola.context/u0a8 (adj 15): empty #7
,W/libprocessgroup(  883): failed to open /acct/uid_10008/pid_6732/cgroup.procs: No such file or directory
,D/PhoneMonitor( 6916): Register our PhoneStateListener
,D/MobileConnectivityChangeReceiver( 6916): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 6916): onReceive CONNECTIVITY_CHANGE networkType=1
,I/ActivityManager(  883): Killing 6236:android.process.acore/u0a7 (adj 15): empty #7
,W/libprocessgroup(  883): failed to open /acct/uid_10007/pid_6236/cgroup.procs: No such file or directory
,I/CheckinService( 6487): Checkin interval check for package: unspecified last checkin: 1450461149595 min interval config: 0 actual interval: 89336
,I/CheckinService( 6487): Disabling old GoogleServicesFramework version
,I/CheckinService( 6487): Checking schedule, now: 1450461238964 next: 1450461179576
,I/CheckinService( 6487): active receiver: enabled
,I/iu.SyncManager( 6487): SYNC; picasa accounts
,D/NetworkLogImpl( 6487): Loaded NetworkSpeedPredictor
,I/CheckinService( 6487): Preparing to send checkin request
,I/iu.Environment( 6487): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/EventLogService( 6487): Accumulating logs since 1450461146385
,I/iu.UploadsManager( 6487): num queued entries: 0
,I/iu.UploadsManager( 6487): num updated entries: 0
,I/iu.SyncManager( 6487): NEXT; no task
,I/ActivityManager(  883): Start proc com.google.android.apps.photos for broadcast com.google.android.apps.photos/.jobqueue.JobServiceBroadcastReceiver: pid=6947 uid=10088 gids={50088, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/CheckinRequestBuilder( 6487): Checkin reason type: 8 attempt count: 1
,D/WifiService(  883): New client listening to asynchronous messages
,E/ActivityThread( 6487): Failed to find provider info for com.google.android.wearable.settings
,I/ActivityManager(  883): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6967 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/art     (  883): Explicit concurrent mark sweep GC freed 37779(1900KB) AllocSpace objects, 5(80KB) LOS objects, 33% free, 21MB/31MB, paused 2.326ms total 128.440ms
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6633): setDiscoveryMode: Failed to set discovery mode to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6633): setDiscoveryMode: Mode set to WIFI
,I/jxcore-log( 6633): BLE supported!!
I/jxcore-log( 6633): 
,W/ResourcesManager( 6967): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,V/GLSActivity( 1740): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1740): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  883): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=6989 uid=10016 gids={50016, 9997, 3003, 1028, 1015, 3002, 3001, 1005, 1007, 3007, 2001, 3006} abi=armeabi-v7a
,I/Babel_SMS( 6967): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 6967): MmsConfig.loadMmsSettings
,I/Babel_SMS( 6967): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,I/Babel_SMS( 6967): MmsConfig.loadFromDatabase
,W/ResourcesManager( 6989): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6989): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,E/Babel_SMS( 6967): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 6967): MmsConfig.loadFromResources
E/Babel_SMS( 6967): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel_SMS( 6967): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,I/MultiDex( 6989): VM with version 2.1.0 has multidex support
I/MultiDex( 6989): install
,I/MultiDex( 6989): VM has multidex support, MultiDex support library is disabled.
,V/JNIHelp ( 6989): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/Settings( 6967): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 6967): startup - clean
,W/ActivityThread( 6989): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 6989): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@38bd6b0: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 6989): Installed default security provider GmsCore_OpenSSL
,I/Babel   ( 6967): deleted: false for 0
,I/art     ( 6989): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 6989): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,I/ActivityManager(  883): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7023 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/NativeLibraryUtils( 6989): Install completed successfully. count=14 extracted=0
,W/VideoCapabilities( 6967): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 6967): Unsupported mime audio/amr-wb-plus
,W/VideoCapabilities( 6967): Unsupported mime video/mpeg2
,I/VideoCapabilities( 6967): Unsupported profile 4 for video/mp4v-es
,D/WVCdm   (  294): Instantiating CDM.
,I/WVCdm   (  294): CdmEngine::OpenSession
,I/WVCdm   (  294): Level3 Library Sep 25 2014 17:10:03
,W/WVCdm   (  294): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,W/VideoCapabilities( 6967): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6967): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6967): Unrecognized profile 2130706433 for video/avc
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
,W/VideoCapabilities( 6967): Unrecognized profile 2130706433 for video/avc
,D/QSEECOMAPI: (  294): Loaded image: APP id = 3
,D/DrmWidevineDash(  294): Service_Initialize: ends! returns 0
D/DrmWidevineDash(  294): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4fa3000
E/DrmWidevineDash(  294): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4fa3000
,D/DrmWidevineDash(  294): OEMCrypto_Initialize: ends! returns 0
D/DrmWidevineDash(  294): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  294): hlos api version =  9
D/DrmWidevineDash(  294): tz api version =  8
D/DrmWidevineDash(  294): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  294): OEMCrypto_IsKeyboxValid: starts!
,D/DrmWidevineDash(  294): OEMCrypto_IsKeyboxValid: ends! returns 0
D/WVCdm   (  294): OEMCrypto_Initialize Level 1 success. I will use level 1.
D/DrmWidevineDash(  294): OEMCrypto_OpenSession: starts! SID=0xb557e960
D/DrmWidevineDash(  294): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  294): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  294): OEMCrypto_GetRandom: starts! randomData=0xb8f12588, dataLength=8
D/DrmWidevineDash(  294): OEMCrypto_GetRandom: ends! returns 0
D/DrmWidevineDash(  294): OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb8e773c0, wrapped_rsa_key_length=1280
,I/vclib   ( 6967): onServiceConnected
,D/DrmWidevineDash(  294): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
I/WVCdm   (  294): CdmEngine::QueryKeyControlInfo
,W/Babel   ( 6967): Attempted to change video mute state without an active call.
,W/WVCdm   (  294): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  294): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  294): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  294): OEMCrypto_GetDeviceID: starts! deviceID=0xb8f5df20, idLength=0xb547e730
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
D/WVCdm   (  294): PrepareKeyRequest: nonce=394102944
D/DrmWidevineDash(  294): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb8e6d570
D/DrmWidevineDash(  294): message_length=1591, signature=0xb8e72350, signature_length=3041388308
,W/art     ( 6989): Suspending all threads took: 7.793ms
,I/Babel   ( 6967): connection state changed from UNKNOWN to CONNECTED
,I/ActivityManager(  883): Killing 6826:com.google.android.music:main/u0a80 (adj 15): empty #7
,D/ConnectivityService(  883): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,W/libprocessgroup(  883): failed to open /acct/uid_10080/pid_6826/cgroup.procs: No such file or directory
,W/BroadcastQueue(  883): Skipping deliver [background] BroadcastRecord{91d7436 u-1 android.net.conn.CONNECTIVITY_CHANGE} to ReceiverList{32ff701a 2647 com.motorola.ccc/10000/u0 remote:5f0bec5}: process crashing
,W/BroadcastQueue(  883): Skipping deliver [background] BroadcastRecord{91d7436 u-1 android.net.conn.CONNECTIVITY_CHANGE} to ReceiverList{14a831e9 2647 com.motorola.ccc/10000/u0 remote:38053a70}: process crashing
W/BroadcastQueue(  883): Skipping deliver [background] BroadcastRecord{91d7436 u-1 android.net.conn.CONNECTIVITY_CHANGE} to ReceiverList{d2fc6da 2647 com.motorola.ccc/10000/u0 remote:2b653885}: process crashing
,W/BroadcastQueue(  883): Skipping deliver [background] BroadcastRecord{91d7436 u-1 android.net.conn.CONNECTIVITY_CHANGE} to ReceiverList{10566fa9 2647 com.motorola.ccc/10000/u0 remote:1632d730}: process crashing
,D/Tethering(  883): MasterInitialState.processMessage what=3
D/Central_PollingManager( 1478): connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/ContextImpl( 1478): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1469 android.content.ContextWrapper.sendBroadcast:381 com.motorola.blur.service.blur.BSUtils.sendBroadcast:94 com.motorola.blur.service.blur.BSUtils.sendBroadcast:90 com.motorola.ccc.plm.pollingmanager.PollingManagerService$MyConnectivityReceiver.onReceive:491 
,W/BroadcastQueue(  883): Skipping deliver [background] BroadcastRecord{32b71f37 u0 com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY} to ReceiverList{2de23b0d 2647 com.motorola.ccc/10000/u0 remote:552e1a4}: process crashing
W/BroadcastQueue(  883): Skipping deliver [background] BroadcastRecord{32b71f37 u0 com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY} to ReceiverList{8a38241 2647 com.motorola.ccc/10000/u0 remote:c84b528}: process crashing
D/Central_PollingManager( 1478): now: 205396 ,futureTime: 86473787
W/BroadcastQueue(  883): Skipping deliver [background] BroadcastRecord{32b71f37 u0 com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY} to ReceiverList{1c20293b 2647 com.motorola.ccc/10000/u0 remote:a413ca}: process crashing
D/Central_PollingManager( 1478): Polling alarm set to expire at: 86473787 Current Time: 205396
W/BroadcastQueue(  883): Skipping deliver [background] BroadcastRecord{32b71f37 u0 com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY} to ReceiverList{255b8d9c 2647 com.motorola.ccc/10000/u0 remote:2250b90f}: process crashing
W/BroadcastQueue(  883): Skipping deliver [background] BroadcastRecord{32b71f37 u0 com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY} to ReceiverList{f503ccd 2647 com.motorola.ccc/10000/u0 remote:3514d264}: process crashing
W/BroadcastQueue(  883): Skipping deliver [background] BroadcastRecord{32b71f37 u0 com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY} to ReceiverList{2845d801 2647 com.motorola.ccc/10000/u0 remote:407c9e8}: process crashing
,W/BroadcastQueue(  883): Skipping deliver [background] BroadcastRecord{32b71f37 u0 com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY} to ReceiverList{bb7be8f 2647 com.motorola.ccc/10000/u0 remote:2f3a19ee}: process crashing
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
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7023): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7023): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7023): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
,W/Vold    (  277): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7023): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,I/GAv4    ( 7023): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 7023):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 7023):   adb logcat -s GAv4
,W/GAv4    ( 7023): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 7023): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 7023): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/WebViewFactory( 7023): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 7023): Time to load native libraries: 2 ms (timestamps 5863-5865)
I/LibraryLoader( 7023): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 7023): Binding Chromium to main looper Looper (main, tid 1) {265a4be0}
,I/LibraryLoader( 7023): Expected native library version number "",actual native library version number ""
I/chromium( 7023): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 7023): Initializing chromium process, singleProcess=true
,W/art     ( 7023): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 7023): ApplicationContext is null in ApplicationStatus
,W/chromium( 7023): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 7023): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 7023): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 7023): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 7023): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7023): Build Date: 10/28/14 Tue
I/Adreno-EGL( 7023): Local Branch: 
I/Adreno-EGL( 7023): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 7023): Local Patches: NONE
I/Adreno-EGL( 7023): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/dex2oat ( 7073): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=28 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,W/AudioManagerAndroid( 7023): Requires BLUETOOTH permission
,I/NSApplication( 7023): Starting up...
,I/dex2oat ( 7073): dex2oat took 122.822ms (threads: 4)
,I/Adreno-EGL( 6989): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 6989): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 6989): Build Date: 10/28/14 Tue
I/Adreno-EGL( 6989): Local Branch: 
I/Adreno-EGL( 6989): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 6989): Local Patches: NONE
I/Adreno-EGL( 6989): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/ActivityManager(  883): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=7095 uid=10052 gids={50052, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  883): Killing 6843:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,I/Adreno-EGL( 6989): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 6989): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 6989): Build Date: 10/28/14 Tue
I/Adreno-EGL( 6989): Local Branch: 
I/Adreno-EGL( 6989): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 6989): Local Patches: NONE
I/Adreno-EGL( 6989): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,W/libprocessgroup(  883): failed to open /acct/uid_10090/pid_6843/cgroup.procs: No such file or directory
,I/WVCdm   (  294): CdmEngine::OpenSession
I/WVCdm   (  294): Level3 Library Sep 25 2014 17:10:03
,W/WVCdm   (  294): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,D/DrmWidevineDash(  294): OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x13
D/DrmWidevineDash(  294): Service_Initialize: starts!
,D/QSEECOMAPI: (  294): QSEECom_get_handle sb_length = 0x19000
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
D/DrmWidevineDash(  294): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4fa3000
E/DrmWidevineDash(  294): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4fa3000
,D/DrmWidevineDash(  294): OEMCrypto_Initialize: ends! returns 0
D/DrmWidevineDash(  294): OEMCrypto_APIVersion: starts!
,D/DrmWidevineDash(  294): hlos api version =  9
D/DrmWidevineDash(  294): tz api version =  8
D/DrmWidevineDash(  294): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  294): OEMCrypto_IsKeyboxValid: starts!
,D/DrmWidevineDash(  294): OEMCrypto_IsKeyboxValid: ends! returns 0
D/WVCdm   (  294): OEMCrypto_Initialize Level 1 success. I will use level 1.
D/DrmWidevineDash(  294): OEMCrypto_OpenSession: starts! SID=0xb547e960
D/DrmWidevineDash(  294): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  294): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  294): OEMCrypto_GetRandom: starts! randomData=0xb8e6da68, dataLength=8
,D/DrmWidevineDash(  294): OEMCrypto_GetRandom: ends! returns 0
,D/DrmWidevineDash(  294): OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb8e773c0, wrapped_rsa_key_length=1280
,D/DrmWidevineDash(  294): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
I/WVCdm   (  294): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  294): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  294): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  294): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  294): OEMCrypto_GetDeviceID: starts! deviceID=0xb8f5df60, idLength=0xbea4c2b0
,D/DrmWidevineDash(  294): OEMCrypto_GetDeviceID: ends! returns 0
D/DrmWidevineDash(  294): OEMCrypto_SupportsUsageTable: starts!
,D/DrmWidevineDash(  294): OEMCrypto_SupportsUsageTable: is_supported = 1
,D/DrmWidevineDash(  294): OEMCrypto_SupportsUsageTable: wv_app_version = 25
,D/DrmWidevineDash(  294): OEMCrypto_SupportsUsageTable: ends! returns 0x0
,D/DrmWidevineDash(  294): OEMCrypto_GetHDCPCapability: starts!
D/DrmWidevineDash(  294): OEMCrypto_GetHDCPCapability: ends! returns 0x0
D/DrmWidevineDash(  294): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  294): hlos api version =  9
D/DrmWidevineDash(  294): tz api version =  8
D/DrmWidevineDash(  294): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  294): OEMCrypto_GenerateNonce: starts! SID=1
D/DrmWidevineDash(  294): OEMCrypto_GenerateNonce: ends! returns 0
D/WVCdm   (  294): PrepareKeyRequest: nonce=68686239
D/DrmWidevineDash(  294): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb8e397d8
D/DrmWidevineDash(  294): message_length=1625, signature=0xb8e72330, signature_length=3198468756
,I/ActivityManager(  883): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7120 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  883): Killing 6884:com.android.mms/u0a23 (adj 15): empty #7
,W/libprocessgroup(  883): failed to open /acct/uid_10023/pid_6884/cgroup.procs: No such file or directory
,D/DrmWidevineDash(  294): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  294): CdmEngine::CloseSession
D/DrmWidevineDash(  294): OEMCrypto_CloseSession: starts! SID=1
D/DrmWidevineDash(  294): OEMCrypto_CloseSession: ends! returns 0
I/WVCdm   (  294): L3 Terminate.
D/DrmWidevineDash(  294): OEMCrypto_Terminate: starts!
D/DrmWidevineDash(  294): Service_Uninitialize: starts!
D/QSEECOMAPI: (  294): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  294): QSEECom_shutdown_app, app_id = 3
,D/DrmWidevineDash(  294): Service_Uninitialize: ends! returns 0x0
,D/DrmWidevineDash(  294): OEMCrypto_Terminate: ends! returns 0
,W/ResourcesManager( 7120): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:33000 mC
,I/ActivityManager(  883): Start proc android.process.acore for content provider com.android.providers.contacts/.ContactsProvider2: pid=7141 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,I/ActivityManager(  883): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=7166 uid=10080 gids={50080, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  883): Killing 6947:com.google.android.apps.photos/u0a88 (adj 15): empty #7
,I/art     (  307): Explicit concurrent mark sweep GC freed 704(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 284us total 21.289ms
,I/art     (  307): Explicit concurrent mark sweep GC freed 7(240B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 286us total 19.661ms
,I/art     (  307): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 255us total 20.219ms
,I/ActivityManager(  883): Killing 6916:com.google.android.setupwizard/u0a35 (adj 15): empty #8
,I/ContactLocale( 7141): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,W/libprocessgroup(  883): failed to open /acct/uid_10088/pid_6947/cgroup.procs: No such file or directory
,V/AlarmManager(  883): send {62c4399, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  883): send {709fa5, *walarm*:com.google.android.intent.action.GCM_RECONNECT}
W/libprocessgroup(  883): failed to open /acct/uid_10035/pid_6916/cgroup.procs: No such file or directory
,V/AlarmManager(  883): done {62c4399, *alarm*:android.intent.action.TIME_TICK} [119ms]
,I/MusicStore( 7166): Database version: 120
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7166): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7166): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
,W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7166): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,W/ResourcesManager( 7166): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7166): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 7166): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 7166): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 7166): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@3483b44b: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7166): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 7166): GMSCore installation verified
,I/ConfigStore( 7166): Config Database version: 1
,I/art     ( 6449): Explicit concurrent mark sweep GC freed 1595(70KB) AllocSpace objects, 0(0B) LOS objects, 25% free, 7MB/9MB, paused 349us total 23.890ms
,I/MediaRouter( 7166): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 7166): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/NetworkMonitor( 7166): type=WIFI subType= reason=null isConnected=true
,I/NetworkMonitor( 7166): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  883): Start proc com.android.mms for broadcast com.android.mms/.transaction.MmsSystemEventReceiver: pid=7201 uid=10023 gids={50023, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/Adreno-EGL( 6989): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 6989): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 6989): Build Date: 10/28/14 Tue
I/Adreno-EGL( 6989): Local Branch: 
I/Adreno-EGL( 6989): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 6989): Local Patches: NONE
I/Adreno-EGL( 6989): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/GHttpClientFactory( 7166): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 7166): Using platform SSLCertificateSocketFactory
,I/ActivityManager(  883): Killing 6967:com.google.android.talk/u0a70 (adj 15): empty #7
,I/Adreno-EGL( 6989): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 6989): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 6989): Build Date: 10/28/14 Tue
I/Adreno-EGL( 6989): Local Branch: 
I/Adreno-EGL( 6989): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 6989): Local Patches: NONE
I/Adreno-EGL( 6989): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,W/libprocessgroup(  883): failed to open /acct/uid_10070/pid_6967/cgroup.procs: No such file or directory
,V/Mms     ( 7201): mnc/mcc: 
,V/Mms     ( 7201): tag: int value: recipientLimit - 20
V/Mms     ( 7201): tag: int value: smsToMmsTextThreshold - 6
V/Mms     ( 7201): tag: int value: emergencySmsTimeout - 30
V/Mms     ( 7201): tag: int value: maxSubjectLength - 80
V/Mms     ( 7201): tag: bool value: smsForceShowEncodingMenu - true
V/Mms     ( 7201): tag: bool value: enableGroupMms - false
,V/Mms     ( 7201):  mUserAgent = MOT-XT1072/Mms-5.0,  mUaProfUrl = http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/ResourcesManager( 7201): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/CheckinRequestBuilder( 6487): Classify the device as Phone.
,I/ActivityManager(  883): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=7233 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,D/PhoneMonitor( 7233): Register our PhoneStateListener
,D/MobileConnectivityChangeReceiver( 7233): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 7233): onReceive CONNECTIVITY_CHANGE networkType=1
,I/ActivityManager(  883): Killing 7023:com.google.android.apps.magazines/u0a81 (adj 15): empty #7
,I/art     (  883): Explicit concurrent mark sweep GC freed 14934(729KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 21MB/31MB, paused 1.759ms total 132.372ms
,W/libprocessgroup(  883): failed to open /acct/uid_10081/pid_7023/cgroup.procs: No such file or directory
,I/CheckinService( 6487): Checkin interval check for package: unspecified last checkin: 1450461149595 min interval config: 0 actual interval: 93569
,I/ActivityManager(  883): Start proc com.google.android.apps.photos for broadcast com.google.android.apps.photos/.jobqueue.JobServiceBroadcastReceiver: pid=7252 uid=10088 gids={50088, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  883): Killing 7095:com.android.chrome/u0a52 (adj 15): empty #7
,W/libprocessgroup(  883): failed to open /acct/uid_10052/pid_7095/cgroup.procs: No such file or directory
,I/CheckinTask( 6487): Sending checkin request (9448 bytes)
,I/ActivityManager(  883): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=7271 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/ActivityManager(  883): Killing 7120:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,W/libprocessgroup(  883): failed to open /acct/uid_10090/pid_7120/cgroup.procs: No such file or directory
,W/ResourcesManager( 7271): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/Babel_SMS( 7271): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 7271): MmsConfig.loadMmsSettings
,I/Babel_SMS( 7271): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
I/Babel_SMS( 7271): MmsConfig.loadFromDatabase
,E/Babel_SMS( 7271): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 7271): MmsConfig.loadFromResources
,E/Babel_SMS( 7271): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 7271): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/Settings( 7271): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 7271): startup - clean
,I/Babel   ( 7271): deleted: false for 0
,I/ActivityManager(  883): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7310 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/VideoCapabilities( 7271): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 7271): Unsupported mime audio/amr-wb-plus
,W/VideoCapabilities( 7271): Unsupported mime video/mpeg2
,I/VideoCapabilities( 7271): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 7271): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7271): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7271): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7271): Unrecognized profile 2130706433 for video/avc
I/CheckinRequestBuilder( 6487): Checkin reason type: 8 attempt count: 1
,E/ActivityThread( 6487): Failed to find provider info for com.google.android.wearable.settings
,I/vclib   ( 7271): onServiceConnected
,W/Babel   ( 7271): Attempted to change video mute state without an active call.
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7310): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,I/GAv4    ( 7310): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 7310):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 7310):   adb logcat -s GAv4
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7310): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7310): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,W/GAv4    ( 7310): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7310): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,I/Babel   ( 7271): connection state changed from UNKNOWN to CONNECTED
,I/ActivityManager(  883): Killing 7141:android.process.acore/u0a7 (adj 15): empty #7
,W/GAv4    ( 7310): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 7310): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,W/libprocessgroup(  883): failed to open /acct/uid_10007/pid_7141/cgroup.procs: No such file or directory
,I/CheckinRequestBuilder( 6487): Classify the device as Phone.
,I/CheckinTask( 6487): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 6487): Checking schedule, now: 1450461244413 next: 1451062381404
I/CheckinService( 6487): active receiver: disabled
,I/CheckinService( 6487): Checking schedule, now: 1450461244429 next: 1451062381404
I/CheckinService( 6487): active receiver: disabled
,D/CheckinService( 6487): Recording last checkin time for package unspecified as 1450461244432
,I/ActivityManager(  883): Killing 7166:com.google.android.music:main/u0a80 (adj 15): empty #7
,W/libprocessgroup(  883): failed to open /acct/uid_10080/pid_7166/cgroup.procs: No such file or directory
,I/WebViewFactory( 7310): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 7310): Time to load native libraries: 2 ms (timestamps 9552-9554)
,I/LibraryLoader( 7310): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 7310): Binding Chromium to main looper Looper (main, tid 1) {265a4be0}
,I/LibraryLoader( 7310): Expected native library version number "",actual native library version number ""
,I/chromium( 7310): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 7310): Initializing chromium process, singleProcess=true
,W/art     ( 7310): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 7310): ApplicationContext is null in ApplicationStatus
,W/chromium( 7310): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 7310): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 7310): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 7310): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 7310): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7310): Build Date: 10/28/14 Tue
I/Adreno-EGL( 7310): Local Branch: 
I/Adreno-EGL( 7310): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 7310): Local Patches: NONE
I/Adreno-EGL( 7310): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,W/AudioManagerAndroid( 7310): Requires BLUETOOTH permission
,I/NSApplication( 7310): Starting up...
,I/ActivityManager(  883): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=7379 uid=10052 gids={50052, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  883): Killing 7233:com.google.android.setupwizard/u0a35 (adj 15): empty #7
,I/ActivityManager(  883): Killing 7201:com.android.mms/u0a23 (adj 15): empty #8
,W/libprocessgroup(  883): failed to open /acct/uid_10035/pid_7233/cgroup.procs: No such file or directory
,W/libprocessgroup(  883): failed to open /acct/uid_10023/pid_7201/cgroup.procs: No such file or directory
,I/ActivityManager(  883): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7398 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  883): Killing 7252:com.google.android.apps.photos/u0a88 (adj 13): empty #7
,W/libprocessgroup(  883): failed to open /acct/uid_10088/pid_7252/cgroup.procs: No such file or directory
,W/ResourcesManager( 7398): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/ActivityManager(  883): Start proc android.process.acore for content provider com.android.providers.contacts/.ContactsProvider2: pid=7421 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,I/ActivityManager(  883): Killing 7310:com.google.android.apps.magazines/u0a81 (adj 13): empty #7
,I/ContactLocale( 7421): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,I/ActivityManager(  883): Killing 7271:com.google.android.talk/u0a70 (adj 15): empty #8
,W/libprocessgroup(  883): failed to open /acct/uid_10081/pid_7310/cgroup.procs: No such file or directory
,W/libprocessgroup(  883): failed to open /acct/uid_10070/pid_7271/cgroup.procs: No such file or directory
,D/EmailService.MarketingOptInSetter( 2647): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/GetNotificationsWS( 2647): bindWebServices(): registering our AIDL callback...
,I/SundryService( 2647): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/WaitableIntentService( 2647): ServiceHandler.handleMessage: mWaitCount=0
,D/GetNotificationsWS( 2647): onServiceConnected()
D/GetNotificationsWS( 2647): onServiceConnected(): Registered for remote service callbacks...
,D/GetNotificationsWS( 2647): unbindWebServices(): un-registering our AIDL callback...
,I/ActivityManager(  883): Start proc com.google.android.apps.photos for broadcast com.google.android.apps.photos/.jobqueue.JobServiceBroadcastReceiverInternal: pid=7455 uid=10088 gids={50088, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/PushService( 2647): started with background data enabled, making sure notification mechanism is enabled
,D/WearableService( 1740): callingUid 10016, callindPid: 1740
,D/LocationInitializer( 6487): Restart initialization of location
,E/MDM     ( 1740): [168] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/AuthorizationBluetoothService( 1740): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,V/GLSActivity( 1740): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  883): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=7485 uid=10080 gids={50080, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/GCoreFlp( 1740): No location to return for getLastLocation()
,W/FusedLocationProvider( 1740): location=null
,I/MusicStore( 7485): Database version: 120
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7485): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7485): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7485): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,W/ResourcesManager( 7485): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7485): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 7485): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 7485): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 7485): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@3483b44b: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7485): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 7485): GMSCore installation verified
,I/ConfigStore( 7485): Config Database version: 1
,I/MediaRouter( 7485): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 7485): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/NetworkMonitor( 7485): type=WIFI subType= reason=null isConnected=true
,I/NetworkMonitor( 7485): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  883): Start proc com.android.mms for broadcast com.android.mms/.transaction.MmsSystemEventReceiver: pid=7524 uid=10023 gids={50023, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/art     (  307): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 255us total 23.215ms
,I/art     (  307): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 243us total 19.424ms
,I/GHttpClientFactory( 7485): Using our fixed implementation of GMSCore's GoogleHttpClient
I/art     (  307): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 252us total 21.564ms
,I/art     (  883): Explicit concurrent mark sweep GC freed 12495(632KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 21MB/31MB, paused 1.637ms total 131.922ms
,I/GoogleURLConnFactory( 7485): Using platform SSLCertificateSocketFactory
,V/Mms     ( 7524): mnc/mcc: 
V/Mms     ( 7524): tag: int value: recipientLimit - 20
V/Mms     ( 7524): tag: int value: smsToMmsTextThreshold - 6
V/Mms     ( 7524): tag: int value: emergencySmsTimeout - 30
V/Mms     ( 7524): tag: int value: maxSubjectLength - 80
V/Mms     ( 7524): tag: bool value: smsForceShowEncodingMenu - true
V/Mms     ( 7524): tag: bool value: enableGroupMms - false
,V/Mms     ( 7524):  mUserAgent = MOT-XT1072/Mms-5.0,  mUaProfUrl = http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/ResourcesManager( 7524): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/ActivityManager(  883): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=7550 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  883): Killing 7379:com.android.chrome/u0a52 (adj 15): empty #7
,W/libprocessgroup(  883): failed to open /acct/uid_10052/pid_7379/cgroup.procs: No such file or directory
,D/PhoneMonitor( 7550): Register our PhoneStateListener
,D/MobileConnectivityChangeReceiver( 7550): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 7550): onReceive CONNECTIVITY_CHANGE networkType=1
,I/ActivityManager(  883): Killing 7398:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,W/libprocessgroup(  883): failed to open /acct/uid_10090/pid_7398/cgroup.procs: No such file or directory
,I/CheckinService( 6487): Checkin interval check for package: unspecified last checkin: 1450461244432 min interval config: 0 actual interval: 2534
,I/CheckinService( 6487): Checkin interval check for package: unspecified last checkin: 1450461244432 min interval config: 0 actual interval: 2539
,I/CheckinService( 6487): Checking schedule, now: 1450461246974 next: 1450461274404
,I/CheckinService( 6487): active receiver: disabled
,I/CheckinService( 6487): Checking schedule, now: 1450461247000 next: 1450461274404
I/CheckinService( 6487): active receiver: disabled
,I/ActivityManager(  883): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=7570 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,W/ResourcesManager( 7570): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/Babel_SMS( 7570): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 7570): MmsConfig.loadMmsSettings
,I/Babel_SMS( 7570): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
I/Babel_SMS( 7570): MmsConfig.loadFromDatabase
,E/Babel_SMS( 7570): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 7570): MmsConfig.loadFromResources
,E/Babel_SMS( 7570): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel_SMS( 7570): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/Settings( 7570): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 7570): startup - clean
,I/Babel   ( 7570): deleted: false for 0
,I/ActivityManager(  883): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7601 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/VideoCapabilities( 7570): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 7570): Unsupported mime audio/amr-wb-plus
,W/VideoCapabilities( 7570): Unsupported mime video/mpeg2
,I/VideoCapabilities( 7570): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 7570): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 7570): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 7570): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7570): Unrecognized profile 2130706433 for video/avc
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7601): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,I/vclib   ( 7570): onServiceConnected
,W/Babel   ( 7570): Attempted to change video mute state without an active call.
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7601): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7601): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7601): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,I/GAv4    ( 7601): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 7601):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 7601):   adb logcat -s GAv4
,W/GAv4    ( 7601): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,I/Babel   ( 7570): connection state changed from UNKNOWN to CONNECTED
,I/ActivityManager(  883): Killing 7421:android.process.acore/u0a7 (adj 15): empty #7
,W/GAv4    ( 7601): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 7601): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,W/libprocessgroup(  883): failed to open /acct/uid_10007/pid_7421/cgroup.procs: No such file or directory
,I/WebViewFactory( 7601): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 7601): Time to load native libraries: 2 ms (timestamps 2964-2966)
,I/LibraryLoader( 7601): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 7601): Binding Chromium to main looper Looper (main, tid 1) {265a4be0}
I/LibraryLoader( 7601): Expected native library version number "",actual native library version number ""
,I/chromium( 7601): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 7601): Initializing chromium process, singleProcess=true
,W/art     ( 7601): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 7601): ApplicationContext is null in ApplicationStatus
,W/chromium( 7601): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 7601): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 7601): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 7601): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 7601): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7601): Build Date: 10/28/14 Tue
I/Adreno-EGL( 7601): Local Branch: 
I/Adreno-EGL( 7601): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 7601): Local Patches: NONE
I/Adreno-EGL( 7601): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/NSApplication( 7601): Starting up...
,W/AudioManagerAndroid( 7601): Requires BLUETOOTH permission
,I/ActivityManager(  883): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=7674 uid=10052 gids={50052, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  883): Killing 7524:com.android.mms/u0a23 (adj 15): empty #7
,I/ActivityManager(  883): Killing 7485:com.google.android.music:main/u0a80 (adj 15): empty #8
,W/libprocessgroup(  883): failed to open /acct/uid_10023/pid_7524/cgroup.procs: No such file or directory
,W/libprocessgroup(  883): failed to open /acct/uid_10080/pid_7485/cgroup.procs: No such file or directory
,I/ActivityManager(  883): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7701 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  883): Killing 7550:com.google.android.setupwizard/u0a35 (adj 15): empty #7
,W/libprocessgroup(  883): failed to open /acct/uid_10035/pid_7550/cgroup.procs: No such file or directory
,W/ResourcesManager( 7701): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/ActivityManager(  883): Start proc android.process.acore for content provider com.android.providers.contacts/.ContactsProvider2: pid=7726 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,I/ActivityManager(  883): Killing 7570:com.google.android.talk/u0a70 (adj 15): empty #7
,I/ActivityManager(  883): Killing 7455:com.google.android.apps.photos/u0a88 (adj 15): empty #8
,I/ContactLocale( 7726): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,D/EmailService.MarketingOptInSetter( 2647): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
W/libprocessgroup(  883): failed to open /acct/uid_10070/pid_7570/cgroup.procs: No such file or directory
,W/libprocessgroup(  883): failed to open /acct/uid_10088/pid_7455/cgroup.procs: No such file or directory
,D/GetNotificationsWS( 2647): bindWebServices(): registering our AIDL callback...
,I/SundryService( 2647): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/GetNotificationsWS( 2647): onServiceConnected()
D/GetNotificationsWS( 2647): onServiceConnected(): Registered for remote service callbacks...
,D/WaitableIntentService( 2647): ServiceHandler.handleMessage: mWaitCount=0
,D/GetNotificationsWS( 2647): unbindWebServices(): un-registering our AIDL callback...
,I/PushService( 2647): started with background data enabled, making sure notification mechanism is enabled
V/AlarmManager(  883): done {709fa5, *walarm*:com.google.android.intent.action.GCM_RECONNECT} [6929ms]
,I/ActivityManager(  883): Start proc com.google.android.apps.photos for broadcast com.google.android.apps.photos/.jobqueue.JobServiceBroadcastReceiverInternal: pid=7753 uid=10088 gids={50088, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/InputReader(  883): Reconfiguring input devices.  changes=0x00000010
,W/ResourcesManager( 1555): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/BackupManagerService(  883): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/BackupManagerService(  883): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
I/BackupManagerService(  883): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/BackupManagerService(  883): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/BackupManagerService(  883): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@3861ae06
,I/GCoreNlp( 1740): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,I/Launcher( 1562): Deferring update until onResume
,I/art     ( 1740): Explicit concurrent mark sweep GC freed 89394(5MB) AllocSpace objects, 33(540KB) LOS objects, 40% free, 14MB/24MB, paused 1.477ms total 143.802ms
,I/ActivityManager(  883): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.util.GservicesChangedReceiver: pid=7785 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  883): Killing 7601:com.google.android.apps.magazines/u0a81 (adj 15): empty #7
,E/DataBuffer( 1740): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@195ae577)
,E/DataBuffer( 1740): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@2ea825e4)
E/DataBuffer( 1740): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@b7bca4d)
E/DataBuffer( 1740): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@1fe6c902)
E/DataBuffer( 1740): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@200e6213)
,W/libprocessgroup(  883): failed to open /acct/uid_10081/pid_7601/cgroup.procs: No such file or directory
,D/PhoneMonitor( 7785): Register our PhoneStateListener
,V/SetupWizard( 7785): Connected to Gservices successfully
,I/ActivityManager(  883): Killing 6989:com.google.android.gms.unstable/u0a16 (adj 15): empty #7
,W/libprocessgroup(  883): failed to open /acct/uid_10016/pid_6989/cgroup.procs: No such file or directory
,D/GCM     ( 1740): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/art     (  883): Explicit concurrent mark sweep GC freed 18169(910KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 21MB/31MB, paused 2.082ms total 132.383ms
,D/GCM     ( 1740): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/ActivityManager(  883): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.GmsPackageWatcher: pid=7805 uid=10039 gids={50039, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
,I/ActivityManager(  883): Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=7830 uid=10019 gids={50019, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  883): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver: pid=7847 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/ActivityManager(  883): Killing 7674:com.android.chrome/u0a52 (adj 15): empty #7
,I/art     (  307): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 245us total 22.512ms
,I/art     (  307): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 251us total 19.493ms
,I/art     (  307): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 246us total 21.071ms
,I/ActivityManager(  883): Killing 7701:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,W/libprocessgroup(  883): failed to open /acct/uid_10052/pid_7674/cgroup.procs: No such file or directory
,W/libprocessgroup(  883): failed to open /acct/uid_10090/pid_7701/cgroup.procs: No such file or directory
,W/ResourcesManager( 7847): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/Babel_SMS( 7847): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 7847): MmsConfig.loadMmsSettings
,I/Babel_SMS( 7847): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
I/Babel_SMS( 7847): MmsConfig.loadFromDatabase
,E/Babel_SMS( 7847): canonicalizeMccMnc: invalid mccmnc 
,I/Babel_SMS( 7847): MmsConfig.loadFromResources
,E/Babel_SMS( 7847): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 7847): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/Settings( 7847): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 7847): startup - clean
,I/Babel   ( 7847): deleted: false for 0
,I/ActivityManager(  883): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=7881 uid=10027 gids={50027, 9997, 1023, 3003, 1028, 1015} abi=armeabi-v7a
,W/VideoCapabilities( 7847): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 7847): Unsupported mime audio/amr-wb-plus
,W/VideoCapabilities( 7847): Unsupported mime video/mpeg2
,W/asset   ( 7881): Asset path /system/framework/com.motorola.gallery is neither a directory nor file (type=1).
W/ResourcesManager( 7881): Asset path '/system/framework/com.motorola.gallery' does not exist or contains no resources.
,W/ResourcesManager( 7881): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 7881): Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
,I/VideoCapabilities( 7847): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 7847): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 7847): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7847): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7847): Unrecognized profile 2130706433 for video/avc
,D/PackageBroadcastService( 6487): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
W/Launcher( 1562): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@1140211 new=com.google.android.velvet.VelvetApplication@1140211
,I/UpdateIcingCorporaServi( 7805): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,I/PackageBroadcastService( 6487): Null package name or gms related package.  Ignoreing.
,I/ActivityManager(  883): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=7912 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/Icing   ( 6487): updateResources: need to parse f{com.google.android.gms}
,W/ResourcesManager( 7912): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/vclib   ( 7847): onServiceConnected
,W/Babel   ( 7847): Attempted to change video mute state without an active call.
,I/UpdateIcingCorporaServi( 7805): UpdateCorporaTask done [took 161 ms] updated apps [took 161 ms] 
,I/ActivityManager(  883): Killing 7753:com.google.android.apps.photos/u0a88 (adj 15): empty #7
,W/ResourcesManager( 7847): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7847): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,W/libprocessgroup(  883): failed to open /acct/uid_10088/pid_7753/cgroup.procs: No such file or directory
,V/JNIHelp ( 7847): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/System  ( 7847): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7847): Installed default security provider GmsCore_OpenSSL
,I/ActivityManager(  883): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=7949 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  883): Killing 7785:com.google.android.setupwizard/u0a35 (adj 15): empty #7
,W/libprocessgroup(  883): failed to open /acct/uid_10035/pid_7785/cgroup.procs: No such file or directory
,D/Finsky  ( 7949): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/Finsky  ( 7949): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:33000 mC
,W/Settings( 7949): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/Settings( 7949): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/Finsky  ( 7949): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 7949): [1] Libraries$2.run: Finished loading 1 libraries.
,D/Ads     ( 7949): Skipping gmscore version check
,D/Finsky  ( 7949): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/Finsky  ( 7949): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/ActivityManager(  883): Killing 7830:com.google.android.partnersetup/u0a19 (adj 15): empty #7
,W/libprocessgroup(  883): failed to open /acct/uid_10019/pid_7830/cgroup.procs: No such file or directory
,I/Icing   ( 6487): Indexing 5905AFFF7E2D60BB1F87C8D56D40BA6B258244BF from com.google.android.gms
,D/Icing   ( 6487): Loaded CLD2 Version V2.0 - 20141016
,I/Icing   ( 6487): Indexing done 5905AFFF7E2D60BB1F87C8D56D40BA6B258244BF
,I/ActivityManager(  883): Killing 7881:com.motorola.MotGallery2/u0a27 (adj 15): empty #7
,W/libprocessgroup(  883): failed to open /acct/uid_10027/pid_7881/cgroup.procs: No such file or directory
,I/ActivityManager(  883): Killing 7805:com.google.android.googlequicksearchbox:search/u0a39 (adj 15): empty #7
,W/libprocessgroup(  883): failed to open /acct/uid_10039/pid_7805/cgroup.procs: No such file or directory
,D/BatteryService(  883): uevent={POWER_SUPPLY_TEMP=300, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4310848, SEQNUM=4493, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-5408, POWER_SUPPLY_CHARGE_COUNTER=-458, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2530): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2530): Disconnected process message: 10, size: 0
,I/CheckinService( 6487): Done disabling old GoogleServicesFramework version
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:33000 mC
,V/AlarmManager(  883): send {1973e850, *walarm*:android.content.syncmanager.SYNC_ALARM}
,V/AlarmManager(  883): done {1973e850, *walarm*:android.content.syncmanager.SYNC_ALARM} [4ms]
,I/MDMCTBK (  291): NetlinkHandler, power_supply subsys
,I/MDMCTBK (  291): NetlinkHandler, usbChargerStateChanged
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
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:32000 mC
,D/BatteryService(  883): uevent={POWER_SUPPLY_TEMP=289, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4310645, SEQNUM=4495, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-6510, POWER_SUPPLY_CHARGE_COUNTER=-491, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2530): Disconnected process message: 10, size: 0
,I/ClearcutLoggerApiImpl( 1740): disconnect managed GoogleApiClient
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:32000 mC
,V/AlarmManager(  883): send {2d66bae5, *walarm*:com.google.android.gms/.checkin.CheckinService$Receiver}
,V/AlarmManager(  883): send {25027a49, *walarm*:com.android.server.task.controllers.BatteryController.ACTION_CHARGING_STABLE}
,V/AlarmManager(  883): done {2d66bae5, *walarm*:com.google.android.gms/.checkin.CheckinService$Receiver} [20ms]
,V/AlarmManager(  883): done {25027a49, *walarm*:com.android.server.task.controllers.BatteryController.ACTION_CHARGING_STABLE} [23ms]
,I/CheckinService( 6487): Checkin interval check for package: unspecified last checkin: 1450461244432 min interval config: 0 actual interval: 39718
,I/CheckinService( 6487): Checking schedule, now: 1450461284165 next: 1450461274404
I/CheckinService( 6487): active receiver: enabled
,I/CheckinService( 6487): Preparing to send checkin request
I/EventLogService( 6487): Accumulating logs since 1450461239158
,I/CheckinRequestBuilder( 6487): Checkin reason type: 12 attempt count: 1
,E/ActivityThread( 6487): Failed to find provider info for com.google.android.wearable.settings
,V/GLSActivity( 1740): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1740): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  883): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=8023 uid=10016 gids={50016, 9997, 3003, 1028, 1015, 3002, 3001, 1005, 1007, 3007, 2001, 3006} abi=armeabi-v7a
,W/ResourcesManager( 8023): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 8023): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/MultiDex( 8023): VM with version 2.1.0 has multidex support
,I/MultiDex( 8023): install
I/MultiDex( 8023): VM has multidex support, MultiDex support library is disabled.
,V/JNIHelp ( 8023): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 8023): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 8023): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@38bd6b0: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 8023): Installed default security provider GmsCore_OpenSSL
,D/WearableService( 1740): callingUid 10016, callindPid: 1740
,E/MDM     ( 1740): [211] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/AuthorizationBluetoothService( 1740): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,D/LocationInitializer( 6487): Restart initialization of location
,V/GLSActivity( 1740): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GCoreFlp( 1740): No location to return for getLastLocation()
W/FusedLocationProvider( 1740): location=null
,I/art     ( 8023): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,I/art     ( 8023): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,D/NativeLibraryUtils( 8023): Install completed successfully. count=14 extracted=0
,D/WVCdm   (  294): Instantiating CDM.
,I/WVCdm   (  294): CdmEngine::OpenSession
I/WVCdm   (  294): Level3 Library Sep 25 2014 17:10:03
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
,E/QSEECOMAPI: (  294): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  294): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  294): App is not loaded in QSEE
,D/QSEECOMAPI: (  294): Loaded image: APP id = 3
,D/DrmWidevineDash(  294): Service_Initialize: ends! returns 0
,D/DrmWidevineDash(  294): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4fa3000
E/DrmWidevineDash(  294): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4fa3000
,D/DrmWidevineDash(  294): OEMCrypto_Initialize: ends! returns 0
D/DrmWidevineDash(  294): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  294): hlos api version =  9
D/DrmWidevineDash(  294): tz api version =  8
D/DrmWidevineDash(  294): OEMCrypto_APIVersion: ends! returns version 9
,D/DrmWidevineDash(  294): OEMCrypto_IsKeyboxValid: starts!
,D/DrmWidevineDash(  294): OEMCrypto_IsKeyboxValid: ends! returns 0
D/WVCdm   (  294): OEMCrypto_Initialize Level 1 success. I will use level 1.
D/DrmWidevineDash(  294): OEMCrypto_OpenSession: starts! SID=0xb136e960
D/DrmWidevineDash(  294): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  294): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  294): OEMCrypto_GetRandom: starts! randomData=0xb8f039e8, dataLength=8
D/DrmWidevineDash(  294): OEMCrypto_GetRandom: ends! returns 0
D/DrmWidevineDash(  294): OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb8f3b8f8, wrapped_rsa_key_length=1280
D/DrmWidevineDash(  294): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
I/WVCdm   (  294): CdmEngine::QueryKeyControlInfo
W/WVCdm   (  294): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  294): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  294): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  294): OEMCrypto_GetDeviceID: starts! deviceID=0xb8f5df40, idLength=0xb557e730
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
D/WVCdm   (  294): PrepareKeyRequest: nonce=859934053
D/DrmWidevineDash(  294): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb8e71d10
D/DrmWidevineDash(  294): message_length=1591, signature=0xb8e72350, signature_length=3042436884
,D/DrmWidevineDash(  294): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  294): CdmEngine::CloseSession
D/DrmWidevineDash(  294): OEMCrypto_CloseSession: starts! SID=1
,D/DrmWidevineDash(  294): OEMCrypto_CloseSession: ends! returns 0
I/WVCdm   (  294): L3 Terminate.
D/DrmWidevineDash(  294): OEMCrypto_Terminate: starts!
D/DrmWidevineDash(  294): Service_Uninitialize: starts!
D/QSEECOMAPI: (  294): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  294): QSEECom_shutdown_app, app_id = 3
D/DrmWidevineDash(  294): Service_Uninitialize: ends! returns 0x0
D/DrmWidevineDash(  294): OEMCrypto_Terminate: ends! returns 0
,I/dex2oat ( 8062): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=28 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,I/dex2oat ( 8062): dex2oat took 79.249ms (threads: 4)
,I/Adreno-EGL( 8023): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 8023): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 8023): Build Date: 10/28/14 Tue
I/Adreno-EGL( 8023): Local Branch: 
I/Adreno-EGL( 8023): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 8023): Local Patches: NONE
I/Adreno-EGL( 8023): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/Adreno-EGL( 8023): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 8023): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 8023): Build Date: 10/28/14 Tue
I/Adreno-EGL( 8023): Local Branch: 
I/Adreno-EGL( 8023): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 8023): Local Patches: NONE
I/Adreno-EGL( 8023): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/WVCdm   (  294): CdmEngine::OpenSession
I/WVCdm   (  294): Level3 Library Sep 25 2014 17:10:03
,W/WVCdm   (  294): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,D/DrmWidevineDash(  294): OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x13
D/DrmWidevineDash(  294): Service_Initialize: starts!
D/QSEECOMAPI: (  294): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  294): App is not loaded in QSEE
,E/QSEECOMAPI: (  294): Error::Cannot open the file /vendor/firmware/widevine.mdt
E/QSEECOMAPI: (  294): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  294): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  294): App is not loaded in QSEE
E/QSEECOMAPI: (  294): Error::Cannot open the file /system/etc/firmware/widevine.mdt
E/QSEECOMAPI: (  294): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  294): QSEECom_get_handle sb_length = 0x19000
,D/QSEECOMAPI: (  294): App is not loaded in QSEE
,D/QSEECOMAPI: (  294): Loaded image: APP id = 3
,D/DrmWidevineDash(  294): Service_Initialize: ends! returns 0
D/DrmWidevineDash(  294): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4fa3000
E/DrmWidevineDash(  294): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4fa3000
,D/DrmWidevineDash(  294): OEMCrypto_Initialize: ends! returns 0
D/DrmWidevineDash(  294): OEMCrypto_APIVersion: starts!
,D/DrmWidevineDash(  294): hlos api version =  9
,D/DrmWidevineDash(  294): tz api version =  8
D/DrmWidevineDash(  294): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  294): OEMCrypto_IsKeyboxValid: starts!
,D/DrmWidevineDash(  294): OEMCrypto_IsKeyboxValid: ends! returns 0
D/WVCdm   (  294): OEMCrypto_Initialize Level 1 success. I will use level 1.
,D/DrmWidevineDash(  294): OEMCrypto_OpenSession: starts! SID=0xb547e960
,D/DrmWidevineDash(  294): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  294): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  294): OEMCrypto_GetRandom: starts! randomData=0xb8f3b670, dataLength=8
D/DrmWidevineDash(  294): OEMCrypto_GetRandom: ends! returns 0
D/DrmWidevineDash(  294): OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb8e773c0, wrapped_rsa_key_length=1280
,D/DrmWidevineDash(  294): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
I/WVCdm   (  294): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  294): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  294): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  294): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  294): OEMCrypto_GetDeviceID: starts! deviceID=0xb8f5df60, idLength=0xbea4c2b0
,D/DrmWidevineDash(  294): OEMCrypto_GetDeviceID: ends! returns 0
D/DrmWidevineDash(  294): OEMCrypto_SupportsUsageTable: starts!
D/DrmWidevineDash(  294): OEMCrypto_SupportsUsageTable: is_supported = 1
D/DrmWidevineDash(  294): OEMCrypto_SupportsUsageTable: wv_app_version = 25
D/DrmWidevineDash(  294): OEMCrypto_SupportsUsageTable: ends! returns 0x0
D/DrmWidevineDash(  294): OEMCrypto_GetHDCPCapability: starts!
D/DrmWidevineDash(  294): OEMCrypto_GetHDCPCapability: ends! returns 0x0
D/DrmWidevineDash(  294): OEMCrypto_APIVersion: starts!
,D/DrmWidevineDash(  294): hlos api version =  9
,D/DrmWidevineDash(  294): tz api version =  8
D/DrmWidevineDash(  294): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  294): OEMCrypto_GenerateNonce: starts! SID=1
D/DrmWidevineDash(  294): OEMCrypto_GenerateNonce: ends! returns 0
D/WVCdm   (  294): PrepareKeyRequest: nonce=1489854520
D/DrmWidevineDash(  294): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb8e6d570
D/DrmWidevineDash(  294): message_length=1626, signature=0xb8e6dbd0, signature_length=3198468756
,D/DrmWidevineDash(  294): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  294): CdmEngine::CloseSession
,D/DrmWidevineDash(  294): OEMCrypto_CloseSession: starts! SID=1
D/DrmWidevineDash(  294): OEMCrypto_CloseSession: ends! returns 0
I/WVCdm   (  294): L3 Terminate.
D/DrmWidevineDash(  294): OEMCrypto_Terminate: starts!
,D/DrmWidevineDash(  294): Service_Uninitialize: starts!
D/QSEECOMAPI: (  294): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  294): QSEECom_shutdown_app, app_id = 3
D/DrmWidevineDash(  294): Service_Uninitialize: ends! returns 0x0
D/DrmWidevineDash(  294): OEMCrypto_Terminate: ends! returns 0
,I/Adreno-EGL( 8023): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 8023): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 8023): Build Date: 10/28/14 Tue
I/Adreno-EGL( 8023): Local Branch: 
I/Adreno-EGL( 8023): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 8023): Local Patches: NONE
I/Adreno-EGL( 8023): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/Adreno-EGL( 8023): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 8023): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 8023): Build Date: 10/28/14 Tue
I/Adreno-EGL( 8023): Local Branch: 
I/Adreno-EGL( 8023): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 8023): Local Patches: NONE
I/Adreno-EGL( 8023): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/CheckinRequestBuilder( 6487): Classify the device as Phone.
,I/art     (  883): Explicit concurrent mark sweep GC freed 16691(829KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 21MB/31MB, paused 1.650ms total 120.215ms
,I/CheckinTask( 6487): Sending checkin request (9448 bytes)
,I/CheckinRequestBuilder( 6487): Checkin reason type: 12 attempt count: 1
,E/ActivityThread( 6487): Failed to find provider info for com.google.android.wearable.settings
,I/CheckinRequestBuilder( 6487): Classify the device as Phone.
,I/CheckinTask( 6487): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 6487): Checking schedule, now: 1450461287328 next: 1451062424316
I/CheckinService( 6487): active receiver: disabled
,D/CheckinService( 6487): Recording last checkin time for package unspecified as 1450461287339
,I/ActivityManager(  883): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.util.GservicesChangedReceiver: pid=8089 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,D/PhoneMonitor( 8089): Register our PhoneStateListener
,V/SetupWizard( 8089): Connected to Gservices successfully
,D/GCM     ( 1740): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/ActivityManager(  883): Killing 7912:com.google.android.apps.plus/u0a90 (adj 13): empty #7
,I/ActivityManager(  883): Killing 7726:android.process.acore/u0a7 (adj 15): empty #8
,W/libprocessgroup(  883): failed to open /acct/uid_10090/pid_7912/cgroup.procs: No such file or directory
,W/libprocessgroup(  883): failed to open /acct/uid_10007/pid_7726/cgroup.procs: No such file or directory
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:32000 mC
,I/InputReader(  883): Reconfiguring input devices.  changes=0x00000010
,I/ActivityManager(  883): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.GmsPackageWatcher: pid=8123 uid=10039 gids={50039, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
,D/BackupManagerService(  883): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/BackupManagerService(  883): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,I/BackupManagerService(  883): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,I/GCoreNlp( 1740): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,V/BackupManagerService(  883): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/BackupManagerService(  883): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@bb86d93
,I/Launcher( 1562): Deferring update until onResume
,I/ActivityManager(  883): Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=8152 uid=10019 gids={50019, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  883): Start proc android.process.acore for broadcast com.android.providers.contacts/.PackageIntentReceiver: pid=8174 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,I/ActivityManager(  883): Killing 7949:com.android.vending/u0a32 (adj 15): empty #7
,W/libprocessgroup(  883): failed to open /acct/uid_10032/pid_7949/cgroup.procs: No such file or directory
,W/ResourcesManager( 7847): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 7847): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/ContactLocale( 8174): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,I/ActivityManager(  883): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=8201 uid=10027 gids={50027, 9997, 1023, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  883): Killing 8089:com.google.android.setupwizard/u0a35 (adj 15): empty #7
,W/libprocessgroup(  883): failed to open /acct/uid_10035/pid_8089/cgroup.procs: No such file or directory
,W/asset   ( 8201): Asset path /system/framework/com.motorola.gallery is neither a directory nor file (type=1).
W/ResourcesManager( 8201): Asset path '/system/framework/com.motorola.gallery' does not exist or contains no resources.
W/ResourcesManager( 8201): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,W/ResourcesManager( 8201): Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
,D/PackageBroadcastService( 6487): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 6487): Null package name or gms related package.  Ignoreing.
,W/Launcher( 1562): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@1140211 new=com.google.android.velvet.VelvetApplication@1140211
,I/UpdateIcingCorporaServi( 8123): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,I/Icing   ( 6487): updateResources: need to parse f{com.google.android.gms}
,I/ActivityManager(  883): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=8230 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,W/ResourcesManager( 8230): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/UpdateIcingCorporaServi( 8123): UpdateCorporaTask done [took 143 ms] updated apps [took 143 ms] 
,I/ActivityManager(  883): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=8255 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/art     (  307): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 242us total 21.236ms
,I/art     (  307): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 245us total 19.396ms
,I/art     (  307): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 285us total 26.206ms
,I/ActivityManager(  883): Killing 8023:com.google.android.gms.unstable/u0a16 (adj 15): empty #7
,W/libprocessgroup(  883): failed to open /acct/uid_10016/pid_8023/cgroup.procs: No such file or directory
,D/Finsky  ( 8255): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/Finsky  ( 8255): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 8255): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 8255): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/Finsky  ( 8255): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 8255): [1] Libraries$2.run: Finished loading 1 libraries.
,D/Ads     ( 8255): Skipping gmscore version check
,D/Finsky  ( 8255): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/Finsky  ( 8255): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/ActivityManager(  883): Killing 8152:com.google.android.partnersetup/u0a19 (adj 15): empty #7
,W/libprocessgroup(  883): failed to open /acct/uid_10019/pid_8152/cgroup.procs: No such file or directory
,I/Icing   ( 6487): Indexing 5905AFFF7E2D60BB1F87C8D56D40BA6B258244BF from com.google.android.gms
,I/Icing   ( 6487): Indexing done 5905AFFF7E2D60BB1F87C8D56D40BA6B258244BF
,I/ActivityManager(  883): Killing 8201:com.motorola.MotGallery2/u0a27 (adj 15): empty #7
,W/libprocessgroup(  883): failed to open /acct/uid_10027/pid_8201/cgroup.procs: No such file or directory
,D/BatteryService(  883): uevent={POWER_SUPPLY_TEMP=286, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4310066, SEQNUM=4515, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-5408, POWER_SUPPLY_CHARGE_COUNTER=-530, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2530): Disconnected process message: 10, size: 0
,I/ActivityManager(  883): Killing 7847:com.google.android.talk/u0a70 (adj 15): empty #7
,W/libprocessgroup(  883): failed to open /acct/uid_10070/pid_7847/cgroup.procs: No such file or directory
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:31000 mC
,V/AlarmManager(  883): send {62c4399, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  883): send {1973e850, *walarm*:android.content.syncmanager.SYNC_ALARM}
,V/AlarmManager(  883): done {1973e850, *walarm*:android.content.syncmanager.SYNC_ALARM} [12ms]
,V/AlarmManager(  883): done {62c4399, *alarm*:android.intent.action.TIME_TICK} [48ms]
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:31000 mC
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
I/MDMCTBK (  291): NetlinkHandler, power_supply subsys
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
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:31000 mC
,I/MDMCTBK (  291): NetlinkHandler, power_supply subsys
,I/MDMCTBK (  291): NetlinkHandler, usbChargerStateChanged
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
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:31000 mC
,I/MDMCTBK (  291): NetlinkHandler, power_supply subsys
,I/MDMCTBK (  291): NetlinkHandler, usbChargerStateChanged
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
,D/BatteryService(  883): uevent={POWER_SUPPLY_TEMP=277, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4309911, SEQNUM=4517, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-2704, POWER_SUPPLY_CHARGE_COUNTER=-625, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2530): Disconnected process message: 10, size: 0
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:30000 mC
,I/jxcore-log( 6633): Connected to the server!
I/jxcore-log( 6633): 
,I/chromium( 6633): [INFO:CONSOLE(63)] "logCallback Connected to the server", source: file:///android_asset/www/js/thali_main.js (63)
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:30000 mC
,I/ClearcutLoggerApiImpl( 1740): disconnect managed GoogleApiClient
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:30000 mC
,I/Process ( 2647): Sending signal. PID: 2647 SIG: 9
,I/SFPerfTracer(  278):      triggers: (rate: 0:0) (0 sw vsyncs) (0 skipped) (0:300 vsyncs) (1:1240)
,W/InputMethodManagerService(  883): Got RemoteException sending setActive(false) notification to pid 2647 uid 10000
,W/IInputConnectionWrapper( 6633): showStatusIcon on inactive InputConnection
,I/Keyboard.Facilitator( 1417): onFinishInput()
,I/ActivityManager(  883): Process com.motorola.ccc (pid 2647) has died
,W/ActivityManager(  883): Scheduling restart of crashed service com.motorola.ccc.devicemanagement/.DeviceManagementNotifierService in 1000ms
W/ActivityManager(  883): Scheduling restart of crashed service com.motorola.ccc.checkin/com.motorola.blur.service.blur.BlurServiceMother in 11000ms
W/ActivityManager(  883): Scheduling restart of crashed service com.motorola.ccc.notification/com.motorola.blur.service.blur.BlurServiceMother in 11000ms
W/ActivityManager(  883): Scheduling restart of crashed service com.motorola.ccc.ota/.env.OtaService in 21000ms
W/ActivityManager(  883): Scheduling restart of crashed service com.motorola.ccc.checkin/.CheckinService in 31000ms
W/ActivityManager(  883): Scheduling restart of crashed service com.motorola.ccc.devicemanagement/com.motorola.blur.service.blur.BlurServiceMother in 41000ms
,I/ActivityManager(  883): Start proc com.motorola.ccc for service com.motorola.ccc.devicemanagement/.DeviceManagementNotifierService: pid=8342 uid=10000 gids={50000, 9997, 3003, 3001, 1007, 9004, 1028, 1015, 2001} abi=armeabi-v7a
,I/art     (  883): Explicit concurrent mark sweep GC freed 20049(1067KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 21MB/31MB, paused 1.563ms total 115.984ms
,W/ResourcesManager( 8342): Asset path '/system/framework/protobufs-2.3.0.jar' does not exist or contains no resources.
,W/ResourcesManager( 8342): Asset path '/system/framework/protobufs-2.3.0.jar' does not exist or contains no resources.
,W/ResourcesManager( 8342): Asset path '/system/framework/protobufs-2.3.0.jar' does not exist or contains no resources.
,I/CCECheckinProvider( 8342): EventInsertThread started
,D/CCECheckinProvider( 8342): Current Event Count is : 0
,I/BSUtils ( 8342): device type: MOTO
,D/CCE     ( 8342): blur version: Blur_Version.22.21.28.thea_reteu.reteuall.en.EU
,I/util.Log( 8342): logging to checkin skipped - tag(MMApiWSBase) is black-listed
,D/MMApiWSBase( 8342): MMApiWSBase configured as mOAuthToken=null, mOAuthTokenSecret=null, mSocketTimeout=30000, mTimeSkew=0, mChunkSize=8192
,I/art     ( 1478): Explicit concurrent mark sweep GC freed 57024(3MB) AllocSpace objects, 39(1277KB) LOS objects, 39% free, 7MB/12MB, paused 956us total 63.374ms
,D/CCE     ( 8342): AppWSProxy created ...
,D/PollingManager( 8342): PollingManagerService()
D/PollingManager( 8342): init()
,D/CCE     ( 8342): Persistent intent sent from notif.
D/UserAuthService( 8342): init()
D/CCCMainStrtRcvr( 1478): starting CCCMain Service
W/ContextImpl( 1478): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1820 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.motorola.ccc.main.StartUpReceiver.onReceive:21 android.app.ActivityThread.handleReceiver:2611 
,I/CCCMainStrtRcvr( 1478): CCCMain Service started: {com.motorola.ccc.mainplm/com.motorola.ccc.main.CCCMainService}
W/ContextImpl( 1478): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1884 android.content.ContextWrapper.bindService:538 com.motorola.ccc.main.CCCMainService.doBindService:104 com.motorola.ccc.main.CCCMainService.onStartCommand:82 android.app.ActivityThread.handleServiceArgs:2896 
,I/UserAuthService( 8342): init(): account exists: false
,D/MMApiProvisionService( 8342): Configuring max forced login attempts to 50
,D/MMApiProvisionService( 8342): MMApiProvisionService created...
,D/MMApiProvisionService( 8342): isDeviceProvisioned: deviceId = 2072049230914535424
,D/CCE     ( 8342): sending request: (update_device) to MMApiprovisionService
I/MMApiProvisionService( 8342): createDeviceIdOrLogin update_device
,D/Checkin ( 8342): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiProvisionService( 8342): Not proxy app, so login/provision not allowed
,D/CCE     ( 8342): onBind() called: com.motorola.blur.service.blur.Actions.BIND_WSPROXY_SVC
,I/System.out( 8342): 18:57:05,064 |-WARN in ch.qos.logback.classic.LoggerContext[default] - No config in SD card
I/System.out( 8342): 18:57:05,069 |-INFO in ch.qos.logback.classic.LoggerContext[default] - Found resource [AndroidManifest.xml] at [jar:file:/system/priv-app/3c_ota/3c_ota.apk!/AndroidManifest.xml]
I/System.out( 8342): 18:57:05,164 |-INFO in ch.qos.logback.classic.LoggerContext[default] - Could NOT find resource [assets/logback-test.xml]
I/System.out( 8342): 18:57:05,167 |-INFO in ch.qos.logback.classic.LoggerContext[default] - Found resource [assets/logback.xml] at [jar:file:/system/priv-app/3c_ota/3c_ota.apk!/assets/logback.xml]
I/System.out( 8342): 18:57:05,171 |-INFO in ch.qos.logback.core.joran.spi.ConfigurationWatchList@2caa9ffe - URL [jar:file:/system/priv-app/3c_ota/3c_ota.apk!/assets/logback.xml] is not of type file
I/System.out( 8342): 18:57:05,198 |-INFO in ch.qos.logback.classic.joran.action.ConfigurationAction - debug attribute not set
I/System.out( 8342): 18:57:05,198 |-INFO in ch.qos.logback.core.joran.action.AppenderAction - About to instantiate appender of type [ch.qos.logback.classic.android.LogcatAppender]
I/System.out( 8342): 18:57:05,201 |-INFO in ch.qos.logback.core.joran.action.AppenderAction - Naming appender as [LOGCAT]
I/System.out( 8342): 18:57:05,208 |-INFO in ch.qos.logback.core.joran.action.NestedComplexPropertyIA - Assuming default type [ch.qos.logback.classic.encoder.PatternLayoutEncoder] for [tagEncoder] property
I/System.out( 8342): 18:57:05,234 |-INFO in ch.qos.logback.core.joran.action.NestedComplexPropertyIA - Assuming default type [ch.qos.logback.classic.encoder.PatternLayoutEncoder] for [encoder] property
I/System.out( 8342): 18:57:05,243 |-INFO in ch.qos.logback.core.joran.action.AppenderAction - About to instantiate appender of type [com.motorola.ccc.ota.checkin.CheckinAppender]
I/System.out( 8342): 18:57:05,244 |-INFO in ch.qos.logback.core.joran.action.AppenderAction - Naming appender as [CHECKIN]
I/System.out( 8342): 18:57:05,247 |-INFO in ch.qos.logback.core.joran.action.NestedComplexPropertyIA - Assuming default type [ch.qos.logback.classic.encoder.PatternLayoutEncoder] for [tagEncoder] property
I/System.out( 8342): 18:57:05,259 |-INFO in ch.qos.logback.core.joran.action.NestedComplexPropertyIA - Assuming default type [ch.qos.logback.classic.encoder.PatternLayoutEncoder] for [encoder] property
I/System.out( 8342): 18:57:05,268 |-INFO in ch.qos.logback.classic.joran.action.RootLoggerAction - Setting level of ROOT logger to TRACE
I/System.out( 8342): 18:57:05,268 |-INFO in ch.qos.logback.core.joran.action.AppenderRefAction - Attaching appender named [LOGCAT] to Logger[ROOT]
I/System.out( 8342): 18:57:05,268 |-INFO in ch.qos.logback.core.joran.action.AppenderRefAction - Attaching appender named [CHECKIN] to Logger[ROOT]
I/System.out( 8342): 18:57:05,268 |-INFO in ch.qos.logback.classic.joran.action.ConfigurationAction - End of configuration.
I/System.out( 8342): 18:57:05,269 |-INFO in ch.qos.logback.classic.joran.JoranConfigurator@3dd9b35f - Registering current configuration as safe fallback point
,D/OtaApp  ( 8342): [debug] > Launching ota service
,I/OtaApp  ( 8342): [info] > OtaService.saveOverlaySettings(): saving :  value : 
,D/Checkin ( 8342): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 8342): [debug] > AndroidPollingManager.init, binding to Polling Manager Service
,W/ContextImpl( 8342): Implicit intents with startService are not safe: Intent { act=com.motorola.ccc.ota.pm.BIND_POLLINGMANAGER_WSPROXY_SVC } android.content.ContextWrapper.bindService:538 com.motorola.ccc.ota.env.AndroidPollingManager.init:79 com.motorola.ccc.ota.env.AndroidPollingManager.<init>:74 
,D/OtaApp  ( 8342): [debug] > CusSM.CusSM: constructing a CusSM object
,D/OtaApp  ( 8342): [debug] > SDCardUpgradeSource.SDCardUpgradeSource object is constructed
,D/OtaApp  ( 8342): [debug] > TetheredUpgradeSource.TetheredUpgradeSource object is constructed
,D/OtaApp  ( 8342): [debug] > FotaUpgradeSource.FotaUpgradeSource object is constructed
,D/OtaApp  ( 8342): [debug] > CusAndroidDB.CusAndroidDB
,D/OtaApp  ( 8342): [debug] > PollingManagerService()
,D/OtaApp  ( 8342): [debug] > PollingManagerService init()
,I/art     ( 8342): Background sticky concurrent mark sweep GC freed 30064(1607KB) AllocSpace objects, 9(144KB) LOS objects, 10% free, 10MB/11MB, paused 6.997ms total 70.518ms
,W/MotorolaSettings( 8342): no such table to get this URI = privacy_droid_blast
W/System.err( 8342): java.lang.Exception
,W/System.err( 8342): 	at com.motorola.android.provider.MotorolaSettings.getUriFor(MotorolaSettings.java:322)
W/System.err( 8342): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 8342): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 8342): 	at com.motorola.ccc.checkin.MotorolaSettings.getUriFor(MotorolaSettings.java:143)
,W/System.err( 8342): 	at com.motorola.ccc.checkin.PrivacyHelper.registerObservers(PrivacyHelper.java:141)
,W/System.err( 8342): 	at com.motorola.ccc.checkin.PrivacyHelper.<init>(PrivacyHelper.java:119)
W/System.err( 8342): 	at com.motorola.ccc.checkin.BcsConfigAndroid.<init>(BcsConfigAndroid.java:241)
W/System.err( 8342): 	at com.motorola.ccc.checkin.BcsPlatformAndroid.<init>(BcsPlatformAndroid.java:137)
W/System.err( 8342): 	at com.motorola.ccc.checkin.CheckinService.onCreate(CheckinService.java:17)
W/System.err( 8342): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2763)
W/System.err( 8342): 	at android.app.ActivityThread.access$1800(ActivityThread.java:148)
,W/System.err( 8342): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1375)
W/System.err( 8342): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 8342): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 8342): 	at android.app.ActivityThread.main(ActivityThread.java:5312)
W/System.err( 8342): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 8342): 	,at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 8342): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:901)
W/System.err( 8342): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:696)
,I/BSUtils ( 8342): device type: MOTO
,I/global frequency( 8342): service created
,D/Checkin ( 8342): publish the event [tag = MOT_CHECKIN event name = LOG]
,I/global frequency( 8342): service started
,D/Checkin ( 8342): publish the event [tag = MOT_CHECKIN event name = LOG]
,D/PollingManager( 8342): connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/PollingManager( 8342): now: 390603 ,futureTime: 9223372036854775807
,D/OtaApp  ( 8342): [debug] > onBind() called: com.motorola.ccc.ota.pm.BIND_POLLINGMANAGER_WSPROXY_SVC
,D/OtaApp  ( 8342): [debug] > pollingManagerService, connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/OtaApp  ( 8342): [debug] > PollingManagerService, now: 390623 ,futureTime: 9223372036854775807
,D/OtaApp  ( 8342): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.ccc.ota.START_ACTION
I/OtaApp  ( 8342): [info] > AndroidClientUpgradeService.handleIntent: starting CusSM
,D/Checkin ( 8342): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 8342): [debug] > CusSM.onStart
,D/OtaApp  ( 8342): [debug] > FotaUpgradeSource.plugin_init: sending Fota Initialization intent
,W/ContextImpl( 8342): Implicit intents with startService are not safe: Intent { act=com.motorola.android.fota.FOTA_INITIALIZATION } android.content.ContextWrapper.startService:515 com.motorola.ccc.ota.env.AndroidFotaInterface.sendFotaInitializationIntent:223 com.motorola.ccc.ota.env.AndroidENV$FotaServices.sendFotaInitializationIntent:502 
,W/ActivityManager(  883): Unable to start service Intent { act=com.motorola.android.fota.FOTA_INITIALIZATION } U=0: not found
,D/OtaApp  ( 8342): [debug] > CusFileUtils.getResultsFile examining /cache/ lost+found
D/OtaApp  ( 8342): [debug] > CusFileUtils.getResultsFile examining /cache/ backup
I/OtaApp  ( 8342): [info] > CusSM.checkForUpgradeCompleted: no upgrade result files found
,D/CCE     ( 8342): blur version: Blur_Version.22.21.28.thea_reteu.reteuall.en.EU
,D/Checkin ( 8342): publish the event [tag = MOT_OTA event name = LOG]
,I/OtaApp  ( 8342): [info] > CusSM.cleanupSpuriousFiles: no spurious files found
,D/Checkin ( 8342): publish the event [tag = MOT_OTA event name = LOG]
,I/OtaApp  ( 8342): [info] > CusSM.resetState
D/Checkin ( 8342): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 8342): [debug] > SDCardUpgradeSource.checkForUpdate: path /storage/emulated/0 [AddOnInfo: sdcard initiated on start]
I/OtaApp  ( 8342): [info] > alternate storage exists but not readable,so return default location
,D/Checkin ( 8342): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 8342): [debug] > SDCardUpgradeSource.checkForUpdate: looking for upgrade files in /storage/emulated/0/
,D/OtaApp  ( 8342): [debug] > SDCardUpgradeSource.checkForUpdate: no upgrade files found on sd card
,E/OtaApp  ( 8342): [error] > CusSM.wifiDiscoverySanityCheck failed: wifi discover time is not set nothing to process
,D/Checkin ( 8342): publish the event [tag = MOT_OTA event name = LOG]
,E/OtaApp  ( 8342): [error] > CusSM.forceUpgradeTimerSanityCheck failed: force upgrade time is not set nothing to process
,D/Checkin ( 8342): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 8342): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,D/OtaApp  ( 8342): [debug] > CusSM.runStateMachine: getVersions's version Blur_Version.22.21.28.thea_reteu.reteuall.en.EU; getDescription's versionBlur_Version.22.21.28.thea_reteu.reteuall.en.EU
,I/OtaApp  ( 8342): [info] > CusSM.runStateMachine: found version Blur_Version.22.21.28.thea_reteu.reteuall.en.EU in database with state (RequestPermission)
,D/Checkin ( 8342): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 8342): [debug] > CusSM.runStateMachine: server told to :continue
,D/OtaApp  ( 8342): [debug] > CusSM.runStateMachine: user is being notified for version Blur_Version.22.21.28.thea_reteu.reteuall.en.EU
,D/OtaApp  ( 8342): [debug] > CusSM.runStateMachine: getDownloadOptStartStopTime text null
,D/OtaApp  ( 8342): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,D/MMApiWSBase( 8342): MMApiWSBase configured as mOAuthToken=null, mOAuthTokenSecret=null, mSocketTimeout=30000, mTimeSkew=0, mChunkSize=8192
,I/art     (  883): Explicit concurrent mark sweep GC freed 7976(405KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 20MB/31MB, paused 1.460ms total 111.803ms
,I/art     ( 1478): Explicit concurrent mark sweep GC freed 4633(201KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 7MB/12MB, paused 473us total 26.632ms
,D/CCE     ( 8342): AppWSProxy created ...
,D/PollingManager( 8342): PollingManagerService()
,D/PollingManager( 8342): init()
,D/UserAuthService( 8342): init()
,I/UserAuthService( 8342): init(): account exists: false
,D/MMApiProvisionService( 8342): Configuring max forced login attempts to 50
,D/MMApiProvisionService( 8342): MMApiProvisionService created...
,D/MMApiProvisionService( 8342): isDeviceProvisioned: deviceId = 2072049230914535424
,D/CCE     ( 8342): sending request: (update_device) to MMApiprovisionService
I/MMApiProvisionService( 8342): createDeviceIdOrLogin update_device
,D/Checkin ( 8342): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiProvisionService( 8342): Not proxy app, so login/provision not allowed
,D/CCE     ( 8342): Checkin is enabled ... launching it.
,D/CCE     ( 8342): onBind() called: com.motorola.blur.service.blur.Actions.BIND_WSPROXY_SVC
,I/global frequency( 8342): BcsTimer.setTimer(317222, 21600000)
,D/Checkin ( 8342): publish the event [tag = MOT_CHECKIN event name = LOG]
,D/Central_PollingManager( 1478): registerApp(): Checkin
,D/Central_PollingManager( 1478): registerApp(): Checkin already registered.
D/Central_PollingManager( 1478): modifyApp(): Checkin
D/Central_PollingManager( 1478): calculateShortestInterval(): shortest interval is 21600000
D/Central_PollingManager( 1478): Polling alarm set to expire at: 708236 Current Time: 391014
,D/OtaApp  ( 8342): [debug] > AndroidPollingManager, successfully bound to Polling Manger Service...
,D/OtaApp  ( 8342): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.ccc.ota.pm.POLLINGMGR_CONNECTIVITY
,D/PollingManager( 8342): connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/OtaApp  ( 8342): [debug] > CusSM.onRadioUp
D/PollingManager( 8342): now: 391030 ,futureTime: 9223372036854775807
D/OtaApp  ( 8342): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,D/OtaApp  ( 8342): [debug] > CusSM.runStateMachine: getVersions's version Blur_Version.22.21.28.thea_reteu.reteuall.en.EU; getDescription's versionBlur_Version.22.21.28.thea_reteu.reteuall.en.EU
,I/OtaApp  ( 8342): [info] > CusSM.runStateMachine: found version Blur_Version.22.21.28.thea_reteu.reteuall.en.EU in database with state (RequestPermission)
,D/GetNotificationsWS( 8342): bindWebServices(): registering our AIDL callback...
D/Checkin ( 8342): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 8342): [debug] > CusSM.runStateMachine: server told to :continue
,D/OtaApp  ( 8342): [debug] > CusSM.runStateMachine: user is being notified for version Blur_Version.22.21.28.thea_reteu.reteuall.en.EU
,D/OtaApp  ( 8342): [debug] > CusSM.runStateMachine: getDownloadOptStartStopTime text null
,D/OtaApp  ( 8342): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,I/SundryService( 8342): onHandleIntent(): action=com.motorola.notification.REGISTRATION
I/SundryService( 8342): Received registration
,D/Checkin ( 8342): publish the event [tag = MOT_CCE_STATS event name = Registration]
,D/CCE     ( 8342): App Checkin requested CCE to send settings
,E/SQLiteLog( 8342): (284) automatic index on registration(APP_ID)
,D/SundryService( 8342): sendNewNotificationsIfMissing: unprocessedApps=[]
,D/OtaApp  ( 8342): [debug] > AndroidPollingManager.handleIntent: com.motorola.blur.service.blur.upgrade_poll
,W/SundryService( 8342): No apps found to updates
W/SundryService( 8342): No apps found to send notifications
I/OtaApp  ( 8342): [info] > Next Polling is scheduled at 1033 mins from now
,D/Checkin ( 8342): publish the event [tag = MOT_OTA event name = LOG]
,D/WaitableIntentService( 8342): ServiceHandler.handleMessage: mWaitCount=0
,D/OtaApp  ( 8342): [debug] > PollingManagerService, registerApp(): cUsPollingService
,D/OtaApp  ( 8342): [debug] > PollingManagerService, registerApp(): shortest interval is 62019000
D/OtaApp  ( 8342): [debug] > Polling alarm set to expire at: 62410079 Current Time: 391082
,D/CCE     ( 8342): onBind() called: com.motorola.blur.service.blur.Actions.BIND_WSPROXY_SVC
,D/CCE     ( 8342): App Checkin requested CCE to send settings
,D/GetNotificationsWS( 8342): unbindWebServices(): un-registering our AIDL callback...
,D/CCE     ( 8342): App Checkin requested CCE to send settings
,I/BSUtils ( 8342): device type: MOTO
,D/OtaApp  ( 8342): [debug] > Receive intent: com.motorola.blur.service.blur.Actions.UPGRADE_UPDATE_NOTIFICATION
,D/OtaApp  ( 8342): [debug] > UpdateReceiver: Received true from doSanityCheck.
,D/OtaApp  ( 8342): [debug] > In cancelAnyPendingIntentSetPreviously
,I/ActivityManager(  883): START u0 {act=com.motorola.blur.service.blur.Actions.UPGRADE_UPDATE_NOTIFICATION flg=0x30000000 cmp=com.motorola.ccc.ota/.ui.DownloadActivity (has extras)} from uid 10000 on display 0
,W/ContextImpl( 1478): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,W/ContextImpl( 1478): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,W/ResourceType( 8342): Failure getting entry for 0x7f0800a7 (t=7 e=167) (error -75)
,W/PackageManager( 8342): Failure retrieving text 0x7f0800a7 in package com.motorola.ccc.ota
W/PackageManager( 8342): android.content.res.Resources$NotFoundException: String resource ID #0x7f0800a7
W/PackageManager( 8342): 	at android.content.res.Resources.getText(Resources.java:274)
W/PackageManager( 8342): 	at android.app.ApplicationPackageManager.getText(ApplicationPackageManager.java:1154)
W/PackageManager( 8342): 	at android.content.pm.ComponentInfo.loadLabel(ComponentInfo.java:85)
W/PackageManager( 8342): 	at android.app.ActivityThread.performLaunchActivity(ActivityThread.java:2244)
W/PackageManager( 8342): 	at android.app.ActivityThread.handleLaunchActivity(ActivityThread.java:2388)
W/PackageManager( 8342): 	at android.app.ActivityThread.access$800(ActivityThread.java:148)
W/PackageManager( 8342): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1292)
W/PackageManager( 8342): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/PackageManager( 8342): 	at android.os.Looper.loop(Looper.java:135)
W/PackageManager( 8342): 	at android.app.ActivityThread.main(ActivityThread.java:5312)
W/PackageManager( 8342): 	at java.lang.reflect.Method.invoke(Native Method)
W/PackageManager( 8342): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/PackageManager( 8342): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:901)
W/PackageManager( 8342): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:696)
I/art     ( 1478): Explicit concurrent mark sweep GC freed 3900(164KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 7MB/12MB, paused 600us total 34.401ms
,I/art     ( 8342): Explicit concurrent mark sweep GC freed 18746(1256KB) AllocSpace objects, 7(112KB) LOS objects, 39% free, 10MB/17MB, paused 1.038ms total 74.961ms
,D/OtaApp  ( 8342): [debug] > DownloadActivity, FormattedText
,I/OtaApp  ( 8342): [info] > DownloadActivity, handling (Blur_Version.22.46.12.thea_reteu.reteuall.en.EU) from ( upgrade)
D/Checkin ( 8342): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 8342): [debug] > cancelling the previous pending intent set for download later
I/OtaApp  ( 8342): [info] > next automatic download prompt (serverAnnoy)  is scheduled in : 60 mins.
,D/Checkin ( 8342): publish the event [tag = MOT_OTA event name = LOG]
,D/OpenGLRenderer( 8342): Render dirty regions requested: true
,D/Atlas   ( 8342): Validating map...
,I/Adreno-EGL( 8342): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 8342): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 8342): Build Date: 10/28/14 Tue
I/Adreno-EGL( 8342): Local Branch: 
I/Adreno-EGL( 8342): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 8342): Local Patches: NONE
I/Adreno-EGL( 8342): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/OpenGLRenderer( 8342): Initialized EGL, version 1.4
,D/OpenGLRenderer( 8342): Enabling debug mode 0
,I/global frequency( 8342): service started
,D/Checkin ( 8342): publish the event [tag = MOT_CHECKIN event name = LOG]
,D/OtaApp  ( 8342): [debug] > Receive intent: com.motorola.blur.service.blur.Actions.UPGRADE_UPDATE_NOTIFICATION
,I/art     (  883): Explicit concurrent mark sweep GC freed 4050(189KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 20MB/31MB, paused 8.917ms total 125.311ms
,D/OtaApp  ( 8342): [debug] > UpdateReceiver: Received true from doSanityCheck.
,D/OtaApp  ( 8342): [debug] > In cancelAnyPendingIntentSetPreviously
,I/ActivityManager(  883): START u0 {act=com.motorola.blur.service.blur.Actions.UPGRADE_UPDATE_NOTIFICATION flg=0x30000000 cmp=com.motorola.ccc.ota/.ui.DownloadActivity (has extras)} from uid 10000 on display 0
,W/ContextImpl( 1478): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,W/ContextImpl( 1478): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,I/ActivityManager(  883): Activity reported stop, but no longer stopping: ActivityRecord{2d62fdb2 u0 com.motorola.ccc.ota/.ui.DownloadActivity t4}
,I/Keyboard.Facilitator( 1417): onFinishInput()
,W/IInputConnectionWrapper( 6633): showStatusIcon on inactive InputConnection
,D/OtaApp  ( 8342): [debug] > DownloadActivity, FormattedText
,I/OtaApp  ( 8342): [info] > DownloadActivity, handling (Blur_Version.22.46.12.thea_reteu.reteuall.en.EU) from ( upgrade)
,D/Checkin ( 8342): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 8342): [debug] > cancelling the previous pending intent set for download later
,I/OtaApp  ( 8342): [info] > next automatic download prompt (serverAnnoy)  is scheduled in : 60 mins.
,D/Checkin ( 8342): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 8342): [debug] > DownloadActivity, FormattedText
,I/LaunchCheckinHandler(  883): Displayed com.motorola.ccc.ota/.ui.DownloadActivity,wp,ca,454
,I/OtaApp  ( 8342): [info] > DownloadActivity, handling (Blur_Version.22.46.12.thea_reteu.reteuall.en.EU) from ( upgrade)
,D/Checkin ( 8342): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 8342): [debug] > cancelling the previous pending intent set for download later
,I/OtaApp  ( 8342): [info] > next automatic download prompt (serverAnnoy)  is scheduled in : 60 mins.
,D/Checkin ( 8342): publish the event [tag = MOT_OTA event name = LOG]
,W/MotorolaSettings( 8342): no such table to get this name = privacy_droid_blast
W/System.err( 8342): java.lang.Exception
,W/System.err( 8342): 	at com.motorola.android.provider.MotorolaSettings.getString(MotorolaSettings.java:290)
W/System.err( 8342): 	at com.motorola.android.provider.MotorolaSettings.getInt(MotorolaSettings.java:328)
W/System.err( 8342): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 8342): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 8342): 	at com.motorola.ccc.checkin.MotorolaSettings.getInt(MotorolaSettings.java:106)
W/System.err( 8342): 	at com.motorola.ccc.checkin.PrivacyHelper.readPrivacy(PrivacyHelper.java:413)
W/System.err( 8342): 	at com.motorola.ccc.checkin.PrivacyHelper.reconfigurePrivacy(PrivacyHelper.java:160)
W/System.err( 8342): 	at com.motorola.ccc.checkin.BcsConfigAndroid.handleConfigChange(BcsConfigAndroid.java:1037)
W/System.err( 8342): 	at com.motorola.ccc.checkin.BcsConfigAndroid.update(BcsConfigAndroid.java:518)
W/System.err( 8342): 	at com.motorola.ccc.checkin.BcsCore.doConfig(BcsCore.java:662)
W/System.err( 8342): 	at com.motorola.ccc.checkin.BcsCore.handleEvent(BcsCore.java:332)
W/System.err( 8342): 	at com.motorola.ccc.checkin.BcsPlatformAndroid.handleCceSendSettingsResponse(BcsPlatformAndroid.java:432)
W/System.err( 8342): 	at com.motorola.ccc.checkin.BcsPlatformAndroid.onReceiveActions(BcsPlatformAndroid.java:403)
W/System.err( 8342): 	at com.motorola.ccc.checkin.BcsPlatformAndroid.access$000(BcsPlatformAndroid.java:87)
W/System.err( 8342): 	at com.motorola.ccc.checkin.BcsPlatformAndroid$1.run(BcsPlatformAndroid.java:295)
W/System.err( 8342): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
W/System.err( 8342): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
W/System.err( 8342): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/System.err( 8342): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/System.err( 8342): 	at java.lang.Thread.run(Thread.java:818)
I/global frequency( 8342): BcsConfigAndroid:updateAllowedEventTagsForPrivacyProfile Blacklisted tags: (DUMMY_TAG:1416552400)
,D/Checkin ( 8342): publish the event [tag = MOT_CHECKIN event name = LOG]
,I/global frequency( 8342): BcsConfigAndroid:updateAllowedEventTagsForPrivacyProfile new whitelisted checkin event tags: MOT_OTA:LOG,MOT_PRIVACY_PROFILE,DEV_ATTRIBS,CHECKIN_SUCCESS,MOT_CCE_STATS:CS_Notif_FFA,DEVICE_PROPERTIES,CHECKIN_FAILURE
,D/Checkin ( 8342): publish the event [tag = MOT_CHECKIN event name = LOG]
,D/Checkin ( 8342): publish the event [tag = MOT_PRIVACY_PROFILE event name = PRIVACY]
,W/Settings( 8342): Setting dropbox_quota_kb has moved from android.provider.Settings.System to android.provider.Settings.Global
,W/Settings( 8342): Setting dropbox_quota_kb has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 8342): Setting dropbox_max_files has moved from android.provider.Settings.System to android.provider.Settings.Global
,W/Settings( 8342): Setting dropbox_max_files has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 8342): Setting dropbox_quota_kb has moved from android.provider.Settings.System to android.provider.Settings.Global
,W/Settings( 8342): Setting dropbox_quota_kb has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/Settings( 8342): Setting dropbox_max_files has moved from android.provider.Settings.System to android.provider.Settings.Global
,W/Settings( 8342): Setting dropbox_max_files has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/global frequency( 8342): BcsTimer.setTimer(86400000, 86400000)
D/Checkin ( 8342): publish the event [tag = MOT_CHECKIN event name = LOG]
,D/Central_PollingManager( 1478): registerApp(): Checkin
,D/Central_PollingManager( 1478): registerApp(): Checkin already registered.
D/Central_PollingManager( 1478): modifyApp(): Checkin
D/Central_PollingManager( 1478): calculateShortestInterval(): shortest interval is 21600000
,W/MotorolaSettings( 8342): no such table to get this name = privacy_droid_blast
W/System.err( 8342): java.lang.Exception
W/System.err( 8342): 	at com.motorola.android.provider.MotorolaSettings.getString(MotorolaSettings.java:290)
,W/System.err( 8342): 	at com.motorola.android.provider.MotorolaSettings.getInt(MotorolaSettings.java:328)
W/System.err( 8342): 	at java.lang.reflect.Method.invoke(Native Method)
,W/System.err( 8342): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 8342): 	at com.motorola.ccc.checkin.MotorolaSettings.getInt(MotorolaSettings.java:106)
W/System.err( 8342): 	at com.motorola.ccc.checkin.PrivacyHelper.readPrivacy(PrivacyHelper.java:413)
W/System.err( 8342): 	at com.motorola.ccc.checkin.PrivacyHelper.reconfigurePrivacy(PrivacyHelper.java:160)
W/System.err( 8342): 	at com.motorola.ccc.checkin.BcsConfigAndroid.handleConfigChange(BcsConfigAndroid.java:996)
W/System.err( 8342): 	at com.motorola.ccc.checkin.BcsConfigAndroid.update(BcsConfigAndroid.java:518)
,W/System.err( 8342): 	at com.motorola.ccc.checkin.BcsCore.doConfig(BcsCore.java:662)
W/System.err( 8342): 	at com.motorola.ccc.checkin.BcsCore.handleEvent(BcsCore.java:332)
W/System.err( 8342): 	at com.motorola.ccc.checkin.BcsPlatformAndroid.handleCceSendSettingsResponse(BcsPlatformAndroid.java:432)
W/System.err( 8342): 	at com.motorola.ccc.checkin.BcsPlatformAndroid.onReceiveActions(BcsPlatformAndroid.java:403)
W/System.err( 8342): 	at com.motorola.ccc.checkin.BcsPlatformAndroid.access$000(BcsPlatformAndroid.java:87)
W/System.err( 8342): 	at com.motorola.ccc.checkin.BcsPlatformAndroid$1.run(BcsPlatformAndroid.java:295)
W/System.err( 8342): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
W/System.err( 8342): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
W/System.err( 8342): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/System.err( 8342): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/System.err( 8342): 	at java.lang.Thread.run(Thread.java:818)
,I/global frequency( 8342): BcsConfigAndroid:updateAllowedEventTagsForPrivacyProfile Blacklisted tags: (DUMMY_TAG:1416552400)
,D/Checkin ( 8342): publish the event [tag = MOT_CHECKIN event name = LOG]
,I/global frequency( 8342): BcsConfigAndroid:updateAllowedEventTagsForPrivacyProfile new whitelisted checkin event tags: MOT_OTA:LOG,MOT_PRIVACY_PROFILE,DEV_ATTRIBS,CHECKIN_SUCCESS,MOT_CCE_STATS:CS_Notif_FFA,DEVICE_PROPERTIES,CHECKIN_FAILURE
D/Checkin ( 8342): publish the event [tag = MOT_CHECKIN event name = LOG]
,D/Checkin ( 8342): publish the event [tag = MOT_PRIVACY_PROFILE event name = PRIVACY]
,W/Settings( 8342): Setting dropbox_quota_kb has moved from android.provider.Settings.System to android.provider.Settings.Global
,W/Settings( 8342): Setting dropbox_quota_kb has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 8342): Setting dropbox_max_files has moved from android.provider.Settings.System to android.provider.Settings.Global
,W/Settings( 8342): Setting dropbox_max_files has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/MotorolaSettings( 8342): no such table to get this name = privacy_droid_blast
,W/System.err( 8342): java.lang.Exception
W/System.err( 8342): 	at com.motorola.android.provider.MotorolaSettings.getString(MotorolaSettings.java:290)
W/System.err( 8342): 	at com.motorola.android.provider.MotorolaSettings.getInt(MotorolaSettings.java:328)
W/System.err( 8342): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 8342): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 8342): 	at com.motorola.ccc.checkin.MotorolaSettings.getInt(MotorolaSettings.java:106)
W/System.err( 8342): 	at com.motorola.ccc.checkin.PrivacyHelper.readPrivacy(PrivacyHelper.java:413)
W/System.err( 8342): 	at com.motorola.ccc.checkin.PrivacyHelper.reconfigurePrivacy(PrivacyHelper.java:160)
,W/System.err( 8342): 	at com.motorola.ccc.checkin.BcsConfigAndroid.handleConfigChange(BcsConfigAndroid.java:996)
W/System.err( 8342): 	at com.motorola.ccc.checkin.BcsConfigAndroid.update(BcsConfigAndroid.java:518)
W/System.err( 8342): 	at com.motorola.ccc.checkin.BcsCore.doConfig(BcsCore.java:662)
W/System.err( 8342): 	at com.motorola.ccc.checkin.BcsCore.handleEvent(BcsCore.java:332)
W/System.err( 8342): 	at com.motorola.ccc.checkin.BcsPlatformAndroid.handleCceSendSettingsResponse(BcsPlatformAndroid.java:432)
W/System.err( 8342): 	at com.motorola.ccc.checkin.BcsPlatformAndroid.onReceiveActions(BcsPlatformAndroid.java:403)
,W/System.err( 8342): 	at com.motorola.ccc.checkin.BcsPlatformAndroid.access$000(BcsPlatformAndroid.java:87)
W/System.err( 8342): 	at com.motorola.ccc.checkin.BcsPlatformAndroid$1.run(BcsPlatformAndroid.java:295)
W/System.err( 8342): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
W/System.err( 8342): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
W/System.err( 8342): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
,W/System.err( 8342): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/System.err( 8342): 	at java.lang.Thread.run(Thread.java:818)
,I/global frequency( 8342): BcsConfigAndroid:updateAllowedEventTagsForPrivacyProfile Blacklisted tags: (DUMMY_TAG:1416552400)
,D/Checkin ( 8342): publish the event [tag = MOT_CHECKIN event name = LOG]
,I/global frequency( 8342): BcsConfigAndroid:updateAllowedEventTagsForPrivacyProfile new whitelisted checkin event tags: MOT_OTA:LOG,MOT_PRIVACY_PROFILE,DEV_ATTRIBS,CHECKIN_SUCCESS,MOT_CCE_STATS:CS_Notif_FFA,DEVICE_PROPERTIES,CHECKIN_FAILURE
,D/Checkin ( 8342): publish the event [tag = MOT_CHECKIN event name = LOG]
,D/Checkin ( 8342): publish the event [tag = MOT_PRIVACY_PROFILE event name = PRIVACY]
,W/Settings( 8342): Setting dropbox_quota_kb has moved from android.provider.Settings.System to android.provider.Settings.Global
,W/Settings( 8342): Setting dropbox_quota_kb has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/Settings( 8342): Setting dropbox_max_files has moved from android.provider.Settings.System to android.provider.Settings.Global
,W/Settings( 8342): Setting dropbox_max_files has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/BatteryService(  883): uevent={POWER_SUPPLY_TEMP=276, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4310209, SEQNUM=4534, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-2704, POWER_SUPPLY_CHARGE_COUNTER=-673, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2530): Disconnected process message: 10, size: 0
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:30000 mC
,I/MDMCTBK (  291): NetlinkHandler, power_supply subsys
,I/MDMCTBK (  291): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  291): checkDefaultInst, current pid is = 291
I/MDMCTBK (  291): checkDefaultInst, pid match
I/MDMCTBK (  291): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  291): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  291): MdmCutbackHndler,Could not open ''
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:30000 mC
,I/Keyboard.Facilitator.LanguageModelFlusher( 1417): run()
,I/Keyboard.Facilitator( 1417): flushDynamicLanguageModels()
,I/ConfigService( 1740): onCreate
,I/ConfigService( 1740): onDestroy
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:30000 mC
,I/jxcore-log( 6633): --- start :testSendData.js---
I/jxcore-log( 6633): 
,I/jxcore-log( 6633): testSendData created {"name":"testSendData.js","serverTimeout":1200000,"timeout":1000000,"rounds":1,"dataTimeout":20000,"dataAmount":100000,"conReTryTimeout":5000,"conReTryCount":5,"peerCount":15}bt-address length : 0
I/jxcore-log( 6633): 
,I/jxcore-log( 6633): daya100000
I/jxcore-log( 6633): 
I/jxcore-log( 6633): check server
I/jxcore-log( 6633): 
I/jxcore-log( 6633): serverPort is 57867
I/jxcore-log( 6633): 
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:30000 mC
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6633): setDiscoveryMode: Failed to set discovery mode to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6633): setDiscoveryMode: Mode set to WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6633): setDiscoveryMode: Mode set to WIFI
,D/BluetoothManagerService(  883): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6633): start: Peer ID: 44:80:EB:7B:5A:05, peer name: motorola-XT1072_PT598
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6633): bind: Binding a new listener
,D/BluetoothManagerService(  883): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6633): initialize: My bluetooth address is 44:80:EB:7B:5A:05
,D/BluetoothManagerService(  883): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6633): verifyIdentityString: Identity string created: {"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT598","ra":"44:80:EB:7B:5A:05"}
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6633): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6633): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6633): startListeningForIncomingConnections: Starting...
,D/BluetoothManagerService(  883): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 6633): getBluetoothService() called with no BluetoothManagerCallback
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6633): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6633): start: OK
I/io.jxcore.node.ConnectionHelper( 6633): start: Using peer discovery mode: WIFI
,D/BluetoothManagerService(  883): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6633): start: Peer ID: 44:80:EB:7B:5A:05, peer name: motorola-XT1072_PT598
,D/BluetoothManagerService(  883): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6633): verifyIdentityString: Identity string created: {"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT598","ra":"44:80:EB:7B:5A:05"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6633): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6633): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6633): start: {"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT598","ra":"44:80:EB:7B:5A:05"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6633): start: Identity string: "{"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT598","ra":"44:80:EB:7B:5A:05"}", service type: "Cordovap2p._tcp"
,D/WifiP2pService(  883): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@74006e08 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  883): P2pEnabledState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@74006e08 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  883): P2pEnabledState add service
,D/WifiP2pService(  883): add a new client
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6633): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6633): start: Starting P2P device discovery...
,D/WifiP2pService(  883): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  883): P2pEnabledState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 1442): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  291): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  291): Event received = CTRL-EVENT-SCAN-STARTED 
,D/WifiP2pService(  883): discovery change broadcast true
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6633): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6633): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6633): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6633): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 6633): start: OK
,I/jxcore-log( 6633): StartBroadcasting started ok
I/jxcore-log( 6633): 
,I/jxcore-log( 6633): null
I/jxcore-log( 6633): 
I/jxcore-log( 6633): 2015-12-18T17:58:21.976Z SendDataTCPServer.js: TCP/IP server is bound to port: 57867
I/jxcore-log( 6633): 
I/chromium( 6633): [INFO:CONSOLE(63)] "logCallback --- start :testSendData.js---", source: file:///android_asset/www/js/thali_main.js (63)
I/io.jxcore.node.ConnectionHelper( 6633): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6633): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6633): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6633): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6633): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6633): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
I/io.jxcore.node.ConnectionHelper( 6633): onDiscoveryManagerStateChanged: RUNNING
,D/MDMCTBK (  291): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 0 c0
D/MDMCTBK (  291): Event received = CTRL-EVENT-BSS-ADDED 0 c0
,D/TCMD    (  474): NL - Read 56 bytes from update socket.
D/TCMD    (  474): NL - message type is RTM_NEWLINK
D/TCMD    (  474): Listening for incoming client connection request
,I/wpa_supplicant( 1442): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  291): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  291): Event received = CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1442): P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 level=-47
I/wpa_supplicant( 1442): P2P-DEVICE-FOUND 92:e7:c4:e6:4c:f8 p2p_dev_addr=92:e7:c4:e6:4c:f8 pri_dev_type=10-0050F204-5 name='Android_608e' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 level=-48
,D/MDMCTBK (  291): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2
,D/MDMCTBK (  291): Event received = P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2
D/MDMCTBK (  291): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND 92:e7:c4:e6:4c:f8 p2
D/MDMCTBK (  291): Event received = P2P-DEVICE-FOUND 92:e7:c4:e6:4c:f8 p2
,D/WifiP2pService(  883): InactiveState{ when=0 what=147477 obj=Device: Thali Test (Galaxy A5)
D/WifiP2pService(  883):  deviceAddress: 7e:f9:0e:51:18:23
D/WifiP2pService(  883):  primary type: 10-0050F204-5
D/WifiP2pService(  883):  secondary type: null
D/WifiP2pService(  883):  wps: 392
D/WifiP2pService(  883):  grpcapab: 0
D/WifiP2pService(  883):  devcapab: 37
D/WifiP2pService(  883):  status: 3
D/WifiP2pService(  883):  wfdInfo: null
D/WifiP2pService(  883):  level: -47 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  883): P2pEnabledState{ when=0 what=147477 obj=Device: Thali Test (Galaxy A5)
D/WifiP2pService(  883):  deviceAddress: 7e:f9:0e:51:18:23
D/WifiP2pService(  883):  primary type: 10-0050F204-5
D/WifiP2pService(  883):  secondary type: null
D/WifiP2pService(  883):  wps: 392
D/WifiP2pService(  883):  grpcapab: 0
D/WifiP2pService(  883):  devcapab: 37
D/WifiP2pService(  883):  status: 3
D/WifiP2pService(  883):  wfdInfo: null
D/WifiP2pService(  883):  level: -47 target=com.android.internal.util.StateMachine$SmHandler }
,D/TCMD    (  474): NL - Read 56 bytes from update socket.
,D/TCMD    (  474): NL - message type is RTM_NEWLINK
D/TCMD    (  474): Listening for incoming client connection request
,D/WifiP2pService(  883): InactiveState{ when=-10ms what=147477 obj=Device: Android_608e
D/WifiP2pService(  883):  deviceAddress: 92:e7:c4:e6:4c:f8
D/WifiP2pService(  883):  primary type: 10-0050F204-5
D/WifiP2pService(  883):  secondary type: null
D/WifiP2pService(  883):  wps: 392
D/WifiP2pService(  883):  grpcapab: 0
D/WifiP2pService(  883):  devcapab: 37
D/WifiP2pService(  883):  status: 3
D/WifiP2pService(  883):  wfdInfo: null
D/WifiP2pService(  883):  level: -48 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  883): P2pEnabledState{ when=-10ms what=147477 obj=Device: Android_608e
D/WifiP2pService(  883):  deviceAddress: 92:e7:c4:e6:4c:f8
D/WifiP2pService(  883):  primary type: 10-0050F204-5
D/WifiP2pService(  883):  secondary type: null
D/WifiP2pService(  883):  wps: 392
D/WifiP2pService(  883):  grpcapab: 0
D/WifiP2pService(  883):  devcapab: 37
D/WifiP2pService(  883):  status: 3
D/WifiP2pService(  883):  wfdInfo: null
D/WifiP2pService(  883):  level: -48 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  883): InactiveState{ when=0 what=139283 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  883): P2pEnabledState{ when=0 what=139283 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  883): DefaultState{ when=0 what=139283 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  883): InactiveState{ when=0 what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  883): P2pEnabledState{ when=-3ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  883): DefaultState{ when=-3ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6633): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6633): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6633): onP2pDeviceListChanged: Peer 2: Android_608e 92:e7:c4:e6:4c:f8
,D/WifiP2pService(  883): InactiveState{ when=0 what=139301 arg2=5 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  883): P2pEnabledState{ when=0 what=139301 arg2=5 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  883): P2pEnabledState add service request
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6633): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6633): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6633): onP2pDeviceListChanged: Peer 2: Android_608e 92:e7:c4:e6:4c:f8
,D/WifiP2pManager( 6633): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6633): Service request added successfully
,I/wpa_supplicant( 1442): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  291): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  291): Event received = CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1442): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 level=-31
,D/MDMCTBK (  291): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2
,D/MDMCTBK (  291): Event received = P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2
,D/WifiP2pService(  883): InactiveState{ when=-1ms what=147477 obj=Device: A3-1
D/WifiP2pService(  883):  deviceAddress: 0a:ec:a9:50:75:42
D/WifiP2pService(  883):  primary type: 10-0050F204-5
D/WifiP2pService(  883):  secondary type: null
D/WifiP2pService(  883):  wps: 392
D/WifiP2pService(  883):  grpcapab: 0
D/WifiP2pService(  883):  devcapab: 37
D/WifiP2pService(  883):  status: 3
D/WifiP2pService(  883):  wfdInfo: null
D/WifiP2pService(  883):  level: -31 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  883): P2pEnabledState{ when=-1ms what=147477 obj=Device: A3-1
D/WifiP2pService(  883):  deviceAddress: 0a:ec:a9:50:75:42
D/WifiP2pService(  883):  primary type: 10-0050F204-5
D/WifiP2pService(  883):  secondary type: null
D/WifiP2pService(  883):  wps: 392
D/WifiP2pService(  883):  grpcapab: 0
D/WifiP2pService(  883):  devcapab: 37
D/WifiP2pService(  883):  status: 3
D/WifiP2pService(  883):  wfdInfo: null
D/WifiP2pService(  883):  level: -31 target=com.android.internal.util.StateMachine$SmHandler }
,D/TCMD    (  474): NL - Read 56 bytes from update socket.
,D/TCMD    (  474): NL - message type is RTM_NEWLINK
D/TCMD    (  474): Listening for incoming client connection request
,D/WifiP2pService(  883): InactiveState{ when=0 what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  883): P2pEnabledState{ when=0 what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  883): DefaultState{ when=0 what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6633): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6633): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6633): onP2pDeviceListChanged: Peer 2: Android_608e 92:e7:c4:e6:4c:f8
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6633): onP2pDeviceListChanged: Peer 3: A3-1 0a:ec:a9:50:75:42
,D/MDMCTBK (  291): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 0 
D/MDMCTBK (  291): Event received = CTRL-EVENT-BSS-REMOVED 0 
,D/WifiP2pService(  883): InactiveState{ when=0 what=139310 arg2=7 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  883): P2pEnabledState{ when=0 what=139310 arg2=7 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  883): P2pEnabledState discover services
,I/wpa_supplicant( 1442): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  291): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  291): Event received = CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6633): Service discovery started successfully
,I/wpa_supplicant( 1442): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 level=-49
D/MDMCTBK (  291): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 1 c0
D/MDMCTBK (  291): Event received = CTRL-EVENT-BSS-ADDED 1 c0
D/MDMCTBK (  291): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2
D/MDMCTBK (  291): Event received = P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2
,D/WifiP2pService(  883): InactiveState{ when=0 what=147477 obj=Device: A5-1
D/WifiP2pService(  883):  deviceAddress: 7e:f9:0e:37:96:ac
D/WifiP2pService(  883):  primary type: 10-0050F204-5
D/WifiP2pService(  883):  secondary type: null
D/WifiP2pService(  883):  wps: 392
D/WifiP2pService(  883):  grpcapab: 0
D/WifiP2pService(  883):  devcapab: 37
D/WifiP2pService(  883):  status: 3
D/WifiP2pService(  883):  wfdInfo: null
D/WifiP2pService(  883):  level: -49 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  883): P2pEnabledState{ when=0 what=147477 obj=Device: A5-1
D/WifiP2pService(  883):  deviceAddress: 7e:f9:0e:37:96:ac
D/WifiP2pService(  883):  primary type: 10-0050F204-5
D/WifiP2pService(  883):  secondary type: null
D/WifiP2pService(  883):  wps: 392
D/WifiP2pService(  883):  grpcapab: 0
D/WifiP2pService(  883):  devcapab: 37
D/WifiP2pService(  883):  status: 3
D/WifiP2pService(  883):  wfdInfo: null
D/WifiP2pService(  883):  level: -49 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  883): InactiveState{ when=0 what=139283 arg2=8 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  883): P2pEnabledState{ when=-1ms what=139283 arg2=8 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  883): DefaultState{ when=-1ms what=139283 arg2=8 target=com.android.internal.util.StateMachine$SmHandler }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6633): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6633): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6633): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6633): onP2pDeviceListChanged: Peer 3: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6633): onP2pDeviceListChanged: Peer 4: A3-1 0a:ec:a9:50:75:42
,D/TCMD    (  474): NL - Read 56 bytes from update socket.
D/TCMD    (  474): NL - message type is RTM_NEWLINK
D/TCMD    (  474): Listening for incoming client connection request
,D/MDMCTBK (  291): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP 0a:ec:
D/MDMCTBK (  291): Event received = P2P-SERV-DISC-RESP 0a:ec:
,D/WifiP2pService(  883): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:0a:ec:a9:50:75:42 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT5572","ra":"08:EC:A9:50:75:41"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  883): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:0a:ec:a9:50:75:42 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT5572","ra":"08:EC:A9:50:75:41"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  883): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6633): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT5572","ra":"08:EC:A9:50:75:41"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6633): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT5572]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6633): onServiceDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT5572]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6633): onPeerDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT5572]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6633): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT5572], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6633): modifyListOfDiscoveredPeers: Adding new peer: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT5572]
I/io.jxcore.node.ConnectionHelper( 6633): onPeerDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT5572], Bluetooth address: 08:EC:A9:50:75:41, device name: A3-1, device address: 0a:ec:a9:50:75:42
D/io.jxcore.node.ConnectionHelper( 6633): notifyPeerAvailability: Peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT5572] is available
I/jxcore-log( 6633): peerAvailabilityChanged [{"peerIdentifier":"08:EC:A9:50:75:41","peerName":"samsung-SM-A300FU_PT5572","peerAvailable":true}]
I/jxcore-log( 6633): 
I/jxcore-log( 6633): Found peer : samsung-SM-A300FU_PT5572, Available: true
I/jxcore-log( 6633): 
I/jxcore-log( 6633): startWithNextDevice
I/jxcore-log( 6633): 
,I/jxcore-log( 6633): device[1]: 08:EC:A9:50:75:41
I/jxcore-log( 6633): 
I/jxcore-log( 6633): 2015-12-18T17:58:24.615Z SendDataConnector.js: Start called with peer 08:EC:A9:50:75:41
I/jxcore-log( 6633): 
I/jxcore-log( 6633): 2015-12-18T17:58:24.615Z SendDataConnector.js: doConnect called with peer 08:EC:A9:50:75:41
I/jxcore-log( 6633): 
I/jxcore-log( 6633): 2015-12-18T17:58:24.616Z SendDataConnector.js: do connect now
I/jxcore-log( 6633): 
I/io.jxcore.node.ConnectionHelper( 6633): connect: Trying to connect to peer with ID 08:EC:A9:50:75:41
D/io.jxcore.node.ConnectionHelper( 6633): hasConnection: No connection with peer with ID 08:EC:A9:50:75:41
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6633): connect: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT5572]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6633): connect: Trying to start connecting to null in address 08:EC:A9:50:75:41
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6633): setInsecureRfcommSocketPort: Using port -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6633): setMaxNumberOfRetries: 0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6633): onConnecting: null 08:EC:A9:50:75:41
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6633): connect: Started connecting to null in address 08:EC:A9:50:75:41
I/io.jxcore.node.ConnectionHelper( 6633): connect: Connection process successfully started (peer ID: 08:EC:A9:50:75:41)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6633): Trying to connect to peer with address 08:EC:A9:50:75:41 (thread ID: 781)
W/BluetoothAdapter( 6633): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2530): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 2530): info:x10
,D/        ( 2530): remote version info [08:ec:a9:50:75:41]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 2530): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 2530): process_service_search_attr_rsp
,D/MDMCTBK (  291): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP 92:b6:
D/MDMCTBK (  291): Event received = P2P-SERV-DISC-RESP 92:b6:
,D/WifiP2pService(  883): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:92:b6:86:43:73:1c version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT6460","ra":"E0:DB:10:14:E2:C0"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  883): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:92:b6:86:43:73:1c version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT6460","ra":"E0:DB:10:14:E2:C0"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  883): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6633): onDnsSdServiceAvailable: Identity: "{"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT6460","ra":"E0:DB:10:14:E2:C0"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6633): onDnsSdServiceAvailable: Resolved peer properties: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT6460]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6633): onServiceDiscovered: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT6460]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6633): onPeerDiscovered: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT6460]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6633): modifyListOfDiscoveredPeers: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT6460], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6633): modifyListOfDiscoveredPeers: Adding new peer: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT6460]
I/io.jxcore.node.ConnectionHelper( 6633): onPeerDiscovered: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT6460], Bluetooth address: E0:DB:10:14:E2:C0, device name: , device address: 92:b6:86:43:73:1c
D/io.jxcore.node.ConnectionHelper( 6633): notifyPeerAvailability: Peer [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT6460] is available
,I/jxcore-log( 6633): peerAvailabilityChanged [{"peerIdentifier":"E0:DB:10:14:E2:C0","peerName":"samsung-SM-N910C_PT6460","peerAvailable":true}]
I/jxcore-log( 6633): 
,I/jxcore-log( 6633): Found peer : samsung-SM-N910C_PT6460, Available: true
I/jxcore-log( 6633): 
,I/BluetoothBondStateMachine( 2530): bondStateChangeCallback: Status: 0 Address: 08:EC:A9:50:75:41 newState: 1
,E/bt-btif ( 2530): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2530): Bond State Change Intent:08:EC:A9:50:75:41 OldState: 10 NewState: 11
,I/BluetoothBondStateMachine( 2530): Entering PendingCommandState State
,D/BluetoothManagerService(  883): Message: 20
D/BluetoothManagerService(  883): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@20b1be86:true
,I/ActivityManager(  883): Start proc com.motorola.context for broadcast com.motorola.context/.publisher.bluetoothdeterminer.BTReceiver: pid=8442 uid=10008 gids={50008, 9997, 3001, 3002, 3003} abi=armeabi-v7a
,W/ResourcesManager( 8442): Asset path '/system/framework/com.motorola.motosignature.jar' does not exist or contains no resources.
,D/BluetoothManagerService(  883): Message: 20
D/BluetoothManagerService(  883): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@62bd774:true
,I/ActivityManager(  883): Start proc com.android.settings for broadcast com.android.settings/.bluetooth.BluetoothPairingRequest: pid=8471 uid=1000 gids={41000, 9997, 1021, 3004, 3005, 1000, 3009, 1015, 1023, 1010, 1004, 2002, 3006, 1028, 3002, 3001, 3003} abi=armeabi-v7a
,I/ActivityManager(  883): Killing 8123:com.google.android.googlequicksearchbox:search/u0a39 (adj 15): empty #7
,I/BluetoothBondStateMachine( 2530): bondStateChangeCallback: Status: 0 Address: 08:EC:A9:50:75:41 newState: 0
D/BluetoothAdapterProperties( 2530): Failed to remove device: 08:EC:A9:50:75:41
,I/BluetoothBondStateMachine( 2530): Bond State Change Intent:08:EC:A9:50:75:41 OldState: 11 NewState: 10
D/BluetoothAdapterService( 2530): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@459897f
W/libprocessgroup(  883): failed to open /acct/uid_10039/pid_8123/cgroup.procs: No such file or directory
,D/BluetoothMetrics( 2530): btclass5a020c
,D/Checkin ( 2530): publish the event [tag = MOT_BT event name = PAIRING]
,I/BluetoothBondStateMachine( 2530): StableState(): Entering Off State
,W/ResourcesManager( 8471): Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
,D/BluetoothManagerService(  883): Message: 20
,D/BluetoothManagerService(  883): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@29e0ace3:true
W/bt-btif ( 2530): new conn_srvc id:26, app_id:1
W/bt-btif ( 2530): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2530): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6633): onSocketConnected: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT5572]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6633): Socket connection succeeded (using system decided port), total number of attempts: 1 (thread ID: 781)
,I/ActivityManager(  883): Killing 8174:android.process.acore/u0a7 (adj 15): empty #7
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6633): onBytesWritten: 80 bytes successfully written (thread ID: 782)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6633): Outgoing connection initialized (*handshake* thread ID: 782)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6633): Exiting thread (thread ID: 781)
D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 6633): Entering thread (ID: 782)
,W/libprocessgroup(  883): failed to open /acct/uid_10007/pid_8174/cgroup.procs: No such file or directory
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6633): onBytesRead: Read 83 bytes successfully (thread ID: 782)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6633): Handshake succeeded with [08:EC:A9:50:75:41 samsung-SM-A300FU_PT5572]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6633): onHandshakeSucceeded: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT5572]
D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 6633): Exiting thread (ID: 782)
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6633): onConnected: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT5572]
I/io.jxcore.node.ConnectionHelper( 6633): onConnected: Outgoing connection to peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT5572]
D/io.jxcore.node.ConnectionHelper( 6633): hasConnection: No connection with peer with ID 08:EC:A9:50:75:41
,W/io.jxcore.node.ConnectionHelper( 6633): modifyListOfDiscoveredPeers: Peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT5572] already in the list, will not add again
,I/io.jxcore.node.ConnectionHelper( 6633): onConnected: Outgoing socket thread, for peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT5572], created successfully
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6633): setInsecureRfcommSocketPort: Will use port -1 when trying to connect
D/io.jxcore.node.ConnectionHelper( 6633): onConnected: The total number of connections is now 1
D/io.jxcore.node.OutgoingSocketThread( 6633): Entering thread (ID: 783)
,D/io.jxcore.node.OutgoingSocketThread( 6633): Server socket local port: 59266
I/io.jxcore.node.OutgoingSocketThread( 6633): Now accepting connections...
,W/bt-btif ( 2530): new conn_srvc id:26, app_id:255
W/bt-btif ( 2530): bta_dm_pm_ssr conn_srvc id:26, app_id:1
,W/bt-btif ( 2530): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 2530): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6633): Incoming connection accepted
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6633): Incoming connection initialized (thread ID: 784)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6633): Waiting for incoming connections...
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 6633): Entering thread (ID: 784)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6633): onBytesRead: Read 83 bytes successfully (thread ID: 784)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6633): Got valid identity from [08:EC:A9:50:75:41 samsung-SM-A300FU_PT5572]
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6633): onBytesWritten: 80 bytes successfully written (thread ID: 784)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6633): removeThreadFromList: Removing thread with ID 784
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6633): Handshake thread disposed (thread ID: 784)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6633): onIncomingConnectionConnected: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT5572]
D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 6633): Exiting thread (ID: 784)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6633): onConnected: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT5572]
I/io.jxcore.node.ConnectionHelper( 6633): onConnected: Incoming connection to peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT5572]
D/io.jxcore.node.ConnectionHelper( 6633): hasConnection: We have an outgoing connection with peer with ID 08:EC:A9:50:75:41
,W/io.jxcore.node.ConnectionHelper( 6633): onConnected: Already connected with peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT5572], continuing anyway...
W/io.jxcore.node.ConnectionHelper( 6633): modifyListOfDiscoveredPeers: Peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT5572] already in the list, will not add again
I/io.jxcore.node.ConnectionHelper( 6633): onConnected: Incoming socket thread, for peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT5572], created successfully
D/io.jxcore.node.ConnectionHelper( 6633): onConnected: The total number of connections is now 2
,D/io.jxcore.node.IncomingSocketThread( 6633): Entering thread (ID: 785)
,I/io.jxcore.node.IncomingSocketThread( 6633): Local host address: localhost/127.0.0.1, port: 57867
,I/jxcore-log( 6633): 2015-12-18T17:58:26.730Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 6633): 
,D/io.jxcore.node.IncomingSocketThread( 6633): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 6633): setBufferSize: Setting buffer size to 8192 bytes
,I/io.jxcore.node.StreamCopyingThread( 6633): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.IncomingSocketThread( 6633): startStreamCopyingThreads: OK
D/io.jxcore.node.IncomingSocketThread( 6633): Exiting thread (ID: 785)
,D/io.jxcore.node.StreamCopyingThread( 6633): Entering thread (ID: 787, name: Receiver)
,D/io.jxcore.node.StreamCopyingThread( 6633): Entering thread (ID: 786, name: Sender)
,D/MDMCTBK (  291): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP 7e:f9:
D/MDMCTBK (  291): Event received = P2P-SERV-DISC-RESP 7e:f9:
,D/WifiP2pService(  883): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:7e:f9:0e:51:18:23 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:51:18:22","pn":"samsung-SM-A500FU_PT3826","ra":"7C:F9:0E:51:18:22"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  883): P2pEnabledState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:7e:f9:0e:51:18:23 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:51:18:22","pn":"samsung-SM-A500FU_PT3826","ra":"7C:F9:0E:51:18:22"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  883): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6633): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:51:18:22","pn":"samsung-SM-A500FU_PT3826","ra":"7C:F9:0E:51:18:22"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6633): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT3826]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6633): onServiceDiscovered: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT3826]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6633): onPeerDiscovered: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT3826]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6633): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT3826], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6633): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT3826]
I/io.jxcore.node.ConnectionHelper( 6633): onPeerDiscovered: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT3826], Bluetooth address: 7C:F9:0E:51:18:22, device name: Thali Test (Galaxy A5), device address: 7e:f9:0e:51:18:23
D/io.jxcore.node.ConnectionHelper( 6633): notifyPeerAvailability: Peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT3826] is available
I/jxcore-log( 6633): peerAvailabilityChanged [{"peerIdentifier":"7C:F9:0E:51:18:22","peerName":"samsung-SM-A500FU_PT3826","peerAvailable":true}]
I/jxcore-log( 6633): 
,I/jxcore-log( 6633): Found peer : samsung-SM-A500FU_PT3826, Available: true
I/jxcore-log( 6633): 
,I/io.jxcore.node.ConnectionHelper( 6633): onListeningForIncomingConnections: Outgoing connection is using port 59266 (peer ID: 08:EC:A9:50:75:41)
,I/jxcore-log( 6633): 2015-12-18T17:58:26.855Z SendDataConnector.js: CLIENT connected to 59266, error: null
I/jxcore-log( 6633): 
I/jxcore-log( 6633): 2015-12-18T17:58:26.855Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 6633): 
,D/MDMCTBK (  291): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-REQ 2412 7e
D/MDMCTBK (  291): Event received = P2P-SERV-DISC-REQ 2412 7e
,I/io.jxcore.node.IncomingSocketThread( 6633): Incoming data from address: /127.0.0.1, port: 59266
D/io.jxcore.node.IncomingSocketThread( 6633): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 6633): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 6633): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.IncomingSocketThread( 6633): startStreamCopyingThreads: OK
D/io.jxcore.node.IncomingSocketThread( 6633): Exiting thread (ID: 783)
,D/MDMCTBK (  291): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP 7e:f9:
,D/MDMCTBK (  291): Event received = P2P-SERV-DISC-RESP 7e:f9:
,D/WifiP2pService(  883): InactiveState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:7e:f9:0e:37:96:ac version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT1532","ra":"7C:F9:0E:37:96:AB"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  883): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:7e:f9:0e:37:96:ac version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT1532","ra":"7C:F9:0E:37:96:AB"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  883): P2pEnabledState receive service response
,D/io.jxcore.node.StreamCopyingThread( 6633): Entering thread (ID: 789, name: Receiver)
,I/jxcore-log( 6633): 2015-12-18T17:58:26.887Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 6633): 
,D/io.jxcore.node.StreamCopyingThread( 6633): Entering thread (ID: 788, name: Sender)
,D/MDMCTBK (  291): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-REQ 2412 ee
D/MDMCTBK (  291): Event received = P2P-SERV-DISC-REQ 2412 ee
D/MDMCTBK (  291): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-REQ 2412 0a
D/MDMCTBK (  291): Event received = P2P-SERV-DISC-REQ 2412 0a
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6633): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT1532","ra":"7C:F9:0E:37:96:AB"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6633): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1532]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6633): onServiceDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1532]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6633): onPeerDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1532]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6633): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1532], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6633): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1532]
I/io.jxcore.node.ConnectionHelper( 6633): onPeerDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1532], Bluetooth address: 7C:F9:0E:37:96:AB, device name: A5-1, device address: 7e:f9:0e:37:96:ac
D/io.jxcore.node.ConnectionHelper( 6633): notifyPeerAvailability: Peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1532] is available
,I/jxcore-log( 6633): peerAvailabilityChanged [{"peerIdentifier":"7C:F9:0E:37:96:AB","peerName":"samsung-SM-A500FU_PT1532","peerAvailable":true}]
I/jxcore-log( 6633): 
I/jxcore-log( 6633): Found peer : samsung-SM-A500FU_PT1532, Available: true
I/jxcore-log( 6633): 
,I/jxcore-log( 6633): 2015-12-18T17:58:27.819Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 6633): 
,I/jxcore-log( 6633): 2015-12-18T17:58:27.824Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 6633): 
,I/jxcore-log( 6633): 2015-12-18T17:58:27.829Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 6633): 
,I/jxcore-log( 6633): 2015-12-18T17:58:27.836Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 6633): 
,I/jxcore-log( 6633): 2015-12-18T17:58:27.841Z SendDataTCPServer.js: TCP/IP server has received 9900 bytes of data
I/jxcore-log( 6633): 
,I/jxcore-log( 6633): 2015-12-18T17:58:27.846Z SendDataTCPServer.js: TCP/IP server has received 11880 bytes of data
I/jxcore-log( 6633): 
,I/jxcore-log( 6633): 2015-12-18T17:58:27.852Z SendDataTCPServer.js: TCP/IP server has received 13860 bytes of data
I/jxcore-log( 6633): 
,E/bt-btm  ( 2530): tBTM_SEC_DEV:0xa6fc489c rs_disc_pending=0
W/bt-btif ( 2530): bta_dm_check_av:0
,W/bt-btif ( 2530): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 6633): 2015-12-18T17:58:28.196Z SendDataTCPServer.js: TCP/IP server has received 15840 bytes of data
I/jxcore-log( 6633): 
,I/jxcore-log( 6633): 2015-12-18T17:58:28.203Z SendDataTCPServer.js: TCP/IP server has received 17820 bytes of data
I/jxcore-log( 6633): 
,I/jxcore-log( 6633): 2015-12-18T17:58:28.209Z SendDataTCPServer.js: TCP/IP server has received 19800 bytes of data
I/jxcore-log( 6633): 
,D/        ( 2530): PORT_WriteDataCO: tx queue is full,tx.queue_size:10172,tx.queue.count:11,available:24706
,I/jxcore-log( 6633): 2015-12-18T17:58:28.222Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 6633): 
,I/jxcore-log( 6633): 2015-12-18T17:58:28.238Z SendDataTCPServer.js: TCP/IP server has received 21780 bytes of data
I/jxcore-log( 6633): 
,I/jxcore-log( 6633): 2015-12-18T17:58:28.247Z SendDataTCPServer.js: TCP/IP server has received 23760 bytes of data
I/jxcore-log( 6633): 
,I/jxcore-log( 6633): 2015-12-18T17:58:28.284Z SendDataTCPServer.js: TCP/IP server has received 25740 bytes of data
I/jxcore-log( 6633): 
,I/jxcore-log( 6633): 2015-12-18T17:58:28.288Z SendDataTCPServer.js: TCP/IP server has received 27720 bytes of data
I/jxcore-log( 6633): 
,I/jxcore-log( 6633): 2015-12-18T17:58:28.296Z SendDataTCPServer.js: TCP/IP server has received 29700 bytes of data
I/jxcore-log( 6633): 
,I/jxcore-log( 6633): 2015-12-18T17:58:28.309Z SendDataTCPServer.js: TCP/IP server has received 31680 bytes of data
I/jxcore-log( 6633): 
,I/jxcore-log( 6633): 2015-12-18T17:58:28.315Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 6633): 
,I/jxcore-log( 6633): 2015-12-18T17:58:28.366Z SendDataTCPServer.js: TCP/IP server has received 33660 bytes of data
I/jxcore-log( 6633): 
,I/jxcore-log( 6633): 2015-12-18T17:58:28.444Z SendDataTCPServer.js: TCP/IP server has received 35640 bytes of data
I/jxcore-log( 6633): 
,I/jxcore-log( 6633): 2015-12-18T17:58:28.456Z SendDataTCPServer.js: TCP/IP server has received 37620 bytes of data
I/jxcore-log( 6633): 
,I/jxcore-log( 6633): 2015-12-18T17:58:28.468Z SendDataTCPServer.js: TCP/IP server has received 39600 bytes of data
I/jxcore-log( 6633): 
,I/jxcore-log( 6633): 2015-12-18T17:58:28.481Z SendDataTCPServer.js: TCP/IP server has received 41580 bytes of data
I/jxcore-log( 6633): 
,I/jxcore-log( 6633): 2015-12-18T17:58:28.498Z SendDataTCPServer.js: TCP/IP server has received 43560 bytes of data
I/jxcore-log( 6633): 
,I/jxcore-log( 6633): 2015-12-18T17:58:28.534Z SendDataTCPServer.js: TCP/IP server has received 47520 bytes of data
I/jxcore-log( 6633): 
,I/jxcore-log( 6633): 2015-12-18T17:58:28.590Z SendDataTCPServer.js: TCP/IP server has received 49500 bytes of data
I/jxcore-log( 6633): 
,I/jxcore-log( 6633): 2015-12-18T17:58:28.599Z SendDataTCPServer.js: TCP/IP server has received 51480 bytes of data
I/jxcore-log( 6633): 
,D/        ( 2530): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:14806
,I/jxcore-log( 6633): 2015-12-18T17:58:28.609Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 6633): 
,I/jxcore-log( 6633): 2015-12-18T17:58:28.613Z SendDataTCPServer.js: TCP/IP server has received 53460 bytes of data
I/jxcore-log( 6633): 
,I/jxcore-log( 6633): 2015-12-18T17:58:28.644Z SendDataTCPServer.js: TCP/IP server has received 57420 bytes of data
I/jxcore-log( 6633): 
,I/jxcore-log( 6633): 2015-12-18T17:58:28.650Z SendDataTCPServer.js: TCP/IP server has received 59400 bytes of data
I/jxcore-log( 6633): 
,I/jxcore-log( 6633): 2015-12-18T17:58:28.665Z SendDataTCPServer.js: TCP/IP server has received 61380 bytes of data
I/jxcore-log( 6633): 
,I/jxcore-log( 6633): 2015-12-18T17:58:28.707Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 6633): 
,I/jxcore-log( 6633): 2015-12-18T17:58:28.783Z SendDataTCPServer.js: TCP/IP server has received 63360 bytes of data
I/jxcore-log( 6633): 
,I/jxcore-log( 6633): 2015-12-18T17:58:28.814Z SendDataTCPServer.js: TCP/IP server has received 67320 bytes of data
I/jxcore-log( 6633): 
,I/jxcore-log( 6633): 2015-12-18T17:58:28.854Z SendDataTCPServer.js: TCP/IP server has received 69300 bytes of data
I/jxcore-log( 6633): 
,I/jxcore-log( 6633): 2015-12-18T17:58:28.864Z SendDataTCPServer.js: TCP/IP server has received 71280 bytes of data
I/jxcore-log( 6633): 
,I/jxcore-log( 6633): 2015-12-18T17:58:28.907Z SendDataTCPServer.js: TCP/IP server has received 73260 bytes of data
I/jxcore-log( 6633): 
,I/jxcore-log( 6633): 2015-12-18T17:58:28.944Z SendDataTCPServer.js: TCP/IP server has received 75240 bytes of data
I/jxcore-log( 6633): 
,D/        ( 2530): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:3916
,I/jxcore-log( 6633): 2015-12-18T17:58:28.969Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 6633): 
,I/jxcore-log( 6633): 2015-12-18T17:58:28.984Z SendDataTCPServer.js: TCP/IP server has received 81180 bytes of data
I/jxcore-log( 6633): 
,I/jxcore-log( 6633): 2015-12-18T17:58:29.013Z SendDataTCPServer.js: TCP/IP server has received 83160 bytes of data
I/jxcore-log( 6633): 
,I/jxcore-log( 6633): 2015-12-18T17:58:29.058Z SendDataTCPServer.js: TCP/IP server has received 85140 bytes of data
I/jxcore-log( 6633): 
,I/jxcore-log( 6633): 2015-12-18T17:58:29.095Z SendDataTCPServer.js: TCP/IP server has received 87120 bytes of data
I/jxcore-log( 6633): 
,I/jxcore-log( 6633): 2015-12-18T17:58:29.135Z SendDataTCPServer.js: TCP/IP server has received 91080 bytes of data
I/jxcore-log( 6633): 
,I/jxcore-log( 6633): 2015-12-18T17:58:29.150Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 6633): 
,I/jxcore-log( 6633): 2015-12-18T17:58:29.253Z SendDataTCPServer.js: TCP/IP server has received 93060 bytes of data
I/jxcore-log( 6633): 
,I/jxcore-log( 6633): 2015-12-18T17:58:29.284Z SendDataTCPServer.js: TCP/IP server has received 95040 bytes of data
I/jxcore-log( 6633): 
,I/jxcore-log( 6633): 2015-12-18T17:58:29.324Z SendDataTCPServer.js: TCP/IP server has received 97020 bytes of data
I/jxcore-log( 6633): 
,I/jxcore-log( 6633): 2015-12-18T17:58:29.364Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
I/jxcore-log( 6633): 
,I/jxcore-log( 6633): 2015-12-18T17:58:29.375Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 6633): 
,I/jxcore-log( 6633): 2015-12-18T17:58:29.394Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 6633): 
,I/jxcore-log( 6633): 2015-12-18T17:58:29.517Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 6633): 
,I/jxcore-log( 6633): 2015-12-18T17:58:29.518Z SendDataConnector.js: got all data for this round
I/jxcore-log( 6633): 
I/jxcore-log( 6633): oneRoundDownNow
I/jxcore-log( 6633): 
,I/jxcore-log( 6633): 2015-12-18T17:58:29.524Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 6633): 
I/jxcore-log( 6633): 2015-12-18T17:58:29.524Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 6633): 
D/io.jxcore.node.ConnectionHelper( 6633): disconnectOutgoingConnection: Trying to close connection to peer with ID 08:EC:A9:50:75:41
I/io.jxcore.node.ConnectionHelper( 6633): closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 08:EC:A9:50:75:41
I/io.jxcore.node.IncomingSocketThread( 6633): close
D/io.jxcore.node.IncomingSocketThread( 6633): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 6633): doStop: Thread ID: 789
D/io.jxcore.node.IncomingSocketThread( 6633): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 6633): doStop: Thread ID: 788
D/io.jxcore.node.IncomingSocketThread( 6633): closeLocalSocketAndStreams: Closing...
D/io.jxcore.node.IncomingSocketThread( 6633): closeLocalSocketAndStreams: Closing the local input stream...
,W/io.jxcore.node.StreamCopyingThread( 6633): Either failed to read from the output stream or write to the input stream (thread ID: 788, thread name: Sender): Socket closed
E/io.jxcore.node.IncomingSocketThread( 6633): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 6633): onDisconnected: Outgoing connection, peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT5572] disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
,D/io.jxcore.node.IncomingSocketThread( 6633): closeLocalSocketAndStreams: Closing the local output stream...
D/io.jxcore.node.IncomingSocketThread( 6633): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.IncomingSocketThread( 6633): closeBluetoothSocketAndStreams
,W/io.jxcore.node.StreamCopyingThread( 6633): Either failed to read from the output stream or write to the input stream (thread ID: 789, thread name: Receiver): bt socket closed, read return: -1
E/io.jxcore.node.IncomingSocketThread( 6633): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
W/io.jxcore.node.ConnectionHelper( 6633): onDisconnected: Outgoing connection, peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT5572] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
,W/bt-btif ( 2530): invalid rfc slot id: 4
,W/io.jxcore.node.StreamCopyingThread( 6633): Either failed to read from the output stream or write to the input stream (thread ID: 787, thread name: Receiver): bt socket closed, read return: -1
E/io.jxcore.node.IncomingSocketThread( 6633): The receiving thread failed with error "Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1", this is likely due to peer having disconnected
,W/io.jxcore.node.ConnectionHelper( 6633): onDisconnected: Incoming connection, peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT5572] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
,D/io.jxcore.node.ConnectionHelper( 6633): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
I/io.jxcore.node.ConnectionHelper( 6633): disconnectOutgoingConnection: Successfully disconnected (peer ID: 08:EC:A9:50:75:41
,E/io.jxcore.node.ConnectionHelper( 6633): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 08:EC:A9:50:75:41
D/io.jxcore.node.ConnectionHelper( 6633): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
D/io.jxcore.node.StreamCopyingThread( 6633): Exiting thread (ID: 788, name: Sender)
,W/bt-btif ( 2530): bta_jv_rfc_port_to_cb(port_handle:0x8):jv handle:0x0 not FOUND
,E/io.jxcore.node.ConnectionHelper( 6633): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 08:EC:A9:50:75:41
D/io.jxcore.node.ConnectionHelper( 6633): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
D/io.jxcore.node.StreamCopyingThread( 6633): Exiting thread (ID: 789, name: Receiver)
,I/io.jxcore.node.ConnectionHelper( 6633): closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 785
D/io.jxcore.node.IncomingSocketThread( 6633): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 6633): doStop: Thread ID: 787
,D/io.jxcore.node.IncomingSocketThread( 6633): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 6633): doStop: Thread ID: 786
D/io.jxcore.node.IncomingSocketThread( 6633): closeLocalSocketAndStreams: Closing...
D/io.jxcore.node.IncomingSocketThread( 6633): closeLocalSocketAndStreams: Closing the local input stream...
D/io.jxcore.node.IncomingSocketThread( 6633): closeLocalSocketAndStreams: Closing the local output stream...
D/io.jxcore.node.IncomingSocketThread( 6633): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.IncomingSocketThread( 6633): closeBluetoothSocketAndStreams
D/io.jxcore.node.ConnectionHelper( 6633): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
D/io.jxcore.node.StreamCopyingThread( 6633): Exiting thread (ID: 787, name: Receiver)
,W/io.jxcore.node.StreamCopyingThread( 6633): Either failed to read from the output stream or write to the input stream (thread ID: 786, thread name: Sender): Socket closed
E/io.jxcore.node.IncomingSocketThread( 6633): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
,W/io.jxcore.node.ConnectionHelper( 6633): onDisconnected: Incoming connection, peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT5572] disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
D/io.jxcore.node.ConnectionHelper( 6633): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
D/io.jxcore.node.StreamCopyingThread( 6633): Exiting thread (ID: 786, name: Sender)
,I/jxcore-log( 6633): 2015-12-18T17:58:29.564Z SendDataConnector.js: Mobile.Disconnect() callback with peer 08:EC:A9:50:75:41
I/jxcore-log( 6633): 
I/jxcore-log( 6633): ---- round done--------
I/jxcore-log( 6633): 
I/jxcore-log( 6633): startWithNextDevice
I/jxcore-log( 6633): 
I/jxcore-log( 6633): device[2]: E0:DB:10:14:E2:C0
I/jxcore-log( 6633): 
I/jxcore-log( 6633): 2015-12-18T17:58:29.565Z SendDataConnector.js: Start called with peer E0:DB:10:14:E2:C0
I/jxcore-log( 6633): 
I/jxcore-log( 6633): 2015-12-18T17:58:29.566Z SendDataConnector.js: doConnect called with peer E0:DB:10:14:E2:C0
I/jxcore-log( 6633): 
I/jxcore-log( 6633): 2015-12-18T17:58:29.566Z SendDataConnector.js: do connect now
I/jxcore-log( 6633): 
I/io.jxcore.node.ConnectionHelper( 6633): connect: Trying to connect to peer with ID E0:DB:10:14:E2:C0
D/io.jxcore.node.ConnectionHelper( 6633): hasConnection: No connection with peer with ID E0:DB:10:14:E2:C0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6633): connect: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT6460]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6633): connect: Trying to start connecting to Note4-1 in address E0:DB:10:14:E2:C0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6633): setInsecureRfcommSocketPort: Using port -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6633): setMaxNumberOfRetries: 0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6633): onConnecting: Note4-1 E0:DB:10:14:E2:C0
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6633): connect: Started connecting to Note4-1 in address E0:DB:10:14:E2:C0
I/io.jxcore.node.ConnectionHelper( 6633): connect: Connection process successfully started (peer ID: E0:DB:10:14:E2:C0)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6633): Trying to connect to peer with address E0:DB:10:14:E2:C0 (thread ID: 790)
W/BluetoothAdapter( 6633): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2530): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/jxcore-log( 6633): 2015-12-18T17:58:29.585Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 6633): 
,E/bt-btm  ( 2530): tBTM_SEC_DEV:0xa6fc489c rs_disc_pending=1
,W/bt-btif ( 2530): bta_dm_check_av:0
,W/bt-btif ( 2530): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 2530): info:x10
,D/        ( 2530): remote version info [e0:db:10:14:e2:c0]: 7, f, 2205
,W/bt-sdp  ( 2530): process_service_search_attr_rsp
,I/ActivityManager(  883): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver: pid=8520 uid=10039 gids={50039, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
,D/BluetoothManagerService(  883): Message: 20
D/BluetoothManagerService(  883): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2b67343f:true
,I/BTConnectionReceiver( 8520): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:14:E2:C0, alias=null, name=Note4-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothBondStateMachine( 2530): bondStateChangeCallback: Status: 0 Address: E0:DB:10:14:E2:C0 newState: 1
,E/bt-btif ( 2530): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2530): Bond State Change Intent:E0:DB:10:14:E2:C0 OldState: 12 NewState: 11
I/BluetoothBondStateMachine( 2530): Entering PendingCommandState State
,I/BluetoothBondStateMachine( 2530): bondStateChangeCallback: Status: 0 Address: E0:DB:10:14:E2:C0 newState: 0
D/BluetoothAdapterProperties( 2530): Removing bonded device:E0:DB:10:14:E2:C0
,I/BluetoothBondStateMachine( 2530): Bond State Change Intent:E0:DB:10:14:E2:C0 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2530): StableState(): Entering Off State
D/BluetoothMetrics( 2530): btclass5a020c
,D/Checkin ( 2530): publish the event [tag = MOT_BT event name = PAIRING]
,W/bt-btif ( 2530): new conn_srvc id:26, app_id:1
W/bt-btif ( 2530): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2530): bta_dm_pm_ssr:2, lat:1200
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6633): onSocketConnected: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT6460]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6633): Socket connection succeeded (using system decided port), total number of attempts: 1 (thread ID: 790)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6633): onBytesWritten: 80 bytes successfully written (thread ID: 791)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6633): Outgoing connection initialized (*handshake* thread ID: 791)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6633): Exiting thread (thread ID: 790)
D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 6633): Entering thread (ID: 791)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6633): onBytesRead: Read 82 bytes successfully (thread ID: 791)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6633): Handshake succeeded with [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT6460]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6633): onHandshakeSucceeded: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT6460]
D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 6633): Exiting thread (ID: 791)
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6633): onConnected: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT6460]
I/io.jxcore.node.ConnectionHelper( 6633): onConnected: Outgoing connection to peer [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT6460]
D/io.jxcore.node.ConnectionHelper( 6633): hasConnection: No connection with peer with ID E0:DB:10:14:E2:C0
W/io.jxcore.node.ConnectionHelper( 6633): modifyListOfDiscoveredPeers: Peer [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT6460] already in the list, will not add again
I/io.jxcore.node.ConnectionHelper( 6633): onConnected: Outgoing socket thread, for peer [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT6460], created successfully
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6633): setInsecureRfcommSocketPort: Will use port -1 when trying to connect
D/io.jxcore.node.ConnectionHelper( 6633): onConnected: The total number of connections is now 1
,D/io.jxcore.node.OutgoingSocketThread( 6633): Entering thread (ID: 792)
D/io.jxcore.node.OutgoingSocketThread( 6633): Server socket local port: 40167
I/io.jxcore.node.OutgoingSocketThread( 6633): Now accepting connections...
,I/ActivityManager(  883): Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=8561 uid=10019 gids={50019, 9997, 3003} abi=armeabi-v7a
,I/BluetoothClassifier( 8520): Bluetooth Device Name: Note4-1
,I/ActivityManager(  883): Killing 8230:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,W/libprocessgroup(  883): failed to open /acct/uid_10090/pid_8230/cgroup.procs: No such file or directory
,W/bt-btif ( 2530): new conn_srvc id:26, app_id:255
W/bt-btif ( 2530): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2530): bta_dm_pm_ssr conn_srvc id:26, app_id:255
,W/bt-btif ( 2530): bta_dm_pm_ssr:2, lat:1200
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6633): Incoming connection accepted
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6633): Incoming connection initialized (thread ID: 793)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6633): Waiting for incoming connections...
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 6633): Entering thread (ID: 793)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6633): onBytesRead: Read 82 bytes successfully (thread ID: 793)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6633): Got valid identity from [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT6460]
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6633): onBytesWritten: 80 bytes successfully written (thread ID: 793)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6633): removeThreadFromList: Removing thread with ID 793
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6633): Handshake thread disposed (thread ID: 793)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6633): onIncomingConnectionConnected: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT6460]
D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 6633): Exiting thread (ID: 793)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6633): onConnected: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT6460]
,I/io.jxcore.node.ConnectionHelper( 6633): onConnected: Incoming connection to peer [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT6460]
,D/io.jxcore.node.ConnectionHelper( 6633): hasConnection: We have an outgoing connection with peer with ID E0:DB:10:14:E2:C0
,W/io.jxcore.node.ConnectionHelper( 6633): onConnected: Already connected with peer [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT6460], continuing anyway...
,W/io.jxcore.node.ConnectionHelper( 6633): modifyListOfDiscoveredPeers: Peer [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT6460] already in the list, will not add again
I/io.jxcore.node.ConnectionHelper( 6633): onConnected: Incoming socket thread, for peer [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT6460], created successfully
D/io.jxcore.node.ConnectionHelper( 6633): onConnected: The total number of connections is now 2
D/io.jxcore.node.IncomingSocketThread( 6633): Entering thread (ID: 794)
,I/jxcore-log( 6633): 2015-12-18T17:58:31.313Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 6633): 
I/io.jxcore.node.IncomingSocketThread( 6633): Local host address: localhost/127.0.0.1, port: 57867
D/io.jxcore.node.IncomingSocketThread( 6633): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 6633): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 6633): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.IncomingSocketThread( 6633): startStreamCopyingThreads: OK
D/io.jxcore.node.IncomingSocketThread( 6633): Exiting thread (ID: 794)
,D/io.jxcore.node.StreamCopyingThread( 6633): Entering thread (ID: 796, name: Receiver)
,D/io.jxcore.node.StreamCopyingThread( 6633): Entering thread (ID: 795, name: Sender)
,I/ActivityManager(  883): Killing 8255:com.android.vending/u0a32 (adj 15): empty #7
,W/libprocessgroup(  883): failed to open /acct/uid_10032/pid_8255/cgroup.procs: No such file or directory
,I/io.jxcore.node.ConnectionHelper( 6633): onListeningForIncomingConnections: Outgoing connection is using port 40167 (peer ID: E0:DB:10:14:E2:C0)
,I/jxcore-log( 6633): 2015-12-18T17:58:31.498Z SendDataConnector.js: CLIENT connected to 40167, error: null
I/jxcore-log( 6633): 
I/jxcore-log( 6633): 2015-12-18T17:58:31.499Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 6633): 
I/io.jxcore.node.IncomingSocketThread( 6633): Incoming data from address: /127.0.0.1, port: 40167
D/io.jxcore.node.IncomingSocketThread( 6633): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 6633): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 6633): setBufferSize: Setting buffer size to 8192 bytes
,I/io.jxcore.node.IncomingSocketThread( 6633): startStreamCopyingThreads: OK
,D/io.jxcore.node.IncomingSocketThread( 6633): Exiting thread (ID: 792)
,I/jxcore-log( 6633): 2015-12-18T17:58:31.508Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 6633): 
,D/io.jxcore.node.StreamCopyingThread( 6633): Entering thread (ID: 797, name: Sender)
D/io.jxcore.node.StreamCopyingThread( 6633): Entering thread (ID: 798, name: Receiver)
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:30000 mC
,I/jxcore-log( 6633): 2015-12-18T17:58:32.012Z SendDataTCPServer.js: TCP/IP server has received 26284 bytes of data
I/jxcore-log( 6633): 
,I/jxcore-log( 6633): 2015-12-18T17:58:32.047Z SendDataTCPServer.js: TCP/IP server has received 28264 bytes of data
I/jxcore-log( 6633): 
,I/jxcore-log( 6633): 2015-12-18T17:58:32.085Z SendDataTCPServer.js: TCP/IP server has received 34748 bytes of data
I/jxcore-log( 6633): 
,I/jxcore-log( 6633): 2015-12-18T17:58:32.091Z SendDataTCPServer.js: TCP/IP server has received 36728 bytes of data
I/jxcore-log( 6633): 
,I/jxcore-log( 6633): 2015-12-18T17:58:32.116Z SendDataTCPServer.js: TCP/IP server has received 38708 bytes of data
I/jxcore-log( 6633): 
,I/jxcore-log( 6633): 2015-12-18T17:58:32.122Z SendDataTCPServer.js: TCP/IP server has received 40688 bytes of data
I/jxcore-log( 6633): 
,I/jxcore-log( 6633): 2015-12-18T17:58:32.129Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 6633): 
,E/bt-btm  ( 2530): tBTM_SEC_DEV:0xa6fc489c rs_disc_pending=0
W/bt-btif ( 2530): bta_dm_check_av:0
,W/bt-btif ( 2530): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 6633): 2015-12-18T17:58:32.202Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 6633): 
,I/jxcore-log( 6633): 2015-12-18T17:58:32.246Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 6633): 
,I/jxcore-log( 6633): 2015-12-18T17:58:32.295Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 6633): 
,I/jxcore-log( 6633): 2015-12-18T17:58:32.300Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 6633): 
,I/jxcore-log( 6633): 2015-12-18T17:58:32.347Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 6633): 
,I/jxcore-log( 6633): 2015-12-18T17:58:32.414Z SendDataTCPServer.js: TCP/IP server has received 42668 bytes of data
I/jxcore-log( 6633): 
,I/jxcore-log( 6633): 2015-12-18T17:58:32.444Z SendDataTCPServer.js: TCP/IP server has received 46628 bytes of data
I/jxcore-log( 6633): 
,I/jxcore-log( 6633): 2015-12-18T17:58:32.511Z SendDataTCPServer.js: TCP/IP server has received 48608 bytes of data
I/jxcore-log( 6633): 
,I/jxcore-log( 6633): 2015-12-18T17:58:32.517Z SendDataTCPServer.js: TCP/IP server has received 50588 bytes of data
I/jxcore-log( 6633): 
,I/jxcore-log( 6633): 2015-12-18T17:58:32.524Z SendDataTCPServer.js: TCP/IP server has received 52568 bytes of data
I/jxcore-log( 6633): 
,I/jxcore-log( 6633): 2015-12-18T17:58:32.581Z SendDataTCPServer.js: TCP/IP server has received 54548 bytes of data
I/jxcore-log( 6633): 
,I/jxcore-log( 6633): 2015-12-18T17:58:32.587Z SendDataTCPServer.js: TCP/IP server has received 56528 bytes of data
I/jxcore-log( 6633): 
,I/jxcore-log( 6633): 2015-12-18T17:58:32.592Z SendDataTCPServer.js: TCP/IP server has received 58508 bytes of data
I/jxcore-log( 6633): 
,I/jxcore-log( 6633): 2015-12-18T17:58:32.601Z SendDataTCPServer.js: TCP/IP server has received 60488 bytes of data
I/jxcore-log( 6633): 
,I/jxcore-log( 6633): 2015-12-18T17:58:32.686Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 6633): 
,I/jxcore-log( 6633): 2015-12-18T17:58:32.691Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 6633): 
,I/jxcore-log( 6633): 2015-12-18T17:58:32.695Z SendDataTCPServer.js: TCP/IP server has received 62468 bytes of data
I/jxcore-log( 6633): 
,I/jxcore-log( 6633): 2015-12-18T17:58:32.724Z SendDataTCPServer.js: TCP/IP server has received 76328 bytes of data
I/jxcore-log( 6633): 
,I/jxcore-log( 6633): 2015-12-18T17:58:32.732Z SendDataTCPServer.js: TCP/IP server has received 80288 bytes of data
I/jxcore-log( 6633): 
,I/jxcore-log( 6633): 2015-12-18T17:58:32.737Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 6633): 
I/jxcore-log( 6633): 2015-12-18T17:58:32.738Z SendDataConnector.js: got all data for this round
I/jxcore-log( 6633): 
I/jxcore-log( 6633): oneRoundDownNow
I/jxcore-log( 6633): 
,I/jxcore-log( 6633): 2015-12-18T17:58:32.741Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 6633): 
I/jxcore-log( 6633): 2015-12-18T17:58:32.742Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 6633): 
,D/io.jxcore.node.ConnectionHelper( 6633): disconnectOutgoingConnection: Trying to close connection to peer with ID E0:DB:10:14:E2:C0
I/io.jxcore.node.ConnectionHelper( 6633): closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: E0:DB:10:14:E2:C0
I/io.jxcore.node.IncomingSocketThread( 6633): close
D/io.jxcore.node.IncomingSocketThread( 6633): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 6633): doStop: Thread ID: 798
D/io.jxcore.node.IncomingSocketThread( 6633): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 6633): doStop: Thread ID: 797
D/io.jxcore.node.IncomingSocketThread( 6633): closeLocalSocketAndStreams: Closing...
D/io.jxcore.node.IncomingSocketThread( 6633): closeLocalSocketAndStreams: Closing the local input stream...
,W/io.jxcore.node.StreamCopyingThread( 6633): Either failed to read from the output stream or write to the input stream (thread ID: 797, thread name: Sender): Socket closed
E/io.jxcore.node.IncomingSocketThread( 6633): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 6633): onDisconnected: Outgoing connection, peer [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT6460] disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
,D/io.jxcore.node.IncomingSocketThread( 6633): closeLocalSocketAndStreams: Closing the local output stream...
D/io.jxcore.node.IncomingSocketThread( 6633): closeLocalSocketAndStreams: Closing the localhost socket...
,I/io.jxcore.node.IncomingSocketThread( 6633): closeBluetoothSocketAndStreams
,W/io.jxcore.node.StreamCopyingThread( 6633): Either failed to read from the output stream or write to the input stream (thread ID: 798, thread name: Receiver): bt socket closed, read return: -1
E/io.jxcore.node.IncomingSocketThread( 6633): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
W/io.jxcore.node.ConnectionHelper( 6633): onDisconnected: Outgoing connection, peer [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT6460] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
,D/io.jxcore.node.ConnectionHelper( 6633): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
I/io.jxcore.node.ConnectionHelper( 6633): disconnectOutgoingConnection: Successfully disconnected (peer ID: E0:DB:10:14:E2:C0
,E/io.jxcore.node.ConnectionHelper( 6633): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID E0:DB:10:14:E2:C0
D/io.jxcore.node.ConnectionHelper( 6633): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
D/io.jxcore.node.StreamCopyingThread( 6633): Exiting thread (ID: 797, name: Sender)
,E/io.jxcore.node.ConnectionHelper( 6633): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID E0:DB:10:14:E2:C0
D/io.jxcore.node.ConnectionHelper( 6633): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
D/io.jxcore.node.StreamCopyingThread( 6633): Exiting thread (ID: 798, name: Receiver)
,I/jxcore-log( 6633): 2015-12-18T17:58:32.761Z SendDataConnector.js: Mobile.Disconnect() callback with peer E0:DB:10:14:E2:C0
I/jxcore-log( 6633): 
I/jxcore-log( 6633): ---- round done--------
I/jxcore-log( 6633): 
I/jxcore-log( 6633): startWithNextDevice
I/jxcore-log( 6633): 
I/jxcore-log( 6633): device[3]: 7C:F9:0E:51:18:22
I/jxcore-log( 6633): 
I/jxcore-log( 6633): 2015-12-18T17:58:32.762Z SendDataConnector.js: Start called with peer 7C:F9:0E:51:18:22
I/jxcore-log( 6633): 
I/jxcore-log( 6633): 2015-12-18T17:58:32.763Z SendDataConnector.js: doConnect called with peer 7C:F9:0E:51:18:22
I/jxcore-log( 6633): 
I/jxcore-log( 6633): 2015-12-18T17:58:32.763Z SendDataConnector.js: do connect now
I/jxcore-log( 6633): 
,I/io.jxcore.node.ConnectionHelper( 6633): connect: Trying to connect to peer with ID 7C:F9:0E:51:18:22
D/io.jxcore.node.ConnectionHelper( 6633): hasConnection: No connection with peer with ID 7C:F9:0E:51:18:22
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6633): connect: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT3826]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6633): connect: Trying to start connecting to null in address 7C:F9:0E:51:18:22
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6633): setInsecureRfcommSocketPort: Using port -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6633): setMaxNumberOfRetries: 0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6633): onConnecting: null 7C:F9:0E:51:18:22
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6633): connect: Started connecting to null in address 7C:F9:0E:51:18:22
I/io.jxcore.node.ConnectionHelper( 6633): connect: Connection process successfully started (peer ID: 7C:F9:0E:51:18:22)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6633): Trying to connect to peer with address 7C:F9:0E:51:18:22 (thread ID: 799)
W/BluetoothAdapter( 6633): getBluetoothService() called with no BluetoothManagerCallback
,I/jxcore-log( 6633): 2015-12-18T17:58:32.771Z SendDataTCPServer.js: TCP/IP server has received 82268 bytes of data
I/jxcore-log( 6633): 
,D/BTIF_SOCK( 2530): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/jxcore-log( 6633): 2015-12-18T17:58:32.782Z SendDataTCPServer.js: TCP/IP server has received 94148 bytes of data
I/jxcore-log( 6633): 
,I/jxcore-log( 6633): 2015-12-18T17:58:32.799Z SendDataTCPServer.js: TCP/IP server has received 96128 bytes of data
I/jxcore-log( 6633): 
,I/jxcore-log( 6633): 2015-12-18T17:58:32.998Z SendDataTCPServer.js: TCP/IP server has received 98108 bytes of data
I/jxcore-log( 6633): 
,W/bt-btif ( 2530): bta_jv_rfc_port_to_cb(port_handle:0xa):jv handle:0x0 not FOUND
,I/jxcore-log( 6633): 2015-12-18T17:58:33.034Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
I/jxcore-log( 6633): 
,W/bt-btif ( 2530): invalid rfc slot id: 6
,W/io.jxcore.node.StreamCopyingThread( 6633): Either failed to read from the output stream or write to the input stream (thread ID: 796, thread name: Receiver): bt socket closed, read return: -1
E/io.jxcore.node.IncomingSocketThread( 6633): The receiving thread failed with error "Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1", this is likely due to peer having disconnected
W/io.jxcore.node.ConnectionHelper( 6633): onDisconnected: Incoming connection, peer [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT6460] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
I/io.jxcore.node.ConnectionHelper( 6633): closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 794
,D/io.jxcore.node.IncomingSocketThread( 6633): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 6633): doStop: Thread ID: 796
D/io.jxcore.node.IncomingSocketThread( 6633): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 6633): doStop: Thread ID: 795
D/io.jxcore.node.IncomingSocketThread( 6633): closeLocalSocketAndStreams: Closing...
D/io.jxcore.node.IncomingSocketThread( 6633): closeLocalSocketAndStreams: Closing the local input stream...
D/io.jxcore.node.IncomingSocketThread( 6633): closeLocalSocketAndStreams: Closing the local output stream...
D/io.jxcore.node.IncomingSocketThread( 6633): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.IncomingSocketThread( 6633): closeBluetoothSocketAndStreams
,W/io.jxcore.node.StreamCopyingThread( 6633): Either failed to read from the output stream or write to the input stream (thread ID: 795, thread name: Sender): Socket closed
E/io.jxcore.node.IncomingSocketThread( 6633): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 6633): onDisconnected: Incoming connection, peer [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT6460] disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
,D/io.jxcore.node.ConnectionHelper( 6633): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
D/io.jxcore.node.StreamCopyingThread( 6633): Exiting thread (ID: 796, name: Receiver)
,D/io.jxcore.node.ConnectionHelper( 6633): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
D/io.jxcore.node.StreamCopyingThread( 6633): Exiting thread (ID: 795, name: Sender)
,I/jxcore-log( 6633): 2015-12-18T17:58:33.087Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 6633): 
,W/bt-btif ( 2530): info:x10
,D/        ( 2530): remote version info [7c:f9:0e:51:18:22]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 2530): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 2530): process_service_search_attr_rsp
,I/BluetoothBondStateMachine( 2530): bondStateChangeCallback: Status: 0 Address: 7C:F9:0E:51:18:22 newState: 1
E/bt-btif ( 2530): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2530): Bond State Change Intent:7C:F9:0E:51:18:22 OldState: 10 NewState: 11
,I/BluetoothBondStateMachine( 2530): Entering PendingCommandState State
,I/BluetoothBondStateMachine( 2530): bondStateChangeCallback: Status: 0 Address: 7C:F9:0E:51:18:22 newState: 0
,D/BluetoothAdapterProperties( 2530): Failed to remove device: 7C:F9:0E:51:18:22
,I/BluetoothBondStateMachine( 2530): Bond State Change Intent:7C:F9:0E:51:18:22 OldState: 11 NewState: 10
,E/bt-btm  ( 2530): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2530): onReceive
,I/BluetoothBondStateMachine( 2530): StableState(): Entering Off State
,D/BluetoothMetrics( 2530): btclass5a020c
,D/Checkin ( 2530): publish the event [tag = MOT_BT event name = PAIRING]
,W/bt-btif ( 2530): new conn_srvc id:26, app_id:1
W/bt-btif ( 2530): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2530): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6633): onSocketConnected: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT3826]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6633): Socket connection succeeded (using system decided port), total number of attempts: 1 (thread ID: 799)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6633): onBytesWritten: 80 bytes successfully written (thread ID: 800)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6633): Outgoing connection initialized (*handshake* thread ID: 800)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6633): Exiting thread (thread ID: 799)
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 6633): Entering thread (ID: 800)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6633): onBytesRead: Read 83 bytes successfully (thread ID: 800)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6633): Handshake succeeded with [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT3826]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6633): onHandshakeSucceeded: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT3826]
D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 6633): Exiting thread (ID: 800)
,I/BTConnectionReceiver( 8520): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=08:EC:A9:50:75:41, alias=null, name=A3-1, majorDeviceClass=512, deviceClass=524]
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6633): onConnected: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT3826]
I/io.jxcore.node.ConnectionHelper( 6633): onConnected: Outgoing connection to peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT3826]
D/io.jxcore.node.ConnectionHelper( 6633): hasConnection: No connection with peer with ID 7C:F9:0E:51:18:22
W/io.jxcore.node.ConnectionHelper( 6633): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT3826] already in the list, will not add again
I/io.jxcore.node.ConnectionHelper( 6633): onConnected: Outgoing socket thread, for peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT3826], created successfully
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6633): setInsecureRfcommSocketPort: Will use port -1 when trying to connect
,D/io.jxcore.node.ConnectionHelper( 6633): onConnected: The total number of connections is now 1
,I/BluetoothClassifier( 8520): Bluetooth Device Name: A3-1
,D/io.jxcore.node.OutgoingSocketThread( 6633): Entering thread (ID: 801)
D/io.jxcore.node.OutgoingSocketThread( 6633): Server socket local port: 60436
I/io.jxcore.node.OutgoingSocketThread( 6633): Now accepting connections...
,W/bt-btif ( 2530): new conn_srvc id:26, app_id:255
W/bt-btif ( 2530): bta_dm_pm_ssr conn_srvc id:26, app_id:1
,W/bt-btif ( 2530): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 2530): bta_dm_pm_ssr:2, lat:1200
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6633): Incoming connection accepted
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6633): Incoming connection initialized (thread ID: 802)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6633): Waiting for incoming connections...
D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 6633): Entering thread (ID: 802)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6633): onBytesRead: Read 83 bytes successfully (thread ID: 802)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6633): Got valid identity from [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT3826]
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6633): onBytesWritten: 80 bytes successfully written (thread ID: 802)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6633): removeThreadFromList: Removing thread with ID 802
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6633): Handshake thread disposed (thread ID: 802)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6633): onIncomingConnectionConnected: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT3826]
D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 6633): Exiting thread (ID: 802)
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6633): onConnected: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT3826]
I/io.jxcore.node.ConnectionHelper( 6633): onConnected: Incoming connection to peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT3826]
D/io.jxcore.node.ConnectionHelper( 6633): hasConnection: We have an outgoing connection with peer with ID 7C:F9:0E:51:18:22
W/io.jxcore.node.ConnectionHelper( 6633): onConnected: Already connected with peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT3826], continuing anyway...
W/io.jxcore.node.ConnectionHelper( 6633): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT3826] already in the list, will not add again
,I/io.jxcore.node.ConnectionHelper( 6633): onConnected: Incoming socket thread, for peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT3826], created successfully
D/io.jxcore.node.ConnectionHelper( 6633): onConnected: The total number of connections is now 2
D/io.jxcore.node.IncomingSocketThread( 6633): Entering thread (ID: 803)
,I/io.jxcore.node.IncomingSocketThread( 6633): Local host address: localhost/127.0.0.1, port: 57867
,D/io.jxcore.node.IncomingSocketThread( 6633): Setting local streams and starting stream copying threads...
,I/io.jxcore.node.StreamCopyingThread( 6633): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 6633): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.IncomingSocketThread( 6633): startStreamCopyingThreads: OK
D/io.jxcore.node.IncomingSocketThread( 6633): Exiting thread (ID: 803)
D/io.jxcore.node.StreamCopyingThread( 6633): Entering thread (ID: 805, name: Receiver)
I/jxcore-log( 6633): 2015-12-18T17:58:33.631Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 6633): 
D/io.jxcore.node.StreamCopyingThread( 6633): Entering thread (ID: 804, name: Sender)
,I/io.jxcore.node.ConnectionHelper( 6633): onListeningForIncomingConnections: Outgoing connection is using port 60436 (peer ID: 7C:F9:0E:51:18:22)
,I/jxcore-log( 6633): 2015-12-18T17:58:33.828Z SendDataConnector.js: CLIENT connected to 60436, error: null
I/jxcore-log( 6633): 
,I/jxcore-log( 6633): 2015-12-18T17:58:33.828Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 6633): 
,I/io.jxcore.node.IncomingSocketThread( 6633): Incoming data from address: /127.0.0.1, port: 60436
,D/io.jxcore.node.IncomingSocketThread( 6633): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 6633): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 6633): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.IncomingSocketThread( 6633): startStreamCopyingThreads: OK
D/io.jxcore.node.IncomingSocketThread( 6633): Exiting thread (ID: 801)
I/jxcore-log( 6633): 2015-12-18T17:58:33.839Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 6633): 
,D/io.jxcore.node.StreamCopyingThread( 6633): Entering thread (ID: 807, name: Receiver)
D/io.jxcore.node.StreamCopyingThread( 6633): Entering thread (ID: 806, name: Sender)
,D/MDMCTBK (  291): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 1 
D/MDMCTBK (  291): Event received = CTRL-EVENT-BSS-REMOVED 1 
,I/jxcore-log( 6633): 2015-12-18T17:58:34.354Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 6633): 
,I/jxcore-log( 6633): 2015-12-18T17:58:34.365Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 6633): 
,I/jxcore-log( 6633): 2015-12-18T17:58:34.372Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 6633): 
,I/jxcore-log( 6633): 2015-12-18T17:58:34.428Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 6633): 
,I/jxcore-log( 6633): 2015-12-18T17:58:34.464Z SendDataTCPServer.js: TCP/IP server has received 9900 bytes of data
I/jxcore-log( 6633): 
,I/jxcore-log( 6633): 2015-12-18T17:58:34.483Z SendDataTCPServer.js: TCP/IP server has received 11880 bytes of data
I/jxcore-log( 6633): 
,I/jxcore-log( 6633): 2015-12-18T17:58:34.498Z SendDataTCPServer.js: TCP/IP server has received 13860 bytes of data
I/jxcore-log( 6633): 
,D/        ( 2530): PORT_WriteDataCO: tx queue is full,tx.queue_size:10444,tx.queue.count:11,available:23716
,I/jxcore-log( 6633): 2015-12-18T17:58:34.529Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 6633): 
,I/jxcore-log( 6633): 2015-12-18T17:58:34.534Z SendDataTCPServer.js: TCP/IP server has received 18364 bytes of data
I/jxcore-log( 6633): 
,I/jxcore-log( 6633): 2015-12-18T17:58:34.574Z SendDataTCPServer.js: TCP/IP server has received 20344 bytes of data
I/jxcore-log( 6633): 
,I/jxcore-log( 6633): 2015-12-18T17:58:34.626Z SendDataTCPServer.js: TCP/IP server has received 22324 bytes of data
I/jxcore-log( 6633): 
,I/jxcore-log( 6633): 2015-12-18T17:58:34.664Z SendDataTCPServer.js: TCP/IP server has received 26284 bytes of data
I/jxcore-log( 6633): 
,I/jxcore-log( 6633): 2015-12-18T17:58:34.667Z SendDataTCPServer.js: TCP/IP server has received 28264 bytes of data
I/jxcore-log( 6633): 
,D/        ( 2530): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:13816
,I/jxcore-log( 6633): 2015-12-18T17:58:34.723Z SendDataTCPServer.js: TCP/IP server has received 30244 bytes of data
I/jxcore-log( 6633): 
,I/jxcore-log( 6633): 2015-12-18T17:58:34.731Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 6633): 
,I/jxcore-log( 6633): 2015-12-18T17:58:34.769Z SendDataTCPServer.js: TCP/IP server has received 32224 bytes of data
I/jxcore-log( 6633): 
,I/jxcore-log( 6633): 2015-12-18T17:58:34.805Z SendDataTCPServer.js: TCP/IP server has received 36728 bytes of data
I/jxcore-log( 6633): 
,I/jxcore-log( 6633): 2015-12-18T17:58:34.810Z SendDataTCPServer.js: TCP/IP server has received 38708 bytes of data
I/jxcore-log( 6633): 
,I/jxcore-log( 6633): 2015-12-18T17:58:34.820Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 6633): 
,D/        ( 2530): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:3916
,I/jxcore-log( 6633): 2015-12-18T17:58:34.931Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 6633): 
,I/jxcore-log( 6633): 2015-12-18T17:58:34.937Z SendDataTCPServer.js: TCP/IP server has received 40688 bytes of data
I/jxcore-log( 6633): 
,I/jxcore-log( 6633): 2015-12-18T17:58:34.953Z SendDataTCPServer.js: TCP/IP server has received 42668 bytes of data
I/jxcore-log( 6633): 
,I/jxcore-log( 6633): 2015-12-18T17:58:34.985Z SendDataTCPServer.js: TCP/IP server has received 48608 bytes of data
I/jxcore-log( 6633): 
,I/jxcore-log( 6633): 2015-12-18T17:58:35.025Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 6633): 
,I/jxcore-log( 6633): 2015-12-18T17:58:35.104Z SendDataTCPServer.js: TCP/IP server has received 50588 bytes of data
I/jxcore-log( 6633): 
,I/jxcore-log( 6633): 2015-12-18T17:58:35.113Z SendDataTCPServer.js: TCP/IP server has received 52568 bytes of data
I/jxcore-log( 6633): 
,I/jxcore-log( 6633): 2015-12-18T17:58:35.144Z SendDataTCPServer.js: TCP/IP server has received 56528 bytes of data
I/jxcore-log( 6633): 
,I/jxcore-log( 6633): 2015-12-18T17:58:35.184Z SendDataTCPServer.js: TCP/IP server has received 58508 bytes of data
I/jxcore-log( 6633): 
,I/jxcore-log( 6633): 2015-12-18T17:58:35.190Z SendDataTCPServer.js: TCP/IP server has received 60488 bytes of data
I/jxcore-log( 6633): 
,I/jxcore-log( 6633): 2015-12-18T17:58:35.226Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 6633): 
,I/jxcore-log( 6633): 2015-12-18T17:58:35.239Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 6633): 
,I/jxcore-log( 6633): 2015-12-18T17:58:35.253Z SendDataTCPServer.js: TCP/IP server has received 62468 bytes of data
I/jxcore-log( 6633): 
,I/jxcore-log( 6633): 2015-12-18T17:58:35.284Z SendDataTCPServer.js: TCP/IP server has received 68408 bytes of data
I/jxcore-log( 6633): 
,I/jxcore-log( 6633): 2015-12-18T17:58:35.339Z SendDataTCPServer.js: TCP/IP server has received 70388 bytes of data
I/jxcore-log( 6633): 
,I/jxcore-log( 6633): 2015-12-18T17:58:35.379Z SendDataTCPServer.js: TCP/IP server has received 72368 bytes of data
I/jxcore-log( 6633): 
,I/jxcore-log( 6633): 2015-12-18T17:58:35.415Z SendDataTCPServer.js: TCP/IP server has received 76328 bytes of data
I/jxcore-log( 6633): 
,I/jxcore-log( 6633): 2015-12-18T17:58:35.432Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 6633): 
,I/jxcore-log( 6633): 2015-12-18T17:58:35.454Z SendDataTCPServer.js: TCP/IP server has received 82268 bytes of data
I/jxcore-log( 6633): 
,I/jxcore-log( 6633): 2015-12-18T17:58:35.489Z SendDataTCPServer.js: TCP/IP server has received 84248 bytes of data
I/jxcore-log( 6633): 
,I/jxcore-log( 6633): 2015-12-18T17:58:35.557Z SendDataTCPServer.js: TCP/IP server has received 86228 bytes of data
I/jxcore-log( 6633): 
,I/jxcore-log( 6633): 2015-12-18T17:58:35.577Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 6633): 
,I/jxcore-log( 6633): 2015-12-18T17:58:35.578Z SendDataConnector.js: got all data for this round
I/jxcore-log( 6633): 
,I/jxcore-log( 6633): oneRoundDownNow
I/jxcore-log( 6633): 
I/jxcore-log( 6633): 2015-12-18T17:58:35.578Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 6633): 
I/jxcore-log( 6633): 2015-12-18T17:58:35.579Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 6633): 
D/io.jxcore.node.ConnectionHelper( 6633): disconnectOutgoingConnection: Trying to close connection to peer with ID 7C:F9:0E:51:18:22
I/io.jxcore.node.ConnectionHelper( 6633): closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 7C:F9:0E:51:18:22
I/io.jxcore.node.IncomingSocketThread( 6633): close
D/io.jxcore.node.IncomingSocketThread( 6633): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 6633): doStop: Thread ID: 807
D/io.jxcore.node.IncomingSocketThread( 6633): close: Stopping sending thread...
,I/io.jxcore.node.StreamCopyingThread( 6633): doStop: Thread ID: 806
D/io.jxcore.node.IncomingSocketThread( 6633): closeLocalSocketAndStreams: Closing...
D/io.jxcore.node.IncomingSocketThread( 6633): closeLocalSocketAndStreams: Closing the local input stream...
,W/io.jxcore.node.StreamCopyingThread( 6633): Either failed to read from the output stream or write to the input stream (thread ID: 806, thread name: Sender): Socket closed
E/io.jxcore.node.IncomingSocketThread( 6633): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 6633): onDisconnected: Outgoing connection, peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT3826] disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
,D/io.jxcore.node.IncomingSocketThread( 6633): closeLocalSocketAndStreams: Closing the local output stream...
,D/io.jxcore.node.IncomingSocketThread( 6633): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.IncomingSocketThread( 6633): closeBluetoothSocketAndStreams
,W/io.jxcore.node.StreamCopyingThread( 6633): Either failed to read from the output stream or write to the input stream (thread ID: 807, thread name: Receiver): bt socket closed, read return: -1
,E/io.jxcore.node.IncomingSocketThread( 6633): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
W/io.jxcore.node.ConnectionHelper( 6633): onDisconnected: Outgoing connection, peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT3826] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
,D/io.jxcore.node.ConnectionHelper( 6633): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,I/io.jxcore.node.ConnectionHelper( 6633): disconnectOutgoingConnection: Successfully disconnected (peer ID: 7C:F9:0E:51:18:22
,E/io.jxcore.node.ConnectionHelper( 6633): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 7C:F9:0E:51:18:22
,D/io.jxcore.node.ConnectionHelper( 6633): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,D/io.jxcore.node.StreamCopyingThread( 6633): Exiting thread (ID: 806, name: Sender)
,E/io.jxcore.node.ConnectionHelper( 6633): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 7C:F9:0E:51:18:22
,D/io.jxcore.node.ConnectionHelper( 6633): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
D/io.jxcore.node.StreamCopyingThread( 6633): Exiting thread (ID: 807, name: Receiver)
,I/jxcore-log( 6633): 2015-12-18T17:58:35.609Z SendDataConnector.js: Mobile.Disconnect() callback with peer 7C:F9:0E:51:18:22
I/jxcore-log( 6633): 
,I/jxcore-log( 6633): ---- round done--------
I/jxcore-log( 6633): 
I/jxcore-log( 6633): startWithNextDevice
I/jxcore-log( 6633): 
I/jxcore-log( 6633): device[4]: 7C:F9:0E:37:96:AB
I/jxcore-log( 6633): 
I/jxcore-log( 6633): 2015-12-18T17:58:35.612Z SendDataConnector.js: Start called with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 6633): 
I/jxcore-log( 6633): 2015-12-18T17:58:35.612Z SendDataConnector.js: doConnect called with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 6633): 
,I/jxcore-log( 6633): 2015-12-18T17:58:35.612Z SendDataConnector.js: do connect now
I/jxcore-log( 6633): 
,I/io.jxcore.node.ConnectionHelper( 6633): connect: Trying to connect to peer with ID 7C:F9:0E:37:96:AB
D/io.jxcore.node.ConnectionHelper( 6633): hasConnection: No connection with peer with ID 7C:F9:0E:37:96:AB
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6633): connect: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1532]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6633): connect: Trying to start connecting to A5-1 in address 7C:F9:0E:37:96:AB
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6633): setInsecureRfcommSocketPort: Using port -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6633): setMaxNumberOfRetries: 0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6633): onConnecting: A5-1 7C:F9:0E:37:96:AB
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6633): connect: Started connecting to A5-1 in address 7C:F9:0E:37:96:AB
I/io.jxcore.node.ConnectionHelper( 6633): connect: Connection process successfully started (peer ID: 7C:F9:0E:37:96:AB)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6633): Trying to connect to peer with address 7C:F9:0E:37:96:AB (thread ID: 808)
,W/BluetoothAdapter( 6633): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2530): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/jxcore-log( 6633): 2015-12-18T17:58:35.629Z SendDataTCPServer.js: TCP/IP server has received 92168 bytes of data
I/jxcore-log( 6633): 
,I/jxcore-log( 6633): 2015-12-18T17:58:35.639Z SendDataTCPServer.js: TCP/IP server has received 96128 bytes of data
I/jxcore-log( 6633): 
,I/jxcore-log( 6633): 2015-12-18T17:58:35.650Z SendDataTCPServer.js: TCP/IP server has received 98108 bytes of data
I/jxcore-log( 6633): 
,D/btif_config_util( 2530): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2530): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2530): onReceive
,I/BTConnectionReceiver( 8520): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:14:E2:C0, alias=null, name=Note4-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 8520): Bluetooth Device Name: Note4-1
,I/jxcore-log( 6633): 2015-12-18T17:58:38.171Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
I/jxcore-log( 6633): 
,W/bt-btif ( 2530): bta_jv_rfc_port_to_cb(port_handle:0xc):jv handle:0x0 not FOUND
,W/bt-btif ( 2530): invalid rfc slot id: 8
,W/io.jxcore.node.StreamCopyingThread( 6633): Either failed to read from the output stream or write to the input stream (thread ID: 805, thread name: Receiver): bt socket closed, read return: -1
,E/io.jxcore.node.IncomingSocketThread( 6633): The receiving thread failed with error "Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1", this is likely due to peer having disconnected
W/io.jxcore.node.ConnectionHelper( 6633): onDisconnected: Incoming connection, peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT3826] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
I/io.jxcore.node.ConnectionHelper( 6633): closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 803
D/io.jxcore.node.IncomingSocketThread( 6633): close: Stopping receiving thread...
,I/io.jxcore.node.StreamCopyingThread( 6633): doStop: Thread ID: 805
,D/io.jxcore.node.IncomingSocketThread( 6633): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 6633): doStop: Thread ID: 804
D/io.jxcore.node.IncomingSocketThread( 6633): closeLocalSocketAndStreams: Closing...
D/io.jxcore.node.IncomingSocketThread( 6633): closeLocalSocketAndStreams: Closing the local input stream...
D/io.jxcore.node.IncomingSocketThread( 6633): closeLocalSocketAndStreams: Closing the local output stream...
D/io.jxcore.node.IncomingSocketThread( 6633): closeLocalSocketAndStreams: Closing the localhost socket...
,I/io.jxcore.node.IncomingSocketThread( 6633): closeBluetoothSocketAndStreams
,W/io.jxcore.node.StreamCopyingThread( 6633): Either failed to read from the output stream or write to the input stream (thread ID: 804, thread name: Sender): Socket closed
,E/io.jxcore.node.IncomingSocketThread( 6633): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
,W/io.jxcore.node.ConnectionHelper( 6633): onDisconnected: Incoming connection, peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT3826] disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
,D/io.jxcore.node.ConnectionHelper( 6633): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
D/io.jxcore.node.StreamCopyingThread( 6633): Exiting thread (ID: 805, name: Receiver)
,D/io.jxcore.node.ConnectionHelper( 6633): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
D/io.jxcore.node.StreamCopyingThread( 6633): Exiting thread (ID: 804, name: Sender)
,I/jxcore-log( 6633): 2015-12-18T17:58:38.240Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 6633): 
,W/bt-btif ( 2530): info:x10
,D/        ( 2530): remote version info [7c:f9:0e:37:96:ab]: 7, 1d, 7d3
,W/bt-sdp  ( 2530): process_service_search_attr_rsp
,I/BTConnectionReceiver( 8520): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:37:96:AB, alias=null, name=A5-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 8520): Bluetooth Device Name: A5-1
,I/BluetoothBondStateMachine( 2530): bondStateChangeCallback: Status: 0 Address: 7C:F9:0E:37:96:AB newState: 1
E/bt-btif ( 2530): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2530): Bond State Change Intent:7C:F9:0E:37:96:AB OldState: 12 NewState: 11
I/BluetoothBondStateMachine( 2530): Entering PendingCommandState State
,I/BluetoothBondStateMachine( 2530): bondStateChangeCallback: Status: 0 Address: 7C:F9:0E:37:96:AB newState: 0
,D/BluetoothAdapterProperties( 2530): Removing bonded device:7C:F9:0E:37:96:AB
,I/BluetoothBondStateMachine( 2530): Bond State Change Intent:7C:F9:0E:37:96:AB OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2530): StableState(): Entering Off State
,D/BluetoothMetrics( 2530): btclass5a020c
,D/Checkin ( 2530): publish the event [tag = MOT_BT event name = PAIRING]
,W/bt-btif ( 2530): new conn_srvc id:26, app_id:1
W/bt-btif ( 2530): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2530): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6633): onSocketConnected: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1532]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6633): Socket connection succeeded (using system decided port), total number of attempts: 1 (thread ID: 808)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6633): onBytesWritten: 80 bytes successfully written (thread ID: 809)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6633): Outgoing connection initialized (*handshake* thread ID: 809)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6633): Exiting thread (thread ID: 808)
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 6633): Entering thread (ID: 809)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6633): onBytesRead: Read 83 bytes successfully (thread ID: 809)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6633): Handshake succeeded with [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1532]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6633): onHandshakeSucceeded: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1532]
D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 6633): Exiting thread (ID: 809)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6633): onConnected: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1532]
,I/io.jxcore.node.ConnectionHelper( 6633): onConnected: Outgoing connection to peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1532]
D/io.jxcore.node.ConnectionHelper( 6633): hasConnection: No connection with peer with ID 7C:F9:0E:37:96:AB
W/io.jxcore.node.ConnectionHelper( 6633): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1532] already in the list, will not add again
,I/io.jxcore.node.ConnectionHelper( 6633): onConnected: Outgoing socket thread, for peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1532], created successfully
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6633): setInsecureRfcommSocketPort: Will use port -1 when trying to connect
D/io.jxcore.node.ConnectionHelper( 6633): onConnected: The total number of connections is now 1
,D/io.jxcore.node.OutgoingSocketThread( 6633): Entering thread (ID: 810)
,D/io.jxcore.node.OutgoingSocketThread( 6633): Server socket local port: 58469
I/io.jxcore.node.OutgoingSocketThread( 6633): Now accepting connections...
,W/bt-btif ( 2530): new conn_srvc id:26, app_id:255
W/bt-btif ( 2530): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2530): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 2530): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6633): Incoming connection accepted
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6633): Incoming connection initialized (thread ID: 811)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6633): Waiting for incoming connections...
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 6633): Entering thread (ID: 811)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6633): onBytesRead: Read 83 bytes successfully (thread ID: 811)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6633): Got valid identity from [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1532]
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6633): onBytesWritten: 80 bytes successfully written (thread ID: 811)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6633): removeThreadFromList: Removing thread with ID 811
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6633): Handshake thread disposed (thread ID: 811)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6633): onIncomingConnectionConnected: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1532]
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6633): onConnected: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1532]
,I/io.jxcore.node.ConnectionHelper( 6633): onConnected: Incoming connection to peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1532]
,D/io.jxcore.node.ConnectionHelper( 6633): hasConnection: We have an outgoing connection with peer with ID 7C:F9:0E:37:96:AB
,W/io.jxcore.node.ConnectionHelper( 6633): onConnected: Already connected with peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1532], continuing anyway...
W/io.jxcore.node.ConnectionHelper( 6633): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1532] already in the list, will not add again
,I/io.jxcore.node.ConnectionHelper( 6633): onConnected: Incoming socket thread, for peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1532], created successfully
,D/io.jxcore.node.ConnectionHelper( 6633): onConnected: The total number of connections is now 2
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 6633): Exiting thread (ID: 811)
,D/io.jxcore.node.IncomingSocketThread( 6633): Entering thread (ID: 812)
,I/io.jxcore.node.IncomingSocketThread( 6633): Local host address: localhost/127.0.0.1, port: 57867
,D/io.jxcore.node.IncomingSocketThread( 6633): Setting local streams and starting stream copying threads...
,I/io.jxcore.node.StreamCopyingThread( 6633): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 6633): setBufferSize: Setting buffer size to 8192 bytes
,I/jxcore-log( 6633): 2015-12-18T17:58:38.886Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 6633): 
,I/io.jxcore.node.IncomingSocketThread( 6633): startStreamCopyingThreads: OK
,D/io.jxcore.node.IncomingSocketThread( 6633): Exiting thread (ID: 812)
,D/io.jxcore.node.StreamCopyingThread( 6633): Entering thread (ID: 813, name: Sender)
,D/io.jxcore.node.StreamCopyingThread( 6633): Entering thread (ID: 814, name: Receiver)
,I/io.jxcore.node.ConnectionHelper( 6633): onListeningForIncomingConnections: Outgoing connection is using port 58469 (peer ID: 7C:F9:0E:37:96:AB)
,I/jxcore-log( 6633): 2015-12-18T17:58:39.095Z SendDataConnector.js: CLIENT connected to 58469, error: null
I/jxcore-log( 6633): 
I/jxcore-log( 6633): 2015-12-18T17:58:39.096Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 6633): 
,I/io.jxcore.node.IncomingSocketThread( 6633): Incoming data from address: /127.0.0.1, port: 58469
,D/io.jxcore.node.IncomingSocketThread( 6633): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 6633): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 6633): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.IncomingSocketThread( 6633): startStreamCopyingThreads: OK
D/io.jxcore.node.IncomingSocketThread( 6633): Exiting thread (ID: 810)
,I/jxcore-log( 6633): 2015-12-18T17:58:39.109Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 6633): 
,D/io.jxcore.node.StreamCopyingThread( 6633): Entering thread (ID: 816, name: Receiver)
,D/io.jxcore.node.StreamCopyingThread( 6633): Entering thread (ID: 815, name: Sender)
,E/bt-btm  ( 2530): tBTM_SEC_DEV:0xa6fc435c rs_disc_pending=0
W/bt-btif ( 2530): bta_dm_check_av:0
W/bt-btif ( 2530): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 2530): tBTM_SEC_DEV:0xa6fc435c rs_disc_pending=0
W/bt-btif ( 2530): bta_dm_check_av:0
,W/bt-btif ( 2530): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 6633): 2015-12-18T17:58:40.955Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 6633): 
,I/jxcore-log( 6633): 2015-12-18T17:58:40.962Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 6633): 
,I/jxcore-log( 6633): 2015-12-18T17:58:40.973Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 6633): 
,I/jxcore-log( 6633): 2015-12-18T17:58:40.987Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 6633): 
,I/jxcore-log( 6633): 2015-12-18T17:58:40.997Z SendDataTCPServer.js: TCP/IP server has received 9900 bytes of data
I/jxcore-log( 6633): 
,I/jxcore-log( 6633): 2015-12-18T17:58:41.005Z SendDataTCPServer.js: TCP/IP server has received 11880 bytes of data
I/jxcore-log( 6633): 
,I/jxcore-log( 6633): 2015-12-18T17:58:41.015Z SendDataTCPServer.js: TCP/IP server has received 13860 bytes of data
I/jxcore-log( 6633): 
,I/jxcore-log( 6633): 2015-12-18T17:58:41.054Z SendDataTCPServer.js: TCP/IP server has received 15840 bytes of data
I/jxcore-log( 6633): 
,I/jxcore-log( 6633): 2015-12-18T17:58:41.088Z SendDataTCPServer.js: TCP/IP server has received 17820 bytes of data
I/jxcore-log( 6633): 
,I/jxcore-log( 6633): 2015-12-18T17:58:41.098Z SendDataTCPServer.js: TCP/IP server has received 19800 bytes of data
I/jxcore-log( 6633): 
,D/        ( 2530): PORT_WriteDataCO: tx queue is full,tx.queue_size:10172,tx.queue.count:11,available:24706
,I/jxcore-log( 6633): 2015-12-18T17:58:41.162Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 6633): 
,I/jxcore-log( 6633): 2015-12-18T17:58:41.163Z SendDataTCPServer.js: TCP/IP server has received 21780 bytes of data
I/jxcore-log( 6633): 
,I/jxcore-log( 6633): 2015-12-18T17:58:41.170Z SendDataTCPServer.js: TCP/IP server has received 23760 bytes of data
I/jxcore-log( 6633): 
,I/jxcore-log( 6633): 2015-12-18T17:58:41.175Z SendDataTCPServer.js: TCP/IP server has received 25740 bytes of data
I/jxcore-log( 6633): 
,I/jxcore-log( 6633): 2015-12-18T17:58:41.246Z SendDataTCPServer.js: TCP/IP server has received 27720 bytes of data
I/jxcore-log( 6633): 
,I/jxcore-log( 6633): 2015-12-18T17:58:41.261Z SendDataTCPServer.js: TCP/IP server has received 29700 bytes of data
I/jxcore-log( 6633): 
,I/jxcore-log( 6633): 2015-12-18T17:58:41.271Z SendDataTCPServer.js: TCP/IP server has received 31680 bytes of data
I/jxcore-log( 6633): 
,I/jxcore-log( 6633): 2015-12-18T17:58:41.280Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 6633): 
,I/jxcore-log( 6633): 2015-12-18T17:58:41.297Z SendDataTCPServer.js: TCP/IP server has received 33660 bytes of data
I/jxcore-log( 6633): 
,I/jxcore-log( 6633): 2015-12-18T17:58:41.334Z SendDataTCPServer.js: TCP/IP server has received 37620 bytes of data
I/jxcore-log( 6633): 
,I/jxcore-log( 6633): 2015-12-18T17:58:41.347Z SendDataTCPServer.js: TCP/IP server has received 39600 bytes of data
I/jxcore-log( 6633): 
,I/jxcore-log( 6633): 2015-12-18T17:58:41.415Z SendDataTCPServer.js: TCP/IP server has received 41580 bytes of data
I/jxcore-log( 6633): 
,D/        ( 2530): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:14806
,I/jxcore-log( 6633): 2015-12-18T17:58:41.447Z SendDataTCPServer.js: TCP/IP server has received 43560 bytes of data
I/jxcore-log( 6633): 
,I/jxcore-log( 6633): 2015-12-18T17:58:41.449Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 6633): 
,I/jxcore-log( 6633): 2015-12-18T17:58:41.494Z SendDataTCPServer.js: TCP/IP server has received 45540 bytes of data
I/jxcore-log( 6633): 
,I/jxcore-log( 6633): 2015-12-18T17:58:41.518Z SendDataTCPServer.js: TCP/IP server has received 47520 bytes of data
I/jxcore-log( 6633): 
,I/jxcore-log( 6633): 2015-12-18T17:58:41.582Z SendDataTCPServer.js: TCP/IP server has received 49500 bytes of data
I/jxcore-log( 6633): 
,I/jxcore-log( 6633): 2015-12-18T17:58:41.592Z SendDataTCPServer.js: TCP/IP server has received 51480 bytes of data
I/jxcore-log( 6633): 
,I/jxcore-log( 6633): 2015-12-18T17:58:41.602Z SendDataTCPServer.js: TCP/IP server has received 53460 bytes of data
I/jxcore-log( 6633): 
,I/jxcore-log( 6633): 2015-12-18T17:58:41.634Z SendDataTCPServer.js: TCP/IP server has received 55440 bytes of data
I/jxcore-log( 6633): 
,I/jxcore-log( 6633): 2015-12-18T17:58:41.814Z SendDataTCPServer.js: TCP/IP server has received 57420 bytes of data
I/jxcore-log( 6633): 
,I/jxcore-log( 6633): 2015-12-18T17:58:41.834Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 6633): 
,I/jxcore-log( 6633): 2015-12-18T17:58:41.855Z SendDataTCPServer.js: TCP/IP server has received 61380 bytes of data
I/jxcore-log( 6633): 
,I/jxcore-log( 6633): 2015-12-18T17:58:41.887Z SendDataTCPServer.js: TCP/IP server has received 63360 bytes of data
I/jxcore-log( 6633): 
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:31000 mC
,I/jxcore-log( 6633): 2015-12-18T17:58:41.924Z SendDataTCPServer.js: TCP/IP server has received 65340 bytes of data
I/jxcore-log( 6633): 
,I/jxcore-log( 6633): 2015-12-18T17:58:42.034Z SendDataTCPServer.js: TCP/IP server has received 67320 bytes of data
I/jxcore-log( 6633): 
,D/        ( 2530): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:3916
,I/jxcore-log( 6633): 2015-12-18T17:58:42.062Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 6633): 
,I/jxcore-log( 6633): 2015-12-18T17:58:42.066Z SendDataTCPServer.js: TCP/IP server has received 71280 bytes of data
I/jxcore-log( 6633): 
,I/jxcore-log( 6633): 2015-12-18T17:58:42.077Z SendDataTCPServer.js: TCP/IP server has received 73260 bytes of data
I/jxcore-log( 6633): 
,I/jxcore-log( 6633): 2015-12-18T17:58:42.114Z SendDataTCPServer.js: TCP/IP server has received 75240 bytes of data
I/jxcore-log( 6633): 
,I/jxcore-log( 6633): 2015-12-18T17:58:42.186Z SendDataTCPServer.js: TCP/IP server has received 77220 bytes of data
I/jxcore-log( 6633): 
,I/jxcore-log( 6633): 2015-12-18T17:58:42.210Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 6633): 
,I/jxcore-log( 6633): 2015-12-18T17:58:42.224Z SendDataTCPServer.js: TCP/IP server has received 81180 bytes of data
I/jxcore-log( 6633): 
,E/bt-btm  ( 2530): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2530): onReceive
,I/BTConnectionReceiver( 8520): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:51:18:22, alias=null, name=Thali Test (Galaxy A5), majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 8520): Bluetooth Device Name: Thali Test (Galaxy A5)
,I/jxcore-log( 6633): 2015-12-18T17:58:42.386Z SendDataTCPServer.js: TCP/IP server has received 87120 bytes of data
I/jxcore-log( 6633): 
,I/jxcore-log( 6633): 2015-12-18T17:58:42.395Z SendDataTCPServer.js: TCP/IP server has received 89100 bytes of data
I/jxcore-log( 6633): 
,I/jxcore-log( 6633): 2015-12-18T17:58:42.492Z SendDataTCPServer.js: TCP/IP server has received 91080 bytes of data
I/jxcore-log( 6633): 
,I/jxcore-log( 6633): 2015-12-18T17:58:42.496Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 6633): 
,I/jxcore-log( 6633): 2015-12-18T17:58:42.508Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 6633): 
,I/jxcore-log( 6633): 2015-12-18T17:58:42.521Z SendDataTCPServer.js: TCP/IP server has received 93060 bytes of data
I/jxcore-log( 6633): 
,I/jxcore-log( 6633): 2015-12-18T17:58:42.554Z SendDataTCPServer.js: TCP/IP server has received 97020 bytes of data
I/jxcore-log( 6633): 
,I/jxcore-log( 6633): 2015-12-18T17:58:42.595Z SendDataTCPServer.js: TCP/IP server has received 99000 bytes of data
I/jxcore-log( 6633): 
,I/jxcore-log( 6633): 2015-12-18T17:58:42.642Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
I/jxcore-log( 6633): 
,I/jxcore-log( 6633): 2015-12-18T17:58:42.647Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 6633): 
,W/bt-btif ( 2530): invalid rfc slot id: 10
,W/io.jxcore.node.StreamCopyingThread( 6633): Either failed to read from the output stream or write to the input stream (thread ID: 814, thread name: Receiver): bt socket closed, read return: -1
E/io.jxcore.node.IncomingSocketThread( 6633): The receiving thread failed with error "Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1", this is likely due to peer having disconnected
W/io.jxcore.node.ConnectionHelper( 6633): onDisconnected: Incoming connection, peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1532] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
I/io.jxcore.node.ConnectionHelper( 6633): closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 812
D/io.jxcore.node.IncomingSocketThread( 6633): close: Stopping receiving thread...
,I/io.jxcore.node.StreamCopyingThread( 6633): doStop: Thread ID: 814
D/io.jxcore.node.IncomingSocketThread( 6633): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 6633): doStop: Thread ID: 813
D/io.jxcore.node.IncomingSocketThread( 6633): closeLocalSocketAndStreams: Closing...
D/io.jxcore.node.IncomingSocketThread( 6633): closeLocalSocketAndStreams: Closing the local input stream...
D/io.jxcore.node.IncomingSocketThread( 6633): closeLocalSocketAndStreams: Closing the local output stream...
,D/io.jxcore.node.IncomingSocketThread( 6633): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.IncomingSocketThread( 6633): closeBluetoothSocketAndStreams
D/io.jxcore.node.ConnectionHelper( 6633): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
D/io.jxcore.node.StreamCopyingThread( 6633): Exiting thread (ID: 814, name: Receiver)
W/io.jxcore.node.StreamCopyingThread( 6633): Either failed to read from the output stream or write to the input stream (thread ID: 813, thread name: Sender): Socket closed
,E/io.jxcore.node.IncomingSocketThread( 6633): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 6633): onDisconnected: Incoming connection, peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1532] disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
D/io.jxcore.node.ConnectionHelper( 6633): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
D/io.jxcore.node.StreamCopyingThread( 6633): Exiting thread (ID: 813, name: Sender)
,I/jxcore-log( 6633): 2015-12-18T17:58:42.800Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 6633): 
I/jxcore-log( 6633): 2015-12-18T17:58:42.800Z SendDataConnector.js: got all data for this round
I/jxcore-log( 6633): 
I/jxcore-log( 6633): oneRoundDownNow
I/jxcore-log( 6633): 
,I/jxcore-log( 6633): 2015-12-18T17:58:42.801Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 6633): 
I/jxcore-log( 6633): 2015-12-18T17:58:42.801Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 6633): 
D/io.jxcore.node.ConnectionHelper( 6633): disconnectOutgoingConnection: Trying to close connection to peer with ID 7C:F9:0E:37:96:AB
I/io.jxcore.node.ConnectionHelper( 6633): closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 7C:F9:0E:37:96:AB
I/io.jxcore.node.IncomingSocketThread( 6633): close
,D/io.jxcore.node.IncomingSocketThread( 6633): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 6633): doStop: Thread ID: 816
D/io.jxcore.node.IncomingSocketThread( 6633): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 6633): doStop: Thread ID: 815
D/io.jxcore.node.IncomingSocketThread( 6633): closeLocalSocketAndStreams: Closing...
D/io.jxcore.node.IncomingSocketThread( 6633): closeLocalSocketAndStreams: Closing the local input stream...
,W/io.jxcore.node.StreamCopyingThread( 6633): Either failed to read from the output stream or write to the input stream (thread ID: 815, thread name: Sender): Socket closed
E/io.jxcore.node.IncomingSocketThread( 6633): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 6633): onDisconnected: Outgoing connection, peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1532] disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
D/io.jxcore.node.IncomingSocketThread( 6633): closeLocalSocketAndStreams: Closing the local output stream...
,D/io.jxcore.node.IncomingSocketThread( 6633): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.IncomingSocketThread( 6633): closeBluetoothSocketAndStreams
W/io.jxcore.node.StreamCopyingThread( 6633): Either failed to read from the output stream or write to the input stream (thread ID: 816, thread name: Receiver): bt socket closed, read return: -1
D/io.jxcore.node.ConnectionHelper( 6633): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
I/io.jxcore.node.ConnectionHelper( 6633): disconnectOutgoingConnection: Successfully disconnected (peer ID: 7C:F9:0E:37:96:AB
E/io.jxcore.node.ConnectionHelper( 6633): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 7C:F9:0E:37:96:AB
,E/io.jxcore.node.IncomingSocketThread( 6633): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
,D/io.jxcore.node.ConnectionHelper( 6633): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,D/io.jxcore.node.StreamCopyingThread( 6633): Exiting thread (ID: 815, name: Sender)
W/io.jxcore.node.ConnectionHelper( 6633): onDisconnected: Outgoing connection, peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1532] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
E/io.jxcore.node.ConnectionHelper( 6633): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 7C:F9:0E:37:96:AB
D/io.jxcore.node.ConnectionHelper( 6633): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
D/io.jxcore.node.StreamCopyingThread( 6633): Exiting thread (ID: 816, name: Receiver)
,I/jxcore-log( 6633): 2015-12-18T17:58:42.808Z SendDataConnector.js: Mobile.Disconnect() callback with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 6633): 
I/jxcore-log( 6633): ---- round done--------
I/jxcore-log( 6633): 
I/jxcore-log( 6633): startWithNextDevice
I/jxcore-log( 6633): 
,I/jxcore-log( 6633): 2015-12-18T17:58:42.813Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 6633): 
,W/bt-btif ( 2530): bta_jv_rfc_port_to_cb(port_handle:0xe):jv handle:0x0 not FOUND
,D/btif_config_util( 2530): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2530): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2530): onReceive
,I/BTConnectionReceiver( 8520): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:37:96:AB, alias=null, name=A5-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 8520): Bluetooth Device Name: A5-1
,I/ActivityManager(  883): Waited long enough for: ServiceRecord{262e05a4 u0 com.motorola.context/.publisher.bluetoothdeterminer.BluetoothContextService}
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:31000 mC
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6633): Got discovery timeout, restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6633): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6633): setState: RESTARTING
,D/WifiP2pService(  883): InactiveState{ when=0 what=139268 arg2=9 target=com.android.internal.util.StateMachine$SmHandler }
,I/wpa_supplicant( 1442): P2P-FIND-STOPPED 
D/MDMCTBK (  291): reply_len: 40 reply is = <3>P2P-FIND-STOPPED 
D/MDMCTBK (  291): Event received = P2P-FIND-STOPPED 
,I/wpa_supplicant( 1442): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:75:42
,I/wpa_supplicant( 1442): P2P-DEVICE-LOST p2p_dev_addr=92:e7:c4:e6:4c:f8
I/wpa_supplicant( 1442): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:51:18:23
I/wpa_supplicant( 1442): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:37:96:ac
D/MDMCTBK (  291): reply_len: 40 reply is = <3>P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9
D/MDMCTBK (  291): Event received = P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9
D/MDMCTBK (  291): reply_len: 40 reply is = <3>P2P-DEVICE-LOST p2p_dev_addr=92:e7:c4
,D/MDMCTBK (  291): Event received = P2P-DEVICE-LOST p2p_dev_addr=92:e7:c4
D/MDMCTBK (  291): reply_len: 40 reply is = <3>P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e
D/MDMCTBK (  291): Event received = P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e
D/MDMCTBK (  291): reply_len: 40 reply is = <3>P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e
D/MDMCTBK (  291): Event received = P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e
,D/WifiP2pService(  883): InactiveState{ when=-8ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  883): P2pEnabledState{ when=-9ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  883): discovery change broadcast false
,D/WifiP2pService(  883): InactiveState{ when=-6ms what=147478 obj=Device: 
D/WifiP2pService(  883):  deviceAddress: 0a:ec:a9:50:75:42
D/WifiP2pService(  883):  primary type: null
D/WifiP2pService(  883):  secondary type: null
D/WifiP2pService(  883):  wps: 0
D/WifiP2pService(  883):  grpcapab: 0
D/WifiP2pService(  883):  devcapab: 0
D/WifiP2pService(  883):  status: 4
D/WifiP2pService(  883):  wfdInfo: null
D/WifiP2pService(  883):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  883): P2pEnabledState{ when=-6ms what=147478 obj=Device: 
D/WifiP2pService(  883):  deviceAddress: 0a:ec:a9:50:75:42
D/WifiP2pService(  883):  primary type: null
D/WifiP2pService(  883):  secondary type: null
D/WifiP2pService(  883):  wps: 0
D/WifiP2pService(  883):  grpcapab: 0
D/WifiP2pService(  883):  devcapab: 0
D/WifiP2pService(  883):  status: 4
D/WifiP2pService(  883):  wfdInfo: null
D/WifiP2pService(  883):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  883): InactiveState{ when=-12ms what=147478 obj=Device: 
D/WifiP2pService(  883):  deviceAddress: 92:e7:c4:e6:4c:f8
D/WifiP2pService(  883):  primary type: null
D/WifiP2pService(  883):  secondary type: null
D/WifiP2pService(  883):  wps: 0
D/WifiP2pService(  883):  grpcapab: 0
D/WifiP2pService(  883):  devcapab: 0
D/WifiP2pService(  883):  status: 4
D/WifiP2pService(  883):  wfdInfo: null
D/WifiP2pService(  883):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  883): P2pEnabledState{ when=-12ms what=147478 obj=Device: 
D/WifiP2pService(  883):  deviceAddress: 92:e7:c4:e6:4c:f8
D/WifiP2pService(  883):  primary type: null
D/WifiP2pService(  883):  secondary type: null
D/WifiP2pService(  883):  wps: 0
D/WifiP2pService(  883):  grpcapab: 0
D/WifiP2pService(  883):  devcapab: 0
D/WifiP2pService(  883):  status: 4
D/WifiP2pService(  883):  wfdInfo: null
D/WifiP2pService(  883):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6633): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped
,D/WifiP2pService(  883): InactiveState{ when=-16ms what=147478 obj=Device: 
D/WifiP2pService(  883):  deviceAddress: 7e:f9:0e:51:18:23
D/WifiP2pService(  883):  primary type: null
D/WifiP2pService(  883):  secondary type: null
D/WifiP2pService(  883):  wps: 0
D/WifiP2pService(  883):  grpcapab: 0
D/WifiP2pService(  883):  devcapab: 0
D/WifiP2pService(  883):  status: 4
D/WifiP2pService(  883):  wfdInfo: null
D/WifiP2pService(  883):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  883): P2pEnabledState{ when=-16ms what=147478 obj=Device: 
D/WifiP2pService(  883):  deviceAddress: 7e:f9:0e:51:18:23
D/WifiP2pService(  883):  primary type: null
D/WifiP2pService(  883):  secondary type: null
D/WifiP2pService(  883):  wps: 0
D/WifiP2pService(  883):  grpcapab: 0
D/WifiP2pService(  883):  devcapab: 0
D/WifiP2pService(  883):  status: 4
D/WifiP2pService(  883):  wfdInfo: null
D/WifiP2pService(  883):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  883): InactiveState{ when=-18ms what=147478 obj=Device: 
D/WifiP2pService(  883):  deviceAddress: 7e:f9:0e:37:96:ac
D/WifiP2pService(  883):  primary type: null
D/WifiP2pService(  883):  secondary type: null
D/WifiP2pService(  883):  wps: 0
D/WifiP2pService(  883):  grpcapab: 0
D/WifiP2pService(  883):  devcapab: 0
D/WifiP2pService(  883):  status: 4
D/WifiP2pService(  883):  wfdInfo: null
D/WifiP2pService(  883):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  883): P2pEnabledState{ when=-18ms what=147478 obj=Device: 
D/WifiP2pService(  883):  deviceAddress: 7e:f9:0e:37:96:ac
D/WifiP2pService(  883):  primary type: null
D/WifiP2pService(  883):  secondary type: null
D/WifiP2pService(  883):  wps: 0
D/WifiP2pService(  883):  grpcapab: 0
D/WifiP2pService(  883):  devcapab: 0
D/WifiP2pService(  883):  status: 4
D/WifiP2pService(  883):  wfdInfo: null
D/WifiP2pService(  883):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  883): InactiveState{ when=0 what=139283 arg2=10 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  883): P2pEnabledState{ when=0 what=139283 arg2=10 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  883): DefaultState{ when=0 what=139283 arg2=10 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  883): InactiveState{ when=0 what=139283 arg2=11 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  883): P2pEnabledState{ when=0 what=139283 arg2=11 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  883): DefaultState{ when=-1ms what=139283 arg2=11 target=com.android.internal.util.StateMachine$SmHandler }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6633): onP2pDeviceListChanged: 0 device(s) discovered
,D/WifiP2pService(  883): InactiveState{ when=0 what=139283 arg2=12 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  883): P2pEnabledState{ when=0 what=139283 arg2=12 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  883): DefaultState{ when=0 what=139283 arg2=12 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  883): InactiveState{ when=0 what=139283 arg2=13 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  883): P2pEnabledState{ when=0 what=139283 arg2=13 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  883): DefaultState{ when=0 what=139283 arg2=13 target=com.android.internal.util.StateMachine$SmHandler }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6633): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6633): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6633): onP2pDeviceListChanged: 0 device(s) discovered
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6633): Start timer timeout, starting now...
,D/WifiP2pService(  883): InactiveState{ when=0 what=139265 arg2=14 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  883): P2pEnabledState{ when=0 what=139265 arg2=14 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 1442): p2p0: CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  291): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  291): Event received = CTRL-EVENT-SCAN-STARTED 
,D/WifiP2pService(  883): discovery change broadcast true
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6633): P2P device discovery started successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6633): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6633): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant( 1442): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 level=-43
,D/MDMCTBK (  291): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 2 c0
D/MDMCTBK (  291): Event received = CTRL-EVENT-BSS-ADDED 2 c0
D/MDMCTBK (  291): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2
D/MDMCTBK (  291): Event received = P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2
,D/WifiP2pService(  883): InactiveState{ when=-1ms what=147477 obj=Device: G4-1
D/WifiP2pService(  883):  deviceAddress: a2:39:f7:6f:c9:5d
D/WifiP2pService(  883):  primary type: 10-0050F204-5
D/WifiP2pService(  883):  secondary type: null
D/WifiP2pService(  883):  wps: 4488
D/WifiP2pService(  883):  grpcapab: 0
D/WifiP2pService(  883):  devcapab: 37
D/WifiP2pService(  883):  status: 3
D/WifiP2pService(  883):  wfdInfo: null
D/WifiP2pService(  883):  level: -43 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  883): P2pEnabledState{ when=-1ms what=147477 obj=Device: G4-1
D/WifiP2pService(  883):  deviceAddress: a2:39:f7:6f:c9:5d
D/WifiP2pService(  883):  primary type: 10-0050F204-5
D/WifiP2pService(  883):  secondary type: null
D/WifiP2pService(  883):  wps: 4488
D/WifiP2pService(  883):  grpcapab: 0
D/WifiP2pService(  883):  devcapab: 37
D/WifiP2pService(  883):  status: 3
D/WifiP2pService(  883):  wfdInfo: null
D/WifiP2pService(  883):  level: -43 target=com.android.internal.util.StateMachine$SmHandler }
,D/TCMD    (  474): NL - Read 56 bytes from update socket.
,D/TCMD    (  474): NL - message type is RTM_NEWLINK
D/TCMD    (  474): Listening for incoming client connection request
,D/WifiP2pService(  883): InactiveState{ when=0 what=139283 arg2=15 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  883): P2pEnabledState{ when=0 what=139283 arg2=15 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  883): DefaultState{ when=0 what=139283 arg2=15 target=com.android.internal.util.StateMachine$SmHandler }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6633): onP2pDeviceListChanged: 1 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6633): onP2pDeviceListChanged: Peer 1: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6633): restart: Restarting...
,D/WifiP2pService(  883): InactiveState{ when=0 what=139307 arg2=16 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  883): P2pEnabledState{ when=0 what=139307 arg2=16 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  883): P2pEnabledState clear service request
,D/WifiP2pService(  883): InactiveState{ when=0 what=139301 arg2=17 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  883): P2pEnabledState{ when=-1ms what=139301 arg2=17 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  883): P2pEnabledState add service request
,D/WifiP2pManager( 6633): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6633): Service request added successfully
,D/MDMCTBK (  291): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-REQ 2412 a2
D/MDMCTBK (  291): Event received = P2P-SERV-DISC-REQ 2412 a2
,I/wpa_supplicant( 1442): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  291): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  291): Event received = CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1442): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 level=-45
,D/MDMCTBK (  291): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2
,D/MDMCTBK (  291): Event received = P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2
,D/WifiP2pService(  883): InactiveState{ when=0 what=147477 obj=Device: G3s-1
D/WifiP2pService(  883):  deviceAddress: a2:39:f7:70:12:80
D/WifiP2pService(  883):  primary type: 10-0050F204-5
D/WifiP2pService(  883):  secondary type: null
D/WifiP2pService(  883):  wps: 4488
D/WifiP2pService(  883):  grpcapab: 0
D/WifiP2pService(  883):  devcapab: 37
D/WifiP2pService(  883):  status: 3
D/WifiP2pService(  883):  wfdInfo: null
D/WifiP2pService(  883):  level: -45 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  883): P2pEnabledState{ when=0 what=147477 obj=Device: G3s-1
D/WifiP2pService(  883):  deviceAddress: a2:39:f7:70:12:80
D/WifiP2pService(  883):  primary type: 10-0050F204-5
D/WifiP2pService(  883):  secondary type: null
D/WifiP2pService(  883):  wps: 4488
D/WifiP2pService(  883):  grpcapab: 0
D/WifiP2pService(  883):  devcapab: 37
D/WifiP2pService(  883):  status: 3
D/WifiP2pService(  883):  wfdInfo: null
D/WifiP2pService(  883):  level: -45 target=com.android.internal.util.StateMachine$SmHandler }
,D/TCMD    (  474): NL - Read 56 bytes from update socket.
,D/TCMD    (  474): NL - message type is RTM_NEWLINK
,D/TCMD    (  474): Listening for incoming client connection request
,D/WifiP2pService(  883): InactiveState{ when=0 what=139283 arg2=18 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  883): P2pEnabledState{ when=-1ms what=139283 arg2=18 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  883): DefaultState{ when=-1ms what=139283 arg2=18 target=com.android.internal.util.StateMachine$SmHandler }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6633): onP2pDeviceListChanged: 2 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6633): onP2pDeviceListChanged: Peer 1: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6633): onP2pDeviceListChanged: Peer 2: G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pService(  883): InactiveState{ when=0 what=139310 arg2=19 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  883): P2pEnabledState{ when=0 what=139310 arg2=19 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  883): P2pEnabledState discover services
,I/wpa_supplicant( 1442): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  291): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  291): Event received = CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6633): Service discovery started successfully
,W/bt-btif ( 2530): info:x10
,D/        ( 2530): remote version info [f8:95:c7:87:3c:51]: 7, f, 6109
,E/BluetoothRemoteDevices( 2530): aclStateChangeCallback: Device is NULL
,D/TCMD    (  474): NL - Read 56 bytes from update socket.
D/TCMD    (  474): NL - message type is RTM_NEWLINK
D/TCMD    (  474): Listening for incoming client connection request
,D/MDMCTBK (  291): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP a2:39:
,D/MDMCTBK (  291): Event received = P2P-SERV-DISC-RESP a2:39:
,D/WifiP2pService(  883): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:a2:39:f7:6f:c9:5d version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT9219","ra":"F8:95:C7:87:3C:51"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  883): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:a2:39:f7:6f:c9:5d version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT9219","ra":"F8:95:C7:87:3C:51"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  883): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6633): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT9219","ra":"F8:95:C7:87:3C:51"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6633): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9219]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6633): onServiceDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9219]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6633): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9219]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6633): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9219], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6633): modifyListOfDiscoveredPeers: Adding new peer: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9219]
I/io.jxcore.node.ConnectionHelper( 6633): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9219], Bluetooth address: F8:95:C7:87:3C:51, device name: G4-1, device address: a2:39:f7:6f:c9:5d
D/io.jxcore.node.ConnectionHelper( 6633): notifyPeerAvailability: Peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9219] is available
I/ThermalEngine(  303): Sensor:xo_therm_pu2:30000 mC
,I/jxcore-log( 6633): peerAvailabilityChanged [{"peerIdentifier":"F8:95:C7:87:3C:51","peerName":"LGE-LG-H815_PT9219","peerAvailable":true}]
I/jxcore-log( 6633): 
,I/jxcore-log( 6633): Found peer : LGE-LG-H815_PT9219, Available: true
I/jxcore-log( 6633): 
I/jxcore-log( 6633): startWithNextDevice
I/jxcore-log( 6633): 
I/jxcore-log( 6633): device[5]: F8:95:C7:87:3C:51
I/jxcore-log( 6633): 
I/jxcore-log( 6633): 2015-12-18T17:59:01.919Z SendDataConnector.js: Start called with peer F8:95:C7:87:3C:51
I/jxcore-log( 6633): 
,I/jxcore-log( 6633): 2015-12-18T17:59:01.920Z SendDataConnector.js: doConnect called with peer F8:95:C7:87:3C:51
I/jxcore-log( 6633): 
I/jxcore-log( 6633): 2015-12-18T17:59:01.920Z SendDataConnector.js: do connect now
I/jxcore-log( 6633): 
I/io.jxcore.node.ConnectionHelper( 6633): connect: Trying to connect to peer with ID F8:95:C7:87:3C:51
D/io.jxcore.node.ConnectionHelper( 6633): hasConnection: No connection with peer with ID F8:95:C7:87:3C:51
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6633): connect: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9219]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6633): connect: Trying to start connecting to null in address F8:95:C7:87:3C:51
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6633): setInsecureRfcommSocketPort: Using port -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6633): setMaxNumberOfRetries: 0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6633): onConnecting: null F8:95:C7:87:3C:51
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6633): connect: Started connecting to null in address F8:95:C7:87:3C:51
I/io.jxcore.node.ConnectionHelper( 6633): connect: Connection process successfully started (peer ID: F8:95:C7:87:3C:51)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6633): Trying to connect to peer with address F8:95:C7:87:3C:51 (thread ID: 817)
W/BluetoothAdapter( 6633): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2530): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2530): process_service_search_attr_rsp
,I/BluetoothBondStateMachine( 2530): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:3C:51 newState: 1
,E/bt-btif ( 2530): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2530): Bond State Change Intent:F8:95:C7:87:3C:51 OldState: 10 NewState: 11
,I/BluetoothBondStateMachine( 2530): Entering PendingCommandState State
,I/BluetoothBondStateMachine( 2530): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:3C:51 newState: 0
,D/BluetoothAdapterProperties( 2530): Failed to remove device: F8:95:C7:87:3C:51
,I/BluetoothBondStateMachine( 2530): Bond State Change Intent:F8:95:C7:87:3C:51 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2530): StableState(): Entering Off State
,D/BluetoothMetrics( 2530): btclass5a020c
,D/Checkin ( 2530): publish the event [tag = MOT_BT event name = PAIRING]
,D/MDMCTBK (  291): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-REQ 2412 ee
,D/MDMCTBK (  291): Event received = P2P-SERV-DISC-REQ 2412 ee
,D/MDMCTBK (  291): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 2 
,D/MDMCTBK (  291): Event received = CTRL-EVENT-BSS-REMOVED 2 
,E/global frequency( 8342): no tags to log
,D/Checkin ( 8342): publish the event [tag = MOT_CHECKIN event name = LOG]
,D/BSUtils ( 8342): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,E/PhoneInterfaceManager( 1555): [PhoneIntfMgr] getIccId: ICC ID is null or empty.
,I/art     ( 1478): Explicit concurrent mark sweep GC freed 3792(173KB) AllocSpace objects, 1(16KB) LOS objects, 39% free, 7MB/12MB, paused 889us total 31.724ms
,W/bt-l2cap( 2530): L2CAP - no CCB for conn rsp, LCID: 78 RCID: 78
,W/bt-btif ( 2530): new conn_srvc id:26, app_id:255
W/bt-btif ( 2530): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 2530): bta_dm_pm_ssr:2, lat:1200
,W/bt-btif ( 2530): new conn_srvc id:26, app_id:1
W/bt-btif ( 2530): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 2530): bta_dm_pm_ssr conn_srvc id:26, app_id:1
,W/bt-btif ( 2530): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6633): onSocketConnected: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9219]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6633): Socket connection succeeded (using system decided port), total number of attempts: 1 (thread ID: 817)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6633): Incoming connection accepted
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6633): Incoming connection initialized (thread ID: 819)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6633): Waiting for incoming connections...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6633): onBytesWritten: 80 bytes successfully written (thread ID: 818)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6633): Outgoing connection initialized (*handshake* thread ID: 818)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6633): Exiting thread (thread ID: 817)
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 6633): Entering thread (ID: 818)
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 6633): Entering thread (ID: 819)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6633): onBytesRead: Read 77 bytes successfully (thread ID: 819)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6633): Got valid identity from [F8:95:C7:87:3C:51 LGE-LG-H815_PT9219]
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6633): onBytesWritten: 80 bytes successfully written (thread ID: 819)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6633): removeThreadFromList: Removing thread with ID 819
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6633): Handshake thread disposed (thread ID: 819)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6633): onIncomingConnectionConnected: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9219]
D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 6633): Exiting thread (ID: 819)
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6633): onConnected: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9219]
I/io.jxcore.node.ConnectionHelper( 6633): onConnected: Incoming connection to peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9219]
D/io.jxcore.node.ConnectionHelper( 6633): hasConnection: No connection with peer with ID F8:95:C7:87:3C:51
W/io.jxcore.node.ConnectionHelper( 6633): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9219] already in the list, will not add again
I/io.jxcore.node.ConnectionHelper( 6633): onConnected: Incoming socket thread, for peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9219], created successfully
D/io.jxcore.node.ConnectionHelper( 6633): onConnected: The total number of connections is now 1
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6633): onBytesRead: Read 77 bytes successfully (thread ID: 818)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6633): Handshake succeeded with [F8:95:C7:87:3C:51 LGE-LG-H815_PT9219]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6633): onHandshakeSucceeded: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9219]
D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 6633): Exiting thread (ID: 818)
D/io.jxcore.node.IncomingSocketThread( 6633): Entering thread (ID: 820)
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6633): onConnected: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9219]
I/io.jxcore.node.ConnectionHelper( 6633): onConnected: Outgoing connection to peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9219]
D/io.jxcore.node.ConnectionHelper( 6633): hasConnection: We have an incoming connection with peer with ID F8:95:C7:87:3C:51
W/io.jxcore.node.ConnectionHelper( 6633): onConnected: Already connected with peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9219], continuing anyway...
W/io.jxcore.node.ConnectionHelper( 6633): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9219] already in the list, will not add again
I/io.jxcore.node.ConnectionHelper( 6633): onConnected: Outgoing socket thread, for peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9219], created successfully
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6633): setInsecureRfcommSocketPort: Will use port -1 when trying to connect
D/io.jxcore.node.ConnectionHelper( 6633): onConnected: The total number of connections is now 2
,D/io.jxcore.node.OutgoingSocketThread( 6633): Entering thread (ID: 821)
D/io.jxcore.node.OutgoingSocketThread( 6633): Server socket local port: 47019
I/io.jxcore.node.OutgoingSocketThread( 6633): Now accepting connections...
,I/io.jxcore.node.OutgoingSocketThread( 6633): Local host address: localhost/127.0.0.1, port: 57867
D/io.jxcore.node.OutgoingSocketThread( 6633): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 6633): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 6633): setBufferSize: Setting buffer size to 8192 bytes
,I/jxcore-log( 6633): 2015-12-18T17:59:07.097Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 6633): 
,D/io.jxcore.node.StreamCopyingThread( 6633): Entering thread (ID: 822, name: Sender)
,I/io.jxcore.node.OutgoingSocketThread( 6633): startStreamCopyingThreads: OK
D/io.jxcore.node.OutgoingSocketThread( 6633): Exiting thread (ID: 820)
D/io.jxcore.node.StreamCopyingThread( 6633): Entering thread (ID: 823, name: Receiver)
,I/art     (  883): Explicit concurrent mark sweep GC freed 20489(1064KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 21MB/31MB, paused 1.861ms total 128.075ms
,D/BSUtils ( 8342): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,I/BSUtils ( 8342): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,D/BSUtils ( 8342): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,E/PhoneInterfaceManager( 1555): [PhoneIntfMgr] getIccId: ICC ID is null or empty.
,D/BSUtils ( 8342): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,I/BSUtils ( 8342): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,I/BSUtils ( 8342): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,I/global frequency( 8342): BcsDSCheckin.logProperties: root status from persist.qe isqe 0/0
,D/Checkin ( 8342): publish the event [tag = MOT_CHECKIN event name = LOG]
,E/global frequency( 8342): BcsDSCheckin.logProperties: BL State from property is null or empty
,D/Checkin ( 8342): publish the event [tag = MOT_CHECKIN event name = LOG]
,D/Checkin ( 8342): publish the event [tag = DEV_ATTRIBS event name = SW]
,D/Checkin ( 8342): publish the event [tag = MOT_CCE_STATS event name = DataUsage]
,I/art     ( 8342): Explicit concurrent mark sweep GC freed 27038(1802KB) AllocSpace objects, 6(92KB) LOS objects, 39% free, 10MB/17MB, paused 909us total 74.662ms
,I/io.jxcore.node.ConnectionHelper( 6633): onListeningForIncomingConnections: Outgoing connection is using port 47019 (peer ID: F8:95:C7:87:3C:51)
,I/jxcore-log( 6633): 2015-12-18T17:59:07.393Z SendDataConnector.js: CLIENT connected to 47019, error: null
I/jxcore-log( 6633): 
,I/jxcore-log( 6633): 2015-12-18T17:59:07.393Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 6633): 
I/io.jxcore.node.OutgoingSocketThread( 6633): Incoming data from address: /127.0.0.1, port: 47019
D/io.jxcore.node.OutgoingSocketThread( 6633): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 6633): setBufferSize: Setting buffer size to 8192 bytes
,I/io.jxcore.node.StreamCopyingThread( 6633): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.OutgoingSocketThread( 6633): startStreamCopyingThreads: OK
D/io.jxcore.node.OutgoingSocketThread( 6633): Exiting thread (ID: 821)
,I/jxcore-log( 6633): 2015-12-18T17:59:07.399Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 6633): 
,D/io.jxcore.node.StreamCopyingThread( 6633): Entering thread (ID: 825, name: Receiver)
D/io.jxcore.node.StreamCopyingThread( 6633): Entering thread (ID: 824, name: Sender)
,I/global frequency( 8342): BcsDSCheckin.events found events 59
,D/Checkin ( 8342): publish the event [tag = MOT_CHECKIN event name = LOG]
,I/BSUtils ( 8342): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,D/MMApiWebService( 8342): doRequest() with req : MMApiWSRequest(v1/cs/checkin)
,I/art     ( 1478): Explicit concurrent mark sweep GC freed 3698(145KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 7MB/12MB, paused 734us total 25.781ms
,I/MMApiWSBase( 8342): doRequest(): url: https://argo.svcmot.com:443/v1/cs/checkin.pb/2072049230914535424?appId=6R1TANEX3ZMQ6EU1UH43P34C8B868KTE
,D/Checkin ( 8342): publish the event [tag = MOT_CCE event name = LOG]
,D/btif_config_util( 2530): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/jxcore-log( 6633): 2015-12-18T17:59:07.898Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 6633): 
,I/jxcore-log( 6633): 2015-12-18T17:59:07.926Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 6633): 
,I/jxcore-log( 6633): 2015-12-18T17:59:08.002Z SendDataTCPServer.js: TCP/IP server has received 9900 bytes of data
I/jxcore-log( 6633): 
,I/jxcore-log( 6633): 2015-12-18T17:59:08.057Z SendDataTCPServer.js: TCP/IP server has received 11880 bytes of data
I/jxcore-log( 6633): 
,I/jxcore-log( 6633): 2015-12-18T17:59:08.068Z SendDataTCPServer.js: TCP/IP server has received 13860 bytes of data
I/jxcore-log( 6633): 
,I/jxcore-log( 6633): 2015-12-18T17:59:08.227Z SendDataTCPServer.js: TCP/IP server has received 15840 bytes of data
I/jxcore-log( 6633): 
,I/jxcore-log( 6633): 2015-12-18T17:59:08.515Z SendDataTCPServer.js: TCP/IP server has received 17820 bytes of data
I/jxcore-log( 6633): 
,I/jxcore-log( 6633): 2015-12-18T17:59:08.784Z SendDataTCPServer.js: TCP/IP server has received 19800 bytes of data
I/jxcore-log( 6633): 
,I/jxcore-log( 6633): 2015-12-18T17:59:08.883Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 6633): 
,I/jxcore-log( 6633): 2015-12-18T17:59:09.079Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 6633): 
,I/jxcore-log( 6633): 2015-12-18T17:59:09.195Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 6633): 
,I/jxcore-log( 6633): 2015-12-18T17:59:09.715Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 6633): 
,D/MMApiWSBase( 8342): doRequest(): v1/cs/checkin resp length: 4
,D/CCE     ( 8342): AppWSProxy - handleResponse(): error=None errorText= statusCode=200 reqId=
,D/CCE     ( 8342): AppWSProxy - sendAIDLWSResponse() sending reponse
,I/global frequency( 8342): BcsCore.status() called with error code=ERROR_OK
,D/Checkin ( 8342): publish the event [tag = MOT_CHECKIN event name = LOG]
,D/CheckinProvider(  883): 59 events delete 0 left
,I/global frequency( 8342): BcsDSCheckin.events found events 0
,D/Checkin ( 8342): publish the event [tag = MOT_CHECKIN event name = LOG]
,I/BSUtils ( 8342): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,I/BSUtils ( 8342): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,I/global frequency( 8342): BcsTimer.onReceive checkin completed (0:ERROR_OK)
,D/Checkin ( 8342): publish the event [tag = MOT_CHECKIN event name = LOG]
,I/jxcore-log( 6633): 2015-12-18T17:59:09.962Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 6633): 
,I/jxcore-log( 6633): 2015-12-18T17:59:10.160Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 6633): 
,I/jxcore-log( 6633): 2015-12-18T17:59:10.305Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 6633): 
,W/DataUsage( 8342): invalid counter update blocked: 'err' by 0
,D/Checkin ( 8342): publish the event [tag = MOT_CCE event name = LOG]
,I/jxcore-log( 6633): 2015-12-18T17:59:10.322Z SendDataTCPServer.js: TCP/IP server has received 21780 bytes of data
I/jxcore-log( 6633): 
,I/jxcore-log( 6633): 2015-12-18T17:59:10.334Z SendDataTCPServer.js: TCP/IP server has received 23760 bytes of data
I/jxcore-log( 6633): 
,I/jxcore-log( 6633): 2015-12-18T17:59:10.364Z SendDataTCPServer.js: TCP/IP server has received 29700 bytes of data
I/jxcore-log( 6633): 
,I/jxcore-log( 6633): 2015-12-18T17:59:10.368Z SendDataTCPServer.js: TCP/IP server has received 31680 bytes of data
I/jxcore-log( 6633): 
,I/jxcore-log( 6633): 2015-12-18T17:59:10.372Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 6633): 
,I/jxcore-log( 6633): 2015-12-18T17:59:10.510Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 6633): 
,I/jxcore-log( 6633): 2015-12-18T17:59:10.543Z SendDataTCPServer.js: TCP/IP server has received 32768 bytes of data
I/jxcore-log( 6633): 
,I/jxcore-log( 6633): 2015-12-18T17:59:10.583Z SendDataTCPServer.js: TCP/IP server has received 34748 bytes of data
I/jxcore-log( 6633): 
,I/jxcore-log( 6633): 2015-12-18T17:59:10.588Z SendDataTCPServer.js: TCP/IP server has received 36728 bytes of data
I/jxcore-log( 6633): 
,I/jxcore-log( 6633): 2015-12-18T17:59:10.647Z SendDataTCPServer.js: TCP/IP server has received 38708 bytes of data
I/jxcore-log( 6633): 
,I/jxcore-log( 6633): 2015-12-18T17:59:10.652Z SendDataTCPServer.js: TCP/IP server has received 40688 bytes of data
I/jxcore-log( 6633): 
,I/jxcore-log( 6633): 2015-12-18T17:59:10.659Z SendDataTCPServer.js: TCP/IP server has received 42668 bytes of data
I/jxcore-log( 6633): 
,I/jxcore-log( 6633): 2015-12-18T17:59:10.682Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 6633): 
I/jxcore-log( 6633): 2015-12-18T17:59:10.682Z SendDataConnector.js: got all data for this round
I/jxcore-log( 6633): 
I/jxcore-log( 6633): oneRoundDownNow
I/jxcore-log( 6633): 
,I/jxcore-log( 6633): 2015-12-18T17:59:10.688Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 6633): 
,I/jxcore-log( 6633): 2015-12-18T17:59:10.688Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 6633): 
D/io.jxcore.node.ConnectionHelper( 6633): disconnectOutgoingConnection: Trying to close connection to peer with ID F8:95:C7:87:3C:51
I/io.jxcore.node.ConnectionHelper( 6633): closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: F8:95:C7:87:3C:51
,I/io.jxcore.node.OutgoingSocketThread( 6633): close
D/io.jxcore.node.OutgoingSocketThread( 6633): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 6633): doStop: Thread ID: 825
D/io.jxcore.node.OutgoingSocketThread( 6633): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 6633): doStop: Thread ID: 824
D/io.jxcore.node.OutgoingSocketThread( 6633): closeLocalSocketAndStreams: Closing...
D/io.jxcore.node.OutgoingSocketThread( 6633): closeLocalSocketAndStreams: Closing the local input stream...
,W/io.jxcore.node.StreamCopyingThread( 6633): Either failed to read from the output stream or write to the input stream (thread ID: 824, thread name: Sender): Socket closed
E/io.jxcore.node.OutgoingSocketThread( 6633): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 6633): onDisconnected: Outgoing connection, peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9219] disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
,D/io.jxcore.node.OutgoingSocketThread( 6633): closeLocalSocketAndStreams: Closing the local output stream...
D/io.jxcore.node.OutgoingSocketThread( 6633): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.OutgoingSocketThread( 6633): closeBluetoothSocketAndStreams
,W/io.jxcore.node.StreamCopyingThread( 6633): Either failed to read from the output stream or write to the input stream (thread ID: 825, thread name: Receiver): bt socket closed, read return: -1
E/io.jxcore.node.OutgoingSocketThread( 6633): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
,W/io.jxcore.node.ConnectionHelper( 6633): onDisconnected: Outgoing connection, peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9219] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
,D/io.jxcore.node.ConnectionHelper( 6633): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
I/io.jxcore.node.ConnectionHelper( 6633): disconnectOutgoingConnection: Successfully disconnected (peer ID: F8:95:C7:87:3C:51
,E/io.jxcore.node.ConnectionHelper( 6633): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID F8:95:C7:87:3C:51
D/io.jxcore.node.ConnectionHelper( 6633): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
D/io.jxcore.node.StreamCopyingThread( 6633): Exiting thread (ID: 824, name: Sender)
,E/io.jxcore.node.ConnectionHelper( 6633): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID F8:95:C7:87:3C:51
D/io.jxcore.node.ConnectionHelper( 6633): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
D/io.jxcore.node.StreamCopyingThread( 6633): Exiting thread (ID: 825, name: Receiver)
,I/jxcore-log( 6633): 2015-12-18T17:59:10.715Z SendDataConnector.js: Mobile.Disconnect() callback with peer F8:95:C7:87:3C:51
I/jxcore-log( 6633): 
I/jxcore-log( 6633): ---- round done--------
I/jxcore-log( 6633): 
I/jxcore-log( 6633): startWithNextDevice
I/jxcore-log( 6633): 
,I/jxcore-log( 6633): 2015-12-18T17:59:10.719Z SendDataTCPServer.js: TCP/IP server has received 52568 bytes of data
I/jxcore-log( 6633): 
,I/jxcore-log( 6633): 2015-12-18T17:59:10.764Z SendDataTCPServer.js: TCP/IP server has received 54548 bytes of data
I/jxcore-log( 6633): 
,I/jxcore-log( 6633): 2015-12-18T17:59:11.294Z SendDataTCPServer.js: TCP/IP server has received 56528 bytes of data
I/jxcore-log( 6633): 
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:31000 mC
,I/jxcore-log( 6633): 2015-12-18T17:59:12.282Z SendDataTCPServer.js: TCP/IP server has received 58508 bytes of data
I/jxcore-log( 6633): 
,I/jxcore-log( 6633): 2015-12-18T17:59:12.334Z SendDataTCPServer.js: TCP/IP server has received 60488 bytes of data
I/jxcore-log( 6633): 
,W/bt-btif ( 2530): bta_jv_rfc_port_to_cb(port_handle:0x10):jv handle:0x0 not FOUND
,I/jxcore-log( 6633): 2015-12-18T17:59:12.345Z SendDataTCPServer.js: TCP/IP server has received 62468 bytes of data
I/jxcore-log( 6633): 
,I/jxcore-log( 6633): 2015-12-18T17:59:12.375Z SendDataTCPServer.js: TCP/IP server has received 74348 bytes of data
I/jxcore-log( 6633): 
,I/jxcore-log( 6633): 2015-12-18T17:59:12.380Z SendDataTCPServer.js: TCP/IP server has received 76328 bytes of data
I/jxcore-log( 6633): 
,I/jxcore-log( 6633): 2015-12-18T17:59:12.415Z SendDataTCPServer.js: TCP/IP server has received 84248 bytes of data
I/jxcore-log( 6633): 
,I/jxcore-log( 6633): 2015-12-18T17:59:12.422Z SendDataTCPServer.js: TCP/IP server has received 86228 bytes of data
I/jxcore-log( 6633): 
,I/jxcore-log( 6633): 2015-12-18T17:59:12.454Z SendDataTCPServer.js: TCP/IP server has received 90188 bytes of data
I/jxcore-log( 6633): 
,I/jxcore-log( 6633): 2015-12-18T17:59:12.480Z SendDataTCPServer.js: TCP/IP server has received 92168 bytes of data
I/jxcore-log( 6633): 
,I/jxcore-log( 6633): 2015-12-18T17:59:12.516Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
I/jxcore-log( 6633): 
,W/bt-btif ( 2530): invalid rfc slot id: 12
,W/io.jxcore.node.StreamCopyingThread( 6633): Either failed to read from the output stream or write to the input stream (thread ID: 823, thread name: Receiver): bt socket closed, read return: -1
,E/io.jxcore.node.OutgoingSocketThread( 6633): The receiving thread failed with error "Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1", this is likely due to peer having disconnected
W/io.jxcore.node.ConnectionHelper( 6633): onDisconnected: Incoming connection, peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9219] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
I/io.jxcore.node.ConnectionHelper( 6633): closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 820
D/io.jxcore.node.OutgoingSocketThread( 6633): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 6633): doStop: Thread ID: 823
D/io.jxcore.node.OutgoingSocketThread( 6633): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 6633): doStop: Thread ID: 822
D/io.jxcore.node.OutgoingSocketThread( 6633): closeLocalSocketAndStreams: Closing...
D/io.jxcore.node.OutgoingSocketThread( 6633): closeLocalSocketAndStreams: Closing the local input stream...
D/io.jxcore.node.OutgoingSocketThread( 6633): closeLocalSocketAndStreams: Closing the local output stream...
D/io.jxcore.node.OutgoingSocketThread( 6633): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.OutgoingSocketThread( 6633): closeBluetoothSocketAndStreams
D/io.jxcore.node.ConnectionHelper( 6633): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
D/io.jxcore.node.StreamCopyingThread( 6633): Exiting thread (ID: 823, name: Receiver)
,W/io.jxcore.node.StreamCopyingThread( 6633): Either failed to read from the output stream or write to the input stream (thread ID: 822, thread name: Sender): Socket closed
,E/io.jxcore.node.OutgoingSocketThread( 6633): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 6633): onDisconnected: Incoming connection, peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9219] disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
D/io.jxcore.node.ConnectionHelper( 6633): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
D/io.jxcore.node.StreamCopyingThread( 6633): Exiting thread (ID: 822, name: Sender)
,I/jxcore-log( 6633): 2015-12-18T17:59:12.605Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 6633): 
,W/bt-rfcomm( 2530): rfc_find_lcid_mcb LCID reused LCID:0x4f current:0x0
W/bt-rfcomm( 2530): RFCOMM_DisconnectInd LCID:0x4f
,D/MDMCTBK (  291): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-REQ 2412 ee
,D/MDMCTBK (  291): Event received = P2P-SERV-DISC-REQ 2412 ee
,E/bt-btm  ( 2530): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2530): onReceive
,I/BTConnectionReceiver( 8520): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:3C:51, alias=null, name=G4-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 8520): Bluetooth Device Name: G4-1
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:31000 mC
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6633): checkListForExpiredPeers: Peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT5572] expired
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6633): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT5572], add/update: false
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6633): modifyListOfDiscoveredPeers: Removed [08:EC:A9:50:75:41 samsung-SM-A300FU_PT5572]
I/io.jxcore.node.ConnectionHelper( 6633): onPeerLost: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT5572]
D/io.jxcore.node.ConnectionHelper( 6633): hasConnection: No connection with peer with ID 08:EC:A9:50:75:41
D/io.jxcore.node.ConnectionHelper( 6633): modifyListOfDiscoveredPeers: Peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT5572] removed
D/io.jxcore.node.ConnectionHelper( 6633): notifyPeerAvailability: Peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT5572] not available
,I/jxcore-log( 6633): peerAvailabilityChanged [{"peerIdentifier":"08:EC:A9:50:75:41","peerName":"samsung-SM-A300FU_PT5572","peerAvailable":false}]
I/jxcore-log( 6633): 
I/jxcore-log( 6633): startWithNextDevice
I/jxcore-log( 6633): 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6633): Got discovery timeout, restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6633): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6633): setState: RESTARTING
,D/WifiP2pService(  883): InactiveState{ when=-1ms what=139268 arg2=20 target=com.android.internal.util.StateMachine$SmHandler }
,I/wpa_supplicant( 1442): P2P-FIND-STOPPED 
D/MDMCTBK (  291): reply_len: 40 reply is = <3>P2P-FIND-STOPPED 
,D/MDMCTBK (  291): Event received = P2P-FIND-STOPPED 
,I/wpa_supplicant( 1442): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
I/wpa_supplicant( 1442): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
,D/MDMCTBK (  291): reply_len: 40 reply is = <3>P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7
D/MDMCTBK (  291): Event received = P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7
D/MDMCTBK (  291): reply_len: 40 reply is = <3>P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7
D/MDMCTBK (  291): Event received = P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7
,D/WifiP2pService(  883): InactiveState{ when=-7ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  883): P2pEnabledState{ when=-7ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  883): discovery change broadcast false
,D/WifiP2pService(  883): InactiveState{ when=-5ms what=147478 obj=Device: 
D/WifiP2pService(  883):  deviceAddress: a2:39:f7:70:12:80
D/WifiP2pService(  883):  primary type: null
D/WifiP2pService(  883):  secondary type: null
D/WifiP2pService(  883):  wps: 0
D/WifiP2pService(  883):  grpcapab: 0
D/WifiP2pService(  883):  devcapab: 0
D/WifiP2pService(  883):  status: 4
D/WifiP2pService(  883):  wfdInfo: null
D/WifiP2pService(  883):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  883): P2pEnabledState{ when=-5ms what=147478 obj=Device: 
D/WifiP2pService(  883):  deviceAddress: a2:39:f7:70:12:80
D/WifiP2pService(  883):  primary type: null
D/WifiP2pService(  883):  secondary type: null
D/WifiP2pService(  883):  wps: 0
D/WifiP2pService(  883):  grpcapab: 0
D/WifiP2pService(  883):  devcapab: 0
D/WifiP2pService(  883):  status: 4
D/WifiP2pService(  883):  wfdInfo: null
D/WifiP2pService(  883):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  883): InactiveState{ when=-5ms what=147478 obj=Device: 
D/WifiP2pService(  883):  deviceAddress: a2:39:f7:6f:c9:5d
D/WifiP2pService(  883):  primary type: null
D/WifiP2pService(  883):  secondary type: null
D/WifiP2pService(  883):  wps: 0
D/WifiP2pService(  883):  grpcapab: 0
D/WifiP2pService(  883):  devcapab: 0
D/WifiP2pService(  883):  status: 4
D/WifiP2pService(  883):  wfdInfo: null
D/WifiP2pService(  883):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  883): P2pEnabledState{ when=-5ms what=147478 obj=Device: 
D/WifiP2pService(  883):  deviceAddress: a2:39:f7:6f:c9:5d
D/WifiP2pService(  883):  primary type: null
D/WifiP2pService(  883):  secondary type: null
D/WifiP2pService(  883):  wps: 0
D/WifiP2pService(  883):  grpcapab: 0
D/WifiP2pService(  883):  devcapab: 0
D/WifiP2pService(  883):  status: 4
D/WifiP2pService(  883):  wfdInfo: null
D/WifiP2pService(  883):  level: 0 target=com.android.internal.util.StateMachine$SmHandler }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6633): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped
,D/WifiP2pService(  883): InactiveState{ when=0 what=139283 arg2=21 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  883): P2pEnabledState{ when=0 what=139283 arg2=21 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  883): DefaultState{ when=0 what=139283 arg2=21 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  883): InactiveState{ when=-1ms what=139283 arg2=22 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  883): P2pEnabledState{ when=-1ms what=139283 arg2=22 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  883): DefaultState{ when=-1ms what=139283 arg2=22 target=com.android.internal.util.StateMachine$SmHandler }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6633): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6633): onP2pDeviceListChanged: 0 device(s) discovered
,W/bt-btif ( 2530): info:x10
,D/        ( 2530): remote version info [b0:c5:59:3f:75:69]: 7, f, 610c
,I/ActivityManager(  883): Waited long enough for: ServiceRecord{305c0f09 u0 com.motorola.context/.publisher.bluetoothdeterminer.BluetoothContextService}
,E/BluetoothRemoteDevices( 2530): aclStateChangeCallback: Device is NULL
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:30000 mC
,I/BluetoothBondStateMachine( 2530): bondStateChangeCallback: Status: 0 Address: B0:C5:59:3F:75:69 newState: 1
,E/bt-btif ( 2530): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2530): Bond State Change Intent:B0:C5:59:3F:75:69 OldState: 10 NewState: 11
,I/BluetoothBondStateMachine( 2530): Entering PendingCommandState State
,I/BluetoothBondStateMachine( 2530): bondStateChangeCallback: Status: 0 Address: B0:C5:59:3F:75:69 newState: 0
,D/BluetoothAdapterProperties( 2530): Failed to remove device: B0:C5:59:3F:75:69
,I/BluetoothBondStateMachine( 2530): Bond State Change Intent:B0:C5:59:3F:75:69 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2530): StableState(): Entering Off State
,D/BluetoothMetrics( 2530): btclass5a020c
,D/Checkin ( 2530): publish the event [tag = MOT_BT event name = PAIRING]
,W/bt-btif ( 2530): new conn_srvc id:26, app_id:255
,W/bt-btif ( 2530): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 2530): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6633): Incoming connection accepted
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6633): Incoming connection initialized (thread ID: 826)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6633): Waiting for incoming connections...
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 6633): Entering thread (ID: 826)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6633): onBytesRead: Read 81 bytes successfully (thread ID: 826)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6633): Got valid identity from [B0:C5:59:3F:75:69 samsung-SM-G900F_PT633]
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6633): onBytesWritten: 80 bytes successfully written (thread ID: 826)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6633): removeThreadFromList: Removing thread with ID 826
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6633): Handshake thread disposed (thread ID: 826)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6633): onIncomingConnectionConnected: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT633]
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6633): onConnected: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT633]
,I/io.jxcore.node.ConnectionHelper( 6633): onConnected: Incoming connection to peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT633]
D/io.jxcore.node.ConnectionHelper( 6633): hasConnection: No connection with peer with ID B0:C5:59:3F:75:69
,D/io.jxcore.node.ConnectionHelper( 6633): notifyPeerAvailability: Peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT633] is available
I/jxcore-log( 6633): peerAvailabilityChanged [{"peerIdentifier":"B0:C5:59:3F:75:69","peerName":"samsung-SM-G900F_PT633","peerAvailable":true}]
I/jxcore-log( 6633): 
I/jxcore-log( 6633): Found peer : samsung-SM-G900F_PT633, Available: true
I/jxcore-log( 6633): 
I/jxcore-log( 6633): startWithNextDevice
I/jxcore-log( 6633): 
I/jxcore-log( 6633): device[6]: B0:C5:59:3F:75:69
I/jxcore-log( 6633): 
I/jxcore-log( 6633): 2015-12-18T17:59:33.480Z SendDataConnector.js: Start called with peer B0:C5:59:3F:75:69
I/jxcore-log( 6633): 
I/jxcore-log( 6633): 2015-12-18T17:59:33.480Z SendDataConnector.js: doConnect called with peer B0:C5:59:3F:75:69
I/jxcore-log( 6633): 
,I/jxcore-log( 6633): 2015-12-18T17:59:33.480Z SendDataConnector.js: do connect now
I/jxcore-log( 6633): 
I/io.jxcore.node.ConnectionHelper( 6633): connect: Trying to connect to peer with ID B0:C5:59:3F:75:69
D/io.jxcore.node.ConnectionHelper( 6633): hasConnection: No connection with peer with ID B0:C5:59:3F:75:69
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6633): connect: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT633]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6633): connect: Trying to start connecting to Thali Test (Galaxy S5) in address B0:C5:59:3F:75:69
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6633): setInsecureRfcommSocketPort: Using port -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6633): setMaxNumberOfRetries: 0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6633): onConnecting: Thali Test (Galaxy S5) B0:C5:59:3F:75:69
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6633): connect: Started connecting to Thali Test (Galaxy S5) in address B0:C5:59:3F:75:69
I/io.jxcore.node.ConnectionHelper( 6633): connect: Connection process successfully started (peer ID: B0:C5:59:3F:75:69)
I/io.jxcore.node.ConnectionHelper( 6633): onConnected: Incoming socket thread, for peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT633], created successfully
D/io.jxcore.node.ConnectionHelper( 6633): onConnected: The total number of connections is now 1
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 6633): Exiting thread (ID: 826)
,D/io.jxcore.node.IncomingSocketThread( 6633): Entering thread (ID: 828)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6633): Trying to connect to peer with address B0:C5:59:3F:75:69 (thread ID: 827)
W/BluetoothAdapter( 6633): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2530): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/io.jxcore.node.IncomingSocketThread( 6633): Local host address: localhost/127.0.0.1, port: 57867
D/io.jxcore.node.IncomingSocketThread( 6633): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 6633): setBufferSize: Setting buffer size to 8192 bytes
,I/jxcore-log( 6633): 2015-12-18T17:59:33.509Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 6633): 
,I/io.jxcore.node.StreamCopyingThread( 6633): setBufferSize: Setting buffer size to 8192 bytes
,I/io.jxcore.node.IncomingSocketThread( 6633): startStreamCopyingThreads: OK
D/io.jxcore.node.IncomingSocketThread( 6633): Exiting thread (ID: 828)
,D/io.jxcore.node.StreamCopyingThread( 6633): Entering thread (ID: 830, name: Receiver)
,D/io.jxcore.node.StreamCopyingThread( 6633): Entering thread (ID: 829, name: Sender)
,W/bt-sdp  ( 2530): process_service_search_attr_rsp
,W/bt-btif ( 2530): new conn_srvc id:26, app_id:1
,W/bt-btif ( 2530): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 2530): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2530): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6633): onSocketConnected: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT633]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6633): Socket connection succeeded (using system decided port), total number of attempts: 1 (thread ID: 827)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6633): onBytesWritten: 80 bytes successfully written (thread ID: 831)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6633): Outgoing connection initialized (*handshake* thread ID: 831)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6633): Exiting thread (thread ID: 827)
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 6633): Entering thread (ID: 831)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6633): onBytesRead: Read 81 bytes successfully (thread ID: 831)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6633): Handshake succeeded with [B0:C5:59:3F:75:69 samsung-SM-G900F_PT633]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6633): onHandshakeSucceeded: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT633]
D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 6633): Exiting thread (ID: 831)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6633): onConnected: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT633]
I/io.jxcore.node.ConnectionHelper( 6633): onConnected: Outgoing connection to peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT633]
,D/io.jxcore.node.ConnectionHelper( 6633): hasConnection: We have an incoming connection with peer with ID B0:C5:59:3F:75:69
W/io.jxcore.node.ConnectionHelper( 6633): onConnected: Already connected with peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT633], continuing anyway...
W/io.jxcore.node.ConnectionHelper( 6633): modifyListOfDiscoveredPeers: Peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT633] already in the list, will not add again
,I/io.jxcore.node.ConnectionHelper( 6633): onConnected: Outgoing socket thread, for peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT633], created successfully
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6633): setInsecureRfcommSocketPort: Will use port -1 when trying to connect
,D/io.jxcore.node.ConnectionHelper( 6633): onConnected: The total number of connections is now 2
,D/io.jxcore.node.OutgoingSocketThread( 6633): Entering thread (ID: 832)
D/io.jxcore.node.OutgoingSocketThread( 6633): Server socket local port: 38585
I/io.jxcore.node.OutgoingSocketThread( 6633): Now accepting connections...
,I/io.jxcore.node.ConnectionHelper( 6633): onListeningForIncomingConnections: Outgoing connection is using port 38585 (peer ID: B0:C5:59:3F:75:69)
,I/jxcore-log( 6633): 2015-12-18T17:59:34.296Z SendDataConnector.js: CLIENT connected to 38585, error: null
I/jxcore-log( 6633): 
,I/jxcore-log( 6633): 2015-12-18T17:59:34.296Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 6633): 
,I/io.jxcore.node.OutgoingSocketThread( 6633): Incoming data from address: /127.0.0.1, port: 38585
,D/io.jxcore.node.OutgoingSocketThread( 6633): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 6633): setBufferSize: Setting buffer size to 8192 bytes
,I/io.jxcore.node.StreamCopyingThread( 6633): setBufferSize: Setting buffer size to 8192 bytes
,I/io.jxcore.node.OutgoingSocketThread( 6633): startStreamCopyingThreads: OK
D/io.jxcore.node.OutgoingSocketThread( 6633): Exiting thread (ID: 832)
,D/io.jxcore.node.StreamCopyingThread( 6633): Entering thread (ID: 833, name: Sender)
,I/jxcore-log( 6633): 2015-12-18T17:59:34.316Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 6633): 
,D/io.jxcore.node.StreamCopyingThread( 6633): Entering thread (ID: 834, name: Receiver)
,I/jxcore-log( 6633): 2015-12-18T17:59:34.946Z SendDataTCPServer.js: TCP/IP server has received 92168 bytes of data
I/jxcore-log( 6633): 
,I/jxcore-log( 6633): 2015-12-18T17:59:34.991Z SendDataTCPServer.js: TCP/IP server has received 94148 bytes of data
I/jxcore-log( 6633): 
,I/jxcore-log( 6633): 2015-12-18T17:59:35.024Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
I/jxcore-log( 6633): 
,I/jxcore-log( 6633): 2015-12-18T17:59:35.054Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 6633): 
,I/jxcore-log( 6633): 2015-12-18T17:59:35.142Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 6633): 
,I/jxcore-log( 6633): 2015-12-18T17:59:35.190Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 6633): 
,I/jxcore-log( 6633): 2015-12-18T17:59:35.237Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 6633): 
,I/jxcore-log( 6633): 2015-12-18T17:59:35.325Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 6633): 
,I/jxcore-log( 6633): 2015-12-18T17:59:35.331Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 6633): 
,I/jxcore-log( 6633): 2015-12-18T17:59:35.450Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 6633): 
,W/bt-btif ( 2530): invalid rfc slot id: 14
,W/io.jxcore.node.StreamCopyingThread( 6633): Either failed to read from the output stream or write to the input stream (thread ID: 830, thread name: Receiver): bt socket closed, read return: -1
E/io.jxcore.node.OutgoingSocketThread( 6633): The receiving thread failed with error "Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1", this is likely due to peer having disconnected
,W/io.jxcore.node.ConnectionHelper( 6633): onDisconnected: Incoming connection, peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT633] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
I/io.jxcore.node.ConnectionHelper( 6633): closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 828
D/io.jxcore.node.OutgoingSocketThread( 6633): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 6633): doStop: Thread ID: 830
D/io.jxcore.node.OutgoingSocketThread( 6633): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 6633): doStop: Thread ID: 829
D/io.jxcore.node.OutgoingSocketThread( 6633): closeLocalSocketAndStreams: Closing...
D/io.jxcore.node.OutgoingSocketThread( 6633): closeLocalSocketAndStreams: Closing the local input stream...
D/io.jxcore.node.OutgoingSocketThread( 6633): closeLocalSocketAndStreams: Closing the local output stream...
D/io.jxcore.node.OutgoingSocketThread( 6633): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.OutgoingSocketThread( 6633): closeBluetoothSocketAndStreams
D/io.jxcore.node.ConnectionHelper( 6633): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
D/io.jxcore.node.StreamCopyingThread( 6633): Exiting thread (ID: 830, name: Receiver)
,W/io.jxcore.node.StreamCopyingThread( 6633): Either failed to read from the output stream or write to the input stream (thread ID: 829, thread name: Sender): Socket closed
E/io.jxcore.node.OutgoingSocketThread( 6633): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 6633): onDisconnected: Incoming connection, peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT633] disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
D/io.jxcore.node.ConnectionHelper( 6633): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
D/io.jxcore.node.StreamCopyingThread( 6633): Exiting thread (ID: 829, name: Sender)
,I/jxcore-log( 6633): 2015-12-18T17:59:35.476Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 6633): 
,I/jxcore-log( 6633): 2015-12-18T17:59:35.545Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 6633): 
,I/jxcore-log( 6633): 2015-12-18T17:59:35.650Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 6633): 
,I/jxcore-log( 6633): 2015-12-18T17:59:35.756Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 6633): 
,I/jxcore-log( 6633): 2015-12-18T17:59:35.756Z SendDataConnector.js: got all data for this round
I/jxcore-log( 6633): 
I/jxcore-log( 6633): oneRoundDownNow
I/jxcore-log( 6633): 
,I/jxcore-log( 6633): 2015-12-18T17:59:35.760Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 6633): 
I/jxcore-log( 6633): 2015-12-18T17:59:35.761Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 6633): 
,D/io.jxcore.node.ConnectionHelper( 6633): disconnectOutgoingConnection: Trying to close connection to peer with ID B0:C5:59:3F:75:69
I/io.jxcore.node.ConnectionHelper( 6633): closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: B0:C5:59:3F:75:69
I/io.jxcore.node.OutgoingSocketThread( 6633): close
D/io.jxcore.node.OutgoingSocketThread( 6633): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 6633): doStop: Thread ID: 834
D/io.jxcore.node.OutgoingSocketThread( 6633): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 6633): doStop: Thread ID: 833
D/io.jxcore.node.OutgoingSocketThread( 6633): closeLocalSocketAndStreams: Closing...
D/io.jxcore.node.OutgoingSocketThread( 6633): closeLocalSocketAndStreams: Closing the local input stream...
,W/io.jxcore.node.StreamCopyingThread( 6633): Either failed to read from the output stream or write to the input stream (thread ID: 833, thread name: Sender): Socket closed
E/io.jxcore.node.OutgoingSocketThread( 6633): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 6633): onDisconnected: Outgoing connection, peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT633] disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
,D/io.jxcore.node.OutgoingSocketThread( 6633): closeLocalSocketAndStreams: Closing the local output stream...
,D/io.jxcore.node.OutgoingSocketThread( 6633): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.OutgoingSocketThread( 6633): closeBluetoothSocketAndStreams
W/io.jxcore.node.StreamCopyingThread( 6633): Either failed to read from the output stream or write to the input stream (thread ID: 834, thread name: Receiver): bt socket closed, read return: -1
E/io.jxcore.node.OutgoingSocketThread( 6633): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
W/io.jxcore.node.ConnectionHelper( 6633): onDisconnected: Outgoing connection, peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT633] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
,D/io.jxcore.node.ConnectionHelper( 6633): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
I/io.jxcore.node.ConnectionHelper( 6633): disconnectOutgoingConnection: Successfully disconnected (peer ID: B0:C5:59:3F:75:69
,E/io.jxcore.node.ConnectionHelper( 6633): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID B0:C5:59:3F:75:69
D/io.jxcore.node.ConnectionHelper( 6633): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
D/io.jxcore.node.StreamCopyingThread( 6633): Exiting thread (ID: 833, name: Sender)
,E/io.jxcore.node.ConnectionHelper( 6633): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID B0:C5:59:3F:75:69
D/io.jxcore.node.ConnectionHelper( 6633): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
D/io.jxcore.node.StreamCopyingThread( 6633): Exiting thread (ID: 834, name: Receiver)
,I/jxcore-log( 6633): 2015-12-18T17:59:35.782Z SendDataConnector.js: Mobile.Disconnect() callback with peer B0:C5:59:3F:75:69
I/jxcore-log( 6633): 
,I/jxcore-log( 6633): ---- round done--------
I/jxcore-log( 6633): 
I/jxcore-log( 6633): startWithNextDevice
I/jxcore-log( 6633): 
,W/bt-btif ( 2530): bta_jv_rfc_port_to_cb(port_handle:0x13):jv handle:0x0 not FOUND
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6633): Start timer timeout, starting now...
,D/WifiP2pService(  883): InactiveState{ when=0 what=139265 arg2=23 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  883): P2pEnabledState{ when=0 what=139265 arg2=23 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 1442): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  291): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  291): Event received = CTRL-EVENT-SCAN-STARTED 
,D/WifiP2pService(  883): discovery change broadcast true
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6633): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6633): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6633): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,D/MDMCTBK (  291): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 3 c0
,D/MDMCTBK (  291): Event received = CTRL-EVENT-BSS-ADDED 3 c0
,D/TCMD    (  474): NL - Read 56 bytes from update socket.
,D/TCMD    (  474): NL - message type is RTM_NEWLINK
D/TCMD    (  474): Listening for incoming client connection request
,D/btif_config_util( 2530): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/wpa_supplicant( 1442): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  291): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  291): Event received = CTRL-EVENT-SCAN-STARTED 
,D/TCMD    (  474): NL - Read 56 bytes from update socket.
,D/TCMD    (  474): NL - message type is RTM_NEWLINK
D/TCMD    (  474): Listening for incoming client connection request
,I/wpa_supplicant( 1442): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  291): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  291): Event received = CTRL-EVENT-SCAN-STARTED 
,D/TCMD    (  474): NL - Read 56 bytes from update socket.
,D/TCMD    (  474): NL - message type is RTM_NEWLINK
D/TCMD    (  474): Listening for incoming client connection request
,E/bt-btm  ( 2530): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2530): onReceive
,I/BTConnectionReceiver( 8520): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=B0:C5:59:3F:75:69, alias=null, name=Thali Test (Galaxy S5), majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 8520): Bluetooth Device Name: Thali Test (Galaxy S5)
,I/wpa_supplicant( 1442): p2p0: CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  291): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  291): Event received = CTRL-EVENT-SCAN-STARTED 
,D/TCMD    (  474): NL - Read 56 bytes from update socket.
,D/TCMD    (  474): NL - message type is RTM_NEWLINK
D/TCMD    (  474): Listening for incoming client connection request
,I/wpa_supplicant( 1442): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  291): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  291): Event received = CTRL-EVENT-SCAN-STARTED 
,D/TCMD    (  474): NL - Read 56 bytes from update socket.
,D/TCMD    (  474): NL - message type is RTM_NEWLINK
D/TCMD    (  474): Listening for incoming client connection request
,I/wpa_supplicant( 1442): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  291): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  291): Event received = CTRL-EVENT-SCAN-STARTED 
,D/TCMD    (  474): NL - Read 56 bytes from update socket.
,D/TCMD    (  474): NL - message type is RTM_NEWLINK
D/TCMD    (  474): Listening for incoming client connection request
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:30000 mC
,I/wpa_supplicant( 1442): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  291): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  291): Event received = CTRL-EVENT-SCAN-STARTED 
,D/TCMD    (  474): NL - Read 56 bytes from update socket.
,D/TCMD    (  474): NL - message type is RTM_NEWLINK
D/TCMD    (  474): Listening for incoming client connection request
,I/wpa_supplicant( 1442): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  291): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  291): Event received = CTRL-EVENT-SCAN-STARTED 
,D/TCMD    (  474): NL - Read 56 bytes from update socket.
,D/TCMD    (  474): NL - message type is RTM_NEWLINK
D/TCMD    (  474): Listening for incoming client connection request
,D/MDMCTBK (  291): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-REQ 2412 52
,D/MDMCTBK (  291): Event received = P2P-SERV-DISC-REQ 2412 52
,I/wpa_supplicant( 1442): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  291): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  291): Event received = CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  291): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 3 
D/MDMCTBK (  291): Event received = CTRL-EVENT-BSS-REMOVED 3 
,I/wpa_supplicant( 1442): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 level=-45
,D/MDMCTBK (  291): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 4 c0
D/MDMCTBK (  291): Event received = CTRL-EVENT-BSS-ADDED 4 c0
D/MDMCTBK (  291): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2
D/MDMCTBK (  291): Event received = P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2
,D/TCMD    (  474): NL - Read 56 bytes from update socket.
D/TCMD    (  474): NL - message type is RTM_NEWLINK
D/TCMD    (  474): Listening for incoming client connection request
,D/WifiP2pService(  883): InactiveState{ when=0 what=147477 obj=Device: G3s-1
D/WifiP2pService(  883):  deviceAddress: a2:39:f7:70:12:80
D/WifiP2pService(  883):  primary type: 10-0050F204-5
D/WifiP2pService(  883):  secondary type: null
D/WifiP2pService(  883):  wps: 4488
D/WifiP2pService(  883):  grpcapab: 0
D/WifiP2pService(  883):  devcapab: 37
D/WifiP2pService(  883):  status: 3
D/WifiP2pService(  883):  wfdInfo: null
D/WifiP2pService(  883):  level: -45 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  883): P2pEnabledState{ when=0 what=147477 obj=Device: G3s-1
D/WifiP2pService(  883):  deviceAddress: a2:39:f7:70:12:80
D/WifiP2pService(  883):  primary type: 10-0050F204-5
D/WifiP2pService(  883):  secondary type: null
D/WifiP2pService(  883):  wps: 4488
D/WifiP2pService(  883):  grpcapab: 0
D/WifiP2pService(  883):  devcapab: 37
D/WifiP2pService(  883):  status: 3
D/WifiP2pService(  883):  wfdInfo: null
D/WifiP2pService(  883):  level: -45 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  883): InactiveState{ when=0 what=139283 arg2=24 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  883): P2pEnabledState{ when=0 what=139283 arg2=24 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  883): DefaultState{ when=0 what=139283 arg2=24 target=com.android.internal.util.StateMachine$SmHandler }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6633): onP2pDeviceListChanged: 1 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6633): onP2pDeviceListChanged: Peer 1: G3s-1 a2:39:f7:70:12:80
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6633): restart: Restarting...
,D/WifiP2pService(  883): InactiveState{ when=0 what=139307 arg2=25 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  883): P2pEnabledState{ when=0 what=139307 arg2=25 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  883): P2pEnabledState clear service request
,D/WifiP2pService(  883): InactiveState{ when=0 what=139301 arg2=26 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  883): P2pEnabledState{ when=0 what=139301 arg2=26 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  883): P2pEnabledState add service request
,D/WifiP2pManager( 6633): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6633): Service request added successfully
,W/bt-btif ( 2530): info:x10
,D/        ( 2530): remote version info [34:fc:ef:11:ae:67]: 7, f, 6109
,E/BluetoothRemoteDevices( 2530): aclStateChangeCallback: Device is NULL
,I/BluetoothBondStateMachine( 2530): bondStateChangeCallback: Status: 0 Address: 34:FC:EF:11:AE:67 newState: 1
,E/bt-btif ( 2530): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2530): Bond State Change Intent:34:FC:EF:11:AE:67 OldState: 10 NewState: 11
,I/BluetoothBondStateMachine( 2530): Entering PendingCommandState State
,I/wpa_supplicant( 1442): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  291): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  291): Event received = CTRL-EVENT-SCAN-STARTED 
,I/BluetoothBondStateMachine( 2530): bondStateChangeCallback: Status: 0 Address: 34:FC:EF:11:AE:67 newState: 0
,D/BluetoothAdapterProperties( 2530): Failed to remove device: 34:FC:EF:11:AE:67
,I/BluetoothBondStateMachine( 2530): Bond State Change Intent:34:FC:EF:11:AE:67 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2530): StableState(): Entering Off State
,D/BluetoothMetrics( 2530): btclass5a020c
,W/bt-btif ( 2530): new conn_srvc id:26, app_id:255
W/bt-btif ( 2530): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 2530): bta_dm_pm_ssr:2, lat:1200
,D/Checkin ( 2530): publish the event [tag = MOT_BT event name = PAIRING]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6633): Incoming connection accepted
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6633): Incoming connection initialized (thread ID: 835)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6633): Waiting for incoming connections...
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 6633): Entering thread (ID: 835)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6633): onBytesRead: Read 77 bytes successfully (thread ID: 835)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6633): Got valid identity from [34:FC:EF:11:AE:67 LGE-Nexus 5_PT5924]
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6633): onBytesWritten: 80 bytes successfully written (thread ID: 835)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6633): removeThreadFromList: Removing thread with ID 835
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6633): Handshake thread disposed (thread ID: 835)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6633): onIncomingConnectionConnected: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT5924]
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6633): onConnected: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT5924]
I/io.jxcore.node.ConnectionHelper( 6633): onConnected: Incoming connection to peer [34:FC:EF:11:AE:67 LGE-Nexus 5_PT5924]
D/io.jxcore.node.ConnectionHelper( 6633): hasConnection: No connection with peer with ID 34:FC:EF:11:AE:67
D/io.jxcore.node.ConnectionHelper( 6633): notifyPeerAvailability: Peer [34:FC:EF:11:AE:67 LGE-Nexus 5_PT5924] is available
I/jxcore-log( 6633): peerAvailabilityChanged [{"peerIdentifier":"34:FC:EF:11:AE:67","peerName":"LGE-Nexus 5_PT5924","peerAvailable":true}]
I/jxcore-log( 6633): 
I/jxcore-log( 6633): Found peer : LGE-Nexus 5_PT5924, Available: true
I/jxcore-log( 6633): 
I/jxcore-log( 6633): startWithNextDevice
I/jxcore-log( 6633): 
I/jxcore-log( 6633): device[7]: 34:FC:EF:11:AE:67
I/jxcore-log( 6633): 
I/jxcore-log( 6633): 2015-12-18T17:59:44.932Z SendDataConnector.js: Start called with peer 34:FC:EF:11:AE:67
I/jxcore-log( 6633): 
I/jxcore-log( 6633): 2015-12-18T17:59:44.932Z SendDataConnector.js: doConnect called with peer 34:FC:EF:11:AE:67
I/jxcore-log( 6633): 
I/jxcore-log( 6633): 2015-12-18T17:59:44.932Z SendDataConnector.js: do connect now
I/jxcore-log( 6633): 
,I/io.jxcore.node.ConnectionHelper( 6633): connect: Trying to connect to peer with ID 34:FC:EF:11:AE:67
D/io.jxcore.node.ConnectionHelper( 6633): hasConnection: No connection with peer with ID 34:FC:EF:11:AE:67
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6633): connect: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT5924]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6633): connect: Trying to start connecting to Nexus 5 in address 34:FC:EF:11:AE:67
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6633): setInsecureRfcommSocketPort: Using port -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6633): setMaxNumberOfRetries: 0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6633): onConnecting: Nexus 5 34:FC:EF:11:AE:67
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6633): connect: Started connecting to Nexus 5 in address 34:FC:EF:11:AE:67
I/io.jxcore.node.ConnectionHelper( 6633): connect: Connection process successfully started (peer ID: 34:FC:EF:11:AE:67)
I/io.jxcore.node.ConnectionHelper( 6633): onConnected: Incoming socket thread, for peer [34:FC:EF:11:AE:67 LGE-Nexus 5_PT5924], created successfully
D/io.jxcore.node.ConnectionHelper( 6633): onConnected: The total number of connections is now 1
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 6633): Exiting thread (ID: 835)
,D/io.jxcore.node.IncomingSocketThread( 6633): Entering thread (ID: 837)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6633): Trying to connect to peer with address 34:FC:EF:11:AE:67 (thread ID: 836)
W/BluetoothAdapter( 6633): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2530): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/io.jxcore.node.IncomingSocketThread( 6633): Local host address: localhost/127.0.0.1, port: 57867
D/io.jxcore.node.IncomingSocketThread( 6633): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 6633): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 6633): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.IncomingSocketThread( 6633): startStreamCopyingThreads: OK
D/io.jxcore.node.IncomingSocketThread( 6633): Exiting thread (ID: 837)
,I/jxcore-log( 6633): 2015-12-18T17:59:44.954Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 6633): 
,D/io.jxcore.node.StreamCopyingThread( 6633): Entering thread (ID: 838, name: Sender)
,D/io.jxcore.node.StreamCopyingThread( 6633): Entering thread (ID: 839, name: Receiver)
,D/WifiP2pService(  883): InactiveState{ when=0 what=139310 arg2=27 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  883): P2pEnabledState{ when=0 what=139310 arg2=27 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  883): P2pEnabledState discover services
I/wpa_supplicant( 1442): p2p0: P2P: Reject scan trigger since one is already pending
D/MDMCTBK (  291): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P: Reject scan trigger 
D/MDMCTBK (  291): Event received = P2P: Reject scan trigger 
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6633): Service discovery started successfully
,W/bt-sdp  ( 2530): process_service_search_attr_rsp
,I/wpa_supplicant( 1442): P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 level=-48
D/MDMCTBK (  291): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2
,D/MDMCTBK (  291): Event received = P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2
D/WifiP2pService(  883): InactiveState{ when=0 what=147477 obj=Device: Android_8ae2
D/WifiP2pService(  883):  deviceAddress: 52:55:27:f0:fd:0b
D/WifiP2pService(  883):  primary type: 10-0050F204-5
D/WifiP2pService(  883):  secondary type: null
D/WifiP2pService(  883):  wps: 392
D/WifiP2pService(  883):  grpcapab: 0
D/WifiP2pService(  883):  devcapab: 37
D/WifiP2pService(  883):  status: 3
D/WifiP2pService(  883):  wfdInfo: null
D/WifiP2pService(  883):  level: -48 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  883): P2pEnabledState{ when=0 what=147477 obj=Device: Android_8ae2
D/WifiP2pService(  883):  deviceAddress: 52:55:27:f0:fd:0b
D/WifiP2pService(  883):  primary type: 10-0050F204-5
D/WifiP2pService(  883):  secondary type: null
D/WifiP2pService(  883):  wps: 392
D/WifiP2pService(  883):  grpcapab: 0
D/WifiP2pService(  883):  devcapab: 37
D/WifiP2pService(  883):  status: 3
D/WifiP2pService(  883):  wfdInfo: null
D/WifiP2pService(  883):  level: -48 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  883): InactiveState{ when=0 what=139283 arg2=28 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  883): P2pEnabledState{ when=0 what=139283 arg2=28 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  883): DefaultState{ when=0 what=139283 arg2=28 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6633): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6633): onP2pDeviceListChanged: Peer 1: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6633): onP2pDeviceListChanged: Peer 2: Android_8ae2 52:55:27:f0:fd:0b
,D/TCMD    (  474): NL - Read 56 bytes from update socket.
,D/TCMD    (  474): NL - message type is RTM_NEWLINK
D/TCMD    (  474): Listening for incoming client connection request
,W/bt-btif ( 2530): new conn_srvc id:26, app_id:1
,W/bt-btif ( 2530): bta_dm_pm_ssr conn_srvc id:26, app_id:255
,W/bt-btif ( 2530): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2530): bta_dm_pm_ssr:2, lat:1200
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6633): onSocketConnected: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT5924]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6633): Socket connection succeeded (using system decided port), total number of attempts: 1 (thread ID: 836)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6633): onBytesWritten: 80 bytes successfully written (thread ID: 840)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6633): Outgoing connection initialized (*handshake* thread ID: 840)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6633): Exiting thread (thread ID: 836)
D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 6633): Entering thread (ID: 840)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6633): onBytesRead: Read 77 bytes successfully (thread ID: 840)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6633): Handshake succeeded with [34:FC:EF:11:AE:67 LGE-Nexus 5_PT5924]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6633): onHandshakeSucceeded: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT5924]
D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 6633): Exiting thread (ID: 840)
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6633): onConnected: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT5924]
I/io.jxcore.node.ConnectionHelper( 6633): onConnected: Outgoing connection to peer [34:FC:EF:11:AE:67 LGE-Nexus 5_PT5924]
D/io.jxcore.node.ConnectionHelper( 6633): hasConnection: We have an incoming connection with peer with ID 34:FC:EF:11:AE:67
,W/io.jxcore.node.ConnectionHelper( 6633): onConnected: Already connected with peer [34:FC:EF:11:AE:67 LGE-Nexus 5_PT5924], continuing anyway...
W/io.jxcore.node.ConnectionHelper( 6633): modifyListOfDiscoveredPeers: Peer [34:FC:EF:11:AE:67 LGE-Nexus 5_PT5924] already in the list, will not add again
I/io.jxcore.node.ConnectionHelper( 6633): onConnected: Outgoing socket thread, for peer [34:FC:EF:11:AE:67 LGE-Nexus 5_PT5924], created successfully
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6633): setInsecureRfcommSocketPort: Will use port -1 when trying to connect
,D/io.jxcore.node.ConnectionHelper( 6633): onConnected: The total number of connections is now 2
D/io.jxcore.node.OutgoingSocketThread( 6633): Entering thread (ID: 841)
D/io.jxcore.node.OutgoingSocketThread( 6633): Server socket local port: 46661
I/io.jxcore.node.OutgoingSocketThread( 6633): Now accepting connections...
,I/io.jxcore.node.ConnectionHelper( 6633): onListeningForIncomingConnections: Outgoing connection is using port 46661 (peer ID: 34:FC:EF:11:AE:67)
,I/jxcore-log( 6633): 2015-12-18T17:59:45.709Z SendDataConnector.js: CLIENT connected to 46661, error: null
I/jxcore-log( 6633): 
I/jxcore-log( 6633): 2015-12-18T17:59:45.709Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 6633): 
,I/io.jxcore.node.OutgoingSocketThread( 6633): Incoming data from address: /127.0.0.1, port: 46661
,D/io.jxcore.node.OutgoingSocketThread( 6633): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 6633): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 6633): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.OutgoingSocketThread( 6633): startStreamCopyingThreads: OK
D/io.jxcore.node.OutgoingSocketThread( 6633): Exiting thread (ID: 841)
,I/jxcore-log( 6633): 2015-12-18T17:59:45.725Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 6633): 
,D/io.jxcore.node.StreamCopyingThread( 6633): Entering thread (ID: 843, name: Receiver)
,D/io.jxcore.node.StreamCopyingThread( 6633): Entering thread (ID: 842, name: Sender)
,I/jxcore-log( 6633): 2015-12-18T17:59:46.264Z SendDataTCPServer.js: TCP/IP server has received 19800 bytes of data
I/jxcore-log( 6633): 
,I/jxcore-log( 6633): 2015-12-18T17:59:46.299Z SendDataTCPServer.js: TCP/IP server has received 21780 bytes of data
I/jxcore-log( 6633): 
,I/jxcore-log( 6633): 2015-12-18T17:59:46.362Z SendDataTCPServer.js: TCP/IP server has received 23760 bytes of data
I/jxcore-log( 6633): 
,I/jxcore-log( 6633): 2015-12-18T17:59:46.523Z SendDataTCPServer.js: TCP/IP server has received 25740 bytes of data
I/jxcore-log( 6633): 
,I/jxcore-log( 6633): 2015-12-18T17:59:46.548Z SendDataTCPServer.js: TCP/IP server has received 27720 bytes of data
I/jxcore-log( 6633): 
,I/jxcore-log( 6633): 2015-12-18T17:59:46.595Z SendDataTCPServer.js: TCP/IP server has received 29700 bytes of data
I/jxcore-log( 6633): 
,I/jxcore-log( 6633): 2015-12-18T17:59:46.625Z SendDataTCPServer.js: TCP/IP server has received 31680 bytes of data
I/jxcore-log( 6633): 
,D/        ( 2530): PORT_WriteDataCO: tx queue is full,tx.queue_size:10172,tx.queue.count:11,available:24706
,I/jxcore-log( 6633): 2015-12-18T17:59:46.668Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 6633): 
,I/jxcore-log( 6633): 2015-12-18T17:59:46.683Z SendDataTCPServer.js: TCP/IP server has received 32768 bytes of data
I/jxcore-log( 6633): 
,I/jxcore-log( 6633): 2015-12-18T17:59:46.714Z SendDataTCPServer.js: TCP/IP server has received 38708 bytes of data
I/jxcore-log( 6633): 
,I/jxcore-log( 6633): 2015-12-18T17:59:46.737Z SendDataTCPServer.js: TCP/IP server has received 40688 bytes of data
I/jxcore-log( 6633): 
,I/jxcore-log( 6633): 2015-12-18T17:59:46.744Z SendDataTCPServer.js: TCP/IP server has received 42668 bytes of data
I/jxcore-log( 6633): 
,I/jxcore-log( 6633): 2015-12-18T17:59:46.775Z SendDataTCPServer.js: TCP/IP server has received 44648 bytes of data
I/jxcore-log( 6633): 
,I/jxcore-log( 6633): 2015-12-18T17:59:46.782Z SendDataTCPServer.js: TCP/IP server has received 46628 bytes of data
I/jxcore-log( 6633): 
,I/jxcore-log( 6633): 2015-12-18T17:59:46.788Z SendDataTCPServer.js: TCP/IP server has received 48608 bytes of data
I/jxcore-log( 6633): 
,I/jxcore-log( 6633): 2015-12-18T17:59:46.794Z SendDataTCPServer.js: TCP/IP server has received 50588 bytes of data
I/jxcore-log( 6633): 
,D/        ( 2530): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:19756
,I/jxcore-log( 6633): 2015-12-18T17:59:46.803Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 6633): 
,I/jxcore-log( 6633): 2015-12-18T17:59:46.835Z SendDataTCPServer.js: TCP/IP server has received 52568 bytes of data
I/jxcore-log( 6633): 
,I/jxcore-log( 6633): 2015-12-18T17:59:46.874Z SendDataTCPServer.js: TCP/IP server has received 56528 bytes of data
I/jxcore-log( 6633): 
,I/jxcore-log( 6633): 2015-12-18T17:59:46.888Z SendDataTCPServer.js: TCP/IP server has received 58508 bytes of data
I/jxcore-log( 6633): 
,I/jxcore-log( 6633): 2015-12-18T17:59:46.897Z SendDataTCPServer.js: TCP/IP server has received 60488 bytes of data
I/jxcore-log( 6633): 
,I/jxcore-log( 6633): 2015-12-18T17:59:46.903Z SendDataTCPServer.js: TCP/IP server has received 62468 bytes of data
I/jxcore-log( 6633): 
,I/jxcore-log( 6633): 2015-12-18T17:59:46.934Z SendDataTCPServer.js: TCP/IP server has received 66428 bytes of data
I/jxcore-log( 6633): 
,I/jxcore-log( 6633): 2015-12-18T17:59:46.975Z SendDataTCPServer.js: TCP/IP server has received 68408 bytes of data
I/jxcore-log( 6633): 
,I/jxcore-log( 6633): 2015-12-18T17:59:47.019Z SendDataTCPServer.js: TCP/IP server has received 70388 bytes of data
I/jxcore-log( 6633): 
,D/        ( 2530): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:8866
,I/jxcore-log( 6633): 2015-12-18T17:59:47.030Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 6633): 
,I/jxcore-log( 6633): 2015-12-18T17:59:47.052Z SendDataTCPServer.js: TCP/IP server has received 72368 bytes of data
I/jxcore-log( 6633): 
,I/jxcore-log( 6633): 2015-12-18T17:59:47.084Z SendDataTCPServer.js: TCP/IP server has received 74348 bytes of data
I/jxcore-log( 6633): 
,I/jxcore-log( 6633): 2015-12-18T17:59:47.128Z SendDataTCPServer.js: TCP/IP server has received 76328 bytes of data
I/jxcore-log( 6633): 
,I/jxcore-log( 6633): 2015-12-18T17:59:47.150Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 6633): 
,I/jxcore-log( 6633): 2015-12-18T17:59:47.165Z SendDataTCPServer.js: TCP/IP server has received 80288 bytes of data
I/jxcore-log( 6633): 
,I/jxcore-log( 6633): 2015-12-18T17:59:47.180Z SendDataTCPServer.js: TCP/IP server has received 82268 bytes of data
I/jxcore-log( 6633): 
,I/jxcore-log( 6633): 2015-12-18T17:59:47.215Z SendDataTCPServer.js: TCP/IP server has received 84248 bytes of data
I/jxcore-log( 6633): 
,I/jxcore-log( 6633): 2015-12-18T17:59:47.255Z SendDataTCPServer.js: TCP/IP server has received 86228 bytes of data
I/jxcore-log( 6633): 
,I/jxcore-log( 6633): 2015-12-18T17:59:47.293Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 6633): 
,I/jxcore-log( 6633): 2015-12-18T17:59:47.297Z SendDataTCPServer.js: TCP/IP server has received 90188 bytes of data
I/jxcore-log( 6633): 
,I/jxcore-log( 6633): 2015-12-18T17:59:47.335Z SendDataTCPServer.js: TCP/IP server has received 92168 bytes of data
I/jxcore-log( 6633): 
,I/jxcore-log( 6633): 2015-12-18T17:59:47.377Z SendDataTCPServer.js: TCP/IP server has received 96128 bytes of data
I/jxcore-log( 6633): 
,I/jxcore-log( 6633): 2015-12-18T17:59:47.414Z SendDataTCPServer.js: TCP/IP server has received 98108 bytes of data
I/jxcore-log( 6633): 
,I/jxcore-log( 6633): 2015-12-18T17:59:47.424Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
I/jxcore-log( 6633): 
,I/jxcore-log( 6633): 2015-12-18T17:59:47.429Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 6633): 
,I/jxcore-log( 6633): 2015-12-18T17:59:47.489Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 6633): 
,W/bt-btif ( 2530): invalid rfc slot id: 15
,W/io.jxcore.node.StreamCopyingThread( 6633): Either failed to read from the output stream or write to the input stream (thread ID: 839, thread name: Receiver): bt socket closed, read return: -1
E/io.jxcore.node.OutgoingSocketThread( 6633): The receiving thread failed with error "Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1", this is likely due to peer having disconnected
W/io.jxcore.node.ConnectionHelper( 6633): onDisconnected: Incoming connection, peer [34:FC:EF:11:AE:67 LGE-Nexus 5_PT5924] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
I/io.jxcore.node.ConnectionHelper( 6633): closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 837
D/io.jxcore.node.OutgoingSocketThread( 6633): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 6633): doStop: Thread ID: 839
D/io.jxcore.node.OutgoingSocketThread( 6633): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 6633): doStop: Thread ID: 838
D/io.jxcore.node.OutgoingSocketThread( 6633): closeLocalSocketAndStreams: Closing...
D/io.jxcore.node.OutgoingSocketThread( 6633): closeLocalSocketAndStreams: Closing the local input stream...
D/io.jxcore.node.OutgoingSocketThread( 6633): closeLocalSocketAndStreams: Closing the local output stream...
D/io.jxcore.node.OutgoingSocketThread( 6633): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.OutgoingSocketThread( 6633): closeBluetoothSocketAndStreams
D/io.jxcore.node.ConnectionHelper( 6633): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
D/io.jxcore.node.StreamCopyingThread( 6633): Exiting thread (ID: 839, name: Receiver)
,W/io.jxcore.node.StreamCopyingThread( 6633): Either failed to read from the output stream or write to the input stream (thread ID: 838, thread name: Sender): Socket closed
E/io.jxcore.node.OutgoingSocketThread( 6633): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 6633): onDisconnected: Incoming connection, peer [34:FC:EF:11:AE:67 LGE-Nexus 5_PT5924] disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
D/io.jxcore.node.ConnectionHelper( 6633): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
D/io.jxcore.node.StreamCopyingThread( 6633): Exiting thread (ID: 838, name: Sender)
I/jxcore-log( 6633): 2015-12-18T17:59:47.567Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 6633): 
I/jxcore-log( 6633): 2015-12-18T17:59:47.584Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 6633): 
I/jxcore-log( 6633): 2015-12-18T17:59:47.584Z SendDataConnector.js: got all data for this round
I/jxcore-log( 6633): 
I/jxcore-log( 6633): oneRoundDownNow
I/jxcore-log( 6633): 
I/jxcore-log( 6633): 2015-12-18T17:59:47.585Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 6633): 
I/jxcore-log( 6633): 2015-12-18T17:59:47.585Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 6633): 
D/io.jxcore.node.ConnectionHelper( 6633): disconnectOutgoingConnection: Trying to close connection to peer with ID 34:FC:EF:11:AE:67
I/io.jxcore.node.ConnectionHelper( 6633): closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 34:FC:EF:11:AE:67
I/io.jxcore.node.OutgoingSocketThread( 6633): close
D/io.jxcore.node.OutgoingSocketThread( 6633): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 6633): doStop: Thread ID: 843
D/io.jxcore.node.OutgoingSocketThread( 6633): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 6633): doStop: Thread ID: 842
D/io.jxcore.node.OutgoingSocketThread( 6633): closeLocalSocketAndStreams: Closing...
D/io.jxcore.node.OutgoingSocketThread( 6633): closeLocalSocketAndStreams: Closing the local input stream...
,W/io.jxcore.node.StreamCopyingThread( 6633): Either failed to read from the output stream or write to the input stream (thread ID: 842, thread name: Sender): Socket closed
E/io.jxcore.node.OutgoingSocketThread( 6633): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 6633): onDisconnected: Outgoing connection, peer [34:FC:EF:11:AE:67 LGE-Nexus 5_PT5924] disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
D/io.jxcore.node.OutgoingSocketThread( 6633): closeLocalSocketAndStreams: Closing the local output stream...
D/io.jxcore.node.OutgoingSocketThread( 6633): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.OutgoingSocketThread( 6633): closeBluetoothSocketAndStreams
W/io.jxcore.node.StreamCopyingThread( 6633): Either failed to read from the output stream or write to the input stream (thread ID: 843, thread name: Receiver): bt socket closed, read return: -1
E/io.jxcore.node.OutgoingSocketThread( 6633): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
W/io.jxcore.node.ConnectionHelper( 6633): onDisconnected: Outgoing connection, peer [34:FC:EF:11:AE:67 LGE-Nexus 5_PT5924] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
D/io.jxcore.node.ConnectionHelper( 6633): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
I/io.jxcore.node.ConnectionHelper( 6633): disconnectOutgoingConnection: Successfully disconnected (peer ID: 34:FC:EF:11:AE:67
E/io.jxcore.node.ConnectionHelper( 6633): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 34:FC:EF:11:AE:67
D/io.jxcore.node.ConnectionHelper( 6633): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
D/io.jxcore.node.StreamCopyingThread( 6633): Exiting thread (ID: 842, name: Sender)
E/io.jxcore.node.ConnectionHelper( 6633): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 34:FC:EF:11:AE:67
D/io.jxcore.node.ConnectionHelper( 6633): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
D/io.jxcore.node.StreamCopyingThread( 6633): Exiting thread (ID: 843, name: Receiver)
I/jxcore-log( 6633): 2015-12-18T17:59:47.610Z SendDataConnector.js: Mobile.Disconnect() callback with peer 34:FC:EF:11:AE:67
I/jxcore-log( 6633): 
I/jxcore-log( 6633): ---- round done--------
I/jxcore-log( 6633): 
I/jxcore-log( 6633): startWithNextDevice
I/jxcore-log( 6633): 
W/bt-btif ( 2530): bta_jv_rfc_port_to_cb(port_handle:0x15):jv handle:0x0 not FOUND
,D/btif_config_util( 2530): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2530): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2530): onReceive
,I/BTConnectionReceiver( 8520): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=34:FC:EF:11:AE:67, alias=null, name=Nexus 5, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 8520): Bluetooth Device Name: Nexus 5
,D/MDMCTBK (  291): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP a2:39:
,D/MDMCTBK (  291): Event received = P2P-SERV-DISC-RESP a2:39:
,D/WifiP2pService(  883): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:a2:39:f7:70:12:80 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT8213","ra":"F8:95:C7:87:85:54"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  883): P2pEnabledState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:a2:39:f7:70:12:80 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT8213","ra":"F8:95:C7:87:85:54"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  883): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6633): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT8213","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6633): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:85:54 LGE-LG-D722_PT8213]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6633): onServiceDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT8213]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6633): onPeerDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT8213]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6633): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT8213], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6633): modifyListOfDiscoveredPeers: Adding new peer: [F8:95:C7:87:85:54 LGE-LG-D722_PT8213]
,I/io.jxcore.node.ConnectionHelper( 6633): onPeerDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT8213], Bluetooth address: F8:95:C7:87:85:54, device name: G3s-1, device address: a2:39:f7:70:12:80
D/io.jxcore.node.ConnectionHelper( 6633): notifyPeerAvailability: Peer [F8:95:C7:87:85:54 LGE-LG-D722_PT8213] is available
I/jxcore-log( 6633): peerAvailabilityChanged [{"peerIdentifier":"F8:95:C7:87:85:54","peerName":"LGE-LG-D722_PT8213","peerAvailable":true}]
I/jxcore-log( 6633): 
I/jxcore-log( 6633): Found peer : LGE-LG-D722_PT8213, Available: true
I/jxcore-log( 6633): 
I/jxcore-log( 6633): startWithNextDevice
I/jxcore-log( 6633): 
I/jxcore-log( 6633): device[8]: F8:95:C7:87:85:54
I/jxcore-log( 6633): 
I/jxcore-log( 6633): 2015-12-18T17:59:51.739Z SendDataConnector.js: Start called with peer F8:95:C7:87:85:54
I/jxcore-log( 6633): 
,I/jxcore-log( 6633): 2015-12-18T17:59:51.740Z SendDataConnector.js: doConnect called with peer F8:95:C7:87:85:54
I/jxcore-log( 6633): 
I/jxcore-log( 6633): 2015-12-18T17:59:51.740Z SendDataConnector.js: do connect now
I/jxcore-log( 6633): 
I/io.jxcore.node.ConnectionHelper( 6633): connect: Trying to connect to peer with ID F8:95:C7:87:85:54
D/io.jxcore.node.ConnectionHelper( 6633): hasConnection: No connection with peer with ID F8:95:C7:87:85:54
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6633): connect: [F8:95:C7:87:85:54 LGE-LG-D722_PT8213]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6633): connect: Trying to start connecting to null in address F8:95:C7:87:85:54
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6633): setInsecureRfcommSocketPort: Using port -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6633): setMaxNumberOfRetries: 0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6633): onConnecting: null F8:95:C7:87:85:54
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6633): connect: Started connecting to null in address F8:95:C7:87:85:54
I/io.jxcore.node.ConnectionHelper( 6633): connect: Connection process successfully started (peer ID: F8:95:C7:87:85:54)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6633): Trying to connect to peer with address F8:95:C7:87:85:54 (thread ID: 844)
W/BluetoothAdapter( 6633): getBluetoothService() called with no BluetoothManagerCallback
D/BTIF_SOCK( 2530): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:31000 mC
,W/bt-btif ( 2530): info:x10
D/        ( 2530): remote version info [f8:95:c7:87:85:54]: 6, f, 410d
E/BluetoothRemoteDevices( 2530): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 2530): process_service_search_attr_rsp
,I/wpa_supplicant( 1442): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  291): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  291): Event received = CTRL-EVENT-SCAN-STARTED 
,I/BluetoothBondStateMachine( 2530): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:85:54 newState: 1
,E/bt-btif ( 2530): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2530): Bond State Change Intent:F8:95:C7:87:85:54 OldState: 10 NewState: 11
,I/BluetoothBondStateMachine( 2530): Entering PendingCommandState State
,D/TCMD    (  474): NL - Read 56 bytes from update socket.
,D/TCMD    (  474): NL - message type is RTM_NEWLINK
D/TCMD    (  474): Listening for incoming client connection request
,D/MDMCTBK (  291): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP 7e:f9:
,D/MDMCTBK (  291): Event received = P2P-SERV-DISC-RESP 7e:f9:
,D/WifiP2pService(  883): InactiveState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:7e:f9:0e:37:96:ac version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT1532","ra":"7C:F9:0E:37:96:AB"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  883): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:7e:f9:0e:37:96:ac version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT1532","ra":"7C:F9:0E:37:96:AB"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  883): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6633): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT1532","ra":"7C:F9:0E:37:96:AB"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6633): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1532]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6633): onServiceDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1532]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6633): onPeerDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1532]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6633): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1532], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6633): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1532]
I/io.jxcore.node.ConnectionHelper( 6633): onPeerDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1532], Bluetooth address: 7C:F9:0E:37:96:AB, device name: , device address: 7e:f9:0e:37:96:ac
W/io.jxcore.node.ConnectionHelper( 6633): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1532] already in the list, will not add again
,D/MDMCTBK (  291): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-REQ 2412 ee
,D/MDMCTBK (  291): Event received = P2P-SERV-DISC-REQ 2412 ee
,D/MDMCTBK (  291): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-REQ 2412 ee
,D/MDMCTBK (  291): Event received = P2P-SERV-DISC-REQ 2412 ee
,D/MDMCTBK (  291): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-REQ 2412 ee
D/MDMCTBK (  291): Event received = P2P-SERV-DISC-REQ 2412 ee
,I/BluetoothBondStateMachine( 2530): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:85:54 newState: 0
,D/BluetoothAdapterProperties( 2530): Failed to remove device: F8:95:C7:87:85:54
,I/BluetoothBondStateMachine( 2530): Bond State Change Intent:F8:95:C7:87:85:54 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2530): StableState(): Entering Off State
,D/BluetoothMetrics( 2530): btclass5a020c
,D/Checkin ( 2530): publish the event [tag = MOT_BT event name = PAIRING]
,W/bt-btif ( 2530): new conn_srvc id:26, app_id:1
,W/bt-btif ( 2530): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2530): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6633): onSocketConnected: [F8:95:C7:87:85:54 LGE-LG-D722_PT8213]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6633): Socket connection succeeded (using system decided port), total number of attempts: 1 (thread ID: 844)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6633): onBytesWritten: 80 bytes successfully written (thread ID: 845)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6633): Outgoing connection initialized (*handshake* thread ID: 845)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6633): Exiting thread (thread ID: 844)
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 6633): Entering thread (ID: 845)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6633): onBytesRead: Read 77 bytes successfully (thread ID: 845)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6633): Handshake succeeded with [F8:95:C7:87:85:54 LGE-LG-D722_PT8213]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6633): onHandshakeSucceeded: [F8:95:C7:87:85:54 LGE-LG-D722_PT8213]
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6633): onConnected: [F8:95:C7:87:85:54 LGE-LG-D722_PT8213]
I/io.jxcore.node.ConnectionHelper( 6633): onConnected: Outgoing connection to peer [F8:95:C7:87:85:54 LGE-LG-D722_PT8213]
D/io.jxcore.node.ConnectionHelper( 6633): hasConnection: No connection with peer with ID F8:95:C7:87:85:54
W/io.jxcore.node.ConnectionHelper( 6633): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:85:54 LGE-LG-D722_PT8213] already in the list, will not add again
,I/io.jxcore.node.ConnectionHelper( 6633): onConnected: Outgoing socket thread, for peer [F8:95:C7:87:85:54 LGE-LG-D722_PT8213], created successfully
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6633): setInsecureRfcommSocketPort: Will use port -1 when trying to connect
D/io.jxcore.node.ConnectionHelper( 6633): onConnected: The total number of connections is now 1
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 6633): Exiting thread (ID: 845)
,D/io.jxcore.node.OutgoingSocketThread( 6633): Entering thread (ID: 846)
D/io.jxcore.node.OutgoingSocketThread( 6633): Server socket local port: 51551
I/io.jxcore.node.OutgoingSocketThread( 6633): Now accepting connections...
,W/bt-btif ( 2530): new conn_srvc id:26, app_id:255
W/bt-btif ( 2530): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2530): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 2530): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6633): Incoming connection accepted
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6633): Incoming connection initialized (thread ID: 847)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6633): Waiting for incoming connections...
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 6633): Entering thread (ID: 847)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6633): onBytesRead: Read 77 bytes successfully (thread ID: 847)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6633): Got valid identity from [F8:95:C7:87:85:54 LGE-LG-D722_PT8213]
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6633): onBytesWritten: 80 bytes successfully written (thread ID: 847)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6633): removeThreadFromList: Removing thread with ID 847
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6633): Handshake thread disposed (thread ID: 847)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6633): onIncomingConnectionConnected: [F8:95:C7:87:85:54 LGE-LG-D722_PT8213]
D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 6633): Exiting thread (ID: 847)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6633): onConnected: [F8:95:C7:87:85:54 LGE-LG-D722_PT8213]
I/io.jxcore.node.ConnectionHelper( 6633): onConnected: Incoming connection to peer [F8:95:C7:87:85:54 LGE-LG-D722_PT8213]
D/io.jxcore.node.ConnectionHelper( 6633): hasConnection: We have an outgoing connection with peer with ID F8:95:C7:87:85:54
,W/io.jxcore.node.ConnectionHelper( 6633): onConnected: Already connected with peer [F8:95:C7:87:85:54 LGE-LG-D722_PT8213], continuing anyway...
W/io.jxcore.node.ConnectionHelper( 6633): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:85:54 LGE-LG-D722_PT8213] already in the list, will not add again
,I/io.jxcore.node.ConnectionHelper( 6633): onConnected: Incoming socket thread, for peer [F8:95:C7:87:85:54 LGE-LG-D722_PT8213], created successfully
D/io.jxcore.node.ConnectionHelper( 6633): onConnected: The total number of connections is now 2
,D/io.jxcore.node.IncomingSocketThread( 6633): Entering thread (ID: 848)
,I/io.jxcore.node.IncomingSocketThread( 6633): Local host address: localhost/127.0.0.1, port: 57867
,I/jxcore-log( 6633): 2015-12-18T17:59:53.450Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 6633): 
,D/io.jxcore.node.IncomingSocketThread( 6633): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 6633): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 6633): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.IncomingSocketThread( 6633): startStreamCopyingThreads: OK
D/io.jxcore.node.IncomingSocketThread( 6633): Exiting thread (ID: 848)
,D/io.jxcore.node.StreamCopyingThread( 6633): Entering thread (ID: 849, name: Sender)
,D/io.jxcore.node.StreamCopyingThread( 6633): Entering thread (ID: 850, name: Receiver)
,I/io.jxcore.node.ConnectionHelper( 6633): onListeningForIncomingConnections: Outgoing connection is using port 51551 (peer ID: F8:95:C7:87:85:54)
,I/jxcore-log( 6633): 2015-12-18T17:59:53.645Z SendDataConnector.js: CLIENT connected to 51551, error: null
I/jxcore-log( 6633): 
I/jxcore-log( 6633): 2015-12-18T17:59:53.645Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 6633): 
,I/io.jxcore.node.IncomingSocketThread( 6633): Incoming data from address: /127.0.0.1, port: 51551
,D/io.jxcore.node.IncomingSocketThread( 6633): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 6633): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 6633): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.IncomingSocketThread( 6633): startStreamCopyingThreads: OK
D/io.jxcore.node.IncomingSocketThread( 6633): Exiting thread (ID: 846)
,D/io.jxcore.node.StreamCopyingThread( 6633): Entering thread (ID: 852, name: Receiver)
,D/io.jxcore.node.StreamCopyingThread( 6633): Entering thread (ID: 851, name: Sender)
,I/jxcore-log( 6633): 2015-12-18T17:59:53.666Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 6633): 
,I/wpa_supplicant( 1442): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  291): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  291): Event received = CTRL-EVENT-SCAN-STARTED 
,D/TCMD    (  474): NL - Read 56 bytes from update socket.
D/TCMD    (  474): NL - message type is RTM_NEWLINK
D/TCMD    (  474): Listening for incoming client connection request
,D/MDMCTBK (  291): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 4 
,D/MDMCTBK (  291): Event received = CTRL-EVENT-BSS-REMOVED 4 
,I/jxcore-log( 6633): 2015-12-18T17:59:54.445Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 6633): 
,I/jxcore-log( 6633): 2015-12-18T17:59:54.451Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 6633): 
,I/jxcore-log( 6633): 2015-12-18T17:59:54.457Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 6633): 
,I/jxcore-log( 6633): 2015-12-18T17:59:54.463Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 6633): 
,I/jxcore-log( 6633): 2015-12-18T17:59:54.468Z SendDataTCPServer.js: TCP/IP server has received 9900 bytes of data
I/jxcore-log( 6633): 
,I/jxcore-log( 6633): 2015-12-18T17:59:54.473Z SendDataTCPServer.js: TCP/IP server has received 11880 bytes of data
I/jxcore-log( 6633): 
,I/jxcore-log( 6633): 2015-12-18T17:59:54.480Z SendDataTCPServer.js: TCP/IP server has received 13860 bytes of data
I/jxcore-log( 6633): 
,I/jxcore-log( 6633): 2015-12-18T17:59:54.515Z SendDataTCPServer.js: TCP/IP server has received 19800 bytes of data
I/jxcore-log( 6633): 
,I/jxcore-log( 6633): 2015-12-18T17:59:54.525Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 6633): 
,I/jxcore-log( 6633): 2015-12-18T17:59:54.572Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 6633): 
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6633): checkListForExpiredPeers: Peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT3826] expired
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6633): checkListForExpiredPeers: Peer [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT6460] expired
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6633): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT3826], add/update: false
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6633): modifyListOfDiscoveredPeers: Removed [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT3826]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6633): modifyListOfDiscoveredPeers: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT6460], add/update: false
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6633): modifyListOfDiscoveredPeers: Removed [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT6460]
I/io.jxcore.node.ConnectionHelper( 6633): onPeerLost: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT3826]
D/io.jxcore.node.ConnectionHelper( 6633): hasConnection: No connection with peer with ID 7C:F9:0E:51:18:22
D/io.jxcore.node.ConnectionHelper( 6633): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT3826] removed
D/io.jxcore.node.ConnectionHelper( 6633): notifyPeerAvailability: Peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT3826] not available
,I/jxcore-log( 6633): peerAvailabilityChanged [{"peerIdentifier":"7C:F9:0E:51:18:22","peerName":"samsung-SM-A500FU_PT3826","peerAvailable":false}]
I/jxcore-log( 6633): 
,I/io.jxcore.node.ConnectionHelper( 6633): onPeerLost: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT6460]
D/io.jxcore.node.ConnectionHelper( 6633): hasConnection: No connection with peer with ID E0:DB:10:14:E2:C0
D/io.jxcore.node.ConnectionHelper( 6633): modifyListOfDiscoveredPeers: Peer [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT6460] removed
D/io.jxcore.node.ConnectionHelper( 6633): notifyPeerAvailability: Peer [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT6460] not available
I/jxcore-log( 6633): peerAvailabilityChanged [{"peerIdentifier":"E0:DB:10:14:E2:C0","peerName":"samsung-SM-N910C_PT6460","peerAvailable":false}]
I/jxcore-log( 6633): 
,I/jxcore-log( 6633): 2015-12-18T17:59:54.619Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 6633): 
,I/jxcore-log( 6633): 2015-12-18T17:59:54.661Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 6633): 
,I/jxcore-log( 6633): 2015-12-18T17:59:54.719Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 6633): 
,I/jxcore-log( 6633): 2015-12-18T17:59:54.785Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 6633): 
,I/jxcore-log( 6633): 2015-12-18T17:59:54.795Z SendDataTCPServer.js: TCP/IP server has received 21780 bytes of data
I/jxcore-log( 6633): 
,I/jxcore-log( 6633): 2015-12-18T17:59:54.801Z SendDataTCPServer.js: TCP/IP server has received 23760 bytes of data
I/jxcore-log( 6633): 
,I/jxcore-log( 6633): 2015-12-18T17:59:54.834Z SendDataTCPServer.js: TCP/IP server has received 31680 bytes of data
I/jxcore-log( 6633): 
,I/jxcore-log( 6633): 2015-12-18T17:59:54.842Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 6633): 
,I/jxcore-log( 6633): 2015-12-18T17:59:54.942Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 6633): 
,I/wpa_supplicant( 1442): p2p0: CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  291): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  291): Event received = CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 6633): 2015-12-18T17:59:55.035Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 6633): 
,I/jxcore-log( 6633): 2015-12-18T17:59:55.036Z SendDataConnector.js: got all data for this round
I/jxcore-log( 6633): 
I/jxcore-log( 6633): oneRoundDownNow
I/jxcore-log( 6633): 
,I/jxcore-log( 6633): 2015-12-18T17:59:55.040Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 6633): 
,I/jxcore-log( 6633): 2015-12-18T17:59:55.041Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 6633): 
D/io.jxcore.node.ConnectionHelper( 6633): disconnectOutgoingConnection: Trying to close connection to peer with ID F8:95:C7:87:85:54
I/io.jxcore.node.ConnectionHelper( 6633): closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: F8:95:C7:87:85:54
I/io.jxcore.node.IncomingSocketThread( 6633): close
D/io.jxcore.node.IncomingSocketThread( 6633): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 6633): doStop: Thread ID: 852
D/io.jxcore.node.IncomingSocketThread( 6633): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 6633): doStop: Thread ID: 851
D/io.jxcore.node.IncomingSocketThread( 6633): closeLocalSocketAndStreams: Closing...
D/io.jxcore.node.IncomingSocketThread( 6633): closeLocalSocketAndStreams: Closing the local input stream...
,W/io.jxcore.node.StreamCopyingThread( 6633): Either failed to read from the output stream or write to the input stream (thread ID: 851, thread name: Sender): Socket closed
E/io.jxcore.node.IncomingSocketThread( 6633): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
,W/io.jxcore.node.ConnectionHelper( 6633): onDisconnected: Outgoing connection, peer [F8:95:C7:87:85:54 LGE-LG-D722_PT8213] disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
,D/io.jxcore.node.IncomingSocketThread( 6633): closeLocalSocketAndStreams: Closing the local output stream...
D/io.jxcore.node.IncomingSocketThread( 6633): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.IncomingSocketThread( 6633): closeBluetoothSocketAndStreams
,W/io.jxcore.node.StreamCopyingThread( 6633): Either failed to read from the output stream or write to the input stream (thread ID: 852, thread name: Receiver): bt socket closed, read return: -1
E/io.jxcore.node.IncomingSocketThread( 6633): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
W/io.jxcore.node.ConnectionHelper( 6633): onDisconnected: Outgoing connection, peer [F8:95:C7:87:85:54 LGE-LG-D722_PT8213] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
,D/io.jxcore.node.ConnectionHelper( 6633): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,I/io.jxcore.node.ConnectionHelper( 6633): disconnectOutgoingConnection: Successfully disconnected (peer ID: F8:95:C7:87:85:54
,E/io.jxcore.node.ConnectionHelper( 6633): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID F8:95:C7:87:85:54
D/io.jxcore.node.ConnectionHelper( 6633): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
D/io.jxcore.node.StreamCopyingThread( 6633): Exiting thread (ID: 851, name: Sender)
,E/io.jxcore.node.ConnectionHelper( 6633): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID F8:95:C7:87:85:54
D/io.jxcore.node.ConnectionHelper( 6633): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
D/io.jxcore.node.StreamCopyingThread( 6633): Exiting thread (ID: 852, name: Receiver)
,I/jxcore-log( 6633): 2015-12-18T17:59:55.067Z SendDataConnector.js: Mobile.Disconnect() callback with peer F8:95:C7:87:85:54
I/jxcore-log( 6633): 
I/jxcore-log( 6633): ---- round done--------
I/jxcore-log( 6633): 
I/jxcore-log( 6633): startWithNextDevice
I/jxcore-log( 6633): 
,I/jxcore-log( 6633): 2015-12-18T17:59:55.071Z SendDataTCPServer.js: TCP/IP server has received 32768 bytes of data
I/jxcore-log( 6633): 
,I/jxcore-log( 6633): 2015-12-18T17:59:55.084Z SendDataTCPServer.js: TCP/IP server has received 42668 bytes of data
I/jxcore-log( 6633): 
,I/jxcore-log( 6633): 2015-12-18T17:59:55.089Z SendDataTCPServer.js: TCP/IP server has received 44648 bytes of data
I/jxcore-log( 6633): 
,I/jxcore-log( 6633): 2015-12-18T17:59:55.124Z SendDataTCPServer.js: TCP/IP server has received 50588 bytes of data
I/jxcore-log( 6633): 
,W/bt-btif ( 2530): bta_jv_rfc_port_to_cb(port_handle:0x16):jv handle:0x0 not FOUND
,I/jxcore-log( 6633): 2015-12-18T17:59:55.147Z SendDataTCPServer.js: TCP/IP server has received 52568 bytes of data
I/jxcore-log( 6633): 
,D/MDMCTBK (  291): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 5 c0
,D/MDMCTBK (  291): Event received = CTRL-EVENT-BSS-ADDED 5 c0
,D/TCMD    (  474): NL - Read 56 bytes from update socket.
,D/TCMD    (  474): NL - message type is RTM_NEWLINK
D/TCMD    (  474): Listening for incoming client connection request
,I/jxcore-log( 6633): 2015-12-18T17:59:55.184Z SendDataTCPServer.js: TCP/IP server has received 60488 bytes of data
I/jxcore-log( 6633): 
,I/jxcore-log( 6633): 2015-12-18T17:59:55.205Z SendDataTCPServer.js: TCP/IP server has received 62468 bytes of data
I/jxcore-log( 6633): 
,I/jxcore-log( 6633): 2015-12-18T17:59:55.244Z SendDataTCPServer.js: TCP/IP server has received 72368 bytes of data
I/jxcore-log( 6633): 
,I/jxcore-log( 6633): 2015-12-18T17:59:55.258Z SendDataTCPServer.js: TCP/IP server has received 74348 bytes of data
I/jxcore-log( 6633): 
,I/jxcore-log( 6633): 2015-12-18T17:59:55.294Z SendDataTCPServer.js: TCP/IP server has received 82268 bytes of data
I/jxcore-log( 6633): 
,D/MDMCTBK (  291): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-REQ 2412 7e
,D/MDMCTBK (  291): Event received = P2P-SERV-DISC-REQ 2412 7e
,I/jxcore-log( 6633): 2015-12-18T17:59:55.421Z SendDataTCPServer.js: TCP/IP server has received 84248 bytes of data
I/jxcore-log( 6633): 
,I/jxcore-log( 6633): 2015-12-18T17:59:55.455Z SendDataTCPServer.js: TCP/IP server has received 96128 bytes of data
I/jxcore-log( 6633): 
,I/jxcore-log( 6633): 2015-12-18T17:59:55.462Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
I/jxcore-log( 6633): 
,W/bt-btif ( 2530): invalid rfc slot id: 17
,W/io.jxcore.node.StreamCopyingThread( 6633): Either failed to read from the output stream or write to the input stream (thread ID: 850, thread name: Receiver): bt socket closed, read return: -1
,E/io.jxcore.node.IncomingSocketThread( 6633): The receiving thread failed with error "Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1", this is likely due to peer having disconnected
W/io.jxcore.node.ConnectionHelper( 6633): onDisconnected: Incoming connection, peer [F8:95:C7:87:85:54 LGE-LG-D722_PT8213] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
I/io.jxcore.node.ConnectionHelper( 6633): closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 848
D/io.jxcore.node.IncomingSocketThread( 6633): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 6633): doStop: Thread ID: 850
D/io.jxcore.node.IncomingSocketThread( 6633): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 6633): doStop: Thread ID: 849
D/io.jxcore.node.IncomingSocketThread( 6633): closeLocalSocketAndStreams: Closing...
D/io.jxcore.node.IncomingSocketThread( 6633): closeLocalSocketAndStreams: Closing the local input stream...
D/io.jxcore.node.IncomingSocketThread( 6633): closeLocalSocketAndStreams: Closing the local output stream...
D/io.jxcore.node.IncomingSocketThread( 6633): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.IncomingSocketThread( 6633): closeBluetoothSocketAndStreams
D/io.jxcore.node.ConnectionHelper( 6633): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
D/io.jxcore.node.StreamCopyingThread( 6633): Exiting thread (ID: 850, name: Receiver)
,W/io.jxcore.node.StreamCopyingThread( 6633): Either failed to read from the output stream or write to the input stream (thread ID: 849, thread name: Sender): Socket closed
,E/io.jxcore.node.IncomingSocketThread( 6633): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 6633): onDisconnected: Incoming connection, peer [F8:95:C7:87:85:54 LGE-LG-D722_PT8213] disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
D/io.jxcore.node.ConnectionHelper( 6633): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
D/io.jxcore.node.StreamCopyingThread( 6633): Exiting thread (ID: 849, name: Sender)
,I/jxcore-log( 6633): 2015-12-18T17:59:55.584Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 6633): 
,I/wpa_supplicant( 1442): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  291): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  291): Event received = CTRL-EVENT-SCAN-STARTED 
,D/TCMD    (  474): NL - Read 56 bytes from update socket.
,D/TCMD    (  474): NL - message type is RTM_NEWLINK
,D/TCMD    (  474): Listening for incoming client connection request
,I/wpa_supplicant( 1442): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  291): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  291): Event received = CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1442): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 level=-49
,D/MDMCTBK (  291): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2
D/MDMCTBK (  291): Event received = P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2
,D/WifiP2pService(  883): InactiveState{ when=0 what=147477 obj=Device: A5-1
D/WifiP2pService(  883):  deviceAddress: 7e:f9:0e:37:96:ac
D/WifiP2pService(  883):  primary type: 10-0050F204-5
D/WifiP2pService(  883):  secondary type: null
D/WifiP2pService(  883):  wps: 392
D/WifiP2pService(  883):  grpcapab: 0
D/WifiP2pService(  883):  devcapab: 37
D/WifiP2pService(  883):  status: 3
D/WifiP2pService(  883):  wfdInfo: null
D/WifiP2pService(  883):  level: -49 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  883): P2pEnabledState{ when=-1ms what=147477 obj=Device: A5-1
D/WifiP2pService(  883):  deviceAddress: 7e:f9:0e:37:96:ac
D/WifiP2pService(  883):  primary type: 10-0050F204-5
D/WifiP2pService(  883):  secondary type: null
D/WifiP2pService(  883):  wps: 392
D/WifiP2pService(  883):  grpcapab: 0
D/WifiP2pService(  883):  devcapab: 37
D/WifiP2pService(  883):  status: 3
D/WifiP2pService(  883):  wfdInfo: null
D/WifiP2pService(  883):  level: -49 target=com.android.internal.util.StateMachine$SmHandler }
,D/TCMD    (  474): NL - Read 56 bytes from update socket.
,D/TCMD    (  474): NL - message type is RTM_NEWLINK
D/TCMD    (  474): Listening for incoming client connection request
,D/WifiP2pService(  883): InactiveState{ when=0 what=139283 arg2=29 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  883): P2pEnabledState{ when=0 what=139283 arg2=29 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  883): DefaultState{ when=0 what=139283 arg2=29 target=com.android.internal.util.StateMachine$SmHandler }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6633): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6633): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6633): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1532], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6633): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1532]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6633): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6633): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT8213], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6633): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT8213]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6633): onP2pDeviceListChanged: Peer 3: Android_8ae2 52:55:27:f0:fd:0b
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6633): restart: Restarting...
,D/WifiP2pService(  883): InactiveState{ when=0 what=139307 arg2=30 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  883): P2pEnabledState{ when=0 what=139307 arg2=30 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  883): P2pEnabledState clear service request
,D/WifiP2pService(  883): InactiveState{ when=0 what=139301 arg2=31 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  883): P2pEnabledState{ when=0 what=139301 arg2=31 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  883): P2pEnabledState add service request
,D/WifiP2pManager( 6633): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6633): Service request added successfully
,D/MDMCTBK (  291): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-REQ 2412 a2
,D/MDMCTBK (  291): Event received = P2P-SERV-DISC-REQ 2412 a2
,D/btif_config_util( 2530): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/wpa_supplicant( 1442): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  291): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  291): Event received = CTRL-EVENT-SCAN-STARTED 
,D/WifiP2pService(  883): InactiveState{ when=0 what=139310 arg2=32 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  883): P2pEnabledState{ when=0 what=139310 arg2=32 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  883): P2pEnabledState discover services
,I/wpa_supplicant( 1442): p2p0: P2P: Reject scan trigger since one is already pending
,D/MDMCTBK (  291): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P: Reject scan trigger 
D/MDMCTBK (  291): Event received = P2P: Reject scan trigger 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6633): Service discovery started successfully
,I/MDMCTBK (  291): NetlinkHandler, power_supply subsys
,I/MDMCTBK (  291): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  291): checkDefaultInst, current pid is = 291
I/MDMCTBK (  291): checkDefaultInst, pid match
,I/MDMCTBK (  291): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  291): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  291): MdmCutbackHndler,Could not open ''
,D/BatteryService(  883): uevent={POWER_SUPPLY_TEMP=278, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311147, SEQNUM=4595, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=503, POWER_SUPPLY_CHARGE_COUNTER=-737, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2530): Disconnected process message: 10, size: 0
,D/TCMD    (  474): NL - Read 56 bytes from update socket.
,D/TCMD    (  474): NL - message type is RTM_NEWLINK
,D/TCMD    (  474): Listening for incoming client connection request
,E/bt-btm  ( 2530): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2530): onReceive
,I/BTConnectionReceiver( 8520): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:85:54, alias=null, name=G3s-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 8520): Bluetooth Device Name: G3s-1
,D/MDMCTBK (  291): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP ee:1f:
D/MDMCTBK (  291): Event received = P2P-SERV-DISC-RESP ee:1f:
,D/WifiP2pService(  883): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:ee:1f:72:63:11:86 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT8280","ra":"7C:F9:0E:34:8A:A0"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  883): P2pEnabledState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:ee:1f:72:63:11:86 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT8280","ra":"7C:F9:0E:34:8A:A0"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  883): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6633): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT8280","ra":"7C:F9:0E:34:8A:A0"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6633): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT8280]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6633): onServiceDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT8280]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6633): onPeerDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT8280]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6633): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT8280], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6633): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT8280]
I/io.jxcore.node.ConnectionHelper( 6633): onPeerDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT8280], Bluetooth address: 7C:F9:0E:34:8A:A0, device name: , device address: ee:1f:72:63:11:86
D/io.jxcore.node.ConnectionHelper( 6633): notifyPeerAvailability: Peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT8280] is available
I/jxcore-log( 6633): peerAvailabilityChanged [{"peerIdentifier":"7C:F9:0E:34:8A:A0","peerName":"samsung-SM-G900F_PT8280","peerAvailable":true}]
I/jxcore-log( 6633): 
I/jxcore-log( 6633): Found peer : samsung-SM-G900F_PT8280, Available: true
I/jxcore-log( 6633): 
I/jxcore-log( 6633): startWithNextDevice
I/jxcore-log( 6633): 
I/jxcore-log( 6633): device[9]: 7C:F9:0E:34:8A:A0
I/jxcore-log( 6633): 
I/jxcore-log( 6633): 2015-12-18T17:59:59.596Z SendDataConnector.js: Start called with peer 7C:F9:0E:34:8A:A0
I/jxcore-log( 6633): 
I/jxcore-log( 6633): 2015-12-18T17:59:59.596Z SendDataConnector.js: doConnect called with peer 7C:F9:0E:34:8A:A0
I/jxcore-log( 6633): 
I/jxcore-log( 6633): 2015-12-18T17:59:59.596Z SendDataConnector.js: do connect now
I/jxcore-log( 6633): 
I/io.jxcore.node.ConnectionHelper( 6633): connect: Trying to connect to peer with ID 7C:F9:0E:34:8A:A0
D/io.jxcore.node.ConnectionHelper( 6633): hasConnection: No connection with peer with ID 7C:F9:0E:34:8A:A0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6633): connect: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT8280]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6633): connect: Trying to start connecting to null in address 7C:F9:0E:34:8A:A0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6633): setInsecureRfcommSocketPort: Using port -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6633): setMaxNumberOfRetries: 0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6633): onConnecting: null 7C:F9:0E:34:8A:A0
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6633): connect: Started connecting to null in address 7C:F9:0E:34:8A:A0
I/io.jxcore.node.ConnectionHelper( 6633): connect: Connection process successfully started (peer ID: 7C:F9:0E:34:8A:A0)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6633): Trying to connect to peer with address 7C:F9:0E:34:8A:A0 (thread ID: 853)
W/BluetoothAdapter( 6633): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2530): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,D/MDMCTBK (  291): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP 52:55:
,D/MDMCTBK (  291): Event received = P2P-SERV-DISC-RESP 52:55:
,D/WifiP2pService(  883): InactiveState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:52:55:27:f0:fd:0b version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT5924","ra":"34:FC:EF:11:AE:67"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  883): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:52:55:27:f0:fd:0b version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT5924","ra":"34:FC:EF:11:AE:67"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  883): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6633): onDnsSdServiceAvailable: Identity: "{"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT5924","ra":"34:FC:EF:11:AE:67"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6633): onDnsSdServiceAvailable: Resolved peer properties: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT5924]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6633): onServiceDiscovered: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT5924]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6633): onPeerDiscovered: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT5924]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6633): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT5924], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6633): modifyListOfDiscoveredPeers: Adding new peer: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT5924]
I/io.jxcore.node.ConnectionHelper( 6633): onPeerDiscovered: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT5924], Bluetooth address: 34:FC:EF:11:AE:67, device name: Android_8ae2, device address: 52:55:27:f0:fd:0b
W/io.jxcore.node.ConnectionHelper( 6633): modifyListOfDiscoveredPeers: Peer [34:FC:EF:11:AE:67 LGE-Nexus 5_PT5924] already in the list, will not add again
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:31000 mC
,D/MDMCTBK (  291): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 5 
,D/MDMCTBK (  291): Event received = CTRL-EVENT-BSS-REMOVED 5 
,I/ActivityManager(  883): Waited long enough for: ServiceRecord{302d92c5 u0 com.motorola.context/.publisher.bluetoothdeterminer.BluetoothContextService}
,D/MDMCTBK (  291): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP a2:39:
,D/MDMCTBK (  291): Event received = P2P-SERV-DISC-RESP a2:39:
,D/WifiP2pService(  883): InactiveState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:a2:39:f7:70:12:80 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT8213","ra":"F8:95:C7:87:85:54"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  883): P2pEnabledState{ when=0 what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:a2:39:f7:70:12:80 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT8213","ra":"F8:95:C7:87:85:54"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  883): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6633): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT8213","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6633): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:85:54 LGE-LG-D722_PT8213]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6633): onServiceDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT8213]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6633): onPeerDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT8213]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6633): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT8213], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6633): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT8213]
I/io.jxcore.node.ConnectionHelper( 6633): onPeerDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT8213], Bluetooth address: F8:95:C7:87:85:54, device name: G3s-1, device address: a2:39:f7:70:12:80
W/io.jxcore.node.ConnectionHelper( 6633): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:85:54 LGE-LG-D722_PT8213] already in the list, will not add again
,I/wpa_supplicant( 1442): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  291): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  291): Event received = CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  291): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 6 c0
,D/MDMCTBK (  291): Event received = CTRL-EVENT-BSS-ADDED 6 c0
,D/TCMD    (  474): NL - Read 56 bytes from update socket.
,D/TCMD    (  474): NL - message type is RTM_NEWLINK
D/TCMD    (  474): Listening for incoming client connection request
,I/wpa_supplicant( 1442): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  291): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  291): Event received = CTRL-EVENT-SCAN-STARTED 
,D/TCMD    (  474): NL - Read 56 bytes from update socket.
,D/TCMD    (  474): NL - message type is RTM_NEWLINK
D/TCMD    (  474): Listening for incoming client connection request
,I/wpa_supplicant( 1442): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  291): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  291): Event received = CTRL-EVENT-SCAN-STARTED 
,D/TCMD    (  474): NL - Read 56 bytes from update socket.
,D/TCMD    (  474): NL - message type is RTM_NEWLINK
D/TCMD    (  474): Listening for incoming client connection request
,I/wpa_supplicant( 1442): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  291): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  291): Event received = CTRL-EVENT-SCAN-STARTED 
,D/TCMD    (  474): NL - Read 56 bytes from update socket.
,D/TCMD    (  474): NL - message type is RTM_NEWLINK
,D/TCMD    (  474): Listening for incoming client connection request
,D/MDMCTBK (  291): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-RESP 0a:ec:
,D/MDMCTBK (  291): Event received = P2P-SERV-DISC-RESP 0a:ec:
,D/WifiP2pService(  883): InactiveState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:0a:ec:a9:50:75:42 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT5572","ra":"08:EC:A9:50:75:41"}] target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  883): P2pEnabledState{ when=-1ms what=147494 obj=[serviceType:DnsSd(1) status:SUCCESS srcAddr:0a:ec:a9:50:75:42 version:01 dnsName:Cordovap2p._tcp.local. TxtRecord: InsName:{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT5572","ra":"08:EC:A9:50:75:41"}] target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  883): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6633): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT5572","ra":"08:EC:A9:50:75:41"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6633): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT5572]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6633): onServiceDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT5572]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6633): onPeerDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT5572]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6633): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT5572], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6633): modifyListOfDiscoveredPeers: Adding new peer: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT5572]
I/io.jxcore.node.ConnectionHelper( 6633): onPeerDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT5572], Bluetooth address: 08:EC:A9:50:75:41, device name: , device address: 0a:ec:a9:50:75:42
,D/io.jxcore.node.ConnectionHelper( 6633): notifyPeerAvailability: Peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT5572] is available
,I/jxcore-log( 6633): peerAvailabilityChanged [{"peerIdentifier":"08:EC:A9:50:75:41","peerName":"samsung-SM-A300FU_PT5572","peerAvailable":true}]
I/jxcore-log( 6633): 
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:31000 mC
,I/wpa_supplicant( 1442): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  291): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  291): Event received = CTRL-EVENT-SCAN-STARTED 
,D/TCMD    (  474): NL - Read 56 bytes from update socket.
,D/TCMD    (  474): NL - message type is RTM_NEWLINK
D/TCMD    (  474): Listening for incoming client connection request
,D/MDMCTBK (  291): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-REQ 2412 7e
,D/MDMCTBK (  291): Event received = P2P-SERV-DISC-REQ 2412 7e
,I/wpa_supplicant( 1442): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  291): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  291): Event received = CTRL-EVENT-SCAN-STARTED 
,D/TCMD    (  474): NL - Read 56 bytes from update socket.
,D/TCMD    (  474): NL - message type is RTM_NEWLINK
D/TCMD    (  474): Listening for incoming client connection request
,D/MDMCTBK (  291): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P-SERV-DISC-REQ 2412 a2
,D/MDMCTBK (  291): Event received = P2P-SERV-DISC-REQ 2412 a2
,D/MDMCTBK (  291): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 6 
,D/MDMCTBK (  291): Event received = CTRL-EVENT-BSS-REMOVED 6 
,I/wpa_supplicant( 1442): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/MDMCTBK (  291): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  291): Event received = CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6633): Connection timeout
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6633): onConnectionTimeout: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT8280]
I/jxcore-log( 6633): 2015-12-18T18:00:14.605Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT8280] timed out
I/jxcore-log( 6633): 
I/jxcore-log( 6633): 2015-12-18T18:00:14.605Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT8280] timed out
I/jxcore-log( 6633): 
I/jxcore-log( 6633): 2015-12-18T18:00:14.606Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 6633): 
,I/wpa_supplicant( 1442): P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 level=-31
,D/MDMCTBK (  291): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 7 c0
D/MDMCTBK (  291): Event received = CTRL-EVENT-BSS-ADDED 7 c0
D/MDMCTBK (  291): reply_len: 40 reply is = <3>P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2
D/MDMCTBK (  291): Event received = P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2
,D/WifiP2pService(  883): InactiveState{ when=0 what=147477 obj=Device: Note4-1
D/WifiP2pService(  883):  deviceAddress: 92:b6:86:43:73:1c
D/WifiP2pService(  883):  primary type: 10-0050F204-5
D/WifiP2pService(  883):  secondary type: null
D/WifiP2pService(  883):  wps: 392
D/WifiP2pService(  883):  grpcapab: 0
D/WifiP2pService(  883):  devcapab: 37
D/WifiP2pService(  883):  status: 3
D/WifiP2pService(  883):  wfdInfo: null
D/WifiP2pService(  883):  level: -31 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  883): P2pEnabledState{ when=0 what=147477 obj=Device: Note4-1
D/WifiP2pService(  883):  deviceAddress: 92:b6:86:43:73:1c
D/WifiP2pService(  883):  primary type: 10-0050F204-5
D/WifiP2pService(  883):  secondary type: null
D/WifiP2pService(  883):  wps: 392
D/WifiP2pService(  883):  grpcapab: 0
D/WifiP2pService(  883):  devcapab: 37
D/WifiP2pService(  883):  status: 3
D/WifiP2pService(  883):  wfdInfo: null
D/WifiP2pService(  883):  level: -31 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  883): InactiveState{ when=0 what=139283 arg2=33 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  883): P2pEnabledState{ when=0 what=139283 arg2=33 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  883): DefaultState{ when=0 what=139283 arg2=33 target=com.android.internal.util.StateMachine$SmHandler }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6633): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6633): onP2pDeviceListChanged: Peer 1: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6633): onP2pDeviceListChanged: Peer 2: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6633): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6633): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT8213], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6633): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT8213]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6633): onP2pDeviceListChanged: Peer 4: Android_8ae2 52:55:27:f0:fd:0b
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6633): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT5924], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6633): modifyListOfDiscoveredPeers: Updating the timestamp of peer [34:FC:EF:11:AE:67 LGE-Nexus 5_PT5924]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6633): restart: Restarting...
,D/WifiP2pService(  883): InactiveState{ when=0 what=139307 arg2=34 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  883): P2pEnabledState{ when=0 what=139307 arg2=34 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  883): P2pEnabledState clear service request
,D/TCMD    (  474): NL - Read 56 bytes from update socket.
D/TCMD    (  474): NL - message type is RTM_NEWLINK
D/TCMD    (  474): Listening for incoming client connection request
,D/WifiP2pService(  883): InactiveState{ when=-1ms what=139301 arg2=35 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  883): P2pEnabledState{ when=-1ms what=139301 arg2=35 obj=android.net.wifi.p2p.nsd.WifiP2pServiceRequest@58c4b5a6 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  883): P2pEnabledState add service request
,D/WifiP2pManager( 6633): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6633): Service request added successfully
,--------- beginning of crash
F/libc    ( 1442): Fatal signal 11 (SIGSEGV), code 1, fault addr 0xc in tid 1442 (wpa_supplicant)
,I/libc    ( 1442): Suppressing debuggerd output because prctl(PR_GET_DUMPABLE)==0
,E/QC-QMI  (  436): qmuxd: RX on fd=28 returned error=0 errno[2:No such file or directory]
,E/QC-QMI  (  436): qmi_ctl_rx_msg.c Can't find txn info for txn_id = 14
,E/QC-QMI  (  436): qmi_ctl_rx_msg.c Can't find txn info for txn_id = 15
,E/QC-QMI  (  436): qmi_ctl_rx_msg.c Can't find txn info for txn_id = 16
E/QC-QMI  (  436): qmi_ctl_rx_msg.c Can't find txn info for txn_id = 17
,D/WifiP2pService(  883): InactiveState{ when=-1ms what=139310 arg2=36 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  883): P2pEnabledState{ when=-1ms what=139310 arg2=36 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  883): P2pEnabledState discover services
E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6633): Failed to start the service discovery, got error code: 3
,I/MDMCTBK (  291): NetlinkHandler, power_supply subsys
,I/MDMCTBK (  291): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  291): checkDefaultInst, current pid is = 291
I/MDMCTBK (  291): checkDefaultInst, pid match
I/MDMCTBK (  291): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
,I/MDMCTBK (  291): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  291): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  291): NetlinkHandler, power_supply subsys
I/MDMCTBK (  291): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  291): checkDefaultInst, current pid is = 291
I/MDMCTBK (  291): checkDefaultInst, pid match
I/MDMCTBK (  291): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  291): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  291): MdmCutbackHndler,Could not open ''
,D/BatteryService(  883): uevent={POWER_SUPPLY_TEMP=278, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4310832, SEQNUM=4597, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-1001, POWER_SUPPLY_CHARGE_COUNTER=1, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2530): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2530): Disconnected process message: 10, size: 0
,I/jxcore-log( 6633): 2015-12-18T18:00:19.607Z SendDataConnector.js: re-try now : 7C:F9:0E:34:8A:A0
I/jxcore-log( 6633): 
,I/jxcore-log( 6633): 2015-12-18T18:00:19.614Z SendDataConnector.js: ReStart called with peer 7C:F9:0E:34:8A:A0
I/jxcore-log( 6633): 
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:31000 mC
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6633): checkListForExpiredPeers: Peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9219] expired
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6633): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9219], add/update: false
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6633): modifyListOfDiscoveredPeers: Removed [F8:95:C7:87:3C:51 LGE-LG-H815_PT9219]
I/io.jxcore.node.ConnectionHelper( 6633): onPeerLost: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9219]
D/io.jxcore.node.ConnectionHelper( 6633): hasConnection: No connection with peer with ID F8:95:C7:87:3C:51
D/io.jxcore.node.ConnectionHelper( 6633): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9219] removed
D/io.jxcore.node.ConnectionHelper( 6633): notifyPeerAvailability: Peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9219] not available
,I/jxcore-log( 6633): peerAvailabilityChanged [{"peerIdentifier":"F8:95:C7:87:3C:51","peerName":"LGE-LG-H815_PT9219","peerAvailable":false}]
I/jxcore-log( 6633): 
,D/io.jxcore.node.ConnectionHelper( 6633): disconnectOutgoingConnection: Trying to close connection to peer with ID 7C:F9:0E:34:8A:A0
,E/io.jxcore.node.ConnectionHelper( 6633): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 7C:F9:0E:34:8A:A0
D/io.jxcore.node.ConnectionHelper( 6633): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 6633): disconnectOutgoingConnection: Failed to disconnect (peer ID: 7C:F9:0E:34:8A:A0), either no such connection or failed to close the connection
I/jxcore-log( 6633): 2015-12-18T18:00:24.617Z SendDataConnector.js: Mobile.Disconnect() callback with peer 7C:F9:0E:34:8A:A0
I/jxcore-log( 6633): 
I/jxcore-log( 6633): 2015-12-18T18:00:24.617Z SendDataConnector.js: Connect (retry count 1) to peer 7C:F9:0E:34:8A:A0 with availability status: true
I/jxcore-log( 6633): 
I/jxcore-log( 6633): 2015-12-18T18:00:24.617Z SendDataConnector.js: doConnect called with peer 7C:F9:0E:34:8A:A0
I/jxcore-log( 6633): 
I/jxcore-log( 6633): 2015-12-18T18:00:24.618Z SendDataConnector.js: do connect now
I/jxcore-log( 6633): 
I/io.jxcore.node.ConnectionHelper( 6633): connect: Trying to connect to peer with ID 7C:F9:0E:34:8A:A0
D/io.jxcore.node.ConnectionHelper( 6633): hasConnection: No connection with peer with ID 7C:F9:0E:34:8A:A0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6633): connect: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT8280]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6633): connect: Trying to start connecting to null in address 7C:F9:0E:34:8A:A0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6633): setInsecureRfcommSocketPort: Using port -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6633): setMaxNumberOfRetries: 0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6633): onConnecting: null 7C:F9:0E:34:8A:A0
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6633): connect: Started connecting to null in address 7C:F9:0E:34:8A:A0
I/io.jxcore.node.ConnectionHelper( 6633): connect: Connection process successfully started (peer ID: 7C:F9:0E:34:8A:A0)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6633): Trying to connect to peer with address 7C:F9:0E:34:8A:A0 (thread ID: 855)
W/BluetoothAdapter( 6633): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2530): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2530): SDP - Rcvd conn cnf with error: 0x8  CID 0x49
,E/bt-btif ( 2530): DISCOVERY_COMP_EVT slot id:21, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2530): invalid rfc slot id: 21
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6633): Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 853)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6633): Maximum number of allowed retries (0) reached, giving up... (thread ID: 853)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6633): onConnectionFailed: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6633): Exiting thread (thread ID: 853)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6633): shutdown (thread ID: 853)
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6633): onConnectionFailed: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT8280]
,I/jxcore-log( 6633): 2015-12-18T18:00:31.179Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT8280] failed
I/jxcore-log( 6633): 
,I/jxcore-log( 6633): 2015-12-18T18:00:31.179Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT8280] failed
I/jxcore-log( 6633): 
I/jxcore-log( 6633): 2015-12-18T18:00:31.179Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 6633): 
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6633): setInsecureRfcommSocketPort: Will use port 1 when trying to connect
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:31000 mC
,W/bt-btif ( 2530): info:x10
,D/        ( 2530): remote version info [7c:f9:0e:34:8a:a0]: 7, f, 610c
,E/BluetoothRemoteDevices( 2530): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 2530): process_service_search_attr_rsp
,I/BluetoothBondStateMachine( 2530): bondStateChangeCallback: Status: 0 Address: 7C:F9:0E:34:8A:A0 newState: 1
,E/bt-btif ( 2530): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2530): Bond State Change Intent:7C:F9:0E:34:8A:A0 OldState: 10 NewState: 11
,I/BluetoothBondStateMachine( 2530): Entering PendingCommandState State
,I/BluetoothBondStateMachine( 2530): bondStateChangeCallback: Status: 0 Address: 7C:F9:0E:34:8A:A0 newState: 0
,D/BluetoothAdapterProperties( 2530): Failed to remove device: 7C:F9:0E:34:8A:A0
,I/BluetoothBondStateMachine( 2530): Bond State Change Intent:7C:F9:0E:34:8A:A0 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2530): StableState(): Entering Off State
,D/BluetoothMetrics( 2530): btclass5a020c
,D/Checkin ( 2530): publish the event [tag = MOT_BT event name = PAIRING]
,W/bt-btif ( 2530): new conn_srvc id:26, app_id:1
W/bt-btif ( 2530): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2530): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6633): onSocketConnected: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT8280]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6633): Socket connection succeeded (using system decided port), total number of attempts: 1 (thread ID: 855)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6633): shutdown (thread ID: 855)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6633): onBytesWritten: 80 bytes successfully written (thread ID: 857)
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6633): Unexpected error: Attempt to invoke virtual method 'long org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread.getId()' on a null object reference
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6633): java.lang.NullPointerException: Attempt to invoke virtual method 'long org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread.getId()' on a null object reference
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6633): 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread.run(BluetoothClientThread.java:186)
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6633): onConnectionFailed: Unexpected error: Attempt to invoke virtual method 'long org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread.getId()' on a null object reference
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6633): Exiting thread (thread ID: 855)
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6633): onConnectionFailed: Unexpected error: Attempt to invoke virtual method 'long org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread.getId()' on a null object reference [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT8280]
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6633): setInsecureRfcommSocketPort: Will use port -1 when trying to connect
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 6633): Entering thread (ID: 857)
D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 6633): Exiting thread (ID: 857)
,W/bt-btif ( 2530): bta_jv_rfc_port_to_cb(port_handle:0x18):jv handle:0x0 not FOUND
,I/jxcore-log( 6633): 2015-12-18T18:00:36.179Z SendDataConnector.js: re-try now : 7C:F9:0E:34:8A:A0
I/jxcore-log( 6633): 
,I/jxcore-log( 6633): 2015-12-18T18:00:36.180Z SendDataConnector.js: ReStart called with peer 7C:F9:0E:34:8A:A0
I/jxcore-log( 6633): 
,D/btif_config_util( 2530): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2530): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2530): onReceive
,I/BTConnectionReceiver( 8520): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:34:8A:A0, alias=null, name=S5-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 8520): Bluetooth Device Name: S5-1
,D/io.jxcore.node.ConnectionHelper( 6633): disconnectOutgoingConnection: Trying to close connection to peer with ID 7C:F9:0E:34:8A:A0
,E/io.jxcore.node.ConnectionHelper( 6633): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 7C:F9:0E:34:8A:A0
D/io.jxcore.node.ConnectionHelper( 6633): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 6633): disconnectOutgoingConnection: Failed to disconnect (peer ID: 7C:F9:0E:34:8A:A0), either no such connection or failed to close the connection
I/jxcore-log( 6633): 2015-12-18T18:00:41.183Z SendDataConnector.js: Mobile.Disconnect() callback with peer 7C:F9:0E:34:8A:A0
I/jxcore-log( 6633): 
,I/jxcore-log( 6633): 2015-12-18T18:00:41.186Z SendDataConnector.js: Connect (retry count 2) to peer 7C:F9:0E:34:8A:A0 with availability status: true
I/jxcore-log( 6633): 
,I/jxcore-log( 6633): 2015-12-18T18:00:41.188Z SendDataConnector.js: doConnect called with peer 7C:F9:0E:34:8A:A0
I/jxcore-log( 6633): 
I/jxcore-log( 6633): 2015-12-18T18:00:41.190Z SendDataConnector.js: do connect now
I/jxcore-log( 6633): 
,I/io.jxcore.node.ConnectionHelper( 6633): connect: Trying to connect to peer with ID 7C:F9:0E:34:8A:A0
D/io.jxcore.node.ConnectionHelper( 6633): hasConnection: No connection with peer with ID 7C:F9:0E:34:8A:A0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6633): connect: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT8280]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6633): connect: Trying to start connecting to S5-1 in address 7C:F9:0E:34:8A:A0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6633): setInsecureRfcommSocketPort: Using port -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6633): setMaxNumberOfRetries: 0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6633): onConnecting: S5-1 7C:F9:0E:34:8A:A0
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6633): connect: Started connecting to S5-1 in address 7C:F9:0E:34:8A:A0
I/io.jxcore.node.ConnectionHelper( 6633): connect: Connection process successfully started (peer ID: 7C:F9:0E:34:8A:A0)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6633): Trying to connect to peer with address 7C:F9:0E:34:8A:A0 (thread ID: 858)
W/BluetoothAdapter( 6633): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2530): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:31000 mC
,E/WifiStateMachine(  883): Connection lost, restart supplicant
,E/WifiStateMachine(  883): setWifiState: disabled
,I/SBar.MotoNetworkCtrlr( 1293): onReceive: WifiManager.WIFI_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1293): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1293): refreshSignalCluster[0]: wifi: mWifiConnected=true Wifi=0x7f02012a=com.android.systemui:drawable/stat_sys_wifi_signal_0_fully Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
I/SBar.MotoNetworkCtrlr( 1293): refreshSignalCluster[0]: mobile: Signal=0x00000000=( none ) Roaming=0x00000000=( none ) mSimIconId=0x00000000=( none ) Accessibility="Airplane mode.","",""
I/SBar.MotoNetworkCtrlr( 1293): refreshSignalCluster[0]: mobile: mHasMobileDataFeature=true DataTypeShown=0x00000000=( none ) Activity=0x00000000=( none ) Accessibility=""
,E/WifiStateMachine(  883): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$8800 - processMessage - processMsg
E/WifiStateMachine(  883): handleNetworkDisconnect any config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  883): handleNetworkDisconnect "NG700" nid=0
E/WifiConfigStore(  883): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
E/WifiConfigStore(  883): failed to set BSSID: any
E/WifiStateMachine(  883): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
,E/WifiStateMachine(  883): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/native  (  883): do suspend true
,D/WifiP2pService(  883): InactiveState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  883): P2pEnabledState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/CommandListener(  289): Clearing all IP addresses on wlan0
,D/TCMD    (  474): NL - Read 60 bytes from update socket.
,D/TCMD    (  474): NL - ignore NL message, type = 21
D/TCMD    (  474): Listening for incoming client connection request
,V/NativeCrypto( 1740): Read error: ssl=0xb7eefd10: I/O error during system call, Connection timed out
,V/NativeCrypto( 1740): SSL shutdown failed: ssl=0xb7eefd10: I/O error during system call, Broken pipe
,D/ConnectivityService(  883): reportBadNetwork(NetworkAgentInfo [WIFI () - 101]) by 10016
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  883): ValidatedState{ when=-3ms what=532488 arg1=10016 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  883): DefaultState{ when=-3ms what=532488 arg1=10016 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  883): Forcing reevaluation
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  883): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  883): Checking http://clients3.google.com/generate_204 on "NG700"
,E/WifiStateMachine(  883): setDetailed state, old =CONNECTED and new state=DISCONNECTED hidden=false
,E/WifiStateMachine(  883): setDetailed state send new extra info<unknown ssid>
,I/SBar.MotoNetworkCtrlr( 1293): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1293): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  883): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
D/WifiMetrics(  883): connected time updated 537495
D/ConnectivityService(  883): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService(  883): NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 2
,I/SBar.MotoNetworkCtrlr( 1293): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1293): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1293): refreshSignalCluster[0]: wifi: mWifiConnected=false Wifi=0x00000000=( none ) Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
D/Checkin (  883): publish the event [tag = MOT_WIFI_L1 event name = CONNECT]
,W/Settings( 1740): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/SBar.MotoNetworkCtrlr( 1293): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1293): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6633): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6633): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6633): setState: RESTARTING
,D/WifiP2pService(  883): InactiveState{ when=0 what=139268 arg2=37 target=com.android.internal.util.StateMachine$SmHandler }
,E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6633): Failed to shutdown P2P device discovery, got error code: 0
,E/WifiStateMachine(  883): WifiStateMachine: Leaving Connected state
E/WifiStateMachine(  883): Unexpected BatchedScanResults :null
,E/WifiStateMachine(  883): [1,450,461,645,006 ms] noteScanEnd no scan source
,D/WifiP2pService(  883): InactiveState{ when=-1ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  883): P2pEnabledState{ when=-1ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiScanningService(  883): SCAN_AVAILABLE : 1
D/RttService(  883): SCAN_AVAILABLE : 1
D/WifiP2pService(  883): discovery change broadcast false
,D/WifiP2pService(  883): P2pDisablingState
,D/WifiP2pService(  883): P2pDisablingState{ when=-1ms what=147458 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  883): p2p socket connection lost
D/RttService(  883): EnabledState got{ when=-2ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  883): P2pDisabledState
E/WifiStateMachine(  883): Link configuration changed for netId: -1 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  883): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
,D/WifiScanningService(  883): DefaultState got{ when=-5ms what=160007 target=com.android.internal.util.StateMachine$SmHandler }
,D/ConnectivityService(  883): notifyType LOST for NetworkAgentInfo [WIFI () - 101]
,D/Nat464Xlat(  883): requiresClat: netType=1, connected=false, hasIPv4Address=true
D/CSLegacyTypeTracker(  883): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/ConnectivityService(  883): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
E/WifiStateMachine(  883): Link configuration changed for netId: -1 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
D/ConnectivityManager.CallbackHandler( 1293): CM callback handler got msg 524292
,E/WifiStateMachine(  883): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
D/ConnectivityService(  883): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/Checkin (  883): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  883): EvaluatingState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  883): DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  883): Disconnected - quitting
D/WifiNetworkAgent(  883): NetworkAgent: NetworkAgent channel lost
I/ModemStatsDSDetect( 1537): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
D/WifiP2pService(  883): P2pDisabledState{ when=0 what=139283 arg2=38 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  883): DefaultState{ when=0 what=139283 arg2=38 target=com.android.internal.util.StateMachine$SmHandler }
I/SBar.MotoNetworkCtrlr( 1293): onReceive: CONNECTIVITY_ACTION_IMMEDIATE Recieved, mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6633): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6633): onWifiStateChanged: State changed to 1
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6633): onWifiStateChanged: Wi-Fi disabled, pausing Wi-Fi Direct based peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6633): stop: Stopping services
,D/WifiP2pService(  883): P2pDisabledState{ when=0 what=139298 arg2=39 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  883): DefaultState{ when=0 what=139298 arg2=39 target=com.android.internal.util.StateMachine$SmHandler }
,D/ConnectivityService(  883): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,E/ConnectivityService(  883): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,I/ModemStatsDSDetect( 1537): INET_CONDITION=0 ,activeNet=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/Checkin (  883): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
I/ModemStatsDSDetect( 1537): onReceive() - done, currentInetCondition=0
I/SBar.MotoNetworkCtrlr( 1293): updateConnectivity[0]: NetworkInfo: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false], raw inetCondition= 0
I/SBar.MotoNetworkCtrlr( 1293): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1293): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1293): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1293): onReceive: CONNECTIVITY_ACTION_IMMEDIATE Recieved, mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/ModemStatsDSDetect( 1537): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
,I/SBar.MotoNetworkCtrlr( 1293): updateConnectivity[0]: NetworkInfo: null, raw inetCondition= 0
I/SBar.MotoNetworkCtrlr( 1293): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1293): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1293): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/ModemStatsDSDetect( 1537): INET_CONDITION=0 ,activeNet=null
I/ModemStatsDSDetect( 1537): onReceive() - done, currentInetCondition=0
,I/ActivityManager(  883): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=8900 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6633): stop: Stopping P2P device discovery...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6633): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6633): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6633): stopWifiPeerDiscovery: Stopped
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6633): setState: WAITING_FOR_SERVICES_TO_BE_ENABLED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6633): onP2pDeviceListChanged: 0 device(s) discovered
D/AndroidRuntime( 6633): Shutting down VM
,D/WifiP2pService(  883): P2pDisabledState{ when=0 what=139268 arg2=40 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  883): DefaultState{ when=0 what=139268 arg2=40 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  883): P2pDisabledState{ when=0 what=139307 arg2=41 target=com.android.internal.util.StateMachine$SmHandler }
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6633): Uncaught exception: Attempt to invoke virtual method 'boolean org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser.isStarted()' on a null object reference
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6633): java.lang.NullPointerException: Attempt to invoke virtual method 'boolean org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser.isStarted()' on a null object reference
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6633): 	at org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer.onP2pDeviceListChanged(WifiPeerDiscoverer.java:164)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6633): 	at org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer$MyPeerListListener.onPeersAvailable(WifiP2pDeviceDiscoverer.java:285)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6633): 	at android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler.handleMessage(WifiP2pManager.java:832)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6633): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6633): 	at android.os.Looper.loop(Looper.java:135)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6633): 	at android.app.ActivityThread.main(ActivityThread.java:5312)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6633): 	at java.lang.reflect.Method.invoke(Native Method)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6633): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6633): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:901)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6633): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:696)
D/WifiP2pService(  883): DefaultState{ when=0 what=139307 arg2=41 target=com.android.internal.util.StateMachine$SmHandler }
,W/ResourcesManager( 8900): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,W/bt-btif ( 2530): info:x10
,D/        ( 2530): remote version info [7c:f9:0e:34:8a:a0]: 7, f, 610c
,I/art     (  883): Explicit concurrent mark sweep GC freed 25034(1357KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 21MB/31MB, paused 1.715ms total 131.654ms
,I/Babel_SMS( 8900): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 8900): MmsConfig.loadMmsSettings
I/Babel_SMS( 8900): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,I/Babel_SMS( 8900): MmsConfig.loadFromDatabase
,E/Babel_SMS( 8900): canonicalizeMccMnc: invalid mccmnc 
,I/Babel_SMS( 8900): MmsConfig.loadFromResources
D/TCMD    (  474): NL - Read 1004 bytes from update socket.
D/TCMD    (  474): NL - message type is RTM_NEWLINK
D/TCMD    (  474): Listening for incoming client connection request
,D/Tethering(  883): InitialState.processMessage what=4
,E/Babel_SMS( 8900): canonicalizeMccMnc: invalid mccmnc nullnull
D/Tethering(  883): exception when get active network info: java.lang.NullPointerException: Attempt to invoke virtual method 'int android.net.NetworkInfo.getType()' on a null object reference
W/Settings(  883): Setting tether_dun_apn has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/Babel_SMS( 8900): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
E/Tethering(  883): ApnList is empty for checkDunConfigured()
D/Tethering(  883):  upstream interface types: 
D/Tethering(  883):  0
,D/Tethering(  883):  1
D/Tethering(  883):  5
D/Tethering(  883):  7
D/Tethering(  883): sendTetherStateChangedBroadcast 0, 0, 0
,D/TCMD    (  474): NL - Read 68 bytes from update socket.
D/TCMD    (  474): NL - message type is RTM_NEWLINK
D/TCMD    (  474): Listening for incoming client connection request
,W/Settings( 8900): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 8900): startup - clean
,I/Babel   ( 8900): deleted: false for 0
,W/bt-sdp  ( 2530): process_service_search_attr_rsp
,I/BTConnectionReceiver( 8520): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:34:8A:A0, alias=null, name=S5-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 8520): Bluetooth Device Name: S5-1
,D/TCMD    (  474): NL - Read 1004 bytes from update socket.
D/TCMD    (  474): NL - message type is RTM_NEWLINK
,D/TCMD    (  474): Listening for incoming client connection request
,W/VideoCapabilities( 8900): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 8900): Unsupported mime audio/amr-wb-plus
,W/VideoCapabilities( 8900): Unsupported mime video/mpeg2
,I/VideoCapabilities( 8900): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 8900): Unrecognized profile 2130706433 for video/avc
,D/TCMD    (  474): NL - Read 444 bytes from update socket.
D/TCMD    (  474): NL - ignore NL message, type = 17
D/TCMD    (  474): Listening for incoming client connection request
,W/VideoCapabilities( 8900): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 8900): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 8900): Unrecognized profile 2130706433 for video/avc
,I/vclib   ( 8900): onServiceConnected
,W/Babel   ( 8900): Attempted to change video mute state without an active call.
,D/TCMD    (  474): NL - Read 1004 bytes from update socket.
D/TCMD    (  474): NL - message type is RTM_NEWLINK
D/TCMD    (  474): Listening for incoming client connection request
,D/TCMD    (  474): NL - Read 444 bytes from update socket.
D/TCMD    (  474): NL - ignore NL message, type = 17
,D/TCMD    (  474): Listening for incoming client connection request
,I/MDMCTBK (  291): NetlinkHandler, wifiStateChanged 0
,I/MDMCTBK (  291): MdmCutbackHndler,wifi, new_state =0
I/MDMCTBK (  291): checkDefaultInst, current pid is = 291
I/MDMCTBK (  291): checkDefaultInst, pid match
,W/bt-btif ( 2530): new conn_srvc id:26, app_id:1
,W/bt-btif ( 2530): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2530): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6633): onSocketConnected: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT8280]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6633): Socket connection succeeded (using system decided port), total number of attempts: 1 (thread ID: 858)
,W/google-breakpad( 8938): -----BEGIN BREAKPAD MICRODUMP-----
W/google-breakpad( 8938): O A arm 04 armv7l 3.4.42-g48d3b85 #1 SMP PREEMPT Tue Jan 6 18:27:11 CST 2015
W/google-breakpad( 8938): S 0 A0ED5FF0 A0ED5000 00008000
,W/google-breakpad( 8938): S A0ED5000 000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000
W/google-breakpad( 8938): S A0ED5180 000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000
W/google-breakpad( 8938): S A0ED5300 000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000
W/google-breakpad( 8938): S A0ED5480 000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000
W/google-breakpad( 8938): S A0ED5600 000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000
W/google-breakpad( 8938): S A0ED5780 000000000000000000000000,00000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000010B3EAB700000000EA22000000B3EAB710B3EAB7000000000010000000B0ACB40000000000000000E919000010B3EAB700B3EAB7C058EDA07003000000000000C058EDA0E42DFDB600B3EAB7805CEDA0005DEDA0A89485A99B7834A90B0000000000000002000000F03FEDA0000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000
,W/google-breakpad( 8938): S A0ED5900 00000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000AA2200000000000000000000000000000000EDA000000000002000000E00000017000000041200006871406FE0A5E76F00BF352360893F23C40000006871406FE0A5E76F60893F2338A6E76F403098B900BF35237058FDA0F03FEDA0F05FEDA06D2AB2713C2AB27130000FA0F03FEDA0041200000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000001504656200100000000000000000000000000000000000000000000000000000000000000000000AA22000000000000813081280E8050805881380EBE108178811000800881380E0000000000000000
,W/google-breakpad( 8938): S A0ED5A80 00400000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000672F496E7465726E6F00690064002E0062006C007500650074006F006F00740068002E00490042006C007500650074006F006F007400680000000000000060400C0000000000B03F0000000000000040DF40C7B316B3B0BF000000000000F03F073A9EB598850040EC40C7B316B3603F76B631FC15B360BF13000020000000000000004098C7FBC03465F2C0000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000
W/google-breakpad( 8938): S A0ED5C00 0000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000028196B00000000000B000000805CEDA0005DEDA000000000537934A908DB7FA10000000004000040B0DC1CB86871406FC40000006871406FE0A5E76F60893F2338A6E76F403098B9B438FEB60B0000000000000002000000F03FEDA00000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000EDA000000000002000000E00000017000000041200006871406FE0A5E76F00BF352360893F23C40000006871406FE0A5E76F60893F2338A6E76F403098B900BF35237058FDA0F03FEDA0F05FEDA06D2AB2713C2AB27130000FA0F03FEDA0041200000000000000000000000000000000000000000000
W/google-breakpad( 8938): S A0ED5D80 000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000001504656200100000000000000000000000000000000000000000000000000000000000000000000AA22000000000000813081280E8050805881380EBE108178811000800881380E000000000000000000400000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000672F496E7465726E6F00690064002E0062006C007500650074006F006F00740068002E00490042006C007500650074006F006F007400680000000000000060400C0000000000B03F0000000000000040DF40C7B316B3B0BF000000000000F03F073A9EB598850040EC40C7B316B3603F76B631FC15B360BF13000020000000000000004098C7FBC0
W/google-breakpad( 8938): S A0ED5F00 3465F2C0000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000AD70A0E3AD0090EF6871406F0000000000000000000000009056406F000000006871406F38A6E76F60893F23E0A5E76F00BF3523B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F60893F2338A6E76F00BF35236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F60893F23E0A5E76F00BF3523B92AB271
W/google-breakpad( 8938): S A0ED6080 6871406F00000000000000000000000000000000000000006871406FE0A5E76F60893F2338A6E76F00BF35236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F60893F23E0A5E76F00BF3523B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F60893F2338A6E76F00BF35236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F60893F23E0A5E76F00BF3523B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F60893F2338A6E76F00BF35236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F60893F23E0A5E76F00BF3523B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F60893F2338A6E76F00BF35236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F60893F23E0A5E76F00BF3523B92AB271
W/google-breakpad( 8938): S A0ED6200 6871406F0000000000000000,0000000000000000000000006871406FE0A5E76F60893F2338A6E76F00BF35236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F60893F23E0A5E76F00BF3523B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F60893F2338A6E76F00BF35236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F60893F23E0A5E76F00BF3523B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F60893F2338A6E76F00BF35236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F60893F23E0A5E76F00BF3523B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F60893F2338A6E76F00BF35236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F60893F23E0A5E76F00BF3523B92AB271
W/google-breakpad( 8938): S A0ED6380 6871406F00000000000000000000000000000000000000006871406FE0A5E76F60893F2338A6E76F00BF35236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F60893F23E0A5E76F00BF3523B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F60893F2338A6E76F00BF35236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F60893F23E0A5E76F00BF3523B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F60893F2338A6E76F00BF35236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F60893F23E0A5E76F00BF3523B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F60893F2338A6E76F00BF35236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F60893F23E0A5E76F00BF3523B92AB271
,W/google-breakpad( 8938): S A0ED6500 6871406F00000000000000000000000000000000000000006871406FE0A5E76F60893F2338A6E76F00BF35236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F60893F23E0A5E76F00BF3523B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F60893F2338A6E76F00BF35236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F60893F23E0A5E76F00BF3523B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F60893F2338A6E76F00BF35236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F60893F23E0A5E76F00BF3523B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F60893F2338A6E76F00BF35236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F60893F23E0A5E76F00BF3523B92AB271
,W/google-breakpad( 8938): S A0ED6680 6871406F00000000000000000000000000000000000000006871406FE0A5E76F60893F2338A6E76F00BF35236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F60893F23E0A5E76F00BF3523B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F60893F2338A6E76F00BF35236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F60893F23E0A5E76F00BF3523B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F60893F2338A6E76F00BF35236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F60893F23E0A5E76F00BF3523B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F60893F2338A6E76F00BF35236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F60893F23E0A5E76F00BF3523B92AB271
,W/google-breakpad( 8938): S A0ED6800 6871406F00000000000000000000000000000000000000006871406FE0A5E76F60893F2338A6E76F00BF35236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F60893F23E0A5E76F00BF3523B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F60893F2338A6E76F00BF35236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F60893F23E0A5E76F00BF3523B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F60893F2338A6E76F00BF35236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F60893F23E0A5E76F00BF3523B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F60893F2338A6E76F00BF35236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F60893F23E0A5E76F00BF3523B92AB271
W/google-breakpad( 8938): S A0ED6980 6871406F00000000000000000000000000000000000000006871406FE0A5E76F60893F2338A6E76F00BF35236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F60893F23E0A5E76F00BF3523B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F60893F2338A6E76F00BF35236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F60893F23E0A5E76F00BF3523B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F60893F2338A6E76F00BF35236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F60893F23E0A5E76F00BF3523B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F60893F2338A6E76F00BF35236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F60893F23E0A5E76F00BF3523B92AB271
W/google-breakpad( 8938): S A0ED6B00 6871406F00000000000000000000000000000000000000006871406FE0A5E76F60893F2338A6E76F00BF35236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F60893F23E0A5E76F00BF3523B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F60893F2338A6E76F00BF35236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F60893F23E0A5E76F00BF3523B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F60893F2338A6E76F00BF35236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F60893F23E0A5E76F00BF3523B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F60893F2338A6E76F00BF35236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F60893F23E0A5E76F00BF3523B92AB271
W/google-breakpad( 8938): S A0ED6C80 6871406F00000000000000000000000000000000000000006871406FE0A5E76F60893F2338A6E76F00BF35236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F60893F23E0A5E76F00BF3523B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F60893F2338A6E76F00BF35236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F60893F23E0A5E76F00BF3523B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F60893F2338A6E76F00BF35236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F60893F23E0A5E76F00BF3523B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F60893F2338A6E76F00BF35236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F60893F23E0A5E76F00BF3523B92AB271
W/google-breakpad( 8938): S A0ED6E00 6871406F00000000000000000000000000000000000000006871406FE0A5E76F60893F2338A6E76F00BF35236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F60893F23E0A5E76F00BF3523B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F60893F2338A6E76F00BF35236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F60893F23E0A5E76F00BF3523B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F60893F2338A6E76F00BF35236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F60893F23E0A5E76F00BF3523B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F60893F2338A6E76F00BF35236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F60893F23E0A5E76F00BF3523B92AB271
W/google-breakpad( 8938): S A0ED6F80 6871406F0000000000000000,0000000000000000000000006871406FE0A5E76F60893F2338A6E76F00BF35236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F60893F23E0A5E76F00BF3523B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F60893F2338A6E76F00BF35236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F60893F23E0A5E76F00BF3523B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F60893F2338A6E76F00BF35236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F60893F23E0A5E76F00BF3523B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F60893F2338A6E76F00BF35236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F60893F23E0A5E76F00BF3523B92AB271
,W/google-breakpad( 8938): S A0ED7100 6871406F00000000000000000000000000000000000000006871406FE0A5E76F60893F2338A6E76F00BF35236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F60893F23E0A5E76F00BF3523B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F60893F2338A6E76F00BF35236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F60893F23E0A5E76F00BF3523B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F60893F2338A6E76F00BF35236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F60893F23E0A5E76F00BF3523B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F60893F2338A6E76F00BF35236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F60893F23E0A5E76F00BF3523B92AB271
,W/google-breakpad( 8938): S A0ED7280 6871406F00000000000000000000000000000000000000006871406FE0A5E76F60893F2338A6E76F00BF35236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F60893F23E0A5E76F00BF3523B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F60893F2338A6E76F00BF35236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F60893F23E0A5E76F00BF3523B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F60893F2338A6E76F00BF35236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F60893F23E0A5E76F00BF3523B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F60893F2338A6E76F00BF35236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F60893F23E0A5E76F00BF3523B92AB271
,W/google-breakpad( 8938): S A0ED7400 6871406F00000000000000000000000000000000000000006871406FE0A5E76F60893F2338A6E76F00BF35236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F60893F23E0A5E76F00BF3523B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F60893F2338A6E76F00BF35236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F60893F23E0A5E76F00BF3523B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F60893F2338A6E76F00BF35236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F60893F23E0A5E76F00BF3523B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F60893F2338A6E76F00BF35236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F60893F23E0A5E76F00BF3523B92AB271
W/google-breakpad( 8938): S A0ED7580 6871406F00000000000000000000000000000000000000006871406FE0A5E76F60893F2338A6E76F00BF35236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F60893F23E0A5E76F00BF3523B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F60893F2338A6E76F00BF35236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F60893F23E0A5E76F00BF3523B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F60893F2338A6E76F00BF35236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F60893F23E0A5E76F00BF3523B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F60893F2338A6E76F00BF35236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F60893F23E0A5E76F00BF3523B92AB271
W/google-breakpad( 8938): S A0ED7700 6871406F00000000000000000000000000000000000000006871406FE0A5E76F60893F2338A6E76F00BF35236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F60893F23E0A5E76F00BF3523B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F60893F2338A6E76F00BF35236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F60893F23E0A5E76F00BF3523B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F60893F2338A6E76F00BF35236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F60893F23E0A5E76F00BF3523B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F60893F2338A6E76F00BF35236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F60893F23E0A5E76F00BF3523B92AB271
W/google-breakpad( 8938): S A0ED7880 6871406F00000000000000000000000000000000000000006871406FE0A5E76F60893F2338A6E76F00BF35236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F60893F23E0A5E76F00BF3523B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F60893F2338A6E76F00BF35236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F60893F23E0A5E76F00BF3523B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F60893F2338A6E76F00BF35236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F60893F23E0A5E76F00BF3523B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F60893F2338A6E76F00BF35236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F60893F23E0A5E76F00BF3523B92AB271
W/google-breakpad( 8938): S A0ED7A00 6871406F00000000000000000000000000000000000000006871406FE0A5E76F60893F2338A6E76F00BF35236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F60893F23E0A5E76F00BF3523B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F60893F2338A6E76F00BF35236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F60893F23E0A5E76F00BF3523B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F60893F2338A6E76F00BF35236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F60893F23E0A5E76F00BF3523B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F60893F2338A6E76F00BF35236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F60893F23E0A5E76F00BF3523B92AB271
W/google-breakpad( 8938): S A0ED7B80 6871406F00000000000000000000000000000000000000006871406FE0A5E76F60893F2338A6E76F00BF35236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F60893F23E0A5E76F00BF3523B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F60893F2338A6E76F00BF35236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F60893F23E0A5E76F00BF3523B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F60893F2338A6E76F00BF35236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F60893F23E0A5E76F00BF3523B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F60893F2338A6E76F00BF35236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F60893F23E0A5E76F00BF3523B92AB271
W/google-breakpad( 8938): S A0ED7D00 6871406F00000000000000000000000000000000000000006871406FE0A5E76F60893F2338A6E76F00BF35236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F60893F23E0A5E76F00BF3523B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F60893F2338A6E76F00BF35236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F60893F23E0A5E76F00BF3523B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F60893F2338A6E76F00BF35236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F60893F23E0A5E76F00BF3523B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F60893F2338A6E76F00BF35236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F60893F23E0A5E76F00BF3523B92AB271
W/google-breakpad( 8938): S A0ED7E80 6871406F00000000000000000000000000000000000000006871406FE0A5E76F60893F2338A6E76F00BF35236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F60893F23E0A5E76F00BF3523B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F60893F2338A6E76F00BF35236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F60893F23E0A5E76F00BF3523B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F60893F2338A6E76F00BF35236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F60893F23E0A5E76F00BF3523B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F60893F2338A6E76F00BF35236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F60893F23E0A5E76F00BF3523B92AB271
W/google-breakpad( 8938): S A0ED8000 6871406F00000000000000000000000000000000000000006871406FE0A5E76F60893F2338A6E76F00BF35236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F60893F23E0A5E76F00BF3523B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F60893F2338A6E76F00BF35236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F60893F23E0A5E76F00BF3523B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F60893F2338A6E76F00BF35236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F60893F23E0A5E76F00BF3523B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F60893F2338A6E76F00BF35236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F60893F23E0A5E76F00BF3523B92AB271
W/google-breakpad( 8938): S A0ED8180 6871406F00000000000000000000000000000000000000006871406FE0A5E76F60893F2338A6E76F00BF35236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F60893F23E0A5E76F00BF3523B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F60893F2338A6E76F00BF35236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F60893F23E0A5E76F00BF3523B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F60893F2338A6E76F00BF35236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F60893F23E0A5E76F00BF3523B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F60893F2338A6E76F00BF35236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F60893F23E0A5E76F00BF3523B92AB271
W/google-breakpad( 8938): S A0ED8300 6871406F00000000000000000000000000000000000000006871406FE0A5E76F60893F2338A6E76F00BF35236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F60893F23E0A5E76F00BF3523B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F60893F2338A6E76F00BF35236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F60893F23E0A5E76F00BF3523B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F60893F2338A6E76F00BF35236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F60893F23E0A5E76F00BF3523B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F60893F2338A6E76F00BF35236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F60893F23E0A5E76F00BF3523B92AB271
W/google-breakpad( 8938): S A0ED8480 6871406F00000000000000000000000000000000000000006871406FE0A5E76F60893F2338A6E76F00BF35236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F60893F23E0A5E76F00BF3523B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F60893F2338A6E76F00BF35236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F60893F23E0A5E76F00BF3523B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F60893F2338A6E76F00BF35236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F60893F23E0A5E76F00BF3523B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F60893F2338A6E76F00BF35236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F60893F23E0A5E76F00BF3523B92AB271
W/google-breakpad( 8938): S A0ED8600 6871406F00000000000000000000000000000000000000006871406FE0A5E76F60893F2338A6E76F00BF35236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F60893F23E0A5E76F00BF3523B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F60893F2338A6E76F00BF35236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F60893F23E0A5E76F00BF3523B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F60893F2338A6E76F00BF35236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F60893F23E0A5E76F00BF3523B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F60893F2338A6E76F00BF35236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F60893F23E0A5E76F00BF3523B92AB271
W/google-breakpad( 8938): S A0ED8780 6871406F00000000000000000000000000000000000000006871406FE0A5E76F60893F2338A6E76F00BF35236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F60893F23E0A5E76F00BF3523B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F60893F2338A6E76F00BF35236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F60893F23E0A5E76F00BF3523B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F60893F2338A6E76F00BF35236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F60893F23E0A5E76F00BF3523B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F60893F2338A6E76F00BF35236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F60893F23E0A5E76F00BF3523B92AB271
W/google-breakpad( 8938): S A0ED8900 6871406F00000000000000000000000000000000000000006871406FE0A5E76F60893F2338A6E76F00BF35236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F60893F23E0A5E76F00BF3523B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F60893F2338A6E76F00BF35236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F60893F23E0A5E76F00BF3523B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F60893F2338A6E76F00BF35236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F60893F23E0A5E76F00BF3523B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F60893F2338A6E76F00BF35236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F60893F23E0A5E76F00BF3523B92AB271
W/google-breakpad( 8938): S A0ED8A80 6871406F00000000000000000000000000000000000000006871406FE0A5E76F60893F2338A6E76F00BF35236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F60893F23E0A5E76F00BF3523B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F60893F2338A6E76F00BF35236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F60893F23E0A5E76F00BF3523B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F60893F2338A6E76F00BF35236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F60893F23E0A5E76F00BF3523B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F60893F2338A6E76F00BF35236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F60893F23E0A5E76F00BF3523B92AB271
W/google-breakpad( 8938): S A0ED8C00 6871406F00000000000000000000000000000000000000006871406FE0A5E76F60893F2338A6E76F00BF35236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F60893F23E0A5E76F00BF3523B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F60893F2338A6E76F00BF35236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F60893F23E0A5E76F00BF3523B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F60893F2338A6E76F00BF35236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F60893F23E0A5E76F00BF3523B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F60893F2338A6E76F00BF35236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F60893F23E0A5E76F00BF3523B92AB271
W/google-breakpad( 8938): S A0ED8D80 6871406F00000000000000000000000000000000000000006871406FE0A5E76F60893F2338A6E76F00BF35236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F60893F23E0A5E76F00BF3523B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F60893F2338A6E76F00BF35236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F60893F23E0A5E76F00BF3523B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F60893F2338A6E76F00BF35236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F60893F23E0A5E76F00BF3523B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F60893F2338A6E76F00BF35236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F60893F23E0A5E76F00BF3523B92AB271
,W/google-breakpad( 8938): S A0ED8F00 6871406F00000000000000000000000000000000000000006871406FE0A5E76F60893F2338A6E76F00BF35236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F60893F23E0A5E76F00BF3523B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F60893F2338A6E76F00BF35236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F60893F23E0A5E76F00BF3523B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F60893F2338A6E76F00BF35236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F60893F23E0A5E76F00BF3523B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F60893F2338A6E76F00BF35236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F60893F23E0A5E76F00BF3523B92AB271
W/google-breakpad( 8938): S A0ED9080 6871406F00000000000000000000000000000000000000006871406FE0A5E76F60893F2338A6E76F00BF35236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F60893F23E0A5E76F00BF3523B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F60893F2338A6E76F00BF35236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F60893F23E0A5E76F00BF3523B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F60893F2338A6E76F00BF35236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F60893F23E0A5E76F00BF3523B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F60893F2338A6E76F00BF35236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F60893F23E0A5E76F00BF3523B92AB271
W/google-breakpad( 8938): S A0ED9200 6871406F00000000000000000000000000000000000000006871406FE0A5E76F60893F2338A6E76F00BF35236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F60893F23E0A5E76F00BF3523B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F60893F2338A6E76F00BF35236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F60893F23E0A5E76F00BF3523B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F60893F2338A6E76F00BF35236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F60893F23E0A5E76F00BF3523B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F60893F2338A6E76F00BF35236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F60893F23E0A5E76F00BF3523B92AB271
W/google-breakpad( 8938): S A0ED9380 6871406F00000000000000000000000000000000000000006871406FE0A5E76F60893F2338A6E76F00BF35236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F60893F23E0A5E76F00BF3523B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F60893F2338A6E76F00BF35236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F60893F23E0A5E76F00BF3523B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F60893F2338A6E76F00BF35236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F60893F23E0A5E76F00BF3523B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F60893F2338A6E76F00BF35236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F60893F23E0A5E76F00BF3523B92AB271
W/google-breakpad( 8938): S A0ED9500 6871406F00000000000000000000000000000000000000006871406FE0A5E76F60893F2338A6E76F00BF35236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F60893F23E0A5E76F00BF3523B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F60893F2338A6E76F00BF35236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F60893F23E0A5E76F00BF3523B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F60893F2338A6E76F00BF35236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F60893F23E0A5E76F00BF3523B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F60893F2338A6E76F00BF35236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F60893F23E0A5E76F00BF3523B92AB271
W/google-breakpad( 8938): S A0ED9680 6871406F00000000000000000000000000000000000000006871406FE0A5E76F60893F2338A6E76F00BF35236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F60893F23E0A5E76F00BF3523B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F60893F2338A6E76F00BF35236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F60893F23E0A5E76F00BF3523B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F60893F2338A6E76F00BF35236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F60893F23E0A5E76F00BF3523B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F60893F2338A6E76F00BF35236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F60893F23E0A5E76F00BF3523B92AB271
W/google-breakpad( 8938): S A0ED9800 6871406F00000000000000000000000000000000000000006871406FE0A5E76F60893F2338A6E76F00BF35236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F60893F23E0A5E76F00BF3523B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F60893F2338A6E76F00BF35236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F60893F23E0A5E76F00BF3523B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F60893F2338A6E76F00BF35236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F60893F23E0A5E76F00BF3523B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F60893F2338A6E76F00BF35236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F60893F23E0A5E76F00BF3523B92AB271
W/google-breakpad( 8938): S A0ED9980 6871406F00000000000000000000000000000000000000006871406FE0A5E76F60893F2338A6E76F00BF35236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F60893F23E0A5E76F00BF3523B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F60893F2338A6E76F00BF35236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F60893F23E0A5E76F00BF3523B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F60893F2338A6E76F00BF35236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F60893F23E0A5E76F00BF3523B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F60893F2338A6E76F00BF35236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F60893F23E0A5E76F00BF3523B92AB271
W/google-breakpad( 8938): S A0ED9B00 6871406F00000000000000000000000000000000000000006871406FE0A5E76F60893F2338A6E76F00BF35236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F60893F23E0A5E76F00BF3523B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F60893F2338A6E76F00BF35236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F60893F23E0A5E76F00BF3523B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F60893F2338A6E76F00BF35236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F60893F23E0A5E76F00BF3523B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F60893F2338A6E76F00BF35236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F60893F23E0A5E76F00BF3523B92AB271
W/google-breakpad( 8938): S A0ED9C80 6871406F00000000000000000000000000000000000000006871406FE0A5E76F60893F2338A6E76F00BF35236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F60893F23E0A5E76F00BF3523B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F60893F2338A6E76F00BF35236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F60893F23E0A5E76F00BF3523B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F60893F2338A6E76F00BF35236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F60893F23E0A5E76F00BF3523B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F60893F2338A6E76F00BF35236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F60893F23E0A5E76F00BF3523B92AB271
W/google-breakpad( 8938): S A0ED9E00 6871406F00000000000000000000000000000000000000006871406FE0A5E76F60893F2338A6E76F00BF35236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F60893F23E0A5E76F00BF3523B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F60893F2338A6E76F00BF35236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F60893F23E0A5E76F00BF3523B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F60893F2338A6E76F00BF35236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F60893F23E0A5E76F00BF3523B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F60893F2338A6E76F00BF35236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F60893F23E0A5E76F00BF3523B92AB271
W/google-breakpad( 8938): S A0ED9F80 6871406F00000000000000000000000000000000000000006871406FE0A5E76F60893F2338A6E76F00BF35236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F60893F23E0A5E76F00BF3523B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F60893F2338A6E76F00BF35236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F60893F23E0A5E76F00BF3523B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F60893F2338A6E76F00BF35236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F60893F23E0A5E76F00BF3523B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F60893F2338A6E76F00BF35236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F60893F23E0A5E76F00BF3523B92AB271
W/google-breakpad( 8938): S A0EDA100 6871406F00000000000000000000000000000000000000006871406FE0A5E76F60893F2338A6E76F00BF35236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F60893F23E0A5E76F00BF3523B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F60893F2338A6E76F00BF35236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F60893F23E0A5E76F00BF3523B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F60893F2338A6E76F00BF35236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F60893F23E0A5E76F00BF3523B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F60893F2338A6E76F00BF35236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F60893F23E0A5E76F00BF3523B92AB271
W/google-breakpad( 8938): S A0EDA280 6871406F00000000000000000000000000000000000000006871406FE0A5E76F60893F2338A6E76F00BF35236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F60893F23E0A5E76F00BF3523B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F60893F2338A6E76F00BF35236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F60893F23E0A5E76F00BF3523B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F60893F2338A6E76F00BF35236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F60893F23E0A5E76F00BF3523B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F60893F2338A6E76F00BF35236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F60893F23E0A5E76F00BF3523B92AB271
W/google-breakpad( 8938): S A0EDA400 6871406F00000000000000000000000000000000000000006871406FE0A5E76F60893F2338A6E76F00BF35236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F60893F23E0A5E76F00BF3523B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F60893F2338A6E76F00BF35236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F60893F23E0A5E76F00BF3523B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F60893F2338A6E76F00BF35236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F60893F23E0A5E76F00BF3523B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F60893F2338A6E76F00BF35236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F60893F23E0A5E76F00BF3523B92AB271
W/google-breakpad( 8938): S A0EDA580 6871406F00000000000000000000000000000000000000006871406FE0A5E76F60893F2338A6E76F00BF35236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F60893F23E0A5E76F00BF3523B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F60893F2338A6E76F00BF35236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F60893F23E0A5E76F00BF3523B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F60893F2338A6E76F00BF35236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F60893F23E0A5E76F00BF3523B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F60893F2338A6E76F00BF35236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F60893F23E0A5E76F00BF3523B92AB271
W/google-breakpad( 8938): S A0EDA700 6871406F00000000000000000000000000000000000000006871406FE0A5E76F60893F2338A6E76F00BF35236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F60893F23E0A5E76F00BF3523B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F60893F2338A6E76F00BF35236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F60893F23E0A5E76F00BF3523B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F60893F2338A6E76F00BF35236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F60893F23E0A5E76F00BF3523B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F60893F2338A6E76F00BF35236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F60893F23E0A5E76F00BF3523B92AB271
W/google-breakpad( 8938): S A0EDA880 6871406F00000000000000000000000000000000000000006871406FE0A5E76F60893F2338A6E76F00BF35236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F60893F23E0A5E76F00BF3523B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F60893F2338A6E76F00BF35236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F60893F23E0A5E76F00BF3523B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F60893F2338A6E76F00BF35236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F60893F23E0A5E76F00BF3523B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F60893F2338A6E76F00BF35236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F60893F23E0A5E76F00BF3523B92AB271
W/google-breakpad( 8938): S A0EDAA00 6871406F00000000000000000000000000000000000000006871406FE0A5E76F60893F2338A6E76F00BF35236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F60893F23E0A5E76F00BF3523B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F60893F2338A6E76F00BF35236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F60893F23E0A5E76F00BF3523B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F60893F2338A6E76F00BF35236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F60893F23E0A5E76F00BF3523B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F60893F2338A6E76F00BF35236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F60893F23E0A5E76F00BF3523B92AB271
W/google-breakpad( 8938): S A0EDAB80 6871406F00000000000000000000000000000000000000006871406FE0A5E76F60893F2338A6E76F00BF35236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F60893F23E0A5E76F00BF3523B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F60893F2338A6E76F00BF35236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F60893F23E0A5E76F00BF3523B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F60893F2338A6E76F00BF35236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F60893F23E0A5E76F00BF3523B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F60893F2338A6E76F00BF35236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F60893F23E0A5E76F00BF3523B92AB271
W/google-breakpad( 8938): S A0EDAD00 6871406F00000000000000000000000000000000000000006871406FE0A5E76F60893F2338A6E76F00BF35236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F60893F23E0A5E76F00BF3523B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F60893F2338A6E76F00BF35236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F60893F23E0A5E76F00BF3523B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F60893F2338A6E76F00BF35236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F60893F23E0A5E76F00BF3523B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F60893F2338A6E76F00BF35236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F60893F23E0A5E76F00BF3523B92AB271
W/google-breakpad( 8938): S A0EDAE80 6871406F00000000000000000000000000000000000000006871406FE0A5E76F60893F2338A6E76F00BF35236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F60893F23E0A5E76F00BF3523B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F60893F2338A6E76F00BF35236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F60893F23E0A5E76F00BF3523B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F60893F2338A6E76F00BF35236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F60893F23E0A5E76F00BF3523B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F60893F2338A6E76F00BF35236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F60893F23E0A5E76F00BF3523B92AB271
W/google-breakpad( 8938): S A0EDB000 6871406F00000000000000000000000000000000000000006871406FE0A5E76F60893F2338A6E76F00BF35236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F60893F23E0A5E76F00BF3523B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F60893F2338A6E76F00BF35236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F60893F23E0A5E76F00BF3523B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F60893F2338A6E76F00BF35236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F60893F23E0A5E76F00BF3523B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F60893F2338A6E76F00BF35236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F60893F23E0A5E76F00BF3523B92AB271
W/google-breakpad( 8938): S A0EDB180 6871406F00000000000000000000000000000000000000006871406FE0A5E76F60893F2338A6E76F00BF35236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F60893F23E0A5E76F00BF3523B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F60893F2338A6E76F00BF35236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F60893F23E0A5E76F00BF3523B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F60893F2338A6E76F00BF35236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F60893F23E0A5E76F00BF3523B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F60893F2338A6E76F00BF35236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F60893F23E0A5E76F00BF3523B92AB271
W/google-breakpad( 8938): S A0EDB300 6871406F00000000000000000000000000000000000000006871406FE0A5E76F60893F2338A6E76F00BF35236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F60893F23E0A5E76F00BF3523B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F60893F2338A6E76F00BF35236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F60893F23E0A5E76F00BF3523B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F60893F2338A6E76F00BF35236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F60893F23E0A5E76F00BF3523B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F60893F2338A6E76F00BF35236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F60893F23E0A5E76F00BF3523B92AB271
W/google-breakpad( 8938): S A0EDB480 6871406F00000000000000000000000000000000000000006871406FE0A5E76F60893F2338A6E76F00BF35236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F60893F23E0A5E76F00BF3523B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F60893F2338A6E76F00BF35236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F60893F23E0A5E76F00BF3523B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F60893F2338A6E76F00BF35236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F60893F23E0A5E76F00BF3523B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F60893F2338A6E76F00BF35236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F60893F23E0A5E76F00BF3523B92AB271
W/google-breakpad( 8938): S A0EDB600 6871406F00000000000000000000000000000000000000006871406FE0A5E76F60893F2338A6E76F00BF35236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F60893F23E0A5E76F00BF3523B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F60893F2338A6E76F00BF35236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F60893F23E0A5E76F00BF3523B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F60893F2338A6E76F00BF35236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F60893F23E0A5E76F00BF3523B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F60893F2338A6E76F00BF35236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F60893F23E0A5E76F00BF3523B92AB271
W/google-breakpad( 8938): S A0EDB780 6871406F00000000000000000000000000000000000000006871406FE0A5E76F60893F2338A6E76F00BF35236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F60893F23E0A5E76F00BF3523B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F60893F2338A6E76F00BF35236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F60893F23E0A5E76F00BF3523B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F60893F2338A6E76F00BF35236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F60893F23E0A5E76F00BF3523B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F60893F2338A6E76F00BF35236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F60893F23E0A5E76F00BF3523B92AB271
W/google-breakpad( 8938): S A0EDB900 6871406F00000000000000000000000000000000000000006871406FE0A5E76F60893F2338A6E76F00BF35236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F60893F23E0A5E76F00BF3523B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F60893F2338A6E76F00BF35236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F60893F23E0A5E76F00BF3523B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F60893F2338A6E76F00BF35236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F60893F23E0A5E76F00BF3523B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F60893F2338A6E76F00BF35236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F60893F23E0A5E76F00BF3523B92AB271
W/google-breakpad( 8938): S A0EDBA80 6871406F00000000000000000000000000000000000000006871406FE0A5E76F60893F2338A6E76F00BF35236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F60893F23E0A5E76F00BF3523B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F60893F2338A6E76F00BF35236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F60893F23E0A5E76F00BF3523B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F60893F2338A6E76F00BF35236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F60893F23E0A5E76F00BF3523B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F60893F2338A6E76F00BF35236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F60893F23E0A5E76F00BF3523B92AB271
W/google-breakpad( 8938): S A0EDBC00 6871406F00000000000000000000000000000000000000006871406FE0A5E76F60893F2338A6E76F00BF35236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F60893F23E0A5E76F00BF3523B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F60893F2338A6E76F00BF35236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F60893F23E0A5E76F00BF3523B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F60893F2338A6E76F00BF35236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F60893F23E0A5E76F00BF3523B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F60893F2338A6E76F00BF35236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F60893F23E0A5E76F00BF3523B92AB271
W/google-breakpad( 8938): S A0EDBD80 6871406F00000000000000000000000000000000000000006871406FE0A5E76F60893F2338A6E76F00BF35236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F60893F23E0A5E76F00BF3523B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F60893F2338A6E76F00BF35236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F60893F23E0A5E76F00BF3523B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F60893F2338A6E76F00BF35236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F60893F23E0A5E76F00BF3523B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F60893F2338A6E76F00BF35236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F60893F23E0A5E76F00BF3523B92AB271
W/google-breakpad( 8938): S A0EDBF00 6871406F00000000000000000000000000000000000000006871406FE0A5E76F60893F2338A6E76F00BF35236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F60893F23E0A5E76F00BF3523B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F60893F2338A6E76F00BF35236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F60893F23E0A5E76F00BF3523B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F60893F2338A6E76F00BF35236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F60893F23E0A5E76F00BF3523B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F60893F2338A6E76F00BF35236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F60893F23E0A5E76F00BF3523B92AB271
W/google-breakpad( 8938): S A0EDC080 6871406F00000000000000000000000000000000000000006871406FE0A5E76F60893F2338A6E76F00BF35236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F60893F23E0A5E76F00BF3523B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F60893F2338A6E76F00BF35236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F60893F23E0A5E76F00BF3523B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F60893F2338A6E76F00BF35236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F60893F23E0A5E76F00BF3523B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F60893F2338A6E76F00BF35236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F60893F23E0A5E76F00BF3523B92AB271
W/google-breakpad( 8938): S A0EDC200 6871406F00000000000000000000000000000000000000006871406FE0A5E76F60893F2338A6E76F00BF35236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F60893F23E0A5E76F00BF3523B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F60893F2338A6E76F00BF35236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F60893F23E0A5E76F00BF3523B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F60893F2338A6E76F00BF35236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F60893F23E0A5E76F00BF3523B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F60893F2338A6E76F00BF35236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F60893F23E0A5E76F00BF3523B92AB271
W/google-breakpad( 8938): S A0EDC380 6871406F00000000000000000000000000000000000000006871406FE0A5E76F60893F2338A6E76F00BF35236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F60893F23E0A5E76F00BF3523B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F60893F2338A6E76F00BF35236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F60893F23E0A5E76F00BF3523B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F60893F2338A6E76F00BF35236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F60893F23E0A5E76F00BF3523B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F60893F2338A6E76F00BF35236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F60893F23E0A5E76F00BF3523B92AB271
W/google-breakpad( 8938): S A0EDC500 6871406F00000000000000000000000000000000000000006871406FE0A5E76F60893F2338A6E76F00BF35236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F60893F23E0A5E76F00BF3523B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F60893F2338A6E76F00BF35236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F60893F23E0A5E76F00BF3523B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F60893F2338A6E76F00BF35236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F60893F23E0A5E76F00BF3523B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F60893F2338A6E76F00BF35236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F60893F23E0A5E76F00BF3523B92AB271
W/google-breakpad( 8938): S A0EDC680 6871406F00000000000000000000000000000000000000006871406FE0A5E76F60893F2338A6E76F00BF35236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F60893F23E0A5E76F00BF3523B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F60893F2338A6E76F00BF35236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F60893F23E0A5E76F00BF3523B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F60893F2338A6E76F00BF35236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F60893F23E0A5E76F00BF3523B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F60893F2338A6E76F00BF35236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F60893F23E0A5E76F00BF3523B92AB271
W/google-breakpad( 8938): S A0EDC800 6871406F00000000000000000000000000000000000000006871406FE0A5E76F60893F2338A6E76F00BF35236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F60893F23E0A5E76F00BF3523B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F60893F2338A6E76F00BF35236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F60893F23E0A5E76F00BF3523B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F60893F2338A6E76F00BF35236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F60893F23E0A5E76F00BF3523B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F60893F2338A6E76F00BF35236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F60893F23E0A5E76F00BF3523B92AB271
W/google-breakpad( 8938): S A0EDC980 6871406F00000000000000000000000000000000000000006871406FE0A5E76F60893F2338A6E76F00BF35236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F60893F23E0A5E76F00BF3523B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F60893F2338A6E76F00BF35236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F60893F23E0A5E76F00BF3523B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F60893F2338A6E76F00BF35236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F60893F23E0A5E76F00BF3523B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F60893F2338A6E76F00BF35236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F60893F23E0A5E76F00BF3523B92AB271
W/google-breakpad( 8938): S A0EDCB00 6871406F00000000000000000000000000000000000000006871406FE0A5E76F60893F2338A6E76F00BF35236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F60893F23E0A5E76F00BF3523B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F60893F2338A6E76F00BF35236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F60893F23E0A5E76F00BF3523B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F608,93F2338A6E76F00BF35236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F60893F23E0A5E76F00BF3523B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F60893F2338A6E76F00BF35236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F60893F23E0A5E76F00BF3523B92AB271
W/google-breakpad( 8938): S A0EDCC80 6871406F00000000000000000000000000000000000000006871406FE0A5E76F60893F2338A6E76F00BF35236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F60893F23E0A5E76F00BF3523B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F60893F2338A6E76F00BF35236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F60893F23E0A5E76F00BF3523B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F60893F2338A6E76F00BF35236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F60893F23E0A5E76F00BF3523B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F60893F2338A6E76F00BF35236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F60893F23E0A5E76F00BF3523B92AB271
W/google-breakpad( 8938): S A0EDCE00 6871406F00000000000000000000000000000000000000006871406FE0A5E76F60893F2338A6E76F00BF35236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F60893F23E0A5E76F00BF3523B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F60893F2338A6E76F00BF35236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F60893F23E0A5E76F00BF3523B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F60893F2338A6E76F00BF35236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F60893F23E0A5E76F00BF3523B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F60893F2338A6E76F00BF35236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F60893F23E0A5E76F00BF3523B92AB271
W/google-breakpad( 8938): S A0EDCF80 6871406F00000000000000000000000000000000000000006871406FE0A5E76F60893F2338A6E76F00BF35236D2AB2716871406F0000000000000000000000009056406F000000006871406F38A6E76F60893F23E0A5E76F00BF3523B92AB2716871406F00000000000000000000000000000000000000006871406FE0A5E76F
W/google-breakpad( 8938): C 060000406871406FE0A5E76F00BF352360893F23C40000006871406FE0A5E76F60893F2338A6E76F403098B900BF35237058FDA0F03FEDA0F05FEDA06D2AB2713C2AB27130000FA00000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000
W/google-breakpad( 8938): M B6FF4000 00000000 00003000 E9668E25F5C80EF4F2CC4AB624E387BF0 app_process32
W/google-breakpad( 8938): M A1497000 00000000 00AB8000 F83F9605A81C561DE740DB94A502D11C0 libjxcore.so
W/google-breakpad( 8938): M A4756000 00000000 00005000 7940278696CC504CA766F27B36AC080A0 gralloc.msm8226.so
W/google-breakpad( 8938): M A5B1D000 00000000 00452000 1C3C15CCBCD1E8D40558461B307435E60 libsc-a3xx.so
W/google-breakpad( 8938): M A5F7F000 00000000 0000A000 BB53B487721763CEB1E8693EAC1446400 libqservice.so
W/google-breakpad( 8938): M A5F89000 00000000 00007000 48FE648D1FA5FCBE53FCA043FD7608CB0 libqdutils.so
W/google-breakpad( 8938): M A72DA000 00000000 00005000 BEDF6C78A529DBAC1032A12C9142745E0 libmemalloc.so
W/google-breakpad( 8938): M A72DF000 00000000 0000C000 FE1E24201276FD291234996A311FBB9C0 eglsubAndroid.so
W/google-breakpad( 8938): M A7BFF000 00000000 01AE1000 488126E5C3F082244EC0664CC97A94320 libwebviewchromium.so
W/google-breakpad( 8938): M ADFFF000 00000000 00003000 932CC9935B065A05D39E38681E0A5F2E0 libwebviewchromium_loader.so
W/google-breakpad( 8938): M AE002000 00000000 00010000 62690FE7B4748EF8151B01903B27608D0 libandroid.so
,W/google-breakpad( 8938): M AE012000 00000000 0013A000 9C03AF685FCBD8E590150A91E97E640F0 libGLESv2_adreno.so
W/google-breakpad( 8938): M AE14D000 00000000 00034000 CF692CC2042CC03999A6210A4668E2EF0 libGLESv1_CM_adreno.so
W/google-breakpad( 8938): M AE181000 00000000 00027000 13BED457CB8AEE0E8E47FB48F3E826420 libgsl.so
W/google-breakpad( 8938): M AE1A9000 00000000 00029000 C29A639A4A36C88466F1ACCA732D030E0 libEGL_adreno.so
W/google-breakpad( 8938): M AE770000 00000000 00018000 0F5D893354D9DF6AC2763E175086C0730 libjavacrypto.so
W/google-breakpad( 8938): M AE788000 00000000 00009000 0D2147262F4305E3AED211CB96FC96BA0 librs_jni.so
W/google-breakpad( 8938): M AE791000 00000000 00006000 ED6A76B3930E7139A7512B4E28EBAC070 libaudioeffect_jni.so
W/google-breakpad( 8938): M AE797000 00000000 00004000 CDA9BA072D4DECC71C5E63467275E7EE0 libsoundpool.so
W/google-breakpad( 8938): M AE79B000 00000000 0000E000 D02CB251CF8787A770DE2CFDC52A2B040 libstagefright_amrnb_common.so
W/google-breakpad( 8938): M AE7A9000 00000000 0001B000 F59669C665FE4B073886A8DAAECEA86F0 libvorbisidec.so
W/google-breakpad( 8938): M AE7C4000 00000000 00004000 9FC00D0B150FE9FC57763A76206D1D550 libstagefright_yuv.so
W/google-breakpad( 8938): M AE7C8000 00000000 0001F000 C2D643DD7028582A8EAF64D04750FE800 libstagefright_omx.so
W/google-breakpad( 8938): M AE7E7000 00000000 00003000 E11DA546CE9E08D1D647E8E1135DAD810 libstagefright_enc_common.so
W/google-breakpad( 8938): M AE7EA000 00000000 00007000 741CC494F5299870A1C62FD71E37AE5F0 libstagefright_avc_common.so
W/google-breakpad( 8938): M AE7F1000 00000000 00005000 D3EA22EB9F383751AB500AE5951F0DB30 libpowermanager.so
W/google-breakpad( 8938): M AE7F6000 00000000 0003C000 F19A7DFF3B6F3AF94EAE23CA21905BAD0 libopus.so
W/google-breakpad( 8938): M AE832000 00000000 0001B000 87AFCC5E47ED503148F1AA03777E88590 libdrmframework.so
W/google-breakpad( 8938): M AE84D000 00000000 00127000 A7BBF189464222DE263F6ABC36940BBC0 libstagefright.so
W/google-breakpad( 8938): M AE974000 00000000 00017000 52DC9A344B2F37EBE6D980F419DD79800 libmtp.so
W/google-breakpad( 8938): M AE98B000 00000000 0002C000 84F170F995DC0EAD4100002C63E26D090 libexif.so
,W/google-breakpad( 8938): M AE9B7000 00000000 0003E000 24984B90B04E5F6F6034503CCF81A3530 libmedia_jni.so
,W/google-breakpad( 8938): M B0E19000 00000000 00003000 41762ACB6188785E5EF211BB8F33F0580 memtrack.msm8226.so
,W/google-breakpad( 8938): M B251F000 00000000 00038000 FE4EB304B0639D600DFB5871136831C50 libjavacore.so
,W/google-breakpad( 8938): M B2594000 00000000 0000B000 D2AB7418CCD8D2EBF766A47707CC1E530 libjhead.so
,W/google-breakpad( 8938): M B25B5000 00000000 00003000 8FF5949AE957364C270D0F448DAD4FE20 libjnigraphics.so
W/google-breakpad( 8938): M B25B8000 00000000 00008000 F2B1298EE4C6EA0900CDACD17FB5C16B0 libcompiler_rt.so
W/google-breakpad( 8938): M B25C0000 00000000 00004000 EB49C798524706CBF3372BB9DFBB92C20 libadreno_utils.so
,W/google-breakpad( 8938): M B44B0000 00000000 00004000 F007D0E8B4B1447628068777E701EBBC0 libwebviewchromium_plat_support.so
W/google-breakpad( 8938): M B4EBB000 00000000 00009000 CF0326786BDECFB45A519C7005E851000 libbacktrace_libc++.so
W/google-breakpad( 8938): M B4EC5000 00000000 0030F000 3DD3B70782F1361DED6013B85580C7EC0 libart.so
,W/google-breakpad( 8938): M B51F7000 00000000 00004000 3CBDF0DE27B9554508AD60FDC96CBC620 libusbhost.so
W/google-breakpad( 8938): M B51FB000 00000000 00041000 CE3E76CDA5E80C14EBD7C841E8D84F650 libssl.so
W/google-breakpad( 8938): M B523C000 00000000 000FF000 8DBA0B7AE9FE1796BB2D267C8FA450650 libsqlite.so
W/google-breakpad( 8938): M B533B000 00000000 0000F000 F954BA248E12C9AF32F54434F977FEF80 libsoundtrigger.so
,W/google-breakpad( 8938): M B534A000 00000000 0000F000 113A72FAE76EEFA7090E693F3549A3010 libselinux.so
W/google-breakpad( 8938): M B5359000 00000000 00004000 4E6C8C876BA563C3C4B0B3BA562093920 libprocessgroup.so
,W/google-breakpad( 8938): M B535D000 00000000 0045B000 83C5B450634DDB5C4FC41CA61A35B3740 libpdfium.so
,W/google-breakpad( 8938): M B57BD000 00000000 00004000 417CB14A7DB4E6A1B990FD8AC53764470 libnetd_client.so
W/google-breakpad( 8938): M B57C1000 00000000 00007000 F2C71E0D275A5D80BD35EE70ECFD70FD0 libnativehelper.so
W/google-breakpad( 8938): M B57C8000 00000000 00004000 1DD26A12D05B7F3D88CEF118B5CB04390 libnativebridge.so
W/google-breakpad( 8938): M B57CC000 00000000 0000C000 31B45FE1FA6CC789F945332C6FECF9750 libminikin.so
,W/google-breakpad( 8938): M B57D8000 00000000 00003000 CCA8BE0D07D24523C8D02FEE5F724EA70 libmemtrack.so
,W/google-breakpad( 8938): M B57DB000 00000000 00015000 60A6E0B998632198B80EB0941121CD710 libstagefright_foundation.so
,W/google-breakpad( 8938): M B57F0000 00000000 00051000 6E42AB0836D73C21533C08A98EE7B24C0 libsonivox.so
,W/google-breakpad( 8938): M B5846000 00000000 0000F000 E43E7FA869E4BCDAA3CC9601DF5A6A520 libcommon_time_client.so
,W/google-breakpad( 8938): M B5855000 00000000 0000A000 6B713D36804D7F05D55318F859E1E1400 libnbaio.so
,W/google-breakpad( 8938): M B585F000 00000000 0009B000 64619D291C1C60AA9DC086C283338A6D0 libmedia.so
,W/google-breakpad( 8938): M B58FA000 00000000 0003D000 C38209953DA7DBBD456E5C2897B2FC150 libinputflinger.so
,W/google-breakpad( 8938): M B5937000 00000000 0001B000 74F168449838583071D83A6436D107740 libinput.so
,W/google-breakpad( 8938): M B5952000 00000000 0000D000 5B082E821F342B59EB7E98B4A5A1B7D10 libimg_utils.so
,W/google-breakpad( 8938): M B595F000 00000000 00032000 89A4F06810290EEAF309C12642A3ECFA0 libjpeg.so
,W/google-breakpad( 8938): M B5992000 00000000 00231000 70FC6B965940F66B510A2E7DDA905A3F0 libskia.so
W/google-breakpad( 8938): M B5BC8000 00000000 0001D000 FC19A9DAC51914495386BF19318E22EA0 libRScpp.so
,W/google-breakpad( 8938): M B5BE5000 00000000 00028000 6E7220E587365DE4D76F850674158CB90 libpng.so
,W/google-breakpad( 8938): M B5C0D000 00000000 0005A000 659F1470013A04F7702E4BAB65F034E70 libft2.so
W/google-breakpad( 8938): M B5C67000 00000000 0003D000 44717FC6883CFF24CB7D5AB323BA6DB00 libbcinfo.so
W/google-breakpad( 8938): M B5CA4000 00000000 00023000 53CBA510148C055D91FC2FE6ABEB7AF80 libbcc.so
W/google-breakpad( 8938): M B5CE7000 00000000 00094000 D27BE45ECDACFCE9AD319AFCC4384FDE0 libc++.so
W/google-breakpad( 8938): M B5D7D000 00000000 00938000 309278A31B6D547CF87ABF9850B977170 libLLVM.so
W/google-breakpad( 8938): M B66BC000 00000000 0003A000 D276EA3D64313AC3429FA50C13E048AD0 libRS.so
,W/google-breakpad( 8938): M B66F6000 00000000 0004C000 676E6078730EA64301EE765F510315BD0 libhwui.so
,W/google-breakpad( 8938): M B6742000 00000000 00110000 1B1FD653750DE88B86D7E83095EE37160 libicuuc.so
W/google-breakpad( 8938): M B6856000 00000000 00006000 F4F99E4A6E63BF8C8005D96B2BAC8CEB0 libgabi++.so
,W/google-breakpad( 8938): M B685C000 00000000 00167000 237F53C12084A7F42405B410FDE8B4020 libicui18n.so
,W/google-breakpad( 8938): M B69C3000 00000000 00048000 AC5AE16EC01F4362C8E63DF66565090D0 libharfbuzz_ng.so
,W/google-breakpad( 8938): M B6A0B000 00000000 00005000 4E8926B7F3B40489DDA2954EC97B8D220 libwpa_client.so
W/google-breakpad( 8938): M B6A10000 00000000 00007000 ADCE932B3390EC21752A7A6149AA6DA60 libnetutils.so
,W/google-breakpad( 8938): M B6A17000 00000000 00007000 F71457D34715CA9491C2A031B5F4D2DE0 libhardware_legacy.so
,W/google-breakpad( 8938): M B6A1F000 00000000 00017000 B98E65710C415C83E972EBDC1EB52AC00 libexpat.so
W/google-breakpad( 8938): M B6A36000 00000000 0015E000 00A487ECBEDBE59A4AF1305D7B4C982D0 libcrypto.so
W/google-breakpad( 8938): M B6B97000 00000000 00003000 914425D16565257955F7E1574360B71F0 libhardware.so
W/google-breakpad( 8938): M B6B9A000 00000000 0000C000 4C6A07EB894125D1DB41E0E4195358730 libui.so
W/google-breakpad( 8938): M B6BA6000 00000000 00003000 2D9083CB8C22C02E1412DA13B1CA43AE0 libsync.so
W/google-breakpad( 8938): M B6BA9000 00000000 0004F000 559E784386AC5E53A9D4D7F9916AA7F90 libgui.so
W/google-breakpad( 8938): M B6BF8000 00000000 00008000 D86968E73262725A4BA707DF821962E60 libcamera_metadata.so
,W/google-breakpad( 8938): M B6C00000 00000000 0003A000 116F763683FB0C7DD45AACC16324410B0 libcamera_client.so
W/google-breakpad( 8938): M B6C3A000 00000000 00006000 AC1D054A26491BE96E8BCCB1E5F2926F0 libspeexresampler.so
W/google-breakpad( 8938): M B6C40000 00000000 00006000 C7B066E606462D658A4D7A9F2EAA61D80 libaudioutils.so
,W/google-breakpad( 8938): M B6C46000 00000000 0001A000 03AD92B0BEDAA751C0016E97AE374CAE0 libz.so
,W/google-breakpad( 8938): M B6C60000 00000000 00030000 AC6C388A36224541CD74B35818111B760 libbinder.so
W/google-breakpad( 8938): M B6C90000 00000000 00028000 4369ED7B14428F57EF37081E2AA076720 libandroidfw.so
W/google-breakpad( 8938): M B6CB8000 00000000 0000B000 E2F67EE50006FD0ED1482E1463C5CCFF0 libGLESv2.so
W/google-breakpad( 8938): M B6CC3000 00000000 00007000 EFE6AB19F4060BCECF8CF0E68958C2F60 libGLESv1_CM.so
,W/google-breakpad( 8938): M B6CCA000 00000000 00004000 C91EAF69D18F0D499BD58532BBA173690 libETC1.so
W/google-breakpad( 8938): M B6CCE000 00000000 00004000 7AE0C00FAEDEA3E81109CC784D49A6960 libunwind-ptrace.so
W/google-breakpad( 8938): M B6CD2000 00000000 0000E000 EF89B10946BDF6079AAF789F56192FDA0 libunwind.so
W/google-breakpad( 8938): M B6D26000 00000000 00007000 3874D35A672DF92604963290963F44990 libgccdemangle.so
W/google-breakpad( 8938): M B6D2F000 00000000 00008000 45B51BF91D330E793C9142C2617D7A8E0 libbacktrace.so
W/google-breakpad( 8938): M B6D38000 00000000 00018000 4929CACB90B1756D54AABC210956A8720 libutils.so
W/google-breakpad( 8938): M B6D50000 00000000 0003B000 2FE003E5119C67BABE1A9FAB459A5A5D0 libstlport.so
W/google-breakpad( 8938): M B6D8B000 00000000 0000D000 89C05C3E2CA4C0CEE048FF2C8DBE53BD0 libcutils.so
,W/google-breakpad( 8938): M B6D99000 00000000 00071000 A12BAF7D82BE28EC681730452D351E880 libGLES_trace.so
,W/google-breakpad( 8938): M B6E0A000 00000000 00068000 924D4C5446BF1132A902C15519E5C4FD0 libEGL.so
,W/google-breakpad( 8938): M B6E75000 00000000 000DD000 ECF593F4D6A605B04E7323D33A3802CE0 libandroid_runtime.so
,W/google-breakpad( 8938): M B6F52000 00000000 00004000 DFCD7772F3A5BD1E84A50C4DBFDE6F570 libstdc++.so
W/google-breakpad( 8938): M B6F56000 00000000 00019000 75E20BCCFF30FFEC047C70BDA7F7144B0 libm.so
W/google-breakpad( 8938): M B6F70000 00000000 00007000 8CAFD8BD12AF3E16BE6445415809E8D90 liblog.so
W/google-breakpad( 8938): M B6F78000 00000000 0005A000 11CB106704827A02E2DDB8936FB8C13B0 libc.so
,W/google-breakpad( 8938): M B6FDC000 00000000 00003000 D773C773634B82249E887ECBC5D28C900 libsigchain.so
W/google-breakpad( 8938): M B6FE4000 00000000 0000F000 F27F6D6C09C0D8A16DDA00721CEC963C0 linker
W/google-breakpad( 8938): -----END BREAKPAD MICRODUMP-----
,W/google-breakpad( 6633): ### ### ### ### ### ### ### ### ### ### ### ### ###
W/google-breakpad( 6633): Chrome build fingerprint:
W/google-breakpad( 6633): 0.0.1
W/google-breakpad( 6633): 18
W/google-breakpad( 6633): 873fd9bc-5759-4679-9dc5-2d671bd0c1b7
W/google-breakpad( 6633): ### ### ### ### ### ### ### ### ### ### ### ### ###
E/chromium( 6633): ### WebView Version 44.0.2403.90 (code 240309000)
F/libc    ( 6633): Fatal signal 11 (SIGSEGV), code 2, fault addr 0xa0ed3ff0 in tid 8874 (Thread-858)
,I/DEBUG   (  290): *** *** *** *** *** *** *** *** *** *** *** *** *** *** *** ***
,I/DEBUG   (  290): Build fingerprint: 'motorola/thea_reteu/thea:5.0.2/LXB22.46-28/27:user/release-keys'
I/DEBUG   (  290): Revision: 'p300'
I/DEBUG   (  290): ABI: 'arm'
,I/DEBUG   (  290): pid: 6633, tid: 8874, name: Thread-858  >>> com.test.thalitest <<<
,I/DEBUG   (  290): signal 11 (SIGSEGV), code 2 (SEGV_ACCERR), fault addr 0xa0ed3ff0
,I/DEBUG   (  290):     r0 6f407168  r1 6fe7a5e0  r2 2335bf00  r3 233f8960
I/DEBUG   (  290):     r4 000000c4  r5 6f407168  r6 6fe7a5e0  r7 233f8960
I/DEBUG   (  290):     r8 6fe7a638  r9 b9983040  sl 2335bf00  fp a0fd5870
I/DEBUG   (  290):     ip a0ed3ff0  sp a0ed5ff0  lr 71b22a6d  pc 71b22a3c  cpsr a00f0030
,I/DEBUG   (  290): 
I/DEBUG   (  290): backtrace:
I/DEBUG   (  290):     #00 pc 00091a3c  /system/framework/arm/boot.oat
I/DEBUG   (  290):     #01 pc 00091a6b  /system/framework/arm/boot.oat
,I/DEBUG   (  290): 
I/DEBUG   (  290): Tombstone written to: /data/tombstones/tombstone_04
,I/BootReceiver(  883): Copying /data/tombstones/tombstone_04 to DropBox (SYSTEM_TOMBSTONE)
,I/WindowState(  883): WIN DEATH: Window{ae912e u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/WifiService(  883): Client connection lost with reason: 4
,I/Zygote  (  307): Process 6633 exited due to signal (11)
,I/ActivityManager(  883): Process com.test.thalitest (pid 6633) has died
,W/bt-btif ( 2530): bta_jv_rfc_port_to_cb(port_handle:0x19):jv handle:0x0 not FOUND
,D/ConnectivityService(  883): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  883): MasterInitialState.processMessage what=3
,D/Central_PollingManager( 1478): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
W/ContextImpl( 1478): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1469 android.content.ContextWrapper.sendBroadcast:381 com.motorola.blur.service.blur.BSUtils.sendBroadcast:94 com.motorola.blur.service.blur.BSUtils.sendBroadcast:90 com.motorola.ccc.plm.pollingmanager.PollingManagerService$MyConnectivityReceiver.onReceive:491 
,D/PollingManager( 8342): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/OtaApp  ( 8342): [debug] > pollingManagerService, connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  883): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,I/ActivityManager(  883): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=8958 uid=10080 gids={50080, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/Tethering(  883): MasterInitialState.processMessage what=3
,D/Central_PollingManager( 1478): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/Central_PollingManager( 1478): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
,D/PollingManager( 8342): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/CCE     ( 8342): Registering with Alarm Manager to restart CCE
,D/CCE     ( 8342): Registering with Alarm Manager to restart CCE
,D/PollingManager( 8342): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/PollingManager( 8342): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
D/OtaApp  ( 8342): [debug] > pollingManagerService, connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/OtaApp  ( 8342): [debug] > PollingManagerService, not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
D/PollingManager( 8342): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/PollingManager( 8342): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
,D/OtaApp  ( 8342): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.ccc.ota.pm.POLLINGMGR_CONNECTIVITY
D/OtaApp  ( 8342): [debug] > CusSM.onRadioDown
,D/btif_config_util( 2530): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/MusicStore( 8958): Database version: 120
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 8958): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 8958): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 8958): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,W/ResourcesManager( 8958): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 8958): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 8958): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 8958): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 8958): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@3483b44b: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 8958): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 8958): GMSCore installation verified
,I/ConfigStore( 8958): Config Database version: 1
,I/MediaRouter( 8958): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 8958): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/ActivityManager(  883): Start proc com.android.mms for broadcast com.android.mms/.transaction.MmsSystemEventReceiver: pid=8992 uid=10023 gids={50023, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/GHttpClientFactory( 8958): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 8958): Using platform SSLCertificateSocketFactory
,I/ActivityManager(  883): Killing 8561:com.google.android.partnersetup/u0a19 (adj 15): empty #7
,W/libprocessgroup(  883): failed to open /acct/uid_10019/pid_8561/cgroup.procs: No such file or directory
,V/Mms     ( 8992): mnc/mcc: 
,V/Mms     ( 8992): tag: int value: recipientLimit - 20
,V/Mms     ( 8992): tag: int value: smsToMmsTextThreshold - 6
,V/Mms     ( 8992): tag: int value: emergencySmsTimeout - 30
V/Mms     ( 8992): tag: int value: maxSubjectLength - 80
V/Mms     ( 8992): tag: bool value: smsForceShowEncodingMenu - true
V/Mms     ( 8992): tag: bool value: enableGroupMms - false
,V/Mms     ( 8992):  mUserAgent = MOT-XT1072/Mms-5.0,  mUaProfUrl = http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/ResourcesManager( 8992): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/ActivityManager(  883): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=9018 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  883): Killing 8471:com.android.settings/1000 (adj 15): empty #7
,D/PhoneMonitor( 9018): Register our PhoneStateListener
,W/libprocessgroup(  883): failed to open /acct/uid_1000/pid_8471/cgroup.procs: No such file or directory
,D/MobileConnectivityChangeReceiver( 9018): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 9018): onReceive CONNECTIVITY_CHANGE networkType=1
,I/iu.Environment( 6487): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/iu.UploadsManager( 6487): num queued entries: 0
,I/iu.UploadsManager( 6487): num updated entries: 0
I/iu.SyncManager( 6487): NEXT; no task
I/ActivityManager(  883): Killing 8900:com.google.android.talk/u0a70 (adj 15): empty #7
,W/libprocessgroup(  883): failed to open /acct/uid_10070/pid_8900/cgroup.procs: No such file or directory
,I/ActivityManager(  883): Start proc com.google.android.apps.photos for broadcast com.google.android.apps.photos/.jobqueue.JobServiceBroadcastReceiver: pid=9036 uid=10088 gids={50088, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  883): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=9053 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
I/ActivityManager(  883): Killing 8520:com.google.android.googlequicksearchbox:search/u0a39 (adj 15): empty #7
,I/art     (  307): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 287us total 24.437ms
,I/art     (  307): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 264us total 21.706ms
,I/art     (  307): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 243us total 21.385ms
,W/libprocessgroup(  883): failed to open /acct/uid_10039/pid_8520/cgroup.procs: No such file or directory
,W/ResourcesManager( 9053): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/Babel_SMS( 9053): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 9053): MmsConfig.loadMmsSettings
I/Babel_SMS( 9053): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
I/Babel_SMS( 9053): MmsConfig.loadFromDatabase
,E/Babel_SMS( 9053): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 9053): MmsConfig.loadFromResources
,V/AlarmManager(  883): send {62c4399, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  883): send {709fa5, *walarm*:com.google.android.intent.action.GCM_RECONNECT}
V/AlarmManager(  883): send {3fe1073, *alarm*:com.android.deskclock.ON_QUARTER_HOUR}
,E/Babel_SMS( 9053): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 9053): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,V/AlarmManager(  883): done {62c4399, *alarm*:android.intent.action.TIME_TICK} [32ms]
,W/Settings( 9053): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 9053): startup - clean
,I/Babel   ( 9053): deleted: false for 0
,I/ActivityManager(  883): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=9084 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/VideoCapabilities( 9053): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 9053): Unsupported mime audio/amr-wb-plus
W/VideoCapabilities( 9053): Unsupported mime video/mpeg2
,I/VideoCapabilities( 9053): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 9053): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 9053): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 9053): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 9053): Unrecognized profile 2130706433 for video/avc
,I/vclib   ( 9053): onServiceConnected
,W/Babel   ( 9053): Attempted to change video mute state without an active call.
,I/Babel   ( 9053): connection state changed from UNKNOWN to DISCONNECTED
,I/ActivityManager(  883): Killing 8958:com.google.android.music:main/u0a80 (adj 15): empty #7
,D/WifiP2pService(  883): P2pDisabledState{ when=-4ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  883): DefaultState{ when=-5ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,W/libprocessgroup(  883): failed to open /acct/uid_10080/pid_8958/cgroup.procs: No such file or directory
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
,W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 9084): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 9084): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,I/GAv4    ( 9084): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 9084):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 9084):   adb logcat -s GAv4
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 9084): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
,W/Vold    (  277): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 9084): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,W/GAv4    ( 9084): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 9084): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 9084): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,D/Tethering(  883): exception when get active network info: java.lang.NullPointerException: Attempt to invoke virtual method 'int android.net.NetworkInfo.getType()' on a null object reference
,W/Settings(  883): Setting tether_dun_apn has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,E/Tethering(  883): ApnList is empty for checkDunConfigured()
D/Tethering(  883):  upstream interface types: 
D/Tethering(  883):  0
D/Tethering(  883):  1
D/Tethering(  883):  5
D/Tethering(  883):  7
,D/Tethering(  883): sendTetherStateChangedBroadcast 1, 0, 0
,D/TCMD    (  474): NL - Read 1008 bytes from update socket.
,D/TCMD    (  474): NL - message type is RTM_NEWLINK
D/TCMD    (  474): Listening for incoming client connection request
D/Tethering(  883): InitialState.processMessage what=4
D/Tethering(  883): exception when get active network info: java.lang.NullPointerException: Attempt to invoke virtual method 'int android.net.NetworkInfo.getType()' on a null object reference
W/Settings(  883): Setting tether_dun_apn has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/Tethering(  883): ApnList is empty for checkDunConfigured()
D/Tethering(  883):  upstream interface types: 
,D/Tethering(  883):  0
D/Tethering(  883):  1
D/Tethering(  883):  5
D/Tethering(  883):  7
D/Tethering(  883): sendTetherStateChangedBroadcast 0, 0, 0
,D/TCMD    (  474): NL - Read 1008 bytes from update socket.
,D/TCMD    (  474): NL - message type is RTM_NEWLINK
D/TCMD    (  474): Listening for incoming client connection request
,D/QsoftapCmd(  289): Got softap fwreload command we are passing on
,D/SoftapController(  289): Softap fwReload - Ok
,D/CommandListener(  289): Setting iface cfg
,D/CommandListener(  289): Trying to bring down wlan0
D/CommandListener(  289): Clearing all IP addresses on wlan0
,I/wpa_supplicant( 9127): Successfully initialized wpa_supplicant
I/wpa_supplicant( 9127): Long line in configuration file truncated
I/wpa_supplicant( 9127): rfkill: Cannot open RFKILL control device
,D/TCMD    (  474): NL - Read 1004 bytes from update socket.
D/TCMD    (  474): NL - message type is RTM_NEWLINK
D/TCMD    (  474): Listening for incoming client connection request
,D/TCMD    (  474): NL - Read 1004 bytes from update socket.
,D/TCMD    (  474): NL - message type is RTM_NEWLINK
D/TCMD    (  474): Listening for incoming client connection request
,E/WifiStateMachine(  883): setWifiState: enabling
E/WifiStateMachine(  883): Supplicant start successful
D/WifiMonitor(  883): startMonitoring(wlan0) with mConnected = false
I/SBar.MotoNetworkCtrlr( 1293): onReceive: WifiManager.WIFI_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1293): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/libmdmdetect( 9127): ESOC framework not supported
,E/Diag_Lib( 9127):  Diag_LSM_Init: Failed to open handle to diag driver, error = 2
E/wpa_supplicant( 9127): baseband property is set to [msm]
I/libmdmdetect( 9127): ESOC framework not supported
,E/wpa_supplicant( 9127):  QMI_UIM_EVENT_REG_REQ_V01, qmi_err_code: 0x0
,E/wpa_supplicant( 9127): QMI_UIM_GET_CARD_STATUS_REQ_V01, qmi_err_code: 0x0
E/wpa_supplicant( 9127): card_info[i].card_state: 0x0
,E/wpa_supplicant( 9127): card_info[i].error_code: 0x0
E/wpa_supplicant( 9127): SIM/USIM not ready
E/wpa_supplicant( 9127): Error while reading SIM card status
I/WebViewFactory( 9084): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,E/wpa_supplicant( 9127): QMI_UIM_GET_CARD_STATUS_REQ_V01, qmi_err_code: 0x0
,E/wpa_supplicant( 9127): card_info[i].card_state: 0x0
E/wpa_supplicant( 9127): card_info[i].error_code: 0x0
E/wpa_supplicant( 9127): SIM/USIM not ready
I/wpa_supplicant( 9127): eap_proxy: Card not ready
,I/LibraryLoader( 9084): Time to load native libraries: 1 ms (timestamps 5435-5436)
,I/LibraryLoader( 9084): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 9084): Binding Chromium to main looper Looper (main, tid 1) {1f654a12}
,I/LibraryLoader( 9084): Expected native library version number "",actual native library version number ""
,I/chromium( 9084): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 9084): Initializing chromium process, singleProcess=true
,W/art     ( 9084): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 9084): ApplicationContext is null in ApplicationStatus
,W/chromium( 9084): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 9084): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,E/libEGL  ( 9084): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 9084): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 9084): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 9084): Build Date: 10/28/14 Tue
I/Adreno-EGL( 9084): Local Branch: 
I/Adreno-EGL( 9084): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 9084): Local Patches: NONE
I/Adreno-EGL( 9084): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,W/AudioManagerAndroid( 9084): Requires BLUETOOTH permission
,I/NSApplication( 9084): Starting up...
,I/wpa_supplicant( 9127): Long line in configuration file truncated
I/wpa_supplicant( 9127): rfkill: Cannot open RFKILL control device
,D/TCMD    (  474): NL - Read 1004 bytes from update socket.
D/TCMD    (  474): NL - message type is RTM_NEWLINK
D/TCMD    (  474): Listening for incoming client connection request
,E/wpa_supplicant( 9127): baseband property is set to [msm]
,I/libmdmdetect( 9127): ESOC framework not supported
,I/ActivityManager(  883): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=9160 uid=10052 gids={50052, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  883): Killing 8992:com.android.mms/u0a23 (adj 15): empty #7
,E/wpa_supplicant( 9127):  QMI_UIM_EVENT_REG_REQ_V01, qmi_err_code: 0x0
,E/wpa_supplicant( 9127): QMI_UIM_GET_CARD_STATUS_REQ_V01, qmi_err_code: 0x0
E/wpa_supplicant( 9127): card_info[i].card_state: 0x0
,E/wpa_supplicant( 9127): card_info[i].error_code: 0x0
E/wpa_supplicant( 9127): SIM/USIM not ready
E/wpa_supplicant( 9127): Error while reading SIM card status
,E/wpa_supplicant( 9127): QMI_UIM_GET_CARD_STATUS_REQ_V01, qmi_err_code: 0x0
,E/wpa_supplicant( 9127): card_info[i].card_state: 0x0
E/wpa_supplicant( 9127): card_info[i].error_code: 0x0
E/wpa_supplicant( 9127): SIM/USIM not ready
I/wpa_supplicant( 9127): eap_proxy: Card not ready
,E/WifiStateMachine(  883): Supplicant connection established
,E/WifiStateMachine(  883): setWifiState: enabled
,W/libprocessgroup(  883): failed to open /acct/uid_10023/pid_8992/cgroup.procs: No such file or directory
,I/SBar.MotoNetworkCtrlr( 1293): onReceive: WifiManager.WIFI_STATE_CHANGED_ACTION Received
D/WifiConfigStore(  883): Loading config and enabling all networks 
I/SBar.MotoNetworkCtrlr( 1293): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1293): refreshSignalCluster[0]: wifi: mWifiConnected=false Wifi=0x7f020133=com.android.systemui:drawable/stat_sys_wifi_signal_null Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
,E/WifiConfigStore(  883):  got CRC SSID "NG700" -> 1501448721
,E/WifiConfigStore(  883):  got CRC SSID "NG7005g" -> 1656539502
,E/WifiConfigStore(  883): Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,D/WifiNative-HAL(  883): Setting external_sim to 1
,W/Settings( 9053): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiStateMachine(  883): Setting OUI to DA-A1-19
I/WifiNative-HAL(  883): startHal
E/wifi    (  883): getStaticLongField sWifiHalHandle 0xa2e7b89c
D/wifi    (  883): halHandle = 0x0, mVM = 0xb7c8c310, mCls = 0x10138a
I/WifiNative-HAL(  883): Could not start hal
,E/WifiStateMachine(  883): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
,E/wpa_supplicant( 9127): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
,E/native  (  883): do suspend true
,D/WifiP2pService(  883): P2pDisabledState{ when=0 what=131203 target=com.android.internal.util.StateMachine$SmHandler }
,D/CommandListener(  289): Setting iface cfg
,D/CommandListener(  289): Trying to bring up p2p0
D/WifiScanningService(  883): SCAN_AVAILABLE : 3
D/RttService(  883): SCAN_AVAILABLE : 3
D/WifiMonitor(  883): startMonitoring(p2p0) with mConnected = true
D/WifiP2pService(  883): P2pEnablingState
D/WifiP2pService(  883): P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
D/RttService(  883): DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  883): P2p socket connection successful
D/WifiP2pService(  883): P2pEnabledState
D/WifiScanningService(  883): DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
I/WifiNative-HAL(  883): startHal
D/WifiP2pService(  883): sending p2p connection changed broadcast
,E/wifi    (  883): getStaticLongField sWifiHalHandle 0xa43f39cc
,D/wifi    (  883): halHandle = 0x0, mVM = 0xb7c8c310, mCls = 0x1012be
I/WifiNative-HAL(  883): Could not start hal
E/WifiScanningService(  883): could not start HAL
I/wpa_supplicant( 9127): wlan0: CTRL-EVENT-AVOID-FREQ ranges=
E/WifiStateMachine(  883): set country code US
D/WifiNative-HAL(  883): p2pGetDeviceAddress
D/WifiNative-HAL(  883): p2pGetDeviceAddress returning 44:80:eb:7b:5a:07
,D/WifiP2pService(  883): DeviceAddress: 44:80:eb:7b:5a:07
,E/WifiStateMachine(  883): set frequency band 2
,I/wpa_supplicant( 9127): wlan0: CTRL-EVENT-SCAN-STARTED 
,D/WifiP2pService(  883): MCC mode enabled 0
,D/WifiP2pService(  883): mP2pAutoConnectSupport = 0
,D/WifiP2pService(  883): sending p2p persistent groups changed broadcast
,D/WifiP2pService(  883): InactiveState
D/WifiP2pService(  883): InactiveState{ when=-7ms what=131222 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  883): P2pEnabledState{ when=-7ms what=131222 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  883): InactiveState{ when=-8ms what=143376 obj=US target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  883): P2pEnabledState{ when=-8ms what=143376 obj=US target=com.android.internal.util.StateMachine$SmHandler }
,E/WifiStateMachine(  883): SUPPLICANT_STATE_CHANGE_EVENT state=DISCONNECTED -> state= DISCONNECTED debouncing=false
,E/WifiStateMachine(  883): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
,E/WifiStateMachine(  883): SUPPLICANT_STATE_CHANGE_EVENT state=SCANNING -> state= SCANNING debouncing=false
,E/WifiStateMachine(  883): setDetailed state, old =DISCONNECTED and new state=SCANNING hidden=false
E/WifiStateMachine(  883): setDetailed state send new extra info0x
,I/SBar.MotoNetworkCtrlr( 1293): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1293): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1293): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1293): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
D/Checkin (  883): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
D/Checkin (  883): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,I/ActivityManager(  883): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=9182 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  883): Killing 9018:com.google.android.setupwizard/u0a35 (adj 15): empty #7
,W/libprocessgroup(  883): failed to open /acct/uid_10035/pid_9018/cgroup.procs: No such file or directory
,W/ResourcesManager( 9182): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/MDMCTBK (  291): NetlinkHandler, wifiStateChanged 1
I/MDMCTBK (  291): MdmCutbackHndler,wifi, new_state =1
,I/MDMCTBK (  291): checkDefaultInst, current pid is = 291
I/MDMCTBK (  291): checkDefaultInst, pid match
I/MDMCTBK (  291): wifi_connect_to_supplicant, current pid is = 291
,D/MDMCTBK (  291): wifi_close_sockets: Close Wifi socket
D/MDMCTBK (  291): wifi_close_sockets: Exit
,E/MDMCTBK (  291): Attach monitor thread
D/MDMCTBK (  291): wifi_ctrl_recv: Exiting
D/MDMCTBK (  291): wifi_wait_on_socket: Exiting monitor thread
D/MDMCTBK (  291): wifi_close_sockets: Close Wifi socket
D/MDMCTBK (  291): wifi_close_sockets: Exit
I/MDMCTBK (  291): createWifiMonitorThread: Started the wifi monitor thread -1194135408
D/MDMCTBK (  291): wifi_wait_on_socket: Enter monitor thread
E/MDMCTBK (  291): Error: monitor connection not available
D/MDMCTBK (  291): wifi_wait_on_socket: Exiting monitor thread
D/MDMCTBK (  291): wifi_close_sockets: Close Wifi socket
,D/MDMCTBK (  291): wifi_close_sockets: Exit
,I/ActivityManager(  883): Start proc android.process.acore for content provider com.android.providers.contacts/.ContactsProvider2: pid=9209 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,I/ActivityManager(  883): Killing 9053:com.google.android.talk/u0a70 (adj 15): empty #7
,D/TCMD    (  474): NL - Read 1004 bytes from update socket.
D/TCMD    (  474): NL - message type is RTM_NEWLINK
D/TCMD    (  474): Listening for incoming client connection request
,I/ContactLocale( 9209): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,I/ActivityManager(  883): Killing 9036:com.google.android.apps.photos/u0a88 (adj 15): empty #8
,E/bt-btm  ( 2530): btm_sec_disconnected - Clearing Pending flag
,W/libprocessgroup(  883): failed to open /acct/uid_10070/pid_9053/cgroup.procs: No such file or directory
,D/EmailService.MarketingOptInSetter( 8342): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,W/libprocessgroup(  883): failed to open /acct/uid_10088/pid_9036/cgroup.procs: No such file or directory
D/BluetoothMapService( 2530): onReceive
,D/GetNotificationsWS( 8342): bindWebServices(): registering our AIDL callback...
,I/SundryService( 8342): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/WaitableIntentService( 8342): ServiceHandler.handleMessage: mWaitCount=0
,D/GetNotificationsWS( 8342): onServiceConnected()
D/GetNotificationsWS( 8342): onServiceConnected(): Registered for remote service callbacks...
D/GetNotificationsWS( 8342): unbindWebServices(): un-registering our AIDL callback...
,I/ActivityManager(  883): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=9239 uid=10080 gids={50080, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/art     (  883): Explicit concurrent mark sweep GC freed 26003(1416KB) AllocSpace objects, 8(3MB) LOS objects, 33% free, 21MB/31MB, paused 1.401ms total 123.710ms
,I/MusicStore( 9239): Database version: 120
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 9239): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,D/WifiP2pService(  883): InactiveState{ when=-1ms what=131222 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  883): P2pEnabledState{ when=-1ms what=131222 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  883): P2pEnabledStateupdate channel list
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
,W/Vold    (  277): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 9239): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
,W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 9239): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,W/ResourcesManager( 9239): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 9239): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 9239): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 9239): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 9239): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@3483b44b: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 9239): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 9239): GMSCore installation verified
,I/ConfigStore( 9239): Config Database version: 1
,I/MediaRouter( 9239): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 9239): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:31000 mC
,I/ActivityManager(  883): Start proc com.android.mms for broadcast com.android.mms/.transaction.MmsSystemEventReceiver: pid=9272 uid=10023 gids={50023, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/GHttpClientFactory( 9239): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 9239): Using platform SSLCertificateSocketFactory
,I/ActivityManager(  883): Killing 9084:com.google.android.apps.magazines/u0a81 (adj 15): empty #7
,V/Mms     ( 9272): mnc/mcc: 
,V/Mms     ( 9272): tag: int value: recipientLimit - 20
,V/Mms     ( 9272): tag: int value: smsToMmsTextThreshold - 6
V/Mms     ( 9272): tag: int value: emergencySmsTimeout - 30
V/Mms     ( 9272): tag: int value: maxSubjectLength - 80
V/Mms     ( 9272): tag: bool value: smsForceShowEncodingMenu - true
V/Mms     ( 9272): tag: bool value: enableGroupMms - false
V/Mms     ( 9272):  mUserAgent = MOT-XT1072/Mms-5.0,  mUaProfUrl = http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/libprocessgroup(  883): failed to open /acct/uid_10081/pid_9084/cgroup.procs: No such file or directory
,W/ResourcesManager( 9272): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/ActivityManager(  883): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=9298 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  883): Killing 9160:com.android.chrome/u0a52 (adj 15): empty #7
,W/libprocessgroup(  883): failed to open /acct/uid_10052/pid_9160/cgroup.procs: No such file or directory
,D/PhoneMonitor( 9298): Register our PhoneStateListener
,D/MobileConnectivityChangeReceiver( 9298): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 9298): onReceive CONNECTIVITY_CHANGE networkType=1
,I/ActivityManager(  883): Killing 9182:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,W/libprocessgroup(  883): failed to open /acct/uid_10090/pid_9182/cgroup.procs: No such file or directory
,I/ActivityManager(  883): Start proc com.google.android.apps.photos for broadcast com.google.android.apps.photos/.jobqueue.JobServiceBroadcastReceiver: pid=9321 uid=10088 gids={50088, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,D/TCMD    (  474): NL - Read 56 bytes from update socket.
D/TCMD    (  474): NL - message type is RTM_NEWLINK
D/TCMD    (  474): Listening for incoming client connection request
I/wpa_supplicant( 9127): CTRL_IFACE: Detach monitor /data/misc/cutback/wpa_ctrl_291-4\x00 that cannot receive messages
,E/WifiStateMachine(  883): [1,450,461,652,562 ms] noteScanEnd no scan source
,E/WifiStateMachine(  883): wifi setScanResults statecom.android.server.wifi.WifiStateMachine$DisconnectedState@1b7e2ac3 sup_state=SCANNING debouncing=false
E/WifiStateMachine(  883): WifiStateMachine shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
E/WifiConfigStore(  883):  rewrite network history for "NG700"WPA_PSK
,E/WifiStateMachine(  883): CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
E/WifiConfigStore(  883): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,E/WifiStateMachine(  883): CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,E/WifiConfigStore(  883): will read network variables netId=0
,E/WifiStateMachine(  883): CMD_AUTO_CONNECT did save config ->  nid=0
,E/WifiConfigStore(  883): will read network variables netId=0
,I/wpa_supplicant( 9127): wlan0: Trying to associate with SSID 'NG700'
D/WifiMonitor(  883): didn't find BSSID Trying to associate with SSID 'NG700'
E/wpa_supplicant( 9127): DSDS: eapol_sm_notify_config config->sim_num = 1
,E/WifiConfigStore(  883): setLastSelectedConfiguration -1
,E/wpa_supplicant( 9127): PNO: In assoc process
E/WifiStateMachine(  883): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATING -> state= CONNECTING debouncing=false
E/WifiStateMachine(  883): setDetailed state, old =SCANNING and new state=CONNECTING hidden=false
,I/SBar.MotoNetworkCtrlr( 1293): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1293): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/ActivityManager(  883): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=9342 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/ActivityManager(  883): Killing 9209:android.process.acore/u0a7 (adj 15): empty #7
,D/TCMD    (  474): NL - Read 312 bytes from update socket.
D/TCMD    (  474): NL - message type is RTM_NEWLINK
D/TCMD    (  474): Listening for incoming client connection request
D/TCMD    (  474): NL - Read 192 bytes from update socket.
D/TCMD    (  474): NL - message type is RTM_NEWLINK
D/TCMD    (  474): Listening for incoming client connection request
D/TCMD    (  474): NL - Read 68 bytes from update socket.
D/TCMD    (  474): NL - message type is RTM_NEWLINK
D/TCMD    (  474): Listening for incoming client connection request
D/TCMD    (  474): NL - Read 1004 bytes from update socket.
D/TCMD    (  474): NL - message type is RTM_NEWLINK
D/TCMD    (  474): Listening for incoming client connection request
,I/wpa_supplicant( 9127): wlan0: Associated with c0:ff:d4:d3:aa:48
,D/TCMD    (  474): NL - Read 80 bytes from update socket.
D/TCMD    (  474): NL - message type is RTM_NEWLINK
D/TCMD    (  474): Listening for incoming client connection request
D/TCMD    (  474): NL - Read 80 bytes from update socket.
D/TCMD    (  474): NL - message type is RTM_NEWLINK
D/TCMD    (  474): Listening for incoming client connection request
D/TCMD    (  474): NL - Read 68 bytes from update socket.
D/TCMD    (  474): NL - message type is RTM_NEWLINK
D/TCMD    (  474): Listening for incoming client connection request
,E/WifiStateMachine(  883): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATED -> state= CONNECTING debouncing=false
E/WifiStateMachine(  883): setDetailed state, old =CONNECTING and new state=CONNECTING hidden=false
E/WifiStateMachine(  883): setDetailed state send new extra info"NG700"
,D/Tethering(  883): exception when get active network info: java.lang.NullPointerException: Attempt to invoke virtual method 'int android.net.NetworkInfo.getType()' on a null object reference
W/Settings(  883): Setting tether_dun_apn has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/Tethering(  883): ApnList is empty for checkDunConfigured()
D/Tethering(  883):  upstream interface types: 
D/Tethering(  883):  0
D/Tethering(  883):  1
D/Tethering(  883):  5
D/Tethering(  883):  7
,W/libprocessgroup(  883): failed to open /acct/uid_10007/pid_9209/cgroup.procs: No such file or directory
,D/Tethering(  883): sendTetherStateChangedBroadcast 1, 0, 0
,E/WifiStateMachine(  883): SUPPLICANT_STATE_CHANGE_EVENT state=FOUR_WAY_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine(  883): setDetailed state, old =CONNECTING and new state=AUTHENTICATING hidden=false
,I/SBar.MotoNetworkCtrlr( 1293): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1293): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/wpa_supplicant( 9127): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
,I/wpa_supplicant( 9127): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
D/TCMD    (  474): NL - Read 1004 bytes from update socket.
D/TCMD    (  474): NL - message type is RTM_NEWLINK
D/TCMD    (  474): Listening for incoming client connection request
,I/SBar.MotoNetworkCtrlr( 1293): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1293): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,E/WifiStateMachine(  883): SUPPLICANT_STATE_CHANGE_EVENT state=GROUP_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine(  883): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING hidden=false
E/WifiStateMachine(  883): Network connection established
E/WifiStateMachine(  883): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR hidden=false
,I/SBar.MotoNetworkCtrlr( 1293): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1293): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
W/ResourcesManager( 9342): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/SBar.MotoNetworkCtrlr( 1293): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1293): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,E/WifiStateMachine(  883): setDetailed state, old =OBTAINING_IPADDR and new state=CONNECTING hidden=false
,I/SBar.MotoNetworkCtrlr( 1293): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1293): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/ConnectivityService(  883): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
E/WifiStateMachine(  883): L2ConnectedState any config "NG700"WPA_PSK config.bssid null
E/WifiStateMachine(  883): L2ConnectedState "NG700" nid=0
E/WifiConfigStore(  883): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/ConnectivityService(  883): NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,E/WifiStateMachine(  883): enter ObtainingIpState netId=0 "NG700"WPA_PSK  roam=0 static=false watchdog= 2
,E/WifiStateMachine(  883): ObtainingIpAddress any config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  883): ObtainingIpAddress "NG700" nid=0
E/WifiConfigStore(  883): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,D/CommandListener(  289): Setting iface cfg
,E/WifiStateMachine(  883): Start Dhcp Watchdog 3
,E/WifiStateMachine(  883): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
,E/WifiStateMachine(  883): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES
,E/WifiStateMachine(  883): setSuspendOptimizationsNative: 1 false -want true stack:setSuspendOptimizationsNative - handlePreDhcpSetup - processMessage - processMsg
E/native  (  883): do suspend false
,E/wpa_supplicant( 9127): wpa_driver_nl80211_driver_cmd: failed to issue private commands
,E/WifiStateMachine(  883): Unexpected BatchedScanResults :null
E/wpa_supplicant( 9127): wpa_driver_nl80211_driver_cmd: failed to issue private commands
,D/WifiP2pService(  883): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@32abe53e target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  883): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@32abe53e target=com.android.internal.util.StateMachine$SmHandler }
,I/Babel_SMS( 9342): MmsConfig: mnc/mcc: 0/0
,I/Babel_SMS( 9342): MmsConfig.loadMmsSettings
I/Babel_SMS( 9342): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
I/Babel_SMS( 9342): MmsConfig.loadFromDatabase
,E/Babel_SMS( 9342): canonicalizeMccMnc: invalid mccmnc 
,I/Babel_SMS( 9342): MmsConfig.loadFromResources
,E/Babel_SMS( 9342): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 9342): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/Settings( 9342): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 9342): startup - clean
,E/DHCPCD  ( 9378): fopen `/system/etc/dhcpcd/dhcpcd.conf': m
,I/Babel   ( 9342): deleted: false for 0
,I/DHCPCD  ( 9378): version 5.5.6 starting
,E/DHCPCD  ( 9378): fopen `/system/etc/dhcpcd/dhcpcd.conf': m
D/DHCPCD  ( 9378): wlan0: using ClientID 01:44:80:eb:7b:5a:06
D/DHCPCD  ( 9378): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
,I/ActivityManager(  883): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=9387 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/DHCPCD  ( 9378): wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
,I/DHCPCD  ( 9378): wlan0: rebinding lease of 192.168.1.123
D/DHCPCD  ( 9378): wlan0: sending REQUEST (xid 0x45ba78fb), next in 3.85 seconds
,W/VideoCapabilities( 9342): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 9342): Unsupported mime audio/amr-wb-plus
,W/VideoCapabilities( 9342): Unsupported mime video/mpeg2
,I/VideoCapabilities( 9342): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 9342): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 9342): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 9342): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 9342): Unrecognized profile 2130706433 for video/avc
,I/vclib   ( 9342): onServiceConnected
W/Babel   ( 9342): Attempted to change video mute state without an active call.
,I/Babel   ( 9342): connection state changed from UNKNOWN to DISCONNECTED
,I/ActivityManager(  883): Killing 9239:com.google.android.music:main/u0a80 (adj 15): empty #7
,W/libprocessgroup(  883): failed to open /acct/uid_10080/pid_9239/cgroup.procs: No such file or directory
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 9387): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
,W/Vold    (  277): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 9387): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,I/GAv4    ( 9387): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 9387):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 9387):   adb logcat -s GAv4
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 9387): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
,W/Vold    (  277): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 9387): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,W/GAv4    ( 9387): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 9387): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 9387): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/WebViewFactory( 9387): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 9387): Time to load native libraries: 1 ms (timestamps 8746-8747)
,I/LibraryLoader( 9387): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 9387): Binding Chromium to main looper Looper (main, tid 1) {1f654a12}
I/LibraryLoader( 9387): Expected native library version number "",actual native library version number ""
,I/chromium( 9387): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 9387): Initializing chromium process, singleProcess=true
,W/art     ( 9387): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 9387): ApplicationContext is null in ApplicationStatus
,W/chromium( 9387): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 9387): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,E/libEGL  ( 9387): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 9387): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 9387): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 9387): Build Date: 10/28/14 Tue
I/Adreno-EGL( 9387): Local Branch: 
I/Adreno-EGL( 9387): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 9387): Local Patches: NONE
I/Adreno-EGL( 9387): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,W/AudioManagerAndroid( 9387): Requires BLUETOOTH permission
,I/NSApplication( 9387): Starting up...
,I/ActivityManager(  883): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=9454 uid=10052 gids={50052, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  883): Killing 9272:com.android.mms/u0a23 (adj 15): empty #7
,I/art     (  307): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 252us total 25.463ms
,I/art     (  307): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 246us total 20.283ms
,I/art     (  307): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 245us total 28.154ms
,W/libprocessgroup(  883): failed to open /acct/uid_10023/pid_9272/cgroup.procs: No such file or directory
,I/ActivityManager(  883): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=9477 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  883): Killing 9298:com.google.android.setupwizard/u0a35 (adj 15): empty #7
,I/ActivityManager(  883): Waited long enough for: ServiceRecord{2b81cb4b u0 com.motorola.context/.publisher.bluetoothdeterminer.BluetoothContextService}
,W/libprocessgroup(  883): failed to open /acct/uid_10035/pid_9298/cgroup.procs: No such file or directory
,W/ResourcesManager( 9477): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/ActivityManager(  883): Start proc android.process.acore for content provider com.android.providers.contacts/.ContactsProvider2: pid=9501 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,I/ActivityManager(  883): Killing 9342:com.google.android.talk/u0a70 (adj 15): empty #7
,I/ContactLocale( 9501): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,W/libprocessgroup(  883): failed to open /acct/uid_10070/pid_9342/cgroup.procs: No such file or directory
,V/AlarmManager(  883): done {709fa5, *walarm*:com.google.android.intent.action.GCM_RECONNECT} [4859ms]
,I/ActivityManager(  883): Start proc com.google.android.deskclock for broadcast com.google.android.deskclock/com.android.alarmclock.DigitalAppWidgetProvider: pid=9534 uid=10055 gids={50055, 9997, 3003, 1028} abi=armeabi-v7a
,I/ActivityManager(  883): Killing 9387:com.google.android.apps.magazines/u0a81 (adj 15): empty #7
,W/libprocessgroup(  883): failed to open /acct/uid_10081/pid_9387/cgroup.procs: No such file or directory
,I/GAv4    ( 9534): Google Analytics 4.5.0/7324 is starting up. To enable debug logging on a device run:
I/GAv4    ( 9534):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 9534):   adb logcat -s GAv4
,W/GAv4    ( 9534): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 9534): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 9534): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,V/AlarmManager(  883): done {3fe1073, *alarm*:com.android.deskclock.ON_QUARTER_HOUR} [5261ms]
I/ActivityManager(  883): Killing 6487:com.google.android.gms/u0a16 (adj 15): empty #7
,D/WifiService(  883): Client connection lost with reason: 4
,W/libprocessgroup(  883): failed to open /acct/uid_10016/pid_6487/cgroup.procs: No such file or directory
,I/art     (  883): Explicit concurrent mark sweep GC freed 24018(1194KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 21MB/31MB, paused 1.519ms total 117.076ms
,I/ActivityManager(  883): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver: pid=9564 uid=10039 gids={50039, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
,D/BluetoothManagerService(  883): Message: 20
,D/BluetoothManagerService(  883): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@330a36a0:true
,I/BTConnectionReceiver( 9564): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:34:8A:A0, alias=null, name=S5-1, majorDeviceClass=512, deviceClass=524]
,I/ActivityManager(  883): Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=9586 uid=10019 gids={50019, 9997, 3003} abi=armeabi-v7a
,I/BluetoothClassifier( 9564): Bluetooth Device Name: S5-1
,I/ActivityManager(  883): Killing 9477:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,I/ActivityManager(  883): Killing 9454:com.android.chrome/u0a52 (adj 15): empty #8
,W/libprocessgroup(  883): failed to open /acct/uid_10052/pid_9454/cgroup.procs: No such file or directory
,W/libprocessgroup(  883): failed to open /acct/uid_10090/pid_9477/cgroup.procs: No such file or directory
,I/ActivityManager(  883): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=9624 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,W/ResourcesManager( 9624): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/Babel_SMS( 9624): MmsConfig: mnc/mcc: 0/0
,I/Babel_SMS( 9624): MmsConfig.loadMmsSettings
I/Babel_SMS( 9624): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
I/Babel_SMS( 9624): MmsConfig.loadFromDatabase
,I/DHCPCD  ( 9378): wlan0: acknowledged 192.168.1.123 from 192.168.1.1
,I/DHCPCD  ( 9378): wlan0: leased 192.168.1.123 for 86400 seconds
D/DHCPCD  ( 9378): wlan0: adding IP address 192.168.1.123/24
D/TCMD    (  474): NL - Read 60 bytes from update socket.
D/DHCPCD  ( 9378): wlan0: adding route to 192.168.1.0/24
D/TCMD    (  474): NL - ignore NL message, type = 20
D/TCMD    (  474): Listening for incoming client connection request
D/DHCPCD  ( 9378): wlan0: adding default route via 192.168.1.1
D/DHCPCD  ( 9378): wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
D/DHCPCD  ( 9378): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
,E/WifiStateMachine(  883): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
,E/WifiStateMachine(  883): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES v4
,E/Babel_SMS( 9624): canonicalizeMccMnc: invalid mccmnc 
,I/Babel_SMS( 9624): MmsConfig.loadFromResources
E/Babel_SMS( 9624): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel_SMS( 9624): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,I/MDMCTBK (  291): NetlinkHandler, subsys is net and action is remove
I/MDMCTBK (  291): NetlinkHandler, interfaceRemoved
I/MDMCTBK (  291): MdmCutbackHndler,interfaceRemoved+
I/MDMCTBK (  291): checkDefaultInst, current pid is = 291
I/MDMCTBK (  291): checkDefaultInst, pid match
I/MDMCTBK (  291): MdmCutbackHndler,interfaceRemoved+,wlan interface removed
E/MDMCTBK (  291): MdmCutbackHndler,interfaceRemoved, Mifi Status =0, Wifi Status = 0, SolReq=0
I/MDMCTBK (  291): MdmCutbackHndler,interfaceRemoved, calling setWifiCutback
I/MDMCTBK (  291): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=0, mf=0, wfd=0
I/MDMCTBK (  291): set_property_value, Enter
I/MDMCTBK (  291): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  291): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  291): set_property_value, Exit
I/MDMCTBK (  291): MdmCutbackHndler, setWifiCutback, No Wifi
I/MDMCTBK (  291): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=0, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  291): set_property_value, Enter
I/MDMCTBK (  291): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
,I/MDMCTBK (  291): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  291): set_property_value, Exit
E/MDMCTBK (  291): MdmCutbackHndler,Airplane Mode Enabled !! =1
,W/Settings( 9624): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/Babel_Crash( 9624): startup - clean
,I/Babel   ( 9624): deleted: false for 0
,W/VideoCapabilities( 9624): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 9624): Unsupported mime audio/amr-wb-plus
,W/VideoCapabilities( 9624): Unsupported mime video/mpeg2
,I/VideoCapabilities( 9624): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 9624): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 9624): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 9624): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 9624): Unrecognized profile 2130706433 for video/avc
,I/ActivityManager(  883): Killing 9501:android.process.acore/u0a7 (adj 15): empty #7
,E/WifiStateMachine(  883): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
,E/WifiStateMachine(  883): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
,E/native  (  883): do suspend true
,W/libprocessgroup(  883): failed to open /acct/uid_10007/pid_9501/cgroup.procs: No such file or directory
,I/vclib   ( 9624): onServiceConnected
,W/Babel   ( 9624): Attempted to change video mute state without an active call.
,D/WifiP2pService(  883): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  883): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,E/WifiStateMachine(  883): WifiStateMachine DHCP successful
E/WifiStateMachine(  883): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,E/WifiStateMachine(  883): updateLinkProperties nid: 0 state: CONNECTING reason: DHCP_SUCCESS v4 v4r v4dns isprov
,E/WifiStateMachine(  883): Calling ARP set with IP = 192.168.1.123
,E/WifiStateMachine(  883): setDetailed state, old =CONNECTING and new state=CAPTIVE_PORTAL_CHECK hidden=false
,I/SBar.MotoNetworkCtrlr( 1293): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1293): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1293): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1293): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
E/WifiStateMachine(  883): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED hidden=false
D/ConnectivityService(  883): NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
D/ConnectivityService(  883): Adding iface wlan0 to network 102
,I/SBar.MotoNetworkCtrlr( 1293): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1293): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1293): refreshSignalCluster[0]: wifi: mWifiConnected=true Wifi=0x7f020129=com.android.systemui:drawable/stat_sys_wifi_signal_0 Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
,D/Checkin (  883): publish the event [tag = MOT_WIFI_L1 event name = CONNECT]
E/WifiStateMachine(  883): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
D/Checkin (  883): publish the event [tag = MOT_WIFI_L1 event name = CONNECT]
,I/SBar.MotoNetworkCtrlr( 1293): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1293): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,E/ConnectivityService(  883): Unexpected mtu value: 0, wlan0
,D/ConnectivityService(  883): Adding Route [fe80::/64 -> :: wlan0] to network 102
,E/WifiStateMachine(  883): ConnectedState Enter  mScreenOn=false scanperiod=20000
,D/ConnectivityService(  883): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
D/ConnectivityService(  883): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
,D/ConnectivityService(  883): Setting Dns servers for network 102 to [/192.168.1.1]
,D/Nat464Xlat(  883): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  883): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
D/ConnectivityService(  883): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
D/ConnectivityService(  883): rematching NetworkAgentInfo [WIFI () - 102]
D/ConnectivityService(  883):    accepting network in place of null
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  883): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  883): Connected
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  883): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  883): Checking http://clients3.google.com/generate_204 on "NG700"
D/ConnectivityService(  883): UpdateTcpBufferSizes: same sizes as current, ignore operation
,D/CSLegacyTypeTracker(  883): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
,D/ConnectivityService(  883): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  883): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
,D/ConnectivityService(  883): UpdateTcpBufferSizes: same sizes as current, ignore operation
D/ConnectivityService(  883): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 102]
,I/SBar.MotoNetworkCtrlr( 1293): onReceive: CONNECTIVITY_ACTION_IMMEDIATE Recieved, mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/ModemStatsDSDetect( 1537): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
D/ConnectivityManager.CallbackHandler( 1293): CM callback handler got msg 524290
I/ModemStatsDSDetect( 1537): INET_CONDITION=0 ,activeNet=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/ModemStatsDSDetect( 1537): onReceive() - done, currentInetCondition=0
I/SBar.MotoNetworkCtrlr( 1293): updateConnectivity[0]: NetworkInfo: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false], raw inetCondition= 0
I/SBar.MotoNetworkCtrlr( 1293): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1293): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1293): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/ConnectivityService(  883): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 101] cleared because we found a replacement network
,E/WifiStateMachine(  883): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,fe80::4680:ebff:fe7b:5a06/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,D/ConnectivityService(  883): UpdateTcpBufferSizes: same sizes as current, ignore operation
,D/Nat464Xlat(  883): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  883): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,D/ConnectivityManager.CallbackHandler( 1293): CM callback handler got msg 524295
,E/WifiStateMachine(  883): updateLinkProperties nid: 0 state: CONNECTED reason: CMD_UPDATE_LINKPROPERTIES v4 v4r v4dns isprov
,D/BatteryService(  883): uevent={POWER_SUPPLY_TEMP=286, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4310416, SEQNUM=4682, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=3734, POWER_SUPPLY_CHARGE_COUNTER=35, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2530): Disconnected process message: 10, size: 0
,D/ConnectivityService(  883): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  883): MasterInitialState.processMessage what=3
,D/Central_PollingManager( 1478): connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
W/ContextImpl( 1478): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1469 android.content.ContextWrapper.sendBroadcast:381 com.motorola.blur.service.blur.BSUtils.sendBroadcast:94 com.motorola.blur.service.blur.BSUtils.sendBroadcast:90 com.motorola.ccc.plm.pollingmanager.PollingManagerService$MyConnectivityReceiver.onReceive:491 
,D/PollingManager( 8342): connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/PollingManager( 8342): now: 624407 ,futureTime: 9223372036854775807
D/OtaApp  ( 8342): [debug] > pollingManagerService, connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ActivityManager(  883): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=9701 uid=10080 gids={50080, 9997, 3003, 1028, 1015} abi=armeabi-v7a
D/Central_PollingManager( 1478): now: 624456 ,futureTime: 86791802
D/Central_PollingManager( 1478): Polling alarm set to expire at: 86791802 Current Time: 624456
D/OtaApp  ( 8342): [debug] > PollingManagerService, now: 624456 ,futureTime: 62410079
D/OtaApp  ( 8342): [debug] > Polling alarm set to expire at: 62410079 Current Time: 624457
,D/PollingManager( 8342): connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/PollingManager( 8342): now: 624462 ,futureTime: 9223372036854775807
,D/MMApiProvisionService( 8342): isDeviceProvisioned: deviceId = 2072049230914535424
,D/CCE     ( 8342): trying to auto login since I haven't yet and the radio is up now
I/MMApiProvisionService( 8342): createDeviceIdOrLogin update_device
,D/Checkin ( 8342): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiProvisionService( 8342): Not proxy app, so login/provision not allowed
,D/MMApiProvisionService( 8342): isDeviceProvisioned: deviceId = 2072049230914535424
,D/CCE     ( 8342): trying to auto login since I haven't yet and the radio is up now
I/MMApiProvisionService( 8342): createDeviceIdOrLogin update_device
,D/Checkin ( 8342): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiProvisionService( 8342): Not proxy app, so login/provision not allowed
,D/OtaApp  ( 8342): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.ccc.ota.pm.POLLINGMGR_CONNECTIVITY
D/OtaApp  ( 8342): [debug] > CusSM.onRadioUp
,D/OtaApp  ( 8342): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
D/OtaApp  ( 8342): [debug] > CusSM.runStateMachine: getVersions's version Blur_Version.22.21.28.thea_reteu.reteuall.en.EU; getDescription's versionBlur_Version.22.21.28.thea_reteu.reteuall.en.EU
I/OtaApp  ( 8342): [info] > CusSM.runStateMachine: found version Blur_Version.22.21.28.thea_reteu.reteuall.en.EU in database with state (RequestPermission)
D/Checkin ( 8342): publish the event [tag = MOT_OTA event name = LOG]
D/OtaApp  ( 8342): [debug] > CusSM.runStateMachine: server told to :continue
,D/OtaApp  ( 8342): [debug] > CusSM.runStateMachine: user is being notified for version Blur_Version.22.21.28.thea_reteu.reteuall.en.EU
D/OtaApp  ( 8342): [debug] > CusSM.runStateMachine: getDownloadOptStartStopTime text null
D/OtaApp  ( 8342): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,I/MusicStore( 9701): Database version: 120
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 9701): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 9701): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
,W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 9701): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,W/ResourcesManager( 9701): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 9701): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 9701): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 9701): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 9701): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@3483b44b: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 9701): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 9701): GMSCore installation verified
,I/ConfigStore( 9701): Config Database version: 1
,I/MediaRouter( 9701): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 9701): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/NetworkMonitor( 9701): type=WIFI subType= reason=null isConnected=true
,I/NetworkMonitor( 9701): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  883): Start proc com.android.mms for broadcast com.android.mms/.transaction.MmsSystemEventReceiver: pid=9747 uid=10023 gids={50023, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/GHttpClientFactory( 9701): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 9701): Using platform SSLCertificateSocketFactory
,I/ActivityManager(  883): Start proc com.google.android.gms for service com.google.android.gms/.ads.identifier.service.AdvertisingIdService: pid=9765 uid=10016 gids={50016, 9997, 3003, 1028, 1015, 3002, 3001, 1005, 1007, 3007, 2001, 3006} abi=armeabi-v7a
,I/ActivityManager(  883): Killing 9534:com.google.android.deskclock/u0a55 (adj 15): empty #7
,W/ResourcesManager( 9765): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 9765): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/Mms     ( 9747): mnc/mcc: 
,V/Mms     ( 9747): tag: int value: recipientLimit - 20
,V/Mms     ( 9747): tag: int value: smsToMmsTextThreshold - 6
V/Mms     ( 9747): tag: int value: emergencySmsTimeout - 30
V/Mms     ( 9747): tag: int value: maxSubjectLength - 80
V/Mms     ( 9747): tag: bool value: smsForceShowEncodingMenu - true
V/Mms     ( 9747): tag: bool value: enableGroupMms - false
V/Mms     ( 9747):  mUserAgent = MOT-XT1072/Mms-5.0,  mUaProfUrl = http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,I/MultiDex( 9765): VM with version 2.1.0 has multidex support
I/MultiDex( 9765): install
I/MultiDex( 9765): VM has multidex support, MultiDex support library is disabled.
,W/libprocessgroup(  883): failed to open /acct/uid_10055/pid_9534/cgroup.procs: No such file or directory
,W/ResourcesManager( 9747): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/art     (  883): Explicit concurrent mark sweep GC freed 19039(972KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 21MB/31MB, paused 2.133ms total 118.415ms
,I/ActivityManager(  883): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=9792 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,V/JNIHelp ( 9765): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,D/PhoneMonitor( 9792): Register our PhoneStateListener
,D/MobileConnectivityChangeReceiver( 9792): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 9792): onReceive CONNECTIVITY_CHANGE networkType=1
,I/ActivityManager(  883): Killing 9564:com.google.android.googlequicksearchbox:search/u0a39 (adj 15): empty #7
,W/ActivityThread( 9765): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 9765): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@3b895236: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 9765): Installed default security provider GmsCore_OpenSSL
,W/libprocessgroup(  883): failed to open /acct/uid_10039/pid_9564/cgroup.procs: No such file or directory
,I/ActivityManager(  883): Killing 9586:com.google.android.partnersetup/u0a19 (adj 15): empty #7
,D/NativeLibraryUtils( 9765): Install completed successfully. count=14 extracted=0
,W/libprocessgroup(  883): failed to open /acct/uid_10019/pid_9586/cgroup.procs: No such file or directory
,I/CheckinService( 9765): Checkin interval check for package: unspecified last checkin: 1450461287339 min interval config: 0 actual interval: 373364
,I/art     ( 6449): Explicit concurrent mark sweep GC freed 1616(56KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 7MB/9MB, paused 404us total 26.860ms
,I/CheckinService( 9765): Disabling old GoogleServicesFramework version
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  883): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 18 Dec 2015 18:00:58 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1450461660762], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1450461657763]}
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  883): Don't send network conditions - lacking user consent.
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  883): Validated
,D/ConnectivityService(  883): Validated NetworkAgentInfo [WIFI () - 102]
,D/ConnectivityService(  883): rematching NetworkAgentInfo [WIFI () - 102]
D/ConnectivityService(  883): Network NetworkAgentInfo [WIFI () - 102] was already satisfying request 1. No change.
D/ConnectivityService(  883): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 102]
D/ConnectivityService(  883): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/ConnectivityManager.CallbackHandler( 1293): CM callback handler got msg 524290
,I/SBar.MotoNetworkCtrlr( 1293): onReceive: INET_CONDITION_ACTION Recieved, mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1293): updateConnectivity: The netConditon[0] for netType 1=WiFi is updated as 1=good by android.net.conn.INET_CONDITION_ACTION, icon color should be white (on KK); without "!" (on L).
I/SBar.MotoNetworkCtrlr( 1293): updateConnectivity[0]: NetworkInfo: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false], raw inetCondition= 1
I/SBar.MotoNetworkCtrlr( 1293): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1293): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1293): refreshSignalCluster[0]: wifi: mWifiConnected=true Wifi=0x7f02012a=com.android.systemui:drawable/stat_sys_wifi_signal_0_fully Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
I/SBar.MotoNetworkCtrlr( 1293): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/ModemStatsDSDetect( 1537): onReceive() -Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) }
,I/ModemStatsDSDetect( 1537): INET_CONDITION=100 ,activeNet=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ModemStatsDSDetect( 1537): Inetcondition changed, white->blue
,I/ModemStatsDSDetect( 1537): onReceive() - done, currentInetCondition=100
,I/CheckinService( 9765): Checking schedule, now: 1450461660795 next: 1450461317316
,I/CheckinService( 9765): active receiver: enabled
,I/iu.SyncManager( 9765): SYNC; picasa accounts
,D/NetworkLogImpl( 9765): Loaded NetworkSpeedPredictor
,I/CheckinService( 9765): Preparing to send checkin request
,I/iu.Environment( 9765): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/EventLogService( 9765): Accumulating logs since 1450461284190
,I/iu.UploadsManager( 9765): num queued entries: 0
,I/iu.UploadsManager( 9765): num updated entries: 0
I/iu.SyncManager( 9765): NEXT; no task
,I/art     ( 9765): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 9765): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,I/ActivityManager(  883): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=9831 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/art     (  307): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 245us total 20.231ms
,I/art     (  307): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 258us total 20.108ms
,I/art     (  307): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 255us total 20.258ms
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 9831): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
,W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 9831): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
I/GAv4    ( 9831): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 9831):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 9831):   adb logcat -s GAv4
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 9831): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
W/GAv4    ( 9831): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 9831): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,W/GAv4    ( 9831): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 9831): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/CheckinRequestBuilder( 9765): Checkin reason type: 8 attempt count: 1
,D/WifiService(  883): New client listening to asynchronous messages
,E/ActivityThread( 9765): Failed to find provider info for com.google.android.wearable.settings
,V/GLSActivity( 1740): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1740): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  883): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=9878 uid=10016 gids={50016, 9997, 3003, 1028, 1015, 3002, 3001, 1005, 1007, 3007, 2001, 3006} abi=armeabi-v7a
,I/WebViewFactory( 9831): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 9831): Time to load native libraries: 6 ms (timestamps 6354-6360)
I/LibraryLoader( 9831): Expected native library version number "",actual native library version number ""
W/ResourcesManager( 9878): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 9878): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/WebViewChromiumFactoryProvider( 9831): Binding Chromium to main looper Looper (main, tid 1) {265a4be0}
,I/LibraryLoader( 9831): Expected native library version number "",actual native library version number ""
,I/chromium( 9831): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 9831): Initializing chromium process, singleProcess=true
,W/art     ( 9831): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 9831): ApplicationContext is null in ApplicationStatus
,W/chromium( 9831): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,I/MultiDex( 9878): VM with version 2.1.0 has multidex support
,I/MultiDex( 9878): install
I/MultiDex( 9878): VM has multidex support, MultiDex support library is disabled.
,E/libEGL  ( 9831): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,E/libEGL  ( 9831): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 9831): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 9831): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 9831): Build Date: 10/28/14 Tue
I/Adreno-EGL( 9831): Local Branch: 
I/Adreno-EGL( 9831): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 9831): Local Patches: NONE
I/Adreno-EGL( 9831): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,V/JNIHelp ( 9878): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/AudioManagerAndroid( 9831): Requires BLUETOOTH permission
,I/NSApplication( 9831): Starting up...
,W/ActivityThread( 9878): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 9878): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@38bd6b0: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 9878): Installed default security provider GmsCore_OpenSSL
,I/ActivityManager(  883): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=9915 uid=10052 gids={50052, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/art     ( 9878): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 9878): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,I/ActivityManager(  883): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=9935 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  883): Killing 9701:com.google.android.music:main/u0a80 (adj 15): empty #7
,D/NativeLibraryUtils( 9878): Install completed successfully. count=14 extracted=0
,W/libprocessgroup(  883): failed to open /acct/uid_10080/pid_9701/cgroup.procs: No such file or directory
,I/Babel   ( 9624): connection state changed from UNKNOWN to CONNECTED
,I/ActivityManager(  883): Killing 9747:com.android.mms/u0a23 (adj 15): empty #7
,D/WVCdm   (  294): Instantiating CDM.
I/WVCdm   (  294): CdmEngine::OpenSession
I/WVCdm   (  294): Level3 Library Sep 25 2014 17:10:03
W/WVCdm   (  294): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,W/ResourcesManager( 9935): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/DrmWidevineDash(  294): OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x13
,D/DrmWidevineDash(  294): Service_Initialize: starts!
,D/QSEECOMAPI: (  294): QSEECom_get_handle sb_length = 0x19000
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
,D/DrmWidevineDash(  294): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4fa3000
E/DrmWidevineDash(  294): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4fa3000
,D/DrmWidevineDash(  294): OEMCrypto_Initialize: ends! returns 0
,D/DrmWidevineDash(  294): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  294): hlos api version =  9
D/DrmWidevineDash(  294): tz api version =  8
D/DrmWidevineDash(  294): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  294): OEMCrypto_IsKeyboxValid: starts!
,D/DrmWidevineDash(  294): OEMCrypto_IsKeyboxValid: ends! returns 0
,D/WVCdm   (  294): OEMCrypto_Initialize Level 1 success. I will use level 1.
,D/DrmWidevineDash(  294): OEMCrypto_OpenSession: starts! SID=0xb136e960
,D/DrmWidevineDash(  294): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  294): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  294): OEMCrypto_GetRandom: starts! randomData=0xb8e71d68, dataLength=8
D/DrmWidevineDash(  294): OEMCrypto_GetRandom: ends! returns 0
D/DrmWidevineDash(  294): OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb8e773c0, wrapped_rsa_key_length=1280
D/DrmWidevineDash(  294): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
I/WVCdm   (  294): CdmEngine::QueryKeyControlInfo
W/WVCdm   (  294): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  294): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  294): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  294): OEMCrypto_GetDeviceID: starts! deviceID=0xb8f5df20, idLength=0xb126e730
,W/libprocessgroup(  883): failed to open /acct/uid_10023/pid_9747/cgroup.procs: No such file or directory
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
D/WVCdm   (  294): PrepareKeyRequest: nonce=2275599494
D/DrmWidevineDash(  294): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb8e6d570
D/DrmWidevineDash(  294): message_length=1591, signature=0xb8e6dbb0, signature_length=2972116756
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:32000 mC
,D/DrmWidevineDash(  294): OEMCrypto_GenerateRSASignature returns 0
I/WVCdm   (  294): CdmEngine::CloseSession
D/DrmWidevineDash(  294): OEMCrypto_CloseSession: starts! SID=1
D/DrmWidevineDash(  294): OEMCrypto_CloseSession: ends! returns 0
I/WVCdm   (  294): L3 Terminate.
D/DrmWidevineDash(  294): OEMCrypto_Terminate: starts!
D/DrmWidevineDash(  294): Service_Uninitialize: starts!
D/QSEECOMAPI: (  294): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  294): QSEECom_shutdown_app, app_id = 3
D/DrmWidevineDash(  294): Service_Uninitialize: ends! returns 0x0
D/DrmWidevineDash(  294): OEMCrypto_Terminate: ends! returns 0
,I/ActivityManager(  883): Start proc android.process.acore for content provider com.android.providers.contacts/.ContactsProvider2: pid=9962 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,I/ActivityManager(  883): Killing 9321:com.google.android.apps.photos/u0a88 (adj 15): empty #7
,I/ContactLocale( 9962): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,I/ActivityManager(  883): Killing 9792:com.google.android.setupwizard/u0a35 (adj 15): empty #8
,W/libprocessgroup(  883): failed to open /acct/uid_10088/pid_9321/cgroup.procs: No such file or directory
D/EmailService.MarketingOptInSetter( 8342): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,W/libprocessgroup(  883): failed to open /acct/uid_10035/pid_9792/cgroup.procs: No such file or directory
,D/GetNotificationsWS( 8342): bindWebServices(): registering our AIDL callback...
I/SundryService( 8342): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
E/SQLiteLog( 8342): (284) automatic index on registration(APP_ID)
D/WaitableIntentService( 8342): ServiceHandler.handleMessage: mWaitCount=0
D/GetNotificationsWS( 8342): onServiceConnected()
,D/GetNotificationsWS( 8342): onServiceConnected(): Registered for remote service callbacks...
,D/GetNotificationsWS( 8342): unbindWebServices(): un-registering our AIDL callback...
,D/OtaApp  ( 8342): [debug] > Receive intent: com.motorola.blur.service.blur.Actions.UPGRADE_UPDATE_NOTIFICATION
,I/PushService( 8342): started with background data enabled, making sure notification mechanism is enabled
,D/OtaApp  ( 8342): [debug] > UpdateReceiver: Received true from doSanityCheck.
D/OtaApp  ( 8342): [debug] > In cancelAnyPendingIntentSetPreviously
,I/ActivityManager(  883): START u0 {act=com.motorola.blur.service.blur.Actions.UPGRADE_UPDATE_NOTIFICATION flg=0x30000000 cmp=com.motorola.ccc.ota/.ui.DownloadActivity (has extras)} from uid 10000 on display 0
,W/ContextImpl( 1478): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,W/ContextImpl( 1478): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,D/OtaApp  ( 8342): [debug] > DownloadActivity, FormattedText
,I/OtaApp  ( 8342): [info] > DownloadActivity, handling (Blur_Version.22.46.12.thea_reteu.reteuall.en.EU) from ( upgrade)
,D/Checkin ( 8342): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 8342): [debug] > cancelling the previous pending intent set for download later
,I/OtaApp  ( 8342): [info] > next automatic download prompt (serverAnnoy)  is scheduled in : 60 mins.
,D/Checkin ( 8342): publish the event [tag = MOT_OTA event name = LOG]
,D/WearableService( 1740): callingUid 10016, callindPid: 1740
,E/MDM     ( 1740): [168] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/OtaApp  ( 8342): [debug] > DownloadActivity, FormattedText
I/OtaApp  ( 8342): [info] > DownloadActivity, handling (Blur_Version.22.46.12.thea_reteu.reteuall.en.EU) from ( upgrade)
,D/Checkin ( 8342): publish the event [tag = MOT_OTA event name = LOG]
,D/LocationInitializer( 9765): Restart initialization of location
,D/OtaApp  ( 8342): [debug] > cancelling the previous pending intent set for download later
,I/OtaApp  ( 8342): [info] > next automatic download prompt (serverAnnoy)  is scheduled in : 60 mins.
D/Checkin ( 8342): publish the event [tag = MOT_OTA event name = LOG]
,D/AuthorizationBluetoothService( 1740): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,V/GLSActivity( 1740): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  883): Start proc com.google.android.apps.photos for broadcast com.google.android.apps.photos/.jobqueue.JobServiceBroadcastReceiverInternal: pid=9998 uid=10088 gids={50088, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,W/GCoreFlp( 1740): No location to return for getLastLocation()
,W/FusedLocationProvider( 1740): location=null
,I/dex2oat (10021): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=28 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,I/dex2oat (10021): dex2oat took 70.501ms (threads: 4)
,I/Adreno-EGL( 9878): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 9878): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 9878): Build Date: 10/28/14 Tue
I/Adreno-EGL( 9878): Local Branch: 
I/Adreno-EGL( 9878): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 9878): Local Patches: NONE
I/Adreno-EGL( 9878): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/art     (  883): Explicit concurrent mark sweep GC freed 13011(634KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 21MB/31MB, paused 2.004ms total 128.468ms
,W/IcingInternalCorpora( 9765): getNumBytesRead when not calculated.
,I/Adreno-EGL( 9878): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 9878): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 9878): Build Date: 10/28/14 Tue
I/Adreno-EGL( 9878): Local Branch: 
I/Adreno-EGL( 9878): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 9878): Local Patches: NONE
I/Adreno-EGL( 9878): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,E/MDM     ( 1740): [178] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/AuthorizationBluetoothService( 1740): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,D/LocationInitializer( 9765): Restart initialization of location
,V/GLSActivity( 1740): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GCoreFlp( 1740): No location to return for getLastLocation()
,W/FusedLocationProvider( 1740): location=null
,I/WVCdm   (  294): CdmEngine::OpenSession
I/WVCdm   (  294): Level3 Library Sep 25 2014 17:10:03
W/WVCdm   (  294): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,I/ActivityManager(  883): Killing 9624:com.google.android.talk/u0a70 (adj 15): empty #7
,D/DrmWidevineDash(  294): OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x13
D/DrmWidevineDash(  294): Service_Initialize: starts!
D/QSEECOMAPI: (  294): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  294): App is not loaded in QSEE
E/QSEECOMAPI: (  294): Error::Cannot open the file /vendor/firmware/widevine.mdt
E/QSEECOMAPI: (  294): Error::Loading image failed with ret = -1
,D/QSEECOMAPI: (  294): QSEECom_get_handle sb_length = 0x19000
,D/QSEECOMAPI: (  294): App is not loaded in QSEE
E/QSEECOMAPI: (  294): Error::Cannot open the file /system/etc/firmware/widevine.mdt
E/QSEECOMAPI: (  294): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  294): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  294): App is not loaded in QSEE
,D/QSEECOMAPI: (  294): Loaded image: APP id = 3
,D/DrmWidevineDash(  294): Service_Initialize: ends! returns 0
D/DrmWidevineDash(  294): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4fa3000
E/DrmWidevineDash(  294): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4fa3000
,D/DrmWidevineDash(  294): OEMCrypto_Initialize: ends! returns 0
,D/DrmWidevineDash(  294): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  294): hlos api version =  9
D/DrmWidevineDash(  294): tz api version =  8
D/DrmWidevineDash(  294): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  294): OEMCrypto_IsKeyboxValid: starts!
,D/DrmWidevineDash(  294): OEMCrypto_IsKeyboxValid: ends! returns 0
,D/WVCdm   (  294): OEMCrypto_Initialize Level 1 success. I will use level 1.
,D/DrmWidevineDash(  294): OEMCrypto_OpenSession: starts! SID=0xb136e960
,D/DrmWidevineDash(  294): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  294): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  294): OEMCrypto_GetRandom: starts! randomData=0xb8f3b648, dataLength=8
D/DrmWidevineDash(  294): OEMCrypto_GetRandom: ends! returns 0
D/DrmWidevineDash(  294): OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb8e773c0, wrapped_rsa_key_length=1280
D/DrmWidevineDash(  294): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
I/WVCdm   (  294): CdmEngine::QueryKeyControlInfo
W/WVCdm   (  294): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  294): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
,I/WVCdm   (  294): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  294): OEMCrypto_GetDeviceID: starts! deviceID=0xb8f5df60, idLength=0xb557e730
,D/DrmWidevineDash(  294): OEMCrypto_GetDeviceID: ends! returns 0
,D/DrmWidevineDash(  294): OEMCrypto_SupportsUsageTable: starts!
D/DrmWidevineDash(  294): OEMCrypto_SupportsUsageTable: is_supported = 1
D/DrmWidevineDash(  294): OEMCrypto_SupportsUsageTable: wv_app_version = 25
D/DrmWidevineDash(  294): OEMCrypto_SupportsUsageTable: ends! returns 0x0
D/DrmWidevineDash(  294): OEMCrypto_GetHDCPCapability: starts!
D/DrmWidevineDash(  294): OEMCrypto_GetHDCPCapability: ends! returns 0x0
D/DrmWidevineDash(  294): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  294): hlos api version =  9
D/DrmWidevineDash(  294): tz api version =  8
,D/DrmWidevineDash(  294): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  294): OEMCrypto_GenerateNonce: starts! SID=1
D/DrmWidevineDash(  294): OEMCrypto_GenerateNonce: ends! returns 0
D/WVCdm   (  294): PrepareKeyRequest: nonce=1066184821
D/DrmWidevineDash(  294): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb8e6d770
D/DrmWidevineDash(  294): message_length=1626, signature=0xb8e4ad00, signature_length=3042436884
,W/libprocessgroup(  883): failed to open /acct/uid_10070/pid_9624/cgroup.procs: No such file or directory
,D/DrmWidevineDash(  294): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  294): CdmEngine::CloseSession
D/DrmWidevineDash(  294): OEMCrypto_CloseSession: starts! SID=1
,D/DrmWidevineDash(  294): OEMCrypto_CloseSession: ends! returns 0
I/WVCdm   (  294): L3 Terminate.
,D/DrmWidevineDash(  294): OEMCrypto_Terminate: starts!
D/DrmWidevineDash(  294): Service_Uninitialize: starts!
D/QSEECOMAPI: (  294): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  294): QSEECom_shutdown_app, app_id = 3
D/DrmWidevineDash(  294): Service_Uninitialize: ends! returns 0x0
,D/DrmWidevineDash(  294): OEMCrypto_Terminate: ends! returns 0
,I/Adreno-EGL( 9878): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 9878): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 9878): Build Date: 10/28/14 Tue
I/Adreno-EGL( 9878): Local Branch: 
I/Adreno-EGL( 9878): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 9878): Local Patches: NONE
I/Adreno-EGL( 9878): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/ActivityManager(  883): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=10048 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/Adreno-EGL( 9878): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 9878): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 9878): Build Date: 10/28/14 Tue
I/Adreno-EGL( 9878): Local Branch: 
I/Adreno-EGL( 9878): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 9878): Local Patches: NONE
I/Adreno-EGL( 9878): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,W/ResourcesManager(10048): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/CheckinRequestBuilder( 9765): Classify the device as Phone.
,I/Babel_SMS(10048): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS(10048): MmsConfig.loadMmsSettings
I/Babel_SMS(10048): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
I/Babel_SMS(10048): MmsConfig.loadFromDatabase
,E/Babel_SMS(10048): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS(10048): MmsConfig.loadFromResources
,E/Babel_SMS(10048): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS(10048): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/Settings(10048): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash(10048): startup - clean
,I/Babel   (10048): deleted: false for 0
,W/VideoCapabilities(10048): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities(10048): Unsupported mime audio/amr-wb-plus
,W/VideoCapabilities(10048): Unsupported mime video/mpeg2
,I/VideoCapabilities(10048): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities(10048): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities(10048): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities(10048): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities(10048): Unrecognized profile 2130706433 for video/avc
,I/ActivityManager(  883): Killing 9831:com.google.android.apps.magazines/u0a81 (adj 15): empty #7
,I/MDMCTBK (  291): NetlinkHandler, subsys is net and action is remove
I/MDMCTBK (  291): NetlinkHandler, interfaceRemoved
I/MDMCTBK (  291): MdmCutbackHndler,interfaceRemoved+
I/MDMCTBK (  291): checkDefaultInst, current pid is = 291
I/MDMCTBK (  291): checkDefaultInst, pid match
I/MDMCTBK (  291): MdmCutbackHndler,interfaceRemoved+,p2p0 interface removed
I/MDMCTBK (  291): MdmCutbackHndler,p2p0 interface removed before, wlan_stat=0, Data_call=0
I/MDMCTBK (  291): MdmCutbackHndler,p2p0 interface removed after, Mifi_stat=0, Wifi_stat=0
I/MDMCTBK (  291): MdmCutbackHndler,interfaceRemoved, calling setWifiCutback
I/MDMCTBK (  291): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=0, mf=0, wfd=0
I/MDMCTBK (  291): set_property_value, Enter
I/MDMCTBK (  291): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
,I/MDMCTBK (  291): set_property_value, Values updated in the property file Successfully
,I/MDMCTBK (  291): set_property_value, Exit
I/MDMCTBK (  291): MdmCutbackHndler, setWifiCutback, No Wifi
I/MDMCTBK (  291): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=0, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  291): set_property_value, Enter
I/MDMCTBK (  291): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  291): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  291): set_property_value, Exit
E/MDMCTBK (  291): MdmCutbackHndler,Airplane Mode Enabled !! =1
,W/libprocessgroup(  883): failed to open /acct/uid_10081/pid_9831/cgroup.procs: No such file or directory
,I/vclib   (10048): onServiceConnected
,W/Babel   (10048): Attempted to change video mute state without an active call.
,I/CheckinTask( 9765): Sending checkin request (9458 bytes)
,I/ActivityManager(  883): Killing 9915:com.android.chrome/u0a52 (adj 15): empty #7
,W/libprocessgroup(  883): failed to open /acct/uid_10052/pid_9915/cgroup.procs: No such file or directory
,I/CheckinRequestBuilder( 9765): Checkin reason type: 8 attempt count: 1
,E/ActivityThread( 9765): Failed to find provider info for com.google.android.wearable.settings
,V/GLSActivity( 1740): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1740): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/CheckinRequestBuilder( 9765): Classify the device as Phone.
,I/CheckinTask( 9765): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 9765): Checking schedule, now: 1450461669461 next: 1451062806453
I/CheckinService( 9765): active receiver: disabled
,D/CheckinService( 9765): Recording last checkin time for package unspecified as 1450461669477
,I/ActivityManager(  883): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.util.GservicesChangedReceiver: pid=10106 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
I/ActivityManager(  883): Killing 9935:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,W/libprocessgroup(  883): failed to open /acct/uid_10090/pid_9935/cgroup.procs: No such file or directory
,D/PhoneMonitor(10106): Register our PhoneStateListener
,V/SetupWizard(10106): Connected to Gservices successfully
,I/ActivityManager(  883): Killing 9962:android.process.acore/u0a7 (adj 15): empty #7
,W/libprocessgroup(  883): failed to open /acct/uid_10007/pid_9962/cgroup.procs: No such file or directory
,D/GCM     ( 1740): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/InputReader(  883): Reconfiguring input devices.  changes=0x00000010
,I/ActivityManager(  883): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.GmsPackageWatcher: pid=10129 uid=10039 gids={50039, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
,D/BackupManagerService(  883): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/BackupManagerService(  883): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,I/BackupManagerService(  883): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/BackupManagerService(  883): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/BackupManagerService(  883): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@364910a6
,I/GCoreNlp( 1740): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,I/Launcher( 1562): Deferring update until onResume
,I/ActivityManager(  883): Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=10165 uid=10019 gids={50019, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  883): Start proc android.process.acore for broadcast com.android.providers.contacts/.PackageIntentReceiver: pid=10186 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,I/ActivityManager(  883): Killing 9998:com.google.android.apps.photos/u0a88 (adj 15): empty #7
,W/libprocessgroup(  883): failed to open /acct/uid_10088/pid_9998/cgroup.procs: No such file or directory
,W/ResourcesManager(10048): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager(10048): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,W/bt-btif ( 2530): info:x10
D/        ( 2530): remote version info [7c:f9:0e:34:8a:a0]: 7, f, 610c
,V/JNIHelp (10048): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/System  (10048): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller(10048): Installed default security provider GmsCore_OpenSSL
,I/ActivityManager(  883): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=10222 uid=10027 gids={50027, 9997, 1023, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  883): Killing 9878:com.google.android.gms.unstable/u0a16 (adj 15): empty #7
,I/ContactLocale(10186): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,I/art     (  307): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 262us total 23.148ms
,I/art     (  307): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 258us total 19.578ms
,I/art     (  307): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 248us total 20.486ms
,W/libprocessgroup(  883): failed to open /acct/uid_10016/pid_9878/cgroup.procs: No such file or directory
,W/asset   (10222): Asset path /system/framework/com.motorola.gallery is neither a directory nor file (type=1).
,W/ResourcesManager(10222): Asset path '/system/framework/com.motorola.gallery' does not exist or contains no resources.
W/ResourcesManager(10222): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager(10222): Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
,I/UpdateIcingCorporaServi(10129): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,W/Launcher( 1562): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@1140211 new=com.google.android.velvet.VelvetApplication@1140211
,D/PackageBroadcastService( 9765): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/ActivityManager(  883): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=10248 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/UpdateIcingCorporaServi(10129): UpdateCorporaTask done [took 128 ms] updated apps [took 127 ms] 
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:32000 mC
,I/art     (  883): Explicit concurrent mark sweep GC freed 17124(871KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 21MB/31MB, paused 1.618ms total 124.463ms
,I/PackageBroadcastService( 9765): Null package name or gms related package.  Ignoreing.
,W/ResourcesManager(10248): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/Icing   ( 9765): Storage manager: low false usage 1.78MB avail 3.12GB capacity 4.85GB
,I/ActivityManager(  883): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=10291 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  883): Killing 10106:com.google.android.setupwizard/u0a35 (adj 15): empty #7
,W/libprocessgroup(  883): failed to open /acct/uid_10035/pid_10106/cgroup.procs: No such file or directory
,I/Icing   ( 9765): updateResources: need to parse f{com.google.android.gms}
,D/Finsky  (10291): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,I/Icing   ( 9765): Internal init done: storage state 0
,I/Icing   ( 9765): Post-init done
I/Icing   ( 9765): updateResources: need to parse f{com.google.android.gms}
,D/Finsky  (10291): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings(10291): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/Settings(10291): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/Finsky  (10291): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  (10291): [1] Libraries$2.run: Finished loading 1 libraries.
,D/Ads     (10291): Skipping gmscore version check
,D/Finsky  (10291): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/Finsky  (10291): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,D/BluetoothManagerService(  883): Message: 20
D/BluetoothManagerService(  883): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@76ed79a:true
,I/BTConnectionReceiver(10129): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:34:8A:A0, alias=null, name=S5-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier(10129): Bluetooth Device Name: S5-1
,I/ActivityManager(  883): Killing 10165:com.google.android.partnersetup/u0a19 (adj 15): empty #7
,W/libprocessgroup(  883): failed to open /acct/uid_10019/pid_10165/cgroup.procs: No such file or directory
,I/Icing   ( 9765): Indexing 5905AFFF7E2D60BB1F87C8D56D40BA6B258244BF from com.google.android.gms
,D/Icing   ( 9765): Loaded CLD2 Version V2.0 - 20141016
I/Icing   ( 9765): Indexing done 5905AFFF7E2D60BB1F87C8D56D40BA6B258244BF
,I/ActivityManager(  883): Killing 10222:com.motorola.MotGallery2/u0a27 (adj 15): empty #7
,W/libprocessgroup(  883): failed to open /acct/uid_10027/pid_10222/cgroup.procs: No such file or directory
,I/MDMCTBK (  291): NetlinkHandler, subsys is net and action is add
,I/MDMCTBK (  291): NetlinkHandler, interfaceAdded
,I/MDMCTBK (  291): MdmCutbackHndler,interfaceAdded+
I/MDMCTBK (  291): checkDefaultInst, current pid is = 291
,I/MDMCTBK (  291): checkDefaultInst, pid match
E/MDMCTBK (  291): MdmCutbackHndler,interfaceAdded+,iface: wlan0 and propVal: wlan0 not null
I/MDMCTBK (  291): MdmCutbackHndler,interfaceAdded, wlan int_stat = 1
I/MDMCTBK (  291): MdmCutbackHndler,interfaceAdded, p2p is false and wlan is 1,Mifi = 0
I/MDMCTBK (  291): , Wifi = 0
,I/MDMCTBK (  291): MdmCutbackHndler,interfaceAdded+, calling setWifiCutback,sendSarCtrl
I/MDMCTBK (  291): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=0, mf=0, wfd=0
I/MDMCTBK (  291): set_property_value, Enter
I/MDMCTBK (  291): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  291): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  291): set_property_value, Exit
I/MDMCTBK (  291): MdmCutbackHndler, setWifiCutback, No Wifi
I/MDMCTBK (  291): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=0, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  291): set_property_value, Enter
I/MDMCTBK (  291): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  291): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  291): set_property_value, Exit
E/MDMCTBK (  291): MdmCutbackHndler,Airplane Mode Enabled !! =1
,D/btif_config_util( 2530): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2530): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2530): onReceive
,I/BTConnectionReceiver(10129): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:34:8A:A0, alias=null, name=S5-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier(10129): Bluetooth Device Name: S5-1
,I/ActivityManager(  883): Killing 10048:com.google.android.talk/u0a70 (adj 15): empty #7
,W/libprocessgroup(  883): failed to open /acct/uid_10070/pid_10048/cgroup.procs: No such file or directory
,D/BatteryService(  883): uevent={POWER_SUPPLY_TEMP=288, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4310092, SEQNUM=4714, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=10902, POWER_SUPPLY_CHARGE_COUNTER=62, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2530): Disconnected process message: 10, size: 0
,I/CheckinService( 9765): Done disabling old GoogleServicesFramework version
,I/MDMCTBK (  291): NetlinkHandler, subsys is net and action is add
,I/MDMCTBK (  291): NetlinkHandler, interfaceAdded
I/MDMCTBK (  291): MdmCutbackHndler,interfaceAdded+
I/MDMCTBK (  291): checkDefaultInst, current pid is = 291
I/MDMCTBK (  291): checkDefaultInst, pid match
,E/MDMCTBK (  291): MdmCutbackHndler,interfaceAdded+,iface: p2p0 and propVal: wlan0 not null
I/MDMCTBK (  291): MdmCutbackHndler,interfaceAdded, p2p int_stat = 1
I/MDMCTBK (  291): MdmCutbackHndler,interfaceAdded, both wlan and p2p are added, Mifi = 0
I/MDMCTBK (  291): , Wifi = 0
I/MDMCTBK (  291): MdmCutbackHndler,interfaceAdded+, calling setWifiCutback,sendSarCtrl
I/MDMCTBK (  291): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=0, mf=0, wfd=0
I/MDMCTBK (  291): set_property_value, Enter
,I/MDMCTBK (  291): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/ThermalEngine(  303): Sensor:xo_therm_pu2:32000 mC
I/MDMCTBK (  291): set_property_value, Values updated in the property file Successfully
,I/MDMCTBK (  291): set_property_value, Exit
I/MDMCTBK (  291): MdmCutbackHndler, setWifiCutback, No Wifi
I/MDMCTBK (  291): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=0, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  291): set_property_value, Enter
I/MDMCTBK (  291): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  291): set_property_value, Values updated in the property file Successfully
,I/MDMCTBK (  291): set_property_value, Exit
E/MDMCTBK (  291): MdmCutbackHndler,Airplane Mode Enabled !! =1
,W/bt-btif ( 2530): info:x10
,D/        ( 2530): remote version info [7c:f9:0e:34:8a:a0]: 7, f, 610c
,I/BTConnectionReceiver(10129): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:34:8A:A0, alias=null, name=S5-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier(10129): Bluetooth Device Name: S5-1
,D/btif_config_util( 2530): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2530): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2530): onReceive
,I/BTConnectionReceiver(10129): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:34:8A:A0, alias=null, name=S5-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier(10129): Bluetooth Device Name: S5-1
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:31000 mC
,W/bt-btif ( 2530): info:x10
,D/        ( 2530): remote version info [7c:f9:0e:34:8a:a0]: 7, f, 610c
,I/BTConnectionReceiver(10129): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:34:8A:A0, alias=null, name=S5-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier(10129): Bluetooth Device Name: S5-1
,D/btif_config_util( 2530): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,D/BatteryService(  883): uevent={POWER_SUPPLY_TEMP=280, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4310274, SEQNUM=4716, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=4339, POWER_SUPPLY_CHARGE_COUNTER=95, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2530): Disconnected process message: 10, size: 0
,E/bt-btm  ( 2530): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2530): onReceive
,I/BTConnectionReceiver(10129): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:34:8A:A0, alias=null, name=S5-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier(10129): Bluetooth Device Name: S5-1
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:31000 mC
,W/bt-btif ( 2530): info:x10
,D/        ( 2530): remote version info [7c:f9:0e:34:8a:a0]: 7, f, 610c
,I/BTConnectionReceiver(10129): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:34:8A:A0, alias=null, name=S5-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier(10129): Bluetooth Device Name: S5-1
,D/btif_config_util( 2530): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2530): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2530): onReceive
,I/BTConnectionReceiver(10129): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:34:8A:A0, alias=null, name=S5-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier(10129): Bluetooth Device Name: S5-1
,I/MDMCTBK (  291): NetlinkHandler, power_supply subsys
,I/MDMCTBK (  291): NetlinkHandler, usbChargerStateChanged
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
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:31000 mC
,W/bt-btif ( 2530): info:x10
,D/        ( 2530): remote version info [7c:f9:0e:34:8a:a0]: 7, f, 610c
,I/BTConnectionReceiver(10129): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:34:8A:A0, alias=null, name=S5-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier(10129): Bluetooth Device Name: S5-1
,D/BatteryService(  883): uevent={POWER_SUPPLY_TEMP=276, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4310784, SEQNUM=4720, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=8175, POWER_SUPPLY_CHARGE_COUNTER=135, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2530): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2530): Disconnected process message: 10, size: 0
,D/btif_config_util( 2530): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2530): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2530): onReceive
,I/BTConnectionReceiver(10129): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:34:8A:A0, alias=null, name=S5-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier(10129): Bluetooth Device Name: S5-1
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:30000 mC
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
I/MDMCTBK (  291): NetlinkHandler, power_supply subsys
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
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:30000 mC
,I/MDMCTBK (  291): NetlinkHandler, power_supply subsys
,I/MDMCTBK (  291): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  291): checkDefaultInst, current pid is = 291
I/MDMCTBK (  291): checkDefaultInst, pid match
I/MDMCTBK (  291): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  291): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  291): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  291): NetlinkHandler, power_supply subsys
,I/MDMCTBK (  291): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  291): checkDefaultInst, current pid is = 291
I/MDMCTBK (  291): checkDefaultInst, pid match
I/MDMCTBK (  291): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  291): MdmCutbackHndler,readFromFile = 
,E/MDMCTBK (  291): MdmCutbackHndler,Could not open ''
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:30000 mC
,V/AlarmManager(  883): send {62c4399, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  883): send {1dd1532d, *walarm*:android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED}
,V/AlarmManager(  883): done {1dd1532d, *walarm*:android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED} [17ms]
,V/AlarmManager(  883): done {62c4399, *alarm*:android.intent.action.TIME_TICK} [41ms]
,I/MDMCTBK (  291): NetlinkHandler, power_supply subsys
I/MDMCTBK (  291): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  291): checkDefaultInst, current pid is = 291
I/MDMCTBK (  291): checkDefaultInst, pid match
I/MDMCTBK (  291): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  291): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  291): MdmCutbackHndler,Could not open ''
,D/BatteryService(  883): uevent={POWER_SUPPLY_TEMP=268, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4309790, SEQNUM=4722, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-500, POWER_SUPPLY_CHARGE_COUNTER=181, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,I/MDMCTBK (  291): NetlinkHandler, power_supply subsys
I/MDMCTBK (  291): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  291): checkDefaultInst, current pid is = 291
I/MDMCTBK (  291): checkDefaultInst, pid match
I/MDMCTBK (  291): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  291): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  291): MdmCutbackHndler,Could not open ''
,D/HeadsetStateMachine( 2530): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2530): Disconnected process message: 10, size: 0
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,D/BatteryService(  883): uevent={POWER_SUPPLY_TEMP=266, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4310045, SEQNUM=4724, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-1602, POWER_SUPPLY_CHARGE_COUNTER=70, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
I/MDMCTBK (  291): NetlinkHandler, power_supply subsys
I/MDMCTBK (  291): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  291): checkDefaultInst, current pid is = 291
I/MDMCTBK (  291): checkDefaultInst, pid match
I/MDMCTBK (  291): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  291): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  291): MdmCutbackHndler,Could not open ''
,D/HeadsetStateMachine( 2530): Disconnected process message: 10, size: 0
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,D/BatteryService(  883): uevent={POWER_SUPPLY_TEMP=266, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4310339, SEQNUM=4725, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=0, POWER_SUPPLY_CHARGE_COUNTER=0, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
I/MDMCTBK (  291): NetlinkHandler, power_supply subsys
I/MDMCTBK (  291): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  291): checkDefaultInst, current pid is = 291
I/MDMCTBK (  291): checkDefaultInst, pid match
I/MDMCTBK (  291): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  291): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  291): MdmCutbackHndler,Could not open ''
,D/HeadsetStateMachine( 2530): Disconnected process message: 10, size: 0
,I/MDMCTBK (  291): NetlinkHandler, power_supply subsys
,I/MDMCTBK (  291): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  291): checkDefaultInst, current pid is = 291
I/MDMCTBK (  291): checkDefaultInst, pid match
I/MDMCTBK (  291): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  291): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  291): MdmCutbackHndler,Could not open ''
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,D/BatteryService(  883): uevent={POWER_SUPPLY_TEMP=264, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4310301, SEQNUM=4727, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-10817, POWER_SUPPLY_CHARGE_COUNTER=-367, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
I/MDMCTBK (  291): NetlinkHandler, power_supply subsys
I/MDMCTBK (  291): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  291): checkDefaultInst, current pid is = 291
I/MDMCTBK (  291): checkDefaultInst, pid match
I/MDMCTBK (  291): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  291): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  291): MdmCutbackHndler,Could not open ''
,D/HeadsetStateMachine( 2530): Disconnected process message: 10, size: 0
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/UsageStatsService(  883): User[0] Flushing usage stats to disk
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,V/AlarmManager(  883): send {62c4399, *alarm*:android.intent.action.TIME_TICK}
V/AlarmManager(  883): send {afee8cb, *alarm*:com.android.deskclock.ON_QUARTER_HOUR}
,I/LaunchCheckinHandler(  883): cleanup(): cleared. Last call was 828778 ms ago
I/ActivityManager(  883): Start proc com.google.android.deskclock for broadcast com.google.android.deskclock/com.android.alarmclock.DigitalAppWidgetProvider: pid=10380 uid=10055 gids={50055, 9997, 3003, 1028} abi=armeabi-v7a
,V/AlarmManager(  883): done {62c4399, *alarm*:android.intent.action.TIME_TICK} [93ms]
,I/GAv4    (10380): Google Analytics 4.5.0/7324 is starting up. To enable debug logging on a device run:
I/GAv4    (10380):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    (10380):   adb logcat -s GAv4
,W/GAv4    (10380): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    (10380): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    (10380): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,V/AlarmManager(  883): done {afee8cb, *alarm*:com.android.deskclock.ON_QUARTER_HOUR} [246ms]
I/ActivityManager(  883): Killing 10186:android.process.acore/u0a7 (adj 15): empty #7
,W/libprocessgroup(  883): failed to open /acct/uid_10007/pid_10186/cgroup.procs: No such file or directory
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,V/AlarmManager(  883): send {62c4399, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  883): send {317928a8, *walarm*:com.google.android.gms.gcm.HEARTBEAT_ALARM}
,V/AlarmManager(  883): done {62c4399, *alarm*:android.intent.action.TIME_TICK} [48ms]
,V/AlarmManager(  883): done {317928a8, *walarm*:com.google.android.gms.gcm.HEARTBEAT_ALARM} [82ms]
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,V/AlarmManager(  883): send {14e9afc1, *walarm*:com.google.android.gms/.checkin.EventLogService$Receiver}
,V/AlarmManager(  883): send {1dd1532d, *walarm*:android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED}
,V/AlarmManager(  883): done {14e9afc1, *walarm*:com.google.android.gms/.checkin.EventLogService$Receiver} [21ms]
V/AlarmManager(  883): done {1dd1532d, *walarm*:android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED} [22ms]
,I/EventLogService( 9765): Aggregate from 1450461661043 (log), 1450460589204 (data)
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,D/BatteryService(  883): uevent={POWER_SUPPLY_TEMP=261, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4310577, SEQNUM=4734, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-5909, POWER_SUPPLY_CHARGE_COUNTER=6, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
I/MDMCTBK (  291): NetlinkHandler, power_supply subsys
I/MDMCTBK (  291): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  291): checkDefaultInst, current pid is = 291
I/MDMCTBK (  291): checkDefaultInst, pid match
I/MDMCTBK (  291): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  291): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  291): MdmCutbackHndler,Could not open ''
,D/HeadsetStateMachine( 2530): Disconnected process message: 10, size: 0
,I/MDMCTBK (  291): NetlinkHandler, power_supply subsys
,I/MDMCTBK (  291): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  291): checkDefaultInst, current pid is = 291
I/MDMCTBK (  291): checkDefaultInst, pid match
I/MDMCTBK (  291): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  291): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  291): MdmCutbackHndler,Could not open ''
,D/HeadsetStateMachine( 2530): Disconnected process message: 10, size: 0
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,V/AlarmManager(  883): send {62c4399, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  883): send {2baf3095, *alarm*:com.android.server.action.NETWORK_STATS_POLL}
V/AlarmManager(  883): send {2101a643, *alarm*:com.google.android.gms.common.receiver.LOG_CORE_ANALYTICS}
,I/ProcessStatsService(  883): Prepared write state in 12ms
,I/ProcessStatsService(  883): Prepared write state in 6ms
,V/AlarmManager(  883): done {2baf3095, *alarm*:com.android.server.action.NETWORK_STATS_POLL} [66ms]
,V/AlarmManager(  883): done {62c4399, *alarm*:android.intent.action.TIME_TICK} [88ms]
,V/AlarmManager(  883): done {2101a643, *alarm*:com.google.android.gms.common.receiver.LOG_CORE_ANALYTICS} [91ms]
,V/GLSActivity( 1740): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 1740): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ProcessStatsService(  883): Pruning old procstats: /data/system/procstats/state-2015-12-18-03-46-59.bin
,I/art     ( 1740): Explicit concurrent mark sweep GC freed 66284(3MB) AllocSpace objects, 22(352KB) LOS objects, 40% free, 13MB/22MB, paused 1.753ms total 106.726ms
,E/DataBuffer( 1740): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@2a45dc4c)
,E/DataBuffer( 1740): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@37a62495)
E/DataBuffer( 1740): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@312129aa)
E/DataBuffer( 1740): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@294cb99b)
,E/DataBuffer( 1740): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@1f1a7138)
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,TIME-OUT KILL (timeout was 1800000ms),D/AndroidRuntime(10459): 
D/AndroidRuntime(10459): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime(10459): CheckJNI is OFF
D/AndroidRuntime(10459): Calling main entry com.android.commands.pm.Pm
I/ActivityManager(  883): Force stopping com.test.thalitest appid=10391 user=-1: uninstall pkg
I/ActivityManager(  883):   Force finishing activity ActivityRecord{12069eda u0 com.test.thalitest/.MainActivity t3}
W/PackageSettings(  883): Skipping PackageSetting{3feceb04 com.example.hello/10377} due to missing metadata
I/ActivityManager(  883): Force stopping com.test.thalitest appid=10391 user=0: pkg removed
I/Keyboard.Facilitator( 1417): resetDictionaries() : en_US
W/GeofencerStateMachine( 1740): Ignoring removeGeofence because network location is disabled.
I/InputReader(  883): Reconfiguring input devices.  changes=0x00000010
I/ActivityManager(  883): Start proc android.process.acore for broadcast com.android.providers.contacts/.PackageIntentReceiver: pid=10478 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
I/Keyboard.Facilitator.DecoderInitializer( 1417): run()
I/Decoder ( 1417): createOrResetDecoder
I/art     ( 3085): Explicit concurrent mark sweep GC freed 19750(3MB) AllocSpace objects, 39(624KB) LOS objects, 39% free, 7MB/12MB, paused 2.798ms total 114.173ms
I/ConfigService( 1740): onCreate
D/BackupManagerService(  883): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService(  883): Receieved: android.intent.action.PACKAGE_REMOVED
D/TaskPersister(  883): removeObsoleteFile: deleting file=3_task.xml
I/Keyboard.Facilitator.MainLanguageModelLoader( 1417): run()
I/art     ( 1562): Explicit concurrent mark sweep GC freed 6748(506KB) AllocSpace objects, 5(261KB) LOS objects, 24% free, 13MB/17MB, paused 1.386ms total 209.310ms
I/Keyboard.Facilitator.MainLanguageModelLoader( 1417): loadStaticLm() : Loading File = /data/app/com.google.android.inputmethod.latin-1/base.apk (offset=5005604, length=4014912) with up to date LoudsLmContentVersion = 20150512
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1417): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1417): run() : Loading LM = contacts
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1417): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1417): run() : Loading LM = history
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1417): run() : Loaded File = UserHistory.en_US.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1417): run() : Loading LM = user
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1417): run() : Missing File = Personal.en_US.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1417): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1417): run()
I/Keyboard.Facilitator.RecurringTaskScheduler( 1417): run()
I/StatsUtilsManager( 1417): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1417): shouldRecordStats() = Too Soon
I/Launcher( 1562): Deferring update until onResume
D/VoicemailCleanupService(10478): Cleaning up data for package: com.test.thalitest
I/art     (  883): Explicit concurrent mark sweep GC freed 32550(2021KB) AllocSpace objects, 11(262KB) LOS objects, 33% free, 21MB/32MB, paused 2ms total 216.012ms
I/art     (  883): WaitForGcToComplete blocked for 138.795ms for cause Explicit
I/ContactLocale(10478): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
I/ActivityManager(  883): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=10513 uid=10027 gids={50027, 9997, 1023, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  883): Killing 10248:com.google.android.apps.plus/u0a90 (adj 15): empty #7
D/AndroidRuntime(10459): Shutting down VM
I/art     (  883): Explicit concurrent mark sweep GC freed 5527(344KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 21MB/31MB, paused 1.468ms total 178.376ms
W/libprocessgroup(  883): failed to open /acct/uid_10090/pid_10248/cgroup.procs: No such file or directory
W/asset   (10513): Asset path /system/framework/com.motorola.gallery is neither a directory nor file (type=1).
W/ResourcesManager(10513): Asset path '/system/framework/com.motorola.gallery' does not exist or contains no resources.
W/ResourcesManager(10513): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager(10513): Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
I/ActivityManager(  883): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=10535 uid=1000 gids={41000, 9997, 1021, 3004, 3005, 1000, 3009, 1015, 1023, 1010, 1004, 2002, 3006, 1028, 3002, 3001, 3003} abi=armeabi-v7a
I/ActivityManager(  883): Killing 10291:com.android.vending/u0a32 (adj 15): empty #7
W/libprocessgroup(  883): failed to open /acct/uid_10032/pid_10291/cgroup.procs: No such file or directory
W/ContextImpl(10535): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1820 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2611 
D/PackageBroadcastService( 9765): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/ChimeraCfgMgr( 9765): Reading stored module config
D/AccountUtils( 9765): Clearing selected account for com.test.thalitest
E/SQLiteDatabase(10535): Failed to open database '/data/data/com.android.keychain/databases/grants.db'.
E/SQLiteDatabase(10535): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase(10535): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase(10535): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase(10535): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase(10535): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase(10535): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase(10535): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase(10535): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase(10535): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase(10535): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase(10535): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1276)
E/SQLiteDatabase(10535): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase(10535): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase(10535): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase(10535): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:402)
E/SQLiteDatabase(10535): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:396)
E/SQLiteDatabase(10535): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase(10535): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase(10535): 	at android.os.Looper.loop(Looper.java:135)
E/SQLiteDatabase(10535): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/ChimeraCfgMgr( 9765): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 9765): Loading module APK com.google.android.play.games
I/qdhwcomposer(  278): handle_blank_event: dpy:0 panel power state: 0
E/AndroidRuntime(10535): FATAL EXCEPTION: IntentService[KeyChainService]
E/AndroidRuntime(10535): Process: com.android.keychain, PID: 10535
E/AndroidRuntime(10535): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime(10535): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime(10535): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/AndroidRuntime(10535): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/AndroidRuntime(10535): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime(10535): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime(10535): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime(10535): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/AndroidRuntime(10535): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/AndroidRuntime(10535): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/AndroidRuntime(10535): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1276)
E/AndroidRuntime(10535): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/AndroidRuntime(10535): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AndroidRuntime(10535): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AndroidRuntime(10535): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:402)
E/AndroidRuntime(10535): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:396)
E/AndroidRuntime(10535): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime(10535): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime(10535): 	at android.os.Looper.loop(Looper.java:135)
E/AndroidRuntime(10535): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/Process (10535): Sending signal. PID: 10535 SIG: 9

```
