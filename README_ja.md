# InteractiveObjectManager

このリポジトリは、**Unity** 上でオブジェクトのクリックやドラッグ操作を簡単に扱うためのサンプルスクリプト集です。内部では [UniRx](https://github.com/neuecc/UniRx) を利用しており、リアクティブに入力イベントを処理できます。

## 主な機能
- クリックやドラッグ時のコールバックを定義する `IClickableObject` インターフェース
- ドラッグ可能なオブジェクト用の基底クラス `DraggableObject`
- マウス入力を検知する `ClickEventManager`
- 二つのオブジェクトが離された際のイベントを配信する `OnObjectReleasedEventManager`
- シーンに追加してすぐ使える各種プレハブ

## 使い方
1. 本リポジトリのスクリプトとプレハブを Unity プロジェクトに取り込みます。
2. `ClickEventManager` と `OnObjectReleasedEventManager` のプレハブをシーンに配置します。
3. 独自の挙動を追加したい場合は `DraggableObject` を継承するか、`IClickableObject` を実装してください。

## ライセンス
このプロジェクトは MIT License の下で公開されています。詳細は `LICENSE` ファイルをご覧ください。
