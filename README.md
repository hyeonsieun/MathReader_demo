# MathReader: Text-to-Speech for Mathematical Documents

## Abstract
TTS (Text-to-Speech) document reader from Microsoft, Adobe, Apple, and OpenAI have been serviced worldwide. They provide relatively good TTS results for general plain text, but sometimes skip contents or provide unsatisfactory results for mathematical expressions. This is because most modern academic papers are written in LaTeX, and when LaTeX formulas are compiled, they are rendered as distinctive text forms within the document. However, traditional TTS document readers output only the text as it is recognized, without considering the mathematical meaning of the formulas. To address this issue, we propose MathReader, which effectively integrates OCR, a fine-tuned T5 model, and TTS. MathReader demonstrated a lower Word Error Rate (WER) than existing TTS document readers, such as Microsoft Edge and Adobe Acrobat, when processing documents containing mathematical formulas. MathReader reduced the WER from 0.510 to 0.281 compared to Microsoft Edge, and from 0.617 to 0.281 compared to Adobe Acrobat. This will significantly contribute to alleviating the inconvenience faced by users who want to listen to documents, especially those who are visually impaired.

### This page is for submission to ICASSP 2025.

Here, you can listen to an example voice from each TTS document reader.

---

## Example results from MathReader

<table border="1">
  <colgroup>
    <col style="width:800px;">
    <col style="width:100px;">
    <col style="width:100px;">
  </colgroup>
  <tr>
    <td align="center"><b>Document 1</b></td>
    <td align="center"><b>TTS document reader</b></td>
    <td align="center"><b>Audio Result</b></td>
  </tr>
  <tr>
    <td rowspan="4"><img src="image/3.png" alt="document"></td>
    <td><b>MathReader</b></td>
    <td><a href="https://soundcloud.com/8j9shhld5qmv/8002e42f-8018-43d9-9897-1d962b4e54ef?in=8j9shhld5qmv/sets/mathreader&si=c0e3ed0db3c5486d88f0614cea5f3a00&utm_source=clipboard&utm_medium=text&utm_campaign=social_sharing" target="_blank">Click Here</a></td>
  </tr>
  <tr>
    <td><b>Microsoft Edge</b></td>
    <td><a href="https://soundcloud.com/8j9shhld5qmv/4d4d1afc-6fb6-4ad1-8605-8021038836a9?in=8j9shhld5qmv/sets/microsoft-edge&si=d9185b792eb944c98c01987f533f672a&utm_source=clipboard&utm_medium=text&utm_campaign=social_sharing" target="_blank">Click Here</a></td>
  </tr>
  <tr>
    <td><b>Adobe Acrobat</b></td>
    <td><a href="https://soundcloud.com/8j9shhld5qmv/d6151c42-071a-449e-a62a-b133558ee83d?in=8j9shhld5qmv/sets/adobe-acrobat&si=94b495a468eb4d2b899e5a46a87dba44&utm_source=clipboard&utm_medium=text&utm_campaign=social_sharing" target="_blank">Click Here</a></td>
  </tr>
  <tr>
    <td><b>MathReader without T5     (Ablation Study)</b></td>
    <td><a href="https://soundcloud.com/8j9shhld5qmv/68de0b0b-ed57-4ff0-81da-2e8f7a2db67e?in=8j9shhld5qmv/sets/mathreader-without-t5-ablation-study&si=80f2be00ceb74fdd8cd0058bd68b8dc1&utm_source=clipboard&utm_medium=text&utm_campaign=social_sharing" target="_blank">Click Here</a></td>
  </tr>
</table>

