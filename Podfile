# Uncomment the next line to define a global platform for your project
platform :osx, '10.15'

target 'Pock' do

  # Comment the next line if you don't want to use dynamic frameworks
  use_frameworks!

  # PockKit — pointed at a fork with a fix for a real crash
  # (EXC_BAD_INSTRUCTION in PKTouchBarMouseController.dismiss ->
  # showCursor, force-unwrapping a view under a reentrant-teardown race)
  # while testing it before upstreaming.
  pod 'PockKit', :git => 'https://github.com/henilptel/pockkit.git', :branch => 'master'

  # Analytics
  pod 'AppCenter/Analytics'
  pod 'AppCenter/Crashes'

  # Utils
  pod 'Magnet'
  pod 'Zip'

end
