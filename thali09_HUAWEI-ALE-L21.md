#### Test 78968685da35147_thali09_HUAWEI-ALE-L21 Logs


```
int logctl_get(): open '/dev/hwlog_switch' fail -1, 13. Permission denied

Note: log switch off, only log_main and log_events will have logs!
,--------- beginning of main
07-27 08:54:03.229  6771  6771 I appproc : CLASSPATH=/system/framework/am.jar
07-27 08:54:03.229  6771  6771 I appproc : Command=app_process /system/bin com.android.commands.am.Am start -n com.test.thalitest/com.test.thalitest.MainActivity 
07-27 08:54:03.229  6771  6771 I appproc : app_process:number,5,0
07-27 08:54:03.229  6771  6771 I AndroidRuntime: readDownloadBoosterConfig: 'false'
07-27 08:54:03.379  6771  6771 I         : power log dlsym ok
07-27 08:54:03.419  6771  6771 E android_hardware_fm.cpp: register_android_hardware_fm_fmradio
07-27 08:54:03.419  6771  6771 I android_hardware_fm.cpp: ========64bit long size = 8
07-27 08:54:03.419  6771  6771 E FM_HAL  : [FM_HAL], libname is libhisifm_if
07-27 08:54:03.419  6771  6771 I fm_hisi : FM::[fm_device_open:4655] fm_device_open
07-27 08:54:03.419  6771  6771 I fm_hisi : 
07-27 08:54:03.419  6771  6771 I fm_hisi : FM::[fm_device_open:4666] find the id:libhisifm_if and begins to open the device
07-27 08:54:03.419  6771  6771 I fm_hisi : 
07-27 08:54:03.419  6771  6771 I fm_hisi : FM::[fm_device_open:4710] device open sucess
07-27 08:54:03.419  6771  6771 I fm_hisi : 
07-27 08:54:03.419  6771  6771 E android_hardware_fm.cpp: register_android_hardware_fm_fmradio, ret is 0
07-27 08:54:03.469  3032  3361 I art     : Can not find class: Lcom/android/server/wm/WindowState$2;
07-27 08:54:03.469  3032  3361 I art     : Can not find class: Lcom/android/server/am/TaskPersister$TaskWriteQueueItem;
07-27 08:54:03.469  3032  3361 I art     : Can not find class: Lcom/android/server/am/TaskPersister$WriteQueueItem;
07-27 08:54:03.529  3032  3653 I art     : Can not find class: Lcom/android/server/am/ActivityStack$2;
07-27 08:54:03.539  3491  3815 W PhoneStateManager: screen off and not process front event:com.test.thalitest
07-27 08:54:03.549  3754  3854 I HwSystemManager: AppLockService:applock password not initial or function is closed
07-27 08:54:03.549  3754  3854 I HwSystemManager: AppLockService:applock password not initial or function is closed
07-27 08:54:03.549  3602  3602 I HwLauncher: Launcher  onWindowVisibilityChanged visibility = 8
07-27 08:54:03.549  3754  4026 I HwSystemManager: AppManager:getNetAppInfoFromDB cursor lenth = 1
07-27 08:54:03.549  3602  3602 I HwLauncher: DynamicIcon onWindowVisibilityChanged 8 - com.android.calendar
07-27 08:54:03.549  3602  3602 I HwLauncher: DynamicIcon onWindowVisibilityChanged 8 - com.android.deskclock
07-27 08:54:03.559  3602  3602 I HwLauncher: DynamicIcon onVisibilityChanged 4 - com.android.calendar
07-27 08:54:03.559  3602  3602 I HwLauncher: DynamicIcon onVisibilityChanged 4 - com.android.deskclock
07-27 08:54:03.689  6791  6791 I WebViewFactory: Loading com.android.webview version 37 (eng.jenkins-arm64) (code 199992)
07-27 08:54:03.719  6791  6791 I LibraryLoader: Loading: webviewchromium
,07-27 08:54:03.769  6791  6791 I LibraryLoader: Time to load native libraries: 57 ms (timestamps 6351-6408)
07-27 08:54:03.769  6791  6791 I LibraryLoader: Expected native library version number "",actual native library version number ""
07-27 08:54:03.809  6791  6791 E ZipFileCache: init failed when open zip file.
07-27 08:54:03.809  6791  6791 E ZipFileCache: init failed when open zip file.
07-27 08:54:03.809  6791  6791 E ZipFileCache: init failed when open zip file.
07-27 08:54:03.809  6791  6791 E ZipFileCache: init failed when open zip file.
07-27 08:54:03.819  6791  6791 I LibraryLoader: Expected native library version number "",actual native library version number ""
07-27 08:54:03.829  6791  6791 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
07-27 08:54:03.839  6791  6791 I BrowserStartupController: Initializing chromium process, renderers=0
07-27 08:54:03.849  6791  6791 W art     : Attempt to remove local handle scope entry from IRT, ignoring
07-27 08:54:03.869  6791  6817 W chromium: [WARNING:dns_config_service_posix.cc(293)] Failed to read DnsConfig.
07-27 08:54:03.899  6791  6791 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
07-27 08:54:03.899  6791  6791 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=37 off=46092 len=2953
07-27 08:54:03.899  6791  6791 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:38 off:228796 len:643667
07-27 08:54:03.919  2349  2349 E Thermal-daemon: [ap] temp_new :30  temp_old :31
07-27 08:54:04.049  6791  6827 W chromium: [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
07-27 08:54:04.059  6791  6791 W chromium: [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
07-27 08:54:04.059  6791  6827 W chromium: [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
07-27 08:54:04.089  6791  6791 E ZipFileCache: init failed when open zip file.
07-27 08:54:04.099  6791  6791 E ZipFileCache: init failed when open zip file.
07-27 08:54:04.099  6791  6791 E ZipFileCache: init failed when open zip file.
07-27 08:54:04.099  6791  6791 E ZipFileCache: init failed when open zip file.
07-27 08:54:04.109  6791  6791 E ZipFileCache: init failed when open zip file.
07-27 08:54:04.109  6791  6791 E ZipFileCache: init failed when open zip file.
07-27 08:54:04.109  6791  6791 E ZipFileCache: init failed when open zip file.
07-27 08:54:04.109  6791  6791 E ZipFileCache: init failed when open zip file.
07-27 08:54:04.109  6791  6791 E ZipFileCache: init failed when open zip file.
07-27 08:54:04.109  6791  6791 E ZipFileCache: init failed when open zip file.
07-27 08:54:04.119  6791  6791 E ZipFileCache: init failed when open zip file.
07-27 08:54:04.119  6791  6791 E ZipFileCache: init failed when open zip file.
07-27 08:54:04.119  6791  6791 E ZipFileCache: init failed when open zip file.
07-27 08:54:04.119  6791  6791 E ZipFileCache: init failed when open zip file.
07-27 08:54:04.129  6791  6791 E ZipFileCache: init failed when open zip file.
07-27 08:54:04.129  6791  6791 E ZipFileCache: init failed when open zip file.
07-27 08:54:04.129  6791  6791 E ZipFileCache: init failed when open zip file.
07-27 08:54:04.129  6791  6791 E ZipFileCache: init failed when open zip file.
07-27 08:54:04.129  6791  6791 E ZipFileCache: init failed when open zip file.
07-27 08:54:04.129  6791  6791 E ZipFileCache: init failed when open zip file.
07-27 08:54:04.139  6791  6791 E ZipFileCache: init failed when open zip file.
07-27 08:54:04.139  6791  6791 E ZipFileCache: init failed when open zip file.
07-27 08:54:04.139  6791  6791 E ZipFileCache: init failed when open zip file.
07-27 08:54:04.139  6791  6791 E ZipFileCache: init failed when open zip file.
07-27 08:54:04.149  6791  6791 E ZipFileCache: init failed when open zip file.
07-27 08:54:04.149  6791  6791 E ZipFileCache: init failed when open zip file.
07-27 08:54:04.149  6791  6791 E ZipFileCache: init failed when open zip file.
07-27 08:54:04.149  6791  6791 E ZipFileCache: init failed when open zip file.
07-27 08:54:04.149  6791  6791 E ZipFileCache: init failed when open zip file.
07-27 08:54:04.149  6791  6791 E ZipFileCache: init failed when open zip file.
07-27 08:54:04.159  6791  6791 E ZipFileCache: init failed when open zip file.
07-27 08:54:04.159  6791  6791 E ZipFileCache: init failed when open zip file.
07-27 08:54:04.159  6791  6791 E ZipFileCache: init failed when open zip file.
07-27 08:54:04.159  6791  6791 E ZipFileCache: init failed when open zip file.
07-27 08:54:04.159  6791  6791 E ZipFileCache: init failed when open zip file.
07-27 08:54:04.159  6791  6791 E ZipFileCache: init failed when open zip file.
07-27 08:54:04.169  6791  6791 E ZipFileCache: init failed when open zip file.
07-27 08:54:04.169  6791  6791 E ZipFileCache: init failed when open zip file.
07-27 08:54:04.169  6791  6791 E ZipFileCache: init failed when open zip file.
07-27 08:54:04.169  6791  6791 E ZipFileCache: init failed when open zip file.
07-27 08:54:04.179  6791  6791 E ZipFileCache: init failed when open zip file.
07-27 08:54:04.179  6791  6791 E ZipFileCache: init failed when open zip file.
07-27 08:54:04.179  6791  6791 E ZipFileCache: init failed when open zip file.
07-27 08:54:04.179  6791  6791 E ZipFileCache: init failed when open zip file.
07-27 08:54:04.179  6791  6791 E ZipFileCache: init failed when open zip file.
07-27 08:54:04.179  6791  6791 E ZipFileCache: init failed when open zip file.
07-27 08:54:04.179  6791  6791 E ZipFileCache: init failed when open zip file.
07-27 08:54:04.179  6791  6791 E ZipFileCache: init failed when open zip file.
07-27 08:54:04.189  6791  6791 E ZipFileCache: init failed when open zip file.
07-27 08:54:04.189  6791  6791 E ZipFileCache: init failed when open zip file.
07-27 08:54:04.189  6791  6791 E ZipFileCache: init failed when open zip file.
07-27 08:54:04.189  6791  6791 E ZipFileCache: init failed when open zip file.
07-27 08:54:04.189  6791  6791 E ZipFileCache: init failed when open zip file.
07-27 08:54:04.189  6791  6791 E ZipFileCache: init failed when open zip file.
07-27 08:54:04.189  6791  6791 E ZipFileCache: init failed when open zip file.
07-27 08:54:04.189  6791  6791 E ZipFileCache: init failed when open zip file.
07-27 08:54:04.189  6791  6791 E ZipFileCache: init failed when open zip file.
07-27 08:54:04.189  6791  6791 E ZipFileCache: init failed when open zip file.
07-27 08:54:04.189  6791  6791 E ZipFileCache: init failed when open zip file.
07-27 08:54:04.189  6791  6791 E ZipFileCache: init failed when open zip file.
07-27 08:54:04.189  6791  6791 E ZipFileCache: init failed when open zip file.
07-27 08:54:04.189  6791  6791 E ZipFileCache: init failed when open zip file.
07-27 08:54:04.199  6791  6791 E ZipFileCache: init failed when open zip file.
07-27 08:54:04.199  6791  6791 E ZipFileCache: init failed when open zip file.
07-27 08:54:04.199  6791  6791 E ZipFileCache: init failed when open zip file.
07-27 08:54:04.199  6791  6791 E ZipFileCache: init failed when open zip file.
07-27 08:54:04.199  6791  6791 E ZipFileCache: init failed when open zip file.
07-27 08:54:04.199  6791  6791 E ZipFileCache: init failed when open zip file.
07-27 08:54:04.199  6791  6791 E ZipFileCache: init failed when open zip file.
07-27 08:54:04.199  6791  6791 E ZipFileCache: init failed when open zip file.
07-27 08:54:04.199  6791  6791 E ZipFileCache: init failed when open zip file.
07-27 08:54:04.199  6791  6791 E ZipFileCache: init failed when open zip file.
07-27 08:54:04.199  6791  6791 E ZipFileCache: init failed when open zip file.
07-27 08:54:04.199  6791  6791 E ZipFileCache: init failed when open zip file.
07-27 08:54:04.199  6791  6791 E ZipFileCache: init failed when open zip file.
07-27 08:54:04.199  6791  6791 E ZipFileCache: init failed when open zip file.
07-27 08:54:04.199  6791  6791 E ZipFileCache: init failed when open zip file.
07-27 08:54:04.199  6791  6791 E ZipFileCache: init failed when open zip file.
07-27 08:54:04.199  6791  6791 E ZipFileCache: init failed when open zip file.
07-27 08:54:04.199  6791  6791 E ZipFileCache: init failed when open zip file.
07-27 08:54:04.209  6791  6791 E ZipFileCache: init failed when open zip file.
07-27 08:54:04.209  6791  6791 E ZipFileCache: init failed when open zip file.
07-27 08:54:04.209  6791  6791 E ZipFileCache: init failed when open zip file.
07-27 08:54:04.209  6791  6791 E ZipFileCache: init failed when open zip file.
07-27 08:54:04.209  6791  6791 E ZipFileCache: init failed when open zip file.
07-27 08:54:04.209  6791  6791 E ZipFileCache: init failed when open zip file.
07-27 08:54:04.209  6791  6791 E ZipFileCache: init failed when open zip file.
07-27 08:54:04.209  6791  6791 E ZipFileCache: init failed when open zip file.
07-27 08:54:04.219  6791  6791 E ZipFileCache: init failed when open zip file.
07-27 08:54:04.219  6791  6791 E ZipFileCache: init failed when open zip file.
07-27 08:54:04.219  6791  6791 E ZipFileCache: init failed when open zip file.
07-27 08:54:04.219  6791  6791 E ZipFileCache: init failed when open zip file.
07-27 08:54:04.229  6791  6791 E ZipFileCache: init failed when open zip file.
07-27 08:54:04.229  6791  6791 E ZipFileCache: init failed when open zip file.
07-27 08:54:04.229  6791  6791 E ZipFileCache: init failed when open zip file.
07-27 08:54:04.229  6791  6791 E ZipFileCache: init failed when open zip file.
07-27 08:54:04.239  6791  6791 E ZipFileCache: init failed when open zip file.
07-27 08:54:04.239  6791  6791 E ZipFileCache: init failed when open zip file.
07-27 08:54:04.239  6791  6791 E ZipFileCache: init failed when open zip file.
07-27 08:54:04.239  6791  6791 E ZipFileCache: init failed when open zip file.
07-27 08:54:04.239  6791  6791 E ZipFileCache: init failed when open zip file.
07-27 08:54:04.249  6791  6791 E ZipFileCache: init failed when open zip file.
07-27 08:54:04.249  6791  6791 E ZipFileCache: init failed when open zip file.
07-27 08:54:04.249  6791  6791 E ZipFileCache: init failed when open zip file.
07-27 08:54:04.249  6791  6791 E ZipFileCache: init failed when open zip file.
07-27 08:54:04.249  6791  6791 E ZipFileCache: init failed when open zip file.
07-27 08:54:04.259  6791  6791 E ZipFileCache: init failed when open zip file.
07-27 08:54:04.259  6791  6791 E ZipFileCache: init failed when open zip file.
07-27 08:54:04.259  6791  6791 E ZipFileCache: init failed when open zip file.
07-27 08:54:04.259  6791  6791 E ZipFileCache: init failed when open zip file.
07-27 08:54:04.259  6791  6791 E ZipFileCache: init failed when open zip file.
07-27 08:54:04.259  6791  6791 E ZipFileCache: init failed when open zip file.
07-27 08:54:04.269  6791  6791 E ZipFileCache: init failed when open zip file.
07-27 08:54:04.269  6791  6791 E ZipFileCache: init failed when open zip file.
07-27 08:54:04.269  6791  6791 E ZipFileCache: init failed when open zip file.
07-27 08:54:04.269  6791  6791 E ZipFileCache: init failed when open zip file.
07-27 08:54:04.269  6791  6791 E ZipFileCache: init failed when open zip file.
07-27 08:54:04.269  6791  6791 E ZipFileCache: init failed when open zip file.
07-27 08:54:04.279  6791  6791 E ZipFileCache: init failed when open zip file.
07-27 08:54:04.279  6791  6791 E ZipFileCache: init failed when open zip file.
07-27 08:54:04.279  6791  6791 E ZipFileCache: init failed when open zip file.
07-27 08:54:04.279  6791  6791 E ZipFileCache: init failed when open zip file.
07-27 08:54:04.279  6791  6791 E ZipFileCache: init failed when open zip file.
07-27 08:54:04.279  6791  6791 E ZipFileCache: init failed when open zip file.
07-27 08:54:04.279  6791  6791 E ZipFileCache: init failed when open zip file.
07-27 08:54:04.289  6791  6791 E ZipFileCache: init failed when open zip file.
07-27 08:54:04.289  6791  6791 E ZipFileCache: init failed when open zip file.
07-27 08:54:04.289  6791  6791 E ZipFileCache: init failed when open zip file.
07-27 08:54:04.289  6791  6791 E ZipFileCache: init failed when open zip file.
07-27 08:54:04.289  6791  6791 E ZipFileCache: init failed when open zip file.
07-27 08:54:04.289  6791  6791 E ZipFileCache: init failed when open zip file.
07-27 08:54:04.289  6791  6791 E ZipFileCache: init failed when open zip file.
07-27 08:54:04.289  6791  6791 E ZipFileCache: init failed when open zip file.
07-27 08:54:04.289  6791  6791 E ZipFileCache: init failed when open zip file.
07-27 08:54:04.289  6791  6791 E ZipFileCache: init failed when open zip file.
07-27 08:54:04.289  6791  6791 E ZipFileCache: init failed when open zip file.
07-27 08:54:04.289  6791  6791 E ZipFileCache: init failed when open zip file.
07-27 08:54:04.289  6791  6791 E ZipFileCache: init failed when open zip file.
07-27 08:54:04.289  6791  6791 E ZipFileCache: init failed when open zip file.
07-27 08:54:04.289  6791  6791 E ZipFileCache: init failed when open zip file.
07-27 08:54:04.289  6791  6791 E ZipFileCache: init failed when open zip file.
07-27 08:54:04.289  6791  6791 E ZipFileCache: init failed when open zip file.
07-27 08:54:04.289  6791  6791 E ZipFileCache: init failed when open zip file.
07-27 08:54:04.289  6791  6791 E ZipFileCache: init failed when open zip file.
07-27 08:54:04.289  6791  6791 E ZipFileCache: init failed when open zip file.
07-27 08:54:04.289  6791  6791 E ZipFileCache: init failed when open zip file.
07-27 08:54:04.289  6791  6791 E ZipFileCache: init failed when open zip file.
07-27 08:54:04.299  6791  6791 E ZipFileCache: init failed when open zip file.
07-27 08:54:04.299  6791  6791 E ZipFileCache: init failed when open zip file.
07-27 08:54:04.299  6791  6791 E ZipFileCache: init failed when open zip file.
07-27 08:54:04.299  6791  6791 E ZipFileCache: init failed when open zip file.
07-27 08:54:04.299  6791  6791 E ZipFileCache: init failed when open zip file.
07-27 08:54:04.299  6791  6791 E ZipFileCache: init failed when open zip file.
07-27 08:54:04.299  6791  6791 E ZipFileCache: init failed when open zip file.
07-27 08:54:04.299  6791  6791 E ZipFileCache: init failed when open zip file.
07-27 08:54:04.299  6791  6791 E ZipFileCache: init failed when open zip file.
07-27 08:54:04.299  6791  6791 W art     : Attempt to remove local handle scope entry from IRT, ignoring
07-27 08:54:04.309  6791  6791 W AwContents: onDetachedFromWindow called when already detached. Ignoring
07-27 08:54:04.309  6791  6791 I art     : Can not find class: Landroid/widget/ViewStub;
07-27 08:54:04.309  6791  6791 I art     : Can not find class: Landroid/webkit/ViewStub;
07-27 08:54:04.309  6791  6791 I art     : Can not find class: Landroid/app/ViewStub;
07-27 08:54:04.339  6791  6791 W art     : Attempt to remove local handle scope entry from IRT, ignoring
07-27 08:54:04.339  6791  6791 W art     : Attempt to remove local handle scope entry from IRT, ignoring
07-27 08:54:04.549  3265  3265 I PhoneStatusBar: hw_status_bar_operators = true, setSystemUIVisibily(SHOW_OPERATOR = false)
07-27 08:54:04.559  3265  3265 I PhoneStatusBar: shouldTranslucent:true
07-27 08:54:04.559  3265  3265 I PhoneStatusBar: hw_status_bar_operators = true, setSystemUIVisibily(SHOW_OPERATOR = false)
07-27 08:54:04.589  6791  6844 I OpenGLRenderer: Initialized EGL, version 1.4
07-27 08:54:04.649  6791  6791 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
07-27 08:54:04.649  3032  3062 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +1s105ms (total +1s176ms)
07-27 08:54:04.759  6791  6791 I chromium: [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
07-27 08:54:04.759  6791  6791 I chromium: 
07-27 08:54:04.899  6791  6856 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 58:2A:F7:ED:96:BE
07-27 08:54:04.909  6791  6856 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
07-27 08:54:04.909  6791  6856 W org.thaliproject.p2p.btconnectorlib.DiscoveryManager: isBleMultipleAdvertisementSupported: Bluetooth is not enabled so we could not check whether or not BluetoothLE multi advertisement is supported. However, Bluetooth LE is supported so we just *assume* multi advertisement is supported too (which may not always be the case).
07-27 08:54:04.919  6791  6856 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
07-27 08:54:04.919  6791  6856 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 1 -> 2
07-27 08:54:04.919  6791  6856 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 2 -> 3
07-27 08:54:04.919  6791  6856 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 1 -> 2
07-27 08:54:04.919  6791  6856 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-27 08:54:04.919  6791  6856 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 58:2A:F7:ED:96:BE
07-27 08:54:04.929  6791  6856 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
07-27 08:54:04.929  6791  6856 I io.jxcore.node.LifeCycleMonitor: start: OK
07-27 08:54:04.949  6791  6791 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,07-27 08:54:05.339  6791  6859 W jxcore-log: Initializing JXcore engine
07-27 08:54:05.339  6791  6859 W jxcore-log: JXcore engine is ready
,07-27 08:54:05.399  6791  6859 W jxcore-log: Starting JXcore engine
,07-27 08:54:05.509  6791  6859 W jxcore-log: Platform android
07-27 08:54:05.509  6791  6859 W jxcore-log: 
07-27 08:54:05.509  6791  6859 W jxcore-log: Process ARCH arm
07-27 08:54:05.509  6791  6859 W jxcore-log: 
,07-27 08:54:05.689  6791  6859 I jxcore-log: JXcore Cordova bridge is ready!
07-27 08:54:05.689  6791  6859 I jxcore-log: 
07-27 08:54:05.689  6791  6859 W jxcore-log: JXcore engine is started
,07-27 08:54:05.689  6791  6856 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,07-27 08:54:05.699  6791  6791 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,07-27 08:54:05.699  6791  6859 E jxcore  : Error!: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js
07-27 08:54:05.699  6791  6859 E jxcore  : Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,07-27 08:54:05.709  6791  6791 I chromium: [INFO:CONSOLE(57)] "App.js file failed to load : "No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\nError: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\n    at $h.require@node.js:1472:1\n    at internal_methods.loadMainFile@main.js.js:260:5\n    at JXMobile.executeJSON@main.js.js:279:7\n    at @JX_Evaluate:1:1\n"", source: file:///android_asset/www/js/thali_main.js (57)
07-27 08:54:05.709  6791  6791 I chromium: [INFO:CONSOLE(62)] "****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****", source: file:///android_asset/www/js/thali_main.js (62)
,07-27 08:54:05.829  6791  6856 W PluginManager: THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 115ms. Plugin should use CordovaInterface.getThreadPool().
,07-27 08:54:05.829  3754  4111 I HwSystemManager: AppLockService:applock password not initial or function is closed
07-27 08:54:05.829  3754  4111 I HwSystemManager: AppLockService:applock password not initial or function is closed
,07-27 08:54:05.829  3754  4052 I HwSystemManager: BgPowerManagerService:onProcessDied uid = 10084
07-27 08:54:05.829  3754  3775 I HwSystemManager: HoldService:uid:10084 pid:6265 died
07-27 08:54:05.829  3754  3775 I HwSystemManager: HoldService:oldVersionKey:10084,6265
07-27 08:54:05.829  3032  4857 E HsmCoreServiceImpl: onTransact in code is: 102
07-27 08:54:05.829  3032  4857 I MediaProcessHandler: processOp opType: 1, uid: 10084, pid: 6265
07-27 08:54:05.829  3032  4857 W MediaProcessHandler: remove target not exist, maybe the UI process: uid: 10084, pid: 6265
,07-27 08:54:05.829  6791  6791 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-27 08:54:05.829  6791  6791 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 08:54:05.829  6791  6791 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-27 08:54:05.829  6791  6791 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 08:54:05.829  6791  6791 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
,07-27 08:54:05.829  6791  6791 I io.jxcore.node.LifeCycleMonitor: stop: OK
07-27 08:54:05.829  3754  4026 I HwSystemManager: AppManager:getNetAppInfoFromDB cursor lenth = 1
,07-27 08:54:05.839  6791  6791 W ScreenOrientationListener: Removing an inexistent observer!
,07-27 08:54:05.999  6861  6861 I appproc : CLASSPATH=/system/framework/pm.jar
07-27 08:54:05.999  6861  6861 I appproc : Command=app_process /system/bin com.android.commands.pm.Pm uninstall com.test.thalitest 
07-27 08:54:05.999  6861  6861 I appproc : app_process:number,4,0
,07-27 08:54:05.999  6861  6861 I AndroidRuntime: readDownloadBoosterConfig: 'false'
,07-27 08:54:06.139  6861  6861 I         : power log dlsym ok
,07-27 08:54:06.189  6861  6861 E android_hardware_fm.cpp: register_android_hardware_fm_fmradio
07-27 08:54:06.189  6861  6861 I android_hardware_fm.cpp: ========64bit long size = 8
07-27 08:54:06.189  6861  6861 E FM_HAL  : [FM_HAL], libname is libhisifm_if
,07-27 08:54:06.189  6861  6861 I fm_hisi : FM::[fm_device_open:4655] fm_device_open
07-27 08:54:06.189  6861  6861 I fm_hisi : 
07-27 08:54:06.189  6861  6861 I fm_hisi : FM::[fm_device_open:4666] find the id:libhisifm_if and begins to open the device
07-27 08:54:06.189  6861  6861 I fm_hisi : 
07-27 08:54:06.189  6861  6861 I fm_hisi : FM::[fm_device_open:4710] device open sucess
07-27 08:54:06.189  6861  6861 I fm_hisi : 
07-27 08:54:06.189  6861  6861 E android_hardware_fm.cpp: register_android_hardware_fm_fmradio, ret is 0
,07-27 08:54:06.229  3032  3363 I art     : Can not find class: Lcom/android/server/pm/PackageInstallerService$PackageDeleteObserverAdapter;
,07-27 08:54:06.229  3032  3363 I art     : Can not find class: Lcom/android/server/pm/PackageManagerService$9;
,07-27 08:54:06.359  3754  3776 I HwSystemManager: BgPowerManagerService:onProcessDied uid = 10072
07-27 08:54:06.359  3032  3653 E HsmCoreServiceImpl: onTransact in code is: 102
07-27 08:54:06.359  3032  3653 I MediaProcessHandler: processOp opType: 1, uid: 10072, pid: 6791
07-27 08:54:06.359  3032  3653 W MediaProcessHandler: remove target not exist, maybe the UI process: uid: 10072, pid: 6791
,07-27 08:54:06.359  3754  3840 I HwSystemManager: HoldService:uid:10072 pid:6791 died
07-27 08:54:06.359  3754  3840 I HwSystemManager: HoldService:oldVersionKey:10072,6791
,07-27 08:54:06.359  3032  3068 I ActivityManager: filter receiver for action = android.intent.action.PACKAGE_REMOVED
,07-27 08:54:06.359  3032  3068 I ActivityManager: filter receiver for action = android.intent.action.PACKAGE_FULLY_REMOVED
,07-27 08:54:06.389  3032  3068 I ActivityManager: filter receiver for action = android.intent.action.UID_REMOVED
,07-27 08:54:06.419  3032  3056 W ResourceType: ResTable_typeSpec entry count inconsistent: given 1, previously 1445
,07-27 08:54:06.419  3032  3134 I InputReader: Reconfiguring input devices.  changes=0x00000010
,07-27 08:54:06.429  3467  4048 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
07-27 08:54:06.429  6226  6362 I AccountTypeManager: Adding account type = com.android.contacts.model.account.ExchangeAccountType@229ebd4e in the cache
,07-27 08:54:06.429  6226  6362 I SimFactoryManager: Get SIM state from SIM factory manager: 1,For slotId:0
,07-27 08:54:06.429  6226  6362 I SimFactoryManager: Get SIM state from SIM factory manager: 1,For slotId:1
,07-27 08:54:06.439  5937  5937 I art     : Explicit concurrent mark sweep GC freed 16637(1371KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 15MB/21MB, paused 703us total 73.037ms
,07-27 08:54:06.439  6226  6362 I AccountTypeManager: Adding account type = com.android.contacts.model.account.ExternalAccountType@13988e6f in the cache
,07-27 08:54:06.469  3534  3534 E RegisteredServicesCache: invalidateCache set mNeedToastTableFull
,07-27 08:54:06.469  3032  3197 I art     : Can not find class: Lcom/android/server/am/TaskPersister$ImageWriteQueueItem;
,07-27 08:54:06.489  6226  6362 W ResourceType: For resource 0x7f020947, entry index(2375) is beyond type entryCount(769)
07-27 08:54:06.489  6226  6362 W ResourceType: Failure getting entry for 0x7f020947 (t=1 e=2375) (error -75)
07-27 08:54:06.489  6226  6362 W ResourceType: For resource 0x7f0209a3, entry index(2467) is beyond type entryCount(769)
07-27 08:54:06.489  6226  6362 W ResourceType: Failure getting entry for 0x7f0209a3 (t=1 e=2467) (error -75)
07-27 08:54:06.489  6226  6362 I AccountTypeManager: Adding account type = com.android.contacts.model.account.ExternalAccountType@2c34a77c in the cache
,07-27 08:54:06.489  6226  6362 I AccountTypeManager: Adding account type = com.android.contacts.model.account.GoogleAccountType@235b4805 in the cache
,07-27 08:54:06.499  3754  3754 I art     : Explicit concurrent mark sweep GC freed 95078(6MB) AllocSpace objects, 27(432KB) LOS objects, 40% free, 14MB/23MB, paused 1.026ms total 122.935ms
07-27 08:54:06.499  3754  3754 I HwSystemManager: HsmPackageManager:Receive intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
07-27 08:54:06.499  3754  3754 I HwSystemManager: HsmPackageManager:replacing:false
07-27 08:54:06.499  3754  3754 I HwSystemManager: HsmPackageManager:pkgName:com.test.thalitest
,07-27 08:54:06.499  3754  3754 I HwSystemManager: HsmPackageManager:doAppRemoved, remove:com.test.thalitest
07-27 08:54:06.499  6401  6401 I art     : Explicit concurrent mark sweep GC freed 31638(2MB) AllocSpace objects, 11(176KB) LOS objects, 25% free, 13MB/18MB, paused 4.099ms total 135.627ms
,07-27 08:54:06.499  3754  3754 I HwSystemManager: ww:deleteLockData:com.test.thalitest
07-27 08:54:06.499  6226  6362 E ExternalAccountType: Unsupported attribute readOnly
,07-27 08:54:06.509  6401  6401 I HwSystemManager: HsmPackageManager:Receive intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,07-27 08:54:06.509  6401  6401 I HwSystemManager: HsmPackageManager:replacing:false
07-27 08:54:06.509  6401  6401 I HwSystemManager: HsmPackageManager:pkgName:com.test.thalitest
07-27 08:54:06.509  6401  6401 I HwSystemManager: HsmPackageManager:doAppRemoved, remove:com.test.thalitest
,07-27 08:54:06.509  6226  6362 I AccountTypeManager: AccountManager, account size is: 2
,07-27 08:54:06.509  6226  6362 I AccountTypeManager: Loaded meta-data for 5 account types, 3 accounts in 83ms(wall) 18ms(cpu)
,07-27 08:54:06.519  3032  3139 I art     : Can not find class: Lcom/android/server/net/NetworkStatsRecorder$RemoveUidRewriter;
,07-27 08:54:06.539  5632  5632 I art     : Explicit concurrent mark sweep GC freed 1956(100KB) AllocSpace objects, 0(0B) LOS objects, 25% free, 22MB/29MB, paused 2.984ms total 177.942ms
,07-27 08:54:06.549  3602  3602 I art     : Explicit concurrent mark sweep GC freed 51774(2MB) AllocSpace objects, 70(7MB) LOS objects, 38% free, 25MB/41MB, paused 1.055ms total 173.490ms
,07-27 08:54:06.549  3602  3602 I HwLauncher: Model  onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
07-27 08:54:06.549  3602  3602 I HwLauncher: Model replacing = false package = com.test.thalitest
07-27 08:54:06.549  3602  3602 I HwLauncher: Model  ACTION_PACKAGE_REMOVED replacing = false
07-27 08:54:06.549  3602  3602 I HwLauncher: MutilSelectedIconsonPreHandleUpdatedTask : mIsInMutilSelectMode = false task = 3 packages = [com.test.thalitest]
07-27 08:54:06.549  3602  3602 I HwLauncher: SimpleLauncherModeaction= android.intent.action.PACKAGE_REMOVEDpackageName = com.test.thalitest
07-27 08:54:06.549  3602  3740 I HwLauncher: Model mAllAppsList.removePackage com.test.thalitest
07-27 08:54:06.549  3602  3747 I HwLauncher: SimpleLauncherModedeleteBadgeItemFromDBByPkg packageName=com.test.thalitest
,07-27 08:54:06.559  3602  3747 I HwLauncher: Launcher.LauncherProvider  only HwLauncher can use LauncherProvider's delete method to delete badge table item 
07-27 08:54:06.559  3602  3747 I HwLauncher: SimpleAllAppsList   add packageName into uninstalledSDApps 
07-27 08:54:06.559  3602  3747 I HwLauncher: SimpleLauncherModeuninstalledSDApps size > 0
07-27 08:54:06.559  3602  3747 W HwLauncher: SimpleLauncherModeNobody to tell about the new app.  Launcher is probably loading.
07-27 08:54:06.559  3602  3747 I HwLauncher: SimpleLauncherModeOP_REMOVE callback is null, delete simpleUI database record
,07-27 08:54:06.559  3602  3602 E HideAppsPagedView: removeItems begin 
07-27 08:54:06.559  3602  3602 E HideAppsPagedView: ShortcutInfo(title=ThaliTest)
07-27 08:54:06.559  3602  3602 E HideAppsPagedView: removeItems end 
,07-27 08:54:06.569  3602  3602 I HwLauncher: Workspace removeItems info = ShortcutInfo(title=ThaliTest) isNeedDelete = true
,07-27 08:54:06.569  3602  3602 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
,07-27 08:54:06.569  3602  3602 W System.err: 	at android.app.ApplicationPackageManager.getApplicationInfo(ApplicationPackageManager.java:287)
07-27 08:54:06.569  3602  3602 W System.err: 	at com.huawei.android.launcher.ShortcutInfo.isAppUninstallable(ShortcutInfo.java:347)
,07-27 08:54:06.569  3602  3602 W System.err: 	at com.huawei.android.launcher.Workspace$10.run(Workspace.java:6784)
07-27 08:54:06.569  3602  3602 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
,07-27 08:54:06.569  3602  3602 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
07-27 08:54:06.569  3602  3602 W System.err: 	at android.os.Looper.loop(Looper.java:135)
07-27 08:54:06.569  3602  3602 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5538)
07-27 08:54:06.569  3602  3602 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
,07-27 08:54:06.569  3602  3602 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
07-27 08:54:06.569  3602  3602 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:960)
07-27 08:54:06.569  3602  3602 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:755)
,07-27 08:54:06.579  3602  3602 W System.err: java.lang.NullPointerException: null receiver
,07-27 08:54:06.579  3602  3602 W System.err: 	at java.lang.reflect.Field.get(Native Method)
,07-27 08:54:06.579  3602  3602 W System.err: 	at java.lang.reflect.Field.get(Field.java:279)
07-27 08:54:06.579  3602  3602 W System.err: 	at com.huawei.android.launcher.ShortcutInfo.isAppUninstallable(ShortcutInfo.java:372)
07-27 08:54:06.579  3602  3602 W System.err: 	at com.huawei.android.launcher.Workspace$10.run(Workspace.java:6784)
07-27 08:54:06.579  3602  3602 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
07-27 08:54:06.579  3602  3602 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
07-27 08:54:06.579  3602  3602 W System.err: 	at android.os.Looper.loop(Looper.java:135)
,07-27 08:54:06.579  3602  3602 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5538)
07-27 08:54:06.579  3602  3602 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
07-27 08:54:06.579  3602  3602 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
07-27 08:54:06.579  3602  3602 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:960)
07-27 08:54:06.579  3602  3602 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:755)
,07-27 08:54:06.579  3602  3602 I HwLauncher: CellLayout rearrangeAfterRmItem isAutoAlign = false
07-27 08:54:06.579  3602  3602 I HwLauncher: Launcher Deferring update until onResume
,07-27 08:54:06.579  3602  3602 I HwLauncher: Launcher  onWindowVisibilityChanged visibility = 4
,07-27 08:54:06.579  3602  3602 I HwLauncher: DynamicIcon onWindowVisibilityChanged 4 - com.android.calendar
,07-27 08:54:06.579  3602  3602 I HwLauncher: DynamicIcon onWindowVisibilityChanged 4 - com.android.deskclock
,07-27 08:54:06.609  3754  3921 I HwSystemManager: aor:Network Stats Updated
07-27 08:54:06.609  3754  3921 I HwSystemManager: aoi:onNetworkStatsUpdated
07-27 08:54:06.609  3754  3924 I HwSystemManager: TrafficAnalyseManager:mDataServiceStatusCard1 : false mDataServiceStatusCard2 : false
,07-27 08:54:06.609  3754  3924 E HwSystemManager: getSimCardType:/getSimCardInfo: imsi is null
,07-27 08:54:06.609  3754  3924 E HwSystemManager: getSimCardType:/getSimCardInfo: imsi is null
07-27 08:54:06.609  3754  3924 E HwSystemManager: getSimCardType:/getPhoneSimCardInfo: boths card not recongnized
07-27 08:54:06.609  3754  3924 W HwSystemManager: TrafficAnalyseManager:initCardStatus: preferredCardInfo is null.
,07-27 08:54:06.609  3754  3924 E HwSystemManager: TrafficNotifyOverMarkForDay:notifyTafficOverMarkForDay: imsi is null.
07-27 08:54:06.609  3754  3924 I HwSystemManager: TrafficAnalyseManager:mDataServiceStatusCard1 : false mDataServiceStatusCard2 : false
,07-27 08:54:06.619  3754  3924 E HwSystemManager: getSimCardType:/getSimCardInfo: imsi is null
,07-27 08:54:06.619  3754  3924 E HwSystemManager: getSimCardType:/getSimCardInfo: imsi is null
07-27 08:54:06.619  3754  3924 E HwSystemManager: getSimCardType:/getPhoneSimCardInfo: boths card not recongnized
07-27 08:54:06.619  3754  3924 W HwSystemManager: TrafficAnalyseManager:initCardStatus: preferredCardInfo is null.
,07-27 08:54:06.619  3754  3924 E HwSystemManager: TrafficNotifyOverMarkForMonth:notifyTafficOverMarkForMonth: imsi is null.
07-27 08:54:06.619  3754  3924 I HwSystemManager: TrafficAnalyseManager:mDataServiceStatusCard1 : false mDataServiceStatusCard2 : false
,07-27 08:54:06.619  3754  3924 E HwSystemManager: getSimCardType:/getSimCardInfo: imsi is null
,07-27 08:54:06.619  3754  3924 E HwSystemManager: getSimCardType:/getSimCardInfo: imsi is null
07-27 08:54:06.619  3754  3924 E HwSystemManager: getSimCardType:/getPhoneSimCardInfo: boths card not recongnized
07-27 08:54:06.619  3754  3924 W HwSystemManager: TrafficAnalyseManager:initCardStatus: preferredCardInfo is null.
,07-27 08:54:06.629  3754  3924 E HwSystemManager: TrafficNotifyExcessForMonth:notifyTafficExcessForMonth: imsi is null.
,07-27 08:54:06.679  3032  3032 I art     : Explicit concurrent mark sweep GC freed 61088(4MB) AllocSpace objects, 4(76KB) LOS objects, 33% free, 28MB/42MB, paused 1.911ms total 319.694ms
07-27 08:54:06.679  3032  3068 I art     : WaitForGcToComplete blocked for 295.481ms for cause Explicit
,07-27 08:54:06.789  3032  3127 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
07-27 08:54:06.789  3032  3127 W System.err: 	at android.app.ApplicationPackageManager.getApplicationInfo(ApplicationPackageManager.java:287)
07-27 08:54:06.789  3032  3127 W System.err: 	at com.android.server.SmartHeartBeat$HeartBeatHandler.updatePackageMessage(SmartHeartBeat.java:872)
07-27 08:54:06.789  3032  3127 W System.err: 	at com.android.server.SmartHeartBeat$HeartBeatHandler.handleMessage(SmartHeartBeat.java:606)
07-27 08:54:06.789  3032  3127 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-27 08:54:06.789  3032  3127 W System.err: 	at android.os.Looper.loop(Looper.java:135)
07-27 08:54:06.789  3032  3127 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,07-27 08:54:06.839  3032  3032 I art     : Can not find class: Lhuawei/com/android/server/util/UserBehaviourRecord;
,07-27 08:54:06.839  3032  3032 I art     : Can not find class: Lhuawei/com/android/server/util/UserBehaviourRecord$1;
,07-27 08:54:06.839  3032  3032 I art     : Can not find class: Lhuawei/com/android/server/util/ReportTool;
,07-27 08:54:06.839  3032  3032 I art     : Can not find class: Lcom/huawei/report/ReporterInterface;
,07-27 08:54:06.839  3032  3032 E ReportTools: Can't find sReporterClazz
,07-27 08:54:06.839  3032  3032 I art     : Can not find class: Lhuawei/com/android/server/util/UserBehaviourRecord$UploadThread;
,07-27 08:54:06.839  3032  3032 I art     : Can not find class: Lhuawei/com/android/server/util/AppInfo;
,07-27 08:54:06.839  3032  3032 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'int com.huawei.lcagent.client.LogCollectManager.getUserType()' on a null object reference
,07-27 08:54:06.849  3032  3032 W System.err: 	at huawei.com.android.server.util.ReportTool.getUserType(ReportTool.java:86)
07-27 08:54:06.849  3032  3032 W System.err: 	at huawei.com.android.server.util.ReportTool.isBetaUser(ReportTool.java:73)
07-27 08:54:06.849  3032  3032 W System.err: 	at huawei.com.android.server.util.ReportTool.report(ReportTool.java:58)
07-27 08:54:06.849  3032  3032 W System.err: 	at huawei.com.android.server.util.UserBehaviourRecord.appExitRecord(UserBehaviourRecord.java:65)
07-27 08:54:06.849  3032  3032 W System.err: 	at com.android.server.am.ActivityManagerService.cleanUpRemovedTaskLocked(ActivityManagerService.java:9041)
07-27 08:54:06.849  3032  3032 W System.err: 	at com.android.server.am.ActivityManagerService.removeTaskByIdLocked(ActivityManagerService.java:9097)
07-27 08:54:06.849  3032  3032 W System.err: 	at com.android.server.am.ActivityManagerService.access$1000(ActivityManagerService.java:293)
07-27 08:54:06.849  3032  3032 W System.err: 	at com.android.server.am.ActivityManagerService$3.onPackageRemoved(ActivityManagerService.java:2234)
,07-27 08:54:06.849  3032  3032 W System.err: 	at com.android.internal.content.PackageMonitor.onReceive(PackageMonitor.java:341)
07-27 08:54:06.849  3032  3032 W System.err: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:899)
07-27 08:54:06.849  3032  3032 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
07-27 08:54:06.849  3032  3032 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
07-27 08:54:06.849  3032  3032 W System.err: 	at android.os.Looper.loop(Looper.java:135)
07-27 08:54:06.849  3032  3032 W System.err: 	at com.android.server.SystemServer.run(SystemServer.java:324)
07-27 08:54:06.849  3032  3032 W System.err: 	at com.android.server.SystemServer.main(SystemServer.java:212)
07-27 08:54:06.849  3032  3032 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
07-27 08:54:06.849  3032  3032 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
07-27 08:54:06.849  3032  3032 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:960)
07-27 08:54:06.849  3032  3032 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:755)
07-27 08:54:06.849  3032  3032 E ReportTools: This is not beta user build
,07-27 08:54:06.869  3032  3068 I art     : Explicit concurrent mark sweep GC freed 6918(400KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 28MB/42MB, paused 3.338ms total 188.691ms,
07-27 08:54:06.869  3032  3264 I art     : WaitForGcToComplete blocked for 299.706ms for cause Explicit
,07-27 08:54:07.049  3032  3264 I art     : Explicit concurrent mark sweep GC freed 4248(284KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 27MB/41MB, paused 1.883ms total 178.980ms
,07-27 08:54:07.049  3602  3602 I HwLauncher: Launcher onStart()
07-27 08:54:07.049  3602  3602 I HwLauncher: Launcher dynamicIconsRegister
07-27 08:54:07.049  3602  3602 I HwLauncher: DynamicUpdater registerReceiver
,07-27 08:54:07.059  3602  3602 I HwLauncher: DynamicUpdater call updateFolder
07-27 08:54:07.059  3602  3602 I HwLauncher: DynamicIcon onResume  isvisible = false   mAttachedToWindow:true    mWindowVisible:falsecom.android.calendar
07-27 08:54:07.059  3602  3602 I HwLauncher: DynamicUpdater registerReceiver
,07-27 08:54:07.059  3602  3602 I HwLauncher: DynamicUpdater call updateFolder
07-27 08:54:07.059  3602  3602 I HwLauncher: DynamicIcon onResume  isvisible = false   mAttachedToWindow:true    mWindowVisible:falsecom.android.deskclock
07-27 08:54:07.059  3602  3602 I HwLauncher: DynamicUpdater registerReceiver
,07-27 08:54:07.059  3602  3602 I HwLauncher: DynamicUpdater call updateFolder
07-27 08:54:07.059  3602  3602 I HwLauncher: DynamicIcon onResume  isvisible = true   mAttachedToWindow:false    mWindowVisible:falsecom.huawei.android.totemweather
,07-27 08:54:07.059  3602  3602 I HwLauncher: DynamicIcon onVisibilityChanged 0 - com.android.calendar
07-27 08:54:07.059  3602  3602 I HwLauncher: DynamicIcon onVisibilityChanged 0 - com.android.deskclock
07-27 08:54:07.059  3602  3740 I HwLauncher: DynamicIconData , getDrawableForDynamic begin, pkg = com.android.deskclock, picName = deskclock_bg
07-27 08:54:07.059  3602  3602 E HideAppsPagedView: removeHideApps  begin 
07-27 08:54:07.059  3602  3602 E HideAppsPagedView: removeHideApps  end 
07-27 08:54:07.059  3602  3602 E HideAppsPagedView:  syncPages mCurrentPage = 0
,07-27 08:54:07.059  3602  3602 E ZipFileCache: init failed when open zip file.
07-27 08:54:07.059  3032  3056 W asset   : Asset path /system/framework/com.huawei.theme.stat.jar is neither a directory nor file (type=1).
07-27 08:54:07.059  3602  3602 E ZipFileCache: init failed when open zip file.
07-27 08:54:07.059  3602  3740 I HwLauncher: DynamicIconData , getDrawableForDynamic end, pkg = com.android.deskclock, picName = deskclock_bg
07-27 08:54:07.059  3602  3740 I HwLauncher: DynamicIconData , getDrawableForDynamic begin, pkg = com.android.deskclock, picName = deskclock_bg
,07-27 08:54:07.059  3602  3602 E ZipFileCache: init failed when open zip file.
07-27 08:54:07.059  3602  3740 I HwLauncher: DynamicIconData , getDrawableForDynamic end, pkg = com.android.deskclock, picName = deskclock_bg
,07-27 08:54:07.059  3602  3602 E ZipFileCache: init failed when open zip file.
07-27 08:54:07.069  3602  3602 E ZipFileCache: init failed when open zip file.
07-27 08:54:07.069  3602  3740 I HwLauncher: Launcher.Utilities createIconBitmap classname = null, sourceWidth = 114, sourceHeight = 114
07-27 08:54:07.069  3602  3602 E HideAppsPagedView:  syncAppsPageItems page = 0 mNumAppsPages = 1 mCurrentPage = 0
07-27 08:54:07.069  3602  3602 E HideAppsPagedView:  createAddIcon count = 0
07-27 08:54:07.069  3602  3602 I HwLauncher:  FPSMonitor snapToPage whichPage = 0 delta = 0 duration = 550
07-27 08:54:07.069  3602  3602 I HwLauncher: Launcher  onWindowVisibilityChanged visibility = 0
07-27 08:54:07.069  3602  3602 I HwLauncher: DynamicIcon onWindowVisibilityChanged 0 - com.android.calendar
07-27 08:54:07.069  3602  3602 I HwLauncher: DynamicIcon onWindowVisibilityChanged 0 - com.android.deskclock
07-27 08:54:07.079  3602  3740 I HwLauncher: ClockDynamicUpdater clock update folder at ClockDynamicUpdater
07-27 08:54:07.079  3602  3740 I HwLauncher: DynamicUpdater updateBitmap end and send update message
07-27 08:54:07.079  3602  3740 I HwLauncher: WeatherDynamicUpdaterpositiveUpdate at WeatherDynamicUpdater
07-27 08:54:07.079  3265  3265 I PhoneStatusBar: hw_status_bar_operators = true, setSystemUIVisibily(SHOW_OPERATOR = false)
07-27 08:54:07.079  3265  3265 I PhoneStatusBar: shouldTranslucent:true
07-27 08:54:07.079  3265  3265 I PhoneStatusBar: hw_status_bar_operators = true, setSystemUIVisibily(SHOW_OPERATOR = false)
07-27 08:54:07.099  3602  3602 I HwLauncher: DynamicUpdater call updateFolder
,07-27 08:54:07.169  2342  2342 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 55% free, 12MB/28MB, paused 592us total 23.975ms
,07-27 08:54:07.169  6908  6908 W asset   : Asset path /system/framework/com.huawei.theme.stat.jar is neither a directory nor file (type=1).
,07-27 08:54:07.179  6884  6884 E Minikin : addFont failed to create font /system/fonts/DroidSansChineseslim.ttf
,07-27 08:54:07.179  6884  6884 W GalleryUtils: the font DroidSanChineseSlim is not exist!
,07-27 08:54:07.189  2342  2342 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 55% free, 12MB/28MB, paused 224us total 23.353ms
,07-27 08:54:07.209  6908  6928 I HwCust  : Constructor found for class com.huawei.android.totemweather.utils.HwCustUseBitmapConfigImpl
,07-27 08:54:07.219  2342  2342 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 55% free, 12MB/28MB, paused 275us total 23.162ms
,07-27 08:54:07.229  6908  6908 I HwCust  : Constructor found for class com.huawei.android.totemweather.HwCustWeatherAppHwBaseImpl
,07-27 08:54:07.269  3602  3602 I HwLauncher: WeatherDynamicUpdaterreceive action = com.huawei.android.action.launcher_weather_icon_change
,07-27 08:54:07.269  3602  3740 I HwLauncher: WeatherDynamicUpdaterreceiver data is int[] = [0, 0]
07-27 08:54:07.269  3602  3740 I HwLauncher:  stringArray[] [unknown]
,07-27 08:54:07.399  3754  4052 I HwSystemManager: BgPowerManagerService:onProcessDied uid = 10050
07-27 08:54:07.399  3754  4052 I HwSystemManager: HoldService:uid:10050 pid:6379 died
07-27 08:54:07.399  3754  4052 I HwSystemManager: HoldService:oldVersionKey:10050,6379
,07-27 08:54:07.399  3032  3601 E HsmCoreServiceImpl: onTransact in code is: 102
07-27 08:54:07.399  3032  3601 I MediaProcessHandler: processOp opType: 1, uid: 10050, pid: 6379
07-27 08:54:07.399  3032  3601 W MediaProcessHandler: remove target not exist, maybe the UI process: uid: 10050, pid: 6379

```
