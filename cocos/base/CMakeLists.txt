
if(MACOSX OR APPLE)
  set(COCOS_BASE_SPECIFIC_SRC
    base/CCUserDefault-apple.mm)
endif()

# todo: android support via base/CCUserDefaultAndroid.cpp
# todo: also base/CCController-android.cpp

set(COCOS_BASE_SRC
  base/CCAsyncTaskPool.cpp
  base/CCAutoreleasePool.cpp
  base/CCConfiguration.cpp
  base/CCConsole.cpp
  base/CCController.cpp
  base/CCData.cpp
  base/CCDataVisitor.cpp
  base/CCNinePatchImageParser.cpp
  base/CCDirector.cpp
  base/CCEvent.cpp
  base/CCEventAcceleration.cpp
  base/CCEventController.cpp
  base/CCEventCustom.cpp
  base/CCEventDispatcher.cpp
  base/CCEventFocus.cpp
  base/CCEventKeyboard.cpp
  base/CCEventListener.cpp
  base/CCEventListenerAcceleration.cpp
  base/CCEventListenerController.cpp
  base/CCEventListenerCustom.cpp
  base/CCEventListenerFocus.cpp
  base/CCEventListenerKeyboard.cpp
  base/CCEventListenerMouse.cpp
  base/CCEventListenerTouch.cpp
  base/CCEventMouse.cpp
  base/CCEventTouch.cpp
  base/CCIMEDispatcher.cpp
  base/CCNS.cpp
  base/CCProfiling.cpp
  base/CCProperties.cpp
  base/CCRef.cpp
  base/CCScheduler.cpp
  base/CCScriptSupport.cpp
  base/CCTouch.cpp
  base/CCUserDefault.cpp
  base/CCValue.cpp
  base/ObjectFactory.cpp
  base/TGAlib.cpp
  base/ZipUtils.cpp
  base/allocator/CCAllocatorDiagnostics.cpp
  base/allocator/CCAllocatorGlobal.cpp
  base/allocator/CCAllocatorGlobalNewDelete.cpp
  base/atitc.cpp
  base/base64.cpp
  base/ccCArray.cpp
  base/ccFPSImages.c
  base/ccRandom.cpp
  base/ccTypes.cpp
  base/ccUTF8.cpp
  base/ccUtils.cpp
  base/etc1.cpp
  base/pvr.cpp
  base/s3tc.cpp
  ${COCOS_BASE_SPECIFIC_SRC}

)