<table border="1">
  <colgroup>
    <col style="width:800px;">
    <col style="width:100px;">
    <col style="width:100px;">
  </colgroup>
  <tr>
    <td align="center"><b>Document 2</b></td>
    <td align="center"><b>TTS document reader</b></td>
    <td align="center"><b>Audio Result</b></td>
  </tr>
  <tr>
    <td rowspan="4"><img src="image/4.png" alt="document"></td>
    <td><b>MathReader</b></td>
    <td><a href="https://soundcloud.com/8j9shhld5qmv/2a7135c2-da8c-4a59-abf3-898777244fc3?in=8j9shhld5qmv/sets/mathreader&si=4989e41beed04fc093664a509673d977&utm_source=clipboard&utm_medium=text&utm_campaign=social_sharing" target="_blank">Click Here</a></td>
  </tr>
  <tr>
    <td><b>Microsoft Edge</b></td>
    <td><a href="https://soundcloud.com/8j9shhld5qmv/e9b7d5ea-38e6-4aad-80d9-8a9fa6663556?in=8j9shhld5qmv/sets/microsoft-edge&si=2a99828299e247bba992d1af04efa2dd&utm_source=clipboard&utm_medium=text&utm_campaign=social_sharing" target="_blank">Click Here</a></td>
  </tr>
  <tr>
    <td><b>Adobe Acrobat</b></td>
    <td><a href="https://soundcloud.com/8j9shhld5qmv/1b5a8dd1-1d82-4d2f-ab4e-7a688c0402aa?in=8j9shhld5qmv/sets/adobe-acrobat&si=847f01450e3c44bbaaff9916dd4c21e8&utm_source=clipboard&utm_medium=text&utm_campaign=social_sharing" target="_blank">Click Here</a></td>
  </tr>
  <tr>
    <td><b>MathReader without T5     (Ablation Study)</b></td>
    <td><a href="https://soundcloud.com/8j9shhld5qmv/824b0ab4-e47f-4ad4-ab0e-ba70decc69ef?in=8j9shhld5qmv/sets/mathreader-without-t5-ablation-study&si=1f68824c2f0c401dad1f375c504b36ec&utm_source=clipboard&utm_medium=text&utm_campaign=social_sharing" target="_blank">Click Here</a></td>
  </tr>
</table>

<table border="1">
  <colgroup>
    <col style="width:800px;">
    <col style="width:100px;">
    <col style="width:100px;">
  </colgroup>
  <tr>
    <td align="center"><b>Document 3</b></td>
    <td align="center"><b>TTS document reader</b></td>
    <td align="center"><b>Audio Result</b></td>
  </tr>
  <tr>
    <td rowspan="4"><img src="image/2.png" alt="document"></td>
    <td><b>MathReader</b></td>
    <td><a href="https://soundcloud.com/8j9shhld5qmv/17fe7bd6-07fb-410d-a204-7229574b283d?in=8j9shhld5qmv/sets/mathreader&si=1fae71985d2b48dead9aa0b39f2798d4&utm_source=clipboard&utm_medium=text&utm_campaign=social_sharing" target="_blank">Click Here</a></td>
  </tr>
  <tr>
    <td><b>Microsoft Edge</b></td>
    <td><a href="https://soundcloud.com/8j9shhld5qmv/bf28e46f-a08b-41f1-ab93-1ef8c0b06841?in=8j9shhld5qmv/sets/microsoft-edge&si=d0cf4ac7e8904a6c976904e17e50bcf4&utm_source=clipboard&utm_medium=text&utm_campaign=social_sharing" target="_blank">Click Here</a></td>
  </tr>
  <tr>
    <td><b>Adobe Acrobat</b></td>
    <td><a href="https://soundcloud.com/8j9shhld5qmv/cb4d670f-d969-4a5f-ad28-f029edc9c305?in=8j9shhld5qmv/sets/adobe-acrobat&si=14e9e0f8080b447082f2e882165c7c19&utm_source=clipboard&utm_medium=text&utm_campaign=social_sharing" target="_blank">Click Here</a></td>
  </tr>
  <tr>
    <td><b>MathReader without T5     (Ablation Study)</b></td>
    <td><a href="https://soundcloud.com/8j9shhld5qmv/9d09cb4a-2db4-4d9b-815e-2ca50a9c9aa9?in=8j9shhld5qmv/sets/mathreader-without-t5-ablation-study&si=2969bc6574434e79985a8d84bef26580&utm_source=clipboard&utm_medium=text&utm_campaign=social_sharing" target="_blank">Click Here</a></td>
  </tr>
