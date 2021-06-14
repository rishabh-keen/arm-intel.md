
 <h1 align=center> ARM Instruction Set </h1>
 
 <p align=center> ARM Processors के दो मुख्य States होते हैं जिनमें वे काम कर सकते हैं ARM और THUMB। इन States का Privilege levels से कोई लेना-देना नहीं है। उदाहरण के लिए, SVC mode में चलने वाला कोड ARM या Thumb हो सकता है। इन दो States के बीच मुख्य Difference Instructions सेट है, जहां ARM States में Instructions हमेशा 32-बिट होते हैं, और THUMB States में Instructions 16-बिट होते हैं (लेकिन 32-बिट हो सकते हैं)। Thumb का उपयोग कब और कैसे करना है, यह जानना हमारे ARM के Development उद्देश्यों के लिए विशेष रूप से महत्वपूर्ण है। और 32-बिट ARM Instructions के बजाय 16-बिट THUMB Instructions का उपयोग करने से उनके होने की संभावना कम हो जाती है। </p>
  
|Sr. No.| ARM |
|:----:|:-----:|
|**1**| ADD - {Rd,} Rn, Op2 <br> **Add.Rd = Rn + Op2** |
|**2**| ADC - {Rd,} Rn, Op2 <br> **Add with carry.Rd = Rn + Op2 + Carry** |
|**3**| SUB - {Rd,} Rn, Op2 <br> **Subtract.Rd = Rn - Op2** |
|**4**| SBC - {Rd,} Rn, Op2 <br> **Subtract with carry.Rd = Rn - Op2 + Carry- l** |
|**5**| RSB - {Rd,} Rn, Op2 <br> **Reverse Subtract.Rd = Op2 - Rn** |
|**6**| MUL - {Rd,} Rn, Rm <br> **Multiply.Rd = (Rn * Rm)** |
|**7**| MLA - Rd, Rn, Rm, Ra <br> **Multiply with accumulate Rd = (Ra + (Rn * Rm))** |
|**8**| MLS - Rd, Rn, Rm, Ra <br> **Multiply and subtract, Rd = (Ra - (Rn * Rm))** |
|**9**| SDIV - {Rd,} Rn, Rm <br> **Signed divide.Rd = Rn / Rm** |
|**10**| UDIV - Rd, Rn, Rm, Ra <br> **UnSigned divide.Rd = Rn / Rm** |

 
