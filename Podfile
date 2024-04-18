platform :ios, '13.1'

target 'Flash Chat iOS13' do
  use_frameworks!

  # Pods for Flash Chat iOS13
  pod 'Firebase/Auth'
  pod 'Firebase/Firestore'
  post_install do |installer|
      installer.generated_projects.each do |project|
          project.targets.each do |target|
              target.build_configurations.each do |config|
                  config.build_settings['IPHONEOS_DEPLOYMENT_TARGET'] = '13.0'
              end
          end
      end
  end
end
