# AIサービスのセキュリティ・規約まとめ

## はじめに
昨今、企業でもAIサービスの導入が進んでいますが、セキュリティや規約面でのチェックは大変です。そこで今回は主要なAIサービスについて、セキュリティの観点で比較してみました。企業でAIサービス導入を検討されているセキュリティご担当者の参考になれば幸いです。

## 本書について
- プルリクエストも歓迎しています。AIサービスは日々アップデートされるため、最新情報の追加にご協力いただけると助かります。
- 1人でメンテしているので、多少の誤字脱字や誤植は多めに見ていただけると幸いです。

## 免責事項
- 本資料は2024年6月時点の情報に基づくものであり、その正確性を保証するものではありません。
- 各社のサービス内容は頻繁に変更されるため、最新の情報は必ず公式サイトなどでご確認ください。
- 適用される規約や法令については、日本国内で一般的に利用する形を想定して記載しております。当然、企業間契約においては別の規約が適用される可能性がありますので、必ず自社の締結している契約をご確認ください。
- 本資料の利用によって生じたいかなる損害についても、著者は一切の責任を負いかねます。

## まとめ
<div style="overflow-x: auto;">
 <table>
   <thead>
     <tr>
       <th>ServiceType</th>
       <th>ServiceName</th>
       <th>ServicePlan/ModelName</th>
       <th>ServiceProvider</th>
       <th>ModelProvider</th>
       <th>Term</th>
       <th>Privacy Policy</th>
       <th>ModelTraining (学習利用)</th>
       <th>DataRetention (データ保持)</th>
       <th>Region</th>
       <th>Japan-Region</th>
       <th>GoverningLaw (準拠法)</th>
       <th>Jurisdiction (管轄裁判所)</th>
       <th>ISO27001</th>
       <th>SOC2</th>
       <th>ISMAP</th>
       <th>Note</th>
     </tr>
   </thead>
   <tbody>
     <tr>
      <th><!--Service Type-->SaaS</th>
      <th><!--Service Name--><a href="https://openai.com/chatgpt/">ChatGPT</a></th>
      <th><!--Plan/ Model-->Free Plan</th>
      <th><!--Service Provider--><a href="https://openai.com/about/">OpenAI</a></th>
      <th><!--Model Procider--><a href="https://openai.com/about/">OpenAI</a></th>
      <th><!--Term of Use--><a href="https://openai.com/ja-JP/policies/terms-of-use/">URL</a></th>
      <th><!--Privacy Policy--><a href="https://openai.com/ja-JP/policies/privacy-policy/">URL</a></th>
      <th><!--学習への利用--><a href="https://openai.com/ja-JP/policies/terms-of-use/">する</a></th>
      <th><!--データ保持--><a href="https://openai.com/ja-JP/policies/terms-of-use/">30日</a></th>
      <th><!--リージョン--><a href="https://openai.com/ja-JP/policies/terms-of-use/">US</a></th>
      <th><!--日本リージョン有無--><a href="https://openai.com/ja-JP/policies/terms-of-use/">なし</a></th>
      <th><!--準拠法--><a href="https://openai.com/ja-JP/policies/terms-of-use/">カリフォルニア州法</a></th>
      <th><!--管轄裁判所--><a href="https://openai.com/ja-JP/policies/terms-of-use/">カリフォルニア州サンフランシスコに所在する連邦裁判所又は州裁判所</a></th>
      <th><!--ISO27001--><a href="https://openai.com/policies/supplier-security-measures/">Yes</a></th>
      <th><!--SOC2-->NO</th>
      <th><!--ISMAP-->NO</th>
      <th><!--NOTE--></th>  
     </tr>
   </tbody>
  　　<tbody>
     <tr>
      <th><!--Service Type-->SaaS</th>
      <th><!--Service Name--><a href="https://openai.com/chatgpt/">ChatGPT</a></th>
      <th><!--Plan/ Model-->Plus Plan</th>
      <th><!--Service Provider--><a href="https://openai.com/about/">OpenAI</a></th>
      <th><!--Model Procider--><a href="https://openai.com/about/">OpenAI</a></th>
      <th><!--Term of Use--><a href="https://openai.com/ja-JP/policies/terms-of-use/">URL</a></th>
      <th><!--Privacy Policy--><a href="https://openai.com/ja-JP/policies/privacy-policy/">URL</a></th>
      <th><!--学習への利用--><a href="https://openai.com/ja-JP/policies/terms-of-use/">する</a></th>
      <th><!--データ保持--><a href="https://openai.com/ja-JP/policies/terms-of-use/">30日</a></th>
      <th><!--リージョン--><a href="https://openai.com/ja-JP/policies/terms-of-use/">US</a></th>
      <th><!--日本リージョン有無--><a href="https://openai.com/ja-JP/policies/terms-of-use/">なし</a></th>
      <th><!--準拠法-->同上</th>
      <th><!--管轄裁判所-->同上</th>
      <th><!--ISO27001--><a href="https://openai.com/policies/supplier-security-measures/">Yes</a></th>
      <th><!--SOC2-->NO</th>
      <th><!--ISMAP-->NO</th>
      <th><!--NOTE--></th>
     </tr>
   </tbody>
    　　<tbody>
     <tr>
      <th><!--Service Type-->SaaS</th>
      <th><!--Service Name--><a href="https://openai.com/chatgpt/">ChatGPT</a></th>
      <th><!--Plan/ Model-->Team Plan</th>
      <th><!--Service Provider--><a href="https://openai.com/about/">OpenAI</a></th>
      <th><!--Model Procider--><a href="https://openai.com/about/">OpenAI</a></th>
      <th><!--Term of Use--><a href="https://openai.com/policies/business-terms/">URL</a></th>
      <th><!--Privacy Policy--><a href="https://openai.com/ja-JP/policies/privacy-policy/">URL</a></th>
      <th><!--学習への利用--><a href="https://openai.com/policies/business-terms/">しない</a></th>
      <th><!--データ保持--><a href="https://openai.com/policies/business-terms/">30日</a></th>
      <th><!--リージョン--><a href="https://openai.com/policies/business-terms/">US</a></th>
      <th><!--日本リージョン有無--><a href="https://openai.com/ja-JP/policies/terms-of-use/">なし</a></th>
      <th><!--準拠法-->同上</th>
      <th><!--管轄裁判所-->同上</th>
      <th><!--ISO27001--><a href="https://openai.com/policies/supplier-security-measures/">Yes</a></th>
      <th><!--SOC2--><a href="https://trust.openai.com/">Type2</a></th>
      <th><!--ISMAP-->NO</th>
      <th><!--NOTE--></th>
     </tr>
   </tbody>
    　　<tbody>
     <tr>
      <th><!--Service Type-->SaaS</th>
      <th><!--Service Name--><a href="https://openai.com/chatgpt/">ChatGPT</a></th>
      <th><!--Plan/ Model-->Enterprise Plan</th>
      <th><!--Service Provider--><a href="https://openai.com/about/">OpenAI</a></th>
      <th><!--Model Procider--><a href="https://openai.com/about/">OpenAI</a></th>
      <th><!--Term of Use--><a href="https://openai.com/policies/business-terms/">URL</a></th>
      <th><!--Privacy Policy--><a href="https://openai.com/ja-JP/policies/privacy-policy/">URL</a></th>
      <th><!--学習への利用--><a href="https://openai.com/policies/business-terms/">しない</a></th>
      <th><!--データ保持--><a href="https://openai.com/policies/business-terms/">30日</a></th>
      <th><!--リージョン--><a href="https://openai.com/policies/business-terms/">US</a></th>
      <th><!--日本リージョン有無--><a href="https://openai.com/ja-JP/policies/terms-of-use/">なし</a></th>
      <th><!--準拠法-->同上</th>
      <th><!--管轄裁判所-->同上</th>
      <th><!--ISO27001--><a href="https://openai.com/policies/supplier-security-measures/">Yes</a></th>
      <th><!--SOC2--><a href="https://trust.openai.com/">Type2</a></th>
      <th><!--ISMAP-->NO</th>
      <th><!--NOTE--></th>
     </tr>
   </tbody>
   <tbody>
     <tr>
      <th><!--Service Type-->API</th>
      <th><!--Service Name--><a href="https://openai.com/index/openai-api/">OpenAI API</a></th>
      <th><!--Plan/ Model-->GPT/Whisper/DALL·E</th>
      <th><!--Service Provider--><a href="https://openai.com/about/">OpenAI</a></th>
      <th><!--Model Procider--><a href="https://openai.com/about/">OpenAI</a></th>
      <th><!--Term of Use--><a href="https://openai.com/policies/business-terms/">URL</a></th>
      <th><!--Privacy Policy--><a href="https://openai.com/ja-JP/policies/privacy-policy/">URL</a></th>
      <th><!--学習への利用--><a href="https://openai.com/policies/business-terms/">しない</a></th>
      <th><!--データ保持--><a href="https://openai.com/policies/business-terms/">30日</a></th>
      <th><!--リージョン--><a href="https://openai.com/policies/business-terms/">US</a></th>
      <th><!--日本リージョン有無--><a href="https://openai.com/ja-JP/policies/terms-of-use/">なし</a></th>
      <th><!--準拠法-->同上</th>
      <th><!--管轄裁判所-->同上</th>
      <th><!--ISO27001--><a href="https://openai.com/policies/supplier-security-measures/">Yes</a></th>
      <th><!--SOC2--><a href="https://trust.openai.com/">Type2</a></th>
      <th><!--ISMAP-->NO</th>
      <th><!--NOTE--></th>
     </tr>
   </tbody>
   <tbody>
     <tr>
      <th><!--Service Type-->API</th>
      <th><!--Service Name--><a href="https://learn.microsoft.com/en-us/azure/ai-services/openai/"></a>Azure OpenAI</th>
      <th><!--Plan/ Model-->GPT/Whisper/DALL·E</th>
      <th><!--Service Provider--><a href="https://www.microsoft.com/ja-jp/">Microsoft</a></th>
      <th><!--Model Procider--><a href="https://openai.com/about/">OpenAI</a></th>
      <th><!--Term of Use--><a href="https://www.microsoft.com/licensing/docs/customeragreement">URL</a></th>
      <th><!--Privacy Policy--><a href="https://learn.microsoft.com/en-us/legal/cognitive-services/openai/data-privacy">URL</a></th>
      <th><!--学習への利用--><a href="https://learn.microsoft.com/en-us/legal/cognitive-services/openai/data-privacy">しない</a></th>
      <th><!--データ保持--><a href="https://learn.microsoft.com/en-us/legal/cognitive-services/openai/data-privacy">30日</a> ※<a href="https://learn.microsoft.com/en-us/azure/ai-services/openai/concepts/abuse-monitoring#:~:text=Azure%20OpenAI%20Limited%20Access%20Review%3A%20Modified%20Abuse%20Monitoring">オプトアウト申請</a>が承認されれば、データは保持されない。</th>
      <th><!--リージョン--><a href="https://learn.microsoft.com/ja-jp/azure/ai-services/openai/concepts/models#standard-deployment-model-availability">世界各地</a></th>
      <th><!--日本リージョン有無--><a href="https://learn.microsoft.com/ja-jp/azure/ai-services/openai/concepts/models#standard-deployment-model-availability">あり</a></th>
      <th><!--準拠法--><a href="https://www.microsoft.com/licensing/docs/customeragreement">日本法</a></th>
      <th><!--管轄裁判所--><a href="https://www.microsoft.com/licensing/docs/customeragreement">東京地方裁判所</a></th>
      <th><!--ISO27001--><a href="https://learn.microsoft.com/en-us/azure/compliance/offerings/offering-iso-27001">Yes</a></th>
      <th><!--SOC2--><a href="https://learn.microsoft.com/en-us/azure/compliance/offerings/offering-soc-2">Type2</a></th>
      <th><!--ISMAP--><a href="https://www.ismap.go.jp/csm?id=cloud_service_list_detail&sys_id=aca3e34e938c8e100072f4fe3bba10ba">Yes</a></th>
      <th><!--NOTE--></th>
     </tr>
   </tbody>
   <tbody>
     <tr>
      <th><!--Service Type--></th>
      <th><!--Service Name-->Copilot for Microsft 365</th>
      <th><!--Plan/ Model-->SaaS</th>
      <th><!--Service Provider-->同上</th>
      <th><!--Model Procider-->同上</th>
      <th><!--Term of Use--><a href=""></a></th>
      <th><!--Privacy Policy--><a href=""></a></th>
      <th><!--学習への利用--><a href=""></a></th>
      <th><!--データ保持--><a href=""></a></th>
      <th><!--リージョン--><a href=""></a></th>
      <th><!--日本リージョン有無--><a href=""></a></th>
      <th><!--準拠法--><a href=""></a></th>
      <th><!--管轄裁判所--><a href=""></a></th>
      <th><!--ISO27001--></th>
      <th><!--SOC2--></th>
      <th><!--ISMAP-->NO</th>
      <th><!--NOTE--></th>
     </tr>
   </tbody>
   <tbody>
     <tr>
      <th><!--Service Type--></th>
      <th><!--Service Name-->Copilot 商用データ保護 </th>
      <th><!--Plan/ Model--></th>
      <th><!--Service Provider--></th>
      <th><!--Model Procider--></th>
      <th><!--Term of Use--></th>
      <th><!--Privacy Policy--></th>
      <th><!--学習への利用--></th>
      <th><!--データ保持--></th>
      <th><!--リージョン--></th>
      <th><!--日本リージョン有無--></th>
      <th><!--準拠法--></th>
      <th><!--管轄裁判所--></th>
      <th><!--ISO27001--></th>
      <th><!--SOC2--></th>
      <th><!--ISMAP--></th>
      <th><!--NOTE-->旧：Bing Search Enterprise </th>
     </tr>
   </tbody>
   <tbody>
     <tr>
      <th><!--Service Type--></th>
      <th><!--Service Name-->Copilot</th>
      <th><!--Plan/ Model--></th>
      <th><!--Service Provider--></th>
      <th><!--Model Procider--></th>
      <th><!--Term of Use--></th>
      <th><!--Privacy Policy--></th>
      <th><!--学習への利用--></th>
      <th><!--データ保持--></th>
      <th><!--リージョン--></th>
      <th><!--日本リージョン有無--></th>
      <th><!--準拠法--></th>
      <th><!--管轄裁判所--></th>
      <th><!--ISO27001--></th>
      <th><!--SOC2--></th>
      <th><!--ISMAP--></th>
      <th><!--NOTE--></th>
     </tr>
   </tbody>
   <tbody>
     <tr>
      <th><!--Service Type--></th>
      <th><!--Service Name-->GithubCopilot</th>
      <th><!--Plan/ Model--></th>
      <th><!--Service Provider--></th>
      <th><!--Model Procider--></th>
      <th><!--Term of Use--></th>
      <th><!--Privacy Policy--></th>
      <th><!--学習への利用--></th>
      <th><!--データ保持--></th>
      <th><!--リージョン--></th>
      <th><!--日本リージョン有無--></th>
      <th><!--準拠法--></th>
      <th><!--管轄裁判所--></th>
      <th><!--ISO27001--></th>
      <th><!--SOC2--></th>
      <th><!--ISMAP--></th>
      <th><!--NOTE--></th>
     </tr>
   </tbody>
   <tbody>
     <tr>
      <th><!--Service Type--></th>
      <th><!--Service Name-->Github Copilot Enterprise</th>
      <th><!--Plan/ Model--></th>
      <th><!--Service Provider--></th>
      <th><!--Model Procider--></th>
      <th><!--Term of Use--></th>
      <th><!--Privacy Policy--></th>
      <th><!--学習への利用--></th>
      <th><!--データ保持--></th>
      <th><!--リージョン--></th>
      <th><!--日本リージョン有無--></th>
      <th><!--準拠法--></th>
      <th><!--管轄裁判所--></th>
      <th><!--ISO27001--></th>
      <th><!--SOC2--></th>
      <th><!--ISMAP--></th>
      <th><!--NOTE--></th>
     </tr>
   </tbody>
   <tbody>
     <tr>
      <th><!--Service Type--></th>
      <th><!--Service Name-->Vertex AI (Free)</th>
      <th><!--Plan/ Model--></th>
      <th><!--Service Provider--></th>
      <th><!--Model Procider--></th>
      <th><!--Term of Use--></th>
      <th><!--Privacy Policy--></th>
      <th><!--学習への利用--></th>
      <th><!--データ保持--></th>
      <th><!--リージョン--></th>
      <th><!--日本リージョン有無--></th>
      <th><!--準拠法--></th>
      <th><!--管轄裁判所--></th>
      <th><!--ISO27001--></th>
      <th><!--SOC2--></th>
      <th><!--ISMAP--></th>
      <th><!--NOTE--></th>
     </tr>
   </tbody>
   <tbody>
     <tr>
      <th><!--Service Type--></th>
      <th><!--Service Name-->Vertex AI (Pay as you go)</th>
      <th><!--Plan/ Model--></th>
      <th><!--Service Provider--></th>
      <th><!--Model Procider--></th>
      <th><!--Term of Use--></th>
      <th><!--Privacy Policy--></th>
      <th><!--学習への利用--></th>
      <th><!--データ保持--></th>
      <th><!--リージョン--></th>
      <th><!--日本リージョン有無--></th>
      <th><!--準拠法--></th>
      <th><!--管轄裁判所--></th>
      <th><!--ISO27001--></th>
      <th><!--SOC2--></th>
      <th><!--ISMAP--></th>
      <th><!--NOTE--></th>
     </tr>
   </tbody>
   <tbody>
     <tr>
      <th><!--Service Type--></th>
      <th><!--Service Name-->Gemini Advanced</th>
      <th><!--Plan/ Model--></th>
      <th><!--Service Provider--></th>
      <th><!--Model Procider--></th>
      <th><!--Term of Use--></th>
      <th><!--Privacy Policy--></th>
      <th><!--学習への利用--></th>
      <th><!--データ保持--></th>
      <th><!--リージョン--></th>
      <th><!--日本リージョン有無--></th>
      <th><!--準拠法--></th>
      <th><!--管轄裁判所--></th>
      <th><!--ISO27001--></th>
      <th><!--SOC2--></th>
      <th><!--ISMAP--></th>
      <th><!--NOTE--></th>      
     </tr>
   </tbody>
   <tbody>
     <tr>
      <th><!--Service Type--></th>
      <th><!--Service Name-->Gemini Business</th>
      <th><!--Plan/ Model--></th>
      <th><!--Service Provider--></th>
      <th><!--Model Procider--></th>
      <th><!--Term of Use--></th>
      <th><!--Privacy Policy--></th>
      <th><!--学習への利用--></th>
      <th><!--データ保持--></th>
      <th><!--リージョン--></th>
      <th><!--日本リージョン有無--></th>
      <th><!--準拠法--></th>
      <th><!--管轄裁判所--></th>
      <th><!--ISO27001--></th>
      <th><!--SOC2--></th>
      <th><!--ISMAP--></th>
      <th><!--NOTE--></th>
     </tr>
   </tbody>
   <tbody>
     <tr>
      <th><!--Service Type--></th>
      <th><!--Service Name-->Gemini Enterprise</th>
      <th><!--Plan/ Model--></th>
      <th><!--Service Provider--></th>
      <th><!--Model Procider--></th>
      <th><!--Term of Use--></th>
      <th><!--Privacy Policy--></th>
      <th><!--学習への利用--></th>
      <th><!--データ保持--></th>
      <th><!--リージョン--></th>
      <th><!--日本リージョン有無--></th>
      <th><!--準拠法--></th>
      <th><!--管轄裁判所--></th>
      <th><!--ISO27001--></th>
      <th><!--SOC2--></th>
      <th><!--ISMAP--></th>
      <th><!--NOTE--></th>
     </tr>
   </tbody>
   <tbody>
     <tr>
      <th><!--Service Type--></th>
      <th><!--Service Name-->Claude</th>
      <th><!--Plan/ Model--></th>
      <th><!--Service Provider--></th>
      <th><!--Model Procider--></th>
      <th><!--Term of Use--></th>
      <th><!--Privacy Policy--></th>
      <th><!--学習への利用--></th>
      <th><!--データ保持--></th>
      <th><!--リージョン--></th>
      <th><!--日本リージョン有無--></th>
      <th><!--準拠法--></th>
      <th><!--管轄裁判所--></th>
      <th><!--ISO27001--></th>
      <th><!--SOC2--></th>
      <th><!--ISMAP--></th>
      <th><!--NOTE--></th>
     </tr>
   </tbody>
   <tbody>
     <tr>
      <th><!--Service Type--></th>
      <th><!--Service Name-->Claude Pro</th>
      <th><!--Plan/ Model--></th>
      <th><!--Service Provider--></th>
      <th><!--Model Procider--></th>
      <th><!--Term of Use--></th>
      <th><!--Privacy Policy--></th>
      <th><!--学習への利用--></th>
      <th><!--データ保持--></th>
      <th><!--リージョン--></th>
      <th><!--日本リージョン有無--></th>
      <th><!--準拠法--></th>
      <th><!--管轄裁判所--></th>
      <th><!--ISO27001--></th>
      <th><!--SOC2--></th>
      <th><!--ISMAP--></th>
      <th><!--NOTE--></th>
     </tr>
   </tbody>
   <tbody>
     <tr>
      <th><!--Service Type--></th>
      <th><!--Service Name-->Claude Team</th>
      <th><!--Plan/ Model--></th>
      <th><!--Service Provider--></th>
      <th><!--Model Procider--></th>
      <th><!--Term of Use--></th>
      <th><!--Privacy Policy--></th>
      <th><!--学習への利用--></th>
      <th><!--データ保持--></th>
      <th><!--リージョン--></th>
      <th><!--日本リージョン有無--></th>
      <th><!--準拠法--></th>
      <th><!--管轄裁判所--></th>
      <th><!--ISO27001--></th>
      <th><!--SOC2--></th>
      <th><!--ISMAP--></th>
      <th><!--NOTE--></th>
     </tr>
   </tbody>
   <tbody>
     <tr>
      <th><!--Service Type--></th>
      <th><!--Service Name-->Claude API</th>
      <th><!--Plan/ Model--></th>
      <th><!--Service Provider--></th>
      <th><!--Model Procider--></th>
      <th><!--Term of Use--></th>
      <th><!--Privacy Policy--></th>
      <th><!--学習への利用--></th>
      <th><!--データ保持--></th>
      <th><!--リージョン--></th>
      <th><!--日本リージョン有無--></th>
      <th><!--準拠法--></th>
      <th><!--管轄裁判所--></th>
      <th><!--ISO27001--></th>
      <th><!--SOC2--></th>
      <th><!--ISMAP--></th>
      <th><!--NOTE--></th>
     </tr>
   </tbody>
   <tbody>
     <tr>
      <th><!--Service Type--></th>
      <th><!--Service Name-->Amazon Bedrock</th>
      <th><!--Plan/ Model--></th>
      <th><!--Service Provider--></th>
      <th><!--Model Procider--></th>
      <th><!--Term of Use--></th>
      <th><!--Privacy Policy--></th>
      <th><!--学習への利用--></th>
      <th><!--データ保持--></th>
      <th><!--リージョン--></th>
      <th><!--日本リージョン有無--></th>
      <th><!--準拠法--></th>
      <th><!--管轄裁判所--></th>
      <th><!--ISO27001--></th>
      <th><!--SOC2--></th>
      <th><!--ISMAP--><a href="https://www.ismap.go.jp/csm?id=cloud_service_list_detail&sys_id=c8e0b6cc9361c610a734bb497bba104f">Yes</a></th>
      <th><!--NOTE--></th>
     </tr>
   </tbody>
   <tbody>
     <tr>
      <th><!--Service Type--></th>
      <th><!--Service Name-->Bedrock (Taitan)</th>
      <th><!--Plan/ Model--></th>
      <th><!--Service Provider--></th>
      <th><!--Model Procider--></th>
      <th><!--Term of Use--></th>
      <th><!--Privacy Policy--></th>
      <th><!--学習への利用--></th>
      <th><!--データ保持--></th>
      <th><!--リージョン--></th>
      <th><!--日本リージョン有無--></th>
      <th><!--準拠法--></th>
      <th><!--管轄裁判所--></th>
      <th><!--ISO27001--></th>
      <th><!--SOC2--></th>
      <th><!--ISMAP--></th>
      <th><!--NOTE--></th>
     </tr>
   </tbody>
   <tbody>
     <tr>
      <th><!--Service Type--></th>
      <th><!--Service Name-->Notion AI</th>
      <th><!--Plan/ Model--></th>
      <th><!--Service Provider--></th>
      <th><!--Model Procider--></th>
      <th><!--Term of Use--></th>
      <th><!--Privacy Policy--></th>
      <th><!--学習への利用--></th>
      <th><!--データ保持--></th>
      <th><!--リージョン--></th>
      <th><!--日本リージョン有無--></th>
      <th><!--準拠法--></th>
      <th><!--管轄裁判所--></th>
      <th><!--ISO27001--></th>
      <th><!--SOC2--></th>
      <th><!--ISMAP--></th>
      <th><!--NOTE--></th>
     </tr>
   </tbody>
   <tbody>
     <tr>
      <th><!--Service Type--></th>
      <th><!--Service Name-->Box AI</th>
      <th><!--Plan/ Model--></th>
      <th><!--Service Provider--></th>
      <th><!--Model Procider--></th>
      <th><!--Term of Use--></th>
      <th><!--Privacy Policy--></th>
      <th><!--学習への利用--></th>
      <th><!--データ保持--></th>
      <th><!--リージョン--></th>
      <th><!--日本リージョン有無--></th>
      <th><!--準拠法--></th>
      <th><!--管轄裁判所--></th>
      <th><!--ISO27001--></th>
      <th><!--SOC2--></th>
      <th><!--ISMAP--></th>
      <th><!--NOTE--></th>
     </tr>
   </tbody>
   <tbody>
     <tr>
      <th><!--Service Type--></th>
      <th><!--Service Name-->Slack AI</th>
      <th><!--Plan/ Model--></th>
      <th><!--Service Provider--></th>
      <th><!--Model Procider--></th>
      <th><!--Term of Use--></th>
      <th><!--Privacy Policy--></th>
      <th><!--学習への利用--></th>
      <th><!--データ保持--></th>
      <th><!--リージョン--></th>
      <th><!--日本リージョン有無--></th>
      <th><!--準拠法--></th>
      <th><!--管轄裁判所--></th>
      <th><!--ISO27001--></th>
      <th><!--SOC2--></th>
      <th><!--ISMAP--></th>
      <th><!--NOTE--></th>  
     </tr>
   </tbody>
 </table>
</div>
