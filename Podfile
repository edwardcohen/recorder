use_frameworks!

target 'VoiceRecorder' do
  pod 'JTAppleCalendar', '~> 6.0'
  pod 'KDCircularProgress', '~> 1.5'
  pod 'SoundWave'
end


post_install do |installer|
    installer.pods_project.targets.each do |target|
        target.build_configurations.each do |config|
            config.build_settings['SWIFT_VERSION'] = '3.0'
        end
    end
end
