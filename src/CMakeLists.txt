include_directories("${LesionSizingToolkit_SOURCE_DIR}/src")  # to include itkIncludeRequiredIOFactories.h
add_executable(itkCannyEdgeDetectionImageFilter1  itkCannyEdgeDetectionImageFilter1.cxx )
target_link_libraries(itkCannyEdgeDetectionImageFilter1 ${LesionSizingToolkit_LIBRARIES})

add_executable(itkCannyEdgeDetectionImageFilter2  itkCannyEdgeDetectionImageFilter2.cxx )
target_link_libraries(itkCannyEdgeDetectionImageFilter2 ${LesionSizingToolkit_LIBRARIES})

add_executable(itkCannyEdgeDetectionImageFilter3  itkCannyEdgeDetectionImageFilter3.cxx )
target_link_libraries(itkCannyEdgeDetectionImageFilter3 ${LesionSizingToolkit_LIBRARIES})

add_executable(itkDicomSeriesReadImageWrite itkDicomSeriesReadImageWrite.cxx)
target_link_libraries(itkDicomSeriesReadImageWrite ${LesionSizingToolkit_LIBRARIES})

add_executable(itkGradientMagnitudeImageFilter itkGradientMagnitudeImageFilter.cxx)
target_link_libraries(itkGradientMagnitudeImageFilter ${LesionSizingToolkit_LIBRARIES})

add_executable(itkGradientMagnitudeRecursiveGaussianImageFilter itkGradientMagnitudeRecursiveGaussianImageFilter.cxx)
target_link_libraries(itkGradientMagnitudeRecursiveGaussianImageFilter ${LesionSizingToolkit_LIBRARIES})

add_executable(itkImageReadRegionOfInterestAroundSeedWrite itkImageReadRegionOfInterestAroundSeedWrite.cxx)
target_link_libraries(itkImageReadRegionOfInterestAroundSeedWrite  ${LesionSizingToolkit_LIBRARIES})

add_executable(itkImageReadRegionOfInterestWrite itkImageReadRegionOfInterestWrite.cxx)
target_link_libraries(itkImageReadRegionOfInterestWrite ${LesionSizingToolkit_LIBRARIES})

add_executable(itkImageReadWrite itkImageReadWrite.cxx)
target_link_libraries(itkImageReadWrite ${LesionSizingToolkit_LIBRARIES})

add_executable(itkLaplacianRecursiveGaussianImageFilter itkLaplacianRecursiveGaussianImageFilter.cxx)
target_link_libraries(itkLaplacianRecursiveGaussianImageFilter ${LesionSizingToolkit_LIBRARIES})

add_executable(itkResampleVolumeToBeIsotropic itkResampleVolumeToBeIsotropic.cxx)
target_link_libraries(itkResampleVolumeToBeIsotropic ${LesionSizingToolkit_LIBRARIES})
