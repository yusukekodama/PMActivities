# Azure AD Knowledge Base へようこそ
- Azure Active Directory に関する有益な技術情報をマイクロソフト公式 / 非公式に関係なく集めた情報まとめサイトです。<br>

最近 Azure Active Directory について Doc や参考にできるリソースが増えてきて、私たち Azure Active Directory 開発チームメンバーとしてもお客様の疑問に対して提示する参考資料を悩んでしまうくらいになりました。このAzure AD Knowledge Base に Azure AD 関連の情報ソースを集約し公開することで少しでも皆様が Azure Active Directory を簡単に導入するためのお手伝いができればと考えています。

載せるべき情報で未掲載のものがあれば是非こちらの[**アンケートフォーム**](https://forms.office.com/Pages/ResponsePage.aspx?id=v4j5cvGGr0GRqy180BHbR0c2zLzd505PpWCpBKbso6xUQ09LWjBPN09SMUs1SEdTOUpFM0EwMU1UQi4u)からリクエストをお願いします。みんなでより良い情報データベースを作ることができればなと思います！



## Azure AD 全般情報収集
- [Azure AD 製品開発チーム主催 Webinar (日本語)](http://aka.ms/azureadwebinar) <br> これまで 4 シリーズ全 22 セッションを実施、レコーディングや資料のダウンロードもこちらから可能です！
    - Azure AD Webinar 検索用の [Power BI Dashboard](https://bit.ly/AzureAdWebinar) - カブコム石川さんにご提供いただきました！

- Blog (Microsoft 社員によるブログ) - 最新情報をキャッチするにはこちら
    - [EMS Blog](https://cloudblogs.microsoft.com/enterprisemobility/) <br> Azure AD 開発部門 による告知や Preview 情報が一番最初に公開されるのがここ
    - [Japan Azure Identity Support Blog ](https://jpazureid.github.io/blog) <br> 日本のサポートエンジニアによる、よくあるお問い合わせをベースとしたナレッジベースとして大好評のブログ

-	Deployment Guide - Azure AD の主要な機能の導入手順書
    - [Azure Active Directory deployment plans](http://aka.ms/deploymentplans)

-   [M365 roadmap](https://www.microsoft.com/en-us/microsoft-365/roadmap?filters=Azure%20Active%20Directory)


## 技術カテゴリ別リソース
- Zero Trust
    - [Zero Trust Deployment Center](http://aka.ms/ZTGuide)
- デバイス管理系
    - [デバイス登録フロー詳細](https://docs.microsoft.com/en-us/windows/security/identity-protection/hello-for-business/hello-how-it-works-device-registration) <br> Azure AD Join, Hybrid Azure AD Join 時のデバイスの Azure AD への登録フロー図
    - [Azure AD Join デバイスでオンプレリソースへの SSO が機能するしくみ](https://docs.microsoft.com/ja-jp/azure/active-directory/devices/azuread-join-sso) <br> Azure AD Join するとオンプレリソースへの SSO ができなくなる、というよくある誤解に対する回答がこちら
    - [Azure Active Directory by Jairo Cadena](https://jairocadena.com/) <br> 元 Device PM Jairo のブログ。未だに一番細かいことが記載されているトピックも存在

- 脱 ADFS
    - [ADFS からの Azure AD へのアプリケーション移行](aka.ms/migrateapps) - 現在 ADFS に連携されているアプリケーションを Azure AD 連携へ移行するために利用できるガイドやツール群
    - [SE03 Good Bye ADFS - Azure Active Directory Only の認証方式へ切り替えよう!](https://www.youtube.com/watch?v=o_MCm_0n2Jo&list=PLWtNmdzETm6ZAnpniNHh6NwLVGfp77ifn&index=2&t=1s)

- セキュリティ強化のためのステップバイステップ
    - [Five steps to securing your identity infrastructure](https://aka.ms/securitysteps)
    - [Identity and device access configurations](http://aka.ms/m365goldenconfig)
    - [Securing privileged access for hybrid and cloud deployments in Azure AD](aka.ms/breakglass)

- パスワードレス
    - パスワードレスウィザード：aka.ms/passwordlesswizard

- アプリケーション連携
    - [Azure AD 対応プロトコル一覧](https://docs.microsoft.com/en-us/azure/active-directory/fundamentals/auth-sync-overview)
    - [Decode20 S09 Apps on Azure AD アプリケーション連携の WHY と HOW](https://www.youtube.com/watch?v=dkbJXn04I9M)
    - [Azure AD App gallery への登録](https://docs.microsoft.com/ja-jp/azure/active-directory/develop/howto-app-gallery-listing)
    - Application Campaign 用マテリアル
        - Azure AD アプリケーション連携促進ポスター ([English](http://aka.ms/AppOnePager), [Japanese](http://aka.ms/AppOnePagerja))
        - Azure AD アプリケーション連携ガイドライン ([English](http://Aka.ms/AppGuideline), [Japanese](http://Aka.ms/AppGuidelineja))
    - [Azure AD SAML toolkit](https://samltoolkit.azurewebsites.net/)
    - [サポートされている認証フロー](https://docs.microsoft.com/ja-jp/azure/active-directory/develop/msal-authentication-flows)
    - [Permission grant チェックスクリプト](https://github.com/mepples21/azureadconfigassessment)

- 外部ユーザー連携関連
    - [Multi tenant collaboration case study paper](https://aka.ms/multi-tenant-users)
    - [Gathering information around external identity proliferation (for Access Reviews Disable-and-Delete) in Azure AD](https://github.com/microsoft/access-reviews-samples/tree/master/ExternalIdentityUse)
    - [Finding and reviewing external identities ("B2B Guests") that have never signed into your tenant, or have signed in to your tenant a long time ago](https://github.com/microsoft/access-reviews-samples/tree/master/ReviewStaleExternals)

- GEO
    - [Where your Microsoft 365 customer data is stored](https://docs.microsoft.com/en-us/office365/enterprise/o365-data-locations?geo=All)

## イベント/ウェビナー系
-	海外イベント
    - Ignite 2019
        - [Identity: The control plane for your digital transformation, now and into the future](https://myignite.techcommunity.microsoft.com/sessions/87373?source=sessions) <br>
        Ignite の Key Note session で SMBC 様が登壇し Cloud Provisioning の導入体験を語っています
        - [Bridge the gap between HR, IT and business with the Azure Active Directory identity provisioning platform](https://myignite.techcommunity.microsoft.com/sessions/81726?source=sessions) <br>
        Ignite の Provisioning break out session。上記の Key note よりも詳細に Cloud provisioning について紹介しています
    
-	国内イベント
    - Tech Summit 2017
        - [ネットワークエンジニア必見! VPN/DMZ は要らなくなる!? Application Proxy で実現するセキュアなアクセス](https://info.microsoft.com/JA-SCRTY-CNTNT-FY18-11Nov-18-Networkengineer-MGC0001441_01Registration-ForminBody.html)
    - De:code 2018
        - [AD FS では守れない？！アカウント乗っ取りを防ぐためにすべき 3 つのこと ～ユーザー企業の実例のご紹介～](https://youtu.be/g2mB_EKqi-g)
    - Tech Summit 2018
        - [開発部門が手掛けた Azure AD B2B 大規模展開 in Japan ～表面化した課題とそれらを解決する新機能・ロードマップ～](https://youtu.be/pHs0eQaicM4)
        - [VPN・証明書はもう不要? Azure ADによるデバイス認証](https://youtu.be/pfExM8YB7c0)

    - De:code 2019
        - [SE03 Good Bye ADFS - Azure Active Directory Only の認証方式へ切り替えよう!](https://www.youtube.com/watch?v=o_MCm_0n2Jo&list=PLWtNmdzETm6ZAnpniNHh6NwLVGfp77ifn&index=2&t=1s)
        - [SE82 20 分で理解する Azure Active Directory 最新アップデートと利活用シナリオ](https://www.youtube.com/watch?v=ypFr77WlJ3M&list=PLWtNmdzETm6ZAnpniNHh6NwLVGfp77ifn&index=3&t=0s)

-	Web/オンデマンド
    - [Azure AD youtube play list](https://www.youtube.com/playlist?list=PLLasX02E8BPBm1xNMRdvP6GtA6otQUqp0)  :Azure AD 各機能を説明した短編動画集 (5-10 分くらいで簡潔にまとまっているので、最初に見る動画として)
    - [Azure AD 製品開発チーム主催 Webinar (日本語)](http://aka.ms/azureadwebinar) <br> これまで 3 シリーズ全 16 セッションを実施、レコーディングや資料のダウンロードもこちらから可能です！
    - [Azure AD 製品開発チーム主催 Webinar (英語)](https://info.microsoft.com/AADP-Webinar-CLE_AADP-Main-Landing-Page.html?ls=Email)
    <br>
    日本語版と英語版ではセッションテーマや利用される資料、スピーカーが異なります。両方チェックしてください。

-  開発者向け
    - [Support single sign-on and app protection policies in mobile apps you develop](https://docs.microsoft.com/ja-jp/azure/active-directory/develop/mobile-sso-support-overview)
    - [Microsoft identity platform documentation](aka.ms/aaddev) :OAuth/OpenID Connect Sample code
    - [SCIM Reference code wiki](https://github.com/AzureAD/SCIMReferenceCode/wiki)
    - [Azure AD for Developers (Pluralsight)](https://www.pluralsight.com/courses/azure-active-directory-developers)
    - [Microsoft identity platform videos](https://www.pluralsight.com/courses/azure-active-directory-developers)  :開発者向け Youtube video シリーズ
    - [B2C sample code](https://github.com/azure-ad-b2c/samples)

## コード Repo
- [Identity GTP code repo](https://repos.opensource.microsoft.com/AzureAD/teams/identitygtp)

## DID
- [Verifiable Credentials Preview by Azure AD](https://didproject.azurewebsites.net/docs/overview.html)


## D&I
- [Exclusive terms](https://github.com/merill/InclusivenessAnalyzer/blob/main/terms.md)