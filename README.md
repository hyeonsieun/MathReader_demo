# MathReader: Text-to-Speech for Mathematical Documents

## Abstract
TTS (Text-to-Speech) document reader from Microsoft, Adobe, Apple, and OpenAI have been serviced worldwide. They provide relatively good TTS results for general plain text, but sometimes skip contents or provide unsatisfactory results for mathematical expressions. This is because most modern academic papers are written in LaTeX, and when LaTeX formulas are compiled, they are rendered as distinctive text forms within the document. However, traditional TTS document readers output only the text as it is recognized, without considering the mathematical meaning of the formulas. To address this issue, we propose MathReader, which effectively integrates OCR, a fine-tuned T5 model, and TTS. MathReader demonstrated a lower Word Error Rate (WER) than existing TTS document readers, such as Microsoft Edge and Adobe Acrobat, when processing documents containing mathematical formulas. MathReader reduced the WER from 0.510 to 0.281 compared to Microsoft Edge, and from 0.617 to 0.281 compared to Adobe Acrobat. This will significantly contribute to alleviating the inconvenience faced by users who want to listen to documents, especially those who are visually impaired.

### This page is for anonymous submission for ICASSP 2025.

Here, you can listen the example voice from each TTS document reader.

---

## Example results from MathReader

<table border="1">
  <colgroup>
    <col style="width:800px;">
    <col style="width:100px;">
    <col style="width:100px;">
  </colgroup>
  <tr>
    <td align="center"><b>Example 1</b></td>
    <td align="center"><b>TTS document reader</b></td>
    <td align="center"><b>Audio Result</b></td>
  </tr>
  <tr>
    <td rowspan="4"><img src="image/1.png" alt="document 1"></td>
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

<table border="1">
  <colgroup>
    <col style="width:800px;">
    <col style="width:100px;">
    <col style="width:100px;">
  </colgroup>
  <tr>
    <td align="center"><b>Example 2</b></td>
    <td align="center"><b>TTS document reader</b></td>
    <td align="center"><b>Audio Result</b></td>
  </tr>
  <tr>
    <td rowspan="4"><img src="image/2.png" alt="document 2"></td>
    <td><b>MathReader</b></td>
    <td><a href="https://drive.google.com/file/d/1BpmjNCN43TRDWQ5DgzjrlQsf18oz33Nf/view?usp=drive_link" target="_blank">Click Here</a></td>
  </tr>
  <tr>
    <td><b>Microsoft Edge</b></td>
    <td><a href="https://drive.google.com/file/d/1-KNUwelQ8rRIpP1oe7sBYW32LSSTyxIp/view?usp=drive_link" target="_blank">Click Here</a></td>
  </tr>
  <tr>
    <td><b>Adobe Acrobat</b></td>
    <td><a href="https://drive.google.com/file/d/12-exajhBrODNXzqfV7chuA2Ws_3_b1R1/view?usp=drive_link" target="_blank">Click Here</a></td>
  </tr>
  <tr>
    <td><b>MathReader without T5     (Ablation Study)</b></td>
    <td><a href="https://drive.google.com/file/d/1v8B5ExJQ1IE0f3AWSty2uHXa0y0Opz0Z/view?usp=drive_link" target="_blank">Click Here</a></td>
  </tr>
</table>

