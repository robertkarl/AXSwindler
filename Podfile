workspace 'AXSwindler'
swift_version = '4.0'
platform :osx, '10.10'

use_frameworks!

project 'AXSwindler'

target 'SwindlerTests' do
  pod 'Quick',  '~> 1.2.0'
  pod 'Nimble', '~> 7.3.1'
end

target 'AXSwindler' do
  pod 'PromiseKit/CorePromise', '~> 6.0'
  pod 'AXSwift', path: './AXSwift'
end

target 'SwindlerExample' do
  pod 'PromiseKit/CorePromise', '~> 6.0'
  pod 'AXSwift', path: './AXSwift'
end
