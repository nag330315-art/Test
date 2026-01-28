platform :ios, '13.0'
use_frameworks!

# 注意: この Podfile はリポジトリのルートに配置されます。
# ターゲット名が Xcode プロジェクトのターゲット名と一致していることを確認してください。
# 例: target 'Test' do ... end

target 'Test' do
  # ここに使用したいライブラリを追加してください。例:
  # pod 'Alamofire', '~> 5.6'
  # pod 'Firebase/Analytics'
end

post_install do |installer|
  installer.pods_project.targets.each do |target|
    target.build_configurations.each do |config|
      # iOS のデプロイターゲットを明示的に設定（必要に応じて変更）
      config.build_settings['IPHONEOS_DEPLOYMENT_TARGET'] = '13.0'
    end
  end
end

# 使い方:
# 1. このリポジトリをローカルにクローン
# 2. Xcode プロジェクト(.xcodeproj)があるディレクトリに移動
# 3. pod install を実行して .xcworkspace を生成