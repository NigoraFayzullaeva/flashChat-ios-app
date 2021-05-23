platform :ios, '13.0'

target 'Flash Chat iOS13' do
  use_frameworks!

  # Pods for Flash Chat iOS13
  
  pod 'CLTypingLabel', '~> 0.4.0'
  
  pod 'Firebase/Auth'
  pod 'Firebase/Firestore'
  
  post_install do |pi|
  pi.pods_project.targets.each do |t|
  t.build_configurations.each do |config|
  config.build_settings['IPHONEOS_DEPLOYMENT_TARGET'] = '9.0'
  end
  end
  end

end
