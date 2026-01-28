# Uncomment the next line to define a global platform for your project
platform :ios, '11.0'

def shared_pods
  pod 'IQKeyboardManager'
  pod 'Alamofire'
  
  pod 'SwiftyJSON'
  pod 'SwiftKeychainWrapper'
  pod 'DropDown'
  pod "ZVProgressHUD", '~> 2.6.0'
  
  pod 'Kingfisher',  '~> 5.15.8'
  pod 'Localize-Swift'
  pod 'MXSegmentedControl'
  
  #aws
  pod 'Amplify'
  pod 'AmplifyPlugins/AWSCognitoAuthPlugin'
  
  #Crop image
  pod 'CropViewController'

  #Local DB
  pod "MagicalRecord"
end



target 'UAT' do
  
  use_frameworks!
  shared_pods
  
end

target 'TRMUAT03' do
  
  use_frameworks!
  shared_pods
  
end

target 'Production' do
  
  use_frameworks!
  shared_pods
  
end

target 'Staging' do
  
  use_frameworks!
  shared_pods
  
end

target 'TRMUAT' do
  
  use_frameworks!
  shared_pods
  
end

