#### Test 55902202f27eba5_thali04_motorola-XT1072 Logs


```
--------- beginning of system
,V/AlarmManager(  892): send {22a3c962, *alarm*:android.intent.action.TIME_TICK}
V/AlarmManager(  892): send {3cc2838c, *walarm*:com.google.android.intent.action.SEND_IDLE}
V/AlarmManager(  892): done {3cc2838c, *walarm*:com.google.android.intent.action.SEND_IDLE} [16ms]
V/AlarmManager(  892): done {22a3c962, *alarm*:android.intent.action.TIME_TICK} [49ms]
--------- beginning of main
D/AndroidRuntime( 6425): 
D/AndroidRuntime( 6425): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6425): CheckJNI is OFF
D/AndroidRuntime( 6425): Calling main entry com.android.commands.am.Am
I/ActivityManager(  892): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
I/ActivityManager(  892): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6444 uid=10447 gids={50447, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 6425): Shutting down VM
V/ActivityManager(  892): Display changed displayId=0
W/ContextImpl( 1482): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
W/ContextImpl( 1482): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
I/WebViewFactory( 6444): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 6444): Time to load native libraries: 2 ms (timestamps 6067-6069)
I/LibraryLoader( 6444): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 6444): Binding Chromium to main looper Looper (main, tid 1) {2712cc92}
I/LibraryLoader( 6444): Expected native library version number "",actual native library version number ""
I/chromium( 6444): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 6444): Initializing chromium process, singleProcess=true
,W/art     ( 6444): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 6444): ApplicationContext is null in ApplicationStatus
,W/chromium( 6444): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 6444): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,E/libEGL  ( 6444): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 6444): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 6444): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 6444): Build Date: 10/28/14 Tue
I/Adreno-EGL( 6444): Local Branch: 
I/Adreno-EGL( 6444): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 6444): Local Patches: NONE
I/Adreno-EGL( 6444): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,D/BluetoothManagerService(  892): Message: 20
D/BluetoothManagerService(  892): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@18763290:true
,W/ActivityManager(  892): Activity pause timeout for ActivityRecord{2d2edad5 u0 com.test.thalitest/.MainActivity t6}
,W/art     ( 6444): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 6444): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 6444): CordovaWebView is running on device made by: motorola
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:30000 mC
,I/art     (  892): Explicit concurrent mark sweep GC freed 39961(1914KB) AllocSpace objects, 2(216KB) LOS objects, 33% free, 20MB/30MB, paused 1.550ms total 131.717ms
,W/art     ( 6444): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 6444): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 6444): Render dirty regions requested: true
,D/Atlas   ( 6444): Validating map...
,W/chromium( 6444): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/OpenGLRenderer( 6444): Initialized EGL, version 1.4
,D/OpenGLRenderer( 6444): Enabling debug mode 0
,I/Keyboard.Facilitator( 1427): onFinishInput()
,I/LaunchCheckinHandler(  892): Displayed com.test.thalitest/.MainActivity,cp,ca,1039
I/ActivityManager(  892): Displayed com.test.thalitest/.MainActivity: +954ms (total +1s39ms)
,W/IInputConnectionWrapper( 6444): showStatusIcon on inactive InputConnection
,E/global frequency( 2602): no tags to log
,D/Checkin ( 2602): publish the event [tag = MOT_CHECKIN event name = LOG]
,E/Adreno-ES20( 6444): <check_framebuffer_attachment:854>: Invalid texture format! Returning error!
E/Adreno-ES20( 6444): <check_framebuffer_object_status:1237>: Framebuffer color attachment incomplete. Returning GL_FRAMEBUFFER_INCOMPLETE_ATTACHMENT!
,W/BindingManager( 6444): Cannot call determinedVisibility() - never saw a connection for the pid: 6444
,I/art     ( 2602): Explicit concurrent mark sweep GC freed 34671(2MB) AllocSpace objects, 6(119KB) LOS objects, 39% free, 11MB/19MB, paused 1.040ms total 90.720ms
,D/BSUtils ( 2602): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,E/PhoneInterfaceManager( 1566): [PhoneIntfMgr] getIccId: ICC ID is null or empty.
,D/BSUtils ( 2602): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,I/art     ( 1482): Explicit concurrent mark sweep GC freed 55525(3MB) AllocSpace objects, 36(1235KB) LOS objects, 39% free, 7MB/12MB, paused 927us total 45.278ms
,I/BSUtils ( 2602): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,D/JsMessageQueue( 6444): Set native->JS mode to OnlineEventsBridgeMode
,D/BSUtils ( 2602): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,E/PhoneInterfaceManager( 1566): [PhoneIntfMgr] getIccId: ICC ID is null or empty.
,D/BSUtils ( 2602): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,I/BSUtils ( 2602): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,D/BSUtils ( 2602): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,E/PhoneInterfaceManager( 1566): [PhoneIntfMgr] getIccId: ICC ID is null or empty.
,D/BSUtils ( 2602): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,I/art     ( 1482): Explicit concurrent mark sweep GC freed 4222(176KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 7MB/12MB, paused 651us total 35.833ms
,I/BSUtils ( 2602): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,I/BSUtils ( 2602): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,I/global frequency( 2602): BcsDSCheckin.logProperties: root status from persist.qe isqe 0/0
,D/Checkin ( 2602): publish the event [tag = MOT_CHECKIN event name = LOG]
,E/global frequency( 2602): BcsDSCheckin.logProperties: BL State from property is null or empty
,D/Checkin ( 2602): publish the event [tag = MOT_CHECKIN event name = LOG]
,D/Checkin ( 2602): publish the event [tag = DEV_ATTRIBS event name = SW]
,D/Checkin ( 2602): publish the event [tag = MOT_CCE_STATS event name = DataUsage]
,I/global frequency( 2602): BcsCore.doCallHomeCore: Exceeded maximum number of checkins for one hour. Bailing out
,D/Checkin ( 2602): publish the event [tag = MOT_CHECKIN event name = LOG]
,D/jxcore_app_log( 6444): JniHelper::setJavaVM(0xb8ffc310), pthread_self() = -1187463488
,D/JX-Cordova( 6444): jxcore cordova android initializing
,W/art     ( 6444): Suspending all threads took: 6.686ms
,I/art     ( 6444): Background sticky concurrent mark sweep GC freed 11034(940KB) AllocSpace objects, 0(0B) LOS objects, 0% free, 22MB/22MB, paused 10.931ms total 28.058ms
,W/jxcore-log( 6444): Initializing JXcore engine
W/jxcore-log( 6444): JXcore engine is ready
,W/jxcore-log( 6444): Starting JXcore engine
,W/.test.thalitest( 6444): type=1400 audit(0.0:4): avc: denied { ioctl } for uid=10447 path="socket:[5590]" dev="sockfs" ino=5590 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,W/.test.thalitest( 6444): type=1400 audit(0.0:5): avc: denied { ioctl } for uid=10447 path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2122 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
W/.test.thalitest( 6444): type=1400 audit(0.0:6): avc: denied { ioctl } for uid=10447 path="socket:[9672]" dev="sockfs" ino=9672 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,W/.test.thalitest( 6444): type=1400 audit(0.0:7): avc: denied { ioctl } for uid=10447 path="socket:[28900]" dev="sockfs" ino=28900 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,W/jxcore-log( 6444): Platform android
W/jxcore-log( 6444): 
,W/jxcore-log( 6444): Process ARCH arm
W/jxcore-log( 6444): 
,I/jxcore-log( 6444): JXcore Cordova bridge is ready!
I/jxcore-log( 6444): 
,W/jxcore-log( 6444): JXcore engine is started
,I/chromium( 6444): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 6444): Toggling radios to true
I/jxcore-log( 6444): 
,D/BluetoothAdapter( 6444): enable(): BT is already enabled..!
,D/WifiService(  892): New client listening to asynchronous messages
,D/WifiService(  892): setWifiEnabled: true pid=6444, uid=10447
E/WifiService(  892): Invoking mWifiStateMachine.setWifiEnabled
,I/jxcore-log( 6444): Radios toggled
I/jxcore-log( 6444): 
I/jxcore-log( 6444): My device name is: motorola-XT1072
I/jxcore-log( 6444): 
,I/wpa_supplicant( 1449): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
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
,D/TCMD    (  483): NL - Read 1004 bytes from update socket.
D/TCMD    (  483): NL - message type is RTM_NEWLINK
D/TCMD    (  483): Listening for incoming client connection request
D/TCMD    (  483): NL - Read 68 bytes from update socket.
D/TCMD    (  483): NL - message type is RTM_NEWLINK
D/TCMD    (  483): Listening for incoming client connection request
D/TCMD    (  483): NL - Read 68 bytes from update socket.
D/TCMD    (  483): NL - message type is RTM_NEWLINK
D/TCMD    (  483): Listening for incoming client connection request
,I/MDMCTBK (  293): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  293): set_property_value, Exit
I/MDMCTBK (  293): MdmCutbackHndler, setWifiCutback, No Wifi
I/MDMCTBK (  293): MdmCutbackHndler,Wifi disconnected !!!
I/MDMCTBK (  293): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=0, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  293): set_property_value, Enter
I/MDMCTBK (  293): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
,I/MDMCTBK (  293): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  293): set_property_value, Exit
E/MDMCTBK (  293): MdmCutbackHndler,Airplane Mode Enabled !! =1
,I/wpa_supplicant( 1449): wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=WORLD
,I/wpa_supplicant( 1449): wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=US
,D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  293): Event received = CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-REGDOM-CHANGE
D/MDMCTBK (  293): Event received = CTRL-EVENT-REGDOM-CHANGE
D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-REGDOM-CHANGE
D/MDMCTBK (  293): Event received = CTRL-EVENT-REGDOM-CHANGE
D/Tethering(  892): InitialState.processMessage what=4
W/Settings(  892): Setting tether_dun_apn has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/Tethering(  892): ApnList is empty for checkDunConfigured()
D/Tethering(  892):  upstream interface types: 
D/Tethering(  892):  1
D/Tethering(  892):  5
D/Tethering(  892):  7
D/Tethering(  892):  0
E/WifiStateMachine(  892): WifiStateMachine: Leaving Connected state
E/WifiStateMachine(  892): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$8800 - exit - invokeExitMethods
E/WifiStateMachine(  892): handleNetworkDisconnect any config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  892): handleNetworkDisconnect "NG700" nid=0
E/WifiConfigStore(  892): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,D/Tethering(  892): sendTetherStateChangedBroadcast 0, 0, 0
E/WifiStateMachine(  892): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/WifiStateMachine(  892): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/native  (  892): do suspend true
,D/WifiP2pService(  892): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  892): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
E/wpa_supplicant( 1449): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
D/CommandListener(  289): Clearing all IP addresses on wlan0
D/TCMD    (  483): NL - Read 60 bytes from update socket.
D/TCMD    (  483): NL - ignore NL message, type = 21
D/TCMD    (  483): Listening for incoming client connection request
,V/NativeCrypto( 1766): Read error: ssl=0xb93f45a8: I/O error during system call, Connection timed out
,V/NativeCrypto( 1766): SSL shutdown failed: ssl=0xb93f45a8: I/O error during system call, Broken pipe
,D/ConnectivityService(  892): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10016
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  892): ValidatedState{ when=-1ms what=532488 arg1=10016 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  892): DefaultState{ when=-1ms what=532488 arg1=10016 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  892): Forcing reevaluation
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  892): EvaluatingState{ when=-1ms what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  892): Checking http://clients3.google.com/generate_204 on "NG700"
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  892): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
,E/WifiStateMachine(  892): setDetailed state, old =CONNECTED and new state=DISCONNECTED hidden=false
E/WifiStateMachine(  892): setDetailed state send new extra info<unknown ssid>
,I/ActivityManager(  892): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6513 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/SBar.MotoNetworkCtrlr( 1303): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1303): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
D/WifiMetrics(  892): connected time updated 131011
D/ConnectivityService(  892): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService(  892): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
,D/Checkin (  892): publish the event [tag = MOT_WIFI_L1 event name = CONNECT]
,E/wpa_supplicant( 1449): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
E/WifiStateMachine(  892): Start Disconnecting Watchdog 1
,I/wpa_supplicant( 1449): wlan0: CTRL-EVENT-SCAN-STARTED ,
D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  293): Event received = CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  293): Event received = CTRL-EVENT-SCAN-STARTED 
,I/SBar.MotoNetworkCtrlr( 1303): refreshSignalCluster[0]: wifi: mWifiConnected=true Wifi=0x7f02012a=com.android.systemui:drawable/stat_sys_wifi_signal_0_fully Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
I/SBar.MotoNetworkCtrlr( 1303): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1303): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1303): refreshSignalCluster[0]: wifi: mWifiConnected=false Wifi=0x7f020133=com.android.systemui:drawable/stat_sys_wifi_signal_null Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
,E/WifiStateMachine(  892): ConnectModeState: Network connection lost 
,D/Checkin (  892): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
E/WifiStateMachine(  892): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$8800 - processMessage - processMsg
,I/SBar.MotoNetworkCtrlr( 1303): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1303): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
E/WifiStateMachine(  892): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
,E/WifiStateMachine(  892): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/native  (  892): do suspend true
,D/Checkin (  892): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
D/WifiP2pService(  892): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  892): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
E/wpa_supplicant( 1449): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
,W/ResourcesManager( 6513): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/CommandListener(  289): Clearing all IP addresses on wlan0
D/ConnectivityService(  892): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
D/Nat464Xlat(  892): requiresClat: netType=1, connected=false, hasIPv4Address=true
D/CSLegacyTypeTracker(  892): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/ConnectivityService(  892): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  892): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  892): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/ConnectivityManager.CallbackHandler( 1303): CM callback handler got msg 524292
,I/ModemStatsDSDetect( 1549): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  892): EvaluatingState{ when=-3ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  892): DefaultState{ when=-4ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  892): Disconnected - quitting
E/WifiStateMachine(  892): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
,I/ModemStatsDSDetect( 1549): INET_CONDITION=0 ,activeNet=null
,I/ModemStatsDSDetect( 1549): onReceive() - done, currentInetCondition=0
E/ConnectivityService(  892): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,I/SBar.MotoNetworkCtrlr( 1303): onReceive: CONNECTIVITY_ACTION_IMMEDIATE Recieved, mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/ModemStatsDSDetect( 1549): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
I/SBar.MotoNetworkCtrlr( 1303): updateConnectivity[0]: NetworkInfo: null, raw inetCondition= 0
I/SBar.MotoNetworkCtrlr( 1303): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1303): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1303): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1303): onReceive: CONNECTIVITY_ACTION_IMMEDIATE Recieved, mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/ModemStatsDSDetect( 1549): INET_CONDITION=0 ,activeNet=null
I/ModemStatsDSDetect( 1549): onReceive() - done, currentInetCondition=0
,I/SBar.MotoNetworkCtrlr( 1303): updateConnectivity[0]: NetworkInfo: null, raw inetCondition= 0
I/SBar.MotoNetworkCtrlr( 1303): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1303): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1303): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1303): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1303): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/Checkin (  892): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,E/WifiStateMachine(  892): SUPPLICANT_STATE_CHANGE_EVENT state=DISCONNECTED -> state= DISCONNECTED debouncing=false
E/WifiStateMachine(  892): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
,E/WifiStateMachine(  892): Link configuration changed for netId: -1 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  892): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
,E/WifiStateMachine(  892): Link configuration changed for netId: -1 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  892): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
,E/WifiStateMachine(  892): Link configuration changed for netId: -1 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  892): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
,D/WifiNetworkAgent(  892): NetworkAgent: NetworkAgent channel lost
E/WifiStateMachine(  892): SUPPLICANT_STATE_CHANGE_EVENT state=SCANNING -> state= SCANNING debouncing=false
E/WifiStateMachine(  892): setDetailed state, old =DISCONNECTED and new state=SCANNING hidden=false
,E/WifiStateMachine(  892): setDetailed state send new extra info"NG700"
,I/SBar.MotoNetworkCtrlr( 1303): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1303): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1303): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1303): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/Checkin (  892): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
D/Checkin (  892): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,I/art     (  892): Explicit concurrent mark sweep GC freed 22882(1206KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 20MB/30MB, paused 1.892ms total 119.648ms
,D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 1
D/MDMCTBK (  293): Event received = CTRL-EVENT-BSS-REMOVED 1
D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  293): Event received = CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=wlan0 <3>WPS-AP-AVAILABLE 
D/MDMCTBK (  293): Event received = WPS-AP-AVAILABLE 
D/TCMD    (  483): NL - Read 56 bytes from update socket.
D/TCMD    (  483): NL - message type is RTM_NEWLINK
D/TCMD    (  483): Listening for incoming client connection request
,I/wpa_supplicant( 1449): wlan0: Trying to associate with SSID 'NG700'
,D/WifiMonitor(  892): didn't find BSSID Trying to associate with SSID 'NG700'
E/wpa_supplicant( 1449): DSDS: eapol_sm_notify_config config->sim_num = 1
,D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=wlan0 <3>Trying to associate with
D/MDMCTBK (  293): Event received = Trying to associate with
D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  293): Event received = CTRL-EVENT-STATE-CHANGE 
E/WifiStateMachine(  892): [1,452,699,436,392 ms] noteScanEnd no scan source
,E/WifiStateMachine(  892): wifi setScanResults statecom.android.server.wifi.WifiStateMachine$DisconnectedState@23f04f26 sup_state=SCANNING debouncing=false
,E/WifiStateMachine(  892): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATING -> state= CONNECTING debouncing=false
E/WifiStateMachine(  892): setDetailed state, old =SCANNING and new state=CONNECTING hidden=false
E/WifiStateMachine(  892): setDetailed state send new extra info0x
,I/SBar.MotoNetworkCtrlr( 1303): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1303): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/Checkin (  892): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,I/SBar.MotoNetworkCtrlr( 1303): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1303): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/Babel_SMS( 6513): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 6513): MmsConfig.loadMmsSettings
I/Babel_SMS( 6513): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
I/Babel_SMS( 6513): MmsConfig.loadFromDatabase
,E/Babel_SMS( 6513): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 6513): MmsConfig.loadFromResources
,E/Babel_SMS( 6513): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel_SMS( 6513): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/art     ( 6513): Suspending all threads took: 9.227ms
,W/Settings( 6513): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/Babel_Crash( 6513): startup - clean
,D/TCMD    (  483): NL - Read 312 bytes from update socket.
D/TCMD    (  483): NL - message type is RTM_NEWLINK
D/TCMD    (  483): Listening for incoming client connection request
D/TCMD    (  483): NL - Read 192 bytes from update socket.
D/TCMD    (  483): NL - message type is RTM_NEWLINK
D/TCMD    (  483): Listening for incoming client connection request
D/TCMD    (  483): NL - Read 68 bytes from update socket.
D/TCMD    (  483): NL - message type is RTM_NEWLINK
D/TCMD    (  483): Listening for incoming client connection request
D/TCMD    (  483): NL - Read 1004 bytes from update socket.
D/TCMD    (  483): NL - message type is RTM_NEWLINK
D/TCMD    (  483): Listening for incoming client connection request
,I/wpa_supplicant( 1449): wlan0: Associated with c0:ff:d4:d3:aa:48
E/WifiStateMachine(  892): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATED -> state= CONNECTING debouncing=false
E/WifiStateMachine(  892): setDetailed state, old =CONNECTING and new state=CONNECTING hidden=false
D/TCMD    (  483): NL - Read 80 bytes from update socket.
D/TCMD    (  483): NL - message type is RTM_NEWLINK
D/TCMD    (  483): Listening for incoming client connection request
D/TCMD    (  483): NL - Read 80 bytes from update socket.
,D/TCMD    (  483): NL - message type is RTM_NEWLINK
D/TCMD    (  483): Listening for incoming client connection request
D/TCMD    (  483): NL - Read 68 bytes from update socket.
D/TCMD    (  483): NL - message type is RTM_NEWLINK
D/TCMD    (  483): Listening for incoming client connection request
D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  293): Event received = CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=wlan0 <3>Associated with c0:ff:d4
D/MDMCTBK (  293): Event received = Associated with c0:ff:d4
D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  293): Event received = CTRL-EVENT-STATE-CHANGE 
D/Tethering(  892): exception when get active network info: java.lang.NullPointerException: Attempt to invoke virtual method 'int android.net.NetworkInfo.getType()' on a null object reference
W/Settings(  892): Setting tether_dun_apn has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/WifiStateMachine(  892): SUPPLICANT_STATE_CHANGE_EVENT state=FOUR_WAY_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine(  892): setDetailed state, old =CONNECTING and new state=AUTHENTICATING hidden=false
E/Tethering(  892): ApnList is empty for checkDunConfigured()
D/Tethering(  892):  upstream interface types: 
E/WifiStateMachine(  892): setDetailed state send new extra info"NG700"
D/Tethering(  892):  0
D/Tethering(  892):  1
D/Tethering(  892):  5
D/Tethering(  892):  7
,D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  293): Event received = CTRL-EVENT-STATE-CHANGE 
I/wpa_supplicant( 1449): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
,I/wpa_supplicant( 1449): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
D/TCMD    (  483): NL - Read 1004 bytes from update socket.
D/TCMD    (  483): NL - message type is RTM_NEWLINK
D/TCMD    (  483): Listening for incoming client connection request
D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=wlan0 <3>WPA: Key negotiation com
D/MDMCTBK (  293): Event received = WPA: Key negotiation com
D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-CONNECTED - C
D/MDMCTBK (  293): Event received = CTRL-EVENT-CONNECTED - C
D/MDMCTBK (  293):  STA Connected !!
E/MDMCTBK (  293): cmd: IFNAME=wlan0 ASSOCFREQ, reply: 2412, reply_len: 4, ret: 0
D/MDMCTBK (  293): get_freq !!, resp=2412
,I/MDMCTBK (  293): get_freq !!, Strip data
I/MDMCTBK (  293): get_freq !!, band = 2, freq = 2412
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
I/SBar.MotoNetworkCtrlr( 1303): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/MDMCTBK (  293): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  293): set_property_value, Exit
I/MDMCTBK (  293): MdmCutbackHndler,setWifiCutback, Wifi_cbk_Used= 0, Wifi_band=2, p2p0 = 1, wlan0 = 1, data=0
I/SBar.MotoNetworkCtrlr( 1303): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/MDMCTBK (  293): MdmCutbackHndler,WifiBand =2, MifiBand =-1, tx_pwr=18
,I/MDMCTBK (  293): MdmCutbackHndler, set WIFI TX pwr !!
I/MDMCTBK (  293): checkDefaultInst, current pid is = 293
I/MDMCTBK (  293): checkDefaultInst, pid match
I/MDMCTBK (  293): get_property_value, Enter
I/MDMCTBK (  293): get_property_value, Values read from property=1,0,0,0,0,0,1,0,0,1,1,0, length=23
I/MDMCTBK (  293): get_property_value, Exit
I/MDMCTBK (  293): create_thread_wpa_supplicant: Started WPA thread for wifi_set_tx_pwr thread -1215102744
I/MDMCTBK (  293): return from set_get_from_wpa_supplicant
I/MDMCTBK (  293): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=1, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  293): set_property_value, Enter
I/MDMCTBK (  293): set_property_value, Values updated in the property=1,0,0,0,0,0,1,0,0,1,1,0
I/MDMCTBK (  293): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  293): set_property_value, Exit
E/MDMCTBK (  293): MdmCutbackHndler,Airplane Mode Enabled !! =1
D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  293): Event received = CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  293): wifi_set_tx_pwr: SETTXPOWER = 18
E/MDMCTBK (  293): cmd: IFNAME=wlan0 DRIVER SETTXPOWER 18, reply: OK
E/MDMCTBK (  293): , reply_len: 3, ret: 0
E/MDMCTBK (  293): MdmCutbackHndler, resp=OK
E/MDMCTBK (  293): 
D/MDMCTBK (  293): wifi_set_tx_pwr: Exit
D/Tethering(  892): sendTetherStateChangedBroadcast 1, 0, 0
,I/SBar.MotoNetworkCtrlr( 1303): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1303): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/Babel   ( 6513): deleted: false for 0
,E/WifiStateMachine(  892): SUPPLICANT_STATE_CHANGE_EVENT state=GROUP_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine(  892): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING hidden=false
E/WifiStateMachine(  892): Network connection established
E/WifiStateMachine(  892): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR hidden=false
I/SBar.MotoNetworkCtrlr( 1303): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1303): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1303): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1303): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,E/WifiStateMachine(  892): setDetailed state, old =OBTAINING_IPADDR and new state=CONNECTING hidden=false
I/SBar.MotoNetworkCtrlr( 1303): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1303): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/ConnectivityService(  892): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
E/WifiStateMachine(  892): L2ConnectedState any config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  892): L2ConnectedState "NG700" nid=0
E/WifiConfigStore(  892): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,D/ConnectivityService(  892): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,E/WifiStateMachine(  892): enter ObtainingIpState netId=0 "NG700"WPA_PSK  roam=0 static=false watchdog= 1
E/WifiStateMachine(  892): ObtainingIpAddress any config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  892): ObtainingIpAddress "NG700" nid=0
E/WifiConfigStore(  892): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,D/CommandListener(  289): Setting iface cfg
,E/WifiStateMachine(  892): Start Dhcp Watchdog 2
,E/WifiStateMachine(  892): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  892): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES
,E/WifiStateMachine(  892): setSuspendOptimizationsNative: 1 false -want true stack:setSuspendOptimizationsNative - handlePreDhcpSetup - processMessage - processMsg
E/native  (  892): do suspend false
,E/wpa_supplicant( 1449): wpa_driver_nl80211_driver_cmd: failed to issue private commands
,E/WifiStateMachine(  892): Unexpected BatchedScanResults :null
E/wpa_supplicant( 1449): wpa_driver_nl80211_driver_cmd: failed to issue private commands
D/WifiP2pService(  892): InactiveState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@1ab0e9e6 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  892): P2pEnabledState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@1ab0e9e6 target=com.android.internal.util.StateMachine$SmHandler }
,I/ActivityManager(  892): Start proc com.motorola.context for broadcast com.motorola.context/.publisher.location.LocationReceiver: pid=6554 uid=10008 gids={50008, 9997, 3001, 3002, 3003} abi=armeabi-v7a
,I/art     (  309): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 246us total 25.530ms
,I/art     (  309): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 255us total 19.367ms
,I/art     (  309): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 248us total 20.206ms
,W/ResourcesManager( 6554): Asset path '/system/framework/com.motorola.motosignature.jar' does not exist or contains no resources.
,W/VideoCapabilities( 6513): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 6513): Unsupported mime audio/amr-wb-plus
,W/VideoCapabilities( 6513): Unsupported mime video/mpeg2
,I/VideoCapabilities( 6513): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 6513): Unrecognized profile 2130706433 for video/avc
,E/DHCPCD  ( 6571): fopen `/system/etc/dhcpcd/dhcpcd.conf': m
,I/DHCPCD  ( 6571): version 5.5.6 starting
E/DHCPCD  ( 6571): fopen `/system/etc/dhcpcd/dhcpcd.conf': m
,D/DHCPCD  ( 6571): wlan0: using ClientID 01:44:80:eb:7b:5a:06
D/DHCPCD  ( 6571): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
,W/VideoCapabilities( 6513): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6513): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6513): Unrecognized profile 2130706433 for video/avc
,I/ActivityManager(  892): Killing 6296:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,D/DHCPCD  ( 6571): wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
I/DHCPCD  ( 6571): wlan0: rebinding lease of 192.168.1.123
D/DHCPCD  ( 6571): wlan0: sending REQUEST (xid 0x55e992fb), next in 3.62 seconds
,W/libprocessgroup(  892): failed to open /acct/uid_10090/pid_6296/cgroup.procs: No such file or directory
,I/vclib   ( 6513): onServiceConnected
W/Babel   ( 6513): Attempted to change video mute state without an active call.
,I/ActivityManager(  892): Killing 6332:android.process.acore/u0a7 (adj 15): empty #7
,W/libprocessgroup(  892): failed to open /acct/uid_10007/pid_6332/cgroup.procs: No such file or directory
,I/DHCPCD  ( 6571): wlan0: acknowledged 192.168.1.123 from 192.168.1.1
,I/DHCPCD  ( 6571): wlan0: leased 192.168.1.123 for 86400 seconds
D/DHCPCD  ( 6571): wlan0: adding IP address 192.168.1.123/24
D/DHCPCD  ( 6571): wlan0: adding route to 192.168.1.0/24
D/DHCPCD  ( 6571): wlan0: adding default route via 192.168.1.1
D/DHCPCD  ( 6571): wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
D/TCMD    (  483): NL - Read 60 bytes from update socket.
D/TCMD    (  483): NL - ignore NL message, type = 20
D/TCMD    (  483): Listening for incoming client connection request
,D/DHCPCD  ( 6571): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
,E/WifiStateMachine(  892): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
,E/WifiStateMachine(  892): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES v4
,E/WifiStateMachine(  892): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
E/WifiStateMachine(  892): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
E/native  (  892): do suspend true
,D/WifiP2pService(  892): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  892): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,E/WifiStateMachine(  892): WifiStateMachine DHCP successful
E/WifiStateMachine(  892): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,E/WifiStateMachine(  892): updateLinkProperties nid: 0 state: CONNECTING reason: DHCP_SUCCESS v4 v4r v4dns isprov
E/WifiStateMachine(  892): Calling ARP set with IP = 192.168.1.123
,E/WifiStateMachine(  892): setDetailed state, old =CONNECTING and new state=CAPTIVE_PORTAL_CHECK hidden=false
,I/SBar.MotoNetworkCtrlr( 1303): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1303): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1303): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1303): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,E/WifiStateMachine(  892): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED hidden=false
,D/ConnectivityService(  892): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
D/ConnectivityService(  892): Adding iface wlan0 to network 101
,I/SBar.MotoNetworkCtrlr( 1303): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1303): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1303): refreshSignalCluster[0]: wifi: mWifiConnected=true Wifi=0x7f020129=com.android.systemui:drawable/stat_sys_wifi_signal_0 Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
,E/WifiStateMachine(  892): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,D/Checkin (  892): publish the event [tag = MOT_WIFI_L1 event name = CONNECT]
,I/SBar.MotoNetworkCtrlr( 1303): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,E/ConnectivityService(  892): Unexpected mtu value: 0, wlan0
D/ConnectivityService(  892): Adding Route [fe80::/64 -> :: wlan0] to network 101
I/SBar.MotoNetworkCtrlr( 1303): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/ConnectivityService(  892): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
D/ConnectivityService(  892): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
D/ConnectivityService(  892): Setting Dns servers for network 101 to [/192.168.1.1]
,E/WifiStateMachine(  892): ConnectedState Enter  mScreenOn=false scanperiod=20000
,D/Checkin (  892): publish the event [tag = MOT_WIFI_L1 event name = CONNECT]
,D/Nat464Xlat(  892): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  892): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  892): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  892): rematching NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityService(  892):    accepting network in place of null
,D/ConnectivityService(  892): UpdateTcpBufferSizes: same sizes as current, ignore operation
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  892): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  892): Connected
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  892): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  892): Checking http://clients3.google.com/generate_204 on "NG700"
,D/CSLegacyTypeTracker(  892): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,D/ConnectivityService(  892): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
I/ModemStatsDSDetect( 1549): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
I/SBar.MotoNetworkCtrlr( 1303): onReceive: CONNECTIVITY_ACTION_IMMEDIATE Recieved, mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/ConnectivityService(  892): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
,I/SBar.MotoNetworkCtrlr( 1303): updateConnectivity[0]: NetworkInfo: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false], raw inetCondition= 0
I/SBar.MotoNetworkCtrlr( 1303): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1303): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1303): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/ModemStatsDSDetect( 1549): INET_CONDITION=0 ,activeNet=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/ModemStatsDSDetect( 1549): onReceive() - done, currentInetCondition=0
D/ConnectivityService(  892): UpdateTcpBufferSizes: same sizes as current, ignore operation
D/ConnectivityService(  892): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityManager.CallbackHandler( 1303): CM callback handler got msg 524290
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  892): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 13 Jan 2016 15:37:18 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1452699438837], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1452699438815]}
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  892): Don't send network conditions - lacking user consent.
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  892): Validated
,D/ConnectivityService(  892): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  892): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  892): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService(  892): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  892): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/ConnectivityManager.CallbackHandler( 1303): CM callback handler got msg 524290
,I/SBar.MotoNetworkCtrlr( 1303): onReceive: INET_CONDITION_ACTION Recieved, mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/ModemStatsDSDetect( 1549): onReceive() -Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) }
,I/ModemStatsDSDetect( 1549): INET_CONDITION=100 ,activeNet=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/ModemStatsDSDetect( 1549): Inetcondition changed, white->blue
,I/ModemStatsDSDetect( 1549): onReceive() - done, currentInetCondition=100
I/SBar.MotoNetworkCtrlr( 1303): updateConnectivity: The netConditon[0] for netType 1=WiFi is updated as 1=good by android.net.conn.INET_CONDITION_ACTION, icon color should be white (on KK); without "!" (on L).
I/SBar.MotoNetworkCtrlr( 1303): updateConnectivity[0]: NetworkInfo: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false], raw inetCondition= 1
I/SBar.MotoNetworkCtrlr( 1303): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1303): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1303): refreshSignalCluster[0]: wifi: mWifiConnected=true Wifi=0x7f02012a=com.android.systemui:drawable/stat_sys_wifi_signal_0_fully Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
I/SBar.MotoNetworkCtrlr( 1303): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/ConnectivityService(  892): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  892): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/PollingManager( 2602): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/Tethering(  892): MasterInitialState.processMessage what=3
,D/Central_PollingManager( 1482): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/Tethering(  892): MasterInitialState.processMessage what=3
,W/ContextImpl( 1482): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1469 android.content.ContextWrapper.sendBroadcast:381 com.motorola.blur.service.blur.BSUtils.sendBroadcast:94 com.motorola.blur.service.blur.BSUtils.sendBroadcast:90 com.motorola.ccc.plm.pollingmanager.PollingManagerService$MyConnectivityReceiver.onReceive:491 
,D/PollingManager( 2602): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/PollingManager( 2602): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/OtaApp  ( 2602): [debug] > pollingManagerService, connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ActivityManager(  892): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=6639 uid=10080 gids={50080, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/Central_PollingManager( 1482): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/Central_PollingManager( 1482): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
,D/PollingManager( 2602): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/PollingManager( 2602): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
,D/PollingManager( 2602): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/PollingManager( 2602): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
D/PollingManager( 2602): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/PollingManager( 2602): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
D/OtaApp  ( 2602): [debug] > pollingManagerService, connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/OtaApp  ( 2602): [debug] > PollingManagerService, not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
,D/CCE     ( 2602): Registering with Alarm Manager to restart CCE
,D/CCE     ( 2602): Registering with Alarm Manager to restart CCE
,D/CCE     ( 2602): Registering with Alarm Manager to restart CCE
,D/OtaApp  ( 2602): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.ccc.ota.pm.POLLINGMGR_CONNECTIVITY
D/OtaApp  ( 2602): [debug] > CusSM.onRadioDown
,I/MusicStore( 6639): Database version: 120
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6639): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6639): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
,W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6639): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,W/ResourcesManager( 6639): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 6639): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 6639): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 6639): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 6639): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@3bbb274e: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6639): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 6639): GMSCore installation verified
,I/ConfigStore( 6639): Config Database version: 1
,I/MediaRouter( 6639): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 6639): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/NetworkMonitor( 6639): type=WIFI subType= reason=null isConnected=true
,I/NetworkMonitor( 6639): type=WIFI subType= reason=null isConnected=true
,D/ConnectivityService(  892): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,I/ActivityManager(  892): Start proc com.android.mms for broadcast com.android.mms/.transaction.MmsSystemEventReceiver: pid=6673 uid=10023 gids={50023, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/GHttpClientFactory( 6639): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 6639): Using platform SSLCertificateSocketFactory
,I/ActivityManager(  892): Killing 6224:com.google.android.googlequicksearchbox:search/u0a39 (adj 15): empty #7
,W/libprocessgroup(  892): failed to open /acct/uid_10039/pid_6224/cgroup.procs: No such file or directory
,V/Mms     ( 6673): mnc/mcc: 
,V/Mms     ( 6673): tag: int value: recipientLimit - 20
V/Mms     ( 6673): tag: int value: smsToMmsTextThreshold - 6
V/Mms     ( 6673): tag: int value: emergencySmsTimeout - 30
,V/Mms     ( 6673): tag: int value: maxSubjectLength - 80
,V/Mms     ( 6673): tag: bool value: smsForceShowEncodingMenu - true
V/Mms     ( 6673): tag: bool value: enableGroupMms - false
V/Mms     ( 6673):  mUserAgent = MOT-XT1072/Mms-5.0,  mUaProfUrl = http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/ResourcesManager( 6673): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/ActivityManager(  892): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=6699 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  892): Killing 6136:com.android.vending/u0a32 (adj 15): empty #7
,W/libprocessgroup(  892): failed to open /acct/uid_10032/pid_6136/cgroup.procs: No such file or directory
,D/PhoneMonitor( 6699): Register our PhoneStateListener
,D/MobileConnectivityChangeReceiver( 6699): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 6699): onReceive CONNECTIVITY_CHANGE networkType=1
,I/ActivityManager(  892): Killing 6513:com.google.android.talk/u0a70 (adj 15): empty #7
,E/WifiStateMachine(  892): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,fe80::4680:ebff:fe7b:5a06/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
E/WifiStateMachine(  892): updateLinkProperties nid: 0 state: CONNECTED reason: CMD_UPDATE_LINKPROPERTIES v4 v4r v4dns isprov
,D/ConnectivityService(  892): UpdateTcpBufferSizes: same sizes as current, ignore operation
D/Nat464Xlat(  892): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  892): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityManager.CallbackHandler( 1303): CM callback handler got msg 524295
,W/libprocessgroup(  892): failed to open /acct/uid_10070/pid_6513/cgroup.procs: No such file or directory
,I/CheckinService( 6089): Checkin interval check for package: unspecified last checkin: 1452699350018 min interval config: 0 actual interval: 90454
,I/CheckinService( 6089): Disabling old GoogleServicesFramework version
,I/iu.SyncManager( 6089): SYNC; picasa accounts
,I/CheckinService( 6089): Checking schedule, now: 1452699440504 next: 1452699379994
I/CheckinService( 6089): active receiver: enabled
,I/CheckinService( 6089): Preparing to send checkin request
,D/NetworkLogImpl( 6089): Loaded NetworkSpeedPredictor
,I/iu.Environment( 6089): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/EventLogService( 6089): Accumulating logs since 1452699347050
,I/iu.UploadsManager( 6089): num queued entries: 0
I/iu.UploadsManager( 6089): num updated entries: 0
I/iu.SyncManager( 6089): NEXT; no task
,I/ActivityManager(  892): Start proc com.google.android.apps.photos for broadcast com.google.android.apps.photos/.jobqueue.JobServiceBroadcastReceiver: pid=6727 uid=10088 gids={50088, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
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
,I/CheckinRequestBuilder( 6089): Checkin reason type: 8 attempt count: 1
D/WifiService(  892): New client listening to asynchronous messages
E/ActivityThread( 6089): Failed to find provider info for com.google.android.wearable.settings
,V/GLSActivity( 1766): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1766): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  892): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6752 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,W/ResourcesManager( 6752): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/ActivityManager(  892): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=6770 uid=10016 gids={50016, 9997, 3003, 1028, 1015, 3002, 3001, 1005, 1007, 3007, 2001, 3006} abi=armeabi-v7a
,I/art     (  892): Explicit concurrent mark sweep GC freed 32026(1577KB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 20MB/30MB, paused 1.714ms total 121.528ms
,W/ResourcesManager( 6770): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6770): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/MultiDex( 6770): VM with version 2.1.0 has multidex support
I/MultiDex( 6770): install
I/MultiDex( 6770): VM has multidex support, MultiDex support library is disabled.
,V/JNIHelp ( 6770): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 6770): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 6770): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@12f5f397: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6770): Installed default security provider GmsCore_OpenSSL
,I/Babel_SMS( 6752): MmsConfig: mnc/mcc: 0/0
,I/Babel_SMS( 6752): MmsConfig.loadMmsSettings
I/Babel_SMS( 6752): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
I/Babel_SMS( 6752): MmsConfig.loadFromDatabase
,E/Babel_SMS( 6752): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 6752): MmsConfig.loadFromResources
E/Babel_SMS( 6752): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 6752): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,I/art     ( 6770): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 6770): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,W/Settings( 6752): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 6752): startup - clean
,I/Babel   ( 6752): deleted: false for 0
D/NativeLibraryUtils( 6770): Install completed successfully. count=14 extracted=0
,I/ActivityManager(  892): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=6800 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/ConnectivityService(  892): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
D/Tethering(  892): MasterInitialState.processMessage what=3
,D/PollingManager( 2602): connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/PollingManager( 2602): now: 206528 ,futureTime: 9223372036854775807
D/Central_PollingManager( 1482): connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/ContextImpl( 1482): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1469 android.content.ContextWrapper.sendBroadcast:381 com.motorola.blur.service.blur.BSUtils.sendBroadcast:94 com.motorola.blur.service.blur.BSUtils.sendBroadcast:90 com.motorola.ccc.plm.pollingmanager.PollingManagerService$MyConnectivityReceiver.onReceive:491 
,D/PollingManager( 2602): connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/PollingManager( 2602): now: 206531 ,futureTime: 9223372036854775807
D/PollingManager( 2602): connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/PollingManager( 2602): now: 206531 ,futureTime: 9223372036854775807
D/Central_PollingManager( 1482): now: 206532 ,futureTime: 86476611
D/Central_PollingManager( 1482): Polling alarm set to expire at: 86476611 Current Time: 206532
,D/OtaApp  ( 2602): [debug] > pollingManagerService, connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/OtaApp  ( 2602): [debug] > PollingManagerService, now: 206535 ,futureTime: 8824280
,I/NetworkMonitor( 6639): type=WIFI subType= reason=null isConnected=true
,D/OtaApp  ( 2602): [debug] > Polling alarm set to expire at: 8824280 Current Time: 206536
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:31000 mC
,D/MMApiProvisionService( 2602): isDeviceProvisioned: deviceId = 2072049230914535424
D/WVCdm   (  295): Instantiating CDM.
,I/WVCdm   (  295): CdmEngine::OpenSession
,I/WVCdm   (  295): Level3 Library Sep 25 2014 17:10:03
,W/WVCdm   (  295): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,D/CCE     ( 2602): trying to auto login since I haven't yet and the radio is up now
I/MMApiProvisionService( 2602): createDeviceIdOrLogin update_device
,D/Checkin ( 2602): publish the event [tag = MOT_CCE event name = LOG]
D/MMApiProvisionService( 2602): Not proxy app, so login/provision not allowed
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
,D/MMApiProvisionService( 2602): isDeviceProvisioned: deviceId = 2072049230914535424
,D/CCE     ( 2602): trying to auto login since I haven't yet and the radio is up now
I/MMApiProvisionService( 2602): createDeviceIdOrLogin update_device
D/Checkin ( 2602): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiProvisionService( 2602): isDeviceProvisioned: deviceId = 2072049230914535424
,D/QSEECOMAPI: (  295): Loaded image: APP id = 3
,D/DrmWidevineDash(  295): Service_Initialize: ends! returns 0
D/DrmWidevineDash(  295): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4f6e000
E/DrmWidevineDash(  295): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4f6e000
,D/MMApiProvisionService( 2602): set mOutstandingReq to true.
D/DrmWidevineDash(  295): OEMCrypto_Initialize: ends! returns 0
,I/ Nonce  ( 2602):  Nonce getNonce 
D/DrmWidevineDash(  295): OEMCrypto_APIVersion: starts!
I/ Nonce  ( 2602):  Nonce Request 
I/ Nonce  ( 2602):  Nonce execute Request 
D/DrmWidevineDash(  295): hlos api version =  9
D/DrmWidevineDash(  295): tz api version =  8
D/DrmWidevineDash(  295): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  295): OEMCrypto_IsKeyboxValid: starts!
D/MMApiWebService( 2602): doRequest() with req : MMApiWSRequest(/v1/gdi/nonce.json)
,D/DrmWidevineDash(  295): OEMCrypto_IsKeyboxValid: ends! returns 0
D/WVCdm   (  295): OEMCrypto_Initialize Level 1 success. I will use level 1.
D/DrmWidevineDash(  295): OEMCrypto_OpenSession: starts! SID=0xb5549960
D/DrmWidevineDash(  295): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  295): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  295): OEMCrypto_GetRandom: starts! randomData=0xb74052c0, dataLength=8
D/DrmWidevineDash(  295): OEMCrypto_GetRandom: ends! returns 0
D/DrmWidevineDash(  295): OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb7417c80, wrapped_rsa_key_length=1280
D/DrmWidevineDash(  295): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
,I/WVCdm   (  295): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  295): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  295): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  295): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  295): OEMCrypto_GetDeviceID: starts! deviceID=0xb7538808, idLength=0xb135f730
,D/MMApiProvisionService( 2602): isDeviceProvisioned: deviceId = 2072049230914535424
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
D/WVCdm   (  295): PrepareKeyRequest: nonce=3125910026
D/DrmWidevineDash(  295): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb74706f0
D/DrmWidevineDash(  295): message_length=1591, signature=0xb74069c8, signature_length=2973103892
,D/CCE     ( 2602): trying to auto login since I haven't yet and the radio is up now
I/MMApiProvisionService( 2602): createDeviceIdOrLogin update_device
D/Checkin ( 2602): publish the event [tag = MOT_CCE event name = LOG]
D/MMApiProvisionService( 2602): Not proxy app, so login/provision not allowed
D/OtaApp  ( 2602): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.ccc.ota.pm.POLLINGMGR_CONNECTIVITY
D/OtaApp  ( 2602): [debug] > CusSM.onRadioUp
,W/VideoCapabilities( 6752): Unrecognized profile 2130706433 for video/avc
,D/OtaApp  ( 2602): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
D/OtaApp  ( 2602): [debug] > CusSM.runStateMachine: getVersions's version Blur_Version.22.21.28.thea_reteu.reteuall.en.EU; getDescription's versionBlur_Version.22.21.28.thea_reteu.reteuall.en.EU
,I/OtaApp  ( 2602): [info] > CusSM.runStateMachine: found version Blur_Version.22.21.28.thea_reteu.reteuall.en.EU in database with state (RequestPermission)
,D/Checkin ( 2602): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 2602): [debug] > CusSM.runStateMachine: server told to :continue
D/OtaApp  ( 2602): [debug] > CusSM.runStateMachine: user is being notified for version Blur_Version.22.21.28.thea_reteu.reteuall.en.EU
D/OtaApp  ( 2602): [debug] > CusSM.runStateMachine: getDownloadOptStartStopTime text null
,D/OtaApp  ( 2602): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,W/AudioCapabilities( 6752): Unsupported mime audio/amr-wb-plus
,W/VideoCapabilities( 6752): Unsupported mime video/mpeg2
,I/VideoCapabilities( 6752): Unsupported profile 4 for video/mp4v-es
,D/MMApiWebService( 2602): generating token using payload instead of using session token
,W/VideoCapabilities( 6752): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6752): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6752): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6752): Unrecognized profile 2130706433 for video/avc
,D/DrmWidevineDash(  295): OEMCrypto_GenerateRSASignature returns 0
,I/vclib   ( 6752): onServiceConnected
W/Babel   ( 6752): Attempted to change video mute state without an active call.
,I/WVCdm   (  295): CdmEngine::CloseSession
D/DrmWidevineDash(  295): OEMCrypto_CloseSession: starts! SID=1
D/DrmWidevineDash(  295): OEMCrypto_CloseSession: ends! returns 0
I/WVCdm   (  295): L3 Terminate.
D/DrmWidevineDash(  295): OEMCrypto_Terminate: starts!
D/DrmWidevineDash(  295): Service_Uninitialize: starts!
D/QSEECOMAPI: (  295): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  295): QSEECom_shutdown_app, app_id = 3
,D/DrmWidevineDash(  295): Service_Uninitialize: ends! returns 0x0
D/DrmWidevineDash(  295): OEMCrypto_Terminate: ends! returns 0
,D/ Nonce  ( 2602):  getUrl method url https://argo.svcmot.com:443/v1/gdi/nonce.json/ZX1C223JKW?appid=6R1TANEX3ZMQ6EU1UH43P34C8B868KTE
,I/MMApiWSBase( 2602): doRequest(): url: https://argo.svcmot.com:443/v1/gdi/nonce.json/ZX1C223JKW?appid=6R1TANEX3ZMQ6EU1UH43P34C8B868KTE
D/Checkin ( 2602): publish the event [tag = MOT_CCE event name = LOG]
,I/Babel   ( 6752): connection state changed from UNKNOWN to CONNECTED
,I/ActivityManager(  892): Killing 6554:com.motorola.context/u0a8 (adj 15): empty #7
,W/libprocessgroup(  892): failed to open /acct/uid_10008/pid_6554/cgroup.procs: No such file or directory
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6800): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
,W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6800): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6800): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6800): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,I/GAv4    ( 6800): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 6800):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 6800):   adb logcat -s GAv4
,W/GAv4    ( 6800): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 6800): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 6800): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/WVCdm   (  295): CdmEngine::OpenSession
,I/WVCdm   (  295): Level3 Library Sep 25 2014 17:10:03
W/WVCdm   (  295): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
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
D/DrmWidevineDash(  295): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4f6e000
E/DrmWidevineDash(  295): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4f6e000
,D/DrmWidevineDash(  295): OEMCrypto_Initialize: ends! returns 0
D/DrmWidevineDash(  295): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  295): hlos api version =  9
D/DrmWidevineDash(  295): tz api version =  8
D/DrmWidevineDash(  295): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  295): OEMCrypto_IsKeyboxValid: starts!
,D/DrmWidevineDash(  295): OEMCrypto_IsKeyboxValid: ends! returns 0
D/WVCdm   (  295): OEMCrypto_Initialize Level 1 success. I will use level 1.
D/DrmWidevineDash(  295): OEMCrypto_OpenSession: starts! SID=0xb135f960
D/DrmWidevineDash(  295): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  295): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  295): OEMCrypto_GetRandom: starts! randomData=0xb7405438, dataLength=8
D/DrmWidevineDash(  295): OEMCrypto_GetRandom: ends! returns 0
D/DrmWidevineDash(  295): OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb74ecf58, wrapped_rsa_key_length=1280
D/DrmWidevineDash(  295): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
I/WVCdm   (  295): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  295): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
,W/WVCdm   (  295): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
,I/WVCdm   (  295): CdmEngine::GenerateKeyRequest
,D/DrmWidevineDash(  295): OEMCrypto_GetDeviceID: starts! deviceID=0xb7538848, idLength=0xbef212b0
,D/DrmWidevineDash(  295): OEMCrypto_GetDeviceID: ends! returns 0
,D/DrmWidevineDash(  295): OEMCrypto_SupportsUsageTable: starts!
,D/DrmWidevineDash(  295): OEMCrypto_SupportsUsageTable: is_supported = 1
,D/DrmWidevineDash(  295): OEMCrypto_SupportsUsageTable: wv_app_version = 25
D/DrmWidevineDash(  295): OEMCrypto_SupportsUsageTable: ends! returns 0x0
D/DrmWidevineDash(  295): OEMCrypto_GetHDCPCapability: starts!
D/DrmWidevineDash(  295): OEMCrypto_GetHDCPCapability: ends! returns 0x0
D/DrmWidevineDash(  295): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  295): hlos api version =  9
D/DrmWidevineDash(  295): tz api version =  8
,D/DrmWidevineDash(  295): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  295): OEMCrypto_GenerateNonce: starts! SID=1
D/DrmWidevineDash(  295): OEMCrypto_GenerateNonce: ends! returns 0
D/WVCdm   (  295): PrepareKeyRequest: nonce=1478846566
D/DrmWidevineDash(  295): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb74706f0
D/DrmWidevineDash(  295): message_length=1626, signature=0xb74069c8, signature_length=3203535508
,I/WebViewFactory( 6800): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 6800): Time to load native libraries: 2 ms (timestamps 7678-7680)
,I/LibraryLoader( 6800): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 6800): Binding Chromium to main looper Looper (main, tid 1) {4a4f087}
,I/LibraryLoader( 6800): Expected native library version number "",actual native library version number ""
I/chromium( 6800): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 6800): Initializing chromium process, singleProcess=true
W/art     ( 6800): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 6800): ApplicationContext is null in ApplicationStatus
,D/DrmWidevineDash(  295): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  295): CdmEngine::CloseSession
,D/DrmWidevineDash(  295): OEMCrypto_CloseSession: starts! SID=1
D/DrmWidevineDash(  295): OEMCrypto_CloseSession: ends! returns 0
I/WVCdm   (  295): L3 Terminate.
D/DrmWidevineDash(  295): OEMCrypto_Terminate: starts!
,D/DrmWidevineDash(  295): Service_Uninitialize: starts!
D/QSEECOMAPI: (  295): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  295): QSEECom_shutdown_app, app_id = 3
D/DrmWidevineDash(  295): Service_Uninitialize: ends! returns 0x0
D/DrmWidevineDash(  295): OEMCrypto_Terminate: ends! returns 0
,W/chromium( 6800): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 6800): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,E/libEGL  ( 6800): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 6800): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 6800): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 6800): Build Date: 10/28/14 Tue
I/Adreno-EGL( 6800): Local Branch: 
I/Adreno-EGL( 6800): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 6800): Local Patches: NONE
I/Adreno-EGL( 6800): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/dex2oat ( 6854): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=36 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
W/AudioManagerAndroid( 6800): Requires BLUETOOTH permission
,I/NSApplication( 6800): Starting up...
,I/ActivityManager(  892): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=6872 uid=10052 gids={50052, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  892): Killing 6639:com.google.android.music:main/u0a80 (adj 15): empty #7
,I/dex2oat ( 6854): dex2oat took 103.811ms (threads: 4)
,I/Adreno-EGL( 6770): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 6770): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 6770): Build Date: 10/28/14 Tue
I/Adreno-EGL( 6770): Local Branch: 
I/Adreno-EGL( 6770): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 6770): Local Patches: NONE
I/Adreno-EGL( 6770): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/Adreno-EGL( 6770): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 6770): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 6770): Build Date: 10/28/14 Tue
I/Adreno-EGL( 6770): Local Branch: 
I/Adreno-EGL( 6770): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 6770): Local Patches: NONE
I/Adreno-EGL( 6770): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,W/libprocessgroup(  892): failed to open /acct/uid_10080/pid_6639/cgroup.procs: No such file or directory
,I/Adreno-EGL( 6770): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 6770): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 6770): Build Date: 10/28/14 Tue
I/Adreno-EGL( 6770): Local Branch: 
I/Adreno-EGL( 6770): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 6770): Local Patches: NONE
I/Adreno-EGL( 6770): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/ Nonce  ( 2602):  Nonce Reponse 
D/        ( 2602): ProvisionWS.Response: processing response data: {"error":"OK","nonce":"42bafe99-e489-4afd-a01d-a118c8332803"}
D/MMApiWSBase( 2602): doRequest(): /v1/gdi/nonce.json resp length: 61
,I/ Nonce  ( 2602):  Nonce Handle Reponse 
,D/MMApiProvisionService( 2602): mOutstandingReq set to false
,I/Adreno-EGL( 6770): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 6770): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 6770): Build Date: 10/28/14 Tue
I/Adreno-EGL( 6770): Local Branch: 
I/Adreno-EGL( 6770): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 6770): Local Patches: NONE
I/Adreno-EGL( 6770): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/art     ( 2602): Explicit concurrent mark sweep GC freed 18137(1043KB) AllocSpace objects, 1(16KB) LOS objects, 39% free, 11MB/19MB, paused 1.018ms total 61.455ms
,D/MMApiProvisionService( 2602):  pTime 1452672215335 sExp 172742 cTime 1452699443507 tTime 1452844957335
D/MMApiProvisionService( 2602):  No login Required 
,I/ActivityManager(  892): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=6892 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  892): Killing 6673:com.android.mms/u0a23 (adj 15): empty #7
,W/libprocessgroup(  892): failed to open /acct/uid_10023/pid_6673/cgroup.procs: No such file or directory
,W/ResourcesManager( 6892): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/CheckinRequestBuilder( 6089): Classify the device as Phone.
,W/DataUsage( 2602): invalid counter update blocked: 'err' by 0
,D/Checkin ( 2602): publish the event [tag = MOT_CCE event name = LOG]
,V/AlarmManager(  892): send {32921255, *walarm*:com.google.android.intent.action.GCM_RECONNECT}
,I/CheckinTask( 6089): Sending checkin request (9509 bytes)
,I/ActivityManager(  892): Start proc android.process.acore for content provider com.android.providers.contacts/.ContactsProvider2: pid=6919 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,I/ActivityManager(  892): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=6940 uid=10080 gids={50080, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  892): Killing 6727:com.google.android.apps.photos/u0a88 (adj 15): empty #7
,I/art     (  309): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 254us total 30.407ms
,I/art     (  309): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 262us total 19.408ms
,I/art     (  309): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 270us total 20.431ms
,I/ContactLocale( 6919): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,I/CheckinRequestBuilder( 6089): Checkin reason type: 8 attempt count: 1
,I/ActivityManager(  892): Killing 6699:com.google.android.setupwizard/u0a35 (adj 15): empty #8
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
,W/libprocessgroup(  892): failed to open /acct/uid_10088/pid_6727/cgroup.procs: No such file or directory
,W/libprocessgroup(  892): failed to open /acct/uid_10035/pid_6699/cgroup.procs: No such file or directory
,E/ActivityThread( 6089): Failed to find provider info for com.google.android.wearable.settings
,I/MusicStore( 6940): Database version: 120
,I/art     (  892): Explicit concurrent mark sweep GC freed 10659(507KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 20MB/30MB, paused 2.079ms total 134.302ms
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
,W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6940): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,I/art     ( 4648): Explicit concurrent mark sweep GC freed 1568(56KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 7MB/9MB, paused 371us total 22.943ms
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6940): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
,W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6940): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,W/ResourcesManager( 6940): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6940): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/CheckinRequestBuilder( 6089): Classify the device as Phone.
,I/CheckinTask( 6089): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 6089): Checking schedule, now: 1452699444990 next: 1453300581980
,I/CheckinService( 6089): active receiver: disabled
,V/JNIHelp ( 6940): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,D/CheckinService( 6089): Recording last checkin time for package unspecified as 1452699445005
,I/ActivityManager(  892): Killing 6752:com.google.android.talk/u0a70 (adj 15): empty #7
,W/ActivityThread( 6940): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 6940): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@3bbb274e: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6940): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 6940): GMSCore installation verified
,W/libprocessgroup(  892): failed to open /acct/uid_10070/pid_6752/cgroup.procs: No such file or directory
,I/ConfigStore( 6940): Config Database version: 1
,I/MediaRouter( 6940): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 6940): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/NetworkMonitor( 6940): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  892): Killing 6800:com.google.android.apps.magazines/u0a81 (adj 13): empty #7
,W/libprocessgroup(  892): failed to open /acct/uid_10081/pid_6800/cgroup.procs: No such file or directory
,I/NetworkMonitor( 6940): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  892): Start proc com.android.mms for broadcast com.android.mms/.transaction.MmsSystemEventReceiver: pid=7001 uid=10023 gids={50023, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/GHttpClientFactory( 6940): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 6940): Using platform SSLCertificateSocketFactory
,I/ActivityManager(  892): Killing 6872:com.android.chrome/u0a52 (adj 15): empty #7
,V/Mms     ( 7001): mnc/mcc: 
V/Mms     ( 7001): tag: int value: recipientLimit - 20
V/Mms     ( 7001): tag: int value: smsToMmsTextThreshold - 6
V/Mms     ( 7001): tag: int value: emergencySmsTimeout - 30
,V/Mms     ( 7001): tag: int value: maxSubjectLength - 80
,V/Mms     ( 7001): tag: bool value: smsForceShowEncodingMenu - true
V/Mms     ( 7001): tag: bool value: enableGroupMms - false
V/Mms     ( 7001):  mUserAgent = MOT-XT1072/Mms-5.0,  mUaProfUrl = http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/libprocessgroup(  892): failed to open /acct/uid_10052/pid_6872/cgroup.procs: No such file or directory
,W/ResourcesManager( 7001): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/ActivityManager(  892): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=7032 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  892): Killing 6892:com.google.android.apps.plus/u0a90 (adj 13): empty #7
,D/PhoneMonitor( 7032): Register our PhoneStateListener
,W/libprocessgroup(  892): failed to open /acct/uid_10090/pid_6892/cgroup.procs: No such file or directory
,D/MobileConnectivityChangeReceiver( 7032): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 7032): onReceive CONNECTIVITY_CHANGE networkType=1
,I/ActivityManager(  892): Killing 6919:android.process.acore/u0a7 (adj 15): empty #7
,W/libprocessgroup(  892): failed to open /acct/uid_10007/pid_6919/cgroup.procs: No such file or directory
,I/CheckinService( 6089): Checkin interval check for package: unspecified last checkin: 1452699445005 min interval config: 0 actual interval: 1665
,I/ActivityManager(  892): Start proc com.google.android.apps.photos for broadcast com.google.android.apps.photos/.jobqueue.JobServiceBroadcastReceiver: pid=7054 uid=10088 gids={50088, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/CheckinService( 6089): Checking schedule, now: 1452699446783 next: 1452699474980
I/CheckinService( 6089): active receiver: disabled
,I/ActivityManager(  892): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=7077 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
I/ActivityManager(  892): Killing 6940:com.google.android.music:main/u0a80 (adj 13): empty #7
,W/libprocessgroup(  892): failed to open /acct/uid_10080/pid_6940/cgroup.procs: No such file or directory
,W/ResourcesManager( 7077): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/Babel_SMS( 7077): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 7077): MmsConfig.loadMmsSettings
I/Babel_SMS( 7077): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
I/Babel_SMS( 7077): MmsConfig.loadFromDatabase
,E/Babel_SMS( 7077): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 7077): MmsConfig.loadFromResources
,E/Babel_SMS( 7077): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 7077): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/Settings( 7077): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 7077): startup - clean
,I/Babel   ( 7077): deleted: false for 0
,I/ActivityManager(  892): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7115 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/VideoCapabilities( 7077): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 7077): Unsupported mime audio/amr-wb-plus
,W/VideoCapabilities( 7077): Unsupported mime video/mpeg2
,I/VideoCapabilities( 7077): Unsupported profile 4 for video/mp4v-es
W/VideoCapabilities( 7077): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 7077): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 7077): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7077): Unrecognized profile 2130706433 for video/avc
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,I/vclib   ( 7077): onServiceConnected
,W/Babel   ( 7077): Attempted to change video mute state without an active call.
W/ContextImpl( 7115): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,I/GAv4    ( 7115): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 7115):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 7115):   adb logcat -s GAv4
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7115): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7115): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7115): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,W/GAv4    ( 7115): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,I/Babel   ( 7077): connection state changed from UNKNOWN to CONNECTED
,I/ActivityManager(  892): Killing 7001:com.android.mms/u0a23 (adj 13): empty #7
,W/GAv4    ( 7115): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 7115): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,W/libprocessgroup(  892): failed to open /acct/uid_10023/pid_7001/cgroup.procs: No such file or directory
,I/jxcore-log( 6444): Test app app.js loaded
I/jxcore-log( 6444): 
,I/chromium( 6444): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/WebViewFactory( 7115): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 7115): Time to load native libraries: 1 ms (timestamps 3260-3261)
,I/LibraryLoader( 7115): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 7115): Binding Chromium to main looper Looper (main, tid 1) {4a4f087}
,I/LibraryLoader( 7115): Expected native library version number "",actual native library version number ""
,I/chromium( 7115): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 7115): Initializing chromium process, singleProcess=true
,W/art     ( 7115): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 7115): ApplicationContext is null in ApplicationStatus
,W/chromium( 7115): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 7115): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 7115): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 7115): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 7115): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7115): Build Date: 10/28/14 Tue
I/Adreno-EGL( 7115): Local Branch: 
I/Adreno-EGL( 7115): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 7115): Local Patches: NONE
I/Adreno-EGL( 7115): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,W/AudioManagerAndroid( 7115): Requires BLUETOOTH permission
,I/NSApplication( 7115): Starting up...
,I/ActivityManager(  892): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=7188 uid=10052 gids={50052, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  892): Killing 7032:com.google.android.setupwizard/u0a35 (adj 15): empty #7
,W/libprocessgroup(  892): failed to open /acct/uid_10035/pid_7032/cgroup.procs: No such file or directory
,I/ActivityManager(  892): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7207 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  892): Killing 7054:com.google.android.apps.photos/u0a88 (adj 15): empty #7
,W/libprocessgroup(  892): failed to open /acct/uid_10088/pid_7054/cgroup.procs: No such file or directory
,W/ResourcesManager( 7207): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/ActivityManager(  892): Start proc android.process.acore for content provider com.android.providers.contacts/.ContactsProvider2: pid=7230 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,I/ActivityManager(  892): Killing 7115:com.google.android.apps.magazines/u0a81 (adj 15): empty #7
,I/art     (  892): Explicit concurrent mark sweep GC freed 11654(591KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 20MB/30MB, paused 2.545ms total 126.712ms
,I/ContactLocale( 7230): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,I/ActivityManager(  892): Killing 7077:com.google.android.talk/u0a70 (adj 15): empty #8
,D/EmailService.MarketingOptInSetter( 2602): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,W/libprocessgroup(  892): failed to open /acct/uid_10081/pid_7115/cgroup.procs: No such file or directory
,W/libprocessgroup(  892): failed to open /acct/uid_10070/pid_7077/cgroup.procs: No such file or directory
,D/GetNotificationsWS( 2602): bindWebServices(): registering our AIDL callback...
,I/SundryService( 2602): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/WaitableIntentService( 2602): ServiceHandler.handleMessage: mWaitCount=0
,D/GetNotificationsWS( 2602): onServiceConnected()
,D/GetNotificationsWS( 2602): onServiceConnected(): Registered for remote service callbacks...
D/GetNotificationsWS( 2602): unbindWebServices(): un-registering our AIDL callback...
,I/ActivityManager(  892): Start proc com.google.android.apps.photos for broadcast com.google.android.apps.photos/.jobqueue.JobServiceBroadcastReceiverInternal: pid=7254 uid=10088 gids={50088, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/PushService( 2602): started with background data enabled, making sure notification mechanism is enabled
,D/AuthorizationBluetoothService( 1766): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,D/LocationInitializer( 6089): Restart initialization of location
,D/WearableService( 1766): callingUid 10016, callindPid: 1766
,V/GLSActivity( 1766): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  892): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=7278 uid=10080 gids={50080, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/MDM     ( 1766): [169] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,W/GCoreFlp( 1766): No location to return for getLastLocation()
,W/FusedLocationProvider( 1766): location=null
,I/MusicStore( 7278): Database version: 120
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7278): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7278): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7278): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,W/ResourcesManager( 7278): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 7278): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 7278): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 7278): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 7278): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@3bbb274e: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7278): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 7278): GMSCore installation verified
,I/ConfigStore( 7278): Config Database version: 1
,I/MediaRouter( 7278): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 7278): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/NetworkMonitor( 7278): type=WIFI subType= reason=null isConnected=true
,I/NetworkMonitor( 7278): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  892): Start proc com.android.mms for broadcast com.android.mms/.transaction.MmsSystemEventReceiver: pid=7309 uid=10023 gids={50023, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/art     (  309): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 253us total 22.028ms
,I/art     (  309): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 251us total 19.634ms
,I/art     (  309): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 249us total 20.159ms
,I/InputReader(  892): Reconfiguring input devices.  changes=0x00000010
,I/GHttpClientFactory( 7278): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 7278): Using platform SSLCertificateSocketFactory
,V/Mms     ( 7309): mnc/mcc: 
,I/ActivityManager(  892): Killing 6770:com.google.android.gms.unstable/u0a16 (adj 15): empty #7
V/Mms     ( 7309): tag: int value: recipientLimit - 20
V/Mms     ( 7309): tag: int value: smsToMmsTextThreshold - 6
V/Mms     ( 7309): tag: int value: emergencySmsTimeout - 30
V/Mms     ( 7309): tag: int value: maxSubjectLength - 80
V/Mms     ( 7309): tag: bool value: smsForceShowEncodingMenu - true
V/Mms     ( 7309): tag: bool value: enableGroupMms - false
,V/Mms     ( 7309):  mUserAgent = MOT-XT1072/Mms-5.0,  mUaProfUrl = http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,D/BackupManagerService(  892): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/BackupManagerService(  892): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,W/libprocessgroup(  892): failed to open /acct/uid_10016/pid_6770/cgroup.procs: No such file or directory
,I/BackupManagerService(  892): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/BackupManagerService(  892): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/BackupManagerService(  892): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@2df98bf5
,I/GCoreNlp( 1766): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,W/ResourcesManager( 7309): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/ActivityManager(  892): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=7345 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,I/Launcher( 1585): Deferring update until onResume
,I/ActivityManager(  892): Killing 7188:com.android.chrome/u0a52 (adj 15): empty #7
,D/PhoneMonitor( 7345): Register our PhoneStateListener
,W/libprocessgroup(  892): failed to open /acct/uid_10052/pid_7188/cgroup.procs: No such file or directory
,D/MobileConnectivityChangeReceiver( 7345): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 7345): onReceive CONNECTIVITY_CHANGE networkType=1
,I/ActivityManager(  892): Killing 7207:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,W/libprocessgroup(  892): failed to open /acct/uid_10090/pid_7207/cgroup.procs: No such file or directory
,I/CheckinService( 6089): Checkin interval check for package: unspecified last checkin: 1452699445005 min interval config: 0 actual interval: 5954
,I/CheckinService( 6089): Checkin interval check for package: unspecified last checkin: 1452699445005 min interval config: 0 actual interval: 5957
,I/CheckinService( 6089): Checking schedule, now: 1452699450975 next: 1452699474980
,I/CheckinService( 6089): active receiver: disabled
,I/ActivityManager(  892): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=7366 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/CheckinService( 6089): Checking schedule, now: 1452699451052 next: 1452699474980
I/CheckinService( 6089): active receiver: disabled
,W/ResourcesManager( 7366): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/Babel_SMS( 7366): MmsConfig: mnc/mcc: 0/0
,I/Babel_SMS( 7366): MmsConfig.loadMmsSettings
I/Babel_SMS( 7366): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
I/Babel_SMS( 7366): MmsConfig.loadFromDatabase
,W/art     ( 7366): No such thread id for suspend: 18
,E/Babel_SMS( 7366): canonicalizeMccMnc: invalid mccmnc 
,I/Babel_SMS( 7366): MmsConfig.loadFromResources
E/Babel_SMS( 7366): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 7366): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/Settings( 7366): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 7366): startup - clean
,I/Babel   ( 7366): deleted: false for 0
,I/ActivityManager(  892): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7396 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/VideoCapabilities( 7366): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 7366): Unsupported mime audio/amr-wb-plus
,W/VideoCapabilities( 7366): Unsupported mime video/mpeg2
,I/VideoCapabilities( 7366): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 7366): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7366): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7366): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7366): Unrecognized profile 2130706433 for video/avc
,I/vclib   ( 7366): onServiceConnected
,W/Babel   ( 7366): Attempted to change video mute state without an active call.
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7396): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,I/GAv4    ( 7396): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 7396):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 7396):   adb logcat -s GAv4
E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
,W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7396): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,W/GAv4    ( 7396): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,I/Babel   ( 7366): connection state changed from UNKNOWN to CONNECTED
,I/ActivityManager(  892): Killing 7230:android.process.acore/u0a7 (adj 15): empty #7
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
,W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/GAv4    ( 7396): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/ContextImpl( 7396): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7396): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,W/GAv4    ( 7396): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,W/libprocessgroup(  892): failed to open /acct/uid_10007/pid_7230/cgroup.procs: No such file or directory
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:32000 mC
,I/art     (  892): Explicit concurrent mark sweep GC freed 18170(904KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 20MB/30MB, paused 1.818ms total 115.695ms
,I/WebViewFactory( 7396): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 7396): Time to load native libraries: 2 ms (timestamps 6856-6858)
,I/LibraryLoader( 7396): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 7396): Binding Chromium to main looper Looper (main, tid 1) {4a4f087}
,I/LibraryLoader( 7396): Expected native library version number "",actual native library version number ""
,I/chromium( 7396): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 7396): Initializing chromium process, singleProcess=true
,W/art     ( 7396): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 7396): ApplicationContext is null in ApplicationStatus
,W/chromium( 7396): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 7396): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,E/libEGL  ( 7396): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 7396): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 7396): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7396): Build Date: 10/28/14 Tue
I/Adreno-EGL( 7396): Local Branch: 
I/Adreno-EGL( 7396): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 7396): Local Patches: NONE
I/Adreno-EGL( 7396): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,W/AudioManagerAndroid( 7396): Requires BLUETOOTH permission
,I/NSApplication( 7396): Starting up...
,I/ActivityManager(  892): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=7467 uid=10052 gids={50052, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  892): Killing 7278:com.google.android.music:main/u0a80 (adj 15): empty #7
,W/libprocessgroup(  892): failed to open /acct/uid_10080/pid_7278/cgroup.procs: No such file or directory
,I/ActivityManager(  892): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7486 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  892): Killing 7309:com.android.mms/u0a23 (adj 15): empty #7
,W/libprocessgroup(  892): failed to open /acct/uid_10023/pid_7309/cgroup.procs: No such file or directory
,W/ResourcesManager( 7486): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/ActivityManager(  892): Start proc android.process.acore for content provider com.android.providers.contacts/.ContactsProvider2: pid=7506 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,I/ActivityManager(  892): Killing 7254:com.google.android.apps.photos/u0a88 (adj 15): empty #7
,I/ContactLocale( 7506): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,I/ActivityManager(  892): Killing 7345:com.google.android.setupwizard/u0a35 (adj 15): empty #8
,W/libprocessgroup(  892): failed to open /acct/uid_10088/pid_7254/cgroup.procs: No such file or directory
,D/EmailService.MarketingOptInSetter( 2602): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,W/libprocessgroup(  892): failed to open /acct/uid_10035/pid_7345/cgroup.procs: No such file or directory
,D/GetNotificationsWS( 2602): bindWebServices(): registering our AIDL callback...
,I/SundryService( 2602): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/GetNotificationsWS( 2602): onServiceConnected()
D/GetNotificationsWS( 2602): onServiceConnected(): Registered for remote service callbacks...
D/WaitableIntentService( 2602): ServiceHandler.handleMessage: mWaitCount=0
,D/OtaApp  ( 2602): [debug] > Receive intent: com.motorola.blur.service.blur.Actions.UPGRADE_UPDATE_NOTIFICATION
I/PushService( 2602): started with background data enabled, making sure notification mechanism is enabled
,D/OtaApp  ( 2602): [debug] > UpdateReceiver: Received true from doSanityCheck.
,D/OtaApp  ( 2602): [debug] > In cancelAnyPendingIntentSetPreviously
,I/ActivityManager(  892): START u0 {act=com.motorola.blur.service.blur.Actions.UPGRADE_UPDATE_NOTIFICATION flg=0x30000000 cmp=com.motorola.ccc.ota/.ui.DownloadActivity (has extras)} from uid 10000 on display 0
,W/ContextImpl( 1482): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,D/GetNotificationsWS( 2602): unbindWebServices(): un-registering our AIDL callback...
W/ContextImpl( 1482): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,V/AlarmManager(  892): done {32921255, *walarm*:com.google.android.intent.action.GCM_RECONNECT} [9078ms]
,D/OtaApp  ( 2602): [debug] > DownloadActivity, FormattedText
,I/OtaApp  ( 2602): [info] > DownloadActivity, handling (Blur_Version.22.46.12.thea_reteu.reteuall.en.EU) from ( upgrade)
,D/Checkin ( 2602): publish the event [tag = MOT_OTA event name = LOG]
,I/ActivityManager(  892): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.util.GservicesChangedReceiver: pid=7540 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,D/OtaApp  ( 2602): [debug] > cancelling the previous pending intent set for download later
,I/OtaApp  ( 2602): [info] > next automatic download prompt (serverAnnoy)  is scheduled in : 60 mins.
,D/Checkin ( 2602): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 2602): [debug] > DownloadActivity, FormattedText
,I/OtaApp  ( 2602): [info] > DownloadActivity, handling (Blur_Version.22.46.12.thea_reteu.reteuall.en.EU) from ( upgrade)
,D/Checkin ( 2602): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 2602): [debug] > cancelling the previous pending intent set for download later
,I/OtaApp  ( 2602): [info] > next automatic download prompt (serverAnnoy)  is scheduled in : 60 mins.
,D/Checkin ( 2602): publish the event [tag = MOT_OTA event name = LOG]
,W/IInputConnectionWrapper( 6444): showStatusIcon on inactive InputConnection
I/Keyboard.Facilitator( 1427): onFinishInput()
,D/PhoneMonitor( 7540): Register our PhoneStateListener
,I/LaunchCheckinHandler(  892): Displayed com.motorola.ccc.ota/.ui.DownloadActivity,wp,wa,163
,V/SetupWizard( 7540): Connected to Gservices successfully
,I/ActivityManager(  892): Killing 7366:com.google.android.talk/u0a70 (adj 15): empty #7
,W/libprocessgroup(  892): failed to open /acct/uid_10070/pid_7366/cgroup.procs: No such file or directory
,D/GCM     ( 1766): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,D/GCM     ( 1766): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/ActivityManager(  892): Start proc com.google.android.apps.photos for broadcast com.google.android.apps.photos/.jobqueue.JobServiceBroadcastReceiverInternal: pid=7560 uid=10088 gids={50088, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  892): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.GmsPackageWatcher: pid=7584 uid=10039 gids={50039, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
,I/ActivityManager(  892): Killing 7396:com.google.android.apps.magazines/u0a81 (adj 15): empty #7
,W/libprocessgroup(  892): failed to open /acct/uid_10081/pid_7396/cgroup.procs: No such file or directory
,I/ActivityManager(  892): Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=7606 uid=10019 gids={50019, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  892): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver: pid=7623 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
I/ActivityManager(  892): Killing 7467:com.android.chrome/u0a52 (adj 15): empty #7
,I/art     (  309): Explicit concurrent mark sweep GC freed 707(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 255us total 20.714ms
,I/art     (  309): Explicit concurrent mark sweep GC freed 7(240B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 245us total 19.551ms
,I/art     (  309): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 245us total 19.733ms
,I/ActivityManager(  892): Killing 7486:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,W/libprocessgroup(  892): failed to open /acct/uid_10052/pid_7467/cgroup.procs: No such file or directory
,W/libprocessgroup(  892): failed to open /acct/uid_10090/pid_7486/cgroup.procs: No such file or directory
,W/ResourcesManager( 7623): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/Babel_SMS( 7623): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 7623): MmsConfig.loadMmsSettings
,I/Babel_SMS( 7623): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
I/Babel_SMS( 7623): MmsConfig.loadFromDatabase
,E/Babel_SMS( 7623): canonicalizeMccMnc: invalid mccmnc 
,I/Babel_SMS( 7623): MmsConfig.loadFromResources
E/Babel_SMS( 7623): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 7623): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/Settings( 7623): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 7623): startup - clean
,I/Babel   ( 7623): deleted: false for 0
,I/ActivityManager(  892): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=7662 uid=10027 gids={50027, 9997, 1023, 3003, 1028, 1015} abi=armeabi-v7a
,W/VideoCapabilities( 7623): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 7623): Unsupported mime audio/amr-wb-plus
W/VideoCapabilities( 7623): Unsupported mime video/mpeg2
,W/asset   ( 7662): Asset path /system/framework/com.motorola.gallery is neither a directory nor file (type=1).
W/ResourcesManager( 7662): Asset path '/system/framework/com.motorola.gallery' does not exist or contains no resources.
W/ResourcesManager( 7662): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 7662): Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
,I/VideoCapabilities( 7623): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 7623): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 7623): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7623): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7623): Unrecognized profile 2130706433 for video/avc
,D/PackageBroadcastService( 6089): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
I/PackageBroadcastService( 6089): Null package name or gms related package.  Ignoreing.
,W/Launcher( 1585): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@a65b48c new=com.google.android.velvet.VelvetApplication@a65b48c
,I/UpdateIcingCorporaServi( 7584): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,I/Icing   ( 6089): updateResources: need to parse f{com.google.android.gms}
,I/ActivityManager(  892): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=7692 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/vclib   ( 7623): onServiceConnected
W/Babel   ( 7623): Attempted to change video mute state without an active call.
,W/ResourcesManager( 7623): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 7623): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,W/ResourcesManager( 7692): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/UpdateIcingCorporaServi( 7584): UpdateCorporaTask done [took 167 ms] updated apps [took 167 ms] 
V/JNIHelp ( 7623): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/ActivityManager(  892): Killing 7540:com.google.android.setupwizard/u0a35 (adj 15): empty #7
,W/System  ( 7623): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 7623): Installed default security provider GmsCore_OpenSSL
,W/libprocessgroup(  892): failed to open /acct/uid_10035/pid_7540/cgroup.procs: No such file or directory
,I/ActivityManager(  892): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=7722 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/art     (  892): Explicit concurrent mark sweep GC freed 12633(622KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 20MB/30MB, paused 1.436ms total 119.888ms
,I/ActivityManager(  892): Killing 7560:com.google.android.apps.photos/u0a88 (adj 15): empty #7
,W/libprocessgroup(  892): failed to open /acct/uid_10088/pid_7560/cgroup.procs: No such file or directory
,D/Finsky  ( 7722): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/Finsky  ( 7722): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 7722): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 7722): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/Ads     ( 7722): Skipping gmscore version check
,D/Finsky  ( 7722): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 7722): [1] Libraries$2.run: Finished loading 1 libraries.
,D/Finsky  ( 7722): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/Finsky  ( 7722): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/ActivityManager(  892): Start proc com.google.android.apps.photos for broadcast com.google.android.apps.photos/.jobqueue.JobServiceBroadcastReceiverInternal: pid=7764 uid=10088 gids={50088, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  892): Killing 7606:com.google.android.partnersetup/u0a19 (adj 15): empty #7
,W/libprocessgroup(  892): failed to open /acct/uid_10019/pid_7606/cgroup.procs: No such file or directory
,D/TaskPersister(  892): removeObsoleteFile: deleting file=5_task.xml
,I/Icing   ( 6089): Indexing 5905AFFF7E2D60BB1F87C8D56D40BA6B258244BF from com.google.android.gms
,I/Icing   ( 6089): Indexing done 5905AFFF7E2D60BB1F87C8D56D40BA6B258244BF
,I/ActivityManager(  892): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.util.GservicesChangedReceiver: pid=7788 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  892): Killing 7662:com.motorola.MotGallery2/u0a27 (adj 15): empty #7
,W/libprocessgroup(  892): failed to open /acct/uid_10027/pid_7662/cgroup.procs: No such file or directory
,I/ActivityManager(  892): Killing 7584:com.google.android.googlequicksearchbox:search/u0a39 (adj 15): empty #7
,D/PhoneMonitor( 7788): Register our PhoneStateListener
,W/libprocessgroup(  892): failed to open /acct/uid_10039/pid_7584/cgroup.procs: No such file or directory
,I/ActivityManager(  892): Killing 7506:android.process.acore/u0a7 (adj 15): empty #7
,W/libprocessgroup(  892): failed to open /acct/uid_10007/pid_7506/cgroup.procs: No such file or directory
,D/GCM     ( 1766): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/CheckinService( 6089): Checkin interval check for package: unspecified last checkin: 1452699445005 min interval config: 0 actual interval: 11220
,I/CheckinService( 6089): Checking schedule, now: 1452699456233 next: 1452699474980
I/CheckinService( 6089): active receiver: disabled
,D/GCM     ( 1766): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,D/BatteryService(  892): uevent={POWER_SUPPLY_TEMP=291, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4310985, SEQNUM=4464, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-7512, POWER_SUPPLY_CHARGE_COUNTER=-454, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2469): Disconnected process message: 10, size: 0
,I/ActivityManager(  892): Killing 7692:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,W/libprocessgroup(  892): failed to open /acct/uid_10090/pid_7692/cgroup.procs: No such file or directory
,I/CheckinService( 6089): Done disabling old GoogleServicesFramework version
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:32000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:31000 mC
,D/BatteryService(  892): uevent={POWER_SUPPLY_TEMP=278, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311012, SEQNUM=4468, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-3205, POWER_SUPPLY_CHARGE_COUNTER=-477, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2469): Disconnected process message: 10, size: 0
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:31000 mC
,I/ClearcutLoggerApiImpl( 1766): disconnect managed GoogleApiClient
,V/AlarmManager(  892): send {22a3c962, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  892): send {1de1ff99, *walarm*:com.android.server.task.controllers.BatteryController.ACTION_CHARGING_STABLE}
V/AlarmManager(  892): send {3bff9817, *walarm*:com.google.android.gms/.checkin.CheckinService$Receiver}
,V/AlarmManager(  892): done {1de1ff99, *walarm*:com.android.server.task.controllers.BatteryController.ACTION_CHARGING_STABLE} [21ms]
,V/AlarmManager(  892): done {3bff9817, *walarm*:com.google.android.gms/.checkin.CheckinService$Receiver} [32ms]
,I/CheckinService( 6089): Checkin interval check for package: unspecified last checkin: 1452699445005 min interval config: 0 actual interval: 41970
,V/AlarmManager(  892): done {22a3c962, *alarm*:android.intent.action.TIME_TICK} [55ms]
,I/CheckinService( 6089): Checking schedule, now: 1452699486999 next: 1452699474980
I/CheckinService( 6089): active receiver: enabled
,I/CheckinService( 6089): Preparing to send checkin request
I/EventLogService( 6089): Accumulating logs since 1452699440700
,I/CheckinRequestBuilder( 6089): Checkin reason type: 8 attempt count: 1
,E/ActivityThread( 6089): Failed to find provider info for com.google.android.wearable.settings
,V/GLSActivity( 1766): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1766): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  892): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=7832 uid=10016 gids={50016, 9997, 3003, 1028, 1015, 3002, 3001, 1005, 1007, 3007, 2001, 3006} abi=armeabi-v7a
,W/ResourcesManager( 7832): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7832): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/MultiDex( 7832): VM with version 2.1.0 has multidex support
I/MultiDex( 7832): install
I/MultiDex( 7832): VM has multidex support, MultiDex support library is disabled.
,V/JNIHelp ( 7832): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 7832): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 7832): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@12f5f397: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7832): Installed default security provider GmsCore_OpenSSL
,D/LocationInitializer( 6089): Restart initialization of location
,D/AuthorizationBluetoothService( 1766): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,V/GLSActivity( 1766): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GCoreFlp( 1766): No location to return for getLastLocation()
D/WearableService( 1766): callingUid 10016, callindPid: 1766
,W/FusedLocationProvider( 1766): location=null
,E/MDM     ( 1766): [169] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,I/art     ( 7832): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 7832): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,D/NativeLibraryUtils( 7832): Install completed successfully. count=14 extracted=0
,D/WVCdm   (  295): Instantiating CDM.
I/WVCdm   (  295): CdmEngine::OpenSession
,I/WVCdm   (  295): Level3 Library Sep 25 2014 17:10:03
,W/WVCdm   (  295): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,D/DrmWidevineDash(  295): OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x13
D/DrmWidevineDash(  295): Service_Initialize: starts!
,D/QSEECOMAPI: (  295): QSEECom_get_handle sb_length = 0x19000
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
,D/DrmWidevineDash(  295): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4f6e000
E/DrmWidevineDash(  295): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4f6e000
,D/DrmWidevineDash(  295): OEMCrypto_Initialize: ends! returns 0
,D/DrmWidevineDash(  295): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  295): hlos api version =  9
D/DrmWidevineDash(  295): tz api version =  8
D/DrmWidevineDash(  295): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  295): OEMCrypto_IsKeyboxValid: starts!
,D/DrmWidevineDash(  295): OEMCrypto_IsKeyboxValid: ends! returns 0
,D/WVCdm   (  295): OEMCrypto_Initialize Level 1 success. I will use level 1.
D/DrmWidevineDash(  295): OEMCrypto_OpenSession: starts! SID=0xb5549960
D/DrmWidevineDash(  295): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  295): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  295): OEMCrypto_GetRandom: starts! randomData=0xb74059d0, dataLength=8
D/DrmWidevineDash(  295): OEMCrypto_GetRandom: ends! returns 0
D/DrmWidevineDash(  295): OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb74ecf58, wrapped_rsa_key_length=1280
,D/DrmWidevineDash(  295): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
,I/WVCdm   (  295): CdmEngine::QueryKeyControlInfo
W/WVCdm   (  295): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  295): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  295): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  295): OEMCrypto_GetDeviceID: starts! deviceID=0xb7538828, idLength=0xb5449730
,D/DrmWidevineDash(  295): OEMCrypto_GetDeviceID: ends! returns 0
D/DrmWidevineDash(  295): OEMCrypto_SupportsUsageTable: starts!
D/DrmWidevineDash(  295): OEMCrypto_SupportsUsageTable: is_supported = 1
D/DrmWidevineDash(  295): OEMCrypto_SupportsUsageTable: wv_app_version = 25
,D/DrmWidevineDash(  295): OEMCrypto_SupportsUsageTable: ends! returns 0x0
D/DrmWidevineDash(  295): OEMCrypto_GetHDCPCapability: starts!
D/DrmWidevineDash(  295): OEMCrypto_GetHDCPCapability: ends! returns 0x0
D/DrmWidevineDash(  295): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  295): hlos api version =  9
D/DrmWidevineDash(  295): tz api version =  8
D/DrmWidevineDash(  295): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  295): OEMCrypto_GenerateNonce: starts! SID=1
D/DrmWidevineDash(  295): OEMCrypto_GenerateNonce: ends! returns 0
D/WVCdm   (  295): PrepareKeyRequest: nonce=1815852089
D/DrmWidevineDash(  295): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb74706f0
D/DrmWidevineDash(  295): message_length=1591, signature=0xb74069c8, signature_length=3041171220
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
,I/WVCdm   (  295): CdmEngine::OpenSession
I/WVCdm   (  295): Level3 Library Sep 25 2014 17:10:03
W/WVCdm   (  295): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
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
D/DrmWidevineDash(  295): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4f6e000
,E/DrmWidevineDash(  295): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4f6e000
,D/DrmWidevineDash(  295): OEMCrypto_Initialize: ends! returns 0
D/DrmWidevineDash(  295): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  295): hlos api version =  9
D/DrmWidevineDash(  295): tz api version =  8
D/DrmWidevineDash(  295): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  295): OEMCrypto_IsKeyboxValid: starts!
,D/DrmWidevineDash(  295): OEMCrypto_IsKeyboxValid: ends! returns 0
D/WVCdm   (  295): OEMCrypto_Initialize Level 1 success. I will use level 1.
D/DrmWidevineDash(  295): OEMCrypto_OpenSession: starts! SID=0xb5549960
,D/DrmWidevineDash(  295): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  295): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  295): OEMCrypto_GetRandom: starts! randomData=0xb7470908, dataLength=8
D/DrmWidevineDash(  295): OEMCrypto_GetRandom: ends! returns 0
D/DrmWidevineDash(  295): OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb74ecf58, wrapped_rsa_key_length=1280
D/DrmWidevineDash(  295): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
I/WVCdm   (  295): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  295): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  295): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  295): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  295): OEMCrypto_GetDeviceID: starts! deviceID=0xb7538848, idLength=0xbef212b0
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
D/WVCdm   (  295): PrepareKeyRequest: nonce=2117316352
,D/DrmWidevineDash(  295): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb7440c20
D/DrmWidevineDash(  295): message_length=1626, signature=0xb7538370, signature_length=3203535508
,D/DrmWidevineDash(  295): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  295): CdmEngine::CloseSession
D/DrmWidevineDash(  295): OEMCrypto_CloseSession: starts! SID=1
,D/DrmWidevineDash(  295): OEMCrypto_CloseSession: ends! returns 0
I/WVCdm   (  295): L3 Terminate.
,D/DrmWidevineDash(  295): OEMCrypto_Terminate: starts!
D/DrmWidevineDash(  295): Service_Uninitialize: starts!
D/QSEECOMAPI: (  295): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  295): QSEECom_shutdown_app, app_id = 3
D/DrmWidevineDash(  295): Service_Uninitialize: ends! returns 0x0
D/DrmWidevineDash(  295): OEMCrypto_Terminate: ends! returns 0
,I/dex2oat ( 7878): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=36 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,I/dex2oat ( 7878): dex2oat took 70.238ms (threads: 4)
,I/Adreno-EGL( 7832): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 7832): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7832): Build Date: 10/28/14 Tue
I/Adreno-EGL( 7832): Local Branch: 
I/Adreno-EGL( 7832): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 7832): Local Patches: NONE
I/Adreno-EGL( 7832): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/Adreno-EGL( 7832): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 7832): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7832): Build Date: 10/28/14 Tue
I/Adreno-EGL( 7832): Local Branch: 
I/Adreno-EGL( 7832): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 7832): Local Patches: NONE
I/Adreno-EGL( 7832): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/Adreno-EGL( 7832): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 7832): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7832): Build Date: 10/28/14 Tue
I/Adreno-EGL( 7832): Local Branch: 
I/Adreno-EGL( 7832): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 7832): Local Patches: NONE
I/Adreno-EGL( 7832): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/Adreno-EGL( 7832): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 7832): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7832): Build Date: 10/28/14 Tue
I/Adreno-EGL( 7832): Local Branch: 
I/Adreno-EGL( 7832): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 7832): Local Patches: NONE
I/Adreno-EGL( 7832): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/CheckinRequestBuilder( 6089): Classify the device as Phone.
,I/CheckinTask( 6089): Sending checkin request (9525 bytes)
,I/CheckinRequestBuilder( 6089): Checkin reason type: 8 attempt count: 1
,E/ActivityThread( 6089): Failed to find provider info for com.google.android.wearable.settings
,I/MDMCTBK (  293): NetlinkHandler, power_supply subsys
I/MDMCTBK (  293): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  293): checkDefaultInst, current pid is = 293
I/MDMCTBK (  293): checkDefaultInst, pid match
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  293): MdmCutbackHndler,Could not open ''
,I/CheckinRequestBuilder( 6089): Classify the device as Phone.
,I/CheckinTask( 6089): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 6089): Checking schedule, now: 1452699489770 next: 1453300626761
I/CheckinService( 6089): active receiver: disabled
,D/CheckinService( 6089): Recording last checkin time for package unspecified as 1452699489780
,V/SetupWizard( 7788): Connected to Gservices successfully
,D/GCM     ( 1766): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/MDMCTBK (  293): NetlinkHandler, power_supply subsys
,I/MDMCTBK (  293): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  293): checkDefaultInst, current pid is = 293
I/MDMCTBK (  293): checkDefaultInst, pid match
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  293): MdmCutbackHndler,Could not open ''
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:30000 mC
,I/ActivityManager(  892): Killing 7722:com.android.vending/u0a32 (adj 15): empty #7
,W/libprocessgroup(  892): failed to open /acct/uid_10032/pid_7722/cgroup.procs: No such file or directory
,I/MDMCTBK (  293): NetlinkHandler, power_supply subsys
,I/MDMCTBK (  293): NetlinkHandler, usbChargerStateChanged
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
,I/InputReader(  892): Reconfiguring input devices.  changes=0x00000010
,I/art     (  309): Background concurrent mark sweep GC freed 791(33KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 10.308ms total 41.648ms
,I/ActivityManager(  892): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.GmsPackageWatcher: pid=7902 uid=10039 gids={50039, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
,D/BackupManagerService(  892): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/BackupManagerService(  892): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,I/BackupManagerService(  892): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,I/Launcher( 1585): Deferring update until onResume
,I/art     ( 1766): Explicit concurrent mark sweep GC freed 106468(5MB) AllocSpace objects, 29(464KB) LOS objects, 40% free, 15MB/25MB, paused 1.165ms total 118.070ms
,V/BackupManagerService(  892): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/BackupManagerService(  892): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@f7d7a1d
,I/GCoreNlp( 1766): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,I/art     (  892): Explicit concurrent mark sweep GC freed 19702(1030KB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 20MB/30MB, paused 1.835ms total 122.750ms
,I/ActivityManager(  892): Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=7940 uid=10019 gids={50019, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  892): Start proc android.process.acore for broadcast com.android.providers.contacts/.PackageIntentReceiver: pid=7961 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,I/ActivityManager(  892): Killing 7764:com.google.android.apps.photos/u0a88 (adj 15): empty #7
,W/libprocessgroup(  892): failed to open /acct/uid_10088/pid_7764/cgroup.procs: No such file or directory
,W/ResourcesManager( 7623): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 7623): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/ContactLocale( 7961): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,I/ActivityManager(  892): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=7984 uid=10027 gids={50027, 9997, 1023, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  892): Killing 7788:com.google.android.setupwizard/u0a35 (adj 15): empty #7
,W/libprocessgroup(  892): failed to open /acct/uid_10035/pid_7788/cgroup.procs: No such file or directory
,W/asset   ( 7984): Asset path /system/framework/com.motorola.gallery is neither a directory nor file (type=1).
,W/ResourcesManager( 7984): Asset path '/system/framework/com.motorola.gallery' does not exist or contains no resources.
W/ResourcesManager( 7984): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,W/ResourcesManager( 7984): Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
,D/PackageBroadcastService( 6089): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 6089): Null package name or gms related package.  Ignoreing.
,I/UpdateIcingCorporaServi( 7902): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,W/Launcher( 1585): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@a65b48c new=com.google.android.velvet.VelvetApplication@a65b48c
,I/ActivityManager(  892): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=8009 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/art     (  309): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 273us total 20.399ms
,I/Icing   ( 6089): updateResources: need to parse f{com.google.android.gms}
,I/art     (  309): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 249us total 19.637ms
,I/art     (  309): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 254us total 20.285ms
,W/ResourcesManager( 8009): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/UpdateIcingCorporaServi( 7902): UpdateCorporaTask done [took 123 ms] updated apps [took 123 ms] 
,I/ActivityManager(  892): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=8035 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  892): Killing 7832:com.google.android.gms.unstable/u0a16 (adj 15): empty #7
,W/libprocessgroup(  892): failed to open /acct/uid_10016/pid_7832/cgroup.procs: No such file or directory
,D/Finsky  ( 8035): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/Finsky  ( 8035): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 8035): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 8035): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/Finsky  ( 8035): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 8035): [1] Libraries$2.run: Finished loading 1 libraries.
,D/Ads     ( 8035): Skipping gmscore version check
,D/Finsky  ( 8035): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/Finsky  ( 8035): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/ActivityManager(  892): Killing 7940:com.google.android.partnersetup/u0a19 (adj 15): empty #7
,W/libprocessgroup(  892): failed to open /acct/uid_10019/pid_7940/cgroup.procs: No such file or directory
,I/Icing   ( 6089): Indexing 5905AFFF7E2D60BB1F87C8D56D40BA6B258244BF from com.google.android.gms
,I/Icing   ( 6089): Indexing done 5905AFFF7E2D60BB1F87C8D56D40BA6B258244BF
,I/ActivityManager(  892): Killing 7984:com.motorola.MotGallery2/u0a27 (adj 15): empty #7
,W/libprocessgroup(  892): failed to open /acct/uid_10027/pid_7984/cgroup.procs: No such file or directory
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:30000 mC
,I/ActivityManager(  892): Killing 7623:com.google.android.talk/u0a70 (adj 15): empty #7
,W/libprocessgroup(  892): failed to open /acct/uid_10070/pid_7623/cgroup.procs: No such file or directory
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:30000 mC
,I/Keyboard.Facilitator.LanguageModelFlusher( 1427): run()
I/Keyboard.Facilitator( 1427): flushDynamicLanguageModels()
,I/ConfigService( 1766): onCreate
,I/ConfigService( 1766): onDestroy
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:30000 mC
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
,D/BatteryService(  892): uevent={POWER_SUPPLY_TEMP=268, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311156, SEQNUM=4484, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=2723, POWER_SUPPLY_CHARGE_COUNTER=-580, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2469): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2469): Disconnected process message: 10, size: 0
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/jxcore-log( 6444): --= Surplus to requirements =--
I/jxcore-log( 6444): 
I/jxcore-log( 6444): ****TEST TOOK:  ms ****
I/jxcore-log( 6444): 
I/jxcore-log( 6444): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 6444): 
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,D/AndroidRuntime( 8102): 
D/AndroidRuntime( 8102): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 8102): CheckJNI is OFF
,D/AndroidRuntime( 8102): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager(  892): Force stopping com.test.thalitest appid=10447 user=-1: uninstall pkg
I/ActivityManager(  892): Killing 6444:com.test.thalitest/u0a447 (adj 9): stop com.test.thalitest
,W/PackageSettings(  892): Skipping PackageSetting{f36067b com.example.hello/10440} due to missing metadata
,I/WindowState(  892): WIN DEATH: Window{3a035fc0 u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/WifiService(  892): Client connection lost with reason: 4
,I/ActivityManager(  892):   Force finishing activity ActivityRecord{2d2edad5 u0 com.test.thalitest/.MainActivity t6}
,W/ActivityManager(  892): Spurious death for ProcessRecord{1346079f 6444:com.test.thalitest/u0a447}, curProc for 6444: null
,I/ActivityManager(  892): Force stopping com.test.thalitest appid=10447 user=0: pkg removed
,I/art     ( 3007): Explicit concurrent mark sweep GC freed 9818(2MB) AllocSpace objects, 11(176KB) LOS objects, 39% free, 7MB/12MB, paused 855us total 38.606ms
,I/art     ( 1585): Explicit concurrent mark sweep GC freed 5023(309KB) AllocSpace objects, 6(297KB) LOS objects, 24% free, 13MB/17MB, paused 474us total 43.945ms
,I/InputReader(  892): Reconfiguring input devices.  changes=0x00000010
,W/GeofencerStateMachine( 1766): Ignoring removeGeofence because network location is disabled.
,I/Keyboard.Facilitator( 1427): resetDictionaries() : en_US
,D/VoicemailCleanupService( 7961): Cleaning up data for package: com.test.thalitest
,I/Keyboard.Facilitator.DecoderInitializer( 1427): run()
,I/Decoder ( 1427): createOrResetDecoder
,W/SQLiteConnectionPool( 6089): A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/networkstatistics.sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
I/art     ( 6089): Explicit concurrent mark sweep GC freed 17149(1019KB) AllocSpace objects, 3(48KB) LOS objects, 24% free, 13MB/17MB, paused 836us total 145.739ms
,I/ActivityManager(  892): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=8135 uid=10027 gids={50027, 9997, 1023, 3003, 1028, 1015} abi=armeabi-v7a
,I/ConfigService( 1766): onCreate
,I/art     (  892): Explicit concurrent mark sweep GC freed 17270(1134KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 20MB/30MB, paused 1.941ms total 200.345ms
I/art     (  892): WaitForGcToComplete blocked for 55.110ms for cause Explicit
,W/asset   ( 8135): Asset path /system/framework/com.motorola.gallery is neither a directory nor file (type=1).
W/ResourcesManager( 8135): Asset path '/system/framework/com.motorola.gallery' does not exist or contains no resources.
W/ResourcesManager( 8135): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 8135): Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1427): run()
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1427): loadStaticLm() : Loading File = /data/data/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4014912) with up to date LoudsLmContentVersion = 20150512
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1427): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1427): run() : Loading LM = contacts
I/ActivityManager(  892): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=8155 uid=1000 gids={41000, 9997, 1021, 3004, 3005, 1000, 3009, 1015, 1023, 1010, 1004, 2002, 3006, 1028, 3002, 3001, 3003} abi=armeabi-v7a
,D/BackupManagerService(  892): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService(  892): Receieved: android.intent.action.PACKAGE_REMOVED
,D/TaskPersister(  892): removeObsoleteFile: deleting file=6_task.xml
,I/ActivityManager(  892): Killing 7902:com.google.android.googlequicksearchbox:search/u0a39 (adj 15): empty #7
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1427): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1427): run() : Loading LM = history
,I/Launcher( 1585): Deferring update until onResume
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1427): run() : Loaded File = UserHistory.en_US.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1427): run() : Loading LM = user
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1427): run() : Missing File = Personal.en_US.dict
,I/Keyboard.Facilitator.PersonalDictionaryLoader( 1427): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1427): run()
I/Keyboard.Facilitator.RecurringTaskScheduler( 1427): run()
I/StatsUtilsManager( 1427): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1427): shouldRecordStats() = Too Soon
,I/art     (  892): Explicit concurrent mark sweep GC freed 5426(292KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 20MB/30MB, paused 1.963ms total 182.744ms
,W/libprocessgroup(  892): failed to open /acct/uid_10039/pid_7902/cgroup.procs: No such file or directory
,W/ContextImpl( 8155): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1820 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2611 
,D/AndroidRuntime( 8102): Shutting down VM
,D/PackageBroadcastService( 6089): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
,D/AccountUtils( 6089): Clearing selected account for com.test.thalitest
,D/ChimeraCfgMgr( 6089): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 6089): Module APK com.google.android.play.games already loaded
,D/ChimeraCfgMgr( 6089): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 6089): Module APK com.google.android.play.games already loaded
,E/NetworkScheduler.SchedulerReceiver( 1766): Invalid parameter app
E/NetworkScheduler.SchedulerReceiver( 1766): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,I/ActivityManager(  892): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.IcingCorporaChangedReceiver: pid=8179 uid=10039 gids={50039, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
,I/LocationSettingsChecker( 6089): Removing dialog suppression flag for package com.test.thalitest
,D/gH_CompatibleDatabase( 6089): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
,D/gH_CompatibleDatabase( 6089): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
,D/gH_MetricsDatabase( 6089): 0 metrics were deleted when clearing package com.test.thalitest.
,D/gH_CompatibleDatabase( 6089): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
,D/gH_CompatibleDatabase( 6089): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
,D/gH_CompatibleDatabase( 6089): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
,D/gH_CompatibleDatabase( 6089): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
,D/gH_CompatibleDatabase( 6089): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
D/gH_CompatibleDatabase( 6089): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
,W/BaseAppContext( 6089): Using Auth Proxy for data requests.
,D/gH_CompatibleDatabase( 6089): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
D/gH_CompatibleDatabase( 6089): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
,D/gH_CompatibleDatabase( 6089): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
D/gH_CompatibleDatabase( 6089): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
,W/BaseAppContext( 6089): Using Auth Proxy for data requests.
,I/GMPM-SVC( 6089): App measurement is starting up, version: 8489
I/GMPM-SVC( 6089): To enable debug logging run: adb shell setprop log.tag.GMPM VERBOSE
,W/Launcher( 1585): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@a65b48c new=com.google.android.velvet.VelvetApplication@a65b48c
,I/ActivityManager(  892): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=8205 uid=10057 gids={50057, 9997, 1028, 3003, 1015} abi=armeabi-v7a
,I/Icing   ( 6089): doRemovePackageData com.test.thalitest
,I/ActivityManager(  892): Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=8232 uid=10019 gids={50019, 9997, 3003} abi=armeabi-v7a
,D/ConnectivityService(  892): listenForNetwork for NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  892): handleRegisterNetworkRequest checking NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  892): apparently satisfied.  currentScore=60
,D/ConnectivityManager.CallbackHandler( 6089): CM callback handler got msg 524290
,I/UpdateIcingCorporaServi( 8179): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,E/SQLiteLog( 6089): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,E/GMPM-SVC( 6089): Task exception on worker thread: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850): com.google.android.gms.measurement.internal.e.b(SourceFile:321)
,E/SharedPreferencesImpl( 6089): Couldn't rename file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.measurement.prefs.xml to backup file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.measurement.prefs.xml.bak
,E/SQLiteDatabase( 8179): Failed to open database '/data/data/com.google.android.googlequicksearchbox/databases/icingcorpora.db'.
E/SQLiteDatabase( 8179): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 8179): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 8179): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 8179): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 8179): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 8179): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 8179): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 8179): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 8179): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 8179): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 8179): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1276)
E/SQLiteDatabase( 8179): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 8179): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 8179): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 8179): 	at com.google.android.search.core.icingsync.d.getWritableDatabase(InternalIcingCorporaProvider.java:592)
E/SQLiteDatabase( 8179): 	at com.google.android.search.core.icingsync.InternalIcingCorporaProvider.update(InternalIcingCorporaProvider.java:284)
E/SQLiteDatabase( 8179): 	at android.content.ContentProvider$Transport.update(ContentProvider.java:325)
E/SQLiteDatabase( 8179): 	at android.content.ContentResolver.update(ContentResolver.java:1333)
E/SQLiteDatabase( 8179): 	at com.google.android.search.core.icingsync.e.JA(UpdateIcingCorporaService.java:408)
E/SQLiteDatabase( 8179): 	at com.google.android.search.core.icingsync.g.aTY(UpdateIcingCorporaService.java:347)
E/SQLiteDatabase( 8179): 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.a(UpdateIcingCorporaService.java:320)
E/SQLiteDatabase( 8179): 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.ba(UpdateIcingCorporaService.java:215)
E/SQLiteDatabase( 8179): 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.onHandleIntent(UpdateIcingCorporaService.java:201)
E/SQLiteDatabase( 8179): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 8179): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 8179): 	at android.os.Looper.loop(Looper.java:135)
E/SQLiteDatabase( 8179): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/qdhwcomposer(  279): handle_blank_event: dpy:0 panel power state: 0
,I/ActivityManager(  892): Start proc com.google.android.googlequicksearchbox:crash_report for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService: pid=8254 uid=10039 gids={50039, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a

```