</table>



<table border="1">
  <colgroup>
    <col style="width:800px;">
    <col style="width:100px;">
    <col style="width:100px;">
  </colgroup>
  <tr>
    <td align="center"><b>Document 4</b></td>
    <td align="center"><b>TTS document reader</b></td>
    <td align="center"><b>Audio Result</b></td>
  </tr>
  <tr>
    <td rowspan="4"><img src="image/5.png" alt="document"></td>
    <td><b>MathReader</b></td>
    <td><a href="https://soundcloud.com/8j9shhld5qmv/50769394-2136-45ad-b9e6-25be1155025e?in=8j9shhld5qmv/sets/mathreader&si=a27c78e1a6094a3ea7b025ddc8eb04c6&utm_source=clipboard&utm_medium=text&utm_campaign=social_sharing" target="_blank">Click Here</a></td>
  </tr>
  <tr>
    <td><b>Microsoft Edge</b></td>
    <td><a href="https://soundcloud.com/8j9shhld5qmv/486c3ba5-7c0a-4cf9-8b9c-44bb4a5d12f1?in=8j9shhld5qmv/sets/microsoft-edge&si=5e581a4ff4524a4c95d907e0f1fcd0a8&utm_source=clipboard&utm_medium=text&utm_campaign=social_sharing" target="_blank">Click Here</a></td> 
  </tr>
  <tr>
    <td><b>Adobe Acrobat</b></td>
    <td><a href="https://soundcloud.com/8j9shhld5qmv/1776db6d-5dcd-4a39-8139-7312d3abe10e?in=8j9shhld5qmv/sets/adobe-acrobat&si=2f0aa0b57ca2470998163558d248ecd9&utm_source=clipboard&utm_medium=text&utm_campaign=social_sharing" target="_blank">Click Here</a></td>
  </tr>
  <tr>
    <td><b>MathReader without T5     (Ablation Study)</b></td>
    <td><a href="https://soundcloud.com/8j9shhld5qmv/966b5b87-2c37-46ca-b75e-63af9189b9b1?in=8j9shhld5qmv/sets/mathreader-without-t5-ablation-study&si=d1b0faf0707f4970a16a644ec2ba10f6&utm_source=clipboard&utm_medium=text&utm_campaign=social_sharing" target="_blank">Click Here</a></td>
  </tr>
</table>



<table border="1">
  <colgroup>
    <col style="width:800px;">
    <col style="width:100px;">
    <col style="width:100px;">
  </colgroup>
  <tr>
    <td align="center"><b>Document 5</b></td>
    <td align="center"><b>TTS document reader</b></td>
    <td align="center"><b>Audio Result</b></td>
  </tr>
  <tr>
    <td rowspan="4"><img src="image/6.png" alt="document"></td>
    <td><b>MathReader</b></td>
    <td><a href="https://soundcloud.com/8j9shhld5qmv/b4ff9b87-c896-4215-a2ea-96cbd20e9118?in=8j9shhld5qmv/sets/mathreader&si=a0d5fd255b164f289379594c898611cc&utm_source=clipboard&utm_medium=text&utm_campaign=social_sharing" target="_blank">Click Here</a></td>
  </tr>
  <tr>
    <td><b>Microsoft Edge</b></td>
    <td><a href="https://soundcloud.com/8j9shhld5qmv/46f3fbb8-1e46-4e0f-a11c-22f9b7d5b233?in=8j9shhld5qmv/sets/microsoft-edge&si=bb7455dfa7f946c5b819c1378887cb79&utm_source=clipboard&utm_medium=text&utm_campaign=social_sharing" target="_blank">Click Here</a></td>
  </tr>
  <tr>
    <td><b>Adobe Acrobat</b></td>
    <td><a href="https://soundcloud.com/8j9shhld5qmv/334fc7e6-4a0e-45fc-9375-83042b5a1ce8?in=8j9shhld5qmv/sets/adobe-acrobat&si=7ab33852d27a4b3fbe2d8e3360a17636&utm_source=clipboard&utm_medium=text&utm_campaign=social_sharing" target="_blank">Click Here</a></td>
  </tr>
  <tr>
    <td><b>MathReader without T5     (Ablation Study)</b></td>
    <td><a href="https://soundcloud.com/8j9shhld5qmv/da4208f4-120e-4687-b4fc-afdf8d5da9b5?in=8j9shhld5qmv/sets/mathreader-without-t5-ablation-study&si=309929894fea492e940a6c838990c31d&utm_source=clipboard&utm_medium=text&utm_campaign=social_sharing" target="_blank">Click Here</a></td>
  </tr>
