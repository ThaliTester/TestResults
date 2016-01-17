#### Test 5615109389cecbd_thali04_motorola-XT1072 Logs


```
--------- beginning of main
,E/global frequency( 2569): no tags to log
D/Checkin ( 2569): publish the event [tag = MOT_CHECKIN event name = LOG]
D/BSUtils ( 2569): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
E/PhoneInterfaceManager( 1548): [PhoneIntfMgr] getIccId: ICC ID is null or empty.
I/art     ( 1476): Explicit concurrent mark sweep GC freed 57418(3MB) AllocSpace objects, 37(1261KB) LOS objects, 40% free, 7MB/12MB, paused 944us total 56.692ms
D/BSUtils ( 2569): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
I/BSUtils ( 2569): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
D/BSUtils ( 2569): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
E/PhoneInterfaceManager( 1548): [PhoneIntfMgr] getIccId: ICC ID is null or empty.
D/AndroidRuntime( 6707): 
D/AndroidRuntime( 6707): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6707): CheckJNI is OFF
I/art     (  879): Explicit concurrent mark sweep GC freed 32231(1562KB) AllocSpace objects, 2(219KB) LOS objects, 33% free, 20MB/30MB, paused 1.878ms total 126.031ms
D/BSUtils ( 2569): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
I/BSUtils ( 2569): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
D/BSUtils ( 2569): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
E/PhoneInterfaceManager( 1548): [PhoneIntfMgr] getIccId: ICC ID is null or empty.
D/AndroidRuntime( 6707): Calling main entry com.android.commands.am.Am
--------- beginning of system
I/ActivityManager(  879): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
I/art     ( 1476): Explicit concurrent mark sweep GC freed 4103(172KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 7MB/12MB, paused 727us total 27.906ms
D/BSUtils ( 2569): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
I/BSUtils ( 2569): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
I/ActivityManager(  879): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6731 uid=10454 gids={50454, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 6707): Shutting down VM
I/BSUtils ( 2569): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
I/global frequency( 2569): BcsDSCheckin.logProperties: root status from persist.qe isqe 0/0
D/Checkin ( 2569): publish the event [tag = MOT_CHECKIN event name = LOG]
E/global frequency( 2569): BcsDSCheckin.logProperties: BL State from property is null or empty
D/Checkin ( 2569): publish the event [tag = MOT_CHECKIN event name = LOG]
D/Checkin ( 2569): publish the event [tag = DEV_ATTRIBS event name = SW]
V/ActivityManager(  879): Display changed displayId=0
D/Checkin ( 2569): publish the event [tag = MOT_CCE_STATS event name = DataUsage]
W/ContextImpl( 1476): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
W/ContextImpl( 1476): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
I/global frequency( 2569): BcsDSCheckin.events found events 108
D/Checkin ( 2569): publish the event [tag = MOT_CHECKIN event name = LOG]
I/BSUtils ( 2569): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,D/MMApiWebService( 2569): doRequest() with req : MMApiWSRequest(v1/cs/checkin)
,I/WebViewFactory( 6731): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/MMApiWSBase( 2569): doRequest(): url: https://argo.svcmot.com:443/v1/cs/checkin.pb/2072049230914535424?appId=6R1TANEX3ZMQ6EU1UH43P34C8B868KTE
D/Checkin ( 2569): publish the event [tag = MOT_CCE event name = LOG]
,I/LibraryLoader( 6731): Time to load native libraries: 2 ms (timestamps 4314-4316)
I/LibraryLoader( 6731): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 6731): Binding Chromium to main looper Looper (main, tid 1) {3c2ce915}
,I/LibraryLoader( 6731): Expected native library version number "",actual native library version number ""
,I/chromium( 6731): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 6731): Initializing chromium process, singleProcess=true
,W/art     ( 6731): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 6731): ApplicationContext is null in ApplicationStatus
,W/chromium( 6731): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 6731): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 6731): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 6731): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 6731): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 6731): Build Date: 10/28/14 Tue
I/Adreno-EGL( 6731): Local Branch: 
I/Adreno-EGL( 6731): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 6731): Local Patches: NONE
I/Adreno-EGL( 6731): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,D/BluetoothManagerService(  879): Message: 20
D/BluetoothManagerService(  879): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2af46f81:true
,W/ActivityManager(  879): Activity pause timeout for ActivityRecord{27934302 u0 com.test.thalitest/.MainActivity t6}
,W/art     ( 6731): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 6731): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 6731): CordovaWebView is running on device made by: motorola
,W/art     ( 6731): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 6731): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 6731): Render dirty regions requested: true
,D/Atlas   ( 6731): Validating map...
,W/chromium( 6731): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/OpenGLRenderer( 6731): Initialized EGL, version 1.4
,D/OpenGLRenderer( 6731): Enabling debug mode 0
,I/Keyboard.Facilitator( 1415): onFinishInput()
,I/LaunchCheckinHandler(  879): Displayed com.test.thalitest/.MainActivity,cp,ca,962
I/ActivityManager(  879): Displayed com.test.thalitest/.MainActivity: +862ms (total +962ms)
,W/IInputConnectionWrapper( 6731): showStatusIcon on inactive InputConnection
,E/Adreno-ES20( 6731): <check_framebuffer_attachment:854>: Invalid texture format! Returning error!
E/Adreno-ES20( 6731): <check_framebuffer_object_status:1237>: Framebuffer color attachment incomplete. Returning GL_FRAMEBUFFER_INCOMPLETE_ATTACHMENT!
,W/BindingManager( 6731): Cannot call determinedVisibility() - never saw a connection for the pid: 6731
,D/JsMessageQueue( 6731): Set native->JS mode to OnlineEventsBridgeMode
,V/AlarmManager(  879): send {36f86a62, *walarm*:com.google.android.intent.action.SEND_IDLE}
,V/AlarmManager(  879): done {36f86a62, *walarm*:com.google.android.intent.action.SEND_IDLE} [8ms]
,D/jxcore_app_log( 6731): JniHelper::setJavaVM(0xb8582310), pthread_self() = -1198450472
D/JX-Cordova( 6731): jxcore cordova android initializing
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:31000 mC
,D/MMApiWSBase( 2569): doRequest(): v1/cs/checkin resp length: 4
,D/CCE     ( 2569): AppWSProxy - handleResponse(): error=None errorText= statusCode=200 reqId=
D/CCE     ( 2569): AppWSProxy - sendAIDLWSResponse() sending reponse
,I/global frequency( 2569): BcsCore.status() called with error code=ERROR_OK
,D/Checkin ( 2569): publish the event [tag = MOT_CHECKIN event name = LOG]
,D/CheckinProvider(  879): 108 events delete 0 left
,I/global frequency( 2569): BcsDSCheckin.events found events 0
,D/Checkin ( 2569): publish the event [tag = MOT_CHECKIN event name = LOG]
,I/BSUtils ( 2569): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,I/BSUtils ( 2569): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,W/jxcore-log( 6731): Initializing JXcore engine
W/jxcore-log( 6731): JXcore engine is ready
,W/jxcore-log( 6731): Starting JXcore engine
,W/.test.thalitest( 6731): type=1400 audit(0.0:4): avc: denied { ioctl } for uid=10454 path="socket:[5759]" dev="sockfs" ino=5759 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,W/.test.thalitest( 6731): type=1400 audit(0.0:5): avc: denied { ioctl } for uid=10454 path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2122 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,W/.test.thalitest( 6731): type=1400 audit(0.0:6): avc: denied { ioctl } for uid=10454 path="socket:[7472]" dev="sockfs" ino=7472 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/.test.thalitest( 6731): type=1400 audit(0.0:7): avc: denied { ioctl } for uid=10454 path="socket:[30898]" dev="sockfs" ino=30898 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,W/DataUsage( 2569): invalid counter update blocked: 'err' by 0
,D/Checkin ( 2569): publish the event [tag = MOT_CCE event name = LOG]
,W/jxcore-log( 6731): Platform android
W/jxcore-log( 6731): 
W/jxcore-log( 6731): Process ARCH arm
W/jxcore-log( 6731): 
,I/jxcore-log( 6731): JXcore Cordova bridge is ready!
I/jxcore-log( 6731): 
,W/jxcore-log( 6731): JXcore engine is started
I/Choreographer( 6731): Skipped 178 frames!  The application may be doing too much work on its main thread.
,I/chromium( 6731): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 6731): Toggling radios to true
I/jxcore-log( 6731): 
,D/BluetoothAdapter( 6731): enable(): BT is already enabled..!
,D/WifiService(  879): New client listening to asynchronous messages
,D/WifiService(  879): setWifiEnabled: true pid=6731, uid=10454
,E/WifiService(  879): Invoking mWifiStateMachine.setWifiEnabled
,I/jxcore-log( 6731): Radios toggled
I/jxcore-log( 6731): 
I/jxcore-log( 6731): My device name is: motorola-XT1072
I/jxcore-log( 6731): 
,I/wpa_supplicant( 1397): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-DISCONNECTED 
D/MDMCTBK (  292): Event received = CTRL-EVENT-DISCONNECTED 
D/MDMCTBK (  292):  STA Disconnected !!
D/TCMD    (  485): NL - Read 1004 bytes from update socket.
,D/TCMD    (  485): NL - message type is RTM_NEWLINK
D/TCMD    (  485): Listening for incoming client connection request
I/MDMCTBK (  292): checkDefaultInst, current pid is = 292
I/MDMCTBK (  292): checkDefaultInst, pid match
I/MDMCTBK (  292): get_property_value, Enter
I/MDMCTBK (  292): get_property_value, Values read from property=1,0,0,0,0,0,1,0,0,1,1,0, length=23
I/MDMCTBK (  292): get_property_value, Exit
I/MDMCTBK (  292): MdmCutbackHndler,wifiDisconnected wifi_dis=1, current_wifi=1
I/MDMCTBK (  292): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=0, mf=0, wfd=0
I/MDMCTBK (  292): set_property_value, Enter
I/MDMCTBK (  292): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  292): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  292): set_property_value, Exit
I/MDMCTBK (  292): MdmCutbackHndler, setWifiCutback, No Wifi
I/MDMCTBK (  292): MdmCutbackHndler,Wifi disconnected !!!
I/MDMCTBK (  292): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=0, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  292): set_property_value, Enter
I/MDMCTBK (  292): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  292): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  292): set_property_value, Exit
E/MDMCTBK (  292): MdmCutbackHndler,Airplane Mode Enabled !! =1
D/TCMD    (  485): NL - Read 68 bytes from update socket.
D/TCMD    (  485): NL - message type is RTM_NEWLINK
D/TCMD    (  485): Listening for incoming client connection request
D/TCMD    (  485): NL - Read 68 bytes from update socket.
D/TCMD    (  485): NL - message type is RTM_NEWLINK
D/TCMD    (  485): Listening for incoming client connection request
,D/Tethering(  879): InitialState.processMessage what=4
,W/Settings(  879): Setting tether_dun_apn has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/Tethering(  879): ApnList is empty for checkDunConfigured()
D/Tethering(  879):  upstream interface types: 
D/Tethering(  879):  1
D/Tethering(  879):  5
D/Tethering(  879):  7
D/Tethering(  879):  0
D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  292): Event received = CTRL-EVENT-STATE-CHANGE 
I/wpa_supplicant( 1397): wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=WORLD
D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-REGDOM-CHANGE
D/MDMCTBK (  292): Event received = CTRL-EVENT-REGDOM-CHANGE
,D/Tethering(  879): sendTetherStateChangedBroadcast 0, 0, 0
,I/wpa_supplicant( 1397): wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=US
D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-REGDOM-CHANGE
D/MDMCTBK (  292): Event received = CTRL-EVENT-REGDOM-CHANGE
,E/WifiStateMachine(  879): WifiStateMachine: Leaving Connected state
E/WifiStateMachine(  879): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$8800 - exit - invokeExitMethods
E/WifiStateMachine(  879): handleNetworkDisconnect any config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  879): handleNetworkDisconnect "NG700" nid=0
E/WifiConfigStore(  879): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,E/WifiStateMachine(  879): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/WifiStateMachine(  879): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/native  (  879): do suspend true
D/WifiP2pService(  879): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  879): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
E/wpa_supplicant( 1397): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
,D/CommandListener(  289): Clearing all IP addresses on wlan0
D/TCMD    (  485): NL - Read 60 bytes from update socket.
D/TCMD    (  485): NL - ignore NL message, type = 21
D/TCMD    (  485): Listening for incoming client connection request
,V/NativeCrypto( 1718): Read error: ssl=0xb88b0d30: I/O error during system call, Connection timed out
,E/WifiStateMachine(  879): setDetailed state, old =CONNECTED and new state=DISCONNECTED hidden=false
E/WifiStateMachine(  879): setDetailed state send new extra info<unknown ssid>
,V/NativeCrypto( 1718): SSL shutdown failed: ssl=0xb88b0d30: I/O error during system call, Broken pipe
,I/SBar.MotoNetworkCtrlr( 1288): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1288): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/WifiMetrics(  879): connected time updated 128993
,D/ConnectivityService(  879): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,D/ConnectivityService(  879): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10016
,D/ConnectivityService(  879): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  879): ValidatedState{ when=-4ms what=532488 arg1=10016 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  879): DefaultState{ when=-4ms what=532488 arg1=10016 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  879): Forcing reevaluation
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  879): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  879): Checking http://clients3.google.com/generate_204 on <unknown ssid>
,I/SBar.MotoNetworkCtrlr( 1288): refreshSignalCluster[0]: wifi: mWifiConnected=true Wifi=0x7f02012a=com.android.systemui:drawable/stat_sys_wifi_signal_0_fully Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
,D/Checkin (  879): publish the event [tag = MOT_WIFI_L1 event name = CONNECT]
,I/ActivityManager(  879): Start proc com.motorola.context for broadcast com.motorola.context/.publisher.location.LocationReceiver: pid=6800 uid=10008 gids={50008, 9997, 3001, 3002, 3003} abi=armeabi-v7a
,D/ConnectivityService(  879): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  879): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
D/Nat464Xlat(  879): requiresClat: netType=1, connected=false, hasIPv4Address=true
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  879): EvaluatingState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/CSLegacyTypeTracker(  879): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  879): DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  879): Disconnected - quitting
D/ConnectivityService(  879): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  879): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  879): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,I/SBar.MotoNetworkCtrlr( 1288): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,D/ConnectivityManager.CallbackHandler( 1288): CM callback handler got msg 524292
,I/SBar.MotoNetworkCtrlr( 1288): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1288): refreshSignalCluster[0]: wifi: mWifiConnected=false Wifi=0x7f020133=com.android.systemui:drawable/stat_sys_wifi_signal_null Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
,I/ModemStatsDSDetect( 1530): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
I/ModemStatsDSDetect( 1530): INET_CONDITION=0 ,activeNet=null
I/ModemStatsDSDetect( 1530): onReceive() - done, currentInetCondition=0
,I/ModemStatsDSDetect( 1530): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
,I/ModemStatsDSDetect( 1530): INET_CONDITION=0 ,activeNet=null
,I/ModemStatsDSDetect( 1530): onReceive() - done, currentInetCondition=0
,E/ConnectivityService(  879): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,D/Checkin (  879): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,E/wpa_supplicant( 1397): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
,E/WifiStateMachine(  879): Start Disconnecting Watchdog 1
,I/wpa_supplicant( 1397): wlan0: CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  292): Event received = CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  292): Event received = CTRL-EVENT-SCAN-STARTED 
,I/SBar.MotoNetworkCtrlr( 1288): onReceive: CONNECTIVITY_ACTION_IMMEDIATE Recieved, mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1288): updateConnectivity[0]: NetworkInfo: null, raw inetCondition= 0
I/SBar.MotoNetworkCtrlr( 1288): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1288): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1288): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1288): onReceive: CONNECTIVITY_ACTION_IMMEDIATE Recieved, mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,E/WifiStateMachine(  879): ConnectModeState: Network connection lost 
,I/SBar.MotoNetworkCtrlr( 1288): updateConnectivity[0]: NetworkInfo: null, raw inetCondition= 0
,I/SBar.MotoNetworkCtrlr( 1288): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1288): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1288): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1288): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1288): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
E/WifiStateMachine(  879): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$8800 - processMessage - processMsg
D/Checkin (  879): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
E/WifiStateMachine(  879): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/WifiStateMachine(  879): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/native  (  879): do suspend true
D/WifiP2pService(  879): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  879): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,E/wpa_supplicant( 1397): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
,D/CommandListener(  289): Clearing all IP addresses on wlan0
,E/WifiStateMachine(  879): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
,I/SBar.MotoNetworkCtrlr( 1288): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1288): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/Checkin (  879): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,E/WifiStateMachine(  879): SUPPLICANT_STATE_CHANGE_EVENT state=DISCONNECTED -> state= DISCONNECTED debouncing=false
E/WifiStateMachine(  879): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
E/WifiStateMachine(  879): Link configuration changed for netId: -1 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  879): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
,E/WifiStateMachine(  879): Link configuration changed for netId: -1 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
,E/WifiStateMachine(  879): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
W/ResourcesManager( 6800): Asset path '/system/framework/com.motorola.motosignature.jar' does not exist or contains no resources.
D/WifiNetworkAgent(  879): NetworkAgent: NetworkAgent channel lost
,E/WifiStateMachine(  879): Link configuration changed for netId: -1 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  879): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
,E/WifiStateMachine(  879): SUPPLICANT_STATE_CHANGE_EVENT state=SCANNING -> state= SCANNING debouncing=false
,E/WifiStateMachine(  879): setDetailed state, old =DISCONNECTED and new state=SCANNING hidden=false
E/WifiStateMachine(  879): setDetailed state send new extra info"NG700"
I/SBar.MotoNetworkCtrlr( 1288): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1288): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1288): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1288): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/Checkin (  879): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,D/Checkin (  879): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,I/ActivityManager(  879): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6826 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/ActivityManager(  879): Killing 6436:com.google.android.videos/u0a98 (adj 15): empty #7
,W/libprocessgroup(  879): failed to open /acct/uid_10098/pid_6436/cgroup.procs: No such file or directory
,W/ResourcesManager( 6826): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/TCMD    (  485): NL - Read 56 bytes from update socket.
D/TCMD    (  485): NL - message type is RTM_NEWLINK
D/TCMD    (  485): Listening for incoming client connection request
,D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 9
D/MDMCTBK (  292): Event received = CTRL-EVENT-BSS-REMOVED 9
D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  292): Event received = CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=wlan0 <3>WPS-AP-AVAILABLE 
D/MDMCTBK (  292): Event received = WPS-AP-AVAILABLE 
I/wpa_supplicant( 1397): wlan0: Trying to associate with SSID 'NG700'
E/wpa_supplicant( 1397): DSDS: eapol_sm_notify_config config->sim_num = 1
D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=wlan0 <3>Trying to associate with
D/MDMCTBK (  292): Event received = Trying to associate with
D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  292): Event received = CTRL-EVENT-STATE-CHANGE 
D/WifiMonitor(  879): didn't find BSSID Trying to associate with SSID 'NG700'
E/WifiStateMachine(  879): [1,453,024,056,679 ms] noteScanEnd no scan source
E/WifiStateMachine(  879): wifi setScanResults statecom.android.server.wifi.WifiStateMachine$DisconnectedState@36efbdf9 sup_state=SCANNING debouncing=false
,E/WifiStateMachine(  879): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATING -> state= CONNECTING debouncing=false
E/WifiStateMachine(  879): setDetailed state, old =SCANNING and new state=CONNECTING hidden=false
E/WifiStateMachine(  879): setDetailed state send new extra info0x
,I/SBar.MotoNetworkCtrlr( 1288): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1288): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1288): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1288): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/Checkin (  879): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,D/TCMD    (  485): NL - Read 312 bytes from update socket.
D/TCMD    (  485): NL - message type is RTM_NEWLINK
D/TCMD    (  485): Listening for incoming client connection request
D/TCMD    (  485): NL - Read 192 bytes from update socket.
D/TCMD    (  485): NL - message type is RTM_NEWLINK
D/TCMD    (  485): Listening for incoming client connection request
D/TCMD    (  485): NL - Read 68 bytes from update socket.
D/TCMD    (  485): NL - message type is RTM_NEWLINK
D/TCMD    (  485): Listening for incoming client connection request
D/TCMD    (  485): NL - Read 1004 bytes from update socket.
D/TCMD    (  485): NL - message type is RTM_NEWLINK
D/TCMD    (  485): Listening for incoming client connection request
D/Tethering(  879): exception when get active network info: java.lang.NullPointerException: Attempt to invoke virtual method 'int android.net.NetworkInfo.getType()' on a null object reference
W/Settings(  879): Setting tether_dun_apn has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/Tethering(  879): ApnList is empty for checkDunConfigured()
D/Tethering(  879):  upstream interface types: 
D/Tethering(  879):  0
D/Tethering(  879):  1
D/Tethering(  879):  5
D/Tethering(  879):  7
I/wpa_supplicant( 1397): wlan0: Associated with c0:ff:d4:d3:aa:48
D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  292): Event received = CTRL-EVENT-STATE-CHANGE 
,D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=wlan0 <3>Associated with c0:ff:d4
D/MDMCTBK (  292): Event received = Associated with c0:ff:d4
D/TCMD    (  485): NL - Read 80 bytes from update socket.
D/TCMD    (  485): NL - message type is RTM_NEWLINK
D/TCMD    (  485): Listening for incoming client connection request
D/TCMD    (  485): NL - Read 80 bytes from update socket.
D/TCMD    (  485): NL - message type is RTM_NEWLINK
D/TCMD    (  485): Listening for incoming client connection request
D/TCMD    (  485): NL - Read 68 bytes from update socket.
D/TCMD    (  485): NL - message type is RTM_NEWLINK
D/TCMD    (  485): Listening for incoming client connection request
,E/WifiStateMachine(  879): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATED -> state= CONNECTING debouncing=false
E/WifiStateMachine(  879): setDetailed state, old =CONNECTING and new state=CONNECTING hidden=false
D/Tethering(  879): sendTetherStateChangedBroadcast 1, 0, 0
,I/Babel_SMS( 6826): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 6826): MmsConfig.loadMmsSettings
I/Babel_SMS( 6826): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
I/Babel_SMS( 6826): MmsConfig.loadFromDatabase
,E/Babel_SMS( 6826): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 6826): MmsConfig.loadFromResources
,E/Babel_SMS( 6826): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 6826): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,E/WifiStateMachine(  879): SUPPLICANT_STATE_CHANGE_EVENT state=FOUR_WAY_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine(  879): setDetailed state, old =CONNECTING and new state=AUTHENTICATING hidden=false
E/WifiStateMachine(  879): setDetailed state send new extra info"NG700"
,D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  292): Event received = CTRL-EVENT-STATE-CHANGE 
,I/SBar.MotoNetworkCtrlr( 1288): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1288): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  292): Event received = CTRL-EVENT-STATE-CHANGE 
,I/wpa_supplicant( 1397): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=wlan0 <3>WPA: Key negotiation com
D/MDMCTBK (  292): Event received = WPA: Key negotiation com
,I/wpa_supplicant( 1397): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-CONNECTED - C
D/MDMCTBK (  292): Event received = CTRL-EVENT-CONNECTED - C
D/MDMCTBK (  292):  STA Connected !!
D/TCMD    (  485): NL - Read 1004 bytes from update socket.
D/TCMD    (  485): NL - message type is RTM_NEWLINK
D/TCMD    (  485): Listening for incoming client connection request
E/MDMCTBK (  292): cmd: IFNAME=wlan0 ASSOCFREQ, reply: 2412, reply_len: 4, ret: 0
D/MDMCTBK (  292): get_freq !!, resp=2412
I/MDMCTBK (  292): get_freq !!, Strip data
I/MDMCTBK (  292): get_freq !!, band = 2, freq = 2412
I/MDMCTBK (  292): checkDefaultInst, current pid is = 292
I/MDMCTBK (  292): checkDefaultInst, pid match
I/MDMCTBK (  292): get_property_value, Enter
I/MDMCTBK (  292): get_property_value, Values read from property=1,0,0,0,0,0,0,0,0,1,1,0, length=23
I/MDMCTBK (  292): get_property_value, Exit
I/MDMCTBK (  292): MdmCutbackHndler,UpdateWifiBand band=2, current_band=2
I/MDMCTBK (  292): MdmCutbackHndler,UpdateWifiBand set mWifi to True, call setWifiCutback and sendSarCtrl!!!
I/MDMCTBK (  292): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=1, mf=0, wfd=0
I/MDMCTBK (  292): set_property_value, Enter
I/MDMCTBK (  292): set_property_value, Values updated in the property=1,0,0,0,0,0,1,0,0,1,1,0
,I/MDMCTBK (  292): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  292): set_property_value, Exit
I/MDMCTBK (  292): MdmCutbackHndler,setWifiCutback, Wifi_cbk_Used= 0, Wifi_band=2, p2p0 = 1, wlan0 = 1, data=0
I/MDMCTBK (  292): MdmCutbackHndler,WifiBand =2, MifiBand =-1, tx_pwr=18
I/MDMCTBK (  292): MdmCutbackHndler, set WIFI TX pwr !!
I/MDMCTBK (  292): checkDefaultInst, current pid is = 292
I/MDMCTBK (  292): checkDefaultInst, pid match
I/MDMCTBK (  292): get_property_value, Enter
I/MDMCTBK (  292): get_property_value, Values read from property=1,0,0,0,0,0,1,0,0,1,1,0, length=23
I/MDMCTBK (  292): get_property_value, Exit
I/MDMCTBK (  292): create_thread_wpa_supplicant: Started WPA thread for wifi_set_tx_pwr thread -1223148064
I/MDMCTBK (  292): return from set_get_from_wpa_supplicant
I/MDMCTBK (  292): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=1, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  292): set_property_value, Enter
I/MDMCTBK (  292): set_property_value, Values updated in the property=1,0,0,0,0,0,1,0,0,1,1,0
I/MDMCTBK (  292): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  292): set_property_value, Exit
E/MDMCTBK (  292): MdmCutbackHndler,Airplane Mode Enabled !! =1
D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  292): Event received = CTRL-EVENT-STATE-CHANGE 
,I/SBar.MotoNetworkCtrlr( 1288): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1288): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
D/MDMCTBK (  292): wifi_set_tx_pwr: SETTXPOWER = 18
E/WifiStateMachine(  879): SUPPLICANT_STATE_CHANGE_EVENT state=GROUP_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine(  879): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING hidden=false
E/MDMCTBK (  292): cmd: IFNAME=wlan0 DRIVER SETTXPOWER 18, reply: OK
E/MDMCTBK (  292): , reply_len: 3, ret: 0
E/MDMCTBK (  292): MdmCutbackHndler, resp=OK
E/MDMCTBK (  292): 
D/MDMCTBK (  292): wifi_set_tx_pwr: Exit
E/WifiStateMachine(  879): Network connection established
E/WifiStateMachine(  879): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR hidden=false
,I/SBar.MotoNetworkCtrlr( 1288): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1288): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1288): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1288): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,E/WifiStateMachine(  879): setDetailed state, old =OBTAINING_IPADDR and new state=CONNECTING hidden=false
,I/SBar.MotoNetworkCtrlr( 1288): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1288): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/ConnectivityService(  879): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
,D/ConnectivityService(  879): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
E/WifiStateMachine(  879): L2ConnectedState any config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  879): L2ConnectedState "NG700" nid=0
E/WifiConfigStore(  879): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,E/WifiStateMachine(  879): enter ObtainingIpState netId=0 "NG700"WPA_PSK  roam=0 static=false watchdog= 1
E/WifiStateMachine(  879): ObtainingIpAddress any config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  879): ObtainingIpAddress "NG700" nid=0
E/WifiConfigStore(  879): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,D/CommandListener(  289): Setting iface cfg
,E/WifiStateMachine(  879): Start Dhcp Watchdog 2
,E/WifiStateMachine(  879): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  879): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES
,E/WifiStateMachine(  879): setSuspendOptimizationsNative: 1 false -want true stack:setSuspendOptimizationsNative - handlePreDhcpSetup - processMessage - processMsg
E/native  (  879): do suspend false
E/wpa_supplicant( 1397): wpa_driver_nl80211_driver_cmd: failed to issue private commands
E/WifiStateMachine(  879): Unexpected BatchedScanResults :null
,W/Settings( 6826): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
E/wpa_supplicant( 1397): wpa_driver_nl80211_driver_cmd: failed to issue private commands
D/WifiP2pService(  879): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@3e8fa3b target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  879): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@3e8fa3b target=com.android.internal.util.StateMachine$SmHandler }
,I/Babel_Crash( 6826): startup - clean
,I/Babel   ( 6826): deleted: false for 0
,W/VideoCapabilities( 6826): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 6826): Unsupported mime audio/amr-wb-plus
,W/VideoCapabilities( 6826): Unsupported mime video/mpeg2
,I/VideoCapabilities( 6826): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 6826): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6826): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6826): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6826): Unrecognized profile 2130706433 for video/avc
,I/ActivityManager(  879): Killing 6168:com.google.android.googlequicksearchbox:search/u0a39 (adj 15): empty #7
,E/DHCPCD  ( 6867): fopen `/system/etc/dhcpcd/dhcpcd.conf': m
,I/DHCPCD  ( 6867): version 5.5.6 starting
,E/DHCPCD  ( 6867): fopen `/system/etc/dhcpcd/dhcpcd.conf': m
,D/DHCPCD  ( 6867): wlan0: using ClientID 01:44:80:eb:7b:5a:06
D/DHCPCD  ( 6867): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
,W/libprocessgroup(  879): failed to open /acct/uid_10039/pid_6168/cgroup.procs: No such file or directory
,I/vclib   ( 6826): onServiceConnected
W/Babel   ( 6826): Attempted to change video mute state without an active call.
,D/DHCPCD  ( 6867): wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
I/DHCPCD  ( 6867): wlan0: rebinding lease of 192.168.1.123
D/DHCPCD  ( 6867): wlan0: sending REQUEST (xid 0x26fb1546), next in 3.55 seconds
,I/DHCPCD  ( 6867): wlan0: acknowledged 192.168.1.123 from 192.168.1.1
,I/DHCPCD  ( 6867): wlan0: leased 192.168.1.123 for 86400 seconds
D/DHCPCD  ( 6867): wlan0: adding IP address 192.168.1.123/24
D/TCMD    (  485): NL - Read 60 bytes from update socket.
D/TCMD    (  485): NL - ignore NL message, type = 20
D/TCMD    (  485): Listening for incoming client connection request
D/DHCPCD  ( 6867): wlan0: adding route to 192.168.1.0/24
D/DHCPCD  ( 6867): wlan0: adding default route via 192.168.1.1
D/DHCPCD  ( 6867): wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
,D/DHCPCD  ( 6867): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
,E/WifiStateMachine(  879): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
,E/WifiStateMachine(  879): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES v4
,E/WifiStateMachine(  879): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
E/WifiStateMachine(  879): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
E/native  (  879): do suspend true
,D/WifiP2pService(  879): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  879): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,E/WifiStateMachine(  879): WifiStateMachine DHCP successful
E/WifiStateMachine(  879): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,E/WifiStateMachine(  879): updateLinkProperties nid: 0 state: CONNECTING reason: DHCP_SUCCESS v4 v4r v4dns isprov
E/WifiStateMachine(  879): Calling ARP set with IP = 192.168.1.123
,E/WifiStateMachine(  879): setDetailed state, old =CONNECTING and new state=CAPTIVE_PORTAL_CHECK hidden=false
,I/SBar.MotoNetworkCtrlr( 1288): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1288): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1288): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1288): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,E/WifiStateMachine(  879): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED hidden=false
,D/ConnectivityService(  879): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,D/ConnectivityService(  879): Adding iface wlan0 to network 101
,I/SBar.MotoNetworkCtrlr( 1288): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1288): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1288): refreshSignalCluster[0]: wifi: mWifiConnected=true Wifi=0x7f020129=com.android.systemui:drawable/stat_sys_wifi_signal_0 Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
,D/Checkin (  879): publish the event [tag = MOT_WIFI_L1 event name = CONNECT]
,E/ConnectivityService(  879): Unexpected mtu value: 0, wlan0
D/ConnectivityService(  879): Adding Route [fe80::/64 -> :: wlan0] to network 101
,D/ConnectivityService(  879): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,D/ConnectivityService(  879): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
D/ConnectivityService(  879): Setting Dns servers for network 101 to [/192.168.1.1]
D/Nat464Xlat(  879): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  879): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityService(  879): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  879): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  879): Connected
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  879): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  879): Checking http://clients3.google.com/generate_204 on "NG700"
D/ConnectivityService(  879): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  879):    accepting network in place of null
I/SBar.MotoNetworkCtrlr( 1288): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1288): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/ConnectivityService(  879): UpdateTcpBufferSizes: same sizes as current, ignore operation
,D/CSLegacyTypeTracker(  879): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/ConnectivityService(  879): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityService(  879): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
,D/ConnectivityService(  879): UpdateTcpBufferSizes: same sizes as current, ignore operation
D/ConnectivityService(  879): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
I/ModemStatsDSDetect( 1530): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
,I/ModemStatsDSDetect( 1530): INET_CONDITION=0 ,activeNet=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/ModemStatsDSDetect( 1530): onReceive() - done, currentInetCondition=0
,D/ConnectivityManager.CallbackHandler( 1288): CM callback handler got msg 524290
,D/Checkin (  879): publish the event [tag = MOT_WIFI_L1 event name = CONNECT]
,I/SBar.MotoNetworkCtrlr( 1288): onReceive: CONNECTIVITY_ACTION_IMMEDIATE Recieved, mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
E/WifiStateMachine(  879): ConnectedState Enter  mScreenOn=false scanperiod=20000
I/SBar.MotoNetworkCtrlr( 1288): updateConnectivity[0]: NetworkInfo: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false], raw inetCondition= 0
I/SBar.MotoNetworkCtrlr( 1288): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1288): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1288): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  879): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Sun, 17 Jan 2016 09:47:39 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1453024059233], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1453024059220]}
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  879): Don't send network conditions - lacking user consent.
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  879): Validated
,D/ConnectivityService(  879): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  879): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  879): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService(  879): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  879): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/ConnectivityManager.CallbackHandler( 1288): CM callback handler got msg 524290
,I/ModemStatsDSDetect( 1530): onReceive() -Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) }
I/SBar.MotoNetworkCtrlr( 1288): onReceive: INET_CONDITION_ACTION Recieved, mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/ModemStatsDSDetect( 1530): INET_CONDITION=100 ,activeNet=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ModemStatsDSDetect( 1530): Inetcondition changed, white->blue
I/ModemStatsDSDetect( 1530): onReceive() - done, currentInetCondition=100
,I/SBar.MotoNetworkCtrlr( 1288): updateConnectivity: The netConditon[0] for netType 1=WiFi is updated as 1=good by android.net.conn.INET_CONDITION_ACTION, icon color should be white (on KK); without "!" (on L).
I/SBar.MotoNetworkCtrlr( 1288): updateConnectivity[0]: NetworkInfo: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false], raw inetCondition= 1
I/SBar.MotoNetworkCtrlr( 1288): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1288): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1288): refreshSignalCluster[0]: wifi: mWifiConnected=true Wifi=0x7f02012a=com.android.systemui:drawable/stat_sys_wifi_signal_0_fully Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
I/SBar.MotoNetworkCtrlr( 1288): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/ConnectivityService(  879): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/ConnectivityService(  879): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
D/PollingManager( 2569): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/Central_PollingManager( 1476): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
W/ContextImpl( 1476): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1469 android.content.ContextWrapper.sendBroadcast:381 com.motorola.blur.service.blur.BSUtils.sendBroadcast:94 com.motorola.blur.service.blur.BSUtils.sendBroadcast:90 com.motorola.ccc.plm.pollingmanager.PollingManagerService$MyConnectivityReceiver.onReceive:491 
,D/Tethering(  879): MasterInitialState.processMessage what=3
,D/PollingManager( 2569): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/Tethering(  879): MasterInitialState.processMessage what=3
,D/PollingManager( 2569): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/Central_PollingManager( 1476): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/Central_PollingManager( 1476): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
,I/NetworkMonitor( 6534): type=WIFI subType= reason=null isConnected=true
,V/MusicLeanback( 6534): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/NetworkMonitor( 6534): type=WIFI subType= reason=null isConnected=true
,D/OtaApp  ( 2569): [debug] > pollingManagerService, connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ActivityManager(  879): Start proc com.android.mms for broadcast com.android.mms/.transaction.MmsSystemEventReceiver: pid=6924 uid=10023 gids={50023, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/PollingManager( 2569): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/PollingManager( 2569): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
D/PollingManager( 2569): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/PollingManager( 2569): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
,D/PollingManager( 2569): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/PollingManager( 2569): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
,D/OtaApp  ( 2569): [debug] > pollingManagerService, connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/OtaApp  ( 2569): [debug] > PollingManagerService, not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
,D/CCE     ( 2569): Registering with Alarm Manager to restart CCE
,D/CCE     ( 2569): Registering with Alarm Manager to restart CCE
,D/CCE     ( 2569): Registering with Alarm Manager to restart CCE
,D/OtaApp  ( 2569): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.ccc.ota.pm.POLLINGMGR_CONNECTIVITY
,D/OtaApp  ( 2569): [debug] > CusSM.onRadioDown
,I/art     (  879): Explicit concurrent mark sweep GC freed 44449(2MB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 20MB/30MB, paused 1.974ms total 127.053ms
,V/Mms     ( 6924): mnc/mcc: 
,V/Mms     ( 6924): tag: int value: recipientLimit - 20
,V/Mms     ( 6924): tag: int value: smsToMmsTextThreshold - 6
V/Mms     ( 6924): tag: int value: emergencySmsTimeout - 30
,V/Mms     ( 6924): tag: int value: maxSubjectLength - 80
,V/Mms     ( 6924): tag: bool value: smsForceShowEncodingMenu - true
,V/Mms     ( 6924): tag: bool value: enableGroupMms - false
V/Mms     ( 6924):  mUserAgent = MOT-XT1072/Mms-5.0,  mUaProfUrl = http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,E/WifiStateMachine(  879): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,fe80::4680:ebff:fe7b:5a06/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,D/ConnectivityService(  879): UpdateTcpBufferSizes: same sizes as current, ignore operation
D/Nat464Xlat(  879): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  879): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityManager.CallbackHandler( 1288): CM callback handler got msg 524295
E/WifiStateMachine(  879): updateLinkProperties nid: 0 state: CONNECTED reason: CMD_UPDATE_LINKPROPERTIES v4 v4r v4dns isprov
,W/ResourcesManager( 6924): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/ActivityManager(  879): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=6952 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  879): Killing 6295:com.google.android.gms/u0a16 (adj 15): empty #7
,D/PhoneMonitor( 6952): Register our PhoneStateListener
,W/libprocessgroup(  879): failed to open /acct/uid_10016/pid_6295/cgroup.procs: No such file or directory
,D/MobileConnectivityChangeReceiver( 6952): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 6952): onReceive CONNECTIVITY_CHANGE networkType=1
,I/ActivityManager(  879): Start proc com.google.android.gms for broadcast com.google.android.gms/.mdm.receivers.ConnectivityReceiver: pid=6970 uid=10016 gids={50016, 9997, 3003, 1028, 1015, 3002, 3001, 1005, 1007, 3007, 2001, 3006} abi=armeabi-v7a
,I/ActivityManager(  879): Killing 6482:com.android.vending/u0a32 (adj 15): empty #7
,D/ConnectivityService(  879): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,W/libprocessgroup(  879): failed to open /acct/uid_10032/pid_6482/cgroup.procs: No such file or directory
,W/ResourcesManager( 6970): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 6970): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/MultiDex( 6970): VM with version 2.1.0 has multidex support
I/MultiDex( 6970): install
I/MultiDex( 6970): VM has multidex support, MultiDex support library is disabled.
,V/JNIHelp ( 6970): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 6970): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 6970): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@2b2e7024: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6970): Installed default security provider GmsCore_OpenSSL
,D/NativeLibraryUtils( 6970): Install completed successfully. count=14 extracted=0
,I/CheckinService( 6970): Checkin interval check for package: unspecified last checkin: 1453023970618 min interval config: 0 actual interval: 89947
,I/CheckinService( 6970): Disabling old GoogleServicesFramework version
,I/CheckinService( 6970): Checking schedule, now: 1453024060603 next: 1453024000595
I/CheckinService( 6970): active receiver: enabled
,I/CheckinService( 6970): Preparing to send checkin request
,I/EventLogService( 6970): Accumulating logs since 1453023967605
,I/iu.SyncManager( 6970): SYNC; picasa accounts
,D/NetworkLogImpl( 6970): Loaded NetworkSpeedPredictor
,I/iu.Environment( 6970): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 6970): num queued entries: 0
I/iu.UploadsManager( 6970): num updated entries: 0
I/iu.SyncManager( 6970): NEXT; no task
,I/art     ( 6970): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 6970): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,I/ActivityManager(  879): Start proc com.google.android.apps.photos for broadcast com.google.android.apps.photos/.jobqueue.JobServiceBroadcastReceiver: pid=7017 uid=10088 gids={50088, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/jxcore-log( 6731): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
I/jxcore-log( 6731): 
,I/CheckinRequestBuilder( 6970): Checkin reason type: 8 attempt count: 1
,D/WifiService(  879): New client listening to asynchronous messages
,E/ActivityThread( 6970): Failed to find provider info for com.google.android.wearable.settings
,V/GLSActivity( 1718): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1718): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  879): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7043 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/Babel   ( 6826): connection state changed from UNKNOWN to CONNECTED
,I/ActivityManager(  879): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=7062 uid=10016 gids={50016, 9997, 3003, 1028, 1015, 3002, 3001, 1005, 1007, 3007, 2001, 3006} abi=armeabi-v7a
,I/ActivityManager(  879): Killing 6800:com.motorola.context/u0a8 (adj 15): empty #7
,W/libprocessgroup(  879): failed to open /acct/uid_10008/pid_6800/cgroup.procs: No such file or directory
,W/ResourcesManager( 7062): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7062): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/MultiDex( 7062): VM with version 2.1.0 has multidex support
I/MultiDex( 7062): install
I/MultiDex( 7062): VM has multidex support, MultiDex support library is disabled.
,I/jxcore-log( 6731): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
I/jxcore-log( 6731): 
,I/jxcore-log( 6731): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliCryptoManager.js
I/jxcore-log( 6731): 
V/JNIHelp ( 7062): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/ActivityThread( 7062): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/ContextImpl( 7043): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,W/System  ( 7062): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@1fec3e2e: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7062): Installed default security provider GmsCore_OpenSSL
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7043): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,I/GAv4    ( 7043): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 7043):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 7043):   adb logcat -s GAv4
,I/jxcore-log( 6731): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliEmitter.js
I/jxcore-log( 6731): 
,W/GAv4    ( 7043): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7043): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,I/jxcore-log( 6731): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNativeLayer.js
I/jxcore-log( 6731): 
I/jxcore-log( 6731): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationManager.js
I/jxcore-log( 6731): 
,W/GAv4    ( 7043): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,I/art     ( 7062): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 7062): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7043): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,I/jxcore-log( 6731): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log( 6731): 
,W/GAv4    ( 7043): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,D/NativeLibraryUtils( 7062): Install completed successfully. count=14 extracted=0
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
D/DrmWidevineDash(  294): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb5039000
E/DrmWidevineDash(  294): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb5039000
,D/DrmWidevineDash(  294): OEMCrypto_Initialize: ends! returns 0
D/DrmWidevineDash(  294): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  294): hlos api version =  9
D/DrmWidevineDash(  294): tz api version =  8
D/DrmWidevineDash(  294): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  294): OEMCrypto_IsKeyboxValid: starts!
,D/DrmWidevineDash(  294): OEMCrypto_IsKeyboxValid: ends! returns 0
D/WVCdm   (  294): OEMCrypto_Initialize Level 1 success. I will use level 1.
D/DrmWidevineDash(  294): OEMCrypto_OpenSession: starts! SID=0xb5614960
,D/DrmWidevineDash(  294): OEMCrypto_OpenSession SID = 1
,D/DrmWidevineDash(  294): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  294): OEMCrypto_GetRandom: starts! randomData=0xb846c548, dataLength=8
D/DrmWidevineDash(  294): OEMCrypto_GetRandom: ends! returns 0
,D/DrmWidevineDash(  294): OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb8380718, wrapped_rsa_key_length=1280
,D/DrmWidevineDash(  294): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
I/WVCdm   (  294): CdmEngine::QueryKeyControlInfo
W/WVCdm   (  294): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  294): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  294): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  294): OEMCrypto_GetDeviceID: starts! deviceID=0xb84b7a30, idLength=0xb0af7730
,D/DrmWidevineDash(  294): OEMCrypto_GetDeviceID: ends! returns 0
D/DrmWidevineDash(  294): OEMCrypto_SupportsUsageTable: starts!
,D/DrmWidevineDash(  294): OEMCrypto_SupportsUsageTable: is_supported = 1
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
D/WVCdm   (  294): PrepareKeyRequest: nonce=1606571015
D/DrmWidevineDash(  294): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb8380f80
D/DrmWidevineDash(  294): message_length=1591, signature=0xb83815c0, signature_length=2964289300
,I/WebViewFactory( 7043): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 7043): Time to load native libraries: 1 ms (timestamps 4723-4724)
I/LibraryLoader( 7043): Expected native library version number "",actual native library version number ""
D/ConnectivityService(  879): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  879): MasterInitialState.processMessage what=3
,V/WebViewChromiumFactoryProvider( 7043): Binding Chromium to main looper Looper (main, tid 1) {367a8ede}
I/LibraryLoader( 7043): Expected native library version number "",actual native library version number ""
I/chromium( 7043): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/NetworkMonitor( 6534): type=WIFI subType= reason=null isConnected=true
,I/BrowserStartupController( 7043): Initializing chromium process, singleProcess=true
W/art     ( 7043): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 7043): ApplicationContext is null in ApplicationStatus
,D/DrmWidevineDash(  294): OEMCrypto_GenerateRSASignature returns 0
,D/PollingManager( 2569): connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/PollingManager( 2569): now: 204759 ,futureTime: 9223372036854775807
D/PollingManager( 2569): connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/PollingManager( 2569): now: 204759 ,futureTime: 9223372036854775807
D/PollingManager( 2569): connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/PollingManager( 2569): now: 204759 ,futureTime: 9223372036854775807
D/OtaApp  ( 2569): [debug] > pollingManagerService, connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/Central_PollingManager( 1476): connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/OtaApp  ( 2569): [debug] > PollingManagerService, now: 204762 ,futureTime: 29810934
W/ContextImpl( 1476): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1469 android.content.ContextWrapper.sendBroadcast:381 com.motorola.blur.service.blur.BSUtils.sendBroadcast:94 com.motorola.blur.service.blur.BSUtils.sendBroadcast:90 com.motorola.ccc.plm.pollingmanager.PollingManagerService$MyConnectivityReceiver.onReceive:491 
D/OtaApp  ( 2569): [debug] > Polling alarm set to expire at: 29810934 Current Time: 204762
,I/WVCdm   (  294): CdmEngine::CloseSession
D/DrmWidevineDash(  294): OEMCrypto_CloseSession: starts! SID=1
,D/DrmWidevineDash(  294): OEMCrypto_CloseSession: ends! returns 0
I/WVCdm   (  294): L3 Terminate.
D/DrmWidevineDash(  294): OEMCrypto_Terminate: starts!
D/DrmWidevineDash(  294): Service_Uninitialize: starts!
D/QSEECOMAPI: (  294): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  294): QSEECom_shutdown_app, app_id = 3
D/DrmWidevineDash(  294): Service_Uninitialize: ends! returns 0x0
,D/DrmWidevineDash(  294): OEMCrypto_Terminate: ends! returns 0
,D/Central_PollingManager( 1476): now: 204775 ,futureTime: 86473303
D/Central_PollingManager( 1476): Polling alarm set to expire at: 86473303 Current Time: 204775
,D/OtaApp  ( 2569): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.ccc.ota.pm.POLLINGMGR_CONNECTIVITY
D/OtaApp  ( 2569): [debug] > CusSM.onRadioUp
D/OtaApp  ( 2569): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,W/chromium( 7043): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
D/OtaApp  ( 2569): [debug] > CusSM.runStateMachine: getVersions's version Blur_Version.22.21.28.thea_reteu.reteuall.en.EU; getDescription's versionBlur_Version.22.21.28.thea_reteu.reteuall.en.EU
,I/OtaApp  ( 2569): [info] > CusSM.runStateMachine: found version Blur_Version.22.21.28.thea_reteu.reteuall.en.EU in database with state (RequestPermission)
D/Checkin ( 2569): publish the event [tag = MOT_OTA event name = LOG]
,E/libEGL  ( 7043): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 7043): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 7043): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 7043): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7043): Build Date: 10/28/14 Tue
I/Adreno-EGL( 7043): Local Branch: 
I/Adreno-EGL( 7043): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 7043): Local Patches: NONE
I/Adreno-EGL( 7043): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
D/OtaApp  ( 2569): [debug] > CusSM.runStateMachine: server told to :continue
D/OtaApp  ( 2569): [debug] > CusSM.runStateMachine: user is being notified for version Blur_Version.22.21.28.thea_reteu.reteuall.en.EU
D/OtaApp  ( 2569): [debug] > CusSM.runStateMachine: getDownloadOptStartStopTime text null
,D/OtaApp  ( 2569): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,I/art     ( 2569): Explicit concurrent mark sweep GC freed 39378(2MB) AllocSpace objects, 6(119KB) LOS objects, 39% free, 11MB/19MB, paused 1.152ms total 99.044ms
,I/NSApplication( 7043): Starting up...
,W/AudioManagerAndroid( 7043): Requires BLUETOOTH permission
,D/MMApiProvisionService( 2569): isDeviceProvisioned: deviceId = 2072049230914535424
,D/CCE     ( 2569): trying to auto login since I haven't yet and the radio is up now
I/MMApiProvisionService( 2569): createDeviceIdOrLogin update_device
,D/Checkin ( 2569): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiProvisionService( 2569): Not proxy app, so login/provision not allowed
,D/MMApiProvisionService( 2569): isDeviceProvisioned: deviceId = 2072049230914535424
,D/CCE     ( 2569): trying to auto login since I haven't yet and the radio is up now
,I/MMApiProvisionService( 2569): createDeviceIdOrLogin update_device
D/Checkin ( 2569): publish the event [tag = MOT_CCE event name = LOG]
,I/ActivityManager(  879): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=7131 uid=10052 gids={50052, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  879): Killing 6534:com.google.android.music:main/u0a80 (adj 15): empty #7
,D/MMApiProvisionService( 2569): isDeviceProvisioned: deviceId = 2072049230914535424
,D/MMApiProvisionService( 2569): set mOutstandingReq to true.
I/ Nonce  ( 2569):  Nonce getNonce 
I/ Nonce  ( 2569):  Nonce Request 
I/ Nonce  ( 2569):  Nonce execute Request 
,D/MMApiWebService( 2569): doRequest() with req : MMApiWSRequest(/v1/gdi/nonce.json)
,I/jxcore-log( 6731): Test app app.js loaded
I/jxcore-log( 6731): 
,I/Choreographer( 6731): Skipped 389 frames!  The application may be doing too much work on its main thread.
,I/chromium( 6731): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,W/libprocessgroup(  879): failed to open /acct/uid_10080/pid_6534/cgroup.procs: No such file or directory
,I/WVCdm   (  294): CdmEngine::OpenSession
I/WVCdm   (  294): Level3 Library Sep 25 2014 17:10:03
,W/WVCdm   (  294): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,I/art     (  879): Explicit concurrent mark sweep GC freed 15036(742KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 20MB/30MB, paused 1.555ms total 125.432ms
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
,D/MMApiProvisionService( 2569): isDeviceProvisioned: deviceId = 2072049230914535424
,D/CCE     ( 2569): trying to auto login since I haven't yet and the radio is up now
I/MMApiProvisionService( 2569): createDeviceIdOrLogin update_device
D/Checkin ( 2569): publish the event [tag = MOT_CCE event name = LOG]
D/MMApiProvisionService( 2569): Not proxy app, so login/provision not allowed
,D/QSEECOMAPI: (  294): Loaded image: APP id = 3
,D/DrmWidevineDash(  294): Service_Initialize: ends! returns 0
,D/DrmWidevineDash(  294): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb5039000
E/DrmWidevineDash(  294): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb5039000
D/MMApiWebService( 2569): generating token using payload instead of using session token
,D/DrmWidevineDash(  294): OEMCrypto_Initialize: ends! returns 0
,D/DrmWidevineDash(  294): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  294): hlos api version =  9
D/DrmWidevineDash(  294): tz api version =  8
D/DrmWidevineDash(  294): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  294): OEMCrypto_IsKeyboxValid: starts!
,D/DrmWidevineDash(  294): OEMCrypto_IsKeyboxValid: ends! returns 0
,D/WVCdm   (  294): OEMCrypto_Initialize Level 1 success. I will use level 1.
D/DrmWidevineDash(  294): OEMCrypto_OpenSession: starts! SID=0xb0af7960
D/DrmWidevineDash(  294): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  294): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  294): OEMCrypto_GetRandom: starts! randomData=0xb83e6aa8, dataLength=8
D/DrmWidevineDash(  294): OEMCrypto_GetRandom: ends! returns 0
D/DrmWidevineDash(  294): OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb8380718, wrapped_rsa_key_length=1280
,D/DrmWidevineDash(  294): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
,I/WVCdm   (  294): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  294): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
,W/WVCdm   (  294): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  294): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  294): OEMCrypto_GetDeviceID: starts! deviceID=0xb84b7a70, idLength=0xb0af7730
,D/DrmWidevineDash(  294): OEMCrypto_GetDeviceID: ends! returns 0
D/DrmWidevineDash(  294): OEMCrypto_SupportsUsageTable: starts!
,D/DrmWidevineDash(  294): OEMCrypto_SupportsUsageTable: is_supported = 1
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
D/WVCdm   (  294): PrepareKeyRequest: nonce=1955032662
D/DrmWidevineDash(  294): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb8380f80
D/DrmWidevineDash(  294): message_length=1626, signature=0xb83815e0, signature_length=2964289300
,I/art     ( 1476): Explicit concurrent mark sweep GC freed 4300(194KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 7MB/12MB, paused 1.384ms total 35.810ms
,D/ Nonce  ( 2569):  getUrl method url https://argo.svcmot.com:443/v1/gdi/nonce.json/ZX1C223JKW?appid=6R1TANEX3ZMQ6EU1UH43P34C8B868KTE
,I/MMApiWSBase( 2569): doRequest(): url: https://argo.svcmot.com:443/v1/gdi/nonce.json/ZX1C223JKW?appid=6R1TANEX3ZMQ6EU1UH43P34C8B868KTE
,D/Checkin ( 2569): publish the event [tag = MOT_CCE event name = LOG]
,D/DrmWidevineDash(  294): OEMCrypto_GenerateRSASignature returns 0
,I/ActivityManager(  879): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7155 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  879): Killing 6924:com.android.mms/u0a23 (adj 15): empty #7
,I/art     (  314): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 273us total 20.500ms
,I/art     (  314): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 254us total 20.052ms
,I/art     (  314): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 244us total 19.903ms
,W/libprocessgroup(  879): failed to open /acct/uid_10023/pid_6924/cgroup.procs: No such file or directory
,W/ResourcesManager( 7155): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/ActivityManager(  879): Start proc android.process.acore for content provider com.android.providers.contacts/.ContactsProvider2: pid=7181 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,I/WVCdm   (  294): CdmEngine::CloseSession
D/DrmWidevineDash(  294): OEMCrypto_CloseSession: starts! SID=1
,D/DrmWidevineDash(  294): OEMCrypto_CloseSession: ends! returns 0
I/WVCdm   (  294): L3 Terminate.
D/DrmWidevineDash(  294): OEMCrypto_Terminate: starts!
D/DrmWidevineDash(  294): Service_Uninitialize: starts!
D/QSEECOMAPI: (  294): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  294): QSEECom_shutdown_app, app_id = 3
,D/DrmWidevineDash(  294): Service_Uninitialize: ends! returns 0x0
D/DrmWidevineDash(  294): OEMCrypto_Terminate: ends! returns 0
,I/ActivityManager(  879): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=7206 uid=10080 gids={50080, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  879): Killing 7017:com.google.android.apps.photos/u0a88 (adj 13): empty #7
,I/ContactLocale( 7181): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,I/ActivityManager(  879): Killing 6952:com.google.android.setupwizard/u0a35 (adj 15): empty #8
,I/dex2oat ( 7229): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=34 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,W/libprocessgroup(  879): failed to open /acct/uid_10088/pid_7017/cgroup.procs: No such file or directory
,W/libprocessgroup(  879): failed to open /acct/uid_10035/pid_6952/cgroup.procs: No such file or directory
,I/dex2oat ( 7229): dex2oat took 71.573ms (threads: 4)
,I/Adreno-EGL( 7062): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 7062): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7062): Build Date: 10/28/14 Tue
I/Adreno-EGL( 7062): Local Branch: 
I/Adreno-EGL( 7062): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 7062): Local Patches: NONE
I/Adreno-EGL( 7062): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/MusicStore( 7206): Database version: 120
,I/ Nonce  ( 2569):  Nonce Reponse 
D/        ( 2569): ProvisionWS.Response: processing response data: {"error":"OK","nonce":"d05fa93b-c4ff-41a8-a6c0-0736f32fec9a"}
D/MMApiWSBase( 2569): doRequest(): /v1/gdi/nonce.json resp length: 61
,I/ Nonce  ( 2569):  Nonce Handle Reponse 
D/MMApiProvisionService( 2569): mOutstandingReq set to false
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7206): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,I/Adreno-EGL( 7062): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 7062): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7062): Build Date: 10/28/14 Tue
I/Adreno-EGL( 7062): Local Branch: 
I/Adreno-EGL( 7062): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 7062): Local Patches: NONE
I/Adreno-EGL( 7062): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7206): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7206): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,D/MMApiProvisionService( 2569):  pTime 1452855605507 sExp 172742 cTime 1453024063674 tTime 1453028347507
D/MMApiProvisionService( 2569):  No login Required 
,I/Adreno-EGL( 7062): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 7062): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7062): Build Date: 10/28/14 Tue
I/Adreno-EGL( 7062): Local Branch: 
I/Adreno-EGL( 7062): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 7062): Local Patches: NONE
I/Adreno-EGL( 7062): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,W/ResourcesManager( 7206): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 7206): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 7206): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/Adreno-EGL( 7062): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 7062): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7062): Build Date: 10/28/14 Tue
I/Adreno-EGL( 7062): Local Branch: 
I/Adreno-EGL( 7062): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 7062): Local Patches: NONE
I/Adreno-EGL( 7062): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,W/ActivityThread( 7206): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 7206): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@2ca286c1: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 7206): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 7206): GMSCore installation verified
,I/ConfigStore( 7206): Config Database version: 1
,I/MediaRouter( 7206): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 7206): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/NetworkMonitor( 7206): type=WIFI subType= reason=null isConnected=true
,I/NetworkMonitor( 7206): type=WIFI subType= reason=null isConnected=true
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:32000 mC
,I/ActivityManager(  879): Start proc com.android.mms for broadcast com.android.mms/.transaction.MmsSystemEventReceiver: pid=7253 uid=10023 gids={50023, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/GHttpClientFactory( 7206): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 7206): Using platform SSLCertificateSocketFactory
,I/ActivityManager(  879): Killing 6826:com.google.android.talk/u0a70 (adj 15): empty #7
,W/DataUsage( 2569): invalid counter update blocked: 'err' by 0
,I/CheckinRequestBuilder( 6970): Classify the device as Phone.
,D/Checkin ( 2569): publish the event [tag = MOT_CCE event name = LOG]
,W/libprocessgroup(  879): failed to open /acct/uid_10070/pid_6826/cgroup.procs: No such file or directory
,V/Mms     ( 7253): mnc/mcc: 
,V/Mms     ( 7253): tag: int value: recipientLimit - 20
,V/Mms     ( 7253): tag: int value: smsToMmsTextThreshold - 6
V/Mms     ( 7253): tag: int value: emergencySmsTimeout - 30
V/Mms     ( 7253): tag: int value: maxSubjectLength - 80
V/Mms     ( 7253): tag: bool value: smsForceShowEncodingMenu - true
V/Mms     ( 7253): tag: bool value: enableGroupMms - false
V/Mms     ( 7253):  mUserAgent = MOT-XT1072/Mms-5.0,  mUaProfUrl = http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/ResourcesManager( 7253): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/ActivityManager(  879): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=7283 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  879): Killing 7043:com.google.android.apps.magazines/u0a81 (adj 15): empty #7
,D/PhoneMonitor( 7283): Register our PhoneStateListener
,I/CheckinTask( 6970): Sending checkin request (9507 bytes)
,W/libprocessgroup(  879): failed to open /acct/uid_10081/pid_7043/cgroup.procs: No such file or directory
,D/MobileConnectivityChangeReceiver( 7283): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 7283): onReceive CONNECTIVITY_CHANGE networkType=1
,I/ActivityManager(  879): Killing 7131:com.android.chrome/u0a52 (adj 15): empty #7
,W/libprocessgroup(  879): failed to open /acct/uid_10052/pid_7131/cgroup.procs: No such file or directory
,I/CheckinService( 6970): Checkin interval check for package: unspecified last checkin: 1453023970618 min interval config: 0 actual interval: 93830
,I/ActivityManager(  879): Start proc com.google.android.apps.photos for broadcast com.google.android.apps.photos/.jobqueue.JobServiceBroadcastReceiver: pid=7301 uid=10088 gids={50088, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  879): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=7321 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/ActivityManager(  879): Killing 7181:android.process.acore/u0a7 (adj 15): empty #7
,W/libprocessgroup(  879): failed to open /acct/uid_10007/pid_7181/cgroup.procs: No such file or directory
,W/ResourcesManager( 7321): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/CheckinRequestBuilder( 6970): Checkin reason type: 8 attempt count: 1
,I/art     (  879): Explicit concurrent mark sweep GC freed 8137(393KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 20MB/30MB, paused 2.777ms total 120.466ms
,E/ActivityThread( 6970): Failed to find provider info for com.google.android.wearable.settings
,I/art     ( 6260): Explicit concurrent mark sweep GC freed 1477(52KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 7MB/9MB, paused 353us total 23.814ms
,I/Babel_SMS( 7321): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 7321): MmsConfig.loadMmsSettings
I/Babel_SMS( 7321): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
I/Babel_SMS( 7321): MmsConfig.loadFromDatabase
,E/Babel_SMS( 7321): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 7321): MmsConfig.loadFromResources
,E/Babel_SMS( 7321): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel_SMS( 7321): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/Settings( 7321): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 7321): startup - clean
,I/CheckinRequestBuilder( 6970): Classify the device as Phone.
,I/Babel   ( 7321): deleted: false for 0
,I/CheckinTask( 6970): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 6970): Checking schedule, now: 1453024065399 next: 1453625202385
I/CheckinService( 6970): active receiver: disabled
,I/CheckinService( 6970): Checking schedule, now: 1453024065433 next: 1453625202385
I/CheckinService( 6970): active receiver: disabled
,D/CheckinService( 6970): Recording last checkin time for package unspecified as 1453024065436
,I/ActivityManager(  879): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7361 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  879): Killing 7206:com.google.android.music:main/u0a80 (adj 13): empty #7
,W/VideoCapabilities( 7321): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 7321): Unsupported mime audio/amr-wb-plus
,W/VideoCapabilities( 7321): Unsupported mime video/mpeg2
,I/VideoCapabilities( 7321): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 7321): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7321): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7321): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7321): Unrecognized profile 2130706433 for video/avc
,I/ActivityManager(  879): Killing 7155:com.google.android.apps.plus/u0a90 (adj 15): empty #8
,W/libprocessgroup(  879): failed to open /acct/uid_10080/pid_7206/cgroup.procs: No such file or directory
,W/libprocessgroup(  879): failed to open /acct/uid_10090/pid_7155/cgroup.procs: No such file or directory
,I/vclib   ( 7321): onServiceConnected
,W/Babel   ( 7321): Attempted to change video mute state without an active call.
,I/Babel   ( 7321): connection state changed from UNKNOWN to CONNECTED
,I/ActivityManager(  879): Killing 7253:com.android.mms/u0a23 (adj 13): empty #7
,W/libprocessgroup(  879): failed to open /acct/uid_10023/pid_7253/cgroup.procs: No such file or directory
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7361): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7361): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7361): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,I/GAv4    ( 7361): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 7361):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 7361):   adb logcat -s GAv4
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
,W/Vold    (  277): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7361): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,W/GAv4    ( 7361): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 7361): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 7361): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/WebViewFactory( 7361): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 7361): Time to load native libraries: 1 ms (timestamps 8794-8795)
I/LibraryLoader( 7361): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 7361): Binding Chromium to main looper Looper (main, tid 1) {367a8ede}
,I/LibraryLoader( 7361): Expected native library version number "",actual native library version number ""
,I/chromium( 7361): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 7361): Initializing chromium process, singleProcess=true
W/art     ( 7361): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 7361): ApplicationContext is null in ApplicationStatus
,W/chromium( 7361): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 7361): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 7361): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 7361): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 7361): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7361): Build Date: 10/28/14 Tue
I/Adreno-EGL( 7361): Local Branch: 
I/Adreno-EGL( 7361): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 7361): Local Patches: NONE
I/Adreno-EGL( 7361): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/NSApplication( 7361): Starting up...
,W/AudioManagerAndroid( 7361): Requires BLUETOOTH permission
,I/ActivityManager(  879): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=7427 uid=10052 gids={50052, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  879): Killing 7283:com.google.android.setupwizard/u0a35 (adj 15): empty #7
,W/libprocessgroup(  879): failed to open /acct/uid_10035/pid_7283/cgroup.procs: No such file or directory
,I/ActivityManager(  879): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7446 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  879): Killing 7301:com.google.android.apps.photos/u0a88 (adj 13): empty #7
,W/libprocessgroup(  879): failed to open /acct/uid_10088/pid_7301/cgroup.procs: No such file or directory
,W/ResourcesManager( 7446): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/ActivityManager(  879): Start proc android.process.acore for content provider com.android.providers.contacts/.ContactsProvider2: pid=7466 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,I/ActivityManager(  879): Killing 7361:com.google.android.apps.magazines/u0a81 (adj 13): empty #7
,I/ContactLocale( 7466): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,I/ActivityManager(  879): Killing 7321:com.google.android.talk/u0a70 (adj 15): empty #8
,W/libprocessgroup(  879): failed to open /acct/uid_10081/pid_7361/cgroup.procs: No such file or directory
,D/EmailService.MarketingOptInSetter( 2569): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,W/libprocessgroup(  879): failed to open /acct/uid_10070/pid_7321/cgroup.procs: No such file or directory
,D/GetNotificationsWS( 2569): bindWebServices(): registering our AIDL callback...
,I/SundryService( 2569): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/WaitableIntentService( 2569): ServiceHandler.handleMessage: mWaitCount=0
,D/GetNotificationsWS( 2569): onServiceConnected()
D/GetNotificationsWS( 2569): onServiceConnected(): Registered for remote service callbacks...
D/GetNotificationsWS( 2569): unbindWebServices(): un-registering our AIDL callback...
,I/PushService( 2569): started with background data enabled, making sure notification mechanism is enabled
,D/WearableService( 1718): callingUid 10016, callindPid: 1718
,E/MDM     ( 1718): [170] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/LocationInitializer( 6970): Restart initialization of location
,D/AuthorizationBluetoothService( 1718): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,V/GLSActivity( 1718): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  879): Start proc com.google.android.apps.photos for broadcast com.google.android.apps.photos/.jobqueue.JobServiceBroadcastReceiverInternal: pid=7504 uid=10088 gids={50088, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,W/GCoreFlp( 1718): No location to return for getLastLocation()
,W/FusedLocationProvider( 1718): location=null
,I/art     (  314): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 266us total 24.824ms
,I/art     (  314): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 275us total 24.414ms
,I/art     (  314): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 258us total 21.639ms
,W/IcingInternalCorpora( 6970): getNumBytesRead when not calculated.
,E/MDM     ( 1718): [178] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/LocationInitializer( 6970): Restart initialization of location
,D/AuthorizationBluetoothService( 1718): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,V/GLSActivity( 1718): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  879): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=7532 uid=10080 gids={50080, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/GCoreFlp( 1718): No location to return for getLastLocation()
,W/FusedLocationProvider( 1718): location=null
,I/MusicStore( 7532): Database version: 120
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7532): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
,W/Vold    (  277): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7532): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
,W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7532): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,W/ResourcesManager( 7532): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 7532): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 7532): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 7532): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 7532): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@2ca286c1: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7532): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 7532): GMSCore installation verified
,I/ConfigStore( 7532): Config Database version: 1
,I/art     (  879): Explicit concurrent mark sweep GC freed 12233(615KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 20MB/30MB, paused 1.891ms total 113.330ms
,I/MediaRouter( 7532): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 7532): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/NetworkMonitor( 7532): type=WIFI subType= reason=null isConnected=true
,I/NetworkMonitor( 7532): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  879): Start proc com.android.mms for broadcast com.android.mms/.transaction.MmsSystemEventReceiver: pid=7569 uid=10023 gids={50023, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/GHttpClientFactory( 7532): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 7532): Using platform SSLCertificateSocketFactory
,V/Mms     ( 7569): mnc/mcc: 
,V/Mms     ( 7569): tag: int value: recipientLimit - 20
,V/Mms     ( 7569): tag: int value: smsToMmsTextThreshold - 6
,V/Mms     ( 7569): tag: int value: emergencySmsTimeout - 30
V/Mms     ( 7569): tag: int value: maxSubjectLength - 80
V/Mms     ( 7569): tag: bool value: smsForceShowEncodingMenu - true
V/Mms     ( 7569): tag: bool value: enableGroupMms - false
V/Mms     ( 7569):  mUserAgent = MOT-XT1072/Mms-5.0,  mUaProfUrl = http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/ResourcesManager( 7569): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/ActivityManager(  879): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=7603 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  879): Killing 7427:com.android.chrome/u0a52 (adj 15): empty #7
,W/libprocessgroup(  879): failed to open /acct/uid_10052/pid_7427/cgroup.procs: No such file or directory
,D/PhoneMonitor( 7603): Register our PhoneStateListener
,D/MobileConnectivityChangeReceiver( 7603): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 7603): onReceive CONNECTIVITY_CHANGE networkType=1
,I/ActivityManager(  879): Killing 7446:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,W/libprocessgroup(  879): failed to open /acct/uid_10090/pid_7446/cgroup.procs: No such file or directory
,I/CheckinService( 6970): Checkin interval check for package: unspecified last checkin: 1453024065436 min interval config: 0 actual interval: 3056
,I/CheckinService( 6970): Checkin interval check for package: unspecified last checkin: 1453024065436 min interval config: 0 actual interval: 3059
,I/CheckinService( 6970): Checking schedule, now: 1453024068500 next: 1453024095385
I/CheckinService( 6970): active receiver: disabled
,I/ActivityManager(  879): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=7628 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
I/CheckinService( 6970): Checking schedule, now: 1453024068563 next: 1453024095385
I/CheckinService( 6970): active receiver: disabled
,W/ResourcesManager( 7628): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/Babel_SMS( 7628): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 7628): MmsConfig.loadMmsSettings
I/Babel_SMS( 7628): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
I/Babel_SMS( 7628): MmsConfig.loadFromDatabase
,E/Babel_SMS( 7628): canonicalizeMccMnc: invalid mccmnc 
,I/Babel_SMS( 7628): MmsConfig.loadFromResources
,E/Babel_SMS( 7628): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel_SMS( 7628): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/Settings( 7628): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 7628): startup - clean
,I/Babel   ( 7628): deleted: false for 0
,I/ActivityManager(  879): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7658 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/VideoCapabilities( 7628): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 7628): Unsupported mime audio/amr-wb-plus
,W/VideoCapabilities( 7628): Unsupported mime video/mpeg2
,I/ActivityManager(  879): Killing 7466:android.process.acore/u0a7 (adj 15): empty #7
,I/VideoCapabilities( 7628): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 7628): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7628): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7628): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7628): Unrecognized profile 2130706433 for video/avc
,W/libprocessgroup(  879): failed to open /acct/uid_10007/pid_7466/cgroup.procs: No such file or directory
,I/vclib   ( 7628): onServiceConnected
W/Babel   ( 7628): Attempted to change video mute state without an active call.
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7658): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7658): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
,W/Vold    (  277): Returning OperationFailed - no handler for errno 0
I/Babel   ( 7628): connection state changed from UNKNOWN to CONNECTED
W/ContextImpl( 7658): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,I/GAv4    ( 7658): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 7658):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 7658):   adb logcat -s GAv4
,I/ActivityManager(  879): Killing 7532:com.google.android.music:main/u0a80 (adj 15): empty #7
E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
,W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7658): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,W/libprocessgroup(  879): failed to open /acct/uid_10080/pid_7532/cgroup.procs: No such file or directory
,W/GAv4    ( 7658): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 7658): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 7658): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/WebViewFactory( 7658): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 7658): Time to load native libraries: 1 ms (timestamps 2208-2209)
,I/LibraryLoader( 7658): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 7658): Binding Chromium to main looper Looper (main, tid 1) {367a8ede}
,I/LibraryLoader( 7658): Expected native library version number "",actual native library version number ""
,I/chromium( 7658): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 7658): Initializing chromium process, singleProcess=true
,W/art     ( 7658): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 7658): ApplicationContext is null in ApplicationStatus
,W/chromium( 7658): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 7658): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 7658): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 7658): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 7658): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7658): Build Date: 10/28/14 Tue
I/Adreno-EGL( 7658): Local Branch: 
I/Adreno-EGL( 7658): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 7658): Local Patches: NONE
I/Adreno-EGL( 7658): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/NSApplication( 7658): Starting up...
,W/AudioManagerAndroid( 7658): Requires BLUETOOTH permission
,I/ActivityManager(  879): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=7732 uid=10052 gids={50052, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  879): Killing 7569:com.android.mms/u0a23 (adj 15): empty #7
,W/libprocessgroup(  879): failed to open /acct/uid_10023/pid_7569/cgroup.procs: No such file or directory
,I/ActivityManager(  879): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7751 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  879): Killing 7603:com.google.android.setupwizard/u0a35 (adj 15): empty #7
,W/libprocessgroup(  879): failed to open /acct/uid_10035/pid_7603/cgroup.procs: No such file or directory
,W/ResourcesManager( 7751): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/ActivityManager(  879): Start proc android.process.acore for content provider com.android.providers.contacts/.ContactsProvider2: pid=7771 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,I/ActivityManager(  879): Killing 7628:com.google.android.talk/u0a70 (adj 15): empty #7
,I/ContactLocale( 7771): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,I/ActivityManager(  879): Killing 7504:com.google.android.apps.photos/u0a88 (adj 15): empty #8
,D/EmailService.MarketingOptInSetter( 2569): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,W/libprocessgroup(  879): failed to open /acct/uid_10070/pid_7628/cgroup.procs: No such file or directory
,W/libprocessgroup(  879): failed to open /acct/uid_10088/pid_7504/cgroup.procs: No such file or directory
,D/GetNotificationsWS( 2569): bindWebServices(): registering our AIDL callback...
,I/SundryService( 2569): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/WaitableIntentService( 2569): ServiceHandler.handleMessage: mWaitCount=0
,D/GetNotificationsWS( 2569): onServiceConnected()
D/GetNotificationsWS( 2569): onServiceConnected(): Registered for remote service callbacks...
,D/GetNotificationsWS( 2569): unbindWebServices(): un-registering our AIDL callback...
,D/OtaApp  ( 2569): [debug] > Receive intent: com.motorola.blur.service.blur.Actions.UPGRADE_UPDATE_NOTIFICATION
,I/PushService( 2569): started with background data enabled, making sure notification mechanism is enabled
,D/OtaApp  ( 2569): [debug] > UpdateReceiver: Received true from doSanityCheck.
D/OtaApp  ( 2569): [debug] > In cancelAnyPendingIntentSetPreviously
I/ActivityManager(  879): START u0 {act=com.motorola.blur.service.blur.Actions.UPGRADE_UPDATE_NOTIFICATION flg=0x30000000 cmp=com.motorola.ccc.ota/.ui.DownloadActivity (has extras)} from uid 10000 on display 0
,W/ContextImpl( 1476): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,W/ContextImpl( 1476): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,I/ActivityManager(  879): Start proc com.google.android.apps.photos for broadcast com.google.android.apps.photos/.jobqueue.JobServiceBroadcastReceiverInternal: pid=7800 uid=10088 gids={50088, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,D/OtaApp  ( 2569): [debug] > DownloadActivity, FormattedText
,I/OtaApp  ( 2569): [info] > DownloadActivity, handling (Blur_Version.22.46.12.thea_reteu.reteuall.en.EU) from ( upgrade)
,D/Checkin ( 2569): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 2569): [debug] > cancelling the previous pending intent set for download later
,I/OtaApp  ( 2569): [info] > next automatic download prompt (serverAnnoy)  is scheduled in : 60 mins.
,D/Checkin ( 2569): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 2569): [debug] > DownloadActivity, FormattedText
I/OtaApp  ( 2569): [info] > DownloadActivity, handling (Blur_Version.22.46.12.thea_reteu.reteuall.en.EU) from ( upgrade)
D/Checkin ( 2569): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 2569): [debug] > cancelling the previous pending intent set for download later
,I/OtaApp  ( 2569): [info] > next automatic download prompt (serverAnnoy)  is scheduled in : 60 mins.
,D/Checkin ( 2569): publish the event [tag = MOT_OTA event name = LOG]
,I/InputReader(  879): Reconfiguring input devices.  changes=0x00000010
,I/Keyboard.Facilitator( 1415): onFinishInput()
W/IInputConnectionWrapper( 6731): showStatusIcon on inactive InputConnection
,I/LaunchCheckinHandler(  879): Displayed com.motorola.ccc.ota/.ui.DownloadActivity,wp,wa,259
,D/BackupManagerService(  879): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,I/BackupManagerService(  879): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,I/BackupManagerService(  879): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/BackupManagerService(  879): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/BackupManagerService(  879): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@3fbd7c87
,I/GCoreNlp( 1718): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,I/Launcher( 1567): Deferring update until onResume
,I/art     (  879): Explicit concurrent mark sweep GC freed 17680(885KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 20MB/30MB, paused 2.017ms total 114.739ms
,I/ActivityManager(  879): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.util.GservicesChangedReceiver: pid=7832 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  879): Killing 7658:com.google.android.apps.magazines/u0a81 (adj 15): empty #7
,W/libprocessgroup(  879): failed to open /acct/uid_10081/pid_7658/cgroup.procs: No such file or directory
,D/PhoneMonitor( 7832): Register our PhoneStateListener
,V/SetupWizard( 7832): Connected to Gservices successfully
,I/ActivityManager(  879): Killing 7062:com.google.android.gms.unstable/u0a16 (adj 15): empty #7
,W/libprocessgroup(  879): failed to open /acct/uid_10016/pid_7062/cgroup.procs: No such file or directory
,D/GCM     ( 1718): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,D/GCM     ( 1718): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/ActivityManager(  879): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.GmsPackageWatcher: pid=7858 uid=10039 gids={50039, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
,I/art     (  314): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 240us total 21.720ms
,I/art     (  314): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 250us total 19.537ms
,I/art     (  314): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 253us total 24.162ms
,I/ActivityManager(  879): Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=7894 uid=10019 gids={50019, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  879): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver: pid=7912 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/ActivityManager(  879): Killing 7732:com.android.chrome/u0a52 (adj 15): empty #7
,I/ActivityManager(  879): Killing 7751:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,W/libprocessgroup(  879): failed to open /acct/uid_10052/pid_7732/cgroup.procs: No such file or directory
,W/libprocessgroup(  879): failed to open /acct/uid_10090/pid_7751/cgroup.procs: No such file or directory
,W/ResourcesManager( 7912): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/Babel_SMS( 7912): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 7912): MmsConfig.loadMmsSettings
,I/Babel_SMS( 7912): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,I/Babel_SMS( 7912): MmsConfig.loadFromDatabase
,E/Babel_SMS( 7912): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 7912): MmsConfig.loadFromResources
E/Babel_SMS( 7912): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 7912): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/Settings( 7912): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 7912): startup - clean
,I/Babel   ( 7912): deleted: false for 0
,I/ActivityManager(  879): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=7942 uid=10027 gids={50027, 9997, 1023, 3003, 1028, 1015} abi=armeabi-v7a
,W/VideoCapabilities( 7912): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 7912): Unsupported mime audio/amr-wb-plus
,W/VideoCapabilities( 7912): Unsupported mime video/mpeg2
,W/asset   ( 7942): Asset path /system/framework/com.motorola.gallery is neither a directory nor file (type=1).
,W/ResourcesManager( 7942): Asset path '/system/framework/com.motorola.gallery' does not exist or contains no resources.
W/ResourcesManager( 7942): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 7942): Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
,I/VideoCapabilities( 7912): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 7912): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 7912): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 7912): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7912): Unrecognized profile 2130706433 for video/avc
,D/PackageBroadcastService( 6970): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,W/Launcher( 1567): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@2a0ff4f7 new=com.google.android.velvet.VelvetApplication@2a0ff4f7
,I/PackageBroadcastService( 6970): Null package name or gms related package.  Ignoreing.
,I/UpdateIcingCorporaServi( 7858): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,I/ActivityManager(  879): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=7968 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/vclib   ( 7912): onServiceConnected
,W/Babel   ( 7912): Attempted to change video mute state without an active call.
W/ResourcesManager( 7968): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 7912): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7912): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/Icing   ( 6970): Storage manager: low false usage 1.73MB avail 3.11GB capacity 4.85GB
,I/UpdateIcingCorporaServi( 7858): UpdateCorporaTask done [took 191 ms] updated apps [took 191 ms] 
,I/ActivityManager(  879): Killing 7800:com.google.android.apps.photos/u0a88 (adj 15): empty #7
,V/JNIHelp ( 7912): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/System  ( 7912): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 7912): Installed default security provider GmsCore_OpenSSL
,W/libprocessgroup(  879): failed to open /acct/uid_10088/pid_7800/cgroup.procs: No such file or directory
,I/ActivityManager(  879): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=8011 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  879): Killing 7832:com.google.android.setupwizard/u0a35 (adj 15): empty #7
,W/libprocessgroup(  879): failed to open /acct/uid_10035/pid_7832/cgroup.procs: No such file or directory
,D/Finsky  ( 8011): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,I/Icing   ( 6970): updateResources: need to parse f{com.google.android.gms}
,D/Finsky  ( 8011): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 8011): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 8011): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/Icing   ( 6970): Internal init done: storage state 0
,I/Icing   ( 6970): Post-init done
,I/Icing   ( 6970): updateResources: need to parse f{com.google.android.gms}
,D/Finsky  ( 8011): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 8011): [1] Libraries$2.run: Finished loading 1 libraries.
,D/Ads     ( 8011): Skipping gmscore version check
,D/Finsky  ( 8011): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/Finsky  ( 8011): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/ActivityManager(  879): Killing 7894:com.google.android.partnersetup/u0a19 (adj 15): empty #7
,W/libprocessgroup(  879): failed to open /acct/uid_10019/pid_7894/cgroup.procs: No such file or directory
,D/TaskPersister(  879): removeObsoleteFile: deleting file=5_task.xml
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:33000 mC
,I/Icing   ( 6970): Indexing 5905AFFF7E2D60BB1F87C8D56D40BA6B258244BF from com.google.android.gms
,D/Icing   ( 6970): Loaded CLD2 Version V2.0 - 20141016
,I/Icing   ( 6970): Indexing done 5905AFFF7E2D60BB1F87C8D56D40BA6B258244BF
,I/ActivityManager(  879): Killing 7942:com.motorola.MotGallery2/u0a27 (adj 15): empty #7
,W/libprocessgroup(  879): failed to open /acct/uid_10027/pid_7942/cgroup.procs: No such file or directory
,I/ActivityManager(  879): Killing 7858:com.google.android.googlequicksearchbox:search/u0a39 (adj 15): empty #7
,W/libprocessgroup(  879): failed to open /acct/uid_10039/pid_7858/cgroup.procs: No such file or directory
,D/BatteryService(  879): uevent={POWER_SUPPLY_TEMP=294, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311064, SEQNUM=4504, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-4306, POWER_SUPPLY_CHARGE_COUNTER=-375, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2457): Disconnected process message: 10, size: 0
,I/CheckinService( 6970): Done disabling old GoogleServicesFramework version
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:32000 mC
,I/MDMCTBK (  292): NetlinkHandler, power_supply subsys
I/MDMCTBK (  292): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  292): checkDefaultInst, current pid is = 292
I/MDMCTBK (  292): checkDefaultInst, pid match
I/MDMCTBK (  292): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  292): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  292): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  292): NetlinkHandler, power_supply subsys
I/MDMCTBK (  292): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  292): checkDefaultInst, current pid is = 292
I/MDMCTBK (  292): checkDefaultInst, pid match
I/MDMCTBK (  292): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  292): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  292): MdmCutbackHndler,Could not open ''
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:31000 mC
,I/MDMCTBK (  292): NetlinkHandler, power_supply subsys
,I/MDMCTBK (  292): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  292): checkDefaultInst, current pid is = 292
I/MDMCTBK (  292): checkDefaultInst, pid match
I/MDMCTBK (  292): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  292): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  292): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  292): NetlinkHandler, power_supply subsys
I/MDMCTBK (  292): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  292): checkDefaultInst, current pid is = 292
I/MDMCTBK (  292): checkDefaultInst, pid match
I/MDMCTBK (  292): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  292): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  292): MdmCutbackHndler,Could not open ''
,D/BatteryService(  879): uevent={POWER_SUPPLY_TEMP=281, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4310291, SEQNUM=4506, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-4306, POWER_SUPPLY_CHARGE_COUNTER=-401, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2457): Disconnected process message: 10, size: 0
,I/ClearcutLoggerApiImpl( 1718): disconnect managed GoogleApiClient
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:31000 mC
,V/AlarmManager(  879): send {718481e, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  879): send {3d3533d1, *walarm*:com.android.server.task.controllers.BatteryController.ACTION_CHARGING_STABLE}
V/AlarmManager(  879): send {2d8cd7d1, *walarm*:com.google.android.gms/.checkin.CheckinService$Receiver}
,V/AlarmManager(  879): done {3d3533d1, *walarm*:com.android.server.task.controllers.BatteryController.ACTION_CHARGING_STABLE} [18ms]
,V/AlarmManager(  879): done {2d8cd7d1, *walarm*:com.google.android.gms/.checkin.CheckinService$Receiver} [30ms]
,I/CheckinService( 6970): Checkin interval check for package: unspecified last checkin: 1453024065436 min interval config: 0 actual interval: 38951
,V/AlarmManager(  879): done {718481e, *alarm*:android.intent.action.TIME_TICK} [49ms]
,I/CheckinService( 6970): Checking schedule, now: 1453024104411 next: 1453024095385
I/CheckinService( 6970): active receiver: enabled
,I/CheckinService( 6970): Preparing to send checkin request
I/EventLogService( 6970): Accumulating logs since 1453024060855
,I/CheckinRequestBuilder( 6970): Checkin reason type: 12 attempt count: 1
,E/ActivityThread( 6970): Failed to find provider info for com.google.android.wearable.settings
,I/art     (  879): Explicit concurrent mark sweep GC freed 15348(802KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 20MB/30MB, paused 1.471ms total 112.148ms
,V/GLSActivity( 1718): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1718): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  879): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=8092 uid=10016 gids={50016, 9997, 3003, 1028, 1015, 3002, 3001, 1005, 1007, 3007, 2001, 3006} abi=armeabi-v7a
,W/ResourcesManager( 8092): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 8092): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/MultiDex( 8092): VM with version 2.1.0 has multidex support
I/MultiDex( 8092): install
I/MultiDex( 8092): VM has multidex support, MultiDex support library is disabled.
,V/JNIHelp ( 8092): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 8092): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 8092): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@1fec3e2e: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 8092): Installed default security provider GmsCore_OpenSSL
,D/WearableService( 1718): callingUid 10016, callindPid: 1718
,E/MDM     ( 1718): [150] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/AuthorizationBluetoothService( 1718): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,D/LocationInitializer( 6970): Restart initialization of location
,V/GLSActivity( 1718): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 8092): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 8092): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,I/art     ( 1718): Explicit concurrent mark sweep GC freed 104136(5MB) AllocSpace objects, 28(448KB) LOS objects, 40% free, 15MB/25MB, paused 1.150ms total 121.399ms
,W/GCoreFlp( 1718): No location to return for getLastLocation()
,W/FusedLocationProvider( 1718): location=null
,D/NativeLibraryUtils( 8092): Install completed successfully. count=14 extracted=0
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
E/QSEECOMAPI: (  294): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  294): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  294): App is not loaded in QSEE
,D/QSEECOMAPI: (  294): Loaded image: APP id = 3
,D/DrmWidevineDash(  294): Service_Initialize: ends! returns 0
D/DrmWidevineDash(  294): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb5039000
,E/DrmWidevineDash(  294): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb5039000
,D/DrmWidevineDash(  294): OEMCrypto_Initialize: ends! returns 0
D/DrmWidevineDash(  294): OEMCrypto_APIVersion: starts!
,D/DrmWidevineDash(  294): hlos api version =  9
D/DrmWidevineDash(  294): tz api version =  8
D/DrmWidevineDash(  294): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  294): OEMCrypto_IsKeyboxValid: starts!
,D/DrmWidevineDash(  294): OEMCrypto_IsKeyboxValid: ends! returns 0
D/WVCdm   (  294): OEMCrypto_Initialize Level 1 success. I will use level 1.
,D/DrmWidevineDash(  294): OEMCrypto_OpenSession: starts! SID=0xbeef44e0
D/DrmWidevineDash(  294): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  294): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  294): OEMCrypto_GetRandom: starts! randomData=0xb83e6aa8, dataLength=8
D/DrmWidevineDash(  294): OEMCrypto_GetRandom: ends! returns 0
,D/DrmWidevineDash(  294): OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb8495110, wrapped_rsa_key_length=1280
,D/DrmWidevineDash(  294): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
,I/WVCdm   (  294): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  294): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  294): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  294): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  294): OEMCrypto_GetDeviceID: starts! deviceID=0xb84b7a50, idLength=0xb5614730
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
D/WVCdm   (  294): PrepareKeyRequest: nonce=3359252547
D/DrmWidevineDash(  294): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb84a9c90
D/DrmWidevineDash(  294): message_length=1591, signature=0xb84aa2d0, signature_length=3043051284
,D/DrmWidevineDash(  294): OEMCrypto_GenerateRSASignature returns 0
I/WVCdm   (  294): CdmEngine::CloseSession
,D/DrmWidevineDash(  294): OEMCrypto_CloseSession: starts! SID=1
D/DrmWidevineDash(  294): OEMCrypto_CloseSession: ends! returns 0
I/WVCdm   (  294): L3 Terminate.
D/DrmWidevineDash(  294): OEMCrypto_Terminate: starts!
D/DrmWidevineDash(  294): Service_Uninitialize: starts!
D/QSEECOMAPI: (  294): QSEECom_dealloc_memory 
,D/QSEECOMAPI: (  294): QSEECom_shutdown_app, app_id = 3
D/DrmWidevineDash(  294): Service_Uninitialize: ends! returns 0x0
D/DrmWidevineDash(  294): OEMCrypto_Terminate: ends! returns 0
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
D/QSEECOMAPI: (  294): App is not loaded in QSEE
,D/QSEECOMAPI: (  294): Loaded image: APP id = 3
,D/DrmWidevineDash(  294): Service_Initialize: ends! returns 0
D/DrmWidevineDash(  294): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb5039000
,E/DrmWidevineDash(  294): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb5039000
,D/DrmWidevineDash(  294): OEMCrypto_Initialize: ends! returns 0
D/DrmWidevineDash(  294): OEMCrypto_APIVersion: starts!
,D/DrmWidevineDash(  294): hlos api version =  9
D/DrmWidevineDash(  294): tz api version =  8
D/DrmWidevineDash(  294): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  294): OEMCrypto_IsKeyboxValid: starts!
,D/DrmWidevineDash(  294): OEMCrypto_IsKeyboxValid: ends! returns 0
D/WVCdm   (  294): OEMCrypto_Initialize Level 1 success. I will use level 1.
D/DrmWidevineDash(  294): OEMCrypto_OpenSession: starts! SID=0xbeef44e0
D/DrmWidevineDash(  294): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  294): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  294): OEMCrypto_GetRandom: starts! randomData=0xb83e6aa8, dataLength=8
D/DrmWidevineDash(  294): OEMCrypto_GetRandom: ends! returns 0
,D/DrmWidevineDash(  294): OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb8495110, wrapped_rsa_key_length=1280
,D/DrmWidevineDash(  294): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
I/WVCdm   (  294): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  294): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  294): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  294): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  294): OEMCrypto_GetDeviceID: starts! deviceID=0xb84b7a70, idLength=0xb0af7730
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
D/WVCdm   (  294): PrepareKeyRequest: nonce=3297091165
D/DrmWidevineDash(  294): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb84a9c90
D/DrmWidevineDash(  294): message_length=1626, signature=0xb84aa2f0, signature_length=2964289300
,D/DrmWidevineDash(  294): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  294): CdmEngine::CloseSession
D/DrmWidevineDash(  294): OEMCrypto_CloseSession: starts! SID=1
D/DrmWidevineDash(  294): OEMCrypto_CloseSession: ends! returns 0
I/WVCdm   (  294): L3 Terminate.
D/DrmWidevineDash(  294): OEMCrypto_Terminate: starts!
,D/DrmWidevineDash(  294): Service_Uninitialize: starts!
D/QSEECOMAPI: (  294): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  294): QSEECom_shutdown_app, app_id = 3
D/DrmWidevineDash(  294): Service_Uninitialize: ends! returns 0x0
D/DrmWidevineDash(  294): OEMCrypto_Terminate: ends! returns 0
,I/dex2oat ( 8142): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=34 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,I/dex2oat ( 8142): dex2oat took 73.419ms (threads: 4)
,I/Adreno-EGL( 8092): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 8092): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 8092): Build Date: 10/28/14 Tue
I/Adreno-EGL( 8092): Local Branch: 
I/Adreno-EGL( 8092): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 8092): Local Patches: NONE
I/Adreno-EGL( 8092): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/Adreno-EGL( 8092): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 8092): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 8092): Build Date: 10/28/14 Tue
I/Adreno-EGL( 8092): Local Branch: 
I/Adreno-EGL( 8092): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 8092): Local Patches: NONE
I/Adreno-EGL( 8092): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/Adreno-EGL( 8092): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 8092): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 8092): Build Date: 10/28/14 Tue
I/Adreno-EGL( 8092): Local Branch: 
I/Adreno-EGL( 8092): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 8092): Local Patches: NONE
I/Adreno-EGL( 8092): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/Adreno-EGL( 8092): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 8092): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 8092): Build Date: 10/28/14 Tue
I/Adreno-EGL( 8092): Local Branch: 
I/Adreno-EGL( 8092): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 8092): Local Patches: NONE
I/Adreno-EGL( 8092): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/CheckinRequestBuilder( 6970): Classify the device as Phone.
,I/CheckinTask( 6970): Sending checkin request (9502 bytes)
,I/CheckinRequestBuilder( 6970): Checkin reason type: 12 attempt count: 1
,E/ActivityThread( 6970): Failed to find provider info for com.google.android.wearable.settings
,I/CheckinRequestBuilder( 6970): Classify the device as Phone.
,I/CheckinTask( 6970): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 6970): Checking schedule, now: 1453024107824 next: 1453625244818
I/CheckinService( 6970): active receiver: disabled
,D/CheckinService( 6970): Recording last checkin time for package unspecified as 1453024107833
,I/ActivityManager(  879): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.util.GservicesChangedReceiver: pid=8167 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,D/PhoneMonitor( 8167): Register our PhoneStateListener
,V/SetupWizard( 8167): Connected to Gservices successfully
,D/GCM     ( 1718): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/ActivityManager(  879): Killing 7968:com.google.android.apps.plus/u0a90 (adj 13): empty #7
,I/ActivityManager(  879): Killing 7771:android.process.acore/u0a7 (adj 15): empty #8
,W/libprocessgroup(  879): failed to open /acct/uid_10090/pid_7968/cgroup.procs: No such file or directory
,W/libprocessgroup(  879): failed to open /acct/uid_10007/pid_7771/cgroup.procs: No such file or directory
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:31000 mC
,I/InputReader(  879): Reconfiguring input devices.  changes=0x00000010
,I/ActivityManager(  879): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.GmsPackageWatcher: pid=8192 uid=10039 gids={50039, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
,D/BackupManagerService(  879): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/BackupManagerService(  879): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,I/BackupManagerService(  879): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/BackupManagerService(  879): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/BackupManagerService(  879): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@2d3e2feb
,I/GCoreNlp( 1718): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,I/Launcher( 1567): Deferring update until onResume
,I/ActivityManager(  879): Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=8229 uid=10019 gids={50019, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  879): Start proc android.process.acore for broadcast com.android.providers.contacts/.PackageIntentReceiver: pid=8248 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,I/ActivityManager(  879): Killing 8011:com.android.vending/u0a32 (adj 15): empty #7
,W/libprocessgroup(  879): failed to open /acct/uid_10032/pid_8011/cgroup.procs: No such file or directory
,W/ResourcesManager( 7912): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7912): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/ContactLocale( 8248): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,I/ActivityManager(  879): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=8274 uid=10027 gids={50027, 9997, 1023, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  879): Killing 8167:com.google.android.setupwizard/u0a35 (adj 15): empty #7
,I/art     (  314): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 284us total 22.973ms
,I/art     (  314): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 280us total 19.270ms
,I/art     (  314): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 255us total 19.806ms
,W/libprocessgroup(  879): failed to open /acct/uid_10035/pid_8167/cgroup.procs: No such file or directory
,W/asset   ( 8274): Asset path /system/framework/com.motorola.gallery is neither a directory nor file (type=1).
W/ResourcesManager( 8274): Asset path '/system/framework/com.motorola.gallery' does not exist or contains no resources.
W/ResourcesManager( 8274): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 8274): Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
,D/PackageBroadcastService( 6970): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 6970): Null package name or gms related package.  Ignoreing.
,W/Launcher( 1567): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@2a0ff4f7 new=com.google.android.velvet.VelvetApplication@2a0ff4f7
,I/UpdateIcingCorporaServi( 8192): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,I/Icing   ( 6970): updateResources: need to parse f{com.google.android.gms}
,I/ActivityManager(  879): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=8300 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,W/ResourcesManager( 8300): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/UpdateIcingCorporaServi( 8192): UpdateCorporaTask done [took 150 ms] updated apps [took 150 ms] 
,I/art     (  879): Explicit concurrent mark sweep GC freed 17554(896KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 20MB/30MB, paused 1.447ms total 114.050ms
,I/ActivityManager(  879): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=8332 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  879): Killing 8092:com.google.android.gms.unstable/u0a16 (adj 15): empty #7
,W/libprocessgroup(  879): failed to open /acct/uid_10016/pid_8092/cgroup.procs: No such file or directory
,D/Finsky  ( 8332): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/Finsky  ( 8332): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 8332): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 8332): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/Finsky  ( 8332): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 8332): [1] Libraries$2.run: Finished loading 1 libraries.
,D/Ads     ( 8332): Skipping gmscore version check
,D/Finsky  ( 8332): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/Finsky  ( 8332): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/ActivityManager(  879): Killing 8229:com.google.android.partnersetup/u0a19 (adj 15): empty #7
,W/libprocessgroup(  879): failed to open /acct/uid_10019/pid_8229/cgroup.procs: No such file or directory
,I/Icing   ( 6970): Indexing 5905AFFF7E2D60BB1F87C8D56D40BA6B258244BF from com.google.android.gms
,I/Icing   ( 6970): Indexing done 5905AFFF7E2D60BB1F87C8D56D40BA6B258244BF
,I/ActivityManager(  879): Killing 8274:com.motorola.MotGallery2/u0a27 (adj 15): empty #7
,W/libprocessgroup(  879): failed to open /acct/uid_10027/pid_8274/cgroup.procs: No such file or directory
,I/ActivityManager(  879): Killing 7912:com.google.android.talk/u0a70 (adj 15): empty #7
,W/libprocessgroup(  879): failed to open /acct/uid_10070/pid_7912/cgroup.procs: No such file or directory
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:31000 mC
,I/Keyboard.Facilitator.LanguageModelFlusher( 1415): run()
,I/Keyboard.Facilitator( 1415): flushDynamicLanguageModels()
,I/ConfigService( 1718): onCreate
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:30000 mC
,I/ConfigService( 1718): onDestroy
,D/BatteryService(  879): uevent={POWER_SUPPLY_TEMP=275, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311074, SEQNUM=4528, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-11318, POWER_SUPPLY_CHARGE_COUNTER=-461, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2457): Disconnected process message: 10, size: 0
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:30000 mC
,I/MDMCTBK (  292): NetlinkHandler, power_supply subsys
I/MDMCTBK (  292): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  292): checkDefaultInst, current pid is = 292
I/MDMCTBK (  292): checkDefaultInst, pid match
I/MDMCTBK (  292): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  292): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  292): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  292): NetlinkHandler, power_supply subsys
I/MDMCTBK (  292): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  292): checkDefaultInst, current pid is = 292
I/MDMCTBK (  292): checkDefaultInst, pid match
I/MDMCTBK (  292): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  292): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  292): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  292): NetlinkHandler, power_supply subsys
I/MDMCTBK (  292): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  292): checkDefaultInst, current pid is = 292
I/MDMCTBK (  292): checkDefaultInst, pid match
I/MDMCTBK (  292): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
,I/MDMCTBK (  292): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  292): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  292): NetlinkHandler, power_supply subsys
I/MDMCTBK (  292): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  292): checkDefaultInst, current pid is = 292
I/MDMCTBK (  292): checkDefaultInst, pid match
I/MDMCTBK (  292): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  292): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  292): MdmCutbackHndler,Could not open ''
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:30000 mC
,I/MDMCTBK (  292): NetlinkHandler, power_supply subsys
I/MDMCTBK (  292): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  292): checkDefaultInst, current pid is = 292
I/MDMCTBK (  292): checkDefaultInst, pid match
I/MDMCTBK (  292): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  292): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  292): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  292): NetlinkHandler, power_supply subsys
I/MDMCTBK (  292): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  292): checkDefaultInst, current pid is = 292
I/MDMCTBK (  292): checkDefaultInst, pid match
I/MDMCTBK (  292): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  292): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  292): MdmCutbackHndler,Could not open ''
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:30000 mC
,I/jxcore-log( 6731): --= Surplus to requirements =--
I/jxcore-log( 6731): 
,I/jxcore-log( 6731): ****TEST TOOK:  ms ****
I/jxcore-log( 6731): 
I/jxcore-log( 6731): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 6731): 
,D/AndroidRuntime( 8389): 
D/AndroidRuntime( 8389): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 8389): CheckJNI is OFF
,D/AndroidRuntime( 8389): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager(  879): Force stopping com.test.thalitest appid=10454 user=-1: uninstall pkg
,I/ActivityManager(  879): Killing 6731:com.test.thalitest/u0a454 (adj 9): stop com.test.thalitest
,I/WindowState(  879): WIN DEATH: Window{13373af1 u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/WifiService(  879): Client connection lost with reason: 4
,W/PackageSettings(  879): Skipping PackageSetting{39d504a2 com.example.hello/10440} due to missing metadata
,I/ActivityManager(  879):   Force finishing activity ActivityRecord{27934302 u0 com.test.thalitest/.MainActivity t6}
,W/ActivityManager(  879): Spurious death for ProcessRecord{2abe68f0 6731:com.test.thalitest/u0a454}, curProc for 6731: null
,I/ActivityManager(  879): Force stopping com.test.thalitest appid=10454 user=0: pkg removed
,I/Keyboard.Facilitator( 1415): resetDictionaries() : en_US
,I/InputReader(  879): Reconfiguring input devices.  changes=0x00000010
,W/GeofencerStateMachine( 1718): Ignoring removeGeofence because network location is disabled.
,I/art     ( 3014): Explicit concurrent mark sweep GC freed 9461(2MB) AllocSpace objects, 8(128KB) LOS objects, 39% free, 7MB/12MB, paused 1.298ms total 65.309ms
,D/VoicemailCleanupService( 8248): Cleaning up data for package: com.test.thalitest
,I/Keyboard.Facilitator.DecoderInitializer( 1415): run()
,I/Decoder ( 1415): createOrResetDecoder
,I/ActivityManager(  879): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=8421 uid=10027 gids={50027, 9997, 1023, 3003, 1028, 1015} abi=armeabi-v7a
,I/art     ( 1567): Explicit concurrent mark sweep GC freed 4960(306KB) AllocSpace objects, 6(297KB) LOS objects, 25% free, 13MB/17MB, paused 505us total 96.569ms
,I/ConfigService( 1718): onCreate
,I/art     (  879): Explicit concurrent mark sweep GC freed 11098(805KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 20MB/30MB, paused 1.457ms total 157.316ms
I/art     (  879): WaitForGcToComplete blocked for 157.570ms for cause Explicit
,W/asset   ( 8421): Asset path /system/framework/com.motorola.gallery is neither a directory nor file (type=1).
W/ResourcesManager( 8421): Asset path '/system/framework/com.motorola.gallery' does not exist or contains no resources.
,W/ResourcesManager( 8421): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 8421): Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1415): run()
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1415): loadStaticLm() : Loading File = /data/data/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4014912) with up to date LoudsLmContentVersion = 20150512
D/BackupManagerService(  879): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService(  879): Receieved: android.intent.action.PACKAGE_REMOVED
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1415): run()
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1415): run() : Loading LM = contacts
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1415): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1415): run() : Loading LM = history
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1415): run() : Loaded File = UserHistory.en_US.dict
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1415): run() : Loading LM = user
,I/ActivityManager(  879): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=8446 uid=1000 gids={41000, 9997, 1021, 3004, 3005, 1000, 3009, 1015, 1023, 1010, 1004, 2002, 3006, 1028, 3002, 3001, 3003} abi=armeabi-v7a
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1415): run() : Missing File = Personal.en_US.dict
,I/Keyboard.Facilitator.PersonalDictionaryLoader( 1415): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1415): run()
I/Keyboard.Facilitator.RecurringTaskScheduler( 1415): run()
I/StatsUtilsManager( 1415): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1415): shouldRecordStats() = Too Soon
,D/TaskPersister(  879): removeObsoleteFile: deleting file=6_task.xml
,I/ActivityManager(  879): Killing 8192:com.google.android.googlequicksearchbox:search/u0a39 (adj 15): empty #7
,I/art     (  879): Explicit concurrent mark sweep GC freed 5877(316KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 20MB/30MB, paused 1.842ms total 205.300ms
,W/libprocessgroup(  879): failed to open /acct/uid_10039/pid_8192/cgroup.procs: No such file or directory
,I/Launcher( 1567): Deferring update until onResume
,W/ContextImpl( 8446): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1820 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2611 
,D/PackageBroadcastService( 6970): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
,D/AccountUtils( 6970): Clearing selected account for com.test.thalitest
,D/ChimeraCfgMgr( 6970): Reading stored module config
,D/ChimeraCfgMgr( 6970): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 6970): Loading module APK com.google.android.play.games
,D/AndroidRuntime( 8389): Shutting down VM
,I/LocationSettingsChecker( 6970): Removing dialog suppression flag for package com.test.thalitest
,I/GMPM-SVC( 6970): App measurement is starting up, version: 8489
I/GMPM-SVC( 6970): To enable debug logging run: adb shell setprop log.tag.GMPM VERBOSE
,E/NetworkScheduler.SchedulerReceiver( 1718): Invalid parameter app
E/NetworkScheduler.SchedulerReceiver( 1718): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,D/gH_CompatibleDatabase( 6970): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/gH_CompatibleDatabase( 6970): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
,D/gH_MetricsDatabase( 6970): 0 metrics were deleted when clearing package com.test.thalitest.
D/gH_CompatibleDatabase( 6970): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
,D/gH_CompatibleDatabase( 6970): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
D/gH_CompatibleDatabase( 6970): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
,D/gH_CompatibleDatabase( 6970): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
,D/gH_CompatibleDatabase( 6970): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
D/gH_CompatibleDatabase( 6970): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
,D/gH_CompatibleDatabase( 6970): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
,D/gH_CompatibleDatabase( 6970): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
,D/gH_CompatibleDatabase( 6970): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
,D/gH_CompatibleDatabase( 6970): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
,I/ActivityManager(  879): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.IcingCorporaChangedReceiver: pid=8476 uid=10039 gids={50039, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
,W/Launcher( 1567): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@2a0ff4f7 new=com.google.android.velvet.VelvetApplication@2a0ff4f7
,D/ChimeraCfgMgr( 6970): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 6970): Module APK com.google.android.play.games already loaded
,I/ActivityManager(  879): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=8498 uid=10057 gids={50057, 9997, 1028, 3003, 1015} abi=armeabi-v7a
,I/Icing   ( 6970): doRemovePackageData com.test.thalitest
,W/BaseAppContext( 6970): Using Auth Proxy for data requests.
,E/BaseAppContext( 6970): Tried to stop global GMSCore RequestQueue. This is likely unintended, so ignoring.
,E/SQLiteLog( 6970): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,--------- beginning of crash
E/AndroidRuntime( 6970): FATAL EXCEPTION: IntentService[PeopleBackgroundTasks]
E/AndroidRuntime( 6970): Process: com.google.android.gms, PID: 6970
E/AndroidRuntime( 6970): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 6970): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AndroidRuntime( 6970): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/AndroidRuntime( 6970): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/AndroidRuntime( 6970): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/AndroidRuntime( 6970): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/AndroidRuntime( 6970): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/AndroidRuntime( 6970): 	at com.google.android.gms.people.c.e.a(SourceFile:110)
E/AndroidRuntime( 6970): 	at com.google.android.gms.people.sync.a.b.d(SourceFile:3166)
E/AndroidRuntime( 6970): 	at com.google.android.gms.people.service.bg.b.a(SourceFile:245)
E/AndroidRuntime( 6970): 	at com.google.android.gms.people.service.bg.PeopleBackgroundTasks.onHandleIntent(SourceFile:77)
E/AndroidRuntime( 6970): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 6970): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 6970): 	at android.os.Looper.loop(Looper.java:135)
E/AndroidRuntime( 6970): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ActivityManager(  879): Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=8534 uid=10019 gids={50019, 9997, 3003} abi=armeabi-v7a
,I/Process ( 6970): Sending signal. PID: 6970 SIG: 9
,E/lowmemorykiller(  275): Error writing /proc/6970/oom_score_adj; errno=22
,D/WifiService(  879): Client connection lost with reason: 4
,I/ActivityManager(  879): Process com.google.android.gms (pid 6970) has died
,W/ActivityManager(  879): Scheduling restart of crashed service com.google.android.gms/.appstate.service.AppStateIntentService in 1000ms
,W/ActivityManager(  879): Scheduling restart of crashed service com.google.android.gms/.icing.service.IndexWorkerService in 1000ms
W/ActivityManager(  879): Scheduling restart of crashed service com.google.android.gms/.games.chimera.GamesAsyncServiceProxy in 11000ms
,W/ActivityManager(  879): Scheduling restart of crashed service com.google.android.gms/.people.service.bg.PeopleBackgroundTasks in 11000ms
W/ActivityManager(  879): Scheduling restart of crashed service com.google.android.gms/.drive.api.DriveAsyncService in 21000ms
,I/UpdateIcingCorporaServi( 8476): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,E/native  ( 1415): dynamic-lm.cc:266 Cannot open fd for /data/data/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
E/native  ( 1415): dynamic-lm.cc:257 Cannot write DynamicLm to /data/data/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
,E/native  ( 1415): dynamic-lm.cc:266 Cannot open fd for /data/data/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
E/native  ( 1415): dynamic-lm.cc:257 Cannot write DynamicLm to /data/data/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
E/native  ( 1415): dynamic-lm.cc:266 Cannot open fd for /data/data/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
E/native  ( 1415): dynamic-lm.cc:257 Cannot write DynamicLm to /data/data/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
,I/ActivityManager(  879): Killing 8300:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,I/qdhwcomposer(  278): handle_blank_event: dpy:0 panel power state: 0

```
