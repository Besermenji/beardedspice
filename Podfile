platform :osx, '10.9'
project 'BeardedSpice'

source 'https://github.com/CocoaPods/Specs.git'

target 'BeardedSpiceControllers' do
    pod 'MASShortcut', '~> 2.3.3'

    target 'BeardedSpice' do
        pod 'MASPreferences', '~> 1.1.4'

        # all pods for tests should ONLY go here
        target 'BeardedSpiceTests' do
            pod 'Kiwi'
            pod 'OCMock'
            pod 'VCRURLConnection'
        end
    end
end