</table>

<table border="1">
  <colgroup>
    <col style="width:800px;">
    <col style="width:100px;">
    <col style="width:100px;">
  </colgroup>
  <tr>
    <td align="center"><b>Document 6</b></td>
    <td align="center"><b>TTS document reader</b></td>
    <td align="center"><b>Audio Result</b></td>
  </tr>
  <tr>
    <td rowspan="4"><img src="image/7.png" alt="document"></td>
    <td><b>MathReader</b></td>
    <td><a href="https://soundcloud.com/8j9shhld5qmv/bd66a1b0-d637-4082-baac-db352ed16193?in=8j9shhld5qmv/sets/mathreader&si=950c8f775b054dc88fd3654291b46302&utm_source=clipboard&utm_medium=text&utm_campaign=social_sharing" target="_blank">Click Here</a></td>
  </tr>
  <tr>
    <td><b>Microsoft Edge</b></td>
    <td><a href="https://soundcloud.com/8j9shhld5qmv/1a92ed84-3149-4c25-adf1-79da2f7a73a7?in=8j9shhld5qmv/sets/microsoft-edge&si=a841006475244c02852732d3c764d755&utm_source=clipboard&utm_medium=text&utm_campaign=social_sharing" target="_blank">Click Here</a></td>
  </tr>
  <tr>
    <td><b>Adobe Acrobat</b></td>
    <td><a href="https://soundcloud.com/8j9shhld5qmv/637c8187-f188-4e3a-8a98-39c4e4174e24?in=8j9shhld5qmv/sets/adobe-acrobat&si=3947546e62d541868c05673cf5535e4e&utm_source=clipboard&utm_medium=text&utm_campaign=social_sharing" target="_blank">Click Here</a></td>
  </tr>
  <tr>
    <td><b>MathReader without T5     (Ablation Study)</b></td>
    <td><a href="https://soundcloud.com/8j9shhld5qmv/4e156825-3b15-4e0f-86c2-8c4cd1055881?in=8j9shhld5qmv/sets/mathreader-without-t5-ablation-study&si=07a422a72971462aa95723030d97a3ec&utm_source=clipboard&utm_medium=text&utm_campaign=social_sharing" target="_blank">Click Here</a></td>
  </tr>
</table>

