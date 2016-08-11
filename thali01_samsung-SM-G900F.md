#### Test 80912877b687439_thali01_samsung-SM-G900F Logs


```
--------- beginning of main
08-11 10:48:58.952  6294  6294 D CAR.SERVICE: onUnbind
08-11 10:48:58.952  6294  6294 D CAR.SERVICE: CSB onClientsDisconnected
08-11 10:48:58.952  6294  6294 D CAR.SERVICE: tearDown
08-11 10:48:58.952  6294  6294 D CAR.SERVICE: tearDownCarState
08-11 10:48:58.952  6294  6294 D CAR.SERVICE: Skip, car not connected.
08-11 10:48:58.952  6294  6294 D CAR.SERVICE: tearDownClientState
08-11 10:48:58.952  6294  6294 D CAR.SERVICE: requestStop
08-11 10:48:58.952  6294  6294 D CAR.SERVICE: onDestroy
08-11 10:48:58.952  6294  6294 D CAR.SERVICE: tearDown
08-11 10:48:58.952  6294  6294 D CAR.SERVICE: tearDownCarState
08-11 10:48:58.952  6294  6294 D CAR.SERVICE: Skip, car not connected.
08-11 10:48:58.952  6294  6294 D CAR.SERVICE: tearDownClientState
08-11 10:48:58.952  6294  6294 D CAR.SERVICE: requestStop
--------- beginning of system
08-11 10:48:58.962  6294  6294 E ActivityThread: Service com.google.android.gms.car.CarService has leaked ServiceConnection fmj@a604a7f that was originally bound here
08-11 10:48:58.962  6294  6294 E ActivityThread: android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarService has leaked ServiceConnection fmj@a604a7f that was originally bound here
08-11 10:48:58.962  6294  6294 E ActivityThread: 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1204)
08-11 10:48:58.962  6294  6294 E ActivityThread: 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1098)
08-11 10:48:58.962  6294  6294 E ActivityThread: 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1412)
08-11 10:48:58.962  6294  6294 E ActivityThread: 	at android.app.ContextImpl.bindService(ContextImpl.java:1395)
08-11 10:48:58.962  6294  6294 E ActivityThread: 	at android.content.ContextWrapper.bindService(ContextWrapper.java:632)
08-11 10:48:58.962  6294  6294 E ActivityThread: 	at android.content.ContextWrapper.bindService(ContextWrapper.java:632)
08-11 10:48:58.962  6294  6294 E ActivityThread: 	at android.content.ContextWrapper.bindService(ContextWrapper.java:632)
08-11 10:48:58.962  6294  6294 E ActivityThread: 	at ivw.a(:com.google.android.gms:120)
08-11 10:48:58.962  6294  6294 E ActivityThread: 	at ivw.a(:com.google.android.gms:137)
08-11 10:48:58.962  6294  6294 E ActivityThread: 	at fmj.h(:com.google.android.gms:76)
08-11 10:48:58.962  6294  6294 E ActivityThread: 	at fmj.<init>(:com.google.android.gms:64)
08-11 10:48:58.962  6294  6294 E ActivityThread: 	at fpn.i(:com.google.android.gms:551)
08-11 10:48:58.962  6294  6294 E ActivityThread: 	at com.google.android.gms.car.CarChimeraService.onBind(:com.google.android.gms:165)
08-11 10:48:58.962  6294  6294 E ActivityThread: 	at com.google.android.chimera.container.ServiceProxy.onBind(:com.google.android.gms:165)
08-11 10:48:58.962  6294  6294 E ActivityThread: 	at android.app.ActivityThread.handleBindService(ActivityThread.java:3834)
08-11 10:48:58.962  6294  6294 E ActivityThread: 	at android.app.ActivityThread.access$2200(ActivityThread.java:221)
08-11 10:48:58.962  6294  6294 E ActivityThread: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1887)
08-11 10:48:58.962  6294  6294 E ActivityThread: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-11 10:48:58.962  6294  6294 E ActivityThread: 	at android.os.Looper.loop(Looper.java:158)
08-11 10:48:58.962  6294  6294 E ActivityThread: 	at android.app.ActivityThread.main(ActivityThread.java:7224)
08-11 10:48:58.962  6294  6294 E ActivityThread: 	at java.lang.reflect.Method.invoke(Native Method)
08-11 10:48:58.962  6294  6294 E ActivityThread: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1230)
08-11 10:48:58.962  6294  6294 E ActivityThread: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1120)
08-11 10:48:58.962   781  1455 W ActivityManager: Unbind failed: could not find connection for android.os.BinderProxy@8993993
,08-11 10:48:59.082   781  2428 V MARsPolicyManager: updatePackagesScore PackageInfo name -- null
08-11 10:48:59.092   781  2428 V MARsPolicyManager: updateSMDBValues
08-11 10:48:59.092   781   916 E MARsDBManager: updateDBAll : begin --size 0
08-11 10:48:59.092   781   916 E MARsDBManager: updateDBAll : end
08-11 10:48:59.502   781  3528 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
08-11 10:48:59.902  2329  2329 E audit   : type=1400 msg=audit(1470905339.892:286): avc:  denied  { execmod } for  pid=6398 comm="app_process" path="/system/lib/lib_SoundAlive_ver118t.so" dev="mmcblk0p23" ino=1786 scontext=u:r:shell:s0 tcontext=u:object_r:system_file:s0 tclass=file permissive=0
08-11 10:48:59.902  2329  2329 E audit   :  SEPF_SECMOBILE_6.0.1_0011
08-11 10:48:59.902  2329  2329 E audit   : type=1300 msg=audit(1470905339.892:286): arch=40000028 syscall=125 per=800008 success=no exit=-13 a0=b3fa5000 a1=51000 a2=5 a3=4 items=0 ppid=3644 ppcomm=adbd pid=6398 auid=4294967295 uid=2000 gid=2000 euid=2000 suid=2000 fsuid=2000 egid=2000 sgid=2000 fsgid=2000 tty=pts1 ses=4294967295 comm="app_process" exe="/system/bin/app_process32" subj=u:r:shell:s0 key=(null)
08-11 10:48:59.902  2329  2329 E audit   : type=1327 msg=audit(1470905339.892:286): proctitle=6170705F70726F63657373002F73797374656D2F62696E00636F6D2E616E64726F69642E636F6D6D616E64732E616D2E416D007374617274002D6E00636F6D2E746573742E7468616C69746573742F636F6D2E746573742E7468616C69746573742E4D61696E4163746976697479
08-11 10:48:59.902  2329  2329 E audit   : type=1320 msg=audit(1470905339.892:286): 
08-11 10:48:59.952  2329  2329 E audit   : type=1400 msg=audit(1470905339.952:287): avc:  denied  { execmod } for  pid=6398 comm="app_process" path="/system/lib/lib_SoundAlive_ver118t.so" dev="mmcblk0p23" ino=1786 scontext=u:r:shell:s0 tcontext=u:object_r:system_file:s0 tclass=file permissive=0
08-11 10:48:59.952  2329  2329 E audit   :  SEPF_SECMOBILE_6.0.1_0011
08-11 10:48:59.962  2329  2329 E audit   : type=1300 msg=audit(1470905339.952:287): arch=40000028 syscall=125 per=800008 success=no exit=-13 a0=b3f65000 a1=51000 a2=5 a3=4 items=0 ppid=3644 ppcomm=adbd pid=6398 auid=4294967295 uid=2000 gid=2000 euid=2000 suid=2000 fsuid=2000 egid=2000 sgid=2000 fsgid=2000 tty=pts1 ses=4294967295 comm="app_process" exe="/system/bin/app_process32" subj=u:r:shell:s0 key=(null)
08-11 10:48:59.962  2329  2329 E audit   : type=1327 msg=audit(1470905339.952:287): proctitle=6170705F70726F63657373002F73797374656D2F62696E00636F6D2E616E64726F69642E636F6D6D616E64732E616D2E416D007374617274002D6E00636F6D2E746573742E7468616C69746573742F636F6D2E746573742E7468616C69746573742E4D61696E4163746976697479
08-11 10:48:59.962  2329  2329 E audit   : type=1320 msg=audit(1470905339.952:287): 
08-11 10:49:00.002   781  1238 V AlarmManager: Expired Alarm result :8
08-11 10:49:00.012  5542  5542 D AASAservice-RuleManager: IsSharedUID() : pkgname - com.test.thalitest, mSharedUserId - null
08-11 10:49:00.012  5542  5542 D AASAservice-UpdateReceiver: AASAUpdateReceiver : check SharedUID package.
08-11 10:49:00.012  5542  5542 E AASAservice-UpdateReceiver: AASAUpdateReceiver : myrule is null.
08-11 10:49:00.012  5542  5542 I art     : System.exit called, status: 0
08-11 10:49:00.012  5542  5542 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
08-11 10:49:00.022  2329  2329 E audit   : type=1400 msg=audit(1470905340.022:288): avc:  denied  { execmod } for  pid=6398 comm="app_process" path="/system/lib/lib_SoundAlive_ver118t.so" dev="mmcblk0p23" ino=1786 scontext=u:r:shell:s0 tcontext=u:object_r:system_file:s0 tclass=file permissive=0
08-11 10:49:00.022  2329  2329 E audit   :  SEPF_SECMOBILE_6.0.1_0011
08-11 10:49:00.022  2329  2329 E audit   : type=1300 msg=audit(1470905340.022:288): arch=40000028 syscall=125 per=800008 success=no exit=-13 a0=b3f65000 a1=51000 a2=5 a3=4 items=0 ppid=3644 ppcomm=adbd pid=6398 auid=4294967295 uid=2000 gid=2000 euid=2000 suid=2000 fsuid=2000 egid=2000 sgid=2000 fsgid=2000 tty=pts1 ses=4294967295 comm="app_process" exe="/system/bin/app_process32" subj=u:r:shell:s0 key=(null)
08-11 10:49:00.022  2329  2329 E audit   : type=1327 msg=audit(1470905340.022:288): proctitle=6170705F70726F63657373002F73797374656D2F62696E00636F6D2E616E64726F69642E636F6D6D616E64732E616D2E416D007374617274002D6E00636F6D2E746573742E7468616C69746573742F636F6D2E746573742E7468616C69746573742E4D61696E4163746976697479
08-11 10:49:00.022  2329  2329 E audit   : type=1320 msg=audit(1470905340.022:288): 
08-11 10:49:00.022  6398  6398 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
08-11 10:49:00.022  6398  6398 D AndroidRuntime: CheckJNI is OFF
08-11 10:49:00.022  6398  6398 D AndroidRuntime: readGMSProperty: start
08-11 10:49:00.022  6398  6398 D AndroidRuntime: readGMSProperty: already setted!!
08-11 10:49:00.022  6398  6398 D AndroidRuntime: propertySet: couldn't set property (it is from app)
08-11 10:49:00.022  6398  6398 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
08-11 10:49:00.022  6398  6398 D AndroidRuntime: readGMSProperty: end
08-11 10:49:00.022  6398  6398 D AndroidRuntime: addProductProperty: start
08-11 10:49:00.032  6398  6398 W art     : 6f853000-705d0000 rw-p 00000000 b3:1a 130841     /data/dalvik-cache/arm/system@framework@boot.art
08-11 10:49:00.032  6398  6398 W art     : aedcc000-b1cf2000 r--p 00000000 b3:17 579        /system/framework/arm/boot.oat
08-11 10:49:00.032  6398  6398 W art     : b1cf2000-b3f61000 r-xp 02f26000 b3:17 579        /system/framework/arm/boot.oat
08-11 10:49:00.032  6398  6398 W art     : b3f61000-b3f62000 rw-p 05195000 b3:17 579        /system/framework/arm/boot.oat
08-11 10:49:00.032  6398  6398 W art     : b3f62000-b3f63000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-11 10:49:00.032  6398  6398 W art     : b42a4000-b46f2000 r-xp 00000000 b3:17 332        /system/lib/libart.so
08-11 10:49:00.032  6398  6398 W art     : b46f2000-b46f3000 ---p 00000000 00:00 0 
08-11 10:49:00.032  6398  6398 W art     : b46f3000-b46fd000 r--p 0044e000 b3:17 332        /system/lib/libart.so
08-11 10:49:00.032  6398  6398 W art     : b46fd000-b46fe000 rw-p 00458000 b3:17 332        /system/lib/libart.so
08-11 10:49:00.032  6398  6398 W art     : b46fe000-b4700000 rw-p 00000000 00:00 0 
08-11 10:49:00.032  6398  6398 W art     : b4700000-b4800000 rw-p 00000000 00:00 0          [anon:libc_malloc]
08-11 10:49:00.032  6398  6398 W art     : b480d000-b4836000 r--p 00d7d000 b3:1a 130841     /data/dalvik-cache/arm/system@framework@boot.art
08-11 10:49:00.032  6398  6398 W art     : b4836000-b4839000 r-xp 00000000 b3:17 2415       /system/lib/libsigchain.so
08-11 10:49:00.032  6398  6398 W art     : b4839000-b483a000 r--p 00002000 b3:17 2415       /system/lib/libsigchain.so
08-11 10:49:00.032  6398  6398 W art     : b483a000-b483b000 rw-p 00003000 b3:17 2415       /system/lib/libsigchain.so
08-11 10:49:00.032  6398  6398 W art     : b483b000-b483c000 r--p 00000000 00:00 0 
08-11 10:49:00.032  6398  6398 W art     : b483c000-b485c000 r--s 00000000 00:0b 8195       /dev/__properties__
08-11 10:49:00.032  6398  6398 W art     : b485c000-b526d000 r-xp 00000000 b3:17 2805       /system/lib/libLLVM.so
08-11 10:49:00.032  6398  6398 W art     : b526d000-b526e000 ---p 00000000 00:00 0 
08-11 10:49:00.032  6398  6398 W art     : b526e000-b52b7000 r--p 00a11000 b3:17 2805       /system/lib/libLLVM.so
08-11 10:49:00.032  6398  6398 W art     : b52b7000-b52b8000 rw-p 00a5a000 b3:17 2805       /system/lib/libLLVM.so
08-11 10:49:00.032  6398  6398 W art     : b52b8000-b52c0000 rw-p 00000000 00:00 0 
08-11 10:49:00.032  6398  6398 W art     : b52c0000-b52c1000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-11 10:49:00.032  6398  6398 W art     : b52c1000-b52f6000 r-xp 00000000 b3:17 726        /system/lib/libbcinfo.so
08-11 10:49:00.032  6398  6398 W art     : b52f6000-b52f7000 ---p 00000000 00:00 0 
08-11 10:49:00.032  6398  6398 W art     : b52f7000-b52f8000 r--p 00035000 b3:17 726        /system/lib/libbcinfo.so
08-11 10:49:00.032  6398  6398 W art     : b52f8000-b52f9000 rw-p 00036000 b3:17 726        /system/lib/libbcinfo.so
08-11 10:49:00.032  6398  6398 W art     : b52f9000-b5351000 r-xp 00000000 b3:17 2785       /system/lib/libbcc.so
08-11 10:49:00.032  6398  6398 W art     : b5351000-b5352000 ---p 00000000 00:00 0 
08-11 10:49:00.032  6398  6398 W art     : b5352000-b5353000 r--p 00058000 b3:17 2785       /system/lib/libbcc.so
08-11 10:49:00.032  6398  6398 W art     : b5353000-b5354000 rw-p 00059000 b3:17 2785       /system/lib/libbcc.so
08-11 10:49:00.032  6398  6398 W art     : b5355000-b535b000 r-xp 00000000 b3:17 32         /system/lib/lib_SamsungVAD_v01009.so
08-11 10:49:00.032  6398  6398 W art     : b535b000-b535c000 r--p 00005000 b3:17 32         /system/lib/lib_SamsungVAD_v01009.so
08-11 10:49:00.032  6398  6398 W art     : b535c000-b535d000 rw-p 00006000 b3:17 32         /system/lib/lib_SamsungVAD_v01009.so
08-11 10:49:00.032  6398  6398 W art     : b535d000-b535f000 rw-p 00000000 00:00 0 
08-11 10:49:00.032  6398  6398 W art     : b5360000-b536a000 r-xp 00000000 b3:17 1088       /system/lib/libcommon_time_client.so
08-11 10:49:00.032  6398  6398 W art     : b536a000-b536d000 r--p 00009000 b3:17 1088       /system/lib/libcommon_time_client.so
08-11 10:49:00.032  6398  6398 W art     : b536d000-b536e000 rw-p 0000c000 b3:17 1088       /system/lib/libcommon_time_client.so
08-11 10:49:00.032  6398  6398 W art     : b536f000-b5386000 r-xp 00000000 b3:17 2932       /system/lib/libprotobuf-cpp-lite.so
08-11 10:49:00.032  6398  6398 W art     : b5386000-b5387000 ---p 00000000 00:00 0 
08-11 10:49:00.032  6398  6398 W art     : b5387000-b5388000 r--p 00017000 b3:17 2932       /system/lib/libprotobuf-cpp-lite.so
08-11 10:49:00.032  6398  6398 W art     : b5388000-b5389000 rw-p 00018000 b3:17 2932       /system/lib/libprotobuf-cpp-lite.so
08-11 10:49:00.032  6398  6398 W art     : b538a000-b5394000 r-xp 00000000 b3:17 2671       /system/lib/libsec_km.so
08-11 10:49:00.032  6398  6398 W art     : b5394000-b5395000 r--p 00009000 b3:17 2671       /system/lib/libsec_km.so
08-11 10:49:00.032  6398  6398 W art     : b5395000-b5396000 rw-p 0000a000 b3:17 2671       /system/lib/libsec_km.so
08-11 10:49:00.032  6398  6398 W art     : b5396000-b539a000 r-xp 00000000 b3:17 2888       /system/lib/libSEF4MP4.so
08-11 10:49:00.032  6398  6398 W art     : b539a000-b539b000 r--p 00003000 b3:17 2888       /system/lib/libSEF4MP4.so
08-11 10:49:00.032  6398  6398 W art     : b539b000-b539c000 rw-p 00004000 b3:17 2888       /system/lib/libSEF4MP4.so
08-11 10:49:00.032  6398  6398 W art     : b539c000-b53b2000 r-xp 00000000 b3:17 2121       /system/lib/libSEF.so
08-11 10:49:00.032  6398  6398 W art     : b53b2000-b53b3000 r--p 00015000 b3:17 2121       /system/lib/libSEF.so
08-11 10:49:00.032  6398  6398 W art     : b53b3000-b53b4000 rw-p 00016000 b3:17 2121       /system/lib/libSEF.so
08-11 10:49:00.032  6398  6398 W art     : b53b4000-b53c1000 r-xp 00000000 b3:17 1082       /system/lib/libsfextcp.so
08-11 10:49:00.032  6398  6398 W art     : b53c1000-b53c2000 r--p 0000c000 b3:17 1082       /system/lib/libsfextcp.so
08-11 10:49:00.032  6398  6398 W art     : b53c2000-b53c3000 rw-p 0000d000 b3:17 1082       /system/lib/libsfextcp.so
08-11 10:49:00.032  6398  6398 W art     : b53c3000-b5423000 r-xp 00000000 b3:17 405        /system/lib/libsavsff.so
08-11 10:49:00.032  6398  6398 W art     : b5423000-b5426000 rw-p 0005f000 b3:17 405        /system/lib/libsavsff.so
08-11 10:49:00.032  6398  6398 W art     : b5426000-b542a000 rw-p 00000000 00:00 0 
08-11 10:49:00.032  6398  6398 W art     : b542a000-b548b000 r-xp 00000000 b3:17 385        /system/lib/libsavscmn.so
08-11 10:49:00.032  6398  6398 W art     : b548b000-b548c000 rw-p 00061000 b3:17 385        /system/lib/libsavscmn.so
08-11 10:49:00.032  6398  6398 W art     : b548c000-b54db000 r-xp 00000000 b3:17 2399       /system/lib/libomafldrm.so
08-11 10:49:00.032  6398  6398 W art     : b54db000-b54dd000 r--p 0004e000 b3:17 2399       /system/lib/libomafldrm.so
08-11 10:49:00.032  6398  6398 W art     : b54dd000-b54de000 rw-p 00050000 b3:17 2399       /system/lib/libomafldrm.so
08-11 10:49:00.032  6398  6398 W art     : b54de000-b54df000 rw-p 00000000 00:00 0 
08-11 10:49:00.032  6398  6398 W art     : b54df000-b54e6000 r-xp 00000000 b3:17 2576       /system/lib/libstagefright_avc_common.so
08-11 10:49:00.032  6398  6398 W art     : b54e6000-b54e7000 r--p 00006000 b3:17 2576       /system/lib/libstagefright_avc_common.so
08-11 10:49:00.032  6398  6398 W art     : b54e7000-b54e8000 rw-p 00007000 b3:17 2576       /system/lib/libstagefright_
08-11 10:49:00.032  6398  6398 W art     : avc_common.so
08-11 10:49:00.032  6398  6398 W art     : b54e9000-b54ec000 r-xp 00000000 b3:17 2552       /system/lib/libstagefright_enc_common.so
08-11 10:49:00.032  6398  6398 W art     : b54ec000-b54ed000 r--p 00002000 b3:17 2552       /system/lib/libstagefright_enc_common.so
08-11 10:49:00.032  6398  6398 W art     : b54ed000-b54ee000 rw-p 00003000 b3:17 2552       /system/lib/libstagefright_
08-11 10:49:00.032  6398  6398 W art     : enc_common.so
08-11 10:49:00.032  6398  6398 W art     : b54ef000-b54f3000 r-xp 00000000 b3:17 2510       /system/lib/libpowermanager.so
08-11 10:49:00.032  6398  6398 W art     : b54f3000-b54f4000 ---p 00000000 00:00 0 
08-11 10:49:00.032  6398  6398 W art     : b54f4000-b54f5000 r--p 00004000 b3:17 2510       /system/lib/libpowermanager.so
08-11 10:49:00.032  6398  6398 W art     : b54f5000-b54f6000 rw-p 00005000 b3:17 2510       /syste
08-11 10:49:00.032  6398  6398 W art     : m/lib/libpowermanager.so
08-11 10:49:00.032  6398  6398 W art     : b54f7000-b5514000 r-xp 00000000 b3:17 2729       /system/lib/libvorbisidec.so
08-11 10:49:00.032  6398  6398 W art     : b5514000-b5515000 r--p 0001c000 b3:17 2729       /system/lib/libvorbisidec.so
08-11 10:49:00.032  6398  6398 W art     : b5515000-b5516000 rw-p 0001d000 b3:17 2729       /system/lib/libvorbisidec.so
08-11 10:49:00.032  6398  6398 W art     : b5517000-b551c000 r-xp 00000000 b3:17 2678       /system/lib/libstagefright_yuv.so
08-11 10:49:00.032  6398  6398 W art     : b551c000-b551d000 r--p 00004000 b3:17 2678       /system/lib/libstagefright_yuv.so
08-11 10:49:00.032  6398  6398 W art     : b551d000-b551e000 rw-p 00005000 b3:17 2678       /system/lib/libstagefright_yuv.so
08-11 10:49:00.032  6398  6398 W art     : b551f000-b5550000 r-xp 00000000 b3:17 2189       /system/lib/libstagefright_omx.so
08-11 10:49:00.032  6398  6398 W art     : b5550000-b5553000 r--p 00030000 b3:17 2189       /system/lib/libstagefright_omx.so
08-11 10:49:00.032  6398  6398 W art     : b5553000-b5554000 rw-p 00033000 b3:17 2189       /system/lib/libstagefright_omx.so
08-11 10:49:00.032  6398  6398 W art     : b5555000-b5590000 r-xp 00000000 b3:17 893        /system/lib/libopus.so
08-11 10:49:00.032  6398  6398 W art     : b5590000-b5591000 r--p 0003a000 b3:17 893        /system/lib/libopus.so
08-11 10:49:00.032  6398  6398 W art     : b5591000-b5592000 rw-p 0003b000 b3:17 893        /system/lib/libopus.so
08-11 10:49:00.032  6398  6398 W art     : b5593000-b559a000 r-xp 00000000 b3:17 2928       /system/lib/libmediautils.so
08-11 10:49:00.032  6398  6398 W art     : b559a000-b559b000 ---p 00000000 00:00 0 
08-11 10:49:00.032  6398  6398 W art     : b559b000-b559c000 r--p 00007000 b3:17 2928       /system/lib/libmediautils.so
08-11 10:49:00.032  6398  6398 W art     : b559c000-b559d000 rw-p 00008000 b3:17 2928       /system/lib/libmediautils.so
08-11 10:49:00.032  6398  6398 W art     : b559d000-b559e000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-11 10:49:00.032  6398  6398 W art     : b559e000-b55b5000 r-xp 00000000 b3:17 808        /system/lib/libdrmframework.so
08-11 10:49:00.032  6398  6398 W art     : b55b5000-b55b6000 ---p 00000000 00:00 0 
08-11 10:49:00.032  6398  6398 W art     : b55b6000-b55b9000 r--p 00017000 b3:17 808        /system/lib/libdrmframework.so
08-11 10:49:00.032  6398  6398 W art     : b55b9000-b55ba000 rw-p 0001a000 b3:17 808        /system/lib/libdrmframework.so
08-11 10:49:00.032  6398  6398 W art     : b55ba000-b55d9000 r-xp 00000000 b3:17 1044       /system/lib/libRScpp.so
08-11 10:49:00.032  6398  6398 W art     : b55d9000-b55da000 r--p 0001e000 b3:17 1044       /system/lib/libRScpp.so
08-11 10:49:00.032  6398  6398 W art     : b55da000-b55db000 rw-p 0001f000 b3:17 1044       /system/lib/libRScpp.so
08-11 10:49:00.032  6398  6398 W art     : b55db000-b5619000 r-xp 00000000 b3:17 2566       /system/lib/libRS.so
08-11 10:49:00.032  6398  6398 W art     : b5619000-b561a000 ---p 00000000 00:00 0 
08-11 10:49:00.032  6398  6398 W art     : b561a000-b561c000 r--p 0003e000 b3:17 2566       /system/lib/libRS.so
08-11 10:49:00.032  6398  6398 W art     : b561c000-b561d000 rw-p 00040000 b3:17 2566       /system/lib/libRS.so
08-11 10:49:00.032  6398  6398 W art     : b561e000-b5625000 r-xp 00000000 b3:17 2637       /system/lib/libspeexresampler.so
08-11 10:49:00.032  6398  6398 W art     : b5625000-b5626000 r--p 00006000 b3:17 2637       /system/lib/libspeexresampler.so
08-11 10:49:00.032  6398  6398 W art     : b5626000-b5627000 rw-p 00007000 b3:17 2637       /system/lib/libspeexresampler.so
08-11 10:49:00.032  6398  6398 W art     : b5628000-b562b000 r-xp 00000000 b3:17 1406       /system/lib/libsamsungvad.so
08-11 10:49:00.032  6398  6398 W art     : b562b000-b562c000 r--p 00002000 b3:17 1406       /system/lib/libsamsungvad.so
08-11 10:49:00.032  6398  6398 W art     : b562c000-b562d000 rw-p 00003000 b3:17 1406       /system/lib/libsamsungvad.so
08-11 10:49:00.032  6398  6398 W art     : b562d000-b5633000 r-xp 00000000 b3:17 2449       /system/lib/libedmnativehelper.so
08-11 10:49:00.032  6398  6398 W art     : b5633000-b5634000 ---p 00000000 00:00 0 
08-11 10:49:00.032  6398  6398 W art     : b5634000-b5635000 r--p 00006000 b3:17 2449       /system/lib/libedmnativehelper.so
08-11 10:49:00.032  6398  6398 W art     : b5635000-b5636000 rw-p 00007000 b3:17 2449       /system/lib/libedmnativehelper.so
08-11 10:49:00.032  6398  6398 W art     : b5636000-b563f000 r-xp 00000000 b3:17 2351       /system/lib/libnbaio.so
08-11 10:49:00.032  6398  6398 W art     : b563f000-b5640000 r--p 00008000 b3:17 2351       /system/lib/libnbaio.so
08-11 10:49:00.032  6398  6398 W art     : b5640000-b5641000 rw-p 00009000 b3:17 2351       /system/lib/libnbaio.so
08-11 10:49:00.032  6398  6398 W art     : b5641000-b56d2000 r-xp 00000000 b3:17 128        /system/lib/libcrypto-rename.so
08-11 10:49:00.032  6398  6398 W art     : b56d2000-b56d3000 ---p 00000000 00:00 0 
08-11 10:49:00.032  6398  6398 W art     : b56d3000-b56de000 r--p 00091000 b3:17 128        /system/lib/libcrypto-rename.so
08-11 10:49:00.032  6398  6398 W art     : b56de000-b56df000 rw-p 0009c000 b3:17 128        /system/lib/libcrypto-rename.so
08-11 10:49:00.032  6398  6398 W art     : b56e0000-b56f2000 r-xp 00000000 b3:17 2929       /system/lib/libpcre.so
08-11 10:49:00.032  6398  6398 W art     : b56f2000-b56f3000 r--p 00011000 b3:17 2929       /system/lib/libpcre.so
08-11 10:49:00.032  6398  6398 W art     : b56f3000-b56f4000 rw-p 00012000 b3:17 2929       /system/lib/libpcre.so
08-11 10:49:00.032  6398  6398 W art     : b56f5000-b56fa000 r-xp 00000000 b3:17 2465       /system/lib/libwpa_client.so
08-11 10:49:00.032  6398  6398 W art     : b56fa000-b56fb000 r--p 00004000 b3:17 2465       /system/lib/libwpa_client.so
08-11 10:49:00.032  6398  6398 W art     : b56fb000-b56fc000 rw-p 00005000 b3:17 2465       /system/lib/libwpa_client.so
08-11 10:49:00.032  6398  6398 W art     : b56fd000-b576a000 r-xp 00000000 b3:17 873        /system/lib/libGLES_trace.so
08-11 10:49:00.032  6398  6398 W art     : b576a000-b576b000 ---p 00000000 00:00 0 
08-11 10:49:00.032  6398  6398 W art     : b576b000-b576d000 r--p 0006d000 b3:17 873        /system/lib/libGLES_trace.so
08-11 10:49:00.032  6398  6398 W art     : b576d000-b576e000 rw-p 0006f000 b3:17 873        /system/lib/libGLES_trace.so
08-11 10:49:00.032  6398  6398 W art     : b576e000-b576f000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-11 10:49:00.032  6398  6398 W art     : b576f000-b5776000 r-xp 00000000 b3:17 2579       /system/lib/libsdp_crypto.so
08-11 10:49:00.032  6398  6398 W art     : b5776000-b5777000 r--p 00006000 b3:17 2579       /system/lib/libsdp_crypto.so
08-11 10:49:00.032  6398  6398 W art     : b5777000-b5778000 rw-p 00007000 b3:17 2579       /system/lib/libsdp_crypto.so
08-11 10:49:00.032  6398  6398 W art     : b5779000-b57f9000 r-xp 00000000 b3:17 2884       /system/lib/libAstcEnc.so
08-11 10:49:00.032  6398  6398 W art     : b57f9000-b57fa000 ---p 00000000 00:00 0 
08-11 10:49:00.032  6398  6398 W art     : b57fa000-b57fb000 r--p 00080000 b3:17 2884       /system/lib/libAstcEnc.so
08-11 10:49:00.032  6398  6398 W art     : b57fb000-b57fc000 rw-p 00081000 b3:17 2884       /system/lib/libAstcEnc.so
08-11 10:49:00.032  6398  6398 W art     : b57fc000-b5813000 rw-p 00000000 00:00 0 
08-11 10:49:00.032  6398  6398 W art     : b5813000-b584a000 r-xp 00000000 b3:17 3244       /system/vendor/l
08-11 10:49:00.032  6398  6398 W art     : ib/libqc-opt.so
08-11 10:49:00.032  6398  6398 W art     : b584a000-b584b000 r--p 00036000 b3:17 3244       /system/vendor/lib/libqc-opt.so
08-11 10:49:00.032  6398  6398 W art     : b584b000-b584c000 rw-p 00037000 b3:17 3244       /system/vendor/lib/libqc-opt.so
08-11 10:49:00.032  6398  6398 W art     : b584c000-b5868000 r-xp 00000000 b3:17 387        /system/lib/libquramimagecodec.so
08-11 10:49:00.032  6398  6398 W art     : b5868000-b5869000 r--p 0001b000 b3:17 387        /system/lib/libquramimagecodec.so
08-11 10:49:00.032  6398  6398 W art     : b5869000-b586a000 rw-p 0001c000 b3:17 387        /system/lib/libquramimagecodec.so
08-11 10:49:00.032  6398  6398 W art     : b586b000-b58cc000 r-xp 00000000 b3:17 2708       /system/lib/libft2.so
08-11 10:49:00.032  6398  6398 W art     : b58cc000-b58ce000 r--p 00060000 b3:17 2708       /system/lib/libft2.so
08-11 10:49:00.032  6398  6398 W art     : b58ce000-b58cf000 rw-p 00062000 b3:17 2708       /system/lib/libft2.so
08-11 10:49:00.032  6398  6398 W art     : b58d0000-b58f7000 r-xp 00000000 b3:17 2633       /system/lib/libpng.so
08-11 10:49:00.032  6398  6398 W art     : b58f7000-b58f8000 ---p 00000000 00:00 0 
08-11 10:49:00.032  6398  6398 W art     : b58f8000-b58f9000 r--p 00027000 b3:17 2633       /system/lib/libpng.so
08-11 10:49:00.032  6398  6398 W art     : b58f9000-b58fa000 rw-p 00028000 b3:17 2633       /system/lib/libpng.so
08-11 10:49:00.032  6398  6398 W art     : b58fb000-b5903000 r-xp 00000000 b3:17 2201       /system/lib/libremotedesktop_client.so
08-11 10:49:00.032  6398  6398 W art     : b5903000-b5905000 r--p 00007000 b3:17 2201       /system/lib/libremotedesktop_client.so
08-11 10:49:00.032  6398  6398 W art     : b5905000-b5906000 rw-p 00009000 b3:17 2201       /system/lib/libremotedesktop_client.so
08-11 10:49:00.032  6398  6398 W art     : b5907000-b590a000 r-xp 00000000 b3:17 2500       /system/lib/libsync.so
08-11 10:49:00.032  6398  6398 W art     : b590a000-b590b000 r--p 00002000 b3:17 2500       /system/lib/libsync.so
08-11 10:49:00.032  6398  6398 W art     : b590b000-b590c000 rw-p 00003000 b3:17 2500       /system/lib/libsync.so
08-11 10:49:00.032  6398  6398 W art     : b590c000-b5910000 r-xp 00000000 b3:17 2632       /system/lib/libstdc++.so
08-11 10:49:00.032  6398  6398 W art     : b5910000-b5911000 ---p 00000000 00:00 0 
08-11 10:49:00.032  6398  6398 W art     : b5911000-b5912000 r--p 00004000 b3:17 2632       /system/lib/libstdc++.so
08-11 10:49:00.032  6398  6398 W art     : b5912000-b5913000 rw-p 00005000 b3:17 2632       /system/lib/libstdc++.so
08-11 10:49:00.032  6398  6398 W art     : b5913000-b5923000 r-xp 00000000 b3:17 433        /system/lib/libunwind.so
08-11 10:49:00.032  6398  6398 W art     : b5923000-b5924000 r--p 0000f000 b3:17 433        /system/lib/libunwind.so
08-11 10:49:00.032  6398  6398 W art     : b5924000-b5925000 rw-p 00010000 b3:17 433        /system/lib/libunwind.so
08-11 10:49:00.032  6398  6398 W art     : b5925000-b596b000 rw-p 00000000 00:00 0 
08-11 10:49:00.032  6398  6398 W art     : b596b000-b5974000 r-xp 00000000 b3:17 2901       /system/lib/libbase.so
08-11 10:49:00.032  6398  6398 W art     : b5974000-b5975000 r--p 00008000 b3:17 2901       /system/lib/libbase.so
08-11 10:49:00.032  6398  6398 W art     : b5975000-b5976000 rw-p 00009000 b3:17 2901       /system/lib/libbase.so
08-11 10:49:00.032  6398  6398 W art     : b5977000-b597c000 r-xp 00000000 b3:17 2653       /system/lib/libeffects.so
08-11 10:49:00.032  6398  6398 W art     : b597c000-b597d000 r--p 00004000 b3:17 2653       /system/lib/libeffects.so
08-11 10:49:00.032  6398  6398 W art     : b597d000-b597e000 rw-p 00005000 b3:17 2653       /system/lib/libeffects.so
08-11 10:49:00.032  6398  6398 W art     : b597e000-b5981000 r-xp 00000000 b3:17 240        /system/lib/libstagefright_http_support.so
08-11 10:49:00.032  6398  6398 W art     : b5981000-b5982000 ---p 00000000 00:00 0 
08-11 10:49:00.032  6398  6398 W art     : b5982000-b5983000 r--p 00003000 b3:17 240        /system/lib/libstagefright_http_support.so
08-11 10:49:00.032  6398  6398 W art     : b5983000-b5984000 rw-p 00004000 b3:17 240        /system/lib/libstagefright_http_support.so
08-11 10:49:00.032  6398  6398 W art     : b5985000-b599d000 r-xp 00000000 b3:17 2406       /system/lib/libstagefright_foundation.so
08-11 10:49:00.032  6398  6398 W art     : b599d000-b599e000 ---p 00000000 00:00 0 
08-11 10:49:00.032  6398  6398 W art     : b599e000-b599f000 r--p 00018000 b3:17 2406       /system/lib/libstagefright_foundation.so
08-11 10:49:00.032  6398  6398 W art     : b599f000-b59a0000 rw-p 00019000 b3:17 2406       /system/lib/libstagefright_foundation.so
08-11 10:49:00.032  6398  6398 W art     : b59a1000-b5b3b000 r-xp 00000000 b3:17 2789       /system/lib/libstagefright.so
08-11 10:49:00.032  6398  6398 W art     : b5b3b000-b5b3c000 ---p 00000000 00:00 0 
08-11 10:49:00.032  6398  6398 W art     : b5b3c000-b5b49000 r--p 0019a000 b3:17 2789       /system/lib/libstagefright.so
08-11 10:49:00.032  6398  6398 W art     : b5b49000-b5b4a000 rw-p 001a7000 b3:17 2789       /system/lib/libstagefright.so
08-11 10:49:00.032  6398  6398 W art     : b5b4a000-b5b4e000 r-xp 00000000 b3:17 2676       /system/lib/libpersona.so
08-11 10:49:00.032  6398  6398 W art     : b5b4e000-b5b4f000 ---p 00000000 00:00 0 
08-11 10:49:00.032  6398  6398 W art     : b5b4f000-b5b50000 r--p 00004000 b3:17 2676       /system/lib/libpersona.so
08-11 10:49:00.032  6398  6398 W art     : b5b50000-b5b51000 rw-p 00005000 b3:17 2676       /system/lib/libpersona.so
08-11 10:49:00.032  6398  6398 W art     : b5b51000-b5b64000 r-xp 00000000 b3:17 2918       /system/lib/libimagefilter.so
08-11 10:49:00.032  6398  6398 W art     : b5b64000-b5b65000 r--p 00012000 b3:17 2918       /system/lib/libimagefilter.so
08-11 10:49:00.032  6398  6398 W art     : b5b65000-b5b66000 rw-p 00013000 b3:17 2918       /system/lib/libimagefilter.so
08-11 10:49:00.032  6398  6398 W art     : b5b66000-b5b67000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
08-11 10:49:00.032  6398  6398 W art     : b5b67000-b5bb2000 r-xp 00000000 b3:17 422        /system/lib/libsecure_storage.so
08-11 10:49:00.032  6398  6398 W art     : b5bb2000-b5bb3000 r--p 0004a000 b3:17 422        /system/lib/libsecure_storage.so
08-11 10:49:00.032  6398  6398 W art     : b5bb3000-b5bb4000 rw-p 0004b000 b3:17 422        /system/lib/libsecure_storage.so
08-11 10:49:00.032  6398  6398 W art     : b5bb4000-b5bb6000 rw-p 00000000 00:00 0 
08-11 10:49:00.032  6398  6398 W art     : b5bb7000-b5bc8000 r-xp 00000000 b3:17 2242       /system/lib/libsamsungeffect.so
08-11 10:49:00.032  6398  6398 W art     : b5bc8000-b5bc9000 ---p 00000000 00:00 0 
08-11 10:49:00.032  6398  6398 W art     : b5bc9000-b5bca000 r--p 00011000 b3:17 2242       /system/lib/libsamsungeffect.so
08-11 10:49:00.032  6398  6398 W art     : b5bca000-b5bcb000 rw-p 00012000 b3:17 2242       /system/lib/libsamsungeffect.so
08-11 10:49:00.032  6398  6398 W art     : b5bcc000-b5bd6000 r-xp 00000000 b3:17 2375       /system/lib/libsensorhub.so
08-11 10:49:00.032  6398  6398 W art     : b5bd6000-b5bd8000 r--p 00009000 b3:17 2375       /system/lib/libsensorhub.so
08-11 10:49:00.032  6398  6398 W art     : b5bd8000-b5bd9000 rw-p 0000b000 b3:17 2375       /system/lib/libsensorhub.so
08-11 10:49:00.032  6398  6398 W art     : b5bd9000-b5bf2000 r-xp 00000000 b3:17 2927       /system/lib/libmctraster.so
08-11 10:49:00.032  6398  6398 W art     : b5bf2000-b5bf3000 r--p 00018000 b3:17 2927       /system/lib/libmctraster.so
08-11 10:49:00.032  6398  6398 W art     : b5bf3000-b5bf6000 rw-p 00019000 b3:17 2927       /system/lib/libmctraster.so
08-11 10:49:00.032  6398  6398 W art     : b5bf6000-b5bfa000 rw-p 00000000 00:00 0 
08-11 10:49:00.032  6398  6398 W art     : b5bfa000-b5c6e000 r-xp 00000000 b3:17 2776       /system/lib/libhwui.so
08-11 10:49:00.032  6398  6398 W art     : b5c6e000-b5c6f000 ---p 00000000 00:00 0 
08-11 10:49:00.032  6398  6398 W art     : b5c6f000-b5c72000 r--p 00074000 b3:17 2776       /system/lib/libhwui.so
08-11 10:49:00.032  6398  6398 W art     : b5c72000-b5c73000 rw-p 00077000 b3:17 2776       /system/lib/libhwui.so
08-11 10:49:00.032  6398  6398 W art     : b5c73000-b5c74000 r--p 00000000 00:00 0 
08-11 10:49:00.032  6398  6398 W art     : b5c74000-b5c77000 r-xp 00000000 b3:17 2491       /system/lib/libcc_manager.so
08-11 10:49:00.032  6398  6398 W art     : b5c77000-b5c78000 r--p 00002000 b3:17 2491       /system/lib/libcc_manager.so
08-11 10:49:00.032  6398  6398 W art     : b5c78000-b5c79000 rw-p 00003000 b3:17 2491       /system/lib/libcc_manager.so
08-11 10:49:00.032  6398  6398 W art     : b5c79000-b5c7a000 r--p 00000000 00:00 0 
08-11 10:49:00.032  6398  6398 W art     : b5c7a000-b5c7f000 r-xp 00000000 b3:17 2461       /system/lib/libsecnativefeature.so
08-11 10:49:00.032  6398  6398 W art     : b5c7f000-b5c80000 r--p 00004000 b3:17 2461       /system/lib/libsecnativefeature.so
08-11 10:49:00.032  6398  6398 W art     : b5c80000-b5c81000 rw-p 00005000 b3:17 2461       /system/lib/libsecnativefeature.so
08-11 10:49:00.032  6398  6398 W art     : b5c81000-b5c82000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-11 10:49:00.032  6398  6398 W art     : b5c82000-b5c85000 r-xp 00000000 b3:17 2937       /system/lib/libradio_metadata.so
08-11 10:49:00.032  6398  6398 W art     : b5c85000-b5c86000 r--p 00002000 b3:17 2937       /system/lib/libradio_metadata.so
08-11 10:49:00.032  6398  6398 W art     : b5c86000-b5c87000 rw-p 00003000 b3:17 2937       /system/lib/libradio_metadata.so
08-11 10:49:00.032  6398  6398 W art     : b5c87000-b5c88000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-11 10:49:00.032  6398  6398 W art     : b5c88000-b5c8c000 r-xp 00000000 b3:17 272        /system/lib/libnativebridge.so
08-11 10:49:00.032  6398  6398 W art     : b5c8c000-b5c8d000 r--p 00003000 b3:17 272        /system/lib/libnativebridge.so
08-11 10:49:00.032  6398  6398 W art     : b5c8d000-b5c8e000 rw-p 00004000 b3:17 272        /system/lib/libnativebridge.so
08-11 10:49:00.032  6398  6398 W art     : b5c8e000-b5c8f000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
08-11 10:49:00.032  6398  6398 W art     : b5c8f000-b5c93000 r-xp 00000000 b3:17 2569       /system/lib/libprocessgroup.so
08-11 10:49:00.032  6398  6398 W art     : b5c93000-b5c94000 r--p 00003000 b3:17 2569       /system/lib/libprocessgroup.so
08-11 10:49:00.032  6398  6398 W art     : b5c94000-b5c95000 rw-p 00004000 b3:17 2569       /system/lib/libprocessgroup.so
08-11 10:49:00.032  6398  6398 W art     : b5c95000-b5c96000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-11 10:49:00.032  6398  6398 W art     : b5c96000-b5ca4000 r-xp 00000000 b3:17 472        /system/lib/libminikin.so
08-11 10:49:00.032  6398  6398 W art     : b5ca4000-b5ca5000 ---p 00000000 00:00 0 
08-11 10:49:00.032  6398  6398 W art     : b5ca5000-b5ca6000 r--p 0000e000 b3:17 472        /system/lib/libminikin.so
08-11 10:49:00.032  6398  6398 W art     : b5ca6000-b5ca7000 rw-p 0000f000 b3:17 472        /system/lib/libminikin.so
08-11 10:49:00.032  6398  6398 W art     : b5ca7000-b5cb1000 r-xp 00000000 b3:17 2202       /system/lib/libsoundtrigger.so
08-11 10:49:00.032  6398  6398 W art     : b5cb1000-b5cb4000 r--p 00009000 b3:17 2202       /system/lib/libsoundtrigger.so
08-11 10:49:00.032  6398  6398 W art     : b5cb4000-b5cb5000 rw-p 0000c000 b3:17 2202       /system/lib/libsoundtrigger.so
08-11 10:49:00.032  6398  6398 W art     : b5cb5000-b5cb6000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-11 10:49:00.032  6398  6398 W art     : b5cb6000-b5cc0000 r-xp 00000000 b3:17 2936       /system/lib/libradio.so
08-11 10:49:00.032  6398  6398 W art     : b5cc0000-b5cc3000 r--p 00009000 b3:17 2936       /system/lib/libradio.so
08-11 10:49:00.032  6398  6398 W art     : b5cc3000-b5cc4000 rw-p 0000c000 b3:17 2936       /system/lib/libradio.so
08-11 10:49:00.032  6398  6398 W art     : b5cc4000-b5cc8000 r-xp 00000000 b3:17 2417       /system/lib/libnetd_client.so
08-11 10:49:00.032  6398  6398 W art     : b5cc8000-b5cc9000 r--p 00003000 b3:17 2417       /system/lib/libnetd_client.so
08-11 10:49:00.032  6398  6398 W art     : b5cc9000-b5cca000 rw-p 00004000 b3:17 2417       /system/lib/libnetd_client.so
08-11 10:49:00.032  6398  6398 W art     : b5cca000-b5ccb000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-11 10:49:00.032  6398  6398 W art     : b5ccb000-b5cd8000 r-xp 00000000 b3:17 2372       /system/lib/libimg_utils.so
08-11 10:49:00.032  6398  6398 W art     : b5cd8000-b5cda000 r--p 0000c000 b3:17 2372       /system/lib/libimg_utils.so
08-11 10:49:00.032  6398  6398 W art     : b5cda000-b5cdb000 rw-p 0000e000 b3:17 2372       /system/lib/libimg_utils.so
08-11 10:49:00.042  6398  6398 W art     : b5cdb000-b60ed000 r-xp 00000000 b3:17 328        /system/lib/libpdfium.so
08-11 10:49:00.042  6398  6398 W art     : b60ed000-b60ee000 ---p 00000000 00:00 0 
08-11 10:49:00.042  6398  6398 W art     : b60ee000-b60f7000 r--p 00412000 b3:17 328        /system/lib/libpdfium.so
08-11 10:49:00.042  6398  6398 W art     : b60f7000-b60fb000 rw-p 0041b000 b3:17 328        /system/lib/libpdfium.so
08-11 10:49:00.042  6398  6398 W art     : b60fb000-b60fc000 rw-p 00000000 00:00 0 
08-11 10:49:00.042  6398  6398 W art     : b60fc000-b6103000 r-xp 00000000 b3:17 2571       /system/lib/libaudioutils.so
08-11 10:49:00.042  6398  6398 W art     : b6103000-b6104000 r--p 00006000 b3:17 2571       /system/lib/libaudioutils.so
08-11 10:49:00.042  6398  6398 W art     : b6104000-b6105000 rw-p 00007000 b3:17 2571       /system/lib/libaudioutils.so
08-11 10:49:00.042  6398  6398 W art     : b6105000-b6106000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-11 10:49:00.042  6398  6398 W art     : b6106000-b6121000 r-xp 00000000 b3:17 1184       /system/lib/libz.so
08-11 10:49:00.042  6398  6398 W art     : b6121000-b6122000 r--p 0001a000 b3:17 1184       /system/lib/libz.so
08-11 10:49:00.042  6398  6398 W art     : b6122000-b6123000 rw-p 0001b000 b3:17 1184       /system/lib/libz.so
08-11 10:49:00.042  6398  6398 W art     : b6123000-b6124000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-11 10:49:00.042  6398  6398 W art     : b6124000-b6170000 r-xp 00000000 b3:17 994        /system/lib/libharfbuzz_ng.so
08-11 10:49:00.042  6398  6398 W art     : b6170000-b6171000 ---p 00000000 00:00 0 
08-11 10:49:00.042  6398  6398 W art     : b6171000-b6172000 r--p 0004c000 b3:17 994        /system/lib/libharfbuzz_ng.so
08-11 10:49:00.042  6398  6398 W art     : b6172000-b6173000 rw-p 0004d000 b3:17 994        /system/lib/libharfbuzz_ng.so
08-11 10:49:00.042  6398  6398 W art     : b6173000-b6174000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-11 10:49:00.042  6398  6398 W art     : b6174000-b6178000 r-xp 00000000 b3:17 2681       /system/lib/libusbhost.so
08-11 10:49:00.042  6398  6398 W art     : b6178000-b6179000 ---p 00000000 00:00 0 
08-11 10:49:00.042  6398  6398 W art     : b6179000-b617a000 r--p 00004000 b3:17 2681       /system/lib/libusbhost.so
08-11 10:49:00.042  6398  6398 W art     : b617a000-b617b000 rw-p 00005000 b3:17 2681       /system/lib/libusbhost.so
08-11 10:49:00.042  6398  6398 W art     : b617b000-b61b3000 r-xp 00000000 b3:17 2746       /system/lib/libjpeg.so
08-11 10:49:00.042  6398  6398 W art     : b61b3000-b61b4000 r--p 00037000 b3:17 2746       /system/lib/libjpeg.so
08-11 10:49:00.042  6398  6398 W art     : b61b4000-b61b5000 rw-p 00038000 b3:17 2746       /system/lib/libjpeg.so
08-11 10:49:00.042  6398  6398 W art     : b61b5000-b61b6000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-11 10:49:00.042  6398  6398 W art     : b61b6000-b6254000 r-xp 00000000 b3:17 496        /system/lib/libmedia.so
08-11 10:49:00.042  6398  6398 W art     : b6254000-b6255000 ---p 00000000 00:00 0 
08-11 10:49:00.042  6398  6398 W art     : b6255000-b6273000 r--p 0009e000 b3:17 496        /system/lib/libmedia.so
08-11 10:49:00.042  6398  6398 W art     : b6273000-b6274000 rw-p 000bc000 b3:17 496        /system/lib/libmedia.so
08-11 10:49:00.042  6398  6398 W art     : b6274000-b63e7000 r-xp 00000000 b3:17 1085       /system/lib/libicui18n.so
08-11 10:49:00.042  6398  6398 W art     : b63e7000-b63f2000 r--p 00172000 b3:17 1085       /system/lib/libicui18n.so
08-11 10:49:00.042  6398  6398 W art     : b63f2000-b63f3000 rw-p 0017d000 b3:17 1085       /system/lib/libicui18n.so
08-11 10:49:00.042  6398  6398 W art     : b63f3000-b650a000 r-xp 00000000 b3:17 2041       /system/lib/libicuuc.so
08-11 10:49:00.042  6398  6398 W art     : b650a000-b6515000 r--p 00116000 b3:17 2041       /system/lib/libicuuc.so
08-11 10:49:00.042  6398  6398 W art     : b6515000-b6516000 rw-p 00121000 b3:17 2041       /system/lib/libicuuc.so
08-11 10:49:00.042  6398  6398 W art     : b6516000-b651a000 rw-p 00000000 00:00 0 
08-11 10:49:00.042  6398  6398 W art     : b651a000-b653e000 r-xp 00000000 b3:17 400        /system/lib/libssl.so
08-11 10:49:00.042  6398  6398 W art     : b653e000-b6540000 r--p 00023000 b3:17 400        /system/lib/libssl.so
08-11 10:49:00.042  6398  6398 W art     : b6540000-b6541000 rw-p 00025000 b3:17 400        /system/lib/libssl.so
08-11 10:49:00.042  6398  6398 W art     : b6541000-b65e7000 r-xp 00000000 b3:17 132        /system/lib/libcrypto.so
08-11 10:49:00.042  6398  6398 W art     : b65e7000-b65f4000 r--p 000a5000 b3:17 132        /system/lib/libcrypto.so
08-11 10:49:00.042  6398  6398 W art     : b65f4000-b65f5000 rw-p 000b2000 b3:17 132        /system/lib/libcrypto.so
08-11 10:49:00.042  6398  6398 W art     : b65f5000-b65f6000 rw-p 00000000 00:00 0 
08-11 10:49:00.042  6398  6398 W art     : b65f6000-b6649000 r-xp 00000000 b3:17 2733       /system/lib/libsonivox.so
08-11 10:49:00.042  6398  6398 W art     : b6649000-b664a000 ---p 00000000 00:00 0 
08-11 10:49:00.042  6398  6398 W art     : b664a000-b664b000 r--p 00053000 b3:17 2733       /system/lib/libsonivox.so
08-11 10:49:00.042  6398  6398 W art     : b664b000-b664c000 rw-p 00054000 b3:17 2733       /system/lib/libsonivox.so
08-11 10:49:00.042  6398  6398 W art     : b664c000-b6651000 rw-p 00000000 00:00 0 
08-11 10:49:00.042  6398  6398 W art     : b6651000-b6663000 r-xp 00000000 b3:17 2634       /system/lib/libselinux.so
08-11 10:49:00.042  6398  6398 W art     : b6663000-b6664000 ---p 00000000 00:00 0 
08-11 10:49:00.042  6398  6398 W art     : b6664000-b6665000 r--p 00012000 b3:17 2634       /system/lib/libselinux.so
08-11 10:49:00.042  6398  6398 W art     : b6665000-b6666000 rw-p 00013000 b3:17 2634       /system/lib/libselinux.so
08-11 10:49:00.042  6398  6398 W art     : b6666000-b666d000 r-xp 00000000 b3:17 2629       /system/lib/libhardware_legacy.so
08-11 10:49:00.042  6398  6398 W art     : b666d000-b666e000 r--p 00007000 b3:17 2629       /system/lib/libhardware_legacy.so
08-11 10:49:00.042  6398  6398 W art     : b666e000-b666f000 rw-p 00008000 b3:17 2629       /system/lib/libhardware_legacy.so
08-11 10:49:00.042  6398  6398 W art     : b666f000-b6670000 rw-p 00000000 00:00 0 
08-11 10:49:00.042  6398  6398 W art     : b6670000-b6673000 r-xp 00000000 b3:17 2418       /system/lib/libhardware.so
08-11 10:49:00.042  6398  6398 W art     : b6673000-b6674000 r--p 00002000 b3:17 2418       /system/lib/libhardware.so
08-11 10:49:00.042  6398  6398 W art     : b6674000-b6675000 rw-p 00003000 b3:17 2418       /system/lib/libhardware.so
08-11 10:49:00.042  6398  6398 W art     : b6675000-b6679000 r-xp 00000000 b3:17 2555       /system/lib/libETC1.so
08-11 10:49:00.042  6398  6398 W art     : b6679000-b667a000 r--p 00003000 b3:17 2555       /system/lib/libETC1.so
08-11 10:49:00.042  6398  6398 W art     : b667a000-b667b000 rw-p 00004000 b3:17 2555       /system/lib/libETC1.so
08-11 10:49:00.042  6398  6398 W art     : b667b000-b6689000 r-xp 00000000 b3:17 2721       /system/lib/libGLESv2.so
08-11 10:49:00.042  6398  6398 W art     : b6689000-b668a000 ---p 00000000 00:00 0 
08-11 10:49:00.042  6398  6398 W art     : b668a000-b668b000 r--p 0000e000 b3:17 2721       /system/lib/libGLESv2.so
08-11 10:49:00.042  6398  6398 W art     : b668b000-b668c000 rw-p 0000f000 b3:17 2721       /system/lib/libGLESv2.so
08-11 10:49:00.042  6398  6398 W art     : b668c000-b6695000 r-xp 00000000 b3:17 2235       /system/lib/libGLESv1_CM.so
08-11 10:49:00.042  6398  6398 W art     : b6695000-b6696000 r--p 00008000 b3:17 2235       /system/lib/libGLESv1_CM.so
08-11 10:49:00.042  6398  6398 W art     : b6696000-b6697000 rw-p 00009000 b3:17 2235       /system/lib/libGLESv1_CM.so
08-11 10:49:00.042  6398  6398 W art     : b6697000-b66fd000 r-xp 00000000 b3:17 82         /system/lib/libEGL.so
08-11 10:49:00.042  6398  6398 W art     : b66fd000-b66fe000 ---p 00000000 00:00 0 
08-11 10:49:00.042  6398  6398 W art     : b66fe000-b6700000 r--p 00066000 b3:17 82         /system/lib/libEGL.so
08-11 10:49:00.042  6398  6398 W art     : b6700000-b6709000 rw-p 00068000 b3:17 82         /system/lib/libEGL.so
08-11 10:49:00.042  6398  6398 W art     : b6709000-b670c000 rw-p 00000000 00:00 0 
08-11 10:49:00.042  6398  6398 W art     : b670c000-b67a3000 r-xp 00000000 b3:17 688        /system/lib/libsqlite.so
08-11 10:49:00.042  6398  6398 W art     : b67a3000-b67a5000 r--p 00096000 b3:17 688        /system/lib/libsqlite.so
08-11 10:49:00.042  6398  6398 W art     : b67a5000-b67a6000 rw-p 00098000 b3:17 688        /system/lib/libsqlite.so
08-11 10:49:00.042  6398  6398 W art     : b67a6000-b67a7000 rw-p 00000000 00:00 0 
08-11 10:49:00.042  6398  6398 W art     : b67a7000-b6ac8000 r-xp 00000000 b3:17 377        /system/lib/libskia.so
08-11 10:49:00.042  6398  6398 W art     : b6ac8000-b6ac9000 ---p 00000000 00:00 0 
08-11 10:49:00.042  6398  6398 W art     : b6ac9000-b6ae4000 r--p 00321000 b3:17 377        /system/lib/libskia.so
08-11 10:49:00.042  6398  6398 W art     : b6ae4000-b6ae8000 rw-p 0033c000 b3:17 377        /system/lib/libskia.so
08-11 10:49:00.042  6398  6398 W art     : b6ae8000-b6aed000 rw-p 00000000 00:00 0 
08-11 10:49:00.042  6398  6398 W art     : b6aed000-b6af5000 r-xp 00000000 b3:17 2591       /system/lib/libcamera_metadata.so
08-11 10:49:00.042  6398  6398 W art     : b6af5000-b6af6000 r--p 00007000 b3:17 2591       /system/lib/libcamera_metadata.so
08-11 10:49:00.042  6398  6398 W art     : b6af6000-b6af7000 rw-p 00008000 b3:17 2591       /system/lib/libcamera_metadata.so
08-11 10:49:00.042  6398  6398 W art     : b6af7000-b6b25000 r-xp 00000000 b3:17 564        /system/lib/libcamera_client.so
08-11 10:49:00.042  6398  6398 W art     : b6b25000-b6b26000 ---p 00000000 00:00 0 
08-11 10:49:00.042  6398  6398 W art     : b6b26000-b6b2d000 r--p 0002e000 b3:17 564        /system/lib/libcamera_client.so
08-11 10:49:00.042  6398  6398 W art     : b6b2d000-b6b2e000 rw-p 00035000 b3:17 564        /system/lib/libcamera_client.so
08-11 10:49:00.042  6398  6398 W art     : b6b2e000-b6b74000 r-xp 00000000 b3:17 1049       /system/lib/libinputflinger.so
08-11 10:49:00.042  6398  6398 W art     : b6b74000-b6b75000 ---p 00000000 00:00 0 
08-11 10:49:00.042  6398  6398 W art     : b6b75000-b6b78000 r--p 00046000 b3:17 1049       /system/lib/libinputflinger.so
08-11 10:49:00.042  6398  6398 W art     : b6b78000-b6b79000 rw-p 00049000 b3:17 1049       /system/lib/libinputflinger.so
08-11 10:49:00.042  6398  6398 W art     : b6b79000-b6b94000 r-xp 00000000 b3:17 2442       /system/lib/libinput.so
08-11 10:49:00.042  6398  6398 W art     : b6b94000-b6b98000 r--p 0001a000 b3:17 2442       /system/lib/libinput.so
08-11 10:49:00.042  6398  6398 W art     : b6b98000-b6b99000 rw-p 0001e000 b3:17 2442       /system/lib/libinput.so
08-11 10:49:00.042  6398  6398 W art     : b6b99000-b6be6000 r-xp 00000000 b3:17 2761       /system/lib/libgui.so
08-11 10:49:00.042  6398  6398 W art     : b6be6000-b6be7000 ---p 00000000 00:00 0 
08-11 10:49:00.042  6398  6398 W art     : b6be7000-b6bf3000 r--p 0004d000 b3:17 2761       /system/lib/libgui.so
08-11 10:49:00.042  6398  6398 W art     : b6bf3000-b6bf4000 rw-p 00059000 b3:17 2761       /system/lib/libgui.so
08-11 10:49:00.042  6398  6398 W art     : b6bf4000-b6c01000 r-xp 00000000 b3:17 2715       /system/lib/libui.so
08-11 10:49:00.042  6398  6398 W art     : b6c01000-b6c02000 ---p 00000000 00:00 0 
08-11 10:49:00.042  6398  6398 W art     : b6c02000-b6c03000 r--p 0000d000 b3:17 2715       /system/lib/libui.so
08-11 10:49:00.042  6398  6398 W art     : b6c03000-b6c04000 rw-p 0000e000 b3:17 2715       /system/lib/libui.so
08-11 10:49:00.042  6398  6398 W art     : b6c04000-b6c0c000 r-xp 00000000 b3:17 1189       /system/lib/libnetutils.so
08-11 10:49:00.042  6398  6398 W art     : b6c0c000-b6c0d000 ---p 00000000 00:00 0 
08-11 10:49:00.042  6398  6398 W art     : b6c0d000-b6c0e000 r--p 00008000 b3:17 1189       /system/lib/libnetutils.so
08-11 10:49:00.042  6398  6398 W art     : b6c0e000-b6c0f000 rw-p 00009000 b3:17 1189       /system/lib/libnetutils.so
08-11 10:49:00.042  6398  6398 W art     : b6c0f000-b6c16000 r-xp 00000000 b3:17 1217       /system/lib/libnativehelper.so
08-11 10:49:00.042  6398  6398 W art     : b6c16000-b6c17000 r--p 00006000 b3:17 1217       /system/lib/libnativehelper.so
08-11 10:49:00.042  6398  6398 W art     : b6c17000-b6c18000 rw-p 00007000 b3:17 1217       /system/lib/libnativehelper.so
08-11 10:49:00.042  6398  6398 W art     : b6c18000-b6c2c000 r-xp 00000000 b3:17 2117       /system/lib/libexpat.so
08-11 10:49:00.072   781  1739 I ActivityManager: Process com.samsung.aasaservice (pid 5542)(adj 0) has died(114,722)
08-11 10:49:00.042  6398  6398 W art     : b6c2c000-b6c2e000 r--p 00013000 b3:17 2117       /system/lib/libexpat.so
08-11 10:49:00.042  6398  6398 W art     : b6c2e000-b6c2f000 rw-p 00015000 b3:17 2117       /system/lib/libexpat.so
08-11 10:49:00.042  6398  6398 W art     : b6c2f000-b6c57000 r-xp 00000000 b3:17 946        /system/lib/libandroidfw.so
08-11 10:49:00.042  6398  6398 W art     : b6c57000-b6c59000 r--p 00027000 b3:17 946        /system/lib/libandroidfw.so
08-11 10:49:00.042  6398  6398 W art     : b6c59000-b6c5a000 rw-p 00029000 b3:17 946        /system/lib/libandroidfw.so
08-11 10:49:00.042  6398  6398 W art     : b6c5a000-b6c5d000 r-xp 00000000 b3:17 2456       /system/lib/libmemtrack.so
08-11 10:49:00.042  6398  6398 W art     : b6c5d000-b6c5e000 r--p 00002000 b3:17 2456       /system/lib/libmemtrack.so
08-11 10:49:00.042  6398  6398 W art     : b6c5e000-b6c5f000 rw-p 00003000 b3:17 2456       /system/lib/libmemtrack.so
08-11 10:49:00.042  6398  6398 W art     : b6c5f000-b6c68000 r-xp 00000000 b3:17 2581       /system/lib/libbacktrace.so
08-11 10:49:00.072   781  1739 D ActivityManager: isAutoRunBlockedApp:: com.samsung.aasaservice, Auto Run ON
08-11 10:49:00.042  6398  6398 W art     : b6c68000-b6c69000 r--p 00008000 b3:17 2581       /system/lib/libbacktrace.so
08-11 10:49:00.072   781  1739 I ActivityManager: isWidgetUsingPkg : com.samsung.aasaservice no widget is using.
08-11 10:49:00.042  6398  6398 W art     : b6c69000-b6c6a000 rw-p 00009000 b3:17 2581       /system/lib/libbacktrace.so
08-11 10:49:00.042  6398  6398 W art     : b6c6a000-b6c8a000 r-xp 00000000 b3:17 2560       /system/lib/libm.so
08-11 10:49:00.072   781  1739 W ActivityManager: Scheduling restart of crashed service com.samsung.aasaservice/.AASAService in 1000ms
08-11 10:49:00.042  6398  6398 W art     : b6c8a000-b6c8b000 r--p 0001f000 b3:17 2560       /system/lib/libm.so
08-11 10:49:00.042  6398  6398 W art     : b6c8b000-b6c8c000 rw-p 00020000 b3:17 2560       /system/lib/libm.so
08-11 10:49:00.042  6398  6398 W art     : b6c8c000-b6cff000 r-xp 00000000 b3:17 860        /system/lib/libc.so
08-11 10:49:00.042  6398  6398 W art     : b6cff000-b6d03000 r--p 00072000 b3:17 860        /system/lib/libc.so
08-11 10:49:00.042  6398  6398 W art     : b6d03000-b6d06000 rw-p 00076000 b3:17 860        /system/lib/libc.so
08-11 10:49:00.042  6398  6398 W art     : b6d06000-b6d10000 rw-p 00000000 00:00 0 
08-11 10:49:00.042  6398  6398 W art     : b6d10000-b6d98000 r-xp 00000000 b3:17 1016       /system/lib/libc++.so
08-11 10:49:00.042  6398  6398 W art     : b6d98000-b6d99000 ---p 00000000 00:00 0 
08-11 10:49:00.042  6398  6398 W art     : b6d99000-b6d9d000 r--p 00088000 b3:17 1016       /system/lib/libc++.so
08-11 10:49:00.042  6398  6398 W art     : b6d9d000-b6d9e000 rw-p 0008c000 b3:17 1016       /system/lib/libc++.so
08-11 10:49:00.042  6398  6398 W art     : b6d9e000-b6d9f000 rw-p 00000000 00:00 0 
08-11 10:49:00.042  6398  6398 W art     : b6d9f000-b6dc8000 r-xp 00000000 b3:17 1253       /system/lib/libwilhelm.so
08-11 10:49:00.042  6398  6398 W art     : b6dc8000-b6dc9000 ---p 00000000 00:00 0 
08-11 10:49:00.042  6398  6398 W art     : b6dc9000-b6dcc000 r--p 00029000 b3:17 1253       /system/lib/libwilhelm.so
08-11 10:49:00.042  6398  6398 W art     : b6dcc000-b6dcd000 rw-p 0002c000 b3:17 1253       /system/lib/libwilhelm.so
08-11 10:49:00.042  6398  6398 W art     : b6dcd000-b6ea7000 r-xp 00000000 b3:17 495        /system/lib/libandroid_runtime.so
08-11 10:49:00.042  6398  6398 W art     : b6ea7000-b6eae000 r--p 000d9000 b3:17 495        /system/lib/libandroid_runtime.so
08-11 10:49:00.042  6398  6398 W art     : b6eae000-b6eb6000 rw-p 000e0000 b3:17 495        /system/lib/libandroid_runtime.so
08-11 10:49:00.042  6398  6398 W art     : b6eb6000-b6eb7000 rw-p 00000000 00:00 0 
08-11 10:49:00.042  6398  6398 W art     : b6eb7000-b6eb8000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
08-11 10:49:00.042  6398  6398 W art     : b6eb8000-b6eb9000 rw-p 00000000 00:00 0          [anon:linker_alloc_64]
08-11 10:49:00.042  6398  6398 W art     : b6eb9000-b6eba000 rw-p 00000000 00:00 0          [anon:linker_alloc]
08-11 10:49:00.042  6398  6398 W art     : b6eba000-b6ebd000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-11 10:49:00.042  6398  6398 W art     : b6ebd000-b6ee2000 r-xp 00000000 b3:17 2179       /system/lib/libbinder.so
08-11 10:49:00.042  6398  6398 W art     : b6ee2000-b6ee3000 ---p 00000000 00:00 0 
08-11 10:49:00.042  6398  6398 W art     : b6ee3000-b6eea000 r--p 00025000 b3:17 2179       /system/lib/libbinder.so
08-11 10:49:00.042  6398  6398 W art     : b6eea000-b6eeb000 rw-p 0002c000 b3:17 2179       /system/lib/libbinder.so
08-11 10:49:00.042  6398  6398 W art     : b6eeb000-b6ef2000 r-xp 00000000 b3:17 2644       /system/lib/liblog.so
08-11 10:49:00.042  6398  6398 W art     : b6ef2000-b6ef3000 r--p 00006000 b3:17 2644       /system/lib/liblog.so
08-11 10:49:00.042  6398  6398 W art     : b6ef3000-b6ef4000 rw-p 00007000 b3:17 2644       /system/lib/liblog.so
08-11 10:49:00.042  6398  6398 W art     : b6ef4000-b6ef5000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-11 10:49:00.042  6398  6398 W art     : b6ef5000-b6f0d000 r-xp 00000000 b3:17 918        /system/lib/libutils.so
08-11 10:49:00.042  6398  6398 W art     : b6f0d000-b6f0e000 ---p 00000000 00:00 0 
08-11 10:49:00.042  6398  6398 W art     : b6f0e000-b6f0f000 r--p 00018000 b3:17 918        /system/lib/libutils.so
08-11 10:49:00.042  6398  6398 W art     : b6f0f000-b6f10000 rw-p 00019000 b3:17 918        /system/lib/libutils.so
08-11 10:49:00.042  6398  6398 W art     : b6f10000-b6f1e000 r-xp 00000000 b3:17 2710       /system/lib/libcutils.so
08-11 10:49:00.042  6398  6398 W art     : b6f1e000-b6f1f000 ---p 00000000 00:00 0 
08-11 10:49:00.042  6398  6398 W art     : b6f1f000-b6f20000 r--p 0000e000 b3:17 2710       /system/lib/libcutils.so
08-11 10:49:00.042  6398  6398 W art     : b6f20000-b6f21000 rw-p 0000f000 b3:17 2710       /system/lib/libcutils.so
08-11 10:49:00.042  6398  6398 W art     : b6f21000-b6f22000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
08-11 10:49:00.042  6398  6398 W art     : b6f22000-b6f24000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-11 10:49:00.042  6398  6398 W art     : b6f24000-b6f25000 rw-p 00000000 00:00 0          [anon:linker_alloc]
08-11 10:49:00.042  6398  6398 W art     : b6f25000-b6f26000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
08-11 10:49:00.042  6398  6398 W art     : b6f26000-b6f27000 rw-p 00000000 00:00 0          [anon:linker_alloc_32]
08-11 10:49:00.042  6398  6398 W art     : b6f27000-b6f28000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-11 10:49:00.042  6398  6398 W art     : b6f28000-b6f48000 r--s 00000000 00:0b 8195       /dev/__properties__
08-11 10:49:00.042  6398  6398 W art     : b6f48000-b6f49000 r--p 00000000 00:00 0 
08-11 10:49:00.042  6398  6398 W art     : b6f49000-b6f4a000 ---p 00000000 00:00 0 
08-11 10:49:00.042  6398  6398 W art     : b6f4a000-b6f4c000 rw-p 00000000 00:00 0          [anon:thread signal stack]
08-11 10:49:00.042  6398  6398 W art     : b6f4c000-b6f4d000 r-xp 00000000 00:00 0          [sigpage]
08-11 10:49:00.042  6398  6398 W art     : b6f4d000-b6f68000 r-xp 00000000 b3:17 2770       /system/bin/linker
08-11 10:49:00.042  6398  6398 W art     : b6f68000-b6f69000 r--p 0001a000 b3:17 2770       /system/bin/linker
08-11 10:49:00.042  6398  6398 W art     : b6f69000-b6f6b000 rw-p 0001b000 b3:17 2770       /system/bin/linker
08-11 10:49:00.042  6398  6398 W art     : b6f6b000-b6f6d000 rw-p 00000000 00:00 0 
08-11 10:49:00.042  6398  6398 W art     : b6f6d000-b6f72000 r-xp 00000000 b3:17 978        /system/bin/app_process32
08-11 10:49:00.042  6398  6398 W art     : b6f72000-b6f73000 r--p 00004000 b3:17 978        /system/bin/app_process32
08-11 10:49:00.042  6398  6398 W art     : b6f73000-b6f74000 rw-p 00000000 00:00 0 
08-11 10:49:00.042  6398  6398 W art     : be971000-be992000 rw-p 00000000 00:00 0          [stack]
08-11 10:49:00.042  6398  6398 W art     : ffff0000-ffff1000 r-xp 00000000 00:00 0          [vectors]
08-11 10:49:00.082  5486  5486 I DBG_POLICYDM: [lIIIIllIIlIIIlIllIII(47/onServiceDisconnected)] AASA: onServiceDisconnected
08-11 10:49:00.092   781   878 I ActivityManager: Start proc 6408:com.google.android.partnersetup/u0a14 for broadcast-3 com.google.android.partnersetup/.RlzPingBroadcastReceiver
08-11 10:49:00.092  6408  6408 E Zygote  : v2
08-11 10:49:00.092  6408  6408 I libpersona: KNOX_SDCARD checking this for 10014
08-11 10:49:00.092  6408  6408 I libpersona: KNOX_SDCARD not a persona
08-11 10:49:00.092   781  1324 D NetworkPolicy: isUidForegroundLocked: 10014, mScreenOn: false, uidstate: -1, mProxSensorScreenOff: false
08-11 10:49:00.092  6408  6408 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-11 10:49:00.092  6408  6408 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
08-11 10:49:00.092  6408  6408 E Zygote  : accessInfo : 0
08-11 10:49:00.092  6408  6408 W SELinux : SELinux: seapp_context_lookup: seinfo=untrusted, level=s0:c512,c768, pkgname=com.google.android.partnersetup 
08-11 10:49:00.102  6398  6398 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
08-11 10:49:00.122  6408  6408 D TimaKeyStoreProvider: TimaSignature is unavailable
08-11 10:49:00.122  6408  6408 D ActivityThread: Added TimaKeyStore provider
08-11 10:49:00.122   781  1758 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{b49c611 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{e68d0ce 6408:com.google.android.partnersetup/u0a14}
08-11 10:49:00.132   781  1324 D NetworkPolicy: isUidForegroundLocked: 10014, mScreenOn: false, uidstate: 11, mProxSensorScreenOff: false
08-11 10:49:00.142  6408  6408 W ResourcesManager: getTopLevelResources: /system/priv-app/GooglePartnerSetup/GooglePartnerSetup.apk / 1.0 running in com.google.android.partnersetup rsrc of package null
08-11 10:49:00.152  6398  6398 I Radio-JNI: register_android_hardware_Radio DONE
08-11 10:49:00.152  6408  6408 W System  : ClassLoader referenced unknown path: /system/priv-app/GooglePartnerSetup/lib/arm
08-11 10:49:00.162  6398  6398 E AffinityControl: AffinityControl: registerfunction enter
08-11 10:49:00.182   781  1739 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{b49c611 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{e68d0ce 6408:com.google.android.partnersetup/u0a14}
08-11 10:49:00.182  6398  6398 D AndroidRuntime: Calling main entry com.android.commands.am.Am
08-11 10:49:00.202  6431  6431 E Zygote  : v2
08-11 10:49:00.202  6431  6431 I libpersona: KNOX_SDCARD checking this for 10015
08-11 10:49:00.202  6431  6431 I libpersona: KNOX_SDCARD not a persona
08-11 10:49:00.202  6431  6431 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-11 10:49:00.202   781  1455 I ActivityManager: Start proc 6431:com.samsung.groupcast/u0a15 for broadcast-3 com.samsung.groupcast/.receiver.SSPReceiver
08-11 10:49:00.202  6431  6431 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
08-11 10:49:00.202  6431  6431 E Zygote  : accessInfo : 0
08-11 10:49:00.202  6431  6431 W SELinux : SELinux: seapp_context_lookup: seinfo=samsung, level=s0:c512,c768, pkgname=com.samsung.groupcast 
08-11 10:49:00.202   781   798 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in null rsrc of package null
08-11 10:49:00.212   781   798 D ActivityManager: mDVFSHelper.acquire()
08-11 10:49:00.222   781   798 V WindowManager: addAppToken: AppWindowToken{2ec480b token=Token{3c52bda ActivityRecord{50d1185 u0 com.test.thalitest/.MainActivity t153}}} to stack=1 task=153 at 0
08-11 10:49:00.222  6431  6431 D TimaKeyStoreProvider: TimaSignature is unavailable
08-11 10:49:00.222  6431  6431 D ActivityThread: Added TimaKeyStore provider
08-11 10:49:00.232  6443  6443 E Zygote  : v2
08-11 10:49:00.232  6443  6443 I libpersona: KNOX_SDCARD checking this for 10004
08-11 10:49:00.232  6443  6443 I libpersona: KNOX_SDCARD not a persona
08-11 10:49:00.232  6443  6443 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-11 10:49:00.232  6443  6443 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
08-11 10:49:00.232  6443  6443 E Zygote  : accessInfo : 0
08-11 10:49:00.232  6443  6443 W SELinux : SELinux: seapp_context_lookup: seinfo=default, level=s0:c512,c768, pkgname=com.test.thalitest 
08-11 10:49:00.232   781   798 I ActivityManager: Start proc 6443:com.test.thalitest/u0a4 for activity com.test.thalitest/.MainActivity
08-11 10:49:00.232   781   923 D SecWifiDisplayUtil: Metadata value : none
08-11 10:49:00.232   781   923 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{6d3ad83 V.E...... R.....ID 0,0-0,0}
08-11 10:49:00.232   781   798 D InputDispatcher: Focused application set to: xxxx
08-11 10:49:00.232   781   798 D InputDispatcher: Focus left window: 4536
08-11 10:49:00.232   781   923 D ISSUE_DEBUG: InputChannelName : 9f50f39 Starting com.test.thalitest
08-11 10:49:00.242   781   880 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=Window{701e8c8 u0 d0 com.sec.android.app.launcher/com.android.launcher2.Launcher}
08-11 10:49:00.242   781  1324 D NetworkPolicy: isUidForegroundLocked: 10004, mScreenOn: false, uidstate: -1, mProxSensorScreenOff: false
08-11 10:49:00.242  1382  1382 D PhoneStatusBar: setSystemUiVisibility vis=40008500 mask=ffffffff oldVal=40008600 newVal=40008500 diff=300
08-11 10:49:00.242  6398  6398 D AndroidRuntime: Shutting down VM
08-11 10:49:00.252   781  1744 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{b49c611 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{711097e 6431:com.samsung.groupcast/u0a15}
08-11 10:49:00.252   781  1452 I ActivityManager: Killing 5522:com.sec.android.app.sns3/u0a35 (adj 15): DHA:empty #37
08-11 10:49:00.252   293   293 I SurfaceFlinger: id=16 createSurf (1x1),1 flag=404, uhalitest
08-11 10:49:00.252   781  1324 D NetworkPolicy: isUidForegroundLocked: 10004, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
08-11 10:49:00.262  6431  6431 W ResourcesManager: getTopLevelResources: /system/priv-app/GroupPlay_27/GroupPlay_27.apk / 1.0 running in com.samsung.groupcast rsrc of package null
08-11 10:49:00.272  6443  6443 D TimaKeyStoreProvider: TimaSignature is unavailable
08-11 10:49:00.272  6443  6443 D ActivityThread: Added TimaKeyStore provider
08-11 10:49:00.272   781   923 D PointerIcon: setMouseIconStyle1 pointerType: 1001 iconType:101 flag:0 pid:781 uid:1000
08-11 10:49:00.272   781  1278 V WindowOrientationListener: setCurrentAppOrientation :-1
08-11 10:49:00.272   781  1278 V WindowManager: rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false mMobileKeyboardEnabled=false displayId=0
08-11 10:49:00.272   781   923 D PointerIcon: setMouseCustomIcon IconType is same.101
08-11 10:49:00.272   781   923 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001 iconType:1 flag:0 pid:781 uid:1000
08-11 10:49:00.272   781   923 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
08-11 10:49:00.272   781   923 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 72 - 0, 0) vi=Rect(0, 72 - 0, 0) or=1
08-11 10:49:00.282   781   880 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=Window{9f50f39 u0 d0 Starting com.test.thalitest}
08-11 10:49:00.292   781   923 W DisplayManagerService: Failed to notify process 5522 that displays changed, assuming it died.
08-11 10:49:00.292   781   923 W DisplayManagerService: android.os.DeadObjectException
08-11 10:49:00.292   781   923 W DisplayManagerService: 	at android.os.BinderProxy.transactNative(Native Method)
08-11 10:49:00.292   781   923 W DisplayManagerService: 	at android.os.BinderProxy.transact(Binder.java:503)
08-11 10:49:00.292   781   923 W DisplayManagerService: 	at android.hardware.display.IDisplayManagerCallback$Stub$Proxy.onDisplayEvent(IDisplayManagerCallback.java:81)
08-11 10:49:00.292   781   923 W DisplayManagerService: 	at com.android.server.display.DisplayManagerService$CallbackRecord.notifyDisplayEventAsync(DisplayManagerService.java:1832)
08-11 10:49:00.292   781   923 W DisplayManagerService: 	at com.android.server.display.DisplayManagerService.deliverDisplayEvent(DisplayManagerService.java:1616)
08-11 10:49:00.292   781   923 W DisplayManagerService: 	at com.android.server.display.DisplayManagerService.access$500(DisplayManagerService.java:187)
08-11 10:49:00.292   781   923 W DisplayManagerService: 	at com.android.server.display.DisplayManagerService$DisplayManagerHandler.handleMessage(DisplayManagerService.java:1760)
08-11 10:49:00.292   781   923 W DisplayManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-11 10:49:00.292   781   923 W DisplayManagerService: 	at android.os.Looper.loop(Looper.java:158)
08-11 10:49:00.292   781   923 W DisplayManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-11 10:49:00.292   781   923 W DisplayManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
08-11 10:49:00.292  1382  1382 D PhoneStatusBar: setSystemUiVisibility vis=8600 mask=ffffffff oldVal=40008500 newVal=8600 diff=40000300
08-11 10:49:00.312   781  1278 D Activit,yManager:  Launching com.test.thalitest, updated priority
08-11 10:49:00.312   293   943 I SurfaceFlinger: id=14 Removed YUIInstallC (6/10)
08-11 10:49:00.312   293  2430 I SurfaceFlinger: id=14 Removed YUIInstallC (-2/10)
08-11 10:49:00.312  6431  6431 W System  : ClassLoader referenced unknown path: /system/priv-app/GroupPlay_27/lib/arm
08-11 10:49:00.312  4536  4536 V ActivityThread: updateVisibility : ActivityRecord{4f7453a token=android.os.BinderProxy@189d100 {com.wssyncmldm/com.samsung.android.app.syncmldm.ui.XUIInstallConfirmActivity}} show : false
08-11 10:49:00.322   781   923 V WindowStateAnimator: Finishing drawing window Window{9f50f39 u0 d0 Starting com.test.thalitest}: mDrawState=DRAW_PENDING
08-11 10:49:00.332   293   293 D libEGL  : eglInitialize EGLDisplay = 0xbef49364
08-11 10:49:00.342  1746  1917 E libGLESv1: HWUI Protection: wrong call from hwui context F:ES1-glDeleteTexturesSEC
08-11 10:49:00.342  1746  1746 D SurfaceWidgetConnection: .SurfaceWidgetWeather#1's surface texture was stored
08-11 10:49:00.342  6431  6431 D GroupCast_FileTools: [getDirectoryForImageResized : 295] cleaning!!
08-11 10:49:00.342  6431  6431 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.sec.android.app.ma.recorder
08-11 10:49:00.342  6431  6431 W System.err: 	at android.app.ApplicationPackageManager.getApplicationInfo(ApplicationPackageManager.java:366)
08-11 10:49:00.342  6431  6431 W System.err: 	at com.samsung.groupcast.application.App.preLoadGroupCamcoderCheck(App.java:354)
08-11 10:49:00.342  6431  6431 W System.err: 	at com.samsung.groupcast.application.App.onCreate(App.java:161)
08-11 10:49:00.342  6431  6431 W System.err: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1036)
08-11 10:49:00.342  6431  6431 W System.err: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:6316)
08-11 10:49:00.342  6431  6431 W System.err: 	at android.app.ActivityThread.access$1800(ActivityThread.java:221)
08-11 10:49:00.342  6431  6431 W System.err: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1860)
08-11 10:49:00.342  6431  6431 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-11 10:49:00.342  6431  6431 W System.err: 	at android.os.Looper.loop(Looper.java:158)
08-11 10:49:00.342  6431  6431 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:7224)
08-11 10:49:00.342  6431  6431 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-11 10:49:00.342  6431  6431 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1230)
08-11 10:49:00.342  6431  6431 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1120)
08-11 10:49:00.352   293   366 D libEGL  : eglTerminate EGLDisplay = 0xb690164c
08-11 10:49:00.352   293   366 D libEGL  : eglTerminate EGLDisplay = 0xb690164c
08-11 10:49:00.352   293   943 I SurfaceFlinger: id=7 Removed Mauncher (4/9)
08-11 10:49:00.352   293  2430 I SurfaceFlinger: id=7 Removed Mauncher (-2/9)
08-11 10:49:00.362  2211  6286 D SurfaceWidgetClient$ISurfaceWidgetStub: [237392/23] Surface widget visibility changed visibility = false on instance = 1
08-11 10:49:00.362  1746  1746 V ActivityThread: updateVisibility : ActivityRecord{5568693 token=android.os.BinderProxy@c308343 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
08-11 10:49:00.362  1746  1746 D Launcher: onTrimMemory. Level: 20
08-11 10:49:00.372   293   293 D libEGL  : eglTerminate EGLDisplay = 0xbef493a4
,08-11 10:49:00.632   781  1278 I WindowManager: Screenshot max retries 4 of Token{3c52bda ActivityRecord{50d1185 u0 com.test.thalitest/.MainActivity t153}} appWin=Window{9f50f39 u0 d0 Starting com.test.thalitest} drawState=4
,08-11 10:49:00.632   781   878 V MARsPolicyManager: updatePackagesScore PackageInfo name -- com.test.thalitest
,08-11 10:49:00.632   781  1743 D ActivityManager: isAutoRunBlockedApp:: com.sec.android.app.sns3, Auto Run ON
,08-11 10:49:00.652   781  1452 I ActivityManager: Killing 5575:com.sec.android.widgetapp.SPlannerAppWidget/u0a148 (adj 15): DHA:empty #37
,08-11 10:49:00.662  6443  6443 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.test.thalitest rsrc of package null
,08-11 10:49:00.662   781  1452 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{b49c611 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{f5f49f6 1936:com.sec.android.app.shealth:remote/u0a34}
,08-11 10:49:00.692   781  1455 I ActivityManager: Start proc 6462:com.samsung.android.sdk.samsunglink/u0a41 for broadcast-3 com.samsung.android.sdk.samsunglink/com.sec.pcw.service.push.spp.SPPReceiver
,08-11 10:49:00.702  6462  6462 E Zygote  : v2
08-11 10:49:00.702  6462  6462 I libpersona: KNOX_SDCARD checking this for 10041
08-11 10:49:00.702  6462  6462 I libpersona: KNOX_SDCARD not a persona
,08-11 10:49:00.702  6462  6462 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-11 10:49:00.702  6462  6462 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,08-11 10:49:00.702  6462  6462 E Zygote  : accessInfo : 0
,08-11 10:49:00.702  6462  6462 W SELinux : SELinux: seapp_context_lookup: seinfo=samsung, level=s0:c512,c768, pkgname=com.samsung.android.sdk.samsunglink 
,08-11 10:49:00.702   781  3500 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,08-11 10:49:00.732  6443  6443 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.test.thalitest rsrc of package null
,08-11 10:49:00.732  6443  6443 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.test.thalitest rsrc of package null
,08-11 10:49:00.752  6443  6443 I WebViewFactory: Loading com.google.android.webview version 48.0.2564.106 (code 256410600)
,08-11 10:49:00.772   781  1744 D ActivityManager: isAutoRunBlockedApp:: com.sec.android.widgetapp.SPlannerAppWidget, Auto Run ON
,08-11 10:49:00.782  6443  6443 W ResourcesManager: getTopLevelResources: /system/app/WebViewGoogle/WebViewGoogle.apk / 1.0 running in com.test.thalitest rsrc of package null
,08-11 10:49:00.782  6462  6462 D TimaKeyStoreProvider: TimaSignature is unavailable
08-11 10:49:00.782  6462  6462 D ActivityThread: Added TimaKeyStore provider
,08-11 10:49:00.782   781   798 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{b49c611 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{8999edf 6462:com.samsung.android.sdk.samsunglink/u0a41}
,08-11 10:49:00.792  6443  6443 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,08-11 10:49:00.802  6443  6443 I cr_LibraryLoader: Time to load native libraries: 4 ms (timestamps 7236-7240)
,08-11 10:49:00.802  6443  6443 I cr_LibraryLoader: Expected native library version number "48.0.2564.106", actual native library version number "48.0.2564.106"
,08-11 10:49:00.802  6462  6462 W ResourcesManager: getTopLevelResources: /system/priv-app/SamsungLinkPlatform/SamsungLinkPlatform.apk / 1.0 running in com.samsung.android.sdk.samsunglink rsrc of package null
,08-11 10:49:00.812  6443  6443 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {16e7702}
08-11 10:49:00.812  6443  6443 I cr_LibraryLoader: Expected native library version number "48.0.2564.106", actual native library version number "48.0.2564.106"
,08-11 10:49:00.812  6443  6443 I chromium: [INFO:library_loader_hooks.cc(130)] Chromium logging enabled: level = 0, default verbosity = 0
,08-11 10:49:00.822  6443  6486 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.test.thalitest/shared_prefs/WebViewChromiumPrefs.xml.bak
,08-11 10:49:00.822  6443  6443 I cr_BrowserStartup: Initializing chromium process, singleProcess=true
,08-11 10:49:00.862  6443  6443 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build:  (Ia10634f51b)
08-11 10:49:00.862  6443  6443 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.29.00.00
08-11 10:49:00.862  6443  6443 I Adreno-EGL: Build Date: 01/28/16 Thu
08-11 10:49:00.862  6443  6443 I Adreno-EGL: Local Branch: ss
08-11 10:49:00.862  6443  6443 I Adreno-EGL: Remote Branch: 
08-11 10:49:00.862  6443  6443 I Adreno-EGL: Local Patches: 
08-11 10:49:00.862  6443  6443 I Adreno-EGL: Reconstruct Branch: 
,08-11 10:49:00.862  6443  6443 D libEGL  : eglInitialize EGLDisplay = 0xbec83dac
,08-11 10:49:00.882  6462  6462 W         : Unable to open '/system/framework/com.qti.location.sdk.jar': No such file or directory
08-11 10:49:00.882  6462  6462 W art     : Failed to open zip archive '/system/framework/com.qti.location.sdk.jar': I/O Error
,08-11 10:49:00.902   781  1742 D ActivityManager: The following uid has registered to recieve broadcast for proxy related updates 10004
,08-11 10:49:00.902   781  1742 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:845 com.android.server.am.ActivityManagerService.requestKnoxVpnToSendProxyBroadcast:29652 com.android.server.am.ActivityManagerService.registerReceiver:22522 android.app.ActivityManagerNative.onTransact:431 com.android.server.am.ActivityManagerService.onTransact:3990 
,08-11 10:49:00.962  6443  6443 D cr_Ime  : [InputMethodManagerWrapper.java:27] Constructor
,08-11 10:49:00.972  6443  6443 W cr_AwContents: onDetachedFromWindow called when already detached. Ignoring
,08-11 10:49:00.972  6443  6443 D cr_Ime  : [ImeAdapter.java:358] onViewFocusChanged: gainFocus [false]
,08-11 10:49:00.972  6443  6443 D cr_Ime  : [ImeAdapter.java:326] hideKeyboard
,08-11 10:49:00.972  6443  6443 D cr_Ime  : [InputMethodManagerWrapper.java:56] isActive: false
,08-11 10:49:00.972  6462  6462 I SL_DEBUG: isLoggable:: isProductShip = 1
,08-11 10:49:00.972  6462  6462 I SL_DEBUG: isLoggable:: SL_DEBUG_EXIST = false
,08-11 10:49:00.982   781   796 D PackageManager: setEnabledSetting : userId = 0 packageName = com.samsung.android.sdk.samsunglink cmp = com.sec.pcw.analytics.AnalyticsAlarmReceiver newState = 0 callingPackage = 10041
,08-11 10:49:00.982  6443  6443 D cr_Ime  : [ImeAdapter.java:358] onViewFocusChanged: gainFocus [true]
,08-11 10:49:00.982   781  2180 D PackageManager: setEnabledSetting : userId = 0 packageName = com.samsung.android.sdk.samsunglink cmp = com.mfluent.asp.BootCompletedBroadcastReciever newState = 0 callingPackage = 10041
,08-11 10:49:00.992   781  1723 D PackageManager: setEnabledSetting : userId = 0 packageName = com.samsung.android.sdk.samsunglink cmp = com.mfluent.asp.AutoUploadMediaReceiver newState = 0 callingPackage = 10041
,08-11 10:49:00.992   781  1743 D PackageManager: setEnabledSetting : userId = 0 packageName = com.samsung.android.sdk.samsunglink cmp = com.sec.pcw.service.push.spp.SPPReceiver newState = 0 callingPackage = 10041
,08-11 10:49:00.992   781  1744 D PackageManager: setEnabledSetting : userId = 0 packageName = com.samsung.android.sdk.samsunglink cmp = com.sec.pcw.service.push.gcm.GCMReceiver newState = 0 callingPackage = 10041
,08-11 10:49:00.992  6443  6443 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
,08-11 10:49:00.992   781   796 D PackageManager: setEnabledSetting : userId = 0 packageName = com.samsung.android.sdk.samsunglink cmp = com.sec.pcw.service.push.PCloudReceiver newState = 0 callingPackage = 10041
,08-11 10:49:00.992   781  1723 D PackageManager: setEnabledSetting : userId = 0 packageName = com.samsung.android.sdk.samsunglink cmp = com.sec.pcw.service.push.RetryReceiver newState = 0 callingPackage = 10041
,08-11 10:49:01.002   781   798 D PackageManager: setEnabledSetting : userId = 0 packageName = com.samsung.android.sdk.samsunglink cmp = com.mfluent.asp.util.ProcessorManagerAlarmReceiver newState = 0 callingPackage = 10041
,08-11 10:49:01.002   781  1455 D PackageManager: setEnabledSetting : userId = 0 packageName = com.samsung.android.sdk.samsunglink cmp = com.sec.pcw.service.account.SamsungAccountReceiver newState = 0 callingPackage = 10041
,08-11 10:49:01.002   781  1743 D PackageManager: setEnabledSetting : userId = 0 packageName = com.samsung.android.sdk.samsunglink cmp = com.mfluent.asp.sync.CloudStorageSyncEnablerReceiver newState = 0 callingPackage = 10041
,08-11 10:49:01.082  6517  6517 E Zygote  : v2
,08-11 10:49:01.082  6517  6517 I libpersona: KNOX_SDCARD checking this for 10210
08-11 10:49:01.082  6517  6517 I libpersona: KNOX_SDCARD not a persona
,08-11 10:49:01.082  6517  6517 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-11 10:49:01.082   781   878 I ActivityManager: Start proc 6517:com.samsung.aasaservice/u0a210 for service com.samsung.aasaservice/.AASAService
08-11 10:49:01.082  6517  6517 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,08-11 10:49:01.082  6517  6517 E Zygote  : accessInfo : 0
,08-11 10:49:01.082  6517  6517 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.samsung.aasaservice 
,08-11 10:49:01.092  6443  6443 D SecWifiDisplayUtil: Metadata value : none
,08-11 10:49:01.092  6443  6443 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{cad00b0 I.E...... R.....ID 0,0-0,0}
,08-11 10:49:01.092  6443  6524 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,08-11 10:49:01.102   781  2180 D ISSUE_DEBUG: InputChannelName : 93e4aea com.test.thalitest/com.test.thalitest.MainActivity
,08-11 10:49:01.102   781  1278 D ActivityManager: post active user change for 0 fullscreen true isFloatingActivity() false isHomeActivity() false
08-11 10:49:01.102   781  1278 D KnoxTimeoutHandler: postActiveUserChange [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
,08-11 10:49:01.102   781   781 D KnoxTimeoutHandler: handleActiveUserChange [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
,08-11 10:49:01.102   781   781 I KnoxTimeoutHandler: Shared devices show user statefalse
,08-11 10:49:01.122  6443  6443 D ConnectivityManager: requestNetwork; getAppId(CallingUid) : 10004, CallingPid : 6443
,08-11 10:49:01.122   781  1278 D ConnectivityService: listenForNetwork for Listen from uid/pid:10004/6443 for NetworkRequest [ id=13, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-11 10:49:01.122   781  1333 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 502]
08-11 10:49:01.122   781  1333 D ConnectivityService:  network has: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::ee1f:72ff:fe63:1186/64,192.168.1.123/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN&VALIDATED LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -47]}  Score{60}  everValidated{true}  lastValidated{true}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
08-11 10:49:01.122   781  1333 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 502] was already satisfying request 1. No change.
,08-11 10:49:01.122   781  1333 D ConnectivityService:   checking if request is: NetworkRequest [ id=10, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
08-11 10:49:01.122   781  1333 D ConnectivityService:   checking if request is: NetworkRequest [ id=12, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
08-11 10:49:01.122   781  1333 D ConnectivityService:   checking if request is: NetworkRequest [ id=13, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
08-11 10:49:01.122   781  1333 D ConnectivityService:   checking if request is: NetworkRequest [ id=5, legacyType=-1, [] ] satisfies: true nri.isRequest: false
08-11 10:49:01.122   781  1333 D ConnectivityService:   checking if request is: NetworkRequest [ id=4, legacyType=-1, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
08-11 10:49:01.122   781  1333 D ConnectivityService:   checking if request is: NetworkRequest [ id=11, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: true nri.isRequest: false
,08-11 10:49:01.122   781  1333 D ConnectivityService:   checking if request is: NetworkRequest [ id=3, legacyType=-1, [ Transports: CELLULAR Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] satisfies: false nri.isRequest: false
08-11 10:49:01.122   781  1333 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=13, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-11 10:49:01.132  6443  6486 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.test.thalitest/shared_prefs/com.test.thalitest_preferences.xml.bak
,08-11 10:49:01.132  6517  6517 D TimaKeyStoreProvider: TimaSignature is unavailable
08-11 10:49:01.132  6517  6517 D ActivityThread: Added TimaKeyStore provider
,08-11 10:49:01.142  6443  6443 D SecWifiDisplayUtil: Metadata value : none
,08-11 10:49:01.152   293   293 I SurfaceFlinger: id=17 createSurf (1x1),1 flag=404, NainActivit
,08-11 10:49:01.152  6517  6517 W ResourcesManager: getTopLevelResources: /system/app/AASAservice/AASAservice.apk / 1.0 running in com.samsung.aasaservice rsrc of package null
,08-11 10:49:01.162   781  1758 D InputDispatcher: Focus entered window: 6443
,08-11 10:49:01.162   781   923 D PointerIcon: setMouseIconStyle1 pointerType: 1001 iconType:101 flag:0 pid:781 uid:1000
08-11 10:49:01.162   781   923 D PointerIcon: setMouseCustomIcon IconType is same.101
08-11 10:49:01.162   781   923 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001 iconType:1 flag:0 pid:781 uid:1000
08-11 10:49:01.162   781   923 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
08-11 10:49:01.162  6443  6524 D libEGL  : eglInitialize EGLDisplay = 0x9c9bc7c4
08-11 10:49:01.162  6443  6524 I OpenGLRenderer: Initialized EGL, version 1.4
,08-11 10:49:01.172  6517  6517 W System  : ClassLoader referenced unknown path: /system/app/AASAservice/lib/arm
,08-11 10:49:01.172  6517  6517 D AASAservice: onCreate()
,08-11 10:49:01.182  5486  5486 I DBG_POLICYDM: [lIIIIllIIlIIIlIllIII(40/onServiceConnected)] AASA: onServiceConnected
08-11 10:49:01.182   781  1455 I ActivityManager: Killing 4960:com.android.calendar/u0a149 (adj 15): DHA:empty #37
,08-11 10:49:01.202   781  2414 D ActivityManager: isAutoRunBlockedApp:: com.android.calendar, Auto Run ON
,08-11 10:49:01.202  6462  6462 W System.err: java.lang.NumberFormatException: Invalid double: "4.0.67"
,08-11 10:49:01.202  6462  6462 W System.err: 	at java.lang.StringToReal.invalidReal(StringToReal.java:63)
08-11 10:49:01.202  6462  6462 W System.err: 	at java.lang.StringToReal.initialParse(StringToReal.java:160)
08-11 10:49:01.202  6462  6462 W System.err: 	at java.lang.StringToReal.parseDouble(StringToReal.java:282)
08-11 10:49:01.202  6462  6462 W System.err: 	at java.lang.Double.parseDouble(Double.java:301)
08-11 10:49:01.202  6462  6462 W System.err: 	at com.mfluent.asp.ASPApplication.onCreate(SourceFile:375)
08-11 10:49:01.202  6462  6462 W System.err: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1036)
08-11 10:49:01.202  6462  6462 W System.err: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:6316)
08-11 10:49:01.202  6462  6462 W System.err: 	at android.app.ActivityThread.access$1800(ActivityThread.java:221)
08-11 10:49:01.202  6462  6462 W System.err: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1860)
08-11 10:49:01.202  6462  6462 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-11 10:49:01.202  6462  6462 W System.err: 	at android.os.Looper.loop(Looper.java:158)
08-11 10:49:01.202  6462  6462 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:7224)
08-11 10:49:01.202  6462  6462 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-11 10:49:01.202  6462  6462 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1230)
08-11 10:49:01.202  6462  6462 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1120)
,08-11 10:49:01.212   781  1744 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{b49c611 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{307add6 1688:android.process.acore/u0a19}
,08-11 10:49:01.222  6443  6443 V ActivityThread: updateVisibility : ActivityRecord{9b7766b token=android.os.BinderProxy@b8a7bf3 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,08-11 10:49:01.222   781  1452 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{b49c611 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{87f5083 5235:com.sec.android.gallery3d/u0a47}
,08-11 10:49:01.222  5235  5235 I PackagesMonitor: PackagesMonitor onReceive :com.test.thalitest
,08-11 10:49:01.232   781  1744 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,08-11 10:49:01.232  6443  6443 W DisplayListCanvas: DisplayListCanvas is started on unbinded RenderNode (without mOwningView)
,08-11 10:49:01.252  6543  6543 E Zygote  : v2
,08-11 10:49:01.252  6543  6543 I libpersona: KNOX_SDCARD checking this for 10050
08-11 10:49:01.252   781  1742 I ActivityManager: Start proc 6543:com.sec.android.app.myfiles/u0a50 for broadcast-3 com.sec.android.app.myfiles/.receiver.MyFilesReceiver
08-11 10:49:01.252  6543  6543 I libpersona: KNOX_SDCARD not a persona
,08-11 10:49:01.262  6543  6543 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
,08-11 10:49:01.262  6543  6543 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,08-11 10:49:01.262  6543  6543 E Zygote  : accessInfo : 0
,08-11 10:49:01.262  6543  6543 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.sec.android.app.myfiles 
,08-11 10:49:01.262   781  1758 V WindowStateAnimator: Finishing drawing window Window{93e4aea u0 d0 com.test.thalitest/com.test.thalitest.MainActivity}: mDrawState=DRAW_PENDING
,08-11 10:49:01.262  6443  6443 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 72 - 0, 0) vi=Rect(0, 72 - 0, 0) or=1
,08-11 10:49:01.262  6443  6443 D cr_Ime  : [ImeAdapter.java:140] onCreateInputConnection returns null.
,08-11 10:49:01.272   781  2414 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,08-11 10:49:01.272   781   923 D KnoxTimeoutHandler: notifyActivityDrawn [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
,08-11 10:49:01.272   781   781 D KnoxTimeoutHandler: activityDrawn [MsgParam] userId: 0 fullscreen is true showWhenlocked is false
,08-11 10:49:01.272   781   923 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +641ms (total +1s54ms)
,08-11 10:49:01.272   781   781 I KnoxTimeoutHandler: SD activityfalse
,08-11 10:49:01.272   781   923 D ActivityManager: mDVFSHelper.release()
,08-11 10:49:01.272   781   923 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{50d1185 u0 com.test.thalitest/.MainActivity t153} time:97719
,08-11 10:49:01.282   293   293 D libEGL  : eglInitialize EGLDisplay = 0xbef49364
,08-11 10:49:01.292   781   923 D ViewRootImpl: #3 mView = null
,08-11 10:49:01.292   293   378 I SurfaceFlinger: id=16 Removed uhalitest (7/9)
,08-11 10:49:01.292   293   293 D libEGL  : eglTerminate EGLDisplay = 0xbef4938c
,08-11 10:49:01.302   781  1455 V WindowStateAnimator: Finishing drawing window Window{93e4aea u0 d0 com.test.thalitest/com.test.thalitest.MainActivity}: mDrawState=HAS_DRAWN
,08-11 10:49:01.302  6443  6556 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-11 10:49:01.302  6443  6556 D libEGL  : eglInitialize EGLDisplay = 0x9a0103ec
,08-11 10:49:01.302  6443  6443 D cr_Ime  : [ImeAdapter.java:140] onCreateInputConnection returns null.
,08-11 10:49:01.302  6443  6443 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@b8a7bf3 time:97746
,08-11 10:49:01.312   293   293 D libEGL  : eglInitialize EGLDisplay = 0xbef49364
,08-11 10:49:01.312  6543  6543 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-11 10:49:01.322  6543  6543 D ActivityThread: Added TimaKeyStore provider
,08-11 10:49:01.332   781  1739 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{b49c611 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{7ae77cb 6543:com.sec.android.app.myfiles/u0a50}
,08-11 10:49:01.332  6543  6543 W ResourcesManager: getTopLevelResources: /system/priv-app/SecMyFiles2014/SecMyFiles2014.apk / 1.0 running in com.sec.android.app.myfiles rsrc of package null
,08-11 10:49:01.342   781  2180 I ActivityManager: Killing 5592:com.sec.esdk.elm/u0a103 (adj 15): DHA:empty #37
,08-11 10:49:01.352  6443  6443 W cr_BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 6443
,08-11 10:49:01.352  6543  6543 W System  : ClassLoader referenced unknown path: /system/priv-app/SecMyFiles2014/lib/arm
,08-11 10:49:01.362   781  1758 D ActivityManager: isAutoRunBlockedApp:: com.sec.esdk.elm, Auto Run ON
,08-11 10:49:01.392  6543  6543 D MyFiles : MyFilesReceiver::Received the android.intent.action.PACKAGE_ADDED
,08-11 10:49:01.402   781  1743 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{b49c611 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{7504284 2870:com.android.settings/1000}
,08-11 10:49:01.412   327   327 E installd: system dir 0 : /system/app/
08-11 10:49:01.412   327   327 E installd: system dir 1 : /system/priv-app/
08-11 10:49:01.412   327   327 E installd: system dir 2 : /vendor/app/
08-11 10:49:01.412   327   327 E installd: system dir 3 : /oem/app/
,08-11 10:49:01.422   781  1015 D PackageManager: remove MCS_UNBIND message and Posting MCS_UNBIND 10 secs later
,08-11 10:49:01.432   781  2180 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{b49c611 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{7504284 2870:com.android.settings/1000}
,08-11 10:49:01.442   781  2180 I ActivityManager: Start proc 6565:com.samsung.android.provider.shootingmodeprovider/u0a169 for broadcast-3 com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.PackageIntentReceiver
,08-11 10:49:01.442  6565  6565 E Zygote  : v2
08-11 10:49:01.442  6565  6565 I libpersona: KNOX_SDCARD checking this for 10169
08-11 10:49:01.442  6565  6565 I libpersona: KNOX_SDCARD not a persona
,08-11 10:49:01.442  6565  6565 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-11 10:49:01.442  6565  6565 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,08-11 10:49:01.442  6565  6565 E Zygote  : accessInfo : 0
,08-11 10:49:01.442  6565  6565 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.samsung.android.provider.shootingmodeprovider 
,08-11 10:49:01.452  6443  6443 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-11 10:49:01.452  5846  5875 D Volley  : [813] c.a: HTTP response for request=<[ ] https://android.clients.google.com/fdfe/replicateLibrary 0xe8d195d1 NORMAL 3> [lifetime=8068], [size=1613], [rc=502], [retryCount=0]
,08-11 10:49:01.452  5846  5875 E Volley  : [813] c.a: Unexpected response code 502 for https://android.clients.google.com/fdfe/replicateLibrary
,08-11 10:49:01.462  5846  5875 W Finsky  : [813] com.google.android.finsky.api.o.a(561): IOException while manually unzipping request.
08-11 10:49:01.462  5846  5846 W Finsky  : [1] com.google.android.finsky.k.ac.a(562): Library replication failed: com.android.volley.ServerError
,08-11 10:49:01.472  6565  6565 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-11 10:49:01.472  6565  6565 D ActivityThread: Added TimaKeyStore provider
,08-11 10:49:01.482   781  1723 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{b49c611 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{3993a54 6565:com.samsung.android.provider.shootingmodeprovider/u0a169}
,08-11 10:49:01.492  6565  6565 W ResourcesManager: getTopLevelResources: /system/priv-app/ShootingModeProvider/ShootingModeProvider.apk / 1.0 running in com.samsung.android.provider.shootingmodeprovider rsrc of package null
,08-11 10:49:01.502  6565  6565 W System  : ClassLoader referenced unknown path: /system/priv-app/ShootingModeProvider/lib/arm
,08-11 10:49:01.532   781  1723 I ActivityManager: Killing 5458:com.samsung.android.app.assistantmenu/1000 (adj 15): DHA:empty #37
,08-11 10:49:01.542   781  1723 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{b49c611 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{4186226 1727:com.android.phone/1001}
,08-11 10:49:01.552   781  1743 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{b49c611 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{bef40d1 1853:com.google.android.googlequicksearchbox:search/u0a61}
,08-11 10:49:01.562   781  1455 D ActivityManager: isAutoRunBlockedApp:: com.samsung.android.app.assistantmenu, Auto Run ON
,08-11 10:49:01.572   781   796 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{b49c611 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{bef40d1 1853:com.google.android.googlequicksearchbox:search/u0a61}
,08-11 10:49:01.602   781  2414 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{b49c611 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{bf38af2 6344:com.samsung.android.sm.provider/1000}
,08-11 10:49:01.632   781  2180 I ActivityManager: Start proc 6582:com.samsung.android.sm.devicesecurity/5012 for broadcast-3 com.samsung.android.sm.devicesecurity/.PackageReceiver
,08-11 10:49:01.632  6582  6582 E Zygote  : v2
08-11 10:49:01.632  6582  6582 I libpersona: KNOX_SDCARD checking this for 5012
08-11 10:49:01.632  6582  6582 I libpersona: KNOX_SDCARD not a persona
,08-11 10:49:01.632  6582  6582 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-11 10:49:01.632  6582  6582 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,08-11 10:49:01.632  6582  6582 E Zygote  : accessInfo : 0
,08-11 10:49:01.632  6582  6582 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.samsung.android.sm.devicesecurity 
,08-11 10:49:01.632  6443  6580 D jxcore_app_log: JniHelper::setJavaVM(0xb477c000), pthread_self() = -1725957840
,08-11 10:49:01.642  6443  6580 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-11 10:49:01.642  6443  6580 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-11 10:49:01.642  6443  6580 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-11 10:49:01.642  6443  6580 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-11 10:49:01.642  6443  6580 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
08-11 10:49:01.642  6443  6580 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a382099 added. We now have 1 listener(s)
,08-11 10:49:01.642  6443  6580 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 7C:F9:0E:34:8A:A0
,08-11 10:49:01.652  6443  6580 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:34:8A:A0"
,08-11 10:49:01.652  6443  6580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-11 10:49:01.652  6443  6580 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-11 10:49:01.652  6443  6580 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-11 10:49:01.652  6443  6580 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-11 10:49:01.652  6443  6580 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-11 10:49:01.652  6443  6580 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 7C:F9:0E:34:8A:A0
08-11 10:49:01.652  6443  6580 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-11 10:49:01.652  6443  6580 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-11 10:49:01.652  6443  6580 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-11 10:49:01.652  6443  6580 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-11 10:49:01.652  6443  6580 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-11 10:49:01.652  6443  6580 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-11 10:49:01.652  6443  6580 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-11 10:49:01.652  6443  6580 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-11 10:49:01.652  6443  6580 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-11 10:49:01.652  6443  6580 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-11 10:49:01.652  6443  6580 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@358900c added. We now have 1 listener(s)
08-11 10:49:01.652  6443  6580 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-11 10:49:01.652  6443  6580 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-11 10:49:01.652  6443  6580 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-11 10:49:01.662  6443  6580 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
,08-11 10:49:01.662  6443  6580 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
,08-11 10:49:01.662  6443  6580 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,08-11 10:49:01.662  6443  6580 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-11 10:49:01.662  6443  6580 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 7C:F9:0E:34:8A:A0
,08-11 10:49:01.662  6582  6582 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-11 10:49:01.662  6582  6582 D ActivityThread: Added TimaKeyStore provider
,08-11 10:49:01.672  6443  6580 D BluetoothAdapter: STATE_ON
,08-11 10:49:01.672   781   796 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{b49c611 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{a958fb5 6582:com.samsung.android.sm.devicesecurity/5012}
,08-11 10:49:01.672  6443  6580 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,08-11 10:49:01.672  6443  6580 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-11 10:49:01.672  6443  6580 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-11 10:49:01.672  6443  6580 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-11 10:49:01.672  6443  6580 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-11 10:49:01.672  6443  6580 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-11 10:49:01.672  6443  6580 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-11 10:49:01.672  6443  6580 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-11 10:49:01.672  6443  6580 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-11 10:49:01.672  6443  6580 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-11 10:49:01.672  6443  6580 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-11 10:49:01.672   781  3503 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in null rsrc of package null
,08-11 10:49:01.682  6443  6443 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-11 10:49:01.682  6443  6580 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-11 10:49:01.682  6443  6443 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-11 10:49:01.682  6582  6582 W ResourcesManager: getTopLevelResources: /system/priv-app/SmartManager_v3_DeviceSecurity/SmartManager_v3_DeviceSecurity.apk / 1.0 running in com.samsung.android.sm.devicesecurity rsrc of package null
,08-11 10:49:01.692  1853  6579 I UpdateIcingCorporaServi: Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,08-11 10:49:01.702  6443  6443 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-11 10:49:01.712  6582  6582 W System  : ClassLoader referenced unknown path: /system/priv-app/SmartManager_v3_DeviceSecurity/lib/arm
,08-11 10:49:01.742   781   796 I ActivityManager: Killing 5608:com.sec.providers.settingsearch/u0a167 (adj 15): DHA:empty #37
,08-11 10:49:01.742   781   796 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{b49c611 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{8d1a41c 3254:com.android.contacts/u0a19}
,08-11 10:49:01.762   781   798 D ActivityManager: isAutoRunBlockedApp:: com.sec.providers.settingsearch, Auto Run ON
,08-11 10:49:01.772  6595  6595 E Zygote  : v2
08-11 10:49:01.772  6595  6595 I libpersona: KNOX_SDCARD checking this for 10049
08-11 10:49:01.772  6595  6595 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-11 10:49:01.772  6595  6595 I libpersona: KNOX_SDCARD not a persona
08-11 10:49:01.772  6595  6595 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
08-11 10:49:01.772  6595  6595 E Zygote  : accessInfo : 0
08-11 10:49:01.772  6595  6595 W SELinux : SELinux: seapp_context_lookup: seinfo=release, level=s0:c512,c768, pkgname=com.android.mms 
,08-11 10:49:01.772   781  1278 I ActivityManager: Start proc 6595:com.android.mms/u0a49 for broadcast-3 com.android.mms/.smishing.PackageInstallReceiver
,08-11 10:49:01.782  1853  6579 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.google.android.googlequicksearchbox rsrc of package null
,08-11 10:49:01.802  1853  6579 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.google.android.googlequicksearchbox rsrc of package null
,08-11 10:49:01.812  6595  6595 D TimaKeyStoreProvider: TimaSignature is unavailable
08-11 10:49:01.812  6595  6595 D ActivityThread: Added TimaKeyStore provider
,08-11 10:49:01.812   781  1455 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{b49c611 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{e75864a 6595:com.android.mms/u0a49}
,08-11 10:49:01.822  6595  6595 W ResourcesManager: getTopLevelResources: /system/priv-app/SecMms_Candy_M/SecMms_Candy_M.apk / 1.0 running in com.android.mms rsrc of package null
,08-11 10:49:01.852  6595  6595 W System  : ClassLoader referenced unknown path: imsmanager.jar
,08-11 10:49:01.862  6595  6595 W System  : ClassLoader referenced unknown path: /system/priv-app/SecMms_Candy_M/lib/arm
,08-11 10:49:01.902  6595  6595 D Mms/MmsApp: [start]    onCreate() consume time = 0.0
,08-11 10:49:01.922  6595  6607 D Mms/ArtClassLoader: init before art first
,08-11 10:49:01.922  6595  6609 D Mms/ArtClassLoader: init before art third
,08-11 10:49:01.932  6595  6608 D Mms/ArtClassLoader: init before art second
,08-11 10:49:01.932  6595  6595 D Mms/TelephonyPermission: start operation mode monitor
08-11 10:49:01.932  6595  6595 D Mms/TelephonyPermission: User ID is null set current User Id
,08-11 10:49:01.942  6595  6595 W ResourcesManager: getTopLevelResources: /system/priv-app/SecMms_Candy_M/SecMms_Candy_M.apk / 1.0 running in com.android.mms rsrc of package null
,08-11 10:49:01.952  1853  6579 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 253 ms] updated apps [took 253 ms] 
,08-11 10:49:01.952  6595  6609 D Mms/ArtClassLoader: init [DONE] art
08-11 10:49:01.952  6595  6595 W ResourcesManager: getTopLevelResources: /system/app/Hangouts/Hangouts.apk / 1.0 running in com.android.mms rsrc of package null
,08-11 10:49:01.982  6595  6595 D Mms/TelephonyPermission: DefaultSmsApp is com.android.mms
08-11 10:49:01.982  6595  6595 D Mms/TelephonyPermission: isDefault true
,08-11 10:49:01.982  6595  6595 D Mms/MmsApp: onCreate() com.android.mms
,08-11 10:49:02.002  6595  6595 D Mms/MessageUtils: getMessagingSimType() simSlotCount : 1
,08-11 10:49:02.022  6595  6595 D Mms/MmsApp: [start]    initCountryIso consume time = 110.932813
,08-11 10:49:02.022   781  1452 D CountryDetector: The first listener is added
,08-11 10:49:02.032  6595  6595 D Mms/MmsApp: [end]    initCountryIso consume time = 12.79651
08-11 10:49:02.032  6595  6595 D Mms/MmsConfig: [start]    MmsConfig.init() consume time = 0.099636
,08-11 10:49:02.062  6595  6595 D Mms/MmsConfig: before partial update
,08-11 10:49:02.072  6595  6607 D Mms/ArtClassLoader: init [DONE] art
,08-11 10:49:02.092  6595  6595 D Mms/MmsConfig: Load Resize quality : 80
,08-11 10:49:02.102  6595  6608 D Mms/ArtClassLoader: init [DONE] art
,08-11 10:49:02.102  6595  6595 E ActivityThread: Failed to find provider info for com.samsung.android.coreapps.easysignup.public
,08-11 10:49:02.102  6595  6595 D EasySignUpManager_1.0.5: isAuth is false
08-11 10:49:02.102  6595  6595 I EasySignUpManager_1.0.5: auth : false, join : 2
,08-11 10:49:02.102  6595  6595 D Mms/MmsConfig: getEasySignUpStatus - sIsAuthEasySignUp(isJoined(SERVICE_ID_RSHARE)) = false, TelephonyUtils.getSimState(0)= 1
,08-11 10:49:02.102  1457  1457 D Recents : onTaskStackChanged
,08-11 10:49:02.112  6595  6595 D EasySignUpManager_1.0.5: userSerialNumber = 0
,08-11 10:49:02.112  6595  6595 E ActivityThread: Failed to find provider info for com.samsung.android.coreapps.easysignup.public
08-11 10:49:02.112  6595  6595 D EasySignUpManager_1.0.5: serviceId : 1, features : -1
,08-11 10:49:02.112  6595  6595 E ActivityThread: Failed to find provider info for com.samsung.android.coreapps.easysignup.public
08-11 10:49:02.112  6595  6595 D EasySignUpManager_1.0.5: isAuth is false
08-11 10:49:02.112  6595  6595 D EasySignUpManager_1.0.5: getServiceStatus : serviceId (1) is OFF
,08-11 10:49:02.112  6595  6595 D Mms/MmsConfig: setFreeMessageEnabled, getSupportedFeatures = -1 sIsAuthEasySignUp = false sIsFreeMessageServiceStatus = false
,08-11 10:49:02.112  1457  1457 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.android.systemui rsrc of package null
,08-11 10:49:02.132  1727  1741 D TP/MmsSmsProvider: query, match:2117, calling pid = 6595, accessRestricted = false
,08-11 10:49:02.132  1727  1741 D TP/MmsSmsProvider: query, match 2117:Elapsed time : 2.433 ms
,08-11 10:49:02.142  6595  6595 E CscParser: mps_code.dat does not exist
,08-11 10:49:02.142  6595  6595 E CscParser: customer_path =/system/csc/customer.xml
08-11 10:49:02.142  6595  6595 E CscParser: fileName + /system/csc/customer.xml
,08-11 10:49:02.162  6595  6595 E CscParser: mps_code.dat does not exist
,08-11 10:49:02.162  6595  6595 E CscParser: customer_path =/system/csc/customer.xml
08-11 10:49:02.162  6595  6595 E CscParser: fileName + /system/csc/customer.xml
,08-11 10:49:02.172  6595  6595 D CscParser: getInstance fileName =/system/csc/customer.xml
,08-11 10:49:02.172  6595  6595 D Mms/MmsConfig:  enable multiwindow = true
,08-11 10:49:02.172  6595  6595 D Mms/PackageInfo: isEnabledComponent compomentName=com.android.mms.ui.RcsTransferContent
,08-11 10:49:02.172  6595  6595 D Mms/PackageInfo: isEnabledComponent compomentName=com.android.mms.ui.TmoRcsTransferContent
,08-11 10:49:02.172  6595  6595 D Mms/MessageUtils: setComponentFreeMessage isChecked = false
08-11 10:49:02.172  6595  6595 D Mms/PackageInfo: isEnabledComponent compomentName=com.android.mms.ui.TransferContent
,08-11 10:49:02.172  6595  6595 D Mms/PackageInfo: isEnabledComponent compomentName=com.android.mms.ui.ComposeMessageMms
,08-11 10:49:02.172  6595  6595 E Mms/MessageUtils: setCountryDetector : update country detector info 
08-11 10:49:02.172  6595  6595 E Mms/MessageUtils: updateCountryIso : update country iso info 
,08-11 10:49:02.182  6595  6595 D Mms/MmsConfig: [end]    init() consume time = 150.558177
,08-11 10:49:02.192  6595  6595 D Mms/Contact: [start]    init() consume time = 6.132708
,08-11 10:49:02.202  6595  6595 D Mms/Contact: [end]    init consume time = 12.945261
,08-11 10:49:02.202  1727  1740 D TP/MmsSmsProvider: query, match:13, calling pid = 6595, accessRestricted = false
,08-11 10:49:02.202  1727  1740 D TP/MmsSmsProvider: query, match 13:Elapsed time : 1.236 ms
,08-11 10:49:02.212  6595  6615 D Mms/DraftCache: [start]    rebuildCache consume time = 10.676458
,08-11 10:49:02.212  6595  6595 D Mms:transaction: roaming -> false (slotId = 0)
,08-11 10:49:02.212  6595  6595 D Mms:transaction: [NotificationTransaction] getAutoDownloadState simSlot : 0
08-11 10:49:02.212  6595  6595 D Mms:transaction: auto download without roaming -> true
08-11 10:49:02.212  6595  6595 D Mms:transaction: [NotificationTransaction] getAutoDownloadState alwaysAuto : false, roaming : false
,08-11 10:49:02.212  6595  6595 D Mms:transaction: roaming -> false (slotId = 1)
08-11 10:49:02.212  6595  6595 D Mms:transaction: [NotificationTransaction] getAutoDownloadState simSlot : 1
08-11 10:49:02.212  6595  6595 D Mms:transaction: auto download without roaming -> true
08-11 10:49:02.212  6595  6595 D Mms:transaction: [NotificationTransaction] getAutoDownloadState alwaysAutoSecondary : false, roaming : false
08-11 10:49:02.212  6595  6595 D Mms:transaction: auto download during roaming secondary -> false
08-11 10:49:02.212  6595  6595 D Mms:transaction: mAutoDownload ------> true
,08-11 10:49:02.222  1727  2026 D TP/MmsSmsProvider: query, match:12, calling pid = 6595, accessRestricted = false
,08-11 10:49:02.222  1727  2026 D TP/MmsSmsProvider: query, match 12:Elapsed time : 1.333 ms
,08-11 10:49:02.222  6595  6615 D Mms/DraftCache: [end]    rebuildCache consume time = 14.687083
,08-11 10:49:02.262  6595  6595 D ComposerPerformance: 1470905342269 ms / [DONE] Composer constructor
,08-11 10:49:02.262  6595  6595 D CII     : Log Level [5]
08-11 10:49:02.262  6595  6595 E CII     : IMSUtility: isIMSServiceEnabled. VoLTE CSC feature disabled.
,08-11 10:49:02.262  6595  6617 D Mms/Conversation: [start]    init() consume time = 38.303021
,08-11 10:49:02.262  1727  1740 D TP/MmsSmsProvider: delete, match:1, calling pid = 6595
08-11 10:49:02.262  1727  1740 D TP/MmsSmsProvider: deleteConversation threadId: 9223372036854775807
08-11 10:49:02.262  1727  1740 V TP/MmsSmsProvider: deleteConversation delete_sys_msg: true finalSelection=thread_id = 9223372036854775807
,08-11 10:49:02.272  1727  1740 I TP/MmsSmsProvider: delete messages table selection : (thread_id = 9223372036854775807) AND (box_type = 3) null
,08-11 10:49:02.272  1727  1740 D TP/MmsSmsProvider: delete URI_CONVERSATIONS_MESSAGES affectedRows=0 isIntegrated=false
08-11 10:49:02.272  1727  1740 V TP/MmsSmsDatabaseHelper: updateThread(), thread_id = 9223372036854775807
,08-11 10:49:02.272  6595  6595 I Mms/ReservationManager: ReservationManager()
,08-11 10:49:02.272  6595  6595 I Mms/ReservationManager: resetAfterConnected()
,08-11 10:49:02.272  1727  1740 V TP/MmsSmsDatabaseHelper: sUpgradeVersion = 0, db.getVersion() = 118
,08-11 10:49:02.282  1727  2247 D TP/MmsSmsProvider: query, match:7, calling pid = 6595, accessRestricted = false
,08-11 10:49:02.282  1727  2247 D TP/MmsSmsProvider: query, match 7:Elapsed time : 2.610 ms
,08-11 10:49:02.292  6595  6595 I Mms/ReservationManager: getReservedSendMessageCount(): retMessageCount=0
08-11 10:49:02.292  1727  1740 V TP/MmsSmsDatabaseHelper: updateThread() end, affectedRows = 0
08-11 10:49:02.292  1727  1740 D TP/MmsSmsProvider: delete URI_CONVERSATIONS_MESSAGES affectedRows=0
08-11 10:49:02.292  1727  1740 D TP/MmsSmsProvider: delete threadId: 9223372036854775807
08-11 10:49:02.292  1727  1740 D TP/MmsSmsProvider: delete, match 1:Elapsed time : 10.988 ms
08-11 10:49:02.292  1727  1740 D TP/MmsSmsProvider: need read changed broadcast:false
,08-11 10:49:02.292  6595  6617 D Mms/Conversation: [end]    init consume time = 27.137761
,08-11 10:49:02.292  6595  6617 D Mms/MessagingNotification: [start]    init() consume time = 2.068541
,08-11 10:49:02.292  6595  6595 D Mms/MmsApp: [end]    onCreate() consume time = 1.314479
08-11 10:49:02.292  6595  6595 D Mms/MmsApp: [end]    onCreate() consume time = 0.09974
,08-11 10:49:02.292  6595  6595 D Mms:transaction: Service state changed: Bundle[mParcelledData.dataSize=1296]
,08-11 10:49:02.292  6595  6595 D Mms:transaction: roaming ------> false, mSimSlot = 0
08-11 10:49:02.292  6595  6595 D Mms:transaction: roaming -> false (slotId = 0)
08-11 10:49:02.292  6595  6595 D Mms:transaction: [NotificationTransaction] getAutoDownloadState simSlot : 0
08-11 10:49:02.292  6595  6595 D Mms:transaction: auto download without roaming -> true
08-11 10:49:02.292  6595  6595 D Mms:transaction: [NotificationTransaction] getAutoDownloadState alwaysAuto : false, roaming : false
08-11 10:49:02.292  6595  6595 D Mms:transaction: mAutoDownload ------> true
,08-11 10:49:02.312  6618  6618 E Zygote  : v2
08-11 10:49:02.312  6618  6618 I libpersona: KNOX_SDCARD checking this for 1000
08-11 10:49:02.312  6618  6618 I libpersona: KNOX_SDCARD not a persona
,08-11 10:49:02.312   781  1452 I ActivityManager: Start proc 6618:com.samsung.android.bbc.bbcagent/1000 for broadcast-3 com.samsung.android.bbc.bbcagent/.bbccontroller.receiver.PackageEventReceiver
,08-11 10:49:02.312  6618  6618 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
,08-11 10:49:02.312  6618  6618 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
08-11 10:49:02.312   781  1452 I ActivityManager: Killing 5623:com.sec.android.Kies/1000 (adj 15): DHA:empty #37
,08-11 10:49:02.312  6618  6618 E Zygote  : accessInfo : 0
,08-11 10:49:02.322  6595  6617 D Mms/MessagingNotification: [end]    init consume time = 26.833906
,08-11 10:49:02.332  6595  6629 D Mms/Synchronizer: [start]    doSync consume time = 9.368906
,08-11 10:49:02.332   781  1743 D ActivityManager: isAutoRunBlockedApp:: com.sec.android.Kies, Auto Run ON
,08-11 10:49:02.352  6595  6628 D Mms/SpamFilter: [start]    SpamFilter fill() begin consume time = 16.285052
,08-11 10:49:02.352  6618  6618 D TimaKeyStoreProvider: TimaSignature is unavailable
08-11 10:49:02.352  6618  6618 D ActivityThread: Added TimaKeyStore provider
,08-11 10:49:02.362   781  2414 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{b49c611 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{60d97c6 6618:com.samsung.android.bbc.bbcagent/1000}
,08-11 10:49:02.362  1727  1741 D TP/MmsSmsProvider: query, match:0, calling pid = 6595, accessRestricted = false
08-11 10:49:02.362  1727  1741 V TP/MmsSmsProvider: getSimpleConversations entered.
,08-11 10:49:02.372  1727  1741 D TP/MmsSmsProvider: query, match 0:Elapsed time : 2.310 ms
,08-11 10:49:02.372  1727  2247 D TP/MmsSmsProvider: query, match:400, calling pid = 6595, accessRestricted = false
,08-11 10:49:02.372  1727  2026 D TP/MmsSmsProvider: update, match:300, calling pid = 6595
08-11 10:49:02.372  1727  2026 V TP/MmsSmsProvider: syncDBData start
,08-11 10:49:02.372  1727  2026 V TP/MmsSmsProvider: syncDBData sms end
,08-11 10:49:02.372  1727  2026 V TP/MmsSmsProvider: syncDBData mms end
,08-11 10:49:02.372  1727  2026 V TP/MmsSmsProvider: syncDBData end
,08-11 10:49:02.372  1727  2026 D TP/MmsSmsProvider: update, match 300:Elapsed time : 2.487 ms
,08-11 10:49:02.372  6595  6629 D Mms/Synchronizer: [end]    doSync consume time = 27.455261
,08-11 10:49:02.382  6618  6618 W ResourcesManager: getTopLevelResources: /system/app/BBCAgent/BBCAgent.apk / 1.0 running in com.samsung.android.bbc.bbcagent rsrc of package null
,08-11 10:49:02.392  6149  6175 D BadgeProvider: query, [selection] : package=?
,08-11 10:49:02.412  6595  6617 D Mms/MessagingNotification: checkBadgeCount unreadCount=0 badgeCount=0
,08-11 10:49:02.422  1727  1741 D TP/SmsProvider: query,matched:26, calling pid = 6595
,08-11 10:49:02.432  1727  1741 D TP/SmsProvider: query, match 26:Elapsed time : 3.056 ms
,08-11 10:49:02.432  6618  6618 W System  : ClassLoader referenced unknown path: /system/app/BBCAgent/lib/arm
,08-11 10:49:02.432  6595  6628 D Mms/SpamFilter: [end]    SpamFilter fill() finished consume time = 60.821406
,08-11 10:49:02.452  1727  1740 D TP/MmsSmsProvider: query, match:6, calling pid = 6595, accessRestricted = false
,08-11 10:49:02.452  1727  1740 D TP/MmsSmsProvider: query, match 6:Elapsed time : 1.896 ms
,08-11 10:49:02.472   781   792 I art     : Background partial concurrent mark sweep GC freed 143563(8MB) AllocSpace objects, 7(1856KB) LOS objects, 27% free, 42MB/58MB, paused 2.183ms total 152.108ms
,08-11 10:49:02.492  6632  6632 E Zygote  : v2
08-11 10:49:02.492  6632  6632 I libpersona: KNOX_SDCARD checking this for 10024
08-11 10:49:02.492  6632  6632 I libpersona: KNOX_SDCARD not a persona
,08-11 10:49:02.492  6632  6632 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-11 10:49:02.492  6632  6632 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
08-11 10:49:02.492   781  1278 I ActivityManager: Start proc 6632:com.wsomacp/u0a24 for content provider com.wsomacp/.db.XCPDBSqlProvider
,08-11 10:49:02.492  6632  6632 E Zygote  : accessInfo : 0
08-11 10:49:02.492  6632  6632 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.wsomacp 
,08-11 10:49:02.522   781  1743 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
08-11 10:49:02.522   781  1743 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4240, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
08-11 10:49:02.522   781  1743 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
08-11 10:49:02.522   781  1743 D BatteryService: stay LED for charging
08-11 10:49:02.522   781   781 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-11 10:49:02.522   781   781 I MotionRecognitionService: Plugged
08-11 10:49:02.522   781   781 D MotionRecognitionService:   cableConnection= 1
08-11 10:49:02.522   781   781 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
08-11 10:49:02.522   781   781 D MotionRecognitionService: skip setTransmitPower. 
,08-11 10:49:02.522  1382  1382 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-11 10:49:02.522  1382  1382 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
,08-11 10:49:02.522  1382  1382 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-11 10:49:02.532  1382  1382 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-11 10:49:02.532  6632  6632 D TimaKeyStoreProvider: TimaSignature is unavailable
08-11 10:49:02.532  6632  6632 D ActivityThread: Added TimaKeyStore provider
,08-11 10:49:02.542  2312  2312 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
08-11 10:49:02.542  2312  2810 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-11 10:49:02.542  6443  6594 W jxcore-log: Initializing JXcore engine
08-11 10:49:02.542  6443  6594 W jxcore-log: JXcore engine is ready
,08-11 10:49:02.552   781  1739 I ActivityManager: Killing 5635:com.sec.android.widgetapp.activeapplicationwidget/u0a157 (adj 15): DHA:empty #37
,08-11 10:49:02.562  1382  1382 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-11 10:49:02.562  1382  1382 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-11 10:49:02.582  6645  6645 E Zygote  : v2
,08-11 10:49:02.582   781  1744 I ActivityManager: Start proc 6645:com.google.android.apps.docs/u0a97 for broadcast-3 com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver
08-11 10:49:02.582  6645  6645 I libpersona: KNOX_SDCARD checking this for 10097
,08-11 10:49:02.582  6645  6645 I libpersona: KNOX_SDCARD not a persona
,08-11 10:49:02.582  6645  6645 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
,08-11 10:49:02.582  6645  6645 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
08-11 10:49:02.582   781  1324 D NetworkPolicy: isUidForegroundLocked: 10097, mScreenOn: false, uidstate: -1, mProxSensorScreenOff: false
,08-11 10:49:02.582  6645  6645 E Zygote  : accessInfo : 0
,08-11 10:49:02.582   781  1744 I ActivityManager: Killing 5471:com.sec.android.diagmonagent/1000 (adj 15): DHA:empty #37
,08-11 10:49:02.592  6645  6645 W SELinux : SELinux: seapp_context_lookup: seinfo=untrusted, level=s0:c512,c768, pkgname=com.google.android.apps.docs 
,08-11 10:49:02.592  6443  6452 I art     : Background partial concurrent mark sweep GC freed 46802(5MB) AllocSpace objects, 11(2MB) LOS objects, 45% free, 19MB/35MB, paused 2.815ms total 109.437ms
,08-11 10:49:02.622   781  1324 D NetworkPolicy: isUidForegroundLocked: 10097, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,08-11 10:49:02.632  2329  2329 E audit   : type=1400 msg=audit(1470905342.632:289): avc:  denied  { ioctl } for  pid=6594 comm="Thread-883" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3095 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
08-11 10:49:02.632  2329  2329 E audit   :  SEPF_SECMOBILE_6.0.1_0011
08-11 10:49:02.632  2329  2329 E audit   : type=1300 msg=audit(1470905342.632:289): arch=40000028 syscall=54 per=800008 success=no exit=-13 a0=7 a1=5451 a2=3 a3=9907f3c8 items=0 ppid=354 ppcomm=main pid=6594 auid=4294967295 uid=10004 gid=10004 euid=10004 suid=10004 fsuid=10004 egid=10004 sgid=10004 fsgid=10004 tty=(none) ses=4294967295 comm="Thread-883" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0:c512,c768 key=(null)
08-11 10:49:02.632  2329  2329 E audit   : type=1327 msg=audit(1470905342.632:289): proctitle="com.test.thalitest"
08-11 10:49:02.632  2329  2329 E audit   : type=1320 msg=audit(1470905342.632:289): 
,08-11 10:49:02.632  2329  2329 E audit   : type=1400 msg=audit(1470905342.632:290): avc:  denied  { ioctl } for  pid=6594 comm="Thread-883" path="socket:[39516]" dev="sockfs" ino=39516 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
08-11 10:49:02.632  2329  2329 E audit   :  SEPF_SECMOBILE_6.0.1_0011
,08-11 10:49:02.632  2329  2329 E audit   : type=1300 msg=audit(1470905342.632:290): arch=40000028 syscall=54 per=800008 success=no exit=-13 a0=3a a1=5451 a2=3 a3=9907f3c8 items=0 ppid=354 ppcomm=main pid=6594 auid=4294967295 uid=10004 gid=10004 euid=10004 suid=10004 fsuid=10004 egid=10004 sgid=10004 fsgid=10004 tty=(none) ses=4294967295 comm="Thread-883" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0:c512,c768 key=(null)
08-11 10:49:02.632  2329  2329 E audit   : type=1327 msg=audit(1470905342.632:290): proctitle="com.test.thalitest"
08-11 10:49:02.632  2329  2329 E audit   : type=1320 msg=audit(1470905342.632:290): 
,08-11 10:49:02.652  6632  6632 W ResourcesManager: getTopLevelResources: /system/priv-app/OmaCP/OmaCP.apk / 1.0 running in com.wsomacp rsrc of package null
,08-11 10:49:02.652  6443  6594 W jxcore-log: Starting JXcore engine
,08-11 10:49:02.652  6645  6645 D TimaKeyStoreProvider: TimaSignature is unavailable
08-11 10:49:02.652  6645  6645 D ActivityThread: Added TimaKeyStore provider
,08-11 10:49:02.662   781  6323 I HarmonyEASService: Updating for all 1
,08-11 10:49:02.672  6632  6632 W System  : ClassLoader referenced unknown path: /system/priv-app/OmaCP/lib/arm
,08-11 10:49:02.682   781  1758 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{b49c611 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{12c2387 6645:com.google.android.apps.docs/u0a97}
,08-11 10:49:02.682   781  1744 D ActivityManager: isAutoRunBlockedApp:: com.sec.android.widgetapp.activeapplicationwidget, Auto Run ON
,08-11 10:49:02.682   781  3500 D SSRM:n  : SIOP:: AP = 470, PST = 441, CUR = 450, LCD = 0
,08-11 10:49:02.692  6645  6645 W ResourcesManager: getTopLevelResources: /system/app/Drive/Drive.apk / 1.0 running in com.google.android.apps.docs rsrc of package null
,08-11 10:49:02.692   781  1723 D ActivityManager: isAutoRunBlockedApp:: com.sec.android.diagmonagent, Auto Run ON
,08-11 10:49:02.722  6645  6645 W System  : ClassLoader referenced unknown path: /system/app/Drive/lib/arm
,08-11 10:49:02.742  6632  6632 I OMACP   : [com.wsomacp.XCPApplication(51/onCreate)] CPApplication Start !
,08-11 10:49:02.752  6595  6617 D Mms/Omacp: checkOmacp()  old OmacpCount 0 current OmacpCount = 0
,08-11 10:49:02.752  6443  6594 W jxcore-log: Platform android
08-11 10:49:02.752  6443  6594 W jxcore-log: 
08-11 10:49:02.752  6443  6594 W jxcore-log: Process ARCH arm
08-11 10:49:02.752  6443  6594 W jxcore-log: 
,08-11 10:49:02.772  2320  2320 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,08-11 10:49:02.782  2320  2320 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,08-11 10:49:02.782  2320  2320 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,08-11 10:49:02.812  6632  6632 I OMACP   : [com.wsomacp.agent.XCPSystem(120/xcpSystemSetCPFeature)] XCP_FEATURE_MAC_CHECK: false
,08-11 10:49:02.822  6632  6632 I OMACP   : [com.wsomacp.agent.XCPSystem(121/xcpSystemSetCPFeature)] XCP_FEATURE_SECURITY: 4369
,08-11 10:49:02.822  6632  6632 I OMACP   : [com.wsomacp.agent.XCPSystem(122/xcpSystemSetCPFeature)] XCP_FEATURE_NETWPIN_CHECK: false
,08-11 10:49:02.822  6632  6632 I OMACP   : [com.wsomacp.agent.XCPSystem(123/xcpSystemSetCPFeature)] XCP_FEATURE_MULTI_APN: true
,08-11 10:49:02.822  6632  6632 I OMACP   : [com.wsomacp.agent.XCPSystem(124/xcpSystemSetCPFeature)] XCP_FEATURE_OVERWRITE_BY_APN: false
08-11 10:49:02.822  6632  6632 I OMACP   : [com.wsomacp.agent.XCPSystem(125/xcpSystemSetCPFeature)] XCP_FEATURE_DELETE_CP_MESSAGE: false
,08-11 10:49:02.832  6632  6632 I OMACP   : [com.wsomacp.agent.XCPSystem(126/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_MYPHONEBOOK: false
,08-11 10:49:02.832  6632  6632 I OMACP   : [com.wsomacp.agent.XCPSystem(127/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_OMADM_BOOTSTRAP: false
08-11 10:49:02.832  6632  6632 I OMACP   : [com.wsomacp.agent.XCPSystem(128/xcpSystemSetCPFeature)] XCP_FEATURE_BG_INTSATLL_DM_BOOTSTRAP: false
08-11 10:49:02.832  6632  6632 I OMACP   : [com.wsomacp.agent.XCPSystem(129/xcpSystemSetCPFeature)] XCP_DEVICETYPE_FEATURE_TABLET : false
08-11 10:49:02.832  6632  6632 I OMACP   : [com.wsomacp.agent.XCPSystem(130/xcpSystemSetCPFeature)] XCP_SUPPORT_DUAL_SIM : false
08-11 10:49:02.842  6632  6632 I OMACP   : [com.wsomacp.agent.XCPSystem(131/xcpSystemSetCPFeature)] XCP_SUPPORT_USA_ATT : false
08-11 10:49:02.842  6632  6632 I OMACP   : [com.wsomacp.agent.XCPSystem(132/xcpSystemSetCPFeature)] XCP_SUPPORT_SAME_APN : false
,08-11 10:49:02.932  4410  5161 I Icing   : Indexing 38360883C61536E4027A6B9191D49E9DF51837DC from com.google.android.googlequicksearchbox
,08-11 10:49:02.952  6443  6594 I jxcore-log: JXcore Cordova bridge is ready!
08-11 10:49:02.952  6443  6594 I jxcore-log: 
,08-11 10:49:02.952  6443  6594 W jxcore-log: JXcore engine is started
08-11 10:49:02.952  6443  6580 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
08-11 10:49:02.962  6443  6443 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-11 10:49:02.972  4410  5161 D Icing   : Loaded CLD2 Version V2.0 - 20141016
,08-11 10:49:03.012  4410  5161 I Icing   : Indexing done 38360883C61536E4027A6B9191D49E9DF51837DC
,08-11 10:49:03.062  6645  6659 I GAv4    : Google Analytics 8.1.15 is starting up. To enable debug logging on a device run:
08-11 10:49:03.062  6645  6659 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
08-11 10:49:03.062  6645  6659 I GAv4    :   adb logcat -s GAv4
,08-11 10:49:03.082  6645  6659 W ResourcesManager: getTopLevelResources: /system/app/Drive/Drive.apk / 1.0 running in com.google.android.apps.docs rsrc of package null
,08-11 10:49:03.082   781  1743 V AlarmManager:  remove PendingIntent] PendingIntent{b07f0e4: PendingIntentRecord{21f394d com.google.android.apps.docs broadcastIntent}}
,08-11 10:49:03.082  6645  6659 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,08-11 10:49:03.092  6645  6659 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,08-11 10:49:03.092  6645  6665 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,08-11 10:49:03.142   781  1758 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,08-11 10:49:03.142   781  1743 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,08-11 10:49:03.142   781  1723 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,08-11 10:49:03.142   781   798 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,08-11 10:49:03.142   781  1452 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
08-11 10:49:03.142   781  1745 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,08-11 10:49:03.142   781  1278 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,08-11 10:49:03.152   781  2180 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,08-11 10:49:03.152   781  1744 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
08-11 10:49:03.152   781   796 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,08-11 10:49:03.152   781  1743 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,08-11 10:49:03.152   781   798 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,08-11 10:49:03.152   781  1452 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,08-11 10:49:03.152   781  1745 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,08-11 10:49:03.152   781  1739 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,08-11 10:49:03.152   781  2414 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,08-11 10:49:03.152   781  1744 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,08-11 10:49:03.152   781  1455 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
08-11 10:49:03.152   781   796 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,08-11 10:49:03.152   781  1758 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,08-11 10:49:03.162   781  1743 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,08-11 10:49:03.162   781  1723 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,08-11 10:49:03.172  5846  5846 I Finsky  : [1] com.google.android.finsky.services.DailyHygiene.d(741): Logging device features
,08-11 10:49:03.192  5846  5846 I Finsky  : [1] com.google.android.finsky.selfupdate.SelfUpdateCheckerScheduler.a(59): Cancelling accelerated self-Update check
,08-11 10:49:03.192  5846  5846 W InstanceID/Rpc: Found 10011
,08-11 10:49:03.212  2320  2320 D WearableService: callingUid 10011, callindPid: 2320
,08-11 10:49:03.212  2320  2376 D DeviceConnectionService: client connected with version: 8487000
,08-11 10:49:03.222  6645  6645 W System.err: remove failed: ENOTEMPTY (Directory not empty) : /data/user/0/com.google.android.apps.docs/cache/diskCache
,08-11 10:49:03.232  5846  5846 E Finsky  : [1] com.google.android.finsky.wear.bo.a(837): onConnectionFailed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,08-11 10:49:03.232  5846  5846 I Finsky  : [1] com.google.android.finsky.wear.WearSupportService.a(6394): Dropping command=hygiene due to Gms not connected
,08-11 10:49:03.232  6645  6645 W System.err: remove failed: ENOTEMPTY (Directory not empty) : /data/user/0/com.google.android.apps.docs/cache/docs_glide
,08-11 10:49:03.232   781  1743 I ActivityManager: Killing 4109:com.android.providers.calendar/u0a45 (adj 15): DHA:empty #37
,08-11 10:49:03.242  6645  6659 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.google.android.apps.docs/databases/ClientFlag.db
08-11 10:49:03.242  6645  6659 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.google.android.apps.docs/databases/ClientFlag.db-journal
08-11 10:49:03.242  6645  6659 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.google.android.apps.docs/databases/ClientFlag.db-shm
08-11 10:49:03.242  6645  6659 W System.err: remove failed: ENOENT (No such file or directory) : /data/user/0/com.google.android.apps.docs/databases/ClientFlag.db-wal
,08-11 10:49:03.252   781  1455 D ActivityManager: isAutoRunBlockedApp:: com.android.providers.calendar, Auto Run ON
,08-11 10:49:03.272   781  1366 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/recent_tasks/153_task.xml.bak
,08-11 10:49:03.302  6671  6671 E Zygote  : v2
08-11 10:49:03.302  6671  6671 I libpersona: KNOX_SDCARD checking this for 10098
08-11 10:49:03.302  6671  6671 I libpersona: KNOX_SDCARD not a persona
,08-11 10:49:03.302  6671  6671 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-11 10:49:03.302  6671  6671 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,08-11 10:49:03.302  6671  6671 E Zygote  : accessInfo : 0
,08-11 10:49:03.302  6671  6671 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.sec.android.automotive.drivelink 
,08-11 10:49:03.302   781  1742 I ActivityManager: Start proc 6671:com.sec.android.automotive.drivelink/u0a98 for broadcast-3 com.sec.android.automotive.drivelink/.framework.manager.update.UpdateManagerReceiver
,08-11 10:49:03.302   781  1742 I ActivityManager: Killing 5263:com.samsung.dcm:DCMService/5004 (adj 15): DHA:empty #37
,08-11 10:49:03.322  6671  6671 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-11 10:49:03.322  6671  6671 D ActivityThread: Added TimaKeyStore provider
,08-11 10:49:03.332   781   796 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{b49c611 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{ebc2c81 6671:com.sec.android.automotive.drivelink/u0a98}
,08-11 10:49:03.342   781  2414 D ActivityManager: isAutoRunBlockedApp:: com.samsung.dcm, Auto Run ON
,08-11 10:49:03.342  6671  6671 W ResourcesManager: getTopLevelResources: /system/app/DriveLink/DriveLink.apk / 1.0 running in com.sec.android.automotive.drivelink rsrc of package null
,08-11 10:49:03.362  6671  6671 W System  : ClassLoader referenced unknown path: /system/app/DriveLink/lib/arm
,08-11 10:49:03.392  6671  6671 W ResourcesManager: getTopLevelResources: /system/app/DriveLink/DriveLink.apk / 1.0 running in com.sec.android.automotive.drivelink rsrc of package null
,08-11 10:49:03.392  2320  2320 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,08-11 10:49:03.402   781  2180 V AlarmManager:  remove PendingIntent] PendingIntent{c7d1480: PendingIntentRecord{880eab9 com.sec.android.automotive.drivelink broadcastIntent}}
,08-11 10:49:03.412  6671  6687 I GMPM    : App measurement is starting up
,08-11 10:49:03.412  6671  6671 E [CarMode]: [DLApplication]-onCreate: Applicatino Started!
,08-11 10:49:03.422  6671  6687 E GMPM    : getGoogleAppId failed with status: 10
,08-11 10:49:03.432  6671  6687 E GMPM    : Uploading is not possible. App measurement disabled
,08-11 10:49:03.442  6671  6671 D SampleAppCoreManager: SampleAppCoreManager VACVersion '2.6.9.18467'
,08-11 10:49:03.442   781  2414 V AlarmManager:  remove PendingIntent] PendingIntent{a7e7efe: PendingIntentRecord{880eab9 com.sec.android.automotive.drivelink broadcastIntent}}
,08-11 10:49:03.442  6645  6660 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.gms-2/base.apk / 1.0 running in com.google.android.apps.docs rsrc of package null
,08-11 10:49:03.452  6671  6671 I VlingoAndroidCore: AppName: SamsungCCKProject, Core: 2.6.9.18467, SDK: 2.0.2440, EDM:18467
,08-11 10:49:03.492  6693  6693 E Zygote  : v2
08-11 10:49:03.492  6693  6693 I libpersona: KNOX_SDCARD checking this for 10032
08-11 10:49:03.492  6693  6693 I libpersona: KNOX_SDCARD not a persona
,08-11 10:49:03.492  6693  6693 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-11 10:49:03.492  6693  6693 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,08-11 10:49:03.492  6693  6693 E Zygote  : accessInfo : 0
,08-11 10:49:03.492  6693  6693 W SELinux : SELinux: seapp_context_lookup: seinfo=samsung, level=s0:c512,c768, pkgname=com.vlingo.midas 
,08-11 10:49:03.492   781  1743 I ActivityManager: Start proc 6693:com.vlingo.midas/u0a32 for content provider com.vlingo.midas/.provider.VlingoConfigProvider
,08-11 10:49:03.492   781  1324 D NetworkPolicy: isUidForegroundLocked: 10032, mScreenOn: false, uidstate: -1, mProxSensorScreenOff: false
,08-11 10:49:03.512  6645  6660 W linker  : /data/app/com.google.android.gms-2/lib/arm/libgmscore.so: unused DT entry: type 0x7ffffffd arg 0xa74
,08-11 10:49:03.512  6693  6693 D TimaKeyStoreProvider: TimaSignature is unavailable
08-11 10:49:03.512  6693  6693 D ActivityThread: Added TimaKeyStore provider
,08-11 10:49:03.522   781  1324 D NetworkPolicy: isUidForegroundLocked: 10032, mScreenOn: false, uidstate: 11, mProxSensorScreenOff: false
,08-11 10:49:03.532  6693  6693 W ResourcesManager: getTopLevelResources: /system/priv-app/S-Voice_Android_phone/S-Voice_Android_phone.apk / 1.0 running in com.vlingo.midas rsrc of package null
,08-11 10:49:03.532  6645  6660 W linker  : /data/app/com.google.android.gms-2/lib/arm/libconscrypt_gmscore_jni.so: unused DT entry: type 0x1d arg 0xe0
,08-11 10:49:03.532  6645  6660 W linker  : /data/app/com.google.android.gms-2/lib/arm/libconscrypt_gmscore_jni.so: unused DT entry: type 0x7ffffffd arg 0x1cb
,08-11 10:49:03.542  6645  6660 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 255 native methods...
,08-11 10:49:03.542  6693  6693 W System  : ClassLoader referenced unknown path: /system/priv-app/S-Voice_Android_phone/lib/arm
,08-11 10:49:03.572  6645  6660 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,08-11 10:49:03.612  6671  6671 D [CarMode]: [DLAppUiUpdater]-test local  en_US
,08-11 10:49:03.622  6671  6671 D [CarMode]: [DLApplication]-GooglePlayServices SUCCESS.
,08-11 10:49:03.622  6671  6671 E [CarMode]: [DLApplication]-PREF_CAR_APP_RUNNING is set to false
,08-11 10:49:03.642  6693  6693 I VlingoApplication: VlingoApplication appVersion ='11.7.0.1.41568', coreVersion = '2.6.12.18641', ro.csc.sales_code=XEO
,08-11 10:49:03.642  6671  6671 I UpdateManagerReceiver: Intent : android.intent.action.PACKAGE_ADDEDThu Aug 11 10:49:03 GMT+02:00 2016
,08-11 10:49:03.662  6707  6707 E Zygote  : v2
08-11 10:49:03.662  6707  6707 I libpersona: KNOX_SDCARD checking this for 1000
08-11 10:49:03.662  6707  6707 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-11 10:49:03.662  6707  6707 I libpersona: KNOX_SDCARD not a persona
08-11 10:49:03.662  6707  6707 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
08-11 10:49:03.662   781  1758 I ActivityManager: Start proc 6707:com.samsung.android.app.filterinstaller/1000 for broadcast-3 com.samsung.android.app.filterinstaller/.PackageIntentReceiver
08-11 10:49:03.662  6707  6707 E Zygote  : accessInfo : 0
08-11 10:49:03.662  6671  6671 D DialogFlow: initQueue()
,08-11 10:49:03.662   781  1758 I ActivityManager: Killing 5319:com.sec.android.app.music:service/u0a43 (adj 15): DHA:empty #37
,08-11 10:49:03.662   781  1758 I ActivityManager: Killing 5293:com.sec.face:FaceProvider/5004 (adj 15): DHA:empty #37
,08-11 10:49:03.682   781  1452 D ActivityManager: isAutoRunBlockedApp:: com.sec.android.app.music, Auto Run ON
,08-11 10:49:03.692   781  1744 D ActivityManager: isAutoRunBlockedApp:: com.sec.face, Auto Run ON
,08-11 10:49:03.692  6707  6707 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-11 10:49:03.692  6707  6707 D ActivityThread: Added TimaKeyStore provider
,08-11 10:49:03.702   781   796 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{b49c611 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{ae837f1 6707:com.samsung.android.app.filterinstaller/1000}
,08-11 10:49:03.702  6693  6693 I VlingoAndroidCore: AppName: SamsungTproject, Core: 2.6.12.18641, SDK: 2.0.2457, EDM:18641
,08-11 10:49:03.712  6707  6707 W ResourcesManager: getTopLevelResources: /system/app/FilterInstaller/FilterInstaller.apk / 1.0 running in com.samsung.android.app.filterinstaller rsrc of package null
,08-11 10:49:03.722  6707  6707 W System  : ClassLoader referenced unknown path: /system/app/FilterInstaller/lib/arm
,08-11 10:49:03.722  6707  6707 E FilterPackageIntentReceiver: This package is not a effect filter
,08-11 10:49:03.732  6723  6723 E Zygote  : v2
08-11 10:49:03.732  6723  6723 I libpersona: KNOX_SDCARD checking this for 1000
08-11 10:49:03.732  6723  6723 I libpersona: KNOX_SDCARD not a persona
,08-11 10:49:03.742  6723  6723 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-11 10:49:03.742   781   798 I ActivityManager: Start proc 6723:com.samsung.helphub/1000 for broadcast-3 com.samsung.helphub/.broadcast.HelpHubBroadcastReceiver
08-11 10:49:03.742  6723  6723 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,08-11 10:49:03.742   781   798 I ActivityManager: Killing 4767:com.google.android.gm/u0a113 (adj 15): DHA:empty #37
08-11 10:49:03.742  6723  6723 E Zygote  : accessInfo : 0
,08-11 10:49:03.762  6723  6723 D TimaKeyStoreProvider: TimaSignature is unavailable
08-11 10:49:03.762  6723  6723 D ActivityThread: Added TimaKeyStore provider
,08-11 10:49:03.762   781  1744 D ActivityManager: isAutoRunBlockedApp:: com.google.android.gm, Auto Run ON
,08-11 10:49:03.772   781   798 D PackageManager: setEnabledSetting : userId = 0 packageName = com.vlingo.midas cmp = com.vlingo.midas.settings.DrivingModeSettings newState = 2 callingPackage = 10032
,08-11 10:49:03.792   781  1742 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{b49c611 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{137622d 6723:com.samsung.helphub/1000}
,08-11 10:49:03.792  6723  6723 W ResourcesManager: getTopLevelResources: /system/app/InteractiveTutorial/InteractiveTutorial.apk / 1.0 running in com.samsung.helphub rsrc of package null
,08-11 10:49:03.802  6693  6693 D VlingoApplication: sac sec ensureCacheEmpty() car_iux_tts_cacheing_required set to false
,08-11 10:49:03.802  6693  6693 D VlingoApplication: sac sec ensureCacheEmpty() purged 0 historically cached TTS files
,08-11 10:49:03.802  6693  6693 D DialogFlow: initQueue()
,08-11 10:49:03.812  6723  6723 W System  : ClassLoader referenced unknown path: /system/app/InteractiveTutorial/lib/arm
,08-11 10:49:03.852  6735  6735 E Zygote  : v2
08-11 10:49:03.852  6735  6735 I libpersona: KNOX_SDCARD checking this for 1000
08-11 10:49:03.852  6735  6735 I libpersona: KNOX_SDCARD not a persona
08-11 10:49:03.852   781  1739 I ActivityManager: Start proc 6735:com.samsung.android.app.mirrorlink/1000 for broadcast-3 com.samsung.android.app.mirrorlink/com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener
,08-11 10:49:03.852  6735  6735 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-11 10:49:03.852  6735  6735 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,08-11 10:49:03.852   781  1739 I ActivityManager: Killing 5193:com.google.android.music:main/u0a125 (adj 15): DHA:empty #37
,08-11 10:49:03.852  6735  6735 E Zygote  : accessInfo : 0
,08-11 10:49:03.872  6735  6735 D TimaKeyStoreProvider: TimaSignature is unavailable
08-11 10:49:03.872  6735  6735 D ActivityThread: Added TimaKeyStore provider
,08-11 10:49:03.882   781  1758 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{b49c611 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{7d4f429 6735:com.samsung.android.app.mirrorlink/1000}
,08-11 10:49:03.882   781  1743 D ActivityManager: isAutoRunBlockedApp:: com.google.android.music, Auto Run ON
,08-11 10:49:03.892  6735  6735 W ResourcesManager: getTopLevelResources: /system/app/MirrorLink/MirrorLink.apk / 1.0 running in com.samsung.android.app.mirrorlink rsrc of package null
,08-11 10:49:03.902  6735  6735 W System  : ClassLoader referenced unknown path: /system/app/MirrorLink/lib/arm
,08-11 10:49:03.932  6735  6735 D AcmsPackageEventListener: action2:android.intent.action.PACKAGE_ADDED
,08-11 10:49:03.932  6735  6735 D AcmsPackageEventListener: pkgName:com.test.thalitest ,10004
,08-11 10:49:03.942   781  1744 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{b49c611 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{ec1a8c1 5279:com.google.android.apps.plus/u0a134}
,08-11 10:49:03.952   781  1758 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{b49c611 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{ec1a8c1 5279:com.google.android.apps.plus/u0a134}
,08-11 10:49:03.962   781   798 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{b49c611 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{ec1a8c1 5279:com.google.android.apps.plus/u0a134}
,08-11 10:49:04.012   781  1452 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.apps.plus cmp = com.google.android.apps.photos.phone.GetContentActivityAlias newState = 2 callingPackage = 10134
,08-11 10:49:04.012   781   798 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.apps.plus cmp = com.google.android.apps.photos.phone.SendContentActivityAlias newState = 2 callingPackage = 10134
,08-11 10:49:04.012   781  2414 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.apps.plus cmp = com.google.android.apps.photos.phone.SetWallpaperActivityAlias newState = 2 callingPackage = 10134
,08-11 10:49:04.022   781   796 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.apps.plus cmp = com.google.android.apps.plus.phone.VideoViewActivityAlias newState = 2 callingPackage = 10134
,08-11 10:49:04.022   781  1743 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.apps.plus cmp = com.google.android.apps.plus.phone.HostPhotoViewIntentActivityAlias newState = 2 callingPackage = 10134
,08-11 10:49:04.032   781  1278 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.apps.plus cmp = com.google.android.libraries.social.ingest.IngestActivity newState = 2 callingPackage = 10134
,08-11 10:49:04.032  6749  6749 E Zygote  : v2
08-11 10:49:04.032  6749  6749 I libpersona: KNOX_SDCARD checking this for 10165
08-11 10:49:04.032  6749  6749 I libpersona: KNOX_SDCARD not a persona
,08-11 10:49:04.032  6749  6749 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-11 10:49:04.032  6749  6749 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,08-11 10:49:04.032  6749  6749 E Zygote  : accessInfo : 0
,08-11 10:49:04.032  6749  6749 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.sec.kidsplat.installer 
,08-11 10:49:04.032   781  1739 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.apps.plus cmp = com.google.android.libraries.social.ingest.IngestService newState = 2 callingPackage = 10134
,08-11 10:49:04.032   781  2180 I ActivityManager: Start proc 6749:com.sec.kidsplat.installer/u0a165 for broadcast-3 com.sec.kidsplat.installer/.KidsModeInstallReceiver
,08-11 10:49:04.042   781  2180 D PackageManager: setEnabledSetting : userId = 0 packageName = com.google.android.apps.plus cmp = com.google.android.apps.photos.service.GooglePhotoDownsyncService newState = 2 callingPackage = 10134
,08-11 10:49:04.042   781  1723 I ActivityManager: Killing 5486:com.policydm/1000 (adj 15): DHA:empty #37
,08-11 10:49:04.052  6749  6749 D TimaKeyStoreProvider: TimaSignature is unavailable
08-11 10:49:04.052  6749  6749 D ActivityThread: Added TimaKeyStore provider
,08-11 10:49:04.062   781   796 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{b49c611 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{be7e4dc 6749:com.sec.kidsplat.installer/u0a165}
,08-11 10:49:04.072   781  1739 D ActivityManager: isAutoRunBlockedApp:: com.policydm, Auto Run ON
,08-11 10:49:04.072  6517  6517 D AASAservice: onDestroy()
,08-11 10:49:04.072  6749  6749 W ResourcesManager: getTopLevelResources: /system/app/SecKidsModeInstaller/SecKidsModeInstaller.apk / 1.0 running in com.sec.kidsplat.installer rsrc of package null
,08-11 10:49:04.082  6517  6517 I art     : System.exit called, status: 80
,08-11 10:49:04.082  6517  6517 I AndroidRuntime: VM exiting with result code 80, cleanup skipped.
,08-11 10:49:04.102   781  1278 I ActivityManager: Process com.samsung.aasaservice (pid 6517)(adj 0) has died(55,757)
,08-11 10:49:04.102   781  1278 D ActivityManager: isAutoRunBlockedApp:: com.samsung.aasaservice, Auto Run ON
,08-11 10:49:04.102  6749  6749 W System  : ClassLoader referenced unknown path: /system/app/SecKidsModeInstaller/lib/arm
,08-11 10:49:04.112   781  1723 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{b49c611 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{be7e4dc 6749:com.sec.kidsplat.installer/u0a165}
,08-11 10:49:04.122  6749  6749 D KidsPlatformStub: Package not found : com.sec.android.app.kidshome
,08-11 10:49:04.132   781  1455 I ActivityManager: Start proc 6762:com.sec.android.app.sbrowser/u0a142 for broadcast-3 com.sec.android.app.sbrowser/.preferences.ContentBlockerReceiver
,08-11 10:49:04.132  6762  6762 E Zygote  : v2
08-11 10:49:04.132  6762  6762 I libpersona: KNOX_SDCARD checking this for 10142
08-11 10:49:04.132  6762  6762 I libpersona: KNOX_SDCARD not a persona
08-11 10:49:04.132  6762  6762 E Zygote  : isSdpEnabledProcess - SDP enabled
08-11 10:49:04.132   781  1324 D NetworkPolicy: isUidForegroundLocked: 10142, mScreenOn: false, uidstate: -1, mProxSensorScreenOff: false
,08-11 10:49:04.132  6762  6762 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-11 10:49:04.132  6762  6762 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,08-11 10:49:04.132  6762  6762 E Zygote  : accessInfo : 64
08-11 10:49:04.132  6762  6762 E Zygote  : isSdpEnabledProcess - SDP enabled
08-11 10:49:04.132  6762  6762 E Zygote  : setSDPgroupsIntarray[pid]: 0 / [gid]: 10142 / [uid]: 10142
08-11 10:49:04.132  6762  6762 W SELinux : SELinux: seapp_context_lookup: seinfo=platform, level=s0:c512,c768, pkgname=com.sec.android.app.sbrowser 
,08-11 10:49:04.142   354   354 I Zygote  : Process 6517 exited cleanly (80)
,08-11 10:49:04.142   781  1324 D NetworkPolicy: isUidForegroundLocked: 10142, mScreenOn: false, uidstate: 16, mProxSensorScreenOff: false
,08-11 10:49:04.152  6762  6762 D TimaKeyStoreProvider: TimaSignature is unavailable
08-11 10:49:04.152  6762  6762 D ActivityThread: Added TimaKeyStore provider
,08-11 10:49:04.162   781  1745 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{b49c611 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{dd4cba 6762:com.sec.android.app.sbrowser/u0a142}
,08-11 10:49:04.172  6762  6762 W ResourcesManager: getTopLevelResources: /system/app/SBrowser_4_LATEST/SBrowser_4_LATEST.apk / 1.0 running in com.sec.android.app.sbrowser rsrc of package null
,08-11 10:49:04.182   781  1238 V AlarmManager: Expired Alarm result :4
,08-11 10:49:04.182  6762  6762 W System  : ClassLoader referenced unknown path: /system/app/SBrowser_4_LATEST/lib/arm
,08-11 10:49:04.182   781   781 V AlarmManager: ___SyncScheduler (v3) ACTIVATED___
,08-11 10:49:04.182   781   781 V AlarmManagerEXT: <AppSync3 Whitelist>
,08-11 10:49:04.192   781   781 V AlarmManagerEXT: (AppSync) ### 0 added ###
,08-11 10:49:04.192  1382  1382 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
08-11 10:49:04.192  1382  1382 I PERF    : received broadcast android.intent.action.TIME_TICK
08-11 10:49:04.192  1382  1382 D KeyguardUpdateMonitor: handleTimeUpdate
,08-11 10:49:04.202  1382  1382 D SecKeyguardClockView: onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,08-11 10:49:04.212  1382  1382 D SecKeyguardClockView: HomeTimezone(): 1
,08-11 10:49:04.212  6762  6762 W ResourcesManager: getTopLevelResources: /system/app/SBrowser_4_LATEST/SBrowser_4_LATEST.apk / 1.0 running in com.sec.android.app.sbrowser rsrc of package null
,08-11 10:49:04.212  1382  1382 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,08-11 10:49:04.212  1382  1382 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,08-11 10:49:04.212  1382  1382 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,08-11 10:49:04.212  1382  1382 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,08-11 10:49:04.212  6762  6762 D ManifestProvider: onCreate()
08-11 10:49:04.212  1382  1382 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,08-11 10:49:04.212  1382  1382 D DateView: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,08-11 10:49:04.212  1382  1382 D SecKeyguardStatusUtils: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,08-11 10:49:04.232  6762  6762 I SBrowserUtils: getSystemProperty of sales_code : XEO
08-11 10:49:04.232  6762  6762 I SBrowserUtils: getSystemProperty of country_code : Poland
08-11 10:49:04.232  6762  6762 I SBrowserUtils: getSystemProperty of country_code : Poland
,08-11 10:49:04.232  6762  6762 I SBrowserUtils: getSystemProperty of countryiso_code : PL
,08-11 10:49:04.242  6762  6762 V SBrowserContentProviderUtility: enableSyncClientProivder is called!
,08-11 10:49:04.252  6762  6762 D [MM]MHDataBaseProvider: onCreate()
,08-11 10:49:04.252  1382  1382 D SecKeyguardStatusUtils: regionalDateFormat = HH:mm isRTLlanguage = false returnDateFormat = E, d MMMM
,08-11 10:49:04.272  6762  6762 D ApplicationStatus: initialize application (com.sec.android.app.sbrowser.common.SBrowserMobileApplication@4b7826f)
,08-11 10:49:04.312   781  1278 I ActivityManager: Killing 5751:com.osp.app.signin/u0a44 (adj 15): DHA:empty #37
,08-11 10:49:04.312   781  1278 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{b49c611 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{3b6b080 2320:com.google.android.gms.persistent/u0a11}
,08-11 10:49:04.332  6595  6595 I Mms/MmsApp:  start initViewCache mms
,08-11 10:49:04.332   781  1745 D ActivityManager: isAutoRunBlockedApp:: com.osp.app.signin, Auto Run ON
,08-11 10:49:04.342  4410  6777 E IntentOperationSvc: Failed to instantiate Chimera operation impl, dropping operation
,08-11 10:49:04.342  4410  6778 D PkgBroadcastIntentOp: Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
,08-11 10:49:04.352   781  1744 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{b49c611 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{ac945c9 4410:com.google.android.gms/u0a11}
,08-11 10:49:04.352  4410  6778 D AuthPkgBcIntentOp: Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
,08-11 10:49:04.372  4410  6778 D MS_IntentHandler: Package broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
,08-11 10:49:04.372  4410  4410 D AsyncTaskServiceImpl: Submit a task: nzm
,08-11 10:49:04.382  4410  6778 D WearableController: Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
,08-11 10:49:04.392   781  2180 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{b49c611 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{3b6b080 2320:com.google.android.gms.persistent/u0a11}
,08-11 10:49:04.402   781  2180 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{b49c611 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{ac945c9 4410:com.google.android.gms/u0a11}
,08-11 10:49:04.412  4410  5192 D nzm     : Processing package: com.test.thalitest
,08-11 10:49:04.422  4410  4410 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.play.games-1/base.apk / 1.0 running in com.google.android.gms rsrc of package null
,08-11 10:49:04.482  4410  5192 D GassUtils: Found app info for package com.test.thalitest:19. Hash: 3a6332e64e629141c2a938dcd325767951fafbc70df540f2afadc7f283ec0db2
08-11 10:49:04.482  4410  5192 D nzm     : Found info for package com.test.thalitest in db.
,08-11 10:49:04.512   781  3528 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-11 10:49:04.552   781  1743 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{b49c611 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{96d88d8 5846:com.android.vending/u0a29}
,08-11 10:49:04.612   781  1742 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{b49c611 u0 android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{58b6a06 6239:com.sec.android.app.samsungapps/u0a39}
,08-11 10:49:04.612  5846  5846 I Finsky  : [1] com.google.android.finsky.utils.PermissionPolicies$PermissionPolicyService.onStartCommand(117): post-install permissions check for com.test.thalitest
,08-11 10:49:04.632   781  1452 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{fdc82d1 u0 com.samsung.android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{a9309f1 5895:com.sec.android.app.shealth/u0a34}
,08-11 10:49:04.632  5846  5846 I Finsky  : [1] com.google.android.finsky.utils.bn.run(1302): Package state data is missing for com.test.thalitest
,08-11 10:49:04.642   781  1723 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{fdc82d1 u0 com.samsung.android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{f5f49f6 1936:com.sec.android.app.shealth:remote/u0a34}
,08-11 10:49:04.642  5846  5846 E Finsky  : [1] com.google.android.finsky.wear.bo.a(837): onConnectionFailed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,08-11 10:49:04.642  5846  5846 I Finsky  : [1] com.google.android.finsky.wear.WearSupportService.a(6394): Dropping command=send_installed_apps due to Gms not connected
,08-11 10:49:04.672  6595  6595 D Mms/BubbleViewCache: fillCache bubble = 4
,08-11 10:49:04.682  6693  6721 W         : Unable to open '/system/framework/com.qti.location.sdk.jar': No such file or directory
08-11 10:49:04.682  6693  6721 W art     : Failed to open zip archive '/system/framework/com.qti.location.sdk.jar': I/O Error
,08-11 10:49:04.692   781  1742 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{fdc82d1 u0 com.samsung.android.intent.action.PACKAGE_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{f5f49f6 1936:com.sec.android.app.shealth:remote/u0a34}
,08-11 10:49:04.702  6693  6721 W         : Unable to open '/system/framework/com.qti.location.sdk.jar': No such file or directory
08-11 10:49:04.702  6693  6721 W art     : Failed to open zip archive '/system/framework/com.qti.location.sdk.jar': I/O Error
08-11 10:49:04.702  6693  6721 I System.out: INFO:Resource not found:/Common.properties Using default values
,08-11 10:49:04.712  6693  6721 W         : Unable to open '/system/framework/com.qti.location.sdk.jar': No such file or directory
,08-11 10:49:04.712  6693  6721 W art     : Failed to open zip archive '/system/framework/com.qti.location.sdk.jar': I/O Error
,08-11 10:49:04.712   781   796 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{f659136 u0 com.google.android.gms.gcm.ACTION_SCHEDULE qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{3b6b080 2320:com.google.android.gms.persistent/u0a11}
,08-11 10:49:04.732   781  1455 V AlarmManager:  remove PendingIntent] PendingIntent{6417837: PendingIntentRecord{7e0a771 com.google.android.gms broadcastIntent}}
,08-11 10:49:04.732   781   781 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{e0b21a4 u0 null qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{96d88d8 5846:com.android.vending/u0a29}
,08-11 10:49:04.752  5846  6786 I Finsky  : [839] com.google.android.finsky.receivers.FlushLogsReceiver$FlushLogsService.onHandleIntent(163): Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,08-11 10:49:04.752   781  2180 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{851910e u0 com.google.android.gms.actions.HANDLE_PACKAGE_INSTALLED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{3b6b080 2320:com.google.android.gms.persistent/u0a11}
,08-11 10:49:04.752   781   781 I BackgroundCompactionService: onStart. jobID=801
,08-11 10:49:04.752  5846  5866 I PlayCommon: [809] com.google.android.play.a.al.e(730): Preparing logs for uploading
,08-11 10:49:04.762   781   781 I BackgroundCompactionService: onStart done. jobID=801
,08-11 10:49:04.762   781  6787 I BackgroundCompactionService: Execute BGCompaction (type1). (0 times)
,08-11 10:49:04.762   781  6787 I BackgroundCompactionService: compact_memory command done
,08-11 10:49:04.842  5846  6789 I PlayCommon: [840] com.google.android.play.a.w.a(27553): Starting to flush logs
,08-11 10:49:04.852  5846  6789 I PlayCommon: [840] com.google.android.play.a.w.a(27564): Log flushed by 0 successful uploads
,08-11 10:49:04.852  2320  2320 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,08-11 10:49:04.872  5846  5866 I PlayCommon: [809] com.google.android.play.a.al.a(870): Connecting to server: https://play.googleapis.com/play/log?format=raw&proto_v2=true
,08-11 10:49:04.872  5846  5866 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-11 10:49:04.872  5846  5866 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-11 10:49:04.892   305  1199 D EnterpriseController: netId is 0
08-11 10:49:04.892   305  1199 D Netd    : getNetworkForDns: using netid 502 for uid 10029
,08-11 10:49:05.122  4410  6783 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.play.games-1/base.apk / 1.0 running in com.google.android.gms rsrc of package null
,08-11 10:49:05.142  5846  5866 I PlayCommon: [809] com.google.android.play.a.al.a(945): Successfully uploaded logs.
,08-11 10:49:05.152  5846  5866 I PlayCommon: [809] com.google.android.play.a.al.e(730): Preparing logs for uploading
08-11 10:49:05.152  5846  5866 I PlayCommon: [809] com.google.android.play.a.al.e(732): No file ready to send
,08-11 10:49:05.622  4410  5192 I Icing   : Indexing 8C917DD38D8401D75FF5D6D4F62E2D76CBAF051C from com.google.android.gms
,08-11 10:49:05.692  4410  5192 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.google.android.gms rsrc of package null
,08-11 10:49:05.692  4410  5192 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.google.android.gms rsrc of package null
,08-11 10:49:05.702  4410  5192 I Icing   : Indexing done 8C917DD38D8401D75FF5D6D4F62E2D76CBAF051C
,08-11 10:49:06.732   781  3500 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,08-11 10:49:09.512   781  3528 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-11 10:49:10.262   781  1015 D PackageManager: [MSG] WRITE_PACKAGE_RESTRICTIONS
,08-11 10:49:10.282   781  1015 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/users/0/package-restrictions.xml.bak
,08-11 10:49:11.292  3768  3768 D FactoryTest: User mode
,08-11 10:49:11.292  3768  3768 D MTPRx   : DRIVER_TIME_OUT 60s lapsed
08-11 10:49:11.292  3768  3768 D MTPRx   : still no open session command from host, so toast
,08-11 10:49:11.292   781  1452 W ResourcesManager: getTopLevelResources: /system/priv-app/MtpApplication/MtpApplication.apk / 1.0 running in null rsrc of package null
,08-11 10:49:11.302   781  1452 D ActivityManager: mDVFSHelper.acquire()
,08-11 10:49:11.302   781  1452 V WindowManager: addAppToken: AppWindowToken{812b3e6 token=Token{c32c241 ActivityRecord{3c8f528 u0 com.samsung.android.MtpApplication/.USBConnection t154}}} to stack=1 task=154 at 0
,08-11 10:49:11.312   781  1452 D ActivityManager:  Launching com.samsung.android.MtpApplication, updated priority
,08-11 10:49:11.312   781   878 V MARsPolicyManager: updatePackagesScore PackageInfo name -- com.samsung.android.MtpApplication
,08-11 10:49:11.332   781  1452 D InputDispatcher: Focused application set to: xxxx
,08-11 10:49:11.332   781  1452 D InputDispatcher: Focus left window: 6443
,08-11 10:49:11.332   781   923 D PointerIcon: setMouseIconStyle1 pointerType: 1001 iconType:101 flag:0 pid:781 uid:1000
08-11 10:49:11.332   781   923 D PointerIcon: setMouseCustomIcon IconType is same.101
08-11 10:49:11.332   781   923 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001 iconType:1 flag:0 pid:781 uid:1000
08-11 10:49:11.332   781   923 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
,08-11 10:49:11.342  3768  3768 E MTPRx   : started activity for popup
,08-11 10:49:11.342  3768  3768 W ResourcesManager: getTopLevelResources: /system/priv-app/MtpApplication/MtpApplication.apk / 1.0 running in com.samsung.android.MtpApplication rsrc of package null
,08-11 10:49:11.342  3768  3768 W ResourcesManager: getTopLevelResources: /system/priv-app/MtpApplication/MtpApplication.apk / 1.0 running in com.samsung.android.MtpApplication rsrc of package null
,08-11 10:49:11.352  3768  3768 D MTPUSBConnection: onCreate in USBConnection
08-11 10:49:11.352  3768  3768 V MTPUSBConnection: Registering broadcast receiver.
,08-11 10:49:11.352  3768  3768 E MTPUSBConnection: AlertDialog Mode is : TIMEOUT
,08-11 10:49:11.362   781  1278 D SecContentProvider2: query(), uri = 14 selection = getSealedState
,08-11 10:49:11.362   781  3500 D ConnectivityService: returning getNetworkInfo for network type 1 : [type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]
,08-11 10:49:11.402  3768  3768 D TAG     : dev.kiessupport is : TRUE
,08-11 10:49:11.432  3768  3768 D SecWifiDisplayUtil: Metadata value : none
,08-11 10:49:11.432  3768  3768 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{ffc0fa3 V.E...... R.....I. 0,0-0,0}
,08-11 10:49:11.432  3768  6811 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,08-11 10:49:11.432   781   796 D ISSUE_DEBUG: InputChannelName : 9ca59be com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection
,08-11 10:49:11.432   781   796 D InputDispatcher: Focus entered window: 3768
,08-11 10:49:11.432   781   880 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=Window{9ca59be u0 d0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}
,08-11 10:49:11.442   781   923 D PointerIcon: setMouseIconStyle1 pointerType: 1001 iconType:101 flag:0 pid:781 uid:1000
08-11 10:49:11.442   781   923 D PointerIcon: setMouseCustomIcon IconType is same.101
08-11 10:49:11.442   781   923 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001 iconType:1 flag:0 pid:781 uid:1000
08-11 10:49:11.442   781   923 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
,08-11 10:49:11.442  1382  1382 D PhoneStatusBar: setSystemUiVisibility vis=8000 mask=ffffffff oldVal=8600 newVal=8000 diff=600
,08-11 10:49:11.442  3768  3768 D ViewRootImpl: #1 mView = com.android.internal.policy.PhoneWindow$DecorView{af1d01b I.E...... R.....I. 0,0-0,0}
,08-11 10:49:11.442   781   796 D ISSUE_DEBUG: InputChannelName : 813316c com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection
,08-11 10:49:11.452   781  1455 D ActivityManager: post active user change for 0 fullscreen false isFloatingActivity() false isHomeActivity() false
08-11 10:49:11.452   781  1455 D KnoxTimeoutHandler: postActiveUserChange [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
,08-11 10:49:11.452   781   781 D KnoxTimeoutHandler: handleActiveUserChange [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
08-11 10:49:11.452   781   781 I KnoxTimeoutHandler: Shared devices show user statefalse
08-11 10:49:11.452   781   781 I KnoxTimeoutHandler: Target Activity is not fullscreen. We will not show this activity0
,08-11 10:49:11.452   781   878 I ActivityManager: Killing 4856:com.google.android.talk/u0a116 (adj 15): DHA:empty #37
,08-11 10:49:11.462   781  1015 D PackageManager: [MSG] MCS_UNBIND
,08-11 10:49:11.472   781  1723 I ActivityManager: Killing 5815:com.samsung.android.app.FileShareServer/5005 (adj 15): DHA:empty #37
,08-11 10:49:11.472   781  1452 D ActivityManager: isAutoRunBlockedApp:: com.google.android.talk, Auto Run ON
,08-11 10:49:11.482   293   293 I SurfaceFlinger: id=18 createSurf (145x145),1 flag=4, VSBConnecti
,08-11 10:49:11.492   781  2414 D ActivityManager: isAutoRunBlockedApp:: com.samsung.android.app.FileShareServer, Auto Run ON
,08-11 10:49:11.502  3768  6811 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build:  (Ia10634f51b)
08-11 10:49:11.502  3768  6811 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.29.00.00
08-11 10:49:11.502  3768  6811 I Adreno-EGL: Build Date: 01/28/16 Thu
08-11 10:49:11.502  3768  6811 I Adreno-EGL: Local Branch: ss
08-11 10:49:11.502  3768  6811 I Adreno-EGL: Remote Branch: 
08-11 10:49:11.502  3768  6811 I Adreno-EGL: Local Patches: 
08-11 10:49:11.502  3768  6811 I Adreno-EGL: Reconstruct Branch: 
,08-11 10:49:11.502  3768  6811 D libEGL  : eglInitialize EGLDisplay = 0x9f0137c4
08-11 10:49:11.502  3768  6811 I OpenGLRenderer: Initialized EGL, version 1.4
,08-11 10:49:11.542   293   293 I SurfaceFlinger: id=19 createSurf (193x193),1 flag=4, VSBConnecti
,08-11 10:49:11.552  3768  3768 V ActivityThread: updateVisibility : ActivityRecord{5ff1ef6 token=android.os.BinderProxy@62882a0 {com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}} show : true
,08-11 10:49:11.562  3768  3768 W DisplayListCanvas: DisplayListCanvas is started on unbinded RenderNode (without mOwningView)
,08-11 10:49:11.632   781  1278 V WindowStateAnimator: Finishing drawing window Window{9ca59be u0 d0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}: mDrawState=DRAW_PENDING
,08-11 10:49:11.632  3768  3768 W DisplayListCanvas: DisplayListCanvas is started on unbinded RenderNode (without mOwningView)
,08-11 10:49:11.632   781  2180 V WindowStateAnimator: Finishing drawing window Window{813316c u0 d0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}: mDrawState=DRAW_PENDING
,08-11 10:49:11.632  3768  3768 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 0 - 0, 0) vi=Rect(0, 0 - 0, 0) or=1
08-11 10:49:11.632  3768  3768 D ViewRootImpl: MSG_RESIZED_REPORT: ci=Rect(0, 0 - 0, 0) vi=Rect(0, 0 - 0, 0) or=1
,08-11 10:49:11.642   781   923 D KnoxTimeoutHandler: notifyActivityDrawn [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
,08-11 10:49:11.642   781   781 D KnoxTimeoutHandler: activityDrawn [MsgParam] userId: 0 fullscreen is false showWhenlocked is false
08-11 10:49:11.642   781   781 I KnoxTimeoutHandler: SD activityfalse
,08-11 10:49:11.642   781   923 I ActivityManager: Displayed com.samsung.android.MtpApplication/.USBConnection: +313ms (total +334ms)
,08-11 10:49:11.642   781   923 D ActivityManager: mDVFSHelper.release()
08-11 10:49:11.642   781   923 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{3c8f528 u0 com.samsung.android.MtpApplication/.USBConnection t154} time:108086
,08-11 10:49:11.642   781  1745 V WindowStateAnimator: Finishing drawing window Window{9ca59be u0 d0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}: mDrawState=HAS_DRAWN
,08-11 10:49:11.642   781  1758 V WindowStateAnimator: Finishing drawing window Window{813316c u0 d0 com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.USBConnection}: mDrawState=HAS_DRAWN
,08-11 10:49:11.642   293   293 D libEGL  : eglInitialize EGLDisplay = 0xbef49364
08-11 10:49:11.642   293   293 D libEGL  : eglInitialize EGLDisplay = 0xbef49364
08-11 10:49:11.642  3768  3768 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@62882a0 time:108089
,08-11 10:49:11.662   293   293 D libEGL  : eglInitialize EGLDisplay = 0xbef49364
,08-11 10:49:12.342   781  3503 W ResourcesManager: getTopLevelResources: /system/priv-app/MtpApplication/MtpApplication.apk / 1.0 running in null rsrc of package null
,08-11 10:49:12.452  1457  1457 D Recents : onTaskStackChanged
,08-11 10:49:12.462  1457  1457 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.android.systemui rsrc of package null
,08-11 10:49:12.572   781  1238 V AlarmManager: Expired Alarm result :4
,08-11 10:49:12.592   781  1324 D NetworkPolicy: isUidForegroundLocked: 10011, mScreenOn: false, uidstate: 6, mProxSensorScreenOff: false
,08-11 10:49:12.592   781  1324 D NetworkPolicy: isUidForegroundLocked: 10011, mScreenOn: false, uidstate: 6, mProxSensorScreenOff: false
,08-11 10:49:12.592   781  1455 V AlarmManager:  remove PendingIntent] PendingIntent{dce53ca: PendingIntentRecord{3e08d7a com.google.android.gms broadcastIntent}}
,08-11 10:49:12.632   781  1743 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-11 10:49:12.632   781  1743 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4353, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303564, invalid charger:0, maxChargingCurrent:0
,08-11 10:49:12.632   781  1743 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, batterySWSelfDischarging:false, current_now:450
08-11 10:49:12.632   781  1743 D BatteryService: stay LED for charging
08-11 10:49:12.632   781   781 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-11 10:49:12.632   781   781 I MotionRecognitionService: Plugged
,08-11 10:49:12.632   781   781 D MotionRecognitionService:   cableConnection= 1
08-11 10:49:12.632   781   781 D MotionRecognitionService: setPowerConnected | current backoffstate  = 1024 , state =1024
08-11 10:49:12.632   781   781 D MotionRecognitionService: skip setTransmitPower. 
,08-11 10:49:12.642  1382  1382 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-11 10:49:12.642  1382  1382 I PERF    : received broadcast android.intent.action.BATTERY_CHANGED
08-11 10:49:12.642  1382  1382 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-11 10:49:12.652  2312  2312 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-11 10:49:12.652  2312  2810 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-11 10:49:12.662  1382  1382 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-11 10:49:12.662  1382  1382 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
08-11 10:49:12.662  1382  1382 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-11 10:49:12.732   781  3500 D SSRM:n  : SIOP:: AP = 460, PST = 443, CUR = 450, LCD = 0
,08-11 10:49:13.472  6443  6594 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-11 10:49:13.472  6443  6594 I jxcore-log: 
,08-11 10:49:13.472  6443  6594 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-11 10:49:13.472  6443  6594 I jxcore-log: 
,08-11 10:49:13.482  6443  6594 D BluetoothAdapter: STATE_ON
,08-11 10:49:13.482  6443  6594 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-11 10:49:13.482  6443  6594 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-11 10:49:13.482  6443  6594 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-11 10:49:13.482  6443  6594 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-11 10:49:13.482  6443  6594 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-11 10:49:13.482  6443  6594 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-11 10:49:13.482  6443  6594 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-11 10:49:13.482  6443  6594 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-11 10:49:13.482  6443  6594 D BluetoothAdapter: STATE_ON
,08-11 10:49:13.482  6443  6594 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-11 10:49:13.482  6443  6594 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-11 10:49:13.482  6443  6594 I jxcore-log: 
,08-11 10:49:13.482  6443  6594 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native,
08-11 10:49:13.482  6443  6594 I jxcore-log: 
,08-11 10:49:13.832  6443  6594 E JX-Cordova: JavaCall recevied a call for unknown method executeNativeTests
08-11 10:49:13.832  6443  6594 I jxcore-log: Failed to execute UT.
08-11 10:49:13.832  6443  6594 I jxcore-log: 
08-11 10:49:13.832  6443  6594 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****
08-11 10:49:13.832  6443  6594 I jxcore-log: 
,08-11 10:49:13.832  6443  6594 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-11 10:49:13.832  6443  6594 I jxcore-log: 
,08-11 10:49:13.842  6443  6443 I chromium: [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74)
,08-11 10:49:14.512   781  3528 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.absolute.android.persistservice.a.run:1244 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-11 10:49:14.782  2329  2329 E audit   : type=1400 msg=audit(1470905354.782:291): avc:  denied  { execmod } for  pid=6833 comm="app_process" path="/system/lib/lib_SoundAlive_ver118t.so" dev="mmcblk0p23" ino=1786 scontext=u:r:shell:s0 tcontext=u:object_r:system_file:s0 tclass=file permissive=0
,08-11 10:49:14.782  2329  2329 E audit   :  SEPF_SECMOBILE_6.0.1_0011
08-11 10:49:14.782  2329  2329 E audit   : type=1300 msg=audit(1470905354.782:291): arch=40000028 syscall=125 per=800008 success=no exit=-13 a0=b3feb000 a1=51000 a2=5 a3=4 items=0 ppid=3644 ppcomm=adbd pid=6833 auid=4294967295 uid=2000 gid=2000 euid=2000 suid=2000 fsuid=2000 egid=2000 sgid=2000 fsgid=2000 tty=pts1 ses=4294967295 comm="app_process" exe="/system/bin/app_process32" subj=u:r:shell:s0 key=(null)
08-11 10:49:14.782  2329  2329 E audit   : type=1327 msg=audit(1470905354.782:291): proctitle=6170705F70726F63657373002F73797374656D2F62696E00636F6D2E616E64726F69642E636F6D6D616E64732E706D2E506D00756E696E7374616C6C00636F6D2E746573742E7468616C6974657374
08-11 10:49:14.782  2329  2329 E audit   : type=1320 msg=audit(1470905354.782:291): 
,08-11 10:49:14.852  2329  2329 E audit   : type=1400 msg=audit(1470905354.842:292): avc:  denied  { execmod } for  pid=6833 comm="app_process" path="/system/lib/lib_SoundAlive_ver118t.so" dev="mmcblk0p23" ino=1786 scontext=u:r:shell:s0 tcontext=u:object_r:system_file:s0 tclass=file permissive=0
08-11 10:49:14.852  2329  2329 E audit   :  SEPF_SECMOBILE_6.0.1_0011
08-11 10:49:14.852  2329  2329 E audit   : type=1300 msg=audit(1470905354.842:292): arch=40000028 syscall=125 per=800008 success=no exit=-13 a0=b3fab000 a1=51000 a2=5 a3=4 items=0 ppid=3644 ppcomm=adbd pid=6833 auid=4294967295 uid=2000 gid=2000 euid=2000 suid=2000 fsuid=2000 egid=2000 sgid=2000 fsgid=2000 tty=pts1 ses=4294967295 comm="app_process" exe="/system/bin/app_process32" subj=u:r:shell:s0 key=(null)
08-11 10:49:14.852  2329  2329 E audit   : type=1327 msg=audit(1470905354.842:292): proctitle=6170705F70726F63657373002F73797374656D2F62696E00636F6D2E616E64726F69642E636F6D6D616E64732E706D2E506D00756E696E7374616C6C00636F6D2E746573742E7468616C6974657374
08-11 10:49:14.852  2329  2329 E audit   : type=1320 msg=audit(1470905354.842:292): 
,08-11 10:49:14.892  2329  2329 E audit   : type=1400 msg=audit(1470905354.892:293): avc:  denied  { execmod } for  pid=6833 comm="app_process" path="/system/lib/lib_SoundAlive_ver118t.so" dev="mmcblk0p23" ino=1786 scontext=u:r:shell:s0 tcontext=u:object_r:system_file:s0 tclass=file permissive=0
08-11 10:49:14.892  2329  2329 E audit   :  SEPF_SECMOBILE_6.0.1_0011
08-11 10:49:14.892  2329  2329 E audit   : type=1300 msg=audit(1470905354.892:293): arch=40000028 syscall=125 per=800008 success=no exit=-13 a0=b3fab000 a1=51000 a2=5 a3=4 items=0 ppid=3644 ppcomm=adbd pid=6833 auid=4294967295 uid=2000 gid=2000 euid=2000 suid=2000 fsuid=2000 egid=2000 sgid=2000 fsgid=2000 tty=pts1 ses=4294967295 comm="app_process" exe="/system/bin/app_process32" subj=u:r:shell:s0 key=(null)
08-11 10:49:14.892  2329  2329 E audit   : type=1327 msg=audit(1470905354.892:293): proctitle=6170705F70726F63657373002F73797374656D2F62696E00636F6D2E616E64726F69642E636F6D6D616E64732E706D2E506D00756E696E7374616C6C00636F6D2E746573742E7468616C6974657374
08-11 10:49:14.892  2329  2329 E audit   : type=1320 msg=audit(1470905354.892:293): 
,08-11 10:49:14.892  6833  6833 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,08-11 10:49:14.902  6833  6833 D AndroidRuntime: CheckJNI is OFF
,08-11 10:49:14.902  6833  6833 D AndroidRuntime: readGMSProperty: start
,08-11 10:49:14.902  6833  6833 D AndroidRuntime: readGMSProperty: already setted!!
08-11 10:49:14.902  6833  6833 D AndroidRuntime: propertySet: couldn't set property (it is from app)
08-11 10:49:14.902  6833  6833 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
08-11 10:49:14.902  6833  6833 D AndroidRuntime: readGMSProperty: end
08-11 10:49:14.902  6833  6833 D AndroidRuntime: addProductProperty: start
,08-11 10:49:14.912  6833  6833 W art     : 6f853000-705d0000 rw-p 00000000 b3:1a 130841     /data/dalvik-cache/arm/system@framework@boot.art
,08-11 10:49:14.912  6833  6833 W art     : af14e000-b2074000 r--p 00000000 b3:17 579        /system/framework/arm/boot.oat
08-11 10:49:14.912  6833  6833 W art     : b2074000-b42e3000 r-xp 02f26000 b3:17 579        /system/framework/arm/boot.oat
08-11 10:49:14.912  6833  6833 W art     : b42e3000-b42e4000 rw-p 05195000 b3:17 579        /system/framework/arm/boot.oat
08-11 10:49:14.912  6833  6833 W art     : b42e4000-b4732000 r-xp 00000000 b3:17 332        /system/lib/libart.so
,08-11 10:49:14.912  6833  6833 W art     : b4732000-b4733000 ---p 00000000 00:00 0 
08-11 10:49:14.912  6833  6833 W art     : b4733000-b473d000 r--p 0044e000 b3:17 332        /system/lib/libart.so
08-11 10:49:14.912  6833  6833 W art     : b473d000-b473e000 rw-p 00458000 b3:17 332        /system/lib/libart.so
08-11 10:49:14.912  6833  6833 W art     : b473e000-b4740000 rw-p 00000000 00:00 0 
08-11 10:49:14.912  6833  6833 W art     : b4740000-b4800000 rw-p 00000000 00:00 0          [anon:libc_malloc]
,08-11 10:49:14.912  6833  6833 W art     : b4811000-b483a000 r--p 00d7d000 b3:1a 130841     /data/dalvik-cache/arm/system@framework@boot.art
08-11 10:49:14.912  6833  6833 W art     : b483a000-b483d000 r-xp 00000000 b3:17 2415       /system/lib/libsigchain.so
08-11 10:49:14.912  6833  6833 W art     : b483d000-b483e000 r--p 00002000 b3:17 2415       /system/lib/libsigchain.so
08-11 10:49:14.912  6833  6833 W art     : b483e000-b483f000 rw-p 00003000 b3:17 2415       /system/lib/libsigchain.so
08-11 10:49:14.912  6833  6833 W art     : b483f000-b4840000 r--p 00000000 00:00 0 
,08-11 10:49:14.912  6833  6833 W art     : b4840000-b4880000 rw-p 00000000 00:00 0          [anon:libc_malloc]
08-11 10:49:14.912  6833  6833 W art     : b4880000-b48a0000 r--s 00000000 00:0b 8195       /dev/__properties__
08-11 10:49:14.912  6833  6833 W art     : b48a0000-b52b1000 r-xp 00000000 b3:17 2805       /system/lib/libLLVM.so
08-11 10:49:14.912  6833  6833 W art     : b52b1000-b52b2000 ---p 00000000 00:00 0 
08-11 10:49:14.912  6833  6833 W art     : b52b2000-b52fb000 r--p 00a11000 b3:17 2805       /system/lib/libLLVM.so
,08-11 10:49:14.912  6833  6833 W art     : b52fb000-b52fc000 rw-p 00a5a000 b3:17 2805       /system/lib/libLLVM.so
08-11 10:49:14.912  6833  6833 W art     : b52fc000-b5304000 rw-p 00000000 00:00 0 
08-11 10:49:14.912  6833  6833 W art     : b5304000-b5305000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-11 10:49:14.912  6833  6833 W art     : b5305000-b533a000 r-xp 00000000 b3:17 726        /system/lib/libbcinfo.so
08-11 10:49:14.912  6833  6833 W art     : b533a000-b533b000 ---p 00000000 00:00 0 
,08-11 10:49:14.912  6833  6833 W art     : b533b000-b533c000 r--p 00035000 b3:17 726        /system/lib/libbcinfo.so
08-11 10:49:14.912  6833  6833 W art     : b533c000-b533d000 rw-p 00036000 b3:17 726        /system/lib/libbcinfo.so
08-11 10:49:14.912  6833  6833 W art     : b533d000-b5395000 r-xp 00000000 b3:17 2785       /system/lib/libbcc.so
08-11 10:49:14.912  6833  6833 W art     : b5395000-b5396000 ---p 00000000 00:00 0 
08-11 10:49:14.912  6833  6833 W art     : b5396000-b5397000 r--p 00058000 b3:17 2785       /system/lib/libbcc.so
,08-11 10:49:14.912  6833  6833 W art     : b5397000-b5398000 rw-p 00059000 b3:17 2785       /system/lib/libbcc.so
08-11 10:49:14.912  6833  6833 W art     : b5399000-b539f000 r-xp 00000000 b3:17 32         /system/lib/lib_SamsungVAD_v01009.so
08-11 10:49:14.922  6833  6833 W art     : b539f000-b53a0000 r--p 00005000 b3:17 32         /system/lib/lib_SamsungVAD_v01009.so
08-11 10:49:14.922  6833  6833 W art     : b53a0000-b53a1000 rw-p 00006000 b3:17 32         /system/lib/lib_SamsungVAD_v01009.so
08-11 10:49:14.922  6833  6833 W art     : b53a1000-b53a3000 rw-p 00000000 00:00 0 
,08-11 10:49:14.922  6833  6833 W art     : b53a4000-b53ae000 r-xp 00000000 b3:17 1088       /system/lib/libcommon_time_client.so
08-11 10:49:14.922  6833  6833 W art     : b53ae000-b53b1000 r--p 00009000 b3:17 1088       /system/lib/libcommon_time_client.so
08-11 10:49:14.922  6833  6833 W art     : b53b1000-b53b2000 rw-p 0000c000 b3:17 1088       /system/lib/libcommon_time_client.so
08-11 10:49:14.922  6833  6833 W art     : b53b3000-b53ca000 r-xp 00000000 b3:17 2932       /system/lib/libprotobuf-cpp-lite.so
,08-11 10:49:14.922  6833  6833 W art     : b53ca000-b53cb000 ---p 00000000 00:00 0 
08-11 10:49:14.922  6833  6833 W art     : b53cb000-b53cc000 r--p 00017000 b3:17 2932       /system/lib/libprotobuf-cpp-lite.so
08-11 10:49:14.922  6833  6833 W art     : b53cc000-b53cd000 rw-p 00018000 b3:17 2932       /system/lib/libprotobuf-cpp-lite.so
08-11 10:49:14.922  6833  6833 W art     : b53ce000-b53d8000 r-xp 00000000 b3:17 2671       /system/lib/libsec_km.so
,08-11 10:49:14.922  6833  6833 W art     : b53d8000-b53d9000 r--p 00009000 b3:17 2671       /system/lib/libsec_km.so
08-11 10:49:14.922  6833  6833 W art     : b53d9000-b53da000 rw-p 0000a000 b3:17 2671       /system/lib/libsec_km.so
08-11 10:49:14.922  6833  6833 W art     : b53da000-b53de000 r-xp 00000000 b3:17 2888       /system/lib/libSEF4MP4.so
08-11 10:49:14.922  6833  6833 W art     : b53de000-b53df000 r--p 00003000 b3:17 2888       /system/lib/libSEF4MP4.so
,08-11 10:49:14.922  6833  6833 W art     : b53df000-b53e0000 rw-p 00004000 b3:17 2888       /system/lib/libSEF4MP4.so
08-11 10:49:14.922  6833  6833 W art     : b53e0000-b53f6000 r-xp 00000000 b3:17 2121       /system/lib/libSEF.so
08-11 10:49:14.922  6833  6833 W art     : b53f6000-b53f7000 r--p 00015000 b3:17 2121       /system/lib/libSEF.so
08-11 10:49:14.922  6833  6833 W art     : b53f7000-b53f8000 rw-p 00016000 b3:17 2121       /system/lib/libSEF.so
,08-11 10:49:14.922  6833  6833 W art     : b53f8000-b5405000 r-xp 00000000 b3:17 1082       /system/lib/libsfextcp.so
08-11 10:49:14.922  6833  6833 W art     : b5405000-b5406000 r--p 0000c000 b3:17 1082       /system/lib/libsfextcp.so
,08-11 10:49:14.922  6833  6833 W art     : b5406000-b5407000 rw-p 0000d000 b3:17 1082       /system/lib/libsfextcp.so,
08-11 10:49:14.922  6833  6833 W art     : b5407000-b5467000 r-xp 00000000 b3:17 405        /system/lib/libsavsff.so
08-11 10:49:14.922  6833  6833 W art     : b5467000-b546a000 rw-p 0005f000 b3:17 405        /system/lib/libsavsff.so
08-11 10:49:14.922  6833  6833 W art     : b546a000-b546e000 rw-p 00000000 00:00 0 
08-11 10:49:14.922  6833  6833 W art     : b546e000-b54cf000 r-xp 00000000 b3:17 385        /system/lib/libsavscmn.so
08-11 10:49:14.922  6833  6833 W art     : b54cf000-b54d0000 rw-p 00061000 b3:17 385        /system/lib/libsavscmn.so
08-11 10:49:14.922  6833  6833 W art     : b54d0000-b551f000 r-xp 00000000 b3:17 2399       /system/lib/libomafldrm.so
08-11 10:49:14.922  6833  6833 W art     : b551f000-b5521000 r--p 0004e000 b3:17 2399       /system/lib/libomafldrm.so
08-11 10:49:14.922  6833  6833 W art     : b5521000-b5522000 rw-p 00050000 b3:17 2399       /system/lib/libomafldrm.so
,08-11 10:49:14.922  6833  6833 W art     : b5522000-b5523000 rw-p 00000000 00:00 0 
08-11 10:49:14.922  6833  6833 W art     : b5523000-b552a000 r-xp 00000000 b3:17 2576       /system/lib/libstagefright_avc_common.so
08-11 10:49:14.922  6833  6833 W art     : b552a000-b552b000 r--p 00006000 b3:17 2576       /system/lib/libstagefright_avc_common.so
08-11 10:49:14.922  6833  6833 W art     : b552b000-b552c000 rw-p 00007000 b3:17 2576       /system/lib/libstagefright_avc_common.so
08-11 10:49:14.922  6833  6833 W art     : b552d000-b5530000 r-xp 00000000 b3:17 2552       /system/lib/libstagefright_enc_common.so
08-11 10:49:14.922  6833  6833 W art     : b5530000-b5531000 r--p 00002000 b3:17 2552       /system/lib/libstagefright_enc_common.so
08-11 10:49:14.922  6833  6833 W art     : b5531000-b5532000 rw-p 00003000 b3:17 2552       /system/lib/libstagefright_enc_common.so
,08-11 10:49:14.922  6833  6833 W art     : b5533000-b5537000 r-xp 00000000 b3:17 2510       /system/lib/libpowermanager.so
08-11 10:49:14.922  6833  6833 W art     : b5537000-b5538000 ---p 00000000 00:00 0 
08-11 10:49:14.922  6833  6833 W art     : b5538000-b5539000 r--p 00004000 b3:17 2510       /system/lib/libpowermanager.so
08-11 10:49:14.922  6833  6833 W art     : b5539000-b553a000 rw-p 00005000 b3:17 2510       /system/lib/libpowermanager.so
08-11 10:49:14.922  6833  6833 W art     : b553b000-b5558000 r-xp 00000000 b3:17 2729       /system/lib/libvorbisidec.so
08-11 10:49:14.922  6833  6833 W art     : b5558000-b5559000 r--p 0001c000 b3:17 2729       /system/lib/libvorbisidec.so
08-11 10:49:14.922  6833  6833 W art     : b5559000-b555a000 rw-p 0001d000 b3:17 2729       /system/lib/libvorbisidec.so
,08-11 10:49:14.922  6833  6833 W art     : b555b000-b5560000 r-xp 00000000 b3:17 2678       /system/lib/libstagefright_yuv.so
08-11 10:49:14.922  6833  6833 W art     : b5560000-b5561000 r--p 00004000 b3:17 2678       /system/lib/libstagefright_yuv.so
08-11 10:49:14.922  6833  6833 W art     : b5561000-b5562000 rw-p 00005000 b3:17 2678       /system/lib/libstagefright_yuv.so
08-11 10:49:14.922  6833  6833 W art     : b5563000-b5594000 r-xp 00000000 b3:17 2189       /system/lib/libstagefright_omx.so
08-11 10:49:14.922  6833  6833 W art     : b5594000-b5597000 r--p 00030000 b3:17 2189       /system/lib/libstagefright_omx.so
08-11 10:49:14.922  6833  6833 W art     : b5597000-b5598000 rw-p 00033000 b3:17 2189       /system/lib/libstagefright_omx.so
,08-11 10:49:14.922  6833  6833 W art     : b5599000-b55d4000 r-xp 00000000 b3:17 893        /system/lib/libopus.so
08-11 10:49:14.922  6833  6833 W art     : b55d4000-b55d5000 r--p 0003a000 b3:17 893        /system/lib/libopus.so
08-11 10:49:14.922  6833  6833 W art     : b55d5000-b55d6000 rw-p 0003b000 b3:17 893        /system/lib/libopus.so
08-11 10:49:14.922  6833  6833 W art     : b55d7000-b55de000 r-xp 00000000 b3:17 2928       /system/lib/libmediautils.so
08-11 10:49:14.922  6833  6833 W art     : b55de000-b55df000 ---p 00000000 00:00 0 
08-11 10:49:14.922  6833  6833 W art     : b55df000-b55e0000 r--p 00007000 b3:17 2928       /system/lib/libmediautils.so
08-11 10:49:14.922  6833  6833 W art     : b55e0000-b55e1000 rw-p 00008000 b3:17 2928       /system/lib/libmediautils.so
08-11 10:49:14.922  6833  6833 W art     : b55e1000-b55e2000 r--p 00000000 00:00 0          [anon:linker_alloc]
,08-11 10:49:14.922  6833  6833 W art     : b55e2000-b55f9000 r-xp 00000000 b3:17 808        /system/lib/libdrmframework.so
08-11 10:49:14.922  6833  6833 W art     : b55f9000-b55fa000 ---p 00000000 00:00 0 
08-11 10:49:14.922  6833  6833 W art     : b55fa000-b55fd000 r--p 00017000 b3:17 808        /system/lib/libdrmframework.so
08-11 10:49:14.922  6833  6833 W art     : b55fd000-b55fe000 rw-p 0001a000 b3:17 808        /system/lib/libdrmframework.so
08-11 10:49:14.922  6833  6833 W art     : b55fe000-b561d000 r-xp 00000000 b3:17 1044       /system/lib/libRScpp.so
08-11 10:49:14.922  6833  6833 W art     : b561d000-b561e000 r--p 0001e000 b3:17 1044       /system/lib/libRScpp.so
08-11 10:49:14.922  6833  6833 W art     : b561e000-b561f000 rw-p 0001f000 b3:17 1044       /system/lib/libRScpp.so
08-11 10:49:14.922  6833  6833 W art     : b561f000-b565d000 r-xp 00000000 b3:17 2566       /system/lib/libRS.so
,08-11 10:49:14.922  6833  6833 W art     : b565d000-b565e000 ---p 00000000 00:00 0 
08-11 10:49:14.922  6833  6833 W art     : b565e000-b5660000 r--p 0003e000 b3:17 2566       /system/lib/libRS.so
08-11 10:49:14.922  6833  6833 W art     : b5660000-b5661000 rw-p 00040000 b3:17 2566       /system/lib/libRS.so
08-11 10:49:14.922  6833  6833 W art     : b5662000-b5669000 r-xp 00000000 b3:17 2637       /system/lib/libspeexresampler.so
08-11 10:49:14.922  6833  6833 W art     : b5669000-b566a000 r--p 00006000 b3:17 2637       /system/lib/libspeexresampler.so
08-11 10:49:14.922  6833  6833 W art     : b566a000-b566b000 rw-p 00007000 b3:17 2637       /system/lib/libspeexresampler.so
08-11 10:49:14.922  6833  6833 W art     : b566c000-b566f000 r-xp 00000000 b3:17 1406       /system/lib/libsamsungvad.so
,08-11 10:49:14.922  6833  6833 W art     : b566f000-b5670000 r--p 00002000 b3:17 1406       /system/lib/libsamsungvad.so
08-11 10:49:14.922  6833  6833 W art     : b5670000-b5671000 rw-p 00003000 b3:17 1406       /system/lib/libsamsungvad.so
08-11 10:49:14.922  6833  6833 W art     : b5671000-b5677000 r-xp 00000000 b3:17 2449       /system/lib/libedmnativehelper.so
08-11 10:49:14.922  6833  6833 W art     : b5677000-b5678000 ---p 00000000 00:00 0 
08-11 10:49:14.922  6833  6833 W art     : b5678000-b5679000 r--p 00006000 b3:17 2449       /system/lib/libedmnativehelper.so
08-11 10:49:14.922  6833  6833 W art     : b5679000-b567a000 rw-p 00007000 b3:17 2449       /system/lib/libedmnativehelper.so
08-11 10:49:14.922  6833  6833 W art     : b567a000-b5683000 r-xp 00000000 b3:17 2351       /system/lib/libnbaio.so
,08-11 10:49:14.922  6833  6833 W art     : b5683000-b5684000 r--p 00008000 b3:17 2351       /system/lib/libnbaio.so
08-11 10:49:14.922  6833  6833 W art     : b5684000-b5685000 rw-p 00009000 b3:17 2351       /system/lib/libnbaio.so
08-11 10:49:14.922  6833  6833 W art     : b5685000-b5716000 r-xp 00000000 b3:17 128        /system/lib/libcrypto-rename.so
08-11 10:49:14.922  6833  6833 W art     : b5716000-b5717000 ---p 00000000 00:00 0 
08-11 10:49:14.922  6833  6833 W art     : b5717000-b5722000 r--p 00091000 b3:17 128        /system/lib/libcrypto-rename.so
08-11 10:49:14.922  6833  6833 W art     : b5722000-b5723000 rw-p 0009c000 b3:17 128        /system/lib/libcrypto-rename.so
08-11 10:49:14.922  6833  6833 W art     : b5724000-b5736000 r-xp 00000000 b3:17 2929       /system/lib/libpcre.so
,08-11 10:49:14.922  6833  6833 W art     : b5736000-b5737000 r--p 00011000 b3:17 2929       /system/lib/libpcre.so
08-11 10:49:14.922  6833  6833 W art     : b5737000-b5738000 rw-p 00012000 b3:17 2929       /system/lib/libpcre.so
08-11 10:49:14.922  6833  6833 W art     : b5739000-b573e000 r-xp 00000000 b3:17 2465       /system/lib/libwpa_client.so
08-11 10:49:14.922  6833  6833 W art     : b573e000-b573f000 r--p 00004000 b3:17 2465       /system/lib/libwpa_client.so
08-11 10:49:14.922  6833  6833 W art     : b573f000-b5740000 rw-p 00005000 b3:17 2465       /system/lib/libwpa_client.so
08-11 10:49:14.922  6833  6833 W art     : b5741000-b57ae000 r-xp 00000000 b3:17 873        /system/lib/libGLES_trace.so
08-11 10:49:14.922  6833  6833 W art     : b57ae000-b57af000 ---p 00000000 00:00 0 
08-11 10:49:14.922  6833  6833 W art     : b57af000-b57b1000 r--p 0006d000 b3:17 873        /system/lib/libGLES_trace.so
,08-11 10:49:14.922  6833  6833 W art     : b57b1000-b57b2000 rw-p 0006f000 b3:17 873        /system/lib/libGLES_trace.so
08-11 10:49:14.922  6833  6833 W art     : b57b2000-b57b3000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-11 10:49:14.922  6833  6833 W art     : b57b3000-b57ba000 r-xp 00000000 b3:17 2579       /system/lib/libsdp_crypto.so
08-11 10:49:14.922  6833  6833 W art     : b57ba000-b57bb000 r--p 00006000 b3:17 2579       /system/lib/libsdp_crypto.so
08-11 10:49:14.922  6833  6833 W art     : b57bb000-b57bc000 rw-p 00007000 b3:17 2579       /system/lib/libsdp_crypto.so
08-11 10:49:14.922  6833  6833 W art     : b57bd000-b583d000 r-xp 00000000 b3:17 2884       /system/lib/libAstcEnc.so
08-11 10:49:14.922  6833  6833 W art     : b583d000-b583e000 ---p 00000000 00:00 0 
08-11 10:49:14.922  6833  6833 W art     : b583e000-b583f000 r--p 00080000 b3:17 2884       /system/lib/libAstcEnc.so
,08-11 10:49:14.922  6833  6833 W art     : b583f000-b5840000 rw-p 00081000 b3:17 2884       /system/lib/libAstcEnc.so
08-11 10:49:14.922  6833  6833 W art     : b5840000-b5857000 rw-p 00000000 00:00 0 
08-11 10:49:14.922  6833  6833 W art     : b5857000-b588e000 r-xp 00000000 b3:17 3244       /system/vendor/l
08-11 10:49:14.922  6833  6833 W art     : ib/libqc-opt.so
08-11 10:49:14.922  6833  6833 W art     : b588e000-b588f000 r--p 00036000 b3:17 3244       /system/vendor/lib/libqc-opt.so
08-11 10:49:14.922  6833  6833 W art     : b588f000-b5890000 rw-p 00037000 b3:17 3244       /system/vendor/lib/libqc-opt.so
08-11 10:49:14.922  6833  6833 W art     : b5890000-b58ac000 r-xp 00000000 b3:17 387        /system/lib/libquramimagecodec.so
08-11 10:49:14.922  6833  6833 W art     : b58ac000-b58ad000 r--p 0001b000 b3:17 387        /system/lib/libquramimagecodec.so
08-11 10:49:14.922  6833  6833 W art     : b58ad000-b58ae000 rw-p 0001c000 b3:17 387        /system/lib/libquramimagecodec.so
,08-11 10:49:14.922  6833  6833 W art     : b58af000-b5910000 r-xp 00000000 b3:17 2708       /system/lib/libft2.so
08-11 10:49:14.922  6833  6833 W art     : b5910000-b5912000 r--p 00060000 b3:17 2708       /system/lib/libft2.so
08-11 10:49:14.922  6833  6833 W art     : b5912000-b5913000 rw-p 00062000 b3:17 2708       /system/lib/libft2.so
08-11 10:49:14.922  6833  6833 W art     : b5914000-b593b000 r-xp 00000000 b3:17 2633       /system/lib/libpng.so
08-11 10:49:14.922  6833  6833 W art     : b593b000-b593c000 ---p 00000000 00:00 0 
08-11 10:49:14.922  6833  6833 W art     : b593c000-b593d000 r--p 00027000 b3:17 2633       /system/lib/libpng.so
,08-11 10:49:14.922  6833  6833 W art     : b593d000-b593e000 rw-p 00028000 b3:17 2633       /system/lib/libpng.so
08-11 10:49:14.922  6833  6833 W art     : b593f000-b5947000 r-xp 00000000 b3:17 2201       /system/lib/libremotedesktop_client.so
08-11 10:49:14.922  6833  6833 W art     : b5947000-b5949000 r--p 00007000 b3:17 2201       /system/lib/libremotedesktop_client.so
08-11 10:49:14.922  6833  6833 W art     : b5949000-b594a000 rw-p 00009000 b3:17 2201       /system/lib/libremotedesktop_client.so
08-11 10:49:14.922  6833  6833 W art     : b594b000-b594e000 r-xp 00000000 b3:17 2500       /system/lib/libsync.so
08-11 10:49:14.922  6833  6833 W art     : b594e000-b594f000 r--p 00002000 b3:17 2500       /system/lib/libsync.so
08-11 10:49:14.922  6833  6833 W art     : b594f000-b5950000 rw-p 00003000 b3:17 2500       /system/lib/libsync.so
,08-11 10:49:14.922  6833  6833 W art     : b5950000-b5954000 r-xp 00000000 b3:17 2632       /system/lib/libstdc++.so
08-11 10:49:14.922  6833  6833 W art     : b5954000-b5955000 ---p 00000000 00:00 0 
08-11 10:49:14.922  6833  6833 W art     : b5955000-b5956000 r--p 00004000 b3:17 2632       /system/lib/libstdc++.so
08-11 10:49:14.922  6833  6833 W art     : b5956000-b5957000 rw-p 00005000 b3:17 2632       /system/lib/libstdc++.so
08-11 10:49:14.922  6833  6833 W art     : b5957000-b5967000 r-xp 00000000 b3:17 433        /system/lib/libunwind.so
08-11 10:49:14.922  6833  6833 W art     : b5967000-b5968000 r--p 0000f000 b3:17 433        /system/lib/libunwind.so
,08-11 10:49:14.922  6833  6833 W art     : b5968000-b5969000 rw-p 00010000 b3:17 433        /system/lib/libunwind.so
08-11 10:49:14.922  6833  6833 W art     : b5969000-b59af000 rw-p 00000000 00:00 0 
08-11 10:49:14.922  6833  6833 W art     : b59af000-b59b8000 r-xp 00000000 b3:17 2901       /system/lib/libbase.so
08-11 10:49:14.922  6833  6833 W art     : b59b8000-b59b9000 r--p 00008000 b3:17 2901       /system/lib/libbase.so
08-11 10:49:14.922  6833  6833 W art     : b59b9000-b59ba000 rw-p 00009000 b3:17 2901       /system/lib/libbase.so
,08-11 10:49:14.922  6833  6833 W art     : b59bb000-b59c0000 r-xp 00000000 b3:17 2653       /system/lib/libeffects.so
08-11 10:49:14.922  6833  6833 W art     : b59c0000-b59c1000 r--p 00004000 b3:17 2653       /system/lib/libeffects.so
08-11 10:49:14.922  6833  6833 W art     : b59c1000-b59c2000 rw-p 00005000 b3:17 2653       /system/lib/libeffects.so
08-11 10:49:14.922  6833  6833 W art     : b59c2000-b59c5000 r-xp 00000000 b3:17 240        /system/lib/libstagefright_http_support.so
08-11 10:49:14.922  6833  6833 W art     : b59c5000-b59c6000 ---p 00000000 00:00 0 
08-11 10:49:14.922  6833  6833 W art     : b59c6000-b59c7000 r--p 00003000 b3:17 240        /system/lib/libstagefright_http_support.so
08-11 10:49:14.922  6833  6833 W art     : b59c7000-b59c8000 rw-p 00004000 b3:17 240        /system/lib/libstagefright_http_support.so
,08-11 10:49:14.922  6833  6833 W art     : b59c9000-b59e1000 r-xp 00000000 b3:17 2406       /system/lib/libstagefright_foundation.so
08-11 10:49:14.922  6833  6833 W art     : b59e1000-b59e2000 ---p 00000000 00:00 0 
08-11 10:49:14.922  6833  6833 W art     : b59e2000-b59e3000 r--p 00018000 b3:17 2406       /system/lib/libstagefright_foundation.so
08-11 10:49:14.922  6833  6833 W art     : b59e3000-b59e4000 rw-p 00019000 b3:17 2406       /system/lib/libstagefright_foundation.so
08-11 10:49:14.922  6833  6833 W art     : b59e4000-b59e5000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
08-11 10:49:14.922  6833  6833 W art     : b59e5000-b5b7f000 r-xp 00000000 b3:17 2789       /system/lib/libstagefright.so
08-11 10:49:14.922  6833  6833 W art     : b5b7f000-b5b80000 ---p 00000000 00:00 0 
,08-11 10:49:14.922  6833  6833 W art     : b5b80000-b5b8d000 r--p 0019a000 b3:17 2789       /system/lib/libstagefright.so
08-11 10:49:14.922  6833  6833 W art     : b5b8d000-b5b8e000 rw-p 001a7000 b3:17 2789       /system/lib/libstagefright.so
08-11 10:49:14.922  6833  6833 W art     : b5b8e000-b5b92000 r-xp 00000000 b3:17 2676       /system/lib/libpersona.so
08-11 10:49:14.922  6833  6833 W art     : b5b92000-b5b93000 ---p 00000000 00:00 0 
08-11 10:49:14.922  6833  6833 W art     : b5b93000-b5b94000 r--p 00004000 b3:17 2676       /system/lib/libpersona.so
08-11 10:49:14.922  6833  6833 W art     : b5b94000-b5b95000 rw-p 00005000 b3:17 2676       /system/lib/libpersona.so
08-11 10:49:14.922  6833  6833 W art     : b5b95000-b5ba8000 r-xp 00000000 b3:17 2918       /system/lib/libimagefilter.so
08-11 10:49:14.922  6833  6833 W art     : b5ba8000-b5ba9000 r--p 00012000 b3:17 2918       /system/lib/libimagefilter.so
,08-11 10:49:14.922  6833  6833 W art     : b5ba9000-b5baa000 rw-p 00013000 b3:17 2918       /system/lib/libimagefilter.so
08-11 10:49:14.922  6833  6833 W art     : b5bab000-b5bf6000 r-xp 00000000 b3:17 422        /system/lib/libsecure_storage.so
08-11 10:49:14.922  6833  6833 W art     : b5bf6000-b5bf7000 r--p 0004a000 b3:17 422        /system/lib/libsecure_storage.so
08-11 10:49:14.922  6833  6833 W art     : b5bf7000-b5bf8000 rw-p 0004b000 b3:17 422        /system/lib/libsecure_storage.so
08-11 10:49:14.922  6833  6833 W art     : b5bf8000-b5bfa000 rw-p 00000000 00:00 0 
08-11 10:49:14.922  6833  6833 W art     : b5bfb000-b5c0c000 r-xp 00000000 b3:17 2242       /system/lib/libsamsungeffect.so
08-11 10:49:14.922  6833  6833 W art     : b5c0c000-b5c0d000 ---p 00000000 00:00 0 
08-11 10:49:14.922  6833  6833 W art     : b5c0d000-b5c0e000 r--p 00011000 b3:17 2242       /system/lib/libsamsungeffect.so
,08-11 10:49:14.922  6833  6833 W art     : b5c0e000-b5c0f000 rw-p 00012000 b3:17 2242       /system/lib/libsamsungeffect.so
08-11 10:49:14.922  6833  6833 W art     : b5c0f000-b5c10000 r--p 00000000 00:00 0 
08-11 10:49:14.922  6833  6833 W art     : b5c10000-b5c1a000 r-xp 00000000 b3:17 2375       /system/lib/libsensorhub.so
08-11 10:49:14.922  6833  6833 W art     : b5c1a000-b5c1c000 r--p 00009000 b3:17 2375       /system/lib/libsensorhub.so
08-11 10:49:14.922  6833  6833 W art     : b5c1c000-b5c1d000 rw-p 0000b000 b3:17 2375       /system/lib/libsensorhub.so
08-11 10:49:14.922  6833  6833 W art     : b5c1d000-b5c36000 r-xp 00000000 b3:17 2927       /system/lib/libmctraster.so
08-11 10:49:14.922  6833  6833 W art     : b5c36000-b5c37000 r--p 00018000 b3:17 2927       /system/lib/libmctraster.so
,08-11 10:49:14.922  6833  6833 W art     : b5c37000-b5c3a000 rw-p 00019000 b3:17 2927       /system/lib/libmctraster.so
08-11 10:49:14.922  6833  6833 W art     : b5c3a000-b5c3e000 rw-p 00000000 00:00 0 
08-11 10:49:14.922  6833  6833 W art     : b5c3e000-b5cb2000 r-xp 00000000 b3:17 2776       /system/lib/libhwui.so
08-11 10:49:14.922  6833  6833 W art     : b5cb2000-b5cb3000 ---p 00000000 00:00 0 
08-11 10:49:14.922  6833  6833 W art     : b5cb3000-b5cb6000 r--p 00074000 b3:17 2776       /system/lib/libhwui.so
08-11 10:49:14.922  6833  6833 W art     : b5cb6000-b5cb7000 rw-p 00077000 b3:17 2776       /system/lib/libhwui.so
08-11 10:49:14.922  6833  6833 W art     : b5cb7000-b5cb8000 r--p 00000000 00:00 0 
08-11 10:49:14.922  6833  6833 W art     : b5cb8000-b5cbb000 r-xp 00000000 b3:17 2491       /system/lib/libcc_manager.so
,08-11 10:49:14.922  6833  6833 W art     : b5cbb000-b5cbc000 r--p 00002000 b3:17 2491       /system/lib/libcc_manager.so
08-11 10:49:14.922  6833  6833 W art     : b5cbc000-b5cbd000 rw-p 00003000 b3:17 2491       /system/lib/libcc_manager.so
08-11 10:49:14.922  6833  6833 W art     : b5cbd000-b5cbe000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-11 10:49:14.922  6833  6833 W art     : b5cbe000-b5cc3000 r-xp 00000000 b3:17 2461       /system/lib/libsecnativefeature.so
08-11 10:49:14.922  6833  6833 W art     : b5cc3000-b5cc4000 r--p 00004000 b3:17 2461       /system/lib/libsecnativefeature.so
08-11 10:49:14.922  6833  6833 W art     : b5cc4000-b5cc5000 rw-p 00005000 b3:17 2461       /system/lib/libsecnativefeature.so
08-11 10:49:14.922  6833  6833 W art     : b5cc5000-b5cc6000 r--p 00000000 00:00 0          [anon:linker_alloc]
,08-11 10:49:14.922  6833  6833 W art     : b5cc6000-b5cc9000 r-xp 00000000 b3:17 2937       /system/lib/libradio_metadata.so
08-11 10:49:14.922  6833  6833 W art     : b5cc9000-b5cca000 r--p 00002000 b3:17 2937       /system/lib/libradio_metadata.so
08-11 10:49:14.922  6833  6833 W art     : b5cca000-b5ccb000 rw-p 00003000 b3:17 2937       /system/lib/libradio_metadata.so
08-11 10:49:14.922  6833  6833 W art     : b5ccb000-b5ccc000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-11 10:49:14.922  6833  6833 W art     : b5ccc000-b5cd0000 r-xp 00000000 b3:17 272        /system/lib/libnativebridge.so
08-11 10:49:14.922  6833  6833 W art     : b5cd0000-b5cd1000 r--p 00003000 b3:17 272        /system/lib/libnativebridge.so
08-11 10:49:14.922  6833  6833 W art     : b5cd1000-b5cd2000 rw-p 00004000 b3:17 272        /system/lib/libnativebridge.so
08-11 10:49:14.922  6833  6833 W art     : b5cd2000-b5cd3000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
,08-11 10:49:14.922  6833  6833 W art     : b5cd3000-b5cd7000 r-xp 00000000 b3:17 2569       /system/lib/libprocessgroup.so
08-11 10:49:14.922  6833  6833 W art     : b5cd7000-b5cd8000 r--p 00003000 b3:17 2569       /system/lib/libprocessgroup.so
08-11 10:49:14.922  6833  6833 W art     : b5cd8000-b5cd9000 rw-p 00004000 b3:17 2569       /system/lib/libprocessgroup.so
08-11 10:49:14.922  6833  6833 W art     : b5cd9000-b5cda000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-11 10:49:14.922  6833  6833 W art     : b5cda000-b5ce8000 r-xp 00000000 b3:17 472        /system/lib/libminikin.so
08-11 10:49:14.922  6833  6833 W art     : b5ce8000-b5ce9000 ---p 00000000 00:00 0 
08-11 10:49:14.922  6833  6833 W art     : b5ce9000-b5cea000 r--p 0000e000 b3:17 472        /system/lib/libminikin.so
,08-11 10:49:14.922  6833  6833 W art     : b5cea000-b5ceb000 rw-p 0000f000 b3:17 472        /system/lib/libminikin.so
08-11 10:49:14.922  6833  6833 W art     : b5ceb000-b5cf5000 r-xp 00000000 b3:17 2202       /system/lib/libsoundtrigger.so
08-11 10:49:14.922  6833  6833 W art     : b5cf5000-b5cf8000 r--p 00009000 b3:17 2202       /system/lib/libsoundtrigger.so
08-11 10:49:14.922  6833  6833 W art     : b5cf8000-b5cf9000 rw-p 0000c000 b3:17 2202       /system/lib/libsoundtrigger.so
08-11 10:49:14.922  6833  6833 W art     : b5cf9000-b5cfa000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-11 10:49:14.922  6833  6833 W art     : b5cfa000-b5d04000 r-xp 00000000 b3:17 2936       /system/lib/libradio.so
,08-11 10:49:14.922  6833  6833 W art     : b5d04000-b5d07000 r--p 00009000 b3:17 2936       /system/lib/libradio.so
08-11 10:49:14.922  6833  6833 W art     : b5d07000-b5d08000 rw-p 0000c000 b3:17 2936       /system/lib/libradio.so
08-11 10:49:14.922  6833  6833 W art     : b5d08000-b5d0c000 r-xp 00000000 b3:17 2417       /system/lib/libnetd_client.so
08-11 10:49:14.922  6833  6833 W art     : b5d0c000-b5d0d000 r--p 00003000 b3:17 2417       /system/lib/libnetd_client.so
08-11 10:49:14.922  6833  6833 W art     : b5d0d000-b5d0e000 rw-p 00004000 b3:17 2417       /system/lib/libnetd_client.so
08-11 10:49:14.922  6833  6833 W art     : b5d0e000-b5d0f000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-11 10:49:14.922  6833  6833 W art     : b5d0f000-b5d1c000 r-xp 00000000 b3:17 2372       /system/lib/libimg_utils.so
08-11 10:49:14.922  6833  6833 W art     : b5d1c000-b5d1e000 r--p 0000c000 b3:17 2372       /system/lib/libimg_utils.so
,08-11 10:49:14.922  6833  6833 W art     : b5d1e000-b5d1f000 rw-p 0000e000 b3:17 2372       /system/lib/libimg_utils.so
08-11 10:49:14.922  6833  6833 W art     : b5d1f000-b6131000 r-xp 00000000 b3:17 328        /system/lib/libpdfium.so
08-11 10:49:14.922  6833  6833 W art     : b6131000-b6132000 ---p 00000000 00:00 0 
08-11 10:49:14.922  6833  6833 W art     : b6132000-b613b000 r--p 00412000 b3:17 328        /system/lib/libpdfium.so
08-11 10:49:14.922  6833  6833 W art     : b613b000-b613f000 rw-p 0041b000 b3:17 328        /system/lib/libpdfium.so
08-11 10:49:14.922  6833  6833 W art     : b613f000-b6140000 rw-p 00000000 00:00 0 
08-11 10:49:14.922  6833  6833 W art     : b6140000-b6147000 r-xp 00000000 b3:17 2571       /system/lib/libaudioutils.so
08-11 10:49:14.922  6833  6833 W art     : b6147000-b6148000 r--p 00006000 b3:17 2571       /system/lib/libaudioutils.so
,08-11 10:49:14.922  6833  6833 W art     : b6148000-b6149000 rw-p 00007000 b3:17 2571       /system/lib/libaudioutils.so
08-11 10:49:14.922  6833  6833 W art     : b6149000-b614a000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-11 10:49:14.922  6833  6833 W art     : b614a000-b6165000 r-xp 00000000 b3:17 1184       /system/lib/libz.so
08-11 10:49:14.922  6833  6833 W art     : b6165000-b6166000 r--p 0001a000 b3:17 1184       /system/lib/libz.so
08-11 10:49:14.922  6833  6833 W art     : b6166000-b6167000 rw-p 0001b000 b3:17 1184       /system/lib/libz.so
08-11 10:49:14.922  6833  6833 W art     : b6167000-b6168000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-11 10:49:14.922  6833  6833 W art     : b6168000-b61b4000 r-xp 00000000 b3:17 994        /system/lib/libharfbuzz_ng.so
,08-11 10:49:14.922  6833  6833 W art     : b61b4000-b61b5000 ---p 00000000 00:00 0 
08-11 10:49:14.922  6833  6833 W art     : b61b5000-b61b6000 r--p 0004c000 b3:17 994        /system/lib/libharfbuzz_ng.so
08-11 10:49:14.922  6833  6833 W art     : b61b6000-b61b7000 rw-p 0004d000 b3:17 994        /system/lib/libharfbuzz_ng.so
08-11 10:49:14.922  6833  6833 W art     : b61b7000-b61b8000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-11 10:49:14.922  6833  6833 W art     : b61b8000-b61bc000 r-xp 00000000 b3:17 2681       /system/lib/libusbhost.so
,08-11 10:49:14.922  6833  6833 W art     : b61bc000-b61bd000 ---p 00000000 00:00 0 
08-11 10:49:14.922  6833  6833 W art     : b61bd000-b61be000 r--p 00004000 b3:17 2681       /system/lib/libusbhost.so
08-11 10:49:14.922  6833  6833 W art     : b61be000-b61bf000 rw-p 00005000 b3:17 2681       /system/lib/libusbhost.so
08-11 10:49:14.922  6833  6833 W art     : b61bf000-b61f7000 r-xp 00000000 b3:17 2746       /system/lib/libjpeg.so
08-11 10:49:14.922  6833  6833 W art     : b61f7000-b61f8000 r--p 00037000 b3:17 2746       /system/lib/libjpeg.so
08-11 10:49:14.922  6833  6833 W art     : b61f8000-b61f9000 rw-p 00038000 b3:17 2746       /system/lib/libjpeg.so
08-11 10:49:14.922  6833  6833 W art     : b61f9000-b61fa000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-11 10:49:14.922  6833  6833 W art     : b61fa000-b6298000 r-xp 00000000 b3:17 496        /system/lib/libmedia.so
,08-11 10:49:14.922  6833  6833 W art     : b6298000-b6299000 ---p 00000000 00:00 0 
08-11 10:49:14.922  6833  6833 W art     : b6299000-b62b7000 r--p 0009e000 b3:17 496        /system/lib/libmedia.so
08-11 10:49:14.922  6833  6833 W art     : b62b7000-b62b8000 rw-p 000bc000 b3:17 496        /system/lib/libmedia.so
08-11 10:49:14.922  6833  6833 W art     : b62b8000-b642b000 r-xp 00000000 b3:17 1085       /system/lib/libicui18n.so
08-11 10:49:14.922  6833  6833 W art     : b642b000-b6436000 r--p 00172000 b3:17 1085       /system/lib/libicui18n.so
08-11 10:49:14.922  6833  6833 W art     : b6436000-b6437000 rw-p 0017d000 b3:17 1085       /system/lib/libicui18n.so
08-11 10:49:14.922  6833  6833 W art     : b6437000-b654e000 r-xp 00000000 b3:17 2041       /system/lib/libicuuc.so
08-11 10:49:14.922  6833  6833 W art     : b654e000-b6559000 r--p 00116000 b3:17 2041       /system/lib/libicuuc.so
08-11 10:49:14.922  6833  6833 W art     : b6559000-b655a000 rw-p 00121000 b3:17 2041       /system/lib/libicuuc.so
,08-11 10:49:14.922  6833  6833 W art     : b655a000-b655e000 rw-p 00000000 00:00 0 
08-11 10:49:14.922  6833  6833 W art     : b655e000-b6582000 r-xp 00000000 b3:17 400        /system/lib/libssl.so
08-11 10:49:14.922  6833  6833 W art     : b6582000-b6584000 r--p 00023000 b3:17 400        /system/lib/libssl.so
08-11 10:49:14.922  6833  6833 W art     : b6584000-b6585000 rw-p 00025000 b3:17 400        /system/lib/libssl.so
08-11 10:49:14.922  6833  6833 W art     : b6585000-b662b000 r-xp 00000000 b3:17 132        /system/lib/libcrypto.so
08-11 10:49:14.922  6833  6833 W art     : b662b000-b6638000 r--p 000a5000 b3:17 132        /system/lib/libcrypto.so
08-11 10:49:14.922  6833  6833 W art     : b6638000-b6639000 rw-p 000b2000 b3:17 132        /system/lib/libcrypto.so
08-11 10:49:14.922  6833  6833 W art     : b6639000-b663a000 rw-p 00000000 00:00 0 
08-11 10:49:14.922  6833  6833 W art     : b663a000-b668d000 r-xp 00000000 b3:17 2733       /system/lib/libsonivox.so
,08-11 10:49:14.922  6833  6833 W art     : b668d000-b668e000 ---p 00000000 00:00 0 
08-11 10:49:14.922  6833  6833 W art     : b668e000-b668f000 r--p 00053000 b3:17 2733       /system/lib/libsonivox.so
08-11 10:49:14.922  6833  6833 W art     : b668f000-b6690000 rw-p 00054000 b3:17 2733       /system/lib/libsonivox.so
08-11 10:49:14.922  6833  6833 W art     : b6690000-b6695000 rw-p 00000000 00:00 0 
08-11 10:49:14.922  6833  6833 W art     : b6695000-b66a7000 r-xp 00000000 b3:17 2634       /system/lib/libselinux.so
08-11 10:49:14.922  6833  6833 W art     : b66a7000-b66a8000 ---p 00000000 00:00 0 
08-11 10:49:14.922  6833  6833 W art     : b66a8000-b66a9000 r--p 00012000 b3:17 2634       /system/lib/libselinux.so
08-11 10:49:14.922  6833  6833 W art     : b66a9000-b66aa000 rw-p 00013000 b3:17 2634       /system/lib/libselinux.so
,08-11 10:49:14.922  6833  6833 W art     : b66aa000-b66b1000 r-xp 00000000 b3:17 2629       /system/lib/libhardware_legacy.so
08-11 10:49:14.922  6833  6833 W art     : b66b1000-b66b2000 r--p 00007000 b3:17 2629       /system/lib/libhardware_legacy.so
08-11 10:49:14.922  6833  6833 W art     : b66b2000-b66b3000 rw-p 00008000 b3:17 2629       /system/lib/libhardware_legacy.so
08-11 10:49:14.922  6833  6833 W art     : b66b3000-b66b4000 rw-p 00000000 00:00 0 
08-11 10:49:14.922  6833  6833 W art     : b66b4000-b66b7000 r-xp 00000000 b3:17 2418       /system/lib/libhardware.so
08-11 10:49:14.922  6833  6833 W art     : b66b7000-b66b8000 r--p 00002000 b3:17 2418       /system/lib/libhardware.so
08-11 10:49:14.922  6833  6833 W art     : b66b8000-b66b9000 rw-p 00003000 b3:17 2418       /system/lib/libhardware.so
,08-11 10:49:14.922  6833  6833 W art     : b66b9000-b66bd000 r-xp 00000000 b3:17 2555       /system/lib/libETC1.so
08-11 10:49:14.922  6833  6833 W art     : b66bd000-b66be000 r--p 00003000 b3:17 2555       /system/lib/libETC1.so
08-11 10:49:14.922  6833  6833 W art     : b66be000-b66bf000 rw-p 00004000 b3:17 2555       /system/lib/libETC1.so
08-11 10:49:14.922  6833  6833 W art     : b66bf000-b66cd000 r-xp 00000000 b3:17 2721       /system/lib/libGLESv2.so
08-11 10:49:14.922  6833  6833 W art     : b66cd000-b66ce000 ---p 00000000 00:00 0 
08-11 10:49:14.922  6833  6833 W art     : b66ce000-b66cf000 r--p 0000e000 b3:17 2721       /system/lib/libGLESv2.so
08-11 10:49:14.922  6833  6833 W art     : b66cf000-b66d0000 rw-p 0000f000 b3:17 2721       /system/lib/libGLESv2.so
08-11 10:49:14.922  6833  6833 W art     : b66d0000-b66d9000 r-xp 00000000 b3:17 2235       /system/lib/libGLESv1_CM.so
,08-11 10:49:14.922  6833  6833 W art     : b66d9000-b66da000 r--p 00008000 b3:17 2235       /system/lib/libGLESv1_CM.so
08-11 10:49:14.922  6833  6833 W art     : b66da000-b66db000 rw-p 00009000 b3:17 2235       /system/lib/libGLESv1_CM.so
08-11 10:49:14.922  6833  6833 W art     : b66db000-b6741000 r-xp 00000000 b3:17 82         /system/lib/libEGL.so
08-11 10:49:14.922  6833  6833 W art     : b6741000-b6742000 ---p 00000000 00:00 0 
08-11 10:49:14.922  6833  6833 W art     : b6742000-b6744000 r--p 00066000 b3:17 82         /system/lib/libEGL.so
08-11 10:49:14.922  6833  6833 W art     : b6744000-b674d000 rw-p 00068000 b3:17 82         /system/lib/libEGL.so
08-11 10:49:14.922  6833  6833 W art     : b674d000-b6750000 rw-p 00000000 00:00 0 
08-11 10:49:14.922  6833  6833 W art     : b6750000-b67e7000 r-xp 00000000 b3:17 688        /system/lib/libsqlite.so
,08-11 10:49:14.922  6833  6833 W art     : b67e7000-b67e9000 r--p 00096000 b3:17 688        /system/lib/libsqlite.so
08-11 10:49:14.922  6833  6833 W art     : b67e9000-b67ea000 rw-p 00098000 b3:17 688        /system/lib/libsqlite.so
08-11 10:49:14.922  6833  6833 W art     : b67ea000-b67eb000 rw-p 00000000 00:00 0 
08-11 10:49:14.922  6833  6833 W art     : b67eb000-b6b0c000 r-xp 00000000 b3:17 377        /system/lib/libskia.so
08-11 10:49:14.922  6833  6833 W art     : b6b0c000-b6b0d000 ---p 00000000 00:00 0 
08-11 10:49:14.922  6833  6833 W art     : b6b0d000-b6b28000 r--p 00321000 b3:17 377        /system/lib/libskia.so
08-11 10:49:14.922  6833  6833 W art     : b6b28000-b6b2c000 rw-p 0033c000 b3:17 377        /system/lib/libskia.so
,08-11 10:49:14.922  6833  6833 W art     : b6b2c000-b6b31000 rw-p 00000000 00:00 0 
08-11 10:49:14.922  6833  6833 W art     : b6b31000-b6b39000 r-xp 00000000 b3:17 2591       /system/lib/libcamera_metadata.so
08-11 10:49:14.922  6833  6833 W art     : b6b39000-b6b3a000 r--p 00007000 b3:17 2591       /system/lib/libcamera_metadata.so
08-11 10:49:14.922  6833  6833 W art     : b6b3a000-b6b3b000 rw-p 00008000 b3:17 2591       /system/lib/libcamera_metadata.so
08-11 10:49:14.922  6833  6833 W art     : b6b3b000-b6b69000 r-xp 00000000 b3:17 564        /system/lib/libcamera_client.so
08-11 10:49:14.922  6833  6833 W art     : b6b69000-b6b6a000 ---p 00000000 00:00 0 
08-11 10:49:14.922  6833  6833 W art     : b6b6a000-b6b71000 r--p 0002e000 b3:17 564        /system/lib/libcamera_client.so
,08-11 10:49:14.922  6833  6833 W art     : b6b71000-b6b72000 rw-p 00035000 b3:17 564        /system/lib/libcamera_client.so
08-11 10:49:14.922  6833  6833 W art     : b6b72000-b6bb8000 r-xp 00000000 b3:17 1049       /system/lib/libinputflinger.so
08-11 10:49:14.922  6833  6833 W art     : b6bb8000-b6bb9000 ---p 00000000 00:00 0 
08-11 10:49:14.922  6833  6833 W art     : b6bb9000-b6bbc000 r--p 00046000 b3:17 1049       /system/lib/libinputflinger.so
08-11 10:49:14.922  6833  6833 W art     : b6bbc000-b6bbd000 rw-p 00049000 b3:17 1049       /system/lib/libinputflinger.so
08-11 10:49:14.922  6833  6833 W art     : b6bbd000-b6bd8000 r-xp 00000000 b3:17 2442       /system/lib/libinput.so
08-11 10:49:14.922  6833  6833 W art     : b6bd8000-b6bdc000 r--p 0001a000 b3:17 2442       /system/lib/libinput.so
,08-11 10:49:14.922  6833  6833 W art     : b6bdc000-b6bdd000 rw-p 0001e000 b3:17 2442       /system/lib/libinput.so
08-11 10:49:14.922  6833  6833 W art     : b6bdd000-b6c2a000 r-xp 00000000 b3:17 2761       /system/lib/libgui.so
08-11 10:49:14.922  6833  6833 W art     : b6c2a000-b6c2b000 ---p 00000000 00:00 0 
08-11 10:49:14.922  6833  6833 W art     : b6c2b000-b6c37000 r--p 0004d000 b3:17 2761       /system/lib/libgui.so
08-11 10:49:14.922  6833  6833 W art     : b6c37000-b6c38000 rw-p 00059000 b3:17 2761       /system/lib/libgui.so
08-11 10:49:14.922  6833  6833 W art     : b6c38000-b6c45000 r-xp 00000000 b3:17 2715       /system/lib/libui.so
08-11 10:49:14.922  6833  6833 W art     : b6c45000-b6c46000 ---p 00000000 00:00 0 
,08-11 10:49:14.922  6833  6833 W art     : b6c46000-b6c47000 r--p 0000d000 b3:17 2715       /system/lib/libui.so
08-11 10:49:14.922  6833  6833 W art     : b6c47000-b6c48000 rw-p 0000e000 b3:17 2715       /system/lib/libui.so
08-11 10:49:14.922  6833  6833 W art     : b6c48000-b6c50000 r-xp 00000000 b3:17 1189       /system/lib/libnetutils.so
08-11 10:49:14.922  6833  6833 W art     : b6c50000-b6c51000 ---p 00000000 00:00 0 
08-11 10:49:14.922  6833  6833 W art     : b6c51000-b6c52000 r--p 00008000 b3:17 1189       /system/lib/libnetutils.so
08-11 10:49:14.922  6833  6833 W art     : b6c52000-b6c53000 rw-p 00009000 b3:17 1189       /system/lib/libnetutils.so
08-11 10:49:14.922  6833  6833 W art     : b6c53000-b6c5a000 r-xp 00000000 b3:17 1217       /system/lib/libnativehelper.so
08-11 10:49:14.922  6833  6833 W art     : b6c5a000-b6c5b000 r--p 00006000 b3:17 1217       /system/lib/libnativehelper.so
,08-11 10:49:14.922  6833  6833 W art     : b6c5b000-b6c5c000 rw-p 00007000 b3:17 1217       /system/lib/libnativehelper.so
,08-11 10:49:14.922  6833  6833 W art     : b6c5c000-b6c70000 r-xp 00000000 b3:17 2117       /system/lib/libexpat.so
08-11 10:49:14.922  6833  6833 W art     : b6c70000-b6c72000 r--p 00013000 b3:17 2117       /system/lib/libexpat.so
08-11 10:49:14.922  6833  6833 W art     : b6c72000-b6c73000 rw-p 00015000 b3:17 2117       /system/lib/libexpat.so
08-11 10:49:14.922  6833  6833 W art     : b6c73000-b6c9b000 r-xp 00000000 b3:17 946        /system/lib/libandroidfw.so
08-11 10:49:14.922  6833  6833 W art     : b6c9b000-b6c9d000 r--p 00027000 b3:17 946        /system/lib/libandroidfw.so
,08-11 10:49:14.922  6833  6833 W art     : b6c9d000-b6c9e000 rw-p 00029000 b3:17 946        /system/lib/libandroidfw.so
08-11 10:49:14.922  6833  6833 W art     : b6c9e000-b6ca1000 r-xp 00000000 b3:17 2456       /system/lib/libmemtrack.so
08-11 10:49:14.922  6833  6833 W art     : b6ca1000-b6ca2000 r--p 00002000 b3:17 2456       /system/lib/libmemtrack.so
08-11 10:49:14.922  6833  6833 W art     : b6ca2000-b6ca3000 rw-p 00003000 b3:17 2456       /system/lib/libmemtrack.so
08-11 10:49:14.922  6833  6833 W art     : b6ca3000-b6cac000 r-xp 00000000 b3:17 2581       /system/lib/libbacktrace.so
08-11 10:49:14.922  6833  6833 W art     : b6cac000-b6cad000 r--p 00008000 b3:17 2581       /system/lib/libbacktrace.so
08-11 10:49:14.922  6833  6833 W art     : b6cad000-b6cae000 rw-p 00009000 b3:17 2581       /system/lib/libbacktrace.so
,08-11 10:49:14.922  6833  6833 W art     : b6cae000-b6cce000 r-xp 00000000 b3:17 2560       /system/lib/libm.so
08-11 10:49:14.922  6833  6833 W art     : b6cce000-b6ccf000 r--p 0001f000 b3:17 2560       /system/lib/libm.so
08-11 10:49:14.922  6833  6833 W art     : b6ccf000-b6cd0000 rw-p 00020000 b3:17 2560       /system/lib/libm.so
08-11 10:49:14.922  6833  6833 W art     : b6cd0000-b6d43000 r-xp 00000000 b3:17 860        /system/lib/libc.so
08-11 10:49:14.922  6833  6833 W art     : b6d43000-b6d47000 r--p 00072000 b3:17 860        /system/lib/libc.so
08-11 10:49:14.922  6833  6833 W art     : b6d47000-b6d4a000 rw-p 00076000 b3:17 860        /system/lib/libc.so
08-11 10:49:14.922  6833  6833 W art     : b6d4a000-b6d54000 rw-p 00000000 00:00 0 
08-11 10:49:14.922  6833  6833 W art     : b6d54000-b6ddc000 r-xp 00000000 b3:17 1016       /system/lib/libc++.so
,08-11 10:49:14.922  6833  6833 W art     : b6ddc000-b6ddd000 ---p 00000000 00:00 0 
08-11 10:49:14.922  6833  6833 W art     : b6ddd000-b6de1000 r--p 00088000 b3:17 1016       /system/lib/libc++.so
08-11 10:49:14.922  6833  6833 W art     : b6de1000-b6de2000 rw-p 0008c000 b3:17 1016       /system/lib/libc++.so
08-11 10:49:14.922  6833  6833 W art     : b6de2000-b6de3000 rw-p 00000000 00:00 0 
08-11 10:49:14.922  6833  6833 W art     : b6de3000-b6e0c000 r-xp 00000000 b3:17 1253       /system/lib/libwilhelm.so
08-11 10:49:14.922  6833  6833 W art     : b6e0c000-b6e0d000 ---p 00000000 00:00 0 
08-11 10:49:14.922  6833  6833 W art     : b6e0d000-b6e10000 r--p 00029000 b3:17 1253       /system/lib/libwilhelm.so
08-11 10:49:14.922  6833  6833 W art     : b6e10000-b6e11000 rw-p 0002c000 b3:17 1253       /system/lib/libwilhelm.so
,08-11 10:49:14.922  6833  6833 W art     : b6e11000-b6eeb000 r-xp 00000000 b3:17 495        /system/lib/libandroid_runtime.so
08-11 10:49:14.922  6833  6833 W art     : b6eeb000-b6ef2000 r--p 000d9000 b3:17 495        /system/lib/libandroid_runtime.so
08-11 10:49:14.922  6833  6833 W art     : b6ef2000-b6efa000 rw-p 000e0000 b3:17 495        /system/lib/libandroid_runtime.so
08-11 10:49:14.922  6833  6833 W art     : b6efa000-b6efb000 rw-p 00000000 00:00 0 
08-11 10:49:14.922  6833  6833 W art     : b6efb000-b6efc000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
08-11 10:49:14.922  6833  6833 W art     : b6efc000-b6efd000 rw-p 00000000 00:00 0          [anon:linker_alloc_64]
08-11 10:49:14.922  6833  6833 W art     : b6efd000-b6efe000 rw-p 00000000 00:00 0          [anon:linker_alloc]
,08-11 10:49:14.922  6833  6833 W art     : b6efe000-b6f01000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-11 10:49:14.922  6833  6833 W art     : b6f01000-b6f26000 r-xp 00000000 b3:17 2179       /system/lib/libbinder.so
08-11 10:49:14.922  6833  6833 W art     : b6f26000-b6f27000 ---p 00000000 00:00 0 
08-11 10:49:14.922  6833  6833 W art     : b6f27000-b6f2e000 r--p 00025000 b3:17 2179       /system/lib/libbinder.so
08-11 10:49:14.922  6833  6833 W art     : b6f2e000-b6f2f000 rw-p 0002c000 b3:17 2179       /system/lib/libbinder.so
08-11 10:49:14.922  6833  6833 W art     : b6f2f000-b6f36000 r-xp 00000000 b3:17 2644       /system/lib/liblog.so
08-11 10:49:14.922  6833  6833 W art     : b6f36000-b6f37000 r--p 00006000 b3:17 2644       /system/lib/liblog.so
08-11 10:49:14.922  6833  6833 W art     : b6f37000-b6f38000 rw-p 00007000 b3:17 2644       /system/lib/liblog.so
,08-11 10:49:14.922  6833  6833 W art     : b6f38000-b6f39000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-11 10:49:14.922  6833  6833 W art     : b6f39000-b6f51000 r-xp 00000000 b3:17 918        /system/lib/libutils.so
08-11 10:49:14.922  6833  6833 W art     : b6f51000-b6f52000 ---p 00000000 00:00 0 
08-11 10:49:14.922  6833  6833 W art     : b6f52000-b6f53000 r--p 00018000 b3:17 918        /system/lib/libutils.so
08-11 10:49:14.922  6833  6833 W art     : b6f53000-b6f54000 rw-p 00019000 b3:17 918        /system/lib/libutils.so
08-11 10:49:14.922  6833  6833 W art     : b6f54000-b6f62000 r-xp 00000000 b3:17 2710       /system/lib/libcutils.so
08-11 10:49:14.922  6833  6833 W art     : b6f62000-b6f63000 ---p 00000000 00:00 0 
08-11 10:49:14.922  6833  6833 W art     : b6f63000-b6f64000 r--p 0000e000 b3:17 2710       /system/lib/libcutils.so
,08-11 10:49:14.922  6833  6833 W art     : b6f64000-b6f65000 rw-p 0000f000 b3:17 2710       /system/lib/libcutils.so
08-11 10:49:14.922  6833  6833 W art     : b6f65000-b6f66000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
08-11 10:49:14.922  6833  6833 W art     : b6f66000-b6f68000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-11 10:49:14.922  6833  6833 W art     : b6f68000-b6f69000 rw-p 00000000 00:00 0          [anon:linker_alloc]
08-11 10:49:14.922  6833  6833 W art     : b6f69000-b6f6a000 rw-p 00000000 00:00 0          [anon:linker_alloc_vector]
08-11 10:49:14.922  6833  6833 W art     : b6f6a000-b6f6b000 rw-p 00000000 00:00 0          [anon:linker_alloc_32]
08-11 10:49:14.922  6833  6833 W art     : b6f6b000-b6f6c000 r--p 00000000 00:00 0          [anon:linker_alloc]
08-11 10:49:14.922  6833  6833 W art     : b6f6c000-b6f8c000 r--s 00000000 00:0b 8195       /dev/__properties__
,08-11 10:49:14.922  6833  6833 W art     : b6f8c000-b6f8d000 r--p 00000000 00:00 0 
08-11 10:49:14.922  6833  6833 W art     : b6f8d000-b6f8e000 ---p 00000000 00:00 0 
08-11 10:49:14.922  6833  6833 W art     : b6f8e000-b6f90000 rw-p 00000000 00:00 0          [anon:thread signal stack]
08-11 10:49:14.922  6833  6833 W art     : b6f90000-b6f91000 r-xp 00000000 00:00 0          [sigpage]
08-11 10:49:14.922  6833  6833 W art     : b6f91000-b6fac000 r-xp 00000000 b3:17 2770       /system/bin/linker
08-11 10:49:14.922  6833  6833 W art     : b6fac000-b6fad000 r--p 0001a000 b3:17 2770       /system/bin/linker
08-11 10:49:14.922  6833  6833 W art     : b6fad000-b6faf000 rw-p 0001b000 b3:17 2770       /system/bin/linker
08-11 10:49:14.922  6833  6833 W art     : b6faf000-b6fb1000 rw-p 00000000 00:00 0 
,08-11 10:49:14.922  6833  6833 W art     : b6fb1000-b6fb6000 r-xp 00000000 b3:17 978        /system/bin/app_process32
08-11 10:49:14.922  6833  6833 W art     : b6fb6000-b6fb7000 r--p 00004000 b3:17 978        /system/bin/app_process32
08-11 10:49:14.922  6833  6833 W art     : b6fb7000-b6fb8000 rw-p 00000000 00:00 0 
08-11 10:49:14.922  6833  6833 W art     : bea12000-bea33000 rw-p 00000000 00:00 0          [stack]
08-11 10:49:14.922  6833  6833 W art     : ffff0000-ffff1000 r-xp 00000000 00:00 0          [vectors]
,08-11 10:49:15.002  6833  6833 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,08-11 10:49:15.052  6833  6833 I Radio-JNI: register_android_hardware_Radio DONE
,08-11 10:49:15.062  6833  6833 E AffinityControl: AffinityControl: registerfunction enter
,08-11 10:49:15.082  6833  6833 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-11 10:49:15.092   781  1742 D PackageManager: START PACKAGE DELETE: observer{110979387}
08-11 10:49:15.092   781  1742 D PackageManager: pkg{<packageName>}
08-11 10:49:15.092   781  1742 D PackageManager: user{0}
08-11 10:49:15.092   781  1742 D PackageManager: caller{2000}
08-11 10:49:15.092   781  1742 D PackageManager: flags{2}
,08-11 10:49:15.092   781  1742 D PersonaManagerService: isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
08-11 10:49:15.092   781  1742 D PersonaManagerService: isFromApprovedUnInstaller: isApproved : true
08-11 10:49:15.092   781  1742 D PersonaManagerService: isFromApprovedUnInstaller: isApproved before exit: true
08-11 10:49:15.092   781  1742 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
08-11 10:49:15.092   781  1742 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
,08-11 10:49:15.092   781  1015 D PackageManager: [MSG] DELETE_PACKAGE_AS_USER
08-11 10:49:15.092   781  1015 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:0
,08-11 10:49:15.092   781  1015 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:-1
08-11 10:49:15.092   781  1015 D ApplicationPolicy: getApplicationUninstallationEnabled
08-11 10:49:15.092   781  1015 D ApplicationPolicy: getApplicationUninstallationEnabled :  enabled true
,08-11 10:49:15.092   781  1015 I PackageManager: !@  calling am.removeDeletedPkgsFromLru from PMS
08-11 10:49:15.102   781  1015 D ActivityManager: removeDeletedPkgsFromLruStats called in AMS...com.test.thalitest
,08-11 10:49:15.102   781  1015 D PackageManager: !@killApplicatoin: 10004, uninstall pkg
08-11 10:49:15.102   781  1015 I PackageManager: !@  calling am.removeDeletedPkgsFromLru from PMS
08-11 10:49:15.102   781   878 I ActivityManager: Force stopping com.test.thalitest appid=10004 user=-1: uninstall pkg
08-11 10:49:15.102   781  1015 D ActivityManager: removeDeletedPkgsFromLruStats called in AMS...com.test.thalitest
,08-11 10:49:15.102   781   878 I ActivityManager: Killing 6443:com.test.thalitest/u0a4 (adj 1): stop com.test.thalitest cause uninstall pkg
,08-11 10:49:15.102   781   878 E ActivityManager: exception=android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
08-11 10:49:15.102   781   878 D ActivityManager: isAutoRunBlockedApp:: com.test.thalitest, Auto Run ON
,08-11 10:49:15.122  6842  6842 E Zygote  : v2
08-11 10:49:15.122   781   878 I ActivityManager: Start proc 6842:com.test.thalitest/u0a4 for activity com.test.thalitest/.MainActivity
08-11 10:49:15.122  6842  6842 I libpersona: KNOX_SDCARD checking this for 10004
08-11 10:49:15.122  6842  6842 I libpersona: KNOX_SDCARD not a persona
,08-11 10:49:15.132  6842  6842 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-11 10:49:15.132   781   878 I ActivityManager:   Force finishing activity ActivityRecord{50d1185 u0 com.test.thalitest/.MainActivity t153}
08-11 10:49:15.132  6842  6842 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,08-11 10:49:15.132  6842  6842 E Zygote  : accessInfo : 0
08-11 10:49:15.132  6842  6842 W SELinux : SELinux: seapp_context_lookup: seinfo=default, level=s0:c512,c768, pkgname=com.test.thalitest 
,08-11 10:49:15.132   293   366 I SurfaceFlinger: id=17 Removed NainActivit (4/10)
,08-11 10:49:15.132   293   293 D libEGL  : eglTerminate EGLDisplay = 0xbef4938c
08-11 10:49:15.132   293   293 D libEGL  : eglTerminate EGLDisplay = 0xbef4938c
,08-11 10:49:15.152  6842  6842 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-11 10:49:15.152  6842  6842 D ActivityThread: Added TimaKeyStore provider
,08-11 10:49:15.162   781  1015 D AASAinstall: there is not AASApackages.xml file
,08-11 10:49:15.182   781  1278 D GraphicsStats: Buffer count: 5
,08-11 10:49:15.182   781  1452 D ConnectivityService: ConnectivityService NetworkRequestInfo binderDied(NetworkRequest [ id=13, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], android.os.BinderProxy@5b7f858)
,08-11 10:49:15.192   781  1333 D ConnectivityService: releasing NetworkRequest NetworkRequest [ id=13, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-11 10:49:15.192   781  1333 D ConnectivityService: sending notification RELEASED for NetworkRequest [ id=13, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-11 10:49:15.192   781  1333 E ConnectivityService: RemoteException caught trying to send a callback msg for NetworkRequest [ id=13, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-11 10:49:15.452   781  1015 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/packages.xml.bak
,08-11 10:49:15.472   781  1015 W PackageSettings: Skipping PackageSetting{e938db6 com.example.hello/10192} due to missing metadata
,08-11 10:49:15.542   781  1015 W System.err: remove failed: ENOENT (No such file or directory) : /data/system/users/0/package-restrictions.xml.bak
,08-11 10:49:15.552   781  1744 I ActivityManager: Killing 5828:com.samsung.android.app.watchmanagerstub/u0a111 (adj 15): DHA:empty #37
,08-11 10:49:15.562   329   329 W keystore: ENTER clear_uid from uid 1000 for 10004
,08-11 10:49:15.562   781  1015 I art     : Starting a blocking GC Explicit
,08-11 10:49:15.572  6842  6842 W ResourcesManager: getTopLevelResources: /data/app/com.test.thalitest-1/base.apk / 1.0 running in com.test.thalitest rsrc of package null
,08-11 10:49:15.572   781  1758 D ActivityManager: isAutoRunBlockedApp:: com.samsung.android.app.watchmanagerstub, Auto Run ON
,08-11 10:49:15.592  6842  6842 W ContextImpl: Unable to create files subdir /data/user/0/com.test.thalitest/cache
,08-11 10:49:15.592  6842  6842 V ActivityThread: Unable to initialize "java.io.tmpdir" property due to missing cache directory
,08-11 10:49:15.592  6842  6842 W ContextImpl: Unable to create files subdir /data/user/0/com.test.thalitest/code_cache
08-11 10:49:15.592  6842  6842 E ActivityThread: Unable to setupGraphicsSupport due to missing code-cache directory
,08-11 10:49:15.612  6842  6842 D AndroidRuntime: Shutting down VM
,08-11 10:49:15.612  6842  6842 E AndroidRuntime: FATAL EXCEPTION: main
08-11 10:49:15.612  6842  6842 E AndroidRuntime: Process: com.test.thalitest, PID: 6842
08-11 10:49:15.612  6842  6842 E AndroidRuntime: java.lang.RuntimeException: Unable to instantiate application android.app.Application: java.lang.IllegalStateException: Unable to get package info for com.test.thalitest; is package not installed?
08-11 10:49:15.612  6842  6842 E AndroidRuntime: 	at android.app.LoadedApk.makeApplication(LoadedApk.java:676)
08-11 10:49:15.612  6842  6842 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:6289)
08-11 10:49:15.612  6842  6842 E AndroidRuntime: 	at android.app.ActivityThread.access$1800(ActivityThread.java:221)
08-11 10:49:15.612  6842  6842 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1860)
08-11 10:49:15.612  6842  6842 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-11 10:49:15.612  6842  6842 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:158)
08-11 10:49:15.612  6842  6842 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:7224)
08-11 10:49:15.612  6842  6842 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-11 10:49:15.612  6842  6842 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1230)
08-11 10:49:15.612  6842  6842 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1120)
08-11 10:49:15.612  6842  6842 E AndroidRuntime: Caused by: java.lang.IllegalStateException: Unable to get package info for com.test.thalitest; is package not installed?
08-11 10:49:15.612  6842  6842 E AndroidRuntime: 	at android.app.LoadedApk.initializeJavaContextClassLoader(LoadedApk.java:485)
08-11 10:49:15.612  6842  6842 E AndroidRuntime: 	at android.app.LoadedApk.makeApplication(LoadedApk.java:661)
08-11 10:49:15.612  6842  6842 E AndroidRuntime: 	... 9 more
,08-11 10:49:15.642   781   878 I ActivityManager: Start proc 6869:com.samsung.android.sm/1000 for broadcast-3 com.samsung.android.sm/.common.SmartManagerReceiver
,08-11 10:49:15.642  6842  6842 I Process : Sending signal. PID: 6842 SIG: 9
,08-11 10:49:15.642  6869  6869 E Zygote  : v2
08-11 10:49:15.642  6869  6869 I libpersona: KNOX_SDCARD checking this for 1000
08-11 10:49:15.642  6869  6869 I libpersona: KNOX_SDCARD not a persona
08-11 10:49:15.642  6869  6869 I SELinux : Function: selinux_compare_spd_ram, index[1], SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0-1 ver=51
08-11 10:49:15.642  6869  6869 W SELinux : Function: selinux_compare_spd_ram, index[1], priority [2], priority version is VE=SEPF_SECMOBILE_6.0.1_0011
,08-11 10:49:15.642  6869  6869 E Zygote  : accessInfo : 0
,08-11 10:49:15.672  6869  6869 D TimaKeyStoreProvider: TimaSignature is unavailable
08-11 10:49:15.672  6869  6869 D ActivityThread: Added TimaKeyStore provider
,08-11 10:49:15.682   781  1723 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{90fbdb1 u0 android.intent.action.DROPBOX_ENTRY_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{f65e296 6869:com.samsung.android.sm/1000}
,08-11 10:49:15.682   781  1745 I ActivityManager: Process com.test.thalitest (pid 6842)(adj 9) has died(143,743)
,08-11 10:49:15.682   781  1745 E ActivityManager: exception=android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
08-11 10:49:15.682   781  1745 D ActivityManager: isAutoRunBlockedApp:: com.test.thalitest, Auto Run ON
,08-11 10:49:15.682   781  1745 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:830 com.android.server.am.ActivityManagerService.updateOomAdjLocked:26661 com.android.server.am.ActivityManagerService.appDiedLocked:7558 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1919 android.os.BinderProxy.sendDeathNotice:558 
,08-11 10:49:15.692   781   878 V MARsPolicyManager: executePolicy policy  spcmpolicy(1) reason Adj 14 BG Killed
,08-11 10:49:15.692   781   878 V MARsPolicyManager: CurrentImportantPackage com.test.thalitest -in latest protected packageslist for SPCM!
,08-11 10:49:15.692  6869  6869 W ResourcesManager: getTopLevelResources: /system/priv-app/SmartManager_v3/SmartManager_v3.apk / 1.0 running in com.samsung.android.sm rsrc of package null
,08-11 10:49:15.732  6869  6869 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1305 android.content.ContextWrapper.startService:606 android.content.ContextWrapper.startService:606 com.samsung.android.sm.common.SmartManagerReceiver.b:259 com.samsung.android.sm.common.SmartManagerReceiver.onReceive:107 
,08-11 10:49:15.742   781  1744 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{90fbdb1 u0 android.intent.action.DROPBOX_ENTRY_ADDED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{ac945c9 4410:com.google.android.gms/u0a11}
,08-11 10:49:15.772   781  1015 I art     : Explicit concurrent mark sweep GC freed 113590(5MB) AllocSpace objects, 19(380KB) LOS objects, 27% free, 42MB/58MB, paused 1.872ms total 208.490ms
08-11 10:49:15.772   781   792 I art     : WaitForGcToComplete blocked for 196.125ms for cause Background
,08-11 10:49:15.792   781  1015 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,08-11 10:49:15.792   781  1015 D AASAuninstall: userId = 0, info.removedAppID = 10004, info.uid = 10004, packageName = com.test.thalitest
08-11 10:49:15.792   781  1015 D AASAinstall: there is not AASApackages.xml file
,08-11 10:49:15.792   781  1015 D PackageManager: result of delete: 1{110979387}
,08-11 10:49:15.792  6833  6833 I art     : System.exit called, status: 0
08-11 10:49:15.792  6833  6833 I AndroidRuntime: VM exiting with result code 0.
08-11 10:49:15.802   781  1015 D PackageManager: [MSG] START_CLEANING_PACKAGE packageName{com.test.thalitest}
08-11 10:49:15.802   781  1015 D PackageManager: userId{-1}
08-11 10:49:15.802   781  1015 D PackageManager: andCode{true}
,08-11 10:49:15.812   781  1015 I ActivityManager: Force stopping com.test.thalitest appid=10004 user=0: pkg removed
,08-11 10:49:15.832  6086  6894 W System.err: remove failed: ENOENT (No such file or directory) : /storage/emulated/0/Android/data/com.test.thalitest
,08-11 10:49:15.832  6086  6894 W System.err: remove failed: ENOENT (No such file or directory) : /storage/emulated/0/Android/media/com.test.thalitest
,08-11 10:49:15.832  6086  6894 W System.err: remove failed: ENOENT (No such file or directory) : /storage/emulated/0/Android/obb/com.test.thalitest
,08-11 10:49:15.862   781   781 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.gms-2/base.apk / 1.0 running in null rsrc of package null
,08-11 10:49:15.862  1382  1382 D KeyguardUpdateMonitor: received broadcast android.intent.action.PACKAGE_REMOVED
08-11 10:49:15.862  1382  1382 I PERF    : received broadcast android.intent.action.PACKAGE_REMOVED
,08-11 10:49:15.862   781   781 W ResourcesManager: getTopLevelResources: /data/app/com.google.android.gms-2/base.apk / 1.0 running in null rsrc of package null
,08-11 10:49:15.862   781   781 W ResourcesManager: getTopLevelResources: /system/priv-app/Samsungservice2_xxhdpi/Samsungservice2_xxhdpi.apk / 1.0 running in null rsrc of package null
08-11 10:49:15.862   781   923 W ResourcesManager: getTopLevelResources: /system/priv-app/InputDevices/InputDevices.apk / 1.0 running in null rsrc of package null
,08-11 10:49:15.872   781   923 W ResourcesManager: getTopLevelResources: /system/priv-app/InputDevices/InputDevices.apk / 1.0 running in null rsrc of package null
,08-11 10:49:15.872  1978  1978 E SamsungIME: mOCRHelper is null
,08-11 10:49:15.872   781  1300 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-11 10:49:15.882   781   878 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{f1eae6e u0 android.intent.action.PACKAGE_REMOVED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{84c80c8 4347:com.samsung.klmsagent/u0a18}
,08-11 10:49:15.882   781   781 W ResourcesManager: getTopLevelResources: /system/priv-app/Samsungservice2_xxhdpi/Samsungservice2_xxhdpi.apk / 1.0 running in null rsrc of package null
08-11 10:49:15.882   781   781 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
,08-11 10:49:15.882  2320  2695 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,08-11 10:49:15.892   781   781 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
,08-11 10:49:15.892   781   781 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
08-11 10:49:15.892   781   781 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
,08-11 10:49:15.892   781   781 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
,08-11 10:49:15.892   781   781 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
,08-11 10:49:15.892   781   781 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
08-11 10:49:15.892   781   781 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
,08-11 10:49:15.892   781   781 W ResourcesManager: getTopLevelResources: /system/app/Dropbox/Dropbox.apk / 1.0 running in null rsrc of package null
,08-11 10:49:15.902   781   781 W ResourcesManager: getTopLevelResources: /system/app/Dropbox/Dropbox.apk / 1.0 running in null rsrc of package null
,08-11 10:49:15.902   781   781 W ResourcesManager: getTopLevelResources: /system/app/Gmail2/Gmail2.apk / 1.0 running in null rsrc of package null
,08-11 10:49:15.902  1727  1727 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,08-11 10:49:15.902  4347  4347 I KLMS-2.6.032: : KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver bqHint=4 (has extras) } | timestamp: Thu Aug 11 10:49:15 GMT+02:00 2016
,08-11 10:49:15.902   781   781 W ResourcesManager: getTopLevelResources: /system/app/Gmail2/Gmail2.apk / 1.0 running in null rsrc of package null
,08-11 10:49:15.912   781   781 W ResourcesManager: getTopLevelResources: /system/app/Gmail2/Gmail2.apk / 1.0 running in null rsrc of package null
,08-11 10:49:15.912   781   781 W ResourcesManager: getTopLevelResources: /system/app/Gmail2/Gmail2.apk / 1.0 running in null rsrc of package null
,08-11 10:49:15.912   781   781 W ResourcesManager: getTopLevelResources: /system/app/SecEmail_K/SecEmail_K.apk / 1.0 running in null rsrc of package null
,08-11 10:49:15.912  4347  4347 I KLMS-2.6.032: : KLMSAbstractReciever(): onReceive().END.
,08-11 10:49:15.912   781   781 W ResourcesManager: getTopLevelResources: /system/app/SecEmail_K/SecEmail_K.apk / 1.0 running in null rsrc of package null
,08-11 10:49:15.912   781   781 W ResourcesManager: getTopLevelResources: /system/app/SecEmail_K/SecEmail_K.apk / 1.0 running in null rsrc of package null
,08-11 10:49:15.922   781   781 W ResourcesManager: getTopLevelResources: /system/app/SecEmail_K/SecEmail_K.apk / 1.0 running in null rsrc of package null
,08-11 10:49:15.922   781   781 W ResourcesManager: getTopLevelResources: /system/app/SecEmail_K/SecEmail_K.apk / 1.0 running in null rsrc of package null
08-11 10:49:15.922   781   781 W ResourcesManager: getTopLevelResources: /system/app/SecEmail_K/SecEmail_K.apk / 1.0 running in null rsrc of package null
,08-11 10:49:15.922   781   781 W ResourcesManager: getTopLevelResources: /system/app/SBrowser_4_LATEST/SBrowser_4_LATEST.apk / 1.0 running in null rsrc of package null
,08-11 10:49:15.922  4347  4347 I KLMS-2.6.032: : KLMSIntentService(): onCreate()
08-11 10:49:15.922  4347  4347 I KLMS-2.6.032: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,08-11 10:49:15.922   781   781 W ResourcesManager: getTopLevelResources: /system/app/SBrowser_4_LATEST/SBrowser_4_LATEST.apk / 1.0 running in null rsrc of package null
,08-11 10:49:15.922   781   796 V BroadcastQueue: [background] Process cur broadcast BroadcastRecord{f1eae6e u0 android.intent.action.PACKAGE_REMOVED qIdx=4}, state= (APP_RECEIVE) DELIVERED for app ProcessRecord{56c70d2 781:system/1000}
,08-11 10:49:15.922   781   781 W ResourcesManager: getTopLevelResources: /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk / 1.0 running in null rsrc of package null
,08-11 10:49:15.922  4347  4347 I KLMS-2.6.032: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,08-11 10:49:15.922  4347  6901 I KLMS-2.6.032: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.service.KLMSIntentService bqHint=4 (has extras) }
08-11 10:49:15.922  4347  6901 D KLMS-2.6.032: : KLMSIntentService(): PACKAGE_REMOVED
,08-11 10:49:15.932  3254  3269 W ResourcesManager: getTopLevelResources: /system/app/PlusOne/PlusOne.apk / 1.0 running in com.android.contacts rsrc of package null
,08-11 10:49:15.932  4347  6901 I KLMS-2.6.032: : Systemprocess(): listeningToPackageRemoved().START
,08-11 10:49:15.932  4347  6901 I KLMS-2.6.032: : Systemprocess(): listeningToPackageRemoved().packageName: com.test.thalitest
08-11 10:49:15.932  4347  6901 I KLMS-2.6.032: : Systemprocess(): listeningToPackageRemovedforELM().START - com.test.thalitest
08-11 10:49:15.932  4347  6901 I KLMS-2.6.032: : MDMBridge(): getAllLicenseInfoFromSDK()
08-11 10:49:15.932   781   781 W ResourcesManager: getTopLevelResources: /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk / 1.0 running in null rsrc of package null
,08-11 10:49:15.932   781   781 W ResourcesManager: getTopLevelResources: /system/priv-app/SHealth4/SHealth4.apk / 1.0 running in null rsrc of package null
,08-11 10:49:15.932  3254  3269 W ResourcesManager: getTopLevelResources: /system/app/PlusOne/PlusOne.apk / 1.0 running in com.android.contacts rsrc of package null
,08-11 10:49:15.932  3254  3269 W ResourcesManager: getTopLevelResources: /system/app/PlusOne/PlusOne.apk / 1.0 running in com.android.contacts rsrc of package null
,08-11 10:49:15.932  3254  3269 W ResourcesManager: getTopLevelResources: /system/app/PlusOne/PlusOne.apk / 1.0 running in com.android.contacts rsrc of package null
,08-11 10:49:15.932   781   781 W ResourcesManager: getTopLevelResources: /system/priv-app/SHealth4/SHealth4.apk / 1.0 running in null rsrc of package null
08-11 10:49:15.932   781   781 W ResourcesManager: getTopLevelResources: /system/priv-app/SHealth4/SHealth4.apk / 1.0 running in null rsrc of package null
,08-11 10:49:15.932   781   781 W ResourcesManager: getTopLevelResources: /system/priv-app/SHealth4/SHealth4.apk / 1.0 running in null rsrc of package null
08-11 10:49:15.932   781   781 W ResourcesManager: getTopLevelResources: /system/priv-app/SCloudService/SCloudService.apk / 1.0 running in null rsrc of package null
,08-11 10:49:15.942   781  1452 D SecContentProvider2: query(), uri = 11 selection = getMyKnoxAdmin
,08-11 10:49:15.942   781   781 W ResourcesManager: getTopLevelResources: /system/priv-app/SCloudService/SCloudService.apk / 1.0 running in null rsrc of package null
,08-11 10:49:15.942   781   781 W ResourcesManager: getTopLevelResources: /system/priv-app/SCloudService/SCloudService.apk / 1.0 running in null rsrc of package null
08-11 10:49:15.942  4347  6901 I KLMS-2.6.032: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,08-11 10:49:15.942  4347  6901 I KLMS-2.6.032: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,08-11 10:49:15.942   781   781 W ResourcesManager: getTopLevelResources: /system/priv-app/SCloudService/SCloudService.apk / 1.0 running in null rsrc of package null
08-11 10:49:15.942   781   781 W ResourcesManager: getTopLevelResources: /system/priv-app/SCloudService/SCloudService.apk / 1.0 running in null rsrc of package null
,08-11 10:49:15.942   781   781 W ResourcesManager: getTopLevelResources: /system/priv-app/SCloudService/SCloudService.apk / 1.0 running in null rsrc of package null
,08-11 10:49:15.942   781   781 W ResourcesManager: getTopLevelResources: /system/priv-app/SCloudService/SCloudService.apk / 1.0 running in null rsrc of package null
08-11 10:49:15.942   781   781 W ResourcesManager: getTopLevelResources: /system/priv-app/SCloudService/SCloudService.apk / 1.0 running in null rsrc of package null
,08-11 10:49:15.942   781   781 W ResourcesManager: getTopLevelResources: /system/priv-app/SCloudService/SCloudService.apk / 1.0 running in null rsrc of package null
08-11 10:49:15.942   781   781 W ResourcesManager: getTopLevelResources: /system/priv-app/SCloudService/SCloudService.apk / 1.0 running in null rsrc of package null
,08-11 10:49:15.942   781   781 W ResourcesManager: getTopLevelResources: /system/priv-app/SCloudService/SCloudService.apk / 1.0 running in null rsrc of package null
08-11 10:49:15.942   781   781 W ResourcesManager: getTopLevelResources: /system/priv-app/SCloudService/SCloudService.apk / 1.0 running in null rsrc of package null
,08-11 10:49:15.942   781   781 W ResourcesManager: getTopLevelResources: /system/priv-app/SCloudService/SCloudService.apk / 1.0 running in null rsrc of package null
,08-11 10:49:15.942   781   875 W System.err: remove failed: EROFS (Read-only file system) : /data/system/users/0/runtime-permissions.xml
08-11 10:49:15.942   781   875 W System.err: rename failed: EROFS (Read-only file system) : /data/system/users/0/runtime-permissions.xml.bak -> /data/system/users/0/runtime-permissions.xml
08-11 10:49:15.942   781   781 W ResourcesManager: getTopLevelResources: /system/priv-app/SCloudService/SCloudService.apk / 1.0 running in null rsrc of package null
08-11 10:49:15.942   781   781 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
,08-11 10:49:15.942   781   781 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
08-11 10:49:15.942   781   781 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
,08-11 10:49:15.942   781   781 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
08-11 10:49:15.952   781   781 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
08-11 10:49:15.952   781   781 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
08-11 10:49:15.952   781   781 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
,08-11 10:49:15.952   781   781 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
08-11 10:49:15.952   781   781 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
08-11 10:49:15.952  4347  6901 I KLMS-2.6.032: : MDMBridge(): getAllLicenseInfoFromSDK()
08-11 10:49:15.952   781   781 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
08-11 10:49:15.952   781   781 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
,08-11 10:49:15.952   781   781 W ResourcesManager: getTopLevelResources: /system/priv-app/SNS_v2/SNS_v2.apk / 1.0 running in null rsrc of package null
08-11 10:49:15.952   781   781 W ResourcesManager: getTopLevelResources: /system/priv-app/SecGallery2014/SecGallery2014.apk / 1.0 running in null rsrc of package null
,08-11 10:49:15.952  4347  6901 D KLMS-2.6.032: : Systemprocess(): arrayLicenseInfo is null
,08-11 10:49:15.952   781   875 W ResourcesManager: getTopLevelResources: /system/priv-app/Velvet/Velvet.apk / 1.0 running in null rsrc of package null
,08-11 10:49:15.952  4347  6901 W SQLiteLog: (28) failed to open "/data/user/0/com.samsung.klmsagent/databases/klms.db" with flag (131138) and mode_t (0) due to error (30)
,08-11 10:49:15.962   781   781 W ResourcesManager: getTopLevelResources: /system/priv-app/SecGallery2014/SecGallery2014.apk / 1.0 running in null rsrc of package null
,08-11 10:49:15.962   781   781 W ResourcesManager: getTopLevelResources: /system/app/Books/Books.apk / 1.0 running in null rsrc of package null
,08-11 10:49:15.962   781  1324 W System.err: rename failed: EROFS (Read-only file system) : /data/system/netpolicy.xml -> /data/system/netpolicy.xml.bak
,08-11 10:49:15.962   781  1323 V NetworkStats: removeUidsLocked() for UIDs [10004]
08-11 10:49:15.962   781  1323 D NtpTrustedTime: currentTimeMillis() cache hit
08-11 10:49:15.962   781  1323 V NetworkStats: performPollLocked(flags=0x3)
08-11 10:49:15.962   781  1324 W AtomicFile: Couldn't rename file /data/system/netpolicy.xml to backup file /data/system/netpolicy.xml.bak
,08-11 10:49:15.962   781   781 W ResourcesManager: getTopLevelResources: /system/app/Books/Books.apk / 1.0 running in null rsrc of package null
,08-11 10:49:15.962   781   781 W ResourcesManager: getTopLevelResources: /system/app/Chrome/Chrome.apk / 1.0 running in null rsrc of package null
,08-11 10:49:15.962  1714  6903 W ResourcesManager: getTopLevelResources: /system/priv-app/SHealth4/SHealth4.apk / 1.0 running in com.android.nfc rsrc of package null
,08-11 10:49:15.962  1714  6903 W ResourcesManager: getTopLevelResources: /system/priv-app/SHealth4/SHealth4.apk / 1.0 running in com.android.nfc rsrc of package null
,08-11 10:49:15.962  1714  6903 W ResourcesManager: getTopLevelResources: /system/priv-app/Tag/Tag.apk / 1.0 running in com.android.nfc rsrc of package null
08-11 10:49:15.962  1714  6903 W ResourcesManager: getTopLevelResources: /system/priv-app/Tag/Tag.apk / 1.0 running in com.android.nfc rsrc of package null
08-11 10:49:15.962  1714  6903 D RegisteredComponentCache: Collect Tech packages for Knox
,08-11 10:49:15.962   781  1323 V NetworkStats: performPollLocked() took 7ms
08-11 10:49:15.962   781  1323 D NtpTrustedTime: currentTimeMillis() cache hit
,08-11 10:49:15.972   781  1324 D NtpTrustedTime: currentTimeMillis() cache hit
08-11 10:49:15.972   781  1324 D NtpTrustedTime: currentTimeMillis() cache hit
,08-11 10:49:15.972   781   781 W ResourcesManager: getTopLevelResources: /system/app/Chrome/Chrome.apk / 1.0 running in null rsrc of package null
,08-11 10:49:15.972   781   781 W ResourcesManager: getTopLevelResources: /system/app/Drive/Drive.apk / 1.0 running in null rsrc of package null
,08-11 10:49:15.982   781   781 W ResourcesManager: getTopLevelResources: /system/app/Drive/Drive.apk / 1.0 running in null rsrc of package null
08-11 10:49:15.982   781   781 W ResourcesManager: getTopLevelResources: /system/app/Dropbox/Dropbox.apk / 1.0 running in null rsrc of package null
,08-11 10:49:15.982   781   781 W ResourcesManager: getTopLevelResources: /system/app/Dropbox/Dropbox.apk / 1.0 running in null rsrc of package null
08-11 10:49:15.982   781   781 W ResourcesManager: getTopLevelResources: /system/app/EditorsDocs/EditorsDocs.apk / 1.0 running in null rsrc of package null
,08-11 10:49:15.982  4347  6901 E SQLiteDatabase: Failed to open database '/data/user/0/com.samsung.klmsagent/databases/klms.db'.
08-11 10:49:15.982  4347  6901 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-11 10:49:15.982  4347  6901 E SQLiteDatabase: #################################################################
08-11 10:49:15.982  4347  6901 E SQLiteDatabase: Error Code : 0 (SQLITE_OK)
08-11 10:49:15.982  4347  6901 E SQLiteDatabase: Caused By : not an error (code 0): Could not open the database in read/write mode.
08-11 10:49:15.982  4347  6901 E SQLiteDatabase: #################################################################
08-11 10:49:15.982  4347  6901 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-11 10:49:15.982  4347  6901 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:283)
08-11 10:49:15.982  4347  6901 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:210)
08-11 10:49:15.982  4347  6901 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
08-11 10:49:15.982  4347  6901 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
08-11 10:49:15.982  4347  6901 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
08-11 10:49:15.982  4347  6901 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
08-11 10:49:15.982  4347  6901 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
08-11 10:49:15.982  4347  6901 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
08-11 10:49:15.982  4347  6901 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:633)
08-11 10:49:15.982  4347  6901 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:283)
08-11 10:49:15.982  4347  6901 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-11 10:49:15.982  4347  6901 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-11 10:49:15.982  4347  6901 E SQLiteDatabase: 	at com.samsung.klmsagent.database.DataSource.fetchData(DataSource.java:88)
08-11 10:49:15.982  4347  6901 E SQLiteDatabase: 	at com.samsung.klmsagent.util.DataBaseUtils.checkKnoxLicenseActivationRecord(DataBaseUtils.java:323)
08-11 10:49:15.982  4347  6901 E SQLiteDatabase: 	at com.samsung.klmsagent.process.Systemprocess.listeningToPackageRemovedforELM(Systemprocess.java:595)
08-11 10:49:15.982  4347  6901 E SQLiteDatabase: 	at com.samsung.klmsagent.process.Systemprocess.listeningToPackageRemoved(Systemprocess.java:532)
08-11 10:49:15.982  4347  6901 E SQLiteDatabase: 	at com.samsung.klmsagent.service.KLMSIntentService.onHandleIntent(KLMSIntentService.java:173)
08-11 10:49:15.982  4347  6901 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-11 10:49:15.982  4347  6901 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-11 10:49:15.982  4347  6901 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:158)
08-11 10:49:15.982  4347  6901 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-11 10:49:15.982  4347  6901 E SQLiteOpenHelper: Couldn't open klms.db for writing (will try read-only):
08-11 10:49:15.982  4347  6901 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-11 10:49:15.982  4347  6901 E SQLiteOpenHelper: #################################################################
08-11 10:49:15.982  4347  6901 E SQLiteOpenHelper: Error Code : 0 (SQLITE_OK)
08-11 10:49:15.982  4347  6901 E SQLiteOpenHelper: Caused By : not an error (code 0): Could not open the database in read/write mode.
08-11 10:49:15.982  4347  6901 E SQLiteOpenHelper: #################################################################
08-11 10:49:15.982  4347  6901 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-11 10:49:15.982  4347  6901 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:283)
08-11 10:49:15.982  4347  6901 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:210)
08-11 10:49:15.982  4347  6901 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
08-11 10:49:15.982  4347  6901 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
08-11 10:49:15.982  4347  6901 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
08-11 10:49:15.982  4347  6901 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
08-11 10:49:15.982  4347  6901 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
08-11 10:49:15.982  4347  6901 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
08-11 10:49:15.982  4347  6901 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:633)
08-11 10:49:15.982  4347  6901 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:283)
08-11 10:49:15.982  4347  6901 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-11 10:49:15.982  4347  6901 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-11 10:49:15.982  4347  6901 E SQLiteOpenHelper: 	at com.samsung.klmsagent.database.DataSource.fetchData(DataSource.java:88)
08-11 10:49:15.982  4347  6901 E SQLiteOpenHelper: 	at com.samsung.klmsagent.util.DataBaseUtils.checkKnoxLicenseActivationRecord(DataBaseUtils.java:323)
08-11 10:49:15.982  4347  6901 E SQLiteOpenHelper: 	at com.samsung.klmsagent.process.Systemprocess.listeningToPackageRemovedforELM(Systemprocess.java:595)
08-11 10:49:15.982  4347  6901 E SQLiteOpenHelper: 	at com.samsung.klmsagent.process.Systemprocess.listeningToPackageRemoved(Systemprocess.java:532)
08-11 10:49:15.982  4347  6901 E SQLiteOpenHelper: 	at com.samsung.klmsagent.service.KLMSIntentService.onHandleIntent(KLMSIntentService.java:173)
08-11 10:49:15.982  4347  6901 E SQLiteOpenHelper: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-11 10:49:15.982  4347  6901 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-11 10:49:15.982  4347  6901 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:158)
08-11 10:49:15.982  4347  6901 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-11 10:49:15.982  4347  6901 W SQLiteOpenHelper: Opened klms.db in read-only mode
08-11 10:49:15.992   781  1366 W System.err: remove failed: EROFS (Read-only file system) : /data/system/recent_tasks/153_task.xml
08-11 10:49:15.992  4347  6901 D KLMS-2.6.032: : DataSource(): Fetched Data from data base count : 0
08-11 10:49:15.992  4347  6901 W System.err: mkdir failed: EEXIST (File exists) : /data/user/0/com.samsung.klmsagent/shared_prefs
08-11 10:49:15.992   781   781 W ResourcesManager: getTopLevelResources: /system/app/EditorsDocs/EditorsDocs.apk / 1.0 running in null rsrc of package null
08-11 10:49:15.992   781   781 W ResourcesManager: getTopLevelResources: /system/app/Gmail2/Gmail2.apk / 1.0 running in null rsrc of package null
08-11 10:49:15.992  4347  6901 E SharedPreferencesImpl: Couldn't create directory for SharedPreferences file /data/user/0/com.samsung.klmsagent/shared_prefs/klmsagent.preferences.xml
08-11 10:49:16.002   781   781 W ResourcesManager: getTopLevelResources: /system/app/Gmail2/Gmail2.apk / 1.0 running in null rsrc of package null
08-11 10:49:16.002   781   781 W ResourcesManager: getTopLevelResources: /system/app/Gmail2/Gmail2.apk / 1.0 running in null rsrc of package null
08-11 10:49:16.002   781   781 W ResourcesManager: getTopLevelResources: /system/app/Gmail2/Gmail2.apk / 1.0 running in null rsrc of package null
08-11 10:49:16.002   781   781 W ResourcesManager: getTopLevelResources: /system/app/Gmail2/Gmail2.apk / 1.0 running in null rsrc of package null
08-11 10:49:16.002   781   781 W ResourcesManager: getTopLevelResources: /system/app/Gmail2/Gmail2.apk / 1.0 running in null rsrc of package null
08-11 10:49:16.002   781   781 W ResourcesManager: getTopLevelResources: /system/app/GoogleCalendarSyncAdapter/GoogleCalendarSyncAdapter.apk / 1.0 running in null rsrc of package null
08-11 10:49:16.002   781   875 W ResourcesManager: getTopLevelResources: /system/priv-app/Velvet/Velvet.apk / 1.0 running in null rsrc of package null
08-11 10:49:16.002   781   781 W ResourcesManager: getTopLevelResources: /system/app/GoogleCalendarSyncAdapter/GoogleCalendarSyncAdapter.apk / 1.0 running in null rsrc of package null
08-11 10:49:16.002   781   781 W ResourcesManager: getTopLevelResources: /system/app/GoogleContactsSyncAdapter/GoogleContactsSyncAdapter.apk / 1.0 running in null rsrc of package null
08-11 10:49:16.002   781   875 W ResourcesManager: getTopLevelResources: /system/app/SamsungIME/SamsungIME.apk / 1.0 running in null rsrc of package null
08-11 10:49:16.012   781  1758 D SettingsProvider: isChangeAllowed() : name = klm_eula_shown
08-11 10:49:16.012   781  1758 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-11 10:49:16.012   781  1758 D SecContentProvider: query(), uri = 17 selection = isSettingsChangesAllowed
08-11 10:49:16.012   781  1758 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-11 10:49:16.012   781  1758 D SettingsProvider: selectionArgs: false
08-11 10:49:16.012   781  1758 D SettingsProvider: selectionArgs: 10018
08-11 10:49:16.012   781  1758 D SettingsProvider: ret = -1
08-11 10:49:16.012  4347  6901 I KLMS-2.6.032: : Systemprocess(): listeningToPackageRemovedforELM().END
08-11 10:49:16.012  4347  6901 I KLMS-2.6.032: : Systemprocess(): listeningToPackageRemovedforKLM().START - com.test.thalitest
08-11 10:49:16.012   781  1300 I EventHub: Removing device '/dev/input/event4' due to inotify event
08-11 10:49:16.012   781  1323 F libc    : Fatal signal 7 (SIGBUS), code 2, fault addr 0x738d9000 in tid 1323 (NetworkStats)
08-11 10:49:16.012  2329  2329 E audit_log: File locking failed. error= Bad file descriptor
08-11 10:49:16.012  2329  2329 E audit_log: File locking failed. error= Bad file descriptor
,08-11 10:49:16.092   327   327 E installd: eof
08-11 10:49:16.092   327   327 E installd: failed to read size
08-11 10:49:16.092   327   327 I installd: closing connection
08-11 10:49:16.092   292   292 I ServiceManager: service 'knox_ccm_policy' died
08-11 10:49:16.092   292   292 I ServiceManager: service 'enterprise_license_policy' died
08-11 10:49:16.092   292   292 I ServiceManager: service 'application_policy' died
08-11 10:49:16.092   292   292 I ServiceManager: service 'wifi_policy' died
08-11 10:49:16.092   292   292 I ServiceManager: service 'phone_restriction_policy' died
08-11 10:49:16.092   292   292 I ServiceManager: service 'remoteinjection' died
08-11 10:49:16.092   292   292 I ServiceManager: service 'knox_ucsm_policy' died
08-11 10:49:16.092   292   292 I ServiceManager: service 'edm_proxy' died
08-11 10:49:16.092   292   292 I ServiceManager: service 'mum_container_policy' died
08-11 10:49:16.092   292   292 I ServiceManager: service 'enterprise_billing_policy' died
08-11 10:49:16.092   292   292 I ServiceManager: service 'otp_service' died
08-11 10:49:16.092   292   292 I ServiceManager: service 'enterprise_shared_device_policy' died
08-11 10:49:16.092   292   292 I ServiceManager: service 'knox_timakeystore_policy' died
08-11 10:49:16.092   292   292 I ServiceManager: service 'enterprise_policy' died
08-11 10:49:16.092   292   292 I ServiceManager: service 'statusbar' died
08-11 10:49:16.092   292   292 I ServiceManager: service 'clipboard' died
08-11 10:49:16.092   292   292 I ServiceManager: service 'clipboardEx' died
08-11 10:49:16.092   292   292 I ServiceManager: service 'network_management' died
08-11 10:49:16.092   292   292 I ServiceManager: service 'audio' died
08-11 10:49:16.092   292   292 I ServiceManager: service 'ABTPersistenceService' died
08-11 10:49:16.092   292   292 I ServiceManager: service 'textservices' died
08-11 10:49:16.092   292   292 I ServiceManager: service 'network_score' died
08-11 10:49:16.092   292   292 I ServiceManager: service 'netstats' died
08-11 10:49:16.092   292   292 I ServiceManager: service 'netpolicy' died
08-11 10:49:16.092   292   292 I ServiceManager: service 'wifip2p' died
08-11 10:49:16.092   292   292 I ServiceManager: service 'wifi' died
08-11 10:49:16.092   292   292 I ServiceManager: service 'wifihs20' died
08-11 10:49:16.092   292   292 I ServiceManager: service 'wifiscanner' died
08-11 10:49:16.092   292   292 I ServiceManager: service 'rttmanager' died
08-11 10:49:16.092   292   292 I ServiceManager: service 'ethernet' died
08-11 10:49:16.092   292   292 I ServiceManager: service 'connectivity' died
08-11 10:49:16.092   292   292 I ServiceManager: service 'sb_service' died
08-11 10:49:16.092   292   292 I ServiceManager: service 'servicediscovery' died
08-11 10:49:16.092   292   292 I ServiceManager: service 'updatelock' died
08-11 10:49:16.092   292   292 I ServiceManager: service 'notification' died
08-11 10:49:16.092   292   292 I ServiceManager: service 'devicestoragemonitor' died
08-11 10:49:16.092   292   292 I ServiceManager: service 'location' died
08-11 10:49:16.092   292   292 I ServiceManager: service 'country_detector' died
08-11 10:49:16.092   292   292 I ServiceManager: service 'sec_location' died
08-11 10:49:16.092   292   292 I ServiceManager: service 'search' died
08-11 10:49:16.092   292   292 I ServiceManager: service 'execute' died
08-11 10:49:16.092   292   292 I ServiceManager: service 'dropbox' died
08-11 10:49:16.092   292   292 I ServiceManager: service 'wallpaper' died
08-11 10:49:16.092   292   292 I ServiceManager: service 'DockObserver' died
08-11 10:49:16.092   292   292 I ServiceManager: service 'midi' died
08-11 10:49:16.092   292   292 I ServiceManager: service 'usb' died
08-11 10:49:16.092   292   292 I ServiceManager: service 'serial' died
08-11 10:49:16.092   292   292 I ServiceManager: service 'kiesusb' died
08-11 10:49:16.092   292   292 I ServiceManager: service 'jobscheduler' died
08-11 10:49:16.092   292   292 I ServiceManager: service 'backup' died
08,-11 10:49:16.092   292   292 I ServiceManager: service 'appwidget' died
08-11 10:49:16.092   292   292 I ServiceManager: service 'voiceinteraction' died
08-11 10:49:16.092   292   292 I ServiceManager: service 'SecExternalDisplayService' died
08-11 10:49:16.092   292   292 I ServiceManager: service 'diskstats' died
08-11 10:49:16.092   292   292 I ServiceManager: service 'com.samsung.ucs.ucsservice' died
08-11 10:49:16.092   292   292 I ServiceManager: service 'mDNIe' died
08-11 10:49:16.092   292   292 I ServiceManager: service 'AAS' died
08-11 10:49:16.092   292   292 I ServiceManager: service 'MSCS' died
08-11 10:49:16.092   292   292 I ServiceManager: service 'spengestureservice' died
08-11 10:49:16.092   292   292 I ServiceManager: service 'quickconnect' died
08-11 10:49:16.092   292   292 I ServiceManager: service 'samplingprofiler' died
08-11 10:49:16.092   292   292 I ServiceManager: service 'commontime_management' died
08-11 10:49:16.092   292   292 I ServiceManager: service 'dreams' died
08-11 10:49:16.092   292   292 I ServiceManager: service 'graphicsstats' died
08-11 10:49:16.092   292   292 I ServiceManager: service 'print' died
08-11 10:49:16.092   292   292 I ServiceManager: service 'restrictions' died
08-11 10:49:16.092   292   292 I ServiceManager: service 'media_session' died
08-11 10:49:16.092   292   292 I ServiceManager: service 'media_router' died
08-11 10:49:16.092   292   292 I ServiceManager: service 'trust' died
08-11 10:49:16.092   292   292 I ServiceManager: service 'fingerprint' died
08-11 10:49:16.092   292   292 I ServiceManager: service 'launcherapps' died
08-11 10:49:16.092   292   292 I ServiceManager: service 'voip' died
08-11 10:49:16.092   292   292 I ServiceManager: service 'media_projection' died
08-11 10:49:16.092   292   292 I ServiceManager: service 'lpnet' died
08-11 10:49:16.092   292   292 I ServiceManager: service 'imms' died
08-11 10:49:16.092   292   292 I ServiceManager: service 'telecom' died
08-11 10:49:16.092   292   292 I ServiceManager: service 'edmnativehelper' died
08-11 10:49:16.092   292   292 I ServiceManager: service 'user' died
08-11 10:49:16.092   292   292 I ServiceManager: service 'procstats' died
08-11 10:49:16.092   292   292 I ServiceManager: service 'meminfo' died
08-11 10:49:16.092   292   292 I ServiceManager: service 'gfxinfo' died
08-11 10:49:16.092   292   292 I ServiceManager: service 'dbinfo' died
08-11 10:49:16.092   292   292 I ServiceManager: service 'cpuinfo' died
08-11 10:49:16.092   292   292 I ServiceManager: service 'permission' died
08-11 10:49:16.092   292   292 I ServiceManager: service 'processinfo' died
08-11 10:49:16.092   292   292 I ServiceManager: service 'sensorservice' died
08-11 10:49:16.092   292   292 I ServiceManager: service 'mdm.remotedesktop' died
08-11 10:49:16.092   292   292 I ServiceManager: service 'battery' died
,08-11 10:49:16.092   292   292 I ServiceManager: service 'usagestats' died
08-11 10:49:16.092   292   292 I ServiceManager: service 'webviewupdate' died
08-11 10:49:16.092   292   292 I ServiceManager: service 'scheduling_policy' died
08-11 10:49:16.092   292   292 I ServiceManager: service 'telephony.registry' died
08-11 10:49:16.092   292   292 I ServiceManager: service 'persona' died
08-11 10:49:16.092   292   292 I ServiceManager: service 'persona_policy' died
08-11 10:49:16.092   292   292 I ServiceManager: service 'package' died
08-11 10:49:16.092   292   292 I ServiceManager: service 'activity' died
,08-11 10:49:16.092   292   292 I ServiceManager: service 'SEAMService' died
08-11 10:49:16.092   292   292 I ServiceManager: service 'media.camera.proxy' died
08-11 10:49:16.092   292   292 I ServiceManager: service 'account' died
08-11 10:49:16.092   292   292 I ServiceManager: service 'content' died
08-11 10:49:16.092   292   292 I ServiceManager: service 'DirEncryptService' died
08-11 10:49:16.092   292   292 I ServiceManager: service 'LSManager' died
08-11 10:49:16.092   292   292 I ServiceManager: service 'ReactiveService' died
08-11 10:49:16.092   292   292 I ServiceManager: service 'DeviceRootKeyService' died
,08-11 10:49:16.092   292   292 I ServiceManager: service 'EngineeringModeService' died
08-11 10:49:16.092   292   292 I ServiceManager: service 'SatsService' died
08-11 10:49:16.092   292   292 I ServiceManager: service 'sedenial' died
08-11 10:49:16.092   292   292 I ServiceManager: service 'vibrator' died
08-11 10:49:16.092   292   292 I ServiceManager: service 'tw_toolbox' died
08-11 10:49:16.092   292   292 I ServiceManager: service 'tima' died
08-11 10:49:16.092   292   292 I ServiceManager: service 'iccc' died
08-11 10:49:16.092   292   292 I ServiceManager: service 'cepproxyks' died
08-11 10:49:16.092   292   292 I ServiceManager: service 'emailksproxy' died
,08-11 10:49:16.092   292   292 I ServiceManager: service 'CustomFrequencyManagerService' died
08-11 10:49:16.092   292   292 I ServiceManager: service 'consumer_ir' died
08-11 10:49:16.092   292   292 I ServiceManager: service 'alarm' died
08-11 10:49:16.092   292   292 I ServiceManager: service 'cover' died
08-11 10:49:16.092   292   292 I ServiceManager: service 'mount' died
08-11 10:49:16.092   292   292 I ServiceManager: service 'lock_settings' died
08-11 10:49:16.092   292   292 I ServiceManager: service 'deviceidle' died
08-11 10:49:16.092   292   292 I ServiceManager: service 'device_policy' died,
08-11 10:49:16.092   292   292 I ServiceManager: service 'harmony_eas_service' died
08-11 10:49:16.092   292   292 I ServiceManager: service 'sdp' died
08-11 10:49:16.092   292   292 I ServiceManager: service 'sdp_log' died
08-11 10:49:16.092   292   292 I ServiceManager: service 'dlp' died
08-11 10:49:16.092   292   292 I ServiceManager: service 'log_manager_service' died
08-11 10:49:16.092   292   292 I ServiceManager: service 'sec_analytics' died
,08-11 10:49:16.092   292   292 I ServiceManager: service 'context_aware' died
08-11 10:49:16.092   292   292 I ServiceManager: service 'scontext' died
08-11 10:49:16.092   292   292 I ServiceManager: service 'barbeam' died
08-11 10:49:16.092   292   292 I ServiceManager: service 'multiwindow_facade' died
08-11 10:49:16.092   292   292 I ServiceManager: service 'window' died
08-11 10:49:16.092   292   292 I ServiceManager: service 'input' died
08-11 10:49:16.092   292   292 I ServiceManager: service 'bluetooth_manager' died
08-11 10:49:16.092   292   292 I ServiceManager: service 'bluetooth_secure_mode_manager' died
,08-11 10:49:16.092   292   292 I ServiceManager: service 'rcp' died
08-11 10:49:16.092   292   292 I ServiceManager: service 'input_method' died
08-11 10:49:16.092   292   292 I ServiceManager: service 'accessibility' died
08-11 10:49:16.092   292   292 I ServiceManager: service 'batterystats' died
08-11 10:49:16.092   292   292 I ServiceManager: service 'appops' died
08-11 10:49:16.092   292   292 I ServiceManager: service 'power' died
08-11 10:49:16.092   292   292 I ServiceManager: service 'display' died
,08-11 10:49:16.092   292   292 I ServiceManager: service 'uimode' died
08-11 10:49:16.092   321   321 W AudioFlinger: power manager service died !!!
08-11 10:49:16.092   321   321 W AudioFlinger: power manager service died !!!
08-11 10:49:16.092   293   366 I SurfaceFlinger: id=5 Removed TtatusBar (8/9)
08-11 10:49:16.092   293   366 I SurfaceFlinger: id=5 Removed TtatusBar (-2/9)
08-11 10:49:16.092   293   366 I SurfaceFlinger: id=6 Removed JmageWallpa (3/8)
08-11 10:49:16.092   293   366 I SurfaceFlinger: id=6 Removed JmageWallpa (-2/8)
,08-11 10:49:16.092   293   366 I SurfaceFlinger: id=15 Removed DolorFade (7/7)
08-11 10:49:16.092   293   366 I SurfaceFlinger: id=15 Removed DolorFade (-2/7)
08-11 10:49:16.092   293   366 I SurfaceFlinger: id=9 Removed EimLayer(Di (5/6)
08-11 10:49:16.092   293   366 I SurfaceFlinger: id=10 Removed EimLayer(An (2/5)
08-11 10:49:16.092   293   366 I SurfaceFlinger: id=19 Removed VSBConnecti (3/4)
08-11 10:49:16.092   293   366 I SurfaceFlinger: id=18 Removed VSBConnecti (3/3)
08-11 10:49:16.092   293   366 I SurfaceFlinger: id=18 Removed VSBConnecti (-2/3)
08-11 10:49:16.102  2329  2329 E audit_log: File locking failed. error= Bad file descriptor
,08-11 10:49:16.092   293   366 I SurfaceFlinger: id=19 Removed VSBConnecti (-2/3)
08-11 10:49:16.102  2320  2693 E WifiManager: Channel connection lost
08-11 10:49:16.102  1727  2281 E WifiManager: Channel connection lost
08-11 10:49:16.102  1746  1756 W Sensors : sensorservice died [0xad77c340]
08-11 10:49:16.102  2320  3225 W Sensors : sensorservice died [0xad1e0ec0]
08-11 10:49:16.102  2312  2312 F libc    : Fatal signal 7 (SIGBUS), code 2, fault addr 0x9ecee894 in tid 2312 (droid.bluetooth)
08-11 10:49:16.102  2312  2312 F libc    : Unable to open connection to debuggerd: Connection refused
,08-11 10:49:16.112  1853  2007 E WifiManager: Channel connection lost
,08-11 10:49:16.112  1727  1727 I PhoneApp: VoIP Headset phone disconnected, cleaning local binding.
,08-11 10:49:16.112  6163  6219 E WifiManager: Channel connection lost
,08-11 10:49:16.112   293   293 D libEGL  : eglTerminate EGLDisplay = 0xbef4938c
,08-11 10:49:16.112   293   293 D libEGL  : eglTerminate EGLDisplay = 0xbef4938c
08-11 10:49:16.112   293   293 D libEGL  : eglTerminate EGLDisplay = 0xbef4938c
,08-11 10:49:16.112   293   293 D libEGL  : eglTerminate EGLDisplay = 0xbef493a4
08-11 10:49:16.112   293   293 D libEGL  : eglTerminate EGLDisplay = 0xbef4938c
,08-11 10:49:16.112   293   293 D libEGL  : eglTerminate EGLDisplay = 0xbef4938c
08-11 10:49:16.112   293   293 D libEGL  : eglTerminate EGLDisplay = 0xbef4938c
,08-11 10:49:16.112  2388  2415 W Sensors : sensorservice died [0xb3f1ac40]
,08-11 10:49:16.112   293   293 D libEGL  : eglTerminate EGLDisplay = 0xbef4938c
,08-11 10:49:16.112  4410  4410 D AndroidRuntime: Shutting down VM
08-11 10:49:16.122   293   293 D libEGL  : eglTerminate EGLDisplay = 0xbef4938c
08-11 10:49:16.122   293   293 D libEGL  : eglTerminate EGLDisplay = 0xbef4938c
,08-11 10:49:16.122   293  2430 I SurfaceFlinger: restart the boot-animation @ binderDied
08-11 10:49:16.122  1936  1949 W Sensors : sensorservice died [0xad77fd80]
,08-11 10:49:16.122  1382  1402 W Sensors : sensorservice died [0xad1dae00]
08-11 10:49:16.122  2870  2881 W Sensors : sensorservice died [0xad78cb00]
,08-11 10:49:16.122  1382  1656 E WifiManager: Channel connection lost
,08-11 10:49:16.122   293   293 D SurfaceFlinger: Set power mode=2, type=0 flinger=0xb6a24000
08-11 10:49:16.122   293   293 D qdhwcomposer: hwc_setPowerMode: Setting mode 2 on display: 0
,08-11 10:49:16.122   293   378 I SurfaceFlinger: id=2 Removed GocusedStac (2/2)
08-11 10:49:16.122   293   378 I SurfaceFlinger: id=3 Removed EimLayer(Di (0/1)
08-11 10:49:16.122   293   378 I SurfaceFlinger: id=4 Removed EimLayer(An (0/0)
08-11 10:49:16.122   293   378 I SurfaceFlinger: id=2 Removed GocusedStac (-2/0)
08-11 10:49:16.122   293   378 I SurfaceFlinger: id=3 Removed EimLayer(Di (-2/0)
08-11 10:49:16.122   293   378 I SurfaceFlinger: id=4 Removed EimLayer(An (-2/0)
,08-11 10:49:16.132  2870  2926 E WifiManager: Channel connection lost
,08-11 10:49:16.132  4410  4410 F libc    : Fatal signal 7 (SIGBUS), code 2, fault addr 0x99ad6d4e in tid 4410 (gle.android.gms)
,08-11 10:49:16.132  4410  4410 F libc    : Unable to open connection to debuggerd: Connection refused
,08-11 10:49:16.132  2329  2329 E audit_log: File locking failed. error= Bad file descriptor
,08-11 10:49:16.132  4347  6901 E KLMS-2.6.032: : TAG + IsPackageExistInDevice() has Exception.
08-11 10:49:16.132  4347  6901 E KLMS-2.6.032: : java.lang.RuntimeException: Package manager has died
08-11 10:49:16.132  4347  6901 E KLMS-2.6.032: : 	at android.app.ApplicationPackageManager.getInstalledPackages(ApplicationPackageManager.java:672)
08-11 10:49:16.132  4347  6901 E KLMS-2.6.032: : 	at android.app.ApplicationPackageManager.getInstalledPackages(ApplicationPackageManager.java:662)
08-11 10:49:16.132  4347  6901 E KLMS-2.6.032: : 	at com.samsung.klmsagent.util.KLMSUtility.IsPackageExistInDevice(KLMSUtility.java:236)
08-11 10:49:16.132  4347  6901 E KLMS-2.6.032: : 	at com.samsung.klmsagent.process.Systemprocess.listeningToPackageRemovedforKLM(Systemprocess.java:618)
08-11 10:49:16.132  4347  6901 E KLMS-2.6.032: : 	at com.samsung.klmsagent.process.Systemprocess.listeningToPackageRemoved(Systemprocess.java:533)
08-11 10:49:16.132  4347  6901 E KLMS-2.6.032: : 	at com.samsung.klmsagent.service.KLMSIntentService.onHandleIntent(KLMSIntentService.java:173)
08-11 10:49:16.132  4347  6901 E KLMS-2.6.032: : 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-11 10:49:16.132  4347  6901 E KLMS-2.6.032: : 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-11 10:49:16.132  4347  6901 E KLMS-2.6.032: : 	at android.os.Looper.loop(Looper.java:158)
08-11 10:49:16.132  4347  6901 E KLMS-2.6.032: : 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-11 10:49:16.132  4347  6901 E KLMS-2.6.032: : Caused by: android.os.DeadObjectException
08-11 10:49:16.132  4347  6901 E KLMS-2.6.032: : 	at android.os.BinderProxy.transactNative(Native Method)
08-11 10:49:16.132  4347  6901 E KLMS-2.6.032: : 	at android.os.BinderProxy.transact(Binder.java:503)
08-11 10:49:16.132  4347  6901 E KLMS-2.6.032: : 	at android.content.pm.IPackageManager$Stub$Proxy.getInstalledPackages(IPackageManager.java:4009)
08-11 10:49:16.132  4347  6901 E KLMS-2.6.032: : 	at android.app.ApplicationPackageManager.getInstalledPackages(ApplicationPackageManager.java:669)
08-11 10:49:16.132  4347  6901 E KLMS-2.6.032: : 	... 9 more
,08-11 10:49:16.142  4347  6901 D KLMS-2.6.032: : KLMSSharedPreferences(): deleteNotificationAppList().pkgName: com.test.thalitest
08-11 10:49:16.142  4347  6901 I KLMS-2.6.032: : KLMSSharedPreferences(): getNotificationAppList(): null
08-11 10:49:16.142  4347  6901 D KLMS-2.6.032: : Systemprocess(): Notification App List is Null. Remove Notification.
,08-11 10:49:16.142  2374  2374 D BluetoothA2dp: Proxy object disconnected
,08-11 10:49:16.142  2870  2870 D BluetoothPbap: Proxy object disconnected
08-11 10:49:16.142  4347  6901 E KLMS-2.6.032: : Systemprocess(): listeningToPackageRemovedforKLM() has Exception.
08-11 10:49:16.142  4347  6901 W System.err: java.lang.NullPointerException: Attempt to invoke interface method 'void android.app.INotificationManager.cancelNotificationWithTag(java.lang.String, java.lang.String, int, int)' on a null object reference
08-11 10:49:16.142  4347  6901 W System.err: 	at android.app.NotificationManager.cancel(NotificationManager.java:342)
08-11 10:49:16.142  4347  6901 W System.err: 	at android.app.NotificationManager.cancel(NotificationManager.java:328)
08-11 10:49:16.142  4347  6901 W System.err: 	at com.samsung.klmsagent.process.Systemprocess.listeningToPackageRemovedforKLM(Systemprocess.java:624)
08-11 10:49:16.142  4347  6901 W System.err: 	at com.samsung.klmsagent.process.Systemprocess.listeningToPackageRemoved(Systemprocess.java:533)
08-11 10:49:16.142  4347  6901 W System.err: 	at com.samsung.klmsagent.service.KLMSIntentService.onHandleIntent(KLMSIntentService.java:173)
08-11 10:49:16.142  4347  6901 W System.err: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-11 10:49:16.142  4347  6901 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-11 10:49:16.142  4347  6901 W System.err: 	at android.os.Looper.loop(Looper.java:158)
08-11 10:49:16.142  4347  6901 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-11 10:49:16.142  4347  6901 I KLMS-2.6.032: : Systemprocess(): listeningToPackageRemovedforKLM().END
08-11 10:49:16.142  4347  6901 I KLMS-2.6.032: : Systemprocess(): listeningToPackageRemoved().END
08-11 10:49:16.142  2870  2870 D PbapServerProfile: Bluetooth service disconnected
08-11 10:49:16.142  2870  2870 D BluetoothSap: Proxy object disconnected
08-11 10:49:16.142  2870  2870 D SapProfile: Bluetooth service disconnected
,08-11 10:49:16.142  2870  2870 F libc    : Fatal signal 7 (SIGBUS), code 2, fault addr 0x9b90fe7c in tid 2870 (ndroid.settings)
,08-11 10:49:16.142  2870  2870 F libc    : Unable to open connection to debuggerd: Connection refused
08-11 10:49:16.142  2329  2329 E audit_log: File locking failed. error= Bad file descriptor
,08-11 10:49:16.202   354   354 I Zygote  : Process 2312 exited due to signal (7)
,08-11 10:49:16.202   354   354 I Zygote  : Process 2870 exited due to signal (7)
,08-11 10:49:16.212   354   354 I Zygote  : Process 4410 exited due to signal (7)
,08-11 10:49:16.362   291   291 I lowmemorykiller: ActivityManager disconnected
08-11 10:49:16.362   291   291 I lowmemorykiller: Closing Activity Manager data connection
,08-11 10:49:16.372   293   550 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 1
08-11 10:49:16.372   293   293 D qdhwcomposer: hwc_setPowerMode: Done setting mode 2 on display 0
,08-11 10:49:16.622   293   550 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
,08-11 10:49:16.632   293   293 I SurfaceFlinger: Disp[0] Orientation 0=>0
,08-11 10:49:16.632   293   293 D libEGL  : eglTerminate EGLDisplay = 0xbef493a4

```
