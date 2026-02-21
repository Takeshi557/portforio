Travel Planner App

旅行前の計画整理を効率化するための
フルスタックWebアプリケーションです。

Next.js × Supabase を用いて
認証・データ管理・CRUD機能を実装しています。

 概要

旅行前に

どこに行くか

何をするか

日程をどう組むか

を整理できるシンプルな旅行計画管理アプリです。

直感的なUIで、旅行プランを作成・編集・管理できます。

 デモURL

※デプロイ後に記載予定（Vercel）

 スクリーンショット

※後日追加予定

 使用技術
フロントエンド

Next.js (App Router)

React

TypeScript（※使っていれば）

CSS / Tailwind（※使っていれば）

バックエンド

Supabase

Authentication

PostgreSQL

Row Level Security（RLS）

インフラ・その他

Vercel（予定）

Git / GitHub

Figma（UI設計）

 実装機能

ユーザー登録 / ログイン（Supabase Auth）

旅行プランの作成・編集・削除（CRUD）

行き先登録機能

行き先ごとのスポット管理

日付ごとのスケジュール管理

RLSによるユーザー別データ保護

 データ設計

trips テーブル

destinations テーブル

spots テーブル

schedules テーブル

ER図・ワイヤーフレームは docs/ ディレクトリに格納予定。

🎯 技術的な工夫

SupabaseのRLSを利用し、ユーザーごとにデータを分離

コンポーネント分割による再利用性の高い設計

Server / Client Componentの適切な使い分け

状態管理の最適化

今後の改善予定

Google Maps APIによる地図表示機能

旅行プランの共有機能

UI/UXの改善

レスポンシブ最適化

テストコード導入

制作背景

Next.jsの理解を深めるため

Supabaseを用いたフルスタック開発経験の習得

実務を想定したCRUDアプリ設計の練習

 開発について

設計・実装・調査をすべて個人で行っています。
開発過程ではChatGPTを活用しながら、理解を深めつつ実装しています。
