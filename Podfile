# Uncomment the next line to define a global platform for your project
platform :ios, '14.0'



target 'Runner' do
  # Comment the next line if you don't want to use dynamic frameworks
  use_frameworks!
  use_modular_headers!
  pod 'FirebaseCore', :modular_headers => true
  # Pods for Runner

  target 'RunnerTests' do
    inherit! :search_paths
    # Pods for testing
  end
  target 'OneSignalNotificationServiceExtension' do
  use_frameworks!
  pod 'OneSignalXCFramework', '>= 5.0.0', '< 6.0'
end
end
