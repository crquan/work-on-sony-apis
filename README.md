work-on-sony-apis
=================

work-on-sony-apis

search-nex.py:
 search a sony api compatible camera with ssdp:discover UPnP

test-nex.py:
 get all available api list from the camera, by default it calls
 getAvailableApiList, may also accept a differenet method name

cheng@t-lap:~/tmp/work-on-sony-apis$ python test-nex.py
{"id":1,"result":[["getVersions","getMethodTypes","getApplicationInfo","getAvailableApiList","getEvent","actTakePicture","stopRecMode","startLiveview","stopLiveview","startLiveviewWithSize","awaitTakePicture","setSelfTimer","getSelfTimer","getAvailableSelfTimer","getSupportedSelfTimer","setExposureMode","getAvailableExposureMode","getExposureMode","getSupportedExposureMode","setExposureCompensation","getExposureCompensation","getAvailableExposureCompensation","getSupportedExposureCompensation","getFNumber","getAvailableFNumber","getSupportedFNumber","setIsoSpeedRate","getIsoSpeedRate","getAvailableIsoSpeedRate","getSupportedIsoSpeedRate","getLiveviewSize","getAvailableLiveviewSize","getSupportedLiveviewSize","setPostviewImageSize","getPostviewImageSize","getAvailablePostviewImageSize","getSupportedPostviewImageSize","setProgramShift","getSupportedProgramShift","setShootMode","getShootMode","getAvailableShootMode","getSupportedShootMode","getShutterSpeed","getAvailableShutterSpeed","getSupportedShutterSpeed","setTouchAFPosition","getTouchAFPosition","setWhiteBalance","getWhiteBalance","getSupportedWhiteBalance","getAvailableWhiteBalance"]]}
cheng@t-lap:~/tmp/work-on-sony-apis$ python test-nex.py getVersions
{"id":1,"result":[["1.0"]]}
cheng@t-lap:~/tmp/work-on-sony-apis$ python test-nex.py getApplicationInfo
{"id":1,"result":["Smart Remote Control SR/2.00 __BTY__","2.0.0"]}

