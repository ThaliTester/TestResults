#### Test 72145431fdae11f_thali03_LGE-Nexus 5 Logs


```
--------- beginning of system
06-30 10:34:54.039   790  1335 I ActivityManager: Start proc 2881:com.quickoffice.android/u0a65 for broadcast com.quickoffice.android/com.qo.android.quickoffice.QOBroadcastReceiver
--------- beginning of main
06-30 10:34:54.043  1393  2880 I UpdateIcingCorporaServi: Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,06-30 10:34:54.139  1393  2880 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 96 ms] updated apps [took 96 ms] 
06-30 10:34:54.184  2881  2881 W Quickoffice: Cleanup of storage: done
06-30 10:34:54.186  2881  2899 D com.google.android.apps.docs.quickoffice.X: Loading recent documents list
06-30 10:34:54.189  2881  2900 D Quickoffice: The number of lines present in  /proc/mount 22
06-30 10:34:54.196  2881  2900 D Quickoffice: Parsing the storagedefinition.xml.
06-30 10:34:54.201  2881  2900 D Quickoffice: # of Storagedefinitions - 35
06-30 10:34:54.201  2881  2900 D Quickoffice: The # of storage definitions available - 35
06-30 10:34:54.201  2881  2900 D Quickoffice: Processing mountline rootfs / rootfs ro,seclabel,relatime 0 0
06-30 10:34:54.202  2881  2900 D Quickoffice: Processing mountline tmpfs /dev tmpfs rw,seclabel,nosuid,relatime,mode=755 0 0
06-30 10:34:54.202  2881  2900 D Quickoffice: Processing mountline devpts /dev/pts devpts rw,seclabel,relatime,mode=600 0 0
06-30 10:34:54.202  2881  2900 D Quickoffice: Processing mountline none /dev/cpuctl cgroup rw,relatime,cpu 0 0
06-30 10:34:54.202  2881  2900 D Quickoffice: Processing mountline proc /proc proc rw,relatime 0 0
06-30 10:34:54.203  2881  2900 D Quickoffice: Processing mountline sysfs /sys sysfs rw,seclabel,relatime 0 0
06-30 10:34:54.204  2881  2900 D Quickoffice: Processing mountline selinuxfs /sys/fs/selinux selinuxfs rw,relatime 0 0
06-30 10:34:54.204  2881  2900 D Quickoffice: Processing mountline debugfs /sys/kernel/debug debugfs rw,seclabel,relatime 0 0
06-30 10:34:54.204  2881  2900 D Quickoffice: Processing mountline none /sys/fs/cgroup tmpfs rw,seclabel,relatime,mode=750,gid=1000 0 0
06-30 10:34:54.204  2881  2900 D Quickoffice: Processing mountline none /acct cgroup rw,relatime,cpuacct 0 0
06-30 10:34:54.205  2881  2900 D Quickoffice: Processing mountline tmpfs /mnt tmpfs rw,seclabel,relatime,mode=755,gid=1000 0 0
06-30 10:34:54.205  2881  2900 D Quickoffice: Processing mountline /dev/fuse /mnt/runtime/default/emulated fuse rw,nosuid,nodev,noexec,noatime,user_id=1023,group_id=1023,default_permissions,allow_other 0 0
06-30 10:34:54.206  2881  2900 D Quickoffice: Processing mountline /dev/fuse /mnt/runtime/read/emulated fuse rw,nosuid,nodev,noexec,noatime,user_id=1023,group_id=1023,default_permissions,allow_other 0 0
06-30 10:34:54.206  2881  2900 D Quickoffice: Processing mountline /dev/fuse /mnt/runtime/write/emulated fuse rw,nosuid,nodev,noexec,noatime,user_id=1023,group_id=1023,default_permissions,allow_other 0 0
06-30 10:34:54.206  2881  2900 D Quickoffice: Processing mountline /dev/block/platform/msm_sdcc.1/by-name/system /system ext4 ro,seclabel,relatime 0 0
06-30 10:34:54.207  2881  2900 D Quickoffice: Processing mountline /dev/block/platform/msm_sdcc.1/by-name/userdata /data ext4 rw,seclabel,nosuid,nodev,noatime,nomblk_io_submit,noauto_da_alloc,errors=panic,data=ordered 0 0
06-30 10:34:54.207  2881  2900 D Quickoffice: Processing mountline /dev/block/platform/msm_sdcc.1/by-name/cache /cache ext4 rw,seclabel,nosuid,nodev,noatime,nomblk_io_submit,noauto_da_alloc,errors=panic,data=ordered 0 0
06-30 10:34:54.207  2881  2900 D Quickoffice: Processing mountline /dev/block/platform/msm_sdcc.1/by-name/persist /persist ext4 rw,seclabel,nosuid,nodev,relatime,nomblk_io_submit,nodelalloc,errors=panic,data=ordered 0 0
06-30 10:34:54.207  2881  2900 D Quickoffice: Processing mountline /dev/block/platform/msm_sdcc.1/by-name/modem /firmware vfat ro,context=u:object_r:firmware_file:s0,relatime,uid=1000,gid=1000,fmask=0337,dmask=0227,codepage=cp437,iocharset=iso8859-1,shortname=lower,errors=remount-ro 0 0
06-30 10:34:54.208  2881  2900 D Quickoffice: Processing mountline tmpfs /storage tmpfs rw,seclabel,relatime,mode=755,gid=1000 0 0
06-30 10:34:54.208  2881  2900 D Quickoffice: Processing mountline /dev/fuse /storage/emulated fuse rw,nosuid,nodev,noexec,noatime,user_id=1023,group_id=1023,default_permissions,allow_other 0 0
06-30 10:34:54.209  2881  2900 D Quickoffice: Processing mountline tmpfs /storage/self tmpfs rw,seclabel,relatime,mode=755,gid=1000 0 0
06-30 10:34:54.218  2881  2900 E Quickoffice: An exception occured in getAllMountedStorages method.
06-30 10:34:54.218  2881  2900 E Quickoffice: java.lang.NullPointerException: Attempt to invoke virtual method 'void com.qo.android.filesystem.h.a(com.qo.android.filesystem.StorageDefinition)' on a null object reference
06-30 10:34:54.218  2881  2900 E Quickoffice: 	at com.quickoffice.mx.engine.a.e(AndroidLocalFileSystems.java:432)
06-30 10:34:54.218  2881  2900 E Quickoffice: 	at com.quickoffice.mx.engine.a.a(AndroidLocalFileSystems.java:92)
06-30 10:34:54.218  2881  2900 E Quickoffice: 	at com.quickoffice.mx.S.b(MxPlugin.java:59)
06-30 10:34:54.218  2881  2900 E Quickoffice: 	at com.quickoffice.mx.engine.q.f(MxEngine.java:1225)
06-30 10:34:54.218  2881  2900 E Quickoffice: 	at com.quickoffice.mx.engine.q.a(MxEngine.java:1219)
06-30 10:34:54.218  2881  2900 E Quickoffice: 	at com.qo.android.b.call(AsyncTask.java:217)
06-30 10:34:54.218  2881  2900 E Quickoffice: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
06-30 10:34:54.218  2881  2900 E Quickoffice: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
06-30 10:34:54.218  2881  2900 E Quickoffice: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
06-30 10:34:54.218  2881  2900 E Quickoffice: 	at java.lang.Thread.run(Thread.java:818)
06-30 10:34:54.218  2881  2900 D Quickoffice: The # of mounts identified -  0
06-30 10:34:54.218  2881  2900 D Quickoffice: Failed to get moto storage state.
06-30 10:34:54.221  2881  2900 D Quickoffice: Failed to get moto storage dir.
06-30 10:34:54.228   790   996 I ActivityManager: Killing 2412:com.google.android.apps.photos/u0a83 (adj 15): empty #17
06-30 10:34:54.230  2881  2902 D com.google.android.apps.docs.quickoffice.X: Checking validity of 0 items
06-30 10:34:54.241  2881  2901 W Quickoffice: Could not load clipboard.
06-30 10:34:54.258  2881  2903 W Quickoffice: Could not store clipboard.
06-30 10:34:54.291   790  1307 W ActivityManager: No permission grants found for com.quickoffice.android
06-30 10:34:54.292  2881  2902 D ContentResolverUtil: There are 0 persisted uri permissions.
06-30 10:34:54.292  2881  2902 D com.google.android.apps.docs.quickoffice.X: 0 items were valid
06-30 10:34:54.388  1651  2370 I Icing   : Indexing F008FD5DA05B75A838060BA8439641A1BB392563 from com.google.android.gms
06-30 10:34:54.438  1651  2370 D Icing   : Loaded CLD2 Version V2.0 - 20141016
06-30 10:34:54.462  1651  2213 I Icing   : Indexing done F008FD5DA05B75A838060BA8439641A1BB392563
06-30 10:34:54.668  2896  2896 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
06-30 10:34:54.672  2896  2896 D AndroidRuntime: CheckJNI is OFF
06-30 10:34:54.707  2896  2896 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
06-30 10:34:54.743  2896  2896 I Radio-JNI: register_android_hardware_Radio DONE
06-30 10:34:54.762  2896  2896 D AndroidRuntime: Calling main entry com.android.commands.am.Am
06-30 10:34:54.764   790   801 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
06-30 10:34:54.785  1393  1526 W SearchService: Abort, client detached.
06-30 10:34:54.797  2896  2896 D AndroidRuntime: Shutting down VM
06-30 10:34:54.802  1393  1568 I DeviceStateChecker: DeviceStateChecker cancelled
06-30 10:34:54.806  1393  1393 I MicroDetector: Keeping mic open: false
06-30 10:34:54.813  1393  1393 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.ah@cf21236
06-30 10:34:54.813  1393  1492 E AudioRecord-JNI: Error -4 during AudioRecord native read
06-30 10:34:54.815   790  1299 I ActivityManager: Start proc 2914:com.test.thalitest/u0a26 for activity com.test.thalitest/.MainActivity
06-30 10:34:54.866   198  1589 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
06-30 10:34:54.866   198  1589 D audio_hw_primary: disable_snd_device: snd_device(61: voice-rec-mic)
06-30 10:34:54.872  1393  1567 I MicroRecognitionRunner: Stopping hotword detection.
06-30 10:34:54.872  1393  1587 I MicroRecognitionRunner: Detection finished
06-30 10:34:54.893  2914  2914 I WebViewFactory: Loading com.google.android.webview version 50.0.2661.86 (code 266108600)
06-30 10:34:54.937  2914  2914 I cr_LibraryLoader: Time to load native libraries: 1 ms (timestamps 3565-3566)
06-30 10:34:54.937  2914  2914 I cr_LibraryLoader: Expected native library version number "50.0.2661.86", actual native library version number "50.0.2661.86"
06-30 10:34:54.952  2914  2914 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {8946668}
06-30 10:34:54.952  2914  2914 I cr_LibraryLoader: Expected native library version number "50.0.2661.86", actual native library version number "50.0.2661.86"
06-30 10:34:54.952  2914  2914 I chromium: [INFO:library_loader_hooks.cc(143)] Chromium logging enabled: level = 0, default verbosity = 0
06-30 10:34:54.971   790   895 D WifiService: New client listening to asynchronous messages
06-30 10:34:54.978  2914  2914 I cr_BrowserStartup: Initializing chromium process, singleProcess=true
06-30 10:34:54.988  2914  2914 E ApkAssets: Error while loading asset assets/natives_blob_64.bin: java.io.FileNotFoundException: assets/natives_blob_64.bin
06-30 10:34:54.988  2914  2914 E ApkAssets: Error while loading asset assets/snapshot_blob_64.bin: java.io.FileNotFoundException: assets/snapshot_blob_64.bin
06-30 10:34:54.998  2914  2914 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: QUALCOMM Build: 10/21/15, 369a2ea, I96aee987eb
,06-30 10:34:55.046   790   810 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@a667b9a:true
06-30 10:34:55.068   790   801 D ConnectivityService: listenForNetwork for Listen from uid/pid:10026/2914 for NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
06-30 10:34:55.076  2914  2914 D cr_Ime  : [InputMethodManagerWrapper.java:30] Constructor
06-30 10:34:55.083  2914  2914 W cr_AwContents: onDetachedFromWindow called when already detached. Ignoring
06-30 10:34:55.084  2914  2914 D cr_Ime  : [InputMethodManagerWrapper.java:59] isActive: false
06-30 10:34:55.093  2914  2914 D SystemWebViewEngine: CordovaWebView is running on device made by: LGE
06-30 10:34:55.110  2914  2914 I cr_Ime  : ImeThread is not enabled.
06-30 10:34:55.122  2914  2960 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
06-30 10:34:55.141  1651  2213 I Icing   : Indexing CC99D49BDF7A31CC93C41E542898B6DE53E184A6 from com.google.android.googlequicksearchbox
06-30 10:34:55.154   790   971 D ConnectivityService: listenForNetwork for Listen from uid/pid:10026/2914 for NetworkRequest [ id=5, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
06-30 10:34:55.182  2914  2960 I OpenGLRenderer: Initialized EGL, version 1.4
06-30 10:34:55.220  2914  2967 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
06-30 10:34:55.244  1651  2213 I Icing   : Indexing done CC99D49BDF7A31CC93C41E542898B6DE53E184A6
06-30 10:34:55.258   790   811 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +453ms
06-30 10:34:55.291  2914  2914 W cr_BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 2914
06-30 10:34:55.292  2914  2914 D cr_Ime  : [InputMethodManagerWrapper.java:59] isActive: true
06-30 10:34:55.292  2914  2914 D cr_Ime  : [InputMethodManagerWrapper.java:68] hideSoftInputFromWindow
06-30 10:34:55.589  2914  2914 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
06-30 10:34:55.591   790   896 D ConnectivityService: releasing NetworkRequest NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
06-30 10:34:55.593   790  1320 I ActivityManager: Killing 2436:com.google.android.deskclock/u0a33 (adj 15): empty #17
06-30 10:34:55.708  2914  2977 D jxcore_app_log: JniHelper::setJavaVM(0xb4cfc000), pthread_self() = -1730414288
06-30 10:34:55.711  2914  2977 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
06-30 10:34:55.711  2914  2977 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
06-30 10:34:55.711  2914  2977 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
06-30 10:34:55.711  2914  2977 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
06-30 10:34:55.711  2914  2977 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
06-30 10:34:55.711  2914  2977 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8de804 added. We now have 1 listener(s)
06-30 10:34:55.713  2914  2977 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 34:FC:EF:11:B1:66
06-30 10:34:55.714  2914  2977 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "34:FC:EF:11:B1:66"
06-30 10:34:55.715  2914  2977 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
06-30 10:34:55.715  2914  2977 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
06-30 10:34:55.721  2914  2977 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
06-30 10:34:55.721  2914  2977 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
06-30 10:34:55.721  2914  2977 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
06-30 10:34:55.721  2914  2977 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 34:FC:EF:11:B1:66
06-30 10:34:55.721  2914  2977 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
06-30 10:34:55.721  2914  2977 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
06-30 10:34:55.721  2914  2977 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
06-30 10:34:55.721  2914  2977 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
06-30 10:34:55.721  2914  2977 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
06-30 10:34:55.721  2914  2977 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
06-30 10:34:55.721  2914  2977 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
06-30 10:34:55.721  2914  2977 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bb022b3 added. We now have 1 listener(s)
06-30 10:34:55.722  2914  2977 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
06-30 10:34:55.723  2914  2977 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
06-30 10:34:55.724  2914  2977 W org.thaliproject.p2p.btconnectorlib.DiscoveryManager: isBleMultipleAdvertisementSupported: Bluetooth is not enabled so we could not check whether or not BluetoothLE multi advertisement is supported. However, Bluetooth LE is supported so we just *assume* multi advertisement is supported too (which may not always be the case).
06-30 10:34:55.726  2914  2977 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
06-30 10:34:55.726  2914  2977 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 1 -> 2
06-30 10:34:55.727  2914  2977 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 2 -> 3
06-30 10:34:55.727  2914  2977 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 1 -> 2
06-30 10:34:55.729  2914  2977 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
06-30 10:34:55.729  2914  2977 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 34:FC:EF:11:B1:66
06-30 10:34:55.731  2914  2977 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
06-30 10:34:55.731  2914  2977 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
06-30 10:34:55.731  2914  2977 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
06-30 10:34:55.731  2914  2977 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
06-30 10:34:55.731  2914  2977 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
06-30 10:34:55.731  2914  2977 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
06-30 10:34:55.731  2914  2977 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
06-30 10:34:55.731  2914  2977 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
06-30 10:34:55.731  2914  2977 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
06-30 10:34:55.731  2914  2977 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
06-30 10:34:55.731  2914  2977 D io.jxcore.node.ConnectivityMonitor: start: OK
06-30 10:34:55.731  2914  2977 I io.jxcore.node.LifeCycleMonitor: start: OK
06-30 10:34:55.756  2914  2914 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
06-30 10:34:56.457  2914  2978 W jxcore-log: Initializing JXcore engine
06-30 10:34:56.457  2914  2978 W jxcore-log: JXcore engine is ready
06-30 10:34:56.489  2978  2978 W Thread-259: type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[7504]" dev="sockfs" ino=7504 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
06-30 10:34:56.489  2978  2978 W Thread-259: type=1400 audit(0.0:7): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3033 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
06-30 10:34:56.489  2978  2978 W Thread-259: type=1400 audit(0.0:8): avc: denied { ioctl } for path="socket:[18379]" dev="sockfs" ino=18379 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
06-30 10:34:56.507  2914  2978 W jxcore-log: Starting JXcore engine
,06-30 10:34:56.606  2914  2978 W jxcore-log: Platform android
06-30 10:34:56.606  2914  2978 W jxcore-log: 
,06-30 10:34:56.606  2914  2978 W jxcore-log: Process ARCH arm
06-30 10:34:56.606  2914  2978 W jxcore-log: 
,06-30 10:34:56.790  2914  2978 I jxcore-log: JXcore Cordova bridge is ready!
06-30 10:34:56.790  2914  2978 I jxcore-log: 
,06-30 10:34:56.791  2914  2978 W jxcore-log: JXcore engine is started
,06-30 10:34:56.802  2914  2977 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,06-30 10:34:56.804   790  1418 I ActivityManager: START u0 {act=android.content.pm.action.REQUEST_PERMISSIONS pkg=com.android.packageinstaller cmp=com.android.packageinstaller/.permission.ui.GrantPermissionsActivity (has extras)} from uid 10026 on display 0
,06-30 10:34:56.818  2914  2914 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,06-30 10:34:56.818  2914  2914 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,06-30 10:34:56.833   790  1335 I ActivityManager: Start proc 2987:com.android.packageinstaller/u0a60 for activity com.android.packageinstaller/.permission.ui.GrantPermissionsActivity
,06-30 10:34:56.882  2987  2987 W System  : ClassLoader referenced unknown path: /system/priv-app/GooglePackageInstaller/lib/arm
,06-30 10:34:56.981  2987  2999 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,06-30 10:34:57.017  2987  2999 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: QUALCOMM Build: 10/21/15, 369a2ea, I96aee987eb
,06-30 10:34:57.019  2987  2999 I OpenGLRenderer: Initialized EGL, version 1.4
,06-30 10:34:57.129   790   811 I ActivityManager: Displayed com.android.packageinstaller/.permission.ui.GrantPermissionsActivity: +307ms
,06-30 10:34:57.309  2914  2914 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@eaf070e Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@ee9d7ad, 16908290=android.view.AbsSavedState$1@ee9d7ad}, android:focusedViewId=100}]}]
,06-30 10:34:57.309  2914  2914 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
,06-30 10:34:57.914   790  1320 I ActivityManager: Killing 2456:com.google.android.gm.exchange/u0a84 (adj 15): empty #17
,06-30 10:35:00.318   790  1297 I ActivityManager: Killing 1762:com.google.android.apps.fitness/u0a82 (adj 15): empty #17
,06-30 10:35:04.889  1573  1573 I Finsky  : [1] com.google.android.finsky.services.DailyHygiene.a(17227): Beginning daily hygiene, foreground = false
,06-30 10:35:04.985  1263  1263 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,06-30 10:35:04.989  1263  1263 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,06-30 10:35:04.989  1263  1263 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,06-30 10:35:05.018  1573  1573 W Finsky  : [1] com.google.android.finsky.services.n.a(313): Unable to preload experiments: com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
,06-30 10:35:05.023  1263  1263 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,06-30 10:35:05.035  1573  1573 W Finsky  : [1] com.google.android.finsky.services.q.a(413): Self-update check failed with error: com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
,06-30 10:35:05.043  1263  1263 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,06-30 10:35:05.071  1573  1573 W Finsky  : [1] com.google.android.finsky.j.ac.a(562): Library replication failed: com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
,06-30 10:35:05.157  1263  1263 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,06-30 10:35:05.179  1573  1573 W Finsky  : [1] com.google.android.finsky.autoupdate.t.a(243): Update check failed: com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
,06-30 10:35:05.182  1573  1573 I Finsky  : [1] com.google.android.finsky.services.DailyHygiene.d(590): Logging device features
,06-30 10:35:05.186  1573  1573 I Finsky  : [1] com.google.android.finsky.selfupdate.SelfUpdateCheckerScheduler.a(57): Cancelling accelerated self-Update check
,06-30 10:35:05.190  1573  1573 I Finsky  : [1] com.google.android.finsky.services.DailyHygiene.a(783): Scheduling new run in 271 minutes (failures=4)
,06-30 10:35:05.236  1573  1573 I Finsky  : [1] com.google.android.vending.verifier.VerifyInstalledPackagesReceiver.onReceive(2100): Skipping verification because network inactive
,06-30 10:35:05.239  1263  1545 D DeviceConnectionService: client connected with version: 8486000
,06-30 10:35:05.244  1263  1263 D WearableService: callingUid 10007, callindPid: 1263
,06-30 10:35:05.248  1573  1573 E Finsky  : [1] com.google.android.finsky.wear.bk.a(752): onConnectionFailed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,06-30 10:35:05.249  1573  1573 I Finsky  : [1] com.google.android.finsky.wear.WearSupportService.a(6355): Dropping command=hygiene due to Gms not connected
,06-30 10:35:05.257  1573  3055 I Finsky  : [125] com.google.android.finsky.receivers.FlushLogsReceiver$FlushLogsService.onHandleIntent(163): Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,06-30 10:35:05.257  1573  1631 I PlayCommon: [107] com.google.android.play.a.w.a(27551): Starting to flush logs
,06-30 10:35:05.295  1263  1263 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,06-30 10:35:05.327  1573  1631 I PlayCommon: [107] com.google.android.play.a.w.a(27562): Log flushed by 0 successful uploads
,06-30 10:35:05.833  1263  1263 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,06-30 10:35:05.969  2825  2860 W linker  : /data/app/com.google.android.gms-1/lib/arm/libgmscore.so: unused DT entry: type 0x7ffffffd arg 0x4ed
,06-30 10:35:05.981  2825  2860 W linker  : /data/app/com.google.android.gms-1/lib/arm/libconscrypt_gmscore_jni.so: unused DT entry: type 0x1d arg 0xef
,06-30 10:35:05.981  2825  2860 W linker  : /data/app/com.google.android.gms-1/lib/arm/libconscrypt_gmscore_jni.so: unused DT entry: type 0x7ffffffd arg 0x1da
,06-30 10:35:05.985  2825  2860 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,06-30 10:35:06.008  2825  2860 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,06-30 10:35:20.101  1573  1634 I Finsky  : [110] com.google.android.finsky.c.e.run(1151): Replicating app states via AMAS.
,06-30 10:35:20.225  1573  1634 I Finsky  : [110] com.google.android.finsky.c.c.a(311): Completed 0 account content syncs with 0 successful.
,06-30 10:35:20.225  1573  1573 I Finsky  : [1] com.google.android.finsky.services.j.a(149): Installation state replication succeeded.
,06-30 10:36:12.543   790   813 I PowerManagerService: Going to sleep due to screen timeout (uid 1000)...
,06-30 10:36:12.546   790   813 I PowerManagerService: Sleeping (uid 1000)...
,06-30 10:36:12.596   189   227 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (607 us)
06-30 10:36:12.597   790   813 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: QUALCOMM Build: 10/21/15, 369a2ea, I96aee987eb
06-30 10:36:12.669  2914  2914 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
06-30 10:36:12.669  2914  2914 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
,06-30 10:36:13.140   790   813 V KeyguardServiceDelegate: onScreenTurnedOff()
,06-30 10:36:13.215   790   813 E libEGL  : call to OpenGL ES API with no current context (logged once per thread)
,06-30 10:36:13.218   790   811 I DisplayManagerService: Display device changed state: "Built-in Screen", OFF
,06-30 10:36:13.222   189   189 D SurfaceFlinger: Set power mode=0, type=0 flinger=0xb6b24000
,06-30 10:36:13.223   189   189 D qdhwcomposer: hwc_blank: Blanking display: 0
,06-30 10:36:13.503   189   189 D qdhwcomposer: hwc_blank: Done blanking display: 0
,06-30 10:36:13.504   790   910 D SurfaceControl: Excessive delay in setPowerMode(): 286ms
,06-30 10:36:13.504  1820  1831 E ANDR-PERF-LOCK: Failed to apply optimization for resource: 4 level: 0
06-30 10:36:13.511   198   198 D audio_hw_primary: adev_set_parameters: enter: screen_state=on
06-30 10:36:13.512   790   894 D WifiConfigStore: Retrieve network priorities after PNO.
06-30 10:36:13.512   790   894 E WifiStateMachine:  Fail to set up pno, want false now false
,06-30 10:36:13.556   198  1065 D audio_hw_primary: adev_set_parameters: enter: screen_state=off
,06-30 10:36:13.557   790   894 D WifiConfigStore: Retrieve network priorities after PNO.
06-30 10:36:13.558   790   894 E WifiStateMachine:  Fail to set up pno, want false now false
,06-30 10:36:13.577  1236  1236 I GoogleInputMethod: onReceive() : Action = android.intent.action.SCREEN_OFF
,06-30 10:36:17.616  1263  1607 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,06-30 10:36:18.216   790   996 D ConnectivityService: listenForNetwork for Listen from uid/pid:10007/1651 for NetworkRequest [ id=6, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,06-30 10:36:18.254  1651  3128 W DriveInitializer: Background init thread started
,06-30 10:36:18.322  1651  3128 W DriveInitializer: Background init thread ended
,06-30 10:36:48.500  1263  1263 E ctxmgr  : [FencePendingIntentCache]Expected to find a PendingIntent for pendingIntentKey=209b4cfd-cffc-4b26-8230-80d543985624
,06-30 10:36:48.502  1263  1263 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,06-30 10:36:48.503  1263  1263 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,06-30 10:36:48.598  1263  1565 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,06-30 10:36:48.601  1651  3141 D UdcContextInitService: registered all accounts: true
,06-30 10:36:48.604  1263  1547 E ctxmgr  : [FenceManager]Could not remove all geofences. status=Status{statusCode=unknown status code: 1000, resolution=null}
,06-30 10:36:48.665  1263  1547 W ctxmgr  : [AclManager]checkPermissionTypeStatus: no inject permission for { uid=10007, packageName=com.google.android.gms }. Returned permission was: PACKAGE_NOT_WHITELISTED for context name=POWER_CONNECTION, account=account#-517948760#
06-30 10:36:48.666  1263  1263 E ctxmgr  : [PowerConnectionProducer]Could not write powerInfo=Plug state: 2 BatteryLevel: 0.97, status=Status{statusCode=unknown status code: 7503, resolution=null}
,06-30 10:36:48.745  1651  2213 I Icing   : Performing maintenance.
,06-30 10:36:48.750  1651  3154 E IcingInternalCorpora: Unknown Contacts update mode: MAYBE
,06-30 10:36:48.793  1651  3156 W IcingInternalCorpora: getNumBytesRead when not calculated.
,06-30 10:36:48.857  1263  3161 I VacuumService: Vacuum at: now=1467275808857 tag=VacuumService
,06-30 10:36:48.900  1263  1532 E Auth    : [GoogleAccountDataServiceImpl] getToken() -> NETWORK_ERROR. Account: <ELLIDED:1197869880>, App: com.google.android.gms, Service: oauth2:https://www.googleapis.com/auth/webhistory
,06-30 10:36:48.902  1651  2213 W Icing   : Failed to get auth token for account:<redacted>, error:NetworkError
,06-30 10:36:48.918  1263  1277 E Auth    : [GoogleAccountDataServiceImpl] getToken() -> NETWORK_ERROR. Account: <ELLIDED:1197869880>, App: com.google.android.gms, Service: oauth2:https://www.googleapis.com/auth/webhistory
06-30 10:36:48.919  1651  2213 W Icing   : Failed to get auth token for account:<redacted>, error:NetworkError
,06-30 10:36:48.964  1651  2213 I Icing   : updateResources: need to parse pru{com.google.android.gms}
,06-30 10:36:49.088  1651  2213 I Icing   : Performing maintenance usage 1696926 budget 5021329999 free 99.966% index free 99.984% purge? false target 3514930999
,06-30 10:36:49.102  1651  2213 I Icing   : Skipping storage state: opt-out
,06-30 10:36:49.218  1651  2152 I Icing   : Query from com.google.android.gms package restrict com.google.android.gms start 0 num 100
,06-30 10:37:48.826  1263  1547 E ctxmgr  : [BaseServerTask]Failed network request due to no network connectivity.
06-30 10:37:48.826  1263  1547 E ctxmgr  : [BaseServerTask]Failed network request due to no network connectivity.
,06-30 10:37:48.827  1263  1547 E ctxmgr  : [BaseServerTask]Failed network request due to no network connectivity.
06-30 10:37:48.827  1263  1547 W ctxmgr  : [DeviceRegistrationSync]Failed device registration sync (statusCode=NO_NETWORK_CONNECTIVITY).  Giving up.
06-30 10:37:48.827  1263  1547 E ctxmgr  : [SyncServerInterestRecordsOperation]Failure response from WriteInterestRecord. StatusCode = 1
,06-30 10:37:48.859  1263  1547 W ctxmgr  : [AclUpdateManager]Failed Acl fetch for account account#61035162# with status: NO_NETWORK_CONNECTIVITY).  Giving up.
,06-30 10:39:06.652  1263  1263 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,06-30 10:39:06.668  1263  1263 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,06-30 10:39:06.668  1263  1263 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,06-30 10:44:06.766  1263  1263 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,06-30 10:44:06.786  1263  1263 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
06-30 10:44:06.787  1263  1263 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,06-30 10:49:05.144  1651  3182 I EventLogChimeraService: Aggregate from 1467274224736 (log), 1467274224736 (data)
,06-30 10:49:05.253  1651  3184 D DropBoxEntryAddedChimeraService: User is not opted-in to Usage & Diagnostics.
,06-30 10:49:05.260  1651  3184 D DropBoxEntryAddedChimeraService: User is not opted-in to Usage & Diagnostics.
,06-30 10:49:05.278  1393  3179 I ContextCompilationHandl: Compiling grammar for: en-US, type=CONTACT_DIALING
,06-30 10:49:05.307  1393  3179 I ContextCompilationHandl: Recognition context unchanged for CONTACT_DIALING en-US
,06-30 10:49:05.307  1393  3179 I ContextCompilationHandl: Compiling grammar for: en-US, type=HANDS_FREE_COMMANDS
,06-30 10:49:05.314  1393  3179 I ContextCompilationHandl: Recognition context unchanged for HANDS_FREE_COMMANDS en-US
06-30 10:49:05.314  1393  3179 I ContextCompilationHandl: Compiling grammar for: en-US, type=CONTACT_NAMES
,06-30 10:49:05.327  1393  3179 E ContextCompilationHandl: No recognition context built for CONTACT_NAMES en-US
,06-30 10:49:05.327  1393  3179 I ContextCompilationHandl: Compiling grammar for: en-US, type=APP_NAMES
,06-30 10:49:05.390  1651  3195 W IcingInternalCorpora: getNumBytesRead when not calculated.
,06-30 10:49:05.403  1651  2636 I Icing   : Query from com.google.android.googlequicksearchbox package restrict com.google.android.googlequicksearchbox start 0 num 1000
,06-30 10:49:05.831  1393  3179 I ContextCompilationHandl: Compiling grammar for: en-US, type=MUSIC_NAMES
,06-30 10:49:05.860  1651  2636 I Icing   : Query from com.google.android.googlequicksearchbox package restrict com.google.android.music start 0 num 500
,06-30 10:49:05.875  1651  2636 E Icing   : No scoring data for corpus [23]
,06-30 10:49:05.899  1651  2151 I Icing   : Query from com.google.android.googlequicksearchbox package restrict com.google.android.music start 0 num 100
,06-30 10:49:05.917  1651  2151 E Icing   : No scoring data for corpus [13]
,06-30 10:49:05.943  1651  2151 I Icing   : Query from com.google.android.googlequicksearchbox package restrict com.google.android.music start 0 num 100
,06-30 10:49:05.959  1651  2151 E Icing   : No scoring data for corpus [11]
,06-30 10:49:05.980  1651  2152 I Icing   : Query from com.google.android.googlequicksearchbox package restrict com.google.android.music start 0 num 100
,06-30 10:49:05.995  1651  2152 E Icing   : No scoring data for corpus [24]
,06-30 10:49:05.997  1393  3179 E ContextCompilationHandl: No recognition context built for MUSIC_NAMES en-US
,06-30 10:49:06.874  1263  1263 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,06-30 10:49:06.886  1263  1263 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,06-30 10:49:06.887  1263  1263 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,06-30 10:53:18.851  1263  1547 W ctxmgr  : [AclManager]checkPermissionTypeStatus: no inject permission for { uid=10007, packageName=com.google.android.gms }. Returned permission was: PACKAGE_NOT_WHITELISTED for context name=POWER_CONNECTION, account=account#-517948760#
,06-30 10:53:18.851  1263  1547 W ctxmgr  : [AclManager]checkPermissionTypeStatus: no inject permission for { uid=10007, packageName=com.google.android.gms }. Returned permission was: PACKAGE_NOT_WHITELISTED for context name=POWER_CONNECTION, account=account#-517948760#
06-30 10:53:18.851  1263  1263 E ctxmgr  : [PowerConnectionProducer]Could not write powerInfo=Plug state: 2 BatteryLevel: 0.98, status=Status{statusCode=unknown status code: 7503, resolution=null}
,06-30 10:54:00.719   790   805 I UsageStatsService: User[0] Flushing usage stats to disk
,06-30 10:54:07.106  1263  1263 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,06-30 10:54:07.126  1263  1263 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,06-30 10:54:07.127  1263  1263 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,TIME-OUT KILL (timeout was 1400000ms)
```
