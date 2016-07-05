#### Test 7214543196063dc_thali03_samsung-SM-G900F Logs


```
--------- beginning of system
07-05 14:03:48.327   767  1237 V AlarmManager: Expired Alarm result :4
,07-05 14:03:48.426   767  1466 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
07-05 14:03:48.426   767  1466 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4372, temperature: 303, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
07-05 14:03:48.426   767  1466 D BatteryService: online:4, current avg:300, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
07-05 14:03:48.426   767  1466 D BatteryService: stay LED for charging
07-05 14:03:48.456   767   767 D BatteryService: Sending ACTION_BATTERY_CHANGED.
07-05 14:03:48.476   767   767 I MotionRecognitionService: Plugged
07-05 14:03:48.476   767   767 D MotionRecognitionService:   cableConnection= 1
07-05 14:03:48.476   767   767 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
07-05 14:03:48.476   767   767 D MotionRecognitionService: skip setTransmitPower. 
--------- beginning of main
07-05 14:03:48.476  1380  1380 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
07-05 14:03:48.476  1380  1380 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
07-05 14:03:48.476  1380  1380 D KeyguardUpdateMonitor: handleBatteryUpdate
07-05 14:03:48.486  2328  2328 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
07-05 14:03:48.486  2328  2834 D HeadsetStateMachine: Disconnected process message: 10, size: 0
07-05 14:03:48.506  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
07-05 14:03:48.506  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
07-05 14:03:48.506  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
07-05 14:03:48.536   767   767 I BackgroundCompactionService: onStart. jobID=801
07-05 14:03:48.546   767   767 I BackgroundCompactionService: onStart done. jobID=801
07-05 14:03:48.546   767  6904 I BackgroundCompactionService: Execute BGCompaction (type1). (0 times)
07-05 14:03:48.556   767  6904 I BackgroundCompactionService: compact_memory command done
07-05 14:03:48.766   767   866 I ActivityManager: Waited long enough for: ServiceRecord{caee898 u0 com.samsung.android.sdk.samsunglink/com.mfluent.asp.ContentAggregatorService}
07-05 14:03:49.156  1653  1653 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
07-05 14:03:49.166  1653  1653 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
07-05 14:03:49.166  1653  1653 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
07-05 14:03:49.186  1653  3945 E Auth    : [GoogleAccountDataServiceImpl] getToken() failed. Status BAD_AUTHENTICATION, Account: <ELLIDED:1197869880>, App: com.android.vending, Service: androidsecure
07-05 14:03:49.186  1653  3945 E Auth    : com.google.android.gms.auth.be.account.b.d: Long live credential not available.
07-05 14:03:49.186  1653  3945 E Auth    : 	at com.google.android.gms.auth.be.account.b.e.a(:com.google.android.gms:105)
07-05 14:03:49.186  1653  3945 E Auth    : 	at com.google.android.gms.auth.be.p.a(:com.google.android.gms:355)
07-05 14:03:49.186  1653  3945 E Auth    : 	at com.google.android.gms.auth.be.o.a(:com.google.android.gms:260)
07-05 14:03:49.186  1653  3945 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.y.a(:com.google.android.gms:197)
07-05 14:03:49.186  1653  3945 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.x.a(:com.google.android.gms:558)
07-05 14:03:49.186  1653  3945 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.x.a(:com.google.android.gms:196)
07-05 14:03:49.186  1653  3945 E Auth    : 	at com.google.android.gms.auth.o.a(:com.google.android.gms:276)
07-05 14:03:49.186  1653  3945 E Auth    : 	at com.google.android.gms.auth.o.a(:com.google.android.gms:196)
07-05 14:03:49.186  1653  3945 E Auth    : 	at com.google.android.gms.auth.t.a(:com.google.android.gms:498)
07-05 14:03:49.186  1653  3945 E Auth    : 	at com.google.android.gms.auth.s.a(:com.google.android.gms:908)
07-05 14:03:49.186  1653  3945 E Auth    : 	at com.google.android.gms.auth.s.e(:com.google.android.gms:528)
07-05 14:03:49.186  1653  3945 E Auth    : 	at com.google.android.gms.auth.be.m.getAuthToken(:com.google.android.gms:201)
07-05 14:03:49.186  1653  3945 E Auth    : 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
07-05 14:03:49.186  1653  3945 E Auth    : 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
07-05 14:03:49.186  1653  3945 E Auth    : 	at android.os.Binder.execTransact(Binder.java:453)
07-05 14:03:49.206  5788  5788 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
07-05 14:03:49.206  5788  5788 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
07-05 14:03:49.206  5788  5788 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 1.
07-05 14:03:49.696  2334  2334 E audit   : type=1400 msg=audit(1467720229.696:286): avc:  denied  { execmod } for  pid=6885 comm="app_process" path="/system/lib/lib_SoundAlive_ver118t.so" dev="mmcblk0p23" ino=1663 scontext=u:r:shell:s0 tcontext=u:object_r:system_file:s0 tclass=file permissive=0
07-05 14:03:49.706  2334  2334 E audit   :  SEPF_SECMOBILE_6.0.1_0011
07-05 14:03:49.706  2334  2334 E audit   : type=1300 msg=audit(1467720229.696:286): arch=40000028 syscall=125 per=800008 success=no exit=-13 a0=b3ffb000 a1=51000 a2=5 a3=4 items=0 ppid=3676 ppcomm=adbd pid=6885 auid=4294967295 uid=2000 gid=2000 euid=2000 suid=2000 fsuid=2000 egid=2000 sgid=2000 fsgid=2000 tty=pts1 ses=4294967295 comm="app_process" exe="/system/bin/app_process32" subj=u:r:shell:s0 key=(null)
07-05 14:03:49.716  2334  2334 E audit   : type=1327 msg=audit(1467720229.696:286): proctitle=6170705F70726F63657373002F73797374656D2F62696E00636F6D2E616E64726F69642E636F6D6D616E64732E616D2E416D007374617274002D6E00636F6D2E746573742E7468616C69746573742F636F6D2E746573742E7468616C69746573742E4D61696E4163746976697479
07-05 14:03:49.716  2334  2334 E audit   : type=1320 msg=audit(1467720229.696:286): 
07-05 14:03:49.786  2334  2334 E audit   : type=1400 msg=audit(1467720229.776:287): avc:  denied  { execmod } for  pid=6885 comm="app_process" path="/system/lib/lib_SoundAlive_ver118t.so" dev="mmcblk0p23" ino=1663 scontext=u:r:shell:s0 tcontext=u:object_r:system_file:s0 tclass=file permissive=0
07-05 14:03:49.786  2334  2334 E audit   :  SEPF_SECMOBILE_6.0.1_0011
07-05 14:03:49.786  2334  2334 E audit   : type=1300 msg=audit(1467720229.776:287): arch=40000028 syscall=125 per=800008 success=no exit=-13 a0=b3fba000 a1=51000 a2=5 a3=4 items=0 ppid=3676 ppcomm=adbd pid=6885 auid=4294967295 uid=2000 gid=2000 euid=2000 suid=2000 fsuid=2000 egid=2000 sgid=2000 fsgid=2000 tty=pts1 ses=4294967295 comm="app_process" exe="/system/bin/app_process32" subj=u:r:shell:s0 key=(null)
07-05 14:03:49.786  2334  2334 E audit   : type=1327 msg=audit(1467720229.776:287): proctitle=6170705F70726F63657373002F73797374656D2F62696E00636F6D2E616E64726F69642E636F6D6D616E64732E616D2E416D007374617274002D6E00636F6D2E746573742E7468616C69746573742F636F6D2E746573742E7468616C69746573742E4D61696E4163746976697479
07-05 14:03:49.796  2334  2334 E audit   : type=1320 msg=audit(1467720229.776:287): 
07-05 14:03:49.846  2334  2334 E audit   : type=1400 msg=audit(1467720229.846:288): avc:  denied  { execmod } for  pid=6885 comm="app_process" path="/system/lib/lib_SoundAlive_ver118t.so" dev="mmcblk0p23" ino=1663 scontext=u:r:shell:s0 tcontext=u:object_r:system_file:s0 tclass=file permissive=0
07-05 14:03:49.846  6885  6885 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
07-05 14:03:49.846  2334  2334 E audit   :  SEPF_SECMOBILE_6.0.1_0011
07-05 14:03:49.846  2334  2334 E audit   : type=1300 msg=audit(1467720229.846:288): arch=40000028 syscall=125 per=800008 success=no exit=-13 a0=b3fbb000 a1=51000 a2=5 a3=4 items=0 ppid=3676 ppcomm=adbd pid=6885 auid=4294967295 uid=2000 gid=2000 euid=2000 suid=2000 fsuid=2000 egid=2000 sgid=2000 fsgid=2000 tty=pts1 ses=4294967295 comm="app_process" exe="/system/bin/app_process32" subj=u:r:shell:s0 key=(null)
07-05 14:03:49.846  2334  2334 E audit   : type=1327 msg=audit(1467720229.846:288): proctitle=6170705F70726F63657373002F73797374656D2F62696E00636F6D2E616E64726F69642E636F6D6D616E64732E616D2E416D007374617274002D6E00636F6D2E746573742E7468616C69746573742F636F6D2E746573742E7468616C69746573742E4D61696E4163746976697479
07-05 14:03:49.856  2334  2334 E audit   : type=1320 msg=audit(1467720229.846:288): 
07-05 14:03:49.856  6885  6885 D AndroidRuntime: CheckJNI is OFF
07-05 14:03:49.856  6885  6885 D AndroidRuntime: readGMSProperty: start
07-05 14:03:49.856  6885  6885 D AndroidRuntime: readGMSProperty: already setted!!
07-05 14:03:49.856  6885  6885 D AndroidRuntime: propertySet: couldn't set property (it is from app)
07-05 14:03:49.856  6885  6885 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
07-05 14:03:49.856  6885  6885 D AndroidRuntime: readGMSProperty: end
07-05 14:03:49.856  6885  6885 D AndroidRuntime: addProductProperty: start
07-05 14:03:49.866  6885  6885 W art     : 70aa4000-71821000 rw-p 00000000 b3:1a 130592     /data/dalvik-cache/arm/system@framework@boot.art
07-05 14:03:49.866  6885  6885 W art     : af164000-b208a000 r--p 00000000 b3:17 579        /system/framework/arm/boot.oat
07-05 14:03:49.866  6885  6885 W art     : b208a000-b42f9000 r-xp 02f26000 b3:17 579        /system/framework/arm/boot.oat
07-05 14:03:49.866  6885  6885 W art     : b42f9000-b42fa000 rw-p 05195000 b3:17 579        /system/framework/arm/boot.oat
07-05 14:03:49.866  6885  6885 W art     : b42fa000-b4323000 r--p 00d7d000 b3:1a 130592     /data/dalvik-cache/arm/system@framework@boot.art
07-05 14:03:49.866  6885  6885 W art     : b4323000-b4771000 r-xp 00000000 b3:17 594        /system/lib/libart.so
07-05 14:03:49.866  6885  6885 W art     : b4771000-b4772000 ---p 00000000 00:00 0 
07-05 14:03:49.866  6885  6885 W art     : b4772000-b477c000 r--p 0044e000 b3:17 594        /system/lib/libart.so
07-05 14:03:49.866  6885  6885 W art     : b477c000-b477d000 rw-p 00458000 b3:17 594        /system/lib/libart.so
07-05 14:03:49.866  6885  6885 W art     : b477d000-b477f000 rw-p 00000000 00:00 0 
07-05 14:03:49.866  6885  6885 W art     : b477f000-b4780000 r--p 00000000 00:00 0 
07-05 14:03:49.866  6885  6885 W art     : b4780000-b4880000 rw-p 00000000 00:00 0          [anon:libc_malloc]
07-05 14:03:49.866  6885  6885 W art     : b4888000-b488b000 r-xp 00000000 b3:17 2411       /system/lib/libsigchain.so
07-05 14:03:49.866  6885  6885 W art     : b488b000-b488c000 r--p 00002000 b3:17 2411       /system/lib/libsigchain.so
07-05 14:03:49.866  6885  6885 W art     : b488c000-b488d000 rw-p 00003000 b3:17 2411       /system/lib/libsigchain.so
07-05 14:03:49.866  6885  6885 W art     : b488d000-b488e000 r--p 00000000 00:00 0 
07-05 14:03:49.866  6885  6885 W art     : b488e000-b48ae000 r--s 00000000 00:0b 6702       /dev/__properties__
07-05 14:03:49.866  6885  6885 W art     : b48ae000-b52bf000 r-xp 00000000 b3:17 2806       /system/lib/libLLVM.so
07-05 14:03:49.866  6885  6885 W art     : b52bf000-b52c0000 ---p 00000000 00:00 0 
07-05 14:03:49.866  6885  6885 W art     : b52c0000-b5309000 r--p 00a11000 b3:17 2806       /system/lib/libLLVM.so
07-05 14:03:49.866  6885  6885 W art     : b5309000-b530a000 rw-p 00a5a000 b3:17 2806       /system/lib/libLLVM.so
07-05 14:03:49.866  6885  6885 W art     : b530a000-b5312000 rw-p 00000000 00:00 0 
07-05 14:03:49.866  6885  6885 W art     : b5312000-b5313000 r--p 00000000 00:00 0          [anon:linker_alloc]
07-05 14:03:49.866  6885  6885 W art     : b5313000-b5348000 r-xp 00000000 b3:17 715        /system/lib/libbcinfo.so
07-05 14:03:49.866  6885  6885 W art     : b5348000-b5349000 ---p 00000000 00:00 0 
07-05 14:03:49.866  6885  6885 W art     : b5349000-b534a000 r--p 00035000 b3:17 715        /system/lib/libbcinfo.so
07-05 14:03:49.866  6885  6885 W art     : b534a000-b534b000 rw-p 00036000 b3:17 715        /system/lib/libbcinfo.so
07-05 14:03:49.866  6885  6885 W art     : b534b000-b53a3000 r-xp 00000000 b3:17 2786       /system/lib/libbcc.so
07-05 14:03:49.866  6885  6885 W art     : b53a3000-b53a4000 ---p 00000000 00:00 0 
07-05 14:03:49.866  6885  6885 W art     : b53a4000-b53a5000 r--p 00058000 b3:17 2786       /system/lib/libbcc.so
07-05 14:03:49.866  6885  6885 W art     : b53a5000-b53a6000 rw-p 00059000 b3:17 2786       /system/lib/libbcc.so
07-05 14:03:49.866  6885  6885 W art     : b53a7000-b53ad000 r-xp 00000000 b3:17 32         /system/lib/lib_SamsungVAD_v01009.so
07-05 14:03:49.866  6885  6885 W art     : b53ad000-b53ae000 r--p 00005000 b3:17 32         /system/lib/lib_SamsungVAD_v01009.so
07-05 14:03:49.866  6885  6885 W art     : b53ae000-b53af000 rw-p 00006000 b3:17 32         /system/lib/lib_SamsungVAD_v01009.so
07-05 14:03:49.866  6885  6885 W art     : b53af000-b53b1000 rw-p 00000000 00:00 0 
07-05 14:03:49.866  6885  6885 W art     : b53b2000-b53bc000 r-xp 00000000 b3:17 979        /system/lib/libcommon_time_client.so
07-05 14:03:49.866  6885  6885 W art     : b53bc000-b53bf000 r--p 00009000 b3:17 979        /system/lib/libcommon_time_client.so
07-05 14:03:49.866  6885  6885 W art     : b53bf000-b53c0000 rw-p 0000c000 b3:17 979        /system/lib/libcommon_time_client.so
07-05 14:03:49.866  6885  6885 W art     : b53c1000-b53d8000 r-xp 00000000 b3:17 2934       /system/lib/libprotobuf-cpp-lite.so
07-05 14:03:49.866  6885  6885 W art     : b53d8000-b53d9000 ---p 00000000 00:00 0 
07-05 14:03:49.866  6885  6885 W art     : b53d9000-b53da000 r--p 00017000 b3:17 2934       /system/lib/libprotobuf-cpp-lite.so
07-05 14:03:49.866  6885  6885 W art     : b53da000-b53db000 rw-p 00018000 b3:17 2934       /system/lib/libprotobuf-cpp-lite.so
07-05 14:03:49.866  6885  6885 W art     : b53dc000-b53e6000 r-xp 00000000 b3:17 2679       /system/lib/libsec_km.so
07-05 14:03:49.866  6885  6885 W art     : b53e6000-b53e7000 r--p 00009000 b3:17 2679       /system/lib/libsec_km.so
07-05 14:03:49.866  6885  6885 W art     : b53e7000-b53e8000 rw-p 0000a000 b3:17 2679       /system/lib/libsec_km.so
07-05 14:03:49.866  6885  6885 W art     : b53e8000-b53ec000 r-xp 00000000 b3:17 2890       /system/lib/libSEF4MP4.so
07-05 14:03:49.866  6885  6885 W art     : b53ec000-b53ed000 r--p 00003000 b3:17 2890       /system/lib/libSEF4MP4.so
07-05 14:03:49.866  6885  6885 W art     : b53ed000-b53ee000 rw-p 00004000 b3:17 2890       /system/lib/libSEF4MP4.so
07-05 14:03:49.866  6885  6885 W art     : b53ee000-b5404000 r-xp 00000000 b3:17 335        /system/lib/libSEF.so
07-05 14:03:49.866  6885  6885 W art     : b5404000-b5405000 r--p 00015000 b3:17 335        /system/lib/libSEF.so
07-05 14:03:49.866  6885  6885 W art     : b5405000-b5406000 rw-p 00016000 b3:17 335        /system/lib/libSEF.so
07-05 14:03:49.866  6885  6885 W art     : b5406000-b5413000 r-xp 00000000 b3:17 965        /system/lib/libsfextcp.so
07-05 14:03:49.866  6885  6885 W art     : b5413000-b5414000 r--p 0000c000 b3:17 965        /system/lib/libsfextcp.so
07-05 14:03:49.866  6885  6885 W art     : b5414000-b5415000 rw-p 0000d000 b3:17 965        /system/lib/libsfextcp.so
07-05 14:03:49.866  6885  6885 W art     : b5415000-b5475000 r-xp 00000000 b3:17 201        /system/lib/libsavsff.so
07-05 14:03:49.866  6885  6885 W art     : b5475000-b5478000 rw-p 0005f000 b3:17 201        /system/lib/libsavsff.so
07-05 14:03:49.866  6885  6885 W art     : b5478000-b547c000 rw-p 00000000 00:00 0 
07-05 14:03:49.866  6885  6885 W art     : b547c000-b54dd000 r-xp 00000000 b3:17 160        /system/lib/libsavscmn.so
07-05 14:03:49.866  6885  6885 W art     : b54dd000-b54de000 rw-p 00061000 b3:17 160        /system/lib/libsavscmn.so
07-05 14:03:49.866  6885  6885 W art     : b54de000-b552d000 r-xp 00000000 b3:17 2395       /system/lib/libomafldrm.so
07-05 14:03:49.866  6885  6885 W art     : b552d000-b552f000 r--p 0004e000 b3:17 2395       /system/lib/libomafldrm.so
07-05 14:03:49.866  6885  6885 W art     : b552f000-b5530000 rw-p 00050000 b3:17 2395       /system/lib/libomafldrm.so
07-05 14:03:49.866  6885  6885 W art     : b5530000-b5531000 rw-p 00000000 00:00 0 
07-05 14:03:49.866  6885  6885 W art     : b5531000-b5538000 r-xp 00000000 b3:17 2587       /system/lib/libstagefright_avc_common.so
07-05 14:03:49.866  6885  6885 W art     : b5538000-b5539000 r--p 00006000 b3:17 2587       /system/lib/libstagefright_avc_common.so
07-05 14:03:49.866  6885  6885 W art     : b5539000-b553a000 rw-p 00007000 b3:17 2587       /system/lib/libstagefright_
07-05 14:03:49.866  6885  6885 W art     : avc_common.so
07-05 14:03:49.866  6885  6885 W art     : b553b000-b553e000 r-xp 00000000 b3:17 2563       /system/lib/libstagefright_enc_common.so
07-05 14:03:49.866  6885  6885 W art     : b553e000-b553f000 r--p 00002000 b3:17 2563       /system/lib/libstagefright_enc_common.so
07-05 14:03:49.866  6885  6885 W art     : b553f000-b5540000 rw-p 00003000 b3:17 2563       /system/lib/libstagefright_
07-05 14:03:49.866  6885  6885 W art     : enc_common.so
07-05 14:03:49.866  6885  6885 W art     : b5541000-b5545000 r-xp 00000000 b3:17 2517       /system/lib/libpowermanager.so
07-05 14:03:49.866  6885  6885 W art     : b5545000-b5546000 ---p 00000000 00:00 0 
07-05 14:03:49.866  6885  6885 W art     : b5546000-b5547000 r--p 00004000 b3:17 2517       /system/lib/libpowermanager.so
07-05 14:03:49.866  6885  6885 W art     : b5547000-b5548000 rw-p 00005000 b3:17 2517       /syste
07-05 14:03:49.866  6885  6885 W art     : m/lib/libpowermanager.so
07-05 14:03:49.866  6885  6885 W art     : b5549000-b5566000 r-xp 00000000 b3:17 2732       /system/lib/libvorbisidec.so
07-05 14:03:49.866  6885  6885 W art     : b5566000-b5567000 r--p 0001c000 b3:17 2732       /system/lib/libvorbisidec.so
07-05 14:03:49.866  6885  6885 W art     : b5567000-b5568000 rw-p 0001d000 b3:17 2732       /system/lib/libvorbisidec.so
07-05 14:03:49.866  6885  6885 W art     : b5569000-b556e000 r-xp 00000000 b3:17 2683       /system/lib/libstagefright_yuv.so
07-05 14:03:49.866  6885  6885 W art     : b556e000-b556f000 r--p 00004000 b3:17 2683       /system/lib/libstagefright_yuv.so
07-05 14:03:49.866  6885  6885 W art     : b556f000-b5570000 rw-p 00005000 b3:17 2683       /system/lib/libstagefright_yuv.so
07-05 14:03:49.866  6885  6885 W art     : b5571000-b55a2000 r-xp 00000000 b3:17 1409       /system/lib/libstagefright_omx.so
07-05 14:03:49.866  6885  6885 W art     : b55a2000-b55a5000 r--p 00030000 b3:17 1409       /system/lib/libstagefright_omx.so
07-05 14:03:49.866  6885  6885 W art     : b55a5000-b55a6000 rw-p 00033000 b3:17 1409       /system/lib/libstagefright_omx.so
07-05 14:03:49.866  6885  6885 W art     : b55a7000-b55e2000 r-xp 00000000 b3:17 2136       /system/lib/libopus.so
07-05 14:03:49.866  6885  6885 W art     : b55e2000-b55e3000 r--p 0003a000 b3:17 2136       /system/lib/libopus.so
07-05 14:03:49.866  6885  6885 W art     : b55e3000-b55e4000 rw-p 0003b000 b3:17 2136       /system/lib/libopus.so
07-05 14:03:49.866  6885  6885 W art     : b55e5000-b55ec000 r-xp 00000000 b3:17 2930       /system/lib/libmediautils.so
07-05 14:03:49.866  6885  6885 W art     : b55ec000-b55ed000 ---p 00000000 00:00 0 
07-05 14:03:49.866  6885  6885 W art     : b55ed000-b55ee000 r--p 00007000 b3:17 2930       /system/lib/libmediautils.so
07-05 14:03:49.866  6885  6885 W art     : b55ee000-b55ef000 rw-p 00008000 b3:17 2930       /system/lib/libmediautils.so
07-05 14:03:49.866  6885  6885 W art     : b55ef000-b55f0000 r--p 00000000 00:00 0          [anon:linker_alloc]
07-05 14:03:49.866  6885  6885 W art     : b55f0000-b5607000 r-xp 00000000 b3:17 726        /system/lib/libdrmframework.so
07-05 14:03:49.866  6885  6885 W art     : b5607000-b5608000 ---p 00000000 00:00 0 
07-05 14:03:49.866  6885  6885 W art     : b5608000-b560b000 r--p 00017000 b3:17 726        /system/lib/libdrmframework.so
07-05 14:03:49.866  6885  6885 W art     : b560b000-b560c000 rw-p 0001a000 b3:17 726        /system/lib/libdrmframework.so
07-05 14:03:49.866  6885  6885 W art     : b560c000-b562b000 r-xp 00000000 b3:17 354        /system/lib/libRScpp.so
07-05 14:03:49.866  6885  6885 W art     : b562b000-b562c000 r--p 0001e000 b3:17 354        /system/lib/libRScpp.so
07-05 14:03:49.866  6885  6885 W art     : b562c000-b562d000 rw-p 0001f000 b3:17 354        /system/lib/libRScpp.so
07-05 14:03:49.866  6885  6885 W art     : b562d000-b566b000 r-xp 00000000 b3:17 2566       /system/lib/libRS.so
07-05 14:03:49.866  6885  6885 W art     : b566b000-b566c000 ---p 00000000 00:00 0 
07-05 14:03:49.866  6885  6885 W art     : b566c000-b566e000 r--p 0003e000 b3:17 2566       /system/lib/libRS.so
07-05 14:03:49.866  6885  6885 W art     : b566e000-b566f000 rw-p 00040000 b3:17 2566       /system/lib/libRS.so
07-05 14:03:49.866  6885  6885 W art     : b5670000-b5677000 r-xp 00000000 b3:17 776        /system/lib/libspeexresampler.so
07-05 14:03:49.866  6885  6885 W art     : b5677000-b5678000 r--p 00006000 b3:17 776        /system/lib/libspeexresampler.so
07-05 14:03:49.866  6885  6885 W art     : b5678000-b5679000 rw-p 00007000 b3:17 776        /system/lib/libspeexresampler.so
07-05 14:03:49.866  6885  6885 W art     : b567a000-b567d000 r-xp 00000000 b3:17 764        /system/lib/libsamsungvad.so
07-05 14:03:49.866  6885  6885 W art     : b567d000-b567e000 r--p 00002000 b3:17 764        /system/lib/libsamsungvad.so
07-05 14:03:49.866  6885  6885 W art     : b567e000-b567f000 rw-p 00003000 b3:17 764        /system/lib/libsamsungvad.so
07-05 14:03:49.866  6885  6885 W art     : b567f000-b5685000 r-xp 00000000 b3:17 2449       /system/lib/libedmnativehelper.so
07-05 14:03:49.866  6885  6885 W art     : b5685000-b5686000 ---p 00000000 00:00 0 
07-05 14:03:49.866  6885  6885 W art     : b5686000-b5687000 r--p 00006000 b3:17 2449       /system/lib/libedmnativehelper.so
07-05 14:03:49.866  6885  6885 W art     : b5687000-b5688000 rw-p 00007000 b3:17 2449       /system/lib/libedmnativehelper.so
07-05 14:03:49.866  6885  6885 W art     : b5688000-b5691000 r-xp 00000000 b3:17 2319       /system/lib/libnbaio.so
07-05 14:03:49.866  6885  6885 W art     : b5691000-b5692000 r--p 00008000 b3:17 2319       /system/lib/libnbaio.so
07-05 14:03:49.866  6885  6885 W art     : b5692000-b5693000 rw-p 00009000 b3:17 2319       /system/lib/libnbaio.so
07-05 14:03:49.866  6885  6885 W art     : b5693000-b5724000 r-xp 00000000 b3:17 108        /system/lib/libcrypto-rename.so
07-05 14:03:49.866  6885  6885 W art     : b5724000-b5725000 ---p 00000000 00:00 0 
07-05 14:03:49.866  6885  6885 W art     : b5725000-b5730000 r--p 00091000 b3:17 108        /system/lib/libcrypto-rename.so
07-05 14:03:49.866  6885  6885 W art     : b5730000-b5731000 rw-p 0009c000 b3:17 108        /system/lib/libcrypto-rename.so
07-05 14:03:49.866  6885  6885 W art     : b5732000-b5744000 r-xp 00000000 b3:17 2931       /system/lib/libpcre.so
07-05 14:03:49.866  6885  6885 W art     : b5744000-b5745000 r--p 00011000 b3:17 2931       /system/lib/libpcre.so
07-05 14:03:49.866  6885  6885 W art     : b5745000-b5746000 rw-p 00012000 b3:17 2931       /system/lib/libpcre.so
07-05 14:03:49.866  6885  6885 W art     : b5747000-b574c000 r-xp 00000000 b3:17 2467       /system/lib/libwpa_client.so
07-05 14:03:49.866  6885  6885 W art     : b574c000-b574d000 r--p 00004000 b3:17 2467       /system/lib/libwpa_client.so
07-05 14:03:49.866  6885  6885 W art     : b574d000-b574e000 rw-p 00005000 b3:17 2467       /system/lib/libwpa_client.so
07-05 14:03:49.866  6885  6885 W art     : b574f000-b57bc000 r-xp 00000000 b3:17 2127       /system/lib/libGLES_trace.so
07-05 14:03:49.866  6885  6885 W art     : b57bc000-b57bd000 ---p 00000000 00:00 0 
07-05 14:03:49.866  6885  6885 W art     : b57bd000-b57bf000 r--p 0006d000 b3:17 2127       /system/lib/libGLES_trace.so
07-05 14:03:49.866  6885  6885 W art     : b57bf000-b57c0000 rw-p 0006f000 b3:17 2127       /system/lib/libGLES_trace.so
07-05 14:03:49.866  6885  6885 W art     : b57c0000-b57c1000 r--p 00000000 00:00 0          [anon:linker_alloc]
07-05 14:03:49.866  6885  6885 W art     : b57c1000-b57c8000 r-xp 00000000 b3:17 2579       /system/lib/libsdp_crypto.so
07-05 14:03:49.866  6885  6885 W art     : b57c8000-b57c9000 r--p 00006000 b3:17 2579       /system/lib/libsdp_crypto.so
07-05 14:03:49.866  6885  6885 W art     : b57c9000-b57ca000 rw-p 00007000 b3:17 2579       /system/lib/libsdp_crypto.so
07-05 14:03:49.866  6885  6885 W art     : b57cb000-b584b000 r-xp 00000000 b3:17 2886       /system/lib/libAstcEnc.so
07-05 14:03:49.866  6885  6885 W art     : b584b000-b584c000 ---p 00000000 00:00 0 
07-05 14:03:49.866  6885  6885 W art     : b584c000-b584d000 r--p 00080000 b3:17 2886       /system/lib/libAstcEnc.so
07-05 14:03:49.866  6885  6885 W art     : b584d000-b584e000 rw-p 00081000 b3:17 2886       /system/lib/libAstcEnc.so
07-05 14:03:49.866  6885  6885 W art     : b584e000-b5865000 rw-p 00000000 00:00 0 
07-05 14:03:49.866  6885  6885 W art     : b5865000-b589c000 r-xp 00000000 b3:17 3247       /system/vendor/l
07-05 14:03:49.866  6885  6885 W art     : ib/libqc-opt.so
07-05 14:03:49.866  6885  6885 W art     : b589c000-b589d000 r--p 00036000 b3:17 3247       /system/vendor/lib/libqc-opt.so
07-05 14:03:49.866  6885  6885 W art     : b589d000-b589e000 rw-p 00037000 b3:17 3247       /system/vendor/lib/libqc-opt.so
07-05 14:03:49.866  6885  6885 W art     : b589e000-b58ba000 r-xp 00000000 b3:17 407        /system/lib/libquramimagecodec.so
07-05 14:03:49.866  6885  6885 W art     : b58ba000-b58bb000 r--p 0001b000 b3:17 407        /system/lib/libquramimagecodec.so
07-05 14:03:49.866  6885  6885 W art     : b58bb000-b58bc000 rw-p 0001c000 b3:17 407        /system/lib/libquramimagecodec.so
07-05 14:03:49.866  6885  6885 W art     : b58bd000-b591e000 r-xp 00000000 b3:17 2708       /system/lib/libft2.so
07-05 14:03:49.866  6885  6885 W art     : b591e000-b5920000 r--p 00060000 b3:17 2708       /system/lib/libft2.so
07-05 14:03:49.866  6885  6885 W art     : b5920000-b5921000 rw-p 00062000 b3:17 2708       /system/lib/libft2.so
07-05 14:03:49.866  6885  6885 W art     : b5922000-b5949000 r-xp 00000000 b3:17 2640       /system/lib/libpng.so
07-05 14:03:49.866  6885  6885 W art     : b5949000-b594a000 ---p 00000000 00:00 0 
07-05 14:03:49.866  6885  6885 W art     : b594a000-b594b000 r--p 00027000 b3:17 2640       /system/lib/libpng.so
07-05 14:03:49.866  6885  6885 W art     : b594b000-b594c000 rw-p 00028000 b3:17 2640       /system/lib/libpng.so
07-05 14:03:49.866  6885  6885 W art     : b594d000-b5955000 r-xp 00000000 b3:17 2191       /system/lib/libremotedesktop_client.so
07-05 14:03:49.866  6885  6885 W art     : b5955000-b5957000 r--p 00007000 b3:17 2191       /system/lib/libremotedesktop_client.so
07-05 14:03:49.866  6885  6885 W art     : b5957000-b5958000 rw-p 00009000 b3:17 2191       /system/lib/libremotedesktop_client.so
07-05 14:03:49.866  6885  6885 W art     : b5959000-b595c000 r-xp 00000000 b3:17 2506       /system/lib/libsync.so
07-05 14:03:49.866  6885  6885 W art     : b595c000-b595d000 r--p 00002000 b3:17 2506       /system/lib/libsync.so
07-05 14:03:49.866  6885  6885 W art     : b595d000-b595e000 rw-p 00003000 b3:17 2506       /system/lib/libsync.so
07-05 14:03:49.866  6885  6885 W art     : b595e000-b5962000 r-xp 00000000 b3:17 2639       /system/lib/libstdc++.so
07-05 14:03:49.866  6885  6885 W art     : b5962000-b5963000 ---p 00000000 00:00 0 
07-05 14:03:49.866  6885  6885 W art     : b5963000-b5964000 r--p 00004000 b3:17 2639       /system/lib/libstdc++.so
07-05 14:03:49.866  6885  6885 W art     : b5964000-b5965000 rw-p 00005000 b3:17 2639       /system/lib/libstdc++.so
07-05 14:03:49.866  6885  6885 W art     : b5965000-b5975000 r-xp 00000000 b3:17 359        /system/lib/libunwind.so
07-05 14:03:49.866  6885  6885 W art     : b5975000-b5976000 r--p 0000f000 b3:17 359        /system/lib/libunwind.so
07-05 14:03:49.866  6885  6885 W art     : b5976000-b5977000 rw-p 00010000 b3:17 359        /system/lib/libunwind.so
07-05 14:03:49.866  6885  6885 W art     : b5977000-b59bd000 rw-p 00000000 00:00 0 
07-05 14:03:49.866  6885  6885 W art     : b59bd000-b59c6000 r-xp 00000000 b3:17 2903       /system/lib/libbase.so
07-05 14:03:49.866  6885  6885 W art     : b59c6000-b59c7000 r--p 00008000 b3:17 2903       /system/lib/libbase.so
07-05 14:03:49.866  6885  6885 W art     : b59c7000-b59c8000 rw-p 00009000 b3:17 2903       /system/lib/libbase.so
07-05 14:03:49.866  6885  6885 W art     : b59c9000-b59ce000 r-xp 00000000 b3:17 2659       /system/lib/libeffects.so
07-05 14:03:49.866  6885  6885 W art     : b59ce000-b59cf000 r--p 00004000 b3:17 2659       /system/lib/libeffects.so
07-05 14:03:49.866  6885  6885 W art     : b59cf000-b59d0000 rw-p 00005000 b3:17 2659       /system/lib/libeffects.so
07-05 14:03:49.866  6885  6885 W art     : b59d0000-b59d3000 r-xp 00000000 b3:17 1371       /system/lib/libstagefright_http_support.so
07-05 14:03:49.866  6885  6885 W art     : b59d3000-b59d4000 ---p 00000000 00:00 0 
07-05 14:03:49.866  6885  6885 W art     : b59d4000-b59d5000 r--p 00003000 b3:17 1371       /system/lib/libstagefright_http_support.so
07-05 14:03:49.866  6885  6885 W art     : b59d5000-b59d6000 rw-p 00004000 b3:17 1371       /system/lib/libstagefright_http_support.so
07-05 14:03:49.866  6885  6885 W art     : b59d7000-b59ef000 r-xp 00000000 b3:17 2406       /system/lib/libstagefright_foundation.so
07-05 14:03:49.866  6885  6885 W art     : b59ef000-b59f0000 ---p 00000000 00:00 0 
07-05 14:03:49.866  6885  6885 W art     : b59f0000-b59f1000 r--p 00018000 b3:17 2406       /system/lib/libstagefright_foundation.so
07-05 14:03:49.866  6885  6885 W art     : b59f1000-b59f2000 rw-p 00019000 b3:17 2406       /system/lib/libstagefright_foundation.so
07-05 14:03:49.866  6885  6885 W art     : b59f3000-b5b8d000 r-xp 00000000 b3:17 2790       /system/lib/libstagefright.so
07-05 14:03:49.866  6885  6885 W art     : b5b8d000-b5b8e000 ---p 00000000 00:00 0 
07-05 14:03:49.866  6885  6885 W art     : b5b8e000-b5b9b000 r--p 0019a000 b3:17 2790       /system/lib/libstagefright.so
07-05 14:03:49.866  6885  6885 W art     : b5b9b000-b5b9c000 rw-p 001a7000 b3:17 2790       /system/lib/libstagefright.so
07-05 14:03:49.866  6885  6885 W art     : b5b9c000-b5ba0000 r-xp 00000000 b3:17 2681       /system/lib/libpersona.so
07-05 14:03:49.866  6885  6885 W art     : b5ba0000-b5ba1000 ---p 00000000 00:00 0 
07-05 14:03:49.866  6885  6885 W art     : b5ba1000-b5ba2000 r--p 00004000 b3:17 2681       /system/lib/libpersona.so
07-05 14:03:49.866  6885  6885 W art     : b5ba2000-b5ba3000 rw-p 00005000 b3:17 2681       /system/lib/libpersona.so
07-05 14:03:49.866  6885  6885 W art     : b5ba3000-b5bb6000 r-xp 00000000 b3:17 2920       /system/lib/libimagefilter.so
07-05 14:03:49.866  6885  6885 W art     : b5bb6000-b5bb7000 r--p 00012000 b3:17 2920       /system/lib/libimagefilter.so
07-05 14:03:49.866  6885  6885 W art     : b5bb7000-b5bb8000 rw-p 00013000 b3:17 2920       /system/lib/libimagefilter.so
07-05 14:03:49.866  6885  6885 W art     : b5bb8000-b5bb9000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
07-05 14:03:49.866  6885  6885 W art     : b5bb9000-b5c04000 r-xp 00000000 b3:17 2156       /system/lib/libsecure_storage.so
07-05 14:03:49.866  6885  6885 W art     : b5c04000-b5c05000 r--p 0004a000 b3:17 2156       /system/lib/libsecure_storage.so
07-05 14:03:49.866  6885  6885 W art     : b5c05000-b5c06000 rw-p 0004b000 b3:17 2156       /system/lib/libsecure_storage.so
07-05 14:03:49.866  6885  6885 W art     : b5c06000-b5c08000 rw-p 00000000 00:00 0 
07-05 14:03:49.866  6885  6885 W art     : b5c09000-b5c1a000 r-xp 00000000 b3:17 2258       /system/lib/libsamsungeffect.so
07-05 14:03:49.866  6885  6885 W art     : b5c1a000-b5c1b000 ---p 00000000 00:00 0 
07-05 14:03:49.866  6885  6885 W art     : b5c1b000-b5c1c000 r--p 00011000 b3:17 2258       /system/lib/libsamsungeffect.so
07-05 14:03:49.866  6885  6885 W art     : b5c1c000-b5c1d000 rw-p 00012000 b3:17 2258       /system/lib/libsamsungeffect.so
07-05 14:03:49.866  6885  6885 W art     : b5c1e000-b5c28000 r-xp 00000000 b3:17 2321       /system/lib/libsensorhub.so
07-05 14:03:49.866  6885  6885 W art     : b5c28000-b5c2a000 r--p 00009000 b3:17 2321       /system/lib/libsensorhub.so
07-05 14:03:49.866  6885  6885 W art     : b5c2a000-b5c2b000 rw-p 0000b000 b3:17 2321       /system/lib/libsensorhub.so
07-05 14:03:49.866  6885  6885 W art     : b5c2b000-b5c44000 r-xp 00000000 b3:17 2929       /system/lib/libmctraster.so
07-05 14:03:49.866  6885  6885 W art     : b5c44000-b5c45000 r--p 00018000 b3:17 2929       /system/lib/libmctraster.so
07-05 14:03:49.866  6885  6885 W art     : b5c45000-b5c48000 rw-p 00019000 b3:17 2929       /system/lib/libmctraster.so
07-05 14:03:49.866  6885  6885 W art     : b5c48000-b5c4c000 rw-p 00000000 00:00 0 
07-05 14:03:49.866  6885  6885 W art     : b5c4c000-b5cc0000 r-xp 00000000 b3:17 2777       /system/lib/libhwui.so
07-05 14:03:49.866  6885  6885 W art     : b5cc0000-b5cc1000 ---p 00000000 00:00 0 
07-05 14:03:49.866  6885  6885 W art     : b5cc1000-b5cc4000 r--p 00074000 b3:17 2777       /system/lib/libhwui.so
07-05 14:03:49.866  6885  6885 W art     : b5cc4000-b5cc5000 rw-p 00077000 b3:17 2777       /system/lib/libhwui.so
07-05 14:03:49.866  6885  6885 W art     : b5cc5000-b5cc6000 r--p 00000000 00:00 0 
07-05 14:03:49.866  6885  6885 W art     : b5cc6000-b5cc9000 r-xp 00000000 b3:17 2497       /system/lib/libcc_manager.so
07-05 14:03:49.866  6885  6885 W art     : b5cc9000-b5cca000 r--p 00002000 b3:17 2497       /system/lib/libcc_manager.so
07-05 14:03:49.866  6885  6885 W art     : b5cca000-b5ccb000 rw-p 00003000 b3:17 2497       /system/lib/libcc_manager.so
07-05 14:03:49.866  6885  6885 W art     : b5ccb000-b5ccc000 r--p 00000000 00:00 0          [anon:linker_alloc]
07-05 14:03:49.866  6885  6885 W art     : b5ccc000-b5cd1000 r-xp 00000000 b3:17 2463       /system/lib/libsecnativefeature.so
07-05 14:03:49.866  6885  6885 W art     : b5cd1000-b5cd2000 r--p 00004000 b3:17 2463       /system/lib/libsecnativefeature.so
07-05 14:03:49.866  6885  6885 W art     : b5cd2000-b5cd3000 rw-p 00005000 b3:17 2463       /system/lib/libsecnativefeature.so
07-05 14:03:49.866  6885  6885 W art     : b5cd3000-b5cd4000 r--p 00000000 00:00 0          [anon:linker_alloc]
07-05 14:03:49.866  6885  6885 W art     : b5cd4000-b5cd7000 r-xp 00000000 b3:17 2939       /system/lib/libradio_metadata.so
07-05 14:03:49.866  6885  6885 W art     : b5cd7000-b5cd8000 r--p 00002000 b3:17 2939       /system/lib/libradio_metadata.so
07-05 14:03:49.866  6885  6885 W art     : b5cd8000-b5cd9000 rw-p 00003000 b3:17 2939       /system/lib/libradio_metadata.so
07-05 14:03:49.866  6885  6885 W art     : b5cd9000-b5cda000 r--p 00000000 00:00 0          [anon:linker_alloc]
07-05 14:03:49.866  6885  6885 W art     : b5cda000-b5cde000 r-xp 00000000 b3:17 808        /system/lib/libnativebridge.so
07-05 14:03:49.866  6885  6885 W art     : b5cde000-b5cdf000 r--p 00003000 b3:17 808        /system/lib/libnativebridge.so
07-05 14:03:49.866  6885  6885 W art     : b5cdf000-b5ce0000 rw-p 00004000 b3:17 808        /system/lib/libnativebridge.so
07-05 14:03:49.866  6885  6885 W art     : b5ce0000-b5ce1000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
07-05 14:03:49.866  6885  6885 W art     : b5ce1000-b5ce5000 r-xp 00000000 b3:17 2582       /system/lib/libprocessgroup.so
07-05 14:03:49.866  6885  6885 W art     : b5ce5000-b5ce6000 r--p 00003000 b3:17 2582       /system/lib/libprocessgroup.so
07-05 14:03:49.866  6885  6885 W art     : b5ce6000-b5ce7000 rw-p 00004000 b3:17 2582       /system/lib/libprocessgroup.so
07-05 14:03:49.866  6885  6885 W art     : b5ce7000-b5ce8000 r--p 00000000 00:00 0          [anon:linker_alloc]
07-05 14:03:49.866  6885  6885 W art     : b5ce8000-b5cf6000 r-xp 00000000 b3:17 472        /system/lib/libminikin.so
07-05 14:03:49.866  6885  6885 W art     : b5cf6000-b5cf7000 ---p 00000000 00:00 0 
07-05 14:03:49.866  6885  6885 W art     : b5cf7000-b5cf8000 r--p 0000e000 b3:17 472        /system/lib/libminikin.so
07-05 14:03:49.866  6885  6885 W art     : b5cf8000-b5cf9000 rw-p 0000f000 b3:17 472        /system/lib/libminikin.so
07-05 14:03:49.866  6885  6885 W art     : b5cf9000-b5d03000 r-xp 00000000 b3:17 2193       /system/lib/libsoundtrigger.so
07-05 14:03:49.866  6885  6885 W art     : b5d03000-b5d06000 r--p 00009000 b3:17 2193       /system/lib/libsoundtrigger.so
07-05 14:03:49.866  6885  6885 W art     : b5d06000-b5d07000 rw-p 0000c000 b3:17 2193       /system/lib/libsoundtrigger.so
07-05 14:03:49.866  6885  6885 W art     : b5d07000-b5d08000 r--p 00000000 00:00 0          [anon:linker_alloc]
07-05 14:03:49.866  6885  6885 W art     : b5d08000-b5d12000 r-xp 00000000 b3:17 2938       /system/lib/libradio.so
07-05 14:03:49.866  6885  6885 W art     : b5d12000-b5d15000 r--p 00009000 b3:17 2938       /system/lib/libradio.so
07-05 14:03:49.866  6885  6885 W art     : b5d15000-b5d16000 rw-p 0000c000 b3:17 2938       /system/lib/libradio.so
07-05 14:03:49.866  6885  6885 W art     : b5d16000-b5d1a000 r-xp 00000000 b3:17 2413       /system/lib/libnetd_client.so
07-05 14:03:49.866  6885  6885 W art     : b5d1a000-b5d1b000 r--p 00003000 b3:17 2413       /system/lib/libnetd_client.so
07-05 14:03:49.866  6885  6885 W art     : b5d1b000-b5d1c000 rw-p 00004000 b3:17 2413       /system/lib/libnetd_client.so
07-05 14:03:49.866  6885  6885 W art     : b5d1c000-b5d1d000 r--p 00000000 00:00 0          [anon:linker_alloc]
07-05 14:03:49.866  6885  6885 W art     : b5d1d000-b5d2a000 r-xp 00000000 b3:17 2372       /system/lib/libimg_utils.so
07-05 14:03:49.866  6885  6885 W art     : b5d2a000-b5d2c000 r--p 0000c000 b3:17 2372       /system/lib/libimg_utils.so
07-05 14:03:49.866  6885  6885 W art     : b5d2c000-b5d2d000 rw-p 0000e000 b3:17 2372       /system/lib/libimg_utils.so
07-05 14:03:49.866  6885  6885 W art     : b5d2d000-b613f000 r-xp 00000000 b3:17 299        /system/lib/libpdfium.so
07-05 14:03:49.866  6885  6885 W art     : b613f000-b6140000 ---p 00000000 00:00 0 
07-05 14:03:49.866  6885  6885 W art     : b6140000-b6149000 r--p 00412000 b3:17 299        /system/lib/libpdfium.so
07-05 14:03:49.866  6885  6885 W art     : b6149000-b614d000 rw-p 0041b000 b3:17 299        /system/lib/libpdfium.so
07-05 14:03:49.866  6885  6885 W art     : b614d000-b614e000 rw-p 00000000 00:00 0 
07-05 14:03:49.866  6885  6885 W art     : b614e000-b6155000 r-xp 00000000 b3:17 2571       /system/lib/libaudioutils.so
07-05 14:03:49.866  6885  6885 W art     : b6155000-b6156000 r--p 00006000 b3:17 2571       /system/lib/libaudioutils.so
07-05 14:03:49.866  6885  6885 W art     : b6156000-b6157000 rw-p 00007000 b3:17 2571       /system/lib/libaudioutils.so
07-05 14:03:49.866  6885  6885 W art     : b6157000-b6158000 r--p 00000000 00:00 0          [anon:linker_alloc]
07-05 14:03:49.866  6885  6885 W art     : b6158000-b6173000 r-xp 00000000 b3:17 1184       /system/lib/libz.so
07-05 14:03:49.866  6885  6885 W art     : b6173000-b6174000 r--p 0001a000 b3:17 1184       /system/lib/libz.so
07-05 14:03:49.866  6885  6885 W art     : b6174000-b6175000 rw-p 0001b000 b3:17 1184       /system/lib/libz.so
07-05 14:03:49.866  6885  6885 W art     : b6175000-b6176000 r--p 00000000 00:00 0          [anon:linker_alloc]
07-05 14:03:49.866  6885  6885 W art     : b6176000-b61c2000 r-xp 00000000 b3:17 342        /system/lib/libharfbuzz_ng.so
07-05 14:03:49.866  6885  6885 W art     : b61c2000-b61c3000 ---p 00000000 00:00 0 
07-05 14:03:49.866  6885  6885 W art     : b61c3000-b61c4000 r--p 0004c000 b3:17 342        /system/lib/libharfbuzz_ng.so
07-05 14:03:49.866  6885  6885 W art     : b61c4000-b61c5000 rw-p 0004d000 b3:17 342        /system/lib/libharfbuzz_ng.so
07-05 14:03:49.866  6885  6885 W art     : b61c5000-b61c6000 r--p 00000000 00:00 0          [anon:linker_alloc]
07-05 14:03:49.866  6885  6885 W art     : b61c6000-b61ca000 r-xp 00000000 b3:17 2688       /system/lib/libusbhost.so
07-05 14:03:49.866  6885  6885 W art     : b61ca000-b61cb000 ---p 00000000 00:00 0 
07-05 14:03:49.866  6885  6885 W art     : b61cb000-b61cc000 r--p 00004000 b3:17 2688       /system/lib/libusbhost.so
07-05 14:03:49.866  6885  6885 W art     : b61cc000-b61cd000 rw-p 00005000 b3:17 2688       /system/lib/libusbhost.so
07-05 14:03:49.876  6885  6885 W art     : b61cd000-b6205000 r-xp 00000000 b3:17 2749       /system/lib/libjpeg.so
07-05 14:03:49.876  6885  6885 W art     : b6205000-b6206000 r--p 00037000 b3:17 2749       /system/lib/libjpeg.so
07-05 14:03:49.876  6885  6885 W art     : b6206000-b6207000 rw-p 00038000 b3:17 2749       /system/lib/libjpeg.so
07-05 14:03:49.876  6885  6885 W art     : b6207000-b6208000 r--p 00000000 00:00 0          [anon:linker_alloc]
07-05 14:03:49.876  6885  6885 W art     : b6208000-b62a6000 r-xp 00000000 b3:17 409        /system/lib/libmedia.so
07-05 14:03:49.876  6885  6885 W art     : b62a6000-b62a7000 ---p 00000000 00:00 0 
07-05 14:03:49.876  6885  6885 W art     : b62a7000-b62c5000 r--p 0009e000 b3:17 409        /system/lib/libmedia.so
07-05 14:03:49.876  6885  6885 W art     : b62c5000-b62c6000 rw-p 000bc000 b3:17 409        /system/lib/libmedia.so
07-05 14:03:49.876  6885  6885 W art     : b62c6000-b6439000 r-xp 00000000 b3:17 2204       /system/lib/libicui18n.so
07-05 14:03:49.876  6885  6885 W art     : b6439000-b6444000 r--p 00172000 b3:17 2204       /system/lib/libicui18n.so
07-05 14:03:49.876  6885  6885 W art     : b6444000-b6445000 rw-p 0017d000 b3:17 2204       /system/lib/libicui18n.so
07-05 14:03:49.876  6885  6885 W art     : b6445000-b655c000 r-xp 00000000 b3:17 2041       /system/lib/libicuuc.so
07-05 14:03:49.876  6885  6885 W art     : b655c000-b6567000 r--p 00116000 b3:17 2041       /system/lib/libicuuc.so
07-05 14:03:49.876  6885  6885 W art     : b6567000-b6568000 rw-p 00121000 b3:17 2041       /system/lib/libicuuc.so
07-05 14:03:49.876  6885  6885 W art     : b6568000-b656c000 rw-p 00000000 00:00 0 
07-05 14:03:49.876  6885  6885 W art     : b656c000-b6590000 r-xp 00000000 b3:17 405        /system/lib/libssl.so
07-05 14:03:49.876  6885  6885 W art     : b6590000-b6592000 r--p 00023000 b3:17 405        /system/lib/libssl.so
07-05 14:03:49.876  6885  6885 W art     : b6592000-b6593000 rw-p 00025000 b3:17 405        /system/lib/libssl.so
07-05 14:03:49.876  6885  6885 W art     : b6593000-b6639000 r-xp 00000000 b3:17 110        /system/lib/libcrypto.so
07-05 14:03:49.876  6885  6885 W art     : b6639000-b6646000 r--p 000a5000 b3:17 110        /system/lib/libcrypto.so
07-05 14:03:49.876  6885  6885 W art     : b6646000-b6647000 rw-p 000b2000 b3:17 110        /system/lib/libcrypto.so
07-05 14:03:49.876  6885  6885 W art     : b6647000-b6648000 rw-p 00000000 00:00 0 
07-05 14:03:49.876  6885  6885 W art     : b6648000-b669b000 r-xp 00000000 b3:17 2736       /system/lib/libsonivox.so
07-05 14:03:49.876  6885  6885 W art     : b669b000-b669c000 ---p 00000000 00:00 0 
07-05 14:03:49.876  6885  6885 W art     : b669c000-b669d000 r--p 00053000 b3:17 2736       /system/lib/libsonivox.so
07-05 14:03:49.876  6885  6885 W art     : b669d000-b669e000 rw-p 00054000 b3:17 2736       /system/lib/libsonivox.so
07-05 14:03:49.876  6885  6885 W art     : b669e000-b66a3000 rw-p 00000000 00:00 0 
07-05 14:03:49.876  6885  6885 W art     : b66a3000-b66b5000 r-xp 00000000 b3:17 2641       /system/lib/libselinux.so
07-05 14:03:49.876  6885  6885 W art     : b66b5000-b66b6000 ---p 00000000 00:00 0 
,07-05 14:03:49.876  6885  6885 W art     : b66b6000-b66b7000 r--p 00012000 b3:17 2641       /system/lib/libselinux.so
07-05 14:03:49.876  6885  6885 W art     : b66b7000-b66b8000 rw-p 00013000 b3:17 2641       /system/lib/libselinux.so
07-05 14:03:49.876  6885  6885 W art     : b66b8000-b66bf000 r-xp 00000000 b3:17 2636       /system/lib/libhardware_legacy.so
07-05 14:03:49.876  6885  6885 W art     : b66bf000-b66c0000 r--p 00007000 b3:17 2636       /system/lib/libhardware_legacy.so
07-05 14:03:49.876  6885  6885 W art     : b66c0000-b66c1000 rw-p 00008000 b3:17 2636       /system/lib/libhardware_legacy.so
07-05 14:03:49.876  6885  6885 W art     : b66c1000-b66c2000 rw-p 00000000 00:00 0 
07-05 14:03:49.876  6885  6885 W art     : b66c2000-b66c5000 r-xp 00000000 b3:17 2414       /system/lib/libhardware.so
07-05 14:03:49.876  6885  6885 W art     : b66c5000-b66c6000 r--p 00002000 b3:17 2414       /system/lib/libhardware.so
07-05 14:03:49.876  6885  6885 W art     : b66c6000-b66c7000 rw-p 00003000 b3:17 2414       /system/lib/libhardware.so
07-05 14:03:49.876  6885  6885 W art     : b66c7000-b66cb000 r-xp 00000000 b3:17 2565       /system/lib/libETC1.so
07-05 14:03:49.876  6885  6885 W art     : b66cb000-b66cc000 r--p 00003000 b3:17 2565       /system/lib/libETC1.so
07-05 14:03:49.876  6885  6885 W art     : b66cc000-b66cd000 rw-p 00004000 b3:17 2565       /system/lib/libETC1.so
07-05 14:03:49.876  6885  6885 W art     : b66cd000-b66db000 r-xp 00000000 b3:17 2725       /system/lib/libGLESv2.so
07-05 14:03:49.876  6885  6885 W art     : b66db000-b66dc000 ---p 00000000 00:00 0 
07-05 14:03:49.876  6885  6885 W art     : b66dc000-b66dd000 r--p 0000e000 b3:17 2725       /system/lib/libGLESv2.so
07-05 14:03:49.876  6885  6885 W art     : b66dd000-b66de000 rw-p 0000f000 b3:17 2725       /system/lib/libGLESv2.so
07-05 14:03:49.876  6885  6885 W art     : b66de000-b66e7000 r-xp 00000000 b3:17 2253       /system/lib/libGLESv1_CM.so
07-05 14:03:49.876  6885  6885 W art     : b66e7000-b66e8000 r--p 00008000 b3:17 2253       /system/lib/libGLESv1_CM.so
07-05 14:03:49.876  6885  6885 W art     : b66e8000-b66e9000 rw-p 00009000 b3:17 2253       /system/lib/libGLESv1_CM.so
07-05 14:03:49.876  6885  6885 W art     : b66e9000-b674f000 r-xp 00000000 b3:17 825        /system/lib/libEGL.so
07-05 14:03:49.876  6885  6885 W art     : b674f000-b6750000 ---p 00000000 00:00 0 
07-05 14:03:49.876  6885  6885 W art     : b6750000-b6752000 r--p 00066000 b3:17 825        /system/lib/libEGL.so
07-05 14:03:49.876  6885  6885 W art     : b6752000-b675b000 rw-p 00068000 b3:17 825        /system/lib/libEGL.so
07-05 14:03:49.876  6885  6885 W art     : b675b000-b675e000 rw-p 00000000 00:00 0 
07-05 14:03:49.876  6885  6885 W art     : b675e000-b67f5000 r-xp 00000000 b3:17 688        /system/lib/libsqlite.so
07-05 14:03:49.876  6885  6885 W art     : b67f5000-b67f7000 r--p 00096000 b3:17 688        /system/lib/libsqlite.so
07-05 14:03:49.876  6885  6885 W art     : b67f7000-b67f8000 rw-p 00098000 b3:17 688        /system/lib/libsqlite.so
07-05 14:03:49.876  6885  6885 W art     : b67f8000-b67f9000 rw-p 00000000 00:00 0 
07-05 14:03:49.876  6885  6885 W art     : b67f9000-b6b1a000 r-xp 00000000 b3:17 286        /system/lib/libskia.so
07-05 14:03:49.876  6885  6885 W art     : b6b1a000-b6b1b000 ---p 00000000 00:00 0 
07-05 14:03:49.876  6885  6885 W art     : b6b1b000-b6b36000 r--p 00321000 b3:17 286        /system/lib/libskia.so
07-05 14:03:49.876  6885  6885 W art     : b6b36000-b6b3a000 rw-p 0033c000 b3:17 286        /system/lib/libskia.so
07-05 14:03:49.876  6885  6885 W art     : b6b3a000-b6b3f000 rw-p 00000000 00:00 0 
07-05 14:03:49.876  6885  6885 W art     : b6b3f000-b6b47000 r-xp 00000000 b3:17 2599       /system/lib/libcamera_metadata.so
07-05 14:03:49.876  6885  6885 W art     : b6b47000-b6b48000 r--p 00007000 b3:17 2599       /system/lib/libcamera_metadata.so
07-05 14:03:49.876  6885  6885 W art     : b6b48000-b6b49000 rw-p 00008000 b3:17 2599       /system/lib/libcamera_metadata.so
07-05 14:03:49.876  6885  6885 W art     : b6b49000-b6b77000 r-xp 00000000 b3:17 564        /system/lib/libcamera_client.so
07-05 14:03:49.876  6885  6885 W art     : b6b77000-b6b78000 ---p 00000000 00:00 0 
07-05 14:03:49.876  6885  6885 W art     : b6b78000-b6b7f000 r--p 0002e000 b3:17 564        /system/lib/libcamera_client.so
07-05 14:03:49.876  6885  6885 W art     : b6b7f000-b6b80000 rw-p 00035000 b3:17 564        /system/lib/libcamera_client.so
07-05 14:03:49.876  6885  6885 W art     : b6b80000-b6bc6000 r-xp 00000000 b3:17 1049       /system/lib/libinputflinger.so
07-05 14:03:49.876  6885  6885 W art     : b6bc6000-b6bc7000 ---p 00000000 00:00 0 
07-05 14:03:49.876  6885  6885 W art     : b6bc7000-b6bca000 r--p 00046000 b3:17 1049       /system/lib/libinputflinger.so
07-05 14:03:49.876  6885  6885 W art     : b6bca000-b6bcb000 rw-p 00049000 b3:17 1049       /system/lib/libinputflinger.so
07-05 14:03:49.876  6885  6885 W art     : b6bcb000-b6be6000 r-xp 00000000 b3:17 2538       /system/lib/libinput.so
07-05 14:03:49.876  6885  6885 W art     : b6be6000-b6bea000 r--p 0001a000 b3:17 2538       /system/lib/libinput.so
07-05 14:03:49.876  6885  6885 W art     : b6bea000-b6beb000 rw-p 0001e000 b3:17 2538       /system/lib/libinput.so
07-05 14:03:49.876  6885  6885 W art     : b6beb000-b6c38000 r-xp 00000000 b3:17 2763       /system/lib/libgui.so
07-05 14:03:49.876  6885  6885 W art     : b6c38000-b6c39000 ---p 00000000 00:00 0 
07-05 14:03:49.876  6885  6885 W art     : b6c39000-b6c45000 r--p 0004d000 b3:17 2763       /system/lib/libgui.so
07-05 14:03:49.876  6885  6885 W art     : b6c45000-b6c46000 rw-p 00059000 b3:17 2763       /system/lib/libgui.so
07-05 14:03:49.876  6885  6885 W art     : b6c46000-b6c53000 r-xp 00000000 b3:17 2719       /system/lib/libui.so
07-05 14:03:49.876  6885  6885 W art     : b6c53000-b6c54000 ---p 00000000 00:00 0 
07-05 14:03:49.876  6885  6885 W art     : b6c54000-b6c55000 r--p 0000d000 b3:17 2719       /system/lib/libui.so
07-05 14:03:49.876  6885  6885 W art     : b6c55000-b6c56000 rw-p 0000e000 b3:17 2719       /system/lib/libui.so
07-05 14:03:49.876  6885  6885 W art     : b6c56000-b6c5e000 r-xp 00000000 b3:17 2160       /system/lib/libnetutils.so
07-05 14:03:49.876  6885  6885 W art     : b6c5e000-b6c5f000 ---p 00000000 00:00 0 
07-05 14:03:49.876  6885  6885 W art     : b6c5f000-b6c60000 r--p 00008000 b3:17 2160       /system/lib/libnetutils.so
07-05 14:03:49.876  6885  6885 W art     : b6c60000-b6c61000 rw-p 00009000 b3:17 2160       /system/lib/libnetutils.so
07-05 14:03:49.876  6885  6885 W art     : b6c61000-b6c68000 r-xp 00000000 b3:17 1217       /system/lib/libnativehelper.so
07-05 14:03:49.876  6885  6885 W art     : b6c68000-b6c69000 r--p 00006000 b3:17 1217       /system/lib/libnativehelper.so
07-05 14:03:49.876  6885  6885 W art     : b6c69000-b6c6a000 rw-p 00007000 b3:17 1217       /system/lib/libnativehelper.so
07-05 14:03:49.876  6885  6885 W art     : b6c6a000-b6c7e000 r-xp 00000000 b3:17 2082       /system/lib/libexpat.so
07-05 14:03:49.876  6885  6885 W art     : b6c7e000-b6c80000 r--p 00013000 b3:17 2082       /system/lib/libexpat.so
07-05 14:03:49.876  6885  6885 W art     : b6c80000-b6c81000 rw-p 00015000 b3:17 2082       /system/lib/libexpat.so
07-05 14:03:49.876  6885  6885 W art     : b6c81000-b6ca9000 r-xp 00000000 b3:17 1012       /system/lib/libandroidfw.so
07-05 14:03:49.876  6885  6885 W art     : b6ca9000-b6cab000 r--p 00027000 b3:17 1012       /system/lib/libandroidfw.so
07-05 14:03:49.876  6885  6885 W art     : b6cab000-b6cac000 rw-p 00029000 b3:17 1012       /system/lib/libandroidfw.so
07-05 14:03:49.876  6885  6885 W art     : b6cac000-b6caf000 r-xp 00000000 b3:17 2457       /system/lib/libmemtrack.so
07-05 14:03:49.876  6885  6885 W art     : b6caf000-b6cb0000 r--p 00002000 b3:17 2457       /system/lib/libmemtrack.so
07-05 14:03:49.876  6885  6885 W art     : b6cb0000-b6cb1000 rw-p 00003000 b3:17 2457       /system/lib/libmemtrack.so
07-05 14:03:49.876  6885  6885 W art     : b6cb1000-b6cba000 r-xp 00000000 b3:17 2581       /system/lib/libbacktrace.so
07-05 14:03:49.876  6885  6885 W art     : b6cba000-b6cbb000 r--p 00008000 b3:17 2581       /system/lib/libbacktrace.so
07-05 14:03:49.876  6885  6885 W art     : b6cbb000-b6cbc000 rw-p 00009000 b3:17 2581       /system/lib/libbacktrace.so
07-05 14:03:49.876  6885  6885 W art     : b6cbc000-b6cdc000 r-xp 00000000 b3:17 2560       /system/lib/libm.so
07-05 14:03:49.876  6885  6885 W art     : b6cdc000-b6cdd000 r--p 0001f000 b3:17 2560       /system/lib/libm.so
07-05 14:03:49.876  6885  6885 W art     : b6cdd000-b6cde000 rw-p 00020000 b3:17 2560       /system/lib/libm.so
07-05 14:03:49.876  6885  6885 W art     : b6cde000-b6d51000 r-xp 00000000 b3:17 328        /system/lib/libc.so
07-05 14:03:49.876  6885  6885 W art     : b6d51000-b6d55000 r--p 00072000 b3:17 328        /system/lib/libc.so
07-05 14:03:49.876  6885  6885 W art     : b6d55000-b6d58000 rw-p 00076000 b3:17 328        /system/lib/libc.so
07-05 14:03:49.876  6885  6885 W art     : b6d58000-b6d62000 rw-p 00000000 00:00 0 
07-05 14:03:49.876  6885  6885 W art     : b6d62000-b6dea000 r-xp 00000000 b3:17 1016       /system/lib/libc++.so
07-05 14:03:49.876  6885  6885 W art     : b6dea000-b6deb000 ---p 00000000 00:00 0 
07-05 14:03:49.876  6885  6885 W art     : b6deb000-b6def000 r--p 00088000 b3:17 1016       /system/lib/libc++.so
07-05 14:03:49.876  6885  6885 W art     : b6def000-b6df0000 rw-p 0008c000 b3:17 1016       /system/lib/libc++.so
07-05 14:03:49.876  6885  6885 W art     : b6df0000-b6df1000 rw-p 00000000 00:00 0 
07-05 14:03:49.876  6885  6885 W art     : b6df1000-b6e1a000 r-xp 00000000 b3:17 1253       /system/lib/libwilhelm.so
07-05 14:03:49.876  6885  6885 W art     : b6e1a000-b6e1b000 ---p 00000000 00:00 0 
07-05 14:03:49.876  6885  6885 W art     : b6e1b000-b6e1e000 r--p 00029000 b3:17 1253       /system/lib/libwilhelm.so
07-05 14:03:49.876  6885  6885 W art     : b6e1e000-b6e1f000 rw-p 0002c000 b3:17 1253       /system/lib/libwilhelm.so
07-05 14:03:49.876  6885  6885 W art     : b6e1f000-b6ef9000 r-xp 00000000 b3:17 460        /system/lib/libandroid_runtime.so
07-05 14:03:49.876  6885  6885 W art     : b6ef9000-b6f00000 r--p 000d9000 b3:17 460        /system/lib/libandroid_runtime.so
07-05 14:03:49.876  6885  6885 W art     : b6f00000-b6f08000 rw-p 000e0000 b3:17 460        /system/lib/libandroid_runtime.so
07-05 14:03:49.876  6885  6885 W art     : b6f08000-b6f09000 rw-p 00000000 00:00 0 
07-05 14:03:49.876  6885  6885 W art     : b6f09000-b6f0a000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
07-05 14:03:49.876  6885  6885 W art     : b6f0a000-b6f0b000 rw-p 00000000 00:00 0          [anon:linker_alloc_64]
07-05 14:03:49.876  6885  6885 W art     : b6f0b000-b6f0c000 rw-p 00000000 00:00 0          [anon:linker_alloc]
07-05 14:03:49.876  6885  6885 W art     : b6f0c000-b6f0f000 r--p 00000000 00:00 0          [anon:linker_alloc]
07-05 14:03:49.876  6885  6885 W art     : b6f0f000-b6f34000 r-xp 00000000 b3:17 2107       /system/lib/libbinder.so
07-05 14:03:49.876  6885  6885 W art     : b6f34000-b6f35000 ---p 00000000 00:00 0 
07-05 14:03:49.876  6885  6885 W art     : b6f35000-b6f3c000 r--p 00025000 b3:17 2107       /system/lib/libbinder.so
07-05 14:03:49.876  6885  6885 W art     : b6f3c000-b6f3d000 rw-p 0002c000 b3:17 2107       /system/lib/libbinder.so
07-05 14:03:49.876  6885  6885 W art     : b6f3d000-b6f44000 r-xp 00000000 b3:17 2644       /system/lib/liblog.so
07-05 14:03:49.876  6885  6885 W art     : b6f44000-b6f45000 r--p 00006000 b3:17 2644       /system/lib/liblog.so
07-05 14:03:49.876  6885  6885 W art     : b6f45000-b6f46000 rw-p 00007000 b3:17 2644       /system/lib/liblog.so
07-05 14:03:49.876  6885  6885 W art     : b6f46000-b6f47000 r--p 00000000 00:00 0          [anon:linker_alloc]
07-05 14:03:49.876  6885  6885 W art     : b6f47000-b6f5f000 r-xp 00000000 b3:17 2149       /system/lib/libutils.so
07-05 14:03:49.876  6885  6885 W art     : b6f5f000-b6f60000 ---p 00000000 00:00 0 
07-05 14:03:49.876  6885  6885 W art     : b6f60000-b6f61000 r--p 00018000 b3:17 2149       /system/lib/libutils.so
07-05 14:03:49.876  6885  6885 W art     : b6f61000-b6f62000 rw-p 00019000 b3:17 2149       /system/lib/libutils.so
07-05 14:03:49.876  6885  6885 W art     : b6f62000-b6f70000 r-xp 00000000 b3:17 2714       /system/lib/libcutils.so
07-05 14:03:49.876  6885  6885 W art     : b6f70000-b6f71000 ---p 00000000 00:00 0 
07-05 14:03:49.876  6885  6885 W art     : b6f71000-b6f72000 r--p 0000e000 b3:17 2714       /system/lib/libcutils.so
07-05 14:03:49.876  6885  6885 W art     : b6f72000-b6f73000 rw-p 0000f000 b3:17 2714       /system/lib/libcutils.so
07-05 14:03:49.876  6885  6885 W art     : b6f73000-b6f74000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
07-05 14:03:49.876  6885  6885 W art     : b6f74000-b6f76000 r--p 00000000 00:00 0          [anon:linker_alloc]
07-05 14:03:49.876  6885  6885 W art     : b6f76000-b6f77000 rw-p 00000000 00:00 0          [anon:linker_alloc]
07-05 14:03:49.876  6885  6885 W art     : b6f77000-b6f78000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
07-05 14:03:49.876  6885  6885 W art     : b6f78000-b6f79000 rw-p 00000000 00:00 0          [anon:linker_alloc_32]
07-05 14:03:49.876  6885  6885 W art     : b6f79000-b6f7a000 r--p 00000000 00:00 0          [anon:linker_alloc]
07-05 14:03:49.876  6885  6885 W art     : b6f7a000-b6f9a000 r--s 00000000 00:0b 6702       /dev/__properties__
07-05 14:03:49.876  6885  6885 W art     : b6f9a000-b6f9b000 r--p 00000000 00:00 0 
07-05 14:03:49.876  6885  6885 W art     : b6f9b000-b6f9c000 ---p 00000000 00:00 0 
07-05 14:03:49.876  6885  6885 W art     : b6f9c000-b6f9e000 rw-p 00000000 00:00 0          [anon:thread signal stack]
07-05 14:03:49.876  6885  6885 W art     : b6f9e000-b6f9f000 r-xp 00000000 00:00 0          [sigpage]
07-05 14:03:49.876  6885  6885 W art     : b6f9f000-b6fba000 r-xp 00000000 b3:17 2771       /system/bin/linker
07-05 14:03:49.876  6885  6885 W art     : b6fba000-b6fbb000 r--p 0001a000 b3:17 2771       /system/bin/linker
07-05 14:03:49.876  6885  6885 W art     : b6fbb000-b6fbd000 rw-p 0001b000 b3:17 2771       /system/bin/linker
07-05 14:03:49.876  6885  6885 W art     : b6fbd000-b6fbf000 rw-p 00000000 00:00 0 
07-05 14:03:49.876  6885  6885 W art     : b6fbf000-b6fc4000 r-xp 00000000 b3:17 978        /system/bin/app_process32
07-05 14:03:49.876  6885  6885 W art     : b6fc4000-b6fc5000 r--p 00004000 b3:17 978        /system/bin/app_process32
07-05 14:03:49.876  6885  6885 W art     : b6fc5000-b6fc6000 rw-p 00000000 00:00 0 
07-05 14:03:49.876  6885  6885 W art     : bede5000-bee06000 rw-p 00000000 00:00 0          [stack]
07-05 14:03:49.876  6885  6885 W art     : ffff0000-ffff1000 r-xp 00000000 00:00 0          [vectors]
07-05 14:03:49.926  6885  6885 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
07-05 14:03:49.986  6885  6885 I Radio-JNI: register_android_hardware_Radio DONE
07-05 14:03:49.996  6885  6885 E AffinityControl: AffinityControl: registerfunction enter
07-05 14:03:50.026  6885  6885 D AndroidRuntime: Calling main entry com.android.commands.am.Am
07-05 14:03:50.046   767  1826 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in null rsrc of package null
07-05 14:03:50.056   767  1826 D ActivityManager: mDVFSHelper.acquire()
07-05 14:03:50.056   767  1826 D FocusedStackFrame: Set to : 0
07-05 14:03:50.066   767  1826 V WindowManager: addAppToken: AppWindowToken{cc3538c token=Token{b6520bf ActivityRecord{c73e6de u0 com.test.thalitest/.MainActivity t77}}} to stack=1 task=77 at 0
07-05 14:03:50.076   767   907 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{bee8824 V.E...... R.....ID 0,0-0,0}
07-05 14:03:50.076   767   907 D SecWifiDisplayUtil: Metadata value : none
07-05 14:03:50.076   767   907 D ISSUE_DEBUG: InputChannelName : 55f9542 Starting com.test.thalitest
07-05 14:03:50.096  6924  6924 E Zygote  : v2
07-05 14:03:50.096   767  1826 I ActivityManager: Start proc 6924:com.test.thalitest/u0a4 for activity com.test.thalitest/.MainActivity
07-05 14:03:50.096  6924  6924 I libpersona: KNOX_SDCARD checking this for 10004
07-05 14:03:50.096  6924  6924 I libpersona: KNOX_SDCARD not a persona
07-05 14:03:50.096   767  1826 D InputDispatcher: Focused application set to: xxxx
07-05 14:03:50.096   767  1826 D InputDispatcher: Focus left window: 1749
07-05 14:03:50.096   293   293 I SurfaceFlinger: id=19 createSurf (1x1),1 flag=404, uhalitest
07-05 14:03:50.096  6885  6885 D AndroidRuntime: Shutting down VM
07-05 14:03:50.096  6924  6924 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
07-05 14:03:50.106  6924  6924 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
07-05 14:03:50.106   767  1322 D NetworkPolicy: isUidForegroundLocked: 10004, mScreenOn: false, uidstate: -1, mProxSensorScreenOff: false
07-05 14:03:50.106  6924  6924 E Zygote  : accessInfo : 0
07-05 14:03:50.106  6924  6924 W SELinux : SELinux: seapp_context_lookup: seinfo=default, level=s0:c512,c768, pkgname=com.test.thalitest 
07-05 14:03:50.136  6924  6924 D TimaKeyStoreProvider: TimaSignature is unavailable
07-05 14:03:50.136  6924  6924 D ActivityThread: Added TimaKeyStore provider
07-05 14:03:50.136   767   907 D PointerIcon: setMouseIconStyle1 pointerType: 1001 iconType:101 flag:0 pid:767 uid:1000
07-05 14:03:50.136   767   907 D PointerIcon: setMouseCustomIcon IconType is same.101
07-05 14:03:50.136   767   907 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001 iconType:1 flag:0 pid:767 uid:1000
07-05 14:03:50.136   767   907 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
07-05 14:03:50.136   767   907 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 72 - 0, 0) vi=Rect(0, 72 - 0, 0) or=1
07-05 14:03:50.146   767  1466 V WindowOrientationListener: setCurrentAppOrientation :-1
07-05 14:03:50.146   767  1466 V WindowManager: rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false mMobileKeyboardEnabled=false displayId=0
07-05 14:03:50.176   767   868 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=Window{55f9542 u0 d0 Starting com.test.thalitest}
07-05 14:03:50.176  1749  1959 E libGLESv1: HWUI Protection: wrong call from hwui context F:ES1-glDeleteTexturesSEC
07-05 14:03:50.176  1380  1380 D PhoneStatusBar: setSystemUiVisibility vis=8600 mask=ffffffff oldVal=40008500 newVal=8600 diff=40000300
07-05 14:03:50.176  1749  1749 D SurfaceWidgetConnection: .SurfaceWidgetWeather#1's surface texture was stored
07-05 14:03:50.186   767  1466 D ActivityManager:  Launching com.test.thalitest, updated priority
07-05 14:03:50.196   767   907 V WindowStateAnimator: Finishing drawing window Window{55f9542 u0 d0 Starting com.test.thalitest}: mDrawState=DRAW_PENDING
07-05 14:03:50.206   293   293 D libEGL  : eglInitialize EGLDisplay = 0xbe99b364
07-05 14:03:50.216   293  1829 D libEGL  : eglTerminate EGLDisplay = 0xb476f64c
07-05 14:03:50.216   293  1829 D libEGL  : eglTerminate EGLDisplay = 0xb476f64c
07-05 14:03:50.216   293  1830 I SurfaceFlinger: id=8 Removed Mauncher (5/9)
07-05 14:03:50.216   293  1364 I SurfaceFlinger: id=8 Removed Mauncher (-2/9)
07-05 14:03:50.226  2290  2305 D SurfaceWidgetClient$ISurfaceWidgetStub: [237392/23] Surface widget visibility changed visibility = false on instance = 1
07-05 14:03:50.226  1749  1749 V ActivityThread: updateVisibility : ActivityRecord{ab038a1 token=android.os.BinderProxy@58db99b {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
07-05 14:03:50.226  1749  1749 D Launcher: onTrimMemory. Level: 20
07-05 14:03:50.236   293   293 D libEGL  : eglTerminate EGLDisplay = 0xbe99b3a4
07-05 14:03:50.356   767   866 V MARsPolicyManager: updatePackagesScore PackageInfo name -- com.test.thalitest
07-05 14:03:50.376   767  1322 D NetworkPolicy: isUidForegroundLocked: 10004, mScreenOn: false, uidstate: 5, mProxSensorScreenOff: false
07-05 14:03:50.376  6924  6924 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.test.thalitest rsrc of package null
07-05 14:03:50.376   767  3520 D M       : limitCPUFreq:: freq = -1
07-05 14:03:50.376   767  3520 D CustomFrequencyManagerService: releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MAX_LIMIT  frequency : 1728000  uid : 1000  pid : 767  tag : SIOP_ARM_MAX@25
07-05 14:03:50.376   767  3520 D M       : limitGPUFreq:: freq = -1
07-05 14:03:50.386   767   905 D MARsDBManager: onChange - mSmartManagerObserver! Uri = content://com.samsung.android.sm/AppFreezer?MARs-self=true&MARs=true
07-05 14:03:50.396   767  3520 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
07-05 14:03:50.406  6924  6924 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.test.thalitest rsrc of package null
07-05 14:03:50.416  6924  6924 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.test.thalitest rsrc of package null
07-05 14:03:50.426  6924  6924 I WebViewFactory: Loading com.google.android.webview version 48.0.2564.106 (code 256410600)
07-05 14:03:50.456  6924  6924 W ResourcesManager: getTopLevelResources: /system/app/WebViewGoogle/WebViewGoogle.apk / 1.0 running in com.test.thalitest rsrc of package null
07-05 14:03:50.456  6924  6924 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
07-05 14:03:50.466  6924  6924 I cr_LibraryLoader: Time to load native libraries: 4 ms (timestamps 5213-5217)
07-05 14:03:50.466  6924  6924 I cr_LibraryLoader: Expected native library version number "48.0.2564.106", actual native library version number "48.0.2564.106"
07-05 14:03:50.486   767   778 I art     : Background partial concurrent mark sweep GC freed 18947(1132KB) AllocSpace objects, 9(180KB) LOS objects, 27% free, 41MB/57MB, paused 1.880ms total 133.588ms
07-05 14:03:50.496  6924  6924 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {1ffa06b}
07-05 14:03:50.496  6924  6924 I cr_LibraryLoader: Expected native library version number "48.0.2564.106", actual native library version number "48.0.2564.106"
07-05 14:03:50.496  6924  6924 I chromium: [INFO:library_loader_hooks.cc(130)] Chromium logging enabled: level = 0, default verbosity = 0
07-05 14:03:50.496  6924  6949 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.test.thalitest/shared_prefs/WebViewChromiumPrefs.xml.bak
07-05 14:03:50.506  6924  6924 I cr_BrowserStartup: Initializing chromium process, singleProcess=true
07-05 14:03:50.536  6924  6924 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build:  (Ia10634f51b)
07-05 14:03:50.536  6924  6924 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.29.00.00
07-05 14:03:50.536  6924  6924 I Adreno-EGL: Build Date: 01/28/16 Thu
07-05 14:03:50.536  6924  6924 I Adreno-EGL: Local Branch: ss
07-05 14:03:50.536  6924  6924 I Adreno-EGL: Remote Branch: 
07-05 14:03:50.536  6924  6924 I Adreno-EGL: Local Patches: 
07-05 14:03:50.536  6924  6924 I Adreno-EGL: Reconstruct Branch: 
07-05 14:03:50.546  6924  6924 D libEGL  : eglInitialize EGLDisplay = 0xbe945dac
07-05 14:03:50.596   767  1679 D ActivityManager: The following uid has registered to recieve broadcast for proxy related updates 10004
07-05 14:03:50.596   767  1679 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:845 com.android.server.am.ActivityManagerService.requestKnoxVpnToSendProxyBroadcast:29652 com.android.server.am.ActivityManagerService.registerReceiver:22522 android.app.ActivityManagerNative.onTransact:431 com.android.server.am.ActivityManagerService.onTransact:3990 
07-05 14:03:50.666  6924  6924 D cr_Ime  : [InputMethodManagerWrapper.java:27] Constructor
07-05 14:03:50.676  6924  6924 W cr_AwContents: onDetachedFromWindow called when already detached. Ignoring
07-05 14:03:50.676  6924  6924 D cr_Ime  : [ImeAdapter.java:358] onViewFocusChanged: gainFocus [false]
07-05 14:03:50.676  6924  6924 D cr_Ime  : [ImeAdapter.java:326] hideKeyboard
07-05 14:03:50.686  6924  6924 D cr_Ime  : [InputMethodManagerWrapper.java:56] isActive: false
07-05 14:03:50.706  6924  6924 D cr_Ime  : [ImeAdapter.java:358] onViewFocusChanged: gainFocus [true]
07-05 14:03:50.716  6924  6924 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
07-05 14:03:50.846  6924  6924 D SecWifiDisplayUtil: Metadata value : none
07-05 14:03:50.856  6924  6924 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{d2c8341 I.E...... R.....ID 0,0-0,0}
07-05 14:03:50.856  6924  6978 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
07-05 14:03:50.856   767   866 W ActivityManager: Activity pause timeout for ActivityRecord{c73e6de u0 com.test.thalitest/.MainActivity t77}
07-05 14:03:50.866   767  1409 D ISSUE_DEBUG: InputChannelName : 5008e97 com.test.thalitest/com.test.thalitest.MainActivity
07-05 14:03:50.866   767  4119 D ActivityManager: post active user change for 0 fullscreen true isFloatingActivity() false isHomeActivity() false
07-05 14:03:50.866   767  4119 D KnoxTimeoutHandler: postActiveUserChange [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
07-05 14:03:50.866   767   767 D KnoxTimeoutHandler: handleActiveUserChange [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
07-05 14:03:50.876   767   767 I KnoxTimeoutHandler: Shared devices show user statefalse
07-05 14:03:50.886  6924  6924 D ConnectivityManager: requestNetwork; getAppId(CallingUid) : 10004, CallingPid : 6924
07-05 14:03:50.896   767  4119 D ConnectivityService: listenForNetwork for Listen from uid/pid:10004/6924 for NetworkRequest [ id=12, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-05 14:03:50.896   767  1331 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 502]
07-05 14:03:50.896   767  1331 D ConnectivityService:  network has: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.124/24,fe80::ee1f:72ff:fe18:8b78/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN&VALIDATED LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -43]}  Score{60}  everValidated{true}  lastValidated{true}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
07-05 14:03:50.896   767  1331 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 502] was already satisfying request 1. No change.
07-05 14:03:50.896   767  1331 D ConnectivityService:   checking if request is: NetworkRequest [ id=10, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
07-05 14:03:50.896   767  1331 D ConnectivityService:   checking if request is: NetworkRequest [ id=12, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
07-05 14:03:50.896   767  1331 D ConnectivityService:   checking if request is: NetworkRequest [ id=7, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
07-05 14:03:50.896   767  1331 D ConnectivityService:   checking if request is: NetworkRequest [ id=5, legacyType=-1, [] ] satisfies: true nri.isRequest: false
07-05 14:03:50.896   767  1331 D ConnectivityService:   checking if request is: NetworkRequest [ id=4, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
07-05 14:03:50.896   767  1331 D ConnectivityService:   checking if request is: NetworkRequest [ id=11, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
07-05 14:03:50.896   767  1331 D ConnectivityService:   checking if request is: NetworkRequest [ id=3, legacyType=-1, [ Transports: CELLULAR Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: false nri.isRequest: false
07-05 14:03:50.896   767  1331 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=12, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-05 14:03:50.906  6924  6949 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.test.thalitest/shared_prefs/com.test.thalitest_preferences.xml.bak
07-05 14:03:50.906  6924  6924 V ActivityThread: updateVisibility : ActivityRecord{1e1ddc3 token=android.os.BinderProxy@37d1a28 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
07-05 14:03:50.906  6924  6924 D SecWifiDisplayUtil: Metadata value : none
07-05 14:03:50.926   293   293 I SurfaceFlinger: id=20 createSurf (1x1),1 flag=404, NainActivit
07-05 14:03:50.936   767  1748 D InputDispatcher: Focus entered window: 6924
07-05 14:03:50.946   767   907 D PointerIcon: setMouseIconStyle1 pointerType: 1001 iconType:101 flag:0 pid:767 uid:1000
07-05 14:03:50.946   767   907 D PointerIcon: setMouseCustomIcon IconType is same.101
07-05 14:03:50.946   767   907 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001 iconType:1 flag:0 pid:767 uid:1000
07-05 14:03:50.946   767   907 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
07-05 14:03:50.946  6924  6978 D libEGL  : eglInitialize EGLDisplay = 0x9d73f7c4
07-05 14:03:50.946  6924  6978 I OpenGLRenderer: Initialized EGL, version 1.4
07-05 14:03:51.016  6924  6924 W DisplayListCanvas: DisplayListCanvas is started on unbinded RenderNode (without mOwningView)
07-05 14:03:51.046   767  1811 V WindowStateAnimator: Finishing drawing window Window{5008e97 u0 d0 com.test.thalitest/com.test.thalitest.MainActivity}: mDrawState=DRAW_PENDING
07-05 14:03:51.046  6924  6924 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 72 - 0, 0) vi=Rect(0, 72 - 0, 0) or=1
07-05 14:03:51.056  6924  6924 D cr_Ime  : [ImeAdapter.java:140] onCreateInputConnection returns null.
07-05 14:03:51.056   767  1748 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
07-05 14:03:51.056   293   293 D libEGL  : eglInitialize EGLDisplay = 0xbe99b364
07-05 14:03:51.056   767   907 D KnoxTimeoutHandler: notifyActivityDrawn [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
07-05 14:03:51.056   767   767 D KnoxTimeoutHandler: activityDrawn [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
07-05 14:03:51.056   767   767 I KnoxTimeoutHandler: SD activityfalse
07-05 14:03:51.056   767   907 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +701ms (total +988ms)
07-05 14:03:51.056   767   907 D ActivityManager: mDVFSHelper.release()
07-05 14:03:51.056   767   907 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{c73e6de u0 com.test.thalitest/.MainActivity t77} time:105809
07-05 14:03:51.076   767   907 D ViewRootImpl: #3 mView = null
07-05 14:03:51.076   293  1830 I SurfaceFlinger: id=19 Removed uhalitest (7/9)
07-05 14:03:51.076   293  1364 I SurfaceFlinger: id=19 Removed uhalitest (-2/9)
07-05 14:03:51.086   293   293 D libEGL  : eglTerminate EGLDisplay = 0xbe99b3a4
07-05 14:03:51.096   767  1811 V WindowStateAnimator: Finishing drawing window Window{5008e97 u0 d0 com.test.thalitest/com.test.thalitest.MainActivity}: mDrawState=HAS_DRAWN
07-05 14:03:51.096  6924  6924 D cr_Ime  : [ImeAdapter.java:140] onCreateInputConnection returns null.
07-05 14:03:51.096  6924  6924 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@37d1a28 time:105847
07-05 14:03:51.106   293   293 D libEGL  : eglInitialize EGLDisplay = 0xbe99b364
07-05 14:03:51.106  6924  6985 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
07-05 14:03:51.106  6924  6985 D libEGL  : eglInitialize EGLDisplay = 0x9c0d03ec
07-05 14:03:51.166  6924  6924 W cr_BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 6924
,07-05 14:03:51.376   767  3521 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in null rsrc of package null
,07-05 14:03:51.466  6924  6924 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,07-05 14:03:51.646  6924  6996 D jxcore_app_log: JniHelper::setJavaVM(0xb477c000), pthread_self() = -1700792016
,07-05 14:03:51.646  6924  6996 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
07-05 14:03:51.646  6924  6996 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
07-05 14:03:51.646  6924  6996 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
07-05 14:03:51.646  6924  6996 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
07-05 14:03:51.646  6924  6996 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,07-05 14:03:51.646  6924  6996 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6b04f96 added. We now have 1 listener(s)
,07-05 14:03:51.656  6924  6996 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: B0:C5:59:3F:75:69
,07-05 14:03:51.656  6924  6996 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "B0:C5:59:3F:75:69"
07-05 14:03:51.656  6924  6996 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-05 14:03:51.656  6924  6996 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,07-05 14:03:51.656  6924  6996 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
07-05 14:03:51.656  6924  6996 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
07-05 14:03:51.656  6924  6996 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
07-05 14:03:51.656  6924  6996 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: B0:C5:59:3F:75:69
07-05 14:03:51.656  6924  6996 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
07-05 14:03:51.656  6924  6996 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
07-05 14:03:51.656  6924  6996 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
07-05 14:03:51.656  6924  6996 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
07-05 14:03:51.656  6924  6996 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
07-05 14:03:51.656  6924  6996 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
07-05 14:03:51.656  6924  6996 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,07-05 14:03:51.656  6924  6996 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@85c94ed added. We now have 1 listener(s)
07-05 14:03:51.656  6924  6996 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,07-05 14:03:51.666  6924  6996 D BluetoothAdapter: STATE_ON
,07-05 14:03:51.666  6924  6996 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Storing the value (SUPPORTED) in persistent storage
,07-05 14:03:51.676  6924  6996 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,07-05 14:03:51.676  6924  6996 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 1 -> 2
07-05 14:03:51.676  6924  6996 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 2 -> 3
,07-05 14:03:51.676  6924  6996 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 1 -> 2
,07-05 14:03:51.676  6924  6996 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,07-05 14:03:51.676  6924  6996 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is B0:C5:59:3F:75:69
,07-05 14:03:51.686  6924  6996 D BluetoothAdapter: STATE_ON
,07-05 14:03:51.686  6924  6996 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-05 14:03:51.686  6924  6996 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-05 14:03:51.686  6924  6996 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-05 14:03:51.686  6924  6996 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-05 14:03:51.686  6924  6996 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-05 14:03:51.686  6924  6996 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-05 14:03:51.686  6924  6996 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-05 14:03:51.686  6924  6996 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,07-05 14:03:51.686  6924  6996 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
07-05 14:03:51.686  6924  6996 D io.jxcore.node.ConnectivityMonitor: start: OK
,07-05 14:03:51.686  6924  6924 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-05 14:03:51.696  6924  6924 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-05 14:03:51.696  6924  6996 I io.jxcore.node.LifeCycleMonitor: start: OK
,07-05 14:03:51.716  6924  6924 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,07-05 14:03:51.776   767  3539 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-05 14:03:51.856  1447  1447 D Recents : onTaskStackChanged
,07-05 14:03:51.866  1447  1447 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.android.systemui rsrc of package null
,07-05 14:03:52.826  6924  6997 W jxcore-log: Initializing JXcore engine
,07-05 14:03:52.826  6924  6997 W jxcore-log: JXcore engine is ready
,07-05 14:03:52.866  2334  2334 E audit   : type=1400 msg=audit(1467720232.866:289): avc:  denied  { ioctl } for  pid=6997 comm="Thread-979" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3095 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
07-05 14:03:52.866  2334  2334 E audit   :  SEPF_SECMOBILE_6.0.1_0011
,07-05 14:03:52.866  2334  2334 E audit   : type=1300 msg=audit(1467720232.866:289): arch=40000028 syscall=54 per=800008 success=no exit=-13 a0=7 a1=5451 a2=3 a3=9a8fa3c8 items=0 ppid=353 ppcomm=main pid=6997 auid=4294967295 uid=10004 gid=10004 euid=10004 suid=10004 fsuid=10004 egid=10004 sgid=10004 fsgid=10004 tty=(none) ses=4294967295 comm="Thread-979" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0:c512,c768 key=(null)
07-05 14:03:52.866  2334  2334 E audit   : type=1327 msg=audit(1467720232.866:289): proctitle="com.test.thalitest"
07-05 14:03:52.866  2334  2334 E audit   : type=1320 msg=audit(1467720232.866:289): 
07-05 14:03:52.866  2334  2334 E audit   : type=1400 msg=audit(1467720232.866:290): avc:  denied  { ioctl } for  pid=6997 comm="Thread-979" path="socket:[40516]" dev="sockfs" ino=40516 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
07-05 14:03:52.866  2334  2334 E audit   :  SEPF_SECMOBILE_6.0.1_0011
07-05 14:03:52.866  2334  2334 E audit   : type=1300 msg=audit(1467720232.866:290): arch=40000028 syscall=54 per=800008 success=no exit=-13 a0=3a a1=5451 a2=3 a3=9a8fa3c8 items=0 ppid=353 ppcomm=main pid=6997 auid=4294967295 uid=10004 gid=10004 euid=10004 suid=10004 fsuid=10004 egid=10004 sgid=10004 fsgid=10004 tty=(none) ses=4294967295 comm="Thread-979" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0:c512,c768 key=(null)
07-05 14:03:52.876  2334  2334 E audit   : type=1327 msg=audit(1467720232.866:290): proctitle="com.test.thalitest"
07-05 14:03:52.876  2334  2334 E audit   : type=1320 msg=audit(1467720232.866:290): 
,07-05 14:03:52.876  6924  6997 W jxcore-log: Starting JXcore engine
,07-05 14:03:52.956  6924  6997 W jxcore-log: Platform android
07-05 14:03:52.956  6924  6997 W jxcore-log: 
,07-05 14:03:52.956  6924  6997 W jxcore-log: Process ARCH arm
07-05 14:03:52.956  6924  6997 W jxcore-log: 
,07-05 14:03:53.016   304  1195 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
07-05 14:03:53.016   304  1195 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
07-05 14:03:53.016   304  1195 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,07-05 14:03:53.116   767  1365 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/recent_tasks/77_task.xml.bak
,07-05 14:03:53.166  6924  6997 I jxcore-log: JXcore Cordova bridge is ready!
07-05 14:03:53.166  6924  6997 I jxcore-log: 
07-05 14:03:53.166  6924  6997 W jxcore-log: JXcore engine is started
,07-05 14:03:53.166  6924  6996 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,07-05 14:03:53.176  6924  6924 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,07-05 14:03:53.416  3576  3576 D FactoryTest: User mode
,07-05 14:03:53.416  3576  3576 D MTPRx   : DRIVER_TIME_OUT 60s lapsed
,07-05 14:03:53.416  3576  3576 D MTPRx   : still no open session command from host, so toast
,07-05 14:03:53.426   767  1826 W ResourcesManager: getTopLevelResources: /system/priv-app/MtpApplication/MtpApplication.apk / 1.0 running in null rsrc of package null
,07-05 14:03:53.426   767  1826 D ActivityManager: mDVFSHelper.acquire()
,07-05 14:03:53.436   767  1826 V WindowManager: addAppToken: AppWindowToken{80c4b87 token=Token{9355fc6 ActivityRecord{78731a1 u0 com.samsung.android.MtpApplication/.USBConnection t78}}} to stack=1 task=78 at 0
,07-05 14:03:53.436   767  1826 D ActivityManager:  Launching com.samsung.android.MtpApplication, updated priority
,07-05 14:03:53.456   767   866 V MARsPolicyManager: updatePackagesScore PackageInfo name -- com.samsung.android.MtpApplication
,07-05 14:03:53.466   767  1826 D InputDispatcher: Focused application set to: xxxx
,07-05 14:03:53.476   767  1826 D InputDispatcher: Focus left window: 6924
,07-05 14:03:53.476   767   907 D PointerIcon: setMouseIconStyle1 pointerType: 1001 iconType:101 flag:0 pid:767 uid:1000
,07-05 14:03:53.476   767   907 D PointerIcon: setMouseCustomIcon IconType is same.101
,07-05 14:03:53.476   767   907 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001 iconType:1 flag:0 pid:767 uid:1000
07-05 14:03:53.476   767   907 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
,07-05 14:03:53.486  3576  3576 E MTPRx   : started activity for popup
,07-05 14:03:53.486  3576  3576 W ResourcesManager: getTopLevelResources: /system/priv-app/MtpApplication/MtpApplication.apk / 1.0 running in com.samsung.android.MtpApplication rsrc of package null
,07-05 14:03:53.486  3576  3576 W ResourcesManager: getTopLevelResources: /system/priv-app/MtpApplication/MtpApplication.apk / 1.0 running in com.samsung.android.MtpApplication rsrc of package null
,07-05 14:03:53.506  3576  3576 D MTPUSBConnection: onCreate in USBConnection
07-05 14:03:53.506  3576  3576 V MTPUSBConnection: Registering broadcast receiver.
,07-05 14:03:53.506  3576  3576 E MTPUSBConnection: AlertDialog Mode is : TIMEOUT
,07-05 14:03:53.506   767  4119 D SecContentProvider2: query(), uri = 14 selection = getSealedState
,07-05 14:03:53.546  3576  3576 D TAG     : dev.kiessupport is : TRUE
,07-05 14:03:53.576  3576  3576 D SecWifiDisplayUtil: Metadata value : none
,07-05 14:03:53.586  3576  3576 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{7be2218 V.E...... R.....I. 0,0-0,0}
,07-05 14:03:53.586  3576  7004 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,07-05 14:03:53.586   767  1679 D ISSUE_DEBUG: InputChannelName : 909247f com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection
,07-05 14:03:53.586   767   868 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=Window{909247f u0 d0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}
07-05 14:03:53.586   767  1679 D InputDispatcher: Focus entered window: 3576
,07-05 14:03:53.586   767   907 D PointerIcon: setMouseIconStyle1 pointerType: 1001 iconType:101 flag:0 pid:767 uid:1000
,07-05 14:03:53.586   767   907 D PointerIcon: setMouseCustomIcon IconType is same.101
07-05 14:03:53.586   767   907 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001 iconType:1 flag:0 pid:767 uid:1000
,07-05 14:03:53.586  1380  1380 D PhoneStatusBar: setSystemUiVisibility vis=8000 mask=ffffffff oldVal=8600 newVal=8000 diff=600
,07-05 14:03:53.586   767   907 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
,07-05 14:03:53.596  3576  3576 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{30b1c30 I.E...... R.....I. 0,0-0,0}
,07-05 14:03:53.596   767  4844 D ISSUE_DEBUG: InputChannelName : eee7495 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection
,07-05 14:03:53.596   767  1679 D ActivityManager: post active user change for 0 fullscreen false isFloatingActivity() false isHomeActivity() false
07-05 14:03:53.596   767  1679 D KnoxTimeoutHandler: postActiveUserChange [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
,07-05 14:03:53.596   767   767 D KnoxTimeoutHandler: handleActiveUserChange [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
,07-05 14:03:53.596   767   767 I KnoxTimeoutHandler: Shared devices show user statefalse
07-05 14:03:53.596   767   767 I KnoxTimeoutHandler: Target Activity is not fullscreen. We will not show this activity0
,07-05 14:03:53.626   293   293 I SurfaceFlinger: id=21 createSurf (145x145),1 flag=4, VSBConnecti
,07-05 14:03:53.646  3576  7004 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build:  (Ia10634f51b)
07-05 14:03:53.646  3576  7004 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.29.00.00
07-05 14:03:53.646  3576  7004 I Adreno-EGL: Build Date: 01/28/16 Thu
07-05 14:03:53.646  3576  7004 I Adreno-EGL: Local Branch: ss
07-05 14:03:53.646  3576  7004 I Adreno-EGL: Remote Branch: 
07-05 14:03:53.646  3576  7004 I Adreno-EGL: Local Patches: 
07-05 14:03:53.646  3576  7004 I Adreno-EGL: Reconstruct Branch: 
,07-05 14:03:53.656  3576  7004 D libEGL  : eglInitialize EGLDisplay = 0x9efe17c4
,07-05 14:03:53.656  3576  7004 I OpenGLRenderer: Initialized EGL, version 1.4
,07-05 14:03:53.706   293   293 I SurfaceFlinger: id=22 createSurf (193x193),1 flag=4, VSBConnecti
,07-05 14:03:53.726  3576  3576 V ActivityThread: updateVisibility : ActivityRecord{a0255cf token=android.os.BinderProxy@e80471 {com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}} show : true
,07-05 14:03:53.726  3576  3576 W DisplayListCanvas: DisplayListCanvas is started on unbinded RenderNode (without mOwningView)
,07-05 14:03:53.846   767  1811 V WindowStateAnimator: Finishing drawing window Window{909247f u0 d0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}: mDrawState=DRAW_PENDING
,07-05 14:03:53.846  3576  3576 W DisplayListCanvas: DisplayListCanvas is started on unbinded RenderNode (without mOwningView)
07-05 14:03:53.846   293   293 D libEGL  : eglInitialize EGLDisplay = 0xbe99b364
07-05 14:03:53.846   293   293 D libEGL  : eglInitialize EGLDisplay = 0xbe99b364
07-05 14:03:53.846   767  1826 V WindowStateAnimator: Finishing drawing window Window{eee7495 u0 d0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}: mDrawState=DRAW_PENDING
07-05 14:03:53.846  3576  3576 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 0 - 0, 0) vi=Rect(0, 0 - 0, 0) or=1
07-05 14:03:53.846  3576  3576 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 0 - 0, 0) vi=Rect(0, 0 - 0, 0) or=1
,07-05 14:03:53.856   767   907 D KnoxTimeoutHandler: notifyActivityDrawn [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
,07-05 14:03:53.856   767   767 D KnoxTimeoutHandler: activityDrawn [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
07-05 14:03:53.856   767   907 I ActivityManager: Displayed com.samsung.android.MtpApplication/.USBConnection: +390ms (total +424ms)
,07-05 14:03:53.856   767   767 I KnoxTimeoutHandler: SD activityfalse
07-05 14:03:53.856   767   907 D ActivityManager: mDVFSHelper.release()
07-05 14:03:53.856   767   907 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{78731a1 u0 com.samsung.android.MtpApplication/.USBConnection t78} time:108607
07-05 14:03:53.856   767  1764 V WindowStateAnimator: Finishing drawing window Window{909247f u0 d0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}: mDrawState=HAS_DRAWN
07-05 14:03:53.856   767  4844 V WindowStateAnimator: Finishing drawing window Window{eee7495 u0 d0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}: mDrawState=HAS_DRAWN
,07-05 14:03:53.866  3576  3576 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@e80471 time:108610
,07-05 14:03:53.866   293   293 D libEGL  : eglInitialize EGLDisplay = 0xbe99b364
,07-05 14:03:54.476   767  3521 W ResourcesManager: getTopLevelResources: /system/priv-app/MtpApplication/MtpApplication.apk / 1.0 running in null rsrc of package null
,07-05 14:03:54.506   767  1237 V AlarmManager: Expired Alarm result :4
,07-05 14:03:54.516   767  1322 D NetworkPolicy: isUidForegroundLocked: 10012, mScreenOn: false, uidstate: 6, mProxSensorScreenOff: false
07-05 14:03:54.516   767  1322 D NetworkPolicy: isUidForegroundLocked: 10012, mScreenOn: false, uidstate: 6, mProxSensorScreenOff: false
,07-05 14:03:54.526   767  4119 V AlarmManager:  remove PendingIntent] PendingIntent{615899b: PendingIntentRecord{2a89711 com.google.android.gms broadcastIntent}}
,07-05 14:03:54.526   304  1195 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
07-05 14:03:54.526   304  1195 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
07-05 14:03:54.526   304  1195 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,07-05 14:03:54.606  1447  1447 D Recents : onTaskStackChanged
,07-05 14:03:54.616  1447  1447 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.android.systemui rsrc of package null
,07-05 14:03:54.746   767  3520 D SSRM:n  : SIOP:: AP = 410, PST = 459, CUR = 300, LCD = 0
,07-05 14:03:54.756   767  3520 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,07-05 14:03:56.776   767  3539 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-05 14:03:58.496   767  1748 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 14:03:58.496   767  1748 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4330, temperature: 304, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
07-05 14:03:58.496   767  1748 D BatteryService: online:4, current avg:300, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
07-05 14:03:58.496   767  1748 D BatteryService: stay LED for charging
07-05 14:03:58.496   767   767 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 14:03:58.496   767   767 I MotionRecognitionService: Plugged
07-05 14:03:58.496   767   767 D MotionRecognitionService:   cableConnection= 1
07-05 14:03:58.496   767   767 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
07-05 14:03:58.496   767   767 D MotionRecognitionService: skip setTransmitPower. 
,07-05 14:03:58.506  1380  1380 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
07-05 14:03:58.506  1380  1380 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,07-05 14:03:58.506  1380  1380 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 14:03:58.526  2328  2328 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 14:03:58.526  2328  2834 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-05 14:03:58.536  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
07-05 14:03:58.536  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,07-05 14:03:58.536  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,07-05 14:03:59.486   767  3520 D M       : limitCPUFreq:: freq = 1728000
,07-05 14:03:59.486   767  3520 D CustomFrequencyManagerService: acquireDVFSLockLocked : type : DVFS_MAX_LIMIT  frequency : 1728000  uid : 1000  pid : 767  pkgName : SIOP_ARM_MAX@25
,07-05 14:03:59.496   767  3520 D M       : limitGPUFreq:: freq = 389000000
,07-05 14:03:59.516   767  3520 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,07-05 14:03:59.986   767  1237 V AlarmManager: Expired Alarm result :8
,07-05 14:04:00.086   767   950 D PackageManager: [MSG] WRITE_PACKAGE_RESTRICTIONS
,07-05 14:04:00.126   767   950 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/users/0/package-restrictions.xml.bak
,07-05 14:04:04.556   767  1322 D NetworkPolicy: isUidForegroundLocked: 10012, mScreenOn: false, uidstate: 6, mProxSensorScreenOff: false
,07-05 14:04:04.566   767  1322 D NetworkPolicy: isUidForegroundLocked: 10012, mScreenOn: false, uidstate: 6, mProxSensorScreenOff: false
,07-05 14:04:04.796  6924  6997 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
07-05 14:04:04.796  6924  6997 I jxcore-log: 
,07-05 14:04:04.806  6924  6997 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
07-05 14:04:04.806  6924  6997 I jxcore-log: 
,07-05 14:04:04.816  6924  6997 D BluetoothAdapter: STATE_ON
,07-05 14:04:04.816   767  3520 D SSRM:n  : SIOP:: AP = 410, PST = 453, CUR = 300, LCD = 0
,07-05 14:04:04.816  6924  6997 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-05 14:04:04.816  6924  6997 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-05 14:04:04.816  6924  6997 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-05 14:04:04.816  6924  6997 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-05 14:04:04.816  6924  6997 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-05 14:04:04.816  6924  6997 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-05 14:04:04.816  6924  6997 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-05 14:04:04.816  6924  6997 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,07-05 14:04:04.826  6924  6997 D BluetoothAdapter: STATE_ON
,07-05 14:04:04.826  6924  6997 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,07-05 14:04:04.826  6924  6997 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
07-05 14:04:04.826  6924  6997 I jxcore-log: 
,07-05 14:04:04.826  6924  6997 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
07-05 14:04:04.826  6924  6997 I jxcore-log: 
,07-05 14:04:04.836   767  3520 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,07-05 14:04:05.326  6924  6997 I jxcore-log: Unit Test app is loaded
07-05 14:04:05.326  6924  6997 I jxcore-log: 
,07-05 14:04:05.336  6924  6997 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
07-05 14:04:05.336  6924  6997 I jxcore-log: 
,07-05 14:04:05.336  6924  6924 I chromium: [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74)
,07-05 14:04:05.346  6924  6997 I jxcore-log: My device name is: samsung-SM-G900F
07-05 14:04:05.346  6924  6997 I jxcore-log: 
,07-05 14:04:06.446   767  1604 E Watchdog: !@Sync 3 [07-05 14:04:06.459]
,07-05 14:04:09.226   767  1237 V AlarmManager: Expired Alarm result :4
,07-05 14:04:09.266   767   767 V AlarmManager: ___SyncScheduler (v3) ACTIVATED___
,07-05 14:04:09.266   767   767 V AlarmManagerEXT: <AppSync3 Whitelist>
,07-05 14:04:09.266   767   767 V AlarmManagerEXT: (AppSync) ### 0 added ###
,07-05 14:04:09.266  1380  1380 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
07-05 14:04:09.266  1380  1380 I PERF    : received broadcast android.intent.action.TIME_TICK
07-05 14:04:09.266  1380  1380 D KeyguardUpdateMonitor: handleTimeUpdate
,07-05 14:04:09.276   767  1591 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 14:04:09.276   767  1591 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4347, temperature: 305, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,07-05 14:04:09.276   767  1591 D BatteryService: online:4, current avg:300, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
07-05 14:04:09.276   767  1591 D BatteryService: stay LED for charging
,07-05 14:04:09.276   767   767 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 14:04:09.296  1380  1380 D SecKeyguardClockView: onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,07-05 14:04:09.296  1380  1380 D SecKeyguardClockView: HomeTimezone(): 1
,07-05 14:04:09.306  2328  2328 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 14:04:09.306  2328  2834 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-05 14:04:09.306   767   767 I MotionRecognitionService: Plugged
07-05 14:04:09.306   767   767 D MotionRecognitionService:   cableConnection= 1
07-05 14:04:09.306   767   767 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
07-05 14:04:09.306   767   767 D MotionRecognitionService: skip setTransmitPower. 
,07-05 14:04:09.316  1380  1380 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-05 14:04:09.316  1380  1380 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-05 14:04:09.316  1380  1380 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-05 14:04:09.316  1380  1380 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-05 14:04:09.316  1380  1380 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-05 14:04:09.316  1380  1380 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-05 14:04:09.316  1380  1380 D SecKeyguardStatusUtils: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-05 14:04:09.326  1380  1380 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
07-05 14:04:09.326  1380  1380 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,07-05 14:04:09.326  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,07-05 14:04:09.326  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
07-05 14:04:09.326  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,07-05 14:04:09.336  1380  1380 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 14:04:09.366  1380  1380 D SecKeyguardStatusUtils: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-05 14:04:09.646  1653  1653 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-05 14:04:09.656   304  1195 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
07-05 14:04:09.656   304  1195 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
07-05 14:04:09.656   304  1195 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,07-05 14:04:09.656  1653  1653 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-05 14:04:09.656  1653  1653 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-05 14:04:09.676  1653  2252 E Auth    : [GoogleAccountDataServiceImpl] getToken() failed. Status BAD_AUTHENTICATION, Account: <ELLIDED:1197869880>, App: com.android.vending, Service: androidsecure
07-05 14:04:09.676  1653  2252 E Auth    : com.google.android.gms.auth.be.account.b.d: Long live credential not available.
07-05 14:04:09.676  1653  2252 E Auth    : 	at com.google.android.gms.auth.be.account.b.e.a(:com.google.android.gms:105)
07-05 14:04:09.676  1653  2252 E Auth    : 	at com.google.android.gms.auth.be.p.a(:com.google.android.gms:355)
07-05 14:04:09.676  1653  2252 E Auth    : 	at com.google.android.gms.auth.be.o.a(:com.google.android.gms:260)
07-05 14:04:09.676  1653  2252 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.y.a(:com.google.android.gms:197)
07-05 14:04:09.676  1653  2252 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.x.a(:com.google.android.gms:558)
07-05 14:04:09.676  1653  2252 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.x.a(:com.google.android.gms:196)
07-05 14:04:09.676  1653  2252 E Auth    : 	at com.google.android.gms.auth.o.a(:com.google.android.gms:276)
07-05 14:04:09.676  1653  2252 E Auth    : 	at com.google.android.gms.auth.o.a(:com.google.android.gms:196)
07-05 14:04:09.676  1653  2252 E Auth    : 	at com.google.android.gms.auth.t.a(:com.google.android.gms:498)
07-05 14:04:09.676  1653  2252 E Auth    : 	at com.google.android.gms.auth.s.a(:com.google.android.gms:908)
07-05 14:04:09.676  1653  2252 E Auth    : 	at com.google.android.gms.auth.s.e(:com.google.android.gms:528)
07-05 14:04:09.676  1653  2252 E Auth    : 	at com.google.android.gms.auth.be.m.getAuthToken(:com.google.android.gms:201)
07-05 14:04:09.676  1653  2252 E Auth    : 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
07-05 14:04:09.676  1653  2252 E Auth    : 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
07-05 14:04:09.676  1653  2252 E Auth    : 	at android.os.Binder.execTransact(Binder.java:453)
,07-05 14:04:09.696  5788  5788 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,07-05 14:04:09.696  5788  5788 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
07-05 14:04:09.696  5788  5788 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 2.
,07-05 14:04:10.456  6924  6997 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js
07-05 14:04:10.456  6924  6997 I jxcore-log: 
,07-05 14:04:10.976  6924  6997 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js
07-05 14:04:10.976  6924  6997 I jxcore-log: 
,07-05 14:04:11.016  6924  6997 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
07-05 14:04:11.016  6924  6997 I jxcore-log: 
,07-05 14:04:11.016  6924  6997 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
07-05 14:04:11.016  6924  6997 I jxcore-log: 
,07-05 14:04:11.036  6924  6997 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js,
07-05 14:04:11.036  6924  6997 I jxcore-log: 
,07-05 14:04:11.046  6924  6997 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js,
07-05 14:04:11.046  6924  6997 I jxcore-log: 
,07-05 14:04:13.586  6924  6997 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js
07-05 14:04:13.586  6924  6997 I jxcore-log: 
,07-05 14:04:13.596  6924  6997 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
07-05 14:04:13.596  6924  6997 I jxcore-log: 
,07-05 14:04:13.606  6924  6997 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js
07-05 14:04:13.606  6924  6997 I jxcore-log: 
,07-05 14:04:13.816  6924  6997 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js
07-05 14:04:13.816  6924  6997 I jxcore-log: 
,07-05 14:04:13.916  6924  6997 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js
07-05 14:04:13.916  6924  6997 I jxcore-log: 
,07-05 14:04:13.996  6924  6997 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js
07-05 14:04:13.996  6924  6997 I jxcore-log: 
,07-05 14:04:14.006  6924  6997 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js
07-05 14:04:14.006  6924  6997 I jxcore-log: 
,07-05 14:04:14.256  6924  6997 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js
07-05 14:04:14.256  6924  6997 I jxcore-log: 
,07-05 14:04:14.286  6924  6997 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js
07-05 14:04:14.286  6924  6997 I jxcore-log: 
,07-05 14:04:14.286  6924  6997 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js
07-05 14:04:14.286  6924  6997 I jxcore-log: 
,07-05 14:04:14.296  6924  6997 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
07-05 14:04:14.296  6924  6997 I jxcore-log: 
,07-05 14:04:14.316  6924  6997 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js,
07-05 14:04:14.316  6924  6997 I jxcore-log: 
,07-05 14:04:14.336  6924  6997 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js,
07-05 14:04:14.336  6924  6997 I jxcore-log: 
,07-05 14:04:14.446  6924  6997 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js,
07-05 14:04:14.446  6924  6997 I jxcore-log: 
,07-05 14:04:14.456  6924  6997 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js,
07-05 14:04:14.456  6924  6997 I jxcore-log: 
,07-05 14:04:14.486  6924  6997 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testthaliPeerPoolDefault.js,
07-05 14:04:14.486  6924  6997 I jxcore-log: 
,07-05 14:04:14.506  6924  6997 D BluetoothAdapter: STATE_ON
,07-05 14:04:14.506  6924  6997 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: SUPPORTED
,07-05 14:04:14.506  6924  6997 I jxcore-log: INFO testUtils: BLE multiple advertisement supported
07-05 14:04:14.506  6924  6997 I jxcore-log: 
,07-05 14:04:14.886   767  3520 D SSRM:n  : SIOP:: AP = 410, PST = 447, CUR = 300, LCD = 0
,07-05 14:04:14.896   767  3520 D M       : limitCPUFreq:: freq = -1,
07-05 14:04:14.896   767  3520 D CustomFrequencyManagerService: releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MAX_LIMIT  frequency : 1728000  uid : 1000  pid : 767  tag : SIOP_ARM_MAX@25
07-05 14:04:14.896   767  3520 D M       : limitGPUFreq:: freq = -1
07-05 14:04:14.896   767  3520 D M       : broadcastSiopLevelIntent:: currentSiopLevel = 1
,07-05 14:04:14.906  2899  2899 D ContentApp:  LEVEL : 1
,07-05 14:04:14.916   767   866 I ActivityManager: Start proc 7049:com.sec.android.app.videoplayer/u0a54 for broadcast-3 com.sec.android.app.videoplayer/.videowall.TranscodeReceiver
,07-05 14:04:14.926   767  1322 D NetworkPolicy: isUidForegroundLocked: 10054, mScreenOn: false, uidstate: -1, mProxSensorScreenOff: false
,07-05 14:04:14.926   767  3520 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,07-05 14:04:14.926  7049  7049 E Zygote  : v2
07-05 14:04:14.926  7049  7049 I libpersona: KNOX_SDCARD checking this for 10054
07-05 14:04:14.926  7049  7049 I libpersona: KNOX_SDCARD not a persona
,07-05 14:04:14.936  7049  7049 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
07-05 14:04:14.936  7049  7049 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,07-05 14:04:14.936  7049  7049 E Zygote  : accessInfo : 0
,07-05 14:04:14.936  7049  7049 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.sec.android.app.videoplayer 
,07-05 14:04:14.986  7049  7049 D TimaKeyStoreProvider: TimaSignature is unavailable
07-05 14:04:14.986  7049  7049 D ActivityThread: Added TimaKeyStore provider
,07-05 14:04:15.006   767  1589 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{fcd2868 u-1 android.intent.action.CHECK_SIOP_LEVEL qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{51a1481 7049:com.sec.android.app.videoplayer/u0a54}
,07-05 14:04:15.006   767  1322 D NetworkPolicy: isUidForegroundLocked: 10054, mScreenOn: false, uidstate: 11, mProxSensorScreenOff: false
,07-05 14:04:15.006  7049  7049 W ResourcesManager: getTopLevelResources: /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk / 1.0 running in com.sec.android.app.videoplayer rsrc of package null
,07-05 14:04:15.046  7049  7049 W System  : ClassLoader referenced unknown path: /system/priv-app/SecVideoPlayer/lib/arm
,07-05 14:04:15.086  7049  7049 W ResourcesManager: getTopLevelResources: /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk / 1.0 running in com.sec.android.app.videoplayer rsrc of package null
,07-05 14:04:15.116  7049  7049 E TranscodeReceiver: onReceive : android.intent.action.CHECK_SIOP_LEVEL
,07-05 14:04:15.116  7049  7049 D videowall-Global: core_num = 4
,07-05 14:04:15.136  7049  7049 D videowall-Global: density : 3.0 width : 1080 height : 1920 Raw width : 1080 Raw height : 1920
07-05 14:04:15.136  7049  7049 D videowall-Global: dsp : 1080, swkey : false, Cores : 4, Clock : 0
,07-05 14:04:15.146  7049  7049 D TranscodeReceiver:  SIOP_LEVEL: 1
,07-05 14:04:15.156   767   784 I ActivityManager: Killing 6199:com.osp.app.signin/u0a45 (adj 15): DHA:empty #37
,07-05 14:04:15.176   304  1195 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
07-05 14:04:15.176   304  1195 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
07-05 14:04:15.176   304  1195 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,07-05 14:04:15.186   767  1826 D ActivityManager: isAutoRunBlockedApp:: com.osp.app.signin, Auto Run ON
,07-05 14:04:16.786   767  3539 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-05 14:04:19.366   767  1679 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 14:04:19.376   767  1679 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4376, temperature: 306, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,07-05 14:04:19.376   767  1679 D BatteryService: online:4, current avg:300, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
,07-05 14:04:19.376   767  1679 D BatteryService: stay LED for charging
,07-05 14:04:19.376   767   767 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 14:04:19.386   767   767 I MotionRecognitionService: Plugged
,07-05 14:04:19.396   767   767 D MotionRecognitionService:   cableConnection= 1
,07-05 14:04:19.396   767   767 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,07-05 14:04:19.396   767   767 D MotionRecognitionService: skip setTransmitPower. 
,07-05 14:04:19.406  1380  1380 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 14:04:19.406  1380  1380 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,07-05 14:04:19.416  1380  1380 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 14:04:19.446  2328  2328 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 14:04:19.446  2328  2834 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-05 14:04:19.446  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,07-05 14:04:19.446  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,07-05 14:04:19.446  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,07-05 14:04:24.986   767  3520 D SSRM:n  : SIOP:: AP = 370, PST = 435, CUR = 300, LCD = 0
,07-05 14:04:29.706   767  1237 V AlarmManager: Expired Alarm result :4
,07-05 14:04:29.786   767  1466 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 14:04:29.786   767  1466 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4380, temperature: 306, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,07-05 14:04:29.786   767  1466 D BatteryService: online:4, current avg:300, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
,07-05 14:04:29.786   767   767 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 14:04:29.786   767  1466 D BatteryService: stay LED for charging
,07-05 14:04:29.806   767   767 I MotionRecognitionService: Plugged
,07-05 14:04:29.816   767   767 D MotionRecognitionService:   cableConnection= 1
,07-05 14:04:29.816   767   767 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,07-05 14:04:29.816   767   767 D MotionRecognitionService: skip setTransmitPower. 
,07-05 14:04:29.816  1380  1380 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 14:04:29.816  1380  1380 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,07-05 14:04:29.816  1380  1380 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 14:04:29.836  2328  2328 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 14:04:29.836  2328  2834 D HeadsetStateMachine: Disconnected process message: 10, size: 0,
,07-05 14:04:29.846  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,07-05 14:04:29.846  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,07-05 14:04:29.846  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,07-05 14:04:30.316  1653  1653 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-05 14:04:30.326  1653  1653 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-05 14:04:30.336   304  1195 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
07-05 14:04:30.336   304  1195 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
07-05 14:04:30.336   304  1195 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,07-05 14:04:30.336  1653  1653 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-05 14:04:30.356  1653  1663 E Auth    : [GoogleAccountDataServiceImpl] getToken() failed. Status BAD_AUTHENTICATION, Account: <ELLIDED:1197869880>, App: com.android.vending, Service: androidsecure
07-05 14:04:30.356  1653  1663 E Auth    : com.google.android.gms.auth.be.account.b.d: Long live credential not available.
07-05 14:04:30.356  1653  1663 E Auth    : 	at com.google.android.gms.auth.be.account.b.e.a(:com.google.android.gms:105)
07-05 14:04:30.356  1653  1663 E Auth    : 	at com.google.android.gms.auth.be.p.a(:com.google.android.gms:355)
07-05 14:04:30.356  1653  1663 E Auth    : 	at com.google.android.gms.auth.be.o.a(:com.google.android.gms:260)
07-05 14:04:30.356  1653  1663 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.y.a(:com.google.android.gms:197)
07-05 14:04:30.356  1653  1663 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.x.a(:com.google.android.gms:558)
07-05 14:04:30.356  1653  1663 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.x.a(:com.google.android.gms:196)
07-05 14:04:30.356  1653  1663 E Auth    : 	at com.google.android.gms.auth.o.a(:com.google.android.gms:276)
07-05 14:04:30.356  1653  1663 E Auth    : 	at com.google.android.gms.auth.o.a(:com.google.android.gms:196)
07-05 14:04:30.356  1653  1663 E Auth    : 	at com.google.android.gms.auth.t.a(:com.google.android.gms:498)
07-05 14:04:30.356  1653  1663 E Auth    : 	at com.google.android.gms.auth.s.a(:com.google.android.gms:908)
07-05 14:04:30.356  1653  1663 E Auth    : 	at com.google.android.gms.auth.s.e(:com.google.android.gms:528)
07-05 14:04:30.356  1653  1663 E Auth    : 	at com.google.android.gms.auth.be.m.getAuthToken(:com.google.android.gms:201)
07-05 14:04:30.356  1653  1663 E Auth    : 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
07-05 14:04:30.356  1653  1663 E Auth    : 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
07-05 14:04:30.356  1653  1663 E Auth    : 	at android.os.Binder.execTransact(Binder.java:453)
,07-05 14:04:30.386  5788  5788 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,07-05 14:04:30.386  5788  5788 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,07-05 14:04:30.386  5788  5788 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 3.
,07-05 14:04:35.066   767  3520 D SSRM:n  : SIOP:: AP = 350, PST = 421, CUR = 300, LCD = 0
,07-05 14:04:35.066   767  3520 D M       : broadcastSiopLevelIntent:: currentSiopLevel = 0
,07-05 14:04:35.086  2899  2899 D ContentApp:  LEVEL : 0
,07-05 14:04:35.116   767   866 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{8901ff1 u-1 android.intent.action.CHECK_SIOP_LEVEL qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{51a1481 7049:com.sec.android.app.videoplayer/u0a54}
,07-05 14:04:35.126   767  3520 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,07-05 14:04:35.126  7049  7049 E TranscodeReceiver: onReceive : android.intent.action.CHECK_SIOP_LEVEL
,07-05 14:04:35.136  7049  7049 D TranscodeReceiver:  SIOP_LEVEL: 0
,07-05 14:04:36.456   767  1604 E Watchdog: !@Sync 4 [07-05 14:04:36.462]
,07-05 14:04:36.786   767  3539 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-05 14:04:37.286  1664  1768 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,07-05 14:04:40.376   767  1237 V AlarmManager: Expired Alarm result :4
,07-05 14:04:40.446   767  4844 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 14:04:40.456   767  4844 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4382, temperature: 307, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,07-05 14:04:40.456   767  4844 D BatteryService: online:4, current avg:300, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
,07-05 14:04:40.456   767  4844 D BatteryService: stay LED for charging
07-05 14:04:40.456   767   767 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 14:04:40.456   767   767 I MotionRecognitionService: Plugged
,07-05 14:04:40.456   767   767 D MotionRecognitionService:   cableConnection= 1
,07-05 14:04:40.456   767   767 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
07-05 14:04:40.456   767   767 D MotionRecognitionService: skip setTransmitPower. 
,07-05 14:04:40.466  1380  1380 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 14:04:40.466  1380  1380 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,07-05 14:04:40.466  1380  1380 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 14:04:40.476  2328  2328 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 14:04:40.476  2328  2834 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-05 14:04:40.486  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,07-05 14:04:40.496  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,07-05 14:04:40.496  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,07-05 14:04:40.676  6809  7108 I BooksSync: Starting books sync for 61035162, extras: ade
,07-05 14:04:40.716  1653  1653 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-05 14:04:40.716  1653  1653 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-05 14:04:40.736  1653  2252 E Auth    : [GoogleAccountDataServiceImpl] getToken() failed. Status BAD_AUTHENTICATION, Account: <ELLIDED:1197869880>, App: com.google.android.apps.books, Service: oauth2:https://www.googleapis.com/auth/books
07-05 14:04:40.736  1653  2252 E Auth    : com.google.android.gms.auth.be.account.b.d: Long live credential not available.
07-05 14:04:40.736  1653  2252 E Auth    : 	at com.google.android.gms.auth.be.account.b.e.a(:com.google.android.gms:105)
07-05 14:04:40.736  1653  2252 E Auth    : 	at com.google.android.gms.auth.be.p.a(:com.google.android.gms:355)
07-05 14:04:40.736  1653  2252 E Auth    : 	at com.google.android.gms.auth.be.o.a(:com.google.android.gms:260)
07-05 14:04:40.736  1653  2252 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.y.a(:com.google.android.gms:197)
07-05 14:04:40.736  1653  2252 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.x.a(:com.google.android.gms:558)
07-05 14:04:40.736  1653  2252 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.x.a(:com.google.android.gms:196)
07-05 14:04:40.736  1653  2252 E Auth    : 	at com.google.android.gms.auth.o.a(:com.google.android.gms:276)
07-05 14:04:40.736  1653  2252 E Auth    : 	at com.google.android.gms.auth.o.a(:com.google.android.gms:196)
07-05 14:04:40.736  1653  2252 E Auth    : 	at com.google.android.b.b.onTransact(:com.google.android.gms:137)
07-05 14:04:40.736  1653  2252 E Auth    : 	at android.os.Binder.execTransact(Binder.java:453)
,07-05 14:04:40.766  1653  1663 E Auth    : [GoogleAccountDataServiceImpl] getToken() failed. Status BAD_AUTHENTICATION, Account: <ELLIDED:1197869880>, App: com.google.android.apps.books, Service: oauth2:https://www.googleapis.com/auth/books
07-05 14:04:40.766  1653  1663 E Auth    : com.google.android.gms.auth.be.account.b.d: Long live credential not available.
07-05 14:04:40.766  1653  1663 E Auth    : 	at com.google.android.gms.auth.be.account.b.e.a(:com.google.android.gms:105)
07-05 14:04:40.766  1653  1663 E Auth    : 	at com.google.android.gms.auth.be.p.a(:com.google.android.gms:355)
07-05 14:04:40.766  1653  1663 E Auth    : 	at com.google.android.gms.auth.be.o.a(:com.google.android.gms:260)
07-05 14:04:40.766  1653  1663 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.y.a(:com.google.android.gms:197)
07-05 14:04:40.766  1653  1663 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.x.a(:com.google.android.gms:558)
07-05 14:04:40.766  1653  1663 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.x.a(:com.google.android.gms:196)
07-05 14:04:40.766  1653  1663 E Auth    : 	at com.google.android.gms.auth.o.a(:com.google.android.gms:276)
07-05 14:04:40.766  1653  1663 E Auth    : 	at com.google.android.gms.auth.o.a(:com.google.android.gms:196)
07-05 14:04:40.766  1653  1663 E Auth    : 	at com.google.android.b.b.onTransact(:com.google.android.gms:137)
07-05 14:04:40.766  1653  1663 E Auth    : 	at android.os.Binder.execTransact(Binder.java:453)
,07-05 14:04:40.776  6809  7109 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
07-05 14:04:40.776  6809  7108 E BooksSync: Soft error
07-05 14:04:40.776  6809  7108 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
07-05 14:04:40.776  6809  7108 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.zza(Unknown)
07-05 14:04:40.776  6809  7108 E BooksSync: Sync error
07-05 14:04:40.776  6809  7108 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
07-05 14:04:40.776  6809  7108 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.zza(Unknown)
07-05 14:04:40.786  6809  7108 I BooksSync: Finished books sync
07-05 14:04:40.796  6809  7115 I GcmRegistrationService: Handling Intent for action: com.google.android.books.GCM_REGISTER
07-05 14:04:40.796  6809  7115 W GcmRegistrationHandler: Could not find device group in preferences; re-associating.
07-05 14:04:40.796   767   862 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 155103, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,07-05 14:04:40.806  1653  3945 E Auth    : [GoogleAccountDataServiceImpl] getToken() failed. Status BAD_AUTHENTICATION, Account: <ELLIDED:1197869880>, App: com.google.android.apps.books, Service: oauth2:https://www.googleapis.com/auth/gcm
07-05 14:04:40.806  1653  3945 E Auth    : com.google.android.gms.auth.be.account.b.d: Long live credential not available.
07-05 14:04:40.806  1653  3945 E Auth    : 	at com.google.android.gms.auth.be.account.b.e.a(:com.google.android.gms:105)
07-05 14:04:40.806  1653  3945 E Auth    : 	at com.google.android.gms.auth.be.p.a(:com.google.android.gms:355)
07-05 14:04:40.806  1653  3945 E Auth    : 	at com.google.android.gms.auth.be.o.a(:com.google.android.gms:260)
07-05 14:04:40.806  1653  3945 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.y.a(:com.google.android.gms:197)
07-05 14:04:40.806  1653  3945 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.x.a(:com.google.android.gms:558)
07-05 14:04:40.806  1653  3945 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.x.a(:com.google.android.gms:196)
07-05 14:04:40.806  1653  3945 E Auth    : 	at com.google.android.gms.auth.o.a(:com.google.android.gms:276)
07-05 14:04:40.806  1653  3945 E Auth    : 	at com.google.android.gms.auth.o.a(:com.google.android.gms:196)
07-05 14:04:40.806  1653  3945 E Auth    : 	at com.google.android.b.b.onTransact(:com.google.android.gms:137)
07-05 14:04:40.806  1653  3945 E Auth    : 	at android.os.Binder.execTransact(Binder.java:453)
,07-05 14:04:40.806   767   862 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/sync/pending.xml.bak
,07-05 14:04:40.836  3277  3292 W ResourcesManager: getTopLevelResources: /system/app/PlusOne/PlusOne.apk / 1.0 running in com.android.contacts rsrc of package null
,07-05 14:04:40.836  3277  3292 W ResourcesManager: getTopLevelResources: /system/app/PlusOne/PlusOne.apk / 1.0 running in com.android.contacts rsrc of package null
,07-05 14:04:40.836  3277  3292 W ResourcesManager: getTopLevelResources: /system/app/PlusOne/PlusOne.apk / 1.0 running in com.android.contacts rsrc of package null
,07-05 14:04:40.836  3277  3292 W ResourcesManager: getTopLevelResources: /system/app/PlusOne/PlusOne.apk / 1.0 running in com.android.contacts rsrc of package null
,07-05 14:04:40.836   767  4119 D SecContentProvider2: query(), uri = 11 selection = getMyKnoxAdmin
,07-05 14:04:40.836  6809  7115 W BooksGcmUtils: Recoverable exception while getting auth token: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
,07-05 14:04:40.836  6809  7115 E GcmRegistrationHandler: Failed to register token for device group
07-05 14:04:40.836  6809  7115 E GcmRegistrationHandler: com.google.android.apps.books.gcm.GcmRegistrationHandler$GcmRequestException: Failed to update GCM device group: null auth token.
07-05 14:04:40.836  6809  7115 E GcmRegistrationHandler: 	at com.google.android.apps.books.gcm.GcmRegistrationHandler.addOrRemoveInstanceIdTokenForAccount(GcmRegistrationHandler.java:275)
07-05 14:04:40.836  6809  7115 E GcmRegistrationHandler: 	at com.google.android.apps.books.gcm.GcmRegistrationHandler.registerTokenForDeviceGroup(GcmRegistrationHandler.java:199)
07-05 14:04:40.836  6809  7115 E GcmRegistrationHandler: 	at com.google.android.apps.books.gcm.GcmRegistrationHandler.registerForDeviceGroup(GcmRegistrationHandler.java:126)
07-05 14:04:40.836  6809  7115 E GcmRegistrationHandler: 	at com.google.android.apps.books.gcm.GcmRegistrationIntentService.handleActionRegister(GcmRegistrationIntentService.java:135)
07-05 14:04:40.836  6809  7115 E GcmRegistrationHandler: 	at com.google.android.apps.books.gcm.GcmRegistrationIntentService.onHandleIntent(GcmRegistrationIntentService.java:94)
07-05 14:04:40.836  6809  7115 E GcmRegistrationHandler: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
07-05 14:04:40.836  6809  7115 E GcmRegistrationHandler: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-05 14:04:40.836  6809  7115 E GcmRegistrationHandler: 	at android.os.Looper.loop(Looper.java:158)
07-05 14:04:40.836  6809  7115 E GcmRegistrationHandler: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,07-05 14:04:43.686   304  1195 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
07-05 14:04:43.686   304  1195 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
07-05 14:04:43.686   304  1195 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,07-05 14:04:45.186   767  3520 D SSRM:n  : SIOP:: AP = 340, PST = 409, CUR = 300, LCD = 0
,07-05 14:04:45.186   767  3520 D M       : broadcastSiopLevelIntent:: currentSiopLevel = -1
,07-05 14:04:45.206  2899  2899 D ContentApp:  LEVEL : -1
,07-05 14:04:45.256   767   866 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{d5d20e3 u-1 android.intent.action.CHECK_SIOP_LEVEL qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{51a1481 7049:com.sec.android.app.videoplayer/u0a54}
,07-05 14:04:45.256  7049  7049 E TranscodeReceiver: onReceive : android.intent.action.CHECK_SIOP_LEVEL
,07-05 14:04:45.256  7049  7049 D TranscodeReceiver:  SIOP_LEVEL: -1
,07-05 14:04:52.376   767  1237 V AlarmManager: Expired Alarm result :4
,07-05 14:04:52.456   767   784 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 14:04:52.456   767   784 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4385, temperature: 307, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,07-05 14:04:52.456   767   784 D BatteryService: online:4, current avg:300, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
07-05 14:04:52.456   767   784 D BatteryService: stay LED for charging
,07-05 14:04:52.456   767   767 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 14:04:52.466   767   866 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{cda1c5e u0 com.google.android.gms.gcm.ACTION_CHECK_QUEUE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{18ebe38 1653:com.google.android.gms.persistent/u0a12}
,07-05 14:04:52.506  1380  1380 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 14:04:52.506  1380  1380 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
07-05 14:04:52.506  1380  1380 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 14:04:52.516  2328  2328 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 14:04:52.516  2328  2834 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-05 14:04:52.526   767  1811 V AlarmManager:  remove PendingIntent] PendingIntent{3f53e55: PendingIntentRecord{560f6d7 com.google.android.gms broadcastIntent}}
,07-05 14:04:52.526  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,07-05 14:04:52.526  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,07-05 14:04:52.526  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,07-05 14:04:52.546   767  1237 I ActivityManager: Start proc 7127:com.mobeam.barcodeService/1000 for service com.mobeam.barcodeService/.system.AppService
,07-05 14:04:52.556  7127  7127 E Zygote  : v2
,07-05 14:04:52.556  7127  7127 I libpersona: KNOX_SDCARD checking this for 1000
,07-05 14:04:52.556   767   767 I MotionRecognitionService: Plugged
,07-05 14:04:52.556   767   767 D MotionRecognitionService:   cableConnection= 1
,07-05 14:04:52.566  7127  7127 I libpersona: KNOX_SDCARD not a persona
,07-05 14:04:52.566  7127  7127 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
,07-05 14:04:52.566   767   767 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,07-05 14:04:52.566   767   767 D MotionRecognitionService: skip setTransmitPower. 
,07-05 14:04:52.566  7127  7127 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,07-05 14:04:52.566  7127  7127 E Zygote  : accessInfo : 0
,07-05 14:04:52.626  7127  7127 D TimaKeyStoreProvider: TimaSignature is unavailable
07-05 14:04:52.626  7127  7127 D ActivityThread: Added TimaKeyStore provider
,07-05 14:04:52.666  7127  7127 W ResourcesManager: getTopLevelResources: /system/app/BeamService/BeamService.apk / 1.0 running in com.mobeam.barcodeService rsrc of package null
,07-05 14:04:52.686  7127  7127 W System  : ClassLoader referenced unknown path: /system/app/BeamService/lib/arm
,07-05 14:04:52.696   767  4119 V AlarmManager:  remove PendingIntent] PendingIntent{cb0a5f8: PendingIntentRecord{560f6d7 com.google.android.gms broadcastIntent}}
,07-05 14:04:52.856  1653  1653 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-05 14:04:52.906   767   866 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{84808d3 u0 com.google.android.gms.gcm.ACTION_SCHEDULE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{18ebe38 1653:com.google.android.gms.persistent/u0a12}
,07-05 14:04:52.926   767  4844 V AlarmManager:  remove PendingIntent] PendingIntent{f8e3c10: PendingIntentRecord{560f6d7 com.google.android.gms broadcastIntent}}
,07-05 14:04:52.976   767  1679 V AlarmManager:  remove PendingIntent] PendingIntent{a3ca309: PendingIntentRecord{560f6d7 com.google.android.gms broadcastIntent}}
,07-05 14:04:53.236   767  1767 V AlarmManager:  remove PendingIntent] PendingIntent{703093c: PendingIntentRecord{560f6d7 com.google.android.gms broadcastIntent}}
,07-05 14:04:53.296  1653  7171 I VacuumService: Vacuum at: now=1467720293303 tag=VacuumService
,07-05 14:04:53.296  1653  1653 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-05 14:04:53.406   767   778 I art     : Background partial concurrent mark sweep GC freed 46836(2MB) AllocSpace objects, 42(840KB) LOS objects, 27% free, 41MB/57MB, paused 2.366ms total 212.406ms
,07-05 14:04:53.956  1653  1653 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-05 14:04:53.966  1653  1653 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-05 14:04:54.016  1653  1653 E ctxmgr  : [FencePendingIntentCache]Expected to find a PendingIntent for pendingIntentKey=5e4eef53-bbe8-4fc7-81c4-25e436a99d41
,07-05 14:04:54.056   767  1590 V AlarmManager:  remove PendingIntent] PendingIntent{81459e9: PendingIntentRecord{560f6d7 com.google.android.gms broadcastIntent}}
,07-05 14:04:54.086   767  1764 V AlarmManager:  remove PendingIntent] PendingIntent{745766e: PendingIntentRecord{560f6d7 com.google.android.gms broadcastIntent}}
,07-05 14:04:54.206  1653  2252 E Auth    : [GoogleAccountDataServiceImpl] getToken() failed. Status BAD_AUTHENTICATION, Account: <ELLIDED:1197869880>, App: com.android.vending, Service: androidsecure
07-05 14:04:54.206  1653  2252 E Auth    : com.google.android.gms.auth.be.account.b.d: Long live credential not available.
07-05 14:04:54.206  1653  2252 E Auth    : 	at com.google.android.gms.auth.be.account.b.e.a(:com.google.android.gms:105)
07-05 14:04:54.206  1653  2252 E Auth    : 	at com.google.android.gms.auth.be.p.a(:com.google.android.gms:355)
07-05 14:04:54.206  1653  2252 E Auth    : 	at com.google.android.gms.auth.be.o.a(:com.google.android.gms:260)
07-05 14:04:54.206  1653  2252 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.y.a(:com.google.android.gms:197)
07-05 14:04:54.206  1653  2252 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.x.a(:com.google.android.gms:558)
07-05 14:04:54.206  1653  2252 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.x.a(:com.google.android.gms:196)
07-05 14:04:54.206  1653  2252 E Auth    : 	at com.google.android.gms.auth.o.a(:com.google.android.gms:276)
07-05 14:04:54.206  1653  2252 E Auth    : 	at com.google.android.gms.auth.o.a(:com.google.android.gms:196)
07-05 14:04:54.206  1653  2252 E Auth    : 	at com.google.android.gms.auth.t.a(:com.google.android.gms:498)
07-05 14:04:54.206  1653  2252 E Auth    : 	at com.google.android.gms.auth.s.a(:com.google.android.gms:908)
07-05 14:04:54.206  1653  2252 E Auth    : 	at com.google.android.gms.auth.s.e(:com.google.android.gms:528)
07-05 14:04:54.206  1653  2252 E Auth    : 	at com.google.android.gms.auth.be.m.getAuthToken(:com.google.android.gms:201)
07-05 14:04:54.206  1653  2252 E Auth    : 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
07-05 14:04:54.206  1653  2252 E Auth    : 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
07-05 14:04:54.206  1653  2252 E Auth    : 	at android.os.Binder.execTransact(Binder.java:453)
,07-05 14:04:54.216  1653  2197 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,07-05 14:04:54.256  1653  7172 E ctxmgr  : [FenceManager]Could not remove all geofences. status=Status{statusCode=unknown status code: 1000, resolution=null}
,07-05 14:04:54.266  5788  5788 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,07-05 14:04:54.266  5788  5788 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,07-05 14:04:54.266  5788  5788 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 4.
,07-05 14:04:54.366  1990  7165 D UdcContextInitService: registered all accounts: true
,07-05 14:04:54.436  1653  7197 I PhenotypeConfigurator: Scheduling Phenotype for one-off execution 5586 seconds from now (1467720294448)
,07-05 14:04:54.486   767   866 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{1bbc815 u0 com.google.android.gms.gcm.ACTION_SCHEDULE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{18ebe38 1653:com.google.android.gms.persistent/u0a12}
,07-05 14:04:54.566  1653  7172 W ctxmgr  : [AclManager]checkPermissionTypeStatus: no inject permission for { uid=10012, packageName=com.google.android.gms }. Returned permission was: PACKAGE_NOT_WHITELISTED for context name=POWER_CONNECTION, account=account#-517948760#
,07-05 14:04:54.576  1653  7192 I PhenotypeFlagCommitter: Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,07-05 14:04:54.576  1653  1653 E ctxmgr  : [PowerConnectionProducer]Could not write powerInfo=Plug state: 2 BatteryLevel: 1.0, status=Status{statusCode=unknown status code: 7503, resolution=null}
,07-05 14:04:54.576  1653  7192 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,07-05 14:04:54.636   767   784 I ActivityManager: Killing 6221:com.sec.android.cloudagent/u0a2 (adj 15): DHA:empty #37
,07-05 14:04:54.646   767   784 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,07-05 14:04:54.666   767  4844 D ActivityManager: isAutoRunBlockedApp:: com.sec.android.cloudagent, Auto Run ON
,07-05 14:04:54.786  1653  7192 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
07-05 14:04:54.786  1653  7192 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,07-05 14:04:54.786   304  1199 D EnterpriseController: netId is 0
07-05 14:04:54.786   304  1199 D Netd    : getNetworkForDns: using netid 502 for uid 10012
,07-05 14:04:54.886  1653  7192 I qtaguid : Tagging socket 77 with tag 1000120100000000{268440065,0} uid -1, pid: 1653, getuid(): 10012
,07-05 14:04:54.956  1653  7192 I qtaguid : Tagging socket 81 with tag 1000120100000000{268440065,0} uid -1, pid: 1653, getuid(): 10012
,07-05 14:04:55.306   767  3520 D SSRM:n  : SIOP:: AP = 340, PST = 397, CUR = 300, LCD = 0
,07-05 14:04:55.396   767  1811 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,07-05 14:04:55.406  1653  7192 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,07-05 14:04:55.406  1653  7192 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
07-05 14:04:55.406  1653  7192 I qtaguid : Tagging socket 77 with tag 1000120100000000{268440065,0} uid -1, pid: 1653, getuid(): 10012
,07-05 14:04:55.566   767   785 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,07-05 14:04:55.616  1653  7192 E Auth    : [GoogleAccountDataServiceImpl] getToken() failed. Status BAD_AUTHENTICATION, Account: <ELLIDED:1197869880>, App: com.google.android.gms, Service: oauth2:https://www.googleapis.com/auth/cclog
07-05 14:04:55.616  1653  7192 E Auth    : com.google.android.gms.auth.be.account.b.d: Long live credential not available.
07-05 14:04:55.616  1653  7192 E Auth    : 	at com.google.android.gms.auth.be.account.b.e.a(:com.google.android.gms:105)
07-05 14:04:55.616  1653  7192 E Auth    : 	at com.google.android.gms.auth.be.p.a(:com.google.android.gms:355)
07-05 14:04:55.616  1653  7192 E Auth    : 	at com.google.android.gms.auth.be.o.a(:com.google.android.gms:260)
07-05 14:04:55.616  1653  7192 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.y.a(:com.google.android.gms:197)
07-05 14:04:55.616  1653  7192 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.x.a(:com.google.android.gms:558)
07-05 14:04:55.616  1653  7192 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.x.a(:com.google.android.gms:196)
07-05 14:04:55.616  1653  7192 E Auth    : 	at com.google.android.gms.auth.o.a(:com.google.android.gms:276)
07-05 14:04:55.616  1653  7192 E Auth    : 	at com.google.android.gms.auth.o.a(:com.google.android.gms:196)
07-05 14:04:55.616  1653  7192 E Auth    : 	at com.google.android.gms.auth.t.a(:com.google.android.gms:498)
07-05 14:04:55.616  1653  7192 E Auth    : 	at com.google.android.gms.auth.s.a(:com.google.android.gms:908)
07-05 14:04:55.616  1653  7192 E Auth    : 	at com.google.android.gms.auth.s.e(:com.google.android.gms:528)
07-05 14:04:55.616  1653  7192 E Auth    : 	at com.google.android.gms.auth.q.f(:com.google.android.gms:315)
07-05 14:04:55.616  1653  7192 E Auth    : 	at com.google.android.gms.auth.q.b(:com.google.android.gms:195)
07-05 14:04:55.616  1653  7192 E Auth    : 	at com.google.android.gms.auth.q.a(:com.google.android.gms:146)
07-05 14:04:55.616  1653  7192 E Auth    : 	at com.google.android.gms.auth.q.a(:com.google.android.gms:73)
07-05 14:04:55.616  1653  7192 E Auth    : 	at com.google.android.gms.playlog.uploader.i.a(:com.google.android.gms:761)
07-05 14:04:55.616  1653  7192 E Auth    : 	at com.google.android.gms.playlog.uploader.i.a(:com.google.android.gms:582)
07-05 14:04:55.616  1653  7192 E Auth    : 	at com.google.android.gms.playlog.uploader.i.a(:com.google.android.gms:469)
07-05 14:04:55.616  1653  7192 E Auth    : 	at com.google.android.gms.playlog.uploader.i.a(:com.google.android.gms:384)
07-05 14:04:55.616  1653  7192 E Auth    : 	at com.google.android.gms.playlog.uploader.UploaderService.b(:com.google.android.gms:100)
07-05 14:04:55.616  1653  7192 E Auth    : 	at com.google.android.gms.playlog.uploader.UploaderService.a(:com.google.android.gms:69)
07-05 14:04:55.616  1653  7192 E Auth    : 	at com.google.android.gms.gcm.aw.run(:com.google.android.gms:144)
,07-05 14:04:55.646  1653  7192 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
07-05 14:04:55.646  1653  7192 E Uploader: com.google.android.gms.auth.am: User intervention required. Notification has been pushed.
07-05 14:04:55.646  1653  7192 E Uploader: 	at com.google.android.gms.auth.q.f(:com.google.android.gms:330)
07-05 14:04:55.646  1653  7192 E Uploader: 	at com.google.android.gms.auth.q.b(:com.google.android.gms:195)
07-05 14:04:55.646  1653  7192 E Uploader: 	at com.google.android.gms.auth.q.a(:com.google.android.gms:146)
07-05 14:04:55.646  1653  7192 E Uploader: 	at com.google.android.gms.auth.q.a(:com.google.android.gms:73)
07-05 14:04:55.646  1653  7192 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(:com.google.android.gms:761)
07-05 14:04:55.646  1653  7192 E Uploader: ,	at com.google.android.gms.playlog.uploader.i.a(:com.google.android.gms:582)
07-05 14:04:55.646  1653  7192 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(:com.google.android.gms:469)
07-05 14:04:55.646  1653  7192 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(:com.google.android.gms:384)
07-05 14:04:55.646  1653  7192 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(:com.google.android.gms:100)
07-05 14:04:55.646  1653  7192 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(:com.google.android.gms:69)
07-05 14:04:55.646  1653  7192 E Uploader: 	at com.google.android.gms.gcm.aw.run(:com.google.android.gms:144)
,07-05 14:04:55.656  1653  7192 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,07-05 14:04:55.656  1653  7192 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,07-05 14:04:55.656  1653  7192 I qtaguid : Tagging socket 77 with tag 1000120100000000{268440065,0} uid -1, pid: 1653, getuid(): 10012
,07-05 14:04:55.816   767  1589 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,07-05 14:04:55.836  1653  7192 W Uploader: UNKNOWN no longer exists, so no auth token.
,07-05 14:04:55.856  1653  7192 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,07-05 14:04:55.856  1653  7192 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,07-05 14:04:55.856  1653  7192 I qtaguid : Tagging socket 77 with tag 1000120100000000{268440065,0} uid -1, pid: 1653, getuid(): 10012
,07-05 14:04:55.996   767  4844 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,07-05 14:04:56.016  1653  7192 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,07-05 14:04:56.016  1653  7192 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,07-05 14:04:56.016  1653  7192 I qtaguid : Tagging socket 77 with tag 1000120100000000{268440065,0} uid -1, pid: 1653, getuid(): 10012
,07-05 14:04:56.156   767  1748 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,07-05 14:04:56.166  1653  7192 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,07-05 14:04:56.166  1653  7192 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,07-05 14:04:56.166  1653  7192 I qtaguid : Tagging socket 77 with tag 1000120100000000{268440065,0} uid -1, pid: 1653, getuid(): 10012
,07-05 14:04:56.296   767  4119 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,07-05 14:04:56.326  1653  7192 E Auth    : [GoogleAccountDataServiceImpl] getToken() failed. Status BAD_AUTHENTICATION, Account: <ELLIDED:1197869880>, App: com.google.android.gms, Service: oauth2:https://www.googleapis.com/auth/cclog
07-05 14:04:56.326  1653  7192 E Auth    : com.google.android.gms.auth.be.account.b.d: Long live credential not available.
07-05 14:04:56.326  1653  7192 E Auth    : 	at com.google.android.gms.auth.be.account.b.e.a(:com.google.android.gms:105)
07-05 14:04:56.326  1653  7192 E Auth    : 	at com.google.android.gms.auth.be.p.a(:com.google.android.gms:355)
07-05 14:04:56.326  1653  7192 E Auth    : 	at com.google.android.gms.auth.be.o.a(:com.google.android.gms:260)
07-05 14:04:56.326  1653  7192 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.y.a(:com.google.android.gms:197)
07-05 14:04:56.326  1653  7192 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.x.a(:com.google.android.gms:558)
07-05 14:04:56.326  1653  7192 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.x.a(:com.google.android.gms:196)
07-05 14:04:56.326  1653  7192 E Auth    : 	at com.google.android.gms.auth.o.a(:com.google.android.gms:276)
07-05 14:04:56.326  1653  7192 E Auth    : 	at com.google.android.gms.auth.o.a(:com.google.android.gms:196)
07-05 14:04:56.326  1653  7192 E Auth    : 	at com.google.android.gms.auth.t.a(:com.google.android.gms:498)
07-05 14:04:56.326  1653  7192 E Auth    : 	at com.google.android.gms.auth.s.a(:com.google.android.gms:908)
07-05 14:04:56.326  1653  7192 E Auth    : 	at com.google.android.gms.auth.s.e(:com.google.android.gms:528)
07-05 14:04:56.326  1653  7192 E Auth    : 	at com.google.android.gms.auth.q.f(:com.google.android.gms:315)
07-05 14:04:56.326  1653  7192 E Auth    : 	at com.google.android.gms.auth.q.b(:com.google.android.gms:195)
07-05 14:04:56.326  1653  7192 E Auth    : 	at com.google.android.gms.auth.q.a(:com.google.android.gms:146)
07-05 14:04:56.326  1653  7192 E Auth    : 	at com.google.android.gms.auth.q.a(:com.google.android.gms:73)
07-05 14:04:56.326  1653  7192 E Auth    : 	at com.google.android.gms.playlog.uploader.i.a(:com.google.android.gms:761)
07-05 14:04:56.326  1653  7192 E Auth    : 	at com.google.android.gms.playlog.uploader.i.a(:com.google.android.gms:582)
07-05 14:04:56.326  1653  7192 E Auth    : 	at com.google.android.gms.playlog.uploader.i.a(:com.google.android.gms:469)
07-05 14:04:56.326  1653  7192 E Auth    : 	at com.google.android.gms.playlog.uploader.i.a(:com.google.android.gms:384)
07-05 14:04:56.326  1653  7192 E Auth    : 	at com.google.android.gms.playlog.uploader.UploaderService.b(:com.google.android.gms:100)
07-05 14:04:56.326  1653  7192 E Auth    : 	at com.google.android.gms.playlog.uploader.UploaderService.a(:com.google.android.gms:69)
07-05 14:04:56.326  1653  7192 E Auth    : 	at com.google.android.gms.gcm.aw.run(:com.google.android.gms:144)
,07-05 14:04:56.356  1653  7192 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
07-05 14:04:56.356  1653  7192 E Uploader: com.google.android.gms.auth.am: User intervention required. Notification has been pushed.
07-05 14:04:56.356  1653  7192 E Uploader: 	at com.google.android.gms.auth.q.f(:com.google.android.gms:330)
07-05 14:04:56.356  1653  7192 E Uploader: 	at com.google.android.gms.auth.q.b(:com.google.android.gms:195)
07-05 14:04:56.356  1653  7192 E Uploader: 	at com.google.android.gms.auth.q.a(:com.google.android.gms:146)
07-05 14:04:56.356  1653  7192 E Uploader: 	at com.google.android.gms.auth.q.a(:com.google.android.gms:73)
07-05 14:04:56.356  1653  7192 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(:com.google.android.gms:761)
07-05 14:04:56.356  1653  7192 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(:com.google.android.gms:582)
07-05 14:04:56.356  1653  7192 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(:com.google.android.gms:469)
07-05 14:04:56.356  1653  7192 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(:com.google.android.gms:384)
07-05 14:04:56.356  1653  7192 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(:com.google.android.gms:100)
07-05 14:04:56.356  1653  7192 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(:com.google.android.gms:69)
07-05 14:04:56.356  1653  7192 E Uploader: 	at com.google.android.gms.gcm.aw.run(:com.google.android.gms:144)
07-05 14:04:56.356  1653  7192 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
07-05 14:04:56.356  1653  7192 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
07-05 14:04:56.356  1653  7192 I qtaguid : Tagging socket 77 with tag 1000120100000000{268440065,0} uid -1, pid: 1653, getuid(): 10012
,07-05 14:04:56.706   767  1811 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,07-05 14:04:56.746  1653  7192 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,07-05 14:04:56.746  1653  7192 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,07-05 14:04:56.756  1653  7192 I qtaguid : Tagging socket 77 with tag 1000120100000000{268440065,0} uid -1, pid: 1653, getuid(): 10012
,07-05 14:04:56.796   767  3539 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-05 14:04:57.006   767  1764 V AlarmManager:  remove PendingIntent] PendingIntent{85100c9: PendingIntentRecord{560f6d7 com.google.android.gms broadcastIntent}}
,07-05 14:04:59.986   767  1237 V AlarmManager: Expired Alarm result :8
,07-05 14:05:02.546   767  4844 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 14:05:02.556   767  4844 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4383, temperature: 307, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,07-05 14:05:02.556   767  4844 D BatteryService: online:4, current avg:300, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
,07-05 14:05:02.556   767   767 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 14:05:02.566   767   767 I MotionRecognitionService: Plugged
,07-05 14:05:02.576   767   767 D MotionRecognitionService:   cableConnection= 1
,07-05 14:05:02.576   767   767 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,07-05 14:05:02.576   767   767 D MotionRecognitionService: skip setTransmitPower. 
,07-05 14:05:02.586   767  4844 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 35ms
,07-05 14:05:02.586   767  4844 D BatteryService: stay LED for charging
,07-05 14:05:02.606  1380  1380 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 14:05:02.606  1380  1380 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
07-05 14:05:02.606  1380  1380 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 14:05:02.616  2328  2328 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 14:05:02.626  2328  2834 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-05 14:05:02.626  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,07-05 14:05:02.626  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
07-05 14:05:02.626  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,07-05 14:05:05.356   767  3520 D SSRM:n  : SIOP:: AP = 330, PST = 384, CUR = 300, LCD = 0
,07-05 14:05:06.356   767  3521 W ResourcesManager: getTopLevelResources: /system/app/Bluetooth/Bluetooth.apk / 1.0 running in null rsrc of package null
,07-05 14:05:06.366   767  3521 W ResourcesManager: getTopLevelResources: /system/app/bootagent/bootagent.apk / 1.0 running in null rsrc of package null
,07-05 14:05:06.376   767  3521 W ResourcesManager: getTopLevelResources: /system/app/BluetoothTest/BluetoothTest.apk / 1.0 running in null rsrc of package null
,07-05 14:05:06.376   767  3521 W ResourcesManager: getTopLevelResources: /system/priv-app/SamsungLinkPlatform/SamsungLinkPlatform.apk / 1.0 running in null rsrc of package null
,07-05 14:05:06.436   767  3521 W ResourcesManager: getTopLevelResources: /system/app/SamsungIME/SamsungIME.apk / 1.0 running in null rsrc of package null
,07-05 14:05:06.446   767  3521 W ResourcesManager: getTopLevelResources: /system/app/WeatherDaemon2014_MMR/WeatherDaemon2014_MMR.apk / 1.0 running in null rsrc of package null
,07-05 14:05:06.456   767  3521 W ResourcesManager: getTopLevelResources: /system/priv-app/SystemUI/SystemUI.apk / 1.0 running in null rsrc of package null
,07-05 14:05:06.456   767  1604 E Watchdog: !@Sync 5 [07-05 14:05:06.469]
,07-05 14:05:06.466   767  3521 W ResourcesManager: getTopLevelResources: /system/priv-app/GmsCore/GmsCore.apk / 1.0 running in null rsrc of package null
,07-05 14:05:06.476   767  3521 W ResourcesManager: getTopLevelResources: /system/app/EdmSimPinService/EdmSimPinService.apk / 1.0 running in null rsrc of package null
,07-05 14:05:06.486   767  3521 W ResourcesManager: getTopLevelResources: /system/app/AntHalService/AntHalService.apk / 1.0 running in null rsrc of package null
,07-05 14:05:06.486   767  3521 W ResourcesManager: getTopLevelResources: /system/priv-app/CSC/CSC.apk / 1.0 running in null rsrc of package null
,07-05 14:05:06.496   767  3521 W ResourcesManager: getTopLevelResources: /system/framework/framework-res.apk / 1.0 running in null rsrc of package null
,07-05 14:05:06.496   767  3521 W ResourcesManager: getTopLevelResources: /system/priv-app/PageBuddyNotiSvcK/PageBuddyNotiSvcK.apk / 1.0 running in null rsrc of package null
,07-05 14:05:06.496   767  3521 W ResourcesManager: getTopLevelResources: /system/priv-app/Telecom/Telecom.apk / 1.0 running in null rsrc of package null
,07-05 14:05:06.506   767  3521 W ResourcesManager: getTopLevelResources: /system/priv-app/SmartcardManager/SmartcardManager.apk / 1.0 running in null rsrc of package null
,07-05 14:05:06.516   767  3521 W ResourcesManager: getTopLevelResources: /system/app/Stk/Stk.apk / 1.0 running in null rsrc of package null
,07-05 14:05:06.516   767  3521 W ResourcesManager: getTopLevelResources: /system/app/Stk/Stk.apk / 1.0 running in null rsrc of package null
,07-05 14:05:06.526   767  3521 W ResourcesManager: getTopLevelResources: /system/priv-app/SecMediaProvider/SecMediaProvider.apk / 1.0 running in null rsrc of package null
,07-05 14:05:06.526   767  3521 W ResourcesManager: getTopLevelResources: /system/priv-app/ContextProvider/ContextProvider.apk / 1.0 running in null rsrc of package null
,07-05 14:05:06.536   767  3521 W ResourcesManager: getTopLevelResources: /system/priv-app/TeleService/TeleService.apk / 1.0 running in null rsrc of package null
,07-05 14:05:06.556   767  3521 W ResourcesManager: getTopLevelResources: /system/priv-app/UcsPinpad/UcsPinpad.apk / 1.0 running in null rsrc of package null
,07-05 14:05:08.076  1653  3264 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,07-05 14:05:11.926   767  3521 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 b.J.a:-1 b.J.a:-1 b.L.run:-1 android.os.Handler.handleCallback:739 
,07-05 14:05:11.936   767  3521 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 b.J.a:-1 b.J.a:-1 b.N.run:-1 android.os.Handler.handleCallback:739 
,07-05 14:05:11.936   767   866 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{3c30001 u0 com.samsung.android.sm.lowpowercontext.START_ANALYSIS qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{65839ba 6270:com.samsung.android.sm.provider/1000}
,07-05 14:05:11.936   767  1679 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{f79b0e7 u0 com.samsung.android.sm.lowpowercontext.START_ANALYSIS qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{65839ba 6270:com.samsung.android.sm.provider/1000}
,07-05 14:05:13.056   304  1195 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
07-05 14:05:13.056   304  1195 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
07-05 14:05:13.056   304  1195 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,07-05 14:05:14.276   767  1237 V AlarmManager: Expired Alarm result :4
,07-05 14:05:14.366  1380  1380 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
,07-05 14:05:14.366  1380  1380 I PERF    : received broadcast android.intent.action.TIME_TICK
07-05 14:05:14.366  1380  1380 D KeyguardUpdateMonitor: handleTimeUpdate
,07-05 14:05:14.396  1380  1380 D SecKeyguardClockView: onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,07-05 14:05:14.406  1380  1380 D SecKeyguardClockView: HomeTimezone(): 1
,07-05 14:05:14.406   767  1679 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 14:05:14.416  1380  1380 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-05 14:05:14.416  1380  1380 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-05 14:05:14.426  1380  1380 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-05 14:05:14.426  1380  1380 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-05 14:05:14.426  1380  1380 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-05 14:05:14.426  1380  1380 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-05 14:05:14.426  1380  1380 D SecKeyguardStatusUtils: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-05 14:05:14.506  1380  1380 D SecKeyguardStatusUtils: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-05 14:05:14.836  1653  1653 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-05 14:05:14.846  1653  1653 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-05 14:05:14.846  1653  1653 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-05 14:05:14.866  1653  3945 E Auth    : [GoogleAccountDataServiceImpl] getToken() failed. Status BAD_AUTHENTICATION, Account: <ELLIDED:1197869880>, App: com.android.vending, Service: androidsecure
07-05 14:05:14.866  1653  3945 E Auth    : com.google.android.gms.auth.be.account.b.d: Long live credential not available.
07-05 14:05:14.866  1653  3945 E Auth    : 	at com.google.android.gms.auth.be.account.b.e.a(:com.google.android.gms:105)
07-05 14:05:14.866  1653  3945 E Auth    : 	at com.google.android.gms.auth.be.p.a(:com.google.android.gms:355)
07-05 14:05:14.866  1653  3945 E Auth    : 	at com.google.android.gms.auth.be.o.a(:com.google.android.gms:260)
07-05 14:05:14.866  1653  3945 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.y.a(:com.google.android.gms:197)
07-05 14:05:14.866  1653  3945 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.x.a(:com.google.android.gms:558)
07-05 14:05:14.866  1653  3945 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.x.a(:com.google.android.gms:196)
07-05 14:05:14.866  1653  3945 E Auth    : 	at com.google.android.gms.auth.o.a(:com.google.android.gms:276)
07-05 14:05:14.866  1653  3945 E Auth    : 	at com.google.android.gms.auth.o.a(:com.google.android.gms:196)
07-05 14:05:14.866  1653  3945 E Auth    : 	at com.google.android.gms.auth.t.a(:com.google.android.gms:498)
07-05 14:05:14.866  1653  3945 E Auth    : 	at com.google.android.gms.auth.s.a(:com.google.android.gms:908)
07-05 14:05:14.866  1653  3945 E Auth    : 	at com.google.android.gms.auth.s.e(:com.google.android.gms:528)
07-05 14:05:14.866  1653  3945 E Auth    : 	at com.google.android.gms.auth.be.m.getAuthToken(:com.google.android.gms:201)
07-05 14:05:14.866  1653  3945 E Auth    : 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
07-05 14:05:14.866  1653  3945 E Auth    : 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
07-05 14:05:14.866  1653  3945 E Auth    : 	at android.os.Binder.execTransact(Binder.java:453)
,07-05 14:05:14.896  5788  5788 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,07-05 14:05:14.896  5788  5788 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
07-05 14:05:14.896  5788  5788 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 5.
,07-05 14:05:15.156  6270  7221 W ResourcesManager: getTopLevelResources: /system/app/SecEmail_K/SecEmail_K.apk / 1.0 running in com.samsung.android.sm.provider rsrc of package null
,07-05 14:05:15.166  6270  7221 W ResourcesManager: getTopLevelResources: /system/priv-app/SecGallery2014/SecGallery2014.apk / 1.0 running in com.samsung.android.sm.provider rsrc of package null
,07-05 14:05:15.166  6270  7221 W ResourcesManager: getTopLevelResources: /system/priv-app/Phonesky/Phonesky.apk / 1.0 running in com.samsung.android.sm.provider rsrc of package null
,07-05 14:05:15.186  6270  7221 W ResourcesManager: getTopLevelResources: /system/priv-app/SHealth4/SHealth4.apk / 1.0 running in com.samsung.android.sm.provider rsrc of package null
,07-05 14:05:15.196  6270  7221 W ResourcesManager: getTopLevelResources: /system/priv-app/SecSettings/SecSettings.apk / 1.0 running in com.samsung.android.sm.provider rsrc of package null
,07-05 14:05:15.206  6270  7221 W ResourcesManager: getTopLevelResources: /system/priv-app/SamsungMusic_20_M/SamsungMusic_20_M.apk / 1.0 running in com.samsung.android.sm.provider rsrc of package null
,07-05 14:05:15.226  6270  7221 W ResourcesManager: getTopLevelResources: /system/priv-app/SamsungCamera3/SamsungCamera3.apk / 1.0 running in com.samsung.android.sm.provider rsrc of package null
,07-05 14:05:15.236  6270  7221 W ResourcesManager: getTopLevelResources: /system/priv-app/SecContacts_M_OSup_Legacy/SecContacts_M_OSup_Legacy.apk / 1.0 running in com.samsung.android.sm.provider rsrc of package null
,07-05 14:05:15.246  6270  7221 W ResourcesManager: getTopLevelResources: /system/priv-app/SecContacts_M_OSup_Legacy/SecContacts_M_OSup_Legacy.apk / 1.0 running in com.samsung.android.sm.provider rsrc of package null
,07-05 14:05:15.246  6270  7221 W ResourcesManager: getTopLevelResources: /system/priv-app/SecMms_Candy_M/SecMms_Candy_M.apk / 1.0 running in com.samsung.android.sm.provider rsrc of package null
,07-05 14:05:15.256  6270  7221 W ResourcesManager: getTopLevelResources: /system/app/Photos/Photos.apk / 1.0 running in com.samsung.android.sm.provider rsrc of package null
,07-05 14:05:15.266  6270  7221 W ResourcesManager: getTopLevelResources: /system/app/Chrome/Chrome.apk / 1.0 running in com.samsung.android.sm.provider rsrc of package null
,07-05 14:05:15.276  6270  7221 W ResourcesManager: getTopLevelResources: /system/app/Drive/Drive.apk / 1.0 running in com.samsung.android.sm.provider rsrc of package null
,07-05 14:05:15.286  6270  7221 W ResourcesManager: getTopLevelResources: /system/app/EditorsDocs/EditorsDocs.apk / 1.0 running in com.samsung.android.sm.provider rsrc of package null
,07-05 14:05:15.296  6270  7221 W ResourcesManager: getTopLevelResources: /system/app/Flipboard/Flipboard.apk / 1.0 running in com.samsung.android.sm.provider rsrc of package null
,07-05 14:05:15.306  6270  7221 W ResourcesManager: getTopLevelResources: /system/app/Gmail2/Gmail2.apk / 1.0 running in com.samsung.android.sm.provider rsrc of package null
,07-05 14:05:15.316  6270  7221 W ResourcesManager: getTopLevelResources: /system/app/Hangouts/Hangouts.apk / 1.0 running in com.samsung.android.sm.provider rsrc of package null
,07-05 14:05:15.336  6270  7221 W ResourcesManager: getTopLevelResources: /system/app/Music2/Music2.apk / 1.0 running in com.samsung.android.sm.provider rsrc of package null
,07-05 14:05:15.346  6270  7221 W ResourcesManager: getTopLevelResources: /system/app/Newsstand/Newsstand.apk / 1.0 running in com.samsung.android.sm.provider rsrc of package null
,07-05 14:05:15.356  6270  7221 W ResourcesManager: getTopLevelResources: /system/app/Videos/Videos.apk / 1.0 running in com.samsung.android.sm.provider rsrc of package null
,07-05 14:05:15.366  6270  7221 W ResourcesManager: getTopLevelResources: /system/app/YouTube/YouTube.apk / 1.0 running in com.samsung.android.sm.provider rsrc of package null
,07-05 14:05:15.376  6270  7221 W ResourcesManager: getTopLevelResources: /system/app/SPlanner_M_OS_UPG/SPlanner_M_OS_UPG.apk / 1.0 running in com.samsung.android.sm.provider rsrc of package null
,07-05 14:05:15.376  6270  7221 W ResourcesManager: getTopLevelResources: /system/app/SBrowser_4_LATEST/SBrowser_4_LATEST.apk / 1.0 running in com.samsung.android.sm.provider rsrc of package null
,07-05 14:05:15.386  6270  7221 W ResourcesManager: getTopLevelResources: /system/priv-app/S-Voice_Android_phone/S-Voice_Android_phone.apk / 1.0 running in com.samsung.android.sm.provider rsrc of package null
,07-05 14:05:15.396  6270  7221 W ResourcesManager: getTopLevelResources: /system/priv-app/SecVideo/SecVideo.apk / 1.0 running in com.samsung.android.sm.provider rsrc of package null
,07-05 14:05:15.406   767  3520 D SSRM:n  : SIOP:: AP = 340, PST = 372, CUR = 300, LCD = 0
,07-05 14:05:15.406  6270  7221 W ResourcesManager: getTopLevelResources: /system/priv-app/SecMyFiles2014/SecMyFiles2014.apk / 1.0 running in com.samsung.android.sm.provider rsrc of package null
,07-05 14:05:15.416  6270  7221 W ResourcesManager: getTopLevelResources: /system/priv-app/Velvet/Velvet.apk / 1.0 running in com.samsung.android.sm.provider rsrc of package null
,07-05 14:05:15.426  6270  7221 W ResourcesManager: getTopLevelResources: /system/priv-app/Velvet/Velvet.apk / 1.0 running in com.samsung.android.sm.provider rsrc of package null
,07-05 14:05:15.426  6270  7221 W ResourcesManager: getTopLevelResources: /system/priv-app/VoiceNote/VoiceNote.apk / 1.0 running in com.samsung.android.sm.provider rsrc of package null
,07-05 14:05:15.436  6270  7221 W ResourcesManager: getTopLevelResources: /system/priv-app/SmartManager_v3/SmartManager_v3.apk / 1.0 running in com.samsung.android.sm.provider rsrc of package null
,07-05 14:05:15.436  6270  7221 W ResourcesManager: getTopLevelResources: /system/priv-app/SecCalculator2_LMUPG/SecCalculator2_LMUPG.apk / 1.0 running in com.samsung.android.sm.provider rsrc of package null
,07-05 14:05:15.456  6270  7221 W ResourcesManager: getTopLevelResources: /system/app/Books/Books.apk / 1.0 running in com.samsung.android.sm.provider rsrc of package null
,07-05 14:05:15.456  6270  7221 W ResourcesManager: getTopLevelResources: /system/app/Dropbox/Dropbox.apk / 1.0 running in com.samsung.android.sm.provider rsrc of package null
,07-05 14:05:15.466  6270  7221 W ResourcesManager: getTopLevelResources: /system/app/Maps/Maps.apk / 1.0 running in com.samsung.android.sm.provider rsrc of package null
,07-05 14:05:15.476  6270  7221 W ResourcesManager: getTopLevelResources: /system/app/PlayGames/PlayGames.apk / 1.0 running in com.samsung.android.sm.provider rsrc of package null
,07-05 14:05:15.486  6270  7221 W ResourcesManager: getTopLevelResources: /system/app/PlusOne/PlusOne.apk / 1.0 running in com.samsung.android.sm.provider rsrc of package null
,07-05 14:05:15.496  6270  7221 W ResourcesManager: getTopLevelResources: /system/app/SecMemoDL/SecMemoDL.apk / 1.0 running in com.samsung.android.sm.provider rsrc of package null
,07-05 14:05:15.496  6270  7221 W ResourcesManager: getTopLevelResources: /system/app/SmartRemote_KL/SmartRemote_KL.apk / 1.0 running in com.samsung.android.sm.provider rsrc of package null
,07-05 14:05:15.646  6270  7221 W ResourcesManager: getTopLevelResources: /system/app/ClockPackage_MUPG/ClockPackage_MUPG.apk / 1.0 running in com.samsung.android.sm.provider rsrc of package null
,07-05 14:05:15.676  6270  7221 W ResourcesManager: getTopLevelResources: /data/app/com.sec.android.app.samsungapps-2/base.apk / 1.0 running in com.samsung.android.sm.provider rsrc of package null
,07-05 14:05:15.706  6270  7221 W ResourcesManager: getTopLevelResources: /data/app/de.pizza-1/base.apk / 1.0 running in com.samsung.android.sm.provider rsrc of package null
,07-05 14:05:15.716  6270  7221 W ResourcesManager: getTopLevelResources: /data/app/de.kaufda.android-1/base.apk / 1.0 running in com.samsung.android.sm.provider rsrc of package null
,07-05 14:05:15.726  6270  7221 W ResourcesManager: getTopLevelResources: /data/app/de.samsung.MeinGalaxy-1/base.apk / 1.0 running in com.samsung.android.sm.provider rsrc of package null
,07-05 14:05:15.746  6270  7221 W ResourcesManager: getTopLevelResources: /data/app/com.paypal.android.p2pmobile-1/base.apk / 1.0 running in com.samsung.android.sm.provider rsrc of package null
,07-05 14:05:15.756  6270  7221 W ResourcesManager: getTopLevelResources: /data/app/de.zalando.mobile-1/base.apk / 1.0 running in com.samsung.android.sm.provider rsrc of package null
,07-05 14:05:15.776  6270  7221 W ResourcesManager: getTopLevelResources: /data/app/de.worldiety.photiety.cewe.smartphoto.de-2/base.apk / 1.0 running in com.samsung.android.sm.provider rsrc of package null
,07-05 14:05:15.786  6270  7221 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.samsung.android.sm.provider rsrc of package null
,07-05 14:05:16.796   767  3539 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-05 14:05:24.436   767  1811 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 14:05:25.456   767  3520 D SSRM:n  : SIOP:: AP = 330, PST = 363, CUR = 300, LCD = 0
,07-05 14:05:34.916   767  1237 V AlarmManager: Expired Alarm result :4
,07-05 14:05:34.986   767  1409 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 14:05:34.986   767  1409 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4385, temperature: 307, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,07-05 14:05:34.986   767  1409 D BatteryService: online:4, current avg:300, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
07-05 14:05:34.986   767  1409 D BatteryService: stay LED for charging
07-05 14:05:34.986   767   767 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 14:05:34.996   767   767 I MotionRecognitionService: Plugged
,07-05 14:05:34.996   767   767 D MotionRecognitionService:   cableConnection= 1
,07-05 14:05:34.996   767   767 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
07-05 14:05:34.996   767   767 D MotionRecognitionService: skip setTransmitPower. 
,07-05 14:05:34.996  1380  1380 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 14:05:34.996  1380  1380 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,07-05 14:05:35.006  1380  1380 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 14:05:35.016  2328  2328 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 14:05:35.016  2328  2834 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-05 14:05:35.026  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,07-05 14:05:35.026  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
07-05 14:05:35.026  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,07-05 14:05:35.516   767  3520 D SSRM:n  : SIOP:: AP = 320, PST = 354, CUR = 300, LCD = 0
,07-05 14:05:35.646  1653  1653 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-05 14:05:35.656  1653  1653 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-05 14:05:35.666  1653  1653 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-05 14:05:35.686  1653  1670 E Auth    : [GoogleAccountDataServiceImpl] getToken() failed. Status BAD_AUTHENTICATION, Account: <ELLIDED:1197869880>, App: com.android.vending, Service: androidsecure
07-05 14:05:35.686  1653  1670 E Auth    : com.google.android.gms.auth.be.account.b.d: Long live credential not available.
07-05 14:05:35.686  1653  1670 E Auth    : 	at com.google.android.gms.auth.be.account.b.e.a(:com.google.android.gms:105)
07-05 14:05:35.686  1653  1670 E Auth    : 	at com.google.android.gms.auth.be.p.a(:com.google.android.gms:355)
07-05 14:05:35.686  1653  1670 E Auth    : 	at com.google.android.gms.auth.be.o.a(:com.google.android.gms:260)
07-05 14:05:35.686  1653  1670 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.y.a(:com.google.android.gms:197)
07-05 14:05:35.686  1653  1670 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.x.a(:com.google.android.gms:558)
07-05 14:05:35.686  1653  1670 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.x.a(:com.google.android.gms:196)
07-05 14:05:35.686  1653  1670 E Auth    : 	at com.google.android.gms.auth.o.a(:com.google.android.gms:276)
07-05 14:05:35.686  1653  1670 E Auth    : 	at com.google.android.gms.auth.o.a(:com.google.android.gms:196)
07-05 14:05:35.686  1653  1670 E Auth    : 	at com.google.android.gms.auth.t.a(:com.google.android.gms:498)
07-05 14:05:35.686  1653  1670 E Auth    : 	at com.google.android.gms.auth.s.a(:com.google.android.gms:908)
07-05 14:05:35.686  1653  1670 E Auth    : 	at com.google.android.gms.auth.s.e(:com.google.android.gms:528)
07-05 14:05:35.686  1653  1670 E Auth    : 	at com.google.android.gms.auth.be.m.getAuthToken(:com.google.android.gms:201)
07-05 14:05:35.686  1653  1670 E Auth    : 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
07-05 14:05:35.686  1653  1670 E Auth    : 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
07-05 14:05:35.686  1653  1670 E Auth    : 	at android.os.Binder.execTransact(Binder.java:453)
,07-05 14:05:35.716  5788  5788 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,07-05 14:05:35.716  5788  5788 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
07-05 14:05:35.716  5788  5788 D Finsky  : [1] ContentSyncService$5.onFinished: Giving up after 6 failures.
,07-05 14:05:36.456   767  1604 E Watchdog: !@Sync 6 [07-05 14:05:36.471]
,07-05 14:05:36.796   767  3539 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-05 14:05:37.296  1664  1768 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,07-05 14:05:45.066   767  4119 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 14:05:45.586   767  3520 D SSRM:n  : SIOP:: AP = 320, PST = 345, CUR = 300, LCD = 0
,07-05 14:05:55.066  1653  1653 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-05 14:05:55.076  1653  1653 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-05 14:05:55.146   767  1409 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 14:05:55.146   767  1409 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4365, temperature: 307, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
07-05 14:05:55.146   767  1409 D BatteryService: online:4, current avg:300, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
,07-05 14:05:55.146   767   767 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 14:05:55.156   767  1409 D LightsService: [api] [SvcLED] setFlashing :: id = 5, color = 0, mode = 14, onMS = 0, offMS = 0,  (uid: 1000 pid: 767) 
,07-05 14:05:55.156   767  1409 D LightsService: [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x10 -> 0x40 | SvcLED(id=5) set On
,07-05 14:05:55.156   767   767 I MotionRecognitionService: Plugged
07-05 14:05:55.156   767   767 D MotionRecognitionService:   cableConnection= 1
07-05 14:05:55.156   767   767 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
07-05 14:05:55.156   767   767 D MotionRecognitionService: skip setTransmitPower. 
,07-05 14:05:55.156   767  1409 D SensorService: SensorEventConnection::SocketBufferSize, SystemSocketBufferSize - 102400, 2097152
,07-05 14:05:55.156   767  1409 E LightSensor: Light old sensor_state 0, new sensor_state : 512 en : 1
,07-05 14:05:55.166  1380  1380 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
07-05 14:05:55.166  1380  1380 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,07-05 14:05:55.166  1380  1380 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 14:05:55.166  1653  7172 E Auth    : [GoogleAccountDataServiceImpl] getToken() failed. Status BAD_AUTHENTICATION, Account: <ELLIDED:-818113082>, App: com.google.android.gms, Service: oauth2:https://www.googleapis.com/auth/contextcontroller
07-05 14:05:55.166  1653  7172 E Auth    : com.google.android.gms.auth.be.account.b.d: Long live credential not available.
07-05 14:05:55.166  1653  7172 E Auth    : 	at com.google.android.gms.auth.be.account.b.e.a(:com.google.android.gms:105)
07-05 14:05:55.166  1653  7172 E Auth    : 	at com.google.android.gms.auth.be.p.a(:com.google.android.gms:355)
07-05 14:05:55.166  1653  7172 E Auth    : 	at com.google.android.gms.auth.be.o.a(:com.google.android.gms:260)
07-05 14:05:55.166  1653  7172 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.y.a(:com.google.android.gms:197)
07-05 14:05:55.166  1653  7172 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.x.a(:com.google.android.gms:558)
07-05 14:05:55.166  1653  7172 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.x.a(:com.google.android.gms:196)
07-05 14:05:55.166  1653  7172 E Auth    : 	at com.google.android.gms.auth.o.a(:com.google.android.gms:276)
07-05 14:05:55.166  1653  7172 E Auth    : 	at com.google.android.gms.auth.o.a(:com.google.android.gms:196)
07-05 14:05:55.166  1653  7172 E Auth    : 	at com.google.android.gms.auth.t.a(:com.google.android.gms:498)
07-05 14:05:55.166  1653  7172 E Auth    : 	at com.google.android.gms.auth.s.a(:com.google.android.gms:908)
07-05 14:05:55.166  1653  7172 E Auth    : 	at com.google.android.gms.auth.s.e(:com.google.android.gms:528)
07-05 14:05:55.166  1653  7172 E Auth    : 	at com.google.android.gms.auth.s.d(:com.google.android.gms:450)
07-05 14:05:55.166  1653  7172 E Auth    : 	at com.google.android.gms.auth.q.c(:com.google.android.gms:586)
07-05 14:05:55.166  1653  7172 E Auth    : 	at com.google.android.gms.common.server.a.a.a(:com.google.android.gms:82)
07-05 14:05:55.166  1653  7172 E Auth    : 	at com.google.android.gms.common.server.c.a(:com.google.android.gms:59)
07-05 14:05:55.166  1653  7172 E Auth    : 	at com.google.android.gms.common.server.s.a(:com.google.android.gms:61)
07-05 14:05:55.166  1653  7172 E Auth    : 	at com.google.android.gms.common.server.s.a(:com.google.android.gms:140)
07-05 14:05:55.166  1653  7172 E Auth    : 	at com.google.android.contextmanager.l.a.a.a(:com.google.android.gms:130)
07-05 14:05:55.166  1653  7172 E Auth    : 	at com.google.android.contextmanager.g.a.a.run(:com.google.android.gms:52)
07-05 14:05:55.166  1653  7172 E Auth    : 	at com.google.android.contextmanager.g.i.a(:com.google.android.gms:263)
07-05 14:05:55.166  1653  7172 E Auth    : 	at com.google.android.contextmanager.g.i.handleMessage(:com.google.android.gms:254)
07-05 14:05:55.166  1653  7172 E Auth    : 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-05 14:05:55.166  1653  7172 E Auth    : 	at android.os.Looper.loop(Looper.java:158)
07-05 14:05:55.166  1653  7172 E Auth    : 	at android.os.HandlerThread.run(HandlerThread.java:61)
,07-05 14:05:55.166  1380  1380 D SecKeyguardStatusUtils: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-05 14:05:55.176   767  1409 D SensorManager: registerListener :: 6, TMG399X RGB Sensor, 200000, 0,  
07-05 14:05:55.176   767  1409 D BatteryService: turn on LED for fully charged
,07-05 14:05:55.186  2328  2328 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
07-05 14:05:55.186  2328  2834 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-05 14:05:55.196  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:05:55.196  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 14:05:55.196  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:05:55.226  1653  7172 W AuthSessionAuthenticato: Auth related exception is being ignored: BadAuthentication
,07-05 14:05:55.346  1653  7172 E Auth    : [GoogleAccountDataServiceImpl] getToken() failed. Status BAD_AUTHENTICATION, Account: <ELLIDED:1197869880>, App: com.google.android.gms, Service: oauth2:https://www.googleapis.com/auth/contextcontroller
07-05 14:05:55.346  1653  7172 E Auth    : com.google.android.gms.auth.be.account.b.d: Long live credential not available.
07-05 14:05:55.346  1653  7172 E Auth    : 	at com.google.android.gms.auth.be.account.b.e.a(:com.google.android.gms:105)
07-05 14:05:55.346  1653  7172 E Auth    : 	at com.google.android.gms.auth.be.p.a(:com.google.android.gms:355)
07-05 14:05:55.346  1653  7172 E Auth    : 	at com.google.android.gms.auth.be.o.a(:com.google.android.gms:260)
07-05 14:05:55.346  1653  7172 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.y.a(:com.google.android.gms:197)
07-05 14:05:55.346  1653  7172 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.x.a(:com.google.android.gms:558)
07-05 14:05:55.346  1653  7172 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.x.a(:com.google.android.gms:196)
07-05 14:05:55.346  1653  7172 E Auth    : 	at com.google.android.gms.auth.o.a(:com.google.android.gms:276)
07-05 14:05:55.346  1653  7172 E Auth    : 	at com.google.android.gms.auth.o.a(:com.google.android.gms:196)
07-05 14:05:55.346  1653  7172 E Auth    : 	at com.google.android.gms.auth.t.a(:com.google.android.gms:498)
07-05 14:05:55.346  1653  7172 E Auth    : 	at com.google.android.gms.auth.s.a(:com.google.android.gms:908)
07-05 14:05:55.346  1653  7172 E Auth    : 	at com.google.android.gms.auth.s.e(:com.google.android.gms:528)
07-05 14:05:55.346  1653  7172 E Auth    : 	at com.google.android.gms.auth.s.d(:com.google.android.gms:450)
07-05 14:05:55.346  1653  7172 E Auth    : 	at com.google.android.gms.auth.q.c(:com.google.android.gms:586)
07-05 14:05:55.346  1653  7172 E Auth    : 	at com.google.android.gms.common.server.a.a.a(:com.google.android.gms:82)
07-05 14:05:55.346  1653  7172 E Auth    : 	at com.google.android.gms.common.server.c.a(:com.google.android.gms:59)
07-05 14:05:55.346  1653  7172 E Auth    : 	at com.google.android.gms.common.server.s.a(:com.google.android.gms:61)
07-05 14:05:55.346  1653  7172 E Auth    : 	at com.google.android.gms.common.server.s.a(:com.google.android.gms:140)
07-05 14:05:55.346  1653  7172 E Auth    : 	at com.google.android.contextmanager.l.a.a.a(:com.google.android.gms:130)
07-05 14:05:55.346  1653  7172 E Auth    : 	at com.google.android.contextmanager.g.a.a.run(:com.google.android.gms:52)
07-05 14:05:55.346  1653  7172 E Auth    : 	at com.google.android.contextmanager.g.i.a(:com.google.android.gms:263)
07-05 14:05:55.346  1653  7172 E Auth    : 	at com.google.android.contextmanager.g.i.handleMessage(:com.google.android.gms:254)
07-05 14:05:55.346  1653  7172 E Auth    : 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-05 14:05:55.346  1653  7172 E Auth    : 	at android.os.Looper.loop(Looper.java:158)
07-05 14:05:55.346  1653  7172 E Auth    : 	at android.os.HandlerThread.run(HandlerThread.java:61)
,07-05 14:05:55.386  1653  7172 W AuthSessionAuthenticato: Auth related exception is being ignored: BadAuthentication
,07-05 14:05:55.446  1653  7172 E Auth    : [GoogleAccountDataServiceImpl] getToken() failed. Status BAD_AUTHENTICATION, Account: <ELLIDED:1197869880>, App: com.google.android.gms, Service: oauth2:https://www.googleapis.com/auth/contextcontroller
07-05 14:05:55.446  1653  7172 E Auth    : com.google.android.gms.auth.be.account.b.d: Long live credential not available.
07-05 14:05:55.446  1653  7172 E Auth    : 	at com.google.android.gms.auth.be.account.b.e.a(:com.google.android.gms:105)
07-05 14:05:55.446  1653  7172 E Auth    : 	at com.google.android.gms.auth.be.p.a(:com.google.android.gms:355)
07-05 14:05:55.446  1653  7172 E Auth    : 	at com.google.android.gms.auth.be.o.a(:com.google.android.gms:260)
07-05 14:05:55.446  1653  7172 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.y.a(:com.google.android.gms:197)
07-05 14:05:55.446  1653  7172 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.x.a(:com.google.android.gms:558)
07-05 14:05:55.446  1653  7172 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.x.a(:com.google.android.gms:196)
07-05 14:05:55.446  1653  7172 E Auth    : 	at com.google.android.gms.auth.o.a(:com.google.android.gms:276)
07-05 14:05:55.446  1653  7172 E Auth    : 	at com.google.android.gms.auth.o.a(:com.google.android.gms:196)
07-05 14:05:55.446  1653  7172 E Auth    : 	at com.google.android.gms.auth.t.a(:com.google.android.gms:498)
07-05 14:05:55.446  1653  7172 E Auth    : 	at com.google.android.gms.auth.s.a(:com.google.android.gms:908)
07-05 14:05:55.446  1653  7172 E Auth    : 	at com.google.android.gms.auth.s.e(:com.google.android.gms:528)
07-05 14:05:55.446  1653  7172 E Auth    : 	at com.google.android.gms.auth.s.d(:com.google.android.gms:450)
07-05 14:05:55.446  1653  7172 E Auth    : 	at com.google.android.gms.auth.q.c(:com.google.android.gms:586)
07-05 14:05:55.446  1653  7172 E Auth    : 	at com.google.android.gms.common.server.a.a.a(:com.google.android.gms:82)
07-05 14:05:55.446  1653  7172 E Auth    : 	at com.google.android.gms.common.server.c.a(:com.google.android.gms:59)
07-05 14:05:55.446  1653  7172 E Auth    : 	at com.google.android.gms.common.server.s.a(:com.google.android.gms:61)
07-05 14:05:55.446  1653  7172 E Auth    : 	at com.google.android.gms.common.server.s.a(:com.google.android.gms:140)
07-05 14:05:55.446  1653  7172 E Auth    : 	at com.google.android.contextmanager.l.a.a.a(:com.google.android.gms:130)
07-05 14:05:55.446  1653  7172 E Auth    : 	at com.google.android.contextmanager.g.a.a.run(:com.google.android.gms:52)
07-05 14:05:55.446  1653  7172 E Auth    : 	at com.google.android.contextmanager.g.i.a(:com.google.android.gms:263)
07-05 14:05:55.446  1653  7172 E Auth    : 	at com.google.android.contextmanager.g.i.handleMessage(:com.google.android.gms:254)
07-05 14:05:55.446  1653  7172 E Auth    : 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-05 14:05:55.446  1653  7172 E Auth    : 	at android.os.Looper.loop(Looper.java:158)
07-05 14:05:55.446  1653  7172 E Auth    : 	at android.os.HandlerThread.run(HandlerThread.java:61)
,07-05 14:05:55.476  1653  7172 W AuthSessionAuthenticato: Auth related exception is being ignored: BadAuthentication
,07-05 14:05:55.516  1653  7172 W ctxmgr  : [DeviceRegistrationSync]Failed device registration sync (statusCode=UNKNOWN).  Giving up.
,07-05 14:05:55.516  1653  7172 E ctxmgr  : [SyncServerInterestRecordsOperation]Failure response from WriteInterestRecord. StatusCode = -1
,07-05 14:05:55.536   767  1220 E LightSensor: RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=0, cp1=0, cpl=3202560
,07-05 14:05:55.536   767   930 D LightsService: [SvcLED]  onSensorChanged::light value = 0
,07-05 14:05:55.536   767   930 E LightSensor: Light old sensor_state 512, new sensor_state : 0 en : 0
,07-05 14:05:55.546   767   930 D SensorManager: unregisterListener ::   
07-05 14:05:55.546   767   930 D lights  : led_pattern : 5 +
,07-05 14:05:55.556   767   930 D lights  : led_pattern : 5 -
07-05 14:05:55.556   767   930 D LightsService: [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=5) maintains its priority right
,07-05 14:05:55.556   767   930 V AlarmManager:  remove PendingIntent] PendingIntent{79303aa: PendingIntentRecord{4328b9b android broadcastIntent}}
,07-05 14:05:55.566  1653  7172 W ctxmgr  : [AclUpdateManager]Failed Acl fetch for account account#61035162# with status: UNKNOWN).  Giving up.
,07-05 14:05:55.636   767  3520 D SSRM:n  : SIOP:: AP = 320, PST = 336, CUR = 300, LCD = 0
,07-05 14:05:56.806   767  3539 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-05 14:05:59.986   767  1237 V AlarmManager: Expired Alarm result :8
,07-05 14:06:05.226   767  4844 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 14:06:05.236   767  4844 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 307, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,07-05 14:06:05.236   767  4844 D BatteryService: online:4, current avg:300, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
,07-05 14:06:05.236   767   767 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 14:06:05.256   767   767 I MotionRecognitionService: Plugged
,07-05 14:06:05.256   767   767 D MotionRecognitionService:   cableConnection= 1
,07-05 14:06:05.256   767   767 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,07-05 14:06:05.256   767   767 D MotionRecognitionService: skip setTransmitPower. 
,07-05 14:06:05.266   767  4844 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 33ms
,07-05 14:06:05.266   767  4844 D BatteryService: stay LED for fully charged
,07-05 14:06:05.286  1380  1380 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 14:06:05.286  1380  1380 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,07-05 14:06:05.286  1380  1380 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 14:06:05.306  2328  2328 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 14:06:05.306  2328  2834 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-05 14:06:05.316  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:06:05.316  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:06:05.316  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:06:05.686   767  3520 D SSRM:n  : SIOP:: AP = 320, PST = 331, CUR = 300, LCD = 0
,07-05 14:06:06.466   767  1604 E Watchdog: !@Sync 7 [07-05 14:06:06.477]
,07-05 14:06:15.326   767  1764 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 14:06:15.326   767  1764 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 306, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,07-05 14:06:15.326   767  1764 D BatteryService: online:4, current avg:300, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
,07-05 14:06:15.336   767   767 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 14:06:15.346   767   767 I MotionRecognitionService: Plugged
,07-05 14:06:15.346   767   767 D MotionRecognitionService:   cableConnection= 1
,07-05 14:06:15.346   767   767 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,07-05 14:06:15.356   767   767 D MotionRecognitionService: skip setTransmitPower. 
,07-05 14:06:15.356   767  1764 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 28ms
,07-05 14:06:15.356   767  1764 D BatteryService: stay LED for fully charged
,07-05 14:06:15.356  1380  1380 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 14:06:15.356  1380  1380 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
07-05 14:06:15.356  1380  1380 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 14:06:15.376  2328  2328 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 14:06:15.376  2328  2834 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-05 14:06:15.386  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:06:15.386  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 14:06:15.386  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:06:15.746   767  3520 D SSRM:n  : SIOP:: AP = 310, PST = 327, CUR = 300, LCD = 0
,07-05 14:06:16.806   767  3539 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-05 14:06:25.406   767   785 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 14:06:25.406   767   785 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 306, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,07-05 14:06:25.416   767   785 D BatteryService: online:4, current avg:300, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
,07-05 14:06:25.416   767   767 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 14:06:25.426   767   767 I MotionRecognitionService: Plugged
,07-05 14:06:25.436   767   785 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 23ms
,07-05 14:06:25.436   767   767 D MotionRecognitionService:   cableConnection= 1
,07-05 14:06:25.436   767   767 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,07-05 14:06:25.436   767   785 D BatteryService: stay LED for fully charged
,07-05 14:06:25.446   767   767 D MotionRecognitionService: skip setTransmitPower. 
,07-05 14:06:25.456  1380  1380 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 14:06:25.456  1380  1380 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
07-05 14:06:25.456  1380  1380 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 14:06:25.466  2328  2328 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 14:06:25.466  2328  2834 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-05 14:06:25.486  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:06:25.486  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 14:06:25.486  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:06:25.806   767  3520 D SSRM:n  : SIOP:: AP = 310, PST = 324, CUR = 300, LCD = 0
,07-05 14:06:35.866   767  3520 D SSRM:n  : SIOP:: AP = 310, PST = 321, CUR = 300, LCD = 0
,07-05 14:06:36.476   767  1604 E Watchdog: !@Sync 8 [07-05 14:06:36.483]
,07-05 14:06:36.806   767  3539 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-05 14:06:37.316  1664  1768 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,07-05 14:06:42.886   767  1237 V AlarmManager: Expired Alarm result :4
,07-05 14:06:42.906  1380  1380 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
,07-05 14:06:42.906  1380  1380 I PERF    : received broadcast android.intent.action.TIME_TICK
,07-05 14:06:42.916  1380  1380 D KeyguardUpdateMonitor: handleTimeUpdate
,07-05 14:06:42.956   767  1767 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 14:06:42.956   767  1767 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 306, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
07-05 14:06:42.956   767  1767 D BatteryService: online:4, current avg:300, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
,07-05 14:06:42.966   767  1767 D BatteryService: stay LED for fully charged
,07-05 14:06:42.966  1380  1380 D SecKeyguardClockView: onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,07-05 14:06:42.976  1380  1380 D SecKeyguardClockView: HomeTimezone(): 1
,07-05 14:06:43.006  1380  1380 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-05 14:06:43.006  1380  1380 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-05 14:06:43.006  1380  1380 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-05 14:06:43.006  1380  1380 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
07-05 14:06:43.006  1380  1380 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-05 14:06:43.006  1380  1380 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-05 14:06:43.006  1380  1380 D SecKeyguardStatusUtils: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
07-05 14:06:43.006   767   767 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 14:06:43.026  2328  2328 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 14:06:43.026  2328  2834 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-05 14:06:43.036   767   767 I MotionRecognitionService: Plugged
,07-05 14:06:43.036   767   767 D MotionRecognitionService:   cableConnection= 1
07-05 14:06:43.036   767   767 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
07-05 14:06:43.036   767   767 D MotionRecognitionService: skip setTransmitPower. 
,07-05 14:06:43.046  1380  1380 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 14:06:43.046  1380  1380 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,07-05 14:06:43.046  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:06:43.046  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:06:43.046  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:06:43.056  1380  1380 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 14:06:43.106  1380  1380 D SecKeyguardStatusUtils: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-05 14:06:43.236  6809  7321 I BooksSync: Starting books sync for 61035162, extras: ade
,07-05 14:06:43.316  1653  1653 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-05 14:06:43.326  1653  1653 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-05 14:06:43.376  1653  3945 E Auth    : [GoogleAccountDataServiceImpl] getToken() failed. Status BAD_AUTHENTICATION, Account: <ELLIDED:1197869880>, App: com.google.android.apps.books, Service: oauth2:https://www.googleapis.com/auth/books
07-05 14:06:43.376  1653  3945 E Auth    : com.google.android.gms.auth.be.account.b.d: Long live credential not available.
07-05 14:06:43.376  1653  3945 E Auth    : 	at com.google.android.gms.auth.be.account.b.e.a(:com.google.android.gms:105)
07-05 14:06:43.376  1653  3945 E Auth    : 	at com.google.android.gms.auth.be.p.a(:com.google.android.gms:355)
07-05 14:06:43.376  1653  3945 E Auth    : 	at com.google.android.gms.auth.be.o.a(:com.google.android.gms:260)
07-05 14:06:43.376  1653  3945 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.y.a(:com.google.android.gms:197)
07-05 14:06:43.376  1653  3945 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.x.a(:com.google.android.gms:558)
07-05 14:06:43.376  1653  3945 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.x.a(:com.google.android.gms:196)
07-05 14:06:43.376  1653  3945 E Auth    : 	at com.google.android.gms.auth.o.a(:com.google.android.gms:276)
07-05 14:06:43.376  1653  3945 E Auth    : 	at com.google.android.gms.auth.o.a(:com.google.android.gms:196)
07-05 14:06:43.376  1653  3945 E Auth    : 	at com.google.android.b.b.onTransact(:com.google.android.gms:137)
07-05 14:06:43.376  1653  3945 E Auth    : 	at android.os.Binder.execTransact(Binder.java:453)
,07-05 14:06:43.436  1653  2252 E Auth    : [GoogleAccountDataServiceImpl] getToken() failed. Status BAD_AUTHENTICATION, Account: <ELLIDED:1197869880>, App: com.google.android.apps.books, Service: oauth2:https://www.googleapis.com/auth/books
07-05 14:06:43.436  1653  2252 E Auth    : com.google.android.gms.auth.be.account.b.d: Long live credential not available.
07-05 14:06:43.436  1653  2252 E Auth    : 	at com.google.android.gms.auth.be.account.b.e.a(:com.google.android.gms:105)
07-05 14:06:43.436  1653  2252 E Auth    : 	at com.google.android.gms.auth.be.p.a(:com.google.android.gms:355)
07-05 14:06:43.436  1653  2252 E Auth    : 	at com.google.android.gms.auth.be.o.a(:com.google.android.gms:260)
07-05 14:06:43.436  1653  2252 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.y.a(:com.google.android.gms:197)
07-05 14:06:43.436  1653  2252 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.x.a(:com.google.android.gms:558)
07-05 14:06:43.436  1653  2252 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.x.a(:com.google.android.gms:196)
07-05 14:06:43.436  1653  2252 E Auth    : 	at com.google.android.gms.auth.o.a(:com.google.android.gms:276)
07-05 14:06:43.436  1653  2252 E Auth    : 	at com.google.android.gms.auth.o.a(:com.google.android.gms:196)
07-05 14:06:43.436  1653  2252 E Auth    : 	at com.google.android.b.b.onTransact(:com.google.android.gms:137)
07-05 14:06:43.436  1653  2252 E Auth    : 	at android.os.Binder.execTransact(Binder.java:453)
,07-05 14:06:43.476  6809  7322 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,07-05 14:06:43.476  6809  7321 E BooksSync: Soft error
07-05 14:06:43.476  6809  7321 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
07-05 14:06:43.476  6809  7321 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.zza(Unknown)
,07-05 14:06:43.476  6809  7321 E BooksSync: Sync error
07-05 14:06:43.476  6809  7321 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
07-05 14:06:43.476  6809  7321 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.zza(Unknown)
,07-05 14:06:43.486  6809  7321 I BooksSync: Finished books sync
,07-05 14:06:43.496  6809  7329 I GcmRegistrationService: Handling Intent for action: com.google.android.books.GCM_REGISTER
,07-05 14:06:43.496  6809  7329 W GcmRegistrationHandler: Could not find device group in preferences; re-associating.
,07-05 14:06:43.516   767   862 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 277616, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,07-05 14:06:43.526  1653  3945 E Auth    : [GoogleAccountDataServiceImpl] getToken() failed. Status BAD_AUTHENTICATION, Account: <ELLIDED:1197869880>, App: com.google.android.apps.books, Service: oauth2:https://www.googleapis.com/auth/gcm
07-05 14:06:43.526  1653  3945 E Auth    : com.google.android.gms.auth.be.account.b.d: Long live credential not available.
07-05 14:06:43.526  1653  3945 E Auth    : 	at com.google.android.gms.auth.be.account.b.e.a(:com.google.android.gms:105)
07-05 14:06:43.526  1653  3945 E Auth    : 	at com.google.android.gms.auth.be.p.a(:com.google.android.gms:355)
07-05 14:06:43.526  1653  3945 E Auth    : 	at com.google.android.gms.auth.be.o.a(:com.google.android.gms:260)
07-05 14:06:43.526  1653  3945 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.y.a(:com.google.android.gms:197)
07-05 14:06:43.526  1653  3945 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.x.a(:com.google.android.gms:558)
07-05 14:06:43.526  1653  3945 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.x.a(:com.google.android.gms:196)
07-05 14:06:43.526  1653  3945 E Auth    : 	at com.google.android.gms.auth.o.a(:com.google.android.gms:276)
07-05 14:06:43.526  1653  3945 E Auth    : 	at com.google.android.gms.auth.o.a(:com.google.android.gms:196)
07-05 14:06:43.526  1653  3945 E Auth    : 	at com.google.android.b.b.onTransact(:com.google.android.gms:137)
07-05 14:06:43.526  1653  3945 E Auth    : 	at android.os.Binder.execTransact(Binder.java:453)
,07-05 14:06:43.536   767   862 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/sync/pending.xml.bak
,07-05 14:06:43.576  6809  7329 W BooksGcmUtils: Recoverable exception while getting auth token: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
,07-05 14:06:43.576  6809  7329 E GcmRegistrationHandler: Failed to register token for device group
07-05 14:06:43.576  6809  7329 E GcmRegistrationHandler: com.google.android.apps.books.gcm.GcmRegistrationHandler$GcmRequestException: Failed to update GCM device group: null auth token.
07-05 14:06:43.576  6809  7329 E GcmRegistrationHandler: 	at com.google.android.apps.books.gcm.GcmRegistrationHandler.addOrRemoveInstanceIdTokenForAccount(GcmRegistrationHandler.java:275)
07-05 14:06:43.576  6809  7329 E GcmRegistrationHandler: 	at com.google.android.apps.books.gcm.GcmRegistrationHandler.registerTokenForDeviceGroup(GcmRegistrationHandler.java:199)
07-05 14:06:43.576  6809  7329 E GcmRegistrationHandler: 	at com.google.android.apps.books.gcm.GcmRegistrationHandler.registerForDeviceGroup(GcmRegistrationHandler.java:126)
07-05 14:06:43.576  6809  7329 E GcmRegistrationHandler: 	at com.google.android.apps.books.gcm.GcmRegistrationIntentService.handleActionRegister(GcmRegistrationIntentService.java:135)
07-05 14:06:43.576  6809  7329 E GcmRegistrationHandler: 	at com.google.android.apps.books.gcm.GcmRegistrationIntentService.onHandleIntent(GcmRegistrationIntentService.java:94)
07-05 14:06:43.576  6809  7329 E GcmRegistrationHandler: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
07-05 14:06:43.576  6809  7329 E GcmRegistrationHandler: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-05 14:06:43.576  6809  7329 E GcmRegistrationHandler: 	at android.os.Looper.loop(Looper.java:158)
07-05 14:06:43.576  6809  7329 E GcmRegistrationHandler: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,07-05 14:06:43.596  3277  3292 W ResourcesManager: getTopLevelResources: /system/app/PlusOne/PlusOne.apk / 1.0 running in com.android.contacts rsrc of package null
07-05 14:06:43.606  3277  3292 W ResourcesManager: getTopLevelResources: /system/app/PlusOne/PlusOne.apk / 1.0 running in com.android.contacts rsrc of package null
07-05 14:06:43.606  3277  3292 W ResourcesManager: getTopLevelResources: /system/app/PlusOne/PlusOne.apk / 1.0 running in com.android.contacts rsrc of package null
07-05 14:06:43.606  3277  3292 W ResourcesManager: getTopLevelResources: /system/app/PlusOne/PlusOne.apk / 1.0 running in com.android.contacts rsrc of package null
07-05 14:06:43.606   767  1590 D SecContentProvider2: query(), uri = 11 selection = getMyKnoxAdmin
,07-05 14:06:43.766   767   778 I art     : Background partial concurrent mark sweep GC freed 56339(3MB) AllocSpace objects, 56(1120KB) LOS objects, 27% free, 41MB/57MB, paused 2.094ms total 155.610ms
,07-05 14:06:45.926   767  3520 D SSRM:n  : SIOP:: AP = 310, PST = 319, CUR = 300, LCD = 0
,07-05 14:06:53.046   767  1409 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 14:06:53.056   767  1409 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 306, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,07-05 14:06:53.056   767  1409 D BatteryService: online:4, current avg:300, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
,07-05 14:06:53.056   767   767 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 14:06:53.076   767   767 I MotionRecognitionService: Plugged
,07-05 14:06:53.076   767   767 D MotionRecognitionService:   cableConnection= 1
,07-05 14:06:53.076   767   767 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,07-05 14:06:53.076   767   767 D MotionRecognitionService: skip setTransmitPower. 
,07-05 14:06:53.086   767  1409 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 33ms
,07-05 14:06:53.086   767  1409 D BatteryService: stay LED for fully charged
,07-05 14:06:53.096  1380  1380 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 14:06:53.096  1380  1380 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
07-05 14:06:53.096  1380  1380 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 14:06:53.106  2328  2328 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 14:06:53.106  2328  2834 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-05 14:06:53.116  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:06:53.116  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:06:53.126  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:06:54.446   304  1195 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
07-05 14:06:54.446   304  1195 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
07-05 14:06:54.446   304  1195 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,07-05 14:06:55.986   767  3520 D SSRM:n  : SIOP:: AP = 310, PST = 316, CUR = 300, LCD = 0
,07-05 14:06:56.816   767  3539 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-05 14:06:59.986   767  1237 V AlarmManager: Expired Alarm result :8
,07-05 14:07:03.136   767  1767 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 14:07:03.136   767  1767 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 306, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,07-05 14:07:03.136   767  1767 D BatteryService: online:4, current avg:300, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
,07-05 14:07:03.146   767   767 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 14:07:03.156   767   767 I MotionRecognitionService: Plugged
,07-05 14:07:03.156   767   767 D MotionRecognitionService:   cableConnection= 1
,07-05 14:07:03.166   767   767 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,07-05 14:07:03.166   767   767 D MotionRecognitionService: skip setTransmitPower. 
,07-05 14:07:03.166   767  1767 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 31ms
,07-05 14:07:03.166   767  1767 D BatteryService: stay LED for fully charged
,07-05 14:07:03.186  1380  1380 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 14:07:03.186  1380  1380 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,07-05 14:07:03.196  1380  1380 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 14:07:03.206  2328  2328 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 14:07:03.206  2328  2834 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-05 14:07:03.216  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:07:03.216  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 14:07:03.216  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:07:06.056   767  3520 D SSRM:n  : SIOP:: AP = 310, PST = 314, CUR = 300, LCD = 0
,07-05 14:07:06.476   767  1604 E Watchdog: !@Sync 9 [07-05 14:07:06.487]
,07-05 14:07:11.536   304  1195 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
07-05 14:07:11.536   304  1195 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
07-05 14:07:11.536   304  1195 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,07-05 14:07:13.216   767  4119 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 14:07:13.226   767  4119 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 306, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,07-05 14:07:13.226   767  4119 D BatteryService: online:4, current avg:300, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
,07-05 14:07:13.226   767   767 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 14:07:13.246   767   767 I MotionRecognitionService: Plugged
,07-05 14:07:13.246   767   767 D MotionRecognitionService:   cableConnection= 1
,07-05 14:07:13.246   767   767 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,07-05 14:07:13.246   767  4119 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 25ms
,07-05 14:07:13.246   767   767 D MotionRecognitionService: skip setTransmitPower. 
,07-05 14:07:13.256   767  4119 D BatteryService: stay LED for fully charged
,07-05 14:07:13.266  1380  1380 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 14:07:13.266  1380  1380 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,07-05 14:07:13.266  1380  1380 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 14:07:13.296  2328  2328 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 14:07:13.296  2328  2834 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-05 14:07:13.296  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:07:13.296  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:07:13.306  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:07:14.896  1653  3264 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,07-05 14:07:16.116   767  3520 D SSRM:n  : SIOP:: AP = 310, PST = 313, CUR = 300, LCD = 0
,07-05 14:07:16.816   767  3539 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-05 14:07:21.176   767  1231 D TimaService: TIMA: TimaService scheduler is intialized. 
,07-05 14:07:21.186   767  1230 D TimaService: TimaServiceHandler.handleMessage what =1
,07-05 14:07:21.186   767  1231 D TimaService: TIMA: checkEvent, operation: 50000 subject: 10000
,07-05 14:07:21.206   767  1231 I TLC_TIMA_PKM_initialize: initializing...
,07-05 14:07:21.206   767  1231 I TLC_TIMA_PKM_initialize: root = /firmware/image, root_strlen = 15
,07-05 14:07:21.206   767  1231 I TLC_TIMA_PKM_initialize: process = tima_pkm, process_strlen = 8
,07-05 14:07:21.216   767  1231 I TZ: qc_tlc_communication: root = /firmware/image, root_len = 15
,07-05 14:07:21.216   767  1231 I TZ: qc_tlc_communication: process = tima_pkm, process_strlen = 8
,07-05 14:07:21.216   767  1231 I TZ: qc_tlc_communication: aligned max_sendmsg_size = 262208 = 0x40040
,07-05 14:07:21.216   767  1231 I TZ: qc_tlc_communication: aligned max_recvmsg_size = 262208 = 0x40040
,07-05 14:07:21.216   767  1231 I TZ: qc_tlc_communication: max_message_size = 524416 = 0x80080
,07-05 14:07:21.226   767  1231 D QSEECOMAPI: : QSEECom_get_handle sb_length = 0x80080
,07-05 14:07:21.226   767  1231 D QSEECOMAPI: : App is not loaded in QSEE
,07-05 14:07:21.286   767  1231 D QSEECOMAPI: : Loaded image: APP id = 3
,07-05 14:07:21.306   767  1231 I TZ: qc_tlc_communication: TIMA: path = /firmware/image, fname = tima_pkm, tzapp is loaded
,07-05 14:07:21.316   767  1231 I TLC_TIMA_PKM_initialize: Trustlet response is completed
,07-05 14:07:23.316   767  1679 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 14:07:23.316   767  1679 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4381, temperature: 305, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,07-05 14:07:23.326   767  1679 D BatteryService: online:4, current avg:300, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
,07-05 14:07:23.326   767   767 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 14:07:23.336   767   767 I MotionRecognitionService: Plugged
,07-05 14:07:23.346   767   767 D MotionRecognitionService:   cableConnection= 1
,07-05 14:07:23.346   767   767 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
07-05 14:07:23.346   767   767 D MotionRecognitionService: skip setTransmitPower. 
,07-05 14:07:23.346   767  1679 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 26ms
07-05 14:07:23.346   767  1679 D BatteryService: stay LED for fully charged
,07-05 14:07:23.346  1380  1380 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 14:07:23.346  1380  1380 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
07-05 14:07:23.346  1380  1380 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 14:07:23.366  2328  2328 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 14:07:23.366  2328  2834 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-05 14:07:23.376  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:07:23.376  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:07:23.376  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:07:24.606   767  1231 I TLC_TIMA_PKM_measure_kernel: TIMA: response_id = 3
,07-05 14:07:24.606   767  1231 I TLC_TIMA_PKM_measure_kernel: TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,07-05 14:07:24.616   767  1231 D TimaService: TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,07-05 14:07:24.616   767  1231 D TimaService: TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,07-05 14:07:26.176   767  3520 D SSRM:n  : SIOP:: AP = 310, PST = 312, CUR = 300, LCD = 0
,07-05 14:07:36.226   767  3520 D SSRM:n  : SIOP:: AP = 310, PST = 311, CUR = 300, LCD = 0
,07-05 14:07:36.476   767  1604 E Watchdog: !@Sync 10 [07-05 14:07:36.491]
,07-05 14:07:36.826   767  3539 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-05 14:07:37.376  1664  1768 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,07-05 14:07:37.436   767  1237 V AlarmManager: Expired Alarm result :4
,07-05 14:07:37.496  1380  1380 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
,07-05 14:07:37.496  1380  1380 I PERF    : received broadcast android.intent.action.TIME_TICK
07-05 14:07:37.496  1380  1380 D KeyguardUpdateMonitor: handleTimeUpdate
,07-05 14:07:37.516   767  4844 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 14:07:37.516   767  4844 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 305, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,07-05 14:07:37.516   767  4844 D BatteryService: online:4, current avg:300, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
07-05 14:07:37.516   767  4844 D BatteryService: stay LED for fully charged
,07-05 14:07:37.526  1380  1380 D SecKeyguardClockView: onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,07-05 14:07:37.536  1380  1380 D SecKeyguardClockView: HomeTimezone(): 1
,07-05 14:07:37.546  1556  1556 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec
07-05 14:07:37.546  1556  1556 I wpa_supplicant: P2P: Current p2p state = IDLE
,07-05 14:07:37.556  1556  1556 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,07-05 14:07:37.566  1380  1380 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-05 14:07:37.566  1380  1380 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-05 14:07:37.566  1380  1380 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-05 14:07:37.566  1380  1380 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-05 14:07:37.586   767   767 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{61efbf0 u0 null qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{a770b0f 1990:com.google.android.gms/u0a12}
,07-05 14:07:37.586  1380  1380 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-05 14:07:37.596  1380  1380 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-05 14:07:37.596  1380  1380 D SecKeyguardStatusUtils: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-05 14:07:37.626   767   767 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 14:07:37.636   767   767 I MotionRecognitionService: Plugged
07-05 14:07:37.636   767   767 D MotionRecognitionService:   cableConnection= 1
07-05 14:07:37.636   767   767 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
07-05 14:07:37.636   767   767 D MotionRecognitionService: skip setTransmitPower. 
,07-05 14:07:37.636  1380  1380 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
07-05 14:07:37.636  1380  1380 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,07-05 14:07:37.636  1380  1380 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 14:07:37.646  2328  2328 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
07-05 14:07:37.646  2328  2834 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-05 14:07:37.656  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:07:37.656  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 14:07:37.656  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:07:37.686  1990  7363 I EventLogService: Aggregate from 1467718603623 (log), 1467718603623 (data)
,07-05 14:07:37.736  1380  1380 D SecKeyguardStatusUtils: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-05 14:07:38.036   767   866 I ActivityManager: Start proc 7371:com.samsung.android.sm/1000 for broadcast-3 com.samsung.android.sm/.common.SmartManagerReceiver
,07-05 14:07:38.046  7371  7371 E Zygote  : v2
,07-05 14:07:38.056  7371  7371 I libpersona: KNOX_SDCARD checking this for 1000
07-05 14:07:38.056  7371  7371 I libpersona: KNOX_SDCARD not a persona
,07-05 14:07:38.056  7371  7371 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
,07-05 14:07:38.066  7371  7371 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,07-05 14:07:38.066  7371  7371 E Zygote  : accessInfo : 0
,07-05 14:07:38.126  7371  7371 D TimaKeyStoreProvider: TimaSignature is unavailable
07-05 14:07:38.126  7371  7371 D ActivityThread: Added TimaKeyStore provider
,07-05 14:07:38.146   767  1764 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{bd81f25 u0 android.intent.action.DROPBOX_ENTRY_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{20b8fa 7371:com.samsung.android.sm/1000}
,07-05 14:07:38.156  7371  7371 W ResourcesManager: getTopLevelResources: /system/priv-app/SmartManager_v3/SmartManager_v3.apk / 1.0 running in com.samsung.android.sm rsrc of package null
,07-05 14:07:38.236   767  1767 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{1a71eab u0 android.intent.action.DROPBOX_ENTRY_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{20b8fa 7371:com.samsung.android.sm/1000}
,07-05 14:07:38.256   767  1591 I ActivityManager: Killing 5604:com.wssyncmldm/1000 (adj 15): DHA:empty #37
,07-05 14:07:38.286   767  4844 D ActivityManager: isAutoRunBlockedApp:: com.wssyncmldm, Auto Run ON
,07-05 14:07:41.436   304  1196 D Netd    : Iface wlan0 link up
,07-05 14:07:41.436  1556  1556 I wpa_supplicant: nl80211: Received scan results (16 BSSes)
,07-05 14:07:41.446  1556  1556 I wpa_supplicant: scan_only_handler, so autoscan_notify() !!!
,07-05 14:07:41.466   767   871 D Tethering: interfaceLinkStateChanged wlan0, true
,07-05 14:07:41.466   767   871 D Tethering: interfaceStatusChanged wlan0, true
,07-05 14:07:41.476   767  1323 D WifiP2pService: InactiveState{ what=147461 }
,07-05 14:07:41.476   767  1323 D WifiP2pService: P2pEnabledState{ what=147461 }
,07-05 14:07:41.476   767  1323 D WifiP2pService: DefaultState{ what=147461 }
,07-05 14:07:41.516   767   866 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{2c25908 u-1 android.net.wifi.SCAN_RESULTS qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{9a0eaf1 1380:com.android.systemui/u0a59}
,07-05 14:07:43.126   304  1195 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
07-05 14:07:43.126   304  1195 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
07-05 14:07:43.126   304  1195 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,07-05 14:07:46.306   767  3520 D SSRM:n  : SIOP:: AP = 310, PST = 310, CUR = 300, LCD = 0
,07-05 14:07:47.596   767  1679 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 14:07:47.596   767  1679 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 305, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,07-05 14:07:47.596   767  1679 D BatteryService: online:4, current avg:300, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
,07-05 14:07:47.606   767   767 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 14:07:47.616   767   767 I MotionRecognitionService: Plugged
,07-05 14:07:47.616   767   767 D MotionRecognitionService:   cableConnection= 1
,07-05 14:07:47.626   767   767 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,07-05 14:07:47.626   767   767 D MotionRecognitionService: skip setTransmitPower. 
,07-05 14:07:47.626   767  1679 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 28ms
,07-05 14:07:47.626   767  1679 D BatteryService: stay LED for fully charged
,07-05 14:07:47.626  1380  1380 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 14:07:47.626  1380  1380 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
07-05 14:07:47.626  1380  1380 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 14:07:47.646  2328  2328 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 14:07:47.646  2328  2834 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-05 14:07:47.656  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:07:47.656  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:07:47.656  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:07:56.366   767  3520 D SSRM:n  : SIOP:: AP = 310, PST = 310, CUR = 300, LCD = 0
,07-05 14:07:56.826   767  3539 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-05 14:07:57.666   767  4119 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 14:07:59.986   767  1237 V AlarmManager: Expired Alarm result :8
,07-05 14:08:06.426   767  3520 D SSRM:n  : SIOP:: AP = 300, PST = 309, CUR = 300, LCD = 0
,07-05 14:08:06.486   767  1604 E Watchdog: !@Sync 11 [07-05 14:08:06.496]
,07-05 14:08:07.756   767  1811 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 14:08:10.856   304  1195 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
07-05 14:08:10.856   304  1195 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
07-05 14:08:10.856   304  1195 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,07-05 14:08:13.246  1653  1653 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-05 14:08:13.276  1653  1653 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-05 14:08:13.276  1653  1653 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-05 14:08:13.326  1653  3945 E Auth    : [GoogleAccountDataServiceImpl] getToken() failed. Status BAD_AUTHENTICATION, Account: <ELLIDED:1197869880>, App: com.android.vending, Service: androidmarket
07-05 14:08:13.326  1653  3945 E Auth    : com.google.android.gms.auth.be.account.b.d: Long live credential not available.
07-05 14:08:13.326  1653  3945 E Auth    : 	at com.google.android.gms.auth.be.account.b.e.a(:com.google.android.gms:105)
07-05 14:08:13.326  1653  3945 E Auth    : 	at com.google.android.gms.auth.be.p.a(:com.google.android.gms:355)
07-05 14:08:13.326  1653  3945 E Auth    : 	at com.google.android.gms.auth.be.o.a(:com.google.android.gms:260)
07-05 14:08:13.326  1653  3945 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.y.a(:com.google.android.gms:197)
07-05 14:08:13.326  1653  3945 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.x.a(:com.google.android.gms:558)
07-05 14:08:13.326  1653  3945 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.x.a(:com.google.android.gms:196)
07-05 14:08:13.326  1653  3945 E Auth    : 	,at com.google.android.gms.auth.o.a(:com.google.android.gms:276)
07-05 14:08:13.326  1653  3945 E Auth    : 	at com.google.android.gms.auth.o.a(:com.google.android.gms:196)
07-05 14:08:13.326  1653  3945 E Auth    : 	at com.google.android.gms.auth.t.a(:com.google.android.gms:498)
07-05 14:08:13.326  1653  3945 E Auth    : 	at com.google.android.gms.auth.s.a(:com.google.android.gms:908)
07-05 14:08:13.326  1653  3945 E Auth    : 	at com.google.android.gms.auth.s.e(:com.google.android.gms:528)
07-05 14:08:13.326  1653  3945 E Auth    : 	at com.google.android.gms.auth.q.f(:com.google.android.gms:315)
07-05 14:08:13.326  1653  3945 E Auth    : 	at com.google.android.gms.auth.q.b(:com.google.android.gms:195)
07-05 14:08:13.326  1653  3945 E Auth    : 	at com.google.android.gms.auth.be.m.getAuthToken(:com.google.android.gms:195)
07-05 14:08:13.326  1653  3945 E Auth    : 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
07-05 14:08:13.326  1653  3945 E Auth    : 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
07-05 14:08:13.326  1653  3945 E Auth    : 	at android.os.Binder.execTransact(Binder.java:453)
,07-05 14:08:13.346  1653  3945 W GLSActivity: com.google.android.gms.auth.am: User intervention required. Notification has been pushed.
07-05 14:08:13.346  1653  3945 W GLSActivity: 	at com.google.android.gms.auth.q.f(:com.google.android.gms:330)
07-05 14:08:13.346  1653  3945 W GLSActivity: 	at com.google.android.gms.auth.q.b(:com.google.android.gms:195)
07-05 14:08:13.346  1653  3945 W GLSActivity: 	at com.google.android.gms.auth.be.m.getAuthToken(:com.google.android.gms:195)
07-05 14:08:13.346  1653  3945 W GLSActivity: 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
07-05 14:08:13.346  1653  3945 W GLSActivity: 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
07-05 14:08:13.346  1653  3945 W GLSActivity: 	at android.os.Binder.execTransact(Binder.java:453)
,07-05 14:08:13.346  5788  5825 E PlayEventLogger: Failed to get auth token: User intervention required. Notification has been pushed.
07-05 14:08:13.346  5788  5825 E PlayEventLogger: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
07-05 14:08:13.346  5788  5825 E PlayEventLogger: 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2153)
07-05 14:08:13.346  5788  5825 E PlayEventLogger: 	at android.accounts.AccountManager.access$500(AccountManager.java:149)
07-05 14:08:13.346  5788  5825 E PlayEventLogger: 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1996)
07-05 14:08:13.346  5788  5825 E PlayEventLogger: 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
07-05 14:08:13.346  5788  5825 E PlayEventLogger: 	at android.os.Binder.execTransact(Binder.java:453)
,07-05 14:08:13.396  5788  5825 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,07-05 14:08:13.396  5788  5825 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,07-05 14:08:13.396   304  1199 D EnterpriseController: netId is 0
07-05 14:08:13.396   304  1199 D Netd    : getNetworkForDns: using netid 502 for uid 10030
,07-05 14:08:13.406   304  1195 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
07-05 14:08:13.406   304  1195 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
07-05 14:08:13.406   304  1195 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,07-05 14:08:16.486   767  3520 D SSRM:n  : SIOP:: AP = 310, PST = 309, CUR = 300, LCD = 0
,07-05 14:08:16.826   767  3539 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-05 14:08:17.836   767  1767 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 14:08:17.846   767  1767 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 304, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,07-05 14:08:17.846   767  1767 D BatteryService: online:4, current avg:300, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
,07-05 14:08:17.846   767   767 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 14:08:17.856   767   767 I MotionRecognitionService: Plugged
,07-05 14:08:17.866   767   767 D MotionRecognitionService:   cableConnection= 1
,07-05 14:08:17.866   767   767 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,07-05 14:08:17.866   767   767 D MotionRecognitionService: skip setTransmitPower. 
,07-05 14:08:17.876   767  1767 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 31ms
,07-05 14:08:17.876   767  1767 D BatteryService: stay LED for fully charged
,07-05 14:08:17.876  1380  1380 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 14:08:17.876  1380  1380 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
07-05 14:08:17.876  1380  1380 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 14:08:17.896  2328  2328 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 14:08:17.896  2328  2834 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-05 14:08:17.906  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:08:17.906  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 14:08:17.906  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:08:26.546   767  3520 D SSRM:n  : SIOP:: AP = 300, PST = 308, CUR = 300, LCD = 0
,07-05 14:08:27.926   767  1767 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 14:08:27.926   767  1767 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 304, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,07-05 14:08:27.926   767  1767 D BatteryService: online:4, current avg:300, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
,07-05 14:08:27.936   767   767 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 14:08:27.946   767   767 I MotionRecognitionService: Plugged
,07-05 14:08:27.946   767   767 D MotionRecognitionService:   cableConnection= 1
,07-05 14:08:27.946   767   767 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
07-05 14:08:27.946   767   767 D MotionRecognitionService: skip setTransmitPower. 
,07-05 14:08:27.956   767  1767 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 31ms
,07-05 14:08:27.956   767  1767 D BatteryService: stay LED for fully charged
,07-05 14:08:27.976  1380  1380 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 14:08:27.976  1380  1380 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
07-05 14:08:27.976  1380  1380 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 14:08:27.986  2328  2328 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 14:08:27.986  2328  2834 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-05 14:08:27.996  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:08:27.996  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 14:08:27.996  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:08:28.696   304  1195 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
07-05 14:08:28.696   304  1195 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
07-05 14:08:28.696   304  1195 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,07-05 14:08:36.486   767  1604 E Watchdog: !@Sync 12 [07-05 14:08:36.500]
,07-05 14:08:36.606   767  3520 D SSRM:n  : SIOP:: AP = 300, PST = 307, CUR = 300, LCD = 0
,07-05 14:08:36.836   767  3539 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-05 14:08:37.386  1664  1768 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,07-05 14:08:38.016   767  1748 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 14:08:46.666   767  3520 D SSRM:n  : SIOP:: AP = 300, PST = 306, CUR = 300, LCD = 0
,07-05 14:08:48.096   767  1764 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 14:08:56.726   767  3520 D SSRM:n  : SIOP:: AP = 300, PST = 305, CUR = 300, LCD = 0
,07-05 14:08:56.836   767  3539 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-05 14:08:57.426   304  1195 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
07-05 14:08:57.426   304  1195 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
07-05 14:08:57.426   304  1195 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,07-05 14:08:58.186   767  1590 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 14:08:58.186   767  1590 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 304, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,07-05 14:08:58.196   767  1590 D BatteryService: online:4, current avg:300, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
,07-05 14:08:58.196   767   767 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 14:08:58.206   767   767 I MotionRecognitionService: Plugged
,07-05 14:08:58.206   767   767 D MotionRecognitionService:   cableConnection= 1
,07-05 14:08:58.216   767   767 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,07-05 14:08:58.216   767   767 D MotionRecognitionService: skip setTransmitPower. 
,07-05 14:08:58.216   767  1590 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 29ms
,07-05 14:08:58.226   767  1590 D BatteryService: stay LED for fully charged
,07-05 14:08:58.226  1380  1380 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 14:08:58.226  1380  1380 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
07-05 14:08:58.226  1380  1380 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 14:08:58.246  2328  2328 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 14:08:58.246  2328  2834 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-05 14:08:58.256  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:08:58.256  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 14:08:58.256  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:09:06.496   767  1604 E Watchdog: !@Sync 13 [07-05 14:09:06.506]
,07-05 14:09:06.786   767  3520 D SSRM:n  : SIOP:: AP = 300, PST = 304, CUR = 300, LCD = 0
,07-05 14:09:08.276   767  4119 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 14:09:12.456   304  1195 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
07-05 14:09:12.456   304  1195 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
07-05 14:09:12.456   304  1195 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,07-05 14:09:16.836   767  3539 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-05 14:09:16.856   767  3520 D SSRM:n  : SIOP:: AP = 300, PST = 303, CUR = 300, LCD = 0
,07-05 14:09:18.356   767  1811 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 14:09:18.366   767  1811 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 304, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,07-05 14:09:18.366   767  1811 D BatteryService: online:4, current avg:300, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
,07-05 14:09:18.366   767   767 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 14:09:18.386   767   767 I MotionRecognitionService: Plugged
,07-05 14:09:18.386   767   767 D MotionRecognitionService:   cableConnection= 1
,07-05 14:09:18.386   767   767 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,07-05 14:09:18.396   767   767 D MotionRecognitionService: skip setTransmitPower. 
,07-05 14:09:18.396   767  1811 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 32ms
,07-05 14:09:18.396   767  1811 D BatteryService: stay LED for fully charged
,07-05 14:09:18.416  1380  1380 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 14:09:18.416  1380  1380 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,07-05 14:09:18.426  1380  1380 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 14:09:18.436  2328  2328 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 14:09:18.436  2328  2834 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-05 14:09:18.446  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:09:18.446  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:09:18.446  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:09:26.916   767  3520 D SSRM:n  : SIOP:: AP = 300, PST = 302, CUR = 300, LCD = 0
,07-05 14:09:28.436   767  1466 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 14:09:28.446   767  1466 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 303, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,07-05 14:09:28.446   767  1466 D BatteryService: online:4, current avg:300, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
,07-05 14:09:28.446   767   767 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 14:09:28.466   767   767 I MotionRecognitionService: Plugged
,07-05 14:09:28.476   767  1466 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 30ms
07-05 14:09:28.476   767  1466 D BatteryService: stay LED for fully charged
,07-05 14:09:28.476  1380  1380 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 14:09:28.476  1380  1380 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
07-05 14:09:28.476  1380  1380 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 14:09:28.486   767   767 D MotionRecognitionService:   cableConnection= 1
,07-05 14:09:28.486   767   767 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
07-05 14:09:28.486   767   767 D MotionRecognitionService: skip setTransmitPower. 
,07-05 14:09:28.496  2328  2328 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 14:09:28.496  2328  2834 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-05 14:09:28.496  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:09:28.496  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:09:28.506  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:09:36.496   767  1604 E Watchdog: !@Sync 14 [07-05 14:09:36.510]
,07-05 14:09:36.846   767  3539 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-05 14:09:36.966   767  3520 D SSRM:n  : SIOP:: AP = 300, PST = 301, CUR = 300, LCD = 0
,07-05 14:09:37.396  1664  1768 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,07-05 14:09:37.636  1664  1768 E ContactsProvider_EventLog: Flush buffer to file cnt : 6 size : 1Kb duration : 226ms lastUpdatedAfter : 173991ms
,07-05 14:09:38.556   767   785 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 14:09:38.566   767   785 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 303, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,07-05 14:09:38.566   767   785 D BatteryService: online:4, current avg:300, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
,07-05 14:09:38.566   767   767 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 14:09:38.576   767   767 I MotionRecognitionService: Plugged
,07-05 14:09:38.576   767   767 D MotionRecognitionService:   cableConnection= 1
,07-05 14:09:38.576   767   767 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
07-05 14:09:38.576   767   767 D MotionRecognitionService: skip setTransmitPower. 
,07-05 14:09:38.576  1380  1380 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 14:09:38.576  1380  1380 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
07-05 14:09:38.576  1380  1380 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 14:09:38.586   767   785 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 24ms
,07-05 14:09:38.586   767   785 D BatteryService: stay LED for fully charged
,07-05 14:09:38.596  2328  2328 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 14:09:38.596  2328  2834 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-05 14:09:38.606  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:09:38.606  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 14:09:38.606  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:09:47.026   767  3520 D SSRM:n  : SIOP:: AP = 300, PST = 301, CUR = 300, LCD = 0
,07-05 14:09:56.846   767  3539 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-05 14:09:56.906   304  1195 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
07-05 14:09:56.906   304  1195 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
07-05 14:09:56.906   304  1195 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,07-05 14:09:57.096   767  3520 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 300, LCD = 0
,07-05 14:10:06.506   767  1604 E Watchdog: !@Sync 15 [07-05 14:10:06.516]
,07-05 14:10:07.156   767  3520 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 300, LCD = 0
,07-05 14:10:08.626   767  4844 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 14:10:08.626   767  4844 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4361, temperature: 303, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,07-05 14:10:08.636   767  4844 D BatteryService: online:4, current avg:300, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
,07-05 14:10:08.636   767   767 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 14:10:08.646   767   767 I MotionRecognitionService: Plugged
,07-05 14:10:08.646   767   767 D MotionRecognitionService:   cableConnection= 1
,07-05 14:10:08.656   767   767 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,07-05 14:10:08.656   767   767 D MotionRecognitionService: skip setTransmitPower. 
,07-05 14:10:08.666   767  4844 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 33ms
,07-05 14:10:08.666   767  4844 D BatteryService: stay LED for fully charged
,07-05 14:10:08.676  1380  1380 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 14:10:08.676  1380  1380 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
07-05 14:10:08.676  1380  1380 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 14:10:08.686  2328  2328 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 14:10:08.696  2328  2834 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-05 14:10:08.706  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:10:08.706  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 14:10:08.706  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:10:10.786   366   366 I bootchecker: bootchecker wake up!!
,07-05 14:10:11.976   304  1195 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
07-05 14:10:11.976   304  1195 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
07-05 14:10:11.976   304  1195 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,07-05 14:10:16.856   767  3539 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-05 14:10:17.206   767  3520 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 300, LCD = 0
,07-05 14:10:27.266   767  3520 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 300, LCD = 0
,07-05 14:10:36.506   767  1604 E Watchdog: !@Sync 16 [07-05 14:10:36.520]
,07-05 14:10:36.856   767  3539 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-05 14:10:37.316   767  3520 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 300, LCD = 0
,07-05 14:10:37.696  1664  1768 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,07-05 14:10:47.366   767  3520 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 300, LCD = 0
,07-05 14:10:47.676   767  1237 V AlarmManager: Expired Alarm result :4
,07-05 14:10:47.706  1380  1380 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
,07-05 14:10:47.706  1380  1380 I PERF    : received broadcast android.intent.action.TIME_TICK
,07-05 14:10:47.706  1380  1380 D KeyguardUpdateMonitor: handleTimeUpdate
,07-05 14:10:47.746   767  1590 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 14:10:47.746   767  1590 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4361, temperature: 302, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,07-05 14:10:47.746   767  1590 D BatteryService: online:4, current avg:300, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
07-05 14:10:47.746   767  1590 D BatteryService: stay LED for fully charged
,07-05 14:10:47.746  1380  1380 D SecKeyguardClockView: onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,07-05 14:10:47.766  1380  1380 D SecKeyguardClockView: HomeTimezone(): 1
,07-05 14:10:47.766  1380  1380 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-05 14:10:47.776  1380  1380 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-05 14:10:47.786   767   767 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 14:10:47.796  2328  2328 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 14:10:47.796  2328  2834 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-05 14:10:47.796   767   767 I MotionRecognitionService: Plugged
,07-05 14:10:47.796   767   767 D MotionRecognitionService:   cableConnection= 1
07-05 14:10:47.796  1380  1380 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
07-05 14:10:47.806   767   767 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,07-05 14:10:47.806   767   767 D MotionRecognitionService: skip setTransmitPower. 
,07-05 14:10:47.806  1380  1380 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-05 14:10:47.806  1380  1380 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-05 14:10:47.806  1380  1380 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-05 14:10:47.806  1380  1380 D SecKeyguardStatusUtils: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-05 14:10:47.816  1380  1380 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 14:10:47.816  1380  1380 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,07-05 14:10:47.816  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:10:47.816  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 14:10:47.816  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:10:47.826  1380  1380 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 14:10:47.886  1380  1380 D SecKeyguardStatusUtils: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-05 14:10:47.896  6809  7440 I BooksSync: Starting books sync for 61035162, extras: ade
,07-05 14:10:47.936  1653  1653 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-05 14:10:47.946  1653  1653 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-05 14:10:47.986  1653  1670 E Auth    : [GoogleAccountDataServiceImpl] getToken() failed. Status BAD_AUTHENTICATION, Account: <ELLIDED:1197869880>, App: com.google.android.apps.books, Service: oauth2:https://www.googleapis.com/auth/books
07-05 14:10:47.986  1653  1670 E Auth    : com.google.android.gms.auth.be.account.b.d: Long live credential not available.
07-05 14:10:47.986  1653  1670 E Auth    : 	at com.google.android.gms.auth.be.account.b.e.a(:com.google.android.gms:105)
07-05 14:10:47.986  1653  1670 E Auth    : 	at com.google.android.gms.auth.be.p.a(:com.google.android.gms:355)
07-05 14:10:47.986  1653  1670 E Auth    : 	at com.google.android.gms.auth.be.o.a(:com.google.android.gms:260)
07-05 14:10:47.986  1653  1670 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.y.a(:com.google.android.gms:197)
07-05 14:10:47.986  1653  1670 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.x.a(:com.google.android.gms:558)
07-05 14:10:47.986  1653  1670 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.x.a(:com.google.android.gms:196)
07-05 14:10:47.986  1653  1670 E Auth    : 	at com.google.android.gms.auth.o.a(:com.google.android.gms:276)
07-05 14:10:47.986  1653  1670 E Auth    : 	at com.google.android.gms.auth.o.a(:com.google.android.gms:196)
07-05 14:10:47.986  1653  1670 E Auth    : 	at com.google.android.b.b.onTransact(:com.google.android.gms:137)
07-05 14:10:47.986  1653  1670 E Auth    : 	at android.os.Binder.execTransact(Binder.java:453)
,07-05 14:10:48.056  1653  3945 E Auth    : [GoogleAccountDataServiceImpl] getToken() failed. Status BAD_AUTHENTICATION, Account: <ELLIDED:1197869880>, App: com.google.android.apps.books, Service: oauth2:https://www.googleapis.com/auth/books
07-05 14:10:48.056  1653  3945 E Auth    : com.google.android.gms.auth.be.account.b.d: Long live credential not available.
07-05 14:10:48.056  1653  3945 E Auth    : 	at com.google.android.gms.auth.be.account.b.e.a(:com.google.android.gms:105)
07-05 14:10:48.056  1653  3945 E Auth    : 	at com.google.android.gms.auth.be.p.a(:com.google.android.gms:355)
07-05 14:10:48.056  1653  3945 E Auth    : 	at com.google.android.gms.auth.be.o.a(:com.google.android.gms:260)
07-05 14:10:48.056  1653  3945 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.y.a(:com.google.android.gms:197)
07-05 14:10:48.056  1653  3945 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.x.a(:com.google.android.gms:558)
07-05 14:10:48.056  1653  3945 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.x.a(:com.google.android.gms:196)
07-05 14:10:48.056  1653  3945 E Auth    : 	at com.google.android.gms.auth.o.a(:com.google.android.gms:276)
07-05 14:10:48.056  1653  3945 E Auth    : 	at com.google.android.gms.auth.o.a(:com.google.android.gms:196)
07-05 14:10:48.056  1653  3945 E Auth    : 	at com.google.android.b.b.onTransact(:com.google.android.gms:137)
07-05 14:10:48.056  1653  3945 E Auth    : 	at android.os.Binder.execTransact(Binder.java:453)
,07-05 14:10:48.106  6809  7441 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,07-05 14:10:48.116  6809  7440 E BooksSync: Soft error
07-05 14:10:48.116  6809  7440 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
07-05 14:10:48.116  6809  7440 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.zza(Unknown)
07-05 14:10:48.116  6809  7440 E BooksSync: Sync error
07-05 14:10:48.116  6809  7440 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
07-05 14:10:48.116  6809  7440 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.zza(Unknown)
,07-05 14:10:48.126  6809  7440 I BooksSync: Finished books sync
,07-05 14:10:48.136  6809  7442 I GcmRegistrationService: Handling Intent for action: com.google.android.books.GCM_REGISTER
,07-05 14:10:48.146  6809  7442 W GcmRegistrationHandler: Could not find device group in preferences; re-associating.
,07-05 14:10:48.166   767   862 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 522410, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,07-05 14:10:48.186  1653  1670 E Auth    : [GoogleAccountDataServiceImpl] getToken() failed. Status BAD_AUTHENTICATION, Account: <ELLIDED:1197869880>, App: com.google.android.apps.books, Service: oauth2:https://www.googleapis.com/auth/gcm
07-05 14:10:48.186  1653  1670 E Auth    : com.google.android.gms.auth.be.account.b.d: Long live credential not available.
07-05 14:10:48.186  1653  1670 E Auth    : 	at com.google.android.gms.auth.be.account.b.e.a(:com.google.android.gms:105)
07-05 14:10:48.186  1653  1670 E Auth    : 	at com.google.android.gms.auth.be.p.a(:com.google.android.gms:355)
07-05 14:10:48.186  1653  1670 E Auth    : 	at com.google.android.gms.auth.be.o.a(:com.google.android.gms:260)
07-05 14:10:48.186  1653  1670 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.y.a(:com.google.android.gms:197)
07-05 14:10:48.186  1653  1670 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.x.a(:com.google.android.gms:558)
07-05 14:10:48.186  1653  1670 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.x.a(:com.google.android.gms:196)
07-05 14:10:48.186  1653  1670 E Auth    : 	at com.google.android.gms.auth.o.a(:com.google.android.gms:276)
07-05 14:10:48.186  1653  1670 E Auth    : 	at com.google.android.gms.auth.o.a(:com.google.android.gms:196)
07-05 14:10:48.186  1653  1670 E Auth    : 	at com.google.android.b.b.onTransact(:com.google.android.gms:137)
07-05 14:10:48.186  1653  1670 E Auth    : 	at android.os.Binder.execTransact(Binder.java:453)
,07-05 14:10:48.186   767   862 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/sync/pending.xml.bak
,07-05 14:10:48.226  3277  3292 W ResourcesManager: getTopLevelResources: /system/app/PlusOne/PlusOne.apk / 1.0 running in com.android.contacts rsrc of package null
,07-05 14:10:48.236  6809  7442 W BooksGcmUtils: Recoverable exception while getting auth token: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
,07-05 14:10:48.236  6809  7442 E GcmRegistrationHandler: Failed to register token for device group
07-05 14:10:48.236  6809  7442 E GcmRegistrationHandler: com.google.android.apps.books.gcm.GcmRegistrationHandler$GcmRequestException: Failed to update GCM device group: null auth token.
07-05 14:10:48.236  6809  7442 E GcmRegistrationHandler: 	at com.google.android.apps.books.gcm.GcmRegistrationHandler.addOrRemoveInstanceIdTokenForAccount(GcmRegistrationHandler.java:275)
07-05 14:10:48.236  6809  7442 E GcmRegistrationHandler: 	at com.google.android.apps.books.gcm.GcmRegistrationHandler.registerTokenForDeviceGroup(GcmRegistrationHandler.java:199)
07-05 14:10:48.236  6809  7442 E GcmRegistrationHandler: 	at com.google.android.apps.books.gcm.GcmRegistrationHandler.registerForDeviceGroup(GcmRegistrationHandler.java:126)
07-05 14:10:48.236  6809  7442 E GcmRegistrationHandler: 	at com.google.android.apps.books.gcm.GcmRegistrationIntentService.handleActionRegister(GcmRegistrationIntentService.java:135)
07-05 14:10:48.236  6809  7442 E GcmRegistrationHandler: 	at com.google.android.apps.books.gcm.GcmRegistrationIntentService.onHandleIntent(GcmRegistrationIntentService.java:94)
07-05 14:10:48.236  6809  7442 E GcmRegistrationHandler: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
07-05 14:10:48.236  6809  7442 E GcmRegistrationHandler: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-05 14:10:48.236  6809  7442 E GcmRegistrationHandler: 	at android.os.Looper.loop(Looper.java:158)
07-05 14:10:48.236  6809  7442 E GcmRegistrationHandler: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,07-05 14:10:48.236  3277  3292 W ResourcesManager: getTopLevelResources: /system/app/PlusOne/PlusOne.apk / 1.0 running in com.android.contacts rsrc of package null
07-05 14:10:48.236  3277  3292 W ResourcesManager: getTopLevelResources: /system/app/PlusOne/PlusOne.apk / 1.0 running in com.android.contacts rsrc of package null
07-05 14:10:48.236  3277  3292 W ResourcesManager: getTopLevelResources: /system/app/PlusOne/PlusOne.apk / 1.0 running in com.android.contacts rsrc of package null
07-05 14:10:48.246   767  1591 D SecContentProvider2: query(), uri = 11 selection = getMyKnoxAdmin
,07-05 14:10:56.856   767  3539 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-05 14:10:57.446   767  3520 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 300, LCD = 0
,07-05 14:10:59.986   767  1237 V AlarmManager: Expired Alarm result :8
,07-05 14:11:06.516   767  1604 E Watchdog: !@Sync 17 [07-05 14:11:06.524]
,07-05 14:11:07.506   767  3520 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 300, LCD = 0
,07-05 14:11:16.866   767  3539 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-05 14:11:17.556   767  3520 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 300, LCD = 0
,07-05 14:11:17.826   767  1811 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 14:11:17.836   767  1811 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4360, temperature: 301, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,07-05 14:11:17.836   767  1811 D BatteryService: online:4, current avg:300, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
,07-05 14:11:17.836   767   767 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 14:11:17.846   767   767 I MotionRecognitionService: Plugged
,07-05 14:11:17.856   767   767 D MotionRecognitionService:   cableConnection= 1
,07-05 14:11:17.856   767   767 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,07-05 14:11:17.856   767   767 D MotionRecognitionService: skip setTransmitPower. 
,07-05 14:11:17.856   767  1811 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 30ms
,07-05 14:11:17.866   767  1811 D BatteryService: stay LED for fully charged
,07-05 14:11:17.876  1380  1380 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 14:11:17.876  1380  1380 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,07-05 14:11:17.876  1380  1380 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 14:11:17.906  2328  2328 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 14:11:17.906  2328  2834 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-05 14:11:17.906  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:11:17.916  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:11:17.916  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:11:27.606   767  3520 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 300, LCD = 0
,07-05 14:11:36.516   767  1604 E Watchdog: !@Sync 18 [07-05 14:11:36.529]
,07-05 14:11:36.866   767  3539 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-05 14:11:37.666   767  3520 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 300, LCD = 0
,07-05 14:11:37.736  1664  1768 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,07-05 14:11:47.726   767  3520 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 300, LCD = 0
,07-05 14:11:47.896   767  4119 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 14:11:56.876   767  3539 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-05 14:11:57.776   767  3520 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 300, LCD = 0
,07-05 14:12:06.526   767  1604 E Watchdog: !@Sync 19 [07-05 14:12:06.533]
,07-05 14:12:07.836   767  3520 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 300, LCD = 0
,07-05 14:12:13.936   304  1195 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
07-05 14:12:13.936   304  1195 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
07-05 14:12:13.936   304  1195 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,07-05 14:12:16.876   767  3539 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-05 14:12:17.906   767  3520 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 300, LCD = 0
,07-05 14:12:17.966   767  4844 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 14:12:21.166   767  1231 D TimaService: TIMA: TimaService scheduler is intialized. 
,07-05 14:12:21.166   767  1231 D TimaService: TIMA: checkEvent, operation: 50000 subject: 10000
,07-05 14:12:21.166   767  1230 D TimaService: TimaServiceHandler.handleMessage what =1
,07-05 14:12:22.686   767  1231 I TLC_TIMA_PKM_measure_kernel: TIMA: response_id = 3
,07-05 14:12:22.696   767  1231 I TLC_TIMA_PKM_measure_kernel: TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,07-05 14:12:22.706   767  1231 D TimaService: TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,07-05 14:12:22.706   767  1231 D TimaService: TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,07-05 14:12:27.956   767  3520 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 300, LCD = 0
,07-05 14:12:28.976   304  1195 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
07-05 14:12:28.976   304  1195 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
07-05 14:12:28.976   304  1195 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,07-05 14:12:36.536   767  1604 E Watchdog: !@Sync 20 [07-05 14:12:36.543]
,07-05 14:12:36.876   767  3539 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-05 14:12:37.786  1664  1768 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,07-05 14:12:38.016   767  3520 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 300, LCD = 0
,07-05 14:12:40.896   767   862 D NetworkPolicy: isUidForegroundLocked: 10002, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,07-05 14:12:40.896   767   862 D NetworkPolicy: isUidForegroundLocked: 10006, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-05 14:12:40.896   767   862 D NetworkPolicy: isUidForegroundLocked: 10010, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-05 14:12:40.896   767   862 D NetworkPolicy: isUidForegroundLocked: 10012, mScreenOn: false, uidstate: 6, mProxSensorScreenOff: false
07-05 14:12:40.896   767   862 D NetworkPolicy: isUidForegroundLocked: 10013, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-05 14:12:40.896   767   862 D NetworkPolicy: isUidForegroundLocked: 10015, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,07-05 14:12:40.896   767   862 D NetworkPolicy: isUidForegroundLocked: 10016, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-05 14:12:40.896   767   862 D NetworkPolicy: isUidForegroundLocked: 10019, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-05 14:12:40.896   767   862 D NetworkPolicy: isUidForegroundLocked: 10020, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-05 14:12:40.896   767   862 D NetworkPolicy: isUidForegroundLocked: 10022, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,07-05 14:12:40.896   767   862 D NetworkPolicy: isUidForegroundLocked: 10028, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-05 14:12:40.896   767   862 D NetworkPolicy: isUidForegroundLocked: 10030, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-05 14:12:40.896   767   862 D NetworkPolicy: isUidForegroundLocked: 10032, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-05 14:12:40.896   767   862 D NetworkPolicy: isUidForegroundLocked: 10033, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-05 14:12:40.896   767   862 D NetworkPolicy: isUidForegroundLocked: 10034, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,07-05 14:12:40.896   767   862 D NetworkPolicy: isUidForegroundLocked: 10035, mScreenOn: false, uidstate: 10, mProxSensorScreenOff: false
07-05 14:12:40.896   767   862 D NetworkPolicy: isUidForegroundLocked: 10036, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-05 14:12:40.896   767   862 D NetworkPolicy: isUidForegroundLocked: 10038, mScreenOn: false, uidstate: 10, mProxSensorScreenOff: false
07-05 14:12:40.896   767   862 D NetworkPolicy: isUidForegroundLocked: 10040, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,07-05 14:12:40.896   767   862 D NetworkPolicy: isUidForegroundLocked: 10041, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-05 14:12:40.896   767   862 D NetworkPolicy: isUidForegroundLocked: 10042, mScreenOn: false, uidstate: 10, mProxSensorScreenOff: false
07-05 14:12:40.896   767   862 D NetworkPolicy: isUidForegroundLocked: 10044, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-05 14:12:40.896   767   862 D NetworkPolicy: isUidForegroundLocked: 10045, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-05 14:12:40.896   767   862 D NetworkPolicy: isUidForegroundLocked: 10046, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-05 14:12:40.896   767   862 D NetworkPolicy: isUidForegroundLocked: 10047, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-05 14:12:40.896   767   862 D NetworkPolicy: isUidForegroundLocked: 10048, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-05 14:12:40.896   767   862 D NetworkPolicy: isUidForegroundLocked: 10050, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,07-05 14:12:40.906   767   862 D NetworkPolicy: isUidForegroundLocked: 10051, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-05 14:12:40.906   767   862 D NetworkPolicy: isUidForegroundLocked: 10053, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-05 14:12:40.906   767   862 D NetworkPolicy: isUidForegroundLocked: 10054, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-05 14:12:40.906   767   862 D NetworkPolicy: isUidForegroundLocked: 10055, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,07-05 14:12:40.906   767   862 D NetworkPolicy: isUidForegroundLocked: 10056, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-05 14:12:40.906   767   862 D NetworkPolicy: isUidForegroundLocked: 10058, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-05 14:12:40.906   767   862 D NetworkPolicy: isUidForegroundLocked: 10062, mScreenOn: false, uidstate: 3, mProxSensorScreenOff: false
07-05 14:12:40.906   767   862 D NetworkPolicy: isUidForegroundLocked: 10070, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,07-05 14:12:40.906   767   862 D NetworkPolicy: isUidForegroundLocked: 10071, mScreenOn: false, uidstate: 12, mProxSensorScreenOff: false
07-05 14:12:40.906   767   862 D NetworkPolicy: isUidForegroundLocked: 10076, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-05 14:12:40.906   767   862 D NetworkPolicy: isUidForegroundLocked: 10082, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-05 14:12:40.906   767   862 D NetworkPolicy: isUidForegroundLocked: 10084, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,07-05 14:12:40.906   767   862 D NetworkPolicy: isUidForegroundLocked: 10088, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-05 14:12:40.906   767   862 D NetworkPolicy: isUidForegroundLocked: 10091, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-05 14:12:40.906   767   862 D NetworkPolicy: isUidForegroundLocked: 10092, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-05 14:12:40.906   767   862 D NetworkPolicy: isUidForegroundLocked: 10096, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,07-05 14:12:40.906   767   862 D NetworkPolicy: isUidForegroundLocked: 10098, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-05 14:12:40.906   767   862 D NetworkPolicy: isUidForegroundLocked: 10099, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-05 14:12:40.906   767   862 D NetworkPolicy: isUidForegroundLocked: 10101, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-05 14:12:40.906   767   862 D NetworkPolicy: isUidForegroundLocked: 10103, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,07-05 14:12:40.906   767   862 D NetworkPolicy: isUidForegroundLocked: 10105, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-05 14:12:40.906   767   862 D NetworkPolicy: isUidForegroundLocked: 10111, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-05 14:12:40.906   767   862 D NetworkPolicy: isUidForegroundLocked: 10112, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-05 14:12:40.906   767   862 D NetworkPolicy: isUidForegroundLocked: 10113, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,07-05 14:12:40.906   767   862 D NetworkPolicy: isUidForegroundLocked: 10114, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-05 14:12:40.906   767   862 D NetworkPolicy: isUidForegroundLocked: 10115, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-05 14:12:40.906   767   862 D NetworkPolicy: isUidForegroundLocked: 10116, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-05 14:12:40.906   767   862 D NetworkPolicy: isUidForegroundLocked: 10117, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,07-05 14:12:40.906   767   862 D NetworkPolicy: isUidForegroundLocked: 10119, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-05 14:12:40.906   767   862 D NetworkPolicy: isUidForegroundLocked: 10122, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-05 14:12:40.906   767   862 D NetworkPolicy: isUidForegroundLocked: 10124, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-05 14:12:40.906   767   862 D NetworkPolicy: isUidForegroundLocked: 10126, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,07-05 14:12:40.916   767   862 D NetworkPolicy: isUidForegroundLocked: 10127, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-05 14:12:40.916   767   862 D NetworkPolicy: isUidForegroundLocked: 10128, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-05 14:12:40.916   767   862 D NetworkPolicy: isUidForegroundLocked: 10129, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,07-05 14:12:40.916   767   862 D NetworkPolicy: isUidForegroundLocked: 10135, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-05 14:12:40.916   767   862 D NetworkPolicy: isUidForegroundLocked: 10136, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-05 14:12:40.916   767   862 D NetworkPolicy: isUidForegroundLocked: 10138, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-05 14:12:40.916   767   862 D NetworkPolicy: isUidForegroundLocked: 10140, mScreenOn: false, uidstate: 7, mProxSensorScreenOff: false
07-05 14:12:40.916   767   862 D NetworkPolicy: isUidForegroundLocked: 10141, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,07-05 14:12:40.916   767   862 D NetworkPolicy: isUidForegroundLocked: 10143, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-05 14:12:40.916   767   862 D NetworkPolicy: isUidForegroundLocked: 10147, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-05 14:12:40.916   767   862 D NetworkPolicy: isUidForegroundLocked: 10150, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-05 14:12:40.916   767   862 D NetworkPolicy: isUidForegroundLocked: 10152, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,07-05 14:12:40.916   767   862 D NetworkPolicy: isUidForegroundLocked: 10153, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-05 14:12:40.916   767   862 D NetworkPolicy: isUidForegroundLocked: 10154, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-05 14:12:40.916   767   862 D NetworkPolicy: isUidForegroundLocked: 10162, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-05 14:12:40.916   767   862 D NetworkPolicy: isUidForegroundLocked: 10163, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,07-05 14:12:40.916   767   862 D NetworkPolicy: isUidForegroundLocked: 10164, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-05 14:12:40.916   767   862 D NetworkPolicy: isUidForegroundLocked: 10166, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-05 14:12:40.916   767   862 D NetworkPolicy: isUidForegroundLocked: 10167, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-05 14:12:40.916   767   862 D NetworkPolicy: isUidForegroundLocked: 10171, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-05 14:12:40.916   767   862 D NetworkPolicy: isUidForegroundLocked: 10173, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-05 14:12:40.916   767   862 D NetworkPolicy: isUidForegroundLocked: 10175, mScreenOn: false, uidstate: 0, mProxSensorScreenOff: false
07-05 14:12:40.916   767   862 D NetworkPolicy: isUidForegroundLocked: 10177, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-05 14:12:40.916   767   862 D NetworkPolicy: isUidForegroundLocked: 10178, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-05 14:12:40.916   767   862 D NetworkPolicy: isUidForegroundLocked: 10179, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-05 14:12:40.916   767   862 D NetworkPolicy: isUidForegroundLocked: 10181, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-05 14:12:40.916   767   862 D NetworkPolicy: isUidForegroundLocked: 10182, mScreenOn: false, uidstate: 10, mProxSensorScreenOff: false
07-05 14:12:40.916   767   862 D NetworkPolicy: isUidForegroundLocked: 10185, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-05 14:12:40.916   767   862 D NetworkPolicy: isUidForegroundLocked: 10189, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-05 14:12:40.916   767   862 D NetworkPolicy: isUidForegroundLocked: 10195, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-05 14:12:40.926   767   862 D NetworkPolicy: isUidForegroundLocked: 10196, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-05 14:12:40.926   767   862 D NetworkPolicy: isUidForegroundLocked: 10199, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-05 14:12:40.926   767   862 D NetworkPolicy: isUidForegroundLocked: 10202, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-05 14:12:40.926   767   862 D NetworkPolicy: isUidForegroundLocked: 10207, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-05 14:12:40.926   767   862 D NetworkPolicy: isUidForegroundLocked: 10208, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-05 14:12:40.926   767   862 D NetworkPolicy: isUidForegroundLocked: 10209, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-05 14:12:40.926   767   862 D NetworkPolicy: isUidForegroundLocked: 10211, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-05 14:12:40.926   767   862 D NetworkPolicy: isUidForegroundLocked: 10212, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-05 14:12:40.926   767   862 D NetworkPolicy: isUidForegroundLocked: 10213, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-05 14:12:40.926   767   862 D NetworkPolicy: isUidForegroundLocked: 10221, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,07-05 14:12:41.026   767   907 I ActivityManager: setMaxStartingBackgroundTimer onfinish
,07-05 14:12:41.026   767   907 I ActivityManager: MaxStartingBackground is set. ( current : 8 )
,07-05 14:12:48.046   767  1748 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 14:12:48.046   767  1748 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4360, temperature: 300, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,07-05 14:12:48.056   767  1748 D BatteryService: online:4, current avg:300, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
,07-05 14:12:48.056   767   767 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 14:12:48.076   767   767 I MotionRecognitionService: Plugged
,07-05 14:12:48.076   767   767 D MotionRecognitionService:   cableConnection= 1
,07-05 14:12:48.076   767   767 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,07-05 14:12:48.076   767   767 D MotionRecognitionService: skip setTransmitPower. 
,07-05 14:12:48.086   767  1748 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 41ms
,07-05 14:12:48.096   767  1748 D BatteryService: stay LED for fully charged
,07-05 14:12:48.106  1380  1380 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 14:12:48.106  1380  1380 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
07-05 14:12:48.106  1380  1380 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 14:12:48.126  2328  2328 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 14:12:48.126  2328  2834 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-05 14:12:48.126   767  3520 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 300, LCD = 0
,07-05 14:12:48.126  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:12:48.126  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 14:12:48.126  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:12:56.886   767  3539 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-05 14:12:58.186   767  3520 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 300, LCD = 0
,07-05 14:13:06.536   767  1604 E Watchdog: !@Sync 21 [07-05 14:13:06.547]
,07-05 14:13:08.236   767  3520 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 300, LCD = 0
,07-05 14:13:13.676   304  1195 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
07-05 14:13:13.676   304  1195 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
07-05 14:13:13.676   304  1195 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,07-05 14:13:18.106   767  4844 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 14:13:18.116   767  4844 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4358, temperature: 300, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,07-05 14:13:18.116   767  4844 D BatteryService: online:4, current avg:300, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
,07-05 14:13:18.116   767   767 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 14:13:18.136   767   767 I MotionRecognitionService: Plugged
,07-05 14:13:18.136   767   767 D MotionRecognitionService:   cableConnection= 1
,07-05 14:13:18.146   767   767 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,07-05 14:13:18.146   767   767 D MotionRecognitionService: skip setTransmitPower. 
,07-05 14:13:18.146   767  4844 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 35ms
,07-05 14:13:18.146   767  4844 D BatteryService: stay LED for fully charged
,07-05 14:13:18.156  1380  1380 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 14:13:18.156  1380  1380 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
07-05 14:13:18.156  1380  1380 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 14:13:18.166  2328  2328 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 14:13:18.166  2328  2834 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-05 14:13:18.176  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:13:18.186  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:13:18.186  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:13:18.296   767  3520 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 300, LCD = 0
,07-05 14:13:24.476   767  1237 V AlarmManager: Expired Alarm result :8
,07-05 14:13:28.366   767  3520 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 300, LCD = 0
,07-05 14:13:28.776   304  1195 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
07-05 14:13:28.776   304  1195 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
07-05 14:13:28.776   304  1195 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,07-05 14:13:36.536   767  1604 E Watchdog: !@Sync 22 [07-05 14:13:36.551]
,07-05 14:13:37.846  1664  1768 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,07-05 14:13:38.006  1664  1768 E ContactsProvider_EventLog: Flush buffer to file cnt : 5 size : 1Kb duration : 147ms lastUpdatedAfter : 169728ms
,07-05 14:13:38.436   767  3520 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 300, LCD = 0
,07-05 14:13:43.496   767  4844 I ActivityManager: Killing 1902:com.sec.android.app.shealth:remote/u0a35 (adj 5): SSR - service for lastStateTime 665s, lastActivityTime 605s
,07-05 14:13:43.506   767  4844 I ActivityManager: Killing 6491:com.samsung.android.sdk.samsunglink/u0a42 (adj 5): SSR - service for lastStateTime 609s, lastActivityTime 609s
,07-05 14:13:43.506   767  4844 I ActivityManager: Killing 4670:com.sec.spp.push/u0a38 (adj 5): SSR - service for lastStateTime 642s, lastActivityTime 614s
,07-05 14:13:43.516   767  4844 I ActivityManager: Killing 1516:com.sec.android.daemonapp/u0a182 (adj 8): SSR - service for lastStateTime 634s, lastActivityTime 619s
,07-05 14:13:43.526   767  4844 I ActivityManager: Killing 4257:com.qualcomm.telephony/1000 (adj 8): SSR - service for lastStateTime 646s, lastActivityTime 646s
,07-05 14:13:43.526   767  4844 I ActivityManager: Killing 3903:com.sec.android.pagebuddynotisvc/u0a27 (adj 8): SSR - service for lastStateTime 649s, lastActivityTime 649s
,07-05 14:13:43.606   292   292 I ServiceManager: service 'AtCmdFwd' died
,07-05 14:13:43.616   370  4576 I Atfwd_Sendcmd: AtCmdFwd : binderDied
,07-05 14:13:43.616   370  4576 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 14:13:43.626   767  1591 D ActivityManager: isAutoRunBlockedApp:: com.qualcomm.atfwd, Auto Run ON
,07-05 14:13:43.626   767  1591 I ActivityManager: isWidgetUsingPkg : com.qualcomm.atfwd no widget is using.
07-05 14:13:43.626   767  1591 W ActivityManager: Scheduling restart of crashed service com.qualcomm.atfwd/.AtFwdService in 1000ms
,07-05 14:13:43.696   767  1589 D ActivityManager: isAutoRunBlockedApp:: com.sec.android.pagebuddynotisvc, Auto Run ON
07-05 14:13:43.696   767  1589 I ActivityManager: isWidgetUsingPkg : com.sec.android.pagebuddynotisvc no widget is using.
07-05 14:13:43.696   767  1589 W ActivityManager: Scheduling restart of crashed service com.sec.android.pagebuddynotisvc/.PageBuddyNotiSvc in 10934ms
,07-05 14:13:43.706  6788  6788 D HealthConsole: Service for HealthDataStore is disconnected
,07-05 14:13:43.706   767  1764 D ActivityManager: isAutoRunBlockedApp:: com.sec.spp.push, Auto Run ON
07-05 14:13:43.706   767  1764 I ActivityManager: isWidgetUsingPkg : com.sec.spp.push no widget is using.
,07-05 14:13:43.716   767  1591 D ActivityManager: isAutoRunBlockedApp:: com.sec.android.daemonapp, Auto Run ON
07-05 14:13:43.716   767  1591 I ActivityManager: isWidgetUsingPkg : com.sec.android.daemonapp no widget is using.
07-05 14:13:43.716   767  1591 W ActivityManager: Scheduling restart of crashed service com.sec.android.daemonapp/.ap.accuweather.WeatherClockService in 20909ms
,07-05 14:13:43.726   767  4844 D ActivityManager: isAutoRunBlockedApp:: com.samsung.android.sdk.samsunglink, Auto Run ON
07-05 14:13:43.726   767  4844 I ActivityManager: isWidgetUsingPkg : com.samsung.android.sdk.samsunglink no widget is using.
,07-05 14:13:43.736   767  1409 D ActivityManager: isAutoRunBlockedApp:: com.sec.android.app.shealth, Auto Run ON
07-05 14:13:43.736   767  1409 I ActivityManager: isWidgetUsingPkg : com.sec.android.app.shealth widget is using.
07-05 14:13:43.736   767  1409 W ActivityManager: Scheduling restart of crashed service com.sec.android.app.shealth/com.samsung.android.app.shealth.data.DelegateService in 30892ms
07-05 14:13:43.736   767  1409 I ActivityManager: isWidgetUsingPkg : com.sec.android.app.shealth widget is using.
07-05 14:13:43.736   767  1409 W ActivityManager: Scheduling restart of crashed service com.sec.android.app.shealth/com.samsung.android.service.health.HealthService in 40892ms
,07-05 14:13:43.766  7488  7488 E Zygote  : v2
07-05 14:13:43.766  7488  7488 I libpersona: KNOX_SDCARD checking this for 10035
07-05 14:13:43.766  7488  7488 I libpersona: KNOX_SDCARD not a persona
,07-05 14:13:43.766   767  1811 I ActivityManager: Start proc 7488:com.sec.android.app.shealth:remote/u0a35 for service com.sec.android.app.shealth/com.samsung.android.service.health.HealthService
07-05 14:13:43.766  7488  7488 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
07-05 14:13:43.766  7488  7488 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,07-05 14:13:43.766  7488  7488 E Zygote  : accessInfo : 0
,07-05 14:13:43.776  7488  7488 W SELinux : SELinux: seapp_context_lookup: seinfo=release, level=s0:c512,c768, pkgname=com.sec.android.app.shealth:remote 
,07-05 14:13:43.806  7488  7488 D TimaKeyStoreProvider: TimaSignature is unavailable
07-05 14:13:43.806  7488  7488 D ActivityThread: Added TimaKeyStore provider
,07-05 14:13:43.836  7488  7488 W ResourcesManager: getTopLevelResources: /system/priv-app/SHealth4/SHealth4.apk / 1.0 running in com.sec.android.app.shealth rsrc of package null
,07-05 14:13:43.866  7488  7488 W System  : ClassLoader referenced unknown path: /system/priv-app/SHealth4/lib/arm
,07-05 14:13:43.876  7488  7488 I MultiDex: VM with version 2.1.0 has multidex support
07-05 14:13:43.876  7488  7488 I MultiDex: install
07-05 14:13:43.876  7488  7488 I MultiDex: VM has multidex support, MultiDex support library is disabled.
07-05 14:13:43.876  7488  7488 I MultiDex: install
07-05 14:13:43.876  7488  7488 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,07-05 14:13:44.146   767  1466 I ActivityManager: Start proc 7512:com.sec.android.service.health/u0a17 for content provider com.sec.android.service.health/.cp.MigrationCpProvider
,07-05 14:13:44.166  7512  7512 E Zygote  : v2
,07-05 14:13:44.176  7512  7512 I libpersona: KNOX_SDCARD checking this for 10017
,07-05 14:13:44.176  7512  7512 I libpersona: KNOX_SDCARD not a persona
,07-05 14:13:44.176  7512  7512 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
,07-05 14:13:44.176  7512  7512 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,07-05 14:13:44.186  7512  7512 E Zygote  : accessInfo : 0
,07-05 14:13:44.196  7512  7512 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.sec.android.service.health 
,07-05 14:13:44.266  7512  7512 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-05 14:13:44.266  7512  7512 D ActivityThread: Added TimaKeyStore provider
,07-05 14:13:44.296  7512  7512 W ResourcesManager: getTopLevelResources: /system/priv-app/HealthService/HealthService.apk / 1.0 running in com.sec.android.service.health rsrc of package null
,07-05 14:13:44.336  7488  7488 W System.err: stat failed: ENOENT (No such file or directory) : /data/user/0/com.sec.android.app.shealth/databases/secure_shealth2.db
,07-05 14:13:44.336  7488  7488 W System.err: stat failed: ENOENT (No such file or directory) : /data/user/0/com.sec.android.app.shealth/databases/secure_sec_health.db
,07-05 14:13:44.376  1380  1380 D AdaptiveEventManager: setAdaptiveEvent() requestClass = com.sec.android.app.shealth.walkingmate.service.WalkingMateDayStepService smallView = not null bigView = not null
,07-05 14:13:44.386   767  1590 D PackageManager: setEnabledSetting : userId = 0 packageName = com.sec.android.app.shealth cmp = com.sec.android.app.shealth.widget.WalkMateAppWidget newState = 1 callingPackage = 10035
,07-05 14:13:44.386  1380  1380 D AdaptiveEventManager: mViewList[PEDOMETER].view=android.widget.RelativeLayout{2057203 VFE...C.. ......I. 0,0-0,0 #7f0f085c app:id/root_view}
07-05 14:13:44.386  1380  1380 D AdaptiveEventManager: M updateContainers()
07-05 14:13:44.386  1380  1380 D AdaptiveEventContainerSmall: C updatePedoContainer()
07-05 14:13:44.386  1380  1380 D AdaptiveEventContainerSmall: handlePedoUpdate()
,07-05 14:13:44.396  1380  1380 D AdaptiveEventContainerSmall: handlePedoUpdate Show: true,   isPedoEnabled: true isPedoEnabledForPhone:true
,07-05 14:13:44.396   767  1589 D PackageManager: setEnabledSetting : userId = 0 packageName = com.sec.android.app.shealth cmp = com.sec.android.app.shealth.widget.WalkMatePlainAppWidget newState = 1 callingPackage = 10035
,07-05 14:13:44.396   767  1764 D PackageManager: setEnabledSetting : userId = 0 packageName = com.sec.android.app.shealth cmp = com.sec.android.app.shealth.widget.WalkMateAppEasyWidget newState = 1 callingPackage = 10035
,07-05 14:13:44.406   767  1591 D PackageManager: setEnabledSetting : userId = 0 packageName = com.sec.android.app.shealth cmp = com.samsung.android.sdk.healthdata.privileged.status.PackageDelegateReceiver newState = 1 callingPackage = 10035
,07-05 14:13:44.436  7488  7488 I Health.HealthService: HealthService: onCreate() start (7488)
,07-05 14:13:44.546  6788  6788 D HealthDataStore: Service for HealthDataStore is connected
,07-05 14:13:44.546  6788  6788 D HealthDataStore: HealthConnectionErrorResult code : 9
,07-05 14:13:44.566   767  1590 I ActivityManager: Killing 6292:com.google.android.apps.magazines/u0a128 (adj 15): DHA:empty #37
,07-05 14:13:44.586  6788  6788 D HealthDataStore: Trying to connect with Health Service fails (error code: 9)
,07-05 14:13:44.586  6788  6788 E HealthDataStore: disconnectService: Context instance is invalid
,07-05 14:13:44.616   370  4576 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 14:13:44.636   767   866 I ActivityManager: Start proc 7534:com.qualcomm.telephony/1000 for service com.qualcomm.atfwd/.AtFwdService
,07-05 14:13:44.646  7534  7534 E Zygote  : v2
,07-05 14:13:44.646  7534  7534 I libpersona: KNOX_SDCARD checking this for 1000
07-05 14:13:44.646  7534  7534 I libpersona: KNOX_SDCARD not a persona
07-05 14:13:44.646  7534  7534 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
,07-05 14:13:44.646  7534  7534 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,07-05 14:13:44.646  7534  7534 E Zygote  : accessInfo : 0
,07-05 14:13:44.656   767   785 D ActivityManager: isAutoRunBlockedApp:: com.google.android.apps.magazines, Auto Run ON
,07-05 14:13:44.686  7534  7534 D TimaKeyStoreProvider: TimaSignature is unavailable
07-05 14:13:44.686  7534  7534 D ActivityThread: Added TimaKeyStore provider
,07-05 14:13:44.696  7488  7488 D HealthDataStore: Service for HealthDataStore is connected
,07-05 14:13:44.696  7488  7488 D HealthDataStore: HealthConnectionErrorResult code : 9
,07-05 14:13:44.706  7488  7488 D HealthConsole: Service for HealthDataConsole is connected
,07-05 14:13:44.706  7488  7488 D HealthDataStore: Trying to connect with Health Service fails (error code: 9)
,07-05 14:13:44.706  7488  7488 E HealthDataStore: disconnectService: Context instance is invalid
,07-05 14:13:44.716  7534  7534 W ResourcesManager: getTopLevelResources: /system/app/atfwd/atfwd.apk / 1.0 running in com.qualcomm.atfwd rsrc of package null
,07-05 14:13:44.726  7534  7534 W System  : ClassLoader referenced unknown path: /system/app/atfwd/lib/arm
,07-05 14:13:44.726  7534  7534 D AtFwdService: onCreate method
07-05 14:13:44.726  7534  7534 I AtFwdService: Instantiate AtCmdFwd Service
,07-05 14:13:44.736  7534  7559 D AtCkpdCmdHandler: De-queing command
,07-05 14:13:44.896  7488  7529 W System.err: stat failed: ENOENT (No such file or directory) : /data/user/0/com.sec.android.app.shealth/databases/SecureHealthData.db.back
,07-05 14:13:44.936  7488  7562 W System.err: stat failed: ENOENT (No such file or directory) : /data/user/0/com.sec.android.app.shealth/databases/HealthFramework.db.back
,07-05 14:13:44.966  7512  7523 I SecureStorage: [INFO]: SPID(0x00000000)Processing data
,07-05 14:13:44.966   384   384 I SecureStorage: [INFO]: SPID(0x00000007)Credentials: uid 10017, gid 10017, pid 7512
07-05 14:13:44.966   384   384 I SecureStorage: [INFO]: SPID(0x00000007)Received function mask & code: 0x00000106
,07-05 14:13:45.116  7512  7523 I SecureStorage: [INFO]: SPID(0x00000008)ss_id will be loaded by secure_storage_daemon: com.sec.android.service.health
,07-05 14:13:45.386  7488  7562 W System.err: stat failed: ENOENT (No such file or directory) : /data/user/0/com.sec.android.app.shealth/databases/Permission.db.back
,07-05 14:13:45.496  7488  7562 W System.err: stat failed: ENOENT (No such file or directory) : /data/user/0/com.sec.android.app.shealth/databases/secure_shealth2.db
,07-05 14:13:45.496  7488  7562 W System.err: stat failed: ENOENT (No such file or directory) : /data/user/0/com.sec.android.app.shealth/databases/secure_sec_health.db
,07-05 14:13:45.546   384   384 I SecureStorage: [INFO]: SPID(0x00000008)Secure Storage Daemon finished processing with result: 0
,07-05 14:13:45.586  7512  7523 I SecureStorage: [INFO]: SPID(0x00000008)Processing data has been completed
,07-05 14:13:45.586  7512  7523 I SecureStorage: [INFO]: SPID(0x00000008)Skip using SecureStorageExceptionJNI
,07-05 14:13:45.596  7512  7523 D HSCheck : SS_G-2d de 1c 15 c8 bf 9d d9 69 c1 84 f0 50 9f a4 42 
,07-05 14:13:48.176   767  1826 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 14:13:48.506   767  3520 D SSRM:n  : SIOP:: AP = 310, PST = 301, CUR = 300, LCD = 0
,07-05 14:13:54.696   767   866 I ActivityManager: Start proc 7582:com.sec.android.pagebuddynotisvc/u0a27 for service com.sec.android.pagebuddynotisvc/.PageBuddyNotiSvc
,07-05 14:13:54.706  7582  7582 E Zygote  : v2
,07-05 14:13:54.706  7582  7582 I libpersona: KNOX_SDCARD checking this for 10027
07-05 14:13:54.706  7582  7582 I libpersona: KNOX_SDCARD not a persona
,07-05 14:13:54.706  7582  7582 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
,07-05 14:13:54.706  7582  7582 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,07-05 14:13:54.716  7582  7582 E Zygote  : accessInfo : 0
,07-05 14:13:54.716  7582  7582 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.sec.android.pagebuddynotisvc 
,07-05 14:13:54.756  7582  7582 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-05 14:13:54.756  7582  7582 D ActivityThread: Added TimaKeyStore provider
,07-05 14:13:54.786  7582  7582 W ResourcesManager: getTopLevelResources: /system/priv-app/PageBuddyNotiSvcK/PageBuddyNotiSvcK.apk / 1.0 running in com.sec.android.pagebuddynotisvc rsrc of package null
,07-05 14:13:54.796  7582  7582 W System  : ClassLoader referenced unknown path: /system/priv-app/PageBuddyNotiSvcK/lib/arm
,07-05 14:13:54.816  7582  7582 I PageBuddyNotiSvc: onCreate mCpBitFlag=0
,07-05 14:13:54.816  7582  7582 D ContextualPageNotification: resetAllNotification : all clear!!!
,07-05 14:13:58.566   767  3520 D SSRM:n  : SIOP:: AP = 300, PST = 301, CUR = 300, LCD = 0
,07-05 14:14:04.696   767   866 I ActivityManager: Start proc 7595:com.sec.android.daemonapp/u0a182 for service com.sec.android.daemonapp/.ap.accuweather.WeatherClockService
07-05 14:14:04.696   767  1322 D NetworkPolicy: isUidForegroundLocked: 10182, mScreenOn: false, uidstate: -1, mProxSensorScreenOff: false
,07-05 14:14:04.706  7595  7595 E Zygote  : v2
,07-05 14:14:04.706  7595  7595 I libpersona: KNOX_SDCARD checking this for 10182
07-05 14:14:04.706  7595  7595 I libpersona: KNOX_SDCARD not a persona
,07-05 14:14:04.706  7595  7595 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
,07-05 14:14:04.706  7595  7595 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,07-05 14:14:04.716  7595  7595 E Zygote  : accessInfo : 0
,07-05 14:14:04.716  7595  7595 W SELinux : SELinux: seapp_context_lookup: seinfo=shared, level=s0:c512,c768, pkgname=com.sec.android.daemonapp 
,07-05 14:14:04.766  7595  7595 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-05 14:14:04.766  7595  7595 D ActivityThread: Added TimaKeyStore provider
,07-05 14:14:04.786   767  1322 D NetworkPolicy: isUidForegroundLocked: 10182, mScreenOn: false, uidstate: 10, mProxSensorScreenOff: false
,07-05 14:14:04.796  7595  7595 W ResourcesManager: getTopLevelResources: /system/app/WeatherDaemon2014_MMR/WeatherDaemon2014_MMR.apk / 1.0 running in com.sec.android.daemonapp rsrc of package null
,07-05 14:14:04.826  7595  7595 W System  : ClassLoader referenced unknown path: /system/app/WeatherDaemon2014_MMR/lib/arm
,07-05 14:14:04.856  7595  7595 D comsamsungapp: [MSC_Daemon]>>> WCP:1124 [0:0] Provider Created
,07-05 14:14:04.866  7595  7595 D comsamsungapp: [MSC_Daemon]>>> AOH:46 [0:0] OpenHelper : 67
,07-05 14:14:04.866   767   866 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{b55bc12 u0 com.sec.android.widgetapp.ap.accuweatherdaemon.action.CHANGE_ICON_OF_DAEMON qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{ababfe3 7595:com.sec.android.daemonapp/u0a182}
,07-05 14:14:04.886  7595  7595 D comsamsungapp: [MSC_Daemon]>>> WNCP:216 [0:0] WeatherNewsJP Provider Created
,07-05 14:14:04.886  7595  7595 D comsamsungapp: [MSC_Daemon]>>> AOH:46 [0:0] OpenHelper : 67
,07-05 14:14:04.886  7595  7595 D comsamsungapp: [MSC_Daemon]>>> CCP:226 [0:0] CmaWeather Provider Created
,07-05 14:14:04.886  7595  7595 D comsamsungapp: [MSC_Daemon]>>> AOH:46 [0:0] OpenHelper : 67
,07-05 14:14:04.896  7595  7595 D comsamsungapp: [MSC_Daemon]>>> KWCP:221 [0:0] KWeather Provider Created
,07-05 14:14:04.896  7595  7595 D comsamsungapp: [MSC_Daemon]>>> AOH:46 [0:0] OpenHelper : 67
,07-05 14:14:04.916  7595  7595 D comsamsungapp: [MSC_Daemon]>>> WU:262 [0:0] regintype : EUR
,07-05 14:14:04.916  7595  7595 D comsamsungapp: [MSC_Daemon]>>> WU:303 [0:0] cp type is : cp_eng
,07-05 14:14:04.926  7595  7595 D comsamsungapp: [MSC_Daemon]>>> WCS:39 [0:0] onStartcommand()
,07-05 14:14:04.926  7595  7595 D comsamsungapp: [MSC_Daemon]>>> WU:262 [0:0] regintype : EUR
,07-05 14:14:04.926  7595  7595 D comsamsungapp: [MSC_Daemon]>>> WU:303 [0:0] cp type is : cp_eng
07-05 14:14:04.926  7595  7595 D comsamsungapp: [MSC_Daemon]>>> WCS:62 [0:0] CP Name cp_eng
,07-05 14:14:04.936  7595  7595 D comsamsungapp: [MSC_Daemon]>>> WCP:1144 [0:0] Provider query : content://daemonappapaccuweatherprovider/weatherinfo
,07-05 14:14:04.956  7595  7595 D comsamsungapp: [MSC_Daemon]>>> WCS:81 [0:0] td null
,07-05 14:14:04.966  7595  7595 D comsamsungapp: [MSC_Daemon]>>> WU:262 [0:0] regintype : EUR
,07-05 14:14:04.966  7595  7595 D comsamsungapp: [MSC_Daemon]>>> WU:303 [0:0] cp type is : cp_eng
07-05 14:14:04.966  7595  7595 D comsamsungapp: [MSC_Daemon]>>> WCP:1144 [0:0] Provider query : content://daemonappapaccuweatherprovider/settings
,07-05 14:14:04.966  7595  7595 D comsamsungapp: [MSC_Daemon]>>> WCP:1144 [0:0] Provider query : content://daemonappapaccuweatherprovider/weatherinfo
,07-05 14:14:04.976  7595  7595 D comsamsungapp: [MSC_Daemon]>>> WDSM:41 [0:0] Act : widgetappapaccuweatherdaemonactionCHANGE_ICON_OF_DAEMON, run:true
,07-05 14:14:04.976  7595  7595 D comsamsunglog: [MSC_Daemon]>>> ====================================================================================================================
07-05 14:14:04.976  7595  7595 D comsamsunglog: [MSC_Daemon]>>> daemonapp [Version : 1602011514259 ] [ 3 ] 
,07-05 14:14:04.976  7595  7595 D comsamsunglog: [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
07-05 14:14:04.976  7595  7595 D comsamsunglog: [MSC_Daemon]>>> ====================================================================================================================
,07-05 14:14:04.976  7595  7595 D daemonapp: [MSC_Daemon]>>> WDSM:82 [0:0] c:null, r:3
07-05 14:14:04.976  7595  7595 D daemonapp: [MSC_Daemon]>>> WDSM:434 [0:0] ====ACTION_SEC_CHANGE_ICON_OF_DAEMON===
,07-05 14:14:04.986  7595  7595 D daemonapp: [MSC_Daemon]>>> WU:1260 [0:0] cDayONight() ::: sunrise is null 
07-05 14:14:04.986  7595  7595 D daemonapp: [MSC_Daemon]>>> WU:1280 [0:0] cDayONight() ::: sunset is null 
,07-05 14:14:04.986  7595  7595 D daemonapp: [MSC_Daemon]>>> WDSM:438 [0:0] checkDay:true, UtilgetIsDay():false
07-05 14:14:04.986  7595  7595 D daemonapp: [MSC_Daemon]>>> WCP:1144 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,07-05 14:14:04.986  7595  7595 D daemonapp: [MSC_Daemon]>>> WDSM:464 [0:0] today==null
,07-05 14:14:04.996   767  1826 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{b4f773f u0 com.sec.android.widgetapp.ap.accuweatherdaemon.action.CHANGE_ICON_OF_DAEMON qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{ababfe3 7595:com.sec.android.daemonapp/u0a182}
,07-05 14:14:05.006  7595  7595 D daemonapp: [MSC_Daemon]>>> WU:262 [0:0] regintype : EUR
,07-05 14:14:05.006  7595  7595 D daemonapp: [MSC_Daemon]>>> WU:303 [0:0] cp type is : cp_eng
07-05 14:14:05.006  7595  7595 D daemonapp: [MSC_Daemon]>>> WCP:1144 [0:0] Provider query : content://apaccuweatherprovider/settings
,07-05 14:14:05.006  7595  7595 D daemonapp: [MSC_Daemon]>>> WCP:1144 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,07-05 14:14:05.016  7595  7595 D daemonapp: [MSC_Daemon]>>> WDSM:41 [0:0] Act : widgetappapaccuweatherdaemonactionCHANGE_ICON_OF_DAEMON, run:true
,07-05 14:14:05.016  7595  7595 D comsamsunglog: [MSC_Daemon]>>> ====================================================================================================================
07-05 14:14:05.016  7595  7595 D comsamsunglog: [MSC_Daemon]>>> daemonapp [Version : 1602011514259 ] [ 3 ] 
07-05 14:14:05.016  7595  7595 D comsamsunglog: [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
,07-05 14:14:05.016  7595  7595 D comsamsunglog: [MSC_Daemon]>>> ====================================================================================================================
07-05 14:14:05.016  7595  7595 D daemonapp: [MSC_Daemon]>>> WDSM:82 [0:0] c:null, r:3
07-05 14:14:05.016  7595  7595 D daemonapp: [MSC_Daemon]>>> WDSM:434 [0:0] ====ACTION_SEC_CHANGE_ICON_OF_DAEMON===
07-05 14:14:05.016  7595  7595 D daemonapp: [MSC_Daemon]>>> WU:1260 [0:0] cDayONight() ::: sunrise is null 
,07-05 14:14:05.016  7595  7595 D daemonapp: [MSC_Daemon]>>> WU:1280 [0:0] cDayONight() ::: sunset is null 
07-05 14:14:05.016  7595  7595 D daemonapp: [MSC_Daemon]>>> WDSM:438 [0:0] checkDay:true, UtilgetIsDay():false
07-05 14:14:05.016  7595  7595 D daemonapp: [MSC_Daemon]>>> WCP:1144 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,07-05 14:14:05.026  7595  7595 D daemonapp: [MSC_Daemon]>>> WDSM:464 [0:0] today==null
,07-05 14:14:05.036   767  1466 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{e5280c u0 com.sec.android.widgetapp.ap.accuweatherdaemon.action.CHANGE_ICON_OF_DAEMON qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{ababfe3 7595:com.sec.android.daemonapp/u0a182}
,07-05 14:14:05.046  7595  7595 D daemonapp: [MSC_Daemon]>>> WU:262 [0:0] regintype : EUR
,07-05 14:14:05.046  7595  7595 D daemonapp: [MSC_Daemon]>>> WU:303 [0:0] cp type is : cp_eng
,07-05 14:14:05.046  7595  7595 D daemonapp: [MSC_Daemon]>>> WCP:1144 [0:0] Provider query : content://apaccuweatherprovider/settings
,07-05 14:14:05.046  7595  7595 D daemonapp: [MSC_Daemon]>>> WCP:1144 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,07-05 14:14:05.056  7595  7595 D daemonapp: [MSC_Daemon]>>> WDSM:41 [0:0] Act : widgetappapaccuweatherdaemonactionCHANGE_ICON_OF_DAEMON, run:true
,07-05 14:14:05.056  7595  7595 D comsamsunglog: [MSC_Daemon]>>> ====================================================================================================================
,07-05 14:14:05.056  7595  7595 D comsamsunglog: [MSC_Daemon]>>> daemonapp [Version : 1602011514259 ] [ 3 ] 
07-05 14:14:05.056  7595  7595 D comsamsunglog: [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
,07-05 14:14:05.056  7595  7595 D comsamsunglog: [MSC_Daemon]>>> ====================================================================================================================
07-05 14:14:05.056  7595  7595 D daemonapp: [MSC_Daemon]>>> WDSM:82 [0:0] c:null, r:3
,07-05 14:14:05.056  7595  7595 D daemonapp: [MSC_Daemon]>>> WDSM:434 [0:0] ====ACTION_SEC_CHANGE_ICON_OF_DAEMON===
07-05 14:14:05.056  7595  7595 D daemonapp: [MSC_Daemon]>>> WU:1260 [0:0] cDayONight() ::: sunrise is null 
,07-05 14:14:05.066  7595  7595 D daemonapp: [MSC_Daemon]>>> WU:1280 [0:0] cDayONight() ::: sunset is null 
07-05 14:14:05.066  7595  7595 D daemonapp: [MSC_Daemon]>>> WDSM:438 [0:0] checkDay:true, UtilgetIsDay():false
,07-05 14:14:05.066  7595  7595 D daemonapp: [MSC_Daemon]>>> WCP:1144 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,07-05 14:14:05.066  7595  7595 D daemonapp: [MSC_Daemon]>>> WDSM:464 [0:0] today==null
,07-05 14:14:05.086   767  1826 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{90de555 u0 com.sec.android.widgetapp.ap.accuweatherdaemon.action.CHANGE_ICON_OF_DAEMON qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{ababfe3 7595:com.sec.android.daemonapp/u0a182}
,07-05 14:14:05.096  7595  7595 D daemonapp: [MSC_Daemon]>>> WU:262 [0:0] regintype : EUR
,07-05 14:14:05.096  7595  7595 D daemonapp: [MSC_Daemon]>>> WU:303 [0:0] cp type is : cp_eng
07-05 14:14:05.096  7595  7595 D daemonapp: [MSC_Daemon]>>> WCP:1144 [0:0] Provider query : content://apaccuweatherprovider/settings
,07-05 14:14:05.096  7595  7595 D daemonapp: [MSC_Daemon]>>> WCP:1144 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,07-05 14:14:05.106  7595  7595 D daemonapp: [MSC_Daemon]>>> WDSM:41 [0:0] Act : widgetappapaccuweatherdaemonactionCHANGE_ICON_OF_DAEMON, run:true
,07-05 14:14:05.106  7595  7595 D comsamsunglog: [MSC_Daemon]>>> ====================================================================================================================
07-05 14:14:05.106  7595  7595 D comsamsunglog: [MSC_Daemon]>>> daemonapp [Version : 1602011514259 ] [ 3 ] 
,07-05 14:14:05.106  7595  7595 D comsamsunglog: [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
07-05 14:14:05.106  7595  7595 D comsamsunglog: [MSC_Daemon]>>> ====================================================================================================================
07-05 14:14:05.106  7595  7595 D daemonapp: [MSC_Daemon]>>> WDSM:82 [0:0] c:null, r:3
,07-05 14:14:05.106  7595  7595 D daemonapp: [MSC_Daemon]>>> WDSM:434 [0:0] ====ACTION_SEC_CHANGE_ICON_OF_DAEMON===
07-05 14:14:05.106  7595  7595 D daemonapp: [MSC_Daemon]>>> WU:1260 [0:0] cDayONight() ::: sunrise is null 
,07-05 14:14:05.106  7595  7595 D daemonapp: [MSC_Daemon]>>> WU:1280 [0:0] cDayONight() ::: sunset is null 
07-05 14:14:05.106  7595  7595 D daemonapp: [MSC_Daemon]>>> WDSM:438 [0:0] checkDay:true, UtilgetIsDay():false
,07-05 14:14:05.106  7595  7595 D daemonapp: [MSC_Daemon]>>> WCP:1144 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,07-05 14:14:05.116  7595  7595 D daemonapp: [MSC_Daemon]>>> WDSM:464 [0:0] today==null
,07-05 14:14:06.546   767  1604 E Watchdog: !@Sync 23 [07-05 14:14:06.557]
,07-05 14:14:08.636   767  3520 D SSRM:n  : SIOP:: AP = 300, PST = 301, CUR = 300, LCD = 0
,07-05 14:14:18.266   767  1748 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 14:14:18.266   767  1748 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4358, temperature: 299, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,07-05 14:14:18.266   767  1748 D BatteryService: online:4, current avg:300, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
,07-05 14:14:18.276   767   767 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 14:14:18.286   767   767 I MotionRecognitionService: Plugged
,07-05 14:14:18.286   767  1748 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 24ms
,07-05 14:14:18.296   767   767 D MotionRecognitionService:   cableConnection= 1
,07-05 14:14:18.296   767  1748 D BatteryService: stay LED for fully charged
,07-05 14:14:18.296   767   767 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,07-05 14:14:18.306   767   767 D MotionRecognitionService: skip setTransmitPower. 
,07-05 14:14:18.316  1380  1380 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 14:14:18.316  1380  1380 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,07-05 14:14:18.326  1380  1380 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 14:14:18.346  2328  2328 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 14:14:18.346  2328  2834 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-05 14:14:18.346  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:14:18.346  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:14:18.346  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:14:18.696   767  3520 D SSRM:n  : SIOP:: AP = 300, PST = 301, CUR = 300, LCD = 0
,07-05 14:14:28.746   767  3520 D SSRM:n  : SIOP:: AP = 300, PST = 301, CUR = 300, LCD = 0
,07-05 14:14:36.556   767  1604 E Watchdog: !@Sync 24 [07-05 14:14:36.566]
,07-05 14:14:38.066  1664  1768 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,07-05 14:14:38.806   767  3520 D SSRM:n  : SIOP:: AP = 300, PST = 301, CUR = 300, LCD = 0
,07-05 14:14:48.326   767  1767 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 14:14:48.326   767  1767 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4357, temperature: 299, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
07-05 14:14:48.326   767  1767 D BatteryService: online:4, current avg:300, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
07-05 14:14:48.326   767  1767 D BatteryService: stay LED for fully charged
,07-05 14:14:48.326   767   767 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 14:14:48.336   767   767 I MotionRecognitionService: Plugged
,07-05 14:14:48.336   767   767 D MotionRecognitionService:   cableConnection= 1
07-05 14:14:48.336   767   767 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
07-05 14:14:48.336   767   767 D MotionRecognitionService: skip setTransmitPower. 
,07-05 14:14:48.336  1380  1380 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 14:14:48.336  1380  1380 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
07-05 14:14:48.336  1380  1380 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 14:14:48.356  2328  2328 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 14:14:48.356  2328  2834 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-05 14:14:48.366  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:14:48.366  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 14:14:48.366  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:14:48.856   767  3520 D SSRM:n  : SIOP:: AP = 300, PST = 301, CUR = 300, LCD = 0
,07-05 14:14:58.936   767  3520 D SSRM:n  : SIOP:: AP = 300, PST = 301, CUR = 300, LCD = 0
,07-05 14:15:06.556   767  1604 E Watchdog: !@Sync 25 [07-05 14:15:06.570]
,07-05 14:15:09.016   767  3520 D SSRM:n  : SIOP:: AP = 300, PST = 301, CUR = 300, LCD = 0
,07-05 14:15:18.406   767  1679 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 14:15:18.406   767  1679 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4361, temperature: 298, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,07-05 14:15:18.416   767  1679 D BatteryService: online:4, current avg:300, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
,07-05 14:15:18.416   767   767 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 14:15:18.426   767   767 I MotionRecognitionService: Plugged
,07-05 14:15:18.426   767   767 D MotionRecognitionService:   cableConnection= 1
,07-05 14:15:18.436   767   767 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,07-05 14:15:18.436   767   767 D MotionRecognitionService: skip setTransmitPower. 
,07-05 14:15:18.446   767  1679 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 36ms
,07-05 14:15:18.446   767  1679 D BatteryService: stay LED for fully charged
,07-05 14:15:18.456  1380  1380 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 14:15:18.456  1380  1380 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,07-05 14:15:18.466  1380  1380 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 14:15:18.486  2328  2328 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 14:15:18.486  2328  2834 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-05 14:15:18.496  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:15:18.496  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 14:15:18.496  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:15:19.076   767  3520 D SSRM:n  : SIOP:: AP = 300, PST = 301, CUR = 300, LCD = 0
,07-05 14:15:29.126   767  3520 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 300, LCD = 0
,07-05 14:15:36.566   767  1604 E Watchdog: !@Sync 26 [07-05 14:15:36.575]
,07-05 14:15:38.116  1664  1768 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,07-05 14:15:39.186   767  3520 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 300, LCD = 0
,07-05 14:15:41.096   767  2427 V MARsPolicyManager: updatePackagesScore PackageInfo name -- null
,07-05 14:15:41.096   767  2427 V MARsPolicyManager: updateSMDBValues
,07-05 14:15:41.106   767   905 E MARsDBManager: updateDBAll : begin --size 0
,07-05 14:15:41.106   767   905 E MARsDBManager: updateDBAll : end
,07-05 14:15:45.766   767  1298 D InputReader: Input event(7): value=1 when=820510418000
,07-05 14:15:45.766   767  1298 D InputReader: !@notifyKey(172), action=0
,07-05 14:15:45.766   767  1298 D InputManager-JNI: !@interceptKeyBeforeQueueing(172), action=0, interactive=false
,07-05 14:15:45.776   767  1298 D CustomFrequencyManagerService: acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 767  pkgName : WAKEUP_BOOSTER@35
,07-05 14:15:45.786   767  1298 E SamsungWindowManager: mCoreNumLockHelper.acquire
,07-05 14:15:45.786   767  1298 D PowerManagerService: [api] [s] wakeUpWithReason (uid: 1000 pid: 767) eventTime = 820510 event = 1
,07-05 14:15:45.796   767  1298 I PowerManagerService: !@[ps] Screen__On  - 1 :  wakeUpWithReason: 1 (uid: 1000 pid: 767) (1)
,07-05 14:15:45.796   767  1298 I PowerManagerService: Waking up from sleep (uid 1000)...
07-05 14:15:45.796   767  1298 D InputManager-JNI: setInteractive(true)
,07-05 14:15:45.796   767  1359 D NetworkPolicy: onScreenStateChanged, state: true, reason: 2
,07-05 14:15:45.796   767  1298 D PowerManagerService: [PWL] sb acquire: PowerManagerService.Broadcasts
,07-05 14:15:45.796   767  1359 V KeyguardServiceDelegate: onStartedWakingUp()
07-05 14:15:45.796  1380  2112 I PERF    : KeyguardViewMediator - onStartedWakingUp() start
,07-05 14:15:45.796   767  1298 D PowerManagerService: [s] UserActivityState : 0 -> 1
07-05 14:15:45.796   767  1298 D PowerManagerService: mDisplayReady: false
07-05 14:15:45.796   767  1298 D PowerManagerService: [PWL] sb acquire: PowerManagerService.Display
07-05 14:15:45.796   767  1298 D InputManager-JNI: !@handleInterceptActions(172), action=0, wmActions=0
07-05 14:15:45.796   767  1298 D InputManager-JNI: Disable repeat for home key when device wake up
,07-05 14:15:45.796  1380  2112 D KeyguardViewMediator: onStartedWakingUp, seq = 2
07-05 14:15:45.796  1380  2112 D KeyguardViewMediator: notifyStartedWakingUp
,07-05 14:15:45.796  1380  1380 I PERF    : KeyguardViewMediator - handleNotifyStartedWakingUp() start
07-05 14:15:45.796  1380  1380 D KeyguardViewMediator: handleNotifyWakingUp
07-05 14:15:45.796  1380  1380 D PanelView: onScreenTurnedOn 0,1
07-05 14:15:45.796  1380  1380 I PERF    : KeyguardViewMediator - handleNotifyStartedWakingUp() end
07-05 14:15:45.796  1380  1380 I PERF    : KeyguardUpdateMonitor - cb.onScreenTurnedOn() start
07-05 14:15:45.806   767   912 D DisplayPowerController: animateScreenStateChange[0]: target=2
07-05 14:15:45.806   767   912 D DisplayPowerController: [M OS] 0 REPORTED_TO_POLICY_SCREEN_OFF -> REPORTED_TO_POLICY_SCREEN_TURNING_ON.
,07-05 14:15:45.806   767   912 I DisplayPowerController: Blocking screen on until initial contents have been drawn.
,07-05 14:15:45.816   767   866 V MARsPolicyManager: updatePackagesScore PackageInfo name -- com.samsung.android.MtpApplication
,07-05 14:15:45.816  1380  1380 D SecKeyguardClockSingleView: onScreenTurnedOn
,07-05 14:15:45.826  1380  1380 D SecKeyguardStatusUtils: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-05 14:15:45.826  1380  1380 I PERF    : KeyguardUpdateMonitor - cb.onScreenTurnedOn() end
,07-05 14:15:45.836   767   912 V KeyguardServiceDelegate: onScreenTurnedOn(showListener = com.android.server.policy.PhoneWindowManager$2@cc2b8f8)
,07-05 14:15:45.836   767   912 D DisplayPowerController: mWindowManagerPolicy.screenTurningOn(mPendingScreenOnUnblocker, 0)
07-05 14:15:45.836   767   912 D DisplayPowerController: animateScreenStateChange[0]: return as screen on blocked
07-05 14:15:45.836   767   912 D DisplayPowerController: [Dual Screen Compatible] state[0] :2
07-05 14:15:45.836   767   912 D AutomaticBrightnessController: [DAB] no lux value from sensor manager
07-05 14:15:45.836   767   912 D DisplayPowerController: getFinalBrightness : Summary is 0 -> 0
07-05 14:15:45.836   767  1361 D AutomaticBrightnessController: [DAB] setLightSensorEnabled : registerListenerRunnable
,07-05 14:15:45.836   767   912 D DisplayPowerController: Animating brightness: target=0, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1), PendingAutoBrightness)
07-05 14:15:45.836  1380  2112 I PERF    : KeyguardViewMediator - onStartedWakingUp() end
07-05 14:15:45.836  1380  2112 D KeyguardViewMediator: notifyScreenOn
07-05 14:15:45.836  6924  6924 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
07-05 14:15:45.836  6924  6924 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STARTED
,07-05 14:15:45.836   767   934 I libsuspend: !@autosuspend_wakeup_count_disable
07-05 14:15:45.836   767   934 I libsuspend: !@autosuspend_wakeup_count_disable done
07-05 14:15:45.836   767   934 D DisplayManagerService: !@display_state: OFF -> ON brightness: 0 -> 0
07-05 14:15:45.836  1380  1380 I PERF    : KeyguardViewMediator - handleNotifyScreenTurningOn() start
07-05 14:15:45.836  1380  1380 D KeyguardViewMediator: handleNotifyScreenTurningOn
07-05 14:15:45.836   767   907 I DisplayManagerService: Display device changed state: "Built-in Screen", ON
,07-05 14:15:45.836   293   293 D SurfaceFlinger: Set power mode=2, type=0 flinger=0xb6a64000
07-05 14:15:45.836  1380  1380 D KeyguardViewMediator: onScreenTurnedOn()
07-05 14:15:45.836   767  1589 V KeyguardServiceDelegate: **** SHOWN CALLED ****
07-05 14:15:45.836   293   293 D qdhwcomposer: hwc_setPowerMode: Setting mode 2 on display: 0
07-05 14:15:45.836  1380  1380 D KeyguardViewMediator: callback.onShown()
07-05 14:15:45.836  1380  1380 I PERF    : KeyguardViewMediator - handleNotifyScreenTurningOn() end
,07-05 14:15:45.846   767  1361 D SensorService: SensorEventConnection::SocketBufferSize, SystemSocketBufferSize - 102400, 2097152
,07-05 14:15:45.856   767  1361 E LightSensor: Light old sensor_state 0, new sensor_state : 512 en : 1,
,07-05 14:15:45.866   767  1361 D SensorManager: registerListener :: 6, TMG399X RGB Sensor, 250000, 0,  
,07-05 14:15:45.866   767  1361 D SensorService: SensorEventConnection::SocketBufferSize, SystemSocketBufferSize - 102400, 2097152
,07-05 14:15:45.866   767  1361 E Sensors : Acc old sensor_state 512, new sensor_state : 513 en : 1
,07-05 14:15:45.876   767  1361 D SensorManager: registerListener :: 0, MPU6500 Acceleration Sensor, 250000, 0,  
07-05 14:15:45.876   767  1361 D PowerManagerUtil: Excessive delay in setLightSensorEnabled::registerListener done: 43ms
,07-05 14:15:45.876   767   785 D CoverManagerWhiteLists: isAllowedToUse : SIGNATURE_MATCH
07-05 14:15:45.876  1380  1380 D BatteryMeterView: onDraw batteryColor : -1107296257
,07-05 14:15:45.886  1733  1944 I System.out: Broadcasting: Intent { act=com.sec.android.LTE_WIDEBAND_INFO flg=0x10000000 (has extras) }
,07-05 14:15:45.886   304  1195 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
07-05 14:15:45.886   304  1195 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
07-05 14:15:45.886   304  1195 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,07-05 14:15:45.886   767  1322 D NetworkPolicy: isUidForegroundLocked: 10004, mScreenOn: false, uidstate: 2, mProxSensorScreenOff: false
,07-05 14:15:45.896  2105  2105 D SamsungIME: showDlgMsgBox : false true true
,07-05 14:15:45.896  1722  1895 D NfcService: call the applyRouting
,07-05 14:15:45.896   767  1679 D ActivityManager: post active user change for 0 fullscreen false isFloatingActivity() false isHomeActivity() false
07-05 14:15:45.896   767  1679 D KnoxTimeoutHandler: postActiveUserChange [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
,07-05 14:15:45.896  3576  3576 E MtpService: In MTPAPP onReceive:android.intent.action.USER_PRESENT
07-05 14:15:45.896  3576  3576 E MtpService: Inside ACTION_USER_PRESENT:android.intent.action.USER_PRESENT
,07-05 14:15:45.896  1380  1380 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
,07-05 14:15:45.896  1380  1380 I PERF    : received broadcast android.intent.action.TIME_TICK
07-05 14:15:45.896  1380  1380 D KeyguardUpdateMonitor: handleTimeUpdate
,07-05 14:15:45.906   767   868 W CAE     : setCAProperty(ContextAwareService.java:578) - [setProperty 01] Mutex is locked for AUTO_ROTATION
,07-05 14:15:45.906   767   868 I CAE     : setPropertyValue(AutoRotationRunner.java:119) - Device Type = 0.0
,07-05 14:15:45.906   767   868 I CAE     : setCAProperty(ContextAwareService.java:583) - result : true
07-05 14:15:45.906   767   868 W CAE     : setCAProperty(ContextAwareService.java:584) - [setProperty 02] Mutex is unlocked for AUTO_ROTATION
07-05 14:15:45.906   767   868 W CAE     : registerCallback(ContextAwareService.java:144) - [regi 01] Mutex is locked for AUTO_ROTATION
,07-05 14:15:45.906  1380  1380 D SecKeyguardClockView: onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,07-05 14:15:45.906   767   868 V CAE     : start(ContextProvider.java:128)
07-05 14:15:45.906   767   868 V CAE     : clear(AutoRotationRunner.java:182)
,07-05 14:15:45.906   767   868 V CAE     : enable(AutoRotationRunner.java:158)
07-05 14:15:45.906   767   868 I CAE     : sendCmdToSensorHub(SensorHubCommManager.java:162) - -79, 7, 0, 0,
07-05 14:15:45.906   767   868 D SensorHubManager: SendSensorHubData: send data = -79, 7, 0, 0
,07-05 14:15:45.916   328   328 D Sensorhubs: sendContextData: -79, 7, 0, 0
,07-05 14:15:45.916  1380  1380 D SecKeyguardClockView: HomeTimezone(): 1
,07-05 14:15:45.916   767   868 D CAE     : getFaultDetectionResult(AutoRotationRunner.java:195) - true
,07-05 14:15:45.916   767   868 I CAE     : notifyCmdProcessResultObserver(ContextProvider.java:627) - CheckResult = 0, Cause = Success
07-05 14:15:45.916  2328  2328 D HeadsetPhoneState: Signal level : previous=0 curr=0
,07-05 14:15:45.926  1380  1380 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
07-05 14:15:45.926  1380  1380 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
07-05 14:15:45.926  1380  1380 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-05 14:15:45.926  1380  1380 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
07-05 14:15:45.926  1380  1380 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-05 14:15:45.926  1380  1380 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
07-05 14:15:45.926  1380  1380 D SecKeyguardStatusUtils: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-05 14:15:45.936   767   868 D CAE     : doCommendProcess(ContextAwareService.java:433) - complete notify the operation result.
,07-05 14:15:45.936   767   868 I CAE     : displayUsedCountForService(ContextAwareService.java:525) - totalCnt = 1, serviceCount = 1, subCollectionCount = 0
,07-05 14:15:45.936   767   868 D CAE     : showListenerList(ContextAwareService.java:366) - ===== Context Aware Service List =====
07-05 14:15:45.936   767   868 I CAE     : showListenerList(ContextAwareService.java:375) - Listener : com.samsung.android.contextaware.manager.ContextAwareService$Listener@b6149c6, Service : ACTIVITY_TRACKER_CURRENT_INFO(1)
,07-05 14:15:45.936   767   868 I CAE     : showListenerList(ContextAwareService.java:375) - Listener : com.samsung.android.contextaware.manager.ContextAwareService$Listener@fef2436, Service : AUTO_ROTATION(1)
07-05 14:15:45.936   767   868 W CAE     : registerCallback(ContextAwareService.java:180) - [regi 02] Mutex is unlocked for AUTO_ROTATION
07-05 14:15:45.936   767   868 D SContextService: 	.registerCallback : 1, client=
07-05 14:15:45.936   767   868 D SContextService: ===== SContext Service List =====
07-05 14:15:45.936   767   868 D SContextService: Listener : android.hardware.scontext.SContextService$Listener@d9f0f37, Service : Auto Rotation
07-05 14:15:45.936   767   868 D DisplayPowerController: [api] WindowManagerPolicy.ScreenOnListener : Received onScreenOn().
07-05 14:15:45.936   767   868 D SContextManager:   .registerListener : listener = com.android.server.policy.WindowOrientationListener$OrientationSensorJudge@1809fbb, service=Auto Rotation
,07-05 14:15:45.936   767   767 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{ee66ca4 u0 android.intent.action.USER_PRESENT qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{18ebe38 1653:com.google.android.gms.persistent/u0a12}
,07-05 14:15:45.936   767   866 V MARsPolicyManager: executePolicy policy  applockerpolicy(3) reason App Locker -- 10Min
07-05 14:15:45.936   767   912 I DisplayPowerController: Unblocked screen on after 134 ms
07-05 14:15:45.936   767   912 D DisplayPowerController: animateScreenStateChange[0]: target=2
07-05 14:15:45.936   767   912 D ColorFade: prepare: mode=2
07-05 14:15:45.936   767   912 D ColorFade: ColorFade is already prepared
07-05 14:15:45.936   767   912 D DisplayPowerController: [Dual Screen Compatible] state[0] :2
07-05 14:15:45.936   767   912 D DisplayPowerController: getFinalBrightness : Summary is 0 -> 0
07-05 14:15:45.936   767   912 D DisplayPowerController: Animating brightness: target=0, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1), PendingAutoBrightness)
,07-05 14:15:45.946  1380  1380 D StatusBar.NetworkController: onSignalStrengthsChanged signalStrength=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte level=0
07-05 14:15:45.946  1380  1380 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
,07-05 14:15:45.946  2328  2328 D HeadsetPhoneState: Signal level : previous=0 curr=0
,07-05 14:15:45.946  1380  1380 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
,07-05 14:15:45.956   767  1298 D InputReader: Input event(7): value=0 when=820700129000
,07-05 14:15:45.956   767  1298 D InputReader: !@notifyKey(172), action=1
07-05 14:15:45.956   767  1298 D InputManager-JNI: !@interceptKeyBeforeQueueing(172), action=1, interactive=true
,07-05 14:15:45.956   767  1298 D InputManager-JNI: !@handleInterceptActions(172), action=1, wmActions=1
,07-05 14:15:45.956  3576  3576 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@e80471 time:820707
,07-05 14:15:45.956   767  1297 D VoIPInterfaceManager: isVoIPRinging()...
07-05 14:15:45.956   767  1297 D VoIPInterfaceManager: isVoIPRunningAndDeregi()...
07-05 14:15:45.956   767  1297 D VoIPInterfaceManager: Not exist call session
,07-05 14:15:45.966   767  1297 I WindowManager: Ignoring HOME; down is not pressed.
,07-05 14:15:45.966  1380  1380 D StatusBar.NetworkController: onSignalStrengthsChanged signalStrength=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte level=0
07-05 14:15:45.966  1380  1380 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
,07-05 14:15:45.966   767   767 D LightsService: [api] [SvcLED] turnOff:: id = 5 (uid: 1000 pid: 767) 
07-05 14:15:45.966   767   767 D LightsService: [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x40 -> 0x0 | SvcLED(id=5) set Off
07-05 14:15:45.966  1380  1380 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
,07-05 14:15:45.966   767   930 D LightsService: [SvcLED] handleForcedSvcLEDTask()
07-05 14:15:45.966   767   930 D lights  : led_pattern : 0 +
,07-05 14:15:45.966   767   930 D lights  : led_pattern : 0 -
,07-05 14:15:45.966   767   930 D LightsService: [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=5) maintains its priority right
07-05 14:15:45.966   299   299 I rmt_storage: rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb6c8a030
07-05 14:15:45.966   299   299 I rmt_storage: rmt_storage_rw_iovec_cb: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: R/W request received
07-05 14:15:45.966   767   767 D BatteryService: turn off LED
07-05 14:15:45.966   299   299 I rmt_storage: wakelock acquired: 1, error no: 42
07-05 14:15:45.966   299   619 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 Unblock worker thread (th_id: -1229715152)
,07-05 14:15:45.976   767   767 E MotionRecognitionService:   mReceiver.onReceive : ACTION_USER_PRESENT  :: UNLOCK SCREEN
,07-05 14:15:45.976   767   767 W ResourcesManager: getTopLevelResources: /system/app/talkback/talkback.apk / 1.0 running in null rsrc of package null
,07-05 14:15:45.996  1380  1380 D PanelView: screenCapture for lockscreen preview
,07-05 14:15:46.016   767   767 W ResourcesManager: getTopLevelResources: /system/app/talkback/talkback.apk / 1.0 running in null rsrc of package null
,07-05 14:15:46.016   767   767 W ResourcesManager: getTopLevelResources: /system/app/talkback/talkback.apk / 1.0 running in null rsrc of package null
,07-05 14:15:46.016   767   767 W ResourcesManager: getTopLevelResources: /system/app/talkback/talkback.apk / 1.0 running in null rsrc of package null
07-05 14:15:46.016  1653  1653 V UserPresentBroadcastReceiver: Received Intent { act=android.intent.action.USER_PRESENT flg=0x24000010 cmp=com.google.android.gms/.auth.trustagent.UserPresentBroadcastReceiver bqHint=4 }.
,07-05 14:15:46.016   767   767 D UniversalCredentialManagerService: inside mBReciever onReceive : android.intent.action.USER_PRESENT
07-05 14:15:46.016   767  4119 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{ee66ca4 u0 android.intent.action.USER_PRESENT qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{18ebe38 1653:com.google.android.gms.persistent/u0a12}
07-05 14:15:46.016   767   767 D LightsService: [api] [SvcLED] turnOff:: id = 6 (uid: 1000 pid: 767) 
,07-05 14:15:46.016   767   767 D LightsService: [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x0 | SvcLED(id=6) set Off
,07-05 14:15:46.016   767   930 D LightsService: [SvcLED] handleForcedSvcLEDTask()
07-05 14:15:46.016   767   930 D LightsService: [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=5) maintains its priority right
,07-05 14:15:46.016   767   767 D UsbDeviceManager: Keyguard Lock/Unlock
07-05 14:15:46.016   767   767 D UsbDeviceManager: updateUsbNotification : mConnected = true, mConfigured = true, mCurrentFunctions = mtp,adb
,07-05 14:15:46.016   767   767 D UsbDeviceManager: mps exists
,07-05 14:15:46.026   767   767 D SecContentProvider: query(), uri = 18 selection = isUsbMediaPlayerAvailable
,07-05 14:15:46.026   767   767 D UsbDeviceManager: isUsb30Enabled: read '/sys/class/android_usb/android0/bcdUSB', state = 0210
,07-05 14:15:46.026   767   767 D UsbDeviceManager: updateUsbNotification : cancel id = 17040367, title = Transferring media files via USB
,07-05 14:15:46.026   767   767 D UsbDeviceManager: updateUsbNotification : isKeyguardShowingAndNotOccluded = false, isKeyguardSecure = false, mBootCompleted = true
,07-05 14:15:46.036   299   619 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: Bytes written = 1572864
07-05 14:15:46.036   299   619 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: Send response: res=0 err=0
,07-05 14:15:46.036   299   619 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 About to block rmt_storage client thread (th_id: -1229715152) wakelock released: 1, error no: 0
07-05 14:15:46.036   299   619 I rmt_storage: 
,07-05 14:15:46.036   299   299 I rmt_storage: rmt_storage_disconnect_cb: clnt_h=0x0x5 conn_h=0x0xb6c8a030
,07-05 14:15:46.056   767   767 D ApplicationPolicy: isStatusBarNotificationAllowedAsUser: packageName = android,userId = -1
07-05 14:15:46.056   767   767 D UsbDeviceManager: updateUsbNotification : notify id = 17040367, title = Transferring media files via USB
,07-05 14:15:46.056   767   767 I PalmMotion: [PALM] 2014 - SURFACE_MOTION_ENGINE: 1 MOTION_MERGED_MUTE_PAUSE & SURFACE_PALM_TOUCH: 1
07-05 14:15:46.056   767   767 I PalmMotion: [PALM] SURFACE_PALM_SWIPE: 1
07-05 14:15:46.056   767   767 D PalmMotion: [PALM] SETTINGS : [TOUCH: true] [SWEEP: true]
07-05 14:15:46.056   767   767 D PalmMotion: [PALM] ACCEPTED : [default] PALM_CNT : 3, M_TOUCH : 1000.0, M_SWEEP : 100.0, E_SWEEP : 2.0, IGNORE_M_SWEEP : false
,07-05 14:15:46.066  1380  1380 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020629/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020629/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02030b/com.android.systemui:drawable/qs_tile_wifi_signal_4 mWifiActivityIconId=0x7f0205df/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f020605/com.android.systemui:drawable/stat_sys_tether_bluetooth
07-05 14:15:46.066  1380  1380 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
07-05 14:15:46.066  1380  1380 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
07-05 14:15:46.066  1380  1380 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
07-05 14:15:46.066  1380  1380 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-05 14:15:46.076   767  4844 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{ee66ca4 u0 android.intent.action.USER_PRESENT qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{18ebe38 1653:com.google.android.gms.persistent/u0a12}
,07-05 14:15:46.086   767   767 D KnoxTimeoutHandler: handleActiveUserChange [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
,07-05 14:15:46.086   767   767 I KnoxTimeoutHandler: Shared devices show user statefalse
07-05 14:15:46.086   767   767 I KnoxTimeoutHandler: Target Activity is not fullscreen. We will not show this activity0
,07-05 14:15:46.106   767  1826 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{ee66ca4 u0 android.intent.action.USER_PRESENT qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{20b8fa 7371:com.samsung.android.sm/1000}
,07-05 14:15:46.116   767   767 D UniversalCredentialManagerService: ****MSG_LOCK_STATUS_UPDATE block started****
,07-05 14:15:46.126   767   767 D UniversalCredentialManagerService: notifyChangeToPlugin is called for Lock status update...
07-05 14:15:46.126   767   767 D UcmService: notifyChangeToPlugin event 16
07-05 14:15:46.126   767   767 D UcmService: checkCallerPermissionFor is called for method-notifyChangeToPlugin
07-05 14:15:46.126   767   767 I UcmService: checkIfNotify for cs Name = com.sec.smartcard.manager:com.samsung.ucs.agent.baiMobile Package name = com.sec.smartcard.manager
07-05 14:15:46.126   767   767 D UcmService: notifying to unmanaged plugin
,07-05 14:15:46.126   293   549 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 1
07-05 14:15:46.126   767   934 D PowerManagerUtil: Excessive delay in !@display_state: ON: 289ms
07-05 14:15:46.126   293   293 D qdhwcomposer: hwc_setPowerMode: Done setting mode 2 on display 0
07-05 14:15:46.126   767   912 D DisplayPowerController: animateScreenStateChange[0]: target=2
07-05 14:15:46.126   293   293 D libEGL  : eglInitialize EGLDisplay = 0xbe99b364
07-05 14:15:46.126   767   912 D ColorFade: prepare: mode=2
07-05 14:15:46.126  1774  1784 E ucsBai_agentService: notifyChange NOT SUPPORTED
07-05 14:15:46.126   767   912 D ColorFade: ColorFade is already prepared
07-05 14:15:46.126   767   767 D UcmService: agentService com.sec.smartcard.manager:com.samsung.ucs.agent.baiMobile notify status - 0
07-05 14:15:46.126   767   767 D LightsService: [api] [SvcLED] turnOff:: id = 6 (uid: 1000 pid: 767) 
07-05 14:15:46.126   767   767 D UcmService: agentService status-0
07-05 14:15:46.126   767   767 D LightsService: [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x0 | SvcLED(id=6) set Off
07-05 14:15:46.126   767   934 D SurfaceControl: Excessive delay in setPowerMode(): 288ms
07-05 14:15:46.126   767   912 D DisplayPowerState: !@ [0] ColorFade exit
07-05 14:15:46.126   767   767 I UcmService: checkIfNotify for cs Name = com.samsung.ucs.agent.boot:com.samsung.ucs.agent.boot Package name = com.samsung.ucs.agent.boot
07-05 14:15:46.126   767   912 D PowerManagerService: [input device light] onColorFadeExit(true)
07-05 14:15:46.126   767   767 D UcmService: notifying to unmanaged plugin
07-05 14:15:46.126   767   930 D LightsService: [SvcLED] handleForcedSvcLEDTask()
07-05 14:15:46.126   293   548 I qdhwcomposer: getPanelResetStatus: got change event in fb0 with PANEL_ALIVE=0
07-05 14:15:46.126   767   930 D LightsService: [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=5) maintains its priority right
07-05 14:15:46.126  1793  1808 D BootAgentService: notifyChange eventId-16
07-05 14:15:46.126   767   767 D UcmService: agentService com.samsung.ucs.agent.boot:com.samsung.ucs.agent.boot notify status - -1
07-05 14:15:46.126   767   767 D UcmService: agentService status--1
07-05 14:15:46.126   767   767 D UniversalCredentialManagerService: ****MSG_LOCK_STATUS_UPDATE block ended****
07-05 14:15:46.126   767   767 D EdgeLight: Turning off
07-05 14:15:46.126   293   293 D libEGL  : eglInitialize EGLDisplay = 0xbe99b364
,07-05 14:15:46.126   293   293 D libEGL  : eglInitialize EGLDisplay = 0xbe99b364
07-05 14:15:46.126   767   912 D DisplayPowerController: ColorFade: onAnimationStart
07-05 14:15:46.126   767   912 D DisplayPowerController: [Dual Screen Compatible] state[0] :2
07-05 14:15:46.126   767   912 D DisplayPowerController: getFinalBrightness : Summary is 0 -> 0
07-05 14:15:46.126   767   912 D DisplayPowerController: Animating brightness: target=0, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1), PendingAutoBrightness)
07-05 14:15:46.126   767   912 D DisplayPowerController: [Dual Screen Compatible] state[0] :2
,07-05 14:15:46.126   767   912 D DisplayPowerController: getFinalBrightness : Summary is 0 -> 0
07-05 14:15:46.126   767   912 D DisplayPowerController: Animating brightness: target=0, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1), PendingAutoBrightness)
,07-05 14:15:46.136   293   293 W qdhwcomposer: hwc_prepare: panel is in bad state. reset the panel
07-05 14:15:46.136   293   293 D qdhwcomposer: reset_panel: setting power mode off
07-05 14:15:46.136   293   293 D qdhwcomposer: hwc_setPowerMode: Setting mode 0 on display: 0
,07-05 14:15:46.136   767  7655 D MISC PowerHAL: sysfs_write +: /sys/class/input/event1/device/enabled: 1
07-05 14:15:46.136   767  7654 D MISC PowerHAL: sysfs_write +: /sys/class/input/event2/device/enabled: 1
,07-05 14:15:46.136   767   912 D DisplayPowerController: [Dual Screen Compatible] state[0] :2
07-05 14:15:46.136   767   912 D DisplayPowerController: getFinalBrightness : Summary is 0 -> 0
07-05 14:15:46.136   767   912 D DisplayPowerController: Animating brightness: target=0, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1), PendingAutoBrightness)
,07-05 14:15:46.146   767   767 D MARsPolicyManager: NotificationListenerService OngoingNotificationRemoved : android
,07-05 14:15:46.156   767   767 W ResourcesManager: getTopLevelResources: /system/framework/framework-res.apk / 1.0 running in null rsrc of package null
,07-05 14:15:46.156   767   767 D MARsPolicyManager: NotificationListenerService OngoingNotificationPosted : android
,07-05 14:15:46.176   767   767 I CAE     : handleMessage(CaPowerManager.java:188) - AP_WAKEUP
,07-05 14:15:46.176   767   767 I CAE     : updateApPowerStatus(SensorHubParserProvider.java:443) - AP_WAKEUP
07-05 14:15:46.176   767   767 I CAE     : sendCmdToSensorHub(SensorHubCommManager.java:162) - -76, 13, -47, 0,
07-05 14:15:46.176   767   767 D SensorHubManager: SendSensorHubData: send data = -76, 13, -47, 0
,07-05 14:15:46.176   328   564 D Sensorhubs: sendContextData: -76, 13, -47, 0
,07-05 14:15:46.176  1380  1380 D PanelView: kidsfalse mQsExpansionEnabled:true
,07-05 14:15:46.196  1380  1380 D PanelView: kidsfalse mQsExpansionEnabled:true
,07-05 14:15:46.196   767   767 D MotionRecognitionService:   mReceiver.onReceive : ACTION_SCREEN_ON
,07-05 14:15:46.196  1380  1380 D SecKeyguardStatusUtils: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-05 14:15:46.206   767  1244 E MotionRecognitionService:  handler : SCREEN_ON end
,07-05 14:15:46.226   767   767 D UniversalCredentialManagerService: inside mBReciever onReceive : android.intent.action.SCREEN_ON
,07-05 14:15:46.226   767   767 D UniversalCredentialManagerService: ****MSG_LOCK_STATUS_UPDATE block started****
,07-05 14:15:46.226   767   767 D UniversalCredentialManagerService: notifyChangeToPlugin is called for Lock status update...
07-05 14:15:46.226   767   767 D UcmService: notifyChangeToPlugin event 16
07-05 14:15:46.226   767   767 D UcmService: checkCallerPermissionFor is called for method-notifyChangeToPlugin
07-05 14:15:46.226   767   767 I UcmService: checkIfNotify for cs Name = com.sec.smartcard.manager:com.samsung.ucs.agent.baiMobile Package name = com.sec.smartcard.manager
07-05 14:15:46.226   767   767 D UcmService: notifying to unmanaged plugin
,07-05 14:15:46.226  1774  1787 E ucsBai_agentService: notifyChange NOT SUPPORTED
,07-05 14:15:46.226   767   767 D UcmService: agentService com.sec.smartcard.manager:com.samsung.ucs.agent.baiMobile notify status - 0
07-05 14:15:46.226   767   767 D UcmService: agentService status-0
07-05 14:15:46.226   767   767 I UcmService: checkIfNotify for cs Name = com.samsung.ucs.agent.boot:com.samsung.ucs.agent.boot Package name = com.samsung.ucs.agent.boot
07-05 14:15:46.226   767   767 D UcmService: notifying to unmanaged plugin
,07-05 14:15:46.226  1793  1810 D BootAgentService: notifyChange eventId-16
07-05 14:15:46.226   767   767 D UcmService: agentService com.samsung.ucs.agent.boot:com.samsung.ucs.agent.boot notify status - -1
07-05 14:15:46.226   767   767 D UcmService: agentService status--1
07-05 14:15:46.226   767   767 D UniversalCredentialManagerService: ****MSG_LOCK_STATUS_UPDATE block ended****
,07-05 14:15:46.226   767  1361 D AutomaticBrightnessController: [DAB] onSensorChanged : 1st lux : 16.0
07-05 14:15:46.226   767  1361 D AutomaticBrightnessController: [DAB] updateAutoBrightnessSEC : 31(31.0)    0.0 < 16.0 < 39.0 (0.0)
07-05 14:15:46.226   767  1361 D AutomaticBrightnessController: mCallbacks.updateBrightness()
07-05 14:15:46.226   767  1361 D PowerManagerUtil: fileWriteInt to /sys/class/tcon/tcon/auto_br, 1
07-05 14:15:46.236   767   912 D DisplayPowerController: [Dual Screen Compatible] state[0] :2
07-05 14:15:46.236   767   912 D PowerManagerUtil: fileWriteInt to /sys/class/lcd/panel/lux, 16
,07-05 14:15:46.236   767  1361 D PowerManagerUtil: fileWriteInt to /sys/class/backlight/panel/auto_brightness, 2
,07-05 14:15:46.236   767  1361 D PowerManagerUtil: fileWriteInt to /sys/class/mdnie/mdnie/auto_brightness, 2
07-05 14:15:46.236   767   912 D DisplayPowerController: getFinalBrightness : Summary is 31 -> 31
07-05 14:15:46.236   767   912 D DisplayPowerController: Animating brightness: target=31, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
,07-05 14:15:46.236   767   912 D DisplayPowerState: Requesting new screen state: [0] state=ON, backlight (By colorFade)=31
07-05 14:15:46.236   767   912 D DisplayPowerController: [Dual Screen Compatible] state[0] :2
,07-05 14:15:46.236   767   912 D DisplayPowerController: getFinalBrightness : Summary is 31 -> 31
07-05 14:15:46.236   767  1362 D DisplayPowerState: Updating screen state [0]: state=ON, backlight (by ColorFade)=31
07-05 14:15:46.236   767  1362 D lights  : lcd : 31 +
07-05 14:15:46.236   767  1362 D lights  : lcd : 31 -
07-05 14:15:46.236   767   912 D DisplayPowerController: Animating brightness: target=31, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
,07-05 14:15:46.246   767  7654 D MISC PowerHAL: sysfs_write -: /sys/class/input/event2/device/enabled: 1
,07-05 14:15:46.256  1380  1380 D KnoxNotification: ----- inflateViews : modified publicViewLocal -----
,07-05 14:15:46.256   767  1324 D WifiStateMachine: handleScreenStateChanged, screen on, start periodic scan !!!
07-05 14:15:46.256   767  1324 D WifiNative-wlan0: callSECApiBoolean - ID [11]
07-05 14:15:46.256  1556  1556 I wpa_supplicant: STOP_PERIODIC_SCAN command
,07-05 14:15:46.266   767   767 D NotificationService: ACTION_SCREEN_ON
07-05 14:15:46.266   767   767 D LightsService: [api] [SvcLED] turnOff:: id = 6 (uid: 1000 pid: 767) 
07-05 14:15:46.266   767   767 D LightsService: [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x0 | SvcLED(id=6) set Off
07-05 14:15:46.266   767   930 D LightsService: [SvcLED] handleForcedSvcLEDTask()
07-05 14:15:46.266   767   930 D LightsService: [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=5) maintains its priority right
07-05 14:15:46.266   767   767 D EdgeLight: Turning off
,07-05 14:15:46.276   767  1324 E WifiNative-wlan0: do suspend false
,07-05 14:15:46.276  1380  1380 D KnoxNotification: ----- inflateViews : modified KnoxViewLocal -----
,07-05 14:15:46.276   317   936 D audio_hw_primary: adev_set_parameters: enter: screen_state=on
07-05 14:15:46.276   317   936 V voice   : voice_set_parameters: enter: screen_state=on
07-05 14:15:46.276   317   936 V voice   : voice_set_parameters: exit with code(-2)
07-05 14:15:46.276   317   936 V msm8974_platform: platform_set_parameters: enter: screen_state=on
07-05 14:15:46.276   317   936 V msm8974_platform: platform_set_parameters: exit with code(-2)
07-05 14:15:46.276   317   936 D audio_hw_hfp: audio_extn_hfp_set_parameters: enter
07-05 14:15:46.276   317   936 V audio_hw_primary: adev_set_parameters: exit
,07-05 14:15:46.286   767  1324 D WifiStateMachine: analyze kernel wifi wakelock 
07-05 14:15:46.286   767  1324 D WifiStateMachine: file not found /proc/wakelocks
,07-05 14:15:46.286   767   767 V AlarmManager:  remove PendingIntent] PendingIntent{9c0a7fa: PendingIntentRecord{f91e1ab android broadcastIntent}}
,07-05 14:15:46.296  1380  1380 D PanelView: kidsfalse mQsExpansionEnabled:true
,07-05 14:15:46.316  1380  1380 D PanelView: kidsfalse mQsExpansionEnabled:true
,07-05 14:15:46.316   767  1325 V AlarmManager:  remove PendingIntent] PendingIntent{9216008: PendingIntentRecord{ca883a1 android broadcastIntent}}
,07-05 14:15:46.326   767   767 D WifiService: ACTION_SCREEN_ON, checkSensorStatus !!
,07-05 14:15:46.326   767   767 E SContext.CaeProvider: setAttribute() : attribute is null!
,07-05 14:15:46.336   767   767 W CAE     : registerCallback(ContextAwareService.java:144) - [regi 01] Mutex is locked for ACTIVITY_TRACKER
,07-05 14:15:46.336   767   767 V CAE     : start(ContextProvider.java:128)
,07-05 14:15:46.336   767   767 V CAE     : clear(ActivityTrackerRunner.java:108)
07-05 14:15:46.336   767   767 V CAE     : enable(ActivityTrackerRunner.java:84)
,07-05 14:15:46.336   767   767 I CAE     : sendCmdToSensorHub(SensorHubCommManager.java:162) - -79, 26, 0, 0, 0, 0, 0, 0, 0, 0, 12, 15, 46,
07-05 14:15:46.336   767   767 D SensorHubManager: SendSensorHubData: send data = -79, 26, 0, 0, 0, 0, 0, 0, 0, 0, 12, 15, 46
07-05 14:15:46.336   328   328 D Sensorhubs: sendContextData: -79, 26, 0, 0, 0, 0, 0, 0, 0, 0, 12, 15, 46
,07-05 14:15:46.346   767  7655 D MISC PowerHAL: sysfs_write -: /sys/class/input/event1/device/enabled: 1
,07-05 14:15:46.346   767   934 D MISC PowerHAL: sysfs_write +: /sys/class/power_supply/battery/lcd: 1
07-05 14:15:46.346   767   934 D MISC PowerHAL: sysfs_write -: /sys/class/power_supply/battery/lcd: 1
07-05 14:15:46.346   767   934 D PowerManagerService-JNI: Excessive delay in MISC setInteractive(true) while turning screen on: 218ms
,07-05 14:15:46.346   767   934 I QCOM PowerHAL: Got set_interactive hint
,07-05 14:15:46.346   767  1360 D lights  : button : 1 +
,07-05 14:15:46.346   767   767 D CAE     : getFaultDetectionResult(ActivityTrackerRunner.java:154) - true
07-05 14:15:46.356   328   557 D Sensorhubs: readContextData: 1, 1, 26, 1, 2, -95, -100, -108, 0, 0
,07-05 14:15:46.356   767   767 I CAE     : notifyCmdProcessResultObserver(ContextProvider.java:627) - CheckResult = 0, Cause = Success
07-05 14:15:46.356   767   934 D PowerManagerUtil: Excessive delay in nativeSetInteractive(true): 227ms
07-05 14:15:46.356   767  1240 D SensorHubManager: onGetSensorHubDataLocked: library(10) = 1, 1, 26, 1, 2, -95, -100, -108, 0, 0
07-05 14:15:46.356   767   934 D PowerManagerUtil: Excessive delay in DisplayManagerInternal.requestDesiredDisplayState: 518ms
,07-05 14:15:46.356   767  1239 D CAE     : onGetSensorHubData(SensorHubParserProvider.java:92) - onGetSensorHubData Event [event buffer len :10], AP_WAKEUP
07-05 14:15:46.356   767  1239 I CAE     : parse(SensorHubParserProvider.java:188) - buffer size = 10
,07-05 14:15:46.356   767  1239 I CAE     : parse(SensorHubParserProvider.java:199) - 1, 1, 26, 1, 2, -95, -100, -108, 0, 0,
07-05 14:15:46.356   767  1239 D CAE     : display(ContextProvider.java:375) - ================= ACTIVITY_TRACKER =================
,07-05 14:15:46.356   767  1239 I CAE     : display(ContextProvider.java:391) - Accuracy=[0], OperationMode=[0], ActivityType=[0], TimeStamp=[1467720945812]
,07-05 14:15:46.356   767  1242 D SContextService: updateSContext() : event = Activity Tracker
,07-05 14:15:46.366   767   912 D DisplayPowerController: [Dual Screen Compatible] state[0] :2
07-05 14:15:46.366   767   912 D DisplayPowerController: getFinalBrightness : Summary is 31 -> 31
07-05 14:15:46.366   767   912 D DisplayPowerController: Animating brightness: target=31, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
,07-05 14:15:46.366   767   767 D CAE     : doCommendProcess(ContextAwareService.java:433) - complete notify the operation result.
,07-05 14:15:46.376   767   767 I CAE     : displayUsedCountForService(ContextAwareService.java:525) - totalCnt = 1, serviceCount = 1, subCollectionCount = 0
,07-05 14:15:46.376   767   767 D CAE     : showListenerList(ContextAwareService.java:366) - ===== Context Aware Service List =====
07-05 14:15:46.376   767   767 I CAE     : showListenerList(ContextAwareService.java:375) - Listener : com.samsung.android.contextaware.manager.ContextAwareService$Listener@b6149c6, Service : ACTIVITY_TRACKER_CURRENT_INFO(1)
,07-05 14:15:46.376   767   767 I CAE     : showListenerList(ContextAwareService.java:375) - Listener : com.samsung.android.contextaware.manager.ContextAwareService$Listener@b6149c6, Service : ACTIVITY_TRACKER(1)
,07-05 14:15:46.376   767   767 I CAE     : showListenerList(ContextAwareService.java:375) - Listener : com.samsung.android.contextaware.manager.ContextAwareService$Listener@fef2436, Service : AUTO_ROTATION(1)
,07-05 14:15:46.376   293   293 D qdhwcomposer: hwc_setPowerMode: Done setting mode 0 on display 0
07-05 14:15:46.376   293   293 D qdhwcomposer: reset_panel: setting power mode normal and enabling vsync
07-05 14:15:46.376   293   293 D qdhwcomposer: hwc_setPowerMode: Setting mode 2 on display: 0
07-05 14:15:46.376   767   767 W CAE     : registerCallback(ContextAwareService.java:180) - [regi 02] Mutex is unlocked for ACTIVITY_TRACKER
,07-05 14:15:46.376   767   767 D SContextService: 	.registerCallback : 2, client=
07-05 14:15:46.376   767   767 D SContextService: ===== SContext Service List =====
07-05 14:15:46.376   293   549 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
,07-05 14:15:46.376   767   767 D SContextService: Listener : android.hardware.scontext.SContextService$Listener@d9f0f37, Service : Auto Rotation
,07-05 14:15:46.376   767   767 D SContextService: Listener : android.hardware.scontext.SContextService$Listener@708ac3c, Service : Activity Tracker
07-05 14:15:46.376   767   767 D SContextManager:   .registerListener : listener = com.android.server.wifi.WifiServiceImpl$12@85aae2f, service=Activity Tracker
,07-05 14:15:46.386   767   767 W CAE     : getContextInfo(ContextAwareService.java:457) - [getContext 01] Mutex is locked for ACTIVITY_TRACKER_CURRENT_INFO
,07-05 14:15:46.386   767   767 V CAE     : enable(ActivityTrackerCurrentInfoRunner.java:178)
07-05 14:15:46.386   767   767 V CAE     : clear(ActivityTrackerCurrentInfoRunner.java:202)
,07-05 14:15:46.386   767   767 I CAE     : sendCmdToSensorHub(SensorHubCommManager.java:162) - -72, 26, 1, 0,
07-05 14:15:46.386   767   767 D SensorHubManager: SendSensorHubData: send data = -72, 26, 1, 0
07-05 14:15:46.386   328   564 D Sensorhubs: sendContextData: -72, 26, 1, 0
,07-05 14:15:46.386   328   557 D Sensorhubs: readContextData: 1, 3, 26, 1, 1, 2, -95, -100, -67, 0, 0
,07-05 14:15:46.386   767  1240 D SensorHubManager: onGetSensorHubDataLocked: library(11) = 1, 3, 26, 1, 1, 2, -95, -100, -67, 0, 0
07-05 14:15:46.386   767  1239 D CAE     : onGetSensorHubData(SensorHubParserProvider.java:92) - onGetSensorHubData Event [event buffer len :11], AP_WAKEUP
07-05 14:15:46.386   767  1239 I CAE     : parse(SensorHubParserProvider.java:188) - buffer size = 11
07-05 14:15:46.386   767  1239 I CAE     : parse(SensorHubParserProvider.java:199) - 1, 3, 26, 1, 1, 2, -95, -100, -67, 0, 0,
,07-05 14:15:46.386   767  1239 D CAE     : display(ContextProvider.java:375) - ================= ACTIVITY_TRACKER =================
07-05 14:15:46.396   767  1360 D lights  : button : 1 -
07-05 14:15:46.396   767  1239 I CAE     : display(ContextProvider.java:391) - Accuracy=[0], OperationMode=[0], ActivityType=[0], TimeStamp=[1467720945853]
07-05 14:15:46.396   767  1242 D SContextService: updateSContext() : event = Activity Tracker
07-05 14:15:46.396   767   767 D CAE     : getFaultDetectionResult(ActivityTrackerCurrentInfoRunner.java:214) - true
,07-05 14:15:46.396   767   767 I CAE     : notifyCmdProcessResultObserver(ContextProvider.java:627) - CheckResult = 0, Cause = Success
,07-05 14:15:46.406   767   767 W CAE     : getContextInfo(ContextAwareService.java:511) - [getContext 02] Mutex is unlocked for ACTIVITY_TRACKER_CURRENT_INFO
,07-05 14:15:46.406   767   767 D SContextService: requestToUpdate() : service = Activity Tracker
07-05 14:15:46.406   767   767 D SContextManager:   .requestToUpdate : listener = com.android.server.wifi.WifiServiceImpl$12@85aae2f, service=Activity Tracker
,07-05 14:15:46.416  1380  1380 D StatusBar.NetworkController: LTE WIDEBAND with extra : false
,07-05 14:15:46.416   767   767 D WifiService: mActivityTrackerListener: onSContextChanged(): 25
,07-05 14:15:46.416   767   767 D WifiService: ACTIVITY_STATUS_UNKNOWN 
07-05 14:15:46.416   767   767 D WifiService: setWifiScanWithSensor bMove = 0
07-05 14:15:46.416   767   767 D WifiStateMachine: setWifiScanMove bMove = 0
07-05 14:15:46.416   767   767 I WifiStateMachine: not vehicle, sendMessageDelayed CMD_SET_SCAN_MOVE with 0
,07-05 14:15:46.416   767  1324 I WifiStateMachine: DriverStartedState :: CMD_SET_SCAN_MOVE(0) 
07-05 14:15:46.416   767   767 D WifiService: mActivityTrackerListener: onSContextChanged(): 25
07-05 14:15:46.416   767   767 D WifiService: ACTIVITY_STATUS_UNKNOWN 
,07-05 14:15:46.426  1733  2035 I System.out: Broadcast completed: result=0
07-05 14:15:46.426  1556  1556 I wpa_supplicant: @@wpa_supplicant_set_scan_move : set [0]
,07-05 14:15:46.426   767   907 D IpRemoteDisplayController: intent received android.intent.action.SCREEN_ON
,07-05 14:15:46.426   767   907 D IpRemoteDisplayController: Bridge Server is not available
,07-05 14:15:46.426   767  1322 D NetworkPolicy: MSG_SCREEN_ON_CHANGED: 1
07-05 14:15:46.426   767  1322 D NetworkPolicy: isUidForegroundLocked: 10004, mScreenOn: true, uidstate: 2, mProxSensorScreenOff: false
,07-05 14:15:46.426   767  1322 D NetworkPolicy: isUidForegroundLocked: 10175, mScreenOn: true, uidstate: 0, mProxSensorScreenOff: false
,07-05 14:15:46.506  1380  1380 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020629/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020629/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02030b/com.android.systemui:drawable/qs_tile_wifi_signal_4 mWifiActivityIconId=0x7f0205dc/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x7f020605/com.android.systemui:drawable/stat_sys_tether_bluetooth
07-05 14:15:46.506  1380  1380 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-05 14:15:46.516  1380  1380 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-05 14:15:46.516  1380  1380 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
07-05 14:15:46.516  1380  1380 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-05 14:15:46.656   293   548 I qdhwcomposer: getPanelResetStatus: got change event in fb0 with PANEL_ALIVE=0
,07-05 14:15:46.666   293   549 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 1
07-05 14:15:46.666   293   293 D qdhwcomposer: hwc_setPowerMode: Done setting mode 2 on display 0
,07-05 14:15:46.746   328   557 D Sensorhubs: readContextData: 1, 1, 26, 1, 2, -95, -98, 35, 1, 2
,07-05 14:15:46.746   767  1240 D SensorHubManager: onGetSensorHubDataLocked: library(10) = 1, 1, 26, 1, 2, -95, -98, 35, 1, 2
,07-05 14:15:46.756   767  1239 D CAE     : onGetSensorHubData(SensorHubParserProvider.java:92) - onGetSensorHubData Event [event buffer len :10], AP_WAKEUP
07-05 14:15:46.756   767  1239 I CAE     : parse(SensorHubParserProvider.java:188) - buffer size = 10
07-05 14:15:46.756   767  1239 I CAE     : parse(SensorHubParserProvider.java:199) - 1, 1, 26, 1, 2, -95, -98, 35, 1, 2,
,07-05 14:15:46.756   767  1239 D CAE     : display(ContextProvider.java:375) - ================= ACTIVITY_TRACKER =================
07-05 14:15:46.756   767  1239 I CAE     : display(ContextProvider.java:391) - Accuracy=[2], OperationMode=[0], ActivityType=[1], TimeStamp=[1467720946211]
,07-05 14:15:46.756   767  1242 D SContextService: updateSContext() : event = Activity Tracker
07-05 14:15:46.756   767   767 D WifiService: mActivityTrackerListener: onSContextChanged(): 25
07-05 14:15:46.756   767   767 D WifiService: ACTIVITY_STATUS_STATIONARY 
,07-05 14:15:46.786   767   767 D CustomFrequencyManagerService: releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 767  tag : WAKEUP_BOOSTER@35
,07-05 14:15:46.946   767   912 D DisplayPowerController: ColorFade: onAnimationEnd
,07-05 14:15:46.946   767   912 D DisplayPowerController: animateScreenStateChange[0]: target=2
,07-05 14:15:46.966   293   383 D libEGL  : eglTerminate EGLDisplay = 0xb667f64c
,07-05 14:15:46.976   767   912 E libEGL  : call to OpenGL ES API with no current context (logged once per thread)
07-05 14:15:46.976   293  1830 I SurfaceFlinger: id=18 Removed DolorFade (10/10)
07-05 14:15:46.976   293  1364 I SurfaceFlinger: id=18 Removed DolorFade (-2/10)
,07-05 14:15:46.976   767   912 D PowerManagerUtil: Excessive delay in ColorFade : dismiss: 21ms
07-05 14:15:46.976   767   912 D DisplayPowerController: [Dual Screen Compatible] state[0] :2
07-05 14:15:46.976   767   912 D DisplayPowerController: getFinalBrightness : Summary is 31 -> 31
07-05 14:15:46.976   767   912 D DisplayPowerController: Animating brightness: target=31, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
07-05 14:15:46.976   767   912 D DisplayPowerController: [M OS] 0 Notify policy about screen turned on.
07-05 14:15:46.976   767   912 D DisplayPowerController: [M OS] 0 REPORTED_TO_POLICY_SCREEN_TURNING_ON -> REPORTED_TO_POLICY_SCREEN_ON.
07-05 14:15:46.976   767   912 V KeyguardServiceDelegate: onScreenTurnedOn()
07-05 14:15:46.976  1380  2282 D KeyguardViewMediator: notifyScreenTurnedOn
07-05 14:15:46.976   767   912 D PowerManagerService: [s] DisplayPowerCallbacks : onStateChanged()
07-05 14:15:46.976   767   912 D PowerManagerService: mDisplayReady: true
,07-05 14:15:46.976  1380  1380 I PERF    : KeyguardViewMediator - handleNotifyScreenTurnedOn() start
07-05 14:15:46.976  1380  1380 D KeyguardViewMediator: handleNotifyScreenTurnedOn
07-05 14:15:46.976  1380  1380 I PERF    : KeyguardViewMediator - handleNotifyScreenTurnedOn() end
07-05 14:15:46.976   293   293 D libEGL  : eglTerminate EGLDisplay = 0xbe99b3a4
,07-05 14:15:47.516  1380  1380 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020629/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020629/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02030b/com.android.systemui:drawable/qs_tile_wifi_signal_4 mWifiActivityIconId=0x7f0205df/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f020605/com.android.systemui:drawable/stat_sys_tether_bluetooth
07-05 14:15:47.516  1380  1380 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-05 14:15:47.526  1380  1380 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-05 14:15:47.526  1380  1380 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
07-05 14:15:47.526  1380  1380 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-05 14:15:47.846   767  1360 D lights  : button : 0 +
,07-05 14:15:47.896   767  1360 D lights  : button : 0 -
,07-05 14:15:48.086   767  1298 D InputReader: Input event(9): value=1 when=822830608000
,07-05 14:15:48.086   767  1298 D InputReader: Input event(9): value=1 when=822830610000
07-05 14:15:48.086   767  1298 I InputReader: Touch event's action is 0x0 (deviceType=0) [pCnt=1, s=0.0 ] when=822830635000
07-05 14:15:48.086   767  1298 D InputReader: lastThreadEndTime = 820703577192, currentThreadStartTime = 820703582348, diff = 0
07-05 14:15:48.086   767  1297 I InputDispatcher: Delivering touch to (1380): action: 0x4, toolType: 1
,07-05 14:15:48.086   767  1297 I InputDispatcher: Delivering touch to (3576): action: 0x0, toolType: 1
,07-05 14:15:48.086  3576  3576 D ViewRootImpl: ViewPostImeInputStage processPointer 0
,07-05 14:15:48.136   767  1297 E InputTransport: channel 'TouchIntercepter (client)' publisher ~ Received unexpected message of type 2 from consumer
07-05 14:15:48.136   767  1297 E InputDispatcher: channel 'TouchIntercepter (client)' ~ Failed to receive finished signal.  status=-2147483648
07-05 14:15:48.136   767  1297 E InputDispatcher: channel ~ Channel is unrecoverably broken and will be disposed!
,07-05 14:15:48.236   767  1298 D InputReader: Input event(9): value=0 when=822981032000
,07-05 14:15:48.236   767  1298 I InputReader: Touch event's action is 0x1 (deviceType=0) [pCnt=1, s=] when=822981033000
07-05 14:15:48.236   767  1297 I InputDispatcher: Delivering touch to (3576): action: 0x1, toolType: 1
,07-05 14:15:48.236  3576  3576 D ViewRootImpl: ViewPostImeInputStage processPointer 1
,07-05 14:15:48.246   767  1466 D InputDispatcher: Focused application set to: xxxx
,07-05 14:15:48.286   293   373 D libEGL  : eglTerminate EGLDisplay = 0xb694164c
,07-05 14:15:48.286   293   373 D libEGL  : eglTerminate EGLDisplay = 0xb694164c
,07-05 14:15:48.286  3576  3576 D ViewRootImpl: #3 mView = null
,07-05 14:15:48.286   767   868 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=Window{5008e97 u0 d0 com.test.thalitest/com.test.thalitest.MainActivity}
,07-05 14:15:48.296  1380  1380 D PhoneStatusBar: setSystemUiVisibility vis=8600 mask=ffffffff oldVal=8000 newVal=8600 diff=600
,07-05 14:15:48.296   767  1409 D InputDispatcher: Focus left window: 3576
07-05 14:15:48.296   767  1409 D InputDispatcher: Focus entered window: 6924
07-05 14:15:48.296   767   907 D PointerIcon: setMouseIconStyle1 pointerType: 1001 iconType:101 flag:0 pid:767 uid:1000
,07-05 14:15:48.296   767   907 D PointerIcon: setMouseCustomIcon IconType is same.101
07-05 14:15:48.296   767   907 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001 iconType:1 flag:0 pid:767 uid:1000
07-05 14:15:48.296   767   907 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
,07-05 14:15:48.296   767  1764 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,07-05 14:15:48.296   767  1764 W InputMethodManagerService: Window already focused, ignoring focus gain of: com.android.internal.view.IInputMethodClient$Stub$Proxy@3fed31a attribute=null, token = android.os.BinderProxy@5b38516
,07-05 14:15:48.296   767  4844 D ActivityManager: mDVFSHelper.acquire()
,07-05 14:15:48.306   767  4844 D ActivityManager:  Launching com.test.thalitest, updated priority
,07-05 14:15:48.306   767  1764 D InputMethodManagerService: [HARDWARE_KEYBOARD] (refreshImeWindowVis) mImeWindowVis= 0 inputVisible = falsehaveHardKeyboard = false hardKeyShown = false
,07-05 14:15:48.316  6924  6924 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,07-05 14:15:48.316  6924  6924 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: RESUMED
,07-05 14:15:48.346   767   866 V MARsPolicyManager: updatePackagesScore PackageInfo name -- com.test.thalitest
,07-05 14:15:48.346  3576  3576 E ViewRootImpl: sendUserActionEvent() mView == null
07-05 14:15:48.346   767  1409 D ActivityManager: post active user change for 0 fullscreen true isFloatingActivity() false isHomeActivity() false
07-05 14:15:48.346   767  1409 D KnoxTimeoutHandler: postActiveUserChange [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
,07-05 14:15:48.346  6924  6924 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@37d1a28 time:823091
07-05 14:15:48.346   767   767 D KnoxTimeoutHandler: handleActiveUserChange [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
,07-05 14:15:48.346   767   767 I KnoxTimeoutHandler: Shared devices show user statefalse
,07-05 14:15:48.356   293  1364 D libEGL  : eglTerminate EGLDisplay = 0xb49ff64c
,07-05 14:15:48.356  3576  3576 D MTPUSBConnection: on destroy
,07-05 14:15:48.356  3576  3576 D ViewRootImpl: #3 mView = null
,07-05 14:15:48.406   767   778 I art     : Background partial concurrent mark sweep GC freed 87774(8MB) AllocSpace objects, 277(5MB) LOS objects, 27% free, 41MB/57MB, paused 1.525ms total 150.217ms
,07-05 14:15:48.466   767  1679 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 14:15:48.466   767  1679 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4306, temperature: 298, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
07-05 14:15:48.466   767  1679 D BatteryService: online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
07-05 14:15:48.466   767   767 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 14:15:48.466   767   767 I MotionRecognitionService: Plugged
07-05 14:15:48.466   767   767 D MotionRecognitionService:   cableConnection= 1
07-05 14:15:48.466   767   767 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
07-05 14:15:48.466   767   767 D MotionRecognitionService: skip setTransmitPower. 
,07-05 14:15:48.466  1380  1380 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
07-05 14:15:48.466  1380  1380 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,07-05 14:15:48.466  1380  1380 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 14:15:48.466  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:15:48.476  2328  2328 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 14:15:48.476  2328  2834 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-05 14:15:48.476  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:15:48.486  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:15:48.666   767  3520 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,07-05 14:15:48.696   767   862 D GpsLocationProvider: receive broadcast intent, action: android.intent.action.SCREEN_ON
,07-05 14:15:48.706   767   767 D PersonaManagerService: ACTION_SCREEN_ON onReceive
,07-05 14:15:48.706   767   959 D PersonaManagerServiceHandler: MSG_ACTION_SCREEN_ON called
,07-05 14:15:48.706   767  1767 D CoverManagerWhiteLists: isAllowedToUse : SIGNATURE_MATCH
07-05 14:15:48.706  1722  1722 I NfcService: When receiving ACTION_SCREEN_ON, S view cover is already opened. So screenState is ON_UNLOCKED by isKeyguardLocked()
,07-05 14:15:48.706  1722  2201 D NfcService: call the applyRouting
,07-05 14:15:48.716  1380  1380 D StatusBar.NetworkController: onDataActivity: direction=0
,07-05 14:15:48.716  1380  1380 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
,07-05 14:15:48.736   767   767 V AlarmManager:  remove PendingIntent] PendingIntent{e88141: PendingIntentRecord{4f0db38 android broadcastIntent}}
,07-05 14:15:48.736   767   767 V AlarmManager:  remove PendingIntent] PendingIntent{3a706e6: PendingIntentRecord{b1481d1 android broadcastIntent}}
,07-05 14:15:48.736  2328  2328 D BtGatt.GattService: LCD turned on
,07-05 14:15:48.736  2328  2561 D BtGatt.ScanManager: handleLcdOnIntent
07-05 14:15:48.736  2328  2561 D BtGatt.ScanManager: handleLcdOnIntent
07-05 14:15:48.736  2328  2561 D BtGatt.ScanManager: ClientIf = 0
,07-05 14:15:48.736  2105  2105 I SamsungIME: getNextShiftState() cursorCapsMode : 0
,07-05 14:15:48.756  2290  2290 D accuweather: [KK AccuPhone]>>> SWW:66 [0:0] action : androidintentactionSCREEN_ON
,07-05 14:15:48.756  2290  2290 D accuweather: [KK AccuPhone]>>> SWW:479 [0:0] doChangeDayOrNight : 1
07-05 14:15:48.756  2290  2290 D accuweather: [KK AccuPhone]>>> SWW:364 [0:0] getWeatherRenderer : 1
07-05 14:15:48.756  2290  2290 D accuweather: [KK AccuPhone]>>> SWW:496 [0:0] makeClock : 1
07-05 14:15:48.756  2290  2290 D accuweather: [KK AccuPhone]>>> SWW:364 [0:0] getWeatherRenderer : 1
,07-05 14:15:48.756  2290  2290 D accuweather: [KK AccuPhone]>>> SM:1417 [0:0] setClockLayoutContent
,07-05 14:15:48.756  2290  2290 D accuweather: [KK AccuPhone]>>> U:850 [0:0] Locale format : MMM d, y
,07-05 14:15:48.786   767  1359 D PowerManagerService: [PWL] sb release: PowerManagerService.Broadcasts
,07-05 14:15:48.806   767  3520 D SSRM:n  : SIOP:: AP = 310, PST = 301, CUR = 300, LCD = 31
,07-05 14:15:48.806   767  3520 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,07-05 14:15:48.816   767   866 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{e1c3427 u-1 com.samsung.ssrm.SCREEN_ON qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{ababfe3 7595:com.sec.android.daemonapp/u0a182}
,07-05 14:15:48.816   293   383 I SurfaceFlinger: id=22 Removed VSBConnecti (3/9)
,07-05 14:15:48.816   293  1829 I SurfaceFlinger: id=22 Removed VSBConnecti (-2/9)
07-05 14:15:48.816   293   373 I SurfaceFlinger: id=21 Removed VSBConnecti (4/8)
07-05 14:15:48.816   293  1364 I SurfaceFlinger: id=21 Removed VSBConnecti (-2/8)
,07-05 14:15:48.816  1380  1380 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020629/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020629/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02030b/com.android.systemui:drawable/qs_tile_wifi_signal_4 mWifiActivityIconId=0x7f0205df/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f020605/com.android.systemui:drawable/stat_sys_tether_bluetooth
07-05 14:15:48.816  1380  1380 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
07-05 14:15:48.816  1380  1380 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
07-05 14:15:48.816  1380  1380 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
07-05 14:15:48.816  1380  1380 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-05 14:15:48.816  7595  7595 D daemonapp: [MSC_Daemon]>>> WU:262 [0:0] regintype : EUR
,07-05 14:15:48.826  7595  7595 D daemonapp: [MSC_Daemon]>>> WU:303 [0:0] cp type is : cp_eng
07-05 14:15:48.826  7595  7595 D daemonapp: [MSC_Daemon]>>> WCP:1144 [0:0] Provider query : content://apaccuweatherprovider/settings
,07-05 14:15:48.826  7595  7595 D daemonapp: [MSC_Daemon]>>> WCP:1144 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,07-05 14:15:48.826  7595  7595 D daemonapp: [MSC_Daemon]>>> WDSM:41 [0:0] Act : comsamsungssrmSCREEN_ON, run:true
,07-05 14:15:48.826  7595  7595 D comsamsunglog: [MSC_Daemon]>>> ====================================================================================================================
07-05 14:15:48.826  7595  7595 D comsamsunglog: [MSC_Daemon]>>> daemonapp [Version : 1602011514259 ] [ 3 ] 
07-05 14:15:48.826  7595  7595 D comsamsunglog: [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
07-05 14:15:48.826  7595  7595 D comsamsunglog: [MSC_Daemon]>>> ====================================================================================================================
07-05 14:15:48.826  7595  7595 D daemonapp: [MSC_Daemon]>>> WDSM:82 [0:0] c:null, r:3
,07-05 14:15:48.826  7595  7595 D daemonapp: [MSC_Daemon]>>> WDSM:419 [0:0]  ==> Act: SCREEN_ON or COVER_OPEN <==
,07-05 14:15:48.826  7595  7595 D daemonapp: [MSC_Daemon]>>> WCP:1144 [0:0] Provider query : content://apaccuweatherprovider/settings
,07-05 14:15:48.836   293   293 D libEGL  : eglTerminate EGLDisplay = 0xbe99b3a4
,07-05 14:15:48.836   293   293 D libEGL  : eglTerminate EGLDisplay = 0xbe99b3a4
07-05 14:15:48.836  7595  7595 D daemonapp: [MSC_Daemon]>>> WDSM:422 [0:0] [ASO][AUTOREFRESHKEY] --> 3
,07-05 14:15:48.836  7595  7595 D daemonapp: [MSC_Daemon]>>> WDSM:423 [0:0] [ASO][NUT] = 1467741720000
07-05 14:15:48.836  7595  7595 D daemonapp: [MSC_Daemon]>>> WDSM:424 [0:0] [ASO][CT] = 1467720948846
07-05 14:15:48.836  7595  7595 D daemonapp: [MSC_Daemon]>>> WCP:1144 [0:0] Provider query : content://apaccuweatherprovider/packagename
,07-05 14:15:48.836  7595  7595 D daemonapp: [MSC_Daemon]>>> WU:1609 [0:0] PakNme size = 5
,07-05 14:15:48.846  7595  7595 D daemonapp: [MSC_Daemon]>>> WU:262 [0:0] regintype : EUR
,07-05 14:15:48.846  7595  7595 D daemonapp: [MSC_Daemon]>>> WU:303 [0:0] cp type is : cp_eng
07-05 14:15:48.846  7595  7595 D daemonapp: [MSC_Daemon]>>> WU:1613 [0:0] CP Name cp_eng
,07-05 14:15:48.846  7595  7595 D daemonapp: [MSC_Daemon]>>> WCP:1144 [0:0] Provider query : content://apaccuweatherprovider/packagename
,07-05 14:15:48.846  7595  7595 E daemonapp: [MSC_Daemon]>>> WU:1593 [0:0] [NameNotFoundException] !!
,07-05 14:15:48.886   767  7679 I BatteryStatsDumper: In refreshStats isReason Screen ON/OFF: true
,07-05 14:15:48.886   767  7679 D BluetoothAdapter: STATE_ON
,07-05 14:15:48.886  2328  2580 D bt_vendor: op for 7
,07-05 14:15:48.886  2328  2580 D bt_upio : upio_set : pio 0 action 2, polarity 1
,07-05 14:15:48.886  2328  2580 D bt_upio : upio_start_stop_timer : timer_settime success
,07-05 14:15:48.886  2328  2580 D bt_upio : upio_set: proc btwrite assertion, buffer: 1, timer_armed 1 1
,07-05 14:15:48.896   767  1826 V AlarmManager:  remove PendingIntent] PendingIntent{71046d4: PendingIntentRecord{9a0d3b4 com.android.bluetooth broadcastIntent}}
,07-05 14:15:48.926   767  7679 D BatteryStatsImpl: poolsize= 1, curBatteryRealtime= 0, mUpdateTime= 0, mTimeout= 0, mNesting= 0, mTotalTime= 0
,07-05 14:15:48.966   767  7679 D BatteryStatsImpl: poolsize= 1, curBatteryRealtime= 0, mUpdateTime= 0, mTimeout= 0, mNesting= 0, mTotalTime= 0
,07-05 14:15:48.966   767  7679 I BatteryStatsDumper: Previous Battery Level: 100 Current Level: 100 Delta: 0
,07-05 14:15:49.126   767  7679 I BatteryStatsDumper: Writing to database completed
,07-05 14:15:49.346  1447  1447 D Recents : onTaskStackChanged
,07-05 14:15:49.516  1380  1380 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020629/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020629/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02030b/com.android.systemui:drawable/qs_tile_wifi_signal_4 mWifiActivityIconId=0x7f0205da/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f020605/com.android.systemui:drawable/stat_sys_tether_bluetooth
07-05 14:15:49.516  1380  1380 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-05 14:15:49.526  1380  1380 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-05 14:15:49.526  1380  1380 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-05 14:15:49.526  1380  1380 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-05 14:15:49.686  2328  2831 D bt_upio : ..proc_btwrite_timeout..
,07-05 14:15:49.696  2328  2831 D bt_upio : upio_set : pio 0 action 1, polarity 1
,07-05 14:15:50.396  2328  2580 D bt_vendor: op for 7
07-05 14:15:50.396  2328  2580 D bt_upio : upio_set : pio 0 action 1, polarity 1
07-05 14:15:50.396  2328  2580 D bt_upio : BT_WAKE is de-asserted already
,07-05 14:15:50.396   767   785 V AlarmManager:  remove PendingIntent] PendingIntent{37af07d: PendingIntentRecord{9a0d3b4 com.android.bluetooth broadcastIntent}}
,07-05 14:15:51.306   767   866 D ActivityManager: mDVFSHelper.release()
,07-05 14:15:51.306   767   866 D CustomFrequencyManagerService: acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 767  pkgName : ACTIVITY_RESUME_BOOSTER@16
,07-05 14:15:51.606   767   767 D CustomFrequencyManagerService: releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 767  tag : ACTIVITY_RESUME_BOOSTER@16
,07-05 14:15:53.536  1380  1380 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020629/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020629/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02030b/com.android.systemui:drawable/qs_tile_wifi_signal_4 mWifiActivityIconId=0x7f0205df/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f020605/com.android.systemui:drawable/stat_sys_tether_bluetooth
07-05 14:15:53.536  1380  1380 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-05 14:15:53.546  1380  1380 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-05 14:15:53.546  1380  1380 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-05 14:15:53.546  1380  1380 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-05 14:15:54.696   767  3520 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,07-05 14:15:58.546   767  1748 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 14:15:58.546   767  1748 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4381, temperature: 298, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
07-05 14:15:58.546   767  1748 D BatteryService: online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
,07-05 14:15:58.546   767   767 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 14:15:58.556   767   767 I MotionRecognitionService: Plugged
07-05 14:15:58.556   767   767 D MotionRecognitionService:   cableConnection= 1
07-05 14:15:58.556   767   767 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
07-05 14:15:58.556   767   767 D MotionRecognitionService: skip setTransmitPower. 
,07-05 14:15:58.566  1380  1380 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
07-05 14:15:58.566  1380  1380 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
07-05 14:15:58.566  1380  1380 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 14:15:58.566  1380  1380 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020629/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020629/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02030b/com.android.systemui:drawable/qs_tile_wifi_signal_4 mWifiActivityIconId=0x7f0205da/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f020605/com.android.systemui:drawable/stat_sys_tether_bluetooth
07-05 14:15:58.566  1380  1380 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-05 14:15:58.586  2328  2328 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 14:15:58.586  2328  2834 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-05 14:15:58.596  1380  1380 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-05 14:15:58.596  1380  1380 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
07-05 14:15:58.596  1380  1380 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-05 14:15:58.596  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:15:58.606  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:15:58.606  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:15:58.846   767  3520 D SSRM:n  : SIOP:: AP = 310, PST = 302, CUR = 300, LCD = 31
,07-05 14:15:59.586  1380  1380 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020629/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020629/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02030b/com.android.systemui:drawable/qs_tile_wifi_signal_4 mWifiActivityIconId=0x7f0205df/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f020605/com.android.systemui:drawable/stat_sys_tether_bluetooth
,07-05 14:15:59.586  1380  1380 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-05 14:15:59.606  1380  1380 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-05 14:15:59.606  1380  1380 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-05 14:15:59.606  1380  1380 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-05 14:15:59.986   767  1237 V AlarmManager: Expired Alarm result :8
,07-05 14:16:00.006  1380  1380 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
07-05 14:16:00.006  1380  1380 I PERF    : received broadcast android.intent.action.TIME_TICK
,07-05 14:16:00.006  1380  1380 D KeyguardUpdateMonitor: handleTimeUpdate
,07-05 14:16:00.026  1380  1380 D SecKeyguardClockView: onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,07-05 14:16:00.036  1380  1380 D SecKeyguardClockView: HomeTimezone(): 1
,07-05 14:16:00.046  1380  1380 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-05 14:16:00.046  1380  1380 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-05 14:16:00.046  1380  1380 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-05 14:16:00.046  1380  1380 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-05 14:16:00.056  1380  1380 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-05 14:16:00.056  1380  1380 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-05 14:16:00.056  1380  1380 D SecKeyguardStatusUtils: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-05 14:16:00.106  1380  1380 D SecKeyguardStatusUtils: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-05 14:16:02.616  1380  1380 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020629/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020629/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02030b/com.android.systemui:drawable/qs_tile_wifi_signal_4 mWifiActivityIconId=0x7f0205da/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f020605/com.android.systemui:drawable/stat_sys_tether_bluetooth
,07-05 14:16:02.616  1380  1380 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-05 14:16:02.626  1380  1380 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-05 14:16:02.626  1380  1380 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-05 14:16:02.626  1380  1380 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-05 14:16:03.626  1380  1380 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020629/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020629/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02030b/com.android.systemui:drawable/qs_tile_wifi_signal_4 mWifiActivityIconId=0x7f0205df/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f020605/com.android.systemui:drawable/stat_sys_tether_bluetooth
07-05 14:16:03.626  1380  1380 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-05 14:16:03.636  1380  1380 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-05 14:16:03.636  1380  1380 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-05 14:16:03.636  1380  1380 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-05 14:16:06.566   767  1604 E Watchdog: !@Sync 27 [07-05 14:16:06.579]
,07-05 14:16:07.656  1380  1380 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020629/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020629/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02030b/com.android.systemui:drawable/qs_tile_wifi_signal_4 mWifiActivityIconId=0x7f0205da/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f020605/com.android.systemui:drawable/stat_sys_tether_bluetooth
,07-05 14:16:07.656  1380  1380 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-05 14:16:07.656  1380  1380 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-05 14:16:07.666  1380  1380 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-05 14:16:07.666  1380  1380 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-05 14:16:08.636   767  1811 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 14:16:08.676  1380  1380 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020629/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020629/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02030b/com.android.systemui:drawable/qs_tile_wifi_signal_4 mWifiActivityIconId=0x7f0205df/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f020605/com.android.systemui:drawable/stat_sys_tether_bluetooth
07-05 14:16:08.676  1380  1380 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-05 14:16:08.676  1380  1380 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
07-05 14:16:08.676  1380  1380 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-05 14:16:08.686  1380  1380 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false),
,07-05 14:16:08.906   767  3520 D SSRM:n  : SIOP:: AP = 300, PST = 302, CUR = 300, LCD = 31
,07-05 14:16:10.696  1380  1380 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020629/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020629/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02030b/com.android.systemui:drawable/qs_tile_wifi_signal_4 mWifiActivityIconId=0x7f0205da/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f020605/com.android.systemui:drawable/stat_sys_tether_bluetooth
07-05 14:16:10.696  1380  1380 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-05 14:16:10.696  1380  1380 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-05 14:16:10.696  1380  1380 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-05 14:16:10.696  1380  1380 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-05 14:16:12.086   767   912 D PowerManagerService: [s] UserActivityState : 1 -> 2
,07-05 14:16:12.086   767   912 D PowerManagerService: mDisplayReady: false
07-05 14:16:12.086   767   912 D DisplayPowerController: animateScreenStateChange[0]: target=2
,07-05 14:16:12.086   767   912 D DisplayPowerController: [Dual Screen Compatible] state[0] :2
07-05 14:16:12.086   767   912 D DisplayPowerController: getFinalBrightness : Summary is 15 -> 15
,07-05 14:16:12.086   767   912 D DisplayPowerController: Animating brightness: target=15, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
,07-05 14:16:12.096   767   912 D PowerManagerService: [s] DisplayPowerCallbacks : onStateChanged()
07-05 14:16:12.096   767   912 D PowerManagerService: mDisplayReady: true
,07-05 14:16:12.096   767  1362 D lights  : lcd : 30 +
,07-05 14:16:12.106   767  1362 D lights  : lcd : 30 -
,07-05 14:16:12.116   767  1362 D lights  : lcd : 21 +
,07-05 14:16:12.116   767   912 D DisplayPowerController: animateScreenStateChange[0]: target=2
07-05 14:16:12.116   767   912 D DisplayPowerController: [Dual Screen Compatible] state[0] :2
,07-05 14:16:12.116   767   912 D DisplayPowerController: getFinalBrightness : Summary is 15 -> 15
07-05 14:16:12.116   767   912 D DisplayPowerController: Animating brightness: target=15, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
,07-05 14:16:12.126   767  1362 D lights  : lcd : 21 -
,07-05 14:16:12.126   767   912 D DisplayPowerController: animateScreenStateChange[0]: target=2
07-05 14:16:12.126   767   912 D DisplayPowerController: [Dual Screen Compatible] state[0] :2
07-05 14:16:12.126   767   912 D DisplayPowerController: getFinalBrightness : Summary is 15 -> 15
07-05 14:16:12.126   767   912 D DisplayPowerController: Animating brightness: target=15, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
,07-05 14:16:12.126   767   912 D DisplayPowerController: animateScreenStateChange[0]: target=2
,07-05 14:16:12.126   767   912 D DisplayPowerController: [Dual Screen Compatible] state[0] :2
07-05 14:16:12.126   767   912 D DisplayPowerController: getFinalBrightness : Summary is 15 -> 15
,07-05 14:16:12.126   767   912 D DisplayPowerController: Animating brightness: target=15, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
,07-05 14:16:12.126   767  1362 D lights  : lcd : 15 +
,07-05 14:16:12.136   767  1362 D lights  : lcd : 15 -
,07-05 14:16:12.136   767   912 D DisplayPowerController: animateScreenStateChange[0]: target=2
,07-05 14:16:12.136   767   912 D DisplayPowerController: [Dual Screen Compatible] state[0] :2
07-05 14:16:12.136   767   912 D DisplayPowerController: getFinalBrightness : Summary is 15 -> 15
07-05 14:16:12.136   767   912 D DisplayPowerController: Animating brightness: target=15, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
,07-05 14:16:14.726  1380  1380 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020629/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020629/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02030b/com.android.systemui:drawable/qs_tile_wifi_signal_4 mWifiActivityIconId=0x7f0205df/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f020605/com.android.systemui:drawable/stat_sys_tether_bluetooth
,07-05 14:16:14.726  1380  1380 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-05 14:16:14.726  1380  1380 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-05 14:16:14.736  1380  1380 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-05 14:16:14.736  1380  1380 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-05 14:16:16.746  1380  1380 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020629/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020629/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02030b/com.android.systemui:drawable/qs_tile_wifi_signal_4 mWifiActivityIconId=0x7f0205da/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f020605/com.android.systemui:drawable/stat_sys_tether_bluetooth
,07-05 14:16:16.746  1380  1380 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-05 14:16:16.756  1380  1380 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-05 14:16:16.756  1380  1380 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-05 14:16:16.756  1380  1380 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-05 14:16:17.766  1380  1380 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020629/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020629/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02030b/com.android.systemui:drawable/qs_tile_wifi_signal_4 mWifiActivityIconId=0x7f0205df/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f020605/com.android.systemui:drawable/stat_sys_tether_bluetooth
,07-05 14:16:17.766  1380  1380 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-05 14:16:17.766  1380  1380 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-05 14:16:17.766  1380  1380 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
07-05 14:16:17.776  1380  1380 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-05 14:16:18.086   767   912 D PowerManagerService: [s] UserActivityState : 2 -> 4
07-05 14:16:18.086   767   912 I PowerManagerService: Nap time (uid 1000)...
,07-05 14:16:18.086   767   912 D PowerManagerService: handleSandman : startDreaming: false  (canDreamLocked: false  canDozeLocked: false)
07-05 14:16:18.086   767   912 I PowerManagerService: !@[ps] Screen__Off - 1 :  dream(timeout) (2)
,07-05 14:16:18.086   767   912 I PowerManagerService: Going to sleep due to screen timeout (uid 1000)...
07-05 14:16:18.086   767   912 D InputManager-JNI: setInteractive(false)
07-05 14:16:18.086   767  1359 D NetworkPolicy: onScreenStateChanged, state: false, reason: 3
,07-05 14:16:18.096   767   912 D PowerManagerService: mDisplayReady: false
,07-05 14:16:18.096   767   912 D DisplayPowerController: animateScreenStateChange[0]: target=1
07-05 14:16:18.096   767   912 D ColorFade: prepare: mode=4
,07-05 14:16:18.096   293   293 I SurfaceFlinger: id=23 createSurf (1080x1920),2 flag=404, DolorFade
,07-05 14:16:18.106  6924  6924 D cr_Ime  : [ImeAdapter.java:140] onCreateInputConnection returns null.
,07-05 14:16:18.106  1380  2282 I PERF    : KeyguardViewMediator - onStartedGoingToSleep() start
07-05 14:16:18.106  1380  2282 D KeyguardViewMediator: onStartedGoingToSleep(3)
,07-05 14:16:18.106   767   912 D PowerManagerUtil: Excessive delay in ColorFade : createSurface: 12ms
,07-05 14:16:18.116  1380  2282 D KeyguardViewMediator: timeout : 5000
,07-05 14:16:18.136  1380  2282 D KeyguardViewMediator: setting alarm to turn off keyguard, seq = 2
,07-05 14:16:18.136  1380  2282 I PERF    : KeyguardViewMediator - onStartedGoingToSleep() end
,07-05 14:16:18.136   767   912 D libEGL  : eglInitialize EGLDisplay = 0x9ab520cc
,07-05 14:16:18.146   767   912 D libEGL  : eglTerminate EGLDisplay = 0x9ab521d4
,07-05 14:16:18.156   767   912 D ColorFade: ColorFade is ready
,07-05 14:16:18.156   767   912 D DisplayPowerController: ColorFade: onAnimationStart
07-05 14:16:18.156   767   912 D DisplayPowerController: [Dual Screen Compatible] state[0] :2
07-05 14:16:18.156   767   912 D DisplayPowerController: getFinalBrightness : Summary is 31 -> 31
,07-05 14:16:18.176   293   293 D libEGL  : eglInitialize EGLDisplay = 0xbe99b364
,07-05 14:16:18.196   293   293 D libEGL  : eglInitialize EGLDisplay = 0xbe99b364
,07-05 14:16:18.446   767   912 D DisplayPowerState: !@ [0] ColorFade entry
07-05 14:16:18.446   767   912 D PowerManagerService: [input device light] onColorFadeExit(false)
,07-05 14:16:18.446   767   912 D DisplayPowerController: ColorFade: onAnimationEnd
,07-05 14:16:18.456   767  1362 D lights  : lcd : 0 +
,07-05 14:16:18.456   767   912 D DisplayPowerController: animateScreenStateChange[0]: target=1
07-05 14:16:18.456   767   912 D DisplayPowerController: [M OS] 0 REPORTED_TO_POLICY_SCREEN_* -> REPORTED_TO_POLICY_SCREEN_OFF.
,07-05 14:16:18.466   767  1362 D lights  : lcd : 0 -
,07-05 14:16:18.506  6924  6924 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,07-05 14:16:18.506  6924  6924 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,07-05 14:16:18.596   767   912 D SContextService: unregisterCallback() : Listener = android.hardware.scontext.SContextService$Listener@d9f0f37, Service = Auto Rotation, used = 0
,07-05 14:16:18.596   767  1322 D NetworkPolicy: isUidForegroundLocked: 10004, mScreenOn: true, uidstate: 5, mProxSensorScreenOff: false
07-05 14:16:18.596   767   912 W CAE     : unregisterCallback(ContextAwareService.java:206) - [unregi 01] Mutex is locked for AUTO_ROTATION
,07-05 14:16:18.596   767   912 V CAE     : stop(ContextProvider.java:155)
,07-05 14:16:18.596  6924  6924 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@5921e0e Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@269b030, 16908290=android.view.AbsSavedState$1@269b030}, android:focusedViewId=100}]}]
,07-05 14:16:18.596   767   912 V CAE     : clear(AutoRotationRunner.java:182)
,07-05 14:16:18.596   767   912 V CAE     : disable(AutoRotationRunner.java:171)
07-05 14:16:18.596   767   912 I CAE     : sendCmdToSensorHub(SensorHubCommManager.java:162) - -78, 7, 0, 0,
07-05 14:16:18.596   767   912 D SensorHubManager: SendSensorHubData: send data = -78, 7, 0, 0
,07-05 14:16:18.596   328   328 D Sensorhubs: sendContextData: -78, 7, 0, 0
07-05 14:16:18.596  6924  6924 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
07-05 14:16:18.606  6924  6924 V ActivityThread: updateVisibility : ActivityRecord{1e1ddc3 token=android.os.BinderProxy@37d1a28 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,07-05 14:16:18.606  6924  6924 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,07-05 14:16:18.606  6924  6924 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
,07-05 14:16:18.606   767   912 D CAE     : getFaultDetectionResult(AutoRotationRunner.java:195) - true
,07-05 14:16:18.606   767   912 I CAE     : notifyCmdProcessResultObserver(ContextProvider.java:627) - CheckResult = 0, Cause = Success
,07-05 14:16:18.626   767   912 D CAE     : doCommendProcess(ContextAwareService.java:433) - complete notify the operation result.
,07-05 14:16:18.626   767   912 I CAE     : displayUsedCountForService(ContextAwareService.java:525) - totalCnt = 0, serviceCount = 0, subCollectionCount = 0
,07-05 14:16:18.626   767   912 D CAE     : showListenerList(ContextAwareService.java:366) - ===== Context Aware Service List =====
07-05 14:16:18.626   767   912 I CAE     : showListenerList(ContextAwareService.java:375) - Listener : com.samsung.android.contextaware.manager.ContextAwareService$Listener@b6149c6, Service : ACTIVITY_TRACKER_CURRENT_INFO(1)
,07-05 14:16:18.626   767   912 I CAE     : showListenerList(ContextAwareService.java:375) - Listener : com.samsung.android.contextaware.manager.ContextAwareService$Listener@b6149c6, Service : ACTIVITY_TRACKER(1)
,07-05 14:16:18.626   767   912 W CAE     : unregisterCallback(ContextAwareService.java:241) - [unregi 02] Mutex is unlocked for AUTO_ROTATION
07-05 14:16:18.626   767   912 D SContextService: 	.unregisterCallback : 2, client=
07-05 14:16:18.626   767   912 D SContextService: ===== SContext Service List =====
07-05 14:16:18.626   767   912 D SContextService: Listener : android.hardware.scontext.SContextService$Listener@708ac3c, Service : Activity Tracker
07-05 14:16:18.626   767   912 D SContextManager:   .unregisterListener : listener = com.android.server.policy.WindowOrientationListener$OrientationSensorJudge@1809fbb, service=Auto Rotation
,07-05 14:16:18.626   767   912 V KeyguardServiceDelegate: onScreenTurnedOff()
07-05 14:16:18.626  1380  2112 D KeyguardViewMediator: notifyScreenTurnedOff
,07-05 14:16:18.626  1380  1380 I PERF    : KeyguardViewMediator - handleNotifyScreenTurnedOff() start
07-05 14:16:18.626  1380  1380 D KeyguardViewMediator: handleNotifyScreenTurnedOff
07-05 14:16:18.626  1380  1380 I PERF    : KeyguardViewMediator - handleNotifyScreenTurnedOff() end
,07-05 14:16:18.636   767   912 D DisplayPowerController: mWindowManagerPolicy.screenTurnedOff(0)
07-05 14:16:18.636   767   912 D DisplayPowerController: [Dual Screen Compatible] state[0] :1
,07-05 14:16:18.636   767  1361 D AutomaticBrightnessController: [DAB] setLightSensorEnabled : unregisterListenerRunnable
,07-05 14:16:18.636   767  1361 E LightSensor: Light old sensor_state 513, new sensor_state : 1 en : 0
,07-05 14:16:18.636   767   912 D PowerManagerUtil: fileWriteInt to /sys/class/tcon/tcon/auto_br, 0
,07-05 14:16:18.636   767   912 D PowerManagerUtil: fileWriteInt to /sys/class/backlight/panel/auto_brightness, 0
,07-05 14:16:18.646   767  1361 D SensorManager: unregisterListener ::   
,07-05 14:16:18.646   767  1361 E Sensors : Acc old sensor_state 1, new sensor_state : 0 en : 0
,07-05 14:16:18.656   767   912 D PowerManagerUtil: fileWriteInt to /sys/class/mdnie/mdnie/auto_brightness, 0
,07-05 14:16:18.656   767  1361 D SensorManager: unregisterListener ::   
07-05 14:16:18.656   767   912 D AutomaticBrightnessController: [DAB] no lux value from sensor manager
07-05 14:16:18.656   767  1361 D PowerManagerUtil: Excessive delay in setLightSensorEnabled::unregisterListener done: 24ms
07-05 14:16:18.656   767   912 D DisplayPowerController: getFinalBrightness : Summary is 0 -> 0
07-05 14:16:18.656   767   912 D DisplayPowerController: Animating brightness: target=0, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
07-05 14:16:18.656   767   912 D DisplayPowerController: animateScreenStateChange[0]: target=1
07-05 14:16:18.656   767   912 D DisplayPowerController: [Dual Screen Compatible] state[0] :1
07-05 14:16:18.656   767   912 D DisplayPowerController: getFinalBrightness : Summary is 0 -> 0
07-05 14:16:18.656   767   912 D DisplayPowerController: Animating brightness: target=0, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
,07-05 14:16:18.656   767  7719 D MISC PowerHAL: sysfs_write +: /sys/class/input/event2/device/enabled: 0
07-05 14:16:18.656   767  1298 D InputReader: Input event(9): value=0 when=853407164000
,07-05 14:16:18.656   767  7719 D MISC PowerHAL: sysfs_write -: /sys/class/input/event2/device/enabled: 0
,07-05 14:16:18.656   767  7720 D MISC PowerHAL: sysfs_write +: /sys/class/input/event1/device/enabled: 0
,07-05 14:16:18.666   767  7720 D MISC PowerHAL: sysfs_write -: /sys/class/input/event1/device/enabled: 0
,07-05 14:16:18.666   767   934 D MISC PowerHAL: sysfs_write +: /sys/class/power_supply/battery/lcd: 0
07-05 14:16:18.666   767   934 D MISC PowerHAL: sysfs_write -: /sys/class/power_supply/battery/lcd: 0
07-05 14:16:18.666   767   934 I QCOM PowerHAL: Got set_interactive hint
,07-05 14:16:18.666   767   934 D DisplayManagerService: !@display_state: ON -> OFF brightness: 0 -> 0
07-05 14:16:18.666   767   907 I DisplayManagerService: Display device changed state: "Built-in Screen", OFF
,07-05 14:16:18.666   293   293 D SurfaceFlinger: Set power mode=0, type=0 flinger=0xb6a64000
07-05 14:16:18.666   293   293 D qdhwcomposer: hwc_setPowerMode: Setting mode 0 on display: 0
,07-05 14:16:18.706   767   778 I art     : Background partial concurrent mark sweep GC freed 46568(3MB) AllocSpace objects, 23(696KB) LOS objects, 27% free, 41MB/57MB, paused 2.963ms total 213.238ms
,07-05 14:16:18.916   293   293 D qdhwcomposer: hwc_setPowerMode: Done setting mode 0 on display 0
,07-05 14:16:18.916   767   934 D SurfaceControl: Excessive delay in setPowerMode(): 248ms
07-05 14:16:18.916   767   934 D PowerManagerUtil: Excessive delay in !@display_state: OFF: 249ms
07-05 14:16:18.916   767   934 I libsuspend: !@autosuspend_wakeup_count_enable
07-05 14:16:18.916   767   912 D DisplayPowerController: animateScreenStateChange[0]: target=1
07-05 14:16:18.916   767   934 I libsuspend: !@autosuspend_wakeup_count_enable done
07-05 14:16:18.916   767   912 D DisplayPowerController: [Dual Screen Compatible] state[0] :1
07-05 14:16:18.916   767   912 D DisplayPowerController: getFinalBrightness : Summary is 0 -> 0
07-05 14:16:18.916   767  1359 D PersonaManagerService: onfinishedGoingToSleep why = 3
07-05 14:16:18.916   767   912 D DisplayPowerController: Animating brightness: target=0, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
07-05 14:16:18.916   767   912 D DisplayPowerController: animateScreenStateChange[0]: target=1
07-05 14:16:18.916  1380  1395 D KeyguardViewMediator: onFinishedGoingToSleep(3)
07-05 14:16:18.916   767   912 D DisplayPowerController: [Dual Screen Compatible] state[0] :1
07-05 14:16:18.916  1380  1395 D KeyguardViewMediator: onFinishedGoingToSleep: mPendingLock false
07-05 14:16:18.916   767   912 D DisplayPowerController: getFinalBrightness : Summary is 0 -> 0
07-05 14:16:18.916  1380  1395 D KeyguardViewMediator: notifyFinishedGoingToSleep
,07-05 14:16:18.916   767   912 D DisplayPowerController: Animating brightness: target=0, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1))
07-05 14:16:18.916  1380  1380 I PERF    : KeyguardViewMediator - handleNotifyFinishedGoingToSleep() start
07-05 14:16:18.916   767   934 D PowerManagerUtil: Excessive delay in DisplayManagerInternal.requestDesiredDisplayState: 260ms
07-05 14:16:18.916  1380  1380 D KeyguardViewMediator: handleNotifyFinishedGoingToSleep
,07-05 14:16:18.916   767   912 D PowerManagerService: [s] DisplayPowerCallbacks : onStateChanged()
07-05 14:16:18.916  1380  1380 I PERF    : KeyguardViewMediator - handleNotifyFinishedGoingToSleep() end
07-05 14:16:18.916   767   912 D PowerManagerService: mDisplayReady: true
,07-05 14:16:18.916   767   959 D PersonaManagerServiceHandler: MSG_ACTION_SCREEN_OFF called
07-05 14:16:18.916   767   912 D PowerManagerService: [PWL] sb release: PowerManagerService.Display
07-05 14:16:18.916   767   912 I PowerManagerService: [PWL] Off : 0s ago
,07-05 14:16:18.926   293   549 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
07-05 14:16:18.916   767   912 D PowerManagerService: handleSandman : startDreaming: true  (canDreamLocked: false  canDozeLocked: true)
07-05 14:16:18.926  1380  1380 D SecKeyguardClockSingleView: onScreenTurnedOff
,07-05 14:16:18.916   767   912 D PowerManagerService: handleSandman : startDream(true)
07-05 14:16:18.926  1380  1380 I PERF    : KeyguardUpdateMonitor - cb.onScreenTurnedOff() end
,07-05 14:16:18.916   767   912 E PowerManagerService: handleSandman : startDreaming, but isDreaming false
07-05 14:16:18.926   767   767 D SensorService: SensorEventConnection::SocketBufferSize, SystemSocketBufferSize - 102400, 2097152
,07-05 14:16:18.916   767   912 I PowerManagerService: Sleeping (uid 1000)...
07-05 14:16:18.926   767   767 E LightSensor: Light old sensor_state 0, new sensor_state : 512 en : 1,
07-05 14:16:18.916   767   912 D PowerManagerService: [s] UserActivityState : 4 -> 0
,07-05 14:16:18.916   767   912 D PowerManagerService: [PWL] sb acquire: PowerManagerService.Broadcasts
07-05 14:16:18.926   767   767 D LightsService: [api] [SvcLED] setFlashing :: id = 5, color = 0, mode = 14, onMS = 0, offMS = 0,  (uid: 1000 pid: 767) 
,07-05 14:16:18.926   767   767 D LightsService: [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x40 | SvcLED(id=5) set On
,07-05 14:16:18.936   767   767 D SensorManager: registerListener :: 6, TMG399X RGB Sensor, 200000, 0,  
07-05 14:16:18.936   767   767 D BatteryService: turn on LED for fully charged
,07-05 14:16:18.956   767   767 I CAE     : handleMessage(CaPowerManager.java:182) - AP_SLEEP
07-05 14:16:18.956   767   767 I CAE     : updateApPowerStatus(SensorHubParserProvider.java:443) - AP_SLEEP
,07-05 14:16:18.956   767   767 I CAE     : sendCmdToSensorHub(SensorHubCommManager.java:162) - -76, 13, -46, 0,
07-05 14:16:18.956   767   767 D SensorHubManager: SendSensorHubData: send data = -76, 13, -46, 0
07-05 14:16:18.956   328   564 D Sensorhubs: sendContextData: -76, 13, -46, 0
,07-05 14:16:18.956   767  3520 D SSRM:n  : SIOP:: AP = 300, PST = 302, CUR = 300, LCD = 0
,07-05 14:16:18.956   767   767 I CAE     : sendCmdToSensorHub(SensorHubCommManager.java:162) - -63, 14, 12, 16, 18,
07-05 14:16:18.956   767   767 D SensorHubManager: SendSensorHubData: send data = -63, 14, 12, 16, 18
,07-05 14:16:18.956   328   328 D Sensorhubs: sendContextData: -63, 14, 12, 16, 18
,07-05 14:16:18.966   767   767 D MotionRecognitionService:   mReceiver.onReceive : ACTION_SCREEN_OFF
,07-05 14:16:18.966   767  1244 D MotionRecognitionService: Screen off setAccIntStatus 
07-05 14:16:18.966   767  1244 E MotionRecognitionService:  handler : SCREEN_OFF end 
,07-05 14:16:18.976   767   866 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{ed9811f u-1 com.samsung.settings.action.directaccess.CLOSE_DIALOG qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{a8288e1 4986:com.android.settings/1000}
,07-05 14:16:18.986   767   767 D UniversalCredentialManagerService: inside mBReciever onReceive : android.intent.action.SCREEN_OFF
,07-05 14:16:18.986   767   767 D UniversalCredentialManagerService: ****MSG_LOCK_STATUS_UPDATE block started****
,07-05 14:16:18.986   767   767 D UniversalCredentialManagerService: notifyChangeToPlugin is called for Lock status update...
07-05 14:16:18.986   767   767 D UcmService: notifyChangeToPlugin event 16
07-05 14:16:18.986   767   767 D UcmService: checkCallerPermissionFor is called for method-notifyChangeToPlugin
07-05 14:16:18.986   767   767 I UcmService: checkIfNotify for cs Name = com.sec.smartcard.manager:com.samsung.ucs.agent.baiMobile Package name = com.sec.smartcard.manager
07-05 14:16:18.986   767   767 D UcmService: notifying to unmanaged plugin
07-05 14:16:18.986  1774  1784 E ucsBai_agentService: notifyChange NOT SUPPORTED
,07-05 14:16:18.986   767   767 D UcmService: agentService com.sec.smartcard.manager:com.samsung.ucs.agent.baiMobile notify status - 0
07-05 14:16:18.986   767   767 D UcmService: agentService status-0
07-05 14:16:18.996   767   767 I UcmService: checkIfNotify for cs Name = com.samsung.ucs.agent.boot:com.samsung.ucs.agent.boot Package name = com.samsung.ucs.agent.boot
07-05 14:16:18.996   767   767 D UcmService: notifying to unmanaged plugin
,07-05 14:16:18.996  1793  1808 D BootAgentService: notifyChange eventId-16
07-05 14:16:18.996   767   767 D UcmService: agentService com.samsung.ucs.agent.boot:com.samsung.ucs.agent.boot notify status - -1
,07-05 14:16:18.996   767   767 D UcmService: agentService status--1
07-05 14:16:18.996   767   767 D UniversalCredentialManagerService: ****MSG_LOCK_STATUS_UPDATE block ended****
,07-05 14:16:19.006   767  1324 D WifiStateMachine: handleScreenStateChanged, screen off, set scan interval as max value  !!!
07-05 14:16:19.006   767  1324 D WifiNative-wlan0: callSECApiVoid - ID [19]
,07-05 14:16:19.006  1556  1556 I wpa_supplicant: set PERIODIC_SCAN_INTERVAL_MAX to 128sec !!!
,07-05 14:16:19.006   767   767 D NotificationService: ACTION_SCREEN_OFF
07-05 14:16:19.006   767   767 D LightsService: [api] [SvcLED] turnOff:: id = 6 (uid: 1000 pid: 767) 
07-05 14:16:19.006   767   767 D LightsService: [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x40 -> 0x40 | SvcLED(id=6) set Off
07-05 14:16:19.006   767   767 D EdgeLight: Turning off
,07-05 14:16:19.006   767  1324 E WifiNative-wlan0: do suspend true
,07-05 14:16:19.006   317   923 D audio_hw_primary: adev_set_parameters: enter: screen_state=off
07-05 14:16:19.006   317   923 V voice   : voice_set_parameters: enter: screen_state=off
07-05 14:16:19.006   317   923 V voice   : voice_set_parameters: exit with code(-2)
07-05 14:16:19.006   317   923 V msm8974_platform: platform_set_parameters: enter: screen_state=off
07-05 14:16:19.006   317   923 V msm8974_platform: platform_set_parameters: exit with code(-2)
07-05 14:16:19.006   317   923 D audio_hw_hfp: audio_extn_hfp_set_parameters: enter
07-05 14:16:19.006   317   923 V audio_hw_primary: adev_set_parameters: exit
,07-05 14:16:19.036   767   767 I FingerprintService: onReceive: android.intent.action.SCREEN_OFF
,07-05 14:16:19.046   767   767 I BackgroundCompactionService: Schedule Type1 BGCompaction
,07-05 14:16:19.056   767   767 D WifiService: ACTION_SCREEN_OFF, mSContextManager.unregisterListener !!
,07-05 14:16:19.056   767   767 D SContextService: unregisterCallback() : Listener = android.hardware.scontext.SContextService$Listener@708ac3c, Service = Activity Tracker, used = 0
,07-05 14:16:19.056   767   767 W CAE     : unregisterCallback(ContextAwareService.java:206) - [unregi 01] Mutex is locked for ACTIVITY_TRACKER
,07-05 14:16:19.066   767   767 V CAE     : stop(ContextProvider.java:155)
,07-05 14:16:19.066   767   767 V CAE     : clear(ActivityTrackerRunner.java:108)
,07-05 14:16:19.066   767   767 V CAE     : disable(ActivityTrackerRunner.java:96)
,07-05 14:16:19.066   767   767 I CAE     : sendCmdToSensorHub(SensorHubCommManager.java:162) - -78, 26, 0, 0, 0, 0, 0, 0, 0, 0,
,07-05 14:16:19.066   767   767 D SensorHubManager: SendSensorHubData: send data = -78, 26, 0, 0, 0, 0, 0, 0, 0, 0
,07-05 14:16:19.076   328   564 D Sensorhubs: sendContextData: -78, 26, 0, 0, 0, 0, 0, 0, 0, 0
,07-05 14:16:19.076   767   767 D CAE     : getFaultDetectionResult(ActivityTrackerRunner.java:154) - true
,07-05 14:16:19.076   767   767 I CAE     : notifyCmdProcessResultObserver(ContextProvider.java:627) - CheckResult = 0, Cause = Success
,07-05 14:16:19.096   767   767 D CAE     : doCommendProcess(ContextAwareService.java:433) - complete notify the operation result.
,07-05 14:16:19.096   767   767 I CAE     : displayUsedCountForService(ContextAwareService.java:525) - totalCnt = 0, serviceCount = 0, subCollectionCount = 0
07-05 14:16:19.096   767   767 D CAE     : showListenerList(ContextAwareService.java:366) - ===== Context Aware Service List =====
07-05 14:16:19.096   767   767 I CAE     : showListenerList(ContextAwareService.java:375) - Listener : com.samsung.android.contextaware.manager.ContextAwareService$Listener@b6149c6, Service : ACTIVITY_TRACKER_CURRENT_INFO(1)
07-05 14:16:19.096   767   767 W CAE     : unregisterCallback(ContextAwareService.java:241) - [unregi 02] Mutex is unlocked for ACTIVITY_TRACKER
07-05 14:16:19.096   767   767 D SContextService: 	.unregisterCallback : 1, client=
07-05 14:16:19.096   767   767 D SContextService: ===== SContext Service List =====
07-05 14:16:19.096   767   767 D SContextManager:   .unregisterListener : listener = com.android.server.wifi.WifiServiceImpl$12@85aae2f, service=Activity Tracker
,07-05 14:16:19.106   767   907 D IpRemoteDisplayController: intent received android.intent.action.SCREEN_OFF
,07-05 14:16:19.106   767   907 D IpRemoteDisplayController: Bridge Server is not available
,07-05 14:16:19.106  1380  1380 D vol.SecVolumeDialog: dismissH : false
,07-05 14:16:19.126   767   767 D NetworkPolicy: mScreenReceiver: ACTION_SCREEN_OFF, extra: 3
,07-05 14:16:19.126   767  1322 D NetworkPolicy: MSG_SCREEN_ON_CHANGED: 3
07-05 14:16:19.126   767  1322 D NetworkPolicy: isUidForegroundLocked: 10175, mScreenOn: false, uidstate: 0, mProxSensorScreenOff: false
,07-05 14:16:19.316   767   930 D LightsService: [SvcLED]  onSensorChanged::light value = 19
,07-05 14:16:19.316   767   930 E LightSensor: Light old sensor_state 512, new sensor_state : 0 en : 0
,07-05 14:16:19.326   767   930 D SensorManager: unregisterListener ::   
,07-05 14:16:19.326   767   930 D lights  : led_pattern : 5 +
,07-05 14:16:19.336   767   930 D lights  : led_pattern : 5 -
,07-05 14:16:19.336   767   930 D LightsService: [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=5) maintains its priority right
,07-05 14:16:19.346   767   930 V AlarmManager:  remove PendingIntent] PendingIntent{79303aa: PendingIntentRecord{4328b9b android broadcastIntent}}
,07-05 14:16:19.596  1447  1447 D Recents : onTaskStackChanged
,07-05 14:16:20.796   767   862 D GpsLocationProvider: receive broadcast intent, action: android.intent.action.SCREEN_OFF
,07-05 14:16:20.806  1722  3470 D NfcService: call the applyRouting
,07-05 14:16:20.816  1380  1380 D StatusBar.NetworkController: onDataActivity: direction=0
,07-05 14:16:20.816  1380  1380 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
,07-05 14:16:20.856  2328  2328 D BtGatt.GattService: LCD turned off
,07-05 14:16:20.856  2328  2561 D BtGatt.ScanManager: handleLcdOffIntent
07-05 14:16:20.856  2328  2561 D BtGatt.ScanManager: handleLcdOffIntent : thresholdScanValue is = 10 mLastConfiguredScanValue =0
,07-05 14:16:20.866  2290  2290 D accuweather: [KK AccuPhone]>>> SWW:66 [0:0] action : androidintentactionSCREEN_OFF
,07-05 14:16:20.876  2290  2290 D accuweather: [KK AccuPhone]>>> SWW:467 [0:0] stopRefreshIcon : 1
,07-05 14:16:20.876  2290  2290 D accuweather: [KK AccuPhone]>>> SWW:364 [0:0] getWeatherRenderer : 1
,07-05 14:16:20.896   767  1359 D PowerManagerService: [PWL] sb release: PowerManagerService.Broadcasts
,07-05 14:16:20.916  1380  1380 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020629/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020629/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02030b/com.android.systemui:drawable/qs_tile_wifi_signal_4 mWifiActivityIconId=0x7f0205df/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f020605/com.android.systemui:drawable/stat_sys_tether_bluetooth
07-05 14:16:20.916  1380  1380 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
07-05 14:16:20.916  1380  1380 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
07-05 14:16:20.916  1380  1380 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
07-05 14:16:20.916  1380  1380 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,07-05 14:16:20.916   767  3520 D SSRM:n  : SIOP:: AP = 310, PST = 303, CUR = 300, LCD = 0
,07-05 14:16:20.926   767  3520 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,07-05 14:16:20.996   767  7741 I BatteryStatsDumper: In refreshStats isReason Screen ON/OFF: true
,07-05 14:16:20.996   767  7741 D BluetoothAdapter: STATE_ON
,07-05 14:16:20.996  2328  2580 D bt_vendor: op for 7
,07-05 14:16:20.996  2328  2580 D bt_upio : upio_set : pio 0 action 2, polarity 1
,07-05 14:16:20.996  2328  2580 D bt_upio : upio_start_stop_timer : timer_settime success
,07-05 14:16:21.006  2328  2580 D bt_upio : upio_set: proc btwrite assertion, buffer: 1, timer_armed 1 1
07-05 14:16:21.006   767  1589 V AlarmManager:  remove PendingIntent] PendingIntent{65cb235: PendingIntentRecord{9a0d3b4 com.android.bluetooth broadcastIntent}}
,07-05 14:16:21.036   767  7741 D BatteryStatsImpl: poolsize= 1, curBatteryRealtime= 0, mUpdateTime= 0, mTimeout= 0, mNesting= 0, mTotalTime= 0
,07-05 14:16:21.076   767  7741 D BatteryStatsImpl: poolsize= 1, curBatteryRealtime= 0, mUpdateTime= 0, mTimeout= 0, mNesting= 0, mTotalTime= 0
,07-05 14:16:21.076   767  7741 I BatteryStatsDumper: Previous Battery Level: 100 Current Level: 100 Delta: 0
,07-05 14:16:21.216   767  7741 I BatteryStatsDumper: Writing to database completed
,07-05 14:16:21.806  2328  2831 D bt_upio : ..proc_btwrite_timeout..
,07-05 14:16:21.806  2328  2831 D bt_upio : upio_set : pio 0 action 1, polarity 1
,07-05 14:16:22.506  2328  2580 D bt_vendor: op for 7
,07-05 14:16:22.506  2328  2580 D bt_upio : upio_set : pio 0 action 1, polarity 1
07-05 14:16:22.506  2328  2580 D bt_upio : BT_WAKE is de-asserted already
,07-05 14:16:22.506   767  1591 V AlarmManager:  remove PendingIntent] PendingIntent{dc236ca: PendingIntentRecord{9a0d3b4 com.android.bluetooth broadcastIntent}}
,07-05 14:16:23.136   767  1237 V AlarmManager: Expired Alarm result :4
,07-05 14:16:23.146  1380  1380 D KeyguardViewMediator: received DELAYED_KEYGUARD_ACTION with seq = 2, mDelayedShowingSequence = 2
,07-05 14:16:23.156  1380  1380 D KeyguardViewMediator: doKeyguardLocked: started
,07-05 14:16:23.186  1380  1380 D KeyguardViewMediator: doKeyguard: not showing because lockscreen is off
,07-05 14:16:23.186  1380  1380 V KeyguardEffectViewController: *** Keyguard wallpaper service already unbounded
,07-05 14:16:23.236   767  1679 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 14:16:23.236   767  1679 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 298, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,07-05 14:16:23.236   767  1679 D BatteryService: online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
07-05 14:16:23.236   767  1679 D BatteryService: stay LED for fully charged
07-05 14:16:23.236   767   767 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 14:16:23.246   767   767 I MotionRecognitionService: Plugged
,07-05 14:16:23.246   767   767 D MotionRecognitionService:   cableConnection= 1
07-05 14:16:23.246   767   767 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
07-05 14:16:23.246   767   767 D MotionRecognitionService: skip setTransmitPower. 
,07-05 14:16:23.246  1380  1380 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 14:16:23.246  1380  1380 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
07-05 14:16:23.246  1380  1380 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 14:16:23.266  2328  2328 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 14:16:23.266  2328  2834 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-05 14:16:23.276  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:16:23.276  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 14:16:23.276  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:16:30.976   767  3520 D SSRM:n  : SIOP:: AP = 310, PST = 304, CUR = 300, LCD = 0
,07-05 14:16:32.046   767  1237 V AlarmManager: Expired Alarm result :4
,07-05 14:16:32.116  5788  5788 D Finsky  : [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,07-05 14:16:32.156  7745  7745 E Zygote  : v2
,07-05 14:16:32.156  7745  7745 I libpersona: KNOX_SDCARD checking this for 1000
,07-05 14:16:32.166  7745  7745 I libpersona: KNOX_SDCARD not a persona
,07-05 14:16:32.166  7745  7745 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
,07-05 14:16:32.166  7745  7745 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,07-05 14:16:32.166  7745  7745 E Zygote  : accessInfo : 0
,07-05 14:16:32.166   767   866 I ActivityManager: Start proc 7745:com.policydm/1000 for broadcast-3 com.policydm/com.sec.android.policyagent.RegistrationReceiver
,07-05 14:16:32.186  1653  1653 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-05 14:16:32.196  1653  1653 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-05 14:16:32.196  1653  1653 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-05 14:16:32.226  1653  1670 E Auth    : [GoogleAccountDataServiceImpl] getToken() failed. Status BAD_AUTHENTICATION, Account: <ELLIDED:1197869880>, App: com.android.vending, Service: androidmarket
07-05 14:16:32.226  1653  1670 E Auth    : com.google.android.gms.auth.be.account.b.d: Long live credential not available.
07-05 14:16:32.226  1653  1670 E Auth    : 	at com.google.android.gms.auth.be.account.b.e.a(:com.google.android.gms:105)
07-05 14:16:32.226  1653  1670 E Auth    : 	at com.google.android.gms.auth.be.p.a(:com.google.android.gms:355)
07-05 14:16:32.226  1653  1670 E Auth    : 	at com.google.android.gms.auth.be.o.a(:com.google.android.gms:260)
07-05 14:16:32.226  1653  1670 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.y.a(:com.google.android.gms:197)
07-05 14:16:32.226  1653  1670 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.x.a(:com.google.android.gms:558)
07-05 14:16:32.226  1653  1670 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.x.a(:com.google.android.gms:196)
07-05 14:16:32.226  1653  1670 E Auth    : 	at com.google.android.gms.auth.o.a(:com.google.android.gms:276)
07-05 14:16:32.226  1653  1670 E Auth    : 	at com.google.android.gms.auth.o.a(:com.google.android.gms:196)
07-05 14:16:32.226  1653  1670 E Auth    : 	at com.google.android.gms.auth.t.a(:com.google.android.gms:498)
07-05 14:16:32.226  1653  1670 E Auth    : 	at com.google.android.gms.auth.s.a(:com.google.android.gms:908)
07-05 14:16:32.226  1653  1670 E Auth    : 	at com.google.android.gms.auth.s.e(:com.google.android.gms:528)
07-05 14:16:32.226  1653  1670 E Auth    : 	at com.google.android.gms.auth.be.m.getAuthToken(:com.google.android.gms:201)
07-05 14:16:32.226  1653  1670 E Auth    : 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
07-05 14:16:32.226  1653  1670 E Auth    : 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
07-05 14:16:32.226  1653  1670 E Auth    : 	at android.os.Binder.execTransact(Binder.java:453)
,07-05 14:16:32.266  5788  5788 W Finsky  : [1] DailyHygiene$1.onErrorResponse: Unable to preload experiments: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,07-05 14:16:32.286  1653  1653 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-05 14:16:32.286  7745  7745 D TimaKeyStoreProvider: TimaSignature is unavailable
07-05 14:16:32.286  7745  7745 D ActivityThread: Added TimaKeyStore provider
,07-05 14:16:32.296   767  1679 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{aaecad2 u0 sec.policyagent.action.POLLING_TIME qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{ea487a3 7745:com.policydm/1000}
,07-05 14:16:32.296  1653  2252 E Auth    : [GoogleAccountDataServiceImpl] getToken() failed. Status BAD_AUTHENTICATION, Account: <ELLIDED:1197869880>, App: com.android.vending, Service: androidmarket
07-05 14:16:32.296  1653  2252 E Auth    : com.google.android.gms.auth.be.account.b.d: Long live credential not available.
07-05 14:16:32.296  1653  2252 E Auth    : 	at com.google.android.gms.auth.be.account.b.e.a(:com.google.android.gms:105)
07-05 14:16:32.296  1653  2252 E Auth    : 	at com.google.android.gms.auth.be.p.a(:com.google.android.gms:355)
07-05 14:16:32.296  1653  2252 E Auth    : 	at com.google.android.gms.auth.be.o.a(:com.google.android.gms:260)
07-05 14:16:32.296  1653  2252 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.y.a(:com.google.android.gms:197)
07-05 14:16:32.296  1653  2252 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.x.a(:com.google.android.gms:558)
07-05 14:16:32.296  1653  2252 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.x.a(:com.google.android.gms:196)
07-05 14:16:32.296  1653  2252 E Auth    : 	at com.google.android.gms.auth.o.a(:com.google.android.gms:276)
07-05 14:16:32.296  1653  2252 E Auth    : 	at com.google.android.gms.auth.o.a(:com.google.android.gms:196)
07-05 14:16:32.296  1653  2252 E Auth    : 	at com.google.android.gms.auth.t.a(:com.google.android.gms:498)
07-05 14:16:32.296  1653  2252 E Auth    : 	at com.google.android.gms.auth.s.a(:com.google.android.gms:908)
07-05 14:16:32.296  1653  2252 E Auth    : 	at com.google.android.gms.auth.s.e(:com.google.android.gms:528)
07-05 14:16:32.296  1653  2252 E Auth    : 	at com.google.android.gms.auth.be.m.getAuthToken(:com.google.android.gms:201)
07-05 14:16:32.296  1653  2252 E Auth    : 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
07-05 14:16:32.296  1653  2252 E Auth    : 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
07-05 14:16:32.296  1653  2252 E Auth    : 	at android.os.Binder.execTransact(Binder.java:453)
,07-05 14:16:32.306  7745  7745 W ResourcesManager: getTopLevelResources: /system/priv-app/SPDClient/SPDClient.apk / 1.0 running in com.policydm rsrc of package null
,07-05 14:16:32.336  7745  7745 W System  : ClassLoader referenced unknown path: /system/priv-app/SPDClient/lib/arm
,07-05 14:16:32.336  1653  1653 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-05 14:16:32.346  1653  3945 E Auth    : [GoogleAccountDataServiceImpl] getToken() failed. Status BAD_AUTHENTICATION, Account: <ELLIDED:1197869880>, App: com.android.vending, Service: androidmarket
07-05 14:16:32.346  1653  3945 E Auth    : com.google.android.gms.auth.be.account.b.d: Long live credential not available.
07-05 14:16:32.346  1653  3945 E Auth    : 	at com.google.android.gms.auth.be.account.b.e.a(:com.google.android.gms:105)
07-05 14:16:32.346  1653  3945 E Auth    : 	at com.google.android.gms.auth.be.p.a(:com.google.android.gms:355)
07-05 14:16:32.346  1653  3945 E Auth    : 	at com.google.android.gms.auth.be.o.a(:com.google.android.gms:260)
07-05 14:16:32.346  1653  3945 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.y.a(:com.google.android.gms:197)
07-05 14:16:32.346  1653  3945 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.x.a(:com.google.android.gms:558)
07-05 14:16:32.346  1653  3945 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.x.a(:com.google.android.gms:196)
07-05 14:16:32.346  1653  3945 E Auth    : 	at com.google.android.gms.auth.o.a(:com.google.android.gms:276)
07-05 14:16:32.346  1653  3945 E Auth    : 	at com.google.android.gms.auth.o.a(:com.google.android.gms:196)
07-05 14:16:32.346  1653  3945 E Auth    : 	at com.google.android.gms.auth.t.a(:com.google.android.gms:498)
07-05 14:16:32.346  1653  3945 E Auth    : 	at com.google.android.gms.auth.s.a(:com.google.android.gms:908)
07-05 14:16:32.346  1653  3945 E Auth    : 	at com.google.android.gms.auth.s.e(:com.google.android.gms:528)
07-05 14:16:32.346  1653  3945 E Auth    : 	at com.google.android.gms.auth.be.m.getAuthToken(:com.google.android.gms:201)
07-05 14:16:32.346  1653  3945 E Auth    : 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
07-05 14:16:32.346  1653  3945 E Auth    : 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
07-05 14:16:32.346  1653  3945 E Auth    : 	at android.os.Binder.execTransact(Binder.java:453)
,07-05 14:16:32.366  5788  5788 W Finsky  : [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,07-05 14:16:32.406  7745  7745 I FOTA    : [com.policydm.db.XDB(1493/llIlIIIIlIIIIIlIlIII)] xdbDMffs_Init
,07-05 14:16:32.536  7745  7745 I DBG_POLICYDM: [IlIIIllIlIIIlIIlIIlI(54/<init>)] 
07-05 14:16:32.536  7745  7745 W System.err: stat failed: ENOENT (No such file or directory) : /data/user/0/com.policydm/app_log/policydm_booting0.log
,07-05 14:16:32.536  7745  7745 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1394 android.content.ContextWrapper.bindService:632 IlIIIllIlIIIlIIlIIlI.<init>:58 IIIlIIlllIlIlIIIIIII.llIIIIlllllIIllIIllI:14 IIIlIIlllIlIlIIIIIII.llllIIIllIlIIIIllllI:20 
,07-05 14:16:32.576  7775  7775 E Zygote  : v2
07-05 14:16:32.576  7775  7775 I libpersona: KNOX_SDCARD checking this for 10217
07-05 14:16:32.576  7775  7775 I libpersona: KNOX_SDCARD not a persona
,07-05 14:16:32.586  7775  7775 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
,07-05 14:16:32.586  7775  7775 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
07-05 14:16:32.586   767  1764 I ActivityManager: Start proc 7775:com.samsung.aasaservice/u0a217 for service com.samsung.aasaservice/.AASAService
,07-05 14:16:32.586  7745  7745 I DBG_POLICYDM: [IIIlIIlllIlIlIIIIIII(23/llllIIIllIlIIIIllllI)] AASAUpdater Init Success
,07-05 14:16:32.586  7775  7775 E Zygote  : accessInfo : 0
,07-05 14:16:32.586  7775  7775 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.samsung.aasaservice 
,07-05 14:16:32.626  7745  7745 I DBG_POLICYDM: [com.policydm.db.llIIIIlllllIIllIIllI(236/llIIIIlllllIIllIIllI)] try read dbString
,07-05 14:16:32.636  7745  7745 I DBG_POLICYDM: [com.policydm.db.IIIIllIlIIlIIIIlllIl(442/IIIlIIllIlIIllIlllII)] xdbGetFUMOStatus : 0
,07-05 14:16:32.646  7775  7775 D TimaKeyStoreProvider: TimaSignature is unavailable
07-05 14:16:32.646  7775  7775 D ActivityThread: Added TimaKeyStore provider
,07-05 14:16:32.646  7745  7745 I DBG_POLICYDM: [com.policydm.XDMService(580/llIlIllllllllllllllI)] get NotibarState : 7
,07-05 14:16:32.656  7745  7745 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1305 android.content.ContextWrapper.startService:606 com.sec.android.policyagent.PolicyApplication.onCreate:61 android.app.Instrumentation.callApplicationOnCreate:1036 android.app.ActivityThread.handleBindApplication:6316 
,07-05 14:16:32.666  7745  7745 I DBG_POLICYDM: [com.sec.android.policyagent.PolicyApplication(64/onCreate)] PolicyApplication onCreated!
,07-05 14:16:32.666  7775  7775 W ResourcesManager: getTopLevelResources: /system/app/AASAservice/AASAservice.apk / 1.0 running in com.samsung.aasaservice rsrc of package null
,07-05 14:16:32.666  7745  7745 I DBG_POLICYDM: [com.sec.android.policyagent.RegistrationReceiver(74/onReceive)] RegistrationReceiver onReceive! action = sec.policyagent.action.POLLING_TIME
,07-05 14:16:32.676  7745  7745 I DBG_POLICYDM: [com.sec.android.policyagent.RegistrationReceiver(108/onReceive)] Already device registered...
,07-05 14:16:32.686  7745  7745 I DBG_POLICYDM: [IIIIlllIIIlIlllllIll(114/llIlIIIIlIIIIIlIlIII)] Next polling time:2016/07/05/14:14:10
,07-05 14:16:32.686  7775  7775 W System  : ClassLoader referenced unknown path: /system/app/AASAservice/lib/arm
,07-05 14:16:32.686  7745  7745 I DBG_POLICYDM: [IIIIlllIIIlIlllllIll(115/llIlIIIIlIIIIIlIlIII)] Polling time is not vaild
,07-05 14:16:32.696  7745  7745 I DBG_POLICYDM: [com.sec.android.policyagent.RegistrationReceiver(256/llIIIIlllllIIllIIllI)] Polling time is done. Start device init
,07-05 14:16:32.696  7775  7775 D AASAservice: onCreate()
,07-05 14:16:32.706  7745  7745 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1305 android.content.ContextWrapper.startService:606 android.content.ContextWrapper.startService:606 com.sec.android.policyagent.registration.llIlIllllllllllllllI.llIIIIlllllIIllIIllI:94 com.sec.android.policyagent.RegistrationReceiver.llIIIIlllllIIllIIllI:257 
,07-05 14:16:32.716  7745  7745 I DBG_POLICYDM: [com.policydm.XDMService(122/onCreate)] 
,07-05 14:16:32.716  7745  7745 I DBG_POLICYDM: [com.policydm.XDMService(171/llIIIIlllllIIllIIllI)] xdmUIHandelerInit
,07-05 14:16:32.716  7745  7745 I DBG_POLICYDM: [IIIlIIlllIlIlIIIIIII(23/llllIIIllIlIIIIllllI)] AASAUpdater Init Success
,07-05 14:16:32.726  7745  7745 I DBG_POLICYDM: [com.policydm.XDMService(515/IIIIllIlIIlIIIIlllIl)] 
,07-05 14:16:32.726  7745  7745 I DBG_POLICYDM: [com.policydm.XDMService(520/IIIIllIlIIlIIIIlllIl)] m_WakeLock is acquire!!
,07-05 14:16:32.736  7745  7745 I DBG_POLICYDM: [com.policydm.adapter.llIlIIIIlIIIIIlIlIII(126/IlIIIllllIIlIIIIIlII)] 
07-05 14:16:32.736  7745  7789 I DBG_POLICYDM: [com.policydm.ui.llIIIIlllllIIllIIllI(33/llIIIIlllllIIllIIllI)] nDmUiMode : 0
,07-05 14:16:32.736  7745  7789 I DBG_POLICYDM: [llIIlIlIlIlIIIIIIlIl(191/llIIIIlllllIIllIIllI)] XEVENT_OS_INITIALIZED
,07-05 14:16:32.736  7745  7789 I DBG_POLICYDM: [IIlIlIIIlIIlIlIIIIII(146/llIIIIlllllIIllIIllI)] nSync = 0
,07-05 14:16:32.746   767   767 I BackgroundCompactionService: onStart. jobID=801
,07-05 14:16:32.746  7745  7789 I DBG_POLICYDM: [com.policydm.ui.llIIIIlllllIIllIIllI(33/llIIIIlllllIIllIIllI)] nDmUiMode : 0
,07-05 14:16:32.746   767   767 I BackgroundCompactionService: onStart done. jobID=801
07-05 14:16:32.746   767  7792 I BackgroundCompactionService: Execute BGCompaction (type1). (1 times)
,07-05 14:16:32.746   767  7792 I BackgroundCompactionService: compact_memory command done
,07-05 14:16:32.746  7745  7789 I DBG_POLICYDM: [llIIlIlIlIlIIIIIIlIl(200/llIIIIlllllIIllIIllI)] XEVENT_DM_INIT
,07-05 14:16:32.756   767  1679 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,07-05 14:16:32.756  7745  7789 I DBG_POLICYDM: [IllllIlIIllIlllIlIIl(85/llllIIIllIlIIIIllllI)] WiFi Network is connected
,07-05 14:16:32.756  7745  7789 I DBG_POLICYDM: [com.policydm.XDMService(580/llIlIllllllllllllllI)] get NotibarState : 7
,07-05 14:16:32.756  7745  7789 I DBG_POLICYDM: [com.policydm.ui.IllIIIIIIlIIlIIIlIII(49/llIIIIlllllIIllIIllI)] Indicator id : 7
,07-05 14:16:32.756  7745  7789 I DBG_POLICYDM: [com.policydm.XDMService(572/llllIIIllIlIIIIllllI)] set NotibarState : 7
,07-05 14:16:32.766  7745  7789 I DBG_POLICYDM: [com.policydm.adapter.llllIIIllIlIIIIllllI(98/lllIlIlIIIllIIlIllIl)] 
,07-05 14:16:32.766  7745  7745 I DBG_POLICYDM: [com.policydm.adapter.llIlIIIIlIIIIIlIlIII(160/IlIIIllllIIlIIIIIlII)] bExternalStorageAvailable [true]
,07-05 14:16:32.766  7745  7745 I DBG_POLICYDM: [com.policydm.XDMService(541/llllllIllIlIlllIIlIl)] 
,07-05 14:16:32.776  7745  7745 I DBG_POLICYDM: [com.policydm.XDMService(546/llllllIllIlIlllIIlIl)] m_WakeLock is release!!
,07-05 14:16:32.776  7745  7745 I DBG_POLICYDM: [com.policydm.XDMService(259/onStartCommand)] 
,07-05 14:16:32.776  7745  7745 I DBG_POLICYDM: [lIIIIllIIlIIIlIllIII(40/onServiceConnected)] AASA: onServiceConnected
,07-05 14:16:32.786  7745  7797 I DBG_POLICYDM: [com.sec.android.policyagent.registration.UpdaterIntentService(32/onHandleIntent)] Polling State: Start polling
,07-05 14:16:32.796  7745  7797 I DBG_POLICYDM: [com.sec.android.policyagent.registration.state.IIIIlllIIIlIlIlllIII(17/llIIIIlllllIIllIIllI)] Register State: updating polling
,07-05 14:16:32.806  7745  7797 I DBG_POLICYDM: [lIIIlllIIIlllIIlllll(20/llIIIIlllllIIllIIllI)] Network is connected
,07-05 14:16:32.806   767  1409 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,07-05 14:16:32.806  7745  7797 I DBG_POLICYDM: [lIIIlllIIIlllIIlllll(27/llIIIIlllllIIllIIllI)] WiFi network is connected
,07-05 14:16:32.806  7745  7789 I DBG_POLICYDM: [com.policydm.db.IIIIllIlIIlIIIIlllIl(442/IIIlIIllIlIIllIlllII)] xdbGetFUMOStatus : 0
,07-05 14:16:32.826  7745  7789 I DBG_POLICYDM: [com.policydm.db.IIIIllIlIIlIIIIlllIl(574/IlIIIllllIIlIIIIIlII)] Initiated Type: 0
,07-05 14:16:32.826  7745  7789 I DBG_POLICYDM: [llIIlIlIlIlIIIIIIlIl(232/llIIIIlllllIIllIIllI)] XEVENT_DM_INIT : Initialized
07-05 14:16:32.826  7745  7790 I DBG_POLICYDM: [llllIlIIIllllIIlIlll(208/llllIIIllIlIIIIllllI)] XUI_DM_IDLE_STATE :true
,07-05 14:16:32.836   767  1591 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,07-05 14:16:32.836  7745  7790 I DBG_POLICYDM: [IllllIlIIllIlllIlIIl(85/llllIIIllIlIIIIllllI)] WiFi Network is connected
,07-05 14:16:32.836  7745  7797 I DBG_POLICYDM: [llIlIIlIIIlllIIlIllI(16/llIIIIlllllIIllIIllI)] Request Network Connection
,07-05 14:16:32.846  7745  7797 I DBG_POLICYDM: [lIIIlllIIIlllIIlllll(20/llIIIIlllllIIllIIllI)] Network is connected
,07-05 14:16:32.846  7745  7790 I DBG_POLICYDM: [com.policydm.db.IIIlIIllIlIIllIlllII(257/llIIllllIIlllIIIIlll)] nSessionSaveState [0], nNotiUiEvent [0]
,07-05 14:16:32.846   767  1748 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,07-05 14:16:32.846  7745  7797 I DBG_POLICYDM: [lIIIlllIIIlllIIlllll(27/llIIIIlllllIIllIIllI)] WiFi network is connected
,07-05 14:16:32.856  7745  7790 I DBG_POLICYDM: [com.policydm.noti.XNOTIAdapter(306/IIIlIIllIlIIllIlllII)] nSessionSaveState:0
,07-05 14:16:32.856  7745  7790 I DBG_POLICYDM: [com.policydm.noti.XNOTIAdapter(307/IIIlIIllIlIIllIlllII)] nNotiUiEvent:0
,07-05 14:16:32.866  7745  7790 I DBG_POLICYDM: [com.policydm.noti.XNOTIAdapter(308/IIIlIIllIlIIllIlllII)] nNotiRetryCount:0
,07-05 14:16:32.866  7745  7797 I DBG_POLICYDM: [lIIIlllIIIIllllIIIIl(46/llIIIIlllllIIllIIllI)] RestClient execute!!
,07-05 14:16:32.866  7745  7797 I DBG_POLICYDM: [com.sec.android.policyagent.network.restclient.llllIIIllIlIIIIllllI(37/llIIIIlllllIIllIIllI)] RestClient execute here
,07-05 14:16:32.876  7745  7790 I DBG_POLICYDM: [com.policydm.noti.XNOTIAdapter(348/IIIlIIllIlIIllIlllII)] Current NOTI NOT SAVED State. EXIT.
,07-05 14:16:32.876  7745  7797 I DBG_POLICYDM: [com.sec.android.policyagent.network.restclient.llllIIIllIlIIIIllllI(40/llIIIIlllllIIllIIllI)] [[ =================================================================
,07-05 14:16:32.876  7745  7790 I DBG_POLICYDM: [com.policydm.noti.XNOTIAdapter(175/IIIIlllIIIlIlIlllIII)] 
,07-05 14:16:32.886  7745  7790 I DBG_POLICYDM: [com.policydm.ui.llIIIIlllllIIllIIllI(39/llIIIIlllllIIllIIllI)] nDmUiMode : 0
,07-05 14:16:32.886  7745  7790 I DBG_POLICYDM: [com.policydm.db.IIIIllIlIIlIIIIlllIl(453/llIIIIlllllIIllIIllI)] xdbSetFUMOStatus : 0
,07-05 14:16:32.886  7745  7789 I DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver(211/lllIlIlIIIllIIlIllIl)] 
,07-05 14:16:32.896  7745  7789 I DBG_POLICYDM: [com.policydm.db.llIlIIIIlIIIIIlIlIII(63/llIIIIlllllIIllIIllI)] doesn't exist target file: /data/security/sepolicy
,07-05 14:16:32.906  7745  7789 I DBG_POLICYDM: [com.policydm.db.llIlIIIIlIIIIIlIlIII(63/llIIIIlllllIIllIIllI)] doesn't exist target file: /data/security/seapp_contexts
,07-05 14:16:32.916  7745  7790 I DBG_POLICYDM: [com.policydm.db.IIIIllIlIIlIIIIlllIl(552/llllIIIllIlIIIIllllI)] Initiated Type: 0
,07-05 14:16:32.916  7745  7789 I DBG_POLICYDM: [com.policydm.db.llIlIIIIlIIIIIlIlIII(63/llIIIIlllllIIllIIllI)] doesn't exist target file: /data/security/property_contexts
,07-05 14:16:32.916  7745  7789 I DBG_POLICYDM: [com.policydm.db.llIlIIIIlIIIIIlIlIII(63/llIIIIlllllIIllIIllI)] doesn't exist target file: /data/security/file_contexts
,07-05 14:16:32.926  7745  7789 I DBG_POLICYDM: [com.policydm.db.llIlIIIIlIIIIIlIlIII(63/llIIIIlllllIIllIIllI)] doesn't exist target file: /data/security/service_contexts
,07-05 14:16:32.926  7745  7789 I DBG_POLICYDM: [com.policydm.db.llIlIIIIlIIIIIlIlIII(63/llIIIIlllllIIllIIllI)] doesn't exist target file: /data/security/mac_permissions.xml
,07-05 14:16:32.936  7745  7797 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
07-05 14:16:32.936  7745  7797 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,07-05 14:16:32.946  7745  7790 I DBG_POLICYDM: [com.policydm.db.XDB(1781/IIIlIIllIlIIllIlllII)] 
,07-05 14:16:32.946   304  1199 D EnterpriseController: netId is 0
07-05 14:16:32.946   304  1199 D Netd    : getNetworkForDns: using netid 502 for uid 1000
,07-05 14:16:33.026  1653  1653 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-05 14:16:33.036  1653  2252 E Auth    : [GoogleAccountDataServiceImpl] getToken() failed. Status BAD_AUTHENTICATION, Account: <ELLIDED:1197869880>, App: com.android.vending, Service: androidmarket
07-05 14:16:33.036  1653  2252 E Auth    : com.google.android.gms.auth.be.account.b.d: Long live credential not available.
07-05 14:16:33.036  1653  2252 E Auth    : 	at com.google.android.gms.auth.be.account.b.e.a(:com.google.android.gms:105)
07-05 14:16:33.036  1653  2252 E Auth    : 	at com.google.android.gms.auth.be.p.a(:com.google.android.gms:355)
07-05 14:16:33.036  1653  2252 E Auth    : 	at com.google.android.gms.auth.be.o.a(:com.google.android.gms:260)
07-05 14:16:33.036  1653  2252 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.y.a(:com.google.android.gms:197)
07-05 14:16:33.036  1653  2252 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.x.a(:com.google.android.gms:558)
07-05 14:16:33.036  1653  2252 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.x.a(:com.google.android.gms:196)
07-05 14:16:33.036  1653  2252 E Auth    : 	at com.google.android.gms.auth.o.a(:com.google.android.gms:276)
07-05 14:16:33.036  1653  2252 E Auth    : 	at com.google.android.gms.auth.o.a(:com.google.android.gms:196)
07-05 14:16:33.036  1653  2252 E Auth    : 	at com.google.android.gms.auth.t.a(:com.google.android.gms:498)
07-05 14:16:33.036  1653  2252 E Auth    : 	at com.google.android.gms.auth.s.a(:com.google.android.gms:908)
07-05 14:16:33.036  1653  2252 E Auth    : 	at com.google.android.gms.auth.s.e(:com.google.android.gms:528)
07-05 14:16:33.036  1653  2252 E Auth    : 	at com.google.android.gms.auth.be.m.getAuthToken(:com.google.android.gms:201)
07-05 14:16:33.036  1653  2252 E Auth    : 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
07-05 14:16:33.036  1653  2252 E Auth    : 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
07-05 14:16:33.036  1653  2252 E Auth    : 	at android.os.Binder.execTransact(Binder.java:453)
,07-05 14:16:33.056  7745  7797 I DBG_POLICYDM: [com.sec.android.policyagent.network.restclient.llllIIIllIlIIIIllllI(82/llIIIIlllllIIllIIllI)] ================================================================= ]]
,07-05 14:16:33.056  7745  7797 I DBG_POLICYDM: [lIIIlllIIIIllllIIIIl(50/llIIIIlllllIIllIIllI)] setNonce !!
,07-05 14:16:33.056  7745  7797 W DBG_POLICYDM: [lIIIlllIIIIllllIIIIl(68/llIIIIlllllIIllIIllI)] nonce header is null
,07-05 14:16:33.056  5788  5788 W Finsky  : [1] UpdateChecker$1$2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,07-05 14:16:33.056  5788  5788 D Finsky  : [1] WearSupportService.startHygiene: disabled
,07-05 14:16:33.056  5788  5788 D Finsky  : [1] DailyHygiene.access$600: Logging device features
,07-05 14:16:33.066  5788  5788 D Finsky  : [1] DailyHygiene.reschedule: Scheduling new run in 29 minutes (failures=2)
,07-05 14:16:33.066  7775  7786 E AASAservice: getConfirmRuleVersion() : Version File is not exist.
,07-05 14:16:33.066  7745  7797 I DBG_POLICYDM: [IlIIIllIlIIIlIIlIIlI(78/llIIIIlllllIIllIIllI)] Device's AASA version: AASA_0000
,07-05 14:16:33.076  1653  1663 D DeviceConnectionService: client connected with version: 8296000
,07-05 14:16:33.086  7745  7797 I DBG_POLICYDM: [llIIlllIlIlllIlIIlII(205/llllIIIllIlIIIIllllI)] update type : 0
,07-05 14:16:33.096  7745  7797 I DBG_POLICYDM: [llIIlllIlIlllIlIIlII(211/llIIIIlllllIIllIIllI)] Update Polling Info: http://svc-cf.spd.samsungdm.com//day/7/9/23
,07-05 14:16:33.096  7745  7790 I DBG_POLICYDM: [com.policydm.db.IIIlIIllIlIIllIlllII(257/llIIllllIIlllIIIIlll)] nSessionSaveState [0], nNotiUiEvent [0]
,07-05 14:16:33.106  7745  7797 I DBG_POLICYDM: [llIIlllIlIlllIlIIlII(217/llIIIIlllllIIllIIllI)] Update heartbeat period: 14
,07-05 14:16:33.106   767  1409 D SettingsProvider: isChangeAllowed() : name = POLICY_AGENT_HEARTBEAT_PERIOD
,07-05 14:16:33.106  7745  7797 I DBG_POLICYDM: [llIIlllIlIlllIlIIlII(221/llIIIIlllllIIllIIllI)] Update heartbeat time: 0
,07-05 14:16:33.106   767  1679 D SettingsProvider: isChangeAllowed() : name = POLICY_AGENT_HEARTBEAT_TIME
,07-05 14:16:33.106  7745  7797 I DBG_POLICYDM: [llIIlllIlIlllIlIIlII(225/llIIIIlllllIIllIIllI)] Update heartbeat range: 23
,07-05 14:16:33.116   767   784 D SettingsProvider: isChangeAllowed() : name = POLICY_AGENT_HEARTBEAT_RANGE
,07-05 14:16:33.116  7745  7797 I DBG_POLICYDM: [IIlllIIllIllIllIIlll(48/llllIIIllIlIIIIllllI)] Next heartbeat time:1970/01/01/01:00:00
,07-05 14:16:33.116  7745  7797 I DBG_POLICYDM: [IIlllIIllIllIllIIlll(54/llllIIIllIlIIIIllllI)] heartbeat time is not vaild
,07-05 14:16:33.126  7745  7797 I DBG_POLICYDM: [llIIlllIlIlllIlIIlII(231/llIIIIlllllIIllIIllI)] Restart Heartbeat
,07-05 14:16:33.126  1380  1380 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
07-05 14:16:33.126  7745  7797 I DBG_POLICYDM: [IIlllIIllIllIllIIlll(25/llIIIIlllllIIllIIllI)] Calculate next heartbeat time
,07-05 14:16:33.126   767  1590 D SettingsProvider: isChangeAllowed() : name = POLICY_AGENT_HEARTBEAT_TIME
,07-05 14:16:33.126  7745  7790 I DBG_POLICYDM: [com.policydm.db.llllllIllIlIlllIIlIl(37/llllIIIllIlIIIIllllI)] Noti Exist : false
,07-05 14:16:33.126  7745  7797 I DBG_POLICYDM: [IIlllIIllIllIllIIlll(40/llIIIIlllllIIllIIllI)] Current time:2016/07/05/14:16:33
,07-05 14:16:33.136  7745  7797 I DBG_POLICYDM: [IIlllIIllIllIllIIlll(41/llIIIIlllllIIllIIllI)] Next heartbeat time:2016/07/19/04:57:41
,07-05 14:16:33.136  7745  7797 I DBG_POLICYDM: [IIlllIIllIllIllIIlll(48/llllIIIllIlIIIIllllI)] Next heartbeat time:2016/07/19/04:57:41
,07-05 14:16:33.136  1380  1380 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,07-05 14:16:33.136  7745  7797 I DBG_POLICYDM: [IIlllIIllIllIllIIlll(51/llllIIIllIlIIIIllllI)] heartbeat time is vaild
,07-05 14:16:33.146  7745  7797 I DBG_POLICYDM: [IIlllIIllIllIllIIlll(69/lllIlIlIIIllIIlIllIl)] Start heartbeat timer: 2016/07/19/04:57:41
,07-05 14:16:33.156  7745  7797 I DBG_POLICYDM: [com.sec.android.policyagent.registration.llIIIIlllllIIllIIllI(246/llIlIllllllllllllllI)] Request NetActionGetPolling
,07-05 14:16:33.156  7745  7797 I DBG_POLICYDM: [com.sec.android.policyagent.registration.state.IIIIlllIIIlIlIlllIII(21/llIIIIlllllIIllIIllI)] Receive result: success in NetActionGetPolling
,07-05 14:16:33.156  7745  7797 I DBG_POLICYDM: [com.sec.android.policyagent.registration.state.llIIllllIIlllIIIIlll(15/llIIIIlllllIIllIIllI)] Update State: success to check polling
,07-05 14:16:33.166  7745  7797 I DBG_POLICYDM: [IIIIlllIIIlIlllllIll(114/llIlIIIIlIIIIIlIlIII)] Next polling time:2016/07/05/14:14:10
,07-05 14:16:33.176  7745  7797 I DBG_POLICYDM: [IIIIlllIIIlIlllllIll(115/llIlIIIIlIIIIIlIlIII)] Polling time is not vaild
,07-05 14:16:33.176  7745  7797 I DBG_POLICYDM: [com.sec.android.policyagent.registration.llIIIIlllllIIllIIllI(208/IIIIllIlIIlIIIIlllIl)] Register polling time
,07-05 14:16:33.176  7745  7797 I DBG_POLICYDM: [IIIIlllIIIlIlllllIll(41/llIIIIlllllIIllIIllI)] Calculate next polling time
,07-05 14:16:33.186   767  1590 D SettingsProvider: isChangeAllowed() : name = POLICY_AGENT_POLLING_TIME
,07-05 14:16:33.196  7745  7797 I DBG_POLICYDM: [IIIIlllIIIlIlllllIll(84/llllIIIllIlIIIIllllI)] Start polling timer: 2016/07/13/07:35:31
,07-05 14:16:33.196  7745  7797 I DBG_POLICYDM: [com.sec.android.policyagent.registration.UpdaterIntentService(39/onHandleIntent)] Updater State: Finish Update
,07-05 14:16:33.196  1380  1380 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,07-05 14:16:33.326   767  1811 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 14:16:33.326   767  1811 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4326, temperature: 298, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
07-05 14:16:33.326   767  1811 D BatteryService: online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
07-05 14:16:33.326   767  1811 D BatteryService: stay LED for fully charged
07-05 14:16:33.326   767   767 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 14:16:33.336   767   767 I MotionRecognitionService: Plugged
07-05 14:16:33.336   767   767 D MotionRecognitionService:   cableConnection= 1
07-05 14:16:33.336   767   767 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
07-05 14:16:33.336   767   767 D MotionRecognitionService: skip setTransmitPower. 
,07-05 14:16:33.346  1380  1380 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 14:16:33.346  1380  1380 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,07-05 14:16:33.356  1380  1380 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 14:16:33.366  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 14:16:33.366  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:16:33.366  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:16:33.376  2328  2328 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 14:16:33.386  2328  2834 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-05 14:16:33.986  7745  7789 I DBG_POLICYDM: [com.policydm.db.IIIIllIlIIlIIIIlllIl(574/IlIIIllllIIlIIIIIlII)] Initiated Type: 0
,07-05 14:16:33.996  7745  7789 I DBG_POLICYDM: [com.policydm.db.IIIIllIlIIlIIIIlllIl(442/IIIlIIllIlIIllIlllII)] xdbGetFUMOStatus : 0
,07-05 14:16:33.996  7745  7789 E DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver(316/llIIllllIIlllIIIIlll)] SPD SERVICE Stop!!
,07-05 14:16:33.996  7745  7789 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1311 android.content.ContextWrapper.stopService:611 com.policydm.XDMBroadcastReceiver.llIIllllIIlllIIIIlll:317 com.policydm.llIlIIIIlIIIIIlIlIII.onFinish:280 android.os.CountDownTimer$1.handleMessage:127 
,07-05 14:16:33.996  7745  7745 I DBG_POLICYDM: [com.policydm.XDMService(105/onDestroy)] 
,07-05 14:16:34.006   767  1409 I ActivityManager: Killing 6382:com.samsung.android.service.travel/u0a178 (adj 15): DHA:empty #37
,07-05 14:16:34.006   767  1409 I ActivityManager: Killing 6346:com.android.email/u0a163 (adj 15): DHA:empty #37
,07-05 14:16:34.046   767  1748 D ActivityManager: isAutoRunBlockedApp:: com.samsung.android.service.travel, Auto Run ON
,07-05 14:16:34.086   767  1466 D ActivityManager: isAutoRunBlockedApp:: com.android.email, Auto Run ON
,07-05 14:16:36.566   767  1604 E Watchdog: !@Sync 28 [07-05 14:16:36.582]
,07-05 14:16:38.146  1664  1768 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,07-05 14:16:38.256  1664  1768 E ContactsProvider_EventLog: Flush buffer to file cnt : 5 size : 1Kb duration : 92ms lastUpdatedAfter : 180249ms
,07-05 14:16:41.056   767  3520 D SSRM:n  : SIOP:: AP = 310, PST = 305, CUR = 300, LCD = 0
,07-05 14:16:47.386   767  1237 V AlarmManager: Expired Alarm result :4
,07-05 14:16:47.456   767  1679 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 14:16:47.456   767  1679 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 298, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
07-05 14:16:47.456   767  1679 D BatteryService: online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
,07-05 14:16:47.456   767  1679 D BatteryService: stay LED for fully charged
07-05 14:16:47.456   767   767 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 14:16:47.466  1380  1380 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 14:16:47.466  1380  1380 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
07-05 14:16:47.466  1380  1380 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 14:16:47.486  2328  2328 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 14:16:47.486  2328  2834 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-05 14:16:47.486   767   767 I MotionRecognitionService: Plugged
,07-05 14:16:47.486   767   767 D MotionRecognitionService:   cableConnection= 1
07-05 14:16:47.486   767   767 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
07-05 14:16:47.486   767   767 D MotionRecognitionService: skip setTransmitPower. 
,07-05 14:16:47.496  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:16:47.496  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 14:16:47.496  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:16:47.836  1653  1653 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-05 14:16:47.846  1653  1653 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-05 14:16:47.856  1653  1653 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-05 14:16:47.886  1653  3945 E Auth    : [GoogleAccountDataServiceImpl] getToken() failed. Status BAD_AUTHENTICATION, Account: <ELLIDED:1197869880>, App: com.android.vending, Service: androidsecure
07-05 14:16:47.886  1653  3945 E Auth    : com.google.android.gms.auth.be.account.b.d: Long live credential not available.
07-05 14:16:47.886  1653  3945 E Auth    : 	at com.google.android.gms.auth.be.account.b.e.a(:com.google.android.gms:105)
07-05 14:16:47.886  1653  3945 E Auth    : 	at com.google.android.gms.auth.be.p.a(:com.google.android.gms:355)
07-05 14:16:47.886  1653  3945 E Auth    : 	at com.google.android.gms.auth.be.o.a(:com.google.android.gms:260)
07-05 14:16:47.886  1653  3945 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.y.a(:com.google.android.gms:197)
07-05 14:16:47.886  1653  3945 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.x.a(:com.google.android.gms:558)
07-05 14:16:47.886  1653  3945 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.x.a(:com.google.android.gms:196)
07-05 14:16:47.886  1653  3945 E Auth    : 	at com.google.android.gms.auth.o.a(:com.google.android.gms:276)
07-05 14:16:47.886  1653  3945 E Auth    : 	at com.google.android.gms.auth.o.a(:com.google.android.gms:196)
07-05 14:16:47.886  1653  3945 E Auth    : 	at com.google.android.gms.auth.t.a(:com.google.android.gms:498)
07-05 14:16:47.886  1653  3945 E Auth    : 	at com.google.android.gms.auth.s.a(:com.google.android.gms:908)
07-05 14:16:47.886  1653  3945 E Auth    : 	at com.google.android.gms.auth.s.e(:com.google.android.gms:528)
07-05 14:16:47.886  1653  3945 E Auth    : 	at com.google.android.gms.auth.be.m.getAuthToken(:com.google.android.gms:201)
07-05 14:16:47.886  1653  3945 E Auth    : 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
07-05 14:16:47.886  1653  3945 E Auth    : 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
07-05 14:16:47.886  1653  3945 E Auth    : 	at android.os.Binder.execTransact(Binder.java:453)
,07-05 14:16:47.906  5788  5788 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,07-05 14:16:47.906  5788  5788 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,07-05 14:16:47.916  5788  5788 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 1.
,07-05 14:16:48.056   304  1195 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
07-05 14:16:48.056   304  1195 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
07-05 14:16:48.056   304  1195 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,07-05 14:16:50.876   767  1237 V AlarmManager: Expired Alarm result :4
,07-05 14:16:50.896   767  4844 V AlarmManager:  remove PendingIntent] PendingIntent{e6d4ad: PendingIntentRecord{2a89711 com.google.android.gms broadcastIntent}}
,07-05 14:16:50.906   304  1195 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
07-05 14:16:50.906   304  1195 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
07-05 14:16:50.906   304  1195 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,07-05 14:16:50.906   767  1322 D NetworkPolicy: isUidForegroundLocked: 10012, mScreenOn: false, uidstate: 6, mProxSensorScreenOff: false
,07-05 14:16:50.916   767  1322 D NetworkPolicy: isUidForegroundLocked: 10012, mScreenOn: false, uidstate: 6, mProxSensorScreenOff: false
,07-05 14:16:51.126   767  3520 D SSRM:n  : SIOP:: AP = 300, PST = 305, CUR = 300, LCD = 0
,07-05 14:16:57.556   767  1764 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 14:16:57.556   767  1764 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 298, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,07-05 14:16:57.556   767  1764 D BatteryService: online:4, current avg:300, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
,07-05 14:16:57.566   767   767 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 14:16:57.576   767   767 I MotionRecognitionService: Plugged
,07-05 14:16:57.576   767   767 D MotionRecognitionService:   cableConnection= 1
,07-05 14:16:57.576   767   767 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,07-05 14:16:57.586   767   767 D MotionRecognitionService: skip setTransmitPower. 
,07-05 14:16:57.586   767  1764 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 29ms
,07-05 14:16:57.586   767  1764 D BatteryService: stay LED for fully charged
,07-05 14:16:57.606  1380  1380 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 14:16:57.606  1380  1380 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
07-05 14:16:57.606  1380  1380 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 14:16:57.616  2328  2328 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 14:16:57.616  2328  2834 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-05 14:16:57.626  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:16:57.626  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 14:16:57.626  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:16:59.986   767  1237 V AlarmManager: Expired Alarm result :8
,07-05 14:17:00.896   767  1322 D NetworkPolicy: isUidForegroundLocked: 10012, mScreenOn: false, uidstate: 6, mProxSensorScreenOff: false
,07-05 14:17:00.896   767  1322 D NetworkPolicy: isUidForegroundLocked: 10012, mScreenOn: false, uidstate: 6, mProxSensorScreenOff: false
,07-05 14:17:01.176   767  3520 D SSRM:n  : SIOP:: AP = 300, PST = 305, CUR = 300, LCD = 0
,07-05 14:17:06.016   304  1195 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
07-05 14:17:06.016   304  1195 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
07-05 14:17:06.016   304  1195 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,07-05 14:17:06.576   767  1604 E Watchdog: !@Sync 29 [07-05 14:17:06.590]
,07-05 14:17:07.916   767  1237 V AlarmManager: Expired Alarm result :4
,07-05 14:17:07.986  1380  1380 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
,07-05 14:17:07.986  1380  1380 I PERF    : received broadcast android.intent.action.TIME_TICK
,07-05 14:17:07.996  1380  1380 D KeyguardUpdateMonitor: handleTimeUpdate
,07-05 14:17:08.056  1380  1380 D SecKeyguardClockView: onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,07-05 14:17:08.056  1380  1380 D SecKeyguardClockView: HomeTimezone(): 1
,07-05 14:17:08.076  1380  1380 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-05 14:17:08.076  1380  1380 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-05 14:17:08.076  1380  1380 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-05 14:17:08.076  1380  1380 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-05 14:17:08.076  1380  1380 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-05 14:17:08.076  1380  1380 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-05 14:17:08.086  1380  1380 D SecKeyguardStatusUtils: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-05 14:17:08.146  1380  1380 D SecKeyguardStatusUtils: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-05 14:17:08.626  1653  1653 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-05 14:17:08.656  1653  1653 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-05 14:17:08.656  1653  1653 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-05 14:17:08.696  1653  1663 E Auth    : [GoogleAccountDataServiceImpl] getToken() failed. Status BAD_AUTHENTICATION, Account: <ELLIDED:1197869880>, App: com.android.vending, Service: androidsecure
07-05 14:17:08.696  1653  1663 E Auth    : com.google.android.gms.auth.be.account.b.d: Long live credential not available.
07-05 14:17:08.696  1653  1663 E Auth    : 	at com.google.android.gms.auth.be.account.b.e.a(:com.google.android.gms:105)
07-05 14:17:08.696  1653  1663 E Auth    : 	at com.google.android.gms.auth.be.p.a(:com.google.android.gms:355)
07-05 14:17:08.696  1653  1663 E Auth    : 	at com.google.android.gms.auth.be.o.a(:com.google.android.gms:260)
07-05 14:17:08.696  1653  1663 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.y.a(:com.google.android.gms:197)
07-05 14:17:08.696  1653  1663 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.x.a(:com.google.android.gms:558)
07-05 14:17:08.696  1653  1663 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.x.a(:com.google.android.gms:196)
07-05 14:17:08.696  1653  1663 E Auth    : 	at com.google.android.gms.auth.o.a(:com.google.android.gms:276)
07-05 14:17:08.696  1653  1663 E Auth    : 	at com.google.android.gms.auth.o.a(:com.google.android.gms:196)
07-05 14:17:08.696  1653  1663 E Auth    : 	at com.google.android.gms.auth.t.a(:com.google.android.gms:498)
07-05 14:17:08.696  1653  1663 E Auth    : 	at com.google.android.gms.auth.s.a(:com.google.android.gms:908)
07-05 14:17:08.696  1653  1663 E Auth    : 	at com.google.android.gms.auth.s.e(:com.google.android.gms:528)
07-05 14:17:08.696  1653  1663 E Auth    : 	at com.google.android.gms.auth.be.m.getAuthToken(:com.google.android.gms:201)
07-05 14:17:08.696  1653  1663 E Auth    : 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
07-05 14:17:08.696  1653  1663 E Auth    : 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
07-05 14:17:08.696  1653  1663 E Auth    : 	at android.os.Binder.execTransact(Binder.java:453)
,07-05 14:17:08.716  5788  5788 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,07-05 14:17:08.716  5788  5788 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,07-05 14:17:08.716  5788  5788 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 2.
,07-05 14:17:11.256   767  3520 D SSRM:n  : SIOP:: AP = 300, PST = 305, CUR = 300, LCD = 0
,07-05 14:17:21.166   767  1231 D TimaService: TIMA: TimaService scheduler is intialized. 
,07-05 14:17:21.166   767  1231 D TimaService: TIMA: checkEvent, operation: 50000 subject: 10000
,07-05 14:17:21.166   767  1230 D TimaService: TimaServiceHandler.handleMessage what =1
,07-05 14:17:21.356   767  3520 D SSRM:n  : SIOP:: AP = 300, PST = 304, CUR = 300, LCD = 0
,07-05 14:17:24.606   767  1231 I TLC_TIMA_PKM_measure_kernel: TIMA: response_id = 3
,07-05 14:17:24.606   767  1231 I TLC_TIMA_PKM_measure_kernel: TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,07-05 14:17:24.616   767  1231 D TimaService: TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,07-05 14:17:24.626   767  1231 D TimaService: TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,07-05 14:17:28.736   767  1237 V AlarmManager: Expired Alarm result :4
,07-05 14:17:28.796   767  1679 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 14:17:28.796   767  1679 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4362, temperature: 298, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
07-05 14:17:28.796   767  1679 D BatteryService: online:4, current avg:300, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
,07-05 14:17:28.796   767  1679 D BatteryService: stay LED for fully charged
,07-05 14:17:28.806   767   767 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 14:17:28.816   767   767 I MotionRecognitionService: Plugged
,07-05 14:17:28.816   767   767 D MotionRecognitionService:   cableConnection= 1
07-05 14:17:28.816   767   767 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
07-05 14:17:28.816   767   767 D MotionRecognitionService: skip setTransmitPower. 
,07-05 14:17:28.826  1380  1380 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 14:17:28.826  1380  1380 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
07-05 14:17:28.826  1380  1380 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 14:17:28.836  2328  2328 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 14:17:28.836  2328  2834 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-05 14:17:28.846  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:17:28.846  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 14:17:28.846  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:17:29.296  1653  1653 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-05 14:17:29.306  1653  1653 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-05 14:17:29.306  1653  1653 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-05 14:17:29.326  1653  1670 E Auth    : [GoogleAccountDataServiceImpl] getToken() failed. Status BAD_AUTHENTICATION, Account: <ELLIDED:1197869880>, App: com.android.vending, Service: androidsecure
07-05 14:17:29.326  1653  1670 E Auth    : com.google.android.gms.auth.be.account.b.d: Long live credential not available.
07-05 14:17:29.326  1653  1670 E Auth    : 	at com.google.android.gms.auth.be.account.b.e.a(:com.google.android.gms:105)
07-05 14:17:29.326  1653  1670 E Auth    : 	at com.google.android.gms.auth.be.p.a(:com.google.android.gms:355)
07-05 14:17:29.326  1653  1670 E Auth    : 	at com.google.android.gms.auth.be.o.a(:com.google.android.gms:260)
07-05 14:17:29.326  1653  1670 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.y.a(:com.google.android.gms:197)
07-05 14:17:29.326  1653  1670 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.x.a(:com.google.android.gms:558)
07-05 14:17:29.326  1653  1670 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.x.a(:com.google.android.gms:196)
07-05 14:17:29.326  1653  1670 E Auth    : 	at com.google.android.gms.auth.o.a(:com.google.android.gms:276)
07-05 14:17:29.326  1653  1670 E Auth    : 	at com.google.android.gms.auth.o.a(:com.google.android.gms:196)
07-05 14:17:29.326  1653  1670 E Auth    : 	at com.google.android.gms.auth.t.a(:com.google.android.gms:498)
07-05 14:17:29.326  1653  1670 E Auth    : 	at com.google.android.gms.auth.s.a(:com.google.android.gms:908)
07-05 14:17:29.326  1653  1670 E Auth    : 	at com.google.android.gms.auth.s.e(:com.google.android.gms:528)
07-05 14:17:29.326  1653  1670 E Auth    : 	at com.google.android.gms.auth.be.m.getAuthToken(:com.google.android.gms:201)
07-05 14:17:29.326  1653  1670 E Auth    : 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
07-05 14:17:29.326  1653  1670 E Auth    : 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
07-05 14:17:29.326  1653  1670 E Auth    : 	at android.os.Binder.execTransact(Binder.java:453)
,07-05 14:17:29.346  5788  5788 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,07-05 14:17:29.346  5788  5788 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
07-05 14:17:29.346  5788  5788 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 3.
,07-05 14:17:31.416   767  3520 D SSRM:n  : SIOP:: AP = 300, PST = 303, CUR = 300, LCD = 0
,07-05 14:17:36.586   767  1604 E Watchdog: !@Sync 30 [07-05 14:17:36.596]
,07-05 14:17:38.346  1664  1768 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,07-05 14:17:41.496   767  3520 D SSRM:n  : SIOP:: AP = 300, PST = 303, CUR = 300, LCD = 0
,07-05 14:17:43.236   767  1237 V AlarmManager: Expired Alarm result :4
,07-05 14:17:43.286  2328  2519 E bt_osi_alarm: reschedule_root_alarm alarm expiration too close for posix timers, switching to guns
,07-05 14:17:43.286  2328  2580 D bt_vendor: op for 7
,07-05 14:17:43.286  2328  2580 D bt_upio : upio_set : pio 0 action 2, polarity 1
,07-05 14:17:43.296  2328  2519 E bt_osi_alarm: reschedule_root_alarm alarm expiration too close for posix timers, switching to guns
,07-05 14:17:43.306  2328  2519 E bt_osi_alarm: reschedule_root_alarm alarm expiration too close for posix timers, switching to guns
,07-05 14:17:43.306  2328  2519 E bt_osi_alarm: reschedule_root_alarm alarm expiration too close for posix timers, switching to guns
,07-05 14:17:43.306  2328  2580 D bt_upio : upio_start_stop_timer : timer_settime success
,07-05 14:17:43.316  2328  2580 D bt_upio : upio_set: proc btwrite assertion, buffer: 1, timer_armed 1 1
,07-05 14:17:43.316  2328  2580 D bt_vendor: op for 7
,07-05 14:17:43.316  2328  2580 D bt_upio : upio_set : pio 0 action 2, polarity 1
,07-05 14:17:43.326  2328  2580 D bt_upio : BT_WAKE is asserted already
,07-05 14:17:43.326  2328  2580 D bt_vendor: op for 7
07-05 14:17:43.326  2328  2580 D bt_upio : upio_set : pio 0 action 2, polarity 1
07-05 14:17:43.326  2328  2580 D bt_upio : BT_WAKE is asserted already
,07-05 14:17:43.326  2328  2580 D bt_vendor: op for 7
,07-05 14:17:43.326  2328  2580 D bt_upio : upio_set : pio 0 action 2, polarity 1
07-05 14:17:43.326  2328  2580 D bt_upio : BT_WAKE is asserted already
,07-05 14:17:43.336  2328  2580 D bt_vendor: op for 7
07-05 14:17:43.336  2328  2580 D bt_upio : upio_set : pio 0 action 2, polarity 1
07-05 14:17:43.336  2328  2580 D bt_upio : BT_WAKE is asserted already
,07-05 14:17:43.336  2328  2580 D bt_vendor: op for 7
,07-05 14:17:43.336  2328  2580 D bt_upio : upio_set : pio 0 action 2, polarity 1
07-05 14:17:43.336  2328  2580 D bt_upio : BT_WAKE is asserted already
,07-05 14:17:43.336  2328  2580 D bt_vendor: op for 7
07-05 14:17:43.336  2328  2580 D bt_upio : upio_set : pio 0 action 2, polarity 1
07-05 14:17:43.336  2328  2580 D bt_upio : BT_WAKE is asserted already
,07-05 14:17:43.336  2328  2580 D bt_vendor: op for 7
,07-05 14:17:43.336  2328  2580 D bt_upio : upio_set : pio 0 action 2, polarity 1
07-05 14:17:43.336  2328  2580 D bt_upio : BT_WAKE is asserted already
,07-05 14:17:43.336  2328  2580 D bt_vendor: op for 7
07-05 14:17:43.336  2328  2580 D bt_upio : upio_set : pio 0 action 2, polarity 1
07-05 14:17:43.336  2328  2580 D bt_upio : BT_WAKE is asserted already
,07-05 14:17:43.346  2328  2580 D bt_vendor: op for 7
,07-05 14:17:43.346  2328  2580 D bt_upio : upio_set : pio 0 action 2, polarity 1
07-05 14:17:43.346  2328  2580 D bt_upio : BT_WAKE is asserted already
,07-05 14:17:43.346  2328  2580 D bt_vendor: op for 7
07-05 14:17:43.346  2328  2580 D bt_upio : upio_set : pio 0 action 2, polarity 1
07-05 14:17:43.346  2328  2580 D bt_upio : BT_WAKE is asserted already
,07-05 14:17:43.346  2328  2580 D bt_vendor: op for 7
,07-05 14:17:43.346  2328  2580 D bt_upio : upio_set : pio 0 action 2, polarity 1
07-05 14:17:43.346  2328  2580 D bt_upio : BT_WAKE is asserted already
,07-05 14:17:43.346  2328  2580 D bt_vendor: op for 7
07-05 14:17:43.346  2328  2580 D bt_upio : upio_set : pio 0 action 2, polarity 1
07-05 14:17:43.346  2328  2580 D bt_upio : BT_WAKE is asserted already
,07-05 14:17:43.346  2328  2580 D bt_vendor: op for 7
,07-05 14:17:43.346  2328  2580 D bt_upio : upio_set : pio 0 action 2, polarity 1
07-05 14:17:43.346  2328  2580 D bt_upio : BT_WAKE is asserted already
,07-05 14:17:43.346  2328  2580 D bt_vendor: op for 7
07-05 14:17:43.346  2328  2580 D bt_upio : upio_set : pio 0 action 2, polarity 1
,07-05 14:17:43.356  2328  2580 D bt_upio : BT_WAKE is asserted already
,07-05 14:17:43.356  2328  2580 D bt_vendor: op for 7
07-05 14:17:43.356  2328  2580 D bt_upio : upio_set : pio 0 action 2, polarity 1
07-05 14:17:43.356  2328  2580 D bt_upio : BT_WAKE is asserted already
,07-05 14:17:43.356  2328  2580 D bt_vendor: op for 7
07-05 14:17:43.356  2328  2580 D bt_upio : upio_set : pio 0 action 2, polarity 1
,07-05 14:17:43.356  2328  2580 D bt_upio : BT_WAKE is asserted already
,07-05 14:17:43.356  2328  2580 D bt_vendor: op for 7
07-05 14:17:43.356  2328  2580 D bt_upio : upio_set : pio 0 action 2, polarity 1
07-05 14:17:43.356  2328  2580 D bt_upio : BT_WAKE is asserted already
,07-05 14:17:43.356  2328  2580 D bt_vendor: op for 7
07-05 14:17:43.356  2328  2580 D bt_upio : upio_set : pio 0 action 2, polarity 1
,07-05 14:17:43.356  2328  2580 D bt_upio : BT_WAKE is asserted already
,07-05 14:17:43.356  2328  2580 D bt_vendor: op for 7
07-05 14:17:43.356  2328  2580 D bt_upio : upio_set : pio 0 action 2, polarity 1
07-05 14:17:43.356  2328  2580 D bt_upio : BT_WAKE is asserted already
,07-05 14:17:43.376   767  1589 V AlarmManager:  remove PendingIntent] PendingIntent{f3f9753: PendingIntentRecord{5728b42 com.android.bluetooth broadcastIntent}}
,07-05 14:17:43.386   767  4119 V AlarmManager:  remove PendingIntent] PendingIntent{b60e890: PendingIntentRecord{5728b42 com.android.bluetooth broadcastIntent}}
,07-05 14:17:43.386   767  1466 V AlarmManager:  remove PendingIntent] PendingIntent{e7f1589: PendingIntentRecord{5728b42 com.android.bluetooth broadcastIntent}}
,07-05 14:17:43.386   767  4844 V AlarmManager:  remove PendingIntent] PendingIntent{5a2198e: PendingIntentRecord{5728b42 com.android.bluetooth broadcastIntent}}
,07-05 14:17:43.396   767  1811 V AlarmManager:  remove PendingIntent] PendingIntent{ba255af: PendingIntentRecord{5728b42 com.android.bluetooth broadcastIntent}}
,07-05 14:17:43.396   767  1826 V AlarmManager:  remove PendingIntent] PendingIntent{e93fdbc: PendingIntentRecord{5728b42 com.android.bluetooth broadcastIntent}}
,07-05 14:17:43.406   767   784 V AlarmManager:  remove PendingIntent] PendingIntent{7ba8145: PendingIntentRecord{5728b42 com.android.bluetooth broadcastIntent}}
,07-05 14:17:43.406   767  1764 V AlarmManager:  remove PendingIntent] PendingIntent{e2a409a: PendingIntentRecord{5728b42 com.android.bluetooth broadcastIntent}}
,07-05 14:17:43.406   767  1591 V AlarmManager:  remove PendingIntent] PendingIntent{8c89dcb: PendingIntentRecord{5728b42 com.android.bluetooth broadcastIntent}}
,07-05 14:17:43.416   767  1409 V AlarmManager:  remove PendingIntent] PendingIntent{38139a8: PendingIntentRecord{5728b42 com.android.bluetooth broadcastIntent}}
,07-05 14:17:43.416   767  1748 V AlarmManager:  remove PendingIntent] PendingIntent{d86ecc1: PendingIntentRecord{5728b42 com.android.bluetooth broadcastIntent}}
,07-05 14:17:43.416   767   785 V AlarmManager:  remove PendingIntent] PendingIntent{cdbcc66: PendingIntentRecord{5728b42 com.android.bluetooth broadcastIntent}}
,07-05 14:17:43.426   767  1679 V AlarmManager:  remove PendingIntent] PendingIntent{ec14ba7: PendingIntentRecord{5728b42 com.android.bluetooth broadcastIntent}}
,07-05 14:17:43.426   767  1590 V AlarmManager:  remove PendingIntent] PendingIntent{7844854: PendingIntentRecord{5728b42 com.android.bluetooth broadcastIntent}}
,07-05 14:17:43.436   767  1767 V AlarmManager:  remove PendingIntent] PendingIntent{65493fd: PendingIntentRecord{5728b42 com.android.bluetooth broadcastIntent}}
,07-05 14:17:43.436   767  1589 V AlarmManager:  remove PendingIntent] PendingIntent{9c848f2: PendingIntentRecord{5728b42 com.android.bluetooth broadcastIntent}}
,07-05 14:17:43.446   767  4119 V AlarmManager:  remove PendingIntent] PendingIntent{dacfb43: PendingIntentRecord{5728b42 com.android.bluetooth broadcastIntent}}
,07-05 14:17:43.446   767  1466 V AlarmManager:  remove PendingIntent] PendingIntent{795c0: PendingIntentRecord{5728b42 com.android.bluetooth broadcastIntent}}
,07-05 14:17:43.446   767  4844 V AlarmManager:  remove PendingIntent] PendingIntent{55b72f9: PendingIntentRecord{5728b42 com.android.bluetooth broadcastIntent}}
,07-05 14:17:43.456   767  1811 V AlarmManager:  remove PendingIntent] PendingIntent{a8e023e: PendingIntentRecord{5728b42 com.android.bluetooth broadcastIntent}}
,07-05 14:17:43.466   767  1826 V AlarmManager:  remove PendingIntent] PendingIntent{d1a089f: PendingIntentRecord{5728b42 com.android.bluetooth broadcastIntent}}
,07-05 14:17:43.466   767   784 V AlarmManager:  remove PendingIntent] PendingIntent{cb04dec: PendingIntentRecord{5728b42 com.android.bluetooth broadcastIntent}}
,07-05 14:17:43.466   767  4844 V AlarmManager:  remove PendingIntent] PendingIntent{f5745b5: PendingIntentRecord{5728b42 com.android.bluetooth broadcastIntent}}
,07-05 14:17:43.476   767  1589 V AlarmManager:  remove PendingIntent] PendingIntent{e64044a: PendingIntentRecord{5728b42 com.android.bluetooth broadcastIntent}}
,07-05 14:17:43.476   767  1679 V AlarmManager:  remove PendingIntent] PendingIntent{5208fbb: PendingIntentRecord{5728b42 com.android.bluetooth broadcastIntent}}
,07-05 14:17:43.476   767  1409 V AlarmManager:  remove PendingIntent] PendingIntent{4a5cd8: PendingIntentRecord{5728b42 com.android.bluetooth broadcastIntent}}
,07-05 14:17:43.486   767   784 V AlarmManager:  remove PendingIntent] PendingIntent{f038831: PendingIntentRecord{5728b42 com.android.bluetooth broadcastIntent}}
,07-05 14:17:43.486   767  4844 V AlarmManager:  remove PendingIntent] PendingIntent{ee61b16: PendingIntentRecord{5728b42 com.android.bluetooth broadcastIntent}}
,07-05 14:17:43.486   767  1589 V AlarmManager:  remove PendingIntent] PendingIntent{d3e6c97: PendingIntentRecord{5728b42 com.android.bluetooth broadcastIntent}}
,07-05 14:17:43.486   767  1679 V AlarmManager:  remove PendingIntent] PendingIntent{c746e84: PendingIntentRecord{5728b42 com.android.bluetooth broadcastIntent}}
,07-05 14:17:43.496   767  1409 V AlarmManager:  remove PendingIntent] PendingIntent{557766d: PendingIntentRecord{5728b42 com.android.bluetooth broadcastIntent}}
,07-05 14:17:43.496   767   784 V AlarmManager:  remove PendingIntent] PendingIntent{1a0d2a2: PendingIntentRecord{5728b42 com.android.bluetooth broadcastIntent}}
,07-05 14:17:43.496   767  4844 V AlarmManager:  remove PendingIntent] PendingIntent{cf33b33: PendingIntentRecord{5728b42 com.android.bluetooth broadcastIntent}}
,07-05 14:17:43.496   767  1589 V AlarmManager:  remove PendingIntent] PendingIntent{c0beef0: PendingIntentRecord{5728b42 com.android.bluetooth broadcastIntent}}
,07-05 14:17:43.496   767  1679 V AlarmManager:  remove PendingIntent] PendingIntent{1820c69: PendingIntentRecord{5728b42 com.android.bluetooth broadcastIntent}}
,07-05 14:17:43.506   767  1409 V AlarmManager:  remove PendingIntent] PendingIntent{65d76ee: PendingIntentRecord{5728b42 com.android.bluetooth broadcastIntent}}
,07-05 14:17:43.506   767   784 V AlarmManager:  remove PendingIntent] PendingIntent{a1c578f: PendingIntentRecord{5728b42 com.android.bluetooth broadcastIntent}}
,07-05 14:17:43.506   767  4844 V AlarmManager:  remove PendingIntent] PendingIntent{8590a1c: PendingIntentRecord{5728b42 com.android.bluetooth broadcastIntent}}
,07-05 14:17:43.506   767  1589 V AlarmManager:  remove PendingIntent] PendingIntent{ca60625: PendingIntentRecord{5728b42 com.android.bluetooth broadcastIntent}}
,07-05 14:17:44.106  2328  2831 D bt_upio : ..proc_btwrite_timeout..
,07-05 14:17:44.116  2328  2831 D bt_upio : upio_set : pio 0 action 1, polarity 1
,07-05 14:17:49.346   767  1237 V AlarmManager: Expired Alarm result :4
,07-05 14:17:49.826  1653  1653 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-05 14:17:49.836  1653  1653 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-05 14:17:49.836  1653  1653 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-05 14:17:49.856  1653  1663 E Auth    : [GoogleAccountDataServiceImpl] getToken() failed. Status BAD_AUTHENTICATION, Account: <ELLIDED:1197869880>, App: com.android.vending, Service: androidsecure
07-05 14:17:49.856  1653  1663 E Auth    : com.google.android.gms.auth.be.account.b.d: Long live credential not available.
07-05 14:17:49.856  1653  1663 E Auth    : 	at com.google.android.gms.auth.be.account.b.e.a(:com.google.android.gms:105)
07-05 14:17:49.856  1653  1663 E Auth    : 	at com.google.android.gms.auth.be.p.a(:com.google.android.gms:355)
07-05 14:17:49.856  1653  1663 E Auth    : 	at com.google.android.gms.auth.be.o.a(:com.google.android.gms:260)
07-05 14:17:49.856  1653  1663 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.y.a(:com.google.android.gms:197)
07-05 14:17:49.856  1653  1663 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.x.a(:com.google.android.gms:558)
07-05 14:17:49.856  1653  1663 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.x.a(:com.google.android.gms:196)
07-05 14:17:49.856  1653  1663 E Auth    : 	at com.google.android.gms.auth.o.a(:com.google.android.gms:276)
07-05 14:17:49.856  1653  1663 E Auth    : 	at com.google.android.gms.auth.o.a(:com.google.android.gms:196)
07-05 14:17:49.856  1653  1663 E Auth    : 	at com.google.android.gms.auth.t.a(:com.google.android.gms:498)
07-05 14:17:49.856  1653  1663 E Auth    : 	at com.google.android.gms.auth.s.a(:com.google.android.gms:908)
07-05 14:17:49.856  1653  1663 E Auth    : 	at com.google.android.gms.auth.s.e(:com.google.android.gms:528)
07-05 14:17:49.856  1653  1663 E Auth    : 	at com.google.android.gms.auth.be.m.getAuthToken(:com.google.android.gms:201)
07-05 14:17:49.856  1653  1663 E Auth    : 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
07-05 14:17:49.856  1653  1663 E Auth    : 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
07-05 14:17:49.856  1653  1663 E Auth    : 	at android.os.Binder.execTransact(Binder.java:453)
,07-05 14:17:49.876  5788  5788 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,07-05 14:17:49.876  5788  5788 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
07-05 14:17:49.876  5788  5788 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 4.
,07-05 14:17:51.576   767  3520 D SSRM:n  : SIOP:: AP = 300, PST = 303, CUR = 300, LCD = 0
,07-05 14:18:00.006   767  1237 V AlarmManager: Expired Alarm result :8
,07-05 14:18:00.076   767  1764 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 14:18:01.646   767  3520 D SSRM:n  : SIOP:: AP = 300, PST = 302, CUR = 300, LCD = 0
,07-05 14:18:06.596   767  1604 E Watchdog: !@Sync 31 [07-05 14:18:06.608]
,07-05 14:18:09.876   767  1237 V AlarmManager: Expired Alarm result :4
,07-05 14:18:09.946  1380  1380 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
,07-05 14:18:09.946  1380  1380 I PERF    : received broadcast android.intent.action.TIME_TICK
07-05 14:18:09.946  1380  1380 D KeyguardUpdateMonitor: handleTimeUpdate
,07-05 14:18:09.966  1380  1380 D SecKeyguardClockView: onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,07-05 14:18:09.976  1380  1380 D SecKeyguardClockView: HomeTimezone(): 1
,07-05 14:18:09.986  1380  1380 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-05 14:18:09.986  1380  1380 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-05 14:18:09.986  1380  1380 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-05 14:18:09.986  1380  1380 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-05 14:18:09.986  1380  1380 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-05 14:18:09.996  1380  1380 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-05 14:18:09.996  1380  1380 D SecKeyguardStatusUtils: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-05 14:18:10.056  1380  1380 D SecKeyguardStatusUtils: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-05 14:18:10.556  1653  1653 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-05 14:18:10.566  1653  1653 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-05 14:18:10.576  1653  1653 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-05 14:18:10.596  1653  3945 E Auth    : [GoogleAccountDataServiceImpl] getToken() failed. Status BAD_AUTHENTICATION, Account: <ELLIDED:1197869880>, App: com.android.vending, Service: androidsecure
07-05 14:18:10.596  1653  3945 E Auth    : com.google.android.gms.auth.be.account.b.d: Long live credential not available.
07-05 14:18:10.596  1653  3945 E Auth    : 	at com.google.android.gms.auth.be.account.b.e.a(:com.google.android.gms:105)
07-05 14:18:10.596  1653  3945 E Auth    : 	at com.google.android.gms.auth.be.p.a(:com.google.android.gms:355)
07-05 14:18:10.596  1653  3945 E Auth    : 	at com.google.android.gms.auth.be.o.a(:com.google.android.gms:260)
07-05 14:18:10.596  1653  3945 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.y.a(:com.google.android.gms:197)
07-05 14:18:10.596  1653  3945 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.x.a(:com.google.android.gms:558)
07-05 14:18:10.596  1653  3945 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.x.a(:com.google.android.gms:196)
07-05 14:18:10.596  1653  3945 E Auth    : 	at com.google.android.gms.auth.o.a(:com.google.android.gms:276)
07-05 14:18:10.596  1653  3945 E Auth    : 	at com.google.android.gms.auth.o.a(:com.google.android.gms:196)
07-05 14:18:10.596  1653  3945 E Auth    : 	at com.google.android.gms.auth.t.a(:com.google.android.gms:498)
07-05 14:18:10.596  1653  3945 E Auth    : 	at com.google.android.gms.auth.s.a(:com.google.android.gms:908)
07-05 14:18:10.596  1653  3945 E Auth    : 	at com.google.android.gms.auth.s.e(:com.google.android.gms:528)
07-05 14:18:10.596  1653  3945 E Auth    : 	at com.google.android.gms.auth.be.m.getAuthToken(:com.google.android.gms:201)
07-05 14:18:10.596  1653  3945 E Auth    : 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
07-05 14:18:10.596  1653  3945 E Auth    : 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
07-05 14:18:10.596  1653  3945 E Auth    : 	at android.os.Binder.execTransact(Binder.java:453)
,07-05 14:18:10.616  5788  5788 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,07-05 14:18:10.616  5788  5788 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
07-05 14:18:10.616  5788  5788 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 5.
,07-05 14:18:11.726   767  3520 D SSRM:n  : SIOP:: AP = 300, PST = 301, CUR = 300, LCD = 0
,07-05 14:18:21.786   767  3520 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 300, LCD = 0
,07-05 14:18:30.636   767  1237 V AlarmManager: Expired Alarm result :4
,07-05 14:18:30.696   767  1826 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 14:18:30.696   767  1826 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4362, temperature: 297, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,07-05 14:18:30.706   767  1826 D BatteryService: online:4, current avg:300, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
,07-05 14:18:30.706   767  1826 D BatteryService: stay LED for fully charged
,07-05 14:18:30.706   767   767 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 14:18:30.716  1380  1380 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 14:18:30.716  1380  1380 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
07-05 14:18:30.716  1380  1380 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 14:18:30.726  2328  2328 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 14:18:30.726  2328  2834 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-05 14:18:30.736   767   767 I MotionRecognitionService: Plugged
,07-05 14:18:30.736   767   767 D MotionRecognitionService:   cableConnection= 1
07-05 14:18:30.736   767   767 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
07-05 14:18:30.736   767   767 D MotionRecognitionService: skip setTransmitPower. 
,07-05 14:18:30.736  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:18:30.736  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 14:18:30.736  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:18:30.896   767   778 I art     : Background partial concurrent mark sweep GC freed 73661(4MB) AllocSpace objects, 75(1736KB) LOS objects, 27% free, 42MB/58MB, paused 2.116ms total 143.392ms
,07-05 14:18:31.096  1653  1653 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-05 14:18:31.106  1653  1653 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-05 14:18:31.106  1653  1653 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-05 14:18:31.116  1653  2252 E Auth    : [GoogleAccountDataServiceImpl] getToken() failed. Status BAD_AUTHENTICATION, Account: <ELLIDED:1197869880>, App: com.android.vending, Service: androidsecure
07-05 14:18:31.116  1653  2252 E Auth    : com.google.android.gms.auth.be.account.b.d: Long live credential not available.
07-05 14:18:31.116  1653  2252 E Auth    : 	at com.google.android.gms.auth.be.account.b.e.a(:com.google.android.gms:105)
07-05 14:18:31.116  1653  2252 E Auth    : 	at com.google.android.gms.auth.be.p.a(:com.google.android.gms:355)
07-05 14:18:31.116  1653  2252 E Auth    : 	at com.google.android.gms.auth.be.o.a(:com.google.android.gms:260)
07-05 14:18:31.116  1653  2252 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.y.a(:com.google.android.gms:197)
07-05 14:18:31.116  1653  2252 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.x.a(:com.google.android.gms:558)
07-05 14:18:31.116  1653  2252 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.x.a(:com.google.android.gms:196)
07-05 14:18:31.116  1653  2252 E Auth    : 	at com.google.android.gms.auth.o.a(:com.google.android.gms:276)
07-05 14:18:31.116  1653  2252 E Auth    : 	at com.google.android.gms.auth.o.a(:com.google.android.gms:196)
07-05 14:18:31.116  1653  2252 E Auth    : 	at com.google.android.gms.auth.t.a(:com.google.android.gms:498)
07-05 14:18:31.116  1653  2252 E Auth    : 	at com.google.android.gms.auth.s.a(:com.google.android.gms:908)
07-05 14:18:31.116  1653  2252 E Auth    : 	at com.google.android.gms.auth.s.e(:com.google.android.gms:528)
07-05 14:18:31.116  1653  2252 E Auth    : 	at com.google.android.gms.auth.be.m.getAuthToken(:com.google.android.gms:201)
07-05 14:18:31.116  1653  2252 E Auth    : 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
07-05 14:18:31.116  1653  2252 E Auth    : 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
07-05 14:18:31.116  1653  2252 E Auth    : 	at android.os.Binder.execTransact(Binder.java:453)
,07-05 14:18:31.136  5788  5788 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,07-05 14:18:31.136  5788  5788 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
07-05 14:18:31.136  5788  5788 D Finsky  : [1] ContentSyncService$5.onFinished: Giving up after 6 failures.
,07-05 14:18:31.856   767  3520 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 300, LCD = 0
,07-05 14:18:32.356  1653  3264 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,07-05 14:18:33.226   304  1195 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
07-05 14:18:33.226   304  1195 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
07-05 14:18:33.226   304  1195 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,07-05 14:18:36.596   767  1604 E Watchdog: !@Sync 32 [07-05 14:18:36.612]
,07-05 14:18:38.446  1664  1768 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,07-05 14:18:41.916   767  3520 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 300, LCD = 0
,07-05 14:18:48.296   304  1195 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
07-05 14:18:48.296   304  1195 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
07-05 14:18:48.296   304  1195 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,07-05 14:18:51.966   767  3520 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 300, LCD = 0
,07-05 14:18:56.466   767  1237 V AlarmManager: Expired Alarm result :4
,07-05 14:18:56.586  6809  7910 I BooksSync: Starting books sync for 61035162, extras: ade
,07-05 14:18:56.626  1653  1653 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-05 14:18:56.626  1653  1653 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-05 14:18:56.646  1653  1663 E Auth    : [GoogleAccountDataServiceImpl] getToken() failed. Status BAD_AUTHENTICATION, Account: <ELLIDED:1197869880>, App: com.google.android.apps.books, Service: oauth2:https://www.googleapis.com/auth/books
07-05 14:18:56.646  1653  1663 E Auth    : com.google.android.gms.auth.be.account.b.d: Long live credential not available.
07-05 14:18:56.646  1653  1663 E Auth    : 	at com.google.android.gms.auth.be.account.b.e.a(:com.google.android.gms:105)
07-05 14:18:56.646  1653  1663 E Auth    : 	at com.google.android.gms.auth.be.p.a(:com.google.android.gms:355)
07-05 14:18:56.646  1653  1663 E Auth    : 	at com.google.android.gms.auth.be.o.a(:com.google.android.gms:260)
07-05 14:18:56.646  1653  1663 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.y.a(:com.google.android.gms:197)
07-05 14:18:56.646  1653  1663 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.x.a(:com.google.android.gms:558)
07-05 14:18:56.646  1653  1663 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.x.a(:com.google.android.gms:196)
07-05 14:18:56.646  1653  1663 E Auth    : 	at com.google.android.gms.auth.o.a(:com.google.android.gms:276)
07-05 14:18:56.646  1653  1663 E Auth    : 	at com.google.android.gms.auth.o.a(:com.google.android.gms:196)
07-05 14:18:56.646  1653  1663 E Auth    : 	at com.google.android.b.b.onTransact(:com.google.android.gms:137)
07-05 14:18:56.646  1653  1663 E Auth    : 	at android.os.Binder.execTransact(Binder.java:453)
,07-05 14:18:56.676  1653  2252 E Auth    : [GoogleAccountDataServiceImpl] getToken() failed. Status BAD_AUTHENTICATION, Account: <ELLIDED:1197869880>, App: com.google.android.apps.books, Service: oauth2:https://www.googleapis.com/auth/books
07-05 14:18:56.676  1653  2252 E Auth    : com.google.android.gms.auth.be.account.b.d: Long live credential not available.
07-05 14:18:56.676  1653  2252 E Auth    : 	at com.google.android.gms.auth.be.account.b.e.a(:com.google.android.gms:105)
07-05 14:18:56.676  1653  2252 E Auth    : 	at com.google.android.gms.auth.be.p.a(:com.google.android.gms:355)
07-05 14:18:56.676  1653  2252 E Auth    : 	at com.google.android.gms.auth.be.o.a(:com.google.android.gms:260)
07-05 14:18:56.676  1653  2252 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.y.a(:com.google.android.gms:197)
07-05 14:18:56.676  1653  2252 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.x.a(:com.google.android.gms:558)
07-05 14:18:56.676  1653  2252 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.x.a(:com.google.android.gms:196)
07-05 14:18:56.676  1653  2252 E Auth    : 	at com.google.android.gms.auth.o.a(:com.google.android.gms:276)
07-05 14:18:56.676  1653  2252 E Auth    : 	at com.google.android.gms.auth.o.a(:com.google.android.gms:196)
07-05 14:18:56.676  1653  2252 E Auth    : 	at com.google.android.b.b.onTransact(:com.google.android.gms:137)
07-05 14:18:56.676  1653  2252 E Auth    : 	at android.os.Binder.execTransact(Binder.java:453)
,07-05 14:18:56.696  6809  7911 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,07-05 14:18:56.696  6809  7910 E BooksSync: Soft error
07-05 14:18:56.696  6809  7910 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
07-05 14:18:56.696  6809  7910 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.zza(Unknown)
07-05 14:18:56.696  6809  7910 E BooksSync: Sync error
07-05 14:18:56.696  6809  7910 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
07-05 14:18:56.696  6809  7910 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.zza(Unknown)
,07-05 14:18:56.706  6809  7910 I BooksSync: Finished books sync
,07-05 14:18:56.706  6809  7917 I GcmRegistrationService: Handling Intent for action: com.google.android.books.GCM_REGISTER
,07-05 14:18:56.706  6809  7917 W GcmRegistrationHandler: Could not find device group in preferences; re-associating.
,07-05 14:18:56.716   767   862 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 1011209, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,07-05 14:18:56.726  1653  1663 E Auth    : [GoogleAccountDataServiceImpl] getToken() failed. Status BAD_AUTHENTICATION, Account: <ELLIDED:1197869880>, App: com.google.android.apps.books, Service: oauth2:https://www.googleapis.com/auth/gcm
07-05 14:18:56.726  1653  1663 E Auth    : com.google.android.gms.auth.be.account.b.d: Long live credential not available.
07-05 14:18:56.726  1653  1663 E Auth    : 	at com.google.android.gms.auth.be.account.b.e.a(:com.google.android.gms:105)
07-05 14:18:56.726  1653  1663 E Auth    : 	at com.google.android.gms.auth.be.p.a(:com.google.android.gms:355)
07-05 14:18:56.726  1653  1663 E Auth    : 	at com.google.android.gms.auth.be.o.a(:com.google.android.gms:260)
07-05 14:18:56.726  1653  1663 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.y.a(:com.google.android.gms:197)
07-05 14:18:56.726  1653  1663 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.x.a(:com.google.android.gms:558)
07-05 14:18:56.726  1653  1663 E Auth    : 	at com.google.android.gms.auth.firstparty.dataservice.x.a(:com.google.android.gms:196)
07-05 14:18:56.726  1653  1663 E Auth    : 	at com.google.android.gms.auth.o.a(:com.google.android.gms:276)
07-05 14:18:56.726  1653  1663 E Auth    : 	at com.google.android.gms.auth.o.a(:com.google.android.gms:196)
07-05 14:18:56.726  1653  1663 E Auth    : 	at com.google.android.b.b.onTransact(:com.google.android.gms:137)
07-05 14:18:56.726  1653  1663 E Auth    : 	at android.os.Binder.execTransact(Binder.java:453)
,07-05 14:18:56.726   767   862 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/sync/pending.xml.bak
,07-05 14:18:56.746  6809  7917 W BooksGcmUtils: Recoverable exception while getting auth token: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
,07-05 14:18:56.746  6809  7917 E GcmRegistrationHandler: Failed to register token for device group
07-05 14:18:56.746  6809  7917 E GcmRegistrationHandler: com.google.android.apps.books.gcm.GcmRegistrationHandler$GcmRequestException: Failed to update GCM device group: null auth token.
07-05 14:18:56.746  6809  7917 E GcmRegistrationHandler: 	at com.google.android.apps.books.gcm.GcmRegistrationHandler.addOrRemoveInstanceIdTokenForAccount(GcmRegistrationHandler.java:275)
07-05 14:18:56.746  6809  7917 E GcmRegistrationHandler: 	at com.google.android.apps.books.gcm.GcmRegistrationHandler.registerTokenForDeviceGroup(GcmRegistrationHandler.java:199)
07-05 14:18:56.746  6809  7917 E GcmRegistrationHandler: 	at com.google.android.apps.books.gcm.GcmRegistrationHandler.registerForDeviceGroup(GcmRegistrationHandler.java:126)
07-05 14:18:56.746  6809  7917 E GcmRegistrationHandler: 	at com.google.android.apps.books.gcm.GcmRegistrationIntentService.handleActionRegister(GcmRegistrationIntentService.java:135)
07-05 14:18:56.746  6809  7917 E GcmRegistrationHandler: 	at com.google.android.apps.books.gcm.GcmRegistrationIntentService.onHandleIntent(GcmRegistrationIntentService.java:94)
07-05 14:18:56.746  6809  7917 E GcmRegistrationHandler: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
07-05 14:18:56.746  6809  7917 E GcmRegistrationHandler: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-05 14:18:56.746  6809  7917 E GcmRegistrationHandler: 	at android.os.Looper.loop(Looper.java:158)
07-05 14:18:56.746  6809  7917 E GcmRegistrationHandler: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,07-05 14:18:56.756  3277  3292 W ResourcesManager: getTopLevelResources: /system/app/PlusOne/PlusOne.apk / 1.0 running in com.android.contacts rsrc of package null
,07-05 14:18:56.766  3277  3292 W ResourcesManager: getTopLevelResources: /system/app/PlusOne/PlusOne.apk / 1.0 running in com.android.contacts rsrc of package null
,07-05 14:18:56.766  3277  3292 W ResourcesManager: getTopLevelResources: /system/app/PlusOne/PlusOne.apk / 1.0 running in com.android.contacts rsrc of package null
,07-05 14:18:56.766  3277  3292 W ResourcesManager: getTopLevelResources: /system/app/PlusOne/PlusOne.apk / 1.0 running in com.android.contacts rsrc of package null
,07-05 14:18:56.766   767  1764 D SecContentProvider2: query(), uri = 11 selection = getMyKnoxAdmin
,07-05 14:18:59.986   767  1237 V AlarmManager: Expired Alarm result :8
,07-05 14:19:00.786   767  4844 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 14:19:02.056   767  3520 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 300, LCD = 0
,07-05 14:19:06.606   767  1604 E Watchdog: !@Sync 33 [07-05 14:19:06.618]
,07-05 14:19:12.146   767  3520 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 300, LCD = 0
,07-05 14:19:22.206   767  3520 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 300, LCD = 0
,07-05 14:19:30.856   767  1466 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 14:19:30.866   767  1466 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4361, temperature: 297, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,07-05 14:19:30.866   767  1466 D BatteryService: online:4, current avg:300, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
,07-05 14:19:30.866   767   767 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 14:19:30.886   767   767 I MotionRecognitionService: Plugged
,07-05 14:19:30.886   767   767 D MotionRecognitionService:   cableConnection= 1
,07-05 14:19:30.886   767   767 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,07-05 14:19:30.896   767  1466 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 30ms
,07-05 14:19:30.896   767   767 D MotionRecognitionService: skip setTransmitPower. 
,07-05 14:19:30.896   767  1466 D BatteryService: stay LED for fully charged
,07-05 14:19:30.916  1380  1380 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 14:19:30.916  1380  1380 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
07-05 14:19:30.916  1380  1380 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 14:19:30.926  2328  2328 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 14:19:30.926  2328  2834 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-05 14:19:30.936  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:19:30.936  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 14:19:30.936  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:19:32.256   767  3520 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 300, LCD = 0
,07-05 14:19:36.616   767  1604 E Watchdog: !@Sync 34 [07-05 14:19:36.622]
,07-05 14:19:38.496  1664  1768 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,07-05 14:19:42.316   767  3520 D SSRM:n  : SIOP:: AP = 290, PST = 299, CUR = 300, LCD = 0
,07-05 14:19:52.376   767  3520 D SSRM:n  : SIOP:: AP = 290, PST = 298, CUR = 300, LCD = 0
,07-05 14:20:00.936   767  1767 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 14:20:00.946   767  1767 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4360, temperature: 297, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,07-05 14:20:00.946   767  1767 D BatteryService: online:4, current avg:300, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
,07-05 14:20:00.946   767   767 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 14:20:00.966   767   767 I MotionRecognitionService: Plugged
,07-05 14:20:00.966   767   767 D MotionRecognitionService:   cableConnection= 1
,07-05 14:20:00.966   767   767 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,07-05 14:20:00.966   767   767 D MotionRecognitionService: skip setTransmitPower. 
,07-05 14:20:00.976   767  1767 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 31ms
,07-05 14:20:00.976   767  1767 D BatteryService: stay LED for fully charged
,07-05 14:20:00.986  1380  1380 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 14:20:00.986  1380  1380 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,07-05 14:20:00.986  1380  1380 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 14:20:01.016  2328  2328 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 14:20:01.016  2328  2834 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-05 14:20:01.016  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:20:01.026  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 14:20:01.026  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:20:02.446   767  3520 D SSRM:n  : SIOP:: AP = 290, PST = 297, CUR = 300, LCD = 0
,07-05 14:20:06.616   767  1604 E Watchdog: !@Sync 35 [07-05 14:20:06.629]
,07-05 14:20:12.506   767  3520 D SSRM:n  : SIOP:: AP = 290, PST = 296, CUR = 300, LCD = 0
,07-05 14:20:22.566   767  3520 D SSRM:n  : SIOP:: AP = 290, PST = 295, CUR = 300, LCD = 0
,07-05 14:20:31.016   767  1826 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 14:20:31.026   767  1826 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4361, temperature: 296, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,07-05 14:20:31.026   767  1826 D BatteryService: online:4, current avg:300, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
,07-05 14:20:31.026   767   767 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 14:20:31.046   767   767 I MotionRecognitionService: Plugged
,07-05 14:20:31.046   767   767 D MotionRecognitionService:   cableConnection= 1
,07-05 14:20:31.046   767   767 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,07-05 14:20:31.046   767   767 D MotionRecognitionService: skip setTransmitPower. 
,07-05 14:20:31.056   767  1826 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 30ms
,07-05 14:20:31.056   767  1826 D BatteryService: stay LED for fully charged
,07-05 14:20:31.066  1380  1380 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 14:20:31.066  1380  1380 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
07-05 14:20:31.066  1380  1380 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 14:20:31.076  2328  2328 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 14:20:31.076  2328  2834 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-05 14:20:31.086  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:20:31.086  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:20:31.096  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:20:32.646   767  3520 D SSRM:n  : SIOP:: AP = 290, PST = 294, CUR = 300, LCD = 0
,07-05 14:20:36.626   767  1604 E Watchdog: !@Sync 36 [07-05 14:20:36.633]
,07-05 14:20:38.526  1664  1768 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,07-05 14:20:42.706   767  3520 D SSRM:n  : SIOP:: AP = 290, PST = 293, CUR = 300, LCD = 0
,07-05 14:20:52.766   767  3520 D SSRM:n  : SIOP:: AP = 290, PST = 292, CUR = 300, LCD = 0
,07-05 14:21:01.086   767   785 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 14:21:01.096   767   785 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4360, temperature: 296, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,07-05 14:21:01.096   767   785 D BatteryService: online:4, current avg:300, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
,07-05 14:21:01.106   767   785 D BatteryService: stay LED for fully charged
,07-05 14:21:01.106   767   767 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 14:21:01.126   767   767 I MotionRecognitionService: Plugged
,07-05 14:21:01.136   767   767 D MotionRecognitionService:   cableConnection= 1
,07-05 14:21:01.136   767   767 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,07-05 14:21:01.136   767   767 D MotionRecognitionService: skip setTransmitPower. 
,07-05 14:21:01.146  1380  1380 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 14:21:01.146  1380  1380 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,07-05 14:21:01.156  1380  1380 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 14:21:01.176  2328  2328 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 14:21:01.176  2328  2834 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-05 14:21:01.186  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:21:01.186  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 14:21:01.186  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:21:02.826   767  3520 D SSRM:n  : SIOP:: AP = 290, PST = 291, CUR = 300, LCD = 0
,07-05 14:21:06.626   767  1604 E Watchdog: !@Sync 37 [07-05 14:21:06.640]
,07-05 14:21:12.926   767  3520 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,07-05 14:21:22.986   767  3520 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,07-05 14:21:31.176   767  1591 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 14:21:33.066   767  3520 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,07-05 14:21:33.086   304  1195 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
07-05 14:21:33.086   304  1195 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
07-05 14:21:33.086   304  1195 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,07-05 14:21:36.636   767  1604 E Watchdog: !@Sync 38 [07-05 14:21:36.646]
,07-05 14:21:38.626  1664  1768 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,07-05 14:21:38.766  1664  1768 E ContactsProvider_EventLog: Flush buffer to file cnt : 5 size : 1Kb duration : 125ms lastUpdatedAfter : 161985ms
,07-05 14:21:43.156   767  3520 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,07-05 14:21:53.216   767  3520 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,07-05 14:21:59.986   767  1237 V AlarmManager: Expired Alarm result :8
,07-05 14:21:59.986   767  1237 V AlarmManager: No more alarm at this time. Why did you wake up?. nowELAPSED=1194734 batch.start=1455593
,07-05 14:22:00.006  1380  1380 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
,07-05 14:22:00.006  1380  1380 I PERF    : received broadcast android.intent.action.TIME_TICK
,07-05 14:22:00.006  1380  1380 D KeyguardUpdateMonitor: handleTimeUpdate
,07-05 14:22:00.046  1380  1380 D SecKeyguardClockView: onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,07-05 14:22:00.066  1380  1380 D SecKeyguardClockView: HomeTimezone(): 1
,07-05 14:22:00.086  1380  1380 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-05 14:22:00.086  1380  1380 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-05 14:22:00.086  1380  1380 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-05 14:22:00.096  1380  1380 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-05 14:22:00.096  1380  1380 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-05 14:22:00.096  1380  1380 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-05 14:22:00.096  1380  1380 D SecKeyguardStatusUtils: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-05 14:22:00.156  1380  1380 D SecKeyguardStatusUtils: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,07-05 14:22:01.266   767  4119 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 14:22:01.266   767  4119 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4361, temperature: 296, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,07-05 14:22:01.266   767  4119 D BatteryService: online:4, current avg:300, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
,07-05 14:22:01.276   767   767 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 14:22:01.286   767   767 I MotionRecognitionService: Plugged
,07-05 14:22:01.286   767   767 D MotionRecognitionService:   cableConnection= 1
,07-05 14:22:01.296   767   767 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,07-05 14:22:01.296   767   767 D MotionRecognitionService: skip setTransmitPower. 
,07-05 14:22:01.296   767  4119 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 32ms
,07-05 14:22:01.306   767  4119 D BatteryService: stay LED for fully charged
,07-05 14:22:01.306  1380  1380 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 14:22:01.316  1380  1380 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,07-05 14:22:01.316  1380  1380 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 14:22:01.346  2328  2328 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 14:22:01.346  2328  2834 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-05 14:22:01.346  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:22:01.346  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 14:22:01.346  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:22:03.276   767  3520 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,07-05 14:22:06.636   767  1604 E Watchdog: !@Sync 39 [07-05 14:22:06.651]
,07-05 14:22:13.336   767  3520 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,07-05 14:22:14.856   304  1195 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
07-05 14:22:14.856   304  1195 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
07-05 14:22:14.856   304  1195 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,07-05 14:22:21.166   767  1231 D TimaService: TIMA: TimaService scheduler is intialized. 
,07-05 14:22:21.166   767  1231 D TimaService: TIMA: checkEvent, operation: 50000 subject: 10000
,07-05 14:22:21.166   767  1230 D TimaService: TimaServiceHandler.handleMessage what =1
,07-05 14:22:22.666   767  1231 I TLC_TIMA_PKM_measure_kernel: TIMA: response_id = 3
,07-05 14:22:22.666   767  1231 I TLC_TIMA_PKM_measure_kernel: TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,07-05 14:22:22.676   767  1231 D TimaService: TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,07-05 14:22:22.686   767  1231 D TimaService: TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,07-05 14:22:23.396   767  3520 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,07-05 14:22:26.776   304  1195 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
07-05 14:22:26.776   304  1195 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
07-05 14:22:26.776   304  1195 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,07-05 14:22:31.336   767  4844 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 14:22:31.346   767  4844 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4361, temperature: 295, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,07-05 14:22:31.346   767  4844 D BatteryService: online:4, current avg:300, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
,07-05 14:22:31.346   767   767 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 14:22:31.356   767   767 I MotionRecognitionService: Plugged
,07-05 14:22:31.356   767   767 D MotionRecognitionService:   cableConnection= 1
,07-05 14:22:31.366   767   767 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,07-05 14:22:31.366   767   767 D MotionRecognitionService: skip setTransmitPower. 
,07-05 14:22:31.366   767  4844 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 31ms
,07-05 14:22:31.376   767  4844 D BatteryService: stay LED for fully charged
,07-05 14:22:31.396  1380  1380 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 14:22:31.396  1380  1380 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
07-05 14:22:31.396  1380  1380 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 14:22:31.406  2328  2328 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 14:22:31.406  2328  2834 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-05 14:22:31.416  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:22:31.416  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 14:22:31.416  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:22:33.186   767   862 I UsageStatsService: User[0] Flushing usage stats to disk
,07-05 14:22:33.456   767  3520 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,07-05 14:22:36.646   767  1604 E Watchdog: !@Sync 40 [07-05 14:22:36.657]
,07-05 14:22:38.826  1664  1768 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,07-05 14:22:41.816   304  1195 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'LABEL' not found
07-05 14:22:41.816   304  1195 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'TIME_NS' not found
07-05 14:22:41.816   304  1195 E NetlinkEvent: NetlinkEvent::FindParam(): Parameter 'UID' not found
,07-05 14:22:43.526   767  3520 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,07-05 14:22:53.586   767  3520 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,07-05 14:22:59.986   767  1237 V AlarmManager: Expired Alarm result :8
,07-05 14:23:01.426   767  1466 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 14:23:03.686   767  3520 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,07-05 14:23:06.646   767  1604 E Watchdog: !@Sync 41 [07-05 14:23:06.661]
,07-05 14:23:13.756   767  3520 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,07-05 14:23:23.806   767  3520 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,07-05 14:23:31.516   767  4844 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 14:23:31.516   767  4844 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4362, temperature: 295, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,07-05 14:23:31.516   767  4844 D BatteryService: online:4, current avg:300, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
,07-05 14:23:31.526   767   767 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 14:23:31.536   767   767 I MotionRecognitionService: Plugged
,07-05 14:23:31.536   767   767 D MotionRecognitionService:   cableConnection= 1
,07-05 14:23:31.536   767   767 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,07-05 14:23:31.546   767   767 D MotionRecognitionService: skip setTransmitPower. 
,07-05 14:23:31.546   767  4844 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 34ms
,07-05 14:23:31.546   767  4844 D BatteryService: stay LED for fully charged
,07-05 14:23:31.566  1380  1380 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 14:23:31.566  1380  1380 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,07-05 14:23:31.566  1380  1380 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 14:23:31.596  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:23:31.596  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:23:31.596  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:23:31.606  2328  2328 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 14:23:31.606  2328  2834 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-05 14:23:33.866   767  3520 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,07-05 14:23:36.656   767  1604 E Watchdog: !@Sync 42 [07-05 14:23:36.666]
,07-05 14:23:38.946  1664  1768 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,07-05 14:23:43.926   767  3520 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,07-05 14:23:53.986   767  3520 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,07-05 14:24:01.586   767  4119 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 14:24:01.586   767  4119 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4361, temperature: 295, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,07-05 14:24:01.596   767  4119 D BatteryService: online:4, current avg:300, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
,07-05 14:24:01.596   767   767 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 14:24:01.606   767   767 I MotionRecognitionService: Plugged
,07-05 14:24:01.606   767   767 D MotionRecognitionService:   cableConnection= 1
,07-05 14:24:01.616   767   767 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,07-05 14:24:01.616   767   767 D MotionRecognitionService: skip setTransmitPower. 
,07-05 14:24:01.616   767  4119 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 32ms
,07-05 14:24:01.636   767  4119 D BatteryService: stay LED for fully charged
,07-05 14:24:01.646  1380  1380 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 14:24:01.646  1380  1380 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
07-05 14:24:01.646  1380  1380 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 14:24:01.666  2328  2328 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 14:24:01.666  2328  2834 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-05 14:24:01.676  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:24:01.676  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:24:01.676  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:24:04.036   767  3520 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,07-05 14:24:06.656   767  1604 E Watchdog: !@Sync 43 [07-05 14:24:06.670]
,07-05 14:24:14.146   767  3520 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,07-05 14:24:24.216   767  3520 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,07-05 14:24:31.656   767  1466 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 14:24:31.666   767  1466 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4360, temperature: 295, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,07-05 14:24:31.666   767  1466 D BatteryService: online:4, current avg:300, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
,07-05 14:24:31.666   767   767 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 14:24:31.676   767   767 I MotionRecognitionService: Plugged
,07-05 14:24:31.686   767   767 D MotionRecognitionService:   cableConnection= 1
,07-05 14:24:31.686   767   767 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,07-05 14:24:31.686   767   767 D MotionRecognitionService: skip setTransmitPower. 
,07-05 14:24:31.696   767  1466 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 28ms
,07-05 14:24:31.696   767  1466 D BatteryService: stay LED for fully charged
,07-05 14:24:31.706  1380  1380 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 14:24:31.706  1380  1380 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,07-05 14:24:31.716  1380  1380 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 14:24:31.746  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:24:31.746  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:24:31.746  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:24:31.746  2328  2328 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 14:24:31.756  2328  2834 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-05 14:24:34.276   767  3520 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,07-05 14:24:36.666   767  1604 E Watchdog: !@Sync 44 [07-05 14:24:36.676]
,07-05 14:24:39.056  1664  1768 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,07-05 14:24:39.186  1664  1768 E ContactsProvider_EventLog: Flush buffer to file cnt : 5 size : 1Kb duration : 109ms lastUpdatedAfter : 180415ms
,07-05 14:24:44.376   767  3520 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,07-05 14:24:54.426   767  3520 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,07-05 14:25:01.736   767   785 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 14:25:01.746   767   785 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4361, temperature: 295, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,07-05 14:25:01.746   767   785 D BatteryService: online:4, current avg:300, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
,07-05 14:25:01.746   767   767 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 14:25:01.766   767   767 I MotionRecognitionService: Plugged
,07-05 14:25:01.766   767   767 D MotionRecognitionService:   cableConnection= 1
,07-05 14:25:01.766   767   785 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 26ms
,07-05 14:25:01.776   767   767 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,07-05 14:25:01.776   767   767 D MotionRecognitionService: skip setTransmitPower. 
,07-05 14:25:01.776   767   785 D BatteryService: stay LED for fully charged
,07-05 14:25:01.796  1380  1380 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 14:25:01.796  1380  1380 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
07-05 14:25:01.796  1380  1380 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 14:25:01.806  2328  2328 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 14:25:01.806  2328  2834 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-05 14:25:01.816  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:25:01.816  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 14:25:01.816  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:25:04.486   767  3520 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,07-05 14:25:06.666   767  1604 E Watchdog: !@Sync 45 [07-05 14:25:06.680]
,07-05 14:25:14.546   767  3520 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,07-05 14:25:24.596   767  3520 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,07-05 14:25:31.816   767  1767 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 14:25:31.826   767  1767 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4360, temperature: 294, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,07-05 14:25:31.826   767  1767 D BatteryService: online:4, current avg:300, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
,07-05 14:25:31.826   767   767 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 14:25:31.846   767   767 I MotionRecognitionService: Plugged
,07-05 14:25:31.846   767   767 D MotionRecognitionService:   cableConnection= 1
,07-05 14:25:31.846   767  1767 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 26ms
,07-05 14:25:31.846   767   767 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,07-05 14:25:31.856   767   767 D MotionRecognitionService: skip setTransmitPower. 
,07-05 14:25:31.856   767  1767 D BatteryService: stay LED for fully charged
,07-05 14:25:31.866  1380  1380 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 14:25:31.866  1380  1380 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,07-05 14:25:31.876  1380  1380 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 14:25:31.896  2328  2328 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 14:25:31.896  2328  2834 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-05 14:25:31.906  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:25:31.906  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 14:25:31.906  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:25:34.666   767  3520 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,07-05 14:25:36.676   767  1604 E Watchdog: !@Sync 46 [07-05 14:25:36.687]
,07-05 14:25:39.266  1664  1768 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,07-05 14:25:44.736   767  3520 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,07-05 14:25:54.796   767  3520 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,07-05 14:26:01.896   767  1764 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 14:26:01.906   767  1764 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4361, temperature: 294, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,07-05 14:26:01.906   767  1764 D BatteryService: online:4, current avg:300, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
,07-05 14:26:01.906   767   767 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 14:26:01.916   767   767 I MotionRecognitionService: Plugged
,07-05 14:26:01.926   767   767 D MotionRecognitionService:   cableConnection= 1
,07-05 14:26:01.926   767   767 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,07-05 14:26:01.926   767   767 D MotionRecognitionService: skip setTransmitPower. 
,07-05 14:26:01.936   767  1764 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 29ms
,07-05 14:26:01.936   767  1764 D BatteryService: stay LED for fully charged
,07-05 14:26:01.946  1380  1380 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 14:26:01.946  1380  1380 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
07-05 14:26:01.946  1380  1380 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 14:26:01.956  2328  2328 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 14:26:01.956  2328  2834 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-05 14:26:01.966  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:26:01.966  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 14:26:01.966  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:26:04.846   767  3520 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,07-05 14:26:06.676   767  1604 E Watchdog: !@Sync 47 [07-05 14:26:06.691]
,07-05 14:26:14.916   767  3520 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,07-05 14:26:20.846   767  1237 V AlarmManager: Expired Alarm result :8
,07-05 14:26:24.966   767  3520 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,07-05 14:26:31.976   767  1679 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 14:26:35.066   767  3520 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,07-05 14:26:36.686   767  1604 E Watchdog: !@Sync 48 [07-05 14:26:36.696]
,07-05 14:26:39.306  1664  1768 D ContactsProvider_EventLog: contents_sample_state: [contacts(0) raw_contacts(0) raw_contacts deleted(0) data(0) accounts({}) accounts deleted({}) ]
,07-05 14:26:45.116   767  3520 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,07-05 14:26:55.176   767  3520 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,07-05 14:27:02.056   767  1764 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 14:27:02.066   767  1764 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4360, temperature: 294, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,07-05 14:27:02.066   767  1764 D BatteryService: online:4, current avg:300, charge type:0, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:300
,07-05 14:27:02.066   767   767 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 14:27:02.086   767   767 I MotionRecognitionService: Plugged
,07-05 14:27:02.086   767   767 D MotionRecognitionService:   cableConnection= 1
,07-05 14:27:02.086   767   767 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
,07-05 14:27:02.096   767  1764 D BatteryService: Excessive delay in BatteryService : sendIntentLocked(): 31ms
,07-05 14:27:02.096   767   767 D MotionRecognitionService: skip setTransmitPower. 
,07-05 14:27:02.096   767  1764 D BatteryService: stay LED for fully charged
,07-05 14:27:02.106  1380  1380 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 14:27:02.106  1380  1380 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,07-05 14:27:02.116  1380  1380 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 14:27:02.146  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:27:02.146  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 14:27:02.146  1380  1380 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:27:02.146  2328  2328 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 14:27:02.146  2328  2834 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,07-05 14:27:05.226   767  3520 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,07-05 14:27:06.686   767  1604 E Watchdog: !@Sync 49 [07-05 14:27:06.700]
,07-05 14:27:15.296   767  3520 D SSRM:n  : SIOP:: AP = 290, PST = 290, CUR = 300, LCD = 0
,07-05 14:27:21.166   767  1231 D TimaService: TIMA: TimaService scheduler is intialized. 
,07-05 14:27:21.166   767  1231 D TimaService: TIMA: checkEvent, operation: 50000 subject: 10000
,07-05 14:27:21.176   767  1230 D TimaService: TimaServiceHandler.handleMessage what =1
,TIME-OUT KILL (timeout was 1400000ms),07-05 14:27:22.526  2334  2334 E audit   : type=1400 msg=audit(1467721642.516:295): avc:  denied  { execmod } for  pid=7964 comm="app_process" path="/system/lib/lib_SoundAlive_ver118t.so" dev="mmcblk0p23" ino=1663 scontext=u:r:shell:s0 tcontext=u:object_r:system_file:s0 tclass=file permissive=0
07-05 14:27:22.526  2334  2334 E audit   :  SEPF_SECMOBILE_6.0.1_0011
07-05 14:27:22.526  2334  2334 E audit   : type=1300 msg=audit(1467721642.516:295): arch=40000028 syscall=125 per=800008 success=no exit=-13 a0=b3f4c000 a1=51000 a2=5 a3=4 items=0 ppid=3676 ppcomm=adbd pid=7964 auid=4294967295 uid=2000 gid=2000 euid=2000 suid=2000 fsuid=2000 egid=2000 sgid=2000 fsgid=2000 tty=pts1 ses=4294967295 comm="app_process" exe="/system/bin/app_process32" subj=u:r:shell:s0 key=(null)
07-05 14:27:22.526  2334  2334 E audit   : type=1327 msg=audit(1467721642.516:295): proctitle=6170705F70726F63657373002F73797374656D2F62696E00636F6D2E616E64726F69642E636F6D6D616E64732E706D2E506D00756E696E7374616C6C00636F6D2E746573742E7468616C6974657374
07-05 14:27:22.526  2334  2334 E audit   : type=1320 msg=audit(1467721642.516:295): 
07-05 14:27:22.576  2334  2334 E audit   : type=1400 msg=audit(1467721642.576:296): avc:  denied  { execmod } for  pid=7964 comm="app_process" path="/system/lib/lib_SoundAlive_ver118t.so" dev="mmcblk0p23" ino=1663 scontext=u:r:shell:s0 tcontext=u:object_r:system_file:s0 tclass=file permissive=0
07-05 14:27:22.576  2334  2334 E audit   :  SEPF_SECMOBILE_6.0.1_0011
07-05 14:27:22.576  2334  2334 E audit   : type=1300 msg=audit(1467721642.576:296): arch=40000028 syscall=125 per=800008 success=no exit=-13 a0=b3f0c000 a1=51000 a2=5 a3=4 items=0 ppid=3676 ppcomm=adbd pid=7964 auid=4294967295 uid=2000 gid=2000 euid=2000 suid=2000 fsuid=2000 egid=2000 sgid=2000 fsgid=2000 tty=pts1 ses=4294967295 comm="app_process" exe="/system/bin/app_process32" subj=u:r:shell:s0 key=(null)
07-05 14:27:22.576  2334  2334 E audit   : type=1327 msg=audit(1467721642.576:296): proctitle=6170705F70726F63657373002F73797374656D2F62696E00636F6D2E616E64726F69642E636F6D6D616E64732E706D2E506D00756E696E7374616C6C00636F6D2E746573742E7468616C6974657374
07-05 14:27:22.576  2334  2334 E audit   : type=1320 msg=audit(1467721642.576:296): 
07-05 14:27:22.626  2334  2334 E audit   : type=1400 msg=audit(1467721642.626:297): avc:  denied  { execmod } for  pid=7964 comm="app_process" path="/system/lib/lib_SoundAlive_ver118t.so" dev="mmcblk0p23" ino=1663 scontext=u:r:shell:s0 tcontext=u:object_r:system_file:s0 tclass=file permissive=0
07-05 14:27:22.626  2334  2334 E audit   :  SEPF_SECMOBILE_6.0.1_0011
07-05 14:27:22.626  7964  7964 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
07-05 14:27:22.626  2334  2334 E audit   : type=1300 msg=audit(1467721642.626:297): arch=40000028 syscall=125 per=800008 success=no exit=-13 a0=b3f0c000 a1=51000 a2=5 a3=4 items=0 ppid=3676 ppcomm=adbd pid=7964 auid=4294967295 uid=2000 gid=2000 euid=2000 suid=2000 fsuid=2000 egid=2000 sgid=2000 fsgid=2000 tty=pts1 ses=4294967295 comm="app_process" exe="/system/bin/app_process32" subj=u:r:shell:s0 key=(null)
07-05 14:27:22.626  2334  2334 E audit   : type=1327 msg=audit(1467721642.626:297): proctitle=6170705F70726F63657373002F73797374656D2F62696E00636F6D2E616E64726F69642E636F6D6D616E64732E706D2E506D00756E696E7374616C6C00636F6D2E746573742E7468616C6974657374
07-05 14:27:22.626  2334  2334 E audit   : type=1320 msg=audit(1467721642.626:297): 
07-05 14:27:22.636  7964  7964 D AndroidRuntime: CheckJNI is OFF
07-05 14:27:22.636  7964  7964 D AndroidRuntime: readGMSProperty: start
07-05 14:27:22.636  7964  7964 D AndroidRuntime: readGMSProperty: already setted!!
07-05 14:27:22.636  7964  7964 D AndroidRuntime: propertySet: couldn't set property (it is from app)
07-05 14:27:22.636  7964  7964 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
07-05 14:27:22.636  7964  7964 D AndroidRuntime: readGMSProperty: end
07-05 14:27:22.636  7964  7964 D AndroidRuntime: addProductProperty: start
07-05 14:27:22.636  7964  7964 W art     : 70aa4000-71821000 rw-p 00000000 b3:1a 130592     /data/dalvik-cache/arm/system@framework@boot.art
07-05 14:27:22.636  7964  7964 W art     : aed73000-b1c99000 r--p 00000000 b3:17 579        /system/framework/arm/boot.oat
07-05 14:27:22.636  7964  7964 W art     : b1c99000-b3f08000 r-xp 02f26000 b3:17 579        /system/framework/arm/boot.oat
07-05 14:27:22.636  7964  7964 W art     : b3f08000-b3f09000 rw-p 05195000 b3:17 579        /system/framework/arm/boot.oat
07-05 14:27:22.636  7964  7964 W art     : b3f09000-b3f0a000 r--p 00000000 00:00 0          [anon:linker_alloc]
07-05 14:27:22.636  7964  7964 W art     : b423b000-b4264000 r--p 00d7d000 b3:1a 130592     /data/dalvik-cache/arm/system@framework@boot.art
07-05 14:27:22.636  7964  7964 W art     : b4264000-b46b2000 r-xp 00000000 b3:17 594        /system/lib/libart.so
07-05 14:27:22.636  7964  7964 W art     : b46b2000-b46b3000 ---p 00000000 00:00 0 
07-05 14:27:22.636  7964  7964 W art     : b46b3000-b46bd000 r--p 0044e000 b3:17 594        /system/lib/libart.so
07-05 14:27:22.636  7964  7964 W art     : b46bd000-b46be000 rw-p 00458000 b3:17 594        /system/lib/libart.so
07-05 14:27:22.646  7964  7964 W art     : b46be000-b46c0000 rw-p 00000000 00:00 0 
07-05 14:27:22.646  7964  7964 W art     : b46c0000-b47c0000 rw-p 00000000 00:00 0          [anon:libc_malloc]
07-05 14:27:22.646  7964  7964 W art     : b47df000-b47e2000 r-xp 00000000 b3:17 2411       /system/lib/libsigchain.so
07-05 14:27:22.646  7964  7964 W art     : b47e2000-b47e3000 r--p 00002000 b3:17 2411       /system/lib/libsigchain.so
07-05 14:27:22.646  7964  7964 W art     : b47e3000-b47e4000 rw-p 00003000 b3:17 2411       /system/lib/libsigchain.so
07-05 14:27:22.646  7964  7964 W art     : b47e4000-b47e5000 r--p 00000000 00:00 0 
07-05 14:27:22.646  7964  7964 W art     : b47e5000-b4805000 r--s 00000000 00:0b 6702       /dev/__properties__
07-05 14:27:22.646  7964  7964 W art     : b4805000-b5216000 r-xp 00000000 b3:17 2806       /system/lib/libLLVM.so
07-05 14:27:22.646  7964  7964 W art     : b5216000-b5217000 ---p 00000000 00:00 0 
07-05 14:27:22.646  7964  7964 W art     : b5217000-b5260000 r--p 00a11000 b3:17 2806       /system/lib/libLLVM.so
07-05 14:27:22.646  7964  7964 W art     : b5260000-b5261000 rw-p 00a5a000 b3:17 2806       /system/lib/libLLVM.so
07-05 14:27:22.646  7964  7964 W art     : b5261000-b5269000 rw-p 00000000 00:00 0 
07-05 14:27:22.646  7964  7964 W art     : b5269000-b526a000 r--p 00000000 00:00 0          [anon:linker_alloc]
07-05 14:27:22.646  7964  7964 W art     : b526a000-b529f000 r-xp 00000000 b3:17 715        /system/lib/libbcinfo.so
07-05 14:27:22.646  7964  7964 W art     : b529f000-b52a0000 ---p 00000000 00:00 0 
07-05 14:27:22.646  7964  7964 W art     : b52a0000-b52a1000 r--p 00035000 b3:17 715        /system/lib/libbcinfo.so
07-05 14:27:22.646  7964  7964 W art     : b52a1000-b52a2000 rw-p 00036000 b3:17 715        /system/lib/libbcinfo.so
07-05 14:27:22.646  7964  7964 W art     : b52a2000-b52fa000 r-xp 00000000 b3:17 2786       /system/lib/libbcc.so
07-05 14:27:22.646  7964  7964 W art     : b52fa000-b52fb000 ---p 00000000 00:00 0 
07-05 14:27:22.646  7964  7964 W art     : b52fb000-b52fc000 r--p 00058000 b3:17 2786       /system/lib/libbcc.so
07-05 14:27:22.646  7964  7964 W art     : b52fc000-b52fd000 rw-p 00059000 b3:17 2786       /system/lib/libbcc.so
07-05 14:27:22.646  7964  7964 W art     : b52fe000-b5304000 r-xp 00000000 b3:17 32         /system/lib/lib_SamsungVAD_v01009.so
07-05 14:27:22.646  7964  7964 W art     : b5304000-b5305000 r--p 00005000 b3:17 32         /system/lib/lib_SamsungVAD_v01009.so
07-05 14:27:22.646  7964  7964 W art     : b5305000-b5306000 rw-p 00006000 b3:17 32         /system/lib/lib_SamsungVAD_v01009.so
07-05 14:27:22.646  7964  7964 W art     : b5306000-b5308000 rw-p 00000000 00:00 0 
07-05 14:27:22.646  7964  7964 W art     : b5309000-b5313000 r-xp 00000000 b3:17 979        /system/lib/libcommon_time_client.so
07-05 14:27:22.646  7964  7964 W art     : b5313000-b5316000 r--p 00009000 b3:17 979        /system/lib/libcommon_time_client.so
07-05 14:27:22.646  7964  7964 W art     : b5316000-b5317000 rw-p 0000c000 b3:17 979        /system/lib/libcommon_time_client.so
07-05 14:27:22.646  7964  7964 W art     : b5318000-b532f000 r-xp 00000000 b3:17 2934       /system/lib/libprotobuf-cpp-lite.so
07-05 14:27:22.646  7964  7964 W art     : b532f000-b5330000 ---p 00000000 00:00 0 
07-05 14:27:22.646  7964  7964 W art     : b5330000-b5331000 r--p 00017000 b3:17 2934       /system/lib/libprotobuf-cpp-lite.so
07-05 14:27:22.646  7964  7964 W art     : b5331000-b5332000 rw-p 00018000 b3:17 2934       /system/lib/libprotobuf-cpp-lite.so
07-05 14:27:22.646  7964  7964 W art     : b5333000-b533d000 r-xp 00000000 b3:17 2679       /system/lib/libsec_km.so
07-05 14:27:22.646  7964  7964 W art     : b533d000-b533e000 r--p 00009000 b3:17 2679       /system/lib/libsec_km.so
07-05 14:27:22.646  7964  7964 W art     : b533e000-b533f000 rw-p 0000a000 b3:17 2679       /system/lib/libsec_km.so
07-05 14:27:22.646  7964  7964 W art     : b533f000-b5343000 r-xp 00000000 b3:17 2890       /system/lib/libSEF4MP4.so
07-05 14:27:22.646  7964  7964 W art     : b5343000-b5344000 r--p 00003000 b3:17 2890       /system/lib/libSEF4MP4.so
07-05 14:27:22.646  7964  7964 W art     : b5344000-b5345000 rw-p 00004000 b3:17 2890       /system/lib/libSEF4MP4.so
07-05 14:27:22.646  7964  7964 W art     : b5345000-b535b000 r-xp 00000000 b3:17 335        /system/lib/libSEF.so
07-05 14:27:22.646  7964  7964 W art     : b535b000-b535c000 r--p 00015000 b3:17 335        /system/lib/libSEF.so
07-05 14:27:22.646  7964  7964 W art     : b535c000-b535d000 rw-p 00016000 b3:17 335        /system/lib/libSEF.so
07-05 14:27:22.646  7964  7964 W art     : b535d000-b536a000 r-xp 00000000 b3:17 965        /system/lib/libsfextcp.so
07-05 14:27:22.646  7964  7964 W art     : b536a000-b536b000 r--p 0000c000 b3:17 965        /system/lib/libsfextcp.so
07-05 14:27:22.646  7964  7964 W art     : b536b000-b536c000 rw-p 0000d000 b3:17 965        /system/lib/libsfextcp.so
07-05 14:27:22.646  7964  7964 W art     : b536c000-b53cc000 r-xp 00000000 b3:17 201        /system/lib/libsavsff.so
07-05 14:27:22.646  7964  7964 W art     : b53cc000-b53cf000 rw-p 0005f000 b3:17 201        /system/lib/libsavsff.so
07-05 14:27:22.646  7964  7964 W art     : b53cf000-b53d3000 rw-p 00000000 00:00 0 
07-05 14:27:22.646  7964  7964 W art     : b53d3000-b5434000 r-xp 00000000 b3:17 160        /system/lib/libsavscmn.so
07-05 14:27:22.646  7964  7964 W art     : b5434000-b5435000 rw-p 00061000 b3:17 160        /system/lib/libsavscmn.so
07-05 14:27:22.646  7964  7964 W art     : b5435000-b5484000 r-xp 00000000 b3:17 2395       /system/lib/libomafldrm.so
07-05 14:27:22.646  7964  7964 W art     : b5484000-b5486000 r--p 0004e000 b3:17 2395       /system/lib/libomafldrm.so
07-05 14:27:22.646  7964  7964 W art     : b5486000-b5487000 rw-p 00050000 b3:17 2395       /system/lib/libomafldrm.so
07-05 14:27:22.646  7964  7964 W art     : b5487000-b5488000 rw-p 00000000 00:00 0 
07-05 14:27:22.646  7964  7964 W art     : b5488000-b548f000 r-xp 00000000 b3:17 2587       /system/lib/libstagefright_avc_common.so
07-05 14:27:22.646  7964  7964 W art     : b548f000-b5490000 r--p 00006000 b3:17 2587       /system/lib/libstagefright_avc_common.so
07-05 14:27:22.646  7964  7964 W art     : b5490000-b5491000 rw-p 00007000 b3:17 2587       /system/lib/libstagefright_
07-05 14:27:22.646  7964  7964 W art     : avc_common.so
07-05 14:27:22.646  7964  7964 W art     : b5492000-b5495000 r-xp 00000000 b3:17 2563       /system/lib/libstagefright_enc_common.so
07-05 14:27:22.646  7964  7964 W art     : b5495000-b5496000 r--p 00002000 b3:17 2563       /system/lib/libstagefright_enc_common.so
07-05 14:27:22.646  7964  7964 W art     : b5496000-b5497000 rw-p 00003000 b3:17 2563       /system/lib/libstagefright_
07-05 14:27:22.646  7964  7964 W art     : enc_common.so
07-05 14:27:22.646  7964  7964 W art     : b5498000-b549c000 r-xp 00000000 b3:17 2517       /system/lib/libpowermanager.so
07-05 14:27:22.646  7964  7964 W art     : b549c000-b549d000 ---p 00000000 00:00 0 
07-05 14:27:22.646  7964  7964 W art     : b549d000-b549e000 r--p 00004000 b3:17 2517       /system/lib/libpowermanager.so
07-05 14:27:22.646  7964  7964 W art     : b549e000-b549f000 rw-p 00005000 b3:17 2517       /syste
07-05 14:27:22.646  7964  7964 W art     : m/lib/libpowermanager.so
07-05 14:27:22.646  7964  7964 W art     : b54a0000-b54bd000 r-xp 00000000 b3:17 2732       /system/lib/libvorbisidec.so
07-05 14:27:22.646  7964  7964 W art     : b54bd000-b54be000 r--p 0001c000 b3:17 2732       /system/lib/libvorbisidec.so
07-05 14:27:22.646  7964  7964 W art     : b54be000-b54bf000 rw-p 0001d000 b3:17 2732       /system/lib/libvorbisidec.so
07-05 14:27:22.646  7964  7964 W art     : b54c0000-b54c5000 r-xp 00000000 b3:17 2683       /system/lib/libstagefright_yuv.so
07-05 14:27:22.646  7964  7964 W art     : b54c5000-b54c6000 r--p 00004000 b3:17 2683       /system/lib/libstagefright_yuv.so
07-05 14:27:22.646  7964  7964 W art     : b54c6000-b54c7000 rw-p 00005000 b3:17 2683       /system/lib/libstagefright_yuv.so
07-05 14:27:22.646  7964  7964 W art     : b54c8000-b54f9000 r-xp 00000000 b3:17 1409       /system/lib/libstagefright_omx.so
07-05 14:27:22.646  7964  7964 W art     : b54f9000-b54fc000 r--p 00030000 b3:17 1409       /system/lib/libstagefright_omx.so
07-05 14:27:22.646  7964  7964 W art     : b54fc000-b54fd000 rw-p 00033000 b3:17 1409       /system/lib/libstagefright_omx.so
07-05 14:27:22.646  7964  7964 W art     : b54fe000-b5539000 r-xp 00000000 b3:17 2136       /system/lib/libopus.so
07-05 14:27:22.646  7964  7964 W art     : b5539000-b553a000 r--p 0003a000 b3:17 2136       /system/lib/libopus.so
07-05 14:27:22.646  7964  7964 W art     : b553a000-b553b000 rw-p 0003b000 b3:17 2136       /system/lib/libopus.so
07-05 14:27:22.646  7964  7964 W art     : b553c000-b5543000 r-xp 00000000 b3:17 2930       /system/lib/libmediautils.so
07-05 14:27:22.646  7964  7964 W art     : b5543000-b5544000 ---p 00000000 00:00 0 
07-05 14:27:22.646  7964  7964 W art     : b5544000-b5545000 r--p 00007000 b3:17 2930       /system/lib/libmediautils.so
07-05 14:27:22.646  7964  7964 W art     : b5545000-b5546000 rw-p 00008000 b3:17 2930       /system/lib/libmediautils.so
07-05 14:27:22.646  7964  7964 W art     : b5546000-b5547000 r--p 00000000 00:00 0          [anon:linker_alloc]
07-05 14:27:22.646  7964  7964 W art     : b5547000-b555e000 r-xp 00000000 b3:17 726        /system/lib/libdrmframework.so
07-05 14:27:22.646  7964  7964 W art     : b555e000-b555f000 ---p 00000000 00:00 0 
07-05 14:27:22.646  7964  7964 W art     : b555f000-b5562000 r--p 00017000 b3:17 726        /system/lib/libdrmframework.so
07-05 14:27:22.646  7964  7964 W art     : b5562000-b5563000 rw-p 0001a000 b3:17 726        /system/lib/libdrmframework.so
07-05 14:27:22.646  7964  7964 W art     : b5563000-b5582000 r-xp 00000000 b3:17 354        /system/lib/libRScpp.so
07-05 14:27:22.646  7964  7964 W art     : b5582000-b5583000 r--p 0001e000 b3:17 354        /system/lib/libRScpp.so
07-05 14:27:22.646  7964  7964 W art     : b5583000-b5584000 rw-p 0001f000 b3:17 354        /system/lib/libRScpp.so
07-05 14:27:22.646  7964  7964 W art     : b5584000-b55c2000 r-xp 00000000 b3:17 2566       /system/lib/libRS.so
07-05 14:27:22.646  7964  7964 W art     : b55c2000-b55c3000 ---p 00000000 00:00 0 
07-05 14:27:22.646  7964  7964 W art     : b55c3000-b55c5000 r--p 0003e000 b3:17 2566       /system/lib/libRS.so
07-05 14:27:22.646  7964  7964 W art     : b55c5000-b55c6000 rw-p 00040000 b3:17 2566       /system/lib/libRS.so
07-05 14:27:22.646  7964  7964 W art     : b55c7000-b55ce000 r-xp 00000000 b3:17 776        /system/lib/libspeexresampler.so
07-05 14:27:22.646  7964  7964 W art     : b55ce000-b55cf000 r--p 00006000 b3:17 776        /system/lib/libspeexresampler.so
07-05 14:27:22.646  7964  7964 W art     : b55cf000-b55d0000 rw-p 00007000 b3:17 776        /system/lib/libspeexresampler.so
07-05 14:27:22.646  7964  7964 W art     : b55d1000-b55d4000 r-xp 00000000 b3:17 764        /system/lib/libsamsungvad.so
07-05 14:27:22.646  7964  7964 W art     : b55d4000-b55d5000 r--p 00002000 b3:17 764        /system/lib/libsamsungvad.so
07-05 14:27:22.646  7964  7964 W art     : b55d5000-b55d6000 rw-p 00003000 b3:17 764        /system/lib/libsamsungvad.so
07-05 14:27:22.646  7964  7964 W art     : b55d6000-b55dc000 r-xp 00000000 b3:17 2449       /system/lib/libedmnativehelper.so
07-05 14:27:22.646  7964  7964 W art     : b55dc000-b55dd000 ---p 00000000 00:00 0 
07-05 14:27:22.646  7964  7964 W art     : b55dd000-b55de000 r--p 00006000 b3:17 2449       /system/lib/libedmnativehelper.so
07-05 14:27:22.646  7964  7964 W art     : b55de000-b55df000 rw-p 00007000 b3:17 2449       /system/lib/libedmnativehelper.so
07-05 14:27:22.646  7964  7964 W art     : b55df000-b55e8000 r-xp 00000000 b3:17 2319       /system/lib/libnbaio.so
07-05 14:27:22.646  7964  7964 W art     : b55e8000-b55e9000 r--p 00008000 b3:17 2319       /system/lib/libnbaio.so
07-05 14:27:22.646  7964  7964 W art     : b55e9000-b55ea000 rw-p 00009000 b3:17 2319       /system/lib/libnbaio.so
07-05 14:27:22.646  7964  7964 W art     : b55ea000-b567b000 r-xp 00000000 b3:17 108        /system/lib/libcrypto-rename.so
07-05 14:27:22.646  7964  7964 W art     : b567b000-b567c000 ---p 00000000 00:00 0 
07-05 14:27:22.646  7964  7964 W art     : b567c000-b5687000 r--p 00091000 b3:17 108        /system/lib/libcrypto-rename.so
07-05 14:27:22.646  7964  7964 W art     : b5687000-b5688000 rw-p 0009c000 b3:17 108        /system/lib/libcrypto-rename.so
07-05 14:27:22.646  7964  7964 W art     : b5689000-b569b000 r-xp 00000000 b3:17 2931       /system/lib/libpcre.so
07-05 14:27:22.646  7964  7964 W art     : b569b000-b569c000 r--p 00011000 b3:17 2931       /system/lib/libpcre.so
07-05 14:27:22.646  7964  7964 W art     : b569c000-b569d000 rw-p 00012000 b3:17 2931       /system/lib/libpcre.so
07-05 14:27:22.646  7964  7964 W art     : b569e000-b56a3000 r-xp 00000000 b3:17 2467       /system/lib/libwpa_client.so
07-05 14:27:22.646  7964  7964 W art     : b56a3000-b56a4000 r--p 00004000 b3:17 2467       /system/lib/libwpa_client.so
07-05 14:27:22.646  7964  7964 W art     : b56a4000-b56a5000 rw-p 00005000 b3:17 2467       /system/lib/libwpa_client.so
07-05 14:27:22.646  7964  7964 W art     : b56a6000-b5713000 r-xp 00000000 b3:17 2127       /system/lib/libGLES_trace.so
07-05 14:27:22.646  7964  7964 W art     : b5713000-b5714000 ---p 00000000 00:00 0 
07-05 14:27:22.646  7964  7964 W art     : b5714000-b5716000 r--p 0006d000 b3:17 2127       /system/lib/libGLES_trace.so
07-05 14:27:22.646  7964  7964 W art     : b5716000-b5717000 rw-p 0006f000 b3:17 2127       /system/lib/libGLES_trace.so
07-05 14:27:22.646  7964  7964 W art     : b5717000-b5718000 r--p 00000000 00:00 0          [anon:linker_alloc]
07-05 14:27:22.646  7964  7964 W art     : b5718000-b571f000 r-xp 00000000 b3:17 2579       /system/lib/libsdp_crypto.so
07-05 14:27:22.646  7964  7964 W art     : b571f000-b5720000 r--p 00006000 b3:17 2579       /system/lib/libsdp_crypto.so
07-05 14:27:22.646  7964  7964 W art     : b5720000-b5721000 rw-p 00007000 b3:17 2579       /system/lib/libsdp_crypto.so
07-05 14:27:22.646  7964  7964 W art     : b5722000-b57a2000 r-xp 00000000 b3:17 2886       /system/lib/libAstcEnc.so
07-05 14:27:22.646  7964  7964 W art     : b57a2000-b57a3000 ---p 00000000 00:00 0 
07-05 14:27:22.646  7964  7964 W art     : b57a3000-b57a4000 r--p 00080000 b3:17 2886       /system/lib/libAstcEnc.so
07-05 14:27:22.646  7964  7964 W art     : b57a4000-b57a5000 rw-p 00081000 b3:17 2886       /system/lib/libAstcEnc.so
07-05 14:27:22.646  7964  7964 W art     : b57a5000-b57bc000 rw-p 00000000 00:00 0 
07-05 14:27:22.646  7964  7964 W art     : b57bc000-b57f3000 r-xp 00000000 b3:17 3247       /system/vendor/l
07-05 14:27:22.646  7964  7964 W art     : ib/libqc-opt.so
07-05 14:27:22.646  7964  7964 W art     : b57f3000-b57f4000 r--p 00036000 b3:17 3247       /system/vendor/lib/libqc-opt.so
07-05 14:27:22.646  7964  7964 W art     : b57f4000-b57f5000 rw-p 00037000 b3:17 3247       /system/vendor/lib/libqc-opt.so
07-05 14:27:22.646  7964  7964 W art     : b57f5000-b5811000 r-xp 00000000 b3:17 407        /system/lib/libquramimagecodec.so
07-05 14:27:22.646  7964  7964 W art     : b5811000-b5812000 r--p 0001b000 b3:17 407        /system/lib/libquramimagecodec.so
07-05 14:27:22.646  7964  7964 W art     : b5812000-b5813000 rw-p 0001c000 b3:17 407        /system/lib/libquramimagecodec.so
07-05 14:27:22.646  7964  7964 W art     : b5814000-b5875000 r-xp 00000000 b3:17 2708       /system/lib/libft2.so
07-05 14:27:22.646  7964  7964 W art     : b5875000-b5877000 r--p 00060000 b3:17 2708       /system/lib/libft2.so
07-05 14:27:22.646  7964  7964 W art     : b5877000-b5878000 rw-p 00062000 b3:17 2708       /system/lib/libft2.so
07-05 14:27:22.646  7964  7964 W art     : b5879000-b58a0000 r-xp 00000000 b3:17 2640       /system/lib/libpng.so
07-05 14:27:22.646  7964  7964 W art     : b58a0000-b58a1000 ---p 00000000 00:00 0 
07-05 14:27:22.646  7964  7964 W art     : b58a1000-b58a2000 r--p 00027000 b3:17 2640       /system/lib/libpng.so
07-05 14:27:22.646  7964  7964 W art     : b58a2000-b58a3000 rw-p 00028000 b3:17 2640       /system/lib/libpng.so
07-05 14:27:22.646  7964  7964 W art     : b58a4000-b58ac000 r-xp 00000000 b3:17 2191       /system/lib/libremotedesktop_client.so
07-05 14:27:22.646  7964  7964 W art     : b58ac000-b58ae000 r--p 00007000 b3:17 2191       /system/lib/libremotedesktop_client.so
07-05 14:27:22.646  7964  7964 W art     : b58ae000-b58af000 rw-p 00009000 b3:17 2191       /system/lib/libremotedesktop_client.so
07-05 14:27:22.646  7964  7964 W art     : b58b0000-b58b3000 r-xp 00000000 b3:17 2506       /system/lib/libsync.so
07-05 14:27:22.646  7964  7964 W art     : b58b3000-b58b4000 r--p 00002000 b3:17 2506       /system/lib/libsync.so
07-05 14:27:22.646  7964  7964 W art     : b58b4000-b58b5000 rw-p 00003000 b3:17 2506       /system/lib/libsync.so
07-05 14:27:22.646  7964  7964 W art     : b58b5000-b58b9000 r-xp 00000000 b3:17 2639       /system/lib/libstdc++.so
07-05 14:27:22.646  7964  7964 W art     : b58b9000-b58ba000 ---p 00000000 00:00 0 
07-05 14:27:22.646  7964  7964 W art     : b58ba000-b58bb000 r--p 00004000 b3:17 2639       /system/lib/libstdc++.so
07-05 14:27:22.646  7964  7964 W art     : b58bb000-b58bc000 rw-p 00005000 b3:17 2639       /system/lib/libstdc++.so
07-05 14:27:22.646  7964  7964 W art     : b58bc000-b58cc000 r-xp 00000000 b3:17 359        /system/lib/libunwind.so
07-05 14:27:22.646  7964  7964 W art     : b58cc000-b58cd000 r--p 0000f000 b3:17 359        /system/lib/libunwind.so
07-05 14:27:22.646  7964  7964 W art     : b58cd000-b58ce000 rw-p 00010000 b3:17 359        /system/lib/libunwind.so
07-05 14:27:22.646  7964  7964 W art     : b58ce000-b5914000 rw-p 00000000 00:00 0 
07-05 14:27:22.646  7964  7964 W art     : b5914000-b591d000 r-xp 00000000 b3:17 2903       /system/lib/libbase.so
07-05 14:27:22.646  7964  7964 W art     : b591d000-b591e000 r--p 00008000 b3:17 2903       /system/lib/libbase.so
07-05 14:27:22.646  7964  7964 W art     : b591e000-b591f000 rw-p 00009000 b3:17 2903       /system/lib/libbase.so
07-05 14:27:22.646  7964  7964 W art     : b5920000-b5925000 r-xp 00000000 b3:17 2659       /system/lib/libeffects.so
07-05 14:27:22.646  7964  7964 W art     : b5925000-b5926000 r--p 00004000 b3:17 2659       /system/lib/libeffects.so
07-05 14:27:22.646  7964  7964 W art     : b5926000-b5927000 rw-p 00005000 b3:17 2659       /system/lib/libeffects.so
07-05 14:27:22.646  7964  7964 W art     : b5927000-b592a000 r-xp 00000000 b3:17 1371       /system/lib/libstagefright_http_support.so
07-05 14:27:22.646  7964  7964 W art     : b592a000-b592b000 ---p 00000000 00:00 0 
07-05 14:27:22.646  7964  7964 W art     : b592b000-b592c000 r--p 00003000 b3:17 1371       /system/lib/libstagefright_http_support.so
07-05 14:27:22.646  7964  7964 W art     : b592c000-b592d000 rw-p 00004000 b3:17 1371       /system/lib/libstagefright_http_support.so
07-05 14:27:22.646  7964  7964 W art     : b592e000-b5946000 r-xp 00000000 b3:17 2406       /system/lib/libstagefright_foundation.so
07-05 14:27:22.646  7964  7964 W art     : b5946000-b5947000 ---p 00000000 00:00 0 
07-05 14:27:22.646  7964  7964 W art     : b5947000-b5948000 r--p 00018000 b3:17 2406       /system/lib/libstagefright_foundation.so
07-05 14:27:22.646  7964  7964 W art     : b5948000-b5949000 rw-p 00019000 b3:17 2406       /system/lib/libstagefright_foundation.so
07-05 14:27:22.646  7964  7964 W art     : b594a000-b5ae4000 r-xp 00000000 b3:17 2790       /system/lib/libstagefright.so
07-05 14:27:22.646  7964  7964 W art     : b5ae4000-b5ae5000 ---p 00000000 00:00 0 
07-05 14:27:22.646  7964  7964 W art     : b5ae5000-b5af2000 r--p 0019a000 b3:17 2790       /system/lib/libstagefright.so
07-05 14:27:22.646  7964  7964 W art     : b5af2000-b5af3000 rw-p 001a7000 b3:17 2790       /system/lib/libstagefright.so
07-05 14:27:22.646  7964  7964 W art     : b5af3000-b5af7000 r-xp 00000000 b3:17 2681       /system/lib/libpersona.so
07-05 14:27:22.646  7964  7964 W art     : b5af7000-b5af8000 ---p 00000000 00:00 0 
07-05 14:27:22.646  7964  7964 W art     : b5af8000-b5af9000 r--p 00004000 b3:17 2681       /system/lib/libpersona.so
07-05 14:27:22.646  7964  7964 W art     : b5af9000-b5afa000 rw-p 00005000 b3:17 2681       /system/lib/libpersona.so
07-05 14:27:22.646  7964  7964 W art     : b5afa000-b5b0d000 r-xp 00000000 b3:17 2920       /system/lib/libimagefilter.so
07-05 14:27:22.646  7964  7964 W art     : b5b0d000-b5b0e000 r--p 00012000 b3:17 2920       /system/lib/libimagefilter.so
07-05 14:27:22.646  7964  7964 W art     : b5b0e000-b5b0f000 rw-p 00013000 b3:17 2920       /system/lib/libimagefilter.so
07-05 14:27:22.646  7964  7964 W art     : b5b0f000-b5b10000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
07-05 14:27:22.646  7964  7964 W art     : b5b10000-b5b5b000 r-xp 00000000 b3:17 2156       /system/lib/libsecure_storage.so
07-05 14:27:22.646  7964  7964 W art     : b5b5b000-b5b5c000 r--p 0004a000 b3:17 2156       /system/lib/libsecure_storage.so
07-05 14:27:22.646  7964  7964 W art     : b5b5c000-b5b5d000 rw-p 0004b000 b3:17 2156       /system/lib/libsecure_storage.so
07-05 14:27:22.646  7964  7964 W art     : b5b5d000-b5b5f000 rw-p 00000000 00:00 0 
07-05 14:27:22.646  7964  7964 W art     : b5b60000-b5b71000 r-xp 00000000 b3:17 2258       /system/lib/libsamsungeffect.so
07-05 14:27:22.646  7964  7964 W art     : b5b71000-b5b72000 ---p 00000000 00:00 0 
07-05 14:27:22.646  7964  7964 W art     : b5b72000-b5b73000 r--p 00011000 b3:17 2258       /system/lib/libsamsungeffect.so
07-05 14:27:22.646  7964  7964 W art     : b5b73000-b5b74000 rw-p 00012000 b3:17 2258       /system/lib/libsamsungeffect.so
07-05 14:27:22.646  7964  7964 W art     : b5b75000-b5b7f000 r-xp 00000000 b3:17 2321       /system/lib/libsensorhub.so
07-05 14:27:22.646  7964  7964 W art     : b5b7f000-b5b81000 r--p 00009000 b3:17 2321       /system/lib/libsensorhub.so
07-05 14:27:22.646  7964  7964 W art     : b5b81000-b5b82000 rw-p 0000b000 b3:17 2321       /system/lib/libsensorhub.so
07-05 14:27:22.646  7964  7964 W art     : b5b82000-b5b9b000 r-xp 00000000 b3:17 2929       /system/lib/libmctraster.so
07-05 14:27:22.646  7964  7964 W art     : b5b9b000-b5b9c000 r--p 00018000 b3:17 2929       /system/lib/libmctraster.so
07-05 14:27:22.646  7964  7964 W art     : b5b9c000-b5b9f000 rw-p 00019000 b3:17 2929       /system/lib/libmctraster.so
07-05 14:27:22.646  7964  7964 W art     : b5b9f000-b5ba3000 rw-p 00000000 00:00 0 
07-05 14:27:22.646  7964  7964 W art     : b5ba3000-b5c17000 r-xp 00000000 b3:17 2777       /system/lib/libhwui.so
07-05 14:27:22.646  7964  7964 W art     : b5c17000-b5c18000 ---p 00000000 00:00 0 
07-05 14:27:22.646  7964  7964 W art     : b5c18000-b5c1b000 r--p 00074000 b3:17 2777       /system/lib/libhwui.so
07-05 14:27:22.646  7964  7964 W art     : b5c1b000-b5c1c000 rw-p 00077000 b3:17 2777       /system/lib/libhwui.so
07-05 14:27:22.646  7964  7964 W art     : b5c1c000-b5c1d000 r--p 00000000 00:00 0 
07-05 14:27:22.646  7964  7964 W art     : b5c1d000-b5c20000 r-xp 00000000 b3:17 2497       /system/lib/libcc_manager.so
07-05 14:27:22.646  7964  7964 W art     : b5c20000-b5c21000 r--p 00002000 b3:17 2497       /system/lib/libcc_manager.so
07-05 14:27:22.646  7964  7964 W art     : b5c21000-b5c22000 rw-p 00003000 b3:17 2497       /system/lib/libcc_manager.so
07-05 14:27:22.646  7964  7964 W art     : b5c22000-b5c23000 r--p 00000000 00:00 0 
07-05 14:27:22.646  7964  7964 W art     : b5c23000-b5c28000 r-xp 00000000 b3:17 2463       /system/lib/libsecnativefeature.so
07-05 14:27:22.646  7964  7964 W art     : b5c28000-b5c29000 r--p 00004000 b3:17 2463       /system/lib/libsecnativefeature.so
07-05 14:27:22.646  7964  7964 W art     : b5c29000-b5c2a000 rw-p 00005000 b3:17 2463       /system/lib/libsecnativefeature.so
07-05 14:27:22.646  7964  7964 W art     : b5c2a000-b5c2b000 r--p 00000000 00:00 0          [anon:linker_alloc]
07-05 14:27:22.646  7964  7964 W art     : b5c2b000-b5c2e000 r-xp 00000000 b3:17 2939       /system/lib/libradio_metadata.so
07-05 14:27:22.646  7964  7964 W art     : b5c2e000-b5c2f000 r--p 00002000 b3:17 2939       /system/lib/libradio_metadata.so
07-05 14:27:22.646  7964  7964 W art     : b5c2f000-b5c30000 rw-p 00003000 b3:17 2939       /system/lib/libradio_metadata.so
07-05 14:27:22.646  7964  7964 W art     : b5c30000-b5c31000 r--p 00000000 00:00 0          [anon:linker_alloc]
07-05 14:27:22.646  7964  7964 W art     : b5c31000-b5c35000 r-xp 00000000 b3:17 808        /system/lib/libnativebridge.so
07-05 14:27:22.646  7964  7964 W art     : b5c35000-b5c36000 r--p 00003000 b3:17 808        /system/lib/libnativebridge.so
07-05 14:27:22.646  7964  7964 W art     : b5c36000-b5c37000 rw-p 00004000 b3:17 808        /system/lib/libnativebridge.so
07-05 14:27:22.646  7964  7964 W art     : b5c37000-b5c38000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
07-05 14:27:22.646  7964  7964 W art     : b5c38000-b5c3c000 r-xp 00000000 b3:17 2582       /system/lib/libprocessgroup.so
07-05 14:27:22.646  7964  7964 W art     : b5c3c000-b5c3d000 r--p 00003000 b3:17 2582       /system/lib/libprocessgroup.so
07-05 14:27:22.646  7964  7964 W art     : b5c3d000-b5c3e000 rw-p 00004000 b3:17 2582       /system/lib/libprocessgroup.so
07-05 14:27:22.646  7964  7964 W art     : b5c3e000-b5c3f000 r--p 00000000 00:00 0          [anon:linker_alloc]
07-05 14:27:22.646  7964  7964 W art     : b5c3f000-b5c4d000 r-xp 00000000 b3:17 472        /system/lib/libminikin.so
07-05 14:27:22.646  7964  7964 W art     : b5c4d000-b5c4e000 ---p 00000000 00:00 0 
07-05 14:27:22.646  7964  7964 W art     : b5c4e000-b5c4f000 r--p 0000e000 b3:17 472        /system/lib/libminikin.so
07-05 14:27:22.646  7964  7964 W art     : b5c4f000-b5c50000 rw-p 0000f000 b3:17 472        /system/lib/libminikin.so
07-05 14:27:22.646  7964  7964 W art     : b5c50000-b5c5a000 r-xp 00000000 b3:17 2193       /system/lib/libsoundtrigger.so
07-05 14:27:22.646  7964  7964 W art     : b5c5a000-b5c5d000 r--p 00009000 b3:17 2193       /system/lib/libsoundtrigger.so
07-05 14:27:22.646  7964  7964 W art     : b5c5d000-b5c5e000 rw-p 0000c000 b3:17 2193       /system/lib/libsoundtrigger.so
07-05 14:27:22.646  7964  7964 W art     : b5c5e000-b5c5f000 r--p 00000000 00:00 0          [anon:linker_alloc]
07-05 14:27:22.646  7964  7964 W art     : b5c5f000-b5c69000 r-xp 00000000 b3:17 2938       /system/lib/libradio.so
07-05 14:27:22.646  7964  7964 W art     : b5c69000-b5c6c000 r--p 00009000 b3:17 2938       /system/lib/libradio.so
07-05 14:27:22.646  7964  7964 W art     : b5c6c000-b5c6d000 rw-p 0000c000 b3:17 2938       /system/lib/libradio.so
07-05 14:27:22.646  7964  7964 W art     : b5c6d000-b5c71000 r-xp 00000000 b3:17 2413       /system/lib/libnetd_client.so
07-05 14:27:22.646  7964  7964 W art     : b5c71000-b5c72000 r--p 00003000 b3:17 2413       /system/lib/libnetd_client.so
07-05 14:27:22.646  7964  7964 W art     : b5c72000-b5c73000 rw-p 00004000 b3:17 2413       /system/lib/libnetd_client.so
07-05 14:27:22.646  7964  7964 W art     : b5c73000-b5c74000 r--p 00000000 00:00 0          [anon:linker_alloc]
07-05 14:27:22.646  7964  7964 W art     : b5c74000-b5c81000 r-xp 00000000 b3:17 2372       /system/lib/libimg_utils.so
07-05 14:27:22.646  7964  7964 W art     : b5c81000-b5c83000 r--p 0000c000 b3:17 2372       /system/lib/libimg_utils.so
07-05 14:27:22.646  7964  7964 W art     : b5c83000-b5c84000 rw-p 0000e000 b3:17 2372       /system/lib/libimg_utils.so
07-05 14:27:22.646  7964  7964 W art     : b5c84000-b6096000 r-xp 00000000 b3:17 299        /system/lib/libpdfium.so
07-05 14:27:22.646  7964  7964 W art     : b6096000-b6097000 ---p 00000000 00:00 0 
07-05 14:27:22.646  7964  7964 W art     : b6097000-b60a0000 r--p 00412000 b3:17 299        /system/lib/libpdfium.so
07-05 14:27:22.646  7964  7964 W art     : b60a0000-b60a4000 rw-p 0041b000 b3:17 299        /system/lib/libpdfium.so
07-05 14:27:22.646  7964  7964 W art     : b60a4000-b60a5000 rw-p 00000000 00:00 0 
07-05 14:27:22.646  7964  7964 W art     : b60a5000-b60ac000 r-xp 00000000 b3:17 2571       /system/lib/libaudioutils.so
07-05 14:27:22.646  7964  7964 W art     : b60ac000-b60ad000 r--p 00006000 b3:17 2571       /system/lib/libaudioutils.so
07-05 14:27:22.646  7964  7964 W art     : b60ad000-b60ae000 rw-p 00007000 b3:17 2571       /system/lib/libaudioutils.so
07-05 14:27:22.646  7964  7964 W art     : b60ae000-b60af000 r--p 00000000 00:00 0          [anon:linker_alloc]
07-05 14:27:22.646  7964  7964 W art     : b60af000-b60ca000 r-xp 00000000 b3:17 1184       /system/lib/libz.so
07-05 14:27:22.646  7964  7964 W art     : b60ca000-b60cb000 r--p 0001a000 b3:17 1184       /system/lib/libz.so
07-05 14:27:22.646  7964  7964 W art     : b60cb000-b60cc000 rw-p 0001b000 b3:17 1184       /system/lib/libz.so
07-05 14:27:22.646  7964  7964 W art     : b60cc000-b60cd000 r--p 00000000 00:00 0          [anon:linker_alloc]
07-05 14:27:22.646  7964  7964 W art     : b60cd000-b6119000 r-xp 00000000 b3:17 342        /system/lib/libharfbuzz_ng.so
07-05 14:27:22.646  7964  7964 W art     : b6119000-b611a000 ---p 00000000 00:00 0 
07-05 14:27:22.646  7964  7964 W art     : b611a000-b611b000 r--p 0004c000 b3:17 342        /system/lib/libharfbuzz_ng.so
07-05 14:27:22.646  7964  7964 W art     : b611b000-b611c000 rw-p 0004d000 b3:17 342        /system/lib/libharfbuzz_ng.so
07-05 14:27:22.646  7964  7964 W art     : b611c000-b611d000 r--p 00000000 00:00 0          [anon:linker_alloc]
07-05 14:27:22.646  7964  7964 W art     : b611d000-b6121000 r-xp 00000000 b3:17 2688       /system/lib/libusbhost.so
07-05 14:27:22.646  7964  7964 W art     : b6121000-b6122000 ---p 00000000 00:00 0 
07-05 14:27:22.646  7964  7964 W art     : b6122000-b6123000 r--p 00004000 b3:17 2688       /system/lib/libusbhost.so
07-05 14:27:22.646  7964  7964 W art     : b6123000-b6124000 rw-p 00005000 b3:17 2688       /system/lib/libusbhost.so
07-05 14:27:22.646  7964  7964 W art     : b6124000-b615c000 r-xp 00000000 b3:17 2749       /system/lib/libjpeg.so
07-05 14:27:22.646  7964  7964 W art     : b615c000-b615d000 r--p 00037000 b3:17 2749       /system/lib/libjpeg.so
07-05 14:27:22.646  7964  7964 W art     : b615d000-b615e000 rw-p 00038000 b3:17 2749       /system/lib/libjpeg.so
07-05 14:27:22.646  7964  7964 W art     : b615e000-b615f000 r--p 00000000 00:00 0          [anon:linker_alloc]
07-05 14:27:22.646  7964  7964 W art     : b615f000-b61fd000 r-xp 00000000 b3:17 409        /system/lib/libmedia.so
07-05 14:27:22.646  7964  7964 W art     : b61fd000-b61fe000 ---p 00000000 00:00 0 
07-05 14:27:22.646  7964  7964 W art     : b61fe000-b621c000 r--p 0009e000 b3:17 409        /system/lib/libmedia.so
07-05 14:27:22.646  7964  7964 W art     : b621c000-b621d000 rw-p 000bc000 b3:17 409        /system/lib/libmedia.so
07-05 14:27:22.646  7964  7964 W art     : b621d000-b6390000 r-xp 00000000 b3:17 2204       /system/lib/libicui18n.so
07-05 14:27:22.646  7964  7964 W art     : b6390000-b639b000 r--p 00172000 b3:17 2204       /system/lib/libicui18n.so
07-05 14:27:22.656  7964  7964 W art     : b639b000-b639c000 rw-p 0017d000 b3:17 2204       /system/lib/libicui18n.so
07-05 14:27:22.656  7964  7964 W art     : b639c000-b64b3000 r-xp 00000000 b3:17 2041       /system/lib/libicuuc.so
07-05 14:27:22.656  7964  7964 W art     : b64b3000-b64be000 r--p 00116000 b3:17 2041       /system/lib/libicuuc.so
07-05 14:27:22.656  7964  7964 W art     : b64be000-b64bf000 rw-p 00121000 b3:17 2041       /system/lib/libicuuc.so
07-05 14:27:22.656  7964  7964 W art     : b64bf000-b64c3000 rw-p 00000000 00:00 0 
07-05 14:27:22.656  7964  7964 W art     : b64c3000-b64e7000 r-xp 00000000 b3:17 405        /system/lib/libssl.so
07-05 14:27:22.656  7964  7964 W art     : b64e7000-b64e9000 r--p 00023000 b3:17 405        /system/lib/libssl.so
07-05 14:27:22.656  7964  7964 W art     : b64e9000-b64ea000 rw-p 00025000 b3:17 405        /system/lib/libssl.so
07-05 14:27:22.656  7964  7964 W art     : b64ea000-b6590000 r-xp 00000000 b3:17 110        /system/lib/libcrypto.so
07-05 14:27:22.656  7964  7964 W art     : b6590000-b659d000 r--p 000a5000 b3:17 110        /system/lib/libcrypto.so
07-05 14:27:22.656  7964  7964 W art     : b659d000-b659e000 rw-p 000b2000 b3:17 110        /system/lib/libcrypto.so
07-05 14:27:22.656  7964  7964 W art     : b659e000-b659f000 rw-p 00000000 00:00 0 
07-05 14:27:22.656  7964  7964 W art     : b659f000-b65f2000 r-xp 00000000 b3:17 2736       /system/lib/libsonivox.so
07-05 14:27:22.656  7964  7964 W art     : b65f2000-b65f3000 ---p 00000000 00:00 0 
07-05 14:27:22.656  7964  7964 W art     : b65f3000-b65f4000 r--p 00053000 b3:17 2736       /system/lib/libsonivox.so
07-05 14:27:22.656  7964  7964 W art     : b65f4000-b65f5000 rw-p 00054000 b3:17 2736       /system/lib/libsonivox.so
07-05 14:27:22.656  7964  7964 W art     : b65f5000-b65fa000 rw-p 00000000 00:00 0 
07-05 14:27:22.656  7964  7964 W art     : b65fa000-b660c000 r-xp 00000000 b3:17 2641       /system/lib/libselinux.so
07-05 14:27:22.656  7964  7964 W art     : b660c000-b660d000 ---p 00000000 00:00 0 
07-05 14:27:22.656  7964  7964 W art     : b660d000-b660e000 r--p 00012000 b3:17 2641       /system/lib/libselinux.so
07-05 14:27:22.656  7964  7964 W art     : b660e000-b660f000 rw-p 00013000 b3:17 2641       /system/lib/libselinux.so
07-05 14:27:22.656  7964  7964 W art     : b660f000-b6616000 r-xp 00000000 b3:17 2636       /system/lib/libhardware_legacy.so
07-05 14:27:22.656  7964  7964 W art     : b6616000-b6617000 r--p 00007000 b3:17 2636       /system/lib/libhardware_legacy.so
07-05 14:27:22.656  7964  7964 W art     : b6617000-b6618000 rw-p 00008000 b3:17 2636       /system/lib/libhardware_legacy.so
07-05 14:27:22.656  7964  7964 W art     : b6618000-b6619000 rw-p 00000000 00:00 0 
07-05 14:27:22.656  7964  7964 W art     : b6619000-b661c000 r-xp 00000000 b3:17 2414       /system/lib/libhardware.so
07-05 14:27:22.656  7964  7964 W art     : b661c000-b661d000 r--p 00002000 b3:17 2414       /system/lib/libhardware.so
07-05 14:27:22.656  7964  7964 W art     : b661d000-b661e000 rw-p 00003000 b3:17 2414       /system/lib/libhardware.so
07-05 14:27:22.656  7964  7964 W art     : b661e000-b6622000 r-xp 00000000 b3:17 2565       /system/lib/libETC1.so
07-05 14:27:22.656  7964  7964 W art     : b6622000-b6623000 r--p 00003000 b3:17 2565       /system/lib/libETC1.so
07-05 14:27:22.656  7964  7964 W art     : b6623000-b6624000 rw-p 00004000 b3:17 2565       /system/lib/libETC1.so
07-05 14:27:22.656  7964  7964 W art     : b6624000-b6632000 r-xp 00000000 b3:17 2725       /system/lib/libGLESv2.so
07-05 14:27:22.656  7964  7964 W art     : b6632000-b6633000 ---p 00000000 00:00 0 
07-05 14:27:22.656  7964  7964 W art     : b6633000-b6634000 r--p 0000e000 b3:17 2725       /system/lib/libGLESv2.so
07-05 14:27:22.656  7964  7964 W art     : b6634000-b6635000 rw-p 0000f000 b3:17 2725       /system/lib/libGLESv2.so
07-05 14:27:22.656  7964  7964 W art     : b6635000-b663e000 r-xp 00000000 b3:17 2253       /system/lib/libGLESv1_CM.so
07-05 14:27:22.656  7964  7964 W art     : b663e000-b663f000 r--p 00008000 b3:17 2253       /system/lib/libGLESv1_CM.so
07-05 14:27:22.656  7964  7964 W art     : b663f000-b6640000 rw-p 00009000 b3:17 2253       /system/lib/libGLESv1_CM.so
07-05 14:27:22.656  7964  7964 W art     : b6640000-b66a6000 r-xp 00000000 b3:17 825        /system/lib/libEGL.so
07-05 14:27:22.656  7964  7964 W art     : b66a6000-b66a7000 ---p 00000000 00:00 0 
07-05 14:27:22.656  7964  7964 W art     : b66a7000-b66a9000 r--p 00066000 b3:17 825        /system/lib/libEGL.so
07-05 14:27:22.656  7964  7964 W art     : b66a9000-b66b2000 rw-p 00068000 b3:17 825        /system/lib/libEGL.so
07-05 14:27:22.656  7964  7964 W art     : b66b2000-b66b5000 rw-p 00000000 00:00 0 
07-05 14:27:22.656  7964  7964 W art     : b66b5000-b674c000 r-xp 00000000 b3:17 688        /system/lib/libsqlite.so
07-05 14:27:22.656  7964  7964 W art     : b674c000-b674e000 r--p 00096000 b3:17 688        /system/lib/libsqlite.so
07-05 14:27:22.656  7964  7964 W art     : b674e000-b674f000 rw-p 00098000 b3:17 688        /system/lib/libsqlite.so
07-05 14:27:22.656  7964  7964 W art     : b674f000-b6750000 rw-p 00000000 00:00 0 
07-05 14:27:22.656  7964  7964 W art     : b6750000-b6a71000 r-xp 00000000 b3:17 286        /system/lib/libskia.so
07-05 14:27:22.656  7964  7964 W art     : b6a71000-b6a72000 ---p 00000000 00:00 0 
07-05 14:27:22.656  7964  7964 W art     : b6a72000-b6a8d000 r--p 00321000 b3:17 286        /system/lib/libskia.so
07-05 14:27:22.656  7964  7964 W art     : b6a8d000-b6a91000 rw-p 0033c000 b3:17 286        /system/lib/libskia.so
07-05 14:27:22.656  7964  7964 W art     : b6a91000-b6a96000 rw-p 00000000 00:00 0 
07-05 14:27:22.656  7964  7964 W art     : b6a96000-b6a9e000 r-xp 00000000 b3:17 2599       /system/lib/libcamera_metadata.so
07-05 14:27:22.656  7964  7964 W art     : b6a9e000-b6a9f000 r--p 00007000 b3:17 2599       /system/lib/libcamera_metadata.so
07-05 14:27:22.656  7964  7964 W art     : b6a9f000-b6aa0000 rw-p 00008000 b3:17 2599       /system/lib/libcamera_metadata.so
07-05 14:27:22.656  7964  7964 W art     : b6aa0000-b6ace000 r-xp 00000000 b3:17 564        /system/lib/libcamera_client.so
07-05 14:27:22.656  7964  7964 W art     : b6ace000-b6acf000 ---p 00000000 00:00 0 
07-05 14:27:22.656  7964  7964 W art     : b6acf000-b6ad6000 r--p 0002e000 b3:17 564        /system/lib/libcamera_client.so
07-05 14:27:22.656  7964  7964 W art     : b6ad6000-b6ad7000 rw-p 00035000 b3:17 564        /system/lib/libcamera_client.so
07-05 14:27:22.656  7964  7964 W art     : b6ad7000-b6b1d000 r-xp 00000000 b3:17 1049       /system/lib/libinputflinger.so
07-05 14:27:22.656  7964  7964 W art     : b6b1d000-b6b1e000 ---p 00000000 00:00 0 
07-05 14:27:22.656  7964  7964 W art     : b6b1e000-b6b21000 r--p 00046000 b3:17 1049       /system/lib/libinputflinger.so
07-05 14:27:22.656  7964  7964 W art     : b6b21000-b6b22000 rw-p 00049000 b3:17 1049       /system/lib/libinputflinger.so
07-05 14:27:22.656  7964  7964 W art     : b6b22000-b6b3d000 r-xp 00000000 b3:17 2538       /system/lib/libinput.so
07-05 14:27:22.656  7964  7964 W art     : b6b3d000-b6b41000 r--p 0001a000 b3:17 2538       /system/lib/libinput.so
07-05 14:27:22.656  7964  7964 W art     : b6b41000-b6b42000 rw-p 0001e000 b3:17 2538       /system/lib/libinput.so
07-05 14:27:22.656  7964  7964 W art     : b6b42000-b6b8f000 r-xp 00000000 b3:17 2763       /system/lib/libgui.so
07-05 14:27:22.656  7964  7964 W art     : b6b8f000-b6b90000 ---p 00000000 00:00 0 
07-05 14:27:22.656  7964  7964 W art     : b6b90000-b6b9c000 r--p 0004d000 b3:17 2763       /system/lib/libgui.so
07-05 14:27:22.656  7964  7964 W art     : b6b9c000-b6b9d000 rw-p 00059000 b3:17 2763       /system/lib/libgui.so
07-05 14:27:22.656  7964  7964 W art     : b6b9d000-b6baa000 r-xp 00000000 b3:17 2719       /system/lib/libui.so
07-05 14:27:22.656  7964  7964 W art     : b6baa000-b6bab000 ---p 00000000 00:00 0 
07-05 14:27:22.656  7964  7964 W art     : b6bab000-b6bac000 r--p 0000d000 b3:17 2719       /system/lib/libui.so
07-05 14:27:22.656  7964  7964 W art     : b6bac000-b6bad000 rw-p 0000e000 b3:17 2719       /system/lib/libui.so
07-05 14:27:22.656  7964  7964 W art     : b6bad000-b6bb5000 r-xp 00000000 b3:17 2160       /system/lib/libnetutils.so
07-05 14:27:22.656  7964  7964 W art     : b6bb5000-b6bb6000 ---p 00000000 00:00 0 
07-05 14:27:22.656  7964  7964 W art     : b6bb6000-b6bb7000 r--p 00008000 b3:17 2160       /system/lib/libnetutils.so
07-05 14:27:22.656  7964  7964 W art     : b6bb7000-b6bb8000 rw-p 00009000 b3:17 2160       /system/lib/libnetutils.so
07-05 14:27:22.656  7964  7964 W art     : b6bb8000-b6bbf000 r-xp 00000000 b3:17 1217       /system/lib/libnativehelper.so
07-05 14:27:22.656  7964  7964 W art     : b6bbf000-b6bc0000 r--p 00006000 b3:17 1217       /system/lib/libnativehelper.so
07-05 14:27:22.656  7964  7964 W art     : b6bc0000-b6bc1000 rw-p 00007000 b3:17 1217       /system/lib/libnativehelper.so
07-05 14:27:22.656  7964  7964 W art     : b6bc1000-b6bd5000 r-xp 00000000 b3:17 2082       /system/lib/libexpat.so
07-05 14:27:22.656  7964  7964 W art     : b6bd5000-b6bd7000 r--p 00013000 b3:17 2082       /system/lib/libexpat.so
07-05 14:27:22.656  7964  7964 W art     : b6bd7000-b6bd8000 rw-p 00015000 b3:17 2082       /system/lib/libexpat.so
07-05 14:27:22.656  7964  7964 W art     : b6bd8000-b6c00000 r-xp 00000000 b3:17 1012       /system/lib/libandroidfw.so
07-05 14:27:22.656  7964  7964 W art     : b6c00000-b6c02000 r--p 00027000 b3:17 1012       /system/lib/libandroidfw.so
07-05 14:27:22.656  7964  7964 W art     : b6c02000-b6c03000 rw-p 00029000 b3:17 1012       /system/lib/libandroidfw.so
07-05 14:27:22.656  7964  7964 W art     : b6c03000-b6c06000 r-xp 00000000 b3:17 2457       /system/lib/libmemtrack.so
07-05 14:27:22.656  7964  7964 W art     : b6c06000-b6c07000 r--p 00002000 b3:17 2457       /system/lib/libmemtrack.so
07-05 14:27:22.656  7964  7964 W art     : b6c07000-b6c08000 rw-p 00003000 b3:17 2457       /system/lib/libmemtrack.so
07-05 14:27:22.656  7964  7964 W art     : b6c08000-b6c11000 r-xp 00000000 b3:17 2581       /system/lib/libbacktrace.so
07-05 14:27:22.666  7964  7964 W art     : b6c11000-b6c12000 r--p 00008000 b3:17 2581       /system/lib/libbacktrace.so
07-05 14:27:22.666  7964  7964 W art     : b6c12000-b6c13000 rw-p 00009000 b3:17 2581       /system/lib/libbacktrace.so
07-05 14:27:22.666  7964  7964 W art     : b6c13000-b6c33000 r-xp 00000000 b3:17 2560       /system/lib/libm.so
07-05 14:27:22.666  7964  7964 W art     : b6c33000-b6c34000 r--p 0001f000 b3:17 2560       /system/lib/libm.so
07-05 14:27:22.666  7964  7964 W art     : b6c34000-b6c35000 rw-p 00020000 b3:17 2560       /system/lib/libm.so
07-05 14:27:22.666  7964  7964 W art     : b6c35000-b6ca8000 r-xp 00000000 b3:17 328        /system/lib/libc.so
07-05 14:27:22.666  7964  7964 W art     : b6ca8000-b6cac000 r--p 00072000 b3:17 328        /system/lib/libc.so
07-05 14:27:22.666  7964  7964 W art     : b6cac000-b6caf000 rw-p 00076000 b3:17 328        /system/lib/libc.so
07-05 14:27:22.666  7964  7964 W art     : b6caf000-b6cb9000 rw-p 00000000 00:00 0 
07-05 14:27:22.666  7964  7964 W art     : b6cb9000-b6d41000 r-xp 00000000 b3:17 1016       /system/lib/libc++.so
07-05 14:27:22.666  7964  7964 W art     : b6d41000-b6d42000 ---p 00000000 00:00 0 
07-05 14:27:22.666  7964  7964 W art     : b6d42000-b6d46000 r--p 00088000 b3:17 1016       /system/lib/libc++.so
07-05 14:27:22.666  7964  7964 W art     : b6d46000-b6d47000 rw-p 0008c000 b3:17 1016       /system/lib/libc++.so
07-05 14:27:22.666  7964  7964 W art     : b6d47000-b6d48000 rw-p 00000000 00:00 0 
07-05 14:27:22.666  7964  7964 W art     : b6d48000-b6d71000 r-xp 00000000 b3:17 1253       /system/lib/libwilhelm.so
07-05 14:27:22.666  7964  7964 W art     : b6d71000-b6d72000 ---p 00000000 00:00 0 
07-05 14:27:22.666  7964  7964 W art     : b6d72000-b6d75000 r--p 00029000 b3:17 1253       /system/lib/libwilhelm.so
07-05 14:27:22.666  7964  7964 W art     : b6d75000-b6d76000 rw-p 0002c000 b3:17 1253       /system/lib/libwilhelm.so
07-05 14:27:22.666  7964  7964 W art     : b6d76000-b6e50000 r-xp 00000000 b3:17 460        /system/lib/libandroid_runtime.so
07-05 14:27:22.666  7964  7964 W art     : b6e50000-b6e57000 r--p 000d9000 b3:17 460        /system/lib/libandroid_runtime.so
07-05 14:27:22.666  7964  7964 W art     : b6e57000-b6e5f000 rw-p 000e0000 b3:17 460        /system/lib/libandroid_runtime.so
07-05 14:27:22.666  7964  7964 W art     : b6e5f000-b6e60000 rw-p 00000000 00:00 0 
07-05 14:27:22.666  7964  7964 W art     : b6e60000-b6e61000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
07-05 14:27:22.666  7964  7964 W art     : b6e61000-b6e62000 rw-p 00000000 00:00 0          [anon:linker_alloc_64]
07-05 14:27:22.666  7964  7964 W art     : b6e62000-b6e63000 rw-p 00000000 00:00 0          [anon:linker_alloc]
07-05 14:27:22.666  7964  7964 W art     : b6e63000-b6e66000 r--p 00000000 00:00 0          [anon:linker_alloc]
07-05 14:27:22.666  7964  7964 W art     : b6e66000-b6e8b000 r-xp 00000000 b3:17 2107       /system/lib/libbinder.so
07-05 14:27:22.666  7964  7964 W art     : b6e8b000-b6e8c000 ---p 00000000 00:00 0 
07-05 14:27:22.666  7964  7964 W art     : b6e8c000-b6e93000 r--p 00025000 b3:17 2107       /system/lib/libbinder.so
07-05 14:27:22.666  7964  7964 W art     : b6e93000-b6e94000 rw-p 0002c000 b3:17 2107       /system/lib/libbinder.so
07-05 14:27:22.666  7964  7964 W art     : b6e94000-b6e9b000 r-xp 00000000 b3:17 2644       /system/lib/liblog.so
07-05 14:27:22.666  7964  7964 W art     : b6e9b000-b6e9c000 r--p 00006000 b3:17 2644       /system/lib/liblog.so
07-05 14:27:22.666  7964  7964 W art     : b6e9c000-b6e9d000 rw-p 00007000 b3:17 2644       /system/lib/liblog.so
07-05 14:27:22.666  7964  7964 W art     : b6e9d000-b6e9e000 r--p 00000000 00:00 0          [anon:linker_alloc]
07-05 14:27:22.666  7964  7964 W art     : b6e9e000-b6eb6000 r-xp 00000000 b3:17 2149       /system/lib/libutils.so
07-05 14:27:22.666  7964  7964 W art     : b6eb6000-b6eb7000 ---p 00000000 00:00 0 
07-05 14:27:22.666  7964  7964 W art     : b6eb7000-b6eb8000 r--p 00018000 b3:17 2149       /system/lib/libutils.so
07-05 14:27:22.666  7964  7964 W art     : b6eb8000-b6eb9000 rw-p 00019000 b3:17 2149       /system/lib/libutils.so
07-05 14:27:22.666  7964  7964 W art     : b6eb9000-b6ec7000 r-xp 00000000 b3:17 2714       /system/lib/libcutils.so
07-05 14:27:22.666  7964  7964 W art     : b6ec7000-b6ec8000 ---p 00000000 00:00 0 
07-05 14:27:22.666  7964  7964 W art     : b6ec8000-b6ec9000 r--p 0000e000 b3:17 2714       /system/lib/libcutils.so
07-05 14:27:22.666  7964  7964 W art     : b6ec9000-b6eca000 rw-p 0000f000 b3:17 2714       /system/lib/libcutils.so
07-05 14:27:22.666  7964  7964 W art     : b6eca000-b6ecb000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
07-05 14:27:22.666  7964  7964 W art     : b6ecb000-b6ecd000 r--p 00000000 00:00 0          [anon:linker_alloc]
07-05 14:27:22.666  7964  7964 W art     : b6ecd000-b6ece000 rw-p 00000000 00:00 0          [anon:linker_alloc]
07-05 14:27:22.666  7964  7964 W art     : b6ece000-b6ecf000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
07-05 14:27:22.666  7964  7964 W art     : b6ecf000-b6ed0000 rw-p 00000000 00:00 0          [anon:linker_alloc_32]
07-05 14:27:22.666  7964  7964 W art     : b6ed0000-b6ed1000 r--p 00000000 00:00 0          [anon:linker_alloc]
07-05 14:27:22.666  7964  7964 W art     : b6ed1000-b6ef1000 r--s 00000000 00:0b 6702       /dev/__properties__
07-05 14:27:22.666  7964  7964 W art     : b6ef1000-b6ef2000 r--p 00000000 00:00 0 
07-05 14:27:22.666  7964  7964 W art     : b6ef2000-b6ef3000 ---p 00000000 00:00 0 
07-05 14:27:22.666  7964  7964 W art     : b6ef3000-b6ef5000 rw-p 00000000 00:00 0          [anon:thread signal stack]
07-05 14:27:22.666  7964  7964 W art     : b6ef5000-b6ef6000 r-xp 00000000 00:00 0          [sigpage]
07-05 14:27:22.666  7964  7964 W art     : b6ef6000-b6f11000 r-xp 00000000 b3:17 2771       /system/bin/linker
07-05 14:27:22.666  7964  7964 W art     : b6f11000-b6f12000 r--p 0001a000 b3:17 2771       /system/bin/linker
07-05 14:27:22.666  7964  7964 W art     : b6f12000-b6f14000 rw-p 0001b000 b3:17 2771       /system/bin/linker
07-05 14:27:22.666  7964  7964 W art     : b6f14000-b6f16000 rw-p 00000000 00:00 0 
07-05 14:27:22.666  7964  7964 W art     : b6f16000-b6f1b000 r-xp 00000000 b3:17 978        /system/bin/app_process32
07-05 14:27:22.666  7964  7964 W art     : b6f1b000-b6f1c000 r--p 00004000 b3:17 978        /system/bin/app_process32
07-05 14:27:22.666  7964  7964 W art     : b6f1c000-b6f1d000 rw-p 00000000 00:00 0 
07-05 14:27:22.666  7964  7964 W art     : bef4f000-bef70000 rw-p 00000000 00:00 0          [stack]
07-05 14:27:22.666  7964  7964 W art     : ffff0000-ffff1000 r-xp 00000000 00:00 0          [vectors]
07-05 14:27:22.736  7964  7964 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
07-05 14:27:22.786  7964  7964 I Radio-JNI: register_android_hardware_Radio DONE
07-05 14:27:22.786  7964  7964 E AffinityControl: AffinityControl: registerfunction enter
07-05 14:27:22.806  7964  7964 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
07-05 14:27:22.816   767  1748 D PackageManager: START PACKAGE DELETE: observer{96295046}
07-05 14:27:22.816   767  1748 D PackageManager: pkg{<packageName>}
07-05 14:27:22.816   767  1748 D PackageManager: user{0}
07-05 14:27:22.816   767  1748 D PackageManager: caller{2000}
07-05 14:27:22.816   767  1748 D PackageManager: flags{2}
07-05 14:27:22.816   767  1748 D PersonaManagerService: isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
07-05 14:27:22.816   767  1748 D PersonaManagerService: isFromApprovedUnInstaller: isApproved : true
07-05 14:27:22.816   767  1748 D PersonaManagerService: isFromApprovedUnInstaller: isApproved before exit: true
07-05 14:27:22.816   767  1748 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
07-05 14:27:22.816   767  1748 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
07-05 14:27:22.816   767   950 D PackageManager: [MSG] DELETE_PACKAGE_AS_USER
07-05 14:27:22.816   767   950 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:0
07-05 14:27:22.816   767   950 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:-1
07-05 14:27:22.816   767   950 D ApplicationPolicy: getApplicationUninstallationEnabled
07-05 14:27:22.816   767   950 D ApplicationPolicy: getApplicationUninstallationEnabled :  enabled true
07-05 14:27:22.826   767   950 I PackageManager: !@  calling am.removeDeletedPkgsFromLru from PMS
07-05 14:27:22.826   767   950 D ActivityManager: removeDeletedPkgsFromLruStats called in AMS...com.test.thalitest
07-05 14:27:22.826   767   950 D PackageManager: !@killApplicatoin: 10004, uninstall pkg
07-05 14:27:22.826   767   866 I ActivityManager: Force stopping com.test.thalitest appid=10004 user=-1: uninstall pkg
07-05 14:27:22.826   767   950 I PackageManager: !@  calling am.removeDeletedPkgsFromLru from PMS
07-05 14:27:22.826   767   950 D ActivityManager: removeDeletedPkgsFromLruStats called in AMS...com.test.thalitest
07-05 14:27:22.826   767   866 I ActivityManager: Killing 6924:com.test.thalitest/u0a4 (adj 0): stop com.test.thalitest cause uninstall pkg
07-05 14:27:22.836   767   866 E ActivityManager: exception=android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
07-05 14:27:22.836   767   866 D ActivityManager: isAutoRunBlockedApp:: com.test.thalitest, Auto Run ON
07-05 14:27:22.836   767   866 D ActivityManager: mDVFSHelper.acquire()
07-05 14:27:22.856   767   907 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
07-05 14:27:22.856   767   866 I ActivityManager: Start proc 7979:com.test.thalitest/u0a4 for activity com.test.thalitest/.MainActivity
07-05 14:27:22.856   767   907 W System.err: 	at android.app.ApplicationPackageManager.getApplicationInfo(ApplicationPackageManager.java:366)
07-05 14:27:22.856   767   907 W System.err: 	at com.android.internal.policy.PhoneWindow.installDecor(PhoneWindow.java:4813)
07-05 14:27:22.866   767   907 W System.err: 	at com.android.internal.policy.PhoneWindow.getDecorView(PhoneWindow.java:2263)
07-05 14:27:22.866   767   907 W System.err: 	at com.android.server.policy.PhoneWindowManager.addStartingWindow(PhoneWindowManager.java:4342)
07-05 14:27:22.866   767   907 W System.err: 	at com.android.server.wm.WindowManagerService$H.handleMessage(WindowManagerService.java:13468)
07-05 14:27:22.866   767   907 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-05 14:27:22.866   767   907 W System.err: 	at android.os.Looper.loop(Looper.java:158)
07-05 14:27:22.866   767   907 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-05 14:27:22.866   767   907 W System.err: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
07-05 14:27:22.866  7979  7979 E Zygote  : v2
07-05 14:27:22.866  7979  7979 I libpersona: KNOX_SDCARD checking this for 10004
07-05 14:27:22.866  7979  7979 I libpersona: KNOX_SDCARD not a persona
07-05 14:27:22.866  7979  7979 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
07-05 14:27:22.866  7979  7979 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
07-05 14:27:22.866   767   907 D SecWifiDisplayUtil: Metadata value : none
07-05 14:27:22.866  7979  7979 E Zygote  : accessInfo : 0
07-05 14:27:22.866  7979  7979 W SELinux : SELinux: seapp_context_lookup: seinfo=default, level=s0:c512,c768, pkgname=com.test.thalitest 
07-05 14:27:22.866   767   907 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{50f25e V.E...... R.....ID 0,0-0,0}
07-05 14:27:22.866   767   866 I ActivityManager: Killing 7595:com.sec.android.daemonapp/u0a182 (adj 5): SSR - service for lastStateTime 798s, lastActivityTime 694s
07-05 14:27:22.866   767   866 I ActivityManager: Killing 7582:com.sec.android.pagebuddynotisvc/u0a27 (adj 5): SSR - service for lastStateTime 808s, lastActivityTime 808s
07-05 14:27:22.866   767   907 W WindowManager: view not successfully added to wm, removing view
07-05 14:27:22.866   767   866 I ActivityManager: Killing 7534:com.qualcomm.telephony/1000 (adj 8): SSR - service for lastStateTime 818s, lastActivityTime 818s
07-05 14:27:22.866   767   907 D ViewRootImpl: #3 mView = null
07-05 14:27:22.866   767   866 I ActivityManager: Killing 7488:com.sec.android.app.shealth:remote/u0a35 (adj 8): SSR - service for lastStateTime 819s, lastActivityTime 818s
07-05 14:27:22.876   767   866 I ActivityManager:   Force finishing activity ActivityRecord{c73e6de u0 com.test.thalitest/.MainActivity t77}
07-05 14:27:22.906   767  1811 D GraphicsStats: Buffer count: 4
07-05 14:27:22.906   767  1591 D ConnectivityService: ConnectivityService NetworkRequestInfo binderDied(NetworkRequest [ id=12, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], android.os.BinderProxy@2580b0c)
07-05 14:27:22.916   767  1331 D ConnectivityService: releasing NetworkRequest NetworkRequest [ id=12, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-05 14:27:22.916   767  1331 D ConnectivityService: sending notification RELEASED for NetworkRequest [ id=12, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-05 14:27:22.916   292   292 I ServiceManager: service 'AtCmdFwd' died
07-05 14:27:22.916   293  1829 D libEGL  : eglTerminate EGLDisplay = 0xb476f6fc
07-05 14:27:22.916   293  1829 D libEGL  : eglTerminate EGLDisplay = 0xb476f6fc
07-05 14:27:22.916   370  4577 I Atfwd_Sendcmd: AtCmdFwd : binderDied
07-05 14:27:22.916   767  1331 E ConnectivityService: RemoteException caught trying to send a callback msg for NetworkRequest [ id=12, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-05 14:27:22.916   370  4577 I ServiceManager: Waiting for service AtCmdFwd...
07-05 14:27:22.926   767   866 D InputDispatcher: Focus left window: 6924
07-05 14:27:22.926   293  1364 I SurfaceFlinger: id=20 Removed NainActivit (6/8)
07-05 14:27:22.926   293   373 I SurfaceFlinger: id=20 Removed NainActivit (-2/8)
07-05 14:27:22.926   767   950 D AASAinstall: there is not AASApackages.xml file
07-05 14:27:22.926   767   866 D InputDispatcher: Focused application released
07-05 14:27:22.936   293  1829 I SurfaceFlinger: id=20 Removed NainActivit (-2/8)
07-05 14:27:22.936   767   866 D FocusedStackFrame: Set to : 0
07-05 14:27:22.936   767  4844 W WindowManager: Failed looking up window
07-05 14:27:22.936   767  4844 W WindowManager: java.lang.IllegalArgumentException: Requested window android.os.BinderProxy@5b38516 does not exist
07-05 14:27:22.936   767  4844 W WindowManager: 	at com.android.server.wm.WindowManagerService.windowForClientLocked(WindowManagerService.java:14788)
07-05 14:27:22.936   767  4844 W WindowManager: 	at com.android.server.wm.WindowManagerService.windowForClientLocked(WindowManagerService.java:14779)
07-05 14:27:22.936   767  4844 W WindowManager: 	at com.android.server.wm.WindowState$DeathRecipient.binderDied(WindowState.java:1764)
07-05 14:27:22.936   767  4844 W WindowManager: 	at android.os.BinderProxy.sendDeathNotice(Binder.java:558)
07-05 14:27:22.936   767  4844 I WindowState: WIN DEATH: null
07-05 14:27:22.936  7979  7979 D TimaKeyStoreProvider: TimaSignature is unavailable
07-05 14:27:22.936  7979  7979 D ActivityThread: Added TimaKeyStore provider
07-05 14:27:22.936   293   293 D libEGL  : eglTerminate EGLDisplay = 0xbe99b3a4
07-05 14:27:22.936   767   907 D PointerIcon: setMouseIconStyle1 pointerType: 1001 iconType:101 flag:0 pid:767 uid:1000
07-05 14:27:22.936   767   907 D PointerIcon: setMouseCustomIcon IconType is same.101
07-05 14:27:22.936   767   907 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001 iconType:1 flag:0 pid:767 uid:1000
07-05 14:27:22.936   767   907 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
07-05 14:27:23.226   767   950 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/packages.xml.bak
07-05 14:27:23.256   767   950 W PackageSettings: Skipping PackageSetting{4d56d5a com.example.hello/10201} due to missing metadata
07-05 14:27:23.326   767   950 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/users/0/package-restrictions.xml.bak
07-05 14:27:23.326   325   325 W keystore: ENTER clear_uid from uid 1000 for 10004
07-05 14:27:23.326   767   950 I art     : Starting a blocking GC Explicit
07-05 14:27:23.346   767   866 V WindowOrientationListener: setCurrentAppOrientation :1
07-05 14:27:23.346   767   866 V WindowManager: rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false mMobileKeyboardEnabled=false displayId=0
07-05 14:27:23.356  1749  1749 D Launcher: onRestart, Launcher: 154482294
07-05 14:27:23.356   767  1826 D ActivityManager: isAutoRunBlockedApp:: com.sec.android.app.shealth, Auto Run ON
07-05 14:27:23.356   767  1826 I ActivityManager: isWidgetUsingPkg : com.sec.android.app.shealth widget is using.
07-05 14:27:23.356   767  1826 W ActivityManager: Scheduling restart of crashed service com.sec.android.app.shealth/com.samsung.android.app.shealth.data.DelegateService in 1000ms
07-05 14:27:23.366   767   866 V MARsPolicyManager: updatePackagesScore PackageInfo name -- com.sec.android.app.launcher
07-05 14:27:23.366   767  1409 D ActivityManager: isAutoRunBlockedApp:: com.qualcomm.atfwd, Auto Run ON
07-05 14:27:23.366   767  1409 I ActivityManager: isWidgetUsingPkg : com.qualcomm.atfwd no widget is using.
07-05 14:27:23.366   767  1409 W ActivityManager: Scheduling restart of crashed service com.qualcomm.atfwd/.AtFwdService in 10991ms
07-05 14:27:23.376   767  1748 D ActivityManager: isAutoRunBlockedApp:: com.sec.android.daemonapp, Auto Run ON
07-05 14:27:23.376   767  1748 I ActivityManager: isWidgetUsingPkg : com.sec.android.daemonapp no widget is using.
07-05 14:27:23.376   767  1748 W ActivityManager: Scheduling restart of crashed service com.sec.android.daemonapp/.ap.accuweather.WeatherClockService in 20985ms
07-05 14:27:23.386   767  1679 D Acti,vityManager: isAutoRunBlockedApp:: com.sec.android.pagebuddynotisvc, Auto Run ON
07-05 14:27:23.386   767  1679 I ActivityManager: isWidgetUsingPkg : com.sec.android.pagebuddynotisvc no widget is using.
07-05 14:27:23.386   767  1679 W ActivityManager: Scheduling restart of crashed service com.sec.android.pagebuddynotisvc/.PageBuddyNotiSvc in 30974ms
07-05 14:27:23.396  1749  1749 D Launcher: onStart, Launcher: 154482294
07-05 14:27:23.396  1749  1749 D Launcher: setSystemUiTransparency.SettingNotFoundException : set as TRUE
07-05 14:27:23.396  1749  1749 D Launcher: Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
07-05 14:27:23.396  1749  1749 D Launcher.HomeView: onStart
07-05 14:27:23.396   767  1767 I ActivityManager: Killing 6367:com.sec.android.provider.badge/u0a78 (adj 15): DHA:empty #37
07-05 14:27:23.396  1749  1749 D Launcher: onResume, Launcher: 154482294
07-05 14:27:23.396   767  4844 D SettingsProvider: isChangeAllowed() : name = kids_home_mode
07-05 14:27:23.396   767  4844 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
07-05 14:27:23.396   767  4844 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
07-05 14:27:23.396   767  4844 D SettingsProvider: selectionArgs: false
07-05 14:27:23.396   767  4844 D SettingsProvider: selectionArgs: 10008
07-05 14:27:23.396   767  4844 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
07-05 14:27:23.396   767  4844 D SettingsProvider: ret = -1
07-05 14:27:23.396  1749  1749 D Launcher.HomeView: onResume
07-05 14:27:23.396  1749  1749 D SurfaceWidgetConnection: .SurfaceWidgetWeather#1 Checking SurfaceTexture if it needs to be updated
07-05 14:27:23.396  1749  1749 D SurfaceWidgetConnection: .SurfaceWidgetWeather#1 SurfaceTexture was set
07-05 14:27:23.396  1749  1749 D SurfaceWidgetConnection: .SurfaceWidgetWeather#1 is being resumed by launcher
07-05 14:27:23.406  2290  2305 D SurfaceWidgetClient$ISurfaceWidgetStub: [237392/23] Surface widget resume on instance = 1
07-05 14:27:23.406  2290  2290 D accuweather: [KK AccuPhone]>>> SWW:209 [0:0] [SWW] onResume : instance = 1
07-05 14:27:23.416  8009  8009 E Zygote  : v2
07-05 14:27:23.416  8009  8009 I libpersona: KNOX_SDCARD checking this for 10182
07-05 14:27:23.416  8009  8009 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
07-05 14:27:23.416  8009  8009 I libpersona: KNOX_SDCARD not a persona
07-05 14:27:23.416  8009  8009 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
07-05 14:27:23.426   767   784 I ActivityManager: Start proc 8009:com.sec.android.daemonapp/u0a182 for content provider com.sec.android.daemonapp/.ap.common.WeatherContentProvider
07-05 14:27:23.416  8009  8009 E Zygote  : accessInfo : 0
07-05 14:27:23.416  8009  8009 W SELinux : SELinux: seapp_context_lookup: seinfo=shared, level=s0:c512,c768, pkgname=com.sec.android.daemonapp 
07-05 14:27:23.426  1749  1749 D MenuAppsGridFragment: onResume
07-05 14:27:23.426   767   866 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{a228c55 u0 com.sec.android.intent.action.HOME_RESUME qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{b42d9b6 1733:com.android.phone/1001}
07-05 14:27:23.446   767  1409 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{a228c55 u0 com.sec.android.intent.action.HOME_RESUME qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{a8288e1 4986:com.android.settings/1000}
07-05 14:27:23.446  1749  1749 D SurfaceWidgetConnection: .SurfaceWidgetWeather#1 Checking SurfaceTexture if it needs to be updated
07-05 14:27:23.446   767  1466 W BroadcastQueue: Permission Denial: broadcasting Intent { act=com.sec.android.intent.action.HOME_RESUME flg=0x10 } from com.sec.android.app.launcher (pid=1749, uid=10008) is not exported from uid 1000 due to receiver com.android.settings/.accessibilitywidget.AccessibilityEasyWidgetProviderAssistiveLight
07-05 14:27:23.456  2290  2303 D SurfaceWidgetClient$ISurfaceWidgetStub: [237392/23] Surface widget visibility changed visibility = true on instance = 1
07-05 14:27:23.456  7979  7979 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.test.thalitest rsrc of package null
07-05 14:27:23.456   767  3520 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
07-05 14:27:23.466  8026  8026 E Zygote  : v2
07-05 14:27:23.466  8026  8026 I libpersona: KNOX_SDCARD checking this for 10154
07-05 14:27:23.466  8026  8026 I libpersona: KNOX_SDCARD not a persona
07-05 14:27:23.476  8026  8026 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
07-05 14:27:23.476  8026  8026 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
07-05 14:27:23.476   767  4119 D ActivityManager: post active user change for 0 fullscreen true isFloatingActivity() false isHomeActivity() true
07-05 14:27:23.476   767   866 I ActivityManager: Start proc 8026:com.sec.android.app.camera/u0a154 for broadcast-3 com.sec.android.app.camera/.HomeResumeCamera
07-05 14:27:23.476   767  4119 I WallpaperManagerService: switchPersonaWallpaper is called for personaId-0
07-05 14:27:23.476   767  4119 D KnoxTimeoutHandler: post home show event for user 0
07-05 14:27:23.476   767  4119 D KnoxTimeoutHandler: postActiveUserChange [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
07-05 14:27:23.476  8026  8026 E Zygote  : accessInfo : 0
07-05 14:27:23.476   767   767 D WallpaperManagerService:  force update = false; persona id = 0; current user =0; current persona = 0
07-05 14:27:23.476   767   767 D KnoxTimeoutHandler: handleHomeShow for 0 and current 0
07-05 14:27:23.476   767   767 D KnoxTimeoutHandler: handleActiveUserChange [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
07-05 14:27:23.476  8026  8026 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.sec.android.app.camera 
07-05 14:27:23.476  1749  1749 D Launcher.HomeView: onPause
07-05 14:27:23.476  1749  1749 D SurfaceWidgetConnection: .SurfaceWidgetWeather#1 is being paused by launcher
07-05 14:27:23.476  2290  2305 D SurfaceWidgetClient$ISurfaceWidgetStub: [237392/23] Surface widget pause on instance = 1
07-05 14:27:23.476   767  1322 D NetworkPolicy: isUidForegroundLocked: 10154, mScreenOn: false, uidstate: -1, mProxSensorScreenOff: false
07-05 14:27:23.476  1749  1749 D Launcher: Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
07-05 14:27:23.476   767   767 I KnoxTimeoutHandler: Shared devices show user statefalse
07-05 14:27:23.476   767  1589 D ActivityManager: isAutoRunBlockedApp:: com.sec.android.provider.badge, Auto Run ON
07-05 14:27:23.486  8009  8009 D TimaKeyStoreProvider: TimaSignature is unavailable
07-05 14:27:23.486  8009  8009 D ActivityThread: Added TimaKeyStore provider
07-05 14:27:23.486  7979  7979 W ContextImpl: Unable to create files subdir /data/user/0/com.test.thalitest/cache
07-05 14:27:23.486  7979  7979 V ActivityThread: Unable to initialize "java.io.tmpdir" property due to missing cache directory
07-05 14:27:23.486  7979  7979 W ContextImpl: Unable to create files subdir /data/user/0/com.test.thalitest/code_cache
07-05 14:27:23.486  7979  7979 E ActivityThread: Unable to setupGraphicsSupport due to missing code-cache directory
07-05 14:27:23.496   767  1322 D NetworkPolicy: isUidForegroundLocked: 10154, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
07-05 14:27:23.496   293   293 I SurfaceFlinger: id=24 createSurf (1080x1920),1 flag=4, Mauncher
07-05 14:27:23.496  8009  8009 W ResourcesManager: getTopLevelResources: /system/app/WeatherDaemon2014_MMR/WeatherDaemon2014_MMR.apk / 1.0 running in com.sec.android.daemonapp rsrc of package null
07-05 14:27:23.506   767  1590 D InputDispatcher: Focus entered window: 1749
07-05 14:27:23.506   767   907 D PointerIcon: setMouseIconStyle1 pointerType: 1001 iconType:101 flag:0 pid:767 uid:1000
07-05 14:27:23.506   767   907 D PointerIcon: setMouseCustomIcon IconType is same.101
07-05 14:27:23.506   767   907 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001 iconType:1 flag:0 pid:767 uid:1000
07-05 14:27:23.506   767   907 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
07-05 14:27:23.516   767   868 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=Window{9f87f10 u0 d0 com.sec.android.app.launcher/com.android.launcher2.Launcher}
07-05 14:27:23.516  1380  1380 D PhoneStatusBar: setSystemUiVisibility vis=8500 mask=ffffffff oldVal=8600 newVal=8500 diff=300
07-05 14:27:23.516  1749  1749 V ActivityThread: updateVisibility : ActivityRecord{ab038a1 token=android.os.BinderProxy@58db99b {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : true
07-05 14:27:23.516  1749  1749 D Launcher.HomeView: onStop
07-05 14:27:23.516   767   868 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=Window{9f87f10 u0 d0 com.sec.android.app.launcher/com.android.launcher2.Launcher}
07-05 14:27:23.516  1380  1380 D PhoneStatusBar: setSystemUiVisibility vis=40008500 mask=ffffffff oldVal=8500 newVal=40008500 diff=40000000
07-05 14:27:23.516   767  1826 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
07-05 14:27:23.516   767  1826 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 6924 uid 10004
07-05 14:27:23.526  8026  8026 D TimaKeyStoreProvider: TimaSignature is unavailable
07-05 14:27:23.526  8026  8026 D ActivityThread: Added TimaKeyStore provider
07-05 14:27:23.526  8009  8009 W System  : ClassLoader referenced unknown path: /system/app/WeatherDaemon2014_MMR/lib/arm
07-05 14:27:23.526  2105  2105 D SamsungIME: onStartInput: No inputType, No imeOption, isInputViewShown = false, isExtractViewShown = false, isShowInputRequested = false, isConfigChanged = false

```
