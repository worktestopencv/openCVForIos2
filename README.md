python3 platforms/apple/build_xcframework.py --out build_all \
--iphoneos_deployment_target 14.0 \
--iphoneos_archs arm64 \
--iphonesimulator_archs arm64,x86_64 \
--build_only_specified_archs True \
--without calib3d \
--without dnn \
--without features2d \
--without gapi \
--without highgui \
--without java \
--without js \
--without ml \
--without objc \
--without objdetect \
--without python \
--without stitching \
--without ts \
--without video \
--without videoio \
--without world