<table border="1">
  <colgroup>
    <col style="width:800px;">
    <col style="width:100px;">
    <col style="width:100px;">
  </colgroup>
  <tr>
    <td align="center"><b>Example 3</b></td>
    <td align="center"><b>TTS document reader</b></td>
    <td align="center"><b>Audio Result</b></td>
  </tr>
  <tr>
    <td rowspan="4"><img src="image/3.png" alt="document 3"></td>
    <td><b>MathReader</b></td>
    <td><a href="https://drive.google.com/file/d/1E6FN16N3kwoW2TPTWy08rNMxbMKKsJp2/view?usp=drive_link" target="_blank">Click Here</a></td>
  </tr>
  <tr>
    <td><b>Microsoft Edge</b></td>
    <td><a href="https://drive.google.com/file/d/1qPDkwimRjJwWvFX780iElStknbbm1ub8/view?usp=drive_link" target="_blank">Click Here</a></td>
  </tr>
  <tr>
    <td><b>Adobe Acrobat</b></td>
    <td><a href="https://drive.google.com/file/d/1PplEEUfmT1VDS6LuOFl-TIRClhkXN_sB/view?usp=drive_link" target="_blank">Click Here</a></td>
  </tr>
  <tr>
    <td><b>MathReader without T5     (Ablation Study)</b></td>
    <td><a href="https://drive.google.com/file/d/1_vMe0lzisUbQT70QJRuiH2dm5xpmTNcF/view?usp=drive_link" target="_blank">Click Here</a></td>
  </tr>
</table>

<table border="1">
  <colgroup>
    <col style="width:800px;">
    <col style="width:100px;">
    <col style="width:100px;">
  </colgroup>
  <tr>
    <td align="center"><b>Example 4</b></td>
    <td align="center"><b>TTS document reader</b></td>
    <td align="center"><b>Audio Result</b></td>
  </tr>
  <tr>
    <td rowspan="4"><img src="image/4.png" alt="document 4"></td>
    <td><b>MathReader</b></td>
    <td><a href="https://drive.google.com/file/d/1rGhAy8Q2wRBJQhKwoLm6FqFn2PFQg85M/view?usp=drive_link" target="_blank">Click Here</a></td>
  </tr>
  <tr>
    <td><b>Microsoft Edge</b></td>
    <td><a href="https://drive.google.com/file/d/1dEsyKnXOlvUJyB2nB0MF3_VJxLAdCbJg/view?usp=drive_link" target="_blank">Click Here</a></td>
  </tr>
  <tr>
    <td><b>Adobe Acrobat</b></td>
    <td><a href="https://drive.google.com/file/d/1KHiqLK3WDcUmTLpohf-F1QWgRPdBg_v7/view?usp=drive_link" target="_blank">Click Here</a></td>
  </tr>
  <tr>
    <td><b>MathReader without T5     (Ablation Study)</b></td>
    <td><a href="https://drive.google.com/file/d/1h17RzF-AjfnNofU0jYbQkf4ZedC5l2RQ/view?usp=drive_link" target="_blank">Click Here</a></td>
  </tr>
</table>

<table border="1">
  <colgroup>
    <col style="width:800px;">
    <col style="width:100px;">
    <col style="width:100px;">
  </colgroup>
  <tr>
    <td align="center"><b>Example 5</b></td>
    <td align="center"><b>TTS document reader</b></td>
    <td align="center"><b>Audio Result</b></td>
  </tr>
  <tr>
    <td rowspan="4"><img src="image/5.png" alt="document 5"></td>
    <td><b>MathReader</b></td>
    <td><a href="https://drive.google.com/file/d/1EIwahGpA-9Xe30dztJvFCxf8cvZjPBFQ/view?usp=drive_link" target="_blank">Click Here</a></td>
  </tr>
  <tr>
    <td><b>Microsoft Edge</b></td>
    <td><a href="https://drive.google.com/file/d/1bqpkk06ZV1IwsNfMuvDFmMKHRMmjZeeK/view?usp=drive_link" target="_blank">Click Here</a></td> 
  </tr>
  <tr>
    <td><b>Adobe Acrobat</b></td>
    <td><a href="https://drive.google.com/file/d/1v5nHE40wz6GKTJ88rzW6Vfg4dQGaX03y/view?usp=drive_link" target="_blank">Click Here</a></td>
  </tr>
  <tr>
    <td><b>MathReader without T5     (Ablation Study)</b></td>
    <td><a href="https://drive.google.com/file/d/138v1Tdu912gX-2pEgaf7htVJ7z01bOAD/view?usp=drive_link" target="_blank">Click Here</a></td>
  </tr>
</table>
