
source 'https://github.com/CocoaPods/Specs.git'

# Uncomment the next line to define a global platform for your project
platform :ios, '11.7'

def common_pods
    pod 'Firebase/Core'
    pod 'MGSwipeTableCell'
end

target 'Bitrise-iOS-Cocoapods-Sample' do
  # Comment the next line if you don't want to use dynamic frameworks
  use_frameworks!
  inhibit_all_warnings!

  # Pods for Bitrise-iOS-Cocoapods-Sample
  common_pods

  target 'Bitrise-iOS-Cocoapods-SampleTests' do
    inherit! :search_paths
    # Pods for testing
    common_pods
  end

  target 'Bitrise-iOS-Cocoapods-SampleUITests' do
    # Pods for testing
    common_pods
  end
end
