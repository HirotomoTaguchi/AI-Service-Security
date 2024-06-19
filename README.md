# AIサービスのセキュリティ・規約まとめ

## はじめに
昨今、企業でもAIサービスの導入が進んでいますが、セキュリティや規約面でのチェックは大変です。そこで今回は主要なAIサービスについて、セキュリティの観点で比較してみました。企業でAIサービス導入を検討されているセキュリティご担当者の参考になれば幸いです。

## 本書について
- プルリクエストも歓迎しています。AIサービスは日々アップデートされるため、最新情報の追加にご協力いただけると助かります。
- 1人でメンテしているので、多少の誤字脱字や誤植は多めに見ていただけると幸いです。

## 免責事項
- 本資料は2024年6月時点の情報に基づくものであり、その正確性を保証するものではありません。
- 各社のサービス内容は頻繁に変更されるため、最新の情報は必ず公式サイトなどでご確認ください。
- 適用される規約や法令については、お住まいの国または地域 (企業の場合は主たる業務地) が日本である前提で記載をしております。当然、企業間契約においては別の規約が適用される可能性がありますので、必ず自社の締結している契約をご確認ください。
- 本資料の利用によって生じたいかなる損害についても、著者は一切の責任を負いかねます。

## まとめ
<div style="overflow-x: auto;">
 <table>
   <thead>
     <tr>
       <th>Generative_AI_Service_Name</th>
       <th>Service_Plan/AI_Model_Name</th>
       <th>Service_Type</th>
       <th>Terget</th>
       <th>Service_Provider</th>
       <th>Model_Provider</th>
       <th>Term</th>
       <th>Privacy Policy</th>
       <th>AI_Model_Training_by_default (既定での学習利用)</th>
       <th>Data_Retention (データ保持)</th>
       <th>Data_Center_Region</th>
       <th>Japan_Region</th>
       <th>Governing_Law (準拠法)</th>
       <th>Competent_Court (管轄裁判所)</th>
       <th>ISO_27001</th>
       <th>SOC_2</th>
       <th>ISMAP</th>
       <th>Other_noteworthy_items</th>
     </tr>
   </thead>
   <tbody>
     <tr>
      <th><!--Service Name--><a href="https://openai.com/chatgpt/">ChatGPT</a></th>
      <th><!--Plan/ Model-->Free Plan</th>
      <th><!--Service Type-->SaaS</th>
      <th><!--Terget-->個人</th>
      <th><!--Service Provider--><a href="https://openai.com/about/">OpenAI</a></th>
      <th><!--Model Procider--><a href="https://openai.com/about/">OpenAI</a></th>
      <th><!--Term of Use--><a href="https://openai.com/ja-JP/policies/terms-of-use/">URL</a></th>
      <th><!--Privacy Policy--><a href="https://openai.com/ja-JP/policies/privacy-policy/">URL</a></th>
      <th><!--学習への利用--><a href="https://openai.com/ja-JP/policies/terms-of-use/">する</a></th>
      <th><!--データ保持--><a href="https://openai.com/ja-JP/policies/terms-of-use/">30日</a></th>
      <th><!--リージョン--><a href="https://openai.com/ja-JP/policies/terms-of-use/">US</a></th>
      <th><!--日本リージョン有無--><a href="https://openai.com/ja-JP/policies/terms-of-use/">なし</a></th>
      <th><!--準拠法--><a href="https://openai.com/ja-JP/policies/terms-of-use/">カリフォルニア州法</a></th>
      <th><!--管轄裁判所--><a href="https://openai.com/ja-JP/policies/terms-of-use/">サンフランシスコに所在する連邦裁判所又は州裁判所</a></th>
      <th><!--ISO27001--><a href="https://openai.com/policies/supplier-security-measures/">Yes</a></th>
      <th><!--SOC2-->NO</th>
      <th><!--ISMAP-->NO</th>
      <th><!--NOTE--></th>  
     </tr>
   </tbody>
  　　<tbody>
     <tr>
      <th><!--Service Name--><a href="https://openai.com/chatgpt/">ChatGPT</a></th>
      <th><!--Plan/ Model-->Plus Plan</th>
      <th><!--Service Type-->SaaS</th>
      <th><!--Terget-->個人</th>
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
      <th><!--Service Name--><a href="https://openai.com/chatgpt/">ChatGPT</a></th>
      <th><!--Plan/ Model-->Team Plan</th>
      <th><!--Service Type-->SaaS</th>
      <th><!--Terget-->法人</th>
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
      <th><!--Service Name--><a href="https://openai.com/chatgpt/">ChatGPT</a></th>
      <th><!--Plan/ Model-->Enterprise Plan</th>
      <th><!--Service Type-->SaaS</th>
      <th><!--Terget-->法人</th>
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
      <th><!--Service Name--><a href="https://openai.com/index/openai-api/">OpenAI API</a></th>
      <th><!--Plan/ Model-->GPT/Whisper/DALL·E</th>
      <th><!--Service Type-->API</th>
      <th><!--Terget-->個人/法人</th>
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
      <th><!--Service Name--><a href="https://learn.microsoft.com/en-us/azure/ai-services/openai/">Azure OpenAI Searvice</a></th>
      <th><!--Plan/ Model-->GPT/Whisper/DALL·E</th>
      <th><!--Service Type-->API</th>
      <th><!--Terget-->法人</th>
      <th><!--Service Provider--><a href="https://www.microsoft.com/ja-jp/">Microsoft</a></th>
      <th><!--Model Procider--><a href="https://openai.com/about/">OpenAI</a></th>
      <th><!--Term of Use--><a href="https://www.microsoft.com/licensing/docs/customeragreement">URL</a></th>
      <th><!--Privacy Policy--><a href="https://learn.microsoft.com/en-us/legal/cognitive-services/openai/data-privacy">URL</a></th>
      <th><!--学習への利用--><a href="https://learn.microsoft.com/en-us/legal/cognitive-services/openai/data-privacy">しない</a></th>
      <th><!--データ保持--><a href="https://learn.microsoft.com/en-us/legal/cognitive-services/openai/data-privacy">30日</a>*1</th>
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
      <th><!--Service Name--><a href="https://www.microsoft.com/ja-jp/microsoft-365/microsoft-copilot">Copilot for Microsft 365</a></th>
      <th><!--Plan/ Model-->GPT-4</th>
      <th><!--Service Type-->SaaS</th>
      <th><!--Terget-->法人</th>
      <th><!--Service Provider-->同上</th>
      <th><!--Model Procider-->同上</th>
      <th><!--Term of Use--><a href="https://www.microsoft.com/ja-jp/legal/terms-of-use#:~:text=%E3%83%9E%E3%82%A4%E3%82%AF%E3%83%AD%E3%82%BD%E3%83%95%E3%83%88%E3%81%8C%E3%81%8A%E5%AE%A2%E6%A7%98%E3%81%AB%E6%8F%90%E4%BE%9B%E3%81%99%E3%82%8B%E3%82%B5%E3%83%BC%E3%83%93%E3%82%B9%E3%81%AB%E3%81%AF%E3%80%81%E4%BB%A5%E4%B8%8B%E3%81%AE%E4%BD%BF%E7%94%A8%E6%9D%A1%E4%BB%B6%20%28%E4%BB%A5%E4%B8%8B%E3%80%8C%E6%9C%AC%E4%BD%BF%E7%94%A8%E6%9D%A1%E4%BB%B6%E3%80%8D%E3%81%A8%E3%81%84%E3%81%84%E3%81%BE%E3%81%99%29%20%E3%81%8C%E9%81%A9%E7%94%A8%E3%81%95%E3%82%8C%E3%81%BE%E3%81%99%E3%80%82%20%E3%83%9E%E3%82%A4%E3%82%AF%E3%83%AD%E3%82%BD%E3%83%95%E3%83%88%E3%81%AF%E3%80%81%E3%81%8A%E5%AE%A2%E6%A7%98%E3%81%AB%E9%80%9A%E7%9F%A5%E3%81%99%E3%82%8B%E3%81%93%E3%81%A8%E3%81%AA%E3%81%8F%E3%81%84%E3%81%A4%E3%81%A7%E3%82%82%E6%9C%AC%E4%BD%BF%E7%94%A8%E6%9D%A1%E4%BB%B6%E3%82%92%E6%9B%B4%E6%96%B0%E3%81%8A%E3%82%88%E3%81%B3%E5%A4%89%E6%9B%B4%E3%81%99%E3%82%8B%E6%A8%A9%E5%88%A9%E3%82%92%E6%9C%89%E3%81%97%E3%81%BE%E3%81%99%E3%80%82%20%E6%9C%AC%E4%BD%BF%E7%94%A8%E6%9D%A1%E4%BB%B6%E3%81%AE%E6%9C%80%E6%96%B0%E7%89%88%E3%81%AF%E3%80%81%E3%83%9E%E3%82%A4%E3%82%AF%E3%83%AD%E3%82%BD%E3%83%95%E3%83%88%E3%81%AE%20Web,%E3%83%9A%E3%83%BC%E3%82%B8%E4%B8%8B%E9%83%A8%E3%81%AB%E3%81%82%E3%82%8B%20%5B%E4%BD%BF%E7%94%A8%E6%9D%A1%E4%BB%B6%5D%20%E3%83%8F%E3%82%A4%E3%83%91%E3%83%BC%E3%83%AA%E3%83%B3%E3%82%AF%E3%82%92%E3%82%AF%E3%83%AA%E3%83%83%E3%82%AF%E3%81%99%E3%82%8B%E3%81%A8%E3%81%94%E8%A6%A7%E3%81%84%E3%81%9F%E3%81%A0%E3%81%91%E3%81%BE%E3%81%99%E3%80%82%20%E3%83%9E%E3%82%A4%E3%82%AF%E3%83%AD%E3%82%BD%E3%83%95%E3%83%88%E3%81%8C%E6%9C%AC%E4%BD%BF%E7%94%A8%E6%9D%A1%E4%BB%B6%E3%82%92%E6%9B%B4%E6%96%B0%E3%81%99%E3%82%8B%E3%81%A8%E3%80%81%E3%81%93%E3%81%AE%E3%83%9A%E3%83%BC%E3%82%B8%E3%81%AE%E4%B8%8A%E9%83%A8%E3%81%AB%E3%81%82%E3%82%8B%E6%97%A5%E4%BB%98%E3%81%8C%E6%9B%B4%E6%96%B0%E3%81%95%E3%82%8C%E3%81%BE%E3%81%99%E3%80%82%20%E6%9C%AC%E4%BD%BF%E7%94%A8%E6%9D%A1%E4%BB%B6%E3%81%AE%E6%96%B0%E3%81%97%E3%81%84%E3%83%90%E3%83%BC%E3%82%B8%E3%83%A7%E3%83%B3%E3%81%8C%E6%8E%B2%E8%BC%89%E3%81%95%E3%82%8C%E3%81%9F%E5%BE%8C%E3%81%AB%20Web%20%E3%82%B5%E3%82%A4%E3%83%88%E3%82%92%E4%BD%BF%E7%94%A8%E3%81%99%E3%82%8B%E3%81%93%E3%81%A8%E3%81%AB%E3%82%88%E3%82%8A%E3%80%81%E3%81%8A%E5%AE%A2%E6%A7%98%E3%81%AF%E3%81%8B%E3%81%8B%E3%82%8B%E6%96%B0%E3%81%97%E3%81%84%E3%83%90%E3%83%BC%E3%82%B8%E3%83%A7%E3%83%B3%E3%81%AE%E4%BD%BF%E7%94%A8%E6%9D%A1%E4%BB%B6%E3%81%AB%E5%90%8C%E6%84%8F%E3%81%97%E3%81%9F%E3%82%82%E3%81%AE%E3%81%A8%E8%A6%8B%E3%81%AA%E3%81%95%E3%82%8C%E3%81%BE%E3%81%99%E3%80%82">Term1</a>　<a href="https://www.microsoft.com/licensing/terms/productoffering/Microsoft365/MCA">Term2</a></th>
      <th><!--Privacy Policy--><a href="https://privacy.microsoft.com/ja-jp/">URL</a></th>
      <th><!--学習への利用--><a href="https://learn.microsoft.com/ja-jp/copilot/microsoft-365/microsoft-365-copilot-privacy">しない</a></th>
      <th><!--データ保持-->調査中</th>
      <th><!--リージョン--><a href="https://learn.microsoft.com/ja-jp/microsoft-365/enterprise/m365-dr-workload-copilot?view=o365-worldwide">世界各地</a></th>
      <th><!--日本リージョン有無--><a href="https://learn.microsoft.com/ja-jp/microsoft-365/enterprise/m365-dr-workload-copilot?view=o365-worldwide">あり</a></th>
      <th><!--準拠法--><a href=""></a>調査中</th>
      <th><!--管轄裁判所--><a href=""></a>調査中</th>
      <th><!--ISO27001-->調査中</th>
      <th><!--SOC2-->調査中</th>
      <th><!--ISMAP-->調査中</th>
      <th><!--NOTE-->Webコンテンツプラグインや拡張については別途確認が必要</th>
     </tr>
   </tbody>
   <tbody>
     <tr>
      <th><!--Service Name--><a href="">商用データ保護 Copilot</a></th>
      <th><!--Plan/ Model-->GPT-4</th>
      <th><!--Service Type-->SaaS</th>
      <th><!--Terget-->法人</th>
      <th><!--Service Provider-->同上</th>
      <th><!--Model Procider-->同上</th>
      <th><!--Term of Use--><a href="https://www.microsoft.com/ja-jp/legal/terms-of-use#:~:text=%E3%83%9E%E3%82%A4%E3%82%AF%E3%83%AD%E3%82%BD%E3%83%95%E3%83%88%E3%81%8C%E3%81%8A%E5%AE%A2%E6%A7%98%E3%81%AB%E6%8F%90%E4%BE%9B%E3%81%99%E3%82%8B%E3%82%B5%E3%83%BC%E3%83%93%E3%82%B9%E3%81%AB%E3%81%AF%E3%80%81%E4%BB%A5%E4%B8%8B%E3%81%AE%E4%BD%BF%E7%94%A8%E6%9D%A1%E4%BB%B6%20%28%E4%BB%A5%E4%B8%8B%E3%80%8C%E6%9C%AC%E4%BD%BF%E7%94%A8%E6%9D%A1%E4%BB%B6%E3%80%8D%E3%81%A8%E3%81%84%E3%81%84%E3%81%BE%E3%81%99%29%20%E3%81%8C%E9%81%A9%E7%94%A8%E3%81%95%E3%82%8C%E3%81%BE%E3%81%99%E3%80%82%20%E3%83%9E%E3%82%A4%E3%82%AF%E3%83%AD%E3%82%BD%E3%83%95%E3%83%88%E3%81%AF%E3%80%81%E3%81%8A%E5%AE%A2%E6%A7%98%E3%81%AB%E9%80%9A%E7%9F%A5%E3%81%99%E3%82%8B%E3%81%93%E3%81%A8%E3%81%AA%E3%81%8F%E3%81%84%E3%81%A4%E3%81%A7%E3%82%82%E6%9C%AC%E4%BD%BF%E7%94%A8%E6%9D%A1%E4%BB%B6%E3%82%92%E6%9B%B4%E6%96%B0%E3%81%8A%E3%82%88%E3%81%B3%E5%A4%89%E6%9B%B4%E3%81%99%E3%82%8B%E6%A8%A9%E5%88%A9%E3%82%92%E6%9C%89%E3%81%97%E3%81%BE%E3%81%99%E3%80%82%20%E6%9C%AC%E4%BD%BF%E7%94%A8%E6%9D%A1%E4%BB%B6%E3%81%AE%E6%9C%80%E6%96%B0%E7%89%88%E3%81%AF%E3%80%81%E3%83%9E%E3%82%A4%E3%82%AF%E3%83%AD%E3%82%BD%E3%83%95%E3%83%88%E3%81%AE%20Web,%E3%83%9A%E3%83%BC%E3%82%B8%E4%B8%8B%E9%83%A8%E3%81%AB%E3%81%82%E3%82%8B%20%5B%E4%BD%BF%E7%94%A8%E6%9D%A1%E4%BB%B6%5D%20%E3%83%8F%E3%82%A4%E3%83%91%E3%83%BC%E3%83%AA%E3%83%B3%E3%82%AF%E3%82%92%E3%82%AF%E3%83%AA%E3%83%83%E3%82%AF%E3%81%99%E3%82%8B%E3%81%A8%E3%81%94%E8%A6%A7%E3%81%84%E3%81%9F%E3%81%A0%E3%81%91%E3%81%BE%E3%81%99%E3%80%82%20%E3%83%9E%E3%82%A4%E3%82%AF%E3%83%AD%E3%82%BD%E3%83%95%E3%83%88%E3%81%8C%E6%9C%AC%E4%BD%BF%E7%94%A8%E6%9D%A1%E4%BB%B6%E3%82%92%E6%9B%B4%E6%96%B0%E3%81%99%E3%82%8B%E3%81%A8%E3%80%81%E3%81%93%E3%81%AE%E3%83%9A%E3%83%BC%E3%82%B8%E3%81%AE%E4%B8%8A%E9%83%A8%E3%81%AB%E3%81%82%E3%82%8B%E6%97%A5%E4%BB%98%E3%81%8C%E6%9B%B4%E6%96%B0%E3%81%95%E3%82%8C%E3%81%BE%E3%81%99%E3%80%82%20%E6%9C%AC%E4%BD%BF%E7%94%A8%E6%9D%A1%E4%BB%B6%E3%81%AE%E6%96%B0%E3%81%97%E3%81%84%E3%83%90%E3%83%BC%E3%82%B8%E3%83%A7%E3%83%B3%E3%81%8C%E6%8E%B2%E8%BC%89%E3%81%95%E3%82%8C%E3%81%9F%E5%BE%8C%E3%81%AB%20Web%20%E3%82%B5%E3%82%A4%E3%83%88%E3%82%92%E4%BD%BF%E7%94%A8%E3%81%99%E3%82%8B%E3%81%93%E3%81%A8%E3%81%AB%E3%82%88%E3%82%8A%E3%80%81%E3%81%8A%E5%AE%A2%E6%A7%98%E3%81%AF%E3%81%8B%E3%81%8B%E3%82%8B%E6%96%B0%E3%81%97%E3%81%84%E3%83%90%E3%83%BC%E3%82%B8%E3%83%A7%E3%83%B3%E3%81%AE%E4%BD%BF%E7%94%A8%E6%9D%A1%E4%BB%B6%E3%81%AB%E5%90%8C%E6%84%8F%E3%81%97%E3%81%9F%E3%82%82%E3%81%AE%E3%81%A8%E8%A6%8B%E3%81%AA%E3%81%95%E3%82%8C%E3%81%BE%E3%81%99%E3%80%82">Term1</a>　<a href="https://www.microsoft.com/licensing/terms/productoffering/Microsoft365/MCA">Term2</a></th>
      <th><!--Privacy Policy--><a href="https://privacy.microsoft.com/ja-jp/"></a>URL</th>
      <th><!--学習への利用--><a href="https://learn.microsoft.com/ja-jp/copilot/privacy-and-protections#chat-history-and-reporting">しない</a></th>
      <th><!--データ保持--><a href="https://learn.microsoft.com/ja-jp/copilot/privacy-and-protections#chat-history-and-reporting">しない</a></th>
      <th><!--リージョン--><a href="https://learn.microsoft.com/ja-jp/copilot/privacy-and-protections#microsoft-as-the-data-controller">グローバルデータセンター</a></th>
      <th><!--日本リージョン有無--><a href="https://learn.microsoft.com/ja-jp/copilot/privacy-and-protections#microsoft-as-the-data-controller">不明</a></th>
      <th><!--準拠法--><a href=""></a>日本法</th>
      <th><!--管轄裁判所--><a href=""></a>東京地方裁判所</th></th>
      <th><!--ISO27001-->調査中</th>
      <th><!--SOC2-->調査中</th>
      <th><!--ISMAP-->NO</th>
      <th><!--NOTE-->旧：Bing Search Enterprise </th>
     </tr>
   </tbody>
   <tbody>
     <tr>
      <th><!--Service Name-->Microsoft Copilot</th>
      <th><!--Plan/ Model-->Free Plan</th>
      <th><!--Service Type-->SaaS</th>
      <th><!--Terget-->個人</th>
      <th><!--Service Provider-->同上</th>
      <th><!--Model Procider-->同上</th>
      <th><!--Term of Use-->調査中</th>
      <th><!--Privacy Policy-->調査中</th>
      <th><!--学習への利用-->調査中</th>
      <th><!--データ保持-->調査中</th>
      <th><!--リージョン-->調査中</th>
      <th><!--日本リージョン有無-->調査中</th>
      <th><!--準拠法--><a href="https://www.microsoft.com/ja-jp/servicesagreement/">日本法</a></th>
      <th><!--管轄裁判所--><a href="https://www.microsoft.com/ja-jp/servicesagreement/">東京地方裁判所</a></th></th>
      <th><!--ISO27001-->調査中</th>
      <th><!--SOC2-->調査中</th>
      <th><!--ISMAP-->NO</th>
      <th><!--NOTE--></th>
     </tr>
   </tbody>
   <tbody>
     <tr>
      <th><!--Service Name--><a href="https://docs.github.com/ja/copilot">Github Copilot</a></th>
      <th><!--Plan/ Model-->Individual Plan</th>
      <th><!--Service Type-->SaaS</th>
      <th><!--Terget-->個人</th>
      <th><!--Service Provider--><a href="https://github.co.jp/about.html">GitHub, Inc.</a></th>
      <th><!--Model Procider--><a href="https://github.com/features/copilot"></a>GitHub,OpenAI,Microsoft</th>
      <th><!--Term of Use--><a href="https://github.com/customer-terms/">URL</a></th>
      <th><!--Privacy Policy--><a href="https://docs.github.com/en/site-policy/privacy-policies">URL</a></th>
      <th><!--学習への利用--><a href="https://github.com/features/copilot#pricing">する</a></th>
      <th><!--データ保持--><a href="https://github.com/features/copilot">スレッド履歴を使用して応答するために一部データを一定期間保持</a></th>
      <th><!--リージョン--><!--Privacy Policy--><a href=""></a>調査中</th>
      <th><!--日本リージョン有無--><!--Privacy Policy--><a href=“”></a>調査中</th>
      <th><!--準拠法--><a href="https://assets.ctfassets.net/8aevphvgewt8/1LvHh4fsBKJ14bXfVfD9VW/78731fab3753750aa90dd1cad7dddfab/GitHub.General.Terms_20220121_locked.pdf"></a>カリフォルニア州法および米国連邦法</th>
      <th><!--管轄裁判所--><a href="https://assets.ctfassets.net/8aevphvgewt8/1LvHh4fsBKJ14bXfVfD9VW/78731fab3753750aa90dd1cad7dddfab/GitHub.General.Terms_20220121_locked.pdf">カリフォルニア州北部地区連邦地方裁判所または州裁判所</a></th>
      <th><!--ISO27001--><a href="https://resources.github.com/copilot-trust-center/">NO</a></th>
      <th><!--SOC2--><a href="https://resources.github.com/copilot-trust-center/">NO</a></th>
      <th><!--ISMAP-->NO</th>
      <th><!--NOTE--></th>
     </tr>
   </tbody>
   <tbody>
     <tr>
      <th><!--Service Name--><a href="https://docs.github.com/ja/copilot">Github Copilot</a></th>
      <th><!--Plan/ Model-->Business Plan</th>
      <th><!--Service Type-->SaaS</th>
      <th><!--Terget-->法人</th>
      <th><!--Service Provider--><a href="https://github.co.jp/about.html">GitHub, Inc.</a></th>
      <th><!--Model Procider--><a href="https://github.com/features/copilot"></a>GitHub,OpenAI,Microsoft</th>
      <th><!--Term of Use--><a href="https://github.com/customer-terms/">URL</a></th>
      <th><!--Privacy Policy--><a href="https://docs.github.com/en/site-policy/privacy-policies">URL</a></th>
      <th><!--学習への利用--><a href="https://github.com/features/copilot#pricing">しない</a></th>
      <th><!--データ保持-->同上</th>
      <th><!--リージョン--><!--Privacy Policy--><a href=“”></a>調査中</th>
      <th><!--日本リージョン有無--><!--Privacy Policy--><a href=“”></a>調査中</th>
      <th><!--準拠法--><a href="https://assets.ctfassets.net/8aevphvgewt8/1LvHh4fsBKJ14bXfVfD9VW/78731fab3753750aa90dd1cad7dddfab/GitHub.General.Terms_20220121_locked.pdf"></a>カリフォルニア州法および米国連邦法</th>
      <th><!--管轄裁判所--><a href="https://assets.ctfassets.net/8aevphvgewt8/1LvHh4fsBKJ14bXfVfD9VW/78731fab3753750aa90dd1cad7dddfab/GitHub.General.Terms_20220121_locked.pdf">カリフォルニア州北部地区連邦地方裁判所または州裁判所</a></th>
      <th><!--ISO27001--><a href="https://resources.github.com/copilot-trust-center/">YES</a></th>
      <th><!--SOC2--><a href="https://resources.github.com/copilot-trust-center/">Type1</a></th>
      <th><!--ISMAP-->NO</th>
      <th><!--NOTE--></th>
     </tr>
   </tbody>
   <tbody>
     <tr>
      <th><!--Service Name--><a href="https://docs.github.com/ja/copilot">Github Copilot</a></th>
      <th><!--Plan/ Model-->Enterprise Plan</th>
      <th><!--Service Type-->SaaS</th>
      <th><!--Terget-->法人</th>
      <th><!--Service Provider--><a href="https://github.co.jp/about.html">GitHub, Inc.</a></th>
      <th><!--Model Procider--><a href="https://github.com/features/copilot"></a>GitHub,OpenAI,Microsoft</th>
      <th><!--Term of Use--><a href="https://github.com/customer-terms/">URL</a></th>
      <th><!--Privacy Policy--><a href="https://docs.github.com/en/site-policy/privacy-policies">URL</a></th>
      <th><!--学習への利用--><a href="https://github.com/features/copilot#pricing">しない</a></th>
      <th><!--データ保持-->同上</th>
      <th><!--リージョン--><!--Privacy Policy--><a href=""></a>調査中</th>
      <th><!--日本リージョン有無--><!--Privacy Policy--><a href=""></a>調査中</th>
      <th><!--準拠法--><a href="https://assets.ctfassets.net/8aevphvgewt8/1LvHh4fsBKJ14bXfVfD9VW/78731fab3753750aa90dd1cad7dddfab/GitHub.General.Terms_20220121_locked.pdf"></a>カリフォルニア州法および米国連邦法</th>
      <th><!--管轄裁判所--><a href="https://assets.ctfassets.net/8aevphvgewt8/1LvHh4fsBKJ14bXfVfD9VW/78731fab3753750aa90dd1cad7dddfab/GitHub.General.Terms_20220121_locked.pdf">カリフォルニア州北部地区連邦地方裁判所または州裁判所</a></th>
      <th><!--ISO27001--><a href="https://resources.github.com/copilot-trust-center/">YES</a></th>
      <th><!--SOC2-->NO</th>
      <th><!--ISMAP-->NO</th>
      <th><!--NOTE--></th>
     </tr>
   </tbody>
   <tbody>
     <tr>
      <th><!--Service Name--><a href="https://gemini.google.com/">Google Gemini</a></th>
      <th><!--Plan/ Model-->Free</th>
      <th><!--Service Type-->SaaS</th>
      <th><!--Terget-->個人</th>
      <th><!--Service Provider--><a href=""></a>Google</th>
      <th><!--Model Procider--><a href=""></a>Google</th>
      <th><!--Term of Use--><a href="https://workspace.google.com/terms/premier_terms/?sjid=15432536244888463008-AP">URL</a></th>
      <th><!--Privacy Policy--><a href="https://support.google.com/gemini/answer/13594961?hl=en&visit_id=638445236399578564-3759371208&rd=1#collected_data">URL</a></th>
      <th><!--学習への利用--><a href="https://support.google.com/gemini/answer/13594961?hl=en&visit_id=638445236399578564-3759371208&rd=1#collected_data">される</a></th>
      <th><!--データ保持--><a href="https://support.google.com/gemini/answer/13594961?hl=en&visit_id=638445236399578564-3759371208&rd=1#collected_data&zippy=%2Cwho-has-access-to-my-gemini-apps-conversations"></a>0日-36ヶ月</th>
      <th><!--リージョン--><a href=""></a>調査中</th>
      <th><!--日本リージョン有無--><a href=""></a>調査中</th>
      <th><!--準拠法--><a href="https://www.ismap.go.jp/csm?id=cloud_service_list_detail&sys_id=18f05f3cc3d7a11045724a3599013176">日本国法</a></th>
      <th><!--管轄裁判所--><a href="https://www.ismap.go.jp/csm?id=cloud_service_list_detail&sys_id=18f05f3cc3d7a11045724a3599013176">東京地方裁判所</a></th>
      <th><!--ISO27001--><a href=""></a>調査中</th>
      <th><!--SOC2--><a href=""></a>調査中</th>
      <th><!--ISMAP--><a href=""></a>調査中</th>
      <th><!--NOTE--></th>      
     </tr>
   </tbody>
  　　<tbody>
     <tr>
      <th><!--Service Name-->Google Gemini</th>
      <th><!--Plan/ Model--><a href=“https://gemini.google.com/advanced”>Advanced Plan</a></th>
      <th><!--Service Type-->SaaS</th>
      <th><!--Terget-->個人</th>
      <th><!--Service Provider--><a href=“”></a>Google</th>
      <th><!--Model Procider--><a href=“”></a>Google</th>
      <th><!--Term of Use--><a href=“https://workspace.google.com/terms/premier_terms/?sjid=15432536244888463008-AP”>URL</a></th>
      <th><!--Privacy Policy--><a href=“https://support.google.com/gemini/answer/13594961?hl=en&visit_id=638445236399578564-3759371208&rd=1#collected_data”>URL</a></th>
      <th><!--学習への利用--><a href=“https://support.google.com/gemini/answer/13594961?hl=en&visit_id=638445236399578564-3759371208&rd=1#collected_data”>される</a></th>
      <th><!--データ保持--><a href=“https://support.google.com/gemini/answer/13594961?hl=en&visit_id=638445236399578564-3759371208&rd=1#collected_data&zippy=%2Cwho-has-access-to-my-gemini-apps-conversations”></a>0日-36ヶ月</th>
      <th><!--リージョン--><a href=“https://www.ismap.go.jp/csm?id=cloud_service_list_detail&sys_id=18f05f3cc3d7a11045724a3599013176”>世界各国</a></th>
      <th><!--日本リージョン有無--><a href=“https://www.ismap.go.jp/csm?id=cloud_service_list_detail&sys_id=18f05f3cc3d7a11045724a3599013176”>存在するが選択不可</a></th>
      <th><!--準拠法--><a href=“https://www.ismap.go.jp/csm?id=cloud_service_list_detail&sys_id=18f05f3cc3d7a11045724a3599013176”>日本国法</a></th>
      <th><!--管轄裁判所--><a href=“https://www.ismap.go.jp/csm?id=cloud_service_list_detail&sys_id=18f05f3cc3d7a11045724a3599013176”>東京地方裁判所</a></th>
      <th><!--ISO27001--><a href=“”></a>調査中</th>
      <th><!--SOC2--><a href=“”></a>調査中</th>
      <th><!--ISMAP--><a href=“”></a>調査中</th>
      <th><!--NOTE--></th>      
     </tr>
   </tbody>
   <tbody>
     <tr>
      <th><!--Service Name-->Gemini for Google Workspace</th>
      <th><!--Plan/ Model--><a href=“https://workspace.google.com/intl/ja/solutions/ai/”></a>Gemini Business</th>
      <th><!--Service Type-->SaaS</th>
      <th><!--Terget-->法人</th>
      <th><!--Service Provider--><a href=“”></a>Google</th>
      <th><!--Model Procider--><a href=“”></a>Google</th>
      <th><!--Term of Use--><a href=“https://workspace.google.com/terms/premier_terms/?sjid=15432536244888463008-AP”>URL</a></th>
      <th><!--Privacy Policy--><a href=“https://workspace.google.com/blog/ja/identity-and-security/protecting-your-data-era-generative-ai?hl=ja”>URL</a></th>
      <th><!--学習への利用--><a href=“https://workspace.google.com/blog/ja/identity-and-security/protecting-your-data-era-generative-ai?hl=ja”></a>しない</th>
      <th><!--データ保持--><a href=“”></a>調査中</th>
      <th><!--リージョン--><a href=“https://www.ismap.go.jp/csm?id=cloud_service_list_detail&sys_id=18f05f3cc3d7a11045724a3599013176”>世界各国</a></th>
      <th><!--日本リージョン有無--><a href=“https://www.ismap.go.jp/csm?id=cloud_service_list_detail&sys_id=18f05f3cc3d7a11045724a3599013176”>存在するが選択不可</a></th>
      <th><!--準拠法--><a href=“https://www.ismap.go.jp/csm?id=cloud_service_list_detail&sys_id=18f05f3cc3d7a11045724a3599013176”>日本国法</a></th>
      <th><!--管轄裁判所--><a href=“https://www.ismap.go.jp/csm?id=cloud_service_list_detail&sys_id=18f05f3cc3d7a11045724a3599013176”>東京地方裁判所</a></th>
      <th><!--ISO27001--><a href=“”></a>調査中</th>
      <th><!--SOC2--><a href=“”></a>調査中</th>
      <th><!--ISMAP--><a href=“”></a>調査中</th>
      <th><!--NOTE--></th>
     </tr>
   </tbody>
   <tbody>
     <tr>
      <th><!--Service Name-->Gemini for Google Workspace</th>
      <th><!--Plan/ Model--><a href=“https://workspace.google.com/intl/ja/solutions/ai/”></a>Gemini Enterprise</th>
      <th><!--Service Type-->SaaS</th>
      <th><!--Terget-->法人</th>
      <th><!--Service Provider--><a href=“”></a>Google</th>
      <th><!--Model Procider--><a href=“”></a>Google</th>
      <th><!--Term of Use--><a href=“https://workspace.google.com/terms/premier_terms/?sjid=15432536244888463008-AP”>URL</a></th>
      <th><!--Privacy Policy--><a href=“https://workspace.google.com/blog/ja/identity-and-security/protecting-your-data-era-generative-ai?hl=ja”>URL</a></th>
      <th><!--学習への利用--><a href=“https://workspace.google.com/blog/ja/identity-and-security/protecting-your-data-era-generative-ai?hl=ja”></a>しない</th>
      <th><!--データ保持--><a href=“”></a>調査中</th>
      <th><!--リージョン--><a href=“https://www.ismap.go.jp/csm?id=cloud_service_list_detail&sys_id=18f05f3cc3d7a11045724a3599013176”>世界各国</a></th>
      <th><!--日本リージョン有無--><a href=“https://www.ismap.go.jp/csm?id=cloud_service_list_detail&sys_id=18f05f3cc3d7a11045724a3599013176”>存在するが選択不可</a></th>
      <th><!--準拠法--><a href=“https://www.ismap.go.jp/csm?id=cloud_service_list_detail&sys_id=18f05f3cc3d7a11045724a3599013176”>日本国法</a></th>
      <th><!--管轄裁判所--><a href=“https://www.ismap.go.jp/csm?id=cloud_service_list_detail&sys_id=18f05f3cc3d7a11045724a3599013176”>東京地方裁判所</a></th>
      <th><!--ISO27001--><a href=“”></a>調査中</th>
      <th><!--SOC2--><a href=“”></a>調査中</th>
      <th><!--ISMAP--><a href=“”></a>調査中</th>
      <th><!--NOTE--></th>
     </tr>
   </tbody>
   <tbody>
     <tr>
      <th><!--Service Name-->Google Cloud Vertex AI</th>
      <th><!--Plan/ Model-->Gemini Free</th>
      <th><!--Service Type-->SaaS</th>
      <th><!--Terget-->法人</th>
      <th><!--Service Provider--><a href=“”></a>Google</th>
      <th><!--Model Procider--><a href=“”></a>Google</th>
      <th><!--Term of Use--><a href=“https://ai.google.dev/gemini-api/terms”>URL</a></th>
      <th><!--Privacy Policy--><a href=“https://ai.google.dev/gemini-api/terms”>URL</a></th>
      <th><!--学習への利用--><a href=“https://ai.google.dev/gemini-api/terms”>する</a></th>
      <th><!--データ保持--><!--Privacy Policy--><a href=“”></a>調査中</th>
      <th><!--リージョン--><a href=“”></a>調査中</th>
      <th><!--日本リージョン有無--><a href=“”></a>調査中</th>
      <th><!--準拠法--><a href=“”></a>調査中</th>
      <th><!--管轄裁判所--><a href=“”></a>調査中</th>
      <th><!--ISO27001--><a href=“”></a>調査中</th>
      <th><!--SOC2--><a href=“”></a>調査中</th>
      <th><!--ISMAP--><a href=“”></a>調査中</th>
      <th><!--NOTE--></th>
     </tr>
   </tbody>
   <tbody>
     <tr>
      <th><!--Service Name-->Google Cloud Vertex AI</th>
      <th><!--Plan/ Model-->Gemini Pay-as-you-go</th>
      <th><!--Service Type-->SaaS</th>
      <th><!--Terget-->法人</th>
      <th><!--Service Provider--><a href=“”></a>Google</th>
      <th><!--Model Procider--><a href=“”></a>Google</th>
      <th><!--Term of Use--><a href=“https://ai.google.dev/gemini-api/terms”>URL</a></th>
      <th><!--Privacy Policy--><a href=“https://ai.google.dev/gemini-api/terms”>URL</a></th>
      <th><!--学習への利用--><a href=“https://ai.google.dev/gemini-api/terms”>しない</a></th>
      <th><!--データ保持--><a href=“”></a>調査中</th>
      <th><!--リージョン--><a href=“”></a>調査中</th>
      <th><!--日本リージョン有無--><a href=“”></a>調査中</th>
      <th><!--準拠法--><a href=“”></a>調査中</th>
      <th><!--管轄裁判所--><a href=“”></a>調査中</th>
      <th><!--ISO27001--><a href=“”></a>調査中</th>
      <th><!--SOC2--><a href=“”></a>調査中</th>
      <th><!--ISMAP--><a href=“”></a>調査中</th>
      <th><!--NOTE--></th>
     </tr>
   </tbody>
   <tbody>
     <tr>
      <th><!--Service Name-->Google Cloud Vertex AI</th>
      <th><!--Plan/ Model-->Claude Series</th>
      <th><!--Service Type-->SaaS</th>
      <th><!--Terget-->法人</th>
      <th><!--Service Provider--><a href=“”></a>Google</th>
      <th><!--Model Procider--><a href=“”></a>Anthropic</th>
      <th><!--Term of Use--><a href=“”></a>調査中</th>
      <th><!--Privacy Policy--><a href=“”></a>調査中</th>
      <th><!--学習への利用--><a href=“”></a>調査中</th>
      <th><!--データ保持--><a href=“”></a>調査中</th>
      <th><!--リージョン--><a href=“”></a>調査中</th>
      <th><!--日本リージョン有無--><a href=“”></a>調査中</th>
      <th><!--準拠法--><a href=“”></a>調査中</th>
      <th><!--管轄裁判所--><a href=“”></a>調査中</th>
      <th><!--ISO27001--><a href=“”></a>調査中</th>
      <th><!--SOC2--><a href=“”></a>調査中</th>
      <th><!--ISMAP--><a href=“”></a>調査中</th>
      <th><!--NOTE--></th>
     </tr>
   </tbody>
   <tbody>
     <tr>
      <th><!--Service Name-->Claude</th>
      <th><!--Plan/ Model-->Free Plan</th>
      <th><!--Service Type-->SaaS</th>
      <th><!--Terget-->個人</th>
      <th><!--Service Provider--><a href=“”></a>Anthropic</th>
      <th><!--Model Procider--><a href=“”></a>Anthropic</th>
      <th><!--Term of Use--><a href=“”></a>調査中</th>
      <th><!--Privacy Policy--><a href=“”></a>調査中</th>
      <th><!--学習への利用--><a href=“”></a>調査中</th>
      <th><!--データ保持--><a href=“”></a>調査中</th>
      <th><!--リージョン--><a href=“”></a>調査中</th>
      <th><!--日本リージョン有無--><a href=“”></a>調査中</th>
      <th><!--準拠法--><a href=“”></a>調査中</th>
      <th><!--管轄裁判所--><a href=“”></a>調査中</th>
      <th><!--ISO27001--><a href=“”></a>調査中</th>
      <th><!--SOC2--><a href=“”></a>調査中</th>
      <th><!--ISMAP--><a href=“”></a>調査中</th>
      <th><!--NOTE--></th>
     </tr>
   </tbody>
   <tbody>
     <tr>
      <th><!--Service Name-->Claude</th>
      <th><!--Plan/ Model-->Pro Plan</th>
      <th><!--Service Type-->SaaS</th>
      <th><!--Terget-->個人</th>
      <th><!--Service Provider--><a href=“”></a>Anthropic</th>
      <th><!--Model Procider--><a href=“”></a>Anthropic</th>
      <th><!--Term of Use--><a href=“”></a>調査中</th>
      <th><!--Privacy Policy--><a href=“”></a>調査中</th>
      <th><!--学習への利用--><a href=“”></a>調査中</th>
      <th><!--データ保持--><a href=“”></a>調査中</th>
      <th><!--リージョン--><a href=“”></a>調査中</th>
      <th><!--日本リージョン有無--><a href=“”></a>調査中</th>
      <th><!--準拠法--><a href=“”></a>調査中</th>
      <th><!--管轄裁判所--><a href=“”></a>調査中</th>
      <th><!--ISO27001--><a href=“”></a>調査中</th>
      <th><!--SOC2--><a href=“”></a>調査中</th>
      <th><!--ISMAP--><a href=“”></a>調査中</th>
      <th><!--NOTE--></th>
     </tr>
   </tbody>
   <tbody>
     <tr>
      <th><!--Service Name-->Claude</th>
      <th><!--Plan/ Model-->Team Plan</th>
      <th><!--Service Type-->SaaS</th>
      <th><!--Terget-->法人</th>
      <th><!--Service Provider--><a href=“”></a>Anthropic</th>
      <th><!--Model Procider--><a href=“”></a>Anthropic</th>
      <th><!--Term of Use--><a href=“”></a>調査中</th>
      <th><!--Privacy Policy--><a href=“”></a>調査中</th>
      <th><!--学習への利用--><a href=“”></a>調査中</th>
      <th><!--データ保持--><a href=“”></a>調査中</th>
      <th><!--リージョン--><a href=“”></a>調査中</th>
      <th><!--日本リージョン有無--><a href=“”></a>調査中</th>
      <th><!--準拠法--><a href=“”></a>調査中</th>
      <th><!--管轄裁判所--><a href=“”></a>調査中</th>
      <th><!--ISO27001--><a href=“”></a>調査中</th>
      <th><!--SOC2--><a href=“”></a>調査中</th>
      <th><!--ISMAP--><a href=“”></a>調査中</th>
      <th><!--NOTE--></th>
     </tr>
   </tbody>
   <tbody>
     <tr>
      <th><!--Service Name-->Claude API</th>
      <th><!--Plan/ Model-->Haiku,Sonnet,Opus</th>
      <th><!--Service Type-->API</th>
      <th><!--Terget-->個人/法人</th>
      <th><!--Service Provider--><a href=“”></a>Anthropic</th>
      <th><!--Model Procider--><a href=“”></a>Anthropic</th>
      <th><!--Term of Use--><a href=“”></a>調査中</th>
      <th><!--Privacy Policy--><a href=“”></a>調査中</th>
      <th><!--学習への利用--><a href=“”>しない</a></th>
      <th><!--データ保持--><a href=“”></a>調査中</th>
      <th><!--リージョン--><a href=“”></a>調査中</th>
      <th><!--日本リージョン有無--><a href=“”></a>調査中</th>
      <th><!--準拠法--><a href=“”></a>調査中</th>
      <th><!--管轄裁判所--><a href=“”></a>調査中</th>
      <th><!--ISO27001--><a href=“”></a>調査中</th>
      <th><!--SOC2--><a href=“”></a>調査中</th>
      <th><!--ISMAP--><a href=“”></a>調査中</th>
      <th><!--NOTE--></th>
     </tr>
   </tbody>
   <tbody>
     <tr>
      <th><!--Service Name-->Amazon Bedrock</th>
      <th><!--Plan/ Model-->Claude Series</th>
      <th><!--Service Type-->API</th>
      <th><!--Terget-->法人</th>
      <th><!--Service Provider--><a href=“”></a>AWS</th>
      <th><!--Model Procider--><a href=“”></a>Anthoropic</th>
      <th><!--Term of Use--><a href=“”></a>調査中</th>
      <th><!--Privacy Policy--><a href=“”></a>調査中</th>
      <th><!--学習への利用--><a href=“https://aws.amazon.com/jp/bedrock/faqs/”>しない</a></th>
      <th><!--データ保持--><a href=“”></a>調査中</th>
      <th><!--リージョン--><a href=“”></a>調査中</th>
      <th><!--日本リージョン有無--><a href=“”></a>調査中</th>
      <th><!--準拠法--><a href=“”></a>調査中</th>
      <th><!--管轄裁判所--><a href=“”></a>調査中</th>
      <th><!--ISO27001--><a href=“https://aws.amazon.com/jp/bedrock/faqs/”>YES</a></th>
      <th><!--SOC2--><a href=“https://aws.amazon.com/jp/bedrock/faqs/”>YES</a></th>
      <th><!--ISMAP--><a href="https://www.ismap.go.jp/csm?id=cloud_service_list_detail&sys_id=c8e0b6cc9361c610a734bb497bba104f">Yes</a></th>
      <th><!--NOTE--></th>
     </tr>
   </tbody>
   <tbody>
     <tr>
      <th><!--Service Name-->Amazon Bedrock</th>
      <th><!--Plan/ Model-->Taitan Series</th>
      <th><!--Service Type-->API</th>
      <th><!--Terget-->法人</th>
      <th><!--Service Provider--><a href=“”></a>AWS</th>
      <th><!--Model Procider--><a href=“”></a>AWS</th>
      <th><!--Term of Use--><a href=“”></a>調査中</th>
      <th><!--Privacy Policy--><a href=“”></a>調査中</th>
      <th><!--学習への利用--><a href=“https://aws.amazon.com/jp/bedrock/faqs/”>しない</a></th>
      <th><!--データ保持--><a href=“”></a>調査中</th>
      <th><!--リージョン--><a href=“”></a>調査中</th>
      <th><!--日本リージョン有無--><a href=“”></a>調査中</th>
      <th><!--準拠法--><a href=“”></a>調査中</th>
      <th><!--管轄裁判所--><a href=“”></a>調査中</th>
      <th><!--ISO27001--><a href=“https://aws.amazon.com/jp/bedrock/faqs/”>YES</a></th>
      <th><!--SOC2--><a href=“https://aws.amazon.com/jp/bedrock/faqs/”>YES</a></th>
      <th><!--ISMAP--><a href="https://www.ismap.go.jp/csm?id=cloud_service_list_detail&sys_id=c8e0b6cc9361c610a734bb497bba104f">Yes</a></th>
      <th><!--NOTE--></th>
     </tr>
   </tbody>
   <tbody>
     <tr>
      <th><!--Service Name--><a href=“https://www.oracle.com/jp/artificial-intelligence/generative-ai/generative-ai-service/”>Oracle Cloud Infrastructure（OCI） Generative AI</a></th>
      <th><!--Plan/ Model-->Cohere</th>
      <th><!--Service Type-->API</th>
      <th><!--Terget-->法人</th>
      <th><!--Service Provider-->Oracle</th>
      <th><!--Model Procider-->Cohere</th>
      <th><!--Term of Use-->調査中</th>
      <th><!--Privacy Policy-->調査中</th>
      <th><!--学習への利用-->調査中</th>
      <th><!--データ保持-->調査中</th>
      <th><!--リージョン-->調査中</th>
      <th><!--日本リージョン有無-->調査中</th>
      <th><!--準拠法-->調査中</th>
      <th><!--管轄裁判所-->調査中</th>
      <th><!--ISO27001-->調査中</th>
      <th><!--SOC2-->調査中</th>
      <th><!--ISMAP-->調査中</th>
      <th><!--NOTE--></th>
     </tr>
   </tbody>
   <tbody>
     <tr>
      <th><!--Service Name-->Notion</th>
      <th><!--Plan/ Model-->AI add-on</th>
      <th><!--Service Type-->SaaS</th>
      <th><!--Terget-->法人</th>
      <th><!--Service Provider-->調査中</th>
      <th><!--Model Procider-->調査中</th>
      <th><!--Term of Use-->調査中</th>
      <th><!--Privacy Policy-->調査中</th>
      <th><!--学習への利用-->調査中</th>
      <th><!--データ保持-->調査中</th>
      <th><!--リージョン-->調査中</th>
      <th><!--日本リージョン有無-->調査中</th>
      <th><!--準拠法-->調査中</th>
      <th><!--管轄裁判所-->調査中</th>
      <th><!--ISO27001-->調査中</th>
      <th><!--SOC2-->調査中</th>
      <th><!--ISMAP-->調査中</th>
      <th><!--NOTE--></th>
     </tr>
   </tbody>
   <tbody>
     <tr>
      <th><!--Service Name-->Box AI</th>
      <th><!--Plan/ Model-->Enterprise Plus</th>
      <th><!--Service Type-->SaaS</th>
      <th><!--Terget-->法人</th>
      <th><!--Service Provider-->調査中</th>
      <th><!--Model Procider-->調査中</th>
      <th><!--Term of Use-->調査中</th>
      <th><!--Privacy Policy-->調査中</th>
      <th><!--学習への利用-->調査中</th>
      <th><!--データ保持-->調査中</th>
      <th><!--リージョン-->調査中</th>
      <th><!--日本リージョン有無-->調査中</th>
      <th><!--準拠法-->調査中</th>
      <th><!--管轄裁判所-->調査中</th>
      <th><!--ISO27001-->調査中</th>
      <th><!--SOC2-->調査中</th>
      <th><!--ISMAP-->調査中</th>
      <th><!--NOTE--></th>
     </tr>
   </tbody>
   <tbody>
     <tr>
      <th><!--Service Name-->Slack AI</th>
      <th><!--Plan/ Model-->モデル非公開</th>
      <th><!--Service Type-->SaaS</th>
      <th><!--Terget-->法人</th>
      <th><!--Service Provider-->調査中</th>
      <th><!--Model Procider-->調査中</th>
      <th><!--Term of Use-->調査中</th>
      <th><!--Privacy Policy-->調査中</th>
      <th><!--学習への利用-->調査中</th>
      <th><!--データ保持-->調査中</th>
      <th><!--リージョン-->調査中</th>
      <th><!--日本リージョン有無-->調査中</th>
      <th><!--準拠法-->調査中</th>
      <th><!--管轄裁判所-->調査中</th>
      <th><!--ISO27001-->調査中</th>
      <th><!--SOC2-->調査中</th>
      <th><!--ISMAP-->調査中</th>
      <th><!--NOTE--></th>  
     </tr>
   </tbody>
 </table>
</div>

*1. <a href="https://learn.microsoft.com/en-us/azure/ai-services/openai/concepts/abuse-monitoring#:~:text=Azure%20OpenAI%20Limited%20Access%20Review%3A%20Modified%20Abuse%20Monitoring">オプトアウト申請</a>が承認されれば、データは保持されない。
