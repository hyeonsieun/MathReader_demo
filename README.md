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
    <td><a href="https://drive.google.com/file/d/1ONoeIQmYewlm3N9T5bo9DsO2TUwxq2S4/view?usp=drive_link" target="_blank">Click Here</a></td>
  </tr>
  <tr>
    <td><b>Microsoft Edge</b></td>
    <td><a href="https://drive.google.com/file/d/1k8xYV5iqa6s7_UEvJJxRPBpB_0nbHQTZ/view?usp=drive_link" target="_blank">Click Here</a></td>
  </tr>
  <tr>
    <td><b>Adobe Acrobat</b></td>
    <td><a href="https://drive.google.com/file/d/1Bc0FZFEa-NeTmNDidt42lqrT17mZ42k0/view?usp=drive_link" target="_blank">Click Here</a></td>
  </tr>
  <tr>
    <td><b>MathReader without T5     (Ablation Study)</b></td>
    <td><a href="https://drive.google.com/file/d/1m05IPg5uRJlyKkyhRpIZ--EShS2K6Rwt/view?usp=drive_link" target="_blank">Click Here</a></td>
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
