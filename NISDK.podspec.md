Pod::Spec.new do |s|
s.name     = 'NISDK'
s.version  = '1.0.0'
s.license = 'MIT'
s.summary  = 'This is for NeoSmartpen'
s.homepage = 'https://github.com/NeolabAram/IOSSDK'
s.author   = { 'NeolabAram' => 'NeolabAram/IOSSDK' }
s.source   = { :git => 'https://github.com/NeolabAram/IOSSDK.git', :tag => s.version }
s.ios.deployment_target = '8.0'
s.source_files = 'NISDK/*'
s.requires_arc = true
end
