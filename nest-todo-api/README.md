<p align="center">
  <a href="http://nestjs.com/" target="blank"><img src="https://nestjs.com/img/logo-small.svg" width="120" alt="Nest Logo" /></a>
</p>

[circleci-image]: https://img.shields.io/circleci/build/github/nestjs/nest/master?token=abc123def456
[circleci-url]: https://circleci.com/gh/nestjs/nest

  <p align="center">A progressive <a href="http://nodejs.org" target="_blank">Node.js</a> framework for building efficient and scalable server-side applications.<br>効率的でスケーラブルなサーバーサイドアプリケーションを構築するための、進歩的な Node.js フレームワーク。</p>
    <p align="center">
<a href="https://www.npmjs.com/~nestjscore" target="_blank"><img src="https://img.shields.io/npm/v/@nestjs/core.svg" alt="NPM Version" /></a>
<a href="https://www.npmjs.com/~nestjscore" target="_blank"><img src="https://img.shields.io/npm/l/@nestjs/core.svg" alt="Package License" /></a>
<a href="https://www.npmjs.com/~nestjscore" target="_blank"><img src="https://img.shields.io/npm/dm/@nestjs/common.svg" alt="NPM Downloads" /></a>
<a href="https://circleci.com/gh/nestjs/nest" target="_blank"><img src="https://img.shields.io/circleci/build/github/nestjs/nest/master" alt="CircleCI" /></a>
<a href="https://discord.gg/G7Qnnhy" target="_blank"><img src="https://img.shields.io/badge/discord-online-brightgreen.svg" alt="Discord"/></a>
<a href="https://opencollective.com/nest#backer" target="_blank"><img src="https://opencollective.com/nest/backers/badge.svg" alt="Backers on Open Collective" /></a>
<a href="https://opencollective.com/nest#sponsor" target="_blank"><img src="https://opencollective.com/nest/sponsors/badge.svg" alt="Sponsors on Open Collective" /></a>
  <a href="https://paypal.me/kamilmysliwiec" target="_blank"><img src="https://img.shields.io/badge/Donate-PayPal-ff3f59.svg" alt="Donate us"/></a>
    <a href="https://opencollective.com/nest#sponsor"  target="_blank"><img src="https://img.shields.io/badge/Support%20us-Open%20Collective-41B883.svg" alt="Support us"></a>
  <a href="https://twitter.com/nestframework" target="_blank"><img src="https://img.shields.io/twitter/follow/nestframework.svg?style=social&label=Follow" alt="Follow us on Twitter"></a>
