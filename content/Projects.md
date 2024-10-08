+++
title = "Projects"
menu = "main"
+++

# Projects

## Twitter Clone
(2024/1~2024/3)
- **レポジトリー:** [Twitter-Clone](https://github.com/eightsuzuki/Twitter-Clone)
- **デモサイト:** [デモサイトURL](https://twitter-clone-next-js-eightsuzukis-projects.vercel.app/)
- **目的:** 学習目的で Twitter の主要機能を実装し、Next.js、NextAuth.js、Firebaseなどのテクノロジーを使用して、自身の技術スキルを向上させることを目指す。
- **課題:** Twitterの主要機能を含むクローンを開発するために、ユーザー認証、投稿の作成と管理、コメントやいいねの機能など、複雑な機能を統合する必要性。
- **解決策とプロセス:** NextAuth.jsを導入し、Firebaseを使用してGoogleアカウントでの認証を実装。Firebaseをデータベースとして使用し、投稿、コメント、およびいいねのデータを保存し、リアルタイムのデータ更新を可能に。Tailwind CSSを使用してレスポンシブなデザインを実装し、様々なデバイスや画面サイズに対応。
- **結果:** Twitterの主要機能を含むクローンを成功裏に実装し、ユーザーは投稿の作成、削除、コメント、いいねなどのアクションを実行できるようになった。サインインページでは、Googleアカウントを使用して認証できるようになり、セキュリティと利便性が向上。

## Reactを使用したGraphQLを使用した歌詞アプリ
(2023/12~2024/1)
- **レポジトリー:** [Lyrics-app-with-GraphQL-and-React](https://github.com/eightsuzuki/Lyrics-app-with-GraphQL-and-React)
- **目的:** GraphQLというクエリ言語およびAPIのためのランタイム環境について学ぶ。RESTとの違いを理解し、柔軟で効率的なクエリ言語の利用を目指す。
- **課題:** RESTful APIはエンドポイントごとにデータを提供するため、使用しない過剰なデータも取得することで過剰な通信が発生。GraphQLを使用するのが初めてであった。
- **解決策とプロセス:** GraphQLの基本的な使用方法を学ぶため、最初にGraphiQLで実際にjson-serverでqueryとmutationを実行しながら、データがやり取りされる仕組みを確認。
- **結果:** GraphQLを実際に使用し、スキーマが中心的な役割を果たし、データの型や関連性を適切に設計。余分なデータの取得を避け、リソースの無駄をなくすことができることを確認。

## マイクロサービスを採用したTicketing Service Webアプリ
(2023/10~2023/12)
- **レポジトリー:** [Ticketing-Service-Microservices-with-Node-JS-and-React
Public](https://github.com/eightsuzuki/Ticketing-Service-Microservices-with-Node-JS-and-React)
- **目的:** 大規模サービスを安定して提供する上で欠かせないマイクロサービスの概念を学び、非同期通信やサービスのカプセル化を体験することが目的。
- **課題:** マイクロサービスに特有の課題である、サービスの分割方法やサービス間の通信手法などに取り組んでいます。
- **解決策とプロセス:** AWS や GCP などの公式ドキュメントを参考にし、マイクロサービスの概念や設計方法を学習しました。これらのサービスで実際に使用されているサービス間通信の手法も参考にしました。
- **結果:** マイクロサービスを実際に構築し、故意に一部のサービスを停止させても他のサービスが正常に動作することを確認。データの整合性を確保しつつ、サービス間で通信するための基本的な手法や考え方を習得しました。

## Webサーバーフレームワークの構築
(2023/8~2023/9)
- **レポジトリー:** [GCDWebServer-Swift](https://github.com/eightsuzuki/GCDWebServer-Swift)
- **目的:** Webサーバーが実際にどのように動いているか理解し、軽量なGCDWebServerを構築して動作するかを確認。
- **課題:** 実際に実装していく上でSwiftを使用することが初めてであった。
- **解決策とプロセス:** Swiftの公式サイトのチュートリアルを読みながら学習。
- **結果:** GCDWebServerが正常に起動し、指定したポートでリクエストを待機していることを確認。ルーティングの動作と応答の確認。

## Reactの構築
(2023/5~2023/8)
- **レポジトリー:** [mini-react](https://github.com/eightsuzuki/mini-react)
- **目的:** Reactがどのように動いているか理解し、実際にReactを構築して動作するかを確認。Jestを使用したテストの方法も学習。
- **課題:** Jestを使用したテストが不慣れであり、JavaScriptの知識不足があった。
- **解決策とプロセス:** JSの専門書「You Don't Know JS」を読み知識不足を解消。Jestは公式サイトのチュートリアルを読みながら学習。
- **結果:** useStateやレンダリングの仕組みについて理解し、実際に実装。Jestを使用したテストの書き方についても学習。

# ハッカソン
## TaskHub
(2024/3/15-2024/3/24)
- **レポジトリー:** [TaskHub](https://github.com/eightsuzuki/Task_Management_App_Using_ReactNative)
- **目的:** ハッカソンに参加し、新しい技術に触りたいと思いreact-nativeでiosアプリを開発。
- **課題:** expo-goでの開発環境構築が初めてであり、環境構築が課題であった。classNameなどのCSSセレクターの使用不可。異なる解像度でのレイアウトへの適応。
- **解決策とプロセス:** expo-goの公式ドキュメントを参考に環境構築を行なった。CSSセレクターの代わりにStyleSheet Componentでのスタイリングを行なった。pxではなくdp、dip、ptを使用し異なる解像度でのレイアウトへの適応した。
- **結果:** ハッカソンで開発したiosアプリを公開できた。また、react-nativeの使い方を学んだ。
