# datasciencecoursera
Data Science Course Project Repo
usr/bin/env ruby 
 2 
 3 $LOAD_PATH.unshift File.dirname(__FILE__) + "/../lib" 
 4 require 'github/markup' 
 5  
 6 if ARGV[0] && File.exists?(file = ARGV[0]) 
 7 puts GitHub::Markup.render(file) 
 8 else 
 9   puts "usage: #$0 FILE" 
 10 end 
