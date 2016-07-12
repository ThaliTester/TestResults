#### Test 72145431744cc2c_thali09_HUAWEI-ALE-L21 Logs


```
int logctl_get(): open '/dev/hwlog_switch' fail -1, 13. Permission denied

Note: log switch off, only log_main and log_events will have logs!
,--------- beginning of main
07-12 11:36:34.909  7181  7181 I appproc : CLASSPATH=/system/framework/am.jar
07-12 11:36:34.909  7181  7181 I appproc : Command=app_process /system/bin com.android.commands.am.Am start -n com.test.thalitest/com.test.thalitest.MainActivity 
07-12 11:36:34.909  7181  7181 I appproc : app_process:number,5,0
07-12 11:36:34.909  7181  7181 I AndroidRuntime: readDownloadBoosterConfig: 'false'
07-12 11:36:35.059  7181  7181 I         : power log dlsym ok
07-12 11:36:35.099  7181  7181 E android_hardware_fm.cpp: register_android_hardware_fm_fmradio
07-12 11:36:35.099  7181  7181 I android_hardware_fm.cpp: ========64bit long size = 8
07-12 11:36:35.099  7181  7181 E FM_HAL  : [FM_HAL], libname is libhisifm_if
07-12 11:36:35.099  7181  7181 I fm_hisi : FM::[fm_device_open:4655] fm_device_open
07-12 11:36:35.099  7181  7181 I fm_hisi : 
07-12 11:36:35.099  7181  7181 I fm_hisi : FM::[fm_device_open:4666] find the id:libhisifm_if and begins to open the device
07-12 11:36:35.099  7181  7181 I fm_hisi : 
07-12 11:36:35.099  7181  7181 I fm_hisi : FM::[fm_device_open:4710] device open sucess
07-12 11:36:35.099  7181  7181 I fm_hisi : 
07-12 11:36:35.099  7181  7181 E android_hardware_fm.cpp: register_android_hardware_fm_fmradio, ret is 0
07-12 11:36:35.149  3154  6534 I art     : Can not find class: Lcom/android/server/wm/WindowState$2;
07-12 11:36:35.149  3154  6534 I art     : Can not find class: Lcom/android/server/am/TaskPersister$TaskWriteQueueItem;
07-12 11:36:35.149  3154  6534 I art     : Can not find class: Lcom/android/server/am/TaskPersister$WriteQueueItem;
07-12 11:36:35.209  3154  3175 I art     : Can not find class: Lcom/android/server/am/ActivityStack$2;
07-12 11:36:35.219  3913  4262 W PhoneStateManager: screen off and not process front event:com.test.thalitest
07-12 11:36:35.229  4227  4251 I HwSystemManager: AppLockService:applock password not initial or function is closed
07-12 11:36:35.229  4227  4251 I HwSystemManager: AppLockService:applock password not initial or function is closed
07-12 11:36:35.229  4035  4035 I HwLauncher: Launcher  onWindowVisibilityChanged visibility = 8
07-12 11:36:35.229  4035  4035 I HwLauncher: DynamicIcon onWindowVisibilityChanged 8 - com.android.calendar
07-12 11:36:35.229  4035  4035 I HwLauncher: DynamicIcon onWindowVisibilityChanged 8 - com.android.deskclock
07-12 11:36:35.229  4227  4472 I HwSystemManager: AppManager:getNetAppInfoFromDB cursor lenth = 1
07-12 11:36:35.239  4035  4035 I HwLauncher: DynamicIcon onVisibilityChanged 4 - com.android.calendar
07-12 11:36:35.239  4035  4035 I HwLauncher: DynamicIcon onVisibilityChanged 4 - com.android.deskclock
07-12 11:36:35.379  7201  7201 I WebViewFactory: Loading com.android.webview version 37 (eng.jenkins-arm64) (code 199992)
,07-12 11:36:35.399  7201  7201 I LibraryLoader: Loading: webviewchromium
07-12 11:36:35.459  7201  7201 I LibraryLoader: Time to load native libraries: 56 ms (timestamps 17-73)
07-12 11:36:35.459  7201  7201 I LibraryLoader: Expected native library version number "",actual native library version number ""
07-12 11:36:35.509  7201  7201 E ZipFileCache: init failed when open zip file.
07-12 11:36:35.509  7201  7201 E ZipFileCache: init failed when open zip file.
07-12 11:36:35.509  7201  7201 E ZipFileCache: init failed when open zip file.
07-12 11:36:35.519  7201  7201 E ZipFileCache: init failed when open zip file.
07-12 11:36:35.529  7201  7201 I LibraryLoader: Expected native library version number "",actual native library version number ""
07-12 11:36:35.529  7201  7201 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
07-12 11:36:35.539  7201  7201 I BrowserStartupController: Initializing chromium process, renderers=0
07-12 11:36:35.549  7201  7201 W art     : Attempt to remove local handle scope entry from IRT, ignoring
07-12 11:36:35.569  7201  7229 W chromium: [WARNING:dns_config_service_posix.cc(293)] Failed to read DnsConfig.
07-12 11:36:35.599  7201  7201 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
07-12 11:36:35.599  7201  7201 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=37 off=46092 len=2953
07-12 11:36:35.599  7201  7201 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:38 off:228796 len:643667
07-12 11:36:35.769  7201  7239 W chromium: [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
07-12 11:36:35.769  7201  7201 W chromium: [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
07-12 11:36:35.779  7201  7239 W chromium: [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
07-12 11:36:35.819  7201  7201 E ZipFileCache: init failed when open zip file.
07-12 11:36:35.819  7201  7201 E ZipFileCache: init failed when open zip file.
07-12 11:36:35.829  7201  7201 E ZipFileCache: init failed when open zip file.
07-12 11:36:35.829  7201  7201 E ZipFileCache: init failed when open zip file.
07-12 11:36:35.839  7201  7201 E ZipFileCache: init failed when open zip file.
07-12 11:36:35.839  7201  7201 E ZipFileCache: init failed when open zip file.
07-12 11:36:35.839  7201  7201 E ZipFileCache: init failed when open zip file.
07-12 11:36:35.839  7201  7201 E ZipFileCache: init failed when open zip file.
07-12 11:36:35.839  7201  7201 E ZipFileCache: init failed when open zip file.
07-12 11:36:35.839  7201  7201 E ZipFileCache: init failed when open zip file.
07-12 11:36:35.849  7201  7201 E ZipFileCache: init failed when open zip file.
07-12 11:36:35.849  7201  7201 E ZipFileCache: init failed when open zip file.
07-12 11:36:35.859  7201  7201 E ZipFileCache: init failed when open zip file.
07-12 11:36:35.859  7201  7201 E ZipFileCache: init failed when open zip file.
07-12 11:36:35.859  7201  7201 E ZipFileCache: init failed when open zip file.
07-12 11:36:35.859  7201  7201 E ZipFileCache: init failed when open zip file.
07-12 11:36:35.869  7201  7201 E ZipFileCache: init failed when open zip file.
07-12 11:36:35.869  7201  7201 E ZipFileCache: init failed when open zip file.
07-12 11:36:35.869  7201  7201 E ZipFileCache: init failed when open zip file.
07-12 11:36:35.869  7201  7201 E ZipFileCache: init failed when open zip file.
07-12 11:36:35.869  7201  7201 E ZipFileCache: init failed when open zip file.
07-12 11:36:35.879  7201  7201 E ZipFileCache: init failed when open zip file.
07-12 11:36:35.879  7201  7201 E ZipFileCache: init failed when open zip file.
07-12 11:36:35.879  7201  7201 E ZipFileCache: init failed when open zip file.
07-12 11:36:35.879  7201  7201 E ZipFileCache: init failed when open zip file.
07-12 11:36:35.879  7201  7201 E ZipFileCache: init failed when open zip file.
07-12 11:36:35.889  7201  7201 E ZipFileCache: init failed when open zip file.
07-12 11:36:35.889  7201  7201 E ZipFileCache: init failed when open zip file.
07-12 11:36:35.889  7201  7201 E ZipFileCache: init failed when open zip file.
07-12 11:36:35.889  7201  7201 E ZipFileCache: init failed when open zip file.
07-12 11:36:35.889  7201  7201 E ZipFileCache: init failed when open zip file.
07-12 11:36:35.889  7201  7201 E ZipFileCache: init failed when open zip file.
07-12 11:36:35.899  7201  7201 E ZipFileCache: init failed when open zip file.
07-12 11:36:35.899  7201  7201 E ZipFileCache: init failed when open zip file.
07-12 11:36:35.899  7201  7201 E ZipFileCache: init failed when open zip file.
07-12 11:36:35.899  7201  7201 E ZipFileCache: init failed when open zip file.
07-12 11:36:35.899  7201  7201 E ZipFileCache: init failed when open zip file.
07-12 11:36:35.909  7201  7201 E ZipFileCache: init failed when open zip file.
07-12 11:36:35.909  7201  7201 E ZipFileCache: init failed when open zip file.
07-12 11:36:35.909  7201  7201 E ZipFileCache: init failed when open zip file.
07-12 11:36:35.909  7201  7201 E ZipFileCache: init failed when open zip file.
07-12 11:36:35.909  7201  7201 E ZipFileCache: init failed when open zip file.
07-12 11:36:35.919  7201  7201 E ZipFileCache: init failed when open zip file.
07-12 11:36:35.919  7201  7201 E ZipFileCache: init failed when open zip file.
07-12 11:36:35.919  7201  7201 E ZipFileCache: init failed when open zip file.
07-12 11:36:35.919  7201  7201 E ZipFileCache: init failed when open zip file.
07-12 11:36:35.919  7201  7201 E ZipFileCache: init failed when open zip file.
07-12 11:36:35.919  7201  7201 E ZipFileCache: init failed when open zip file.
07-12 11:36:35.919  7201  7201 E ZipFileCache: init failed when open zip file.
07-12 11:36:35.919  7201  7201 E ZipFileCache: init failed when open zip file.
07-12 11:36:35.919  7201  7201 E ZipFileCache: init failed when open zip file.
07-12 11:36:35.919  7201  7201 E ZipFileCache: init failed when open zip file.
07-12 11:36:35.929  7201  7201 E ZipFileCache: init failed when open zip file.
07-12 11:36:35.929  7201  7201 E ZipFileCache: init failed when open zip file.
07-12 11:36:35.929  7201  7201 E ZipFileCache: init failed when open zip file.
07-12 11:36:35.929  7201  7201 E ZipFileCache: init failed when open zip file.
07-12 11:36:35.929  7201  7201 E ZipFileCache: init failed when open zip file.
07-12 11:36:35.929  7201  7201 E ZipFileCache: init failed when open zip file.
07-12 11:36:35.929  7201  7201 E ZipFileCache: init failed when open zip file.
07-12 11:36:35.929  7201  7201 E ZipFileCache: init failed when open zip file.
07-12 11:36:35.929  7201  7201 E ZipFileCache: init failed when open zip file.
07-12 11:36:35.929  7201  7201 E ZipFileCache: init failed when open zip file.
07-12 11:36:35.929  7201  7201 E ZipFileCache: init failed when open zip file.
07-12 11:36:35.929  7201  7201 E ZipFileCache: init failed when open zip file.
07-12 11:36:35.929  7201  7201 E ZipFileCache: init failed when open zip file.
07-12 11:36:35.929  7201  7201 E ZipFileCache: init failed when open zip file.
07-12 11:36:35.929  7201  7201 E ZipFileCache: init failed when open zip file.
07-12 11:36:35.929  7201  7201 E ZipFileCache: init failed when open zip file.
07-12 11:36:35.929  7201  7201 E ZipFileCache: init failed when open zip file.
07-12 11:36:35.929  7201  7201 E ZipFileCache: init failed when open zip file.
07-12 11:36:35.929  7201  7201 E ZipFileCache: init failed when open zip file.
07-12 11:36:35.929  7201  7201 E ZipFileCache: init failed when open zip file.
07-12 11:36:35.929  7201  7201 E ZipFileCache: init failed when open zip file.
07-12 11:36:35.929  7201  7201 E ZipFileCache: init failed when open zip file.
07-12 11:36:35.939  7201  7201 E ZipFileCache: init failed when open zip file.
07-12 11:36:35.939  7201  7201 E ZipFileCache: init failed when open zip file.
07-12 11:36:35.939  7201  7201 E ZipFileCache: init failed when open zip file.
07-12 11:36:35.939  7201  7201 E ZipFileCache: init failed when open zip file.
07-12 11:36:35.939  7201  7201 E ZipFileCache: init failed when open zip file.
07-12 11:36:35.939  7201  7201 E ZipFileCache: init failed when open zip file.
07-12 11:36:35.939  7201  7201 E ZipFileCache: init failed when open zip file.
07-12 11:36:35.939  7201  7201 E ZipFileCache: init failed when open zip file.
07-12 11:36:35.939  7201  7201 E ZipFileCache: init failed when open zip file.
07-12 11:36:35.939  7201  7201 E ZipFileCache: init failed when open zip file.
07-12 11:36:35.949  7201  7201 E ZipFileCache: init failed when open zip file.
07-12 11:36:35.949  7201  7201 E ZipFileCache: init failed when open zip file.
07-12 11:36:35.949  7201  7201 E ZipFileCache: init failed when open zip file.
07-12 11:36:35.949  7201  7201 E ZipFileCache: init failed when open zip file.
07-12 11:36:35.949  7201  7201 E ZipFileCache: init failed when open zip file.
07-12 11:36:35.949  7201  7201 E ZipFileCache: init failed when open zip file.
07-12 11:36:35.959  7201  7201 E ZipFileCache: init failed when open zip file.
07-12 11:36:35.959  7201  7201 E ZipFileCache: init failed when open zip file.
07-12 11:36:35.959  7201  7201 E ZipFileCache: init failed when open zip file.
07-12 11:36:35.959  7201  7201 E ZipFileCache: init failed when open zip file.
07-12 11:36:35.959  7201  7201 E ZipFileCache: init failed when open zip file.
07-12 11:36:35.959  7201  7201 E ZipFileCache: init failed when open zip file.
07-12 11:36:35.969  7201  7201 E ZipFileCache: init failed when open zip file.
07-12 11:36:35.969  7201  7201 E ZipFileCache: init failed when open zip file.
07-12 11:36:35.969  7201  7201 E ZipFileCache: init failed when open zip file.
07-12 11:36:35.969  7201  7201 E ZipFileCache: init failed when open zip file.
07-12 11:36:35.969  7201  7201 E ZipFileCache: init failed when open zip file.
07-12 11:36:35.969  7201  7201 E ZipFileCache: init failed when open zip file.
07-12 11:36:35.979  7201  7201 E ZipFileCache: init failed when open zip file.
07-12 11:36:35.979  7201  7201 E ZipFileCache: init failed when open zip file.
07-12 11:36:35.979  7201  7201 E ZipFileCache: init failed when open zip file.
07-12 11:36:35.979  7201  7201 E ZipFileCache: init failed when open zip file.
07-12 11:36:35.979  7201  7201 E ZipFileCache: init failed when open zip file.
07-12 11:36:35.989  7201  7201 E ZipFileCache: init failed when open zip file.
07-12 11:36:35.989  7201  7201 E ZipFileCache: init failed when open zip file.
07-12 11:36:35.989  7201  7201 E ZipFileCache: init failed when open zip file.
07-12 11:36:35.989  7201  7201 E ZipFileCache: init failed when open zip file.
07-12 11:36:35.989  7201  7201 E ZipFileCache: init failed when open zip file.
07-12 11:36:35.999  7201  7201 E ZipFileCache: init failed when open zip file.
07-12 11:36:35.999  7201  7201 E ZipFileCache: init failed when open zip file.
07-12 11:36:35.999  7201  7201 E ZipFileCache: init failed when open zip file.
07-12 11:36:35.999  7201  7201 E ZipFileCache: init failed when open zip file.
07-12 11:36:35.999  7201  7201 E ZipFileCache: init failed when open zip file.
07-12 11:36:35.999  7201  7201 E ZipFileCache: init failed when open zip file.
07-12 11:36:36.009  7201  7201 E ZipFileCache: init failed when open zip file.
07-12 11:36:36.009  7201  7201 E ZipFileCache: init failed when open zip file.
07-12 11:36:36.009  7201  7201 E ZipFileCache: init failed when open zip file.
07-12 11:36:36.009  7201  7201 E ZipFileCache: init failed when open zip file.
07-12 11:36:36.009  7201  7201 E ZipFileCache: init failed when open zip file.
07-12 11:36:36.009  7201  7201 E ZipFileCache: init failed when open zip file.
07-12 11:36:36.009  7201  7201 E ZipFileCache: init failed when open zip file.
07-12 11:36:36.009  7201  7201 E ZipFileCache: init failed when open zip file.
07-12 11:36:36.009  7201  7201 E ZipFileCache: init failed when open zip file.
07-12 11:36:36.019  7201  7201 E ZipFileCache: init failed when open zip file.
07-12 11:36:36.019  7201  7201 E ZipFileCache: init failed when open zip file.
07-12 11:36:36.019  7201  7201 E ZipFileCache: init failed when open zip file.
07-12 11:36:36.019  7201  7201 E ZipFileCache: init failed when open zip file.
07-12 11:36:36.019  7201  7201 E ZipFileCache: init failed when open zip file.
07-12 11:36:36.019  7201  7201 E ZipFileCache: init failed when open zip file.
07-12 11:36:36.019  7201  7201 E ZipFileCache: init failed when open zip file.
07-12 11:36:36.019  7201  7201 E ZipFileCache: init failed when open zip file.
07-12 11:36:36.019  7201  7201 E ZipFileCache: init failed when open zip file.
07-12 11:36:36.019  7201  7201 E ZipFileCache: init failed when open zip file.
07-12 11:36:36.019  7201  7201 E ZipFileCache: init failed when open zip file.
07-12 11:36:36.019  7201  7201 E ZipFileCache: init failed when open zip file.
07-12 11:36:36.019  7201  7201 E ZipFileCache: init failed when open zip file.
07-12 11:36:36.019  7201  7201 E ZipFileCache: init failed when open zip file.
07-12 11:36:36.019  7201  7201 E ZipFileCache: init failed when open zip file.
07-12 11:36:36.019  7201  7201 E ZipFileCache: init failed when open zip file.
07-12 11:36:36.019  7201  7201 E ZipFileCache: init failed when open zip file.
07-12 11:36:36.019  7201  7201 E ZipFileCache: init failed when open zip file.
07-12 11:36:36.019  7201  7201 E ZipFileCache: init failed when open zip file.
07-12 11:36:36.019  7201  7201 E ZipFileCache: init failed when open zip file.
07-12 11:36:36.019  7201  7201 E ZipFileCache: init failed when open zip file.
07-12 11:36:36.019  7201  7201 E ZipFileCache: init failed when open zip file.
07-12 11:36:36.029  7201  7201 E ZipFileCache: init failed when open zip file.
07-12 11:36:36.029  7201  7201 E ZipFileCache: init failed when open zip file.
07-12 11:36:36.029  7201  7201 E ZipFileCache: init failed when open zip file.
07-12 11:36:36.029  7201  7201 E ZipFileCache: init failed when open zip file.
07-12 11:36:36.029  7201  7201 E ZipFileCache: init failed when open zip file.
07-12 11:36:36.029  7201  7201 E ZipFileCache: init failed when open zip file.
07-12 11:36:36.029  7201  7201 E ZipFileCache: init failed when open zip file.
07-12 11:36:36.029  7201  7201 W art     : Attempt to remove local handle scope entry from IRT, ignoring
07-12 11:36:36.029  7201  7201 W AwContents: onDetachedFromWindow called when already detached. Ignoring
07-12 11:36:36.039  7201  7201 I art     : Can not find class: Landroid/widget/ViewStub;
07-12 11:36:36.039  7201  7201 I art     : Can not find class: Landroid/webkit/ViewStub;
07-12 11:36:36.039  7201  7201 I art     : Can not find class: Landroid/app/ViewStub;
07-12 11:36:36.059  7201  7201 W art     : Attempt to remove local handle scope entry from IRT, ignoring
07-12 11:36:36.059  7201  7201 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,07-12 11:36:36.289  3694  3694 I PhoneStatusBar: hw_status_bar_operators = true, setSystemUIVisibily(SHOW_OPERATOR = false)
,07-12 11:36:36.299  3694  3694 I PhoneStatusBar: shouldTranslucent:true
,07-12 11:36:36.299  3694  3694 I PhoneStatusBar: hw_status_bar_operators = true, setSystemUIVisibily(SHOW_OPERATOR = false)
,07-12 11:36:36.339  7201  7257 I OpenGLRenderer: Initialized EGL, version 1.4
,07-12 11:36:36.389  7201  7201 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
07-12 11:36:36.389  3154  3215 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +1s168ms (total +1s238ms)
,07-12 11:36:36.499  7201  7201 I chromium: [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
07-12 11:36:36.499  7201  7201 I chromium: 
,07-12 11:36:36.659  7201  7268 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 58:2A:F7:ED:96:BE
,07-12 11:36:36.669  7201  7268 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
,07-12 11:36:36.669  7201  7268 W org.thaliproject.p2p.btconnectorlib.DiscoveryManager: isBleMultipleAdvertisementSupported: Bluetooth is not enabled so we could not check whether or not BluetoothLE multi advertisement is supported. However, Bluetooth LE is supported so we just *assume* multi advertisement is supported too (which may not always be the case).
,07-12 11:36:36.679  7201  7268 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
07-12 11:36:36.679  7201  7268 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 1 -> 2
07-12 11:36:36.679  7201  7268 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 2 -> 3
07-12 11:36:36.679  7201  7268 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 1 -> 2
,07-12 11:36:36.679  7201  7268 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,07-12 11:36:36.679  7201  7268 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 58:2A:F7:ED:96:BE
,07-12 11:36:36.679  7201  7268 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
,07-12 11:36:36.679  7201  7268 I io.jxcore.node.LifeCycleMonitor: start: OK
,07-12 11:36:36.709  7201  7201 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,07-12 11:36:37.149  7201  7271 W jxcore-log: Initializing JXcore engine
07-12 11:36:37.149  7201  7271 W jxcore-log: JXcore engine is ready
,07-12 11:36:37.219  7201  7271 W jxcore-log: Starting JXcore engine
,07-12 11:36:37.319  7201  7271 W jxcore-log: Platform android
07-12 11:36:37.319  7201  7271 W jxcore-log: 
07-12 11:36:37.319  7201  7271 W jxcore-log: Process ARCH arm
07-12 11:36:37.319  7201  7271 W jxcore-log: 
,07-12 11:36:37.539  7201  7271 I jxcore-log: JXcore Cordova bridge is ready!
07-12 11:36:37.539  7201  7271 I jxcore-log: 
,07-12 11:36:37.539  7201  7271 W jxcore-log: JXcore engine is started
,07-12 11:36:37.549  7201  7268 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,07-12 11:36:37.549  7201  7201 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,07-12 11:36:37.559  7201  7271 E jxcore  : Error!: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js
07-12 11:36:37.559  7201  7271 E jxcore  : Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,07-12 11:36:37.559  7201  7201 I chromium: [INFO:CONSOLE(57)] "App.js file failed to load : "No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\nError: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\n    at $h.require@node.js:1472:1\n    at internal_methods.loadMainFile@main.js.js:260:5\n    at JXMobile.executeJSON@main.js.js:279:7\n    at @JX_Evaluate:1:1\n"", source: file:///android_asset/www/js/thali_main.js (57)
07-12 11:36:37.559  7201  7201 I chromium: [INFO:CONSOLE(62)] "****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****", source: file:///android_asset/www/js/thali_main.js (62)
,07-12 11:36:37.779  4227  4251 I HwSystemManager: AppLockService:applock password not initial or function is closed
07-12 11:36:37.789  4227  4251 I HwSystemManager: AppLockService:applock password not initial or function is closed
07-12 11:36:37.789  4227  4624 I HwSystemManager: BgPowerManagerService:onProcessDied uid = 10084
07-12 11:36:37.789  4227  4624 I HwSystemManager: HoldService:uid:10084 pid:6687 died
07-12 11:36:37.789  4227  4624 I HwSystemManager: HoldService:oldVersionKey:10084,6687
,07-12 11:36:37.789  3154  3175 E HsmCoreServiceImpl: onTransact in code is: 102
07-12 11:36:37.789  3154  3175 I MediaProcessHandler: processOp opType: 1, uid: 10084, pid: 6687
07-12 11:36:37.789  3154  3175 W MediaProcessHandler: remove target not exist, maybe the UI process: uid: 10084, pid: 6687
07-12 11:36:37.789  7201  7268 W PluginManager: THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 223ms. Plugin should use CordovaInterface.getThreadPool().
07-12 11:36:37.789  7201  7201 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-12 11:36:37.789  7201  7201 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-12 11:36:37.789  7201  7201 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-12 11:36:37.789  7201  7201 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-12 11:36:37.789  7201  7201 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
07-12 11:36:37.789  4227  4472 I HwSystemManager: AppManager:getNetAppInfoFromDB cursor lenth = 1
,07-12 11:36:37.789  7201  7201 I io.jxcore.node.LifeCycleMonitor: stop: OK
,07-12 11:36:37.799  7201  7201 W ScreenOrientationListener: Removing an inexistent observer!
,07-12 11:36:37.849  7273  7273 I appproc : CLASSPATH=/system/framework/pm.jar
07-12 11:36:37.849  7273  7273 I appproc : Command=app_process /system/bin com.android.commands.pm.Pm uninstall com.test.thalitest 
07-12 11:36:37.849  7273  7273 I appproc : app_process:number,4,0
,07-12 11:36:37.849  7273  7273 I AndroidRuntime: readDownloadBoosterConfig: 'false'
,07-12 11:36:37.989  7273  7273 I         : power log dlsym ok
,07-12 11:36:38.029  7273  7273 E android_hardware_fm.cpp: register_android_hardware_fm_fmradio
07-12 11:36:38.029  7273  7273 I android_hardware_fm.cpp: ========64bit long size = 8
07-12 11:36:38.029  7273  7273 E FM_HAL  : [FM_HAL], libname is libhisifm_if
,07-12 11:36:38.029  7273  7273 I fm_hisi : FM::[fm_device_open:4655] fm_device_open
07-12 11:36:38.029  7273  7273 I fm_hisi : 
07-12 11:36:38.029  7273  7273 I fm_hisi : FM::[fm_device_open:4666] find the id:libhisifm_if and begins to open the device
07-12 11:36:38.029  7273  7273 I fm_hisi : 
07-12 11:36:38.029  7273  7273 I fm_hisi : FM::[fm_device_open:4710] device open sucess
07-12 11:36:38.029  7273  7273 I fm_hisi : 
07-12 11:36:38.029  7273  7273 E android_hardware_fm.cpp: register_android_hardware_fm_fmradio, ret is 0
,07-12 11:36:38.069  3154  6534 I art     : Can not find class: Lcom/android/server/pm/PackageInstallerService$PackageDeleteObserverAdapter;
,07-12 11:36:38.079  3154  6534 I art     : Can not find class: Lcom/android/server/pm/PackageManagerService$9;
,07-12 11:36:38.149  3154  3622 I art     : Can not find class: Lcom/android/server/am/TaskPersister$ImageWriteQueueItem;
,07-12 11:36:38.189  4227  4251 I HwSystemManager: HoldService:uid:10072 pid:7201 died
07-12 11:36:38.189  4227  4315 I HwSystemManager: BgPowerManagerService:onProcessDied uid = 10072
07-12 11:36:38.189  4227  4251 I HwSystemManager: HoldService:oldVersionKey:10072,7201
07-12 11:36:38.189  3154  4060 E HsmCoreServiceImpl: onTransact in code is: 102
07-12 11:36:38.189  3154  4060 I MediaProcessHandler: processOp opType: 1, uid: 10072, pid: 7201
07-12 11:36:38.189  3154  4060 W MediaProcessHandler: remove target not exist, maybe the UI process: uid: 10072, pid: 7201
,07-12 11:36:38.239  3154  3230 I ActivityManager: filter receiver for action = android.intent.action.PACKAGE_REMOVED
,07-12 11:36:38.259  4227  4227 I art     : Explicit concurrent mark sweep GC freed 95407(6MB) AllocSpace objects, 27(432KB) LOS objects, 40% free, 14MB/23MB, paused 1.141ms total 61.980ms
,07-12 11:36:38.259  4227  4227 I HwSystemManager: HsmPackageManager:Receive intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
07-12 11:36:38.259  4227  4227 I HwSystemManager: HsmPackageManager:replacing:false
07-12 11:36:38.259  4227  4227 I HwSystemManager: HsmPackageManager:pkgName:com.test.thalitest
,07-12 11:36:38.259  4227  4227 I HwSystemManager: HsmPackageManager:doAppRemoved, remove:com.test.thalitest
,07-12 11:36:38.269  4227  4227 I HwSystemManager: ww:deleteLockData:com.test.thalitest
,07-12 11:36:38.269  3154  3563 I InputReader: Reconfiguring input devices.  changes=0x00000010
,07-12 11:36:38.279  6650  6791 I AccountTypeManager: Adding account type = com.android.contacts.model.account.ExchangeAccountType@19dd5052 in the cache
,07-12 11:36:38.279  6650  6791 I SimFactoryManager: Get SIM state from SIM factory manager: 1,For slotId:0
,07-12 11:36:38.279  3886  4322 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,07-12 11:36:38.289  6830  6830 I art     : Explicit concurrent mark sweep GC freed 31168(2MB) AllocSpace objects, 10(160KB) LOS objects, 25% free, 13MB/18MB, paused 13.165ms total 80.030ms
,07-12 11:36:38.289  6830  6830 I HwSystemManager: HsmPackageManager:Receive intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,07-12 11:36:38.289  6830  6830 I HwSystemManager: HsmPackageManager:replacing:false
,07-12 11:36:38.289  6830  6830 I HwSystemManager: HsmPackageManager:pkgName:com.test.thalitest
07-12 11:36:38.289  6830  6830 I HwSystemManager: HsmPackageManager:doAppRemoved, remove:com.test.thalitest
,07-12 11:36:38.289  6650  6791 I SimFactoryManager: Get SIM state from SIM factory manager: 1,For slotId:1
,07-12 11:36:38.289  3965  3965 E RegisteredServicesCache: invalidateCache set mNeedToastTableFull
07-12 11:36:38.299  6650  6791 I AccountTypeManager: Adding account type = com.android.contacts.model.account.ExternalAccountType@23205f23 in the cache
,07-12 11:36:38.319  6650  6791 W ResourceType: For resource 0x7f020947, entry index(2375) is beyond type entryCount(769)
,07-12 11:36:38.319  6650  6791 W ResourceType: Failure getting entry for 0x7f020947 (t=1 e=2375) (error -75)
,07-12 11:36:38.319  6650  6791 W ResourceType: For resource 0x7f0209a3, entry index(2467) is beyond type entryCount(769)
07-12 11:36:38.319  6650  6791 W ResourceType: Failure getting entry for 0x7f0209a3 (t=1 e=2467) (error -75)
,07-12 11:36:38.319  6650  6791 I AccountTypeManager: Adding account type = com.android.contacts.model.account.ExternalAccountType@9d75c20 in the cache
,07-12 11:36:38.319  6650  6791 I AccountTypeManager: Adding account type = com.android.contacts.model.account.GoogleAccountType@2f8429d9 in the cache
,07-12 11:36:38.329  6650  6791 E ExternalAccountType: Unsupported attribute readOnly
,07-12 11:36:38.329  6650  6791 I AccountTypeManager: AccountManager, account size is: 2
,07-12 11:36:38.339  6650  6791 I AccountTypeManager: Loaded meta-data for 5 account types, 3 accounts in 73ms(wall) 20ms(cpu)
,07-12 11:36:38.339  3154  3230 I ActivityManager: filter receiver for action = android.intent.action.PACKAGE_FULLY_REMOVED
,07-12 11:36:38.349  3154  3230 I ActivityManager: filter receiver for action = android.intent.action.UID_REMOVED
,07-12 11:36:38.349  3154  3568 I art     : Can not find class: Lcom/android/server/net/NetworkStatsRecorder$RemoveUidRewriter;
,07-12 11:36:38.369  4227  4349 I HwSystemManager: aor:Network Stats Updated
07-12 11:36:38.369  4227  4349 I HwSystemManager: aoi:onNetworkStatsUpdated
,07-12 11:36:38.369  4227  4351 I HwSystemManager: TrafficAnalyseManager:mDataServiceStatusCard1 : false mDataServiceStatusCard2 : false
07-12 11:36:38.369  6456  6456 I art     : Explicit concurrent mark sweep GC freed 16712(1374KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 15MB/21MB, paused 1.701ms total 171.922ms
,07-12 11:36:38.379  4227  4351 E HwSystemManager: getSimCardType:/getSimCardInfo: imsi is null
,07-12 11:36:38.379  4227  4351 E HwSystemManager: getSimCardType:/getSimCardInfo: imsi is null
07-12 11:36:38.379  4227  4351 E HwSystemManager: getSimCardType:/getPhoneSimCardInfo: boths card not recongnized
07-12 11:36:38.379  4227  4351 W HwSystemManager: TrafficAnalyseManager:initCardStatus: preferredCardInfo is null.
,07-12 11:36:38.379  4227  4351 E HwSystemManager: TrafficNotifyOverMarkForDay:notifyTafficOverMarkForDay: imsi is null.
07-12 11:36:38.379  4227  4351 I HwSystemManager: TrafficAnalyseManager:mDataServiceStatusCard1 : false mDataServiceStatusCard2 : false
,07-12 11:36:38.379  4035  4035 I art     : Explicit concurrent mark sweep GC freed 64882(3MB) AllocSpace objects, 121(12MB) LOS objects, 38% free, 25MB/41MB, paused 1.217ms total 183.744ms
07-12 11:36:38.379  4035  4035 I HwLauncher: Model  onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
07-12 11:36:38.379  4035  4035 I HwLauncher: Model replacing = false package = com.test.thalitest
07-12 11:36:38.379  4035  4035 I HwLauncher: Model  ACTION_PACKAGE_REMOVED replacing = false
07-12 11:36:38.379  4035  4035 I HwLauncher: MutilSelectedIconsonPreHandleUpdatedTask : mIsInMutilSelectMode = false task = 3 packages = [com.test.thalitest]
07-12 11:36:38.379  4035  4035 I HwLauncher: SimpleLauncherModeaction= android.intent.action.PACKAGE_REMOVEDpackageName = com.test.thalitest
,07-12 11:36:38.389  4035  4168 I HwLauncher: SimpleLauncherModedeleteBadgeItemFromDBByPkg packageName=com.test.thalitest
,07-12 11:36:38.389  4227  4351 E HwSystemManager: getSimCardType:/getSimCardInfo: imsi is null
,07-12 11:36:38.389  4227  4351 E HwSystemManager: getSimCardType:/getSimCardInfo: imsi is null
07-12 11:36:38.389  4227  4351 E HwSystemManager: getSimCardType:/getPhoneSimCardInfo: boths card not recongnized
07-12 11:36:38.389  4227  4351 W HwSystemManager: TrafficAnalyseManager:initCardStatus: preferredCardInfo is null.
,07-12 11:36:38.389  4227  4351 E HwSystemManager: TrafficNotifyOverMarkForMonth:notifyTafficOverMarkForMonth: imsi is null.
07-12 11:36:38.389  4227  4351 I HwSystemManager: TrafficAnalyseManager:mDataServiceStatusCard1 : false mDataServiceStatusCard2 : false
,07-12 11:36:38.399  4227  4351 E HwSystemManager: getSimCardType:/getSimCardInfo: imsi is null
,07-12 11:36:38.399  4035  4168 I HwLauncher: Launcher.LauncherProvider  only HwLauncher can use LauncherProvider's delete method to delete badge table item 
07-12 11:36:38.399  4035  4168 I HwLauncher: SimpleAllAppsList   add packageName into uninstalledSDApps 
07-12 11:36:38.399  4035  4168 I HwLauncher: SimpleLauncherModeuninstalledSDApps size > 0
07-12 11:36:38.399  4035  4168 W HwLauncher: SimpleLauncherModeNobody to tell about the new app.  Launcher is probably loading.
07-12 11:36:38.399  4035  4168 I HwLauncher: SimpleLauncherModeOP_REMOVE callback is null, delete simpleUI database record
07-12 11:36:38.399  4035  4167 I HwLauncher: Model mAllAppsList.removePackage com.test.thalitest
,07-12 11:36:38.399  6059  6059 I art     : Explicit concurrent mark sweep GC freed 1507(69KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 22MB/29MB, paused 2.140ms total 204.530ms
,07-12 11:36:38.399  4227  4351 E HwSystemManager: getSimCardType:/getSimCardInfo: imsi is null
07-12 11:36:38.399  4227  4351 E HwSystemManager: getSimCardType:/getPhoneSimCardInfo: boths card not recongnized
07-12 11:36:38.399  4227  4351 W HwSystemManager: TrafficAnalyseManager:initCardStatus: preferredCardInfo is null.
,07-12 11:36:38.409  4227  4351 E HwSystemManager: TrafficNotifyExcessForMonth:notifyTafficExcessForMonth: imsi is null.
,07-12 11:36:38.419  4035  4035 I HwLauncher: Launcher  onWindowVisibilityChanged visibility = 4
,07-12 11:36:38.419  4035  4035 I HwLauncher: DynamicIcon onWindowVisibilityChanged 4 - com.android.calendar
07-12 11:36:38.419  4035  4035 I HwLauncher: DynamicIcon onWindowVisibilityChanged 4 - com.android.deskclock
,07-12 11:36:38.429  4035  4035 E HideAppsPagedView: removeItems begin 
07-12 11:36:38.429  4035  4035 E HideAppsPagedView: ShortcutInfo(title=ThaliTest)
07-12 11:36:38.429  4035  4035 E HideAppsPagedView: removeItems end 
,07-12 11:36:38.429  4035  4035 I HwLauncher: Launcher onStart()
07-12 11:36:38.429  4035  4035 I HwLauncher: Launcher dynamicIconsRegister
07-12 11:36:38.429  4035  4035 I HwLauncher: DynamicUpdater registerReceiver
,07-12 11:36:38.429  4035  4035 I HwLauncher: DynamicUpdater call updateFolder
,07-12 11:36:38.429  4035  4035 I HwLauncher: DynamicIcon onResume  isvisible = false   mAttachedToWindow:true    mWindowVisible:falsecom.android.calendar
,07-12 11:36:38.429  4035  4035 I HwLauncher: DynamicUpdater registerReceiver
,07-12 11:36:38.439  4035  4035 I HwLauncher: DynamicUpdater call updateFolder
07-12 11:36:38.439  4035  4035 I HwLauncher: DynamicIcon onResume  isvisible = false   mAttachedToWindow:true    mWindowVisible:falsecom.android.deskclock
,07-12 11:36:38.439  4035  4035 I HwLauncher: DynamicUpdater registerReceiver
07-12 11:36:38.439  4035  4167 I HwLauncher: DynamicIconData , getDrawableForDynamic begin, pkg = com.android.deskclock, picName = deskclock_bg
,07-12 11:36:38.439  4035  4167 I HwLauncher: DynamicIconData , getDrawableForDynamic end, pkg = com.android.deskclock, picName = deskclock_bg
,07-12 11:36:38.439  4035  4167 I HwLauncher: DynamicIconData , getDrawableForDynamic begin, pkg = com.android.deskclock, picName = deskclock_bg
07-12 11:36:38.439  4035  4167 I HwLauncher: DynamicIconData , getDrawableForDynamic end, pkg = com.android.deskclock, picName = deskclock_bg
07-12 11:36:38.439  4035  4035 I HwLauncher: DynamicUpdater call updateFolder
07-12 11:36:38.439  4035  4035 I HwLauncher: DynamicIcon onResume  isvisible = true   mAttachedToWindow:false    mWindowVisible:falsecom.huawei.android.totemweather
07-12 11:36:38.439  4035  4035 I HwLauncher: DynamicIcon onVisibilityChanged 0 - com.android.calendar
07-12 11:36:38.439  4035  4035 I HwLauncher: DynamicIcon onVisibilityChanged 0 - com.android.deskclock
,07-12 11:36:38.439  4035  4167 I HwLauncher: Launcher.Utilities createIconBitmap classname = null, sourceWidth = 114, sourceHeight = 114
07-12 11:36:38.439  4035  4035 I HwLauncher: Workspace removeItems info = ShortcutInfo(title=ThaliTest) isNeedDelete = true
,07-12 11:36:38.439  4035  4035 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
07-12 11:36:38.439  4035  4167 I HwLauncher: ClockDynamicUpdater clock update folder at ClockDynamicUpdater
07-12 11:36:38.439  4035  4167 I HwLauncher: DynamicUpdater updateBitmap end and send update message
07-12 11:36:38.439  4035  4167 I HwLauncher: WeatherDynamicUpdaterpositiveUpdate at WeatherDynamicUpdater
07-12 11:36:38.449  4035  4035 W System.err: 	at android.app.ApplicationPackageManager.getApplicationInfo(ApplicationPackageManager.java:287)
07-12 11:36:38.449  4035  4035 W System.err: 	at com.huawei.android.launcher.ShortcutInfo.isAppUninstallable(ShortcutInfo.java:347)
07-12 11:36:38.449  4035  4035 W System.err: 	at com.huawei.android.launcher.Workspace$10.run(Workspace.java:6784)
07-12 11:36:38.449  4035  4035 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
07-12 11:36:38.449  4035  4035 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
07-12 11:36:38.449  4035  4035 W System.err: 	at android.os.Looper.loop(Looper.java:135)
07-12 11:36:38.449  4035  4035 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5538)
07-12 11:36:38.449  4035  4035 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
07-12 11:36:38.449  4035  4035 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
07-12 11:36:38.449  4035  4035 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:960)
07-12 11:36:38.449  4035  4035 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:755)
,07-12 11:36:38.449  4035  4035 W System.err: java.lang.NullPointerException: null receiver
07-12 11:36:38.449  4035  4035 W System.err: 	at java.lang.reflect.Field.get(Native Method)
07-12 11:36:38.449  4035  4035 W System.err: 	at java.lang.reflect.Field.get(Field.java:279)
07-12 11:36:38.449  4035  4035 W System.err: 	at com.huawei.android.launcher.ShortcutInfo.isAppUninstallable(ShortcutInfo.java:372)
07-12 11:36:38.449  4035  4035 W System.err: 	at com.huawei.android.launcher.Workspace$10.run(Workspace.java:6784)
07-12 11:36:38.449  4035  4035 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
07-12 11:36:38.449  4035  4035 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
07-12 11:36:38.449  4035  4035 W System.err: 	at android.os.Looper.loop(Looper.java:135)
07-12 11:36:38.449  4035  4035 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5538)
07-12 11:36:38.449  4035  4035 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
07-12 11:36:38.449  4035  4035 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
07-12 11:36:38.449  4035  4035 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:960)
07-12 11:36:38.449  4035  4035 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:755)
07-12 11:36:38.449  4035  4035 I HwLauncher: CellLayout rearrangeAfterRmItem isAutoAlign = false
,07-12 11:36:38.449  4035  4035 I HwLauncher: Launcher  onWindowVisibilityChanged visibility = 0
,07-12 11:36:38.449  4035  4035 I HwLauncher: DynamicIcon onWindowVisibilityChanged 0 - com.android.calendar
07-12 11:36:38.449  4035  4035 I HwLauncher: DynamicIcon onWindowVisibilityChanged 0 - com.android.deskclock
,07-12 11:36:38.469  4035  4035 I HwLauncher: DynamicUpdater call updateFolder,
07-12 11:36:38.469  4035  4035 E HideAppsPagedView: removeHideApps  begin 
07-12 11:36:38.469  4035  4035 E HideAppsPagedView: removeHideApps  end 
07-12 11:36:38.469  4035  4035 E HideAppsPagedView:  syncPages mCurrentPage = 0
,07-12 11:36:38.469  4035  4035 E ZipFileCache: init failed when open zip file.,
07-12 11:36:38.469  4035  4035 E ZipFileCache: init failed when open zip file.
,07-12 11:36:38.469  4035  4035 E ZipFileCache: init failed when open zip file.
,07-12 11:36:38.469  4035  4035 E ZipFileCache: init failed when open zip file.,
,07-12 11:36:38.469  4035  4035 E ZipFileCache: init failed when open zip file.
,07-12 11:36:38.479  4035  4035 E HideAppsPagedView:  syncAppsPageItems page = 0 mNumAppsPages = 1 mCurrentPage = 0,
07-12 11:36:38.479  4035  4035 E HideAppsPagedView:  createAddIcon count = 0
,07-12 11:36:38.479  4035  4035 I HwLauncher:  FPSMonitor snapToPage whichPage = 0 delta = 0 duration = 550,
,07-12 11:36:38.529  2342  2342 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 55% free, 12MB/28MB, paused 164us total 26.516ms
,07-12 11:36:38.539  7320  7320 W asset   : Asset path /system/framework/com.huawei.theme.stat.jar is neither a directory nor file (type=1).
,07-12 11:36:38.549  7298  7298 E Minikin : addFont failed to create font /system/fonts/DroidSansChineseslim.ttf
,07-12 11:36:38.549  7298  7298 W GalleryUtils: the font DroidSanChineseSlim is not exist!
,07-12 11:36:38.549  3154  3154 I art     : Explicit concurrent mark sweep GC freed 67067(4MB) AllocSpace objects, 4(76KB) LOS objects, 33% free, 28MB/42MB, paused 2.192ms total 320.490ms
,07-12 11:36:38.549  3154  3230 I art     : WaitForGcToComplete blocked for 202.656ms for cause Explicit
,07-12 11:36:38.559  2342  2342 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 55% free, 12MB/28MB, paused 218us total 29.094ms
,07-12 11:36:38.579  7320  7340 I HwCust  : Constructor found for class com.huawei.android.totemweather.utils.HwCustUseBitmapConfigImpl
,07-12 11:36:38.579  7320  7320 I HwCust  : Constructor found for class com.huawei.android.totemweather.HwCustWeatherAppHwBaseImpl
,07-12 11:36:38.589  2342  2342 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 55% free, 12MB/28MB, paused 218us total 29.063ms
,07-12 11:36:38.629  4035  4035 I HwLauncher: WeatherDynamicUpdaterreceive action = com.huawei.android.action.launcher_weather_icon_change
,07-12 11:36:38.649  4035  4167 I HwLauncher: WeatherDynamicUpdaterreceiver data is int[] = [0, 0]
07-12 11:36:38.649  4035  4167 I HwLauncher:  stringArray[] [unknown]
,07-12 11:36:38.669  3154  3556 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
,07-12 11:36:38.679  3154  3556 W System.err: 	at android.app.ApplicationPackageManager.getApplicationInfo(ApplicationPackageManager.java:287)
07-12 11:36:38.679  3154  3556 W System.err: 	at com.android.server.SmartHeartBeat$HeartBeatHandler.updatePackageMessage(SmartHeartBeat.java:872)
07-12 11:36:38.679  3154  3556 W System.err: 	at com.android.server.SmartHeartBeat$HeartBeatHandler.handleMessage(SmartHeartBeat.java:606)
07-12 11:36:38.679  3154  3556 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-12 11:36:38.679  3154  3556 W System.err: 	at android.os.Looper.loop(Looper.java:135)
07-12 11:36:38.679  3154  3556 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,07-12 11:36:38.739  3154  3230 I art     : Explicit concurrent mark sweep GC freed 7873(435KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 28MB/42MB, paused 3.275ms total 194.115ms
,07-12 11:36:38.759  3154  3154 I art     : Can not find class: Lhuawei/com/android/server/util/UserBehaviourRecord;
,07-12 11:36:38.769  3154  3154 I art     : Can not find class: Lhuawei/com/android/server/util/UserBehaviourRecord$1;
,07-12 11:36:38.769  3154  3154 I art     : Can not find class: Lhuawei/com/android/server/util/ReportTool;
,07-12 11:36:38.769  3154  3154 I art     : Can not find class: Lcom/huawei/report/ReporterInterface;
,07-12 11:36:38.769  3154  3154 E ReportTools: Can't find sReporterClazz
,07-12 11:36:38.769  3154  3154 I art     : Can not find class: Lhuawei/com/android/server/util/UserBehaviourRecord$UploadThread;
,07-12 11:36:38.769  3154  3154 I art     : Can not find class: Lhuawei/com/android/server/util/AppInfo;
,07-12 11:36:38.769  3154  3154 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'int com.huawei.lcagent.client.LogCollectManager.getUserType()' on a null object reference
,07-12 11:36:38.779  3154  3154 W System.err: 	at huawei.com.android.server.util.ReportTool.getUserType(ReportTool.java:86)
07-12 11:36:38.779  3154  3154 W System.err: 	at huawei.com.android.server.util.ReportTool.isBetaUser(ReportTool.java:73)
07-12 11:36:38.779  3154  3154 W System.err: 	at huawei.com.android.server.util.ReportTool.report(ReportTool.java:58)
07-12 11:36:38.779  3154  3154 W System.err: 	at huawei.com.android.server.util.UserBehaviourRecord.appExitRecord(UserBehaviourRecord.java:65)
07-12 11:36:38.779  3154  3154 W System.err: 	at com.android.server.am.ActivityManagerService.cleanUpRemovedTaskLocked(ActivityManagerService.java:9041)
07-12 11:36:38.779  3154  3154 W System.err: 	at com.android.server.am.ActivityManagerService.removeTaskByIdLocked(ActivityManagerService.java:9097)
07-12 11:36:38.779  3154  3154 W System.err: 	at com.android.server.am.ActivityManagerService.access$1000(ActivityManagerService.java:293)
07-12 11:36:38.779  3154  3154 W System.err: 	at com.android.server.am.ActivityManagerService$3.onPackageRemoved(ActivityManagerService.java:2234)
07-12 11:36:38.779  3154  3154 W System.err: 	at com.android.internal.content.PackageMonitor.onReceive(PackageMonitor.java:341)
07-12 11:36:38.779  3154  3154 W System.err: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:899)
07-12 11:36:38.779  3154  3154 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
07-12 11:36:38.779  3154  3154 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
07-12 11:36:38.779  3154  3154 W System.err: 	at android.os.Looper.loop(Looper.java:135)
07-12 11:36:38.779  3154  3154 W System.err: 	at com.android.server.SystemServer.run(SystemServer.java:324)
07-12 11:36:38.779  3154  3154 W System.err: 	at com.android.server.SystemServer.main(SystemServer.java:212)
07-12 11:36:38.779  3154  3154 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
07-12 11:36:38.779  3154  3154 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
07-12 11:36:38.779  3154  3154 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:960)
07-12 11:36:38.779  3154  3154 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:755)
07-12 11:36:38.779  3154  3154 E ReportTools: This is not beta user build
,07-12 11:36:38.779  3694  3694 I PhoneStatusBar: hw_status_bar_operators = true, setSystemUIVisibily(SHOW_OPERATOR = false)
07-12 11:36:38.779  3694  3694 I PhoneStatusBar: shouldTranslucent:true
07-12 11:36:38.779  3694  3694 I PhoneStatusBar: hw_status_bar_operators = true, setSystemUIVisibily(SHOW_OPERATOR = false)
07-12 11:36:38.779  4227  6440 I HwSystemManager: BgPowerManagerService:onProcessDied uid = 10058
07-12 11:36:38.779  4227  4315 I HwSystemManager: HoldService:uid:10058 pid:6232 died
07-12 11:36:38.779  4227  4315 I HwSystemManager: HoldService:oldVersionKey:10058,6232
07-12 11:36:38.779  3154  3773 E HsmCoreServiceImpl: onTransact in code is: 102
07-12 11:36:38.779  3154  3773 I MediaProcessHandler: processOp opType: 1, uid: 10058, pid: 6232
07-12 11:36:38.779  3154  3773 W MediaProcessHandler: remove target not exist, maybe the UI process: uid: 10058, pid: 6232
07-12 11:36:38.789  4227  4227 I HwSystemManager: NotificationManagerReceiver:onReceive action = android.intent.action.PACKAGE_REMOVED
07-12 11:36:38.789  4227  4227 I HwSystemManager: NotificationManagerReceiver:onReceive, send action to background
07-12 11:36:38.799  4227  4227 I HwSystemManager: HsmIntentService:created. this:com.huawei.systemmanager.util.content.HsmIntentService_bg@bc135ec
07-12 11:36:38.799  4227  4227 I HwSystemManager: HsmIntentService:started for intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.huawei.systemmanager/com.huawei.notificationmanager.receiver.Receiver (has extras) }, action:android.intent.action.PACKAGE_REMOVED, class:com.huawei.notificationmanager.receiver.Receiver
07-12 11:36:38.799  4227  7371 I HwSystemManager: HsmIntentService:invoked com.huawei.notificationmanager.receiver.Receiver
07-12 11:36:38.799  6830  6830 I HwSystemManager: AppInstallationReceiver:AppInstallationReceiver onReceive action = android.intent.action.PACKAGE_REMOVED
07-12 11:36:38.799  6830  6830 I HwSystemManager: HsmIntentService:created. this:com.huawei.systemmanager.util.content.HsmIntentService_ui@32e745c4
07-12 11:36:38.799  6830  6830 I HwSystemManager: HsmIntentService:started for intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.huawei.systemmanager/com.huawei.permissionmanager.ui.AppInstallationReceiver (has extras) }, action:android.intent.action.PACKAGE_REMOVED, class:com.huawei.permissionmanager.ui.AppInstallationReceiver
07-12 11:36:38.809  6830  7372 I HwSystemManager: HsmIntentService:invoked com.huawei.permissionmanager.ui.AppInstallationReceiver
,07-12 11:36:38.809  6830  6830 I HwSystemManager: HsmIntentService:started for intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.huawei.systemmanager/.optimize.OptimizeReceiver (has extras) }, action:android.intent.action.PACKAGE_REMOVED, class:com.huawei.systemmanager.optimize.OptimizeReceiver
07-12 11:36:38.809  6830  7373 I HwSystemManager: HsmIntentService:invoked com.huawei.systemmanager.optimize.OptimizeReceiver
07-12 11:36:38.809  6830  7373 I HwSystemManager: OptimizeReceiver:OptimizeReceiver received action:android.intent.action.PACKAGE_REMOVED
07-12 11:36:38.809  6830  7373 I HwSystemManager: OverseaCfgHelper:permissionStatus is 0
07-12 11:36:38.809  6830  7079 I HwSystemManager: ProtectAppControl:handleMessage:7
07-12 11:36:38.809  6830  7373 I HwSystemManager: HsmIntentService:task completed for intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.huawei.systemmanager/.optimize.OptimizeReceiver (has extras) }, action:android.intent.action.PACKAGE_REMOVED
07-12 11:36:38.809  6830  7373 I HwSystemManager: HsmIntentService:in thread:Thread[HsmIntentServiceTask #5,5,main], current active tasksize:2, queue size:0
07-12 11:36:38.809  4227  4320 I HwSystemManager: OptimizeProvider:delete com.test.thalitest
07-12 11:36:38.809  6830  6830 I HwSystemManager: ComBroadcastReceiver:ComBroadcastReceiver action = android.intent.action.PACKAGE_REMOVED
07-12 11:36:38.809  6830  7079 I HwSystemManager: PowerGenieDbHelper:delete protect app:com.test.thalitest
07-12 11:36:38.819  4227  4227 I HwSystemManager: AppCleanUpService:onStartCommand() in!
07-12 11:36:38.819  4227  4227 I HwSystemManager: AppCleanUpService:onStartCommand() out!
07-12 11:36:38.819  4227  4227 E HwSystemManager: AppCleanUpService:msg is 1
07-12 11:36:38.829  6830  6830 I HwSystemManager: HsmIntentService:started for intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.huawei.systemmanager/.power.receiver.BootBroadcastReceiver (has extras) }, action:android.intent.action.PACKAGE_REMOVED, class:com.huawei.systemmanager.power.receiver.BootBroadcastReceiver
07-12 11:36:38.829  6830  7375 I HwSystemManager: HsmIntentService:invoked com.huawei.systemmanager.power.receiver.BootBroadcastReceiver
07-12 11:36:38.829  6830  6830 I HwSystemManager: NetAppListPrepareReceiver:NetAppListPrepareReceiver:  onReceive(), action = android.intent.action.PACKAGE_REMOVED
07-12 11:36:38.829  6830  7375 W HwSystemManager: BootBroadcastReceiver:No handler exist for registered action:android.intent.action.PACKAGE_REMOVED
07-12 11:36:38.829  6830  7375 I HwSystemManager: HsmIntentService:task completed for intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.huawei.systemmanager/.power.receiver.BootBroadcastReceiver (has extras) }, action:android.intent.action.PACKAGE_REMOVED
07-12 11:36:38.829  6830  7375 I HwSystemManager: HsmIntentService:in thread:Thread[HsmIntentServiceTask #6,5,main], current active tasksize:2, queue size:0
07-12 11:36:38.829  6830  6830 I HwSystemManager: NetAppListPrepareReceiver:package removed: package:com.test.thalitest
07-12 11:36:38.829  6830  6830 I HwSystemManager: NetAppListPrepareReceiver:replacing?:false
,07-12 11:36:38.859  4227  4624 I HwSystemManager: NotificationDBProvider:call: method = notification_list_query
07-12 11:36:38.859  4227  4624 I HwSystemManager: NotificationDBProvider:query starts, uri = content://com.huawei.systemmanager.NotificationDBProvider/notificationCfg
07-12 11:36:38.859  4227  4624 I HwSystemManager: NotificationDBProvider:query starts, matchCode = 1
07-12 11:36:38.859  4227  4251 I HwSystemManager: NotificationDBProvider:query starts, uri = content://com.huawei.systemmanager.NotificationDBProvider/notificationCfg
07-12 11:36:38.859  4227  4251 I HwSystemManager: NotificationDBProvider:query starts, matchCode = 1
07-12 11:36:38.859  4227  7371 I HwSystemManager: HsmIntentService:task completed for intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.huawei.systemmanager/com.huawei.notificationmanager.receiver.Receiver (has extras) }, action:android.intent.action.PACKAGE_REMOVED
07-12 11:36:38.859  4227  7371 I HwSystemManager: HsmIntentService:in thread:Thread[HsmIntentServiceTask #2,5,main], current active tasksize:1, queue size:0
07-12 11:36:38.859  4227  7371 I HwSystemManager: HsmIntentService:last work complete! lets stop service.
07-12 11:36:38.859  6830  7372 I HwSystemManager: HsmPackageManager:get all installed packages, flag:0, size:148
07-12 11:36:38.859  6830  7372 E HwSystemManager: PermissionDBAdapter:appcationsList size:148
07-12 11:36:38.859  4227  4316 I HwSystemManager: NotificationDBProvider:call: method = notification_list_query
07-12 11:36:38.859  4227  4316 I HwSystemManager: NotificationDBProvider:query starts, uri = content://com.huawei.systemmanager.NotificationDBProvider/notificationCfg
07-12 11:36:38.859  4227  4316 I HwSystemManager: NotificationDBProvider:query starts, matchCode = 1
07-12 11:36:38.859  3694  3694 I PhoneStatusBar: notification pkg =com.android.settings
07-12 11:36:38.859  3694  3694 I PhoneStatusBar: notification provisioned=true, score =10, [score > HIDE_ICONS_BELOW_SCORE] =true, showNotificationEvenIfUnprovisioned = false
07-12 11:36:38.859  3694  3694 I PhoneStatusBar: notification pkg =android
07-12 11:36:38.859  3694  3694 I PhoneStatusBar: notification provisioned=true, score =-10, [score > HIDE_ICONS_BELOW_SCORE] =true, showNotificationEvenIfUnprovisioned = false
07-12 11:36:38.869  6830  6830 I HwSystemManager: netAppDBHelper: DBHelper Create Database!  : SQLiteDatabase: /data/data/com.huawei.systemmanager/databases/net_permission.db
07-12 11:36:38.869  6830  6830 I HwSystemManager: NetAppListPrepareReceiver:in deleteUninstallAppFromDBAndIptables
07-12 11:36:38.869  6830  6830 I HwSystemManager: NetAppListPrepareReceiver:uid = 10072
07-12 11:36:38.869  6830  6830 I HwSystemManager: NetAppListPrepareReceiver:permissionCfg = 0
07-12 11:36:38.869  4227  7376 I HwSystemManager: ProtectAppService:send unprotect list broadcast,unprotect list:[com.gameloft.android.GloftPDMF, com.android.calculator2, com.huawei.android.ntp, com.huawei.android.Huaweiwear, com.android.hwmirror, com.zinio.android.settings, com.gameloft.android.GloftPZOR, com.zinio.mobile.android.reader, com.applift.huaweihub, com.android.email, com.huawei.phoneservice, com.android.providers.downloads, com.gameloft.android.GloftDBMF, com.hp.android.printservice, com.android.musicvis, com.android.exchange, com.todoist, com.huawei.android.thememanager, com.gameloft.android.GloftRF15, com.gameloft.android.GloftSMIM, com.android.browser, com.gameloft.android.GloftCRSM, com.example.hello, org.thaliproject.p2p.btconnectorlib.test]
,07-12 11:36:38.889  6830  7377 I HwSystemManager: NetAppListPrepareReceiver:deleteUninstallAppFromIptables thread has started
07-12 11:36:38.889  6830  7377 I HwSystemManager: NetAppListPrepareReceiver:deleteUninstallAppFromIptables thread has terminated
07-12 11:36:38.899  6830  7379 I YhdsEngine: [EngineIntentService] Received: com.dianxinos.optimizer.engine.action.PKG_CHANGE
07-12 11:36:38.899  6830  6830 I HwSystemManager: DX-Optimizer:[PackageChangeReceiver] Received: android.intent.action.PACKAGE_REMOVED, data: package:com.test.thalitest, replacing: false
07-12 11:36:38.899  6830  7380 I HwSystemManager: DX-Optimizer:[CommonIntentService] Received: com.dianxinos.optimizer.action.PKG_CHANGE
07-12 11:36:38.899  6830  6830 I HwSystemManager: AppChangeReceiver:AppChangeReceiver:  onReceive(), action = android.intent.action.PACKAGE_REMOVED
07-12 11:36:38.909  6830  7380 I TrashManager: EngineManager not initialed, please EngineManager#init()
,07-12 11:36:38.939  4227  4227 I HwSystemManager: HsmIntentService:destroyed. this:com.huawei.systemmanager.util.content.HsmIntentService_bg@bc135ec
,07-12 11:36:38.969  6830  7372 I HwSystemManager: PermissionDBAdapter:DBAdapter refreshAllCachedData!
,07-12 11:36:38.969  6830  7372 I HwSystemManager: PermissionDbVisitor:removeHistoryRecord,pkgName:com.test.thalitest, delete count:0
,07-12 11:36:38.969  6830  7372 I HwSystemManager: HsmPackageManager:get all installed packages, flag:0, size:148
07-12 11:36:38.969  6830  7372 E HwSystemManager: PermissionDBAdapter:appcationsList size:148
,07-12 11:36:39.099  6830  7372 I HwSystemManager: PermissionDBAdapter:DBAdapter refreshAllCachedData!
,07-12 11:36:39.099  6830  7372 I HwSystemManager: HsmIntentService:task completed for intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.huawei.systemmanager/com.huawei.permissionmanager.ui.AppInstallationReceiver (has extras) }, action:android.intent.action.PACKAGE_REMOVED
07-12 11:36:39.099  6830  7372 I HwSystemManager: HsmIntentService:in thread:Thread[HsmIntentServiceTask #4,5,main], current active tasksize:1, queue size:0
07-12 11:36:39.099  6830  7372 I HwSystemManager: HsmIntentService:last work complete! lets stop service.
,07-12 11:36:39.149  6830  6830 I HwSystemManager: HsmIntentService:destroyed. this:com.huawei.systemmanager.util.content.HsmIntentService_ui@32e745c4
,07-12 11:36:39.259  4227  4315 I HwSystemManager: HoldService:uid:10007 pid:6972 died
07-12 11:36:39.259  4227  4251 I HwSystemManager: BgPowerManagerService:onProcessDied uid = 10007
07-12 11:36:39.259  4227  4315 I HwSystemManager: HoldService:oldVersionKey:10007,6972
07-12 11:36:39.259  3154  6533 E HsmCoreServiceImpl: onTransact in code is: 102
07-12 11:36:39.259  3154  6533 I MediaProcessHandler: processOp opType: 1, uid: 10007, pid: 6972
07-12 11:36:39.259  3154  6533 W MediaProcessHandler: remove target not exist, maybe the UI process: uid: 10007, pid: 6972

```
