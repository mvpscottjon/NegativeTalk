# Uncomment the next line to define a global platform for your project
# platform :ios, '9.0'

def core_pods
    pod 'SnapKit'
    pod 'RxSwift'
    pod 'RxCocoa'
    pod 'RxDataSources'
    pod 'Alamofire'
    pod 'Kingfisher'
    pod 'FirebaseAuth'
    pod 'FirebaseFirestore'
    pod 'FirebaseAnalytics'
end

target 'NegativeTalk' do
  # Comment the next line if you don't want to use dynamic frameworks
  use_frameworks!

  # Pods for NegativeTalk
  core_pods

  target 'NegativeTalkTests' do
    inherit! :search_paths
    # Pods for testing
  end

  target 'NegativeTalkUITests' do
    # Pods for testing
  end

end
