# -*- coding: utf-8 -*-
$:.unshift("/Library/RubyMotion/lib")

require 'motion/project/template/ios'
require "bundler/gem_tasks"
require "bundler/setup"
require 'motion_print'
Bundler.require

Motion::Project::App.setup do |app|
  # Use `rake config' to see complete project settings.
  app.identifier = 'com.infinitered.redpotion'
  app.name = 'RedPotion'

  app.interface_orientations = [:portrait, :landscape_left, :landscape_right, :portrait_upside_down]
end
task :"build:simulator" => :"schema:build"
