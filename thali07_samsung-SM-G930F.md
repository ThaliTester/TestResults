#### Test 9835488260af434_thali07_samsung-SM-G930F Logs


```
--------- beginning of system
,12-19 12:52:51.705  3455  4077 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
12-19 12:52:51.705  3455  4077 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4350, temperature: 291, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
12-19 12:52:51.705  3455  4077 D BatteryService: online:4, current avg:67, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:375
12-19 12:52:51.705  3455  3455 D BatteryService: Sending ACTION_BATTERY_CHANGED.
12-19 12:52:51.715  3455  3455 I MotionRecognitionService: Plugged
12-19 12:52:51.715  3455  3455 D MotionRecognitionService:   cableConnection= 1
12-19 12:52:51.715  3455  3455 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
12-19 12:52:51.715  3455  3455 D MotionRecognitionService: skip setTransmitPower. 
--------- beginning of main
12-19 12:52:51.715  3455  3852 D WifiController: ApOrStaEnabledState  msg.what= 155652
12-19 12:52:51.715  3929  3929 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
12-19 12:52:51.725  3929  3929 D KeyguardUpdateMonitor: handleBatteryUpdate
12-19 12:52:51.725  3929  3929 D PowerUI : priorPlugType = 2 mPlugType =  2
12-19 12:52:51.725  3929  3929 D PowerUI.Notification: dismissChargingNotification()
12-19 12:52:51.725  3455  3455 D EdgeLight: Turning off
12-19 12:52:51.725  3455  3455 D LightsService: [api] [SvcLED] turnOff:: id = 6 (uid: 1000 pid: 3455) 
12-19 12:52:51.725  3455  3455 D LightsService: [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x0 | SvcLED(id=6) set Off
12-19 12:52:51.725  3455  3583 D LightsService: [SvcLED] handleForcedSvcLEDTask()
12-19 12:52:51.725  3455  3583 D LightsService: [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=5) maintains its priority right
12-19 12:52:51.745  3929  3929 D PhoneStatusBar: removeNotification key=-1|com.android.systemui|2131624021|charging_state|10062 old=StatusBarNotification(pkg=com.android.systemui user=UserHandle{-1} id=2131624021 tag=charging_state score=-20 key=-1|com.android.systemui|2131624021|charging_state|10062: Notification(pri=-2 contentView=com.android.systemui/0x10900a3 vibrate=null sound=null defaults=0x0 flags=0xa color=0xff7792a9 category=sys vis=PUBLIC secFlags=0x0 secPriority=0))
12-19 12:52:51.745  3929  3929 D PhoneStatusBar: setAreThereNotifications: N=2 any=true clearable=true
12-19 12:52:51.745  4883  4883 D CommonServiceConfiguration: getStringValueSetting
12-19 12:52:51.755  4838  4838 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
12-19 12:52:51.755  4838  5195 D HeadsetStateMachine: Disconnected process message: 10, size: 0
12-19 12:52:51.755  4883  4883 D BatteryMonitor: new battery level: 100
12-19 12:52:51.765  3929  3929 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
12-19 12:52:51.765  3929  3929 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
12-19 12:52:52.195  9253  9253 I FIPS_bssl: FIPS approved mode (1) | 9253 | app_process
12-19 12:52:52.195  9253  9253 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
12-19 12:52:52.195  9253  9253 D AndroidRuntime: CheckJNI is OFF
12-19 12:52:52.195  9253  9253 D AndroidRuntime: readGMSProperty: start
12-19 12:52:52.195  9253  9253 D AndroidRuntime: readGMSProperty: already setted!!
12-19 12:52:52.195  9253  9253 D AndroidRuntime: propertySet: couldn't set property (it is from app)
12-19 12:52:52.195  9253  9253 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
12-19 12:52:52.195  9253  9253 D AndroidRuntime: readGMSProperty: end
12-19 12:52:52.195  9253  9253 D AndroidRuntime: addProductProperty: start
12-19 12:52:52.215  9253  9253 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
12-19 12:52:52.235  9253  9253 I Radio-JNI: register_android_hardware_Radio DONE
12-19 12:52:52.245  9253  9253 E AffinityControl: AffinityControl: registerfunction enter
12-19 12:52:52.255  9253  9253 D AndroidRuntime: Calling main entry com.android.commands.am.Am
12-19 12:52:52.285  3455  4534 D VirtualScreenPolicy: applyVirtualScreenAttrs attrs=VirtualScreenAttrs{mDisplayId=0, mBaseDisplayId=0, mBaseActivity=false}
12-19 12:52:52.285  3455  4534 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in null rsrc of package com.test.thalitest
12-19 12:52:52.305  3455  4534 D ResourcesManager: For user 0 new overlays fetched Null
12-19 12:52:52.305  3455  4534 D GameManagerService: identifyGamePackage. com.test.thalitest
12-19 12:52:52.305  3455  4534 D MultiWindowPolicy: Gamemode - return 0,  when calling  identifyForegroundApp(com.test.thalitest)
12-19 12:52:52.315  3455  4534 D CustomFrequencyManagerService: acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1872000  uid : 1000  pid : 3455  pkgName : ACTIVITY_RESUME_BOOSTER@3
12-19 12:52:52.315  3455  4534 D ActivityManager: mDVFSHelper.acquire()
12-19 12:52:52.315  3009  3009 I SurfaceFlinger: id=12 createSurf (16x16),-1 flag=20004, EimLayer(Di
12-19 12:52:52.315  3009  3009 I SurfaceFlinger: id=13 createSurf (16x16),-1 flag=20004, EimLayer(An
12-19 12:52:52.325  3455  3455 D ViewRootImpl: MSG_RESIZED: ci=Rect(0, 0 - 0, 0) vi=Rect(0, 0 - 0, 0) or=1
12-19 12:52:52.325  3929  3929 D ViewRootImpl: MSG_RESIZED: ci=Rect(0, 0 - 0, 0) vi=Rect(0, 0 - 0, 0) or=1
12-19 12:52:52.325  3455  3455 D ViewRootImpl: MSG_RESIZED: ci=Rect(0, 0 - 0, 0) vi=Rect(0, 0 - 0, 0) or=1
12-19 12:52:52.325  3929  3939 D WallpaperService: resized:[frame]Rect(0, 0 - 2240, 2560) [newConfig] is null
12-19 12:52:52.325  3929  3929 D WallpaperService: MSG_WINDOW_RESIZED
12-19 12:52:52.325  3455  4534 D FocusedStackFrame: Set to : 0
12-19 12:52:52.325  3929  3929 D WallpaperService: updateSurface:[forceRelayout]true[redrawNeeded]false
12-19 12:52:52.325  3929  3929 V WallpaperService: Changes: creating=false format=false size=false
12-19 12:52:52.325  3455  4534 V WindowManager: addAppToken: AppWindowToken{d0d073cd9 token=Token{bfedb20 ActivityRecord{54a7a23 u0 com.test.thalitest/.MainActivity t170}}} to stack=2 task=170 at 0
12-19 12:52:52.325  3929  3929 V WallpaperService: currentWidth:2240 currentHeight:2560 requestedWidth:2240 requestedWidth:2560
12-19 12:52:52.325  4250  4250 D Launcher: onPause, Launcher: 43607672
12-19 12:52:52.325  4250  4250 D Launcher.HomeView: onPause
12-19 12:52:52.325  4250  4250 D Launcher.Workspace: exitWidgetResizeMode. isClearResizeFrame is false
12-19 12:52:52.325  3929  3929 V WallpaperService: relayout result: Surface(name=null)/@0xfaeceb5, frame=Rect(0, 0 - 2240, 2560),relayoutResult:1, mConfiguration{0 1.0 themeSeq = 0 showBtnBg = -1 ?mcc?mnc pl_PL ?layoutDir ?swdp ?wdp ?hdp ?density ?lsize ?long ?orien ?uimode ?night ?touch ?keyb/?/? ?nav/? mkbd/?}
12-19 12:52:52.325  3929  3929 V WallpaperService: Wallpaper size has changed: (2240, 2560)
12-19 12:52:52.325  3455  4534 D InputDispatcher: Focused application set to: xxxx
12-19 12:52:52.335  3455  4534 D InputDispatcher: Focus left window: 4250
12-19 12:52:52.335  3455  3571 I InjectionManager: Inside getClassLibPath caller 
12-19 12:52:52.335  3455  3571 D SecWifiDisplayUtil: Metadata value : SecSettings2
12-19 12:52:52.335  3455  3571 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{762ae11 V.E...... R.....ID 0,0-0,0}
12-19 12:52:52.335  3455  3571 D ISSUE_DEBUG: InputChannelName : cdb577 Starting com.test.thalitest
12-19 12:52:52.335  9253  9253 D AndroidRuntime: Shutting down VM
12-19 12:52:52.345  3455  3571 D PointerIcon: setMouseIconStyle1 pointerType: 1001 iconType:101 flag:0 pid:3455 uid:1000
12-19 12:52:52.345  3455  3571 D PointerIcon: setMouseCustomIcon IconType is same.101
12-19 12:52:52.345  3009  3009 I SurfaceFlinger: id=14 createSurf (1440x2560),1 flag=404, uhalitest
12-19 12:52:52.345  9263  9263 E Zygote  : v2
12-19 12:52:52.345  9263  9263 I libpersona: KNOX_SDCARD checking this for 10074
12-19 12:52:52.345  9263  9263 I libpersona: KNOX_SDCARD not a persona
12-19 12:52:52.345  9263  9263 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0031
12-19 12:52:52.345  3455  3973 I ActivityManager: Start proc 9263:com.test.thalitest/u0a74 for activity com.test.thalitest/.MainActivity
12-19 12:52:52.345  9263  9263 E Zygote  : accessInfo : 0
12-19 12:52:52.345  9263  9263 W SELinux : SELinux: seapp_context_lookup: seinfo=default, level=s0:c512,c768, pkgname=com.test.thalitest 
12-19 12:52:52.345  3455  3571 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 96 - 0, 0) vi=Rect(0, 96 - 0, 0) or=1
12-19 12:52:52.355  4388  4817 I DeviceStateChecker: DeviceStateChecker cancelled
12-19 12:52:52.355  4388  4388 I MicroDetector: Keeping mic open: false
12-19 12:52:52.355  4388  4388 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.ae@1dfd422
12-19 12:52:52.355  4388  4845 E AudioRecord-JNI: Error -4 during AudioRecord native read
12-19 12:52:52.355  3455  3847 D NetworkPolicy: isUidForegroundLocked: 10019, mScreenOn: true, uidstate: 6, mProxSensorScreenOff: false
12-19 12:52:52.365  3160  4429 I APM::AudioPolicyManager: stopInput() input 17
12-19 12:52:52.365  4388  4816 I MicroRecognitionRunner: Stopping hotword detection.
12-19 12:52:52.365  4388  4842 I MicroRecognitionRunner: Detection finished
12-19 12:52:52.365  4388  4401 W SearchService: Abort, client detached.
12-19 12:52:52.365  3160  4867 I audio_hw_primary: do_in_standby : in->standby 0
12-19 12:52:52.365  3455  3571 V WindowStateAnimator: Finishing drawing window Window{cdb577 u0 d0 Starting com.test.thalitest}: mDrawState=DRAW_PENDING
12-19 12:52:52.375  3455  3534 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{5eab5e4 u0 update-hint qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{7f45300 4388:com.google.android.googlequicksearchbox:search/u0a68}
12-19 12:52:52.375  3455  3473 V AlarmManager:  remove PendingIntent] PendingIntent{ab31a4d: PendingIntentRecord{4d3d902 com.google.android.googlequicksearchbox startService}}
12-19 12:52:52.375  9263  9263 D TimaKeyStoreProvider: TimaSignature is unavailable
12-19 12:52:52.375  9263  9263 D ActivityThread: Added TimaKeyStore provider
12-19 12:52:52.375  3160  4867 V audio_hw_primary: select_devices output_scenario:-1 input_scenario:-1 out_snd_device 0x0 in_snd_device:0x0
12-19 12:52:52.375  3160  4867 I audio_route: 
12-19 12:52:52.375  3160  4867 I audio_route: > audio_route_reset :
12-19 12:52:52.375  3160  4867 I audio_route: 
12-19 12:52:52.375  3160  4867 I audio_route: > audio_route_update_mixer : +
12-19 12:52:52.375  3009  3009 D libEGL  : eglInitialize EGLDisplay = 0x7fe591e988
12-19 12:52:52.375  3455  3973 V WindowOrientationListener: setCurrentAppOrientation :-1
12-19 12:52:52.375  3455  3973 V WindowOrientationListener: OrientationSensorJudge.getProposedRotation, Rotation: -1
12-19 12:52:52.375  3455  3973 V WindowManager: rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false mMobileKeyboardEnabled=false displayId=0
12-19 12:52:52.375  3455  3973 V WindowOrientationListener: OrientationSensorJudge.getProposedRotation, Rotation: -1
12-19 12:52:52.375  3455  3973 D ActivityManager:  Launching com.test.thalitest, updated priority
12-19 12:52:52.385  3455  3455 D GameManagerService: NotifyRunnable. pkg: com.test.thalitest, type: 4, isMinimized: false, isTunableApp: false
12-19 12:52:52.385  3160  4867 I audio_route: > audio_route_update_mixer : changed(5) -
12-19 12:52:52.385  3160  4867 I audio_hw_primary: select_devices - 
12-19 12:52:52.385  3160  4433 V audio_hw_primary: stop_voice_note_recording
12-19 12:52:52.385  3160  4433 E audio_hw_primary: adev_close_input_stream, set jack_in to null
12-19 12:52:52.385  4388  4494 I GrammarCompilationSvcCt: Grammar compilation alarm set for interval 604800000
12-19 12:52:52.395  3009  4295 D libEGL  : eglTerminate EGLDisplay = 0x7f786ffe78
12-19 12:52:52.395  3009  4295 D libEGL  : eglTerminate EGLDisplay = 0x7f786ffe78
12-19 12:52:52.395  9263  9263 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.test.thalitest rsrc of package com.test.thalitest
12-19 12:52:52.395  3455  4144 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
12-19 12:52:52.395  9263  9263 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
12-19 12:52:52.405  3455  3534 V MARsPolicyManager: updatePackagesScore PackageInfo name -- com.test.thalitest
12-19 12:52:52.405  9263  9263 D ResourcesManager: For user 0 new overlays fetched Null
12-19 12:52:52.405  3455  3536 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=Window{cdb577 u0 d0 Starting com.test.thalitest}
12-19 12:52:52.405  3455  3847 D NetworkPolicy: isUidForegroundLocked: 10074, mScreenOn: true, uidstate: 2, mProxSensorScreenOff: false
12-19 12:52:52.415  3455  3566 D MARsDBManager: onChange - mSmartManagerObserver! Uri = content://com.samsung.android.sm/AppFreezer?MARs-self=true&MARs=true
12-19 12:52:52.415  3009  4295 I SurfaceFlinger: Modify Choreographer's phase offset to 0
12-19 12:52:52.415  3009  3020 I SurfaceFlinger: Modify SurfaceFlinger's phase offset to 0
12-19 12:52:52.415  9263  9263 I InjectionManager: Inside getClassLibPath caller 
12-19 12:52:52.415  3455  6024 D GameManagerService: identifyGamePackage. com.test.thalitest
12-19 12:52:52.415  3455  6024 D GameManagerService: identifyGamePackage. com.test.thalitest
12-19 12:52:52.425  3455  6024 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
12-19 12:52:52.425  9263  9263 D InjectionManager: InjectionManager
12-19 12:52:52.425  9263  9263 D InjectionManager: fillFeatureStoreMap com.test.thalitest
12-19 12:52:52.425  9263  9263 I InjectionManager: Constructor com.test.thalitest, Feature store :{}
12-19 12:52:52.425  9263  9263 I InjectionManager: featureStore :{}
12-19 12:52:52.425  3455  6024 D GameManagerService: identifyGamePackage. com.test.thalitest
12-19 12:52:52.425  3455  6024 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
12-19 12:52:52.425  9263  9263 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.test.thalitest rsrc of package com.test.thalitest
12-19 12:52:52.425  3455  6024 D GameManagerService: identifyGamePackage. com.test.thalitest
12-19 12:52:52.425  3455  6024 D GameManagerService: identifyGamePackage. com.test.thalitest
12-19 12:52:52.425  9263  9263 D ContextRelationManager: ContextRelationManager() : FEATURE_ENABLED=true
12-19 12:52:52.425  9263  9263 D RelationGraph: garbageCollect()
12-19 12:52:52.425  9263  9263 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.test.thalitest rsrc of package com.test.thalitest
12-19 12:52:52.435  9263  9263 I CordovaLog: Changing log level to DEBUG(3)
12-19 12:52:52.435  9263  9263 I CordovaActivity: Apache Cordova native platform version 6.0.0 is starting
12-19 12:52:52.435  9263  9263 D CordovaActivity: CordovaActivity.onCreate()
12-19 12:52:52.445  9263  9263 I WebViewFactory: Loading com.google.android.webview version 50.0.2661.86 (code 266108650)
12-19 12:52:52.455  9263  9263 W ResourcesManager: getTopLevelResources: /system/app/WebViewGoogle/WebViewGoogle.apk / 1.0 running in com.test.thalitest rsrc of package com.google.android.webview
12-19 12:52:52.455  9263  9263 D ResourcesManager: For user 0 new overlays fetched Null
12-19 12:52:52.455  9263  9263 I InjectionManager: Inside getClassLibPath caller 
12-19 12:52:52.455  9263  9263 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
12-19 12:52:52.485  9263  9263 I cr_LibraryLoader: Time to load native libraries: 19 ms (timestamps 3490-3509)
12-19 12:52:52.485  9263  9263 I cr_LibraryLoader: Expected native library version number "50.0.2661.86", actual native library version number "50.0.2661.86"
12-19 12:52:52.505  9263  9277 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.test.thalitest/shared_prefs/WebViewChromiumPrefs.xml.bak
12-19 12:52:52.525  9263  9263 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {14d35a7}
12-19 12:52:52.525  9263  9263 I cr_LibraryLoader: Expected native library version number "50.0.2661.86", actual native library version number "50.0.2661.86"
12-19 12:52:52.535  9263  9263 I chromium: [INFO:library_loader_hooks.cc(143)] Chromium logging enabled: level = 0, default verbosity = 0
,12-19 12:52:52.565  9263  9263 I cr_BrowserStartup: Initializing chromium process, singleProcess=true
,12-19 12:52:52.645  9263  9263 D libEGL  : eglInitialize EGLDisplay = 0xffc54f44
,12-19 12:52:52.655  3455  3872 D MdnieScenarioControlService:  packageName : com.test.thalitest    className : com.test.thalitest.MainActivity
,12-19 12:52:52.685  3455  4077 D ActivityManager: The following uid has registered to recieve broadcast for proxy related updates 10074
12-19 12:52:52.685  3455  4077 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:845 com.android.server.am.ActivityManagerService.requestKnoxVpnToSendProxyBroadcast:29757 com.android.server.am.ActivityManagerService.registerReceiver:22622 android.app.ActivityManagerNative.onTransact:431 com.android.server.am.ActivityManagerService.onTransact:3990 
,12-19 12:52:52.705  3455  3847 D NetworkPolicy: isUidForegroundLocked: 10019, mScreenOn: true, uidstate: 2, mProxSensorScreenOff: false
,12-19 12:52:52.725  9263  9263 D ConnectivityManager: requestNetwork; getAppId(CallingUid) : 10074, CallingPid : 9263
,12-19 12:52:52.725  3455  4077 D ConnectivityService: listenForNetwork for Listen from uid/pid:10074/9263 for NetworkRequest [ id=8, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,12-19 12:52:52.725  3455  3859 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 502]
12-19 12:52:52.725  3455  3859 D ConnectivityService:  network has: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::4e66:41ff:fea9:1541/64,192.168.1.137/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,2097120,524288,1048576,4194240}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN&VALIDATED LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -43]}  Score{60}  everValidated{true}  lastValidated{true}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,12-19 12:52:52.725  3455  3859 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 502] was already satisfying request 1. No change.
,12-19 12:52:52.735  3455  3859 D ConnectivityService:   checking if request is: NetworkRequest [ id=4, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
,12-19 12:52:52.735  3455  3859 D ConnectivityService:   checking if request is: NetworkRequest [ id=3, legacyType=-1, [ Transports: CELLULAR Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: false nri.isRequest: false
,12-19 12:52:52.735  3455  3859 D ConnectivityService:   checking if request is: NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
,12-19 12:52:52.735  3455  3859 D ConnectivityService:   checking if request is: NetworkRequest [ id=8, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
,12-19 12:52:52.735  9263  9263 D cr_Ime  : [InputMethodManagerWrapper.java:30] Constructor
,12-19 12:52:52.735  3455  3859 D ConnectivityService:   checking if request is: NetworkRequest [ id=5, legacyType=-1, [] ] satisfies: true nri.isRequest: false
,12-19 12:52:52.735  3455  3859 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=8, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,12-19 12:52:52.745  9263  9263 W cr_AwContents: onDetachedFromWindow called when already detached. Ignoring
,12-19 12:52:52.745  9263  9263 D cr_Ime  : [InputMethodManagerWrapper.java:59] isActive: false
,12-19 12:52:52.755  3455  3872 I MdnieScenarioControlService: mGameModeLauncher : false
,12-19 12:52:52.755  3455  3872 I MdnieScenarioControlService: setUIMode
,12-19 12:52:52.765  9263  9263 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
,12-19 12:52:52.765  9263  9263 D PluginManager: init()
,12-19 12:52:52.765  9263  9263 D CordovaWebViewImpl: >>> loadUrl(file:///android_asset/www/index.html)
,12-19 12:52:52.765  3009  3018 I SurfaceFlinger: id=10 Removed MauncherAct (5/11)
12-19 12:52:52.765  3009  4467 I SurfaceFlinger: id=10 Removed MauncherAct (-2/11)
,12-19 12:52:52.775  3929  3929 D ImageWallpaper: onVisibilityChanged:false
,12-19 12:52:52.775  3929  3929 D ImageWallpaper: drawFrame:false rotation:0 mLastRotation:0
,12-19 12:52:52.775  3929  3929 D ImageWallpaper: drawFrame:[frame.width()]2240[frame.height()]2560
12-19 12:52:52.775  3929  3929 D ImageWallpaper: Suppressed drawFrame since redraw is not needed and offsets have not changed.
,12-19 12:52:52.775  9263  9263 I cr_Ime  : ImeThread is not enabled.
,12-19 12:52:52.785  9263  9263 D Activity: performCreate Call Injection manager
12-19 12:52:52.785  3009  3009 D libEGL  : eglTerminate EGLDisplay = 0x7fe591eaa8
,12-19 12:52:52.785  9263  9263 D CordovaActivity: Started the activity.
12-19 12:52:52.785  9263  9263 I InjectionManager: dispatchOnViewCreated > Target : com.test.thalitest.MainActivity isFragment :false
12-19 12:52:52.785  9263  9263 D CordovaActivity: Resumed the activity.
,12-19 12:52:52.785  9263  9263 D SecWifiDisplayUtil: Metadata value : SecSettings2
12-19 12:52:52.795  9263  9263 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{f2c9a52 I.E...... R.....ID 0,0-0,0}
12-19 12:52:52.795  9263  9312 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
12-19 12:52:52.795  3455  3473 D ISSUE_DEBUG: InputChannelName : fc939ba com.test.thalitest/com.test.thalitest.MainActivity
12-19 12:52:52.795  3455  3844 D ActivityManager: post active user change for 0 fullscreen true isFloatingActivity() false isHomeActivity() false
12-19 12:52:52.795  3455  3844 D KnoxTimeoutHandler: postActiveUserChange [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
12-19 12:52:52.795  3455  3455 D KnoxTimeoutHandler: handleActiveUserChange [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
12-19 12:52:52.795  3455  3455 I KnoxTimeoutHandler: Shared devices show user statefalse
12-19 12:52:52.805  9263  9263 D ConnectivityManager: requestNetwork; getAppId(CallingUid) : 10074, CallingPid : 9263
12-19 12:52:52.805  9263  9277 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.test.thalitest/shared_prefs/com.test.thalitest_preferences.xml.bak
12-19 12:52:52.805  3455  4898 D ConnectivityService: listenForNetwork for Listen from uid/pid:10074/9263 for NetworkRequest [ id=9, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
12-19 12:52:52.805  3455  3859 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 502]
12-19 12:52:52.805  3455  3859 D ConnectivityService:  network has: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::4e66:41ff:fea9:1541/64,192.168.1.137/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,2097120,524288,1048576,4194240}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN&VALIDATED LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -43]}  Score{60}  everValidated{true}  lastValidated{true}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
12-19 12:52:52.805  3455  3859 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 502] was already satisfying request 1. No change.
12-19 12:52:52.815  3455  3859 D ConnectivityService:   checking if request is: NetworkRequest [ id=4, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
12-19 12:52:52.815  3455  3847 D NetworkPolicy: isUidForegroundLocked: 10019, mScreenOn: true, uidstate: 6, mProxSensorScreenOff: false
12-19 12:52:52.815  3455  3859 D ConnectivityService:   checking if request is: NetworkRequest [ id=3, legacyType=-1, [ Transports: CELLULAR Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: false nri.isRequest: false
,12-19 12:52:52.815  3455  3859 D ConnectivityService:   checking if request is: NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
,12-19 12:52:52.815  3455  3859 D ConnectivityService:   checking if request is: NetworkRequest [ id=8, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
,12-19 12:52:52.815  9263  9263 D SecWifiDisplayUtil: Metadata value : SecSettings2
,12-19 12:52:52.825  3455  3859 D ConnectivityService:   checking if request is: NetworkRequest [ id=9, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
,12-19 12:52:52.825  3455  3859 D ConnectivityService:   checking if request is: NetworkRequest [ id=5, legacyType=-1, [] ] satisfies: true nri.isRequest: false
,12-19 12:52:52.825  3455  3859 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=9, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,12-19 12:52:52.825  3009  3009 I SurfaceFlinger: id=15 createSurf (1x1),1 flag=404, NainActivit
,12-19 12:52:52.835  3455  4289 D InputDispatcher: Focus entered window: 9263
,12-19 12:52:52.835  3455  3571 D PointerIcon: setMouseIconStyle1 pointerType: 1001 iconType:101 flag:0 pid:3455 uid:1000
12-19 12:52:52.835  3455  3571 D PointerIcon: setMouseCustomIcon IconType is same.101
12-19 12:52:52.835  9263  9312 D libEGL  : eglInitialize EGLDisplay = 0xdd33f7c4
12-19 12:52:52.835  9263  9312 I OpenGLRenderer: Initialized EGL, version 1.4
,12-19 12:52:52.835  9263  9312 D mali_winsys: EGLint new_window_surface(egl_winsys_display*, void*, EGLSurface, EGLConfig, egl_winsys_surface**, egl_color_buffer_format*, EGLBoolean) returns 0x3000,  [1440x2560]-format:1
,12-19 12:52:52.855  9263  9263 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 96 - 0, 0) vi=Rect(0, 96 - 0, 0) or=1
,12-19 12:52:52.855  9263  9263 W DisplayListCanvas: DisplayListCanvas is started on unbinded RenderNode (without mOwningView)
,12-19 12:52:52.865  9263  9316 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
12-19 12:52:52.865  9263  9316 D libEGL  : eglInitialize EGLDisplay = 0xdbcef3e4
,12-19 12:52:52.875  9263  9316 D libGLESv2: DTS_GLAPI : DTS is not allowed for Package : com.test.thalitest
,12-19 12:52:52.885  3455  4262 V WindowStateAnimator: Finishing drawing window Window{fc939ba u0 d0 com.test.thalitest/com.test.thalitest.MainActivity}: mDrawState=DRAW_PENDING
,12-19 12:52:52.895  3455  4534 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,12-19 12:52:52.895  3455  3571 D KnoxTimeoutHandler: notifyActivityDrawn [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
12-19 12:52:52.895  3455  3455 D KnoxTimeoutHandler: activityDrawn [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
,12-19 12:52:52.895  3455  3571 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +562ms
,12-19 12:52:52.895  3455  3571 D CustomFrequencyManagerService: releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1872000  uid : 1000  pid : 3455  tag : ACTIVITY_RESUME_BOOSTER@3
12-19 12:52:52.895  3455  3455 I KnoxTimeoutHandler: SD activityfalse
12-19 12:52:52.895  3455  3571 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{54a7a23 u0 com.test.thalitest/.MainActivity t170} time:63915
12-19 12:52:52.895  3455  3571 D ActivityManager: mDVFSHelper.release()
12-19 12:52:52.895  3455  3571 D ViewRootImpl: #3 mView = null
,12-19 12:52:52.895  3455  3534 D CustomFrequencyManagerService: acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1872000  uid : 1000  pid : 3455  pkgName : ACTIVITY_RESUME_BOOSTER@9
,12-19 12:52:52.905  4782  4782 D SamsungIME: IMPL finishInput
,12-19 12:52:52.905  4782  4782 D SamsungIME: SwiftKeyWrapper writeDBdataToFileOnFinishInput
12-19 12:52:52.905  4782  4782 D SamsungIME: saveAndClear +
12-19 12:52:52.905  4782  4782 D SamsungIME: saveAndClear -
12-19 12:52:52.905  3009  3009 D libEGL  : eglInitialize EGLDisplay = 0x7fe591e988
,12-19 12:52:52.905  9263  9263 D CordovaWebViewImpl: onPageDidNavigate(file:///android_asset/www/index.html)
,12-19 12:52:52.905  9263  9263 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@15a729a time:63927
,12-19 12:52:52.915  9263  9263 W cr_BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 9263
,12-19 12:52:52.915  9263  9263 D cr_Ime  : [InputMethodManagerWrapper.java:59] isActive: true
12-19 12:52:52.915  9263  9263 D cr_Ime  : [InputMethodManagerWrapper.java:68] hideSoftInputFromWindow
,12-19 12:52:52.915  4250  4250 D Launcher.HomeView: onStop
12-19 12:52:52.915  4250  4250 D capture : ----destroy
,12-19 12:52:52.915  4250  4250 V ActivityThread: updateVisibility : ActivityRecord{8c2be4a token=android.os.BinderProxy@d51bab7 {com.sec.android.app.launcher/com.sec.android.app.launcher.activities.LauncherActivity}} show : false
12-19 12:52:52.915  4250  4250 D Launcher: onTrimMemory. Level: 20
,12-19 12:52:52.915  3009  3009 D libEGL  : eglInitialize EGLDisplay = 0x7fe591e988
,12-19 12:52:52.955  3009  3009 D libEGL  : eglInitialize EGLDisplay = 0x7fe591e988
,12-19 12:52:53.025  9263  9263 D JsMessageQueue: Set native->JS mode to EvalBridgeMode
,12-19 12:52:53.035  3455  6024 D SSRM:n  : SIOP:: AP = 380, PST = 440 (W:5), CP = 304, CUR = 67, LCD = 40
,12-19 12:52:53.085  9263  9325 D jxcore_app_log: JniHelper::setJavaVM(0xf4934000), pthread_self() = -670041808
,12-19 12:52:53.085  3009  4467 I SurfaceFlinger: id=14 Removed uhalitest (7/11)
12-19 12:52:53.085  3009  3831 I SurfaceFlinger: id=14 Removed uhalitest (-2/11)
,12-19 12:52:53.095  9263  9263 D CordovaWebViewImpl: onPageFinished(file:///android_asset/www/index.html)
,12-19 12:52:53.095  9263  9263 D SystemWebChromeClient: file:///android_asset/www/js/index.js: Line 36 : Uncaught TypeError: Cannot read property 'querySelector' of null
12-19 12:52:53.095  9263  9263 I chromium: [INFO:CONSOLE(36)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (36)
,12-19 12:52:53.105  3009  3009 D libEGL  : eglTerminate EGLDisplay = 0x7fe591eaa8
,12-19 12:52:53.145  3455  6056 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,12-19 12:52:53.175  3455  3872 D MdnieScenarioControlService:  packageName : com.test.thalitest    className : com.test.thalitest.MainActivity
,12-19 12:52:53.195  3455  3455 D CustomFrequencyManagerService: releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1872000  uid : 1000  pid : 3455  tag : ACTIVITY_RESUME_BOOSTER@9
,12-19 12:52:53.275  3455  3872 I MdnieScenarioControlService: mGameModeLauncher : false
,12-19 12:52:53.275  3455  3872 I MdnieScenarioControlService: setUIMode
,12-19 12:52:53.355  4017  4017 D Recents : onTaskStackChanged
,12-19 12:52:53.355  4017  4017 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.android.systemui rsrc of package com.test.thalitest
,12-19 12:52:53.365  4017  4017 D ResourcesManager: For user 0 new overlays fetched Null
,12-19 12:52:53.375  4585  9327 W IcingInternalCorpora: getNumBytesRead when not calculated.
,12-19 12:52:53.405  3455  6025 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in null rsrc of package com.test.thalitest
,12-19 12:52:53.495  9263  9326 W jxcore-log: Initializing JXcore engine
12-19 12:52:53.495  9263  9326 W jxcore-log: JXcore engine is ready
,12-19 12:52:53.515  4844  4844 E audit   : type=1400 msg=audit(1482148373.515:264): avc:  denied  { ioctl } for  pid=9326 comm="Thread-138" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2123 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
12-19 12:52:53.515  4844  4844 E audit   :  SEPF_SECMOBILE_6.0.1_0031
12-19 12:52:53.515  4844  4844 E audit   : type=1300 msg=audit(1482148373.515:264): arch=40000028 syscall=54 per=8 success=no exit=-13 a0=8 a1=5451 a2=4 a3=d75053c8 items=0 ppid=3177 pid=9326 auid=4294967295 uid=10074 gid=10074 euid=10074 suid=10074 fsuid=10074 egid=10074 sgid=10074 fsgid=10074 tty=(none) ses=4294967295 comm="Thread-138" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0:c512,c768 key=(null)
12-19 12:52:53.515  4844  4844 E audit   : type=1327 msg=audit(1482148373.515:264): proctitle="com.test.thalitest"
12-19 12:52:53.515  4844  4844 E audit   : type=1320 msg=audit(1482148373.515:264): 
12-19 12:52:53.515  4844  4844 E audit   : type=1400 msg=audit(1482148373.515:265): avc:  denied  { ioctl } for  pid=9326 comm="Thread-138" path="socket:[37901]" dev="sockfs" ino=37901 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
12-19 12:52:53.515  4844  4844 E audit   :  SEPF_SECMOBILE_6.0.1_0031
12-19 12:52:53.515  4844  4844 E audit   : type=1300 msg=audit(1482148373.515:265): arch=40000028 syscall=54 per=8 success=no exit=-13 a0=33 a1=5451 a2=4 a3=d75053c8 items=0 ppid=3177 pid=9326 auid=4294967295 uid=10074 gid=10074 euid=10074 suid=10074 fsuid=10074 egid=10074 sgid=10074 fsgid=10074 tty=(none) ses=4294967295 comm="Thread-138" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0:c512,c768 key=(null)
12-19 12:52:53.515  4844  4844 E audit   : type=1327 msg=audit(1482148373.515:265): proctitle="com.test.thalitest"
12-19 12:52:53.515  4844  4844 E audit   : type=1320 msg=audit(1482148373.515:265): 
,12-19 12:52:53.515  9263  9326 W jxcore-log: Starting JXcore engine
,12-19 12:52:53.555  9263  9326 W jxcore-log: Platform android
12-19 12:52:53.555  9263  9326 W jxcore-log: 
12-19 12:52:53.555  9263  9326 W jxcore-log: Process ARCH arm
12-19 12:52:53.555  9263  9326 W jxcore-log: 
,12-19 12:52:53.655  9263  9326 I jxcore-log: JXcore Cordova bridge is ready!
12-19 12:52:53.655  9263  9326 I jxcore-log: 
12-19 12:52:53.655  9263  9326 W jxcore-log: JXcore engine is started
,12-19 12:52:55.335  3455  3898 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/recent_tasks/170_task.xml.bak
,12-19 12:52:55.415  3455  6024 D GameManagerService: identifyGamePackage. com.test.thalitest
,12-19 12:52:56.605  9113  9330 W System.err: mkdir failed: EEXIST (File exists) : /data/user/0/com.google.android.apps.docs/files/shiny_blobs/blobs
12-19 12:52:56.605  9113  9330 W System.err: mkdir failed: EEXIST (File exists) : /data/user/0/com.google.android.apps.docs/files/shiny_blobs/blobs_in_construction
,12-19 12:52:56.645  9113  9129 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.google.android.apps.docs/databases/ClientFlag.db
12-19 12:52:56.645  9113  9129 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.google.android.apps.docs/databases/ClientFlag.db-journal
,12-19 12:52:56.645  9113  9129 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.google.android.apps.docs/databases/ClientFlag.db-shm
12-19 12:52:56.645  9113  9129 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.google.android.apps.docs/databases/ClientFlag.db-wal
,12-19 12:52:56.685  9113  9129 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in com.google.android.apps.docs rsrc of package com.google.android.gms
,12-19 12:52:56.685  9113  9129 D ResourcesManager: For user 0 new overlays fetched Null
,12-19 12:52:56.695  9113  9129 I InjectionManager: Inside getClassLibPath caller 
,12-19 12:52:56.705  9113  9129 W System  : ClassLoader referenced unknown path: /system/priv-app/GmsCore/lib/arm64
,12-19 12:52:56.765  9113  9129 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 255 native methods...
,12-19 12:52:56.785  9113  9129 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,12-19 12:52:57.975  3455  3534 I ActivityManager: Waited long enough for: ServiceRecord{25e90eb u0 com.samsung.voiceserviceplatform/com.samsung.vsf.core.framework.VoiceFrameworkService}
,12-19 12:52:58.145  3455  6056 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,12-19 12:52:58.445  3455  6024 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,12-19 12:52:59.635  9263  9326 E JX-Cordova: JavaCall recevied a call for unknown method didRegisterToNative
12-19 12:52:59.635  9263  9326 E JX-Cordova: JavaCall recevied a call for unknown method didRegisterToNative
12-19 12:52:59.635  9263  9326 E JX-Cordova: JavaCall recevied a call for unknown method didRegisterToNative
12-19 12:52:59.645  9263  9326 E JX-Cordova: JavaCall recevied a call for unknown method didRegisterToNative
,12-19 12:52:59.795  9263  9326 E JX-Cordova: JavaCall recevied a call for unknown method executeNativeTests
12-19 12:52:59.795  9263  9326 I jxcore-log: Failed to execute UT.
12-19 12:52:59.795  9263  9326 I jxcore-log: 
,12-19 12:52:59.795  9263  9326 I jxcore-log: 2016-12-19 11:52:59 - DEBUG UnitTest_app: 'Failed to execute UT.'
12-19 12:52:59.795  9263  9326 I jxcore-log: 
12-19 12:52:59.795  9263  9326 I jxcore-log: 2016-12-19 11:52:59 - DEBUG UnitTest_app: 'Unit Test app is loaded'
12-19 12:52:59.795  9263  9326 I jxcore-log: 
,12-19 12:52:59.815  9263  9263 D SystemWebChromeClient: file:///android_asset/www/js/thali_main.js: Line 68 : UIApp is all set and ready!
,12-19 12:52:59.815  9263  9263 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
,12-19 12:52:59.995  3455  3806 V AlarmManager: Expired Alarm result :8
,12-19 12:53:00.005  3929  3929 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
12-19 12:53:00.005  3929  3929 D KeyguardUpdateMonitor: handleTimeUpdate
,12-19 12:53:00.015  3929  3929 D Clock   : received broadcast android.intent.action.TIME_TICK
,12-19 12:53:00.085  3929  3929 D DateView: received broadcast android.intent.action.TIME_TICK
,12-19 12:53:00.115  4693  4693 D [Weather Widget]  WeatherService: {[EC3334F14841398C8B464A72D0E61AB7C564889C89112557F2146D56794659083956C77974A4825103AB5C5D4AC85EDAA24236388AC138058106446B92A35777]}
,12-19 12:53:00.115  4693  4693 D [Weather Widget]  : {[3AE6950019B083611567B0F9442DB03EEFA9050249635C043F7E254E316C2550]}
,12-19 12:53:00.115  4693  4693 D [Weather Widget]  : {[3AE6950019B083611567B0F9442DB03EAB01DC5C99149A39F887E17599325AFBFF089086AA9902184ADA25758C536FE2]}
,12-19 12:53:00.125  4693  4693 D [Weather Widget]  : {[3AE6950019B083611567B0F9442DB03EFF0B905BDFF72B69FB632A6CB072B41F95D2E6F4F84443284E97F40042D431D8350388453A923ABD8469D82798FA7548]}
,12-19 12:53:00.125  4693  4693 D [Weather Widget]  : {[A1AF0F6A1A65A89C43D705938923D0FEFB71880C4E84718DA0A3E1F383E54FB27A4284D9BEDF7BAA2ABFFE671EB65C640578FF9DE16A23BFE3280A9DCDBB09A02B0671077C7106D78CB8F8AA7271B61687D5A2DB0728818D2FACBA6D466417F21B2EEAB14C27FA7B76D3321C20617608]}
,12-19 12:53:00.125  4693  4693 W [Weather Widget]  : {[15CF912BDCF42F9CFB4A85BDA543B9C03270F5FAA9F5676E82AF8C619BCF91CE5FB3CE2082F25CD9A43F9287628E184E1B535DD573D2968B1284E288CF459C13DF414A1402CD333D136FA7792C603AC4]}
,12-19 12:53:00.125  4693  4693 D [Weather Widget]  AutoRefresh: {[9BDBD671986BB5350BB30F5195E2700D025AD0AB6B43765153FE15B38684E558D03F28FB0B91AB39310ABEC4D7D82D6E635843040DF4C0F1B9C2397CFFDE153E031020FC4E2C26F3A31388ED7A346963]}
,12-19 12:53:00.125  4693  4693 D [Weather Widget]  : {[15C09394A4E9AFE55A5C62F22AB3FC5902EB2A2150B6646A86F2B3102D669614]}
,12-19 12:53:01.755  3455  3966 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,12-19 12:53:01.755  3455  3966 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4349, temperature: 293, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
12-19 12:53:01.755  3455  3966 D BatteryService: online:4, current avg:-36, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:395
12-19 12:53:01.755  3455  3455 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,12-19 12:53:01.755  3455  3455 I MotionRecognitionService: Plugged
12-19 12:53:01.755  3455  3455 D MotionRecognitionService:   cableConnection= 1
12-19 12:53:01.755  3455  3455 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
12-19 12:53:01.755  3455  3455 D MotionRecognitionService: skip setTransmitPower. 
,12-19 12:53:01.765  3455  3852 D WifiController: ApOrStaEnabledState  msg.what= 155652
,12-19 12:53:01.765  3929  3929 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,12-19 12:53:01.765  3929  3929 D KeyguardUpdateMonitor: handleBatteryUpdate
,12-19 12:53:01.765  3929  3929 D PowerUI : priorPlugType = 2 mPlugType =  2
,12-19 12:53:01.785  3929  3929 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,12-19 12:53:01.785  4883  4883 D CommonServiceConfiguration: getStringValueSetting
,12-19 12:53:01.795  4838  4838 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,12-19 12:53:01.795  4838  5195 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,12-19 12:53:01.805  3929  3929 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,12-19 12:53:01.815  4883  4883 D BatteryMonitor: new battery level: 100
,12-19 12:53:01.945  3929  3929 V KeyguardUpdateMonitor: onSubscriptionInfoChanged()
,12-19 12:53:01.955  3929  3929 V KeyguardUpdateMonitor: onSubscriptionInfoChanged: list is null
,12-19 12:53:01.955  3929  3929 D KeyguardCarrierText: onRefreshCarrierInfo: 
,12-19 12:53:01.955  3929  3929 D KeyguardCarrierText: updateAllSlot
,12-19 12:53:01.965  3929  3929 D KeyguardCarrierText: updateIntentData(): isMultiSIMState: falsesubId: 2147483643 phoneId:0plmn: Brak sieciSPN: 
,12-19 12:53:01.965  3455  3473 D SecContentProvider2: query(), uri = 15 selection = getLockScreenHiddenItems
,12-19 12:53:01.975  3929  3929 D KeyguardCarrierText: updateCarrierText(): isMultiSIMState: false
,12-19 12:53:01.975  3929  3929 D KeyguardCarrierText: updateDate All slot
,12-19 12:53:01.975  3929  3929 D KeyguardCarrierText: mSimState[0]ABSENT
12-19 12:53:01.975  3929  3929 D KeyguardCarrierText: mSimState[1]ABSENT
,12-19 12:53:01.975  3929  3929 D KeyguardCarrierText: Getting plmn/spn sticky brdcst  mPlmn:Brak sieci / mSpn:  phoneId:0 subId:2147483643 showPlmn: true showSpn:false
12-19 12:53:01.975  3929  3929 D KeyguardCarrierText: getStatusForIccState :  SIM state = ABSENT
12-19 12:53:01.975  3929  3929 D KeyguardCarrierText: makeCarrierStringOnEmergencyCapable :  mIsEmergencyCallCapable:  true
,12-19 12:53:01.975  3929  3929 D KeyguardCarrierText: concatenate : plmn = Brak karty SIM, spn = Brak sieci
12-19 12:53:01.975  3929  3929 D KeyguardCarrierText: getCarrierTextForSimState :  SIM state = SimMissingcarrierText: Brak karty SIM | Brak sieci
12-19 12:53:01.975  3929  3929 D KeyguardCarrierText: Handling ABSENT , carrierTextForSimState = Brak karty SIM | Brak sieci
,12-19 12:53:01.985  3929  3929 D KeyguardCarrierText: updateCarrierText insertedMultiSim = false
,12-19 12:53:01.985  3929  3929 D KeyguardCarrierText: updateCarrierText State: Absent SIM Number = 0
,12-19 12:53:01.985  3929  3929 D KeyguardCarrierText: Getting plmn/spn sticky brdcst for Absent case Brak sieci/showPlmn: trueshowSpn: false phoneId:0 subId:2147483643
,12-19 12:53:01.985  3929  3929 D KeyguardCarrierText: concatenate : plmn = Brak sieci
12-19 12:53:01.985  3929  3929 D KeyguardCarrierText: makeCarrierStringOnEmergencyCapable :  mIsEmergencyCallCapable:  true
12-19 12:53:01.985  3929  3929 D KeyguardCarrierText: concatenate : plmn = Brak karty SIM, spn = Brak sieci
,12-19 12:53:01.985  3929  3929 D KeyguardCarrierText: setText :  displayText = Tryb Offline
12-19 12:53:01.985  3929  3929 D EmergencyButton: onRefreshCarrierInfo
,12-19 12:53:02.375  3455  3593 D PackageManager: [MSG] WRITE_PACKAGE_RESTRICTIONS
12-19 12:53:02.375  3455  3806 V AlarmManager: Expired Alarm result :4
,12-19 12:53:02.395  3455  3593 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/users/0/package-restrictions.xml.bak
,12-19 12:53:02.435  8577  8621 W Finsky  : [862] com.google.android.finsky.FinskyApp.i(1379): No account configured on this device.
,12-19 12:53:02.435  8577  8621 I Finsky  : [862] com.google.android.finsky.c.e.run(1151): Replicating app states via AMAS.
,12-19 12:53:02.605  3455  4123 E Watchdog: !@Sync 2 [12-19 12:53:02.616]
,12-19 12:53:03.065  3455  6024 D SSRM:n  : SIOP:: AP = 390, PST = 431 (W:6), CP = 303, CUR = -36, LCD = 40
,12-19 12:53:03.145  3455  6056 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,12-19 12:53:03.265  8577  8621 I Finsky  : [862] com.google.android.finsky.c.c.a(311): Completed 0 account content syncs with 0 successful.
,12-19 12:53:03.265  8577  8577 I Finsky  : [1] com.google.android.finsky.services.j.a(149): Installation state replication succeeded.
,12-19 12:53:03.805  4336  4435 D ContactsProvider_EventLog: contents_sample_state: [ contacts(0) data(0) accounts({}) accounts deleted({}) calls([])  ]
12-19 12:53:03.805  4336  4435 D ContactsProvider_EventLog: contents_sample_state: [ agr({})  ]
,12-19 12:53:05.865  3455  4926 V MARsPolicyManager: updatePackagesScore PackageInfo name -- null
,12-19 12:53:05.865  3455  4926 V MARsPolicyManager: updateSMDBValues
,12-19 12:53:05.865  3455  3566 E MARsDBManager: updateDBAll : begin --size 0
12-19 12:53:05.865  3455  3566 E MARsDBManager: updateDBAll : end
,12-19 12:53:08.145  3455  6056 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,12-19 12:53:11.805  3455  4262 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
12-19 12:53:11.805  3455  4262 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4350, temperature: 294, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
12-19 12:53:11.805  3455  4262 D BatteryService: online:4, current avg:181, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:296
12-19 12:53:11.805  3455  3455 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,12-19 12:53:11.815  3455  3455 I MotionRecognitionService: Plugged
,12-19 12:53:11.815  3455  3455 D MotionRecognitionService:   cableConnection= 1
12-19 12:53:11.815  3455  3455 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
12-19 12:53:11.815  3455  3455 D MotionRecognitionService: skip setTransmitPower. 
12-19 12:53:11.825  3455  3852 D WifiController: ApOrStaEnabledState  msg.what= 155652
12-19 12:53:11.825  3929  3929 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
12-19 12:53:11.825  3929  3929 D KeyguardUpdateMonitor: handleBatteryUpdate
12-19 12:53:11.825  3929  3929 D PowerUI : priorPlugType = 2 mPlugType =  2
,12-19 12:53:11.845  4883  4883 D CommonServiceConfiguration: getStringValueSetting
,12-19 12:53:11.845  4838  4838 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
12-19 12:53:11.845  4838  5195 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,12-19 12:53:11.855  3929  3929 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,12-19 12:53:11.865  4883  4883 D BatteryMonitor: new battery level: 100
12-19 12:53:11.865  3929  3929 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,12-19 12:53:13.085  3455  6024 D SSRM:n  : SIOP:: AP = 350, PST = 420 (W:7), CP = 294, CUR = 181, LCD = 40
,12-19 12:53:13.155  3455  6056 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,12-19 12:53:14.905  6112  6112 D FactoryTest: User mode
,12-19 12:53:14.905  6112  6112 D MTPRx   : DRIVER_TIME_OUT 60s lapsed
12-19 12:53:14.905  6112  6112 D MTPRx   : still no open session command from host, so toast
,12-19 12:53:14.925  3455  4289 D VirtualScreenPolicy: applyVirtualScreenAttrs attrs=VirtualScreenAttrs{mDisplayId=0, mBaseDisplayId=0, mBaseActivity=false}
,12-19 12:53:14.925  3455  4289 W ResourcesManager: getTopLevelResources: /system/priv-app/MtpApplication/MtpApplication.apk / 1.0 running in null rsrc of package com.samsung.android.MtpApplication
,12-19 12:53:14.935  3455  4289 D ResourcesManager: For user 0 new overlays fetched Null
,12-19 12:53:14.935  3455  4289 D GameManagerService: identifyGamePackage. com.samsung.android.MtpApplication
,12-19 12:53:14.935  3455  4289 D MultiWindowPolicy: Gamemode - return 0,  when calling  identifyForegroundApp(com.samsung.android.MtpApplication)
12-19 12:53:14.935  3455  4289 D CustomFrequencyManagerService: acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1872000  uid : 1000  pid : 3455  pkgName : ACTIVITY_RESUME_BOOSTER@3
,12-19 12:53:14.945  3455  4289 D ActivityManager: mDVFSHelper.acquire()
,12-19 12:53:14.945  3455  4289 V WindowManager: addAppToken: AppWindowToken{d0e801d1a token=Token{383ffc5 ActivityRecord{6b2663c u0 com.samsung.android.MtpApplication/.USBConnection t171}}} to stack=2 task=171 at 0
,12-19 12:53:14.945  3009  3831 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (174 us)
,12-19 12:53:14.955  3455  4289 D InputDispatcher: Focused application set to: xxxx
,12-19 12:53:14.955  3455  4289 D InputDispatcher: Focus left window: 9263
,12-19 12:53:14.955  6112  6112 E MTPRx   : started activity for popup
,12-19 12:53:14.965  9263  9263 D CordovaActivity: Paused the activity.
,12-19 12:53:14.965  3455  3571 D PointerIcon: setMouseIconStyle1 pointerType: 1001 iconType:101 flag:0 pid:3455 uid:1000
12-19 12:53:14.965  3455  3571 D PointerIcon: setMouseCustomIcon IconType is same.101
,12-19 12:53:14.965  3455  4144 D ActivityManager:  Launching com.samsung.android.MtpApplication, updated priority
,12-19 12:53:14.965  3455  3534 V MARsPolicyManager: updatePackagesScore PackageInfo name -- com.samsung.android.MtpApplication
,12-19 12:53:14.965  3455  3455 D GameManagerService: NotifyRunnable. pkg: com.samsung.android.MtpApplication, type: 4, isMinimized: false, isTunableApp: false
,12-19 12:53:14.965  6112  6112 W ResourcesManager: getTopLevelResources: /system/priv-app/MtpApplication/MtpApplication.apk / 1.0 running in com.samsung.android.MtpApplication rsrc of package com.samsung.android.MtpApplication
,12-19 12:53:14.975  6112  6112 D ContextRelationManager: ContextRelationManager() : FEATURE_ENABLED=true
,12-19 12:53:14.975  6112  6112 D RelationGraph: garbageCollect()
12-19 12:53:14.975  3455  6024 D GameManagerService: identifyGamePackage. com.samsung.android.MtpApplication
,12-19 12:53:14.975  6112  6112 W ResourcesManager: getTopLevelResources: /system/priv-app/MtpApplication/MtpApplication.apk / 1.0 running in com.samsung.android.MtpApplication rsrc of package com.samsung.android.MtpApplication
,12-19 12:53:14.975  3455  6024 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
12-19 12:53:14.975  3455  6024 D GameManagerService: identifyGamePackage. com.samsung.android.MtpApplication
,12-19 12:53:14.985  3455  6024 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,12-19 12:53:14.985  3455  6024 D GameManagerService: identifyGamePackage. com.samsung.android.MtpApplication
,12-19 12:53:14.985  3455  6024 D GameManagerService: identifyGamePackage. com.samsung.android.MtpApplication
,12-19 12:53:14.985  6112  6112 D MTPUSBConnection: onCreate in USBConnection
12-19 12:53:14.985  6112  6112 V MTPUSBConnection: Registering broadcast receiver.
,12-19 12:53:14.985  6112  6112 E MTPUSBConnection: AlertDialog Mode is : TIMEOUT
,12-19 12:53:14.985  3455  3475 D SecContentProvider2: query(), uri = 14 selection = getSealedState
,12-19 12:53:15.025  6112  6112 D TAG     : dev.kiessupport is : TRUE
,12-19 12:53:15.045  6112  6112 D SecWifiDisplayUtil: Metadata value : SecSettings2
,12-19 12:53:15.045  6112  6112 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{48fa344 V.E...... R.....I. 0,0-0,0}
,12-19 12:53:15.045  3455  4387 D ISSUE_DEBUG: InputChannelName : a6d3572 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection
,12-19 12:53:15.045  3455  3536 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=Window{a6d3572 u0 d0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}
12-19 12:53:15.045  3455  4387 D InputDispatcher: Focus entered window: 6112
12-19 12:53:15.045  3455  3571 D PointerIcon: setMouseIconStyle1 pointerType: 1001 iconType:101 flag:0 pid:3455 uid:1000
12-19 12:53:15.045  3455  3571 D PointerIcon: setMouseCustomIcon IconType is same.101
12-19 12:53:15.045  3929  3929 D PhoneStatusBar: setSystemUiVisibility vis=8000 mask=ffffffff oldVal=8600 newVal=8000 diff=600
,12-19 12:53:15.045  6112  6112 D Activity: performCreate Call Injection manager
,12-19 12:53:15.045  6112  6112 I InjectionManager: dispatchOnViewCreated > Target : com.samsung.android.MtpApplication.USBConnection isFragment :false
,12-19 12:53:15.045  6112  6112 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{7e9f4f I.E...... R.....I. 0,0-0,0}
,12-19 12:53:15.045  3455  3966 D ISSUE_DEBUG: InputChannelName : 2f19640 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection
,12-19 12:53:15.055  3455  3844 D ActivityManager: post active user change for 0 fullscreen false isFloatingActivity() false isHomeActivity() false
12-19 12:53:15.055  3455  3844 D KnoxTimeoutHandler: postActiveUserChange [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
,12-19 12:53:15.055  3455  3455 D KnoxTimeoutHandler: handleActiveUserChange [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
,12-19 12:53:15.055  3455  3455 I KnoxTimeoutHandler: Shared devices show user statefalse
,12-19 12:53:15.055  3455  3455 I KnoxTimeoutHandler: Target Activity is not fullscreen. We will not show this activity0
,12-19 12:53:15.065  3009  3009 I SurfaceFlinger: id=16 createSurf (193x193),1 flag=4, VSBConnecti
,12-19 12:53:15.075  3455  3466 I art     : Background partial concurrent mark sweep GC freed 106606(7MB) AllocSpace objects, 38(940KB) LOS objects, 30% free, 35MB/51MB, paused 1.766ms total 119.207ms
,12-19 12:53:15.085  3009  3009 I SurfaceFlinger: id=17 createSurf (257x257),1 flag=4, VSBConnecti
,12-19 12:53:15.125  3455  4290 V WindowStateAnimator: Finishing drawing window Window{a6d3572 u0 d0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}: mDrawState=DRAW_PENDING
,12-19 12:53:15.125  3455  3973 V WindowStateAnimator: Finishing drawing window Window{2f19640 u0 d0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}: mDrawState=DRAW_PENDING
,12-19 12:53:15.125  6112  6112 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 0 - 0, 0) vi=Rect(0, 0 - 0, 0) or=1
12-19 12:53:15.125  6112  6112 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 0 - 0, 0) vi=Rect(0, 0 - 0, 0) or=1
,12-19 12:53:15.125  3009  3009 D libEGL  : eglInitialize EGLDisplay = 0x7fe591e988
,12-19 12:53:15.125  3009  3009 D libEGL  : eglInitialize EGLDisplay = 0x7fe591e988
,12-19 12:53:15.135  3455  3571 D KnoxTimeoutHandler: notifyActivityDrawn [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
,12-19 12:53:15.135  3455  3571 I ActivityManager: Displayed com.samsung.android.MtpApplication/.USBConnection: +171ms
12-19 12:53:15.135  3455  3455 D KnoxTimeoutHandler: activityDrawn [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
,12-19 12:53:15.135  3455  3455 I KnoxTimeoutHandler: SD activityfalse
,12-19 12:53:15.135  3455  4144 V WindowStateAnimator: Finishing drawing window Window{a6d3572 u0 d0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}: mDrawState=HAS_DRAWN
,12-19 12:53:15.135  3455  3475 V WindowStateAnimator: Finishing drawing window Window{2f19640 u0 d0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}: mDrawState=HAS_DRAWN
12-19 12:53:15.135  6112  6112 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@9e3fd8c time:86158
,12-19 12:53:15.145  3009  3009 D libEGL  : eglInitialize EGLDisplay = 0x7fe591e988
,12-19 12:53:15.225  3455  3872 D MdnieScenarioControlService:  packageName : com.samsung.android.MtpApplication    className : com.samsung.android.MtpApplication.USBConnection
,12-19 12:53:15.325  3455  3872 I MdnieScenarioControlService: mGameModeLauncher : false
,12-19 12:53:15.325  3455  3872 I MdnieScenarioControlService: setUIMode
,12-19 12:53:15.345  3455  3571 D CustomFrequencyManagerService: releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1872000  uid : 1000  pid : 3455  tag : ACTIVITY_RESUME_BOOSTER@3
,12-19 12:53:15.345  3455  3571 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{6b2663c u0 com.samsung.android.MtpApplication/.USBConnection t171} time:86369
12-19 12:53:15.345  3455  3571 D ActivityManager: mDVFSHelper.release()
,12-19 12:53:15.355  9263  9263 V ActivityThread: updateVisibility : ActivityRecord{cf61eea token=android.os.BinderProxy@15a729a {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,12-19 12:53:15.365  3455  3534 D CustomFrequencyManagerService: acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1872000  uid : 1000  pid : 3455  pkgName : ACTIVITY_RESUME_BOOSTER@9
,12-19 12:53:15.665  3455  3455 D CustomFrequencyManagerService: releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1872000  uid : 1000  pid : 3455  tag : ACTIVITY_RESUME_BOOSTER@9
,12-19 12:53:15.975  3455  6025 W ResourcesManager: getTopLevelResources: /system/priv-app/MtpApplication/MtpApplication.apk / 1.0 running in null rsrc of package com.samsung.android.MtpApplication
12-19 12:53:15.975  4017  4017 D Recents : onTaskStackChanged
,12-19 12:53:15.995  4017  4017 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.android.systemui rsrc of package com.test.thalitest
,12-19 12:53:16.015  3455  3473 D PackageManager: getComponentMetadataForIconTray : com.test.thalitest.MainActivity does not exist in mServices
,12-19 12:53:16.015  3455  3473 D PackageManager: getComponentMetadataForIconTray : com.test.thalitest.MainActivity does not exist in mProviders
12-19 12:53:16.015  3455  3473 D PackageManager: getComponentMetadataForIconTray : com.test.thalitest.MainActivity does not exist in mReceivers
12-19 12:53:16.015  4017  4017 I ApplicationPackageManager: load=com.test.thalitest, bg=192-192, dr=192-192
,12-19 12:53:16.015  4017  4017 I ApplicationPackageManager: scaled rate=0.97032255, size=192, alpha=3, hold=26, target=192
,12-19 12:53:16.775  3009  3009 D libEGL  : eglInitialize EGLDisplay = 0x7fe591e988
,12-19 12:53:18.155  3455  6056 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,12-19 12:53:21.025  3455  6024 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,12-19 12:53:21.865  3455  4387 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
12-19 12:53:21.865  3455  4387 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4349, temperature: 294, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
12-19 12:53:21.865  3455  4387 D BatteryService: online:4, current avg:226, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:255
12-19 12:53:21.865  3455  3455 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,12-19 12:53:21.865  3455  3455 I MotionRecognitionService: Plugged
12-19 12:53:21.865  3455  3455 D MotionRecognitionService:   cableConnection= 1
12-19 12:53:21.865  3455  3455 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
12-19 12:53:21.865  3455  3455 D MotionRecognitionService: skip setTransmitPower. 
,12-19 12:53:21.875  3455  3852 D WifiController: ApOrStaEnabledState  msg.what= 155652
,12-19 12:53:21.875  3929  3929 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,12-19 12:53:21.875  3929  3929 D KeyguardUpdateMonitor: handleBatteryUpdate
,12-19 12:53:21.875  3929  3929 D PowerUI : priorPlugType = 2 mPlugType =  2
,12-19 12:53:21.895  4883  4883 D CommonServiceConfiguration: getStringValueSetting
,12-19 12:53:21.895  4838  4838 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
12-19 12:53:21.895  4838  5195 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,12-19 12:53:21.905  4883  4883 D BatteryMonitor: new battery level: 100
,12-19 12:53:21.915  3929  3929 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
12-19 12:53:21.915  3929  3929 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,12-19 12:53:23.115  3455  6024 D SSRM:n  : SIOP:: AP = 330, PST = 408 (W:8), CP = 286, CUR = 226, LCD = 40
,12-19 12:53:24.335  3455  3806 V AlarmManager: Expired Alarm result :4
,12-19 12:53:24.355  3455  3534 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{82a00ca u0 com.google.android.gms.gcm.ACTION_CHECK_QUEUE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{830e7cc 4275:com.google.android.gms.persistent/u0a19}
,12-19 12:53:24.375  3455  3966 V AlarmManager:  remove PendingIntent] PendingIntent{c5c123b: PendingIntentRecord{209402a com.google.android.gms broadcastIntent}}
,12-19 12:53:24.455  3455  4262 V AlarmManager:  remove PendingIntent] PendingIntent{7ed0eb1: PendingIntentRecord{209402a com.google.android.gms broadcastIntent}}
,12-19 12:53:24.635  4275  9344 I VacuumService: Vacuum at: now=1482148404640 tag=VacuumService
,12-19 12:53:24.725  3455  4077 V AlarmManager:  remove PendingIntent] PendingIntent{4d68704: PendingIntentRecord{209402a com.google.android.gms broadcastIntent}}
,12-19 12:53:31.915  3455  4144 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
12-19 12:53:31.925  3455  4144 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4349, temperature: 295, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
12-19 12:53:31.925  3455  4144 D BatteryService: online:4, current avg:233, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:226
12-19 12:53:31.925  3455  3455 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,12-19 12:53:31.925  3455  3455 I MotionRecognitionService: Plugged
,12-19 12:53:31.925  3455  3455 D MotionRecognitionService:   cableConnection= 1
12-19 12:53:31.925  3455  3455 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
12-19 12:53:31.925  3455  3455 D MotionRecognitionService: skip setTransmitPower. 
,12-19 12:53:31.935  3455  3852 D WifiController: ApOrStaEnabledState  msg.what= 155652
,12-19 12:53:31.935  3929  3929 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
12-19 12:53:31.935  3929  3929 D KeyguardUpdateMonitor: handleBatteryUpdate
,12-19 12:53:31.935  3929  3929 D PowerUI : priorPlugType = 2 mPlugType =  2
,12-19 12:53:31.945  4883  4883 D CommonServiceConfiguration: getStringValueSetting
,12-19 12:53:31.945  4838  4838 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,12-19 12:53:31.945  4838  5195 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,12-19 12:53:31.955  4883  4883 D BatteryMonitor: new battery level: 100
,12-19 12:53:31.965  3929  3929 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,12-19 12:53:31.965  3929  3929 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,12-19 12:53:32.615  3455  4123 E Watchdog: !@Sync 3 [12-19 12:53:32.618]
,12-19 12:53:33.135  3455  6024 D SSRM:n  : SIOP:: AP = 320, PST = 398 (W:9), CP = 280, CUR = 233, LCD = 40
,12-19 12:53:38.155  3455  6056 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,12-19 12:53:41.975  3455  4387 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
12-19 12:53:41.975  3455  4387 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4349, temperature: 295, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
12-19 12:53:41.975  3455  4387 D BatteryService: online:4, current avg:223, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:210
12-19 12:53:41.975  3455  3455 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,12-19 12:53:41.985  3455  3455 I MotionRecognitionService: Plugged
,12-19 12:53:41.985  3455  3455 D MotionRecognitionService:   cableConnection= 1
12-19 12:53:41.985  3455  3455 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
12-19 12:53:41.985  3455  3455 D MotionRecognitionService: skip setTransmitPower. 
,12-19 12:53:41.985  3455  3852 D WifiController: ApOrStaEnabledState  msg.what= 155652
,12-19 12:53:41.985  3929  3929 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
12-19 12:53:41.985  3929  3929 D KeyguardUpdateMonitor: handleBatteryUpdate
,12-19 12:53:41.985  3929  3929 D PowerUI : priorPlugType = 2 mPlugType =  2
,12-19 12:53:42.005  4883  4883 D CommonServiceConfiguration: getStringValueSetting
,12-19 12:53:42.005  4838  4838 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
12-19 12:53:42.005  4838  5195 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,12-19 12:53:42.015  4883  4883 D BatteryMonitor: new battery level: 100
,12-19 12:53:42.025  3929  3929 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
12-19 12:53:42.025  3929  3929 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,12-19 12:53:43.155  3455  6024 D SSRM:n  : SIOP:: AP = 320, PST = 391 (W:10), CP = 276, CUR = 223, LCD = 40
,12-19 12:53:52.035  3455  4077 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
12-19 12:53:52.035  3455  4077 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4349, temperature: 295, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
12-19 12:53:52.035  3455  4077 D BatteryService: online:4, current avg:208, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:197
12-19 12:53:52.035  3455  3455 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,12-19 12:53:52.035  3455  3455 I MotionRecognitionService: Plugged
,12-19 12:53:52.035  3455  3455 D MotionRecognitionService:   cableConnection= 1
12-19 12:53:52.035  3455  3455 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
12-19 12:53:52.035  3455  3455 D MotionRecognitionService: skip setTransmitPower. 
,12-19 12:53:52.045  3455  3852 D WifiController: ApOrStaEnabledState  msg.what= 155652
,12-19 12:53:52.045  3929  3929 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
12-19 12:53:52.045  3929  3929 D KeyguardUpdateMonitor: handleBatteryUpdate
12-19 12:53:52.045  3929  3929 D PowerUI : priorPlugType = 2 mPlugType =  2
,12-19 12:53:52.065  4883  4883 D CommonServiceConfiguration: getStringValueSetting
12-19 12:53:52.065  4838  4838 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
12-19 12:53:52.065  4838  5195 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,12-19 12:53:52.065  4883  4883 D BatteryMonitor: new battery level: 100
,12-19 12:53:52.075  3929  3929 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
12-19 12:53:52.075  3929  3929 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,12-19 12:53:53.185  3455  6024 D SSRM:n  : SIOP:: AP = 310, PST = 375 (W:10), CP = 273, CUR = 208, LCD = 40
,12-19 12:53:58.155  3455  6056 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,12-19 12:53:59.995  3455  3806 V AlarmManager: Expired Alarm result :8
,12-19 12:53:59.995  3455  3455 V AlarmManager: ___SyncScheduler (v3) ACTIVATED___
,12-19 12:53:59.995  3455  3455 V AlarmManagerEXT: <AppSync3 Whitelist>
12-19 12:53:59.995  3455  3455 V AlarmManagerEXT: (AppSync) ### 0 added ###
,12-19 12:54:00.005  3929  3929 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
,12-19 12:54:00.005  3929  3929 D KeyguardUpdateMonitor: handleTimeUpdate
,12-19 12:54:00.015  3929  3929 D Clock   : received broadcast android.intent.action.TIME_TICK
,12-19 12:54:00.075  3929  3929 D DateView: received broadcast android.intent.action.TIME_TICK
,12-19 12:54:00.105  4693  4693 D [Weather Widget]  WeatherService: {[EC3334F14841398C8B464A72D0E61AB7C564889C89112557F2146D56794659083956C77974A4825103AB5C5D4AC85EDAA24236388AC138058106446B92A35777]}
,12-19 12:54:00.105  4693  4693 D [Weather Widget]  : {[3AE6950019B083611567B0F9442DB03EEFA9050249635C043F7E254E316C2550]}
,12-19 12:54:00.105  4693  4693 D [Weather Widget]  : {[3AE6950019B083611567B0F9442DB03EAB01DC5C99149A39F887E17599325AFBFF089086AA9902184ADA25758C536FE2]}
,12-19 12:54:00.105  4693  4693 D [Weather Widget]  : {[3AE6950019B083611567B0F9442DB03EFF0B905BDFF72B69FB632A6CB072B41F95D2E6F4F84443284E97F40042D431D8350388453A923ABD8469D82798FA7548]}
,12-19 12:54:00.105  4693  4693 D [Weather Widget]  : {[A1AF0F6A1A65A89C43D705938923D0FEFB71880C4E84718DA0A3E1F383E54FB27A4284D9BEDF7BAA2ABFFE671EB65C640578FF9DE16A23BFE3280A9DCDBB09A02B0671077C7106D78CB8F8AA7271B61687D5A2DB0728818D2FACBA6D466417F21B2EEAB14C27FA7B76D3321C20617608]}
,12-19 12:54:00.105  4693  4693 D [Weather Widget]  : {[15C09394A4E9AFE55A5C62F22AB3FC5902EB2A2150B6646A86F2B3102D669614]}
,12-19 12:54:02.085  3455  3973 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
12-19 12:54:02.085  3455  3973 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4348, temperature: 295, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
12-19 12:54:02.085  3455  3973 D BatteryService: online:4, current avg:194, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:177
12-19 12:54:02.095  3455  3455 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,12-19 12:54:02.095  3455  3455 I MotionRecognitionService: Plugged
,12-19 12:54:02.095  3455  3455 D MotionRecognitionService:   cableConnection= 1
12-19 12:54:02.095  3455  3455 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
12-19 12:54:02.095  3455  3455 D MotionRecognitionService: skip setTransmitPower. 
,12-19 12:54:02.105  3455  3852 D WifiController: ApOrStaEnabledState  msg.what= 155652
,12-19 12:54:02.105  3929  3929 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,12-19 12:54:02.105  3929  3929 D KeyguardUpdateMonitor: handleBatteryUpdate
,12-19 12:54:02.105  3929  3929 D PowerUI : priorPlugType = 2 mPlugType =  2
,12-19 12:54:02.115  4883  4883 D CommonServiceConfiguration: getStringValueSetting
,12-19 12:54:02.115  4838  4838 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,12-19 12:54:02.125  4838  5195 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,12-19 12:54:02.125  4883  4883 D BatteryMonitor: new battery level: 100
,12-19 12:54:02.145  3929  3929 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,12-19 12:54:02.145  3929  3929 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,12-19 12:54:02.615  3455  4123 E Watchdog: !@Sync 4 [12-19 12:54:02.619]
,12-19 12:54:03.205  3455  6024 D SSRM:n  : SIOP:: AP = 310, PST = 357 (W:10), CP = 271, CUR = 194, LCD = 40
,12-19 12:54:03.875  4336  4435 D ContactsProvider_EventLog: contents_sample_state: [ contacts(0) data(0) accounts({}) accounts deleted({}) calls([])  ]
12-19 12:54:03.875  4336  4435 D ContactsProvider_EventLog: contents_sample_state: [ agr({})  ]
,12-19 12:54:11.495  4275  5785 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,12-19 12:54:12.145  3455  4290 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
12-19 12:54:12.145  3455  4290 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4349, temperature: 295, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
12-19 12:54:12.145  3455  4290 D BatteryService: online:4, current avg:181, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:174
12-19 12:54:12.145  3455  3455 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,12-19 12:54:12.155  3455  3455 I MotionRecognitionService: Plugged
,12-19 12:54:12.155  3455  3455 D MotionRecognitionService:   cableConnection= 1
12-19 12:54:12.155  3455  3455 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
12-19 12:54:12.155  3455  3455 D MotionRecognitionService: skip setTransmitPower. 
,12-19 12:54:12.155  3455  3852 D WifiController: ApOrStaEnabledState  msg.what= 155652
,12-19 12:54:12.155  3929  3929 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,12-19 12:54:12.155  3929  3929 D KeyguardUpdateMonitor: handleBatteryUpdate
,12-19 12:54:12.165  3929  3929 D PowerUI : priorPlugType = 2 mPlugType =  2
,12-19 12:54:12.175  4883  4883 D CommonServiceConfiguration: getStringValueSetting
,12-19 12:54:12.175  4838  4838 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
12-19 12:54:12.175  4838  5195 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,12-19 12:54:12.185  4883  4883 D BatteryMonitor: new battery level: 100
,12-19 12:54:12.195  3929  3929 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
12-19 12:54:12.195  3929  3929 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,12-19 12:54:13.225  3455  6024 D SSRM:n  : SIOP:: AP = 310, PST = 345 (W:10), CP = 269, CUR = 181, LCD = 40
,12-19 12:54:18.155  3455  6056 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,12-19 12:54:22.205  3455  4262 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
12-19 12:54:22.205  3455  4262 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4348, temperature: 295, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
12-19 12:54:22.205  3455  4262 D BatteryService: online:4, current avg:171, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:162
12-19 12:54:22.205  3455  3455 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,12-19 12:54:22.205  3455  3455 I MotionRecognitionService: Plugged
12-19 12:54:22.215  3455  3455 D MotionRecognitionService:   cableConnection= 1
12-19 12:54:22.215  3455  3455 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
12-19 12:54:22.215  3455  3455 D MotionRecognitionService: skip setTransmitPower. 
,12-19 12:54:22.215  3455  3852 D WifiController: ApOrStaEnabledState  msg.what= 155652
,12-19 12:54:22.215  3929  3929 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,12-19 12:54:22.215  3929  3929 D KeyguardUpdateMonitor: handleBatteryUpdate
,12-19 12:54:22.215  3929  3929 D PowerUI : priorPlugType = 2 mPlugType =  2
,12-19 12:54:22.225  3929  3929 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,12-19 12:54:22.235  4883  4883 D CommonServiceConfiguration: getStringValueSetting
,12-19 12:54:22.235  4838  4838 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,12-19 12:54:22.235  4838  5195 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,12-19 12:54:22.235  4883  4883 D BatteryMonitor: new battery level: 100
,12-19 12:54:22.255  3929  3929 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,12-19 12:54:23.255  3455  6024 D SSRM:n  : SIOP:: AP = 310, PST = 333 (W:10), CP = 268, CUR = 171, LCD = 40
,12-19 12:54:24.345  3455  3806 V AlarmManager: Expired Alarm result :4
,12-19 12:54:24.365  3455  3534 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{51449a3 u0 com.google.android.gms.gcm.ACTION_CHECK_QUEUE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{830e7cc 4275:com.google.android.gms.persistent/u0a19}
,12-19 12:54:24.385  3455  3973 V AlarmManager:  remove PendingIntent] PendingIntent{f2534a0: PendingIntentRecord{209402a com.google.android.gms broadcastIntent}}
,12-19 12:54:24.455  4585  9373 D UdcContextInitService: registered all accounts: true
,12-19 12:54:24.545  3455  4423 V AlarmManager:  remove PendingIntent] PendingIntent{906ec1e: PendingIntentRecord{209402a com.google.android.gms broadcastIntent}}
,12-19 12:54:24.905  4275  9375 I PhenotypeFlagCommitter: Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,12-19 12:54:24.905  4275  9375 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,12-19 12:54:25.285  4275  9375 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
12-19 12:54:25.285  4275  9375 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,12-19 12:54:25.285  3152  3627 D EnterpriseController: netId is 0
12-19 12:54:25.285  3152  3627 D Netd    : getNetworkForDns: using netid 502 for uid 10019
,12-19 12:54:25.335  4275  9375 I qtaguid : Tagging socket 64 with tag 3000120100000000{805310977,0} uid -1, pid: 4275, getuid(): 10019
,12-19 12:54:25.375  4275  9375 I qtaguid : Tagging socket 68 with tag 3000120100000000{805310977,0} uid -1, pid: 4275, getuid(): 10019
,12-19 12:54:25.745  4275  9375 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
12-19 12:54:25.745  4275  9375 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
12-19 12:54:25.745  4275  9375 I qtaguid : Tagging socket 64 with tag 3000120100000000{805310977,0} uid -1, pid: 4275, getuid(): 10019
,12-19 12:54:26.065  4275  9375 W Uploader: GMM_PRIMES no longer exists, so no auth token.
,12-19 12:54:26.065  4275  4282 E DataBuffer: Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@e095ba5)
12-19 12:54:26.065  4275  9375 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
12-19 12:54:26.065  4275  9375 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
12-19 12:54:26.065  4275  9375 I qtaguid : Tagging socket 64 with tag 3000120100000000{805310977,0} uid -1, pid: 4275, getuid(): 10019
,12-19 12:54:26.175  4275  9375 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
12-19 12:54:26.175  4275  9375 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
12-19 12:54:26.175  4275  9375 I qtaguid : Tagging socket 64 with tag 3000120100000000{805310977,0} uid -1, pid: 4275, getuid(): 10019
,12-19 12:54:26.305  4275  9375 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
12-19 12:54:26.305  4275  9375 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
12-19 12:54:26.305  4275  9375 I qtaguid : Tagging socket 64 with tag 3000120100000000{805310977,0} uid -1, pid: 4275, getuid(): 10019
,12-19 12:54:26.435  4275  9375 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
12-19 12:54:26.435  4275  9375 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
12-19 12:54:26.435  4275  9375 I qtaguid : Tagging socket 64 with tag 3000120100000000{805310977,0} uid -1, pid: 4275, getuid(): 10019
,12-19 12:54:26.545  4275  9375 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
12-19 12:54:26.545  4275  9375 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
12-19 12:54:26.545  4275  9375 I qtaguid : Tagging socket 64 with tag 3000120100000000{805310977,0} uid -1, pid: 4275, getuid(): 10019
,12-19 12:54:26.705  3455  4394 V AlarmManager:  remove PendingIntent] PendingIntent{a3f9682: PendingIntentRecord{209402a com.google.android.gms broadcastIntent}}
,12-19 12:54:32.265  3455  4898 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
12-19 12:54:32.265  3455  4898 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4348, temperature: 295, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
12-19 12:54:32.265  3455  4898 D BatteryService: online:4, current avg:164, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:155
12-19 12:54:32.265  3455  3455 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,12-19 12:54:32.265  3455  3455 I MotionRecognitionService: Plugged
,12-19 12:54:32.265  3455  3455 D MotionRecognitionService:   cableConnection= 1
12-19 12:54:32.265  3455  3455 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,12-19 12:54:32.265  3455  3455 D MotionRecognitionService: skip setTransmitPower. 
,12-19 12:54:32.275  3455  3852 D WifiController: ApOrStaEnabledState  msg.what= 155652
,12-19 12:54:32.275  3929  3929 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,12-19 12:54:32.275  3929  3929 D PowerUI : priorPlugType = 2 mPlugType =  2
,12-19 12:54:32.275  3929  3929 D KeyguardUpdateMonitor: handleBatteryUpdate
,12-19 12:54:32.285  3929  3929 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,12-19 12:54:32.295  4883  4883 D CommonServiceConfiguration: getStringValueSetting
,12-19 12:54:32.295  4838  4838 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
12-19 12:54:32.295  4838  5195 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,12-19 12:54:32.305  4883  4883 D BatteryMonitor: new battery level: 100
,12-19 12:54:32.305  3929  3929 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,12-19 12:54:32.615  3455  4123 E Watchdog: !@Sync 5 [12-19 12:54:32.620]
,12-19 12:54:33.275  3455  6024 D SSRM:n  : SIOP:: AP = 310, PST = 326 (W:14), CP = 268, CUR = 164, LCD = 40
,12-19 12:54:38.155  3455  6056 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,12-19 12:54:42.315  3455  3473 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
12-19 12:54:42.315  3455  3473 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4349, temperature: 294, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
12-19 12:54:42.315  3455  3473 D BatteryService: online:4, current avg:159, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:150
12-19 12:54:42.315  3455  3455 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,12-19 12:54:42.325  3455  3455 I MotionRecognitionService: Plugged
12-19 12:54:42.325  3455  3455 D MotionRecognitionService:   cableConnection= 1
12-19 12:54:42.325  3455  3455 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
12-19 12:54:42.325  3455  3455 D MotionRecognitionService: skip setTransmitPower. 
,12-19 12:54:42.325  3455  3852 D WifiController: ApOrStaEnabledState  msg.what= 155652
,12-19 12:54:42.335  3929  3929 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,12-19 12:54:42.335  3929  3929 D KeyguardUpdateMonitor: handleBatteryUpdate
,12-19 12:54:42.335  3929  3929 D PowerUI : priorPlugType = 2 mPlugType =  2
,12-19 12:54:42.345  4883  4883 D CommonServiceConfiguration: getStringValueSetting
,12-19 12:54:42.355  4838  4838 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,12-19 12:54:42.355  4838  5195 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,12-19 12:54:42.355  4883  4883 D BatteryMonitor: new battery level: 100
,12-19 12:54:42.375  3929  3929 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,12-19 12:54:42.375  3929  3929 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,12-19 12:54:43.305  3455  6024 D SSRM:n  : SIOP:: AP = 310, PST = 315 (W:14), CP = 267, CUR = 159, LCD = 40
,12-19 12:54:52.375  3455  4262 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
12-19 12:54:52.375  3455  4262 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4349, temperature: 294, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
12-19 12:54:52.375  3455  4262 D BatteryService: online:4, current avg:154, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:147
12-19 12:54:52.375  3455  3455 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,12-19 12:54:52.385  3455  3455 I MotionRecognitionService: Plugged
,12-19 12:54:52.385  3455  3455 D MotionRecognitionService:   cableConnection= 1
12-19 12:54:52.385  3455  3455 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
12-19 12:54:52.385  3455  3455 D MotionRecognitionService: skip setTransmitPower. 
,12-19 12:54:52.385  3455  3852 D WifiController: ApOrStaEnabledState  msg.what= 155652
,12-19 12:54:52.385  3929  3929 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,12-19 12:54:52.385  3929  3929 D KeyguardUpdateMonitor: handleBatteryUpdate
,12-19 12:54:52.395  3929  3929 D PowerUI : priorPlugType = 2 mPlugType =  2
,12-19 12:54:52.405  4883  4883 D CommonServiceConfiguration: getStringValueSetting
,12-19 12:54:52.405  4838  4838 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
12-19 12:54:52.405  4838  5195 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,12-19 12:54:52.415  4883  4883 D BatteryMonitor: new battery level: 100
,12-19 12:54:52.415  3929  3929 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,12-19 12:54:52.415  3929  3929 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,12-19 12:54:53.335  3455  6024 D SSRM:n  : SIOP:: AP = 300, PST = 312 (W:14), CP = 266, CUR = 154, LCD = 40
,12-19 12:54:58.155  3455  6056 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,12-19 12:54:59.995  3455  3806 V AlarmManager: Expired Alarm result :8
,12-19 12:54:59.995  3929  3929 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
12-19 12:54:59.995  3929  3929 D KeyguardUpdateMonitor: handleTimeUpdate
,12-19 12:55:00.015  3929  3929 D Clock   : received broadcast android.intent.action.TIME_TICK
,12-19 12:55:00.065  3929  3929 D DateView: received broadcast android.intent.action.TIME_TICK
,12-19 12:55:00.085  4693  4693 D [Weather Widget]  WeatherService: {[EC3334F14841398C8B464A72D0E61AB7C564889C89112557F2146D56794659083956C77974A4825103AB5C5D4AC85EDAA24236388AC138058106446B92A35777]}
,12-19 12:55:00.095  4693  4693 D [Weather Widget]  : {[3AE6950019B083611567B0F9442DB03EEFA9050249635C043F7E254E316C2550]}
,12-19 12:55:00.095  4693  4693 D [Weather Widget]  : {[3AE6950019B083611567B0F9442DB03EAB01DC5C99149A39F887E17599325AFBFF089086AA9902184ADA25758C536FE2]}
,12-19 12:55:00.095  4693  4693 D [Weather Widget]  : {[3AE6950019B083611567B0F9442DB03EFF0B905BDFF72B69FB632A6CB072B41F95D2E6F4F84443284E97F40042D431D8350388453A923ABD8469D82798FA7548]}
,12-19 12:55:00.095  4693  4693 D [Weather Widget]  : {[A1AF0F6A1A65A89C43D705938923D0FEFB71880C4E84718DA0A3E1F383E54FB27A4284D9BEDF7BAA2ABFFE671EB65C640578FF9DE16A23BFE3280A9DCDBB09A02B0671077C7106D78CB8F8AA7271B61687D5A2DB0728818D2FACBA6D466417F21B2EEAB14C27FA7B76D3321C20617608]}
,12-19 12:55:00.095  4693  4693 D [Weather Widget]  : {[15C09394A4E9AFE55A5C62F22AB3FC5902EB2A2150B6646A86F2B3102D669614]}
,12-19 12:55:02.435  3455  4077 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
12-19 12:55:02.435  3455  4077 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4350, temperature: 294, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
12-19 12:55:02.435  3455  4077 D BatteryService: online:4, current avg:148, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:136
12-19 12:55:02.435  3455  3455 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,12-19 12:55:02.435  3455  3455 I MotionRecognitionService: Plugged
,12-19 12:55:02.435  3455  3455 D MotionRecognitionService:   cableConnection= 1
12-19 12:55:02.435  3455  3455 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
12-19 12:55:02.435  3455  3455 D MotionRecognitionService: skip setTransmitPower. 
,12-19 12:55:02.445  3455  3852 D WifiController: ApOrStaEnabledState  msg.what= 155652
,12-19 12:55:02.445  3929  3929 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,12-19 12:55:02.445  3929  3929 D KeyguardUpdateMonitor: handleBatteryUpdate
,12-19 12:55:02.445  3929  3929 D PowerUI : priorPlugType = 2 mPlugType =  2
,12-19 12:55:02.465  4883  4883 D CommonServiceConfiguration: getStringValueSetting
,12-19 12:55:02.465  4838  4838 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
12-19 12:55:02.465  4838  5195 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,12-19 12:55:02.465  4883  4883 D BatteryMonitor: new battery level: 100
,12-19 12:55:02.485  3929  3929 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
12-19 12:55:02.485  3929  3929 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,12-19 12:55:02.615  3455  4123 E Watchdog: !@Sync 6 [12-19 12:55:02.622]
,12-19 12:55:03.355  3455  6024 D SSRM:n  : SIOP:: AP = 300, PST = 310 (W:14), CP = 265, CUR = 148, LCD = 40
,12-19 12:55:03.965  4336  4435 D ContactsProvider_EventLog: contents_sample_state: [ contacts(0) data(0) accounts({}) accounts deleted({}) calls([])  ]
12-19 12:55:03.965  4336  4435 D ContactsProvider_EventLog: contents_sample_state: [ agr({})  ]
,12-19 12:55:04.055  4336  4435 E ContactsProvider_EventLog: Flush buffer to file cnt : 4 size : 1Kb duration : 88ms lastUpdatedAfter : 130684ms
,12-19 12:55:12.485  3455  3473 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
12-19 12:55:12.485  3455  3473 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4348, temperature: 294, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
12-19 12:55:12.485  3455  3473 D BatteryService: online:4, current avg:144, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:145
12-19 12:55:12.485  3455  3455 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,12-19 12:55:12.495  3455  3455 I MotionRecognitionService: Plugged
,12-19 12:55:12.495  3455  3455 D MotionRecognitionService:   cableConnection= 1
12-19 12:55:12.495  3455  3455 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
12-19 12:55:12.495  3455  3455 D MotionRecognitionService: skip setTransmitPower. 
,12-19 12:55:12.495  3455  3852 D WifiController: ApOrStaEnabledState  msg.what= 155652
,12-19 12:55:12.505  3929  3929 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,12-19 12:55:12.505  3929  3929 D KeyguardUpdateMonitor: handleBatteryUpdate
,12-19 12:55:12.505  3929  3929 D PowerUI : priorPlugType = 2 mPlugType =  2
,12-19 12:55:12.515  4883  4883 D CommonServiceConfiguration: getStringValueSetting
12-19 12:55:12.515  4838  4838 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
12-19 12:55:12.515  4838  5195 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,12-19 12:55:12.525  4883  4883 D BatteryMonitor: new battery level: 100
,12-19 12:55:12.535  3929  3929 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,12-19 12:55:12.535  3929  3929 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,12-19 12:55:13.385  3455  6024 D SSRM:n  : SIOP:: AP = 300, PST = 308 (W:14), CP = 265, CUR = 144, LCD = 40
,12-19 12:55:18.165  3455  6056 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,12-19 12:55:22.555  3455  3973 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
12-19 12:55:22.555  3455  3973 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4349, temperature: 294, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
12-19 12:55:22.555  3455  3973 D BatteryService: online:4, current avg:140, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:134
12-19 12:55:22.555  3455  3455 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,12-19 12:55:22.555  3455  3455 I MotionRecognitionService: Plugged
,12-19 12:55:22.555  3455  3455 D MotionRecognitionService:   cableConnection= 1
12-19 12:55:22.555  3455  3455 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
12-19 12:55:22.555  3455  3455 D MotionRecognitionService: skip setTransmitPower. 
,12-19 12:55:22.565  3929  3929 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,12-19 12:55:22.565  3455  3852 D WifiController: ApOrStaEnabledState  msg.what= 155652
12-19 12:55:22.565  3929  3929 D KeyguardUpdateMonitor: handleBatteryUpdate
,12-19 12:55:22.565  3929  3929 D PowerUI : priorPlugType = 2 mPlugType =  2
,12-19 12:55:22.575  4883  4883 D CommonServiceConfiguration: getStringValueSetting
,12-19 12:55:22.585  4838  4838 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
12-19 12:55:22.585  4838  5195 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,12-19 12:55:22.585  4883  4883 D BatteryMonitor: new battery level: 100
,12-19 12:55:22.595  3929  3929 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,12-19 12:55:22.605  3929  3929 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,12-19 12:55:23.405  3455  6024 D SSRM:n  : SIOP:: AP = 300, PST = 307 (W:14), CP = 265, CUR = 140, LCD = 40
,12-19 12:55:32.615  3455  4123 E Watchdog: !@Sync 7 [12-19 12:55:32.623]
,12-19 12:55:33.445  3455  6024 D SSRM:n  : SIOP:: AP = 300, PST = 306 (W:14), CP = 264, CUR = 140, LCD = 40
,12-19 12:55:38.165  3455  6056 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,12-19 12:55:43.465  3455  6024 D SSRM:n  : SIOP:: AP = 300, PST = 305 (W:14), CP = 264, CUR = 140, LCD = 40
,12-19 12:55:52.595  3455  4898 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
12-19 12:55:52.595  3455  4898 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4343, temperature: 293, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
12-19 12:55:52.595  3455  4898 D BatteryService: online:4, current avg:9, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:0
12-19 12:55:52.595  3455  3455 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,12-19 12:55:52.605  3455  3455 I MotionRecognitionService: Plugged
12-19 12:55:52.605  3455  3455 D MotionRecognitionService:   cableConnection= 1
12-19 12:55:52.605  3455  3455 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
12-19 12:55:52.605  3455  3455 D MotionRecognitionService: skip setTransmitPower. 
,12-19 12:55:52.605  3455  3852 D WifiController: ApOrStaEnabledState  msg.what= 155652
,12-19 12:55:52.605  3929  3929 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,12-19 12:55:52.605  3929  3929 D KeyguardUpdateMonitor: handleBatteryUpdate
,12-19 12:55:52.615  3929  3929 D PowerUI : priorPlugType = 2 mPlugType =  2
,12-19 12:55:52.625  4883  4883 D CommonServiceConfiguration: getStringValueSetting
,12-19 12:55:52.625  4838  4838 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
12-19 12:55:52.625  4838  5195 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,12-19 12:55:52.635  4883  4883 D BatteryMonitor: new battery level: 100
,12-19 12:55:52.645  3929  3929 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
12-19 12:55:52.645  3929  3929 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,12-19 12:55:53.485  3455  6024 D SSRM:n  : SIOP:: AP = 300, PST = 305 (W:14), CP = 263, CUR = 9, LCD = 40
,12-19 12:55:58.165  3455  6056 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,12-19 12:55:59.995  3455  3806 V AlarmManager: Expired Alarm result :8
,12-19 12:55:59.995  3929  3929 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
12-19 12:55:59.995  3929  3929 D KeyguardUpdateMonitor: handleTimeUpdate
,12-19 12:56:00.015  3929  3929 D Clock   : received broadcast android.intent.action.TIME_TICK,
,12-19 12:56:00.075  3929  3929 D DateView: received broadcast android.intent.action.TIME_TICK
,12-19 12:56:00.095  4693  4693 D [Weather Widget]  WeatherService: {[EC3334F14841398C8B464A72D0E61AB7C564889C89112557F2146D56794659083956C77974A4825103AB5C5D4AC85EDAA24236388AC138058106446B92A35777]}
,12-19 12:56:00.095  4693  4693 D [Weather Widget]  : {[3AE6950019B083611567B0F9442DB03EEFA9050249635C043F7E254E316C2550]}
,12-19 12:56:00.105  4693  4693 D [Weather Widget]  : {[3AE6950019B083611567B0F9442DB03EAB01DC5C99149A39F887E17599325AFBFF089086AA9902184ADA25758C536FE2]}
,12-19 12:56:00.105  4693  4693 D [Weather Widget]  : {[3AE6950019B083611567B0F9442DB03EFF0B905BDFF72B69FB632A6CB072B41F95D2E6F4F84443284E97F40042D431D8350388453A923ABD8469D82798FA7548]}
,12-19 12:56:00.105  4693  4693 D [Weather Widget]  : {[A1AF0F6A1A65A89C43D705938923D0FEFB71880C4E84718DA0A3E1F383E54FB27A4284D9BEDF7BAA2ABFFE671EB65C640578FF9DE16A23BFE3280A9DCDBB09A02B0671077C7106D78CB8F8AA7271B61687D5A2DB0728818D2FACBA6D466417F21B2EEAB14C27FA7B76D3321C20617608]}
,12-19 12:56:00.105  4693  4693 D [Weather Widget]  : {[15C09394A4E9AFE55A5C62F22AB3FC5902EB2A2150B6646A86F2B3102D669614]}
,12-19 12:56:02.615  3455  4123 E Watchdog: !@Sync 8 [12-19 12:56:02.625]
,12-19 12:56:03.545  3455  6024 D SSRM:n  : SIOP:: AP = 300, PST = 304 (W:14), CP = 263, CUR = 9, LCD = 40
,12-19 12:56:04.095  4336  4435 D ContactsProvider_EventLog: contents_sample_state: [ contacts(0) data(0) accounts({}) accounts deleted({}) calls([])  ]
12-19 12:56:04.095  4336  4435 D ContactsProvider_EventLog: contents_sample_state: [ agr({})  ]
,12-19 12:56:13.575  3455  6024 D SSRM:n  : SIOP:: AP = 300, PST = 303 (W:14), CP = 263, CUR = 9, LCD = 40
,12-19 12:56:18.165  3455  6056 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,12-19 12:56:22.645  3455  3473 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
12-19 12:56:22.645  3455  3473 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4342, temperature: 293, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
12-19 12:56:22.645  3455  3473 D BatteryService: online:4, current avg:0, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:0
12-19 12:56:22.645  3455  3455 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,12-19 12:56:22.655  3455  3455 I MotionRecognitionService: Plugged
12-19 12:56:22.655  3455  3455 D MotionRecognitionService:   cableConnection= 1
12-19 12:56:22.655  3455  3455 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
12-19 12:56:22.655  3455  3455 D MotionRecognitionService: skip setTransmitPower. 
,12-19 12:56:22.655  3455  3852 D WifiController: ApOrStaEnabledState  msg.what= 155652
,12-19 12:56:22.655  3929  3929 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
12-19 12:56:22.655  3929  3929 D KeyguardUpdateMonitor: handleBatteryUpdate
,12-19 12:56:22.655  3929  3929 D PowerUI : priorPlugType = 2 mPlugType =  2
,12-19 12:56:22.675  4883  4883 D CommonServiceConfiguration: getStringValueSetting
,12-19 12:56:22.675  4838  4838 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,12-19 12:56:22.675  4838  5195 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,12-19 12:56:22.685  4883  4883 D BatteryMonitor: new battery level: 100
,12-19 12:56:22.695  3929  3929 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,12-19 12:56:22.695  3929  3929 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,12-19 12:56:23.595  3455  6024 D SSRM:n  : SIOP:: AP = 300, PST = 302 (W:14), CP = 263, LCD = 40
,12-19 12:56:32.615  3455  4123 E Watchdog: !@Sync 9 [12-19 12:56:32.626]
,12-19 12:56:33.625  3455  6024 D SSRM:n  : SIOP:: AP = 300, PST = 302 (W:14), CP = 262, LCD = 40
,12-19 12:56:38.165  3455  6056 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,12-19 12:56:43.645  3455  6024 D SSRM:n  : SIOP:: AP = 300, PST = 301 (W:14), CP = 262, LCD = 40
,12-19 12:56:52.695  3455  4262 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
12-19 12:56:52.695  3455  4262 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4340, temperature: 293, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
12-19 12:56:52.695  3455  4262 D BatteryService: online:4, current avg:0, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:0
12-19 12:56:52.695  3455  3455 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,12-19 12:56:52.705  3455  3455 I MotionRecognitionService: Plugged
,12-19 12:56:52.705  3455  3455 D MotionRecognitionService:   cableConnection= 1
12-19 12:56:52.705  3455  3455 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
12-19 12:56:52.705  3455  3455 D MotionRecognitionService: skip setTransmitPower. 
,12-19 12:56:52.705  3455  3852 D WifiController: ApOrStaEnabledState  msg.what= 155652
,12-19 12:56:52.705  3929  3929 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
12-19 12:56:52.705  3929  3929 D KeyguardUpdateMonitor: handleBatteryUpdate
,12-19 12:56:52.705  3929  3929 D PowerUI : priorPlugType = 2 mPlugType =  2
,12-19 12:56:52.725  4883  4883 D CommonServiceConfiguration: getStringValueSetting
,12-19 12:56:52.725  4838  4838 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
12-19 12:56:52.725  4838  5195 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,12-19 12:56:52.735  4883  4883 D BatteryMonitor: new battery level: 100
,12-19 12:56:52.745  3929  3929 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,12-19 12:56:52.745  3929  3929 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,12-19 12:56:53.675  3455  6024 D SSRM:n  : SIOP:: AP = 300, PST = 300 (W:14), CP = 262, LCD = 40
,12-19 12:56:58.165  3455  6056 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,12-19 12:56:59.995  3455  3806 V AlarmManager: Expired Alarm result :8
,12-19 12:56:59.995  3929  3929 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
12-19 12:56:59.995  3929  3929 D KeyguardUpdateMonitor: handleTimeUpdate
,12-19 12:57:00.015  3929  3929 D Clock   : received broadcast android.intent.action.TIME_TICK
,12-19 12:57:00.085  3929  3929 D DateView: received broadcast android.intent.action.TIME_TICK
,12-19 12:57:00.115  4693  4693 D [Weather Widget]  WeatherService: {[EC3334F14841398C8B464A72D0E61AB7C564889C89112557F2146D56794659083956C77974A4825103AB5C5D4AC85EDAA24236388AC138058106446B92A35777]}
,12-19 12:57:00.115  4693  4693 D [Weather Widget]  : {[3AE6950019B083611567B0F9442DB03EEFA9050249635C043F7E254E316C2550]}
,12-19 12:57:00.125  4693  4693 D [Weather Widget]  : {[3AE6950019B083611567B0F9442DB03EAB01DC5C99149A39F887E17599325AFBFF089086AA9902184ADA25758C536FE2]}
,12-19 12:57:00.125  4693  4693 D [Weather Widget]  : {[3AE6950019B083611567B0F9442DB03EFF0B905BDFF72B69FB632A6CB072B41F95D2E6F4F84443284E97F40042D431D8350388453A923ABD8469D82798FA7548]}
,12-19 12:57:00.125  4693  4693 D [Weather Widget]  : {[A1AF0F6A1A65A89C43D705938923D0FEFB71880C4E84718DA0A3E1F383E54FB27A4284D9BEDF7BAA2ABFFE671EB65C640578FF9DE16A23BFE3280A9DCDBB09A02B0671077C7106D78CB8F8AA7271B61687D5A2DB0728818D2FACBA6D466417F21B2EEAB14C27FA7B76D3321C20617608]}
12-19 12:57:00.125  4693  4693 D [Weather Widget]  : {[15C09394A4E9AFE55A5C62F22AB3FC5902EB2A2150B6646A86F2B3102D669614]}
,12-19 12:57:02.625  3455  4123 E Watchdog: !@Sync 10 [12-19 12:57:02.628]
,12-19 12:57:03.375  3455  3798 D TimaService: TIMA: TimaService scheduler is intialized. 
12-19 12:57:03.375  3455  3798 D TimaService: TIMA: checkEvent, operation: 50000 subject: 10000
12-19 12:57:03.375  3455  3797 D TimaService: TimaServiceHandler.handleMessage what =1
,12-19 12:57:03.375  3455  3798 I TLC_TIMA_PKM_initialize: initializing...
12-19 12:57:03.375  3455  3798 I TLC_TIMA_PKM_initialize: root = 0, root_strlen = 1
12-19 12:57:03.375  3455  3798 I TLC_TIMA_PKM_initialize: process = ffffffff00000000000000000000000a, process_strlen = 32
12-19 12:57:03.375  3455  3798 I TZ: mc_tlc_communication: input max_sendmsg_size = 262196
12-19 12:57:03.375  3455  3798 I TZ: mc_tlc_communication: input max_recvmsg_size = 262196
12-19 12:57:03.375  3455  3798 I TZ: mc_tlc_communication: root = 0, root_len = 1
12-19 12:57:03.375  3455  3798 I TZ: mc_tlc_communication: process = ffffffff00000000000000000000000a, process_strlen = 32
12-19 12:57:03.375  3455  3798 I TZ: mc_tlc_communication: aligned max_sendmsg_size = 262208
12-19 12:57:03.375  3455  3798 I TZ: mc_tlc_communication: aligned max_recvmsg_size = 262208
12-19 12:57:03.375  3455  3798 I TZ: mc_tlc_communication: device_id = 0x0
,12-19 12:57:03.375  3455  3798 I TZ: mc_tlc_communication: tlc_open() was called
12-19 12:57:03.375  3455  3798 I TZ: mc_tlc_communication: Opening MobiCore device
12-19 12:57:03.375  3455  3798 I TeeDriverClient: driver client open [hardware/samsung_slsi/exynos8890/mobicore/ClientLib/src/driver_client.cpp:103]
12-19 12:57:03.375  3455  3798 I TZ: mc_tlc_communication: Allocating message buffer for TCI
12-19 12:57:03.385  3455  3798 I TZ: mc_tlc_communication: Opening the session
,12-19 12:57:03.425  3455  3798 I TZ: mc_tlc_communication: tlc_open() succeeded
12-19 12:57:03.425  3455  3798 E TLC_TIMA_PKM_initialize: tima_pkm : /system/kern_sec_info1
,12-19 12:57:03.445  3455  3798 E TLC_TIMA_PKM_initialize: tima_pkm : /system/kern_sec_info2
,12-19 12:57:03.475  3455  3798 E TLC_TIMA_PKM_initialize: tima_pkm : /system/kern_sec_info3
,12-19 12:57:03.475  3455  3798 E TLC_TIMA_PKM_initialize: tima_pkm : /system/kern_sec_info4
,12-19 12:57:03.485  3455  3798 I TLC_TIMA_PKM_initialize: Trustlet response is completed
,12-19 12:57:03.735  3455  6024 D SSRM:n  : SIOP:: AP = 300, PST = 300 (W:14), CP = 262, LCD = 40
,12-19 12:57:04.195  4336  4435 D ContactsProvider_EventLog: contents_sample_state: [ contacts(0) data(0) accounts({}) accounts deleted({}) calls([])  ]
12-19 12:57:04.195  4336  4435 D ContactsProvider_EventLog: contents_sample_state: [ agr({})  ]
,12-19 12:57:06.855  3455  3798 I TLC_TIMA_PKM_measure_kernel: TIMA: response_id = 3
12-19 12:57:06.855  3455  3798 I TLC_TIMA_PKM_measure_kernel: TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,12-19 12:57:06.865  3455  3798 D TimaService: TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,12-19 12:57:06.865  3455  3798 D TimaService: TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,12-19 12:57:07.145  3455  3806 V AlarmManager: Expired Alarm result :4
,12-19 12:57:07.155  4111  4111 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec
12-19 12:57:07.155  4111  4111 I wpa_supplicant: P2P: Current p2p state = IDLE
,12-19 12:57:07.165  4111  4111 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,12-19 12:57:07.195  9404  9404 E Zygote  : v2
12-19 12:57:07.195  9404  9404 I libpersona: KNOX_SDCARD checking this for 1000
12-19 12:57:07.195  9404  9404 I libpersona: KNOX_SDCARD not a persona
,12-19 12:57:07.205  9404  9404 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0031
,12-19 12:57:07.205  3455  3806 I ActivityManager: Start proc 9404:com.mobeam.barcodeService/1000 for service com.mobeam.barcodeService/.system.AppService
,12-19 12:57:07.205  9404  9404 E Zygote  : accessInfo : 0
,12-19 12:57:07.245  9404  9404 D TimaKeyStoreProvider: TimaSignature is unavailable
12-19 12:57:07.245  9404  9404 D ActivityThread: Added TimaKeyStore provider
,12-19 12:57:07.275  9404  9404 W ResourcesManager: getTopLevelResources: /system/app/BeamService/BeamService.apk / 1.0 running in com.mobeam.barcodeService rsrc of package com.mobeam.barcodeService
,12-19 12:57:07.275  3455  3844 I InjectionManagerService -AppFeature: getCoreFeaturePkgList :[]
,12-19 12:57:07.275  9404  9404 I InjectionManager: Inside getClassLibPath + mLibMap{0=, 1=}
,12-19 12:57:07.285  9404  9404 D ResourcesManager: For user 0 new overlays fetched Null
,12-19 12:57:07.285  9404  9404 I InjectionManager: Inside getClassLibPath caller 
,12-19 12:57:07.295  9404  9404 W System  : ClassLoader referenced unknown path: /system/app/BeamService/lib/arm64
,12-19 12:57:07.295  9404  9404 D InjectionManager: InjectionManager
12-19 12:57:07.295  9404  9404 D InjectionManager: fillFeatureStoreMap com.mobeam.barcodeService
,12-19 12:57:07.305  9404  9404 I InjectionManager: Constructor com.mobeam.barcodeService, Feature store :{}
12-19 12:57:07.305  9404  9404 I InjectionManager: featureStore :{}
,12-19 12:57:07.335  3455  3973 I ActivityManager: Killing 8645:com.samsung.android.app.FileShareServer/5005 (adj 15): DHA:empty #33
,12-19 12:57:07.365  3455  4898 D ActivityManager: cleanUpApplicationRecord -- 8645
,12-19 12:57:07.365  3455  4898 D ActivityManager: isAutoRunBlockedApp:: com.samsung.android.app.FileShareServer, Auto Run ON
,12-19 12:57:11.125  3152  3624 D Netd    : Iface wlan0 link up
,12-19 12:57:11.125  3455  3538 D Tethering: interfaceLinkStateChanged wlan0, true
12-19 12:57:11.125  3455  3538 D Tethering: interfaceStatusChanged wlan0, true
,12-19 12:57:11.125  4883  4893 D PdnController: Interface Changed wlan0 link up
12-19 12:57:11.125  4111  4111 I wpa_supplicant: nl80211: Received scan results (18 BSSes)
,12-19 12:57:11.135  4111  4111 I wpa_supplicant: scan_only_handler, so autoscan_notify() !!!
,12-19 12:57:11.135  3455  3848 D WifiP2pService: InactiveState{ what=147461 }
,12-19 12:57:11.135  3455  3848 D WifiP2pService: P2pEnabledState{ what=147461 }
12-19 12:57:11.135  3455  3848 D WifiP2pService: DefaultState{ what=147461 }
,12-19 12:57:11.195  3455  3455 I CLocInfoService: ['16.5] External Intent Received android.net.wifi.SCAN_RESULTS
,12-19 12:57:11.205  3455  3534 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{ea17985 u-1 android.net.wifi.SCAN_RESULTS qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{f8e7582 3929:com.android.systemui/u0a62}
,12-19 12:57:13.765  3455  6024 D SSRM:n  : SIOP:: AP = 300, PST = 300 (W:14), CP = 262, LCD = 40
,12-19 12:57:18.165  3455  6056 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,12-19 12:57:22.745  3455  4144 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,12-19 12:57:23.815  3455  6024 D SSRM:n  : SIOP:: AP = 300, PST = 300 (W:14), CP = 262, LCD = 40
,12-19 12:57:27.905  8577  8619 W PlayEventLogger: No account for auth token provided
,12-19 12:57:27.915  8577  8619 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
12-19 12:57:27.915  8577  8619 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,12-19 12:57:27.925  3152  3627 D EnterpriseController: netId is 0
12-19 12:57:27.925  3152  3627 D Netd    : getNetworkForDns: using netid 502 for uid 10032
,12-19 12:57:32.625  3455  4123 E Watchdog: !@Sync 11 [12-19 12:57:32.629]
,12-19 12:57:33.885  3455  6024 D SSRM:n  : SIOP:: AP = 300, PST = 300 (W:14), CP = 262, LCD = 40
,12-19 12:57:38.175  3455  6056 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,12-19 12:57:43.905  3455  6024 D SSRM:n  : SIOP:: AP = 300, PST = 300 (W:14), CP = 262, LCD = 40
,12-19 12:57:52.795  3455  4262 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,12-19 12:57:53.945  3455  6024 D SSRM:n  : SIOP:: AP = 300, PST = 300 (W:14), CP = 262, LCD = 40
,12-19 12:57:58.175  3455  6056 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,12-19 12:57:59.995  3455  3806 V AlarmManager: Expired Alarm result :8
,12-19 12:58:00.005  3929  3929 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
,12-19 12:58:00.005  3929  3929 D KeyguardUpdateMonitor: handleTimeUpdate
,12-19 12:58:00.015  3929  3929 D Clock   : received broadcast android.intent.action.TIME_TICK,
,12-19 12:58:00.085  3929  3929 D DateView: received broadcast android.intent.action.TIME_TICK
,12-19 12:58:00.105  4693  4693 D [Weather Widget]  WeatherService: {[EC3334F14841398C8B464A72D0E61AB7C564889C89112557F2146D56794659083956C77974A4825103AB5C5D4AC85EDAA24236388AC138058106446B92A35777]}
,12-19 12:58:00.105  4693  4693 D [Weather Widget]  : {[3AE6950019B083611567B0F9442DB03EEFA9050249635C043F7E254E316C2550]}
,12-19 12:58:00.105  4693  4693 D [Weather Widget]  : {[3AE6950019B083611567B0F9442DB03EAB01DC5C99149A39F887E17599325AFBFF089086AA9902184ADA25758C536FE2]}
,12-19 12:58:00.115  4693  4693 D [Weather Widget]  : {[3AE6950019B083611567B0F9442DB03EFF0B905BDFF72B69FB632A6CB072B41F95D2E6F4F84443284E97F40042D431D8350388453A923ABD8469D82798FA7548]}
,12-19 12:58:00.115  4693  4693 D [Weather Widget]  : {[A1AF0F6A1A65A89C43D705938923D0FEFB71880C4E84718DA0A3E1F383E54FB27A4284D9BEDF7BAA2ABFFE671EB65C640578FF9DE16A23BFE3280A9DCDBB09A02B0671077C7106D78CB8F8AA7271B61687D5A2DB0728818D2FACBA6D466417F21B2EEAB14C27FA7B76D3321C20617608]}
,12-19 12:58:00.115  4693  4693 D [Weather Widget]  : {[15C09394A4E9AFE55A5C62F22AB3FC5902EB2A2150B6646A86F2B3102D669614]}
,12-19 12:58:02.625  3455  4123 E Watchdog: !@Sync 12 [12-19 12:58:02.630]
,12-19 12:58:04.005  3455  6024 D SSRM:n  : SIOP:: AP = 300, PST = 300 (W:14), CP = 262, LCD = 40
,12-19 12:58:04.285  4336  4435 D ContactsProvider_EventLog: contents_sample_state: [ contacts(0) data(0) accounts({}) accounts deleted({}) calls([])  ]
12-19 12:58:04.285  4336  4435 D ContactsProvider_EventLog: contents_sample_state: [ agr({})  ]
,12-19 12:58:04.355  4336  4435 E ContactsProvider_EventLog: Flush buffer to file cnt : 3 size : 0Kb duration : 63ms lastUpdatedAfter : 180299ms
,12-19 12:58:14.035  3455  6024 D SSRM:n  : SIOP:: AP = 300, PST = 300 (W:14), CP = 262, LCD = 40
,12-19 12:58:18.175  3455  6056 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,12-19 12:58:22.835  3455  4387 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
12-19 12:58:22.835  3455  4387 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4339, temperature: 293, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303413, invalid charger:0, maxChargingCurrent:0
12-19 12:58:22.835  3455  4387 D BatteryService: online:4, current avg:0, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:0
12-19 12:58:22.835  3455  3455 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,12-19 12:58:22.845  3455  3455 I MotionRecognitionService: Plugged
,12-19 12:58:22.845  3455  3455 D MotionRecognitionService:   cableConnection= 1
12-19 12:58:22.845  3455  3455 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
12-19 12:58:22.845  3455  3455 D MotionRecognitionService: skip setTransmitPower. 
,12-19 12:58:22.845  3455  3852 D WifiController: ApOrStaEnabledState  msg.what= 155652
,12-19 12:58:22.855  3929  3929 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,12-19 12:58:22.855  3929  3929 D KeyguardUpdateMonitor: handleBatteryUpdate
12-19 12:58:22.855  3929  3929 D PowerUI : priorPlugType = 2 mPlugType =  2
,12-19 12:58:22.865  4883  4883 D CommonServiceConfiguration: getStringValueSetting
,12-19 12:58:22.875  4838  4838 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,12-19 12:58:22.875  4838  5195 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,12-19 12:58:22.875  4883  4883 D BatteryMonitor: new battery level: 100
,12-19 12:58:22.875  3929  3929 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,12-19 12:58:22.875  3929  3929 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2

```
