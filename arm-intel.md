
 <h1 align=center> ARM Instruction Set </h1>
 
 <p align=center> ARM Processors के दो मुख्य States होते हैं जिनमें वे काम कर सकते हैं ARM और THUMB। इन दो States के बीच मुख्य Difference Instructions सेट है, जहां ARM States में Instructions हमेशा 32-बिट, 64-बिट होते हैं, और THUMB States में Instructions 16-बिट होते हैं (लेकिन 32-बिट हो सकते हैं)। </p>
  
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



 <h1 align=center> Intel Instruction Set </h1>
 
 <p align=center> Processor एक छोटी चिप होती है जो बोलने के लिए कंप्यूटर के इनपुट और आउटपुट communications प्रदान करती है। ARM Processor एक प्रकार का Architecture है और Android, creator इस तकनीक का उपयोग अपने मोबाइल उपकरणों में करते हैं जबकि Intel आमतौर पर कंप्यूटर में उपयोग किया जाता है। </p>


|Sr. No.| 8086 |
|:----:|:-----:|
|**1**| MOV (copies data from one location to another) <br> **R1 ==> R2** |
|**2**| MVI (Move Immediate DATA to Accumulator) <br> **R1 ==> 5700H** |
|**3**| ADD (Accumulator Data + Register Data) <br> **A ==> A + R** |
|**4**| SUB (Accumulator Data + Register Data) <br> **A ==> A - R** |
|**5**| INR (Increment) <br> **R = R + 1** |
|**6**| DCR (Decrement) <br> **R = R - 1** |
|**7**| ADC (Accumulator Data + Carry <br> **R = R + Op2 + Carry** |
|**8**| PUSHA (put all the register into the stack) |
|**9**| IN (Input to the port or copies a byte or word from **S** to **D**) |
|**10**| OUTPUT (Output to the port or copies a byte or word from **D** to **S**) |

 