</p>
  <!--[![Backers on Open Collective](https://opencollective.com/nest/backers/badge.svg)](https://opencollective.com/nest#backer)
  [![Sponsors on Open Collective](https://opencollective.com/nest/sponsors/badge.svg)](https://opencollective.com/nest#sponsor)-->

## Description (説明)

[Nest](https://github.com/nestjs/nest) framework TypeScript starter repository.  
[Nest](https://github.com/nestjs/nest) フレームワークの TypeScript スターターリポジトリ。

## Project setup (プロジェクトのセットアップ)

```bash
$ npm install
```

## Compile and run the project (プロジェクトをコンパイルして実行する)

```bash
# development (開発)
$ npm run start

# watch mode (ウォッチモード：開発中にコードを頻繁に変更する場合に非常に便利な機能)
$ npm run start:dev

# production mode (本番モード)
$ npm run start:prod
```

## Run tests (テストを実行する)

```bash
# unit tests (ユニットテスト)
$ npm run test

# e2e tests (e2e テスト)
$ npm run test:e2e

# test coverage (テストカバレッジ)
$ npm run test:cov
```

## Deployment (開発)

When you're ready to deploy your NestJS application to production, there are some key steps you can take to ensure it runs as efficiently as possible. Check out the [deployment documentation](https://docs.nestjs.com/deployment) for more information.  
NestJS アプリケーションを本番環境にデプロイする準備ができたら、アプリケーションをできるだけ効率的に実行するために実行できる重要な手順がいくつかあります。詳細については、[デプロイ ドキュメント](https://docs.nestjs.com/deployment) を参照してください。

If you are looking for a cloud-based platform to deploy your NestJS application, check out [Mau](https://mau.nestjs.com), our official platform for deploying NestJS applications on AWS. Mau makes deployment straightforward and fast, requiring just a few simple steps:  
NestJS アプリケーションをデプロイするためのクラウドベースのプラットフォームをお探しの場合は、AWS に NestJS アプリケーションをデプロイするための公式プラットフォームである [Mau](https://mau.nestjs.com) をご覧ください。Mau を使用すると、デプロイが簡単かつ高速になり、必要な手順はわずか数ステップです。

```bash
$ npm install -g mau
$ mau deploy
```

With Mau, you can deploy your application in just a few clicks, allowing you to focus on building features rather than managing infrastructure.  
Mau を使用すると、数回クリックするだけでアプリケーションをデプロイできるため、インフラストラクチャの管理ではなく機能の構築に集中できます。

## Resources (リソース)

Check out a few resources that may come in handy when working with NestJS:  
NestJS を使用するときに役立つ可能性のあるリソースをいくつか確認してください。

- Visit the [NestJS Documentation](https://docs.nestjs.com) to learn more about the framework.  
フレームワークの詳細については、[NestJS ドキュメント](https://docs.nestjs.com)をご覧ください。
- For questions and support, please visit our [Discord channel](https://discord.gg/G7Qnnhy).  
ご質問やサポートについては、[Discord チャンネル](https://discord.gg/G7Qnnhy) をご覧ください。
- To dive deeper and get more hands-on experience, check out our official video [courses](https://courses.nestjs.com/).  
さらに深く掘り下げて実践的な経験を積むには、公式ビデオ [コース](https://courses.nestjs.com/) をご覧ください。
- Deploy your application to AWS with the help of [NestJS Mau](https://mau.nestjs.com) in just a few clicks.  
[NestJS Mau](https://mau.nestjs.com) を使用すると、数回クリックするだけでアプリケーションを AWS にデプロイできます。
- Visualize your application graph and interact with the NestJS application in real-time using [NestJS Devtools](https://devtools.nestjs.com).  
NestJS Devtools](https://devtools.nestjs.com) を使用して、アプリケーション グラフを視覚化し、NestJS アプリケーションをリアルタイムで操作します。
- Need help with your project (part-time to full-time)? Check out our official [enterprise support](https://enterprise.nestjs.com).  
プロジェクトに関してサポートが必要ですか (パートタイムからフルタイムまで)? 公式の [エンタープライズ サポート](https://enterprise.nestjs.com) をご覧ください。
- To stay in the loop and get updates, follow us on [X](https://x.com/nestframework) and [LinkedIn](https://linkedin.com/company/nestjs).  
最新情報を入手するには、[X](https://x.com/nestframework) と [LinkedIn](https://linkedin.com/company/nestjs) をフォローしてください。
- Looking for a job, or have a job to offer? Check out our official [Jobs board](https://jobs.nestjs.com).  
仕事をお探しですか、それとも仕事をお持ちですか? 公式の[求人掲示板](https://jobs.nestjs.com)をご覧ください。

## Support (サポート)

Nest is an MIT-licensed open source project. It can grow thanks to the sponsors and support by the amazing backers. If you'd like to join them, please [read more here](https://docs.nestjs.com/support).  
Nest は MIT ライセンスのオープンソース プロジェクトです。スポンサーと素晴らしい支援者のサポートのおかげで成長することができます。参加をご希望の場合は、[詳細はこちら](https://docs.nestjs.com/support) をご覧ください。

## Stay in touch (連絡を取り合う)

- Author (著者) - [Kamil Myśliwiec](https://twitter.com/kammysliwiec)
- Website (Webサイト) - [https://nestjs.com](https://nestjs.com/)
- Twitter (ツイッター) - [@nestframework](https://twitter.com/nestframework)

## License (ライセンス)

Nest is [MIT licensed](https://github.com/nestjs/nest/blob/master/LICENSE).  
Nestは[MITライセンス](https://github.com/nestjs/nest/blob/master/LICENSE)です。

