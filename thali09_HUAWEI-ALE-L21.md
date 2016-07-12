#### Test 757892685a40176_thali09_HUAWEI-ALE-L21 Logs


```
int logctl_get(): open '/dev/hwlog_switch' fail -1, 13. Permission denied

Note: log switch off, only log_main and log_events will have logs!
,--------- beginning of main
07-12 17:44:54.859  7343  7343 I appproc : CLASSPATH=/system/framework/am.jar
07-12 17:44:54.859  7343  7343 I appproc : Command=app_process /system/bin com.android.commands.am.Am start -n com.test.thalitest/com.test.thalitest.MainActivity 
07-12 17:44:54.859  7343  7343 I appproc : app_process:number,5,0
07-12 17:44:54.859  7343  7343 I AndroidRuntime: readDownloadBoosterConfig: 'false'
07-12 17:44:55.009  7343  7343 I         : power log dlsym ok
07-12 17:44:55.049  7343  7343 E android_hardware_fm.cpp: register_android_hardware_fm_fmradio
07-12 17:44:55.049  7343  7343 I android_hardware_fm.cpp: ========64bit long size = 8
07-12 17:44:55.049  7343  7343 E FM_HAL  : [FM_HAL], libname is libhisifm_if
07-12 17:44:55.049  7343  7343 I fm_hisi : FM::[fm_device_open:4655] fm_device_open
07-12 17:44:55.049  7343  7343 I fm_hisi : 
07-12 17:44:55.049  7343  7343 I fm_hisi : FM::[fm_device_open:4666] find the id:libhisifm_if and begins to open the device
07-12 17:44:55.049  7343  7343 I fm_hisi : 
07-12 17:44:55.049  7343  7343 I fm_hisi : FM::[fm_device_open:4710] device open sucess
07-12 17:44:55.049  7343  7343 I fm_hisi : 
07-12 17:44:55.049  7343  7343 E android_hardware_fm.cpp: register_android_hardware_fm_fmradio, ret is 0
07-12 17:44:55.099  3029  3049 I art     : Can not find class: Lcom/android/server/wm/WindowState$2;
07-12 17:44:55.099  3029  3049 I art     : Can not find class: Lcom/android/server/am/TaskPersister$TaskWriteQueueItem;
07-12 17:44:55.099  3029  3049 I art     : Can not find class: Lcom/android/server/am/TaskPersister$WriteQueueItem;
07-12 17:44:55.159  3029  3369 I art     : Can not find class: Lcom/android/server/am/ActivityStack$2;
07-12 17:44:55.169  3580  3949 W PhoneStateManager: screen off and not process front event:com.test.thalitest
07-12 17:44:55.179  3955  4036 I HwSystemManager: AppLockService:applock password not initial or function is closed
07-12 17:44:55.179  3955  4036 I HwSystemManager: AppLockService:applock password not initial or function is closed
07-12 17:44:55.179  3955  4288 I HwSystemManager: AppManager:getNetAppInfoFromDB cursor lenth = 1
07-12 17:44:55.179  3696  3696 I HwLauncher: Launcher  onWindowVisibilityChanged visibility = 8
07-12 17:44:55.179  3696  3696 I HwLauncher: DynamicIcon onWindowVisibilityChanged 8 - com.android.calendar
07-12 17:44:55.179  3696  3696 I HwLauncher: DynamicIcon onWindowVisibilityChanged 8 - com.android.deskclock
07-12 17:44:55.189  3696  3696 I HwLauncher: DynamicIcon onVisibilityChanged 4 - com.android.calendar
07-12 17:44:55.189  3696  3696 I HwLauncher: DynamicIcon onVisibilityChanged 4 - com.android.deskclock
07-12 17:44:55.329  7368  7368 I WebViewFactory: Loading com.android.webview version 37 (eng.jenkins-arm64) (code 199992)
07-12 17:44:55.339  7368  7368 I LibraryLoader: Loading: webviewchromium
07-12 17:44:55.339  7368  7368 I LibraryLoader: Time to load native libraries: 4 ms (timestamps 1993-1997)
07-12 17:44:55.339  7368  7368 I LibraryLoader: Expected native library version number "",actual native library version number ""
,07-12 17:44:55.359  7368  7368 E ZipFileCache: init failed when open zip file.
07-12 17:44:55.359  7368  7368 E ZipFileCache: init failed when open zip file.
07-12 17:44:55.369  7368  7368 E ZipFileCache: init failed when open zip file.
07-12 17:44:55.369  7368  7368 E ZipFileCache: init failed when open zip file.
07-12 17:44:55.379  7368  7368 I LibraryLoader: Expected native library version number "",actual native library version number ""
07-12 17:44:55.379  7368  7368 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
07-12 17:44:55.389  7368  7368 I BrowserStartupController: Initializing chromium process, renderers=0
07-12 17:44:55.389  7368  7368 W art     : Attempt to remove local handle scope entry from IRT, ignoring
07-12 17:44:55.399  7368  7394 W chromium: [WARNING:dns_config_service_posix.cc(293)] Failed to read DnsConfig.
07-12 17:44:55.399  7368  7368 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
07-12 17:44:55.399  7368  7368 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=37 off=46092 len=2953
07-12 17:44:55.399  7368  7368 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:38 off:228796 len:643667
07-12 17:44:55.489  7368  7404 W chromium: [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
07-12 17:44:55.489  7368  7404 W chromium: [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
07-12 17:44:55.499  7368  7368 W chromium: [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
07-12 17:44:55.539  7368  7368 E ZipFileCache: init failed when open zip file.
07-12 17:44:55.539  7368  7368 E ZipFileCache: init failed when open zip file.
07-12 17:44:55.539  7368  7368 E ZipFileCache: init failed when open zip file.
07-12 17:44:55.549  7368  7368 E ZipFileCache: init failed when open zip file.
07-12 17:44:55.549  7368  7368 E ZipFileCache: init failed when open zip file.
07-12 17:44:55.549  7368  7368 E ZipFileCache: init failed when open zip file.
07-12 17:44:55.549  7368  7368 E ZipFileCache: init failed when open zip file.
07-12 17:44:55.549  7368  7368 E ZipFileCache: init failed when open zip file.
07-12 17:44:55.549  7368  7368 E ZipFileCache: init failed when open zip file.
07-12 17:44:55.549  7368  7368 E ZipFileCache: init failed when open zip file.
07-12 17:44:55.559  7368  7368 E ZipFileCache: init failed when open zip file.
07-12 17:44:55.559  7368  7368 E ZipFileCache: init failed when open zip file.
07-12 17:44:55.559  7368  7368 E ZipFileCache: init failed when open zip file.
07-12 17:44:55.559  7368  7368 E ZipFileCache: init failed when open zip file.
07-12 17:44:55.569  7368  7368 E ZipFileCache: init failed when open zip file.
07-12 17:44:55.569  7368  7368 E ZipFileCache: init failed when open zip file.
07-12 17:44:55.569  7368  7368 E ZipFileCache: init failed when open zip file.
07-12 17:44:55.569  7368  7368 E ZipFileCache: init failed when open zip file.
07-12 17:44:55.579  7368  7368 E ZipFileCache: init failed when open zip file.
07-12 17:44:55.579  7368  7368 E ZipFileCache: init failed when open zip file.
07-12 17:44:55.579  7368  7368 E ZipFileCache: init failed when open zip file.
07-12 17:44:55.579  7368  7368 E ZipFileCache: init failed when open zip file.
07-12 17:44:55.579  7368  7368 E ZipFileCache: init failed when open zip file.
07-12 17:44:55.579  7368  7368 E ZipFileCache: init failed when open zip file.
07-12 17:44:55.589  7368  7368 E ZipFileCache: init failed when open zip file.
07-12 17:44:55.589  7368  7368 E ZipFileCache: init failed when open zip file.
07-12 17:44:55.589  7368  7368 E ZipFileCache: init failed when open zip file.
07-12 17:44:55.589  7368  7368 E ZipFileCache: init failed when open zip file.
07-12 17:44:55.589  7368  7368 E ZipFileCache: init failed when open zip file.
07-12 17:44:55.589  7368  7368 E ZipFileCache: init failed when open zip file.
07-12 17:44:55.599  7368  7368 E ZipFileCache: init failed when open zip file.
07-12 17:44:55.599  7368  7368 E ZipFileCache: init failed when open zip file.
07-12 17:44:55.599  7368  7368 E ZipFileCache: init failed when open zip file.
07-12 17:44:55.599  7368  7368 E ZipFileCache: init failed when open zip file.
07-12 17:44:55.599  7368  7368 E ZipFileCache: init failed when open zip file.
07-12 17:44:55.609  7368  7368 E ZipFileCache: init failed when open zip file.
07-12 17:44:55.609  7368  7368 E ZipFileCache: init failed when open zip file.
07-12 17:44:55.609  7368  7368 E ZipFileCache: init failed when open zip file.
07-12 17:44:55.609  7368  7368 E ZipFileCache: init failed when open zip file.
07-12 17:44:55.609  7368  7368 E ZipFileCache: init failed when open zip file.
07-12 17:44:55.619  7368  7368 E ZipFileCache: init failed when open zip file.
07-12 17:44:55.619  7368  7368 E ZipFileCache: init failed when open zip file.
07-12 17:44:55.619  7368  7368 E ZipFileCache: init failed when open zip file.
07-12 17:44:55.619  7368  7368 E ZipFileCache: init failed when open zip file.
07-12 17:44:55.619  7368  7368 E ZipFileCache: init failed when open zip file.
07-12 17:44:55.619  7368  7368 E ZipFileCache: init failed when open zip file.
07-12 17:44:55.619  7368  7368 E ZipFileCache: init failed when open zip file.
07-12 17:44:55.619  7368  7368 E ZipFileCache: init failed when open zip file.
07-12 17:44:55.629  7368  7368 E ZipFileCache: init failed when open zip file.
07-12 17:44:55.629  7368  7368 E ZipFileCache: init failed when open zip file.
07-12 17:44:55.629  7368  7368 E ZipFileCache: init failed when open zip file.
07-12 17:44:55.629  7368  7368 E ZipFileCache: init failed when open zip file.
07-12 17:44:55.629  7368  7368 E ZipFileCache: init failed when open zip file.
07-12 17:44:55.629  7368  7368 E ZipFileCache: init failed when open zip file.
07-12 17:44:55.629  7368  7368 E ZipFileCache: init failed when open zip file.
07-12 17:44:55.629  7368  7368 E ZipFileCache: init failed when open zip file.
07-12 17:44:55.629  7368  7368 E ZipFileCache: init failed when open zip file.
07-12 17:44:55.629  7368  7368 E ZipFileCache: init failed when open zip file.
07-12 17:44:55.629  7368  7368 E ZipFileCache: init failed when open zip file.
07-12 17:44:55.629  7368  7368 E ZipFileCache: init failed when open zip file.
07-12 17:44:55.629  7368  7368 E ZipFileCache: init failed when open zip file.
07-12 17:44:55.629  7368  7368 E ZipFileCache: init failed when open zip file.
07-12 17:44:55.629  7368  7368 E ZipFileCache: init failed when open zip file.
07-12 17:44:55.629  7368  7368 E ZipFileCache: init failed when open zip file.
07-12 17:44:55.629  7368  7368 E ZipFileCache: init failed when open zip file.
07-12 17:44:55.629  7368  7368 E ZipFileCache: init failed when open zip file.
07-12 17:44:55.629  7368  7368 E ZipFileCache: init failed when open zip file.
07-12 17:44:55.629  7368  7368 E ZipFileCache: init failed when open zip file.
07-12 17:44:55.639  7368  7368 E ZipFileCache: init failed when open zip file.
07-12 17:44:55.639  7368  7368 E ZipFileCache: init failed when open zip file.
07-12 17:44:55.639  7368  7368 E ZipFileCache: init failed when open zip file.
07-12 17:44:55.639  7368  7368 E ZipFileCache: init failed when open zip file.
07-12 17:44:55.639  7368  7368 E ZipFileCache: init failed when open zip file.
07-12 17:44:55.639  7368  7368 E ZipFileCache: init failed when open zip file.
07-12 17:44:55.639  7368  7368 E ZipFileCache: init failed when open zip file.
07-12 17:44:55.639  7368  7368 E ZipFileCache: init failed when open zip file.
07-12 17:44:55.639  7368  7368 E ZipFileCache: init failed when open zip file.
07-12 17:44:55.639  7368  7368 E ZipFileCache: init failed when open zip file.
07-12 17:44:55.639  7368  7368 E ZipFileCache: init failed when open zip file.
07-12 17:44:55.639  7368  7368 E ZipFileCache: init failed when open zip file.
07-12 17:44:55.639  7368  7368 E ZipFileCache: init failed when open zip file.
07-12 17:44:55.639  7368  7368 E ZipFileCache: init failed when open zip file.
07-12 17:44:55.649  7368  7368 E ZipFileCache: init failed when open zip file.
07-12 17:44:55.649  7368  7368 E ZipFileCache: init failed when open zip file.
07-12 17:44:55.649  7368  7368 E ZipFileCache: init failed when open zip file.
07-12 17:44:55.649  7368  7368 E ZipFileCache: init failed when open zip file.
07-12 17:44:55.649  7368  7368 E ZipFileCache: init failed when open zip file.
07-12 17:44:55.649  7368  7368 E ZipFileCache: init failed when open zip file.
07-12 17:44:55.649  7368  7368 E ZipFileCache: init failed when open zip file.
07-12 17:44:55.649  7368  7368 E ZipFileCache: init failed when open zip file.
07-12 17:44:55.659  7368  7368 E ZipFileCache: init failed when open zip file.
07-12 17:44:55.659  7368  7368 E ZipFileCache: init failed when open zip file.
07-12 17:44:55.659  7368  7368 E ZipFileCache: init failed when open zip file.
07-12 17:44:55.659  7368  7368 E ZipFileCache: init failed when open zip file.
07-12 17:44:55.669  7368  7368 E ZipFileCache: init failed when open zip file.
07-12 17:44:55.669  7368  7368 E ZipFileCache: init failed when open zip file.
07-12 17:44:55.669  7368  7368 E ZipFileCache: init failed when open zip file.
07-12 17:44:55.669  7368  7368 E ZipFileCache: init failed when open zip file.
07-12 17:44:55.669  7368  7368 E ZipFileCache: init failed when open zip file.
07-12 17:44:55.669  7368  7368 E ZipFileCache: init failed when open zip file.
07-12 17:44:55.679  7368  7368 E ZipFileCache: init failed when open zip file.
07-12 17:44:55.679  7368  7368 E ZipFileCache: init failed when open zip file.
07-12 17:44:55.679  7368  7368 E ZipFileCache: init failed when open zip file.
07-12 17:44:55.679  7368  7368 E ZipFileCache: init failed when open zip file.
07-12 17:44:55.679  7368  7368 E ZipFileCache: init failed when open zip file.
07-12 17:44:55.679  7368  7368 E ZipFileCache: init failed when open zip file.
07-12 17:44:55.689  7368  7368 E ZipFileCache: init failed when open zip file.
07-12 17:44:55.689  7368  7368 E ZipFileCache: init failed when open zip file.
07-12 17:44:55.689  7368  7368 E ZipFileCache: init failed when open zip file.
07-12 17:44:55.689  7368  7368 E ZipFileCache: init failed when open zip file.
07-12 17:44:55.699  7368  7368 E ZipFileCache: init failed when open zip file.
07-12 17:44:55.699  7368  7368 E ZipFileCache: init failed when open zip file.
07-12 17:44:55.699  7368  7368 E ZipFileCache: init failed when open zip file.
07-12 17:44:55.699  7368  7368 E ZipFileCache: init failed when open zip file.
07-12 17:44:55.699  7368  7368 E ZipFileCache: init failed when open zip file.
07-12 17:44:55.709  7368  7368 E ZipFileCache: init failed when open zip file.
07-12 17:44:55.709  7368  7368 E ZipFileCache: init failed when open zip file.
07-12 17:44:55.709  7368  7368 E ZipFileCache: init failed when open zip file.
07-12 17:44:55.709  7368  7368 E ZipFileCache: init failed when open zip file.
07-12 17:44:55.709  7368  7368 E ZipFileCache: init failed when open zip file.
07-12 17:44:55.719  7368  7368 E ZipFileCache: init failed when open zip file.
07-12 17:44:55.719  7368  7368 E ZipFileCache: init failed when open zip file.
07-12 17:44:55.719  7368  7368 E ZipFileCache: init failed when open zip file.
07-12 17:44:55.719  7368  7368 E ZipFileCache: init failed when open zip file.
07-12 17:44:55.719  7368  7368 E ZipFileCache: init failed when open zip file.
07-12 17:44:55.719  7368  7368 E ZipFileCache: init failed when open zip file.
07-12 17:44:55.719  7368  7368 E ZipFileCache: init failed when open zip file.
07-12 17:44:55.719  7368  7368 E ZipFileCache: init failed when open zip file.
07-12 17:44:55.719  7368  7368 E ZipFileCache: init failed when open zip file.
07-12 17:44:55.719  7368  7368 E ZipFileCache: init failed when open zip file.
07-12 17:44:55.719  7368  7368 E ZipFileCache: init failed when open zip file.
07-12 17:44:55.719  7368  7368 E ZipFileCache: init failed when open zip file.
07-12 17:44:55.719  7368  7368 E ZipFileCache: init failed when open zip file.
07-12 17:44:55.719  7368  7368 E ZipFileCache: init failed when open zip file.
07-12 17:44:55.729  7368  7368 E ZipFileCache: init failed when open zip file.
07-12 17:44:55.729  7368  7368 E ZipFileCache: init failed when open zip file.
07-12 17:44:55.729  7368  7368 E ZipFileCache: init failed when open zip file.
07-12 17:44:55.729  7368  7368 E ZipFileCache: init failed when open zip file.
07-12 17:44:55.729  7368  7368 E ZipFileCache: init failed when open zip file.
07-12 17:44:55.729  7368  7368 E ZipFileCache: init failed when open zip file.
07-12 17:44:55.729  7368  7368 E ZipFileCache: init failed when open zip file.
07-12 17:44:55.729  7368  7368 E ZipFileCache: init failed when open zip file.
07-12 17:44:55.729  7368  7368 E ZipFileCache: init failed when open zip file.
07-12 17:44:55.729  7368  7368 E ZipFileCache: init failed when open zip file.
07-12 17:44:55.729  7368  7368 E ZipFileCache: init failed when open zip file.
07-12 17:44:55.729  7368  7368 E ZipFileCache: init failed when open zip file.
07-12 17:44:55.729  7368  7368 E ZipFileCache: init failed when open zip file.
07-12 17:44:55.729  7368  7368 E ZipFileCache: init failed when open zip file.
07-12 17:44:55.729  7368  7368 E ZipFileCache: init failed when open zip file.
07-12 17:44:55.729  7368  7368 E ZipFileCache: init failed when open zip file.
07-12 17:44:55.729  7368  7368 E ZipFileCache: init failed when open zip file.
07-12 17:44:55.729  7368  7368 E ZipFileCache: init failed when open zip file.
07-12 17:44:55.729  7368  7368 E ZipFileCache: init failed when open zip file.
07-12 17:44:55.729  7368  7368 E ZipFileCache: init failed when open zip file.
07-12 17:44:55.739  7368  7368 E ZipFileCache: init failed when open zip file.
07-12 17:44:55.739  7368  7368 E ZipFileCache: init failed when open zip file.
07-12 17:44:55.739  7368  7368 W art     : Attempt to remove local handle scope entry from IRT, ignoring
07-12 17:44:55.739  7368  7368 W AwContents: onDetachedFromWindow called when already detached. Ignoring
07-12 17:44:55.749  7368  7368 I art     : Can not find class: Landroid/widget/ViewStub;
07-12 17:44:55.749  7368  7368 I art     : Can not find class: Landroid/webkit/ViewStub;
07-12 17:44:55.749  7368  7368 I art     : Can not find class: Landroid/app/ViewStub;
07-12 17:44:55.769  7368  7368 W art     : Attempt to remove local handle scope entry from IRT, ignoring
07-12 17:44:55.769  7368  7368 W art     : Attempt to remove local handle scope entry from IRT, ignoring
07-12 17:44:56.009  3357  3357 I PhoneStatusBar: hw_status_bar_operators = true, setSystemUIVisibily(SHOW_OPERATOR = false)
07-12 17:44:56.009  3357  3357 I PhoneStatusBar: shouldTranslucent:true
07-12 17:44:56.009  3357  3357 I PhoneStatusBar: hw_status_bar_operators = true, setSystemUIVisibily(SHOW_OPERATOR = false)
07-12 17:44:56.039  7368  7418 I OpenGLRenderer: Initialized EGL, version 1.4
07-12 17:44:56.099  7368  7368 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
07-12 17:44:56.099  3029  3060 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +930ms (total +1s1ms)
,07-12 17:44:56.209  7368  7368 I chromium: [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
07-12 17:44:56.209  7368  7368 I chromium: 
07-12 17:44:56.399  7368  7430 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 58:2A:F7:ED:96:BE
07-12 17:44:56.429  7368  7430 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
07-12 17:44:56.429  7368  7430 W org.thaliproject.p2p.btconnectorlib.DiscoveryManager: isBleMultipleAdvertisementSupported: Bluetooth is not enabled so we could not check whether or not BluetoothLE multi advertisement is supported. However, Bluetooth LE is supported so we just *assume* multi advertisement is supported too (which may not always be the case).
07-12 17:44:56.429  7368  7430 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
07-12 17:44:56.429  7368  7430 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 1 -> 2
07-12 17:44:56.429  7368  7430 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 2 -> 3
07-12 17:44:56.429  7368  7430 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 1 -> 2
07-12 17:44:56.439  7368  7430 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-12 17:44:56.439  7368  7430 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 58:2A:F7:ED:96:BE
07-12 17:44:56.439  7368  7430 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
07-12 17:44:56.439  7368  7430 I io.jxcore.node.LifeCycleMonitor: start: OK
07-12 17:44:56.469  7368  7368 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,07-12 17:44:56.919  7368  7433 W jxcore-log: Initializing JXcore engine
07-12 17:44:56.919  7368  7433 W jxcore-log: JXcore engine is ready
,07-12 17:44:56.989  7368  7433 W jxcore-log: Starting JXcore engine
,07-12 17:44:57.109  7368  7433 W jxcore-log: Platform android
07-12 17:44:57.109  7368  7433 W jxcore-log: 
07-12 17:44:57.109  7368  7433 W jxcore-log: Process ARCH arm
07-12 17:44:57.109  7368  7433 W jxcore-log: 
,07-12 17:44:57.319  7368  7433 I jxcore-log: JXcore Cordova bridge is ready!
07-12 17:44:57.319  7368  7433 I jxcore-log: 
,07-12 17:44:57.319  7368  7433 W jxcore-log: JXcore engine is started
,07-12 17:44:57.319  7368  7430 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,07-12 17:44:57.329  7368  7368 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,07-12 17:44:57.339  7368  7433 E jxcore  : Error!: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js
07-12 17:44:57.339  7368  7433 E jxcore  : Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,07-12 17:44:57.339  7368  7368 I chromium: [INFO:CONSOLE(57)] "App.js file failed to load : "No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\nError: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\n    at $h.require@node.js:1472:1\n    at internal_methods.loadMainFile@main.js.js:260:5\n    at JXMobile.executeJSON@main.js.js:279:7\n    at @JX_Evaluate:1:1\n"", source: file:///android_asset/www/js/thali_main.js (57)
07-12 17:44:57.339  7368  7368 I chromium: [INFO:CONSOLE(62)] "****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****", source: file:///android_asset/www/js/thali_main.js (62)
,07-12 17:44:57.459  7368  7430 W PluginManager: THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 115ms. Plugin should use CordovaInterface.getThreadPool().
07-12 17:44:57.459  3955  3979 I HwSystemManager: AppLockService:applock password not initial or function is closed
07-12 17:44:57.459  3955  3979 I HwSystemManager: AppLockService:applock password not initial or function is closed
,07-12 17:44:57.459  3955  4491 I HwSystemManager: BgPowerManagerService:onProcessDied uid = 10084
07-12 17:44:57.459  3955  4491 I HwSystemManager: HoldService:uid:10084 pid:6777 died
07-12 17:44:57.459  3955  4491 I HwSystemManager: HoldService:oldVersionKey:10084,6777
07-12 17:44:57.459  3029  3670 E HsmCoreServiceImpl: onTransact in code is: 102
07-12 17:44:57.459  3029  3670 I MediaProcessHandler: processOp opType: 1, uid: 10084, pid: 6777
07-12 17:44:57.459  3029  3670 W MediaProcessHandler: remove target not exist, maybe the UI process: uid: 10084, pid: 6777
,07-12 17:44:57.459  7368  7368 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,07-12 17:44:57.459  7368  7368 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-12 17:44:57.459  7368  7368 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-12 17:44:57.459  7368  7368 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-12 17:44:57.459  7368  7368 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
,07-12 17:44:57.469  3955  4288 I HwSystemManager: AppManager:getNetAppInfoFromDB cursor lenth = 1
,07-12 17:44:57.469  7368  7368 I io.jxcore.node.LifeCycleMonitor: stop: OK
,07-12 17:44:57.469  7368  7368 W ScreenOrientationListener: Removing an inexistent observer!
,07-12 17:44:57.509  6181  7303 I PG Utils: acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,07-12 17:44:57.639  7435  7435 I appproc : CLASSPATH=/system/framework/pm.jar
07-12 17:44:57.639  7435  7435 I appproc : Command=app_process /system/bin com.android.commands.pm.Pm uninstall com.test.thalitest 
07-12 17:44:57.639  7435  7435 I appproc : app_process:number,4,0
,07-12 17:44:57.639  7435  7435 I AndroidRuntime: readDownloadBoosterConfig: 'false'
,07-12 17:44:57.779  7435  7435 I         : power log dlsym ok
,07-12 17:44:57.819  7435  7435 E android_hardware_fm.cpp: register_android_hardware_fm_fmradio
07-12 17:44:57.819  7435  7435 I android_hardware_fm.cpp: ========64bit long size = 8
07-12 17:44:57.819  7435  7435 E FM_HAL  : [FM_HAL], libname is libhisifm_if
,07-12 17:44:57.819  7435  7435 I fm_hisi : FM::[fm_device_open:4655] fm_device_open
07-12 17:44:57.819  7435  7435 I fm_hisi : 
07-12 17:44:57.819  7435  7435 I fm_hisi : FM::[fm_device_open:4666] find the id:libhisifm_if and begins to open the device
07-12 17:44:57.819  7435  7435 I fm_hisi : 
07-12 17:44:57.819  7435  7435 I fm_hisi : FM::[fm_device_open:4710] device open sucess
07-12 17:44:57.819  7435  7435 I fm_hisi : 
07-12 17:44:57.819  7435  7435 E android_hardware_fm.cpp: register_android_hardware_fm_fmradio, ret is 0
,07-12 17:44:57.859  3029  3695 I art     : Can not find class: Lcom/android/server/pm/PackageInstallerService$PackageDeleteObserverAdapter;
,07-12 17:44:57.859  3029  3695 I art     : Can not find class: Lcom/android/server/pm/PackageManagerService$9;
,07-12 17:44:58.099  3955  4491 I HwSystemManager: BgPowerManagerService:onProcessDied uid = 10072
07-12 17:44:58.099  3955  4030 I HwSystemManager: HoldService:uid:10072 pid:7368 died
07-12 17:44:58.099  3955  4030 I HwSystemManager: HoldService:oldVersionKey:10072,7368
,07-12 17:44:58.099  3029  3670 E HsmCoreServiceImpl: onTransact in code is: 102
07-12 17:44:58.099  3029  3670 I MediaProcessHandler: processOp opType: 1, uid: 10072, pid: 7368
07-12 17:44:58.099  3029  3670 W MediaProcessHandler: remove target not exist, maybe the UI process: uid: 10072, pid: 7368
,07-12 17:44:58.099  3029  3291 I art     : Can not find class: Lcom/android/server/am/TaskPersister$ImageWriteQueueItem;
,07-12 17:44:58.149  6955  6955 I art     : Explicit concurrent mark sweep GC freed 31314(2MB) AllocSpace objects, 10(160KB) LOS objects, 24% free, 13MB/18MB, paused 3.424ms total 49.751ms
,07-12 17:44:58.159  6505  6505 I art     : Explicit concurrent mark sweep GC freed 16717(1375KB) AllocSpace objects, 0(0B) LOS objects, 25% free, 16MB/21MB, paused 1.094ms total 59.060ms
,07-12 17:44:58.169  3955  3955 I art     : Explicit concurrent mark sweep GC freed 95863(6MB) AllocSpace objects, 27(432KB) LOS objects, 39% free, 14MB/23MB, paused 1.486ms total 66.338ms
,07-12 17:44:58.179  3029  3067 I ActivityManager: filter receiver for action = android.intent.action.PACKAGE_REMOVED
,07-12 17:44:58.179  3955  3955 I HwSystemManager: HsmPackageManager:Receive intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
07-12 17:44:58.179  3955  3955 I HwSystemManager: HsmPackageManager:replacing:false
07-12 17:44:58.179  3955  3955 I HwSystemManager: HsmPackageManager:pkgName:com.test.thalitest
07-12 17:44:58.179  3955  3955 I HwSystemManager: HsmPackageManager:doAppRemoved, remove:com.test.thalitest
,07-12 17:44:58.179  3955  3955 I HwSystemManager: ww:deleteLockData:com.test.thalitest
,07-12 17:44:58.189  3029  3067 I ActivityManager: filter receiver for action = android.intent.action.PACKAGE_FULLY_REMOVED
,07-12 17:44:58.189  3029  3229 I InputReader: Reconfiguring input devices.  changes=0x00000010
,07-12 17:44:58.189  6955  6955 I HwSystemManager: HsmPackageManager:Receive intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
07-12 17:44:58.189  6955  6955 I HwSystemManager: HsmPackageManager:replacing:false
07-12 17:44:58.189  6955  6955 I HwSystemManager: HsmPackageManager:pkgName:com.test.thalitest
07-12 17:44:58.189  6955  6955 I HwSystemManager: HsmPackageManager:doAppRemoved, remove:com.test.thalitest
,07-12 17:44:58.199  6717  6916 I AccountTypeManager: Adding account type = com.android.contacts.model.account.ExchangeAccountType@290d3238 in the cache
,07-12 17:44:58.199  6717  6916 I SimFactoryManager: Get SIM state from SIM factory manager: 1,For slotId:0
,07-12 17:44:58.199  6717  6916 I SimFactoryManager: Get SIM state from SIM factory manager: 1,For slotId:1
,07-12 17:44:58.199  3523  4178 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,07-12 17:44:58.209  6717  6916 I AccountTypeManager: Adding account type = com.android.contacts.model.account.ExternalAccountType@f3ba211 in the cache
,07-12 17:44:58.209  3029  3067 I ActivityManager: filter receiver for action = android.intent.action.UID_REMOVED
,07-12 17:44:58.219  6717  6916 W ResourceType: For resource 0x7f020947, entry index(2375) is beyond type entryCount(769)
07-12 17:44:58.219  6717  6916 W ResourceType: Failure getting entry for 0x7f020947 (t=1 e=2375) (error -75)
07-12 17:44:58.219  6717  6916 W ResourceType: For resource 0x7f0209a3, entry index(2467) is beyond type entryCount(769)
07-12 17:44:58.219  6717  6916 W ResourceType: Failure getting entry for 0x7f0209a3 (t=1 e=2467) (error -75)
07-12 17:44:58.219  6717  6916 I AccountTypeManager: Adding account type = com.android.contacts.model.account.ExternalAccountType@11eb5f76 in the cache
07-12 17:44:58.219  6717  6916 I AccountTypeManager: Adding account type = com.android.contacts.model.account.GoogleAccountType@2391c977 in the cache
,07-12 17:44:58.229  6717  6916 E ExternalAccountType: Unsupported attribute readOnly
,07-12 17:44:58.229  6717  6916 I AccountTypeManager: AccountManager, account size is: 2
,07-12 17:44:58.229  6717  6916 I AccountTypeManager: Loaded meta-data for 5 account types, 3 accounts in 42ms(wall) 17ms(cpu)
,07-12 17:44:58.249  6181  6181 I art     : Explicit concurrent mark sweep GC freed 7586(501KB) AllocSpace objects, 0(0B) LOS objects, 25% free, 23MB/30MB, paused 959us total 147.540ms
,07-12 17:44:58.269  3029  3234 I art     : Can not find class: Lcom/android/server/net/NetworkStatsRecorder$RemoveUidRewriter;
,07-12 17:44:58.289  3626  3626 E RegisteredServicesCache: invalidateCache set mNeedToastTableFull
,07-12 17:44:58.299  3696  3696 I art     : Explicit concurrent mark sweep GC freed 63825(3MB) AllocSpace objects, 112(11MB) LOS objects, 38% free, 25MB/41MB, paused 1.066ms total 137.391ms
07-12 17:44:58.299  3696  3696 I HwLauncher: Model  onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
07-12 17:44:58.299  3696  3696 I HwLauncher: Model replacing = false package = com.test.thalitest
07-12 17:44:58.299  3696  3696 I HwLauncher: Model  ACTION_PACKAGE_REMOVED replacing = false
07-12 17:44:58.299  3696  3696 I HwLauncher: MutilSelectedIconsonPreHandleUpdatedTask : mIsInMutilSelectMode = false task = 3 packages = [com.test.thalitest]
07-12 17:44:58.299  3696  3853 I HwLauncher: Model mAllAppsList.removePackage com.test.thalitest
07-12 17:44:58.299  3696  3696 I HwLauncher: SimpleLauncherModeaction= android.intent.action.PACKAGE_REMOVEDpackageName = com.test.thalitest
07-12 17:44:58.299  3696  3696 E HideAppsPagedView: removeItems begin 
07-12 17:44:58.299  3696  3696 E HideAppsPagedView: ShortcutInfo(title=ThaliTest)
07-12 17:44:58.299  3696  3696 E HideAppsPagedView: removeItems end 
07-12 17:44:58.299  3696  3857 I HwLauncher: SimpleLauncherModedeleteBadgeItemFromDBByPkg packageName=com.test.thalitest
,07-12 17:44:58.299  3696  3696 I HwLauncher: Workspace removeItems info = ShortcutInfo(title=ThaliTest) isNeedDelete = true
,07-12 17:44:58.299  3696  3857 I HwLauncher: Launcher.LauncherProvider  only HwLauncher can use LauncherProvider's delete method to delete badge table item 
07-12 17:44:58.299  3696  3857 I HwLauncher: SimpleAllAppsList   add packageName into uninstalledSDApps 
,07-12 17:44:58.299  3696  3857 I HwLauncher: SimpleLauncherModeuninstalledSDApps size > 0
07-12 17:44:58.299  3696  3857 W HwLauncher: SimpleLauncherModeNobody to tell about the new app.  Launcher is probably loading.
07-12 17:44:58.299  3696  3857 I HwLauncher: SimpleLauncherModeOP_REMOVE callback is null, delete simpleUI database record
,07-12 17:44:58.299  3696  3696 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
,07-12 17:44:58.299  3696  3696 W System.err: 	at android.app.ApplicationPackageManager.getApplicationInfo(ApplicationPackageManager.java:287)
,07-12 17:44:58.309  3696  3696 W System.err: 	at com.huawei.android.launcher.ShortcutInfo.isAppUninstallable(ShortcutInfo.java:347)
07-12 17:44:58.309  3696  3696 W System.err: 	at com.huawei.android.launcher.Workspace$10.run(Workspace.java:6784)
,07-12 17:44:58.309  3696  3696 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
07-12 17:44:58.309  3696  3696 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
07-12 17:44:58.309  3696  3696 W System.err: 	at android.os.Looper.loop(Looper.java:135)
,07-12 17:44:58.309  3696  3696 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5538)
07-12 17:44:58.309  3696  3696 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
07-12 17:44:58.309  3696  3696 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
,07-12 17:44:58.319  3696  3696 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:960)
07-12 17:44:58.319  3696  3696 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:755)
,07-12 17:44:58.319  3696  3696 W System.err: java.lang.NullPointerException: null receiver
07-12 17:44:58.319  3696  3696 W System.err: 	at java.lang.reflect.Field.get(Native Method)
07-12 17:44:58.319  3696  3696 W System.err: 	at java.lang.reflect.Field.get(Field.java:279)
07-12 17:44:58.319  3696  3696 W System.err: 	at com.huawei.android.launcher.ShortcutInfo.isAppUninstallable(ShortcutInfo.java:372)
07-12 17:44:58.319  3696  3696 W System.err: 	at com.huawei.android.launcher.Workspace$10.run(Workspace.java:6784)
07-12 17:44:58.319  3696  3696 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
07-12 17:44:58.319  3696  3696 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
07-12 17:44:58.319  3696  3696 W System.err: 	at android.os.Looper.loop(Looper.java:135)
07-12 17:44:58.319  3696  3696 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5538)
07-12 17:44:58.319  3696  3696 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
07-12 17:44:58.319  3696  3696 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
07-12 17:44:58.319  3696  3696 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:960)
07-12 17:44:58.319  3696  3696 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:755)
07-12 17:44:58.319  3696  3696 I HwLauncher: CellLayout rearrangeAfterRmItem isAutoAlign = false
07-12 17:44:58.319  3696  3696 I HwLauncher: Launcher Deferring update until onResume
,07-12 17:44:58.329  3955  4135 I HwSystemManager: aor:Network Stats Updated
07-12 17:44:58.329  3955  4135 I HwSystemManager: aoi:onNetworkStatsUpdated
07-12 17:44:58.329  3955  4156 I HwSystemManager: TrafficAnalyseManager:mDataServiceStatusCard1 : false mDataServiceStatusCard2 : false
,07-12 17:44:58.339  3955  4156 E HwSystemManager: getSimCardType:/getSimCardInfo: imsi is null
,07-12 17:44:58.339  3955  4156 E HwSystemManager: getSimCardType:/getSimCardInfo: imsi is null
07-12 17:44:58.339  3955  4156 E HwSystemManager: getSimCardType:/getPhoneSimCardInfo: boths card not recongnized
07-12 17:44:58.339  3955  4156 W HwSystemManager: TrafficAnalyseManager:initCardStatus: preferredCardInfo is null.
,07-12 17:44:58.339  3955  4156 E HwSystemManager: TrafficNotifyOverMarkForDay:notifyTafficOverMarkForDay: imsi is null.
07-12 17:44:58.339  3955  4156 I HwSystemManager: TrafficAnalyseManager:mDataServiceStatusCard1 : false mDataServiceStatusCard2 : false
,07-12 17:44:58.339  3696  3696 I HwLauncher: Launcher  onWindowVisibilityChanged visibility = 4
07-12 17:44:58.339  3696  3696 I HwLauncher: DynamicIcon onWindowVisibilityChanged 4 - com.android.calendar
07-12 17:44:58.339  3696  3696 I HwLauncher: DynamicIcon onWindowVisibilityChanged 4 - com.android.deskclock
,07-12 17:44:58.349  3955  4156 E HwSystemManager: getSimCardType:/getSimCardInfo: imsi is null
,07-12 17:44:58.349  3696  3696 I HwLauncher: Launcher onStart()
07-12 17:44:58.349  3696  3696 I HwLauncher: Launcher dynamicIconsRegister
07-12 17:44:58.349  3696  3696 I HwLauncher: DynamicUpdater registerReceiver
,07-12 17:44:58.349  3955  4156 E HwSystemManager: getSimCardType:/getSimCardInfo: imsi is null
07-12 17:44:58.349  3955  4156 E HwSystemManager: getSimCardType:/getPhoneSimCardInfo: boths card not recongnized
07-12 17:44:58.349  3955  4156 W HwSystemManager: TrafficAnalyseManager:initCardStatus: preferredCardInfo is null.
07-12 17:44:58.349  3029  3053 W ResourceType: ResTable_typeSpec entry count inconsistent: given 1, previously 1445
,07-12 17:44:58.349  3955  4156 E HwSystemManager: TrafficNotifyOverMarkForMonth:notifyTafficOverMarkForMonth: imsi is null.
07-12 17:44:58.349  3955  4156 I HwSystemManager: TrafficAnalyseManager:mDataServiceStatusCard1 : false mDataServiceStatusCard2 : false
,07-12 17:44:58.359  3955  4156 E HwSystemManager: getSimCardType:/getSimCardInfo: imsi is null
,07-12 17:44:58.359  3955  4156 E HwSystemManager: getSimCardType:/getSimCardInfo: imsi is null
07-12 17:44:58.359  3955  4156 E HwSystemManager: getSimCardType:/getPhoneSimCardInfo: boths card not recongnized
07-12 17:44:58.359  3955  4156 W HwSystemManager: TrafficAnalyseManager:initCardStatus: preferredCardInfo is null.
,07-12 17:44:58.359  3955  4156 E HwSystemManager: TrafficNotifyExcessForMonth:notifyTafficExcessForMonth: imsi is null.
,07-12 17:44:58.429  3029  3029 I art     : Explicit concurrent mark sweep GC freed 64535(4MB) AllocSpace objects, 4(76KB) LOS objects, 33% free, 28MB/42MB, paused 3.093ms total 281.008ms
07-12 17:44:58.429  3029  3067 I art     : WaitForGcToComplete blocked for 209.206ms for cause Explicit
,07-12 17:44:58.529  3029  3222 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
07-12 17:44:58.529  3029  3222 W System.err: 	at android.app.ApplicationPackageManager.getApplicationInfo(ApplicationPackageManager.java:287)
07-12 17:44:58.529  3029  3222 W System.err: 	at com.android.server.SmartHeartBeat$HeartBeatHandler.updatePackageMessage(SmartHeartBeat.java:872)
07-12 17:44:58.529  3029  3222 W System.err: 	at com.android.server.SmartHeartBeat$HeartBeatHandler.handleMessage(SmartHeartBeat.java:606)
07-12 17:44:58.529  3029  3222 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-12 17:44:58.529  3029  3222 W System.err: 	at android.os.Looper.loop(Looper.java:135)
07-12 17:44:58.529  3029  3222 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,07-12 17:44:58.579  3029  3029 I art     : Can not find class: Lhuawei/com/android/server/util/UserBehaviourRecord;
,07-12 17:44:58.579  3029  3029 I art     : Can not find class: Lhuawei/com/android/server/util/UserBehaviourRecord$1;
,07-12 17:44:58.589  3029  3029 I art     : Can not find class: Lhuawei/com/android/server/util/ReportTool;
,07-12 17:44:58.589  3029  3029 I art     : Can not find class: Lcom/huawei/report/ReporterInterface;
,07-12 17:44:58.589  3029  3029 E ReportTools: Can't find sReporterClazz
,07-12 17:44:58.589  3029  3029 I art     : Can not find class: Lhuawei/com/android/server/util/UserBehaviourRecord$UploadThread;
,07-12 17:44:58.589  3029  3029 I art     : Can not find class: Lhuawei/com/android/server/util/AppInfo;
,07-12 17:44:58.589  3029  3029 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'int com.huawei.lcagent.client.LogCollectManager.getUserType()' on a null object reference
,07-12 17:44:58.589  3029  3029 W System.err: 	at huawei.com.android.server.util.ReportTool.getUserType(ReportTool.java:86)
07-12 17:44:58.589  3029  3029 W System.err: 	at huawei.com.android.server.util.ReportTool.isBetaUser(ReportTool.java:73)
07-12 17:44:58.589  3029  3029 W System.err: 	at huawei.com.android.server.util.ReportTool.report(ReportTool.java:58)
07-12 17:44:58.589  3029  3029 W System.err: 	at huawei.com.android.server.util.UserBehaviourRecord.appExitRecord(UserBehaviourRecord.java:65)
07-12 17:44:58.589  3029  3029 W System.err: 	at com.android.server.am.ActivityManagerService.cleanUpRemovedTaskLocked(ActivityManagerService.java:9041)
07-12 17:44:58.589  3029  3029 W System.err: 	at com.android.server.am.ActivityManagerService.removeTaskByIdLocked(ActivityManagerService.java:9097)
07-12 17:44:58.589  3029  3029 W System.err: 	at com.android.server.am.ActivityManagerService.access$1000(ActivityManagerService.java:293)
07-12 17:44:58.589  3029  3029 W System.err: 	at com.android.server.am.ActivityManagerService$3.onPackageRemoved(ActivityManagerService.java:2234)
07-12 17:44:58.589  3029  3029 W System.err: 	at com.android.internal.content.PackageMonitor.onReceive(PackageMonitor.java:341)
07-12 17:44:58.589  3029  3029 W System.err: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:899)
07-12 17:44:58.589  3029  3029 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
07-12 17:44:58.589  3029  3029 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
07-12 17:44:58.589  3029  3029 W System.err: 	at android.os.Looper.loop(Looper.java:135)
07-12 17:44:58.589  3029  3029 W System.err: 	at com.android.server.SystemServer.run(SystemServer.java:324)
07-12 17:44:58.589  3029  3029 W System.err: 	at com.android.server.SystemServer.main(SystemServer.java:212)
07-12 17:44:58.589  3029  3029 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
07-12 17:44:58.589  3029  3029 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
07-12 17:44:58.589  3029  3029 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:960)
07-12 17:44:58.589  3029  3029 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:755)
07-12 17:44:58.589  3029  3029 E ReportTools: This is not beta user build
,07-12 17:44:58.619  3029  3067 I art     : Explicit concurrent mark sweep GC freed 8199(476KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 28MB/42MB, paused 2.169ms total 189.192ms
,07-12 17:44:58.619  3029  3050 I art     : WaitForGcToComplete blocked for 266.423ms for cause Explicit
,07-12 17:44:58.799  3029  3050 I art     : Explicit concurrent mark sweep GC freed 4425(307KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 27MB/41MB, paused 1.991ms total 182.590ms
,07-12 17:44:58.799  3696  3696 I HwLauncher: DynamicUpdater call updateFolder
07-12 17:44:58.799  3696  3696 I HwLauncher: DynamicIcon onResume  isvisible = false   mAttachedToWindow:true    mWindowVisible:falsecom.android.calendar
07-12 17:44:58.799  3696  3696 I HwLauncher: DynamicUpdater registerReceiver
,07-12 17:44:58.799  3696  3696 I HwLauncher: DynamicUpdater call updateFolder
07-12 17:44:58.799  3696  3696 I HwLauncher: DynamicIcon onResume  isvisible = false   mAttachedToWindow:true    mWindowVisible:falsecom.android.deskclock
07-12 17:44:58.799  3696  3696 I HwLauncher: DynamicUpdater registerReceiver
07-12 17:44:58.799  3696  3853 I HwLauncher: DynamicIconData , getDrawableForDynamic begin, pkg = com.android.deskclock, picName = deskclock_bg
07-12 17:44:58.809  3696  3696 I HwLauncher: DynamicUpdater call updateFolder
07-12 17:44:58.809  3696  3696 I HwLauncher: DynamicIcon onResume  isvisible = true   mAttachedToWindow:false    mWindowVisible:falsecom.huawei.android.totemweather
07-12 17:44:58.809  3696  3696 I HwLauncher: DynamicIcon onVisibilityChanged 0 - com.android.calendar
07-12 17:44:58.809  3696  3696 I HwLauncher: DynamicIcon onVisibilityChanged 0 - com.android.deskclock
07-12 17:44:58.809  3696  3696 E HideAppsPagedView: removeHideApps  begin 
07-12 17:44:58.809  3696  3696 E HideAppsPagedView: removeHideApps  end 
07-12 17:44:58.809  3696  3696 E HideAppsPagedView:  syncPages mCurrentPage = 0
07-12 17:44:58.809  3696  3853 I HwLauncher: DynamicIconData , getDrawableForDynamic end, pkg = com.android.deskclock, picName = deskclock_bg
07-12 17:44:58.809  3696  3853 I HwLauncher: DynamicIconData , getDrawableForDynamic begin, pkg = com.android.deskclock, picName = deskclock_bg
07-12 17:44:58.809  3696  3853 I HwLauncher: DynamicIconData , getDrawableForDynamic end, pkg = com.android.deskclock, picName = deskclock_bg
07-12 17:44:58.809  3696  3696 E ZipFileCache: init failed when open zip file.
07-12 17:44:58.809  3696  3696 E ZipFileCache: init failed when open zip file.
07-12 17:44:58.809  3696  3696 E ZipFileCache: init failed when open zip file.
07-12 17:44:58.809  3696  3853 I HwLauncher: Launcher.Utilities createIconBitmap classname = null, sourceWidth = 114, sourceHeight = 114
07-12 17:44:58.809  3696  3696 E ZipFileCache: init failed when open zip file.
07-12 17:44:58.809  3696  3696 E ZipFileCache: init failed when open zip file.
07-12 17:44:58.809  3696  3853 I HwLauncher: ClockDynamicUpdater clock update folder at ClockDynamicUpdater
07-12 17:44:58.809  3696  3853 I HwLauncher: DynamicUpdater updateBitmap end and send update message
07-12 17:44:58.809  3696  3853 I HwLauncher: WeatherDynamicUpdaterpositiveUpdate at WeatherDynamicUpdater
07-12 17:44:58.819  3029  3053 W asset   : Asset path /system/framework/com.huawei.theme.stat.jar is neither a directory nor file (type=1).
07-12 17:44:58.819  3696  3696 E HideAppsPagedView:  syncAppsPageItems page = 0 mNumAppsPages = 1 mCurrentPage = 0
07-12 17:44:58.819  3696  3696 E HideAppsPagedView:  createAddIcon count = 0
07-12 17:44:58.819  3696  3696 I HwLauncher:  FPSMonitor snapToPage whichPage = 0 delta = 0 duration = 550
07-12 17:44:58.819  3696  3696 I HwLauncher: Launcher  onWindowVisibilityChanged visibility = 0
07-12 17:44:58.819  3696  3696 I HwLauncher: DynamicIcon onWindowVisibilityChanged 0 - com.android.calendar
07-12 17:44:58.819  3696  3696 I HwLauncher: DynamicIcon onWindowVisibilityChanged 0 - com.android.deskclock
07-12 17:44:58.829  3357  3357 I PhoneStatusBar: hw_status_bar_operators = true, setSystemUIVisibily(SHOW_OPERATOR = false)
07-12 17:44:58.829  3357  3357 I PhoneStatusBar: shouldTranslucent:true
07-12 17:44:58.829  3357  3357 I PhoneStatusBar: hw_status_bar_operators = true, setSystemUIVisibily(SHOW_OPERATOR = false)
07-12 17:44:58.839  7457  7457 E Minikin : addFont failed to create font /system/fonts/DroidSansChineseslim.ttf
07-12 17:44:58.839  7457  7457 W GalleryUtils: the font DroidSanChineseSlim is not exist!
07-12 17:44:58.839  3696  3696 I HwLauncher: DynamicUpdater call updateFolder
,07-12 17:44:58.919  7481  7481 W asset   : Asset path /system/framework/com.huawei.theme.stat.jar is neither a directory nor file (type=1).
,07-12 17:44:58.999  7481  7481 I HwCust  : Constructor found for class com.huawei.android.totemweather.HwCustWeatherAppHwBaseImpl
07-12 17:44:58.999  7481  7505 I HwCust  : Constructor found for class com.huawei.android.totemweather.utils.HwCustUseBitmapConfigImpl
,07-12 17:44:59.019  3696  3696 I HwLauncher: WeatherDynamicUpdaterreceive action = com.huawei.android.action.launcher_weather_icon_change
,07-12 17:44:59.019  3696  3853 I HwLauncher: WeatherDynamicUpdaterreceiver data is int[] = [0, 0]
07-12 17:44:59.019  3696  3853 I HwLauncher:  stringArray[] [unknown]
,07-12 17:44:59.019  3955  3955 I HwSystemManager: NotificationManagerReceiver:onReceive action = android.intent.action.PACKAGE_REMOVED
07-12 17:44:59.019  3955  3955 I HwSystemManager: NotificationManagerReceiver:onReceive, send action to background
,07-12 17:44:59.039  7508  7531 E SQLiteDatabase: Failed to open database '/data/data/com.android.keychain/databases/grants.db'.
07-12 17:44:59.039  7508  7531 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error(Sqlite code 0): Could not open the database in read/write mode.,(OS error - 30:Read-only file system)
07-12 17:44:59.039  7508  7531 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
07-12 17:44:59.039  7508  7531 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
07-12 17:44:59.039  7508  7531 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
07-12 17:44:59.039  7508  7531 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
07-12 17:44:59.039  7508  7531 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
07-12 17:44:59.039  7508  7531 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
07-12 17:44:59.039  7508  7531 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:819)
07-12 17:44:59.039  7508  7531 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:804)
07-12 17:44:59.039  7508  7531 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:707)
07-12 17:44:59.039  7508  7531 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1195)
07-12 17:44:59.039  7508  7531 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
07-12 17:44:59.039  7508  7531 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
07-12 17:44:59.039  7508  7531 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
07-12 17:44:59.039  7508  7531 E SQLiteDatabase: 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:402)
07-12 17:44:59.039  7508  7531 E SQLiteDatabase: 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:396)
07-12 17:44:59.039  7508  7531 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
07-12 17:44:59.039  7508  7531 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-12 17:44:59.039  7508  7531 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:135)
07-12 17:44:59.039  7508  7531 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,07-12 17:44:59.039  7508  7531 E AndroidRuntime: FATAL EXCEPTION: IntentService[KeyChainService]
07-12 17:44:59.039  7508  7531 E AndroidRuntime: Process: com.android.keychain, PID: 7508
07-12 17:44:59.039  7508  7531 E AndroidRuntime: android.database.sqlite.SQLiteException: not an error(Sqlite code 0): Could not open the database in read/write mode.,(OS error - 30:Read-only file system)
07-12 17:44:59.039  7508  7531 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
07-12 17:44:59.039  7508  7531 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
07-12 17:44:59.039  7508  7531 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
07-12 17:44:59.039  7508  7531 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
07-12 17:44:59.039  7508  7531 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
07-12 17:44:59.039  7508  7531 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
07-12 17:44:59.039  7508  7531 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:819)
07-12 17:44:59.039  7508  7531 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:804)
07-12 17:44:59.039  7508  7531 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:707)
07-12 17:44:59.039  7508  7531 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1195)
07-12 17:44:59.039  7508  7531 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
07-12 17:44:59.039  7508  7531 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
07-12 17:44:59.039  7508  7531 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
07-12 17:44:59.039  7508  7531 E AndroidRuntime: 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:402)
07-12 17:44:59.039  7508  7531 E AndroidRuntime: 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:396)
07-12 17:44:59.039  7508  7531 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
07-12 17:44:59.039  7508  7531 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-12 17:44:59.039  7508  7531 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:135)
07-12 17:44:59.039  7508  7531 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,07-12 17:44:59.129  3955  3955 I HwSystemManager: HsmIntentService:created. this:com.huawei.systemmanager.util.content.HsmIntentService_bg@ceb05a2
07-12 17:44:59.129  3955  3955 I HwSystemManager: HsmIntentService:started for intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.huawei.systemmanager/com.huawei.notificationmanager.receiver.Receiver (has extras) }, action:android.intent.action.PACKAGE_REMOVED, class:com.huawei.notificationmanager.receiver.Receiver
07-12 17:44:59.129  3955  7532 I HwSystemManager: HsmIntentService:invoked com.huawei.notificationmanager.receiver.Receiver
,07-12 17:44:59.139  6955  6955 I HwSystemManager: AppInstallationReceiver:AppInstallationReceiver onReceive action = android.intent.action.PACKAGE_REMOVED
07-12 17:44:59.139  3955  6817 I HwSystemManager: BgPowerManagerService:onProcessDied uid = 10058
07-12 17:44:59.139  3955  3979 I HwSystemManager: HoldService:uid:10058 pid:6392 died
07-12 17:44:59.139  3955  3979 I HwSystemManager: HoldService:oldVersionKey:10058,6392
,07-12 17:44:59.139  3029  3725 E HsmCoreServiceImpl: onTransact in code is: 102
07-12 17:44:59.139  3029  3725 I MediaProcessHandler: processOp opType: 1, uid: 10058, pid: 6392
07-12 17:44:59.139  3029  3725 W MediaProcessHandler: remove target not exist, maybe the UI process: uid: 10058, pid: 6392
,07-12 17:44:59.149  6955  6955 I HwSystemManager: HsmIntentService:created. this:com.huawei.systemmanager.util.content.HsmIntentService_ui@52e303a
,07-12 17:44:59.149  6955  6955 I HwSystemManager: HsmIntentService:started for intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.huawei.systemmanager/com.huawei.permissionmanager.ui.AppInstallationReceiver (has extras) }, action:android.intent.action.PACKAGE_REMOVED, class:com.huawei.permissionmanager.ui.AppInstallationReceiver
,07-12 17:44:59.149  6955  7533 I HwSystemManager: HsmIntentService:invoked com.huawei.permissionmanager.ui.AppInstallationReceiver
,07-12 17:44:59.149  3029  3049 I art     : Can not find class: Lcom/android/server/am/ActivityManagerService$21;
,07-12 17:44:59.149  3029  3049 I art     : Can not find class: Lcom/android/server/am/AppErrorResult;
07-12 17:44:59.149  6955  6955 I HwSystemManager: HsmIntentService:started for intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.huawei.systemmanager/.optimize.OptimizeReceiver (has extras) }, action:android.intent.action.PACKAGE_REMOVED, class:com.huawei.systemmanager.optimize.OptimizeReceiver
,07-12 17:44:59.149  6955  7535 I HwSystemManager: HsmIntentService:invoked com.huawei.systemmanager.optimize.OptimizeReceiver
,07-12 17:44:59.149  6955  7535 I HwSystemManager: OptimizeReceiver:OptimizeReceiver received action:android.intent.action.PACKAGE_REMOVED
07-12 17:44:59.149  6955  7535 I HwSystemManager: OverseaCfgHelper:permissionStatus is 0
,07-12 17:44:59.149  6955  7535 I HwSystemManager: HsmIntentService:task completed for intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.huawei.systemmanager/.optimize.OptimizeReceiver (has extras) }, action:android.intent.action.PACKAGE_REMOVED
07-12 17:44:59.149  6955  6955 I HwSystemManager: ComBroadcastReceiver:ComBroadcastReceiver action = android.intent.action.PACKAGE_REMOVED
07-12 17:44:59.149  6955  7535 I HwSystemManager: HsmIntentService:in thread:Thread[HsmIntentServiceTask #5,5,main], current active tasksize:2, queue size:0
07-12 17:44:59.149  6955  7224 I HwSystemManager: ProtectAppControl:handleMessage:7
,07-12 17:44:59.149  3955  4036 I HwSystemManager: OptimizeProvider:delete com.test.thalitest
,07-12 17:44:59.159  3955  3955 I HwSystemManager: AppCleanUpService:onStartCommand() in!
07-12 17:44:59.159  3955  3955 I HwSystemManager: AppCleanUpService:onStartCommand() out!
07-12 17:44:59.159  3955  3955 E HwSystemManager: AppCleanUpService:msg is 1
,07-12 17:44:59.159  6955  6955 I HwSystemManager: HsmIntentService:started for intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.huawei.systemmanager/.power.receiver.BootBroadcastReceiver (has extras) }, action:android.intent.action.PACKAGE_REMOVED, class:com.huawei.systemmanager.power.receiver.BootBroadcastReceiver
,07-12 17:44:59.159  6955  6955 I HwSystemManager: NetAppListPrepareReceiver:NetAppListPrepareReceiver:  onReceive(), action = android.intent.action.PACKAGE_REMOVED
07-12 17:44:59.159  6955  6955 I HwSystemManager: NetAppListPrepareReceiver:package removed: package:com.test.thalitest
07-12 17:44:59.159  6955  6955 I HwSystemManager: NetAppListPrepareReceiver:replacing?:false
07-12 17:44:59.159  6955  7536 I HwSystemManager: HsmIntentService:invoked com.huawei.systemmanager.power.receiver.BootBroadcastReceiver
07-12 17:44:59.159  6955  7536 W HwSystemManager: BootBroadcastReceiver:No handler exist for registered action:android.intent.action.PACKAGE_REMOVED
,07-12 17:44:59.159  6955  7536 I HwSystemManager: HsmIntentService:task completed for intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.huawei.systemmanager/.power.receiver.BootBroadcastReceiver (has extras) }, action:android.intent.action.PACKAGE_REMOVED
07-12 17:44:59.159  6955  7536 I HwSystemManager: HsmIntentService:in thread:Thread[HsmIntentServiceTask #6,5,main], current active tasksize:2, queue size:0

```
