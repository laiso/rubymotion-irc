# -*- coding: utf-8 -*-
$:.unshift("/Library/RubyMotion/lib")
require 'motion/project/template/ios'

require 'xcodeproj'
require 'sugarcube'
require 'motion-cocoapods'

Motion::Project::App.setup do |app|
  # Use `rake config' to see complete project settings.
  app.name = 'irc'
  app.pods do
    pod 'CocoaAsyncSocket'
    pod 'PHFComposeBarView'
  end
end
