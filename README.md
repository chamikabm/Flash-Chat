# Flash-Chat
📱 | Project Stub | (Swift 4.0/Xcode 9) - Flash Chat App

Pro: Git clone to your Xcode projects folder.

## Podfile Configuration
```
post_install do |installer|
    installer.pods_project.targets.each do |target|
        target.build_configurations.each do |config|
            config.build_settings['CLANG_WARN_DOCUMENTATION_COMMENTS'] = 'NO'
        end
    end
end
```

## Finished App
![Finished App](https://github.com/londonappbrewery/Images/blob/master/Flash%20Chat.gif)

