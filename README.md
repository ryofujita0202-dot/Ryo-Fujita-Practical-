# LinkFastAPINext Practical

## 📋 プロジェクト概要

このプロジェクトは、**FastAPI**（Python）をバックエンド、**Next.js**（React）をフロントエンドとしたフルスタックWebアプリケーションです。

### 🎯 解決する課題
- モダンなWebアプリケーション開発の実践
- APIベースのフロントエンド・バックエンド分離アーキテクチャ
- 顧客管理システムの実装

### 🚀 主な機能
- 顧客管理機能
- RESTful API（FastAPI）
- レスポンシブなWebUI（Next.js）
- リアルタイムデータ通信

## 🛠️ 技術スタック

### バックエンド
- **FastAPI** - Python製の高速APIフレームワーク
- **Uvicorn** - ASGIサーバー
- **Python 3.x**

### フロントエンド
- **Next.js** - Reactベースのフレームワーク
- **React** - UIライブラリ

## 🔧 環境構築

### 前提条件
- Python 3.8以上
- Node.js 18以上
- npm

### 1. リポジトリのクローン
```bash
git clone https://github.com/ryofujita0202-dot/Ryo-Fujita-Practical-.git
cd LinkFastAPINext_Practical-main
```

### 2. バックエンドのセットアップ
```bash
# バックエンドディレクトリに移動
cd backend

# 仮想環境の作成
python3 -m venv backend_env

# 仮想環境の有効化
# Windows PowerShell の場合
./backend_env/Scripts/activate.ps1

# macOS/Linux の場合
source backend_env/bin/activate

# 依存関係のインストール
pip install -r requirements.txt
```

### 3. フロントエンドのセットアップ
```bash
# フロントエンドディレクトリに移動
cd frontend

# 依存関係のインストール
npm install
```

## 🚀 使い方

### 開発サーバーの起動

#### 1. バックエンド（FastAPI）
```bash
cd backend
# 仮想環境が有効化されていることを確認
uvicorn app:app --reload
```

#### 2. フロントエンド（Next.js）
```bash
cd frontend
npm run dev
```

### アクセス
- **顧客管理ページ**: http://localhost:3000/customers
- **フロントエンド**: http://localhost:3000
- **バックエンドAPI**: http://localhost:8000
- **API ドキュメント**: http://localhost:8000/docs

## 📁 プロジェクト構成

```
LinkFastAPINext_Practical/
├── backend/
│   ├── app.py              # FastAPIアプリケーション
│   ├── requirements.txt    # Python依存関係
│   └── backend_env/        # 仮想環境
├── frontend/
│   ├── pages/
│   │   └── customers/      # 顧客管理ページ
│   ├── components/         # Reactコンポーネント
│   ├── package.json        # Node.js依存関係
│   └── .env               # フロントエンド環境変数
├── .gitignore
└── README.md
```

## 👥 開発ルール・貢献ガイドライン

### ブランチ命名規則
- `feature/機能名` - 新機能開発
- `fix/修正内容` - バグ修正
- `docs/文書名` - ドキュメント更新

### コミットメッセージ
```
[種別] 簡潔な説明

例：
[feat] 顧客管理機能を追加
[fix] APIレスポンスのバグを修正
[docs] READMEを更新
```

## 📄 ライセンス

このプロジェクトは [MIT License](LICENSE) の下で公開されています。

## 👤 開発者情報

### 開発者
- **名前**: Ryo Fujita
- **GitHub**: [@ryofujita0202-dot](https://github.com/ryofujita0202-dot)
- **リポジトリ**: [Ryo-Fujita-Practical-](https://github.com/ryofujita0202-dot/Ryo-Fujita-Practical-)

### サポート・お問い合わせ
- **Issues**: [GitHub Issues](https://github.com/ryofujita0202-dot/Ryo-Fujita-Practical-/issues)

### 参考リンク
- [FastAPI Documentation](https://fastapi.tiangolo.com/)
- [Next.js Documentation](https://nextjs.org/docs)

---

⭐ このプロジェクトが役に立ったら、GitHubでスターをお願いします！