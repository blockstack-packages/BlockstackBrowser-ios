# Uncomment the next line to define a global platform for your project
platform :ios, '10.0'


target 'BlockStackBrowser' do
  # Comment the next line if you're not using Swift and don't want to use dynamic frameworks
  use_frameworks!
  
  # Pods for BlockStackBrowser.
  
    #build from the public version
    pod "BlockstackCoreApi-iOS"
    
    #OR build with your local pod during development
    #pod 'BlockstackCoreApi-iOS', :path => '../BlockstackCoreApi'
    
    #QR Code scanner
    pod 'CDZQRScanningViewController'
    
    #http request helper
    pod 'QwikHttp'
    
    #Using pre-release version of dropbox SDK for xcode 9. remove :git => ... after xcode 9 out of beta
    #replace with version => 5+
    #this is used by swiftydropbox
    #pod 'Alamofire', :git => 'https://github.com/Alamofire/Alamofire.git', :branch => 'alamofire5'
    
    #storage apis
    pod 'SwiftyDropbox', :git => 'https://github.com/dropbox/SwiftyDropbox.git'
    pod 'Google/SignIn'
    pod 'GoogleAPIClientForREST/Drive', '~> 1.2.1'
    #pod 'OneDriveSDK'
    
    #Helper functions and methods--- stuff like rounded network image views
    pod 'SeaseAssist'
    
    #keychain access, for storing and encrypting pass phrases
    pod 'SwiftKeychainWrapper'
    #pod 'CryptoSwift', :git => 'https://github.com/krzyzanowskim/CryptoSwift', :branch => 'swift4'
    pod 'RNCryptor', '~> 5.0'
    
    pod 'IQKeyboardManager' #manages keyboard scrolling over textfields
    
end