<table border="1">
  <colgroup>
    <col style="width:800px;">
    <col style="width:100px;">
    <col style="width:100px;">
  </colgroup>
  <tr>
    <td align="center"><b>Document 7</b></td>
    <td align="center"><b>TTS document reader</b></td>
    <td align="center"><b>Audio Result</b></td>
  </tr>
  <tr>
    <td rowspan="4"><img src="image/8.png" alt="document"></td>
    <td><b>MathReader</b></td>
    <td><a href="https://soundcloud.com/8j9shhld5qmv/1945e0aa-d3cc-4734-a381-17157082bc38?in=8j9shhld5qmv/sets/mathreader&si=0ad7081abb7b42e69733551898c5b0fd&utm_source=clipboard&utm_medium=text&utm_campaign=social_sharing" target="_blank">Click Here</a></td>
  </tr>
  <tr>
    <td><b>Microsoft Edge</b></td>
    <td><a href="https://soundcloud.com/8j9shhld5qmv/fa8343f0-ebd8-4ea0-922e-f3c97aead809?in=8j9shhld5qmv/sets/microsoft-edge&si=8946251c937d40108696defb8842b7a8&utm_source=clipboard&utm_medium=text&utm_campaign=social_sharing" target="_blank">Click Here</a></td>
  </tr>
  <tr>
    <td><b>Adobe Acrobat</b></td>
    <td><a href="https://soundcloud.com/8j9shhld5qmv/412d652f-5ce6-48c7-bdc7-b29c56c1052c?in=8j9shhld5qmv/sets/adobe-acrobat&si=cae62e48bc794d48a3234bb7232d8e3a&utm_source=clipboard&utm_medium=text&utm_campaign=social_sharing" target="_blank">Click Here</a></td>
  </tr>
  <tr>
    <td><b>MathReader without T5     (Ablation Study)</b></td>
    <td><a href="https://soundcloud.com/8j9shhld5qmv/426c4766-9f4a-4c58-954e-7bc85031482e?in=8j9shhld5qmv/sets/mathreader-without-t5-ablation-study&si=a7d7df88a55e403daf77b21a9914ab68&utm_source=clipboard&utm_medium=text&utm_campaign=social_sharing" target="_blank">Click Here</a></td>
  </tr>
</table>

<table border="1">
  <colgroup>
    <col style="width:800px;">
    <col style="width:100px;">
    <col style="width:100px;">
  </colgroup>
  <tr>
    <td align="center"><b>Document 8</b></td>
    <td align="center"><b>TTS document reader</b></td>
    <td align="center"><b>Audio Result</b></td>
  </tr>
  <tr>
    <td rowspan="4"><img src="image/9.png" alt="document"></td>
    <td><b>MathReader</b></td>
    <td><a href="https://soundcloud.com/8j9shhld5qmv/7ab231be-a9fd-4638-b6a6-effa77c0862a?in=8j9shhld5qmv/sets/mathreader&si=400ba887a8d84cc19b3f5aedd5d67b63&utm_source=clipboard&utm_medium=text&utm_campaign=social_sharing" target="_blank">Click Here</a></td>
  </tr>
  <tr>
    <td><b>Microsoft Edge</b></td>
    <td><a href="https://soundcloud.com/8j9shhld5qmv/9a?in=8j9shhld5qmv/sets/microsoft-edge&si=838e832049674aa3a60544cd20cdbfc9&utm_source=clipboard&utm_medium=text&utm_campaign=social_sharing" target="_blank">Click Here</a></td>
  </tr>
  <tr>
    <td><b>Adobe Acrobat</b></td>
    <td><a href="https://soundcloud.com/8j9shhld5qmv/da0e2411-019a-4b9a-a916-9de70a1d5b3e?in=8j9shhld5qmv/sets/adobe-acrobat&si=6aadcc99777e4a43a7e8a41d511e46d5&utm_source=clipboard&utm_medium=text&utm_campaign=social_sharing" target="_blank">Click Here</a></td>
  </tr>
  <tr>
    <td><b>MathReader without T5     (Ablation Study)</b></td>
    <td><a href="https://soundcloud.com/8j9shhld5qmv/a001b5a8-df26-458e-b2c9-7fd5f661ff18?in=8j9shhld5qmv/sets/mathreader-without-t5-ablation-study&si=1823c3b58cc8439fb61587e73ef2a968&utm_source=clipboard&utm_medium=text&utm_campaign=social_sharing" target="_blank">Click Here</a></td>
  </tr>
</table>

