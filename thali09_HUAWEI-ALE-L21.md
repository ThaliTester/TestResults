#### Test 75789268514fc25_thali09_HUAWEI-ALE-L21 Logs


```
int logctl_get(): open '/dev/hwlog_switch' fail -1, 13. Permission denied

Note: log switch off, only log_main and log_events will have logs!
,--------- beginning of main
07-15 15:21:45.299  6950  6950 I appproc : CLASSPATH=/system/framework/am.jar
07-15 15:21:45.299  6950  6950 I appproc : Command=app_process /system/bin com.android.commands.am.Am start -n com.test.thalitest/com.test.thalitest.MainActivity 
07-15 15:21:45.299  6950  6950 I appproc : app_process:number,5,0
07-15 15:21:45.309  6950  6950 I AndroidRuntime: readDownloadBoosterConfig: 'false'
07-15 15:21:45.449  6950  6950 I         : power log dlsym ok
07-15 15:21:45.489  6950  6950 E android_hardware_fm.cpp: register_android_hardware_fm_fmradio
07-15 15:21:45.489  6950  6950 I android_hardware_fm.cpp: ========64bit long size = 8
07-15 15:21:45.489  6950  6950 E FM_HAL  : [FM_HAL], libname is libhisifm_if
07-15 15:21:45.499  6950  6950 I fm_hisi : FM::[fm_device_open:4655] fm_device_open
07-15 15:21:45.499  6950  6950 I fm_hisi : 
07-15 15:21:45.499  6950  6950 I fm_hisi : FM::[fm_device_open:4666] find the id:libhisifm_if and begins to open the device
07-15 15:21:45.499  6950  6950 I fm_hisi : 
07-15 15:21:45.499  6950  6950 I fm_hisi : FM::[fm_device_open:4710] device open sucess
07-15 15:21:45.499  6950  6950 I fm_hisi : 
07-15 15:21:45.499  6950  6950 E android_hardware_fm.cpp: register_android_hardware_fm_fmradio, ret is 0
07-15 15:21:45.539  3043  3591 I art     : Can not find class: Lcom/android/server/wm/WindowState$2;
07-15 15:21:45.539  3043  3591 I art     : Can not find class: Lcom/android/server/am/TaskPersister$TaskWriteQueueItem;
07-15 15:21:45.539  3043  3591 I art     : Can not find class: Lcom/android/server/am/TaskPersister$WriteQueueItem;
07-15 15:21:45.609  3043  3163 I art     : Can not find class: Lcom/android/server/am/ActivityStack$2;
07-15 15:21:45.609  3505  3835 W PhoneStateManager: screen off and not process front event:com.test.thalitest
07-15 15:21:45.619  3761  3783 I HwSystemManager: AppLockService:applock password not initial or function is closed
07-15 15:21:45.619  3761  3783 I HwSystemManager: AppLockService:applock password not initial or function is closed
07-15 15:21:45.619  3761  4044 I HwSystemManager: AppManager:getNetAppInfoFromDB cursor lenth = 1
07-15 15:21:45.629  3615  3615 I HwLauncher: Launcher  onWindowVisibilityChanged visibility = 8
07-15 15:21:45.629  3615  3615 I HwLauncher: DynamicIcon onWindowVisibilityChanged 8 - com.android.calendar
07-15 15:21:45.629  3615  3615 I HwLauncher: DynamicIcon onWindowVisibilityChanged 8 - com.android.deskclock
07-15 15:21:45.639  3615  3615 I HwLauncher: DynamicIcon onVisibilityChanged 4 - com.android.calendar
07-15 15:21:45.639  3615  3615 I HwLauncher: DynamicIcon onVisibilityChanged 4 - com.android.deskclock
07-15 15:21:45.769  6970  6970 I WebViewFactory: Loading com.android.webview version 37 (eng.jenkins-arm64) (code 199992)
07-15 15:21:45.779  6970  6970 I LibraryLoader: Loading: webviewchromium
07-15 15:21:45.789  6970  6970 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 1397-1400)
07-15 15:21:45.789  6970  6970 I LibraryLoader: Expected native library version number "",actual native library version number ""
,07-15 15:21:45.809  6970  6970 E ZipFileCache: init failed when open zip file.
07-15 15:21:45.809  6970  6970 E ZipFileCache: init failed when open zip file.
07-15 15:21:45.809  6970  6970 E ZipFileCache: init failed when open zip file.
07-15 15:21:45.809  6970  6970 E ZipFileCache: init failed when open zip file.
07-15 15:21:45.819  6970  6970 I LibraryLoader: Expected native library version number "",actual native library version number ""
07-15 15:21:45.819  6970  6970 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
07-15 15:21:45.829  6970  6970 I BrowserStartupController: Initializing chromium process, renderers=0
07-15 15:21:45.829  6970  6970 W art     : Attempt to remove local handle scope entry from IRT, ignoring
07-15 15:21:45.839  6970  6999 W chromium: [WARNING:dns_config_service_posix.cc(293)] Failed to read DnsConfig.
07-15 15:21:45.839  6970  6970 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
07-15 15:21:45.849  6970  6970 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=37 off=46092 len=2953
07-15 15:21:45.849  6970  6970 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:38 off:228796 len:643667
07-15 15:21:45.919  6970  7009 W chromium: [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
07-15 15:21:45.929  6970  7009 W chromium: [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
07-15 15:21:45.929  6970  6970 W chromium: [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
07-15 15:21:45.979  6970  6970 E ZipFileCache: init failed when open zip file.
07-15 15:21:45.979  6970  6970 E ZipFileCache: init failed when open zip file.
07-15 15:21:45.989  6970  6970 E ZipFileCache: init failed when open zip file.
07-15 15:21:45.989  6970  6970 E ZipFileCache: init failed when open zip file.
07-15 15:21:45.989  6970  6970 E ZipFileCache: init failed when open zip file.
07-15 15:21:45.999  6970  6970 E ZipFileCache: init failed when open zip file.
07-15 15:21:45.999  6970  6970 E ZipFileCache: init failed when open zip file.
07-15 15:21:45.999  6970  6970 E ZipFileCache: init failed when open zip file.
07-15 15:21:45.999  6970  6970 E ZipFileCache: init failed when open zip file.
07-15 15:21:45.999  6970  6970 E ZipFileCache: init failed when open zip file.
07-15 15:21:46.009  6970  6970 E ZipFileCache: init failed when open zip file.
07-15 15:21:46.009  6970  6970 E ZipFileCache: init failed when open zip file.
07-15 15:21:46.019  6970  6970 E ZipFileCache: init failed when open zip file.
07-15 15:21:46.019  6970  6970 E ZipFileCache: init failed when open zip file.
07-15 15:21:46.019  6970  6970 E ZipFileCache: init failed when open zip file.
07-15 15:21:46.019  6970  6970 E ZipFileCache: init failed when open zip file.
07-15 15:21:46.029  6970  6970 E ZipFileCache: init failed when open zip file.
07-15 15:21:46.029  6970  6970 E ZipFileCache: init failed when open zip file.
07-15 15:21:46.029  6970  6970 E ZipFileCache: init failed when open zip file.
07-15 15:21:46.029  6970  6970 E ZipFileCache: init failed when open zip file.
07-15 15:21:46.029  6970  6970 E ZipFileCache: init failed when open zip file.
07-15 15:21:46.029  6970  6970 E ZipFileCache: init failed when open zip file.
07-15 15:21:46.039  6970  6970 E ZipFileCache: init failed when open zip file.
07-15 15:21:46.039  6970  6970 E ZipFileCache: init failed when open zip file.
07-15 15:21:46.039  6970  6970 E ZipFileCache: init failed when open zip file.
07-15 15:21:46.039  6970  6970 E ZipFileCache: init failed when open zip file.
07-15 15:21:46.039  6970  6970 E ZipFileCache: init failed when open zip file.
07-15 15:21:46.039  6970  6970 E ZipFileCache: init failed when open zip file.
07-15 15:21:46.049  6970  6970 E ZipFileCache: init failed when open zip file.
07-15 15:21:46.049  6970  6970 E ZipFileCache: init failed when open zip file.
07-15 15:21:46.049  6970  6970 E ZipFileCache: init failed when open zip file.
07-15 15:21:46.049  6970  6970 E ZipFileCache: init failed when open zip file.
07-15 15:21:46.059  6970  6970 E ZipFileCache: init failed when open zip file.
07-15 15:21:46.059  6970  6970 E ZipFileCache: init failed when open zip file.
07-15 15:21:46.059  6970  6970 E ZipFileCache: init failed when open zip file.
07-15 15:21:46.059  6970  6970 E ZipFileCache: init failed when open zip file.
07-15 15:21:46.059  6970  6970 E ZipFileCache: init failed when open zip file.
07-15 15:21:46.059  6970  6970 E ZipFileCache: init failed when open zip file.
07-15 15:21:46.069  6970  6970 E ZipFileCache: init failed when open zip file.
07-15 15:21:46.069  6970  6970 E ZipFileCache: init failed when open zip file.
07-15 15:21:46.069  6970  6970 E ZipFileCache: init failed when open zip file.
07-15 15:21:46.069  6970  6970 E ZipFileCache: init failed when open zip file.
07-15 15:21:46.069  6970  6970 E ZipFileCache: init failed when open zip file.
07-15 15:21:46.069  6970  6970 E ZipFileCache: init failed when open zip file.
07-15 15:21:46.079  6970  6970 E ZipFileCache: init failed when open zip file.
07-15 15:21:46.079  6970  6970 E ZipFileCache: init failed when open zip file.
07-15 15:21:46.079  6970  6970 E ZipFileCache: init failed when open zip file.
07-15 15:21:46.079  6970  6970 E ZipFileCache: init failed when open zip file.
07-15 15:21:46.079  6970  6970 E ZipFileCache: init failed when open zip file.
07-15 15:21:46.079  6970  6970 E ZipFileCache: init failed when open zip file.
07-15 15:21:46.079  6970  6970 E ZipFileCache: init failed when open zip file.
07-15 15:21:46.079  6970  6970 E ZipFileCache: init failed when open zip file.
07-15 15:21:46.079  6970  6970 E ZipFileCache: init failed when open zip file.
07-15 15:21:46.079  6970  6970 E ZipFileCache: init failed when open zip file.
07-15 15:21:46.079  6970  6970 E ZipFileCache: init failed when open zip file.
07-15 15:21:46.079  6970  6970 E ZipFileCache: init failed when open zip file.
07-15 15:21:46.079  6970  6970 E ZipFileCache: init failed when open zip file.
07-15 15:21:46.079  6970  6970 E ZipFileCache: init failed when open zip file.
07-15 15:21:46.089  6970  6970 E ZipFileCache: init failed when open zip file.
07-15 15:21:46.089  6970  6970 E ZipFileCache: init failed when open zip file.
07-15 15:21:46.089  6970  6970 E ZipFileCache: init failed when open zip file.
07-15 15:21:46.089  6970  6970 E ZipFileCache: init failed when open zip file.
07-15 15:21:46.089  6970  6970 E ZipFileCache: init failed when open zip file.
07-15 15:21:46.089  6970  6970 E ZipFileCache: init failed when open zip file.
07-15 15:21:46.089  6970  6970 E ZipFileCache: init failed when open zip file.
07-15 15:21:46.089  6970  6970 E ZipFileCache: init failed when open zip file.
07-15 15:21:46.089  6970  6970 E ZipFileCache: init failed when open zip file.
07-15 15:21:46.089  6970  6970 E ZipFileCache: init failed when open zip file.
07-15 15:21:46.089  6970  6970 E ZipFileCache: init failed when open zip file.
07-15 15:21:46.089  6970  6970 E ZipFileCache: init failed when open zip file.
07-15 15:21:46.089  6970  6970 E ZipFileCache: init failed when open zip file.
07-15 15:21:46.089  6970  6970 E ZipFileCache: init failed when open zip file.
07-15 15:21:46.089  6970  6970 E ZipFileCache: init failed when open zip file.
07-15 15:21:46.089  6970  6970 E ZipFileCache: init failed when open zip file.
07-15 15:21:46.089  6970  6970 E ZipFileCache: init failed when open zip file.
07-15 15:21:46.089  6970  6970 E ZipFileCache: init failed when open zip file.
07-15 15:21:46.089  6970  6970 E ZipFileCache: init failed when open zip file.
07-15 15:21:46.089  6970  6970 E ZipFileCache: init failed when open zip file.
07-15 15:21:46.089  6970  6970 E ZipFileCache: init failed when open zip file.
07-15 15:21:46.089  6970  6970 E ZipFileCache: init failed when open zip file.
07-15 15:21:46.099  6970  6970 E ZipFileCache: init failed when open zip file.
07-15 15:21:46.099  6970  6970 E ZipFileCache: init failed when open zip file.
07-15 15:21:46.099  6970  6970 E ZipFileCache: init failed when open zip file.
07-15 15:21:46.099  6970  6970 E ZipFileCache: init failed when open zip file.
07-15 15:21:46.099  6970  6970 E ZipFileCache: init failed when open zip file.
07-15 15:21:46.099  6970  6970 E ZipFileCache: init failed when open zip file.
07-15 15:21:46.099  6970  6970 E ZipFileCache: init failed when open zip file.
07-15 15:21:46.099  6970  6970 E ZipFileCache: init failed when open zip file.
07-15 15:21:46.109  6970  6970 E ZipFileCache: init failed when open zip file.
07-15 15:21:46.109  6970  6970 E ZipFileCache: init failed when open zip file.
07-15 15:21:46.109  6970  6970 E ZipFileCache: init failed when open zip file.
07-15 15:21:46.109  6970  6970 E ZipFileCache: init failed when open zip file.
07-15 15:21:46.119  6970  6970 E ZipFileCache: init failed when open zip file.
07-15 15:21:46.119  6970  6970 E ZipFileCache: init failed when open zip file.
07-15 15:21:46.119  6970  6970 E ZipFileCache: init failed when open zip file.
07-15 15:21:46.119  6970  6970 E ZipFileCache: init failed when open zip file.
07-15 15:21:46.119  6970  6970 E ZipFileCache: init failed when open zip file.
07-15 15:21:46.119  6970  6970 E ZipFileCache: init failed when open zip file.
07-15 15:21:46.129  6970  6970 E ZipFileCache: init failed when open zip file.
07-15 15:21:46.129  6970  6970 E ZipFileCache: init failed when open zip file.
07-15 15:21:46.129  6970  6970 E ZipFileCache: init failed when open zip file.
07-15 15:21:46.129  6970  6970 E ZipFileCache: init failed when open zip file.
07-15 15:21:46.139  6970  6970 E ZipFileCache: init failed when open zip file.
07-15 15:21:46.139  6970  6970 E ZipFileCache: init failed when open zip file.
07-15 15:21:46.139  6970  6970 E ZipFileCache: init failed when open zip file.
07-15 15:21:46.139  6970  6970 E ZipFileCache: init failed when open zip file.
07-15 15:21:46.139  6970  6970 E ZipFileCache: init failed when open zip file.
07-15 15:21:46.139  6970  6970 E ZipFileCache: init failed when open zip file.
07-15 15:21:46.149  6970  6970 E ZipFileCache: init failed when open zip file.
07-15 15:21:46.149  6970  6970 E ZipFileCache: init failed when open zip file.
07-15 15:21:46.149  6970  6970 E ZipFileCache: init failed when open zip file.
07-15 15:21:46.149  6970  6970 E ZipFileCache: init failed when open zip file.
07-15 15:21:46.159  6970  6970 E ZipFileCache: init failed when open zip file.
07-15 15:21:46.159  6970  6970 E ZipFileCache: init failed when open zip file.
07-15 15:21:46.159  6970  6970 E ZipFileCache: init failed when open zip file.
07-15 15:21:46.159  6970  6970 E ZipFileCache: init failed when open zip file.
07-15 15:21:46.159  6970  6970 E ZipFileCache: init failed when open zip file.
07-15 15:21:46.159  6970  6970 E ZipFileCache: init failed when open zip file.
07-15 15:21:46.169  6970  6970 E ZipFileCache: init failed when open zip file.
07-15 15:21:46.169  6970  6970 E ZipFileCache: init failed when open zip file.
07-15 15:21:46.169  6970  6970 E ZipFileCache: init failed when open zip file.
07-15 15:21:46.169  6970  6970 E ZipFileCache: init failed when open zip file.
07-15 15:21:46.169  6970  6970 E ZipFileCache: init failed when open zip file.
07-15 15:21:46.169  6970  6970 E ZipFileCache: init failed when open zip file.
07-15 15:21:46.169  6970  6970 E ZipFileCache: init failed when open zip file.
07-15 15:21:46.169  6970  6970 E ZipFileCache: init failed when open zip file.
07-15 15:21:46.179  6970  6970 E ZipFileCache: init failed when open zip file.
07-15 15:21:46.179  6970  6970 E ZipFileCache: init failed when open zip file.
07-15 15:21:46.179  6970  6970 E ZipFileCache: init failed when open zip file.
07-15 15:21:46.179  6970  6970 E ZipFileCache: init failed when open zip file.
07-15 15:21:46.179  6970  6970 E ZipFileCache: init failed when open zip file.
07-15 15:21:46.179  6970  6970 E ZipFileCache: init failed when open zip file.
07-15 15:21:46.179  6970  6970 E ZipFileCache: init failed when open zip file.
07-15 15:21:46.179  6970  6970 E ZipFileCache: init failed when open zip file.
07-15 15:21:46.179  6970  6970 E ZipFileCache: init failed when open zip file.
07-15 15:21:46.179  6970  6970 E ZipFileCache: init failed when open zip file.
07-15 15:21:46.179  6970  6970 E ZipFileCache: init failed when open zip file.
07-15 15:21:46.179  6970  6970 E ZipFileCache: init failed when open zip file.
07-15 15:21:46.179  6970  6970 E ZipFileCache: init failed when open zip file.
07-15 15:21:46.179  6970  6970 E ZipFileCache: init failed when open zip file.
07-15 15:21:46.179  6970  6970 E ZipFileCache: init failed when open zip file.
07-15 15:21:46.179  6970  6970 E ZipFileCache: init failed when open zip file.
07-15 15:21:46.179  6970  6970 E ZipFileCache: init failed when open zip file.
07-15 15:21:46.179  6970  6970 E ZipFileCache: init failed when open zip file.
07-15 15:21:46.179  6970  6970 E ZipFileCache: init failed when open zip file.
07-15 15:21:46.189  6970  6970 E ZipFileCache: init failed when open zip file.
07-15 15:21:46.189  6970  6970 E ZipFileCache: init failed when open zip file.
07-15 15:21:46.189  6970  6970 E ZipFileCache: init failed when open zip file.
07-15 15:21:46.189  6970  6970 E ZipFileCache: init failed when open zip file.
07-15 15:21:46.189  6970  6970 E ZipFileCache: init failed when open zip file.
07-15 15:21:46.189  6970  6970 E ZipFileCache: init failed when open zip file.
07-15 15:21:46.189  6970  6970 E ZipFileCache: init failed when open zip file.
07-15 15:21:46.189  6970  6970 E ZipFileCache: init failed when open zip file.
07-15 15:21:46.189  6970  6970 E ZipFileCache: init failed when open zip file.
07-15 15:21:46.189  6970  6970 E ZipFileCache: init failed when open zip file.
07-15 15:21:46.189  6970  6970 E ZipFileCache: init failed when open zip file.
07-15 15:21:46.189  6970  6970 W art     : Attempt to remove local handle scope entry from IRT, ignoring
07-15 15:21:46.199  6970  6970 W AwContents: onDetachedFromWindow called when already detached. Ignoring
07-15 15:21:46.199  6970  6970 I art     : Can not find class: Landroid/widget/ViewStub;
07-15 15:21:46.199  6970  6970 I art     : Can not find class: Landroid/webkit/ViewStub;
07-15 15:21:46.199  6970  6970 I art     : Can not find class: Landroid/app/ViewStub;
07-15 15:21:46.229  6970  6970 W art     : Attempt to remove local handle scope entry from IRT, ignoring
07-15 15:21:46.229  6970  6970 W art     : Attempt to remove local handle scope entry from IRT, ignoring
07-15 15:21:46.519  3249  3249 I PhoneStatusBar: hw_status_bar_operators = true, setSystemUIVisibily(SHOW_OPERATOR = false)
,07-15 15:21:46.519  3249  3249 I PhoneStatusBar: shouldTranslucent:true
07-15 15:21:46.519  3249  3249 I PhoneStatusBar: hw_status_bar_operators = true, setSystemUIVisibily(SHOW_OPERATOR = false)
,07-15 15:21:46.549  6970  7027 I OpenGLRenderer: Initialized EGL, version 1.4
,07-15 15:21:46.619  3043  3075 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +995ms (total +1s67ms)
,07-15 15:21:46.619  6970  6970 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
,07-15 15:21:46.719  6970  6970 I chromium: [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
07-15 15:21:46.719  6970  6970 I chromium: 
,07-15 15:21:46.919  6970  7034 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 58:2A:F7:ED:96:BE
07-15 15:21:46.939  6970  7034 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
07-15 15:21:46.939  6970  7034 W org.thaliproject.p2p.btconnectorlib.DiscoveryManager: isBleMultipleAdvertisementSupported: Bluetooth is not enabled so we could not check whether or not BluetoothLE multi advertisement is supported. However, Bluetooth LE is supported so we just *assume* multi advertisement is supported too (which may not always be the case).
07-15 15:21:46.939  6970  7034 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
07-15 15:21:46.939  6970  7034 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 1 -> 2
07-15 15:21:46.939  6970  7034 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 2 -> 3
07-15 15:21:46.939  6970  7034 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 1 -> 2
07-15 15:21:46.939  6970  7034 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-15 15:21:46.949  6970  7034 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 58:2A:F7:ED:96:BE
07-15 15:21:46.949  6970  7034 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
07-15 15:21:46.949  6970  7034 I io.jxcore.node.LifeCycleMonitor: start: OK
07-15 15:21:46.979  6970  6970 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
07-15 15:21:47.439  6970  7037 W jxcore-log: Initializing JXcore engine
07-15 15:21:47.439  6970  7037 W jxcore-log: JXcore engine is ready
,07-15 15:21:47.499  6970  7037 W jxcore-log: Starting JXcore engine
,07-15 15:21:47.619  6970  7037 W jxcore-log: Platform android
07-15 15:21:47.619  6970  7037 W jxcore-log: 
07-15 15:21:47.619  6970  7037 W jxcore-log: Process ARCH arm
07-15 15:21:47.619  6970  7037 W jxcore-log: 
,07-15 15:21:47.829  6970  7037 I jxcore-log: JXcore Cordova bridge is ready!
07-15 15:21:47.829  6970  7037 I jxcore-log: 
,07-15 15:21:47.829  6970  7037 W jxcore-log: JXcore engine is started
,07-15 15:21:47.829  6970  7034 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,07-15 15:21:47.839  6970  6970 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,07-15 15:21:47.849  6970  7037 E jxcore  : Error!: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js
07-15 15:21:47.849  6970  7037 E jxcore  : Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,07-15 15:21:47.849  6970  6970 I chromium: [INFO:CONSOLE(57)] "app.js file failed to load : "No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\nError: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\n    at $h.require@node.js:1472:1\n    at internal_methods.loadMainFile@main.js.js:260:5\n    at JXMobile.executeJSON@main.js.js:279:7\n    at @JX_Evaluate:1:1\n"", source: file:///android_asset/www/js/thali_main.js (57)
07-15 15:21:47.849  6970  6970 I chromium: [INFO:CONSOLE(62)] "****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****", source: file:///android_asset/www/js/thali_main.js (62)
,07-15 15:21:47.919  3761  4084 I HwSystemManager: AppLockService:applock password not initial or function is closed
07-15 15:21:47.929  6970  6970 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-15 15:21:47.929  6970  6970 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,07-15 15:21:47.929  6970  6970 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,07-15 15:21:47.929  6970  6970 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-15 15:21:47.929  6970  6970 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
,07-15 15:21:47.929  3761  4084 I HwSystemManager: AppLockService:applock password not initial or function is closed
07-15 15:21:47.929  6970  7034 W PluginManager: THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 76ms. Plugin should use CordovaInterface.getThreadPool().
,07-15 15:21:47.939  3761  4044 I HwSystemManager: AppManager:getNetAppInfoFromDB cursor lenth = 1
,07-15 15:21:47.939  3043  3289 E HsmCoreServiceImpl: onTransact in code is: 102
07-15 15:21:47.939  3043  3289 I MediaProcessHandler: processOp opType: 1, uid: 10041, pid: 6004
07-15 15:21:47.939  3761  4259 I HwSystemManager: HoldService:uid:10041 pid:6004 died
07-15 15:21:47.939  3043  3289 W MediaProcessHandler: remove target not exist, maybe the UI process: uid: 10041, pid: 6004
07-15 15:21:47.939  3761  4259 I HwSystemManager: HoldService:oldVersionKey:10041,6004
07-15 15:21:47.939  3761  4259 I HwSystemManager: BgPowerManagerService:onProcessDied uid = 10041
,07-15 15:21:47.939  6970  6970 I io.jxcore.node.LifeCycleMonitor: stop: OK
,07-15 15:21:47.949  6970  6970 W ScreenOrientationListener: Removing an inexistent observer!
,07-15 15:21:48.129  7040  7040 I appproc : CLASSPATH=/system/framework/pm.jar
07-15 15:21:48.129  7040  7040 I appproc : Command=app_process /system/bin com.android.commands.pm.Pm uninstall com.test.thalitest 
07-15 15:21:48.129  7040  7040 I appproc : app_process:number,4,0
,07-15 15:21:48.139  7040  7040 I AndroidRuntime: readDownloadBoosterConfig: 'false'
,07-15 15:21:48.269  7040  7040 I         : power log dlsym ok
,07-15 15:21:48.319  7040  7040 E android_hardware_fm.cpp: register_android_hardware_fm_fmradio
07-15 15:21:48.319  7040  7040 I android_hardware_fm.cpp: ========64bit long size = 8
07-15 15:21:48.319  7040  7040 E FM_HAL  : [FM_HAL], libname is libhisifm_if
,07-15 15:21:48.319  7040  7040 I fm_hisi : FM::[fm_device_open:4655] fm_device_open
07-15 15:21:48.319  7040  7040 I fm_hisi : 
07-15 15:21:48.319  7040  7040 I fm_hisi : FM::[fm_device_open:4666] find the id:libhisifm_if and begins to open the device
07-15 15:21:48.319  7040  7040 I fm_hisi : 
07-15 15:21:48.319  7040  7040 I fm_hisi : FM::[fm_device_open:4710] device open sucess
07-15 15:21:48.319  7040  7040 I fm_hisi : 
07-15 15:21:48.319  7040  7040 E android_hardware_fm.cpp: register_android_hardware_fm_fmradio, ret is 0
,07-15 15:21:48.329  5753  6907 I PG Utils: acquire_providerpkg:[com.google.android.gsf] pid:[]  maybe timeout , send to PG
,07-15 15:21:48.539  3043  3591 I art     : Explicit concurrent mark sweep GC freed 52001(3MB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 28MB/42MB, paused 1.700ms total 179.605ms
,07-15 15:21:48.539  3043  3591 I art     : Can not find class: Lcom/android/server/pm/PackageInstallerService$PackageDeleteObserverAdapter;
,07-15 15:21:48.539  3043  3591 I art     : Can not find class: Lcom/android/server/pm/PackageManagerService$9;
,07-15 15:21:48.539  3043  3204 I art     : Can not find class: Lcom/android/server/am/TaskPersister$ImageWriteQueueItem;
,07-15 15:21:48.659  3761  4259 I HwSystemManager: HoldService:uid:10072 pid:6970 died
07-15 15:21:48.659  3761  4084 I HwSystemManager: BgPowerManagerService:onProcessDied uid = 10072
07-15 15:21:48.659  3761  4259 I HwSystemManager: HoldService:oldVersionKey:10072,6970
07-15 15:21:48.659  3043  3637 E HsmCoreServiceImpl: onTransact in code is: 102
07-15 15:21:48.659  3043  3637 I MediaProcessHandler: processOp opType: 1, uid: 10072, pid: 6970
07-15 15:21:48.659  3043  3637 W MediaProcessHandler: remove target not exist, maybe the UI process: uid: 10072, pid: 6970
,07-15 15:21:48.699  3043  3082 I ActivityManager: filter receiver for action = android.intent.action.PACKAGE_REMOVED
,07-15 15:21:48.729  3480  4035 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,07-15 15:21:48.729  3043  3146 I InputReader: Reconfiguring input devices.  changes=0x00000010
07-15 15:21:48.729  6365  6557 I AccountTypeManager: Adding account type = com.android.contacts.model.account.ExchangeAccountType@81c496f in the cache
,07-15 15:21:48.739  3548  3548 E RegisteredServicesCache: invalidateCache set mNeedToastTableFull
,07-15 15:21:48.739  6365  6557 I SimFactoryManager: Get SIM state from SIM factory manager: 1,For slotId:0
,07-15 15:21:48.739  6140  6140 I art     : Explicit concurrent mark sweep GC freed 13083(907KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 16MB/21MB, paused 1.561ms total 78.943ms
,07-15 15:21:48.749  6365  6557 I SimFactoryManager: Get SIM state from SIM factory manager: 1,For slotId:1
,07-15 15:21:48.749  6365  6557 I AccountTypeManager: Adding account type = com.android.contacts.model.account.ExternalAccountType@d45467c in the cache
,07-15 15:21:48.779  6365  6557 W ResourceType: For resource 0x7f020947, entry index(2375) is beyond type entryCount(769)
,07-15 15:21:48.779  6365  6557 W ResourceType: Failure getting entry for 0x7f020947 (t=1 e=2375) (error -75)
07-15 15:21:48.779  6365  6557 W ResourceType: For resource 0x7f0209a3, entry index(2467) is beyond type entryCount(769)
07-15 15:21:48.779  6365  6557 W ResourceType: Failure getting entry for 0x7f0209a3 (t=1 e=2467) (error -75)
07-15 15:21:48.779  6365  6557 I AccountTypeManager: Adding account type = com.android.contacts.model.account.ExternalAccountType@1e0fb05 in the cache
07-15 15:21:48.779  6604  6604 I art     : Explicit concurrent mark sweep GC freed 31087(2MB) AllocSpace objects, 10(160KB) LOS objects, 24% free, 13MB/18MB, paused 7.902ms total 115.597ms
,07-15 15:21:48.779  6604  6604 I HwSystemManager: HsmPackageManager:Receive intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
07-15 15:21:48.779  6604  6604 I HwSystemManager: HsmPackageManager:replacing:false
07-15 15:21:48.779  6604  6604 I HwSystemManager: HsmPackageManager:pkgName:com.test.thalitest
,07-15 15:21:48.779  6604  6604 I HwSystemManager: HsmPackageManager:doAppRemoved, remove:com.test.thalitest
07-15 15:21:48.779  6365  6557 I AccountTypeManager: Adding account type = com.android.contacts.model.account.GoogleAccountType@424975a in the cache
,07-15 15:21:48.789  6365  6557 E ExternalAccountType: Unsupported attribute readOnly
,07-15 15:21:48.799  6365  6557 I AccountTypeManager: AccountManager, account size is: 2
,07-15 15:21:48.799  6365  6557 I AccountTypeManager: Loaded meta-data for 5 account types, 3 accounts in 76ms(wall) 23ms(cpu)
,07-15 15:21:48.799  3043  3069 W ResourceType: ResTable_typeSpec entry count inconsistent: given 1, previously 1445
07-15 15:21:48.799  3043  3082 I ActivityManager: filter receiver for action = android.intent.action.PACKAGE_FULLY_REMOVED
,07-15 15:21:48.799  3043  3082 I ActivityManager: filter receiver for action = android.intent.action.UID_REMOVED
,07-15 15:21:48.819  3761  3761 I art     : Explicit concurrent mark sweep GC freed 95350(6MB) AllocSpace objects, 27(432KB) LOS objects, 39% free, 14MB/23MB, paused 9.427ms total 158.104ms
07-15 15:21:48.819  3761  3761 I HwSystemManager: HsmPackageManager:Receive intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
07-15 15:21:48.819  3761  3761 I HwSystemManager: HsmPackageManager:replacing:false
07-15 15:21:48.819  3761  3761 I HwSystemManager: HsmPackageManager:pkgName:com.test.thalitest
07-15 15:21:48.819  3761  3761 I HwSystemManager: HsmPackageManager:doAppRemoved, remove:com.test.thalitest
,07-15 15:21:48.819  3615  3615 I art     : Explicit concurrent mark sweep GC freed 62176(3MB) AllocSpace objects, 106(10MB) LOS objects, 38% free, 25MB/41MB, paused 1.084ms total 140.016ms
07-15 15:21:48.819  3615  3615 I HwLauncher: Model  onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
07-15 15:21:48.819  3615  3615 I HwLauncher: Model replacing = false package = com.test.thalitest
07-15 15:21:48.819  3615  3615 I HwLauncher: Model  ACTION_PACKAGE_REMOVED replacing = false
07-15 15:21:48.819  3615  3615 I HwLauncher: MutilSelectedIconsonPreHandleUpdatedTask : mIsInMutilSelectMode = false task = 3 packages = [com.test.thalitest]
07-15 15:21:48.819  3615  3615 I HwLauncher: SimpleLauncherModeaction= android.intent.action.PACKAGE_REMOVEDpackageName = com.test.thalitest
07-15 15:21:48.829  3615  3746 I HwLauncher: SimpleLauncherModedeleteBadgeItemFromDBByPkg packageName=com.test.thalitest
07-15 15:21:48.829  3761  3761 I HwSystemManager: ww:deleteLockData:com.test.thalitest
07-15 15:21:48.829  3043  3151 I art     : Can not find class: Lcom/android/server/net/NetworkStatsRecorder$RemoveUidRewriter;
,07-15 15:21:48.849  3615  3746 I HwLauncher: Launcher.LauncherProvider  only HwLauncher can use LauncherProvider's delete method to delete badge table item 
07-15 15:21:48.849  3615  3746 I HwLauncher: SimpleAllAppsList   add packageName into uninstalledSDApps 
07-15 15:21:48.849  3615  3746 I HwLauncher: SimpleLauncherModeuninstalledSDApps size > 0
07-15 15:21:48.849  3615  3746 W HwLauncher: SimpleLauncherModeNobody to tell about the new app.  Launcher is probably loading.
07-15 15:21:48.849  3615  3746 I HwLauncher: SimpleLauncherModeOP_REMOVE callback is null, delete simpleUI database record
,07-15 15:21:48.849  3615  3730 I HwLauncher: Model mAllAppsList.removePackage com.test.thalitest
,07-15 15:21:48.859  5753  5753 I art     : Explicit concurrent mark sweep GC freed 9987(683KB) AllocSpace objects, 2(40KB) LOS objects, 24% free, 23MB/31MB, paused 1.133ms total 202.387ms
,07-15 15:21:48.869  3615  3615 I HwLauncher: Launcher  onWindowVisibilityChanged visibility = 4
07-15 15:21:48.869  3615  3615 I HwLauncher: DynamicIcon onWindowVisibilityChanged 4 - com.android.calendar
07-15 15:21:48.869  3615  3615 I HwLauncher: DynamicIcon onWindowVisibilityChanged 4 - com.android.deskclock
,07-15 15:21:48.879  3615  3615 E HideAppsPagedView: removeItems begin 
07-15 15:21:48.879  3615  3615 E HideAppsPagedView: ShortcutInfo(title=ThaliTest)
07-15 15:21:48.879  3615  3615 E HideAppsPagedView: removeItems end 
,07-15 15:21:48.879  3615  3615 I HwLauncher: Launcher onStart()
07-15 15:21:48.879  3615  3615 I HwLauncher: Launcher dynamicIconsRegister
07-15 15:21:48.879  3615  3615 I HwLauncher: DynamicUpdater registerReceiver
,07-15 15:21:48.879  3615  3615 I HwLauncher: DynamicUpdater call updateFolder
07-15 15:21:48.879  3615  3615 I HwLauncher: DynamicIcon onResume  isvisible = false   mAttachedToWindow:true    mWindowVisible:falsecom.android.calendar
07-15 15:21:48.879  3615  3615 I HwLauncher: DynamicUpdater registerReceiver
,07-15 15:21:48.879  3615  3615 I HwLauncher: DynamicUpdater call updateFolder
07-15 15:21:48.879  3615  3615 I HwLauncher: DynamicIcon onResume  isvisible = false   mAttachedToWindow:true    mWindowVisible:falsecom.android.deskclock
07-15 15:21:48.879  3615  3615 I HwLauncher: DynamicUpdater registerReceiver
07-15 15:21:48.889  3615  3615 I HwLauncher: DynamicUpdater call updateFolder
07-15 15:21:48.889  3615  3730 I HwLauncher: DynamicIconData , getDrawableForDynamic begin, pkg = com.android.deskclock, picName = deskclock_bg
07-15 15:21:48.889  3615  3615 I HwLauncher: DynamicIcon onResume  isvisible = true   mAttachedToWindow:false    mWindowVisible:falsecom.huawei.android.totemweather
07-15 15:21:48.889  3615  3615 I HwLauncher: DynamicIcon onVisibilityChanged 0 - com.android.calendar
07-15 15:21:48.889  3615  3615 I HwLauncher: DynamicIcon onVisibilityChanged 0 - com.android.deskclock
,07-15 15:21:48.889  3761  3934 I HwSystemManager: aor:Network Stats Updated
07-15 15:21:48.889  3761  3934 I HwSystemManager: aoi:onNetworkStatsUpdated
07-15 15:21:48.889  3761  3937 I HwSystemManager: TrafficAnalyseManager:mDataServiceStatusCard1 : false mDataServiceStatusCard2 : false
07-15 15:21:48.889  3615  3615 I HwLauncher: Workspace removeItems info = ShortcutInfo(title=ThaliTest) isNeedDelete = true
07-15 15:21:48.889  3615  3730 I HwLauncher: DynamicIconData , getDrawableForDynamic end, pkg = com.android.deskclock, picName = deskclock_bg
07-15 15:21:48.889  3615  3730 I HwLauncher: DynamicIconData , getDrawableForDynamic begin, pkg = com.android.deskclock, picName = deskclock_bg
,07-15 15:21:48.889  3615  3730 I HwLauncher: DynamicIconData , getDrawableForDynamic end, pkg = com.android.deskclock, picName = deskclock_bg
,07-15 15:21:48.889  3615  3615 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
07-15 15:21:48.889  3615  3615 W System.err: 	at android.app.ApplicationPackageManager.getApplicationInfo(ApplicationPackageManager.java:287)
07-15 15:21:48.889  3615  3615 W System.err: 	at com.huawei.android.launcher.ShortcutInfo.isAppUninstallable(ShortcutInfo.java:347)
07-15 15:21:48.889  3615  3615 W System.err: 	at com.huawei.android.launcher.Workspace$10.run(Workspace.java:6784)
07-15 15:21:48.889  3615  3615 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
07-15 15:21:48.889  3615  3615 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
07-15 15:21:48.889  3615  3615 W System.err: 	at android.os.Looper.loop(Looper.java:135)
07-15 15:21:48.889  3615  3615 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5538)
07-15 15:21:48.889  3615  3615 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
07-15 15:21:48.889  3615  3615 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
07-15 15:21:48.889  3615  3615 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:960)
07-15 15:21:48.889  3615  3615 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:755)
07-15 15:21:48.889  3615  3615 W System.err: java.lang.NullPointerException: null receiver
07-15 15:21:48.889  3615  3615 W System.err: 	at java.lang.reflect.Field.get(Native Method)
07-15 15:21:48.889  3615  3615 W System.err: 	at java.lang.reflect.Field.get(Field.java:279)
07-15 15:21:48.889  3615  3615 W System.err: 	at com.huawei.android.launcher.ShortcutInfo.isAppUninstallable(ShortcutInfo.java:372)
07-15 15:21:48.889  3615  3615 W System.err: 	at com.huawei.android.launcher.Workspace$10.run(Workspace.java:6784)
07-15 15:21:48.889  3615  3615 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
07-15 15:21:48.889  3615  3615 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
07-15 15:21:48.889  3615  3615 W System.err: 	at android.os.Looper.loop(Looper.java:135)
07-15 15:21:48.889  3615  3615 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5538)
07-15 15:21:48.889  3615  3615 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
07-15 15:21:48.889  3615  3615 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
07-15 15:21:48.889  3615  3615 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:960)
07-15 15:21:48.889  3615  3615 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:755)
07-15 15:21:48.889  3615  3615 I HwLauncher: CellLayout rearrangeAfterRmItem isAutoAlign = false
,07-15 15:21:48.899  3615  3615 I HwLauncher: Launcher  onWindowVisibilityChanged visibility = 0,
07-15 15:21:48.899  3615  3615 I HwLauncher: DynamicIcon onWindowVisibilityChanged 0 - com.android.calendar
07-15 15:21:48.899  3615  3615 I HwLauncher: DynamicIcon onWindowVisibilityChanged 0 - com.android.deskclock
07-15 15:21:48.899  3615  3730 I HwLauncher: Launcher.Utilities createIconBitmap classname = null, sourceWidth = 114, sourceHeight = 114
,07-15 15:21:48.899  3615  3730 I HwLauncher: ClockDynamicUpdater clock update folder at ClockDynamicUpdater
07-15 15:21:48.899  3615  3730 I HwLauncher: DynamicUpdater updateBitmap end and send update message
07-15 15:21:48.899  3761  3937 E HwSystemManager: getSimCardType:/getSimCardInfo: imsi is null
,07-15 15:21:48.899  3615  3730 I HwLauncher: WeatherDynamicUpdaterpositiveUpdate at WeatherDynamicUpdater,
07-15 15:21:48.899  3761  3937 E HwSystemManager: getSimCardType:/getSimCardInfo: imsi is null
07-15 15:21:48.899  3761  3937 E HwSystemManager: getSimCardType:/getPhoneSimCardInfo: boths card not recongnized
,07-15 15:21:48.899  3761  3937 W HwSystemManager: TrafficAnalyseManager:initCardStatus: preferredCardInfo is null.
07-15 15:21:48.909  3761  3937 E HwSystemManager: TrafficNotifyOverMarkForDay:notifyTafficOverMarkForDay: imsi is null.
07-15 15:21:48.909  3761  3937 I HwSystemManager: TrafficAnalyseManager:mDataServiceStatusCard1 : false mDataServiceStatusCard2 : false
,07-15 15:21:48.919  3761  3937 E HwSystemManager: getSimCardType:/getSimCardInfo: imsi is null,
,07-15 15:21:48.929  3615  3615 E HideAppsPagedView: removeHideApps  begin ,
07-15 15:21:48.929  3761  3937 E HwSystemManager: getSimCardType:/getSimCardInfo: imsi is null
07-15 15:21:48.929  3761  3937 E HwSystemManager: getSimCardType:/getPhoneSimCardInfo: boths card not recongnized
07-15 15:21:48.929  3761  3937 W HwSystemManager: TrafficAnalyseManager:initCardStatus: preferredCardInfo is null.
07-15 15:21:48.929  3615  3615 E HideAppsPagedView: removeHideApps  end 
,07-15 15:21:48.929  3615  3615 E HideAppsPagedView:  syncPages mCurrentPage = 0
,07-15 15:21:48.929  3761  3937 E HwSystemManager: TrafficNotifyOverMarkForMonth:notifyTafficOverMarkForMonth: imsi is null.
07-15 15:21:48.929  3761  3937 I HwSystemManager: TrafficAnalyseManager:mDataServiceStatusCard1 : false mDataServiceStatusCard2 : false
,07-15 15:21:48.929  3615  3615 E ZipFileCache: init failed when open zip file.
,07-15 15:21:48.929  3615  3615 E ZipFileCache: init failed when open zip file.
,07-15 15:21:48.939  3761  3937 E HwSystemManager: getSimCardType:/getSimCardInfo: imsi is null
,07-15 15:21:48.939  3615  3615 E ZipFileCache: init failed when open zip file.
,07-15 15:21:48.939  3615  3615 E ZipFileCache: init failed when open zip file.
,07-15 15:21:48.939  3615  3615 E ZipFileCache: init failed when open zip file.
07-15 15:21:48.939  3761  3937 E HwSystemManager: getSimCardType:/getSimCardInfo: imsi is null
07-15 15:21:48.939  3761  3937 E HwSystemManager: getSimCardType:/getPhoneSimCardInfo: boths card not recongnized
,07-15 15:21:48.939  3761  3937 W HwSystemManager: TrafficAnalyseManager:initCardStatus: preferredCardInfo is null.
,07-15 15:21:48.939  3761  3937 E HwSystemManager: TrafficNotifyExcessForMonth:notifyTafficExcessForMonth: imsi is null.
,07-15 15:21:48.939  3615  3615 E HideAppsPagedView:  syncAppsPageItems page = 0 mNumAppsPages = 1 mCurrentPage = 0
,07-15 15:21:48.939  3615  3615 E HideAppsPagedView:  createAddIcon count = 0
,07-15 15:21:48.949  3043  3138 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
07-15 15:21:48.949  3043  3138 W System.err: 	at android.app.ApplicationPackageManager.getApplicationInfo(ApplicationPackageManager.java:287)
07-15 15:21:48.949  3043  3138 W System.err: 	at com.android.server.SmartHeartBeat$HeartBeatHandler.updatePackageMessage(SmartHeartBeat.java:872)
07-15 15:21:48.949  3043  3138 W System.err: 	at com.android.server.SmartHeartBeat$HeartBeatHandler.handleMessage(SmartHeartBeat.java:606)
07-15 15:21:48.949  3043  3138 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-15 15:21:48.949  3043  3138 W System.err: 	at android.os.Looper.loop(Looper.java:135)
07-15 15:21:48.949  3043  3138 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,07-15 15:21:48.949  3615  3615 I HwLauncher:  FPSMonitor snapToPage whichPage = 0 delta = 0 duration = 550
,07-15 15:21:48.949  3615  3615 I HwLauncher: DynamicUpdater call updateFolder
,07-15 15:21:48.999  3043  3069 W asset   : Asset path /system/framework/com.huawei.theme.stat.jar is neither a directory nor file (type=1).
,07-15 15:21:49.009  7085  7085 W asset   : Asset path /system/framework/com.huawei.theme.stat.jar is neither a directory nor file (type=1).
,07-15 15:21:49.009  7062  7062 E Minikin : addFont failed to create font /system/fonts/DroidSansChineseslim.ttf
,07-15 15:21:49.009  7062  7062 W GalleryUtils: the font DroidSanChineseSlim is not exist!
,07-15 15:21:49.029  3043  3043 I art     : Can not find class: Lhuawei/com/android/server/util/UserBehaviourRecord;
,07-15 15:21:49.029  3043  3043 I art     : Can not find class: Lhuawei/com/android/server/util/UserBehaviourRecord$1;
,07-15 15:21:49.029  3043  3043 I art     : Can not find class: Lhuawei/com/android/server/util/ReportTool;
07-15 15:21:49.029  3043  3043 I art     : Can not find class: Lcom/huawei/report/ReporterInterface;
,07-15 15:21:49.029  3043  3043 E ReportTools: Can't find sReporterClazz
,07-15 15:21:49.029  3043  3043 I art     : Can not find class: Lhuawei/com/android/server/util/UserBehaviourRecord$UploadThread;
,07-15 15:21:49.029  3043  3043 I art     : Can not find class: Lhuawei/com/android/server/util/AppInfo;
,07-15 15:21:49.039  3043  3043 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'int com.huawei.lcagent.client.LogCollectManager.getUserType()' on a null object reference
,07-15 15:21:49.039  7085  7105 I HwCust  : Constructor found for class com.huawei.android.totemweather.utils.HwCustUseBitmapConfigImpl
,07-15 15:21:49.039  3043  3043 W System.err: 	at huawei.com.android.server.util.ReportTool.getUserType(ReportTool.java:86)
07-15 15:21:49.039  3043  3043 W System.err: 	at huawei.com.android.server.util.ReportTool.isBetaUser(ReportTool.java:73)
07-15 15:21:49.039  3043  3043 W System.err: 	at huawei.com.android.server.util.ReportTool.report(ReportTool.java:58)
07-15 15:21:49.039  3043  3043 W System.err: 	at huawei.com.android.server.util.UserBehaviourRecord.appExitRecord(UserBehaviourRecord.java:65)
07-15 15:21:49.039  3043  3043 W System.err: 	at com.android.server.am.ActivityManagerService.cleanUpRemovedTaskLocked(ActivityManagerService.java:9041)
07-15 15:21:49.039  3043  3043 W System.err: 	at com.android.server.am.ActivityManagerService.removeTaskByIdLocked(ActivityManagerService.java:9097)
07-15 15:21:49.039  3043  3043 W System.err: 	at com.android.server.am.ActivityManagerService.access$1000(ActivityManagerService.java:293)
07-15 15:21:49.039  3043  3043 W System.err: 	at com.android.server.am.ActivityManagerService$3.onPackageRemoved(ActivityManagerService.java:2234)
07-15 15:21:49.039  3043  3043 W System.err: 	at com.android.internal.content.PackageMonitor.onReceive(PackageMonitor.java:341)
07-15 15:21:49.039  3043  3043 W System.err: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:899)
07-15 15:21:49.039  3043  3043 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
07-15 15:21:49.039  3043  3043 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
07-15 15:21:49.039  3043  3043 W System.err: 	at android.os.Looper.loop(Looper.java:135)
07-15 15:21:49.039  3043  3043 W System.err: 	at com.android.server.SystemServer.run(SystemServer.java:324)
07-15 15:21:49.039  3043  3043 W System.err: 	at com.android.server.SystemServer.main(SystemServer.java:212)
07-15 15:21:49.039  3043  3043 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
07-15 15:21:49.039  3043  3043 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
07-15 15:21:49.039  3043  3043 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:960)
07-15 15:21:49.039  3043  3043 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:755)
07-15 15:21:49.039  3043  3043 E ReportTools: This is not beta user build
,07-15 15:21:49.039  3249  3249 I PhoneStatusBar: hw_status_bar_operators = true, setSystemUIVisibily(SHOW_OPERATOR = false)
07-15 15:21:49.039  3249  3249 I PhoneStatusBar: shouldTranslucent:true
,07-15 15:21:49.039  3249  3249 I PhoneStatusBar: hw_status_bar_operators = true, setSystemUIVisibily(SHOW_OPERATOR = false)
,07-15 15:21:49.039  7085  7085 I HwCust  : Constructor found for class com.huawei.android.totemweather.HwCustWeatherAppHwBaseImpl
,07-15 15:21:49.059  3761  3761 I HwSystemManager: NotificationManagerReceiver:onReceive action = android.intent.action.PACKAGE_REMOVED
07-15 15:21:49.059  3761  3761 I HwSystemManager: NotificationManagerReceiver:onReceive, send action to background
,07-15 15:21:49.059  3761  3761 I HwSystemManager: HsmIntentService:created. this:com.huawei.systemmanager.util.content.HsmIntentService_bg@29b393fa
,07-15 15:21:49.059  3761  3761 I HwSystemManager: HsmIntentService:started for intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.huawei.systemmanager/com.huawei.notificationmanager.receiver.Receiver (has extras) }, action:android.intent.action.PACKAGE_REMOVED, class:com.huawei.notificationmanager.receiver.Receiver
,07-15 15:21:49.059  3615  3615 I HwLauncher: WeatherDynamicUpdaterreceive action = com.huawei.android.action.launcher_weather_icon_change
,07-15 15:21:49.059  3761  7113 I HwSystemManager: HsmIntentService:invoked com.huawei.notificationmanager.receiver.Receiver
,07-15 15:21:49.059  6604  6604 I HwSystemManager: AppInstallationReceiver:AppInstallationReceiver onReceive action = android.intent.action.PACKAGE_REMOVED
,07-15 15:21:49.069  6604  6604 I HwSystemManager: HsmIntentService:created. this:com.huawei.systemmanager.util.content.HsmIntentService_ui@3e066760
07-15 15:21:49.069  6604  6604 I HwSystemManager: HsmIntentService:started for intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.huawei.systemmanager/com.huawei.permissionmanager.ui.AppInstallationReceiver (has extras) }, action:android.intent.action.PACKAGE_REMOVED, class:com.huawei.permissionmanager.ui.AppInstallationReceiver
07-15 15:21:49.069  6604  7114 I HwSystemManager: HsmIntentService:invoked com.huawei.permissionmanager.ui.AppInstallationReceiver
,07-15 15:21:49.069  6604  6604 I HwSystemManager: HsmIntentService:started for intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.huawei.systemmanager/.optimize.OptimizeReceiver (has extras) }, action:android.intent.action.PACKAGE_REMOVED, class:com.huawei.systemmanager.optimize.OptimizeReceiver
,07-15 15:21:49.069  6604  6604 I HwSystemManager: ComBroadcastReceiver:ComBroadcastReceiver action = android.intent.action.PACKAGE_REMOVED
,07-15 15:21:49.069  6604  7115 I HwSystemManager: HsmIntentService:invoked com.huawei.systemmanager.optimize.OptimizeReceiver
07-15 15:21:49.069  6604  7115 I HwSystemManager: OptimizeReceiver:OptimizeReceiver received action:android.intent.action.PACKAGE_REMOVED
,07-15 15:21:49.069  6604  7115 I HwSystemManager: OverseaCfgHelper:permissionStatus is 0
07-15 15:21:49.069  6604  6827 I HwSystemManager: ProtectAppControl:handleMessage:7
07-15 15:21:49.069  6604  7115 I HwSystemManager: HsmIntentService:task completed for intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.huawei.systemmanager/.optimize.OptimizeReceiver (has extras) }, action:android.intent.action.PACKAGE_REMOVED
07-15 15:21:49.069  6604  7115 I HwSystemManager: HsmIntentService:in thread:Thread[HsmIntentServiceTask #5,5,main], current active tasksize:2, queue size:0
,07-15 15:21:49.079  3761  3761 I HwSystemManager: AppCleanUpService:onStartCommand() in!
07-15 15:21:49.079  3761  3761 I HwSystemManager: AppCleanUpService:onStartCommand() out!
07-15 15:21:49.079  3761  3761 E HwSystemManager: AppCleanUpService:msg is 1
07-15 15:21:49.079  3761  3783 I HwSystemManager: OptimizeProvider:delete com.test.thalitest
,07-15 15:21:49.079  6604  6827 I HwSystemManager: PowerGenieDbHelper:delete protect app:com.test.thalitest
,07-15 15:21:49.079  6604  6604 I HwSystemManager: HsmIntentService:started for intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.huawei.systemmanager/.power.receiver.BootBroadcastReceiver (has extras) }, action:android.intent.action.PACKAGE_REMOVED, class:com.huawei.systemmanager.power.receiver.BootBroadcastReceiver
,07-15 15:21:49.079  6604  6604 I HwSystemManager: NetAppListPrepareReceiver:NetAppListPrepareReceiver:  onReceive(), action = android.intent.action.PACKAGE_REMOVED
07-15 15:21:49.079  6604  6604 I HwSystemManager: NetAppListPrepareReceiver:package removed: package:com.test.thalitest
,07-15 15:21:49.079  6604  6604 I HwSystemManager: NetAppListPrepareReceiver:replacing?:false
,07-15 15:21:49.089  6604  7116 I HwSystemManager: HsmIntentService:invoked com.huawei.systemmanager.power.receiver.BootBroadcastReceiver
,07-15 15:21:49.089  6604  7116 W HwSystemManager: BootBroadcastReceiver:No handler exist for registered action:android.intent.action.PACKAGE_REMOVED
07-15 15:21:49.089  6604  7116 I HwSystemManager: HsmIntentService:task completed for intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.huawei.systemmanager/.power.receiver.BootBroadcastReceiver (has extras) }, action:android.intent.action.PACKAGE_REMOVED
07-15 15:21:49.089  6604  7116 I HwSystemManager: HsmIntentService:in thread:Thread[HsmIntentServiceTask #6,5,main], current active tasksize:2, queue size:0
,07-15 15:21:49.089  3615  3730 I HwLauncher: WeatherDynamicUpdaterreceiver data is int[] = [0, 0]
07-15 15:21:49.089  3615  3730 I HwLauncher:  stringArray[] [unknown]
,07-15 15:21:49.089  3761  3840 I HwSystemManager: NotificationDBProvider:call: method = notification_list_query
07-15 15:21:49.089  3761  3840 I HwSystemManager: NotificationDBProvider:query starts, uri = content://com.huawei.systemmanager.NotificationDBProvider/notificationCfg
07-15 15:21:49.089  3761  4084 I HwSystemManager: NotificationDBProvider:query starts, uri = content://com.huawei.systemmanager.NotificationDBProvider/notificationCfg
07-15 15:21:49.089  3761  4084 I HwSystemManager: NotificationDBProvider:query starts, matchCode = 1
,07-15 15:21:49.089  3761  3840 I HwSystemManager: NotificationDBProvider:query starts, matchCode = 1
,07-15 15:21:49.099  3761  7113 I HwSystemManager: HsmIntentService:task completed for intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.huawei.systemmanager/com.huawei.notificationmanager.receiver.Receiver (has extras) }, action:android.intent.action.PACKAGE_REMOVED
,07-15 15:21:49.099  3761  7113 I HwSystemManager: HsmIntentService:in thread:Thread[HsmIntentServiceTask #2,5,main], current active tasksize:1, queue size:0
07-15 15:21:49.099  3761  7113 I HwSystemManager: HsmIntentService:last work complete! lets stop service.
07-15 15:21:49.099  3761  3783 I HwSystemManager: NotificationDBProvider:call: method = notification_list_query
07-15 15:21:49.099  3761  3783 I HwSystemManager: NotificationDBProvider:query starts, uri = content://com.huawei.systemmanager.NotificationDBProvider/notificationCfg
07-15 15:21:49.099  3761  3783 I HwSystemManager: NotificationDBProvider:query starts, matchCode = 1
,07-15 15:21:49.099  6604  6604 I HwSystemManager: netAppDBHelper: DBHelper Create Database!  : SQLiteDatabase: /data/data/com.huawei.systemmanager/databases/net_permission.db
07-15 15:21:49.099  3249  3249 I PhoneStatusBar: notification pkg =com.android.settings
07-15 15:21:49.099  3249  3249 I PhoneStatusBar: notification provisioned=true, score =10, [score > HIDE_ICONS_BELOW_SCORE] =true, showNotificationEvenIfUnprovisioned = false
07-15 15:21:49.099  3249  3249 I PhoneStatusBar: notification pkg =android
07-15 15:21:49.099  3249  3249 I PhoneStatusBar: notification provisioned=true, score =-10, [score > HIDE_ICONS_BELOW_SCORE] =true, showNotificationEvenIfUnprovisioned = false
07-15 15:21:49.099  6604  6604 I HwSystemManager: NetAppListPrepareReceiver:in deleteUninstallAppFromDBAndIptables
07-15 15:21:49.099  6604  6604 I HwSystemManager: NetAppListPrepareReceiver:uid = 10072
07-15 15:21:49.099  6604  6604 I HwSystemManager: NetAppListPrepareReceiver:permissionCfg = 0
,07-15 15:21:49.099  6604  7114 I HwSystemManager: HsmPackageManager:get all installed packages, flag:0, size:148
07-15 15:21:49.099  6604  7114 E HwSystemManager: PermissionDBAdapter:appcationsList size:148
,07-15 15:21:49.099  3043  3082 I art     : Explicit concurrent mark sweep GC freed 23335(1741KB) AllocSpace objects, 3(60KB) LOS objects, 33% free, 28MB/42MB, paused 3.814ms total 299.325ms
,07-15 15:21:49.109  6604  7118 I HwSystemManager: NetAppListPrepareReceiver:deleteUninstallAppFromIptables thread has started
,07-15 15:21:49.109  6604  7118 I HwSystemManager: NetAppListPrepareReceiver:deleteUninstallAppFromIptables thread has terminated
,07-15 15:21:49.119  3761  7117 I HwSystemManager: ProtectAppService:send unprotect list broadcast,unprotect list:[com.gameloft.android.GloftPDMF, com.android.calculator2, com.huawei.android.ntp, com.huawei.android.Huaweiwear, com.android.hwmirror, com.zinio.android.settings, com.gameloft.android.GloftPZOR, com.zinio.mobile.android.reader, com.applift.huaweihub, com.android.email, com.huawei.phoneservice, com.android.providers.downloads, com.gameloft.android.GloftDBMF, com.hp.android.printservice, com.android.musicvis, com.android.exchange, com.todoist, com.huawei.android.thememanager, com.gameloft.android.GloftRF15, com.gameloft.android.GloftSMIM, com.android.browser, com.gameloft.android.GloftCRSM, com.example.hello, org.thaliproject.p2p.btconnectorlib.test]
,07-15 15:21:49.119  6604  6604 I HwSystemManager: DX-Optimizer:[PackageChangeReceiver] Received: android.intent.action.PACKAGE_REMOVED, data: package:com.test.thalitest, replacing: false
,07-15 15:21:49.129  6604  7120 I YhdsEngine: [EngineIntentService] Received: com.dianxinos.optimizer.engine.action.PKG_CHANGE
,07-15 15:21:49.129  6604  7121 I HwSystemManager: DX-Optimizer:[CommonIntentService] Received: com.dianxinos.optimizer.action.PKG_CHANGE
,07-15 15:21:49.139  6604  6604 I HwSystemManager: AppChangeReceiver:AppChangeReceiver:  onReceive(), action = android.intent.action.PACKAGE_REMOVED
,07-15 15:21:49.139  6604  7121 I TrashManager: EngineManager not initialed, please EngineManager#init()
,07-15 15:21:49.199  3761  3761 I HwSystemManager: HsmIntentService:destroyed. this:com.huawei.systemmanager.util.content.HsmIntentService_bg@29b393fa
07-15 15:21:49.199  6604  7114 I HwSystemManager: PermissionDBAdapter:DBAdapter refreshAllCachedData!
07-15 15:21:49.209  6604  7114 I HwSystemManager: PermissionDbVisitor:removeHistoryRecord,pkgName:com.test.thalitest, delete count:0
07-15 15:21:49.209  6604  7114 I HwSystemManager: HsmPackageManager:get all installed packages, flag:0, size:148
07-15 15:21:49.209  6604  7114 E HwSystemManager: PermissionDBAdapter:appcationsList size:148
,07-15 15:21:49.289  6604  7114 I HwSystemManager: PermissionDBAdapter:DBAdapter refreshAllCachedData!
,07-15 15:21:49.299  6604  7114 I HwSystemManager: HsmIntentService:task completed for intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.huawei.systemmanager/com.huawei.permissionmanager.ui.AppInstallationReceiver (has extras) }, action:android.intent.action.PACKAGE_REMOVED
07-15 15:21:49.299  6604  7114 I HwSystemManager: HsmIntentService:in thread:Thread[HsmIntentServiceTask #4,5,main], current active tasksize:1, queue size:0
07-15 15:21:49.299  6604  7114 I HwSystemManager: HsmIntentService:last work complete! lets stop service.
,07-15 15:21:49.509  6604  6604 I HwSystemManager: HsmIntentService:destroyed. this:com.huawei.systemmanager.util.content.HsmIntentService_ui@3e066760
,07-15 15:21:49.519  3761  4259 I HwSystemManager: HoldService:uid:10084 pid:6416 died
07-15 15:21:49.519  3761  4259 I HwSystemManager: HoldService:oldVersionKey:10084,6416
07-15 15:21:49.519  3761  4259 I HwSystemManager: BgPowerManagerService:onProcessDied uid = 10084
07-15 15:21:49.519  3043  3637 E HsmCoreServiceImpl: onTransact in code is: 102
07-15 15:21:49.519  3043  3637 I MediaProcessHandler: processOp opType: 1, uid: 10084, pid: 6416
07-15 15:21:49.519  3043  3637 W MediaProcessHandler: remove target not exist, maybe the UI process: uid: 10084, pid: 6416
,07-15 15:21:49.639  3043  3637 E HsmCoreServiceImpl: onTransact in code is: 102
07-15 15:21:49.639  3043  3637 I MediaProcessHandler: processOp opType: 1, uid: 10058, pid: 5970
07-15 15:21:49.639  3761  4084 I HwSystemManager: HoldService:uid:10058 pid:5970 died
07-15 15:21:49.639  3761  4259 I HwSystemManager: BgPowerManagerService:onProcessDied uid = 10058
07-15 15:21:49.639  3043  3637 W MediaProcessHandler: remove target not exist, maybe the UI process: uid: 10058, pid: 5970
07-15 15:21:49.639  3761  4084 I HwSystemManager: HoldService:oldVersionKey:10058,5970

```
