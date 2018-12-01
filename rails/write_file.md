write file| write_yaml | write yaml
File.open('/tmp/test.yml', 'w') {|f| f.write d.to_yaml }