<table border="1">
  <colgroup>
    <col style="width:800px;">
    <col style="width:100px;">
    <col style="width:100px;">
  </colgroup>
  <tr>
    <td align="center"><b>Document 9</b></td>
    <td align="center"><b>TTS document reader</b></td>
    <td align="center"><b>Audio Result</b></td>
  </tr>
  <tr>
    <td rowspan="4"><img src="image/10.png" alt="document"></td>
    <td><b>MathReader</b></td>
    <td><a href="https://soundcloud.com/8j9shhld5qmv/4701ea74-099d-4891-b28c-c0d59c06f3f9?in=8j9shhld5qmv/sets/mathreader&si=b53ff0f42cee41d497bfdee6286cfbcb&utm_source=clipboard&utm_medium=text&utm_campaign=social_sharing" target="_blank">Click Here</a></td>
  </tr>
  <tr>
    <td><b>Microsoft Edge</b></td>
    <td><a href="https://soundcloud.com/8j9shhld5qmv/10a?in=8j9shhld5qmv/sets/microsoft-edge&si=8420f41f45f146a38d6b895981445b98&utm_source=clipboard&utm_medium=text&utm_campaign=social_sharing" target="_blank">Click Here</a></td>
  </tr>
  <tr>
    <td><b>Adobe Acrobat</b></td>
    <td><a href="https://soundcloud.com/8j9shhld5qmv/d1fb0250-dcad-4b62-b680-fbdde03d26f4?in=8j9shhld5qmv/sets/adobe-acrobat&si=c52b0df7ff17470095b1d2003790d180&utm_source=clipboard&utm_medium=text&utm_campaign=social_sharing" target="_blank">Click Here</a></td>
  </tr>
  <tr>
    <td><b>MathReader without T5     (Ablation Study)</b></td>
    <td><a href="https://soundcloud.com/8j9shhld5qmv/6a4ea359-31c3-4168-93cf-67b1d6b37522?in=8j9shhld5qmv/sets/mathreader-without-t5-ablation-study&si=5372d03baa194f5d954100b7e6d0c1ef&utm_source=clipboard&utm_medium=text&utm_campaign=social_sharing" target="_blank">Click Here</a></td>
  </tr>
</table>

<table border="1">
  <colgroup>
    <col style="width:800px;">
    <col style="width:100px;">
    <col style="width:100px;">
  </colgroup>
  <tr>
    <td align="center"><b>Document 10</b></td>
    <td align="center"><b>TTS document reader</b></td>
    <td align="center"><b>Audio Result</b></td>
  </tr>
  <tr>
    <td rowspan="4"><img src="image/1.png" alt="document"></td>
    <td><b>MathReader</b></td>
    <td><a href="https://soundcloud.com/8j9shhld5qmv/b7641286-b7cf-4070-a9d9-e9e739266a50?in=8j9shhld5qmv/sets/mathreader&si=e7be50fab6564f458f3aeb9c7152ea3e&utm_source=clipboard&utm_medium=text&utm_campaign=social_sharing" target="_blank">Click Here</a></td>
  </tr>
  <tr>
    <td><b>Microsoft Edge</b></td>
    <td><a href="https://soundcloud.com/8j9shhld5qmv/956e9473-96a8-4f7b-b59c-243f69a7f2e2?in=8j9shhld5qmv/sets/microsoft-edge&si=edacc4982aa34998bb1df88590e68df3&utm_source=clipboard&utm_medium=text&utm_campaign=social_sharing" target="_blank">Click Here</a></td>
  </tr>
  <tr>
    <td><b>Adobe Acrobat</b></td>
    <td><a href="https://soundcloud.com/8j9shhld5qmv/5a87227b-4a4b-43de-848a-ceec4f6f6b2e?in=8j9shhld5qmv/sets/adobe-acrobat&si=69e9e512e58d4f9c9572e9945b4ba806&utm_source=clipboard&utm_medium=text&utm_campaign=social_sharing" target="_blank">Click Here</a></td>
  </tr>
  <tr>
    <td><b>MathReader without T5     (Ablation Study)</b></td>
    <td><a href="https://soundcloud.com/8j9shhld5qmv/6e3543f9-556f-4778-a642-3a8e2f44cd04?in=8j9shhld5qmv/sets/mathreader-without-t5-ablation-study&si=d7886bafad874d17a22133566d0d3802&utm_source=clipboard&utm_medium=text&utm_campaign=social_sharing" target="_blank">Click Here</a></td>
  </tr>
</table>
