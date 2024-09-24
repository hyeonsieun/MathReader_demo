# MathReader: Text-to-Speech for Mathematical Documents

## Abstract
TTS (Text-to-Speech) document reader from Microsoft, Adobe, Apple, and OpenAI have been serviced worldwide. They provide relatively good TTS results for general plain text, but sometimes skip contents or provide unsatisfactory results for mathematical expressions. This is because most modern academic papers are written in LaTeX, and when LaTeX formulas are compiled, they are rendered as distinctive text forms within the document. However, traditional TTS document readers output only the text as it is recognized, without considering the mathematical meaning of the formulas. To address this issue, we propose MathReader, which effectively integrates OCR, a fine-tuned T5 model, and TTS. MathReader demonstrated a lower Word Error Rate (WER) than existing TTS document readers, such as Microsoft Edge and Adobe Acrobat, when processing documents containing mathematical formulas. MathReader reduced the WER from 0.510 to 0.281 compared to Microsoft Edge, and from 0.617 to 0.281 compared to Adobe Acrobat. This will significantly contribute to alleviating the inconvenience faced by users who want to listen to documents, especially those who are visually impaired.

### This page is for anonymous submission for ICASSP 2025.

Here, you can find the experimental code, example wav files, and the test dataset developed for our research.

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

