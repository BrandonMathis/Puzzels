#!/usr/bin/env ruby

def getnum(file)
  regex = /[0-9]+/
  while line=file.gets
    return line.match(regex).to_s if line =~ regex
  end
end

a = File.new(ARGV[0], "r")
number = Integer(getnum( a ))
range = Range.new(1, number)

range.each do |value|
  if (value % 3) == 0 && (value % 5) == 0
    puts "Hop"
  elsif (value % 3) == 0
    puts "Hoppity"
  elsif (value % 5) == 0
    puts "Hophop"
  end
end
