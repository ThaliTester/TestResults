#### Test 5615109319b4771_thali04_motorola-XT1072 Logs


```
--------- beginning of main
,E/global frequency( 2734): no tags to log
D/Checkin ( 2734): publish the event [tag = MOT_CHECKIN event name = LOG]
D/BSUtils ( 2734): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
E/PhoneInterfaceManager( 1556): [PhoneIntfMgr] getIccId: ICC ID is null or empty.
I/art     (  891): Explicit concurrent mark sweep GC freed 36716(1767KB) AllocSpace objects, 2(215KB) LOS objects, 33% free, 20MB/30MB, paused 2.216ms total 159.911ms
I/art     ( 1477): Explicit concurrent mark sweep GC freed 55466(3MB) AllocSpace objects, 35(1216KB) LOS objects, 39% free, 7MB/12MB, paused 979us total 48.132ms
I/art     ( 2734): Explicit concurrent mark sweep GC freed 15631(828KB) AllocSpace objects, 2(32KB) LOS objects, 40% free, 11MB/18MB, paused 1.010ms total 78.379ms
D/AndroidRuntime( 6608): 
D/AndroidRuntime( 6608): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6608): CheckJNI is OFF
D/BSUtils ( 2734): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
I/BSUtils ( 2734): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
D/BSUtils ( 2734): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
E/PhoneInterfaceManager( 1556): [PhoneIntfMgr] getIccId: ICC ID is null or empty.
D/BSUtils ( 2734): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
I/BSUtils ( 2734): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
D/BSUtils ( 2734): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
E/PhoneInterfaceManager( 1556): [PhoneIntfMgr] getIccId: ICC ID is null or empty.
D/AndroidRuntime( 6608): Calling main entry com.android.commands.am.Am
--------- beginning of system
I/ActivityManager(  891): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
I/art     ( 1477): Explicit concurrent mark sweep GC freed 3911(165KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 7MB/12MB, paused 623us total 29.838ms
D/BSUtils ( 2734): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
I/ActivityManager(  891): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6632 uid=10458 gids={50458, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 6608): Shutting down VM
I/BSUtils ( 2734): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
I/BSUtils ( 2734): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
I/global frequency( 2734): BcsDSCheckin.logProperties: root status from persist.qe isqe 0/0
D/Checkin ( 2734): publish the event [tag = MOT_CHECKIN event name = LOG]
E/global frequency( 2734): BcsDSCheckin.logProperties: BL State from property is null or empty
D/Checkin ( 2734): publish the event [tag = MOT_CHECKIN event name = LOG]
D/Checkin ( 2734): publish the event [tag = DEV_ATTRIBS event name = SW]
I/global frequency( 2734): BcsCore.doCallHomeCore: Exceeded maximum number of checkins for one hour. Bailing out
D/Checkin ( 2734): publish the event [tag = MOT_CHECKIN event name = LOG]
V/ActivityManager(  891): Display changed displayId=0
W/ContextImpl( 1477): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
W/ContextImpl( 1477): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
V/AlarmManager(  891): send {842bec4, *alarm*:android.intent.action.TIME_TICK}
V/AlarmManager(  891): send {164430ac, *walarm*:com.google.android.intent.action.SEND_IDLE}
V/AlarmManager(  891): done {164430ac, *walarm*:com.google.android.intent.action.SEND_IDLE} [4ms]
V/AlarmManager(  891): done {842bec4, *alarm*:android.intent.action.TIME_TICK} [30ms]
,I/WebViewFactory( 6632): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/PhenotypeConfigurator( 1751): Scheduling Phenotype for one-off execution 13809 seconds from now (1453044900883)
,D/GetConfigurationSnapshotOperation( 1751): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/LibraryLoader( 6632): Time to load native libraries: 17 ms (timestamps 6000-6017)
,I/LibraryLoader( 6632): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 6632): Binding Chromium to main looper Looper (main, tid 1) {2712cc92}
I/LibraryLoader( 6632): Expected native library version number "",actual native library version number ""
,I/chromium( 6632): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 6632): Initializing chromium process, singleProcess=true
,W/art     ( 6632): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 6632): ApplicationContext is null in ApplicationStatus
,W/ActivityManager(  891): Activity pause timeout for ActivityRecord{144c42b9 u0 com.test.thalitest/.MainActivity t6}
,W/chromium( 6632): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 6632): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,E/libEGL  ( 6632): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 6632): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 6632): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 6632): Build Date: 10/28/14 Tue
I/Adreno-EGL( 6632): Local Branch: 
I/Adreno-EGL( 6632): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 6632): Local Patches: NONE
I/Adreno-EGL( 6632): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/PhenotypeFlagCommitter( 1751): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
I/GoogleURLConnFactory( 1751): Using platform SSLCertificateSocketFactory
,D/BluetoothManagerService(  891): Message: 20
D/BluetoothManagerService(  891): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1391bae:true
,W/art     ( 6632): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 6632): onDetachedFromWindow called when already detached. Ignoring
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:31000 mC
,D/SystemWebViewEngine( 6632): CordovaWebView is running on device made by: motorola
,W/art     ( 6632): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 6632): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 6632): Render dirty regions requested: true
,D/Atlas   ( 6632): Validating map...
,W/chromium( 6632): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/art     (  891): Explicit concurrent mark sweep GC freed 11418(572KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 20MB/30MB, paused 1.445ms total 128.522ms
,I/OpenGLRenderer( 6632): Initialized EGL, version 1.4
,D/OpenGLRenderer( 6632): Enabling debug mode 0
,I/Keyboard.Facilitator( 1428): onFinishInput()
,I/LaunchCheckinHandler(  891): Displayed com.test.thalitest/.MainActivity,cp,ca,1298
,I/ActivityManager(  891): Displayed com.test.thalitest/.MainActivity: +1s203ms (total +1s298ms)
,W/IInputConnectionWrapper( 6632): showStatusIcon on inactive InputConnection
,E/Adreno-ES20( 6632): <check_framebuffer_attachment:854>: Invalid texture format! Returning error!
E/Adreno-ES20( 6632): <check_framebuffer_object_status:1237>: Framebuffer color attachment incomplete. Returning GL_FRAMEBUFFER_INCOMPLETE_ATTACHMENT!
,W/BindingManager( 6632): Cannot call determinedVisibility() - never saw a connection for the pid: 6632
,D/JsMessageQueue( 6632): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 6632): JniHelper::setJavaVM(0xb8043310), pthread_self() = -1203950720
D/JX-Cordova( 6632): jxcore cordova android initializing
,I/art     ( 6632): Background sticky concurrent mark sweep GC freed 33273(3MB) AllocSpace objects, 10(1398KB) LOS objects, 20% free, 15MB/19MB, paused 1.976ms total 103.894ms
,W/jxcore-log( 6632): Initializing JXcore engine
,W/jxcore-log( 6632): JXcore engine is ready
,W/jxcore-log( 6632): Starting JXcore engine
,W/.test.thalitest( 6632): type=1400 audit(0.0:4): avc: denied { ioctl } for uid=10458 path="socket:[5575]" dev="sockfs" ino=5575 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/.test.thalitest( 6632): type=1400 audit(0.0:5): avc: denied { ioctl } for uid=10458 path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2122 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
W/.test.thalitest( 6632): type=1400 audit(0.0:6): avc: denied { ioctl } for uid=10458 path="socket:[9471]" dev="sockfs" ino=9471 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/.test.thalitest( 6632): type=1400 audit(0.0:7): avc: denied { ioctl } for uid=10458 path="socket:[28111]" dev="sockfs" ino=28111 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,W/jxcore-log( 6632): Platform android
W/jxcore-log( 6632): 
W/jxcore-log( 6632): Process ARCH arm
W/jxcore-log( 6632): 
,V/GLSActivity( 1751): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1751): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/jxcore-log( 6632): JXcore Cordova bridge is ready!
I/jxcore-log( 6632): 
W/jxcore-log( 6632): JXcore engine is started
,I/chromium( 6632): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 6632): Toggling radios to true
I/jxcore-log( 6632): 
,D/BluetoothAdapter( 6632): enable(): BT is already enabled..!
,D/WifiService(  891): New client listening to asynchronous messages
,D/WifiService(  891): setWifiEnabled: true pid=6632, uid=10458
E/WifiService(  891): Invoking mWifiStateMachine.setWifiEnabled
,I/jxcore-log( 6632): Radios toggled
I/jxcore-log( 6632): 
,I/jxcore-log( 6632): My device name is: motorola-XT1072
I/jxcore-log( 6632): 
,D/TCMD    (  482): NL - Read 1004 bytes from update socket.
D/TCMD    (  482): NL - message type is RTM_NEWLINK
D/TCMD    (  482): Listening for incoming client connection request
D/TCMD    (  482): NL - Read 68 bytes from update socket.
D/TCMD    (  482): NL - message type is RTM_NEWLINK
D/TCMD    (  482): Listening for incoming client connection request
D/TCMD    (  482): NL - Read 68 bytes from update socket.
D/TCMD    (  482): NL - message type is RTM_NEWLINK
D/TCMD    (  482): Listening for incoming client connection request
,I/wpa_supplicant( 1420): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-DISCONNECTED 
D/MDMCTBK (  292): Event received = CTRL-EVENT-DISCONNECTED 
D/MDMCTBK (  292):  STA Disconnected !!
I/MDMCTBK (  292): checkDefaultInst, current pid is = 292
I/MDMCTBK (  292): checkDefaultInst, pid match
I/MDMCTBK (  292): get_property_value, Enter
I/MDMCTBK (  292): get_property_value, Values read from property=1,0,0,0,0,0,1,0,0,1,1,0, length=23
I/MDMCTBK (  292): get_property_value, Exit
I/MDMCTBK (  292): MdmCutbackHndler,wifiDisconnected wifi_dis=1, current_wifi=1
I/MDMCTBK (  292): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=0, mf=0, wfd=0
I/MDMCTBK (  292): set_property_value, Enter
I/MDMCTBK (  292): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
,I/MDMCTBK (  292): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  292): set_property_value, Exit
I/MDMCTBK (  292): MdmCutbackHndler, setWifiCutback, No Wifi
I/MDMCTBK (  292): MdmCutbackHndler,Wifi disconnected !!!
I/MDMCTBK (  292): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=0, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  292): set_property_value, Enter
I/MDMCTBK (  292): set_property_value, Values updated in the property=1,0,0,0,0,0,0,0,0,1,1,0
I/MDMCTBK (  292): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  292): set_property_value, Exit
E/MDMCTBK (  292): MdmCutbackHndler,Airplane Mode Enabled !! =1
,D/Tethering(  891): InitialState.processMessage what=4
,D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  292): Event received = CTRL-EVENT-STATE-CHANGE 
,I/wpa_supplicant( 1420): wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=WORLD
D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-REGDOM-CHANGE
D/MDMCTBK (  292): Event received = CTRL-EVENT-REGDOM-CHANGE
,E/WifiStateMachine(  891): WifiStateMachine: Leaving Connected state
,E/WifiStateMachine(  891): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$8800 - exit - invokeExitMethods
E/WifiStateMachine(  891): handleNetworkDisconnect any config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  891): handleNetworkDisconnect "NG700" nid=0
E/WifiConfigStore(  891): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,W/Settings(  891): Setting tether_dun_apn has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,E/Tethering(  891): ApnList is empty for checkDunConfigured()
D/Tethering(  891):  upstream interface types: 
D/Tethering(  891):  1
D/Tethering(  891):  5
D/Tethering(  891):  7
D/Tethering(  891):  0
,I/wpa_supplicant( 1420): wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=US
,D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-REGDOM-CHANGE
D/MDMCTBK (  292): Event received = CTRL-EVENT-REGDOM-CHANGE
,D/Tethering(  891): sendTetherStateChangedBroadcast 0, 0, 0
,E/WifiStateMachine(  891): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/WifiStateMachine(  891): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/native  (  891): do suspend true
,E/wpa_supplicant( 1420): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
,D/WifiP2pService(  891): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  891): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/CommandListener(  290): Clearing all IP addresses on wlan0
D/TCMD    (  482): NL - Read 60 bytes from update socket.
D/TCMD    (  482): NL - ignore NL message, type = 21
D/TCMD    (  482): Listening for incoming client connection request
,V/NativeCrypto( 1751): Read error: ssl=0xb8289b48: I/O error during system call, Connection timed out
,V/NativeCrypto( 1751): SSL shutdown failed: ssl=0xb8289b48: I/O error during system call, Broken pipe
D/ConnectivityService(  891): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10016
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  891): ValidatedState{ when=-5ms what=532488 arg1=10016 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  891): DefaultState{ when=-5ms what=532488 arg1=10016 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  891): Forcing reevaluation
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  891): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  891): Checking http://clients3.google.com/generate_204 on "NG700"
E/WifiStateMachine(  891): setDetailed state, old =CONNECTED and new state=DISCONNECTED hidden=false
E/WifiStateMachine(  891): setDetailed state send new extra info<unknown ssid>
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  891): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
,I/ActivityManager(  891): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6720 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/SBar.MotoNetworkCtrlr( 1301): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1301): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/WifiMetrics(  891): connected time updated 130304
,I/SBar.MotoNetworkCtrlr( 1301): refreshSignalCluster[0]: wifi: mWifiConnected=true Wifi=0x7f02012a=com.android.systemui:drawable/stat_sys_wifi_signal_0_fully Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
,D/ConnectivityService(  891): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,D/Checkin (  891): publish the event [tag = MOT_WIFI_L1 event name = CONNECT]
D/ConnectivityService(  891): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
,E/wpa_supplicant( 1420): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
,E/WifiStateMachine(  891): Start Disconnecting Watchdog 1
I/wpa_supplicant( 1420): wlan0: CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  292): Event received = CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  292): Event received = CTRL-EVENT-SCAN-STARTED 
D/Checkin (  891): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,I/SBar.MotoNetworkCtrlr( 1301): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1301): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1301): refreshSignalCluster[0]: wifi: mWifiConnected=false Wifi=0x7f020133=com.android.systemui:drawable/stat_sys_wifi_signal_null Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
,I/SBar.MotoNetworkCtrlr( 1301): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1301): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/Checkin (  891): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
E/WifiStateMachine(  891): ConnectModeState: Network connection lost 
,E/WifiStateMachine(  891): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$8800 - processMessage - processMsg
,E/WifiStateMachine(  891): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
,E/WifiStateMachine(  891): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/native  (  891): do suspend true
,D/WifiP2pService(  891): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  891): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,E/wpa_supplicant( 1420): wpa_driver_nl80211_driver_cmd: failed to set RXFILTER option
,D/CommandListener(  290): Clearing all IP addresses on wlan0
D/ConnectivityService(  891): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
D/Nat464Xlat(  891): requiresClat: netType=1, connected=false, hasIPv4Address=true
D/CSLegacyTypeTracker(  891): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/ConnectivityManager.CallbackHandler( 1971): CM callback handler got msg 524292
D/ConnectivityService(  891): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  891): EvaluatingState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  891): DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  891): Disconnected - quitting
D/ConnectivityManager.CallbackHandler( 1301): CM callback handler got msg 524292
E/WifiStateMachine(  891): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
,W/ResourcesManager( 6720): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/ConnectivityService(  891): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,I/ModemStatsDSDetect( 1545): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
,I/SBar.MotoNetworkCtrlr( 1301): onReceive: CONNECTIVITY_ACTION_IMMEDIATE Recieved, mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/ModemStatsDSDetect( 1545): INET_CONDITION=0 ,activeNet=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  891): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,I/ModemStatsDSDetect( 1545): onReceive() - done, currentInetCondition=0
I/ModemStatsDSDetect( 1545): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
,I/SBar.MotoNetworkCtrlr( 1301): updateConnectivity[0]: NetworkInfo: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false], raw inetCondition= 0
I/SBar.MotoNetworkCtrlr( 1301): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/ModemStatsDSDetect( 1545): INET_CONDITION=0 ,activeNet=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/ModemStatsDSDetect( 1545): onReceive() - done, currentInetCondition=0
I/SBar.MotoNetworkCtrlr( 1301): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1301): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1301): onReceive: CONNECTIVITY_ACTION_IMMEDIATE Recieved, mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,E/ConnectivityService(  891): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,I/SBar.MotoNetworkCtrlr( 1301): updateConnectivity[0]: NetworkInfo: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false], raw inetCondition= 0
I/SBar.MotoNetworkCtrlr( 1301): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1301): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1301): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1301): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
D/Checkin (  891): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
I/SBar.MotoNetworkCtrlr( 1301): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,E/WifiStateMachine(  891): SUPPLICANT_STATE_CHANGE_EVENT state=DISCONNECTED -> state= DISCONNECTED debouncing=false
E/WifiStateMachine(  891): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
,E/WifiStateMachine(  891): Link configuration changed for netId: -1 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  891): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
,E/WifiStateMachine(  891): Link configuration changed for netId: -1 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  891): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
,E/WifiStateMachine(  891): Link configuration changed for netId: -1 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  891): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
D/WifiNetworkAgent(  891): NetworkAgent: NetworkAgent channel lost
E/WifiStateMachine(  891): SUPPLICANT_STATE_CHANGE_EVENT state=SCANNING -> state= SCANNING debouncing=false
,E/WifiStateMachine(  891): setDetailed state, old =DISCONNECTED and new state=SCANNING hidden=false
E/WifiStateMachine(  891): setDetailed state send new extra info"NG700"
,I/SBar.MotoNetworkCtrlr( 1301): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1301): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/Checkin (  891): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,I/SBar.MotoNetworkCtrlr( 1301): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1301): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/Checkin (  891): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,I/Babel_SMS( 6720): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 6720): MmsConfig.loadMmsSettings
I/Babel_SMS( 6720): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
I/Babel_SMS( 6720): MmsConfig.loadFromDatabase
,E/Babel_SMS( 6720): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 6720): MmsConfig.loadFromResources
,E/Babel_SMS( 6720): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel_SMS( 6720): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/Settings( 6720): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 6720): startup - clean
,I/Babel   ( 6720): deleted: false for 0
,D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-SCAN-RESULTS 
D/MDMCTBK (  292): Event received = CTRL-EVENT-SCAN-RESULTS 
D/TCMD    (  482): NL - Read 56 bytes from update socket.
D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=wlan0 <3>WPS-AP-AVAILABLE 
D/MDMCTBK (  292): Event received = WPS-AP-AVAILABLE 
D/TCMD    (  482): NL - message type is RTM_NEWLINK
D/TCMD    (  482): Listening for incoming client connection request
,I/wpa_supplicant( 1420): wlan0: Trying to associate with SSID 'NG700'
,E/wpa_supplicant( 1420): DSDS: eapol_sm_notify_config config->sim_num = 1
D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=wlan0 <3>Trying to associate with
D/MDMCTBK (  292): Event received = Trying to associate with
D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  292): Event received = CTRL-EVENT-STATE-CHANGE 
D/WifiMonitor(  891): didn't find BSSID Trying to associate with SSID 'NG700'
E/WifiStateMachine(  891): [1,453,044,906,292 ms] noteScanEnd no scan source
E/WifiStateMachine(  891): wifi setScanResults statecom.android.server.wifi.WifiStateMachine$DisconnectedState@23f04f26 sup_state=SCANNING debouncing=false
,E/WifiStateMachine(  891): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATING -> state= CONNECTING debouncing=false
E/WifiStateMachine(  891): setDetailed state, old =SCANNING and new state=CONNECTING hidden=false
E/WifiStateMachine(  891): setDetailed state send new extra info0x
,I/ActivityManager(  891): Start proc com.motorola.context for broadcast com.motorola.context/.publisher.location.LocationReceiver: pid=6758 uid=10008 gids={50008, 9997, 3001, 3002, 3003} abi=armeabi-v7a
,I/SBar.MotoNetworkCtrlr( 1301): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1301): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/Checkin (  891): publish the event [tag = MOT_WIFI_L1 event name = DISCONNECT]
,I/SBar.MotoNetworkCtrlr( 1301): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1301): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/TCMD    (  482): NL - Read 312 bytes from update socket.
D/TCMD    (  482): NL - message type is RTM_NEWLINK
D/TCMD    (  482): Listening for incoming client connection request
D/TCMD    (  482): NL - Read 192 bytes from update socket.
D/TCMD    (  482): NL - message type is RTM_NEWLINK
D/TCMD    (  482): Listening for incoming client connection request
D/TCMD    (  482): NL - Read 68 bytes from update socket.
D/TCMD    (  482): NL - message type is RTM_NEWLINK
D/TCMD    (  482): Listening for incoming client connection request
D/TCMD    (  482): NL - Read 1004 bytes from update socket.
D/TCMD    (  482): NL - message type is RTM_NEWLINK
D/TCMD    (  482): Listening for incoming client connection request
D/TCMD    (  482): NL - Read 80 bytes from update socket.
D/TCMD    (  482): NL - message type is RTM_NEWLINK
D/TCMD    (  482): Listening for incoming client connection request
D/TCMD    (  482): NL - Read 80 bytes from update socket.
D/TCMD    (  482): NL - message type is RTM_NEWLINK
I/wpa_supplicant( 1420): wlan0: Associated with c0:ff:d4:d3:aa:48
D/TCMD    (  482): Listening for incoming client connection request
D/TCMD    (  482): NL - Read 68 bytes from update socket.
D/TCMD    (  482): NL - message type is RTM_NEWLINK
D/TCMD    (  482): Listening for incoming client connection request
D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  292): Event received = CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=wlan0 <3>Associated with c0:ff:d4
D/MDMCTBK (  292): Event received = Associated with c0:ff:d4
D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  292): Event received = CTRL-EVENT-STATE-CHANGE 
E/WifiStateMachine(  891): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATED -> state= CONNECTING debouncing=false
E/WifiStateMachine(  891): setDetailed state, old =CONNECTING and new state=CONNECTING hidden=false
D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  292): Event received = CTRL-EVENT-STATE-CHANGE 
I/wpa_supplicant( 1420): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 1420): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
D/TCMD    (  482): NL - Read 1004 bytes from update socket.
D/TCMD    (  482): NL - message type is RTM_NEWLINK
D/TCMD    (  482): Listening for incoming client connection request
D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=wlan0 <3>WPA: Key negotiation com
D/MDMCTBK (  292): Event received = WPA: Key negotiation com
D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-CONNECTED - C
D/MDMCTBK (  292): Event received = CTRL-EVENT-CONNECTED - C
D/MDMCTBK (  292):  STA Connected !!
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
,I/MDMCTBK (  292): MdmCutbackHndler,UpdateWifiBand set mWifi to True, call setWifiCutback and sendSarCtrl!!!
I/MDMCTBK (  292): MdmCutbackHndler, setWifiCutback vc=0, dc=0, wf=1, mf=0, wfd=0
I/MDMCTBK (  292): set_property_value, Enter
I/MDMCTBK (  292): set_property_value, Values updated in the property=1,0,0,0,0,0,1,0,0,1,1,0
D/Tethering(  891): exception when get active network info: java.lang.NullPointerException: Attempt to invoke virtual method 'int android.net.NetworkInfo.getType()' on a null object reference
W/Settings(  891): Setting tether_dun_apn has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
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
,I/MDMCTBK (  292): create_thread_wpa_supplicant: Started WPA thread for wifi_set_tx_pwr thread -1218355384
I/MDMCTBK (  292): return from set_get_from_wpa_supplicant
I/MDMCTBK (  292): MdmCutbackHndler Status: Qmi =1, cg=0, ep=0, vc=0, dc=0, cn=0, wf=1, mf=0, wfd=0, apm=1, usb=1, stopqmi=0
I/MDMCTBK (  292): set_property_value, Enter
D/MDMCTBK (  292): wifi_set_tx_pwr: SETTXPOWER = 18
I/MDMCTBK (  292): set_property_value, Values updated in the property=1,0,0,0,0,0,1,0,0,1,1,0
E/MDMCTBK (  292): cmd: IFNAME=wlan0 DRIVER SETTXPOWER 18, reply: OK
E/MDMCTBK (  292): , reply_len: 3, ret: 0
E/MDMCTBK (  292): MdmCutbackHndler, resp=OK
E/MDMCTBK (  292): 
,D/MDMCTBK (  292): wifi_set_tx_pwr: Exit
I/MDMCTBK (  292): set_property_value, Values updated in the property file Successfully
I/MDMCTBK (  292): set_property_value, Exit
E/MDMCTBK (  292): MdmCutbackHndler,Airplane Mode Enabled !! =1
D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-STATE-CHANGE 
D/MDMCTBK (  292): Event received = CTRL-EVENT-STATE-CHANGE 
E/Tethering(  891): ApnList is empty for checkDunConfigured()
D/Tethering(  891):  upstream interface types: 
D/Tethering(  891):  0
D/Tethering(  891):  1
D/Tethering(  891):  5
D/Tethering(  891):  7
,D/Tethering(  891): sendTetherStateChangedBroadcast 1, 0, 0
,E/WifiStateMachine(  891): SUPPLICANT_STATE_CHANGE_EVENT state=FOUR_WAY_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine(  891): setDetailed state, old =CONNECTING and new state=AUTHENTICATING hidden=false
,E/WifiStateMachine(  891): setDetailed state send new extra info"NG700"
,I/SBar.MotoNetworkCtrlr( 1301): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1301): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1301): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1301): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,E/WifiStateMachine(  891): SUPPLICANT_STATE_CHANGE_EVENT state=GROUP_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine(  891): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING hidden=false
E/WifiStateMachine(  891): Network connection established
E/WifiStateMachine(  891): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR hidden=false
I/SBar.MotoNetworkCtrlr( 1301): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1301): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
W/VideoCapabilities( 6720): Unrecognized profile 2130706433 for video/avc
,I/SBar.MotoNetworkCtrlr( 1301): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1301): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,E/WifiStateMachine(  891): setDetailed state, old =OBTAINING_IPADDR and new state=CONNECTING hidden=false
,I/SBar.MotoNetworkCtrlr( 1301): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1301): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/ConnectivityService(  891): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
,E/WifiStateMachine(  891): L2ConnectedState any config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  891): L2ConnectedState "NG700" nid=0
E/WifiConfigStore(  891): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/ConnectivityService(  891): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,E/WifiStateMachine(  891): enter ObtainingIpState netId=0 "NG700"WPA_PSK  roam=0 static=false watchdog= 1
E/WifiStateMachine(  891): ObtainingIpAddress any config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  891): ObtainingIpAddress "NG700" nid=0
E/WifiConfigStore(  891): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,D/CommandListener(  290): Setting iface cfg
E/WifiStateMachine(  891): Start Dhcp Watchdog 2
,E/WifiStateMachine(  891): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
,W/ResourcesManager( 6758): Asset path '/system/framework/com.motorola.motosignature.jar' does not exist or contains no resources.
,E/WifiStateMachine(  891): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES
,E/WifiStateMachine(  891): setSuspendOptimizationsNative: 1 false -want true stack:setSuspendOptimizationsNative - handlePreDhcpSetup - processMessage - processMsg
,E/native  (  891): do suspend false
,E/wpa_supplicant( 1420): wpa_driver_nl80211_driver_cmd: failed to issue private commands
,E/WifiStateMachine(  891): Unexpected BatchedScanResults :null
E/wpa_supplicant( 1420): wpa_driver_nl80211_driver_cmd: failed to issue private commands
,W/AudioCapabilities( 6720): Unsupported mime audio/amr-wb-plus
D/WifiP2pService(  891): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@16bad087 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  891): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@16bad087 target=com.android.internal.util.StateMachine$SmHandler }
,W/VideoCapabilities( 6720): Unsupported mime video/mpeg2
,I/VideoCapabilities( 6720): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 6720): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6720): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6720): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6720): Unrecognized profile 2130706433 for video/avc
,I/ActivityManager(  891): Killing 6216:android.process.acore/u0a7 (adj 15): empty #7
,I/vclib   ( 6720): onServiceConnected
W/Babel   ( 6720): Attempted to change video mute state without an active call.
,W/libprocessgroup(  891): failed to open /acct/uid_10007/pid_6216/cgroup.procs: No such file or directory
,E/DHCPCD  ( 6779): fopen `/system/etc/dhcpcd/dhcpcd.conf': m
,I/DHCPCD  ( 6779): version 5.5.6 starting
,E/DHCPCD  ( 6779): fopen `/system/etc/dhcpcd/dhcpcd.conf': m
D/DHCPCD  ( 6779): wlan0: using ClientID 01:44:80:eb:7b:5a:06
,D/DHCPCD  ( 6779): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
,I/ActivityManager(  891): Killing 6458:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,D/DHCPCD  ( 6779): wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
I/DHCPCD  ( 6779): wlan0: rebinding lease of 192.168.1.123
,D/DHCPCD  ( 6779): wlan0: sending REQUEST (xid 0x96691ffe), next in 4.52 seconds
,W/libprocessgroup(  891): failed to open /acct/uid_10090/pid_6458/cgroup.procs: No such file or directory
,I/DHCPCD  ( 6779): wlan0: acknowledged 192.168.1.123 from 192.168.1.1
,I/DHCPCD  ( 6779): wlan0: leased 192.168.1.123 for 86400 seconds
D/DHCPCD  ( 6779): wlan0: adding IP address 192.168.1.123/24
,D/DHCPCD  ( 6779): wlan0: adding route to 192.168.1.0/24
D/DHCPCD  ( 6779): wlan0: adding default route via 192.168.1.1
D/DHCPCD  ( 6779): wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
,D/TCMD    (  482): NL - Read 60 bytes from update socket.
D/TCMD    (  482): NL - ignore NL message, type = 20
D/TCMD    (  482): Listening for incoming client connection request
,D/DHCPCD  ( 6779): wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
,E/WifiStateMachine(  891): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  891): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES v4
,E/WifiStateMachine(  891): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
E/WifiStateMachine(  891): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
E/native  (  891): do suspend true
,D/WifiP2pService(  891): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  891): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiStateMachine(  891): WifiStateMachine DHCP successful
E/WifiStateMachine(  891): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,E/WifiStateMachine(  891): updateLinkProperties nid: 0 state: CONNECTING reason: DHCP_SUCCESS v4 v4r v4dns isprov
E/WifiStateMachine(  891): Calling ARP set with IP = 192.168.1.123
E/WifiStateMachine(  891): setDetailed state, old =CONNECTING and new state=CAPTIVE_PORTAL_CHECK hidden=false
,I/SBar.MotoNetworkCtrlr( 1301): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1301): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1301): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
I/SBar.MotoNetworkCtrlr( 1301): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,E/WifiStateMachine(  891): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED hidden=false
,D/ConnectivityService(  891): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,D/ConnectivityService(  891): Adding iface wlan0 to network 101
,I/SBar.MotoNetworkCtrlr( 1301): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
,I/SBar.MotoNetworkCtrlr( 1301): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/SBar.MotoNetworkCtrlr( 1301): refreshSignalCluster[0]: wifi: mWifiConnected=true Wifi=0x7f020129=com.android.systemui:drawable/stat_sys_wifi_signal_0 Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
,E/ConnectivityService(  891): Unexpected mtu value: 0, wlan0
D/ConnectivityService(  891): Adding Route [fe80::/64 -> :: wlan0] to network 101
D/ConnectivityService(  891): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
D/ConnectivityService(  891): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
D/ConnectivityService(  891): Setting Dns servers for network 101 to [/192.168.1.1]
D/Nat464Xlat(  891): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  891): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  891): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  891): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  891): Connected
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  891): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  891): Checking http://clients3.google.com/generate_204 on "NG700"
,D/Checkin (  891): publish the event [tag = MOT_WIFI_L1 event name = CONNECT]
,I/SBar.MotoNetworkCtrlr( 1301): onReceive: WifiManager.NETWORK_STATE_CHANGED_ACTION Received
D/ConnectivityService(  891): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  891):    accepting network in place of null
I/SBar.MotoNetworkCtrlr( 1301): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/ConnectivityService(  891): UpdateTcpBufferSizes: same sizes as current, ignore operation
,E/WifiStateMachine(  891): ConnectedState Enter  mScreenOn=false scanperiod=20000
,D/CSLegacyTypeTracker(  891): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/ConnectivityService(  891): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  891): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
D/Checkin (  891): publish the event [tag = MOT_WIFI_L1 event name = CONNECT]
D/ConnectivityService(  891): UpdateTcpBufferSizes: same sizes as current, ignore operation
D/ConnectivityService(  891): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
,I/ModemStatsDSDetect( 1545): onReceive() -Intent { act=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE flg=0x4000010 (has extras) }
,I/SBar.MotoNetworkCtrlr( 1301): onReceive: CONNECTIVITY_ACTION_IMMEDIATE Recieved, mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/ModemStatsDSDetect( 1545): INET_CONDITION=0 ,activeNet=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/ModemStatsDSDetect( 1545): onReceive() - done, currentInetCondition=0
I/SBar.MotoNetworkCtrlr( 1301): updateConnectivity[0]: NetworkInfo: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false], raw inetCondition= 0
I/SBar.MotoNetworkCtrlr( 1301): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1301): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1301): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,D/ConnectivityManager.CallbackHandler( 1301): CM callback handler got msg 524290
,D/ConnectivityManager.CallbackHandler( 1971): CM callback handler got msg 524290
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  891): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Sun, 17 Jan 2016 15:35:08 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1453044908516], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1453044908491]}
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  891): Don't send network conditions - lacking user consent.
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  891): Validated
D/ConnectivityService(  891): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  891): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  891): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
,D/ConnectivityService(  891): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityManager.CallbackHandler( 1301): CM callback handler got msg 524290
D/ConnectivityService(  891): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/ConnectivityManager.CallbackHandler( 1971): CM callback handler got msg 524290
I/SBar.MotoNetworkCtrlr( 1301): onReceive: INET_CONDITION_ACTION Recieved, mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
,I/ModemStatsDSDetect( 1545): onReceive() -Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) }
I/SBar.MotoNetworkCtrlr( 1301): updateConnectivity: The netConditon[0] for netType 1=WiFi is updated as 1=good by android.net.conn.INET_CONDITION_ACTION, icon color should be white (on KK); without "!" (on L).
I/SBar.MotoNetworkCtrlr( 1301): updateConnectivity[0]: NetworkInfo: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false], raw inetCondition= 1
I/SBar.MotoNetworkCtrlr( 1301): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1301): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/SBar.MotoNetworkCtrlr( 1301): refreshSignalCluster[0]: wifi: mWifiConnected=true Wifi=0x7f02012a=com.android.systemui:drawable/stat_sys_wifi_signal_0_fully Activity=0x00000000=( none ) Accessibility="Wifi disconnected."
,I/SBar.MotoNetworkCtrlr( 1301): updateDataIcon[0]: mCurrentDataSubId=-1000 maps to: dataPhoneId:0 ( SubscriptionManager.getPhoneId returned -1000=0xfffffc18 )
I/ModemStatsDSDetect( 1545): INET_CONDITION=100 ,activeNet=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/ModemStatsDSDetect( 1545): Inetcondition changed, white->blue
I/ModemStatsDSDetect( 1545): onReceive() - done, currentInetCondition=100
,D/ConnectivityService(  891): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
D/PollingManager( 2734): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/Tethering(  891): MasterInitialState.processMessage what=3
D/ConnectivityService(  891): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Central_PollingManager( 1477): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/PollingManager( 2734): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/ContextImpl( 1477): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1469 android.content.ContextWrapper.sendBroadcast:381 com.motorola.blur.service.blur.BSUtils.sendBroadcast:94 com.motorola.blur.service.blur.BSUtils.sendBroadcast:90 com.motorola.ccc.plm.pollingmanager.PollingManagerService$MyConnectivityReceiver.onReceive:491 
,D/PollingManager( 2734): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/OtaApp  ( 2734): [debug] > pollingManagerService, connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ActivityManager(  891): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=6845 uid=10080 gids={50080, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/Tethering(  891): MasterInitialState.processMessage what=3
,D/PollingManager( 2734): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/Central_PollingManager( 1477): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/PollingManager( 2734): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
D/PollingManager( 2734): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/PollingManager( 2734): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
D/PollingManager( 2734): connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/PollingManager( 2734): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
D/OtaApp  ( 2734): [debug] > pollingManagerService, connectivity_action: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/OtaApp  ( 2734): [debug] > PollingManagerService, not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
D/Central_PollingManager( 1477): not sending out intent since this notification wasn't for the active network or it was and nothing has changed: null
D/OtaApp  ( 2734): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.ccc.ota.pm.POLLINGMGR_CONNECTIVITY
D/OtaApp  ( 2734): [debug] > CusSM.onRadioDown
,D/CCE     ( 2734): Registering with Alarm Manager to restart CCE
,D/CCE     ( 2734): Registering with Alarm Manager to restart CCE
,D/CCE     ( 2734): Registering with Alarm Manager to restart CCE
,I/MusicStore( 6845): Database version: 120
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6845): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6845): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6845): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,W/ResourcesManager( 6845): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6845): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 6845): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 6845): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 6845): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@3bbb274e: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6845): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 6845): GMSCore installation verified
,I/ConfigStore( 6845): Config Database version: 1
,D/ConnectivityService(  891): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,I/MediaRouter( 6845): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 6845): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/NetworkMonitor( 6845): type=WIFI subType= reason=null isConnected=true
,I/NetworkMonitor( 6845): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  891): Start proc com.android.mms for broadcast com.android.mms/.transaction.MmsSystemEventReceiver: pid=6887 uid=10023 gids={50023, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/GHttpClientFactory( 6845): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 6845): Using platform SSLCertificateSocketFactory
,I/ActivityManager(  891): Killing 6397:com.google.android.googlequicksearchbox:search/u0a39 (adj 15): empty #7
,W/libprocessgroup(  891): failed to open /acct/uid_10039/pid_6397/cgroup.procs: No such file or directory
,V/Mms     ( 6887): mnc/mcc: 
,V/Mms     ( 6887): tag: int value: recipientLimit - 20
,V/Mms     ( 6887): tag: int value: smsToMmsTextThreshold - 6
,V/Mms     ( 6887): tag: int value: emergencySmsTimeout - 30
,V/Mms     ( 6887): tag: int value: maxSubjectLength - 80
V/Mms     ( 6887): tag: bool value: smsForceShowEncodingMenu - true
V/Mms     ( 6887): tag: bool value: enableGroupMms - false
V/Mms     ( 6887):  mUserAgent = MOT-XT1072/Mms-5.0,  mUaProfUrl = http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/ResourcesManager( 6887): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/ActivityManager(  891): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=6913 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  891): Killing 6486:com.android.vending/u0a32 (adj 15): empty #7
,D/PhoneMonitor( 6913): Register our PhoneStateListener
,W/libprocessgroup(  891): failed to open /acct/uid_10032/pid_6486/cgroup.procs: No such file or directory
,D/MobileConnectivityChangeReceiver( 6913): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 6913): onReceive CONNECTIVITY_CHANGE networkType=1
,I/ActivityManager(  891): Killing 6720:com.google.android.talk/u0a70 (adj 15): empty #7
,I/jxcore-log( 6632): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
I/jxcore-log( 6632): 
,W/libprocessgroup(  891): failed to open /acct/uid_10070/pid_6720/cgroup.procs: No such file or directory
,I/CheckinService( 1971): Checkin interval check for package: unspecified last checkin: 1453044820740 min interval config: 0 actual interval: 89504
,I/ActivityManager(  891): Start proc com.google.android.apps.photos for broadcast com.google.android.apps.photos/.jobqueue.JobServiceBroadcastReceiver: pid=6932 uid=10088 gids={50088, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
I/CheckinService( 1971): Checking schedule, now: 1453044910297 next: 1453044850710
,I/CheckinService( 1971): active receiver: enabled
,I/CheckinService( 1971): Preparing to send checkin request
I/EventLogService( 1971): Accumulating logs since 1453044816549
,I/CheckinRequestBuilder( 1971): Checkin reason type: 8 attempt count: 1
,E/ActivityThread( 1971): Failed to find provider info for com.google.android.wearable.settings
,I/art     (  891): Explicit concurrent mark sweep GC freed 45515(2MB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 20MB/30MB, paused 3.318ms total 144.210ms
,I/ActivityManager(  891): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6955 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,V/GLSActivity( 1751): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1751): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ResourcesManager( 6955): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/ActivityManager(  891): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=6973 uid=10016 gids={50016, 9997, 3003, 1028, 1015, 3002, 3001, 1005, 1007, 3007, 2001, 3006} abi=armeabi-v7a
,I/art     (  309): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 250us total 21.949ms
,I/art     (  309): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 253us total 19.248ms
,I/art     (  309): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 249us total 20.987ms
,I/jxcore-log( 6632): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
I/jxcore-log( 6632): 
,I/jxcore-log( 6632): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliCryptoManager.js
I/jxcore-log( 6632): 
,W/ResourcesManager( 6973): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6973): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/MultiDex( 6973): VM with version 2.1.0 has multidex support
I/MultiDex( 6973): install
I/MultiDex( 6973): VM has multidex support, MultiDex support library is disabled.
,I/jxcore-log( 6632): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliEmitter.js
I/jxcore-log( 6632): 
,V/JNIHelp ( 6973): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/Babel_SMS( 6955): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 6955): MmsConfig.loadMmsSettings
I/Babel_SMS( 6955): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
I/Babel_SMS( 6955): MmsConfig.loadFromDatabase
,I/jxcore-log( 6632): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNativeLayer.js
I/jxcore-log( 6632): 
,I/jxcore-log( 6632): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationManager.js
I/jxcore-log( 6632): 
E/WifiStateMachine(  891): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 131072,262144,3145728,4096,221184,3145728} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.123/24,fe80::4680:ebff:fe7b:5a06/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
E/WifiStateMachine(  891): updateLinkProperties nid: 0 state: CONNECTED reason: CMD_UPDATE_LINKPROPERTIES v4 v4r v4dns isprov
D/ConnectivityService(  891): UpdateTcpBufferSizes: same sizes as current, ignore operation
D/Nat464Xlat(  891): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  891): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityManager.CallbackHandler( 1971): CM callback handler got msg 524295
D/ConnectivityManager.CallbackHandler( 1301): CM callback handler got msg 524295
,E/Babel_SMS( 6955): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 6955): MmsConfig.loadFromResources
,E/Babel_SMS( 6955): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 6955): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,I/jxcore-log( 6632): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log( 6632): 
,W/ActivityThread( 6973): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 6973): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@12f5f397: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 6973): Installed default security provider GmsCore_OpenSSL
,I/art     ( 6973): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 6973): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
W/Settings( 6955): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 6955): startup - clean
,I/Babel   ( 6955): deleted: false for 0
,D/NativeLibraryUtils( 6973): Install completed successfully. count=14 extracted=0
,I/ActivityManager(  891): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7011 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/ConnectivityService(  891): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  891): MasterInitialState.processMessage what=3
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:32000 mC
,D/PollingManager( 2734): connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/PollingManager( 2734): now: 206510 ,futureTime: 9223372036854775807
D/PollingManager( 2734): connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/PollingManager( 2734): now: 206510 ,futureTime: 9223372036854775807
D/PollingManager( 2734): connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/PollingManager( 2734): now: 206510 ,futureTime: 9223372036854775807
D/OtaApp  ( 2734): [debug] > pollingManagerService, connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/Central_PollingManager( 1477): connectivity_action: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/ContextImpl( 1477): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1469 android.content.ContextWrapper.sendBroadcast:381 com.motorola.blur.service.blur.BSUtils.sendBroadcast:94 com.motorola.blur.service.blur.BSUtils.sendBroadcast:90 com.motorola.ccc.plm.pollingmanager.PollingManagerService$MyConnectivityReceiver.onReceive:491 
,D/Central_PollingManager( 1477): now: 206517 ,futureTime: 86474939
D/Central_PollingManager( 1477): Polling alarm set to expire at: 86474939 Current Time: 206517
,D/OtaApp  ( 2734): [debug] > PollingManagerService, now: 206513 ,futureTime: 8963428
,D/OtaApp  ( 2734): [debug] > Polling alarm set to expire at: 8963428 Current Time: 206518
,D/OtaApp  ( 2734): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.ccc.ota.pm.POLLINGMGR_CONNECTIVITY
D/OtaApp  ( 2734): [debug] > CusSM.onRadioUp
,I/NetworkMonitor( 6845): type=WIFI subType= reason=null isConnected=true
D/OtaApp  ( 2734): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,D/OtaApp  ( 2734): [debug] > CusSM.runStateMachine: getVersions's version Blur_Version.22.21.28.thea_reteu.reteuall.en.EU; getDescription's versionBlur_Version.22.21.28.thea_reteu.reteuall.en.EU
,D/MMApiProvisionService( 2734): isDeviceProvisioned: deviceId = 2072049230914535424
I/OtaApp  ( 2734): [info] > CusSM.runStateMachine: found version Blur_Version.22.21.28.thea_reteu.reteuall.en.EU in database with state (RequestPermission)
D/Checkin ( 2734): publish the event [tag = MOT_OTA event name = LOG]
D/WVCdm   (  294): Instantiating CDM.
,D/OtaApp  ( 2734): [debug] > CusSM.runStateMachine: server told to :continue
,D/OtaApp  ( 2734): [debug] > CusSM.runStateMachine: user is being notified for version Blur_Version.22.21.28.thea_reteu.reteuall.en.EU
,D/OtaApp  ( 2734): [debug] > CusSM.runStateMachine: getDownloadOptStartStopTime text null
,I/WVCdm   (  294): CdmEngine::OpenSession
,D/OtaApp  ( 2734): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,I/WVCdm   (  294): Level3 Library Sep 25 2014 17:10:03
,W/WVCdm   (  294): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,D/CCE     ( 2734): trying to auto login since I haven't yet and the radio is up now
I/MMApiProvisionService( 2734): createDeviceIdOrLogin update_device
,D/Checkin ( 2734): publish the event [tag = MOT_CCE event name = LOG]
D/MMApiProvisionService( 2734): Not proxy app, so login/provision not allowed
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
,D/MMApiProvisionService( 2734): isDeviceProvisioned: deviceId = 2072049230914535424
,D/CCE     ( 2734): trying to auto login since I haven't yet and the radio is up now
I/MMApiProvisionService( 2734): createDeviceIdOrLogin update_device
,D/Checkin ( 2734): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiProvisionService( 2734): isDeviceProvisioned: deviceId = 2072049230914535424
,D/QSEECOMAPI: (  294): Loaded image: APP id = 3
,D/DrmWidevineDash(  294): Service_Initialize: ends! returns 0
,D/DrmWidevineDash(  294): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4ff7000
E/DrmWidevineDash(  294): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4ff7000
D/MMApiProvisionService( 2734): set mOutstandingReq to true.
I/ Nonce  ( 2734):  Nonce getNonce 
I/ Nonce  ( 2734):  Nonce Request 
I/ Nonce  ( 2734):  Nonce execute Request 
,D/MMApiWebService( 2734): doRequest() with req : MMApiWSRequest(/v1/gdi/nonce.json)
,D/DrmWidevineDash(  294): OEMCrypto_Initialize: ends! returns 0
D/DrmWidevineDash(  294): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  294): hlos api version =  9
D/DrmWidevineDash(  294): tz api version =  8
D/DrmWidevineDash(  294): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  294): OEMCrypto_IsKeyboxValid: starts!
,D/DrmWidevineDash(  294): OEMCrypto_IsKeyboxValid: ends! returns 0
D/WVCdm   (  294): OEMCrypto_Initialize Level 1 success. I will use level 1.
D/DrmWidevineDash(  294): OEMCrypto_OpenSession: starts! SID=0xbe8ed4e0
D/DrmWidevineDash(  294): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  294): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  294): OEMCrypto_GetRandom: starts! randomData=0xb7ca4e48, dataLength=8
D/DrmWidevineDash(  294): OEMCrypto_GetRandom: ends! returns 0
D/MMApiProvisionService( 2734): isDeviceProvisioned: deviceId = 2072049230914535424
,D/DrmWidevineDash(  294): OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb7c8da78, wrapped_rsa_key_length=1280
D/DrmWidevineDash(  294): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
I/WVCdm   (  294): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  294): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  294): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  294): CdmEngine::GenerateKeyRequest
,D/DrmWidevineDash(  294): OEMCrypto_GetDeviceID: starts! deviceID=0xb7ce7da0, idLength=0xb13df730
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
D/WVCdm   (  294): PrepareKeyRequest: nonce=2701239965
,W/VideoCapabilities( 6955): Unrecognized profile 2130706433 for video/avc
,D/DrmWidevineDash(  294): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb7c9c4e8
D/DrmWidevineDash(  294): message_length=1591, signature=0xb7c192e0, signature_length=2973628180
,D/CCE     ( 2734): trying to auto login since I haven't yet and the radio is up now
,I/MMApiProvisionService( 2734): createDeviceIdOrLogin update_device
D/Checkin ( 2734): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiProvisionService( 2734): Not proxy app, so login/provision not allowed
,W/AudioCapabilities( 6955): Unsupported mime audio/amr-wb-plus
W/VideoCapabilities( 6955): Unsupported mime video/mpeg2
,I/VideoCapabilities( 6955): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 6955): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6955): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6955): Unrecognized profile 2130706433 for video/avc
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
,D/DrmWidevineDash(  294): OEMCrypto_Terminate: ends! returns 0
,W/VideoCapabilities( 6955): Unrecognized profile 2130706433 for video/avc
,I/vclib   ( 6955): onServiceConnected
,W/Babel   ( 6955): Attempted to change video mute state without an active call.
,I/jxcore-log( 6632): Test app app.js loaded
I/jxcore-log( 6632): 
,I/chromium( 6632): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/Babel   ( 6955): connection state changed from UNKNOWN to CONNECTED
,I/ActivityManager(  891): Killing 6758:com.motorola.context/u0a8 (adj 15): empty #7
,I/art     ( 1477): Explicit concurrent mark sweep GC freed 4407(198KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 7MB/12MB, paused 2.913ms total 96.776ms
,D/MMApiWebService( 2734): generating token using payload instead of using session token
,D/ Nonce  ( 2734):  getUrl method url https://argo.svcmot.com:443/v1/gdi/nonce.json/ZX1C223JKW?appid=6R1TANEX3ZMQ6EU1UH43P34C8B868KTE
,I/MMApiWSBase( 2734): doRequest(): url: https://argo.svcmot.com:443/v1/gdi/nonce.json/ZX1C223JKW?appid=6R1TANEX3ZMQ6EU1UH43P34C8B868KTE
,D/Checkin ( 2734): publish the event [tag = MOT_CCE event name = LOG]
,I/dex2oat ( 7034): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=28 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,W/libprocessgroup(  891): failed to open /acct/uid_10008/pid_6758/cgroup.procs: No such file or directory
,I/dex2oat ( 7034): dex2oat took 89.666ms (threads: 4)
,I/Adreno-EGL( 6973): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 6973): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 6973): Build Date: 10/28/14 Tue
I/Adreno-EGL( 6973): Local Branch: 
I/Adreno-EGL( 6973): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 6973): Local Patches: NONE
I/Adreno-EGL( 6973): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
,W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7011): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
,W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7011): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7011): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7011): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,I/GAv4    ( 7011): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 7011):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 7011):   adb logcat -s GAv4
,W/GAv4    ( 7011): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 7011): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 7011): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/Adreno-EGL( 6973): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 6973): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 6973): Build Date: 10/28/14 Tue
I/Adreno-EGL( 6973): Local Branch: 
I/Adreno-EGL( 6973): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 6973): Local Patches: NONE
I/Adreno-EGL( 6973): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,V/AlarmManager(  891): send {105d1aec, *walarm*:com.google.android.intent.action.GCM_RECONNECT}
,I/Adreno-EGL( 6973): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 6973): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 6973): Build Date: 10/28/14 Tue
I/Adreno-EGL( 6973): Local Branch: 
I/Adreno-EGL( 6973): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 6973): Local Patches: NONE
I/Adreno-EGL( 6973): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/WebViewFactory( 7011): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/Adreno-EGL( 6973): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 6973): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 6973): Build Date: 10/28/14 Tue
I/Adreno-EGL( 6973): Local Branch: 
I/Adreno-EGL( 6973): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 6973): Local Patches: NONE
I/Adreno-EGL( 6973): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/LibraryLoader( 7011): Time to load native libraries: 2 ms (timestamps 7593-7595)
,I/LibraryLoader( 7011): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 7011): Binding Chromium to main looper Looper (main, tid 1) {4a4f087}
I/LibraryLoader( 7011): Expected native library version number "",actual native library version number ""
I/chromium( 7011): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 7011): Initializing chromium process, singleProcess=true
,W/art     ( 7011): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 7011): ApplicationContext is null in ApplicationStatus
,W/chromium( 7011): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 7011): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 7011): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 7011): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 7011): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7011): Build Date: 10/28/14 Tue
I/Adreno-EGL( 7011): Local Branch: 
I/Adreno-EGL( 7011): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 7011): Local Patches: NONE
I/Adreno-EGL( 7011): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,W/AudioManagerAndroid( 7011): Requires BLUETOOTH permission
,I/NSApplication( 7011): Starting up...
,I/ActivityManager(  891): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=7084 uid=10052 gids={50052, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  891): Killing 6845:com.google.android.music:main/u0a80 (adj 15): empty #7
,W/libprocessgroup(  891): failed to open /acct/uid_10080/pid_6845/cgroup.procs: No such file or directory
,I/WVCdm   (  294): CdmEngine::OpenSession
I/WVCdm   (  294): Level3 Library Sep 25 2014 17:10:03
,W/WVCdm   (  294): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,D/DrmWidevineDash(  294): OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x13
D/DrmWidevineDash(  294): Service_Initialize: starts!
D/QSEECOMAPI: (  294): QSEECom_get_handle sb_length = 0x19000
,D/QSEECOMAPI: (  294): App is not loaded in QSEE
E/QSEECOMAPI: (  294): Error::Cannot open the file /vendor/firmware/widevine.mdt
,E/QSEECOMAPI: (  294): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  294): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  294): App is not loaded in QSEE
E/QSEECOMAPI: (  294): Error::Cannot open the file /system/etc/firmware/widevine.mdt
E/QSEECOMAPI: (  294): Error::Loading image failed with ret = -1
D/QSEECOMAPI: (  294): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  294): App is not loaded in QSEE
,D/QSEECOMAPI: (  294): Loaded image: APP id = 3
,D/DrmWidevineDash(  294): Service_Initialize: ends! returns 0
D/DrmWidevineDash(  294): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4fdb000
E/DrmWidevineDash(  294): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4fdb000
,D/DrmWidevineDash(  294): OEMCrypto_Initialize: ends! returns 0
,D/DrmWidevineDash(  294): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  294): hlos api version =  9
D/DrmWidevineDash(  294): tz api version =  8
D/DrmWidevineDash(  294): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  294): OEMCrypto_IsKeyboxValid: starts!
,D/DrmWidevineDash(  294): OEMCrypto_IsKeyboxValid: ends! returns 0
,D/WVCdm   (  294): OEMCrypto_Initialize Level 1 success. I will use level 1.
D/DrmWidevineDash(  294): OEMCrypto_OpenSession: starts! SID=0xbe8ed4e0
D/DrmWidevineDash(  294): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  294): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  294): OEMCrypto_GetRandom: starts! randomData=0xb7c1aab8, dataLength=8
D/DrmWidevineDash(  294): OEMCrypto_GetRandom: ends! returns 0
D/DrmWidevineDash(  294): OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb7c8da78, wrapped_rsa_key_length=1280
D/DrmWidevineDash(  294): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
,I/WVCdm   (  294): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  294): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  294): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  294): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  294): OEMCrypto_GetDeviceID: starts! deviceID=0xb7ce7de0, idLength=0xb13df730
,I/ Nonce  ( 2734):  Nonce Reponse 
D/        ( 2734): ProvisionWS.Response: processing response data: {"error":"OK","nonce":"d48db7a3-9cc6-42ce-b4d7-e3994c628d61"}
,D/MMApiWSBase( 2734): doRequest(): /v1/gdi/nonce.json resp length: 61
,D/DrmWidevineDash(  294): OEMCrypto_GetDeviceID: ends! returns 0
I/ Nonce  ( 2734):  Nonce Handle Reponse 
D/DrmWidevineDash(  294): OEMCrypto_SupportsUsageTable: starts!
D/MMApiProvisionService( 2734): mOutstandingReq set to false
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
D/WVCdm   (  294): PrepareKeyRequest: nonce=65149005
D/DrmWidevineDash(  294): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb7c15ff8
D/DrmWidevineDash(  294): message_length=1625, signature=0xb7c15398, signature_length=2973628180
,I/art     ( 2734): Explicit concurrent mark sweep GC freed 16600(984KB) AllocSpace objects, 1(16KB) LOS objects, 40% free, 11MB/18MB, paused 1.264ms total 77.256ms
,D/MMApiProvisionService( 2734):  pTime 1453032756427 sExp 172742 cTime 1453044913018 tTime 1453205498427
D/MMApiProvisionService( 2734):  No login Required 
,D/DrmWidevineDash(  294): OEMCrypto_GenerateRSASignature returns 0
,I/ActivityManager(  891): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7106 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  891): Killing 6887:com.android.mms/u0a23 (adj 15): empty #7
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
,W/libprocessgroup(  891): failed to open /acct/uid_10023/pid_6887/cgroup.procs: No such file or directory
,W/ResourcesManager( 7106): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/CheckinRequestBuilder( 1971): Classify the device as Phone.
,W/DataUsage( 2734): invalid counter update blocked: 'err' by 0
,D/Checkin ( 2734): publish the event [tag = MOT_CCE event name = LOG]
,I/art     (  891): Explicit concurrent mark sweep GC freed 14533(700KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 20MB/30MB, paused 1.690ms total 113.848ms
,I/ActivityManager(  891): Start proc android.process.acore for content provider com.android.providers.contacts/.ContactsProvider2: pid=7129 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,I/ActivityManager(  891): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=7152 uid=10080 gids={50080, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  891): Killing 6932:com.google.android.apps.photos/u0a88 (adj 15): empty #7
,I/ContactLocale( 7129): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,I/ActivityManager(  891): Killing 6913:com.google.android.setupwizard/u0a35 (adj 15): empty #8
,W/libprocessgroup(  891): failed to open /acct/uid_10088/pid_6932/cgroup.procs: No such file or directory
,W/libprocessgroup(  891): failed to open /acct/uid_10035/pid_6913/cgroup.procs: No such file or directory
,I/MusicStore( 7152): Database version: 120
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7152): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
,W/Vold    (  277): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7152): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7152): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,W/ResourcesManager( 7152): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7152): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 7152): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 7152): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 7152): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@3bbb274e: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7152): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 7152): GMSCore installation verified
,I/ConfigStore( 7152): Config Database version: 1
,I/MediaRouter( 7152): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 7152): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/NetworkMonitor( 7152): type=WIFI subType= reason=null isConnected=true
,I/NetworkMonitor( 7152): type=WIFI subType= reason=null isConnected=true
,I/CheckinTask( 1971): Sending checkin request (9507 bytes)
,I/ActivityManager(  891): Start proc com.android.mms for broadcast com.android.mms/.transaction.MmsSystemEventReceiver: pid=7186 uid=10023 gids={50023, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/GHttpClientFactory( 7152): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 7152): Using platform SSLCertificateSocketFactory
,I/ActivityManager(  891): Killing 6955:com.google.android.talk/u0a70 (adj 15): empty #7
,W/libprocessgroup(  891): failed to open /acct/uid_10070/pid_6955/cgroup.procs: No such file or directory
,V/Mms     ( 7186): mnc/mcc: 
,V/Mms     ( 7186): tag: int value: recipientLimit - 20
V/Mms     ( 7186): tag: int value: smsToMmsTextThreshold - 6
,V/Mms     ( 7186): tag: int value: emergencySmsTimeout - 30
V/Mms     ( 7186): tag: int value: maxSubjectLength - 80
V/Mms     ( 7186): tag: bool value: smsForceShowEncodingMenu - true
V/Mms     ( 7186): tag: bool value: enableGroupMms - false
,V/Mms     ( 7186):  mUserAgent = MOT-XT1072/Mms-5.0,  mUaProfUrl = http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
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
I/MDMCTBK (  292): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  292): MdmCutbackHndler,Could not open ''
,W/ResourcesManager( 7186): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/ActivityManager(  891): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=7217 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  891): Killing 7011:com.google.android.apps.magazines/u0a81 (adj 15): empty #7
,W/libprocessgroup(  891): failed to open /acct/uid_10081/pid_7011/cgroup.procs: No such file or directory
,D/PhoneMonitor( 7217): Register our PhoneStateListener
,D/MobileConnectivityChangeReceiver( 7217): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 7217): onReceive CONNECTIVITY_CHANGE networkType=1
,I/ActivityManager(  891): Killing 7084:com.android.chrome/u0a52 (adj 15): empty #7
,W/libprocessgroup(  891): failed to open /acct/uid_10052/pid_7084/cgroup.procs: No such file or directory
,I/CheckinService( 1971): Checkin interval check for package: unspecified last checkin: 1453044820740 min interval config: 0 actual interval: 93798
,I/CheckinRequestBuilder( 1971): Checkin reason type: 8 attempt count: 1
,I/ActivityManager(  891): Start proc com.google.android.apps.photos for broadcast com.google.android.apps.photos/.jobqueue.JobServiceBroadcastReceiver: pid=7236 uid=10088 gids={50088, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,E/ActivityThread( 1971): Failed to find provider info for com.google.android.wearable.settings
,I/art     ( 6506): Explicit concurrent mark sweep GC freed 1784(79KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 7MB/9MB, paused 391us total 26.228ms
,I/CheckinRequestBuilder( 1971): Classify the device as Phone.
,I/CheckinTask( 1971): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 1971): Checking schedule, now: 1453044914838 next: 1453646051827
I/CheckinService( 1971): active receiver: disabled
,I/CheckinService( 1971): Checking schedule, now: 1453044914861 next: 1453646051827
I/CheckinService( 1971): active receiver: disabled
,D/CheckinService( 1971): Recording last checkin time for package unspecified as 1453044914866
,I/ActivityManager(  891): Killing 7129:android.process.acore/u0a7 (adj 13): empty #7
,I/ActivityManager(  891): Killing 7106:com.google.android.apps.plus/u0a90 (adj 15): empty #8
,W/libprocessgroup(  891): failed to open /acct/uid_10007/pid_7129/cgroup.procs: No such file or directory
,W/libprocessgroup(  891): failed to open /acct/uid_10090/pid_7106/cgroup.procs: No such file or directory
,I/ActivityManager(  891): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=7256 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/ActivityManager(  891): Killing 7152:com.google.android.music:main/u0a80 (adj 13): empty #7
,W/libprocessgroup(  891): failed to open /acct/uid_10080/pid_7152/cgroup.procs: No such file or directory
,W/ResourcesManager( 7256): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/Babel_SMS( 7256): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 7256): MmsConfig.loadMmsSettings
,I/Babel_SMS( 7256): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
I/Babel_SMS( 7256): MmsConfig.loadFromDatabase
,E/Babel_SMS( 7256): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 7256): MmsConfig.loadFromResources
,E/Babel_SMS( 7256): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel_SMS( 7256): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/Settings( 7256): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 7256): startup - clean
,I/Babel   ( 7256): deleted: false for 0
,I/ActivityManager(  891): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7290 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/VideoCapabilities( 7256): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 7256): Unsupported mime audio/amr-wb-plus
W/VideoCapabilities( 7256): Unsupported mime video/mpeg2
,I/VideoCapabilities( 7256): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 7256): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7256): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7256): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7256): Unrecognized profile 2130706433 for video/avc
,I/vclib   ( 7256): onServiceConnected
W/Babel   ( 7256): Attempted to change video mute state without an active call.
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,I/GAv4    ( 7290): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 7290):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 7290):   adb logcat -s GAv4
W/ContextImpl( 7290): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7290): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,W/GAv4    ( 7290): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7290): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
,W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7290): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,W/GAv4    ( 7290): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 7290): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/Babel   ( 7256): connection state changed from UNKNOWN to CONNECTED
,I/ActivityManager(  891): Killing 7186:com.android.mms/u0a23 (adj 13): empty #7
,W/libprocessgroup(  891): failed to open /acct/uid_10023/pid_7186/cgroup.procs: No such file or directory
,I/WebViewFactory( 7290): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 7290): Time to load native libraries: 1 ms (timestamps 1083-1084)
I/LibraryLoader( 7290): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 7290): Binding Chromium to main looper Looper (main, tid 1) {4a4f087}
I/LibraryLoader( 7290): Expected native library version number "",actual native library version number ""
I/chromium( 7290): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 7290): Initializing chromium process, singleProcess=true
,W/art     ( 7290): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 7290): ApplicationContext is null in ApplicationStatus
,W/chromium( 7290): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 7290): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 7290): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 7290): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 7290): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7290): Build Date: 10/28/14 Tue
I/Adreno-EGL( 7290): Local Branch: 
I/Adreno-EGL( 7290): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 7290): Local Patches: NONE
I/Adreno-EGL( 7290): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,W/AudioManagerAndroid( 7290): Requires BLUETOOTH permission
,I/NSApplication( 7290): Starting up...
,I/ActivityManager(  891): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=7359 uid=10052 gids={50052, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  891): Killing 7217:com.google.android.setupwizard/u0a35 (adj 15): empty #7
,I/art     (  309): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 257us total 21.754ms
,I/art     (  309): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 249us total 19.391ms
,I/art     (  309): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 253us total 19.618ms
,W/libprocessgroup(  891): failed to open /acct/uid_10035/pid_7217/cgroup.procs: No such file or directory
,I/art     (  891): Explicit concurrent mark sweep GC freed 11007(557KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 20MB/30MB, paused 1.602ms total 127.047ms
,I/ActivityManager(  891): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7378 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  891): Killing 7236:com.google.android.apps.photos/u0a88 (adj 13): empty #7
,W/libprocessgroup(  891): failed to open /acct/uid_10088/pid_7236/cgroup.procs: No such file or directory
,W/ResourcesManager( 7378): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/ActivityManager(  891): Start proc android.process.acore for content provider com.android.providers.contacts/.ContactsProvider2: pid=7401 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,I/ActivityManager(  891): Killing 7290:com.google.android.apps.magazines/u0a81 (adj 13): empty #7
,I/ContactLocale( 7401): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,I/ActivityManager(  891): Killing 7256:com.google.android.talk/u0a70 (adj 15): empty #8
,W/libprocessgroup(  891): failed to open /acct/uid_10081/pid_7290/cgroup.procs: No such file or directory
,W/libprocessgroup(  891): failed to open /acct/uid_10070/pid_7256/cgroup.procs: No such file or directory
,D/EmailService.MarketingOptInSetter( 2734): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/GetNotificationsWS( 2734): bindWebServices(): registering our AIDL callback...
,I/SundryService( 2734): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
D/WaitableIntentService( 2734): ServiceHandler.handleMessage: mWaitCount=0
,D/GetNotificationsWS( 2734): onServiceConnected()
D/GetNotificationsWS( 2734): onServiceConnected(): Registered for remote service callbacks...
,D/GetNotificationsWS( 2734): unbindWebServices(): un-registering our AIDL callback...
,I/ActivityManager(  891): Start proc com.google.android.apps.photos for broadcast com.google.android.apps.photos/.jobqueue.JobServiceBroadcastReceiverInternal: pid=7435 uid=10088 gids={50088, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/PushService( 2734): started with background data enabled, making sure notification mechanism is enabled
,D/WearableService( 1751): callingUid 10016, callindPid: 1751
,D/LocationInitializer( 1971): Restart initialization of location
,D/AuthorizationBluetoothService( 1751): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,V/GLSActivity( 1751): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/MDM     ( 1751): [153] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,I/ActivityManager(  891): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=7465 uid=10080 gids={50080, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/GCoreFlp( 1751): No location to return for getLastLocation()
,W/FusedLocationProvider( 1751): location=null
,I/MusicStore( 7465): Database version: 120
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7465): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7465): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.music/files/
,W/Vold    (  277): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7465): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.music/files
,W/ResourcesManager( 7465): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7465): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 7465): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 7465): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 7465): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@3bbb274e: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7465): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 7465): GMSCore installation verified
,I/ConfigStore( 7465): Config Database version: 1
,I/MediaRouter( 7465): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 7465): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/NetworkMonitor( 7465): type=WIFI subType= reason=null isConnected=true
,I/NetworkMonitor( 7465): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  891): Start proc com.android.mms for broadcast com.android.mms/.transaction.MmsSystemEventReceiver: pid=7497 uid=10023 gids={50023, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/GHttpClientFactory( 7465): Using our fixed implementation of GMSCore's GoogleHttpClient
I/GoogleURLConnFactory( 7465): Using platform SSLCertificateSocketFactory
,V/Mms     ( 7497): mnc/mcc: 
V/Mms     ( 7497): tag: int value: recipientLimit - 20
V/Mms     ( 7497): tag: int value: smsToMmsTextThreshold - 6
V/Mms     ( 7497): tag: int value: emergencySmsTimeout - 30
V/Mms     ( 7497): tag: int value: maxSubjectLength - 80
V/Mms     ( 7497): tag: bool value: smsForceShowEncodingMenu - true
V/Mms     ( 7497): tag: bool value: enableGroupMms - false
V/Mms     ( 7497):  mUserAgent = MOT-XT1072/Mms-5.0,  mUaProfUrl = http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/ResourcesManager( 7497): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/ActivityManager(  891): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=7528 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  891): Killing 7359:com.android.chrome/u0a52 (adj 15): empty #7
,W/libprocessgroup(  891): failed to open /acct/uid_10052/pid_7359/cgroup.procs: No such file or directory
,I/ActivityManager(  891): Killing 7378:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,I/MDMCTBK (  292): NetlinkHandler, power_supply subsys
I/MDMCTBK (  292): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  292): checkDefaultInst, current pid is = 292
I/MDMCTBK (  292): checkDefaultInst, pid match
I/MDMCTBK (  292): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  292): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  292): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  292): NetlinkHandler, power_supply subsys
,I/MDMCTBK (  292): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  292): checkDefaultInst, current pid is = 292
I/MDMCTBK (  292): checkDefaultInst, pid match
I/MDMCTBK (  292): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  292): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  292): MdmCutbackHndler,Could not open ''
,D/PhoneMonitor( 7528): Register our PhoneStateListener
,W/libprocessgroup(  891): failed to open /acct/uid_10090/pid_7378/cgroup.procs: No such file or directory
,D/MobileConnectivityChangeReceiver( 7528): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 7528): onReceive CONNECTIVITY_CHANGE networkType=1
,I/ActivityManager(  891): Killing 7401:android.process.acore/u0a7 (adj 15): empty #7
,W/libprocessgroup(  891): failed to open /acct/uid_10007/pid_7401/cgroup.procs: No such file or directory
,I/CheckinService( 1971): Checkin interval check for package: unspecified last checkin: 1453044914866 min interval config: 0 actual interval: 3638
,I/CheckinService( 1971): Checkin interval check for package: unspecified last checkin: 1453044914866 min interval config: 0 actual interval: 3643
,I/CheckinService( 1971): Checking schedule, now: 1453044918519 next: 1453044944827
I/CheckinService( 1971): active receiver: disabled
,I/ActivityManager(  891): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=7548 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
I/CheckinService( 1971): Checking schedule, now: 1453044918593 next: 1453044944827
,I/CheckinService( 1971): active receiver: disabled
,W/ResourcesManager( 7548): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/Babel_SMS( 7548): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 7548): MmsConfig.loadMmsSettings
,I/Babel_SMS( 7548): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
I/Babel_SMS( 7548): MmsConfig.loadFromDatabase
,E/Babel_SMS( 7548): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 7548): MmsConfig.loadFromResources
,E/Babel_SMS( 7548): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 7548): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/Settings( 7548): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 7548): startup - clean
,I/Babel   ( 7548): deleted: false for 0
,I/ActivityManager(  891): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7578 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/VideoCapabilities( 7548): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 7548): Unsupported mime audio/amr-wb-plus
W/VideoCapabilities( 7548): Unsupported mime video/mpeg2
,I/VideoCapabilities( 7548): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 7548): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 7548): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 7548): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7548): Unrecognized profile 2130706433 for video/avc
,I/vclib   ( 7548): onServiceConnected
,W/Babel   ( 7548): Attempted to change video mute state without an active call.
,I/GAv4    ( 7578): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 7578):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 7578):   adb logcat -s GAv4
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7578): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7578): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,W/GAv4    ( 7578): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7578): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/cache
,I/Babel   ( 7548): connection state changed from UNKNOWN to CONNECTED
,I/ActivityManager(  891): Killing 7465:com.google.android.music:main/u0a80 (adj 15): empty #7
,E/Vold    (  277): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  277): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7578): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.apps.magazines/files
,W/GAv4    ( 7578): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 7578): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,W/libprocessgroup(  891): failed to open /acct/uid_10080/pid_7465/cgroup.procs: No such file or directory
,I/WebViewFactory( 7578): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 7578): Time to load native libraries: 2 ms (timestamps 4659-4661)
I/LibraryLoader( 7578): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 7578): Binding Chromium to main looper Looper (main, tid 1) {4a4f087}
,I/LibraryLoader( 7578): Expected native library version number "",actual native library version number ""
,I/chromium( 7578): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 7578): Initializing chromium process, singleProcess=true
,W/art     ( 7578): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 7578): ApplicationContext is null in ApplicationStatus
,W/chromium( 7578): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 7578): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,E/libEGL  ( 7578): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 7578): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 7578): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7578): Build Date: 10/28/14 Tue
I/Adreno-EGL( 7578): Local Branch: 
I/Adreno-EGL( 7578): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 7578): Local Patches: NONE
I/Adreno-EGL( 7578): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,W/AudioManagerAndroid( 7578): Requires BLUETOOTH permission
,I/art     (  891): Explicit concurrent mark sweep GC freed 12171(586KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 20MB/30MB, paused 1.899ms total 117.972ms
,I/NSApplication( 7578): Starting up...
,I/ActivityManager(  891): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=7653 uid=10052 gids={50052, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  891): Killing 7497:com.android.mms/u0a23 (adj 15): empty #7
,W/libprocessgroup(  891): failed to open /acct/uid_10023/pid_7497/cgroup.procs: No such file or directory
,I/ActivityManager(  891): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7680 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  891): Killing 6973:com.google.android.gms.unstable/u0a16 (adj 15): empty #7
,W/libprocessgroup(  891): failed to open /acct/uid_10016/pid_6973/cgroup.procs: No such file or directory
,W/ResourcesManager( 7680): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/ActivityManager(  891): Start proc android.process.acore for content provider com.android.providers.contacts/.ContactsProvider2: pid=7706 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,I/InputReader(  891): Reconfiguring input devices.  changes=0x00000010
,I/art     (  309): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 342us total 25.416ms
,I/art     (  309): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 274us total 20.815ms
,I/art     (  309): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 248us total 21.577ms
,I/ActivityManager(  891): Killing 7435:com.google.android.apps.photos/u0a88 (adj 15): empty #7
,D/BackupManagerService(  891): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/BackupManagerService(  891): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,I/ContactLocale( 7706): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,I/ActivityManager(  891): Killing 7528:com.google.android.setupwizard/u0a35 (adj 15): empty #8
,W/libprocessgroup(  891): failed to open /acct/uid_10088/pid_7435/cgroup.procs: No such file or directory
,D/EmailService.MarketingOptInSetter( 2734): received com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,W/libprocessgroup(  891): failed to open /acct/uid_10035/pid_7528/cgroup.procs: No such file or directory
,I/BackupManagerService(  891): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/BackupManagerService(  891): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/BackupManagerService(  891): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@4389f36
,D/GetNotificationsWS( 2734): bindWebServices(): registering our AIDL callback...
,I/SundryService( 2734): onHandleIntent(): action=com.motorola.blur.service.blur.Actions.POLLINGMGR_CONNECTIVITY
,D/WaitableIntentService( 2734): ServiceHandler.handleMessage: mWaitCount=0
D/GetNotificationsWS( 2734): onServiceConnected()
D/GetNotificationsWS( 2734): onServiceConnected(): Registered for remote service callbacks...
,I/PushService( 2734): started with background data enabled, making sure notification mechanism is enabled
,D/OtaApp  ( 2734): [debug] > Receive intent: com.motorola.blur.service.blur.Actions.UPGRADE_UPDATE_NOTIFICATION
,D/OtaApp  ( 2734): [debug] > UpdateReceiver: Received true from doSanityCheck.
D/OtaApp  ( 2734): [debug] > In cancelAnyPendingIntentSetPreviously
,I/ActivityManager(  891): START u0 {act=com.motorola.blur.service.blur.Actions.UPGRADE_UPDATE_NOTIFICATION flg=0x30000000 cmp=com.motorola.ccc.ota/.ui.DownloadActivity (has extras)} from uid 10000 on display 0
,I/Launcher( 1582): Deferring update until onResume
,W/ContextImpl( 1477): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,D/GetNotificationsWS( 2734): unbindWebServices(): un-registering our AIDL callback...
,W/ContextImpl( 1477): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,D/OtaApp  ( 2734): [debug] > DownloadActivity, FormattedText
I/OtaApp  ( 2734): [info] > DownloadActivity, handling (Blur_Version.22.46.12.thea_reteu.reteuall.en.EU) from ( upgrade)
D/Checkin ( 2734): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 2734): [debug] > cancelling the previous pending intent set for download later
,I/OtaApp  ( 2734): [info] > next automatic download prompt (serverAnnoy)  is scheduled in : 60 mins.
,D/Checkin ( 2734): publish the event [tag = MOT_OTA event name = LOG]
,I/GCoreNlp( 1751): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,D/OtaApp  ( 2734): [debug] > DownloadActivity, FormattedText
,I/OtaApp  ( 2734): [info] > DownloadActivity, handling (Blur_Version.22.46.12.thea_reteu.reteuall.en.EU) from ( upgrade)
,D/Checkin ( 2734): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 2734): [debug] > cancelling the previous pending intent set for download later
,I/OtaApp  ( 2734): [info] > next automatic download prompt (serverAnnoy)  is scheduled in : 60 mins.
,D/Checkin ( 2734): publish the event [tag = MOT_OTA event name = LOG]
,I/Keyboard.Facilitator( 1428): onFinishInput()
W/IInputConnectionWrapper( 6632): showStatusIcon on inactive InputConnection
,I/LaunchCheckinHandler(  891): Displayed com.motorola.ccc.ota/.ui.DownloadActivity,wp,wa,162
,V/AlarmManager(  891): done {105d1aec, *walarm*:com.google.android.intent.action.GCM_RECONNECT} [8636ms]
,I/ActivityManager(  891): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.util.GservicesChangedReceiver: pid=7746 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,D/PhoneMonitor( 7746): Register our PhoneStateListener
,V/SetupWizard( 7746): Connected to Gservices successfully
,I/ActivityManager(  891): Killing 7548:com.google.android.talk/u0a70 (adj 15): empty #7
,W/libprocessgroup(  891): failed to open /acct/uid_10070/pid_7548/cgroup.procs: No such file or directory
,D/GCM     ( 1751): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/ActivityManager(  891): Start proc com.google.android.apps.photos for broadcast com.google.android.apps.photos/.jobqueue.JobServiceBroadcastReceiverInternal: pid=7770 uid=10088 gids={50088, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:33000 mC
,D/GCM     ( 1751): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/ActivityManager(  891): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.GmsPackageWatcher: pid=7794 uid=10039 gids={50039, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
,I/ActivityManager(  891): Killing 7578:com.google.android.apps.magazines/u0a81 (adj 15): empty #7
,W/libprocessgroup(  891): failed to open /acct/uid_10081/pid_7578/cgroup.procs: No such file or directory
,I/ActivityManager(  891): Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=7816 uid=10019 gids={50019, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  891): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver: pid=7833 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/ActivityManager(  891): Killing 7653:com.android.chrome/u0a52 (adj 15): empty #7
,I/ActivityManager(  891): Killing 7680:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,W/libprocessgroup(  891): failed to open /acct/uid_10052/pid_7653/cgroup.procs: No such file or directory
,W/libprocessgroup(  891): failed to open /acct/uid_10090/pid_7680/cgroup.procs: No such file or directory
,W/ResourcesManager( 7833): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/Babel_SMS( 7833): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 7833): MmsConfig.loadMmsSettings
I/Babel_SMS( 7833): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
I/Babel_SMS( 7833): MmsConfig.loadFromDatabase
,E/Babel_SMS( 7833): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 7833): MmsConfig.loadFromResources
,E/Babel_SMS( 7833): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel_SMS( 7833): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/Settings( 7833): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 7833): startup - clean
,I/Babel   ( 7833): deleted: false for 0
,I/ActivityManager(  891): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=7866 uid=10027 gids={50027, 9997, 1023, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  891): Killing 7770:com.google.android.apps.photos/u0a88 (adj 15): empty #7
,W/VideoCapabilities( 7833): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 7833): Unsupported mime audio/amr-wb-plus
,W/VideoCapabilities( 7833): Unsupported mime video/mpeg2
,I/VideoCapabilities( 7833): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 7833): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7833): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7833): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7833): Unrecognized profile 2130706433 for video/avc
,W/libprocessgroup(  891): failed to open /acct/uid_10088/pid_7770/cgroup.procs: No such file or directory
,W/asset   ( 7866): Asset path /system/framework/com.motorola.gallery is neither a directory nor file (type=1).
W/ResourcesManager( 7866): Asset path '/system/framework/com.motorola.gallery' does not exist or contains no resources.
W/ResourcesManager( 7866): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 7866): Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
,D/PackageBroadcastService( 1971): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 1971): Null package name or gms related package.  Ignoreing.
,I/Icing   ( 1971): updateResources: need to parse f{com.google.android.gms}
,W/Launcher( 1582): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@a65b48c new=com.google.android.velvet.VelvetApplication@a65b48c
,I/UpdateIcingCorporaServi( 7794): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,I/ActivityManager(  891): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=7899 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/vclib   ( 7833): onServiceConnected
,W/Babel   ( 7833): Attempted to change video mute state without an active call.
,W/ResourcesManager( 7833): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7833): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,W/ResourcesManager( 7899): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,V/JNIHelp ( 7833): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/UpdateIcingCorporaServi( 7794): UpdateCorporaTask done [took 153 ms] updated apps [took 153 ms] 
,W/System  ( 7833): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7833): Installed default security provider GmsCore_OpenSSL
,I/art     (  891): Explicit concurrent mark sweep GC freed 17804(889KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 20MB/30MB, paused 1.602ms total 121.720ms
,I/ActivityManager(  891): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=7931 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  891): Killing 7746:com.google.android.setupwizard/u0a35 (adj 15): empty #7
,W/libprocessgroup(  891): failed to open /acct/uid_10035/pid_7746/cgroup.procs: No such file or directory
,D/Finsky  ( 7931): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/Finsky  ( 7931): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 7931): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 7931): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/Finsky  ( 7931): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 7931): [1] Libraries$2.run: Finished loading 1 libraries.
,D/Ads     ( 7931): Skipping gmscore version check
,I/ActivityManager(  891): Killing 7816:com.google.android.partnersetup/u0a19 (adj 15): empty #7
,W/libprocessgroup(  891): failed to open /acct/uid_10019/pid_7816/cgroup.procs: No such file or directory
,D/Finsky  ( 7931): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/Finsky  ( 7931): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,D/TaskPersister(  891): removeObsoleteFile: deleting file=5_task.xml
,I/Icing   ( 1971): Indexing 5905AFFF7E2D60BB1F87C8D56D40BA6B258244BF from com.google.android.gms
,I/Icing   ( 1971): Indexing done 5905AFFF7E2D60BB1F87C8D56D40BA6B258244BF
,I/ActivityManager(  891): Killing 7866:com.motorola.MotGallery2/u0a27 (adj 15): empty #7
,W/libprocessgroup(  891): failed to open /acct/uid_10027/pid_7866/cgroup.procs: No such file or directory
,D/BatteryService(  891): uevent={POWER_SUPPLY_TEMP=297, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4310558, SEQNUM=4475, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-6510, POWER_SUPPLY_CHARGE_COUNTER=-708, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2587): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2587): Disconnected process message: 10, size: 0
,I/ActivityManager(  891): Killing 7794:com.google.android.googlequicksearchbox:search/u0a39 (adj 15): empty #7
,W/libprocessgroup(  891): failed to open /acct/uid_10039/pid_7794/cgroup.procs: No such file or directory
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:32000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:32000 mC
,D/BatteryService(  891): uevent={POWER_SUPPLY_TEMP=284, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4310909, SEQNUM=4483, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-4807, POWER_SUPPLY_CHARGE_COUNTER=-744, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2587): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2587): Disconnected process message: 10, size: 0
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:31000 mC
,I/ClearcutLoggerApiImpl( 1751): disconnect managed GoogleApiClient
,V/AlarmManager(  891): send {3e840b5, *walarm*:com.google.android.gms/.checkin.CheckinService$Receiver}
,V/AlarmManager(  891): send {1e571e01, *walarm*:com.android.server.task.controllers.BatteryController.ACTION_CHARGING_STABLE}
,V/AlarmManager(  891): done {3e840b5, *walarm*:com.google.android.gms/.checkin.CheckinService$Receiver} [18ms]
,V/AlarmManager(  891): done {1e571e01, *walarm*:com.android.server.task.controllers.BatteryController.ACTION_CHARGING_STABLE} [19ms]
,I/CheckinService( 1971): Checkin interval check for package: unspecified last checkin: 1453044914866 min interval config: 0 actual interval: 40305
,I/CheckinService( 1971): Checking schedule, now: 1453044955183 next: 1453044944827
I/CheckinService( 1971): active receiver: enabled
,I/CheckinService( 1971): Preparing to send checkin request
I/EventLogService( 1971): Accumulating logs since 1453044910339
,I/CheckinRequestBuilder( 1971): Checkin reason type: 12 attempt count: 1
,E/ActivityThread( 1971): Failed to find provider info for com.google.android.wearable.settings
,V/GLSActivity( 1751): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1751): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  891): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=8018 uid=10016 gids={50016, 9997, 3003, 1028, 1015, 3002, 3001, 1005, 1007, 3007, 2001, 3006} abi=armeabi-v7a
,W/ResourcesManager( 8018): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 8018): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/MultiDex( 8018): VM with version 2.1.0 has multidex support
I/MultiDex( 8018): install
I/MultiDex( 8018): VM has multidex support, MultiDex support library is disabled.
,V/JNIHelp ( 8018): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 8018): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 8018): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@12f5f397: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 8018): Installed default security provider GmsCore_OpenSSL
,D/WearableService( 1751): callingUid 10016, callindPid: 1751
,E/MDM     ( 1751): [199] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
D/AuthorizationBluetoothService( 1751): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
D/LocationInitializer( 1971): Restart initialization of location
,V/GLSActivity( 1751): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GCoreFlp( 1751): No location to return for getLastLocation()
,W/FusedLocationProvider( 1751): location=null
,I/art     ( 8018): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 8018): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,D/NativeLibraryUtils( 8018): Install completed successfully. count=14 extracted=0
,D/WVCdm   (  294): Instantiating CDM.
I/WVCdm   (  294): CdmEngine::OpenSession
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
D/DrmWidevineDash(  294): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4ff5000
E/DrmWidevineDash(  294): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4ff5000
,D/DrmWidevineDash(  294): OEMCrypto_Initialize: ends! returns 0
D/DrmWidevineDash(  294): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  294): hlos api version =  9
D/DrmWidevineDash(  294): tz api version =  8
D/DrmWidevineDash(  294): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  294): OEMCrypto_IsKeyboxValid: starts!
,D/DrmWidevineDash(  294): OEMCrypto_IsKeyboxValid: ends! returns 0
D/WVCdm   (  294): OEMCrypto_Initialize Level 1 success. I will use level 1.
D/DrmWidevineDash(  294): OEMCrypto_OpenSession: starts! SID=0xb55c9960
,D/DrmWidevineDash(  294): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  294): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  294): OEMCrypto_GetRandom: starts! randomData=0xb7ca55e8, dataLength=8
D/DrmWidevineDash(  294): OEMCrypto_GetRandom: ends! returns 0
D/DrmWidevineDash(  294): OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb7c8da78, wrapped_rsa_key_length=1280
,D/DrmWidevineDash(  294): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
,I/WVCdm   (  294): CdmEngine::QueryKeyControlInfo
W/WVCdm   (  294): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  294): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  294): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  294): OEMCrypto_GetDeviceID: starts! deviceID=0xb7ce7dc0, idLength=0xb13df730
,D/DrmWidevineDash(  294): OEMCrypto_GetDeviceID: ends! returns 0
D/DrmWidevineDash(  294): OEMCrypto_SupportsUsageTable: starts!
D/DrmWidevineDash(  294): OEMCrypto_SupportsUsageTable: is_supported = 1
D/DrmWidevineDash(  294): OEMCrypto_SupportsUsageTable: wv_app_version = 25
D/DrmWidevineDash(  294): OEMCrypto_SupportsUsageTable: ends! returns 0x0
D/DrmWidevineDash(  294): OEMCrypto_GetHDCPCapability: starts!
,D/DrmWidevineDash(  294): OEMCrypto_GetHDCPCapability: ends! returns 0x0
D/DrmWidevineDash(  294): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  294): hlos api version =  9
D/DrmWidevineDash(  294): tz api version =  8
D/DrmWidevineDash(  294): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  294): OEMCrypto_GenerateNonce: starts! SID=1
D/DrmWidevineDash(  294): OEMCrypto_GenerateNonce: ends! returns 0
D/WVCdm   (  294): PrepareKeyRequest: nonce=4109075259
D/DrmWidevineDash(  294): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb7c9c4e8
D/DrmWidevineDash(  294): message_length=1591, signature=0xb7c16638, signature_length=2973628180
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
D/DrmWidevineDash(  294): OEMCrypto_Terminate: ends! returns 0
,I/dex2oat ( 8052): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=28 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,I/dex2oat ( 8052): dex2oat took 76.328ms (threads: 4)
,I/Adreno-EGL( 8018): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 8018): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 8018): Build Date: 10/28/14 Tue
I/Adreno-EGL( 8018): Local Branch: 
I/Adreno-EGL( 8018): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 8018): Local Patches: NONE
I/Adreno-EGL( 8018): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/Adreno-EGL( 8018): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 8018): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 8018): Build Date: 10/28/14 Tue
I/Adreno-EGL( 8018): Local Branch: 
I/Adreno-EGL( 8018): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 8018): Local Patches: NONE
I/Adreno-EGL( 8018): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/Adreno-EGL( 8018): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 8018): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 8018): Build Date: 10/28/14 Tue
I/Adreno-EGL( 8018): Local Branch: 
I/Adreno-EGL( 8018): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 8018): Local Patches: NONE
I/Adreno-EGL( 8018): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/Adreno-EGL( 8018): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 8018): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 8018): Build Date: 10/28/14 Tue
I/Adreno-EGL( 8018): Local Branch: 
I/Adreno-EGL( 8018): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 8018): Local Patches: NONE
I/Adreno-EGL( 8018): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/WVCdm   (  294): CdmEngine::OpenSession
I/WVCdm   (  294): Level3 Library Sep 25 2014 17:10:03
W/WVCdm   (  294): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
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
D/DrmWidevineDash(  294): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4ff5000
E/DrmWidevineDash(  294): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4ff5000
,D/DrmWidevineDash(  294): OEMCrypto_Initialize: ends! returns 0
D/DrmWidevineDash(  294): OEMCrypto_APIVersion: starts!
,D/DrmWidevineDash(  294): hlos api version =  9
,D/DrmWidevineDash(  294): tz api version =  8
,D/DrmWidevineDash(  294): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  294): OEMCrypto_IsKeyboxValid: starts!
,D/DrmWidevineDash(  294): OEMCrypto_IsKeyboxValid: ends! returns 0
D/WVCdm   (  294): OEMCrypto_Initialize Level 1 success. I will use level 1.
D/DrmWidevineDash(  294): OEMCrypto_OpenSession: starts! SID=0xb12df960
D/DrmWidevineDash(  294): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  294): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  294): OEMCrypto_GetRandom: starts! randomData=0xb7cb1358, dataLength=8
,D/DrmWidevineDash(  294): OEMCrypto_GetRandom: ends! returns 0
,D/DrmWidevineDash(  294): OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb7c8da78, wrapped_rsa_key_length=1280
,D/DrmWidevineDash(  294): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
I/WVCdm   (  294): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  294): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  294): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  294): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  294): OEMCrypto_GetDeviceID: starts! deviceID=0xb7ce7de0, idLength=0xbe8ed2b0
,D/DrmWidevineDash(  294): OEMCrypto_GetDeviceID: ends! returns 0
D/DrmWidevineDash(  294): OEMCrypto_SupportsUsageTable: starts!
,D/DrmWidevineDash(  294): OEMCrypto_SupportsUsageTable: is_supported = 1
,D/DrmWidevineDash(  294): OEMCrypto_SupportsUsageTable: wv_app_version = 25
D/DrmWidevineDash(  294): OEMCrypto_SupportsUsageTable: ends! returns 0x0
,D/DrmWidevineDash(  294): OEMCrypto_GetHDCPCapability: starts!
,D/DrmWidevineDash(  294): OEMCrypto_GetHDCPCapability: ends! returns 0x0
,D/DrmWidevineDash(  294): OEMCrypto_APIVersion: starts!
,D/DrmWidevineDash(  294): hlos api version =  9
,D/DrmWidevineDash(  294): tz api version =  8
D/DrmWidevineDash(  294): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  294): OEMCrypto_GenerateNonce: starts! SID=1
D/DrmWidevineDash(  294): OEMCrypto_GenerateNonce: ends! returns 0
D/WVCdm   (  294): PrepareKeyRequest: nonce=3551902740
D/DrmWidevineDash(  294): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb7c9c4e8
D/DrmWidevineDash(  294): message_length=1626, signature=0xb7c16658, signature_length=3197031060
,D/DrmWidevineDash(  294): OEMCrypto_GenerateRSASignature returns 0
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
,I/CheckinRequestBuilder( 1971): Classify the device as Phone.
,I/CheckinTask( 1971): Sending checkin request (9513 bytes)
,I/CheckinRequestBuilder( 1971): Checkin reason type: 12 attempt count: 1
,E/ActivityThread( 1971): Failed to find provider info for com.google.android.wearable.settings
,I/CheckinRequestBuilder( 1971): Classify the device as Phone.
,I/CheckinTask( 1971): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 1971): Checking schedule, now: 1453044959296 next: 1453646096287
I/CheckinService( 1971): active receiver: disabled
,D/CheckinService( 1971): Recording last checkin time for package unspecified as 1453044959315
,I/ActivityManager(  891): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.util.GservicesChangedReceiver: pid=8089 uid=10035 gids={50035, 9997, 3003} abi=armeabi-v7a
,D/PhoneMonitor( 8089): Register our PhoneStateListener
,V/SetupWizard( 8089): Connected to Gservices successfully
,D/GCM     ( 1751): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/ActivityManager(  891): Killing 7899:com.google.android.apps.plus/u0a90 (adj 13): empty #7
,I/ActivityManager(  891): Killing 7706:android.process.acore/u0a7 (adj 15): empty #8
,W/libprocessgroup(  891): failed to open /acct/uid_10090/pid_7899/cgroup.procs: No such file or directory
,W/libprocessgroup(  891): failed to open /acct/uid_10007/pid_7706/cgroup.procs: No such file or directory
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:31000 mC
,I/InputReader(  891): Reconfiguring input devices.  changes=0x00000010
,I/ActivityManager(  891): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.GmsPackageWatcher: pid=8119 uid=10039 gids={50039, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
,I/art     (  309): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 246us total 22.379ms
,I/art     (  309): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 243us total 19.143ms
,I/art     (  309): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 272us total 20.412ms
,D/BackupManagerService(  891): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/BackupManagerService(  891): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,I/BackupManagerService(  891): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/BackupManagerService(  891): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/BackupManagerService(  891): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@23143aaa
,I/GCoreNlp( 1751): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,I/Launcher( 1582): Deferring update until onResume
,I/art     (  891): Explicit concurrent mark sweep GC freed 20647(1095KB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 20MB/30MB, paused 1.718ms total 125.101ms
,I/ActivityManager(  891): Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=8152 uid=10019 gids={50019, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  891): Start proc android.process.acore for broadcast com.android.providers.contacts/.PackageIntentReceiver: pid=8171 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,I/ActivityManager(  891): Killing 7931:com.android.vending/u0a32 (adj 15): empty #7
,W/libprocessgroup(  891): failed to open /acct/uid_10032/pid_7931/cgroup.procs: No such file or directory
,W/ResourcesManager( 7833): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7833): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/ContactLocale( 8171): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,I/ActivityManager(  891): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=8194 uid=10027 gids={50027, 9997, 1023, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  891): Killing 8089:com.google.android.setupwizard/u0a35 (adj 15): empty #7
,W/libprocessgroup(  891): failed to open /acct/uid_10035/pid_8089/cgroup.procs: No such file or directory
,W/asset   ( 8194): Asset path /system/framework/com.motorola.gallery is neither a directory nor file (type=1).
W/ResourcesManager( 8194): Asset path '/system/framework/com.motorola.gallery' does not exist or contains no resources.
W/ResourcesManager( 8194): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 8194): Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
,D/PackageBroadcastService( 1971): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 1971): Null package name or gms related package.  Ignoreing.
,W/Launcher( 1582): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@a65b48c new=com.google.android.velvet.VelvetApplication@a65b48c
,I/UpdateIcingCorporaServi( 8119): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,I/Icing   ( 1971): updateResources: need to parse f{com.google.android.gms}
,I/ActivityManager(  891): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=8219 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,W/ResourcesManager( 8219): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/UpdateIcingCorporaServi( 8119): UpdateCorporaTask done [took 142 ms] updated apps [took 142 ms] 
,I/ActivityManager(  891): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=8245 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  891): Killing 8018:com.google.android.gms.unstable/u0a16 (adj 15): empty #7
,W/libprocessgroup(  891): failed to open /acct/uid_10016/pid_8018/cgroup.procs: No such file or directory
,D/Finsky  ( 8245): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/Finsky  ( 8245): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 8245): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 8245): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/Finsky  ( 8245): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Ads     ( 8245): Skipping gmscore version check
D/Finsky  ( 8245): [1] Libraries$2.run: Finished loading 1 libraries.
,D/Finsky  ( 8245): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/Finsky  ( 8245): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/ActivityManager(  891): Killing 8152:com.google.android.partnersetup/u0a19 (adj 15): empty #7
,W/libprocessgroup(  891): failed to open /acct/uid_10019/pid_8152/cgroup.procs: No such file or directory
,I/Icing   ( 1971): Indexing 5905AFFF7E2D60BB1F87C8D56D40BA6B258244BF from com.google.android.gms
,I/Icing   ( 1971): Indexing done 5905AFFF7E2D60BB1F87C8D56D40BA6B258244BF
,I/ActivityManager(  891): Killing 8194:com.motorola.MotGallery2/u0a27 (adj 15): empty #7
,W/libprocessgroup(  891): failed to open /acct/uid_10027/pid_8194/cgroup.procs: No such file or directory
,I/ActivityManager(  891): Killing 7833:com.google.android.talk/u0a70 (adj 15): empty #7
,W/libprocessgroup(  891): failed to open /acct/uid_10070/pid_7833/cgroup.procs: No such file or directory
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:31000 mC
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
,I/Keyboard.Facilitator.LanguageModelFlusher( 1428): run()
I/Keyboard.Facilitator( 1428): flushDynamicLanguageModels()
,I/ConfigService( 1751): onCreate
,I/art     ( 1751): Explicit concurrent mark sweep GC freed 98726(5MB) AllocSpace objects, 27(455KB) LOS objects, 40% free, 15MB/25MB, paused 1.452ms total 118.273ms
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:31000 mC
,I/ConfigService( 1751): onDestroy
,D/BatteryService(  891): uevent={POWER_SUPPLY_TEMP=277, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4310806, SEQNUM=4503, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-4807, POWER_SUPPLY_CHARGE_COUNTER=-822, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2587): Disconnected process message: 10, size: 0
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:30000 mC
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
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:30000 mC
,I/jxcore-log( 6632): TAP version 13
I/jxcore-log( 6632): 
,I/jxcore-log( 6632): # setup
I/jxcore-log( 6632): 
,I/jxcore-log( 6632): # multiplex can send data
I/jxcore-log( 6632): 
,I/jxcore-log( 6632): # teardown
I/jxcore-log( 6632): 
,I/jxcore-log( 6632): ok 1 String should be length:200
I/jxcore-log( 6632): 
,I/jxcore-log( 6632): # setup
I/jxcore-log( 6632): 
,I/jxcore-log( 6632): # basic
I/jxcore-log( 6632): 
,I/jxcore-log( 6632): # teardown
I/jxcore-log( 6632): 
,I/jxcore-log( 6632): ok 2 sane
I/jxcore-log( 6632): 
,I/jxcore-log( 6632): # setup
I/jxcore-log( 6632): 
,I/jxcore-log( 6632): # another
I/jxcore-log( 6632): 
,I/jxcore-log( 6632): # teardown
I/jxcore-log( 6632): 
,I/jxcore-log( 6632): ok 3 sane
I/jxcore-log( 6632): 
,I/jxcore-log( 6632): # setup
I/jxcore-log( 6632): 
,I/jxcore-log( 6632): # successfully create a new pkcs12 file and return hash value
I/jxcore-log( 6632): 
,I/jxcore-log( 6632): # teardown
I/jxcore-log( 6632): 
,I/jxcore-log( 6632): ok 4 should be equal
I/jxcore-log( 6632): 
,I/jxcore-log( 6632): ok 5 null
I/jxcore-log( 6632): 
,I/jxcore-log( 6632): ok 6 (unnamed assert)
I/jxcore-log( 6632): 
,I/jxcore-log( 6632): ok 7 should be equal
I/jxcore-log( 6632): 
,I/jxcore-log( 6632): ok 8 should not throw
I/jxcore-log( 6632): 
,I/jxcore-log( 6632): # setup
I/jxcore-log( 6632): 
,I/jxcore-log( 6632): # successfully read a previous pkcs12 file and return hash value
I/jxcore-log( 6632): 
,I/jxcore-log( 6632): # teardown
I/jxcore-log( 6632): 
,I/jxcore-log( 6632): ok 9 (unnamed assert)
I/jxcore-log( 6632): 
,I/jxcore-log( 6632): ok 10 (unnamed assert)
I/jxcore-log( 6632): 
,I/jxcore-log( 6632): ok 11 should not throw
I/jxcore-log( 6632): 
,I/jxcore-log( 6632): ok 12 should be equal
I/jxcore-log( 6632): 
,I/jxcore-log( 6632): ok 13 should be equal
I/jxcore-log( 6632): 
,I/jxcore-log( 6632): # setup
I/jxcore-log( 6632): 
,I/jxcore-log( 6632): # failed to extract public key because of corrupt pkcs12 file
I/jxcore-log( 6632): 
,I/jxcore-log( 6632): # teardown
I/jxcore-log( 6632): 
,I/jxcore-log( 6632): ok 14 should be equal
I/jxcore-log( 6632): 
,I/jxcore-log( 6632): # setup
I/jxcore-log( 6632): 
,I/jxcore-log( 6632): # failed to get mobile documents path
I/jxcore-log( 6632): 
,I/jxcore-log( 6632): # teardown
I/jxcore-log( 6632): 
,I/jxcore-log( 6632): ok 15 should be equal
I/jxcore-log( 6632): 
,I/jxcore-log( 6632): # setup
I/jxcore-log( 6632): 
,I/jxcore-log( 6632): # #init should register the peerAvailabilityChanged event
I/jxcore-log( 6632): 
,I/jxcore-log( 6632): # teardown
I/jxcore-log( 6632): 
,I/jxcore-log( 6632): ok 16 should be equal
I/jxcore-log( 6632): 
,I/jxcore-log( 6632): ok 17 should be equal
I/jxcore-log( 6632): 
,I/jxcore-log( 6632): ok 18 should be equal
I/jxcore-log( 6632): 
,I/jxcore-log( 6632): # setup
I/jxcore-log( 6632): 
,I/jxcore-log( 6632): # #init should register the networkChanged event
I/jxcore-log( 6632): 
,I/jxcore-log( 6632): # teardown
I/jxcore-log( 6632): 
,I/jxcore-log( 6632): ok 19 should be equal
I/jxcore-log( 6632): 
,I/jxcore-log( 6632): # setup
I/jxcore-log( 6632): 
,I/jxcore-log( 6632): # #startBroadcasting should throw on null device name
I/jxcore-log( 6632): 
,I/jxcore-log( 6632): # teardown
I/jxcore-log( 6632): 
,I/jxcore-log( 6632): ok 20 should throw
I/jxcore-log( 6632): 
,I/jxcore-log( 6632): # setup
I/jxcore-log( 6632): 
,I/jxcore-log( 6632): # #startBroadcasting should throw on empty string device name
I/jxcore-log( 6632): 
,I/jxcore-log( 6632): # teardown
I/jxcore-log( 6632): 
,I/jxcore-log( 6632): ok 21 should throw
I/jxcore-log( 6632): 
,I/jxcore-log( 6632): # setup
I/jxcore-log( 6632): 
,I/jxcore-log( 6632): # #startBroadcasting should throw on non-number port
I/jxcore-log( 6632): 
,I/jxcore-log( 6632): # teardown
I/jxcore-log( 6632): 
,I/jxcore-log( 6632): ok 22 should throw
I/jxcore-log( 6632): 
,I/jxcore-log( 6632): # setup
I/jxcore-log( 6632): 
,I/jxcore-log( 6632): # #startBroadcasting should throw on NaN port
I/jxcore-log( 6632): 
,I/jxcore-log( 6632): # teardown
I/jxcore-log( 6632): 
,I/jxcore-log( 6632): ok 23 should throw
I/jxcore-log( 6632): 
,I/jxcore-log( 6632): # setup
I/jxcore-log( 6632): 
,I/jxcore-log( 6632): # #startBroadcasting should throw on negative port
I/jxcore-log( 6632): 
,I/jxcore-log( 6632): # teardown
I/jxcore-log( 6632): 
,I/jxcore-log( 6632): ok 24 should throw
I/jxcore-log( 6632): 
,I/jxcore-log( 6632): # setup
I/jxcore-log( 6632): 
,I/jxcore-log( 6632): # #startBroadcasting should throw on too large port
I/jxcore-log( 6632): 
,I/jxcore-log( 6632): # teardown
I/jxcore-log( 6632): 
,I/jxcore-log( 6632): ok 25 should throw
I/jxcore-log( 6632): 
,I/jxcore-log( 6632): # setup
I/jxcore-log( 6632): 
,I/jxcore-log( 6632): # #startBroadcasting should call Mobile("StartBroadcasting") without an error
I/jxcore-log( 6632): 
,I/jxcore-log( 6632): # teardown
I/jxcore-log( 6632): 
,I/jxcore-log( 6632): ok 26 should be equal
I/jxcore-log( 6632): 
,I/jxcore-log( 6632): ok 27 should be equal
I/jxcore-log( 6632): 
,I/jxcore-log( 6632): ok 28 should be equal
I/jxcore-log( 6632): 
,I/jxcore-log( 6632): # setup
I/jxcore-log( 6632): 
,I/jxcore-log( 6632): # #startBroadcasting should call Mobile("StartBroadcasting") and handle an error
I/jxcore-log( 6632): 
,I/jxcore-log( 6632): # teardown
I/jxcore-log( 6632): 
,I/jxcore-log( 6632): ok 29 should be equal
I/jxcore-log( 6632): 
,I/jxcore-log( 6632): ok 30 should be equal
I/jxcore-log( 6632): 
,I/jxcore-log( 6632): ok 31 should be equal
I/jxcore-log( 6632): 
,I/jxcore-log( 6632): # setup
I/jxcore-log( 6632): 
,I/jxcore-log( 6632): # #stopBroadcasting should call Mobile("StopBroadcasting") without an error
I/jxcore-log( 6632): 
,I/jxcore-log( 6632): # teardown
I/jxcore-log( 6632): 
,I/jxcore-log( 6632): ok 32 should be equal
I/jxcore-log( 6632): 
,I/jxcore-log( 6632): ok 33 should be equal
I/jxcore-log( 6632): 
,I/jxcore-log( 6632): # setup
I/jxcore-log( 6632): 
,I/jxcore-log( 6632): # #stopBroadcasting should call Mobile("StopBroadcasting") and handle an error
I/jxcore-log( 6632): 
,I/jxcore-log( 6632): # teardown
I/jxcore-log( 6632): 
,I/jxcore-log( 6632): ok 34 should be equal
I/jxcore-log( 6632): 
I/jxcore-log( 6632): ok 35 should be equal
I/jxcore-log( 6632): 
,I/jxcore-log( 6632): # setup
I/jxcore-log( 6632): 
,I/jxcore-log( 6632): # #connect should call Mobile("Connect") with a port and without an error
I/jxcore-log( 6632): 
,I/jxcore-log( 6632): # teardown
I/jxcore-log( 6632): 
,I/jxcore-log( 6632): ok 36 should be equal
I/jxcore-log( 6632): 
I/jxcore-log( 6632): ok 37 should be equal
I/jxcore-log( 6632): 
I/jxcore-log( 6632): ok 38 should be equal
I/jxcore-log( 6632): 
,I/jxcore-log( 6632): # setup
I/jxcore-log( 6632): 
,I/jxcore-log( 6632): # #connect should call Mobile("Connect") and handle an error
I/jxcore-log( 6632): 
,I/jxcore-log( 6632): # teardown
I/jxcore-log( 6632): 
,I/jxcore-log( 6632): ok 39 should be equal
I/jxcore-log( 6632): 
,I/jxcore-log( 6632): ok 40 should be equal
I/jxcore-log( 6632): 
,I/jxcore-log( 6632): # setup
I/jxcore-log( 6632): 
,I/jxcore-log( 6632): # should call Mobile("Disconnect") without an error
I/jxcore-log( 6632): 
,I/jxcore-log( 6632): # teardown
I/jxcore-log( 6632): 
,I/jxcore-log( 6632): ok 41 should be equal
I/jxcore-log( 6632): 
I/jxcore-log( 6632): ok 42 should be equal
I/jxcore-log( 6632): 
,I/jxcore-log( 6632): # setup
I/jxcore-log( 6632): 
,I/jxcore-log( 6632): # should call Mobile("Disconnect") and handle an error
I/jxcore-log( 6632): 
,I/jxcore-log( 6632): # teardown
I/jxcore-log( 6632): 
,I/jxcore-log( 6632): ok 43 should be equal
I/jxcore-log( 6632): 
I/jxcore-log( 6632): ok 44 should be equal
I/jxcore-log( 6632): 
,I/jxcore-log( 6632): # setup
I/jxcore-log( 6632): 
,I/jxcore-log( 6632): # ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error
I/jxcore-log( 6632): 
,I/jxcore-log( 6632): # teardown
I/jxcore-log( 6632): 
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6632): setDiscoveryMode: Mode set to BLE
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6632): setDiscoveryMode: Mode set to BLE_AND_WIFI
,D/BluetoothManagerService(  891): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6632): start: Peer ID: 44:80:EB:7B:5A:05, peer name: 1453045035381.6632
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6632): bind: Binding a new listener
,D/BluetoothManagerService(  891): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6632): initialize: My bluetooth address is 44:80:EB:7B:5A:05
,D/BluetoothManagerService(  891): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6632): verifyIdentityString: Identity string created: {"pi":"44:80:EB:7B:5A:05","pn":"1453045035381.6632","ra":"44:80:EB:7B:5A:05"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6632): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6632): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6632): startListeningForIncomingConnections: Starting...
,D/BluetoothManagerService(  891): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 6632): getBluetoothService() called with no BluetoothManagerCallback
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6632): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6632): start: OK
I/io.jxcore.node.ConnectionHelper( 6632): start: Using peer discovery mode: BLE_AND_WIFI
,D/BluetoothManagerService(  891): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6632): start: Peer ID: 44:80:EB:7B:5A:05, peer name: 1453045035381.6632
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6632): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6632): bind: Binding a new listener
,D/BluetoothManagerService(  891): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6632): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 6632): setAdvertiseSettings: Mode: 1, Tx power level: 1, timeout: 0, is connectable: true
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 6632): createAdvertiseData: From: 1453045035381.6632 b6a44ad1-d319-4b3a-815d-8b805a47fb51 44:80:EB:7B:5A:05
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 6632): 44:80:EB:7B:5A:5
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 6632): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, 68, -128, -21, 123, 90, 5]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 6632): setScanSettings: Mode: 1, report delay in milliseconds: 0, scan result type: 0
,D/BtGatt.GattService( 2587): registerClient() - UUID=ce8590d2-3e10-4d26-a685-8c1c472a8d99
,D/BtGatt.GattService( 2587): onClientRegistered() - UUID=ce8590d2-3e10-4d26-a685-8c1c472a8d99, clientIf=5
,D/BluetoothLeAdvertiser( 6632): onClientRegistered() - status=0 clientIf=5
,D/BtGatt.AdvertiseManager( 2587): message : 0
,D/BtGatt.AdvertiseManager( 2587): starting single advertising
,D/BtGatt.GattService( 2587): onAdvertiseCallback,- clientIf=5, status=0
,E/bt-btif ( 2587): Listen For All now
,D/BtGatt.GattService( 2587): registerClient() - UUID=0af03e54-ac52-439b-a107-23846dfdfa6f
D/BtGatt.GattService( 2587): onClientRegistered() - UUID=0af03e54-ac52-439b-a107-23846dfdfa6f, clientIf=6
,D/BluetoothLeScanner( 6632): onClientRegistered() - status=0 clientIf=6
,D/BtGatt.GattService( 2587): start scan with filters
,D/BtGatt.ScanManager( 2587): handling starting scan
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6632): startBlePeerDiscovery: OK
,D/BluetoothManagerService(  891): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6632): verifyIdentityString: Identity string created: {"pi":"44:80:EB:7B:5A:05","pn":"1453045035381.6632","ra":"44:80:EB:7B:5A:05"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6632): start: {"pi":"44:80:EB:7B:5A:05","pn":"1453045035381.6632","ra":"44:80:EB:7B:5A:05"}
D/BtGatt.ScanManager( 2587): configureRegularScanParams() - queue=1
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6632): start: Identity string: "{"pi":"44:80:EB:7B:5A:05","pn":"1453045035381.6632","ra":"44:80:EB:7B:5A:05"}", service type: "Cordovap2p._tcp"
D/BtGatt.ScanManager( 2587): configureRegularScanParams() - ScanSetting Scan mode=1 mLastConfiguredScanSetting=-2147483648
,D/WifiP2pService(  891): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@8400340c target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  891): P2pEnabledState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@8400340c target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  891): P2pEnabledState add service
,D/WifiP2pService(  891): add a new client
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6632): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6632): start: Starting P2P device discovery...
,D/WifiP2pService(  891): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6632): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6632): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6632): start: OK
D/WifiP2pService(  891): P2pEnabledState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6632): setState: RUNNING_BLE_AND_WIFI
I/io.jxcore.node.ConnectionHelper( 6632): start: OK
I/wpa_supplicant( 1420): p2p0: CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-SCAN-STARTED 
D/MDMCTBK (  292): Event received = CTRL-EVENT-SCAN-STARTED 
I/jxcore-log( 6632): ok 45 Should be able to call startBroadcasting without error
I/jxcore-log( 6632): 
,D/WifiP2pService(  891): discovery change broadcast true
I/io.jxcore.node.ConnectionHelper( 6632): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6632): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6632): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6632): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6632): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6632): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6632): onServerStopped
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6632): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6632): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6632): stop: Stopping peer discovery...
,D/BtGatt.AdvertiseManager( 2587): message : 1
,D/BtGatt.AdvertiseManager( 2587): stop advertise for client 5
D/BtGatt.GattService( 2587): onAdvertiseCallback,- clientIf=5, status=0
,D/BtGatt.GattService( 2587): onAdvertiseInstanceDisabled() - clientIf=5, status=0
D/BtGatt.GattService( 2587): Client app is not null!
,D/BtGatt.GattService( 2587): unregisterClient() - clientIf=5
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 6632): onIsAdvertiserStartedChanged: false
,D/BtGatt.GattService( 2587): stopScan() - queue size =1
D/BtGatt.ScanManager( 2587): stop scan
,D/BtGatt.ScanManager( 2587): configureRegularScanParams() - queue=0
D/BtGatt.ScanManager( 2587): configureRegularScanParams() - ScanSetting Scan mode=-2147483648 mLastConfiguredScanSetting=1
,D/BtGatt.ScanManager( 2587): configureRegularScanParams() - queue emtpy, scan stopped
,D/BtGatt.GattService( 2587): unregisterClient() - clientIf=6
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 6632): onIsScannerStartedChanged: false
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 6632): setIsStarted: true
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6632): onIsBlePeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6632): stopBlePeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6632): stop: Stopping services
,D/WifiP2pService(  891): InactiveState{ when=0 what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  891): P2pEnabledState{ when=0 what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  891): P2pEnabledState clear service
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6632): stop: Stopping P2P device discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6632): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6632): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6632): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6632): release: No more listeners, de-initializing...
D/WifiP2pService(  891): remove client information from framework
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6632): release: No more listeners, de-initializing...
,D/WifiP2pService(  891): InactiveState{ when=0 what=139268 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 1420): P2P-FIND-STOPPED 
D/MDMCTBK (  292): reply_len: 40 reply is = <3>P2P-FIND-STOPPED 
D/MDMCTBK (  292): Event received = P2P-FIND-STOPPED 
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6632): setState: NOT_STARTED
,I/jxcore-log( 6632): ok 46 Should be able to call stopBroadcasting without error
I/jxcore-log( 6632): 
D/WifiP2pService(  891): InactiveState{ when=-4ms what=139307 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  891): P2pEnabledState{ when=-4ms what=139307 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  891): P2pEnabledState clear service request
D/WifiP2pService(  891): InactiveState{ when=-4ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  891): P2pEnabledState{ when=-4ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  891): discovery change broadcast false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6632): setDiscoveryMode: Mode set to BLE
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6632): setDiscoveryMode: Mode set to BLE_AND_WIFI
,D/BluetoothManagerService(  891): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6632): start: Peer ID: 44:80:EB:7B:5A:05, peer name: 1453045035656.6632
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6632): bind: Binding a new listener
,D/BluetoothManagerService(  891): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6632): initialize: My bluetooth address is 44:80:EB:7B:5A:05
,D/BluetoothManagerService(  891): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6632): verifyIdentityString: Identity string created: {"pi":"44:80:EB:7B:5A:05","pn":"1453045035656.6632","ra":"44:80:EB:7B:5A:05"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6632): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6632): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6632): startListeningForIncomingConnections: Starting...
,D/BluetoothManagerService(  891): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 6632): getBluetoothService() called with no BluetoothManagerCallback
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6632): setState: RUNNING
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6632): start: OK
I/io.jxcore.node.ConnectionHelper( 6632): start: Using peer discovery mode: BLE_AND_WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6632): Waiting for incoming connections...
,D/BluetoothManagerService(  891): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6632): start: Peer ID: 44:80:EB:7B:5A:05, peer name: 1453045035656.6632
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6632): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6632): bind: Binding a new listener
,D/BluetoothManagerService(  891): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 6632): setAdvertiseSettings: Mode: 1, Tx power level: 1, timeout: 0, is connectable: true
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 6632): createAdvertiseData: From: 1453045035656.6632 b6a44ad1-d319-4b3a-815d-8b805a47fb51 44:80:EB:7B:5A:05
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 6632): 44:80:EB:7B:5A:5
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 6632): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, 68, -128, -21, 123, 90, 5]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 6632): setScanSettings: Mode: 1, report delay in milliseconds: 0, scan result type: 0
,D/BtGatt.GattService( 2587): registerClient() - UUID=76d349fe-b021-4b41-8b2b-eb820ab15cde
D/BtGatt.GattService( 2587): onClientRegistered() - UUID=76d349fe-b021-4b41-8b2b-eb820ab15cde, clientIf=5
,D/BluetoothLeAdvertiser( 6632): onClientRegistered() - status=0 clientIf=5
,D/BtGatt.AdvertiseManager( 2587): message : 0
,D/BtGatt.AdvertiseManager( 2587): starting single advertising
,E/bt-btif ( 2587): Listen For All now
,D/BtGatt.GattService( 2587): onAdvertiseCallback,- clientIf=5, status=0
,D/BtGatt.GattService( 2587): registerClient() - UUID=3ea1f196-5ad7-4247-9c5f-e0d59492130f
D/BtGatt.GattService( 2587): onClientRegistered() - UUID=3ea1f196-5ad7-4247-9c5f-e0d59492130f, clientIf=6
,D/BluetoothLeScanner( 6632): onClientRegistered() - status=0 clientIf=6
D/BtGatt.GattService( 2587): start scan with filters
,D/BtGatt.ScanManager( 2587): handling starting scan
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6632): startBlePeerDiscovery: OK
,D/BtGatt.ScanManager( 2587): configureRegularScanParams() - queue=1
D/BtGatt.ScanManager( 2587): configureRegularScanParams() - ScanSetting Scan mode=1 mLastConfiguredScanSetting=-2147483648
,D/BluetoothManagerService(  891): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6632): verifyIdentityString: Identity string created: {"pi":"44:80:EB:7B:5A:05","pn":"1453045035656.6632","ra":"44:80:EB:7B:5A:05"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6632): start: {"pi":"44:80:EB:7B:5A:05","pn":"1453045035656.6632","ra":"44:80:EB:7B:5A:05"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6632): start: Identity string: "{"pi":"44:80:EB:7B:5A:05","pn":"1453045035656.6632","ra":"44:80:EB:7B:5A:05"}", service type: "Cordovap2p._tcp"
,D/WifiP2pService(  891): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@137d3bc2 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  891): P2pEnabledState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@137d3bc2 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  891): P2pEnabledState add service
D/WifiP2pService(  891): add a new client
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6632): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6632): start: Starting P2P device discovery...
,D/WifiP2pService(  891): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  891): P2pEnabledState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 1420): p2p0: P2P: Reject scan trigger since one is already pending
,D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P: Reject scan trigger 
D/MDMCTBK (  292): Event received = P2P: Reject scan trigger 
,D/WifiP2pService(  891): discovery change broadcast true
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6632): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6632): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6632): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6632): setState: RUNNING_BLE_AND_WIFI
I/io.jxcore.node.ConnectionHelper( 6632): start: OK
,I/jxcore-log( 6632): ok 47 Should be able to call startBroadcasting without error
I/jxcore-log( 6632): 
I/io.jxcore.node.ConnectionHelper( 6632): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6632): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6632): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6632): stopListeningForIncomingConnections: Stopping...
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6632): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6632): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6632): onServerStopped
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6632): release: 1 listener(s) left
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6632): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6632): stop: Stopping peer discovery...
,D/BtGatt.AdvertiseManager( 2587): message : 1
,D/BtGatt.AdvertiseManager( 2587): stop advertise for client 5
,D/BtGatt.GattService( 2587): onAdvertiseCallback,- clientIf=5, status=0
D/BtGatt.GattService( 2587): onAdvertiseInstanceDisabled() - clientIf=5, status=0
D/BtGatt.GattService( 2587): Client app is not null!
,D/BtGatt.GattService( 2587): unregisterClient() - clientIf=5
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 6632): onIsAdvertiserStartedChanged: false
,D/BtGatt.GattService( 2587): stopScan() - queue size =1
,D/BtGatt.ScanManager( 2587): stop scan
D/BtGatt.ScanManager( 2587): configureRegularScanParams() - queue=0
D/BtGatt.ScanManager( 2587): configureRegularScanParams() - ScanSetting Scan mode=-2147483648 mLastConfiguredScanSetting=1
D/BtGatt.ScanManager( 2587): configureRegularScanParams() - queue emtpy, scan stopped
,D/BtGatt.GattService( 2587): unregisterClient() - clientIf=6
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 6632): onIsScannerStartedChanged: false
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 6632): setIsStarted: true
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6632): onIsBlePeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6632): stopBlePeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6632): stop: Stopping services
D/WifiP2pService(  891): InactiveState{ when=0 what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  891): P2pEnabledState{ when=-1ms what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  891): P2pEnabledState clear service
,D/WifiP2pService(  891): remove client information from framework
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6632): stop: Stopping P2P device discovery...
,D/WifiP2pService(  891): InactiveState{ when=0 what=139268 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 1420): P2P-FIND-STOPPED 
,D/MDMCTBK (  292): reply_len: 40 reply is = <3>P2P-FIND-STOPPED 
D/MDMCTBK (  292): Event received = P2P-FIND-STOPPED 
,D/WifiP2pService(  891): InactiveState{ when=-2ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  891): P2pEnabledState{ when=-3ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  891): discovery change broadcast false
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6632): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6632): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6632): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6632): release: No more listeners, de-initializing...
,D/WifiP2pService(  891): InactiveState{ when=0 what=139307 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  891): P2pEnabledState{ when=0 what=139307 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  891): P2pEnabledState clear service request
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6632): release: No more listeners, de-initializing...
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6632): setState: NOT_STARTED
,I/jxcore-log( 6632): ok 48 Should be able to call stopBroadcasting without error
I/jxcore-log( 6632): 
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6632): setDiscoveryMode: Mode set to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6632): setDiscoveryMode: Mode set to BLE_AND_WIFI
,D/BluetoothManagerService(  891): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6632): start: Peer ID: 44:80:EB:7B:5A:05, peer name: 1453045035742.6632
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6632): bind: Binding a new listener
D/BluetoothManagerService(  891): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6632): initialize: My bluetooth address is 44:80:EB:7B:5A:05
,D/BluetoothManagerService(  891): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6632): verifyIdentityString: Identity string created: {"pi":"44:80:EB:7B:5A:05","pn":"1453045035742.6632","ra":"44:80:EB:7B:5A:05"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6632): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6632): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6632): startListeningForIncomingConnections: Starting...
D/BluetoothManagerService(  891): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 6632): getBluetoothService() called with no BluetoothManagerCallback
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6632): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6632): start: OK
I/io.jxcore.node.ConnectionHelper( 6632): start: Using peer discovery mode: BLE_AND_WIFI
D/BluetoothManagerService(  891): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6632): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6632): start: Peer ID: 44:80:EB:7B:5A:05, peer name: 1453045035742.6632
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6632): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6632): bind: Binding a new listener
,D/BluetoothManagerService(  891): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 6632): setAdvertiseSettings: Mode: 1, Tx power level: 1, timeout: 0, is connectable: true
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 6632): createAdvertiseData: From: 1453045035742.6632 b6a44ad1-d319-4b3a-815d-8b805a47fb51 44:80:EB:7B:5A:05
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 6632): 44:80:EB:7B:5A:5
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 6632): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, 68, -128, -21, 123, 90, 5]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 6632): setScanSettings: Mode: 1, report delay in milliseconds: 0, scan result type: 0
,D/BtGatt.GattService( 2587): registerClient() - UUID=94a0651f-54b8-485a-8a3d-ddb4de97fb14
,D/BtGatt.GattService( 2587): onClientRegistered() - UUID=94a0651f-54b8-485a-8a3d-ddb4de97fb14, clientIf=5
D/BluetoothLeAdvertiser( 6632): onClientRegistered() - status=0 clientIf=5
,D/BtGatt.AdvertiseManager( 2587): message : 0
,D/BtGatt.AdvertiseManager( 2587): starting single advertising
,E/bt-btif ( 2587): Listen For All now
D/BtGatt.GattService( 2587): onAdvertiseCallback,- clientIf=5, status=0
,D/BtGatt.GattService( 2587): registerClient() - UUID=fdf00afb-718a-4fb9-8240-d42444e389a8
,D/BtGatt.GattService( 2587): onClientRegistered() - UUID=fdf00afb-718a-4fb9-8240-d42444e389a8, clientIf=6
D/BluetoothLeScanner( 6632): onClientRegistered() - status=0 clientIf=6
D/BtGatt.GattService( 2587): start scan with filters
,D/BtGatt.ScanManager( 2587): handling starting scan
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6632): startBlePeerDiscovery: OK
,D/BtGatt.ScanManager( 2587): configureRegularScanParams() - queue=1
,D/BtGatt.ScanManager( 2587): configureRegularScanParams() - ScanSetting Scan mode=1 mLastConfiguredScanSetting=-2147483648
D/BluetoothManagerService(  891): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6632): verifyIdentityString: Identity string created: {"pi":"44:80:EB:7B:5A:05","pn":"1453045035742.6632","ra":"44:80:EB:7B:5A:05"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6632): start: {"pi":"44:80:EB:7B:5A:05","pn":"1453045035742.6632","ra":"44:80:EB:7B:5A:05"}
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6632): start: Identity string: "{"pi":"44:80:EB:7B:5A:05","pn":"1453045035742.6632","ra":"44:80:EB:7B:5A:05"}", service type: "Cordovap2p._tcp"
D/WifiP2pService(  891): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@3cd69f4a target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  891): P2pEnabledState{ when=-1ms what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@3cd69f4a target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  891): P2pEnabledState add service
D/WifiP2pService(  891): add a new client
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6632): setState: INITIALIZED
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6632): start: Starting P2P device discovery...
D/WifiP2pService(  891): InactiveState{ when=-1ms what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  891): P2pEnabledState{ when=-1ms what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 1420): p2p0: P2P: Reject scan trigger since one is already pending
D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P: Reject scan trigger 
D/MDMCTBK (  292): Event received = P2P: Reject scan trigger 
D/WifiP2pService(  891): discovery change broadcast true
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6632): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6632): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6632): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6632): setState: RUNNING_BLE_AND_WIFI
I/io.jxcore.node.ConnectionHelper( 6632): start: OK
,I/jxcore-log( 6632): ok 49 Should be able to call startBroadcasting without error
I/jxcore-log( 6632): 
,I/io.jxcore.node.ConnectionHelper( 6632): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6632): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6632): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6632): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6632): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6632): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6632): onServerStopped
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6632): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6632): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6632): stop: Stopping peer discovery...
D/BtGatt.AdvertiseManager( 2587): message : 1
D/BtGatt.AdvertiseManager( 2587): stop advertise for client 5
D/BtGatt.GattService( 2587): onAdvertiseCallback,- clientIf=5, status=0
D/BtGatt.GattService( 2587): onAdvertiseInstanceDisabled() - clientIf=5, status=0
D/BtGatt.GattService( 2587): Client app is not null!
D/BtGatt.GattService( 2587): unregisterClient() - clientIf=5
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 6632): onIsAdvertiserStartedChanged: false
D/BtGatt.GattService( 2587): stopScan() - queue size =1
D/BtGatt.ScanManager( 2587): stop scan
D/BtGatt.ScanManager( 2587): configureRegularScanParams() - queue=0
D/BtGatt.ScanManager( 2587): configureRegularScanParams() - ScanSetting Scan mode=-2147483648 mLastConfiguredScanSetting=1
D/BtGatt.ScanManager( 2587): configureRegularScanParams() - queue emtpy, scan stopped
D/BtGatt.GattService( 2587): unregisterClient() - clientIf=6
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 6632): onIsScannerStartedChanged: false
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 6632): setIsStarted: true
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6632): onIsBlePeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6632): stopBlePeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6632): stop: Stopping services
D/WifiP2pService(  891): InactiveState{ when=0 what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  891): P2pEnabledState{ when=0 what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  891): P2pEnabledState clear service
D/WifiP2pService(  891): remove client information from framework
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6632): stop: Stopping P2P device discovery...
D/WifiP2pService(  891): InactiveState{ when=0 what=139268 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 1420): P2P-FIND-STOPPED 
D/MDMCTBK (  292): reply_len: 40 reply is = <3>P2P-FIND-STOPPED 
D/MDMCTBK (  292): Event received = P2P-FIND-STOPPED 
D/WifiP2pService(  891): InactiveState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  891): P2pEnabledState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  891): discovery change broadcast false
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6632): setState: NOT_INITIALIZED
D/WifiP2pService(  891): InactiveState{ when=0 what=139307 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  891): P2pEnabledState{ when=-1ms what=139307 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  891): P2pEnabledState clear service request
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6632): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6632): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6632): release: No more listeners, de-initializing...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6632): release: No more listeners, de-initializing...
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6632): setState: NOT_STARTED
I/jxcore-log( 6632): ok 50 Should be able to call stopBroadcasting without error
I/jxcore-log( 6632): 
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6632): setDiscoveryMode: Mode set to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6632): setDiscoveryMode: Mode set to BLE_AND_WIFI
D/BluetoothManagerService(  891): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6632): start: Peer ID: 44:80:EB:7B:5A:05, peer name: 1453045035801.6632
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6632): bind: Binding a new listener
D/BluetoothManagerService(  891): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6632): initialize: My bluetooth address is 44:80:EB:7B:5A:05
D/BluetoothManagerService(  891): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6632): verifyIdentityString: Identity string created: {"pi":"44:80:EB:7B:5A:05","pn":"1453045035801.6632","ra":"44:80:EB:7B:5A:05"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6632): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6632): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6632): startListeningForIncomingConnections: Starting...
D/BluetoothManagerService(  891): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 6632): getBluetoothService() called with no BluetoothManagerCallback
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6632): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6632): start: OK
I/io.jxcore.node.ConnectionHelper( 6632): start: Using peer discovery mode: BLE_AND_WIFI
D/BluetoothManagerService(  891): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6632): Waiting for incoming connections...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6632): start: Peer ID: 44:80:EB:7B:5A:05, peer name: 1453045035801.6632
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6632): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6632): bind: Binding a new listener
D/BluetoothManagerService(  891): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 6632): setAdvertiseSettings: Mode: 1, Tx power level: 1, timeout: 0, is connectable: true
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 6632): createAdvertiseData: From: 1453045035801.6632 b6a44ad1-d319-4b3a-815d-8b805a47fb51 44:80:EB:7B:5A:05
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 6632): 44:80:EB:7B:5A:5
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 6632): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, 68, -128, -21, 123, 90, 5]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 6632): setScanSettings: Mode: 1, report delay in milliseconds: 0, scan result type: 0
D/BtGatt.GattService( 2587): registerClient() - UUID=044f6b08-fb9f-4f34-951a-24f00a4ee2ab
D/BtGatt.GattService( 2587): onClientRegistered() - UUID=044f6b08-fb9f-4f34-951a-24f00a4ee2ab, clientIf=5
D/BluetoothLeAdvertiser( 6632): onClientRegistered() - status=0 clientIf=5
D/BtGatt.AdvertiseManager( 2587): message : 0
D/BtGatt.AdvertiseManager( 2587): starting single advertising
E/bt-btif ( 2587): Listen For All now
D/BtGatt.GattService( 2587): onAdvertiseCallback,- clientIf=5, status=0
D/BtGatt.GattService( 2587): registerClient() - UUID=0c035b75-a275-401b-9331-bae4772ccada
D/BtGatt.GattService( 2587): onClientRegistered() - UUID=0c035b75-a275-401b-9331-bae4772ccada, clientIf=6
D/BluetoothLeScanner( 6632): onClientRegistered() - status=0 clientIf=6
D/BtGatt.GattService( 2587): start scan with filters
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6632): startBlePeerDiscovery: OK
D/BtGatt.ScanManager( 2587): handling starting scan
D/BluetoothManagerService(  891): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6632): verifyIdentityString: Identity string created: {"pi":"44:80:EB:7B:5A:05","pn":"1453045035801.6632","ra":"44:80:EB:7B:5A:05"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6632): start: {"pi":"44:80:EB:7B:5A:05","pn":"1453045035801.6632","ra":"44:80:EB:7B:5A:05"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6632): start: Identity string: "{"pi":"44:80:EB:7B:5A:05","pn":"1453045035801.6632","ra":"44:80:EB:7B:5A:05"}", service type: "Cordovap2p._tcp"
D/BtGatt.ScanManager( 2587): configureRegularScanParams() - queue=1
D/BtGatt.ScanManager( 2587): configureRegularScanParams() - ScanSetting Scan mode=1 mLastConfiguredScanSetting=-2147483648
D/WifiP2pService(  891): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@d3f80952 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  891): P2pEnabledState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@d3f80952 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  891): P2pEnabledState add service
D/WifiP2pService(  891): add a new client
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6632): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6632): start: Starting P2P device discovery...
D/WifiP2pService(  891): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  891): P2pEnabledState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 1420): p2p0: P2P: Reject scan trigger since one is already pending
D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P: Reject scan trigger 
,D/MDMCTBK (  292): Event received = P2P: Reject scan trigger 
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6632): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6632): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6632): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6632): setState: RUNNING_BLE_AND_WIFI
I/io.jxcore.node.ConnectionHelper( 6632): start: OK
D/WifiP2pService(  891): discovery change broadcast true
I/jxcore-log( 6632): ok 51 Should be able to call startBroadcasting without error
I/jxcore-log( 6632): 
I/io.jxcore.node.ConnectionHelper( 6632): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6632): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6632): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6632): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6632): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6632): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6632): onServerStopped
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6632): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6632): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6632): stop: Stopping peer discovery...
D/BtGatt.AdvertiseManager( 2587): message : 1
D/BtGatt.AdvertiseManager( 2587): stop advertise for client 5
D/BtGatt.GattService( 2587): onAdvertiseInstanceDisabled() - clientIf=5, status=0
D/BtGatt.GattService( 2587): Client app is not null!
D/BtGatt.GattService( 2587): onAdvertiseCallback,- clientIf=5, status=0
D/BtGatt.GattService( 2587): unregisterClient() - clientIf=5
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 6632): onIsAdvertiserStartedChanged: false
D/BtGatt.GattService( 2587): stopScan() - queue size =1
D/BtGatt.ScanManager( 2587): stop scan
D/BtGatt.ScanManager( 2587): configureRegularScanParams() - queue=0
D/BtGatt.ScanManager( 2587): configureRegularScanParams() - ScanSetting Scan mode=-2147483648 mLastConfiguredScanSetting=1
D/BtGatt.ScanManager( 2587): configureRegularScanParams() - queue emtpy, scan stopped
D/BtGatt.GattService( 2587): unregisterClient() - clientIf=6
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 6632): onIsScannerStartedChanged: false
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 6632): setIsStarted: true
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6632): onIsBlePeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6632): stopBlePeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6632): stop: Stopping services
D/WifiP2pService(  891): InactiveState{ when=0 what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  891): P2pEnabledState{ when=0 what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  891): P2pEnabledState clear service
D/WifiP2pService(  891): remove client information from framework
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6632): stop: Stopping P2P device discovery...
D/WifiP2pService(  891): InactiveState{ when=0 what=139268 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 1420): P2P-FIND-STOPPED 
D/MDMCTBK (  292): reply_len: 40 reply is = <3>P2P-FIND-STOPPED 
D/MDMCTBK (  292): Event received = P2P-FIND-STOPPED 
D/WifiP2pService(  891): InactiveState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  891): P2pEnabledState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  891): discovery change broadcast false
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6632): setState: NOT_INITIALIZED
D/WifiP2pService(  891): InactiveState{ when=0 what=139307 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  891): P2pEnabledState{ when=0 what=139307 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  891): P2pEnabledState clear service request
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6632): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6632): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6632): release: No more listeners, de-initializing...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6632): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6632): setState: NOT_STARTED
I/jxcore-log( 6632): ok 52 Should be able to call stopBroadcasting without error
I/jxcore-log( 6632): 
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6632): setDiscoveryMode: Mode set to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6632): setDiscoveryMode: Mode set to BLE_AND_WIFI
D/BluetoothManagerService(  891): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6632): start: Peer ID: 44:80:EB:7B:5A:05, peer name: 1453045035854.6632
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6632): bind: Binding a new listener
D/BluetoothManagerService(  891): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6632): initialize: My bluetooth address is 44:80:EB:7B:5A:05
D/BluetoothManagerService(  891): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6632): verifyIdentityString: Identity string created: {"pi":"44:80:EB:7B:5A:05","pn":"1453045035854.6632","ra":"44:80:EB:7B:5A:05"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6632): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6632): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6632): startListeningForIncomingConnections: Starting...
D/BluetoothManagerService(  891): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 6632): getBluetoothService() called with no BluetoothManagerCallback
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6632): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6632): start: OK
I/io.jxcore.node.ConnectionHelper( 6632): start: Using peer discovery mode: BLE_AND_WIFI
D/BluetoothManagerService(  891): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6632): Waiting for incoming connections...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6632): start: Peer ID: 44:80:EB:7B:5A:05, peer name: 1453045035854.6632
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6632): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6632): bind: Binding a new listener
D/BluetoothManagerService(  891): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 6632): setAdvertiseSettings: Mode: 1, Tx power level: 1, timeout: 0, is connectable: true
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 6632): createAdvertiseData: From: 1453045035854.6632 b6a44ad1-d319-4b3a-815d-8b805a47fb51 44:80:EB:7B:5A:05
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 6632): 44:80:EB:7B:5A:5
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 6632): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, 68, -128, -21, 123, 90, 5]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 6632): setScanSettings: Mode: 1, report delay in milliseconds: 0, scan result type: 0
D/BtGatt.GattService( 2587): registerClient() - UUID=376b0a3e-7478-49f5-b99e-44f7eaa67638
D/BtGatt.GattService( 2587): onClientRegistered() - UUID=376b0a3e-7478-49f5-b99e-44f7eaa67638, clientIf=5
D/BluetoothLeAdvertiser( 6632): onClientRegistered() - status=0 clientIf=5
D/BtGatt.AdvertiseManager( 2587): message : 0
D/BtGatt.AdvertiseManager( 2587): starting single advertising
E/bt-btif ( 2587): Listen For All now
D/BtGatt.GattService( 2587): onAdvertiseCallback,- clientIf=5, status=0
D/BtGatt.GattService( 2587): registerClient() - UUID=6a300daf-c0c5-47ae-b50d-252b3ac70af3
D/BtGatt.GattService( 2587): onClientRegistered() - UUID=6a300daf-c0c5-47ae-b50d-252b3ac70af3, clientIf=6
D/BluetoothLeScanner( 6632): onClientRegistered() - status=0 clientIf=6
D/BtGatt.GattService( 2587): start scan with filters
D/BtGatt.ScanManager( 2587): handling starting scan
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6632): startBlePeerDiscovery: OK
D/BluetoothManagerService(  891): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6632): verifyIdentityString: Identity string created: {"pi":"44:80:EB:7B:5A:05","pn":"1453045035854.6632","ra":"44:80:EB:7B:5A:05"}
D/BtGatt.ScanManager( 2587): configureRegularScanParams() - queue=1
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6632): start: {"pi":"44:80:EB:7B:5A:05","pn":"1453045035854.6632","ra":"44:80:EB:7B:5A:05"}
D/BtGatt.ScanManager( 2587): configureRegularScanParams() - ScanSetting Scan mode=1 mLastConfiguredScanSetting=-2147483648
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6632): start: Identity string: "{"pi":"44:80:EB:7B:5A:05","pn":"1453045035854.6632","ra":"44:80:EB:7B:5A:05"}", service type: "Cordovap2p._tcp"
D/WifiP2pService(  891): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@b7b79dc2 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  891): P2pEnabledState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@b7b79dc2 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  891): P2pEnabledState add service
D/WifiP2pService(  891): add a new client
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6632): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6632): start: Starting P2P device discovery...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6632): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6632): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6632): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6632): setState: RUNNING_BLE_AND_WIFI
I/io.jxcore.node.ConnectionHelper( 6632): start: OK
D/WifiP2pService(  891): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  891): P2pEnabledState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 1420): p2p0: P2P: Reject scan trigger since one is already pending
D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P: Reject scan trigger 
D/MDMCTBK (  292): Event received = P2P: Reject scan trigger 
D/WifiP2pService(  891): discovery change broadcast true
I/jxcore-log( 6632): ok 53 Should be able to call startBroadcasting without error
I/jxcore-log( 6632): 
I/io.jxcore.node.ConnectionHelper( 6632): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6632): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6632): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6632): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6632): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6632): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6632): onServerStopped
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6632): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6632): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6632): stop: Stopping peer discovery...
D/BtGatt.AdvertiseManager( 2587): message : 1
D/BtGatt.AdvertiseManager( 2587): stop advertise for client 5
D/BtGatt.GattService( 2587): onAdvertiseCallback,- clientIf=5, status=0
D/BtGatt.GattService( 2587): onAdvertiseInstanceDisabled() - clientIf=5, status=0
D/BtGatt.GattService( 2587): Client app is not null!
D/BtGatt.GattService( 2587): unregisterClient() - clientIf=5
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 6632): onIsAdvertiserStartedChanged: false
D/BtGatt.GattService( 2587): stopScan() - queue size =1
D/BtGatt.ScanManager( 2587): stop scan
D/BtGatt.GattService( 2587): unregisterClient() - clientIf=6
D/BtGatt.ScanManager( 2587): configureRegularScanParams() - queue=0
D/BtGatt.ScanManager( 2587): configureRegularScanParams() - ScanSetting Scan mode=-2147483648 mLastConfiguredScanSetting=1
D/BtGatt.ScanManager( 2587): configureRegularScanParams() - queue emtpy, scan stopped
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 6632): onIsScannerStartedChanged: false
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 6632): setIsStarted: true
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6632): onIsBlePeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6632): stopBlePeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6632): stop: Stopping services
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6632): stop: Stopping P2P device discovery...
D/WifiP2pService(  891): InactiveState{ when=0 what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  891): P2pEnabledState{ when=0 what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  891): P2pEnabledState clear service
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6632): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6632): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6632): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6632): release: No more listeners, de-initializing...
D/WifiP2pService(  891): remove client information from framework
D/WifiP2pService(  891): InactiveState{ when=0 what=139268 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6632): release: No more listeners, de-initializing...
I/wpa_supplicant( 1420): P2P-FIND-STOPPED 
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6632): setState: NOT_STARTED
D/MDMCTBK (  292): reply_len: 40 reply is = <3>P2P-FIND-STOPPED 
D/MDMCTBK (  292): Event received = P2P-FIND-STOPPED 
D/WifiP2pService(  891): InactiveState{ when=-2ms what=139307 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  891): P2pEnabledState{ when=-2ms what=139307 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  891): P2pEnabledState clear service request
D/WifiP2pService(  891): InactiveState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  891): P2pEnabledState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  891): discovery change broadcast false
I/jxcore-log( 6632): ok 54 Should be able to call stopBroadcasting without error
I/jxcore-log( 6632): 
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6632): setDiscoveryMode: Mode set to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6632): setDiscoveryMode: Mode set to BLE_AND_WIFI
D/BluetoothManagerService(  891): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6632): start: Peer ID: 44:80:EB:7B:5A:05, peer name: 1453045035898.6632
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6632): bind: Binding a new listener
D/BluetoothManagerService(  891): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6632): initialize: My bluetooth address is 44:80:EB:7B:5A:05
D/BluetoothManagerService(  891): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6632): verifyIdentityString: Identity string created: {"pi":"44:80:EB:7B:5A:05","pn":"1453045035898.6632","ra":"44:80:EB:7B:5A:05"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6632): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6632): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6632): startListeningForIncomingConnections: Starting...
D/BluetoothManagerService(  891): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 6632): getBluetoothService() called with no BluetoothManagerCallback
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6632): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6632): start: OK
I/io.jxcore.node.ConnectionHelper( 6632): start: Using peer discovery mode: BLE_AND_WIFI
D/BluetoothManagerService(  891): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6632): Waiting for incoming connections...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6632): start: Peer ID: 44:80:EB:7B:5A:05, peer name: 1453045035898.6632
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6632): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6632): bind: Binding a new listener
D/BluetoothManagerService(  891): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 6632): setAdvertiseSettings: Mode: 1, Tx power level: 1, timeout: 0, is connectable: true
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 6632): createAdvertiseData: From: 1453045035898.6632 b6a44ad1-d319-4b3a-815d-8b805a47fb51 44:80:EB:7B:5A:05
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 6632): 44:80:EB:7B:5A:5
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 6632): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, 68, -128, -21, 123, 90, 5]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 6632): setScanSettings: Mode: 1, report delay in milliseconds: 0, scan result type: 0
D/BtGatt.GattService( 2587): registerClient() - UUID=d6ddbac3-869e-4d0f-8a23-72d469e6462e
D/BtGatt.GattService( 2587): onClientRegistered() - UUID=d6ddbac3-869e-4d0f-8a23-72d469e6462e, clientIf=5
D/BluetoothLeAdvertiser( 6632): onClientRegistered() - status=0 clientIf=5
D/BtGatt.AdvertiseManager( 2587): message : 0
,D/BtGatt.AdvertiseManager( 2587): starting single advertising
E/bt-btif ( 2587): Listen For All now
D/BtGatt.GattService( 2587): onAdvertiseCallback,- clientIf=5, status=0
D/BtGatt.GattService( 2587): registerClient() - UUID=2ede99e7-3c0e-4689-917b-488fbe8c7b3a
D/BtGatt.GattService( 2587): onClientRegistered() - UUID=2ede99e7-3c0e-4689-917b-488fbe8c7b3a, clientIf=6
D/BluetoothLeScanner( 6632): onClientRegistered() - status=0 clientIf=6
D/BtGatt.GattService( 2587): start scan with filters
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6632): startBlePeerDiscovery: OK
D/BtGatt.ScanManager( 2587): handling starting scan
D/BluetoothManagerService(  891): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6632): verifyIdentityString: Identity string created: {"pi":"44:80:EB:7B:5A:05","pn":"1453045035898.6632","ra":"44:80:EB:7B:5A:05"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6632): start: {"pi":"44:80:EB:7B:5A:05","pn":"1453045035898.6632","ra":"44:80:EB:7B:5A:05"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6632): start: Identity string: "{"pi":"44:80:EB:7B:5A:05","pn":"1453045035898.6632","ra":"44:80:EB:7B:5A:05"}", service type: "Cordovap2p._tcp"
D/BtGatt.ScanManager( 2587): configureRegularScanParams() - queue=1
D/BtGatt.ScanManager( 2587): configureRegularScanParams() - ScanSetting Scan mode=1 mLastConfiguredScanSetting=-2147483648
D/WifiP2pService(  891): InactiveState{ when=-1ms what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@156489b2 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  891): P2pEnabledState{ when=-1ms what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@156489b2 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  891): P2pEnabledState add service
D/WifiP2pService(  891): add a new client
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6632): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6632): start: Starting P2P device discovery...
D/WifiP2pService(  891): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  891): P2pEnabledState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6632): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6632): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6632): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6632): setState: RUNNING_BLE_AND_WIFI
I/io.jxcore.node.ConnectionHelper( 6632): start: OK
I/wpa_supplicant( 1420): p2p0: P2P: Reject scan trigger since one is already pending
D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P: Reject scan trigger 
D/MDMCTBK (  292): Event received = P2P: Reject scan trigger 
D/WifiP2pService(  891): discovery change broadcast true
I/jxcore-log( 6632): ok 55 Should be able to call startBroadcasting without error
I/jxcore-log( 6632): 
I/io.jxcore.node.ConnectionHelper( 6632): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6632): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6632): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6632): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6632): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6632): Exiting thread
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6632): release: 1 listener(s) left
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6632): onServerStopped
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6632): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6632): stop: Stopping peer discovery...
D/BtGatt.AdvertiseManager( 2587): message : 1
D/BtGatt.AdvertiseManager( 2587): stop advertise for client 5
D/BtGatt.GattService( 2587): onAdvertiseInstanceDisabled() - clientIf=5, status=0
D/BtGatt.GattService( 2587): Client app is not null!
D/BtGatt.GattService( 2587): onAdvertiseCallback,- clientIf=5, status=0
D/BtGatt.GattService( 2587): unregisterClient() - clientIf=5
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 6632): onIsAdvertiserStartedChanged: false
D/BtGatt.GattService( 2587): stopScan() - queue size =1
D/BtGatt.ScanManager( 2587): stop scan
D/BtGatt.ScanManager( 2587): configureRegularScanParams() - queue=0
D/BtGatt.ScanManager( 2587): configureRegularScanParams() - ScanSetting Scan mode=-2147483648 mLastConfiguredScanSetting=1
D/BtGatt.ScanManager( 2587): configureRegularScanParams() - queue emtpy, scan stopped
D/BtGatt.GattService( 2587): unregisterClient() - clientIf=6
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 6632): onIsScannerStartedChanged: false
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 6632): setIsStarted: true
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6632): onIsBlePeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6632): stopBlePeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6632): stop: Stopping services
D/WifiP2pService(  891): InactiveState{ when=0 what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  891): P2pEnabledState{ when=0 what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  891): P2pEnabledState clear service
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6632): stop: Stopping P2P device discovery...
D/WifiP2pService(  891): remove client information from framework
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6632): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6632): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6632): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6632): release: No more listeners, de-initializing...
D/WifiP2pService(  891): InactiveState{ when=0 what=139268 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 1420): P2P-FIND-STOPPED 
D/MDMCTBK (  292): reply_len: 40 reply is = <3>P2P-FIND-STOPPED 
D/MDMCTBK (  292): Event received = P2P-FIND-STOPPED 
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6632): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6632): setState: NOT_STARTED
D/WifiP2pService(  891): InactiveState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  891): P2pEnabledState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  891): discovery change broadcast false
D/WifiP2pService(  891): InactiveState{ when=0 what=139307 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  891): P2pEnabledState{ when=0 what=139307 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  891): P2pEnabledState clear service request
I/jxcore-log( 6632): ok 56 Should be able to call stopBroadcasting without error
I/jxcore-log( 6632): 
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6632): setDiscoveryMode: Mode set to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6632): setDiscoveryMode: Mode set to BLE_AND_WIFI
D/BluetoothManagerService(  891): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6632): start: Peer ID: 44:80:EB:7B:5A:05, peer name: 1453045035944.6632
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6632): bind: Binding a new listener
D/BluetoothManagerService(  891): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6632): initialize: My bluetooth address is 44:80:EB:7B:5A:05
D/BluetoothManagerService(  891): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6632): verifyIdentityString: Identity string created: {"pi":"44:80:EB:7B:5A:05","pn":"1453045035944.6632","ra":"44:80:EB:7B:5A:05"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6632): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6632): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6632): startListeningForIncomingConnections: Starting...
D/BluetoothManagerService(  891): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 6632): getBluetoothService() called with no BluetoothManagerCallback
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6632): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6632): start: OK
I/io.jxcore.node.ConnectionHelper( 6632): start: Using peer discovery mode: BLE_AND_WIFI
D/BluetoothManagerService(  891): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6632): Waiting for incoming connections...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6632): start: Peer ID: 44:80:EB:7B:5A:05, peer name: 1453045035944.6632
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6632): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6632): bind: Binding a new listener
D/BluetoothManagerService(  891): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 6632): setAdvertiseSettings: Mode: 1, Tx power level: 1, timeout: 0, is connectable: true
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 6632): createAdvertiseData: From: 1453045035944.6632 b6a44ad1-d319-4b3a-815d-8b805a47fb51 44:80:EB:7B:5A:05
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 6632): 44:80:EB:7B:5A:5
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 6632): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, 68, -128, -21, 123, 90, 5]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 6632): setScanSettings: Mode: 1, report delay in milliseconds: 0, scan result type: 0
,D/BtGatt.GattService( 2587): registerClient() - UUID=8498f717-c586-480c-9ef9-26d553e2afdc
,D/BtGatt.GattService( 2587): onClientRegistered() - UUID=8498f717-c586-480c-9ef9-26d553e2afdc, clientIf=5
D/BluetoothLeAdvertiser( 6632): onClientRegistered() - status=0 clientIf=5
D/BtGatt.AdvertiseManager( 2587): message : 0
,D/BtGatt.AdvertiseManager( 2587): starting single advertising
E/bt-btif ( 2587): Listen For All now
,D/BtGatt.GattService( 2587): onAdvertiseCallback,- clientIf=5, status=0
,D/BtGatt.GattService( 2587): registerClient() - UUID=83691e1d-aa43-4db2-ab61-b2bfb9ca2247
D/BtGatt.GattService( 2587): onClientRegistered() - UUID=83691e1d-aa43-4db2-ab61-b2bfb9ca2247, clientIf=6
,D/BluetoothLeScanner( 6632): onClientRegistered() - status=0 clientIf=6
D/BtGatt.GattService( 2587): start scan with filters
D/BtGatt.ScanManager( 2587): handling starting scan
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6632): startBlePeerDiscovery: OK
,D/BluetoothManagerService(  891): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/BtGatt.ScanManager( 2587): configureRegularScanParams() - queue=1
D/BtGatt.ScanManager( 2587): configureRegularScanParams() - ScanSetting Scan mode=1 mLastConfiguredScanSetting=-2147483648
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6632): verifyIdentityString: Identity string created: {"pi":"44:80:EB:7B:5A:05","pn":"1453045035944.6632","ra":"44:80:EB:7B:5A:05"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6632): start: {"pi":"44:80:EB:7B:5A:05","pn":"1453045035944.6632","ra":"44:80:EB:7B:5A:05"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6632): start: Identity string: "{"pi":"44:80:EB:7B:5A:05","pn":"1453045035944.6632","ra":"44:80:EB:7B:5A:05"}", service type: "Cordovap2p._tcp"
,D/WifiP2pService(  891): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@3c22642 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  891): P2pEnabledState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@3c22642 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  891): P2pEnabledState add service
,D/WifiP2pService(  891): add a new client
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6632): setState: INITIALIZED
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6632): start: Starting P2P device discovery...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6632): onIsWifiPeerDiscoveryStartedChanged: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6632): startWifiPeerDiscovery: Wi-Fi Direct OK
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6632): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6632): setState: RUNNING_BLE_AND_WIFI
I/io.jxcore.node.ConnectionHelper( 6632): start: OK
D/WifiP2pService(  891): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  891): P2pEnabledState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 1420): p2p0: P2P: Reject scan trigger since one is already pending
D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P: Reject scan trigger 
,D/MDMCTBK (  292): Event received = P2P: Reject scan trigger 
D/WifiP2pService(  891): discovery change broadcast true
I/jxcore-log( 6632): ok 57 Should be able to call startBroadcasting without error
I/jxcore-log( 6632): 
I/io.jxcore.node.ConnectionHelper( 6632): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6632): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6632): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6632): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6632): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6632): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6632): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6632): stop: Stopping peer discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6632): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6632): onServerStopped
D/BtGatt.AdvertiseManager( 2587): message : 1
D/BtGatt.AdvertiseManager( 2587): stop advertise for client 5
D/BtGatt.GattService( 2587): onAdvertiseCallback,- clientIf=5, status=0
D/BtGatt.GattService( 2587): onAdvertiseInstanceDisabled() - clientIf=5, status=0
D/BtGatt.GattService( 2587): Client app is not null!
,D/BtGatt.GattService( 2587): unregisterClient() - clientIf=5
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 6632): onIsAdvertiserStartedChanged: false
,D/BtGatt.GattService( 2587): stopScan() - queue size =1
D/BtGatt.ScanManager( 2587): stop scan
D/BtGatt.ScanManager( 2587): configureRegularScanParams() - queue=0
D/BtGatt.ScanManager( 2587): configureRegularScanParams() - ScanSetting Scan mode=-2147483648 mLastConfiguredScanSetting=1
D/BtGatt.ScanManager( 2587): configureRegularScanParams() - queue emtpy, scan stopped
D/BtGatt.GattService( 2587): unregisterClient() - clientIf=6
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 6632): onIsScannerStartedChanged: false
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 6632): setIsStarted: true
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6632): onIsBlePeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6632): stopBlePeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6632): stop: Stopping services
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6632): stop: Stopping P2P device discovery...
D/WifiP2pService(  891): InactiveState{ when=0 what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  891): P2pEnabledState{ when=0 what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6632): setState: NOT_INITIALIZED
,D/WifiP2pService(  891): P2pEnabledState clear service
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6632): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6632): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6632): release: No more listeners, de-initializing...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6632): release: No more listeners, de-initializing...
D/WifiP2pService(  891): remove client information from framework
D/WifiP2pService(  891): InactiveState{ when=0 what=139268 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 1420): P2P-FIND-STOPPED 
D/MDMCTBK (  292): reply_len: 40 reply is = <3>P2P-FIND-STOPPED 
D/MDMCTBK (  292): Event received = P2P-FIND-STOPPED 
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6632): setState: NOT_STARTED
,D/WifiP2pService(  891): InactiveState{ when=-2ms what=139307 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  891): P2pEnabledState{ when=-2ms what=139307 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  891): P2pEnabledState clear service request
D/WifiP2pService(  891): InactiveState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  891): P2pEnabledState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  891): discovery change broadcast false
I/jxcore-log( 6632): ok 58 Should be able to call stopBroadcasting without error
I/jxcore-log( 6632): 
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6632): setDiscoveryMode: Mode set to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6632): setDiscoveryMode: Mode set to BLE_AND_WIFI
D/BluetoothManagerService(  891): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6632): start: Peer ID: 44:80:EB:7B:5A:05, peer name: 1453045035994.6632
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6632): bind: Binding a new listener
D/BluetoothManagerService(  891): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6632): initialize: My bluetooth address is 44:80:EB:7B:5A:05
,D/BluetoothManagerService(  891): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6632): verifyIdentityString: Identity string created: {"pi":"44:80:EB:7B:5A:05","pn":"1453045035994.6632","ra":"44:80:EB:7B:5A:05"}
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6632): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6632): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6632): startListeningForIncomingConnections: Starting...
D/BluetoothManagerService(  891): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 6632): getBluetoothService() called with no BluetoothManagerCallback
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6632): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6632): start: OK
I/io.jxcore.node.ConnectionHelper( 6632): start: Using peer discovery mode: BLE_AND_WIFI
D/BluetoothManagerService(  891): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6632): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6632): start: Peer ID: 44:80:EB:7B:5A:05, peer name: 1453045035994.6632
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6632): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6632): bind: Binding a new listener
D/BluetoothManagerService(  891): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 6632): setAdvertiseSettings: Mode: 1, Tx power level: 1, timeout: 0, is connectable: true
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 6632): createAdvertiseData: From: 1453045035994.6632 b6a44ad1-d319-4b3a-815d-8b805a47fb51 44:80:EB:7B:5A:05
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 6632): 44:80:EB:7B:5A:5
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 6632): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, 68, -128, -21, 123, 90, 5]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 6632): setScanSettings: Mode: 1, report delay in milliseconds: 0, scan result type: 0
,D/BtGatt.GattService( 2587): registerClient() - UUID=61405da7-6f98-4163-9f06-1d9d5a11adae
,D/BtGatt.GattService( 2587): onClientRegistered() - UUID=61405da7-6f98-4163-9f06-1d9d5a11adae, clientIf=5
D/BluetoothLeAdvertiser( 6632): onClientRegistered() - status=0 clientIf=5
,D/BtGatt.AdvertiseManager( 2587): message : 0
,D/BtGatt.AdvertiseManager( 2587): starting single advertising
E/bt-btif ( 2587): Listen For All now
,D/BtGatt.GattService( 2587): onAdvertiseCallback,- clientIf=5, status=0
,D/BtGatt.GattService( 2587): registerClient() - UUID=800879b5-ca9d-4b7d-abab-f982dc080b7b
,D/BtGatt.GattService( 2587): onClientRegistered() - UUID=800879b5-ca9d-4b7d-abab-f982dc080b7b, clientIf=6
D/BluetoothLeScanner( 6632): onClientRegistered() - status=0 clientIf=6
D/BtGatt.GattService( 2587): start scan with filters
D/BtGatt.ScanManager( 2587): handling starting scan
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6632): startBlePeerDiscovery: OK
D/BluetoothManagerService(  891): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BtGatt.ScanManager( 2587): configureRegularScanParams() - queue=1
D/BtGatt.ScanManager( 2587): configureRegularScanParams() - ScanSetting Scan mode=1 mLastConfiguredScanSetting=-2147483648
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6632): verifyIdentityString: Identity string created: {"pi":"44:80:EB:7B:5A:05","pn":"1453045035994.6632","ra":"44:80:EB:7B:5A:05"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6632): start: {"pi":"44:80:EB:7B:5A:05","pn":"1453045035994.6632","ra":"44:80:EB:7B:5A:05"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6632): start: Identity string: "{"pi":"44:80:EB:7B:5A:05","pn":"1453045035994.6632","ra":"44:80:EB:7B:5A:05"}", service type: "Cordovap2p._tcp"
D/WifiP2pService(  891): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@4d7cdef8 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  891): P2pEnabledState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@4d7cdef8 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  891): P2pEnabledState add service
D/WifiP2pService(  891): add a new client
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6632): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6632): start: Starting P2P device discovery...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6632): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6632): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6632): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6632): setState: RUNNING_BLE_AND_WIFI
I/io.jxcore.node.ConnectionHelper( 6632): start: OK
D/WifiP2pService(  891): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  891): P2pEnabledState{ when=-1ms what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 1420): p2p0: P2P: Reject scan trigger since one is already pending
D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P: Reject scan trigger 
D/MDMCTBK (  292): Event received = P2P: Reject scan trigger 
D/WifiP2pService(  891): discovery change broadcast true
I/jxcore-log( 6632): ok 59 Should be able to call startBroadcasting without error
I/jxcore-log( 6632): 
I/io.jxcore.node.ConnectionHelper( 6632): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6632): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6632): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6632): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6632): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6632): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6632): onServerStopped
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6632): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6632): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6632): stop: Stopping peer discovery...
D/BtGatt.AdvertiseManager( 2587): message : 1
D/BtGatt.AdvertiseManager( 2587): stop advertise for client 5
D/BtGatt.GattService( 2587): onAdvertiseInstanceDisabled() - clientIf=5, status=0
D/BtGatt.GattService( 2587): Client app is not null!
D/BtGatt.GattService( 2587): onAdvertiseCallback,- clientIf=5, status=0
D/BtGatt.GattService( 2587): unregisterClient() - clientIf=5
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 6632): onIsAdvertiserStartedChanged: false
D/BtGatt.GattService( 2587): stopScan() - queue size =1
D/BtGatt.ScanManager( 2587): stop scan
D/BtGatt.ScanManager( 2587): configureRegularScanParams() - queue=0
D/BtGatt.GattService( 2587): unregisterClient() - clientIf=6
D/BtGatt.ScanManager( 2587): configureRegularScanParams() - ScanSetting Scan mode=-2147483648 mLastConfiguredScanSetting=1
D/BtGatt.ScanManager( 2587): configureRegularScanParams() - queue emtpy, scan stopped
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 6632): onIsScannerStartedChanged: false
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 6632): setIsStarted: true
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6632): onIsBlePeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6632): stopBlePeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6632): stop: Stopping services
,D/WifiP2pService(  891): InactiveState{ when=0 what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  891): P2pEnabledState{ when=0 what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  891): P2pEnabledState clear service
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6632): stop: Stopping P2P device discovery...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6632): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6632): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6632): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6632): release: No more listeners, de-initializing...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6632): release: No more listeners, de-initializing...
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6632): setState: NOT_STARTED
I/jxcore-log( 6632): ok 60 Should be able to call stopBroadcasting without error
I/jxcore-log( 6632): 
D/WifiP2pService(  891): remove client information from framework
D/WifiP2pService(  891): InactiveState{ when=0 what=139268 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 1420): P2P-FIND-STOPPED 
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6632): setDiscoveryMode: Mode set to BLE
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6632): setDiscoveryMode: Mode set to BLE_AND_WIFI
D/BluetoothManagerService(  891): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/MDMCTBK (  292): reply_len: 40 reply is = <3>P2P-FIND-STOPPED 
D/MDMCTBK (  292): Event received = P2P-FIND-STOPPED 
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6632): start: Peer ID: 44:80:EB:7B:5A:05, peer name: 1453045036041.6632
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6632): bind: Binding a new listener
,D/BluetoothManagerService(  891): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/WifiP2pService(  891): InactiveState{ when=-3ms what=139307 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  891): P2pEnabledState{ when=-4ms what=139307 arg2=5 target=com.android.internal.util.StateMachine$SmHandler },
D/WifiP2pService(  891): P2pEnabledState clear service request
D/WifiP2pService(  891): InactiveState{ when=-3ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  891): P2pEnabledState{ when=-3ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  891): discovery change broadcast false
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6632): initialize: My bluetooth address is 44:80:EB:7B:5A:05
,D/BluetoothManagerService(  891): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6632): verifyIdentityString: Identity string created: {"pi":"44:80:EB:7B:5A:05","pn":"1453045036041.6632","ra":"44:80:EB:7B:5A:05"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6632): setConnectionTimeout: 15000
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6632): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6632): startListeningForIncomingConnections: Starting...
D/BluetoothManagerService(  891): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 6632): getBluetoothService() called with no BluetoothManagerCallback
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6632): setState: RUNNING
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6632): start: OK
,I/io.jxcore.node.ConnectionHelper( 6632): start: Using peer discovery mode: BLE_AND_WIFI
D/BluetoothManagerService(  891): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6632): Waiting for incoming connections...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6632): start: Peer ID: 44:80:EB:7B:5A:05, peer name: 1453045036041.6632
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6632): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6632): bind: Binding a new listener
,D/BluetoothManagerService(  891): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 6632): setAdvertiseSettings: Mode: 1, Tx power level: 1, timeout: 0, is connectable: true
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 6632): createAdvertiseData: From: 1453045036041.6632 b6a44ad1-d319-4b3a-815d-8b805a47fb51 44:80:EB:7B:5A:05
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 6632): 44:80:EB:7B:5A:5
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 6632): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, 68, -128, -21, 123, 90, 5]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 6632): setScanSettings: Mode: 1, report delay in milliseconds: 0, scan result type: 0
,D/BtGatt.GattService( 2587): registerClient() - UUID=34468537-7fab-4a26-b866-25c6b9f139d4
D/BtGatt.GattService( 2587): onClientRegistered() - UUID=34468537-7fab-4a26-b866-25c6b9f139d4, clientIf=5
,D/BluetoothLeAdvertiser( 6632): onClientRegistered() - status=0 clientIf=5
D/BtGatt.AdvertiseManager( 2587): message : 0
,D/BtGatt.AdvertiseManager( 2587): starting single advertising
,E/bt-btif ( 2587): Listen For All now
D/BtGatt.GattService( 2587): onAdvertiseCallback,- clientIf=5, status=0
,D/BtGatt.GattService( 2587): registerClient() - UUID=9e884b8c-a64c-4ef1-9922-3d4e5b6f6b02
D/BtGatt.GattService( 2587): onClientRegistered() - UUID=9e884b8c-a64c-4ef1-9922-3d4e5b6f6b02, clientIf=6
,D/BluetoothLeScanner( 6632): onClientRegistered() - status=0 clientIf=6
D/BtGatt.GattService( 2587): start scan with filters
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6632): startBlePeerDiscovery: OK
,D/BtGatt.ScanManager( 2587): handling starting scan
,D/BluetoothManagerService(  891): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/BtGatt.ScanManager( 2587): configureRegularScanParams() - queue=1
,D/BtGatt.ScanManager( 2587): configureRegularScanParams() - ScanSetting Scan mode=1 mLastConfiguredScanSetting=-2147483648
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6632): verifyIdentityString: Identity string created: {"pi":"44:80:EB:7B:5A:05","pn":"1453045036041.6632","ra":"44:80:EB:7B:5A:05"}
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6632): start: {"pi":"44:80:EB:7B:5A:05","pn":"1453045036041.6632","ra":"44:80:EB:7B:5A:05"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6632): start: Identity string: "{"pi":"44:80:EB:7B:5A:05","pn":"1453045036041.6632","ra":"44:80:EB:7B:5A:05"}", service type: "Cordovap2p._tcp"
D/WifiP2pService(  891): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@6fbe118 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  891): P2pEnabledState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@6fbe118 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  891): P2pEnabledState add service
D/WifiP2pService(  891): add a new client
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6632): setState: INITIALIZED
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6632): start: Starting P2P device discovery...
D/WifiP2pService(  891): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  891): P2pEnabledState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 1420): p2p0: P2P: Reject scan trigger since one is already pending
D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P: Reject scan trigger 
D/MDMCTBK (  292): Event received = P2P: Reject scan trigger 
D/WifiP2pService(  891): discovery change broadcast true
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6632): onIsWifiPeerDiscoveryStartedChanged: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6632): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6632): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6632): setState: RUNNING_BLE_AND_WIFI
I/io.jxcore.node.ConnectionHelper( 6632): start: OK
I/jxcore-log( 6632): ok 61 Should be able to call startBroadcasting without error
I/jxcore-log( 6632): 
I/io.jxcore.node.ConnectionHelper( 6632): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6632): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6632): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6632): stopListeningForIncomingConnections: Stopping...
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6632): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6632): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6632): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6632): stop: Stopping peer discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6632): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6632): onServerStopped
D/BtGatt.AdvertiseManager( 2587): message : 1
D/BtGatt.AdvertiseManager( 2587): stop advertise for client 5
,D/BtGatt.GattService( 2587): onAdvertiseCallback,- clientIf=5, status=0
,D/BtGatt.GattService( 2587): onAdvertiseInstanceDisabled() - clientIf=5, status=0
D/BtGatt.GattService( 2587): Client app is not null!
D/BtGatt.GattService( 2587): unregisterClient() - clientIf=5
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 6632): onIsAdvertiserStartedChanged: false
,D/BtGatt.GattService( 2587): stopScan() - queue size =1
,D/BtGatt.ScanManager( 2587): stop scan
D/BtGatt.ScanManager( 2587): configureRegularScanParams() - queue=0
D/BtGatt.ScanManager( 2587): configureRegularScanParams() - ScanSetting Scan mode=-2147483648 mLastConfiguredScanSetting=1
D/BtGatt.ScanManager( 2587): configureRegularScanParams() - queue emtpy, scan stopped
D/BtGatt.GattService( 2587): unregisterClient() - clientIf=6
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 6632): onIsScannerStartedChanged: false
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 6632): setIsStarted: true
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6632): onIsBlePeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6632): stopBlePeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6632): stop: Stopping services
D/WifiP2pService(  891): InactiveState{ when=0 what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  891): P2pEnabledState{ when=0 what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  891): P2pEnabledState clear service
,D/WifiP2pService(  891): remove client information from framework
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6632): stop: Stopping P2P device discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6632): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6632): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6632): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6632): release: No more listeners, de-initializing...
D/WifiP2pService(  891): InactiveState{ when=0 what=139268 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
,I/wpa_supplicant( 1420): P2P-FIND-STOPPED 
D/MDMCTBK (  292): reply_len: 40 reply is = <3>P2P-FIND-STOPPED 
D/MDMCTBK (  292): Event received = P2P-FIND-STOPPED 
D/WifiP2pService(  891): InactiveState{ when=-1ms what=139307 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  891): P2pEnabledState{ when=-1ms what=139307 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  891): P2pEnabledState clear service request
D/WifiP2pService(  891): InactiveState{ when=-2ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  891): P2pEnabledState{ when=-2ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  891): discovery change broadcast false
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6632): release: No more listeners, de-initializing...
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6632): setState: NOT_STARTED
I/jxcore-log( 6632): ok 62 Should be able to call stopBroadcasting without error
I/jxcore-log( 6632): 
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6632): setDiscoveryMode: Mode set to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6632): setDiscoveryMode: Mode set to BLE_AND_WIFI
,D/BluetoothManagerService(  891): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6632): start: Peer ID: 44:80:EB:7B:5A:05, peer name: 1453045036105.6632
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6632): bind: Binding a new listener
D/BluetoothManagerService(  891): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6632): initialize: My bluetooth address is 44:80:EB:7B:5A:05
,D/BluetoothManagerService(  891): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6632): verifyIdentityString: Identity string created: {"pi":"44:80:EB:7B:5A:05","pn":"1453045036105.6632","ra":"44:80:EB:7B:5A:05"}
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6632): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6632): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6632): startListeningForIncomingConnections: Starting...
D/BluetoothManagerService(  891): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 6632): getBluetoothService() called with no BluetoothManagerCallback
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6632): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6632): start: OK
I/io.jxcore.node.ConnectionHelper( 6632): start: Using peer discovery mode: BLE_AND_WIFI
D/BluetoothManagerService(  891): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6632): Waiting for incoming connections...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6632): start: Peer ID: 44:80:EB:7B:5A:05, peer name: 1453045036105.6632
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6632): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6632): bind: Binding a new listener
,D/BluetoothManagerService(  891): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 6632): setAdvertiseSettings: Mode: 1, Tx power level: 1, timeout: 0, is connectable: true
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 6632): createAdvertiseData: From: 1453045036105.6632 b6a44ad1-d319-4b3a-815d-8b805a47fb51 44:80:EB:7B:5A:05
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 6632): 44:80:EB:7B:5A:5
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 6632): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, 68, -128, -21, 123, 90, 5]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 6632): setScanSettings: Mode: 1, report delay in milliseconds: 0, scan result type: 0
,D/BtGatt.GattService( 2587): registerClient() - UUID=252e0b87-c312-47b9-90a4-f6c98a11500f
,D/BtGatt.GattService( 2587): onClientRegistered() - UUID=252e0b87-c312-47b9-90a4-f6c98a11500f, clientIf=5
D/BluetoothLeAdvertiser( 6632): onClientRegistered() - status=0 clientIf=5
,D/BtGatt.AdvertiseManager( 2587): message : 0
,D/BtGatt.AdvertiseManager( 2587): starting single advertising
E/bt-btif ( 2587): Listen For All now
,D/BtGatt.GattService( 2587): onAdvertiseCallback,- clientIf=5, status=0
,D/BtGatt.GattService( 2587): registerClient() - UUID=a226a486-1d5c-4623-9783-9054d04625d7
,D/BtGatt.GattService( 2587): onClientRegistered() - UUID=a226a486-1d5c-4623-9783-9054d04625d7, clientIf=6
D/BluetoothLeScanner( 6632): onClientRegistered() - status=0 clientIf=6
D/BtGatt.GattService( 2587): start scan with filters
,D/BtGatt.ScanManager( 2587): handling starting scan
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6632): startBlePeerDiscovery: OK
,D/BluetoothManagerService(  891): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BtGatt.ScanManager( 2587): configureRegularScanParams() - queue=1
,D/BtGatt.ScanManager( 2587): configureRegularScanParams() - ScanSetting Scan mode=1 mLastConfiguredScanSetting=-2147483648
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6632): verifyIdentityString: Identity string created: {"pi":"44:80:EB:7B:5A:05","pn":"1453045036105.6632","ra":"44:80:EB:7B:5A:05"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6632): start: {"pi":"44:80:EB:7B:5A:05","pn":"1453045036105.6632","ra":"44:80:EB:7B:5A:05"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6632): start: Identity string: "{"pi":"44:80:EB:7B:5A:05","pn":"1453045036105.6632","ra":"44:80:EB:7B:5A:05"}", service type: "Cordovap2p._tcp"
D/WifiP2pService(  891): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@497ab956 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  891): P2pEnabledState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@497ab956 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  891): P2pEnabledState add service
D/WifiP2pService(  891): add a new client
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6632): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6632): start: Starting P2P device discovery...
,D/WifiP2pService(  891): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  891): P2pEnabledState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6632): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6632): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6632): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6632): setState: RUNNING_BLE_AND_WIFI
I/io.jxcore.node.ConnectionHelper( 6632): start: OK
I/wpa_supplicant( 1420): p2p0: P2P: Reject scan trigger since one is already pending
D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=p2p0 <3>P2P: Reject scan trigger 
D/MDMCTBK (  292): Event received = P2P: Reject scan trigger 
,D/WifiP2pService(  891): discovery change broadcast true
I/jxcore-log( 6632): ok 63 Should be able to call startBroadcasting without error
I/jxcore-log( 6632): 
I/io.jxcore.node.ConnectionHelper( 6632): stop
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6632): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6632): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6632): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6632): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6632): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6632): onServerStopped
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6632): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6632): setState: NOT_STARTED
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6632): stop: Stopping peer discovery...
D/BtGatt.AdvertiseManager( 2587): message : 1
D/BtGatt.AdvertiseManager( 2587): stop advertise for client 5
,D/BtGatt.GattService( 2587): onAdvertiseInstanceDisabled() - clientIf=5, status=0
D/BtGatt.GattService( 2587): Client app is not null!
,D/BtGatt.GattService( 2587): onAdvertiseCallback,- clientIf=5, status=0
D/BtGatt.GattService( 2587): unregisterClient() - clientIf=5
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 6632): onIsAdvertiserStartedChanged: false
,D/BtGatt.GattService( 2587): stopScan() - queue size =1
,D/BtGatt.ScanManager( 2587): stop scan
,D/BtGatt.ScanManager( 2587): configureRegularScanParams() - queue=0
,D/BtGatt.ScanManager( 2587): configureRegularScanParams() - ScanSetting Scan mode=-2147483648 mLastConfiguredScanSetting=1
D/BtGatt.ScanManager( 2587): configureRegularScanParams() - queue emtpy, scan stopped
D/BtGatt.GattService( 2587): unregisterClient() - clientIf=6
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 6632): onIsScannerStartedChanged: false
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 6632): setIsStarted: true
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6632): onIsBlePeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6632): stopBlePeerDiscovery: Stopped
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6632): stop: Stopping services
D/WifiP2pService(  891): InactiveState{ when=0 what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  891): P2pEnabledState{ when=0 what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  891): P2pEnabledState clear service
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6632): stop: Stopping P2P device discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6632): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6632): onIsWifiPeerDiscoveryStartedChanged: false
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6632): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6632): release: No more listeners, de-initializing...
D/WifiP2pService(  891): remove client information from framework
D/WifiP2pService(  891): InactiveState{ when=0 what=139268 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6632): release: No more listeners, de-initializing...
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6632): setState: NOT_STARTED
,I/wpa_supplicant( 1420): P2P-FIND-STOPPED 
D/MDMCTBK (  292): reply_len: 40 reply is = <3>P2P-FIND-STOPPED 
D/MDMCTBK (  292): Event received = P2P-FIND-STOPPED 
I/jxcore-log( 6632): ok 64 Should be able to call stopBroadcasting without error
I/jxcore-log( 6632): 
D/WifiP2pService(  891): InactiveState{ when=-3ms what=139307 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  891): P2pEnabledState{ when=-3ms what=139307 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  891): P2pEnabledState clear service request
,D/WifiP2pService(  891): InactiveState{ when=-2ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  891): P2pEnabledState{ when=-2ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  891): discovery change broadcast false
,I/jxcore-log( 6632): # setup
I/jxcore-log( 6632): 
,I/io.jxcore.node.ConnectionHelper( 6632): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 6632): onStartSuccess
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 6632): onIsAdvertiserStartedChanged: true
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6632): Local service added successfully
I/io.jxcore.node.ConnectionHelper( 6632): onDiscoveryManagerStateChanged: RUNNING_BLE_AND_WIFI
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6632): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6632): setState: STARTED
,I/io.jxcore.node.ConnectionHelper( 6632): onConnectionManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6632): Local services cleared successfully
I/io.jxcore.node.ConnectionHelper( 6632): onDiscoveryManagerStateChanged: NOT_STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6632): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6632): Service requests cleared successfully
I/io.jxcore.node.ConnectionHelper( 6632): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 6632): onStartSuccess
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 6632): onIsAdvertiserStartedChanged: true
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6632): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6632): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6632): setState: STARTED
I/io.jxcore.node.ConnectionHelper( 6632): onDiscoveryManagerStateChanged: RUNNING_BLE_AND_WIFI
I/io.jxcore.node.ConnectionHelper( 6632): onConnectionManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6632): Local services cleared successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6632): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6632): Service requests cleared successfully
I/io.jxcore.node.ConnectionHelper( 6632): onDiscoveryManagerStateChanged: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 6632): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 6632): onStartSuccess
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 6632): onIsAdvertiserStartedChanged: true
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6632): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6632): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6632): setState: STARTED
I/io.jxcore.node.ConnectionHelper( 6632): onDiscoveryManagerStateChanged: RUNNING_BLE_AND_WIFI
I/io.jxcore.node.ConnectionHelper( 6632): onConnectionManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6632): Local services cleared successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6632): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6632): Service requests cleared successfully
I/io.jxcore.node.ConnectionHelper( 6632): onDiscoveryManagerStateChanged: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 6632): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 6632): onStartSuccess
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 6632): onIsAdvertiserStartedChanged: true
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6632): Local service added successfully
I/io.jxcore.node.ConnectionHelper( 6632): onDiscoveryManagerStateChanged: RUNNING_BLE_AND_WIFI
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6632): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6632): setState: STARTED
I/io.jxcore.node.ConnectionHelper( 6632): onConnectionManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6632): Local services cleared successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6632): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6632): Service requests cleared successfully
I/io.jxcore.node.ConnectionHelper( 6632): onDiscoveryManagerStateChanged: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 6632): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 6632): onStartSuccess
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 6632): onIsAdvertiserStartedChanged: true
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6632): Local service added successfully
I/io.jxcore.node.ConnectionHelper( 6632): onDiscoveryManagerStateChanged: RUNNING_BLE_AND_WIFI
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6632): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6632): setState: STARTED
I/io.jxcore.node.ConnectionHelper( 6632): onConnectionManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6632): Local services cleared successfully
I/io.jxcore.node.ConnectionHelper( 6632): onDiscoveryManagerStateChanged: NOT_STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6632): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6632): Service requests cleared successfully
I/io.jxcore.node.ConnectionHelper( 6632): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 6632): onStartSuccess
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 6632): onIsAdvertiserStartedChanged: true
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6632): Local service added successfully
I/io.jxcore.node.ConnectionHelper( 6632): onDiscoveryManagerStateChanged: RUNNING_BLE_AND_WIFI
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6632): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6632): setState: STARTED
I/io.jxcore.node.ConnectionHelper( 6632): onConnectionManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6632): Local services cleared successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6632): P2P device discovery stopped successfully
I/io.jxcore.node.ConnectionHelper( 6632): onDiscoveryManagerStateChanged: NOT_STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6632): Service requests cleared successfully
I/io.jxcore.node.ConnectionHelper( 6632): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 6632): onStartSuccess
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 6632): onIsAdvertiserStartedChanged: true
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6632): Local service added successfully
I/io.jxcore.node.ConnectionHelper( 6632): onDiscoveryManagerStateChanged: RUNNING_BLE_AND_WIFI
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6632): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6632): setState: STARTED
I/io.jxcore.node.ConnectionHelper( 6632): onConnectionManagerStateChanged: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 6632): onDiscoveryManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6632): Local services cleared successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6632): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6632): Service requests cleared successfully
I/io.jxcore.node.ConnectionHelper( 6632): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 6632): onStartSuccess
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 6632): onIsAdvertiserStartedChanged: true
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6632): Local service added successfully
I/io.jxcore.node.ConnectionHelper( 6632): onDiscoveryManagerStateChanged: RUNNING_BLE_AND_WIFI
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6632): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6632): setState: STARTED
I/io.jxcore.node.ConnectionHelper( 6632): onConnectionManagerStateChanged: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 6632): onDiscoveryManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6632): Local services cleared successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6632): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6632): Service requests cleared successfully
I/io.jxcore.node.ConnectionHelper( 6632): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 6632): onStartSuccess
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 6632): onIsAdvertiserStartedChanged: true
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6632): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6632): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6632): setState: STARTED
I/io.jxcore.node.ConnectionHelper( 6632): onDiscoveryManagerStateChanged: RUNNING_BLE_AND_WIFI
I/io.jxcore.node.ConnectionHelper( 6632): onConnectionManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6632): Local services cleared successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6632): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6632): Service requests cleared successfully
I/io.jxcore.node.ConnectionHelper( 6632): onDiscoveryManagerStateChanged: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 6632): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 6632): onStartSuccess
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 6632): onIsAdvertiserStartedChanged: true
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6632): Local service added successfully
I/io.jxcore.node.ConnectionHelper( 6632): onDiscoveryManagerStateChanged: RUNNING_BLE_AND_WIFI
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6632): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6632): setState: STARTED
I/io.jxcore.node.ConnectionHelper( 6632): onConnectionManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6632): Local services cleared successfully
I/io.jxcore.node.ConnectionHelper( 6632): onDiscoveryManagerStateChanged: NOT_STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6632): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6632): Service requests cleared successfully
,D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-ADDED 0 c0,
D/MDMCTBK (  292): Event received = CTRL-EVENT-BSS-ADDED 0 c0
,D/TCMD    (  482): NL - Read 56 bytes from update socket.
D/TCMD    (  482): NL - message type is RTM_NEWLINK
D/TCMD    (  482): Listening for incoming client connection request
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:30000 mC
,V/AlarmManager(  891): send {842bec4, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  891): send {1d58b2c, *walarm*:android.content.syncmanager.SYNC_ALARM}
,V/AlarmManager(  891): done {1d58b2c, *walarm*:android.content.syncmanager.SYNC_ALARM} [9ms]
,V/AlarmManager(  891): done {842bec4, *alarm*:android.intent.action.TIME_TICK} [49ms]
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:30000 mC
,D/MDMCTBK (  292): reply_len: 40 reply is = IFNAME=p2p0 <3>CTRL-EVENT-BSS-REMOVED 0 
D/MDMCTBK (  292): Event received = CTRL-EVENT-BSS-REMOVED 0 
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:30000 mC
,I/MDMCTBK (  292): NetlinkHandler, power_supply subsys
,I/MDMCTBK (  292): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  292): checkDefaultInst, current pid is = 292
I/MDMCTBK (  292): checkDefaultInst, pid match
I/MDMCTBK (  292): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  292): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  292): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  292): NetlinkHandler, power_supply subsys
I/MDMCTBK (  292): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  292): checkDefaultInst, current pid is = 292
I/MDMCTBK (  292): checkDefaultInst, pid match
I/MDMCTBK (  292): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  292): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  292): MdmCutbackHndler,Could not open ''
,D/BatteryService(  891): uevent={POWER_SUPPLY_TEMP=268, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4310962, SEQNUM=4519, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-8112, POWER_SUPPLY_CHARGE_COUNTER=-1172, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2587): Disconnected process message: 10, size: 0
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
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,I/MDMCTBK (  292): NetlinkHandler, power_supply subsys
,I/MDMCTBK (  292): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  292): checkDefaultInst, current pid is = 292
I/MDMCTBK (  292): checkDefaultInst, pid match
I/MDMCTBK (  292): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  292): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  292): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  292): NetlinkHandler, power_supply subsys
,I/MDMCTBK (  292): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  292): checkDefaultInst, current pid is = 292
I/MDMCTBK (  292): checkDefaultInst, pid match
I/MDMCTBK (  292): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  292): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  292): MdmCutbackHndler,Could not open ''
,D/BatteryService(  891): uevent={POWER_SUPPLY_TEMP=258, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4310841, SEQNUM=4521, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-3705, POWER_SUPPLY_CHARGE_COUNTER=-2526, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2587): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2587): Disconnected process message: 10, size: 0
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,V/AlarmManager(  891): send {842bec4, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  891): send {291bd7c1, *walarm*:android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED}
V/AlarmManager(  891): send {285bd9f5, *walarm*:com.google.android.gms/.checkin.EventLogService$Receiver}
V/AlarmManager(  891): send {3402a38a, *alarm*:com.android.deskclock.ON_QUARTER_HOUR}
,V/AlarmManager(  891): done {291bd7c1, *walarm*:android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED} [26ms]
,V/AlarmManager(  891): done {285bd9f5, *walarm*:com.google.android.gms/.checkin.EventLogService$Receiver} [52ms]
,I/ActivityManager(  891): Start proc com.google.android.deskclock for broadcast com.google.android.deskclock/com.android.alarmclock.DigitalAppWidgetProvider: pid=8400 uid=10055 gids={50055, 9997, 3003, 1028} abi=armeabi-v7a
,V/AlarmManager(  891): done {842bec4, *alarm*:android.intent.action.TIME_TICK} [157ms]
,I/EventLogService( 1971): Aggregate from 1453044955209 (log), 1453044017363 (data)
,I/GAv4    ( 8400): Google Analytics 4.5.0/7324 is starting up. To enable debug logging on a device run:
I/GAv4    ( 8400):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 8400):   adb logcat -s GAv4
,W/GAv4    ( 8400): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 8400): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 8400): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,V/AlarmManager(  891): done {3402a38a, *alarm*:com.android.deskclock.ON_QUARTER_HOUR} [326ms]
I/ActivityManager(  891): Killing 8119:com.google.android.googlequicksearchbox:search/u0a39 (adj 15): empty #7
,W/libprocessgroup(  891): failed to open /acct/uid_10039/pid_8119/cgroup.procs: No such file or directory
,V/AlarmManager(  891): send {38145ed7, *walarm*:com.google.android.gms.gcm.HEARTBEAT_ALARM}
,V/AlarmManager(  891): done {38145ed7, *walarm*:com.google.android.gms.gcm.HEARTBEAT_ALARM} [23ms]
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/MDMCTBK (  292): NetlinkHandler, power_supply subsys
,I/MDMCTBK (  292): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  292): checkDefaultInst, current pid is = 292
I/MDMCTBK (  292): checkDefaultInst, pid match
I/MDMCTBK (  292): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  292): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  292): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  292): NetlinkHandler, power_supply subsys
I/MDMCTBK (  292): NetlinkHandler, usbChargerStateChanged
,I/MDMCTBK (  292): checkDefaultInst, current pid is = 292
I/MDMCTBK (  292): checkDefaultInst, pid match
I/MDMCTBK (  292): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  292): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  292): MdmCutbackHndler,Could not open ''
,D/BatteryService(  891): uevent={POWER_SUPPLY_TEMP=259, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4310556, SEQNUM=4533, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-4306, POWER_SUPPLY_CHARGE_COUNTER=-2546, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2587): Disconnected process message: 10, size: 0
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,I/MDMCTBK (  292): NetlinkHandler, power_supply subsys
,I/MDMCTBK (  292): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  292): checkDefaultInst, current pid is = 292
I/MDMCTBK (  292): checkDefaultInst, pid match
I/MDMCTBK (  292): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  292): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  292): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  292): NetlinkHandler, power_supply subsys
,I/MDMCTBK (  292): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  292): checkDefaultInst, current pid is = 292
I/MDMCTBK (  292): checkDefaultInst, pid match
I/MDMCTBK (  292): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  292): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  292): MdmCutbackHndler,Could not open ''
,D/BatteryService(  891): uevent={POWER_SUPPLY_TEMP=258, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4310837, SEQNUM=4535, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-5909, POWER_SUPPLY_CHARGE_COUNTER=-2571, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2587): Disconnected process message: 10, size: 0
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,I/UsageStatsService(  891): User[0] Flushing usage stats to disk
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,V/AlarmManager(  891): send {842bec4, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  891): send {1d58b2c, *walarm*:android.content.syncmanager.SYNC_ALARM}
,V/AlarmManager(  891): done {1d58b2c, *walarm*:android.content.syncmanager.SYNC_ALARM} [16ms]
,V/AlarmManager(  891): done {842bec4, *alarm*:android.intent.action.TIME_TICK} [46ms]
,TIME-OUT KILL (timeout was 1200000ms),D/AndroidRuntime( 8447): 
D/AndroidRuntime( 8447): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 8447): CheckJNI is OFF
D/AndroidRuntime( 8447): Calling main entry com.android.commands.pm.Pm
I/ActivityManager(  891): Force stopping com.test.thalitest appid=10458 user=-1: uninstall pkg
I/ActivityManager(  891): Killing 6632:com.test.thalitest/u0a458 (adj 9): stop com.test.thalitest
W/PackageSettings(  891): Skipping PackageSetting{f36067b com.example.hello/10440} due to missing metadata
I/WindowState(  891): WIN DEATH: Window{3e1cae55 u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/WifiService(  891): Client connection lost with reason: 4
I/ActivityManager(  891):   Force finishing activity ActivityRecord{144c42b9 u0 com.test.thalitest/.MainActivity t6}
W/ActivityManager(  891): Spurious death for ProcessRecord{6dc13c4 6632:com.test.thalitest/u0a458}, curProc for 6632: null
I/ActivityManager(  891): Force stopping com.test.thalitest appid=10458 user=0: pkg removed
I/art     ( 3243): Explicit concurrent mark sweep GC freed 11014(2MB) AllocSpace objects, 25(400KB) LOS objects, 39% free, 7MB/12MB, paused 1.045ms total 38.765ms
W/GeofencerStateMachine( 1751): Ignoring removeGeofence because network location is disabled.
I/InputReader(  891): Reconfiguring input devices.  changes=0x00000010
I/Keyboard.Facilitator( 1428): resetDictionaries() : en_US
I/Keyboard.Facilitator.DecoderInitializer( 1428): run()
D/VoicemailCleanupService( 8171): Cleaning up data for package: com.test.thalitest
I/art     ( 1582): Explicit concurrent mark sweep GC freed 4928(303KB) AllocSpace objects, 6(297KB) LOS objects, 25% free, 13MB/17MB, paused 678us total 116.926ms
I/ActivityManager(  891): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=8480 uid=10027 gids={50027, 9997, 1023, 3003, 1028, 1015} abi=armeabi-v7a
I/art     ( 1971): Explicit concurrent mark sweep GC freed 18798(1138KB) AllocSpace objects, 5(80KB) LOS objects, 24% free, 14MB/19MB, paused 1.379ms total 166.051ms
I/art     (  891): Explicit concurrent mark sweep GC freed 31375(2MB) AllocSpace objects, 7(112KB) LOS objects, 33% free, 20MB/30MB, paused 1.665ms total 150.154ms
I/Decoder ( 1428): createOrResetDecoder
I/art     (  891): WaitForGcToComplete blocked for 50.919ms for cause Explicit
I/ConfigService( 1751): onCreate
W/asset   ( 8480): Asset path /system/framework/com.motorola.gallery is neither a directory nor file (type=1).
W/ResourcesManager( 8480): Asset path '/system/framework/com.motorola.gallery' does not exist or contains no resources.
W/ResourcesManager( 8480): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 8480): Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
I/Keyboard.Facilitator.MainLanguageModelLoader( 1428): run()
I/ActivityManager(  891): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=8503 uid=1000 gids={41000, 9997, 1021, 3004, 3005, 1000, 3009, 1015, 1023, 1010, 1004, 2002, 3006, 1028, 3002, 3001, 3003} abi=armeabi-v7a
D/BackupManagerService(  891): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService(  891): Receieved: android.intent.action.PACKAGE_REMOVED
D/TaskPersister(  891): removeObsoleteFile: deleting file=6_task.xml
I/ActivityManager(  891): Killing 8219:com.google.android.apps.plus/u0a90 (adj 15): empty #7
I/Keyboard.Facilitator.MainLanguageModelLoader( 1428): loadStaticLm() : Loading File = /data/data/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4014912) with up to date LoudsLmContentVersion = 20150512
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1428): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1428): run() : Loading LM = contacts
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1428): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1428): run() : Loading LM = history
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1428): run() : Loaded File = UserHistory.en_US.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1428): run() : Loading LM = user
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1428): run() : Missing File = Personal.en_US.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1428): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1428): run()
I/Keyboard.Facilitator.RecurringTaskScheduler( 1428): run()
I/StatsUtilsManager( 1428): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1428): shouldRecordStats() = Too Soon
I/art     (  891): Explicit concurrent mark sweep GC freed 7971(430KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 20MB/30MB, paused 1.759ms total 200.282ms
I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
D/AndroidRuntime( 8447): Shutting down VM
W/libprocessgroup(  891): failed to open /acct/uid_10090/pid_8219/cgroup.procs: No such file or directory
I/Launcher( 1582): Deferring update until onResume
W/ContextImpl( 8503): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1820 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2611 
D/PackageBroadcastService( 1971): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/AccountUtils( 1971): Clearing selected account for com.test.thalitest
D/ChimeraCfgMgr( 1971): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1971): Module APK com.google.android.play.games already loaded
I/LocationSettingsChecker( 1971): Removing dialog suppression flag for package com.test.thalitest
D/ChimeraCfgMgr( 1971): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1971): Module APK com.google.android.play.games already loaded
E/NetworkScheduler.SchedulerReceiver( 1751): Invalid parameter app
E/NetworkScheduler.SchedulerReceiver( 1751): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
D/gH_CompatibleDatabase( 1971): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/gH_CompatibleDatabase( 1971): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
D/gH_MetricsDatabase( 1971): 0 metrics were deleted when clearing package com.test.thalitest.
D/gH_CompatibleDatabase( 1971): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
D/gH_CompatibleDatabase( 1971): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
D/gH_CompatibleDatabase( 1971): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
D/gH_CompatibleDatabase( 1971): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
D/gH_CompatibleDatabase( 1971): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
D/gH_CompatibleDatabase( 1971): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
D/gH_CompatibleDatabase( 1971): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
I/ActivityManager(  891): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.IcingCorporaChangedReceiver: pid=8531 uid=10039 gids={50039, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
D/gH_CompatibleDatabase( 1971): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
D/gH_CompatibleDatabase( 1971): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
D/gH_CompatibleDatabase( 1971): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
I/Icing   ( 1971): doRemovePackageData com.test.thalitest
W/Launcher( 1582): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@a65b48c new=com.google.android.velvet.VelvetApplication@a65b48c
I/ActivityManager(  891): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=8560 uid=10057 gids={50057, 9997, 1028, 3003, 1015} abi=armeabi-v7a
I/qdhwcomposer(  278): handle_blank_event: dpy:0 panel power state: 0

```
