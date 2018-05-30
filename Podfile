# include public/private pods
source 'git@github.com:cocoapods/Specs.git'

platform :ios, '11.0'

ENV['COCOAPODS_DISABLE_STATS'] = 'true'

# setup
workspace './Poly.xcworkspace'
swift_version = '4.0'
use_frameworks!

def shared_pods
  pod 'Alamofire', '~> 4.7'
  pod 'AlamofireNetworkActivityIndicator', '~> 2.2'
  pod 'Cache', '~> 4.2'
  pod 'ObjectMapper', '~> 3.1'
  pod 'PromiseKit', '~> 6.2'
  pod 'Disk', '~> 0.3'
end

target 'Poly' do
  shared_pods
end

target 'Poly_iOS' do
  pod 'IGListKit', '3.4.0'
  shared_pods
end
