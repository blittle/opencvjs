opencvjs
========

OpenCV Modules Compiled to JS through Emscripten

All modules are built with the -02 emscripten optimization level. ASM mode is disabled due to a function pointer cast warning.

The following modules are available:
 * opencv.js - Includes all the modules below.
 * opencv-core.js - Includes only libopencv_core.
 * opencv-imgproc.js - Includes libopencv_core and libopencv_imgproc.
 * opencv-video.js - Includes libopencv_core, libopencv_imgproc, and libopencv_video.
 * opencv-objdetect.js - Includes libopencv_core, libopencv_imgproc, and libopencv_objdetect.
 * opencv-features2d.js - Includes libopencv_core, libopencv_imgproc, libopencv_flann, and libopencv_features2d.
 * opencv-calib3d.js - Includes libopencv_core and libopencv_calib3d
 * opencv-ml.js - Includes libopencv_core and libopencv_ml
