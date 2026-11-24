# 1.6 指標與名詞　補充練習題（656 題）（第 2／4 頁）

所屬：[1.6 指標與名詞](1-6.md)

GSMA 這個細項題目不足，以下為補充題（情境與數據為出題用的假設資料）。另有留存題不放在書上，只用來評估。換頁時若從情境中間開始，情境內容請看上一頁。

頁次：[1](1-6-bank-1.md)　**2**　[3](1-6-bank-3.md)　[4](1-6-bank-4.md)

## 1.6.2 訊號品質：RSRQ、SINR、CQI（續）

**0315.** 若較高調變配置的計算名目值較大，可以推定應用層有效吞吐量必然較大嗎？

<details><summary>看答案</summary>

**答案**　仍需以實測的有效資料量與時間驗證。

**詳解**　排程資源、傳輸區塊大小、錯誤、重傳和應用開銷都會影響實際交付速率。

**出處**　[3GPP TS 38.214 §5.1.3.1](https://www.etsi.org/deliver/etsi_ts/138200_138299/138214/18.07.00_60/ts_138214v180700p.pdf) · [3GPP TS 28.552 §5.1.1.3](https://www.etsi.org/deliver/etsi_ts/128500_128599/128552/19.06.00_60/ts_128552v190600p.pdf)

</details>

**情境 064｜校園資料鏈測試**

UE 回報 table1 的 CQI 9，工程師另取得兩筆實際下行配置，調變階數 Qₘ 分別為 2、4，編碼率分子分別為 602、616（分母 1024）。另抽測 250 個首傳區塊，22 個錯誤。配置數字直接由本題給定。

**0316.** ［計算題］第一筆 Qₘ＝2、目標編碼率 602/1024。忽略其他開銷，名目值 Qₘ × 編碼率為何？（四捨五入至小數第 4 位）

<details><summary>看答案</summary>

**答案**　1.1758 bit／調變符號。

**詳解**　算式 `2 × 602 ÷ 1024 ≈ 1.1758` bit／調變符號。

**出處**　[3GPP TS 38.214 §5.1.3.1](https://www.etsi.org/deliver/etsi_ts/138200_138299/138214/18.07.00_60/ts_138214v180700p.pdf)

</details>

**0317.** ［計算題］第一筆 Qₘ＝2、編碼率 602/1024，第二筆 Qₘ＝4、編碼率 616/1024。第二筆的 Qₘ × 編碼率比第一筆多多少？（四捨五入至小數第 4 位）

<details><summary>看答案</summary>

**答案**　1.2305 bit／調變符號。

**詳解**　算式 `(4 × 616−2 × 602) ÷ 1024 ≈ 1.2305` bit／調變符號。

**出處**　[3GPP TS 38.214 §5.1.3.1](https://www.etsi.org/deliver/etsi_ts/138200_138299/138214/18.07.00_60/ts_138214v180700p.pdf)

</details>

**0318.** ［計算題］抽測 250 個首傳區塊，其中 22 個錯誤，測得的首傳區塊錯誤百分比為何？（四捨五入至小數第 2 位）

<details><summary>看答案</summary>

**答案**　8.80%。

**詳解**　算式 `22 ÷ 250 × 100 = 8.80`%。

**出處**　[3GPP TS 28.552 §§5.1.1.7.1–5.1.1.7.2](https://www.etsi.org/deliver/etsi_ts/128500_128599/128552/19.06.00_60/ts_128552v190600p.pdf)

</details>

**0319.** 跨兩次測試比較 CQI 9 時，為何須一起記下 table1 這個配置？

<details><summary>看答案</summary>

**答案**　同一索引在不同 CQI 表的解釋和適用條件可能不同。

**詳解**　表的配置決定索引對應的調變／編碼描述及目標錯誤機率。

**出處**　[3GPP TS 38.214 §5.2.2.1](https://www.etsi.org/deliver/etsi_ts/138200_138299/138214/18.07.00_60/ts_138214v180700p.pdf)

</details>

**情境 065｜封閉量測場下行調度**

UE 回報 table1 的 CQI 8，工程師另取得兩筆實際下行配置，調變階數 Qₘ 分別為 2、6，編碼率分子分別為 308、567（分母 1024）。另抽測 500 個首傳區塊，34 個錯誤。配置數字直接由本題給定。

**0321.** ［計算題］第一筆 Qₘ＝2、目標編碼率 308/1024。忽略其他開銷，名目值 Qₘ × 編碼率為何？（四捨五入至小數第 4 位）

<details><summary>看答案</summary>

**答案**　0.6016 bit／調變符號。

**詳解**　算式 `2 × 308 ÷ 1024 ≈ 0.6016` bit／調變符號。

**出處**　[3GPP TS 38.214 §5.1.3.1](https://www.etsi.org/deliver/etsi_ts/138200_138299/138214/18.07.00_60/ts_138214v180700p.pdf)

</details>

**0322.** ［計算題］第一筆 Qₘ＝2、編碼率 308/1024，第二筆 Qₘ＝6、編碼率 567/1024。第二筆的 Qₘ × 編碼率比第一筆多多少？（四捨五入至小數第 4 位）

<details><summary>看答案</summary>

**答案**　2.7207 bit／調變符號。

**詳解**　算式 `(6 × 567−2 × 308) ÷ 1024 ≈ 2.7207` bit／調變符號。

**出處**　[3GPP TS 38.214 §5.1.3.1](https://www.etsi.org/deliver/etsi_ts/138200_138299/138214/18.07.00_60/ts_138214v180700p.pdf)

</details>

**0323.** ［計算題］抽測 500 個首傳區塊，其中 34 個錯誤，測得的首傳區塊錯誤百分比為何？（四捨五入至小數第 2 位）

<details><summary>看答案</summary>

**答案**　6.80%。

**詳解**　算式 `34 ÷ 500 × 100 = 6.80`%。

**出處**　[3GPP TS 28.552 §§5.1.1.7.1–5.1.1.7.2](https://www.etsi.org/deliver/etsi_ts/128500_128599/128552/19.06.00_60/ts_128552v190600p.pdf)

</details>

**0324.** 跨兩次測試比較 CQI 8 時，為何須一起記下 table1 這個配置？

<details><summary>看答案</summary>

**答案**　同一索引在不同 CQI 表的解釋和適用條件可能不同。

**詳解**　表的配置決定索引對應的調變／編碼描述及目標錯誤機率。

**出處**　[3GPP TS 38.214 §5.2.2.1](https://www.etsi.org/deliver/etsi_ts/138200_138299/138214/18.07.00_60/ts_138214v180700p.pdf)

</details>

## 1.6.3 吞吐量與延遲

### 1. 十進位 bit／byte 與有效資料量

**情境 067｜雲端備份下載**

同一 12 s 觀測窗內，接收測點計入總量 120 MB，應用層收到不重複有效資料 96 MB。定義 1 MB＝10⁶ byte，1 byte＝8 bit。

**0331.** ［計算題］接收測點在 12 s 內累積 120 MB，採十進位 MB。其觀測吞吐量是多少 Mbit/s？（四捨五入至小數第 2 位）

<details><summary>看答案</summary>

**答案**　80.00 Mbit/s。

**詳解**　將 MB 乘以 8 轉成 Mbit，再除以經過時間。 算式 `120 × 8 ÷ 12 = 80.00` Mbit/s。

**出處**　[RFC 5136，IP 容量與使用率](https://www.rfc-editor.org/rfc/rfc5136.html) · [BIPM SI Brochure，十進位前綴](https://www.bipm.org/en/publications/si-brochure)

</details>

**0332.** ［計算題］應用在 12 s 內去重後收到 96 MB，採十進位 MB。求 goodput。（四捨五入至小數第 2 位）

<details><summary>看答案</summary>

**答案**　64.00 Mbit/s。

**詳解**　應用有效資料是此題 goodput 的分子。 算式 `96 × 8 ÷ 12 = 64.00` Mbit/s。

**出處**　[RFC 7928 §2.5 Goodput](https://www.rfc-editor.org/info/rfc7928/) · [BIPM SI Brochure，十進位前綴](https://www.bipm.org/en/publications/si-brochure)

</details>

**0333.** ［計算題］同一時間窗總量 120 MB、有效量 96 MB，有效資料占觀測總量的百分比為何？（四捨五入至小數第 2 位）

<details><summary>看答案</summary>

**答案**　80.00%。

**詳解**　算式 `96 ÷ 120 × 100 = 80.00`%。

**出處**　[RFC 7928 §2.5 Goodput](https://www.rfc-editor.org/info/rfc7928/)

</details>

**0334.** 能否由兩層資料量之差，判定全部差額皆由重傳造成？

<details><summary>看答案</summary>

**答案**　現有資料只支持兩個量測口徑有差額。

**詳解**　重傳、協定標頭、封裝和量測計數位置都可能影響差額。可再看重傳與封包分類的統計。

**出處**　[RFC 7928 §2.5 Goodput](https://www.rfc-editor.org/info/rfc7928/) · [RFC 5136，IP 容量與使用率](https://www.rfc-editor.org/rfc/rfc5136.html)

</details>

**0335.** 把這組結果和基地台的 DL UE 吞吐量相比，先核對什麼？

<details><summary>看答案</summary>

**答案**　核對統計所在層、資料量篩選、時間定義及所量測的 UE／方向。

**詳解**　TS 28.552 的 UE 吞吐量有特定資料量、時間與承載口徑，應用有效速率另依應用交付量計算。

**出處**　[3GPP TS 28.552 §5.1.1.3](https://www.etsi.org/deliver/etsi_ts/128500_128599/128552/19.06.00_60/ts_128552v190600p.pdf)

</details>

**情境 068｜倉庫終端韌體下載**

同一 10 s 觀測窗內，接收測點計入總量 75 MB，應用層收到不重複有效資料 60 MB。定義 1 MB＝10⁶ byte，1 byte＝8 bit。

**0336.** ［計算題］接收測點在 10 s 內累積 75 MB，採十進位 MB。其觀測吞吐量是多少 Mbit/s？（四捨五入至小數第 2 位）

<details><summary>看答案</summary>

**答案**　60.00 Mbit/s。

**詳解**　將 MB 乘以 8 轉成 Mbit，再除以經過時間。 算式 `75 × 8 ÷ 10 = 60.00` Mbit/s。

**出處**　[RFC 5136，IP 容量與使用率](https://www.rfc-editor.org/rfc/rfc5136.html) · [BIPM SI Brochure，十進位前綴](https://www.bipm.org/en/publications/si-brochure)

</details>

**0337.** ［計算題］應用在 10 s 內去重後收到 60 MB，採十進位 MB。求 goodput。（四捨五入至小數第 2 位）

<details><summary>看答案</summary>

**答案**　48.00 Mbit/s。

**詳解**　應用有效資料是此題 goodput 的分子。 算式 `60 × 8 ÷ 10 = 48.00` Mbit/s。

**出處**　[RFC 7928 §2.5 Goodput](https://www.rfc-editor.org/info/rfc7928/) · [BIPM SI Brochure，十進位前綴](https://www.bipm.org/en/publications/si-brochure)

</details>

**0338.** ［計算題］同一時間窗總量 75 MB、有效量 60 MB，有效資料占觀測總量的百分比為何？（四捨五入至小數第 2 位）

<details><summary>看答案</summary>

**答案**　80.00%。

**詳解**　算式 `60 ÷ 75 × 100 = 80.00`%。

**出處**　[RFC 7928 §2.5 Goodput](https://www.rfc-editor.org/info/rfc7928/)

</details>

**0339.** 能否由兩層資料量之差，判定全部差額皆由重傳造成？

<details><summary>看答案</summary>

**答案**　現有資料只支持兩個量測口徑有差額。

**詳解**　重傳、協定標頭、封裝和量測計數位置都可能影響差額。可再看重傳與封包分類的統計。

**出處**　[RFC 7928 §2.5 Goodput](https://www.rfc-editor.org/info/rfc7928/) · [RFC 5136，IP 容量與使用率](https://www.rfc-editor.org/rfc/rfc5136.html)

</details>

**0340.** 把這組結果和基地台的 DL UE 吞吐量相比，先核對什麼？

<details><summary>看答案</summary>

**答案**　核對統計所在層、資料量篩選、時間定義及所量測的 UE／方向。

**詳解**　TS 28.552 的 UE 吞吐量有特定資料量、時間與承載口徑，應用有效速率另依應用交付量計算。

**出處**　[3GPP TS 28.552 §5.1.1.3](https://www.etsi.org/deliver/etsi_ts/128500_128599/128552/19.06.00_60/ts_128552v190600p.pdf)

</details>

**情境 069｜場館內容同步**

同一 25 s 觀測窗內，接收測點計入總量 420 MB，應用層收到不重複有效資料 350 MB。定義 1 MB＝10⁶ byte，1 byte＝8 bit。

**0341.** ［計算題］接收測點在 25 s 內累積 420 MB，採十進位 MB。其觀測吞吐量是多少 Mbit/s？（四捨五入至小數第 2 位）

<details><summary>看答案</summary>

**答案**　134.40 Mbit/s。

**詳解**　將 MB 乘以 8 轉成 Mbit，再除以經過時間。 算式 `420 × 8 ÷ 25 = 134.40` Mbit/s。

**出處**　[RFC 5136，IP 容量與使用率](https://www.rfc-editor.org/rfc/rfc5136.html) · [BIPM SI Brochure，十進位前綴](https://www.bipm.org/en/publications/si-brochure)

</details>

**0342.** ［計算題］應用在 25 s 內去重後收到 350 MB，採十進位 MB。求 goodput。（四捨五入至小數第 2 位）

<details><summary>看答案</summary>

**答案**　112.00 Mbit/s。

**詳解**　應用有效資料是此題 goodput 的分子。 算式 `350 × 8 ÷ 25 = 112.00` Mbit/s。

**出處**　[RFC 7928 §2.5 Goodput](https://www.rfc-editor.org/info/rfc7928/) · [BIPM SI Brochure，十進位前綴](https://www.bipm.org/en/publications/si-brochure)

</details>

**0343.** ［計算題］同一時間窗總量 420 MB、有效量 350 MB，有效資料占觀測總量的百分比為何？（四捨五入至小數第 2 位）

<details><summary>看答案</summary>

**答案**　83.33%。

**詳解**　算式 `350 ÷ 420 × 100 ≈ 83.33`%。

**出處**　[RFC 7928 §2.5 Goodput](https://www.rfc-editor.org/info/rfc7928/)

</details>

**情境 071｜企業專線驗收**

同一 30 s 觀測窗內，接收測點計入總量 525 MB，應用層收到不重複有效資料 450 MB。定義 1 MB＝10⁶ byte，1 byte＝8 bit。

**0351.** ［計算題］接收測點在 30 s 內累積 525 MB，採十進位 MB。其觀測吞吐量是多少 Mbit/s？（四捨五入至小數第 2 位）

<details><summary>看答案</summary>

**答案**　140.00 Mbit/s。

**詳解**　將 MB 乘以 8 轉成 Mbit，再除以經過時間。 算式 `525 × 8 ÷ 30 = 140.00` Mbit/s。

**出處**　[RFC 5136，IP 容量與使用率](https://www.rfc-editor.org/rfc/rfc5136.html) · [BIPM SI Brochure，十進位前綴](https://www.bipm.org/en/publications/si-brochure)

</details>

**0352.** ［計算題］應用在 30 s 內去重後收到 450 MB，採十進位 MB。求 goodput。（四捨五入至小數第 2 位）

<details><summary>看答案</summary>

**答案**　120.00 Mbit/s。

**詳解**　應用有效資料是此題 goodput 的分子。 算式 `450 × 8 ÷ 30 = 120.00` Mbit/s。

**出處**　[RFC 7928 §2.5 Goodput](https://www.rfc-editor.org/info/rfc7928/) · [BIPM SI Brochure，十進位前綴](https://www.bipm.org/en/publications/si-brochure)

</details>

**0353.** ［計算題］同一時間窗總量 525 MB、有效量 450 MB，有效資料占觀測總量的百分比為何？（四捨五入至小數第 2 位）

<details><summary>看答案</summary>

**答案**　85.71%。

**詳解**　算式 `450 ÷ 525 × 100 ≈ 85.71`%。

**出處**　[RFC 7928 §2.5 Goodput](https://www.rfc-editor.org/info/rfc7928/)

</details>

### 2. 共享路徑瓶頸與容量利用

**情境 073｜分校連外匯聚**

4 條同條件工作階段的入口各 100 Mbit/s、出口各 75 Mbit/s，共用 200 Mbit/s 中段並等分。各工作階段持續傳輸，忽略其他開銷。

**0361.** ［計算題］共用鏈路 200 Mbit/s，由 4 條工作階段等分。每條可用的共享段容量為何？（四捨五入至小數第 2 位）

<details><summary>看答案</summary>

**答案**　50.00 Mbit/s。

**詳解**　算式 `200 ÷ 4 = 50.00` Mbit/s。

**出處**　[RFC 5136，IP 容量與使用率](https://www.rfc-editor.org/rfc/rfc5136.html)

</details>

**0362.** ［計算題］入口 100、出口 75 Mbit/s，共享段 200 Mbit/s 由 4 條等分。求單條端到端理想速率上限。（四捨五入至小數第 2 位）

<details><summary>看答案</summary>

**答案**　50.00 Mbit/s。

**詳解**　取沿路可用速率的最小值。 算式 `min(100, 75, 200 ÷ 4) = 50.00` Mbit/s。

**出處**　[RFC 5136，IP 容量與使用率](https://www.rfc-editor.org/rfc/rfc5136.html)

</details>

**0363.** ［計算題］上述條件下，單條需傳送 125 MB（十進位）。入口 100、出口 75 Mbit/s，共享段 200 Mbit/s 等分成 4 條，理想至少需多久？（四捨五入至小數第 2 位）

<details><summary>看答案</summary>

**答案**　20.00 s。

**詳解**　算式 `125 × 8 ÷ min(100, 75, 200 ÷ 4) = 20.00` s。

**出處**　[RFC 5136，IP 容量與使用率](https://www.rfc-editor.org/rfc/rfc5136.html) · [BIPM SI Brochure，十進位前綴](https://www.bipm.org/en/publications/si-brochure)

</details>

**0364.** 若只升級已大於最小可用速率的路段，本題模型中的端到端上限會立刻增加嗎？

<details><summary>看答案</summary>

**答案**　只提升非限制路段時，原瓶頸仍限制速率。

**詳解**　比較的是工作階段逐段可用容量。該最小可用速率仍限制全路徑。

**出處**　[RFC 5136，IP 容量與使用率](https://www.rfc-editor.org/rfc/rfc5136.html)

</details>

**0365.** 現場測得的 goodput 低於本題上限，應優先補哪些資訊？

<details><summary>看答案</summary>

**答案**　查實際負載、資料封裝、重傳、應用端或接收端處理，並確認各段使用的時間窗。

**詳解**　題設理想化忽略了這些成本。基於同條件的觀測才有辦法定位差異。

**出處**　[RFC 5136，IP 容量與使用率](https://www.rfc-editor.org/rfc/rfc5136.html) · [RFC 7928 §2.5 Goodput](https://www.rfc-editor.org/info/rfc7928/)

</details>

**情境 074｜物流站點專線合流**

5 條同條件工作階段的入口各 90 Mbit/s、出口各 80 Mbit/s，共用 350 Mbit/s 中段並等分。各工作階段持續傳輸，忽略其他開銷。

**0366.** ［計算題］共用鏈路 350 Mbit/s，由 5 條工作階段等分。每條可用的共享段容量為何？（四捨五入至小數第 2 位）

<details><summary>看答案</summary>

**答案**　70.00 Mbit/s。

**詳解**　算式 `350 ÷ 5 = 70.00` Mbit/s。

**出處**　[RFC 5136，IP 容量與使用率](https://www.rfc-editor.org/rfc/rfc5136.html)

</details>

**0367.** ［計算題］入口 90、出口 80 Mbit/s，共享段 350 Mbit/s 由 5 條等分。求單條端到端理想速率上限。（四捨五入至小數第 2 位）

<details><summary>看答案</summary>

**答案**　70.00 Mbit/s。

**詳解**　取沿路可用速率的最小值。 算式 `min(90, 80, 350 ÷ 5) = 70.00` Mbit/s。

**出處**　[RFC 5136，IP 容量與使用率](https://www.rfc-editor.org/rfc/rfc5136.html)

</details>

**0368.** ［計算題］上述條件下，單條需傳送 280 MB（十進位）。入口 90、出口 80 Mbit/s，共享段 350 Mbit/s 等分成 5 條，理想至少需多久？（四捨五入至小數第 2 位）

<details><summary>看答案</summary>

**答案**　32.00 s。

**詳解**　算式 `280 × 8 ÷ min(90, 80, 350 ÷ 5) = 32.00` s。

**出處**　[RFC 5136，IP 容量與使用率](https://www.rfc-editor.org/rfc/rfc5136.html) · [BIPM SI Brochure，十進位前綴](https://www.bipm.org/en/publications/si-brochure)

</details>

**0369.** 若只升級已大於最小可用速率的路段，本題模型中的端到端上限會立刻增加嗎？

<details><summary>看答案</summary>

**答案**　只提升非限制路段時，原瓶頸仍限制速率。

**詳解**　比較的是工作階段逐段可用容量。該最小可用速率仍限制全路徑。

**出處**　[RFC 5136，IP 容量與使用率](https://www.rfc-editor.org/rfc/rfc5136.html)

</details>

**0370.** 現場測得的 goodput 低於本題上限，應優先補哪些資訊？

<details><summary>看答案</summary>

**答案**　查實際負載、資料封裝、重傳、應用端或接收端處理，並確認各段使用的時間窗。

**詳解**　題設理想化忽略了這些成本。基於同條件的觀測才有辦法定位差異。

**出處**　[RFC 5136，IP 容量與使用率](https://www.rfc-editor.org/rfc/rfc5136.html) · [RFC 7928 §2.5 Goodput](https://www.rfc-editor.org/info/rfc7928/)

</details>

**情境 075｜碼頭設備同步共享段**

3 條同條件工作階段的入口各 110 Mbit/s、出口各 95 Mbit/s，共用 240 Mbit/s 中段並等分。各工作階段持續傳輸，忽略其他開銷。

**0371.** ［計算題］共用鏈路 240 Mbit/s，由 3 條工作階段等分。每條可用的共享段容量為何？（四捨五入至小數第 2 位）

<details><summary>看答案</summary>

**答案**　80.00 Mbit/s。

**詳解**　算式 `240 ÷ 3 = 80.00` Mbit/s。

**出處**　[RFC 5136，IP 容量與使用率](https://www.rfc-editor.org/rfc/rfc5136.html)

</details>

**0372.** ［計算題］入口 110、出口 95 Mbit/s，共享段 240 Mbit/s 由 3 條等分。求單條端到端理想速率上限。（四捨五入至小數第 2 位）

<details><summary>看答案</summary>

**答案**　80.00 Mbit/s。

**詳解**　取沿路可用速率的最小值。 算式 `min(110, 95, 240 ÷ 3) = 80.00` Mbit/s。

**出處**　[RFC 5136，IP 容量與使用率](https://www.rfc-editor.org/rfc/rfc5136.html)

</details>

**0373.** ［計算題］上述條件下，單條需傳送 120 MB（十進位）。入口 110、出口 95 Mbit/s，共享段 240 Mbit/s 等分成 3 條，理想至少需多久？（四捨五入至小數第 2 位）

<details><summary>看答案</summary>

**答案**　12.00 s。

**詳解**　算式 `120 × 8 ÷ min(110, 95, 240 ÷ 3) = 12.00` s。

**出處**　[RFC 5136，IP 容量與使用率](https://www.rfc-editor.org/rfc/rfc5136.html) · [BIPM SI Brochure，十進位前綴](https://www.bipm.org/en/publications/si-brochure)

</details>

**情境 076｜企業伺服器共同出站**

4 條同條件工作階段的入口各 85 Mbit/s、出口各 100 Mbit/s，共用 360 Mbit/s 中段並等分。各工作階段持續傳輸，忽略其他開銷。

**0376.** ［計算題］共用鏈路 360 Mbit/s，由 4 條工作階段等分。每條可用的共享段容量為何？（四捨五入至小數第 2 位）

<details><summary>看答案</summary>

**答案**　90.00 Mbit/s。

**詳解**　算式 `360 ÷ 4 = 90.00` Mbit/s。

**出處**　[RFC 5136，IP 容量與使用率](https://www.rfc-editor.org/rfc/rfc5136.html)

</details>

**0377.** ［計算題］入口 85、出口 100 Mbit/s，共享段 360 Mbit/s 由 4 條等分。求單條端到端理想速率上限。（四捨五入至小數第 2 位）

<details><summary>看答案</summary>

**答案**　85.00 Mbit/s。

**詳解**　取沿路可用速率的最小值。 算式 `min(85, 100, 360 ÷ 4) = 85.00` Mbit/s。

**出處**　[RFC 5136，IP 容量與使用率](https://www.rfc-editor.org/rfc/rfc5136.html)

</details>

**0378.** ［計算題］上述條件下，單條需傳送 170 MB（十進位）。入口 85、出口 100 Mbit/s，共享段 360 Mbit/s 等分成 4 條，理想至少需多久？（四捨五入至小數第 2 位）

<details><summary>看答案</summary>

**答案**　16.00 s。

**詳解**　算式 `170 × 8 ÷ min(85, 100, 360 ÷ 4) = 16.00` s。

**出處**　[RFC 5136，IP 容量與使用率](https://www.rfc-editor.org/rfc/rfc5136.html) · [BIPM SI Brochure，十進位前綴](https://www.bipm.org/en/publications/si-brochure)

</details>

### 3. 單向延遲、RTT 與回應處理

**情境 078｜園區務工探測**

A 於 2000 ms 送出探測，B 在 2009 ms 收到，在 2013 ms 送出回應，A 在 2035 ms 收到。兩端時鐘已同步，時間戳採同一時基。

**0386.** ［計算題］A 送出為 2000 ms，B 收到為 2009 ms。A→B 單向延遲是多少？

<details><summary>看答案</summary>

**答案**　9 ms。

**詳解**　算式 `2009−2000 = 9` ms。

**出處**　[RFC 7679，單向延遲](https://www.rfc-editor.org/rfc/rfc7679.html)

</details>

**0387.** ［計算題］B 在 2013 ms 送出回應，A 於 2035 ms 收到。B→A 單向延遲是多少？

<details><summary>看答案</summary>

**答案**　22 ms。

**詳解**　算式 `2035−2013 = 22` ms。

**出處**　[RFC 7679，單向延遲](https://www.rfc-editor.org/rfc/rfc7679.html)

</details>

**0388.** ［計算題］A 於 2000 ms 送出，2035 ms 收到回應。本題的探測 RTT 包括 B 的處理時間，是多少？

<details><summary>看答案</summary>

**答案**　35 ms。

**詳解**　算式 `2035−2000 = 35` ms。

**出處**　[RFC 2681，往返延遲](https://www.rfc-editor.org/rfc/rfc2681.html)

</details>

**0389.** 如果只留下 A 端的送出與回應時間，可把 RTT 除以 2 當作 A→B 的真實延遲嗎？

<details><summary>看答案</summary>

**答案**　無法單靠 RTT 求得真實單向延遲。

**詳解**　往返路徑可能非對稱，回應也可能有處理時間。要直接量單向延遲，應掌握同步時間戳和方向。

**出處**　[RFC 7679，單向延遲](https://www.rfc-editor.org/rfc/rfc7679.html) · [RFC 2681，往返延遲](https://www.rfc-editor.org/rfc/rfc2681.html)

</details>

**0390.** 若 B 時鐘未與 A 同步，哪一個指標仍可直接用同一台 A 的時間戳求得？

<details><summary>看答案</summary>

**答案**　本題探測的 RTT。

**詳解**　A 同一時基的起迄時間可相減。跨裝置計算單向延遲受相對時鐘誤差影響。

**出處**　[RFC 7679，單向延遲](https://www.rfc-editor.org/rfc/rfc7679.html) · [RFC 2681，往返延遲](https://www.rfc-editor.org/rfc/rfc2681.html)

</details>

**情境 079｜海港監控回應**

A 於 3000 ms 送出探測，B 在 3024 ms 收到，在 3027 ms 送出回應，A 在 3044 ms 收到。兩端時鐘已同步，時間戳採同一時基。

**0391.** ［計算題］A 送出為 3000 ms，B 收到為 3024 ms。A→B 單向延遲是多少？

<details><summary>看答案</summary>

**答案**　24 ms。

**詳解**　算式 `3024−3000 = 24` ms。

**出處**　[RFC 7679，單向延遲](https://www.rfc-editor.org/rfc/rfc7679.html)

</details>

**0392.** ［計算題］B 在 3027 ms 送出回應，A 於 3044 ms 收到。B→A 單向延遲是多少？

<details><summary>看答案</summary>

**答案**　17 ms。

**詳解**　算式 `3044−3027 = 17` ms。

**出處**　[RFC 7679，單向延遲](https://www.rfc-editor.org/rfc/rfc7679.html)

</details>

**0393.** ［計算題］A 於 3000 ms 送出，3044 ms 收到回應。本題的探測 RTT 包括 B 的處理時間，是多少？

<details><summary>看答案</summary>

**答案**　44 ms。

**詳解**　算式 `3044−3000 = 44` ms。

**出處**　[RFC 2681，往返延遲](https://www.rfc-editor.org/rfc/rfc2681.html)

</details>

**0394.** 如果只留下 A 端的送出與回應時間，可把 RTT 除以 2 當作 A→B 的真實延遲嗎？

<details><summary>看答案</summary>

**答案**　無法單靠 RTT 求得真實單向延遲。

**詳解**　往返路徑可能非對稱，回應也可能有處理時間。要直接量單向延遲，應掌握同步時間戳和方向。

**出處**　[RFC 7679，單向延遲](https://www.rfc-editor.org/rfc/rfc7679.html) · [RFC 2681，往返延遲](https://www.rfc-editor.org/rfc/rfc2681.html)

</details>

**0395.** 若 B 時鐘未與 A 同步，哪一個指標仍可直接用同一台 A 的時間戳求得？

<details><summary>看答案</summary>

**答案**　本題探測的 RTT。

**詳解**　A 同一時基的起迄時間可相減。跨裝置計算單向延遲受相對時鐘誤差影響。

**出處**　[RFC 7679，單向延遲](https://www.rfc-editor.org/rfc/rfc7679.html) · [RFC 2681，往返延遲](https://www.rfc-editor.org/rfc/rfc2681.html)

</details>

**情境 080｜校園伺服器回應**

A 於 4000 ms 送出探測，B 在 4014 ms 收到，在 4022 ms 送出回應，A 在 4045 ms 收到。兩端時鐘已同步，時間戳採同一時基。

**0396.** ［計算題］A 送出為 4000 ms，B 收到為 4014 ms。A→B 單向延遲是多少？

<details><summary>看答案</summary>

**答案**　14 ms。

**詳解**　算式 `4014−4000 = 14` ms。

**出處**　[RFC 7679，單向延遲](https://www.rfc-editor.org/rfc/rfc7679.html)

</details>

**0397.** ［計算題］B 在 4022 ms 送出回應，A 於 4045 ms 收到。B→A 單向延遲是多少？

<details><summary>看答案</summary>

**答案**　23 ms。

**詳解**　算式 `4045−4022 = 23` ms。

**出處**　[RFC 7679，單向延遲](https://www.rfc-editor.org/rfc/rfc7679.html)

</details>

**0398.** ［計算題］A 於 4000 ms 送出，4045 ms 收到回應。本題的探測 RTT 包括 B 的處理時間，是多少？

<details><summary>看答案</summary>

**答案**　45 ms。

**詳解**　算式 `4045−4000 = 45` ms。

**出處**　[RFC 2681，往返延遲](https://www.rfc-editor.org/rfc/rfc2681.html)

</details>

**情境 081｜跨城量測路徑**

A 於 5000 ms 送出探測，B 在 5031 ms 收到，在 5035 ms 送出回應，A 在 5051 ms 收到。兩端時鐘已同步，時間戳採同一時基。

**0401.** ［計算題］A 送出為 5000 ms，B 收到為 5031 ms。A→B 單向延遲是多少？

<details><summary>看答案</summary>

**答案**　31 ms。

**詳解**　算式 `5031−5000 = 31` ms。

**出處**　[RFC 7679，單向延遲](https://www.rfc-editor.org/rfc/rfc7679.html)

</details>

**0402.** ［計算題］B 在 5035 ms 送出回應，A 於 5051 ms 收到。B→A 單向延遲是多少？

<details><summary>看答案</summary>

**答案**　16 ms。

**詳解**　算式 `5051−5035 = 16` ms。

**出處**　[RFC 7679，單向延遲](https://www.rfc-editor.org/rfc/rfc7679.html)

</details>

**0403.** ［計算題］A 於 5000 ms 送出，5051 ms 收到回應。本題的探測 RTT 包括 B 的處理時間，是多少？

<details><summary>看答案</summary>

**答案**　51 ms。

**詳解**　算式 `5051−5000 = 51` ms。

**出處**　[RFC 2681，往返延遲](https://www.rfc-editor.org/rfc/rfc2681.html)

</details>

**情境 082｜夜間平台會話探測**

A 於 6000 ms 送出探測，B 在 6008 ms 收到，在 6010 ms 送出回應，A 在 6029 ms 收到。兩端時鐘已同步，時間戳採同一時基。

**0406.** ［計算題］A 送出為 6000 ms，B 收到為 6008 ms。A→B 單向延遲是多少？

<details><summary>看答案</summary>

**答案**　8 ms。

**詳解**　算式 `6008−6000 = 8` ms。

**出處**　[RFC 7679，單向延遲](https://www.rfc-editor.org/rfc/rfc7679.html)

</details>

**0407.** ［計算題］B 在 6010 ms 送出回應，A 於 6029 ms 收到。B→A 單向延遲是多少？

<details><summary>看答案</summary>

**答案**　19 ms。

**詳解**　算式 `6029−6010 = 19` ms。

**出處**　[RFC 7679，單向延遲](https://www.rfc-editor.org/rfc/rfc7679.html)

</details>

**0408.** ［計算題］A 於 6000 ms 送出，6029 ms 收到回應。本題的探測 RTT 包括 B 的處理時間，是多少？

<details><summary>看答案</summary>

**答案**　29 ms。

**詳解**　算式 `6029−6000 = 29` ms。

**出處**　[RFC 2681，往返延遲](https://www.rfc-editor.org/rfc/rfc2681.html)

</details>

### 4. 分位數與尾端延遲

**情境 084｜平台 API 延遲抽樣**

同方向 10 筆延遲樣本已排序，單位均為 ms。樣本為 4、5、6、7、8、9、13、18、23、41。本題採最近名次法，Pₚ 取排序後第 ceil(p × N) 筆，p 使用 0 到 1。

**0416.** ［計算題］樣本 4、5、6、7、8、9、13、18、23、41 ms。依題設最近名次法，P90 取哪個值？

<details><summary>看答案</summary>

**答案**　23 ms。

**詳解**　位置＝ceil(0.90 × 10)＝9，取第 9 筆。 rank 表示按題設取分位數。 算式 `rank(4, 5, 6, 7, 8, 9, 13, 18, 23, 41, 0.9) = 23` ms。

**出處**　[NIST 統計手冊，Percentiles](https://www.itl.nist.gov/div898/handbook/prc/section2/prc262.htm)

</details>

**0417.** ［計算題］樣本 4、5、6、7、8、9、13、18、23、41 ms。依同一最近名次法，P90 和 P50 相差多少？

<details><summary>看答案</summary>

**答案**　15 ms。

**詳解**　P90 取第 9 筆，P50 取第 5 筆。 rank 表示按題設取分位數。 算式 `rank(4, 5, 6, 7, 8, 9, 13, 18, 23, 41, 0.9)−rank(4, 5, 6, 7, 8, 9, 13, 18, 23, 41, 0.5) = 15` ms。

**出處**　[NIST 統計手冊，Percentiles](https://www.itl.nist.gov/div898/handbook/prc/section2/prc262.htm)

</details>

**0418.** ［計算題］樣本 4、5、6、7、8、9、13、18、23、41 ms 中，嚴格超過 10 ms 的比例是多少？（四捨五入至小數第 2 位）

<details><summary>看答案</summary>

**答案**　40.00%。

**詳解**　符合條件者 4 筆，等於門檻的樣本不計。 above 計數嚴格大於第一參數的樣本。 算式 `above(10, 4, 5, 6, 7, 8, 9, 13, 18, 23, 41) ÷ 10 × 100 = 40.00`%。

**出處**　[NIST 統計手冊，Percentiles](https://www.itl.nist.gov/div898/handbook/prc/section2/prc262.htm)

</details>

**0419.** P50 符合門檻但 P90 偏高，可由這批樣本看出什麼？

<details><summary>看答案</summary>

**答案**　中間水準與較慢端的延遲表現有差異。

**詳解**　P50 描述中間位置，P90 更能顯示較慢的樣本。兩者需在同一採樣配置及計算法下對讀。

**出處**　[NIST 統計手冊，Percentiles](https://www.itl.nist.gov/div898/handbook/prc/section2/prc262.htm) · [RFC 7679，單向延遲](https://www.rfc-editor.org/rfc/rfc7679.html)

</details>

**0420.** 另一份報表也寫 P90，但樣本經過插值規則與不同抽樣頻率。能否直接用兩個值判定變差？

<details><summary>看答案</summary>

**答案**　先核對分位數算法、樣本範圍、測點與抽樣頻率。

**詳解**　分位數對樣本集合和求法敏感。條件未對齊時，不宜把算法差異當成網路變化。

**出處**　[NIST 統計手冊，Percentiles](https://www.itl.nist.gov/div898/handbook/prc/section2/prc262.htm)

</details>

**情境 085｜企業專線探測抽樣**

同方向 10 筆延遲樣本已排序，單位均為 ms。樣本為 12、14、15、16、20、21、22、25、32、70。本題採最近名次法，Pₚ 取排序後第 ceil(p × N) 筆，p 使用 0 到 1。

**0421.** ［計算題］樣本 12、14、15、16、20、21、22、25、32、70 ms。依題設最近名次法，P90 取哪個值？

<details><summary>看答案</summary>

**答案**　32 ms。

**詳解**　位置＝ceil(0.90 × 10)＝9，取第 9 筆。 rank 表示按題設取分位數。 算式 `rank(12, 14, 15, 16, 20, 21, 22, 25, 32, 70, 0.9) = 32` ms。

**出處**　[NIST 統計手冊，Percentiles](https://www.itl.nist.gov/div898/handbook/prc/section2/prc262.htm)

</details>

**0422.** ［計算題］樣本 12、14、15、16、20、21、22、25、32、70 ms。依同一最近名次法，P90 和 P50 相差多少？

<details><summary>看答案</summary>

**答案**　12 ms。

**詳解**　P90 取第 9 筆，P50 取第 5 筆。 rank 表示按題設取分位數。 算式 `rank(12, 14, 15, 16, 20, 21, 22, 25, 32, 70, 0.9)−rank(12, 14, 15, 16, 20, 21, 22, 25, 32, 70, 0.5) = 12` ms。

**出處**　[NIST 統計手冊，Percentiles](https://www.itl.nist.gov/div898/handbook/prc/section2/prc262.htm)

</details>

**0423.** ［計算題］樣本 12、14、15、16、20、21、22、25、32、70 ms 中，嚴格超過 22 ms 的比例是多少？（四捨五入至小數第 2 位）

<details><summary>看答案</summary>

**答案**　30.00%。

**詳解**　符合條件者 3 筆，等於門檻的樣本不計。 above 計數嚴格大於第一參數的樣本。 算式 `above(22, 12, 14, 15, 16, 20, 21, 22, 25, 32, 70) ÷ 10 × 100 = 30.00`%。

**出處**　[NIST 統計手冊，Percentiles](https://www.itl.nist.gov/div898/handbook/prc/section2/prc262.htm)

</details>

**0424.** P50 符合門檻但 P90 偏高，可由這批樣本看出什麼？

<details><summary>看答案</summary>

**答案**　中間水準與較慢端的延遲表現有差異。

**詳解**　P50 描述中間位置，P90 更能顯示較慢的樣本。兩者需在同一採樣配置及計算法下對讀。

**出處**　[NIST 統計手冊，Percentiles](https://www.itl.nist.gov/div898/handbook/prc/section2/prc262.htm) · [RFC 7679，單向延遲](https://www.rfc-editor.org/rfc/rfc7679.html)

</details>

**0425.** 另一份報表也寫 P90，但樣本經過插值規則與不同抽樣頻率。能否直接用兩個值判定變差？

<details><summary>看答案</summary>

**答案**　先核對分位數算法、樣本範圍、測點與抽樣頻率。

**詳解**　分位數對樣本集合和求法敏感。條件未對齊時，不宜把算法差異當成網路變化。

**出處**　[NIST 統計手冊，Percentiles](https://www.itl.nist.gov/div898/handbook/prc/section2/prc262.htm)

</details>

**情境 086｜車站無線應用探測**

同方向 10 筆延遲樣本已排序，單位均為 ms。樣本為 10、12、13、14、18、20、30、36、41、85。本題採最近名次法，Pₚ 取排序後第 ceil(p × N) 筆，p 使用 0 到 1。

**0426.** ［計算題］樣本 10、12、13、14、18、20、30、36、41、85 ms。依題設最近名次法，P90 取哪個值？

<details><summary>看答案</summary>

**答案**　41 ms。

**詳解**　位置＝ceil(0.90 × 10)＝9，取第 9 筆。 rank 表示按題設取分位數。 算式 `rank(10, 12, 13, 14, 18, 20, 30, 36, 41, 85, 0.9) = 41` ms。

**出處**　[NIST 統計手冊，Percentiles](https://www.itl.nist.gov/div898/handbook/prc/section2/prc262.htm)

</details>

**0427.** ［計算題］樣本 10、12、13、14、18、20、30、36、41、85 ms。依同一最近名次法，P90 和 P50 相差多少？

<details><summary>看答案</summary>

**答案**　23 ms。

**詳解**　P90 取第 9 筆，P50 取第 5 筆。 rank 表示按題設取分位數。 算式 `rank(10, 12, 13, 14, 18, 20, 30, 36, 41, 85, 0.9)−rank(10, 12, 13, 14, 18, 20, 30, 36, 41, 85, 0.5) = 23` ms。

**出處**　[NIST 統計手冊，Percentiles](https://www.itl.nist.gov/div898/handbook/prc/section2/prc262.htm)

</details>

**0428.** ［計算題］樣本 10、12、13、14、18、20、30、36、41、85 ms 中，嚴格超過 30 ms 的比例是多少？（四捨五入至小數第 2 位）

<details><summary>看答案</summary>

**答案**　30.00%。

**詳解**　符合條件者 3 筆，等於門檻的樣本不計。 above 計數嚴格大於第一參數的樣本。 算式 `above(30, 10, 12, 13, 14, 18, 20, 30, 36, 41, 85) ÷ 10 × 100 = 30.00`%。

**出處**　[NIST 統計手冊，Percentiles](https://www.itl.nist.gov/div898/handbook/prc/section2/prc262.htm)

</details>

**情境 087｜機房路徑延遲抽樣**

同方向 10 筆延遲樣本已排序，單位均為 ms。樣本為 3、4、4、5、5、6、7、9、13、23。本題採最近名次法，Pₚ 取排序後第 ceil(p × N) 筆，p 使用 0 到 1。

**0431.** ［計算題］樣本 3、4、4、5、5、6、7、9、13、23 ms。依題設最近名次法，P90 取哪個值？

<details><summary>看答案</summary>

**答案**　13 ms。

**詳解**　位置＝ceil(0.90 × 10)＝9，取第 9 筆。 rank 表示按題設取分位數。 算式 `rank(3, 4, 4, 5, 5, 6, 7, 9, 13, 23, 0.9) = 13` ms。

**出處**　[NIST 統計手冊，Percentiles](https://www.itl.nist.gov/div898/handbook/prc/section2/prc262.htm)

</details>

**0432.** ［計算題］樣本 3、4、4、5、5、6、7、9、13、23 ms。依同一最近名次法，P90 和 P50 相差多少？

<details><summary>看答案</summary>

**答案**　8 ms。

**詳解**　P90 取第 9 筆，P50 取第 5 筆。 rank 表示按題設取分位數。 算式 `rank(3, 4, 4, 5, 5, 6, 7, 9, 13, 23, 0.9)−rank(3, 4, 4, 5, 5, 6, 7, 9, 13, 23, 0.5) = 8` ms。

**出處**　[NIST 統計手冊，Percentiles](https://www.itl.nist.gov/div898/handbook/prc/section2/prc262.htm)

</details>

**0433.** ［計算題］樣本 3、4、4、5、5、6、7、9、13、23 ms 中，嚴格超過 7 ms 的比例是多少？（四捨五入至小數第 2 位）

<details><summary>看答案</summary>

**答案**　30.00%。

**詳解**　符合條件者 3 筆，等於門檻的樣本不計。 above 計數嚴格大於第一參數的樣本。 算式 `above(7, 3, 4, 4, 5, 5, 6, 7, 9, 13, 23) ÷ 10 × 100 = 30.00`%。

**出處**　[NIST 統計手冊，Percentiles](https://www.itl.nist.gov/div898/handbook/prc/section2/prc262.htm)

</details>

### 5. 不同時間窗的觀測與加權

**情境 088｜日班備份流量**

同一測點連續兩個不重疊時窗。第一段 10 s 收到 80 MB，第二段 30 s 收到 120 MB。資料量採十進位 MB，統計口徑相同。

**0436.** ［計算題］第一段 10 s 收到 80 MB。十進位下第一段的平均速率為何？（四捨五入至小數第 2 位）

<details><summary>看答案</summary>

**答案**　64.00 Mbit/s。

**詳解**　算式 `80 × 8 ÷ 10 = 64.00` Mbit/s。

**出處**　[RFC 5136，IP 容量與使用率](https://www.rfc-editor.org/rfc/rfc5136.html) · [BIPM SI Brochure，十進位前綴](https://www.bipm.org/en/publications/si-brochure)

</details>

**0437.** ［計算題］第一段 10 s 有 80 MB，第二段 30 s 有 120 MB。兩段合起來的平均速率是多少？（四捨五入至小數第 2 位）

<details><summary>看答案</summary>

**答案**　40.00 Mbit/s。

**詳解**　算式 `(80 + 120) × 8 ÷ (10 + 30) = 40.00` Mbit/s。

**出處**　[RFC 5136，IP 容量與使用率](https://www.rfc-editor.org/rfc/rfc5136.html) · [BIPM SI Brochure，十進位前綴](https://www.bipm.org/en/publications/si-brochure)

</details>

**0438.** ［計算題］若只問第二段 30 s 所收 120 MB 占兩段 80 與 120 MB 的總量百分比，是多少？（四捨五入至小數第 2 位）

<details><summary>看答案</summary>

**答案**　60.00%。

**詳解**　算式 `120 ÷ (80 + 120) × 100 = 60.00`%。

**出處**　[RFC 5136，IP 容量與使用率](https://www.rfc-editor.org/rfc/rfc5136.html)

</details>

**0439.** 平均速率應直接把兩段各自的速率除以 2 嗎？

<details><summary>看答案</summary>

**答案**　以兩段總資料量除以總時間。

**詳解**　時窗長度不同時，需要按時間加權才等於合併速率。單純等權會讓短窗口影響過大。

**出處**　[RFC 5136，IP 容量與使用率](https://www.rfc-editor.org/rfc/rfc5136.html)

</details>

**0440.** 某報表以「有資料待傳期間」計時，另一份用完整觀測窗。比較前需做什麼？

<details><summary>看答案</summary>

**答案**　確認活動時間的篩選條件與是否涵蓋空閒期。

**詳解**　即使原始資料量相近，分母的累計時間可以不同。網管吞吐量有指定量測定義。

**出處**　[3GPP TS 28.552 §5.1.1.3](https://www.etsi.org/deliver/etsi_ts/128500_128599/128552/19.06.00_60/ts_128552v190600p.pdf)

</details>

**情境 090｜教學平台發布流量**

同一測點連續兩個不重疊時窗。第一段 15 s 收到 90 MB，第二段 25 s 收到 150 MB。資料量採十進位 MB，統計口徑相同。

**0446.** ［計算題］第一段 15 s 收到 90 MB。十進位下第一段的平均速率為何？（四捨五入至小數第 2 位）

<details><summary>看答案</summary>

**答案**　48.00 Mbit/s。

**詳解**　算式 `90 × 8 ÷ 15 = 48.00` Mbit/s。

**出處**　[RFC 5136，IP 容量與使用率](https://www.rfc-editor.org/rfc/rfc5136.html) · [BIPM SI Brochure，十進位前綴](https://www.bipm.org/en/publications/si-brochure)

</details>

**0447.** ［計算題］第一段 15 s 有 90 MB，第二段 25 s 有 150 MB。兩段合起來的平均速率是多少？（四捨五入至小數第 2 位）

<details><summary>看答案</summary>

**答案**　48.00 Mbit/s。

**詳解**　算式 `(90 + 150) × 8 ÷ (15 + 25) = 48.00` Mbit/s。

**出處**　[RFC 5136，IP 容量與使用率](https://www.rfc-editor.org/rfc/rfc5136.html) · [BIPM SI Brochure，十進位前綴](https://www.bipm.org/en/publications/si-brochure)

</details>

**0448.** ［計算題］若只問第二段 25 s 所收 150 MB 占兩段 90 與 150 MB 的總量百分比，是多少？（四捨五入至小數第 2 位）

<details><summary>看答案</summary>

**答案**　62.50%。

**詳解**　算式 `150 ÷ (90 + 150) × 100 = 62.50`%。

**出處**　[RFC 5136，IP 容量與使用率](https://www.rfc-editor.org/rfc/rfc5136.html)

</details>

**0449.** 平均速率應直接把兩段各自的速率除以 2 嗎？

<details><summary>看答案</summary>

**答案**　以兩段總資料量除以總時間。

**詳解**　時窗長度不同時，需要按時間加權才等於合併速率。單純等權會讓短窗口影響過大。

**出處**　[RFC 5136，IP 容量與使用率](https://www.rfc-editor.org/rfc/rfc5136.html)

</details>

**0450.** 某報表以「有資料待傳期間」計時，另一份用完整觀測窗。比較前需做什麼？

<details><summary>看答案</summary>

**答案**　確認活動時間的篩選條件與是否涵蓋空閒期。

**詳解**　即使原始資料量相近，分母的累計時間可以不同。網管吞吐量有指定量測定義。

**出處**　[3GPP TS 28.552 §5.1.1.3](https://www.etsi.org/deliver/etsi_ts/128500_128599/128552/19.06.00_60/ts_128552v190600p.pdf)

</details>

**情境 091｜場館出入口監控**

同一測點連續兩個不重疊時窗。第一段 5 s 收到 40 MB，第二段 20 s 收到 100 MB。資料量採十進位 MB，統計口徑相同。

**0451.** ［計算題］第一段 5 s 收到 40 MB。十進位下第一段的平均速率為何？（四捨五入至小數第 2 位）

<details><summary>看答案</summary>

**答案**　64.00 Mbit/s。

**詳解**　算式 `40 × 8 ÷ 5 = 64.00` Mbit/s。

**出處**　[RFC 5136，IP 容量與使用率](https://www.rfc-editor.org/rfc/rfc5136.html) · [BIPM SI Brochure，十進位前綴](https://www.bipm.org/en/publications/si-brochure)

</details>

**0452.** ［計算題］第一段 5 s 有 40 MB，第二段 20 s 有 100 MB。兩段合起來的平均速率是多少？（四捨五入至小數第 2 位）

<details><summary>看答案</summary>

**答案**　44.80 Mbit/s。

**詳解**　算式 `(40 + 100) × 8 ÷ (5 + 20) = 44.80` Mbit/s。

**出處**　[RFC 5136，IP 容量與使用率](https://www.rfc-editor.org/rfc/rfc5136.html) · [BIPM SI Brochure，十進位前綴](https://www.bipm.org/en/publications/si-brochure)

</details>

**0453.** ［計算題］若只問第二段 20 s 所收 100 MB 占兩段 40 與 100 MB 的總量百分比，是多少？（四捨五入至小數第 2 位）

<details><summary>看答案</summary>

**答案**　71.43%。

**詳解**　算式 `100 ÷ (40 + 100) × 100 ≈ 71.43`%。

**出處**　[RFC 5136，IP 容量與使用率](https://www.rfc-editor.org/rfc/rfc5136.html)

</details>

**情境 092｜企業月末資料移轉**

同一測點連續兩個不重疊時窗。第一段 12 s 收到 180 MB，第二段 28 s 收到 210 MB。資料量採十進位 MB，統計口徑相同。

**0456.** ［計算題］第一段 12 s 收到 180 MB。十進位下第一段的平均速率為何？（四捨五入至小數第 2 位）

<details><summary>看答案</summary>

**答案**　120.00 Mbit/s。

**詳解**　算式 `180 × 8 ÷ 12 = 120.00` Mbit/s。

**出處**　[RFC 5136，IP 容量與使用率](https://www.rfc-editor.org/rfc/rfc5136.html) · [BIPM SI Brochure，十進位前綴](https://www.bipm.org/en/publications/si-brochure)

</details>

**0457.** ［計算題］第一段 12 s 有 180 MB，第二段 28 s 有 210 MB。兩段合起來的平均速率是多少？（四捨五入至小數第 2 位）

<details><summary>看答案</summary>

**答案**　78.00 Mbit/s。

**詳解**　算式 `(180 + 210) × 8 ÷ (12 + 28) = 78.00` Mbit/s。

**出處**　[RFC 5136，IP 容量與使用率](https://www.rfc-editor.org/rfc/rfc5136.html) · [BIPM SI Brochure，十進位前綴](https://www.bipm.org/en/publications/si-brochure)

</details>

**0458.** ［計算題］若只問第二段 28 s 所收 210 MB 占兩段 180 與 210 MB 的總量百分比，是多少？（四捨五入至小數第 2 位）

<details><summary>看答案</summary>

**答案**　53.85%。

**詳解**　算式 `210 ÷ (180 + 210) × 100 ≈ 53.85`%。

**出處**　[RFC 5136，IP 容量與使用率](https://www.rfc-editor.org/rfc/rfc5136.html)

</details>

**情境 093｜外勤巡檢上傳**

同一測點連續兩個不重疊時窗。第一段 9 s 收到 36 MB，第二段 21 s 收到 126 MB。資料量採十進位 MB，統計口徑相同。

**0461.** ［計算題］第一段 9 s 收到 36 MB。十進位下第一段的平均速率為何？（四捨五入至小數第 2 位）

<details><summary>看答案</summary>

**答案**　32.00 Mbit/s。

**詳解**　算式 `36 × 8 ÷ 9 = 32.00` Mbit/s。

**出處**　[RFC 5136，IP 容量與使用率](https://www.rfc-editor.org/rfc/rfc5136.html) · [BIPM SI Brochure，十進位前綴](https://www.bipm.org/en/publications/si-brochure)

</details>

**0462.** ［計算題］第一段 9 s 有 36 MB，第二段 21 s 有 126 MB。兩段合起來的平均速率是多少？（四捨五入至小數第 2 位）

<details><summary>看答案</summary>

**答案**　43.20 Mbit/s。

**詳解**　算式 `(36 + 126) × 8 ÷ (9 + 21) = 43.20` Mbit/s。

**出處**　[RFC 5136，IP 容量與使用率](https://www.rfc-editor.org/rfc/rfc5136.html) · [BIPM SI Brochure，十進位前綴](https://www.bipm.org/en/publications/si-brochure)

</details>

**0463.** ［計算題］若只問第二段 21 s 所收 126 MB 占兩段 36 與 126 MB 的總量百分比，是多少？（四捨五入至小數第 2 位）

<details><summary>看答案</summary>

**答案**　77.78%。

**詳解**　算式 `126 ÷ (36 + 126) × 100 ≈ 77.78`%。

**出處**　[RFC 5136，IP 容量與使用率](https://www.rfc-editor.org/rfc/rfc5136.html)

</details>

## 1.6.4 接通率（Accessibility）、掉話率（Retainability）與可用率（Availability）

### 1. PDU Session 建立成功率與切片聚合

**情境 094｜企業專網切片晨間**

同一 S-NSSAI、同一時窗。SMF 甲處理 80 次建立嘗試，成功 76 次。SMF 乙處理 120 次，成功 114 次。數量為同口徑觀測。

**0466.** ［計算題］SMF 甲嘗試 80 次、成功 76 次，乙嘗試 120 次、成功 114 次。切片的 PDU Session 建立成功百分比為何？（四捨五入至小數第 2 位）

<details><summary>看答案</summary>

**答案**　95.00%。

**詳解**　同一切片先跨對應 SMF 加總，再以成功除以嘗試。 算式 `(76 + 114) ÷ (80 + 120) × 100 = 95.00`%。

**出處**　[3GPP TS 28.554 §6.2.5](https://www.etsi.org/deliver/etsi_ts/128500_128599/128554/19.07.00_60/ts_128554v190700p.pdf)

</details>

**0467.** ［計算題］兩台 SMF 分別有嘗試／成功 80／76 次與 120／114 次。若每次嘗試都已確定成功或未成功，未成功共有幾次？

<details><summary>看答案</summary>

**答案**　10 次。

**詳解**　算式 `(80−76) + (120−114) = 10` 次。

**出處**　[3GPP TS 28.554 §6.2.5](https://www.etsi.org/deliver/etsi_ts/128500_128599/128554/19.07.00_60/ts_128554v190700p.pdf)

</details>

**0468.** 若有人想把兩台 SMF 的百分比直接等權平均，可以用來重算這個切片 KPI 嗎？

<details><summary>看答案</summary>

**答案**　依規格口徑加總成功及嘗試，再求比值。

**詳解**　兩台 SMF 嘗試量不同，各台百分比的等權平均不一定等於以所有嘗試加權的切片 KPI。

**出處**　[3GPP TS 28.554 §6.2.5](https://www.etsi.org/deliver/etsi_ts/128500_128599/128554/19.07.00_60/ts_128554v190700p.pdf)

</details>

**0469.** 若切片另從 RAN 取得 DRB 建立成功次數，能否加進本題的成功分子？

<details><summary>看答案</summary>

**答案**　應維持本題的 PDU Session 建立事件口徑。

**詳解**　DRB 建立和 SMF 的 PDU Session 建立屬不同對象與事件，不能併入同一分子。

**出處**　[3GPP TS 28.554 §6.2.5](https://www.etsi.org/deliver/etsi_ts/128500_128599/128554/19.07.00_60/ts_128554v190700p.pdf) · [3GPP TS 28.554 §6.2.4](https://www.etsi.org/deliver/etsi_ts/128500_128599/128554/19.07.00_60/ts_128554v190700p.pdf)

</details>

**0470.** 若某時窗兩台 SMF 都沒有嘗試，該窗的成功率如何呈現？

<details><summary>看答案</summary>

**答案**　註記沒有嘗試，依資料規則以不適用或空值呈現。

**詳解**　分母為 0 時比值未定義。標為 0% 或 100% 都會誤解為已有成功率觀測。

**出處**　[3GPP TS 28.554 §6.2.5](https://www.etsi.org/deliver/etsi_ts/128500_128599/128554/19.07.00_60/ts_128554v190700p.pdf)

</details>

**情境 096｜港區物流切片**

同一 S-NSSAI、同一時窗。SMF 甲處理 150 次建立嘗試，成功 142 次。SMF 乙處理 50 次，成功 45 次。數量為同口徑觀測。

**0476.** ［計算題］SMF 甲嘗試 150 次、成功 142 次，乙嘗試 50 次、成功 45 次。切片的 PDU Session 建立成功百分比為何？（四捨五入至小數第 2 位）

<details><summary>看答案</summary>

**答案**　93.50%。

**詳解**　同一切片先跨對應 SMF 加總，再以成功除以嘗試。 算式 `(142 + 45) ÷ (150 + 50) × 100 = 93.50`%。

**出處**　[3GPP TS 28.554 §6.2.5](https://www.etsi.org/deliver/etsi_ts/128500_128599/128554/19.07.00_60/ts_128554v190700p.pdf)

</details>

**0477.** ［計算題］兩台 SMF 分別有嘗試／成功 150／142 次與 50／45 次。若每次嘗試都已確定成功或未成功，未成功共有幾次？

<details><summary>看答案</summary>

**答案**　13 次。

**詳解**　算式 `(150−142) + (50−45) = 13` 次。

**出處**　[3GPP TS 28.554 §6.2.5](https://www.etsi.org/deliver/etsi_ts/128500_128599/128554/19.07.00_60/ts_128554v190700p.pdf)

</details>

**0478.** 若有人想把兩台 SMF 的百分比直接等權平均，可以用來重算這個切片 KPI 嗎？

<details><summary>看答案</summary>

**答案**　依規格口徑加總成功及嘗試，再求比值。

**詳解**　兩台 SMF 嘗試量不同，各台百分比的等權平均不一定等於以所有嘗試加權的切片 KPI。

**出處**　[3GPP TS 28.554 §6.2.5](https://www.etsi.org/deliver/etsi_ts/128500_128599/128554/19.07.00_60/ts_128554v190700p.pdf)

</details>

**0479.** 若切片另從 RAN 取得 DRB 建立成功次數，能否加進本題的成功分子？

<details><summary>看答案</summary>

**答案**　應維持本題的 PDU Session 建立事件口徑。

**詳解**　DRB 建立和 SMF 的 PDU Session 建立屬不同對象與事件，不能併入同一分子。

**出處**　[3GPP TS 28.554 §6.2.5](https://www.etsi.org/deliver/etsi_ts/128500_128599/128554/19.07.00_60/ts_128554v190700p.pdf) · [3GPP TS 28.554 §6.2.4](https://www.etsi.org/deliver/etsi_ts/128500_128599/128554/19.07.00_60/ts_128554v190700p.pdf)

</details>

**0480.** 若某時窗兩台 SMF 都沒有嘗試，該窗的成功率如何呈現？

<details><summary>看答案</summary>

**答案**　註記沒有嘗試，依資料規則以不適用或空值呈現。

**詳解**　分母為 0 時比值未定義。標為 0% 或 100% 都會誤解為已有成功率觀測。

**出處**　[3GPP TS 28.554 §6.2.5](https://www.etsi.org/deliver/etsi_ts/128500_128599/128554/19.07.00_60/ts_128554v190700p.pdf)

</details>

**情境 097｜醫療 IoT 切片**

同一 S-NSSAI、同一時窗。SMF 甲處理 100 次建立嘗試，成功 98 次。SMF 乙處理 60 次，成功 53 次。數量為同口徑觀測。

**0481.** ［計算題］SMF 甲嘗試 100 次、成功 98 次，乙嘗試 60 次、成功 53 次。切片的 PDU Session 建立成功百分比為何？（四捨五入至小數第 2 位）

<details><summary>看答案</summary>

**答案**　94.38%。

**詳解**　同一切片先跨對應 SMF 加總，再以成功除以嘗試。 算式 `(98 + 53) ÷ (100 + 60) × 100 ≈ 94.38`%。

**出處**　[3GPP TS 28.554 §6.2.5](https://www.etsi.org/deliver/etsi_ts/128500_128599/128554/19.07.00_60/ts_128554v190700p.pdf)

</details>

**0482.** ［計算題］兩台 SMF 分別有嘗試／成功 100／98 次與 60／53 次。若每次嘗試都已確定成功或未成功，未成功共有幾次？

<details><summary>看答案</summary>

**答案**　9 次。

**詳解**　算式 `(100−98) + (60−53) = 9` 次。

**出處**　[3GPP TS 28.554 §6.2.5](https://www.etsi.org/deliver/etsi_ts/128500_128599/128554/19.07.00_60/ts_128554v190700p.pdf)

</details>

**情境 098｜園區設備切片**

同一 S-NSSAI、同一時窗。SMF 甲處理 30 次建立嘗試，成功 29 次。SMF 乙處理 170 次，成功 155 次。數量為同口徑觀測。

**0486.** ［計算題］SMF 甲嘗試 30 次、成功 29 次，乙嘗試 170 次、成功 155 次。切片的 PDU Session 建立成功百分比為何？（四捨五入至小數第 2 位）

<details><summary>看答案</summary>

**答案**　92.00%。

**詳解**　同一切片先跨對應 SMF 加總，再以成功除以嘗試。 算式 `(29 + 155) ÷ (30 + 170) × 100 = 92.00`%。

**出處**　[3GPP TS 28.554 §6.2.5](https://www.etsi.org/deliver/etsi_ts/128500_128599/128554/19.07.00_60/ts_128554v190700p.pdf)

</details>

**0487.** ［計算題］兩台 SMF 分別有嘗試／成功 30／29 次與 170／155 次。若每次嘗試都已確定成功或未成功，未成功共有幾次？

<details><summary>看答案</summary>

**答案**　16 次。

**詳解**　算式 `(30−29) + (170−155) = 16` 次。

**出處**　[3GPP TS 28.554 §6.2.5](https://www.etsi.org/deliver/etsi_ts/128500_128599/128554/19.07.00_60/ts_128554v190700p.pdf)

</details>

**情境 099｜展演上傳切片**

同一 S-NSSAI、同一時窗。SMF 甲處理 120 次建立嘗試，成功 112 次。SMF 乙處理 180 次，成功 167 次。數量為同口徑觀測。

**0491.** ［計算題］SMF 甲嘗試 120 次、成功 112 次，乙嘗試 180 次、成功 167 次。切片的 PDU Session 建立成功百分比為何？（四捨五入至小數第 2 位）

<details><summary>看答案</summary>

**答案**　93.00%。

**詳解**　同一切片先跨對應 SMF 加總，再以成功除以嘗試。 算式 `(112 + 167) ÷ (120 + 180) × 100 = 93.00`%。

**出處**　[3GPP TS 28.554 §6.2.5](https://www.etsi.org/deliver/etsi_ts/128500_128599/128554/19.07.00_60/ts_128554v190700p.pdf)

</details>

**0492.** ［計算題］兩台 SMF 分別有嘗試／成功 120／112 次與 180／167 次。若每次嘗試都已確定成功或未成功，未成功共有幾次？

<details><summary>看答案</summary>

**答案**　21 次。

**詳解**　算式 `(120−112) + (180−167) = 21` 次。

**出處**　[3GPP TS 28.554 §6.2.5](https://www.etsi.org/deliver/etsi_ts/128500_128599/128554/19.07.00_60/ts_128554v190700p.pdf)

</details>

### 2. 部分 DRB 可接取性與排除原因

**情境 100｜小區 RRC 和 DRB 監測**

同一 NRCellCU 的某 5QI，RRC 全原因嘗試／成功 200／188 次，其中 mo-Signalling 40／38 次。NG 信令連線已排除 mo-Signalling，嘗試／成功 150／145 次。該 5QI 的 DRB 建立嘗試／成功 100／96 次。

**0496.** ［計算題］RRC 嘗試／成功 200／188 次，mo-Signalling 佔 40／38 次。排除該原因後，RRC 成功百分比是多少？（四捨五入至小數第 2 位）

<details><summary>看答案</summary>

**答案**　93.75%。

**詳解**　從成功和嘗試各扣除相應原因的計數。 算式 `(188−38) ÷ (200−40) × 100 = 93.75`%。

**出處**　[3GPP TS 28.554 §6.2.4](https://www.etsi.org/deliver/etsi_ts/128500_128599/128554/19.07.00_60/ts_128554v190700p.pdf)

</details>

**0497.** ［計算題］RRC 全原因嘗試／成功 200／188 次，其中 mo-Signalling 40／38 次。已排除該原因的 NG 嘗試／成功 150／145 次，該 5QI 的 DRB 嘗試／成功 100／96 次。求 Partial DRB Accessibility。（四捨五入至小數第 2 位）

<details><summary>看答案</summary>

**答案**　87.00%。

**詳解**　將三個同口徑階段的比值相乘，最後轉成百分比。 算式 `((188−38) ÷ (200−40)) × (145 ÷ 150) × (96 ÷ 100) × 100 = 87.00`%。

**出處**　[3GPP TS 28.554 §6.2.4](https://www.etsi.org/deliver/etsi_ts/128500_128599/128554/19.07.00_60/ts_128554v190700p.pdf)

</details>

**0498.** 此處哪兩個連線建立階段需要排除 mo-Signalling？

<details><summary>看答案</summary>

**答案**　RRC 連線建立及 NG 信令連線建立。

**詳解**　TS 28.554 的此 KPI 按適用原因加總。題設已提供排除後的 NG 計數，無需重扣。

**出處**　[3GPP TS 28.554 §6.2.4](https://www.etsi.org/deliver/etsi_ts/128500_128599/128554/19.07.00_60/ts_128554v190700p.pdf)

</details>

**0499.** 如果只用最後一段 DRB 成功次數除以其嘗試次數，這是三階段 KPI 嗎？

<details><summary>看答案</summary>

**答案**　這只表示題設的 DRB 建立階段比值。

**詳解**　部分 DRB 可接取性會把前兩個連線建立階段一起納入，單一比值少了前置階段。

**出處**　[3GPP TS 28.554 §6.2.4](https://www.etsi.org/deliver/etsi_ts/128500_128599/128554/19.07.00_60/ts_128554v190700p.pdf)

</details>

**0500.** 從只查一個 5QI 改成查 S-NSSAI，報表應同時變更哪個階段的篩選？

<details><summary>看答案</summary>

**答案**　DRB 建立計數須換成對應 S-NSSAI 的嘗試與成功計數。

**詳解**　規格分別定義按 5QI 及按 S-NSSAI 的部分 DRB KPI。分子、分母在對應維度維持一致。

**出處**　[3GPP TS 28.554 §6.2.4](https://www.etsi.org/deliver/etsi_ts/128500_128599/128554/19.07.00_60/ts_128554v190700p.pdf)

</details>

**情境 101｜展館連線階段統計**

同一 NRCellCU 的某 5QI，RRC 全原因嘗試／成功 180／172 次，其中 mo-Signalling 30／29 次。NG 信令連線已排除 mo-Signalling，嘗試／成功 140／132 次。該 5QI 的 DRB 建立嘗試／成功 120／115 次。

**0501.** ［計算題］RRC 嘗試／成功 180／172 次，mo-Signalling 佔 30／29 次。排除該原因後，RRC 成功百分比是多少？（四捨五入至小數第 2 位）

<details><summary>看答案</summary>

**答案**　95.33%。

**詳解**　從成功和嘗試各扣除相應原因的計數。 算式 `(172−29) ÷ (180−30) × 100 ≈ 95.33`%。

**出處**　[3GPP TS 28.554 §6.2.4](https://www.etsi.org/deliver/etsi_ts/128500_128599/128554/19.07.00_60/ts_128554v190700p.pdf)

</details>

**0502.** ［計算題］RRC 全原因嘗試／成功 180／172 次，其中 mo-Signalling 30／29 次。已排除該原因的 NG 嘗試／成功 140／132 次，該 5QI 的 DRB 嘗試／成功 120／115 次。求 Partial DRB Accessibility。（四捨五入至小數第 2 位）

<details><summary>看答案</summary>

**答案**　86.14%。

**詳解**　將三個同口徑階段的比值相乘，最後轉成百分比。 算式 `((172−29) ÷ (180−30)) × (132 ÷ 140) × (115 ÷ 120) × 100 ≈ 86.14`%。

**出處**　[3GPP TS 28.554 §6.2.4](https://www.etsi.org/deliver/etsi_ts/128500_128599/128554/19.07.00_60/ts_128554v190700p.pdf)

</details>

**0503.** 此處哪兩個連線建立階段需要排除 mo-Signalling？

<details><summary>看答案</summary>

**答案**　RRC 連線建立及 NG 信令連線建立。

**詳解**　TS 28.554 的此 KPI 按適用原因加總。題設已提供排除後的 NG 計數，無需重扣。

**出處**　[3GPP TS 28.554 §6.2.4](https://www.etsi.org/deliver/etsi_ts/128500_128599/128554/19.07.00_60/ts_128554v190700p.pdf)

</details>

**0504.** 如果只用最後一段 DRB 成功次數除以其嘗試次數，這是三階段 KPI 嗎？

<details><summary>看答案</summary>

**答案**　這只表示題設的 DRB 建立階段比值。

**詳解**　部分 DRB 可接取性會把前兩個連線建立階段一起納入，單一比值少了前置階段。

**出處**　[3GPP TS 28.554 §6.2.4](https://www.etsi.org/deliver/etsi_ts/128500_128599/128554/19.07.00_60/ts_128554v190700p.pdf)

</details>

**0505.** 從只查一個 5QI 改成查 S-NSSAI，報表應同時變更哪個階段的篩選？

<details><summary>看答案</summary>

**答案**　DRB 建立計數須換成對應 S-NSSAI 的嘗試與成功計數。

**詳解**　規格分別定義按 5QI 及按 S-NSSAI 的部分 DRB KPI。分子、分母在對應維度維持一致。

**出處**　[3GPP TS 28.554 §6.2.4](https://www.etsi.org/deliver/etsi_ts/128500_128599/128554/19.07.00_60/ts_128554v190700p.pdf)

</details>

**情境 102｜園區小區承載觀測**

同一 NRCellCU 的某 5QI，RRC 全原因嘗試／成功 240／227 次，其中 mo-Signalling 20／19 次。NG 信令連線已排除 mo-Signalling，嘗試／成功 210／200 次。該 5QI 的 DRB 建立嘗試／成功 160／152 次。

**0506.** ［計算題］RRC 嘗試／成功 240／227 次，mo-Signalling 佔 20／19 次。排除該原因後，RRC 成功百分比是多少？（四捨五入至小數第 2 位）

<details><summary>看答案</summary>

**答案**　94.55%。

**詳解**　從成功和嘗試各扣除相應原因的計數。 算式 `(227−19) ÷ (240−20) × 100 ≈ 94.55`%。

**出處**　[3GPP TS 28.554 §6.2.4](https://www.etsi.org/deliver/etsi_ts/128500_128599/128554/19.07.00_60/ts_128554v190700p.pdf)

</details>

**0507.** ［計算題］RRC 全原因嘗試／成功 240／227 次，其中 mo-Signalling 20／19 次。已排除該原因的 NG 嘗試／成功 210／200 次，該 5QI 的 DRB 嘗試／成功 160／152 次。求 Partial DRB Accessibility。（四捨五入至小數第 2 位）

<details><summary>看答案</summary>

**答案**　85.54%。

**詳解**　將三個同口徑階段的比值相乘，最後轉成百分比。 算式 `((227−19) ÷ (240−20)) × (200 ÷ 210) × (152 ÷ 160) × 100 ≈ 85.54`%。

**出處**　[3GPP TS 28.554 §6.2.4](https://www.etsi.org/deliver/etsi_ts/128500_128599/128554/19.07.00_60/ts_128554v190700p.pdf)

</details>

**情境 103｜港區承載階段驗收**

同一 NRCellCU 的某 5QI，RRC 全原因嘗試／成功 160／147 次，其中 mo-Signalling 25／24 次。NG 信令連線已排除 mo-Signalling，嘗試／成功 130／124 次。該 5QI 的 DRB 建立嘗試／成功 95／91 次。

**0511.** ［計算題］RRC 嘗試／成功 160／147 次，mo-Signalling 佔 25／24 次。排除該原因後，RRC 成功百分比是多少？（四捨五入至小數第 2 位）

<details><summary>看答案</summary>

**答案**　91.11%。

**詳解**　從成功和嘗試各扣除相應原因的計數。 算式 `(147−24) ÷ (160−25) × 100 ≈ 91.11`%。

**出處**　[3GPP TS 28.554 §6.2.4](https://www.etsi.org/deliver/etsi_ts/128500_128599/128554/19.07.00_60/ts_128554v190700p.pdf)

</details>

**0512.** ［計算題］RRC 全原因嘗試／成功 160／147 次，其中 mo-Signalling 25／24 次。已排除該原因的 NG 嘗試／成功 130／124 次，該 5QI 的 DRB 嘗試／成功 95／91 次。求 Partial DRB Accessibility。（四捨五入至小數第 2 位）

<details><summary>看答案</summary>

**答案**　83.25%。

**詳解**　將三個同口徑階段的比值相乘，最後轉成百分比。 算式 `((147−24) ÷ (160−25)) × (124 ÷ 130) × (91 ÷ 95) × 100 ≈ 83.25`%。

**出處**　[3GPP TS 28.554 §6.2.4](https://www.etsi.org/deliver/etsi_ts/128500_128599/128554/19.07.00_60/ts_128554v190700p.pdf)

</details>

**情境 105｜校園語音承載建立試驗**

同一 NRCellCU 的某 5QI，RRC 全原因嘗試／成功 100／96 次，其中 mo-Signalling 15／15 次。NG 信令連線已排除 mo-Signalling，嘗試／成功 80／77 次。該 5QI 的 DRB 建立嘗試／成功 75／73 次。

**0521.** ［計算題］RRC 嘗試／成功 100／96 次，mo-Signalling 佔 15／15 次。排除該原因後，RRC 成功百分比是多少？（四捨五入至小數第 2 位）

<details><summary>看答案</summary>

**答案**　95.29%。

**詳解**　從成功和嘗試各扣除相應原因的計數。 算式 `(96−15) ÷ (100−15) × 100 ≈ 95.29`%。

**出處**　[3GPP TS 28.554 §6.2.4](https://www.etsi.org/deliver/etsi_ts/128500_128599/128554/19.07.00_60/ts_128554v190700p.pdf)

</details>

**0522.** ［計算題］RRC 全原因嘗試／成功 100／96 次，其中 mo-Signalling 15／15 次。已排除該原因的 NG 嘗試／成功 80／77 次，該 5QI 的 DRB 嘗試／成功 75／73 次。求 Partial DRB Accessibility。（四捨五入至小數第 2 位）

<details><summary>看答案</summary>

**答案**　89.27%。

**詳解**　將三個同口徑階段的比值相乘，最後轉成百分比。 算式 `((96−15) ÷ (100−15)) × (77 ÷ 80) × (73 ÷ 75) × 100 ≈ 89.27`%。

**出處**　[3GPP TS 28.554 §6.2.4](https://www.etsi.org/deliver/etsi_ts/128500_128599/128554/19.07.00_60/ts_128554v190700p.pdf)

</details>

### 3. DRB Retainability 與活動期間

**情境 106｜行動承載活動釋放監測**

同一統計維度有異常釋放 22 次，其中 4 次在釋放時未處於活動狀態。另有正常釋放 11 次。題設符合規格口徑的累計資料會話時間為 9000 s。

**0526.** ［計算題］異常釋放共 22 次，其中 4 次未活動。符合「異常且活動」的釋放共有幾次？

<details><summary>看答案</summary>

**答案**　18 次。

**詳解**　算式 `22−4 = 18` 次。

**出處**　[3GPP TS 28.554 §6.5.2.1](https://www.etsi.org/deliver/etsi_ts/128500_128599/128554/19.07.00_60/ts_128554v190700p.pdf)

</details>

**0527.** ［計算題］異常釋放 22 次，其中未活動 4 次，資料會話時間 9000 s。依 DRB Retainability 的原始比值求每秒活動異常釋放次數。（四捨五入至小數第 6 位）

<details><summary>看答案</summary>

**答案**　0.002000 次/s。

**詳解**　算式 `(22−4) ÷ 9000 = 0.002000` 次/s。

**出處**　[3GPP TS 28.554 §6.5.2.1](https://www.etsi.org/deliver/etsi_ts/128500_128599/128554/19.07.00_60/ts_128554v190700p.pdf)

</details>

**0528.** 正常釋放 11 次要放進這項 KPI 的活動異常釋放分子嗎？

<details><summary>看答案</summary>

**答案**　正常釋放不進入該分子。

**詳解**　分子需同時符合異常釋放與活動狀態兩個條件。資料會話時間是獨立的分母。

**出處**　[3GPP TS 28.554 §6.5.2.1](https://www.etsi.org/deliver/etsi_ts/128500_128599/128554/19.07.00_60/ts_128554v190700p.pdf)

</details>

**0529.** 可否把這個每秒值當成「每百通掉話數」？

<details><summary>看答案</summary>

**答案**　兩者分母和量測對象要分別標註。

**詳解**　本題分母是資料會話秒數，量測對象是 DRB。每百通涉及呼叫樣本，還要定義哪些通話與掉話事件入列。

**出處**　[3GPP TS 28.554 §6.5.2.1](https://www.etsi.org/deliver/etsi_ts/128500_128599/128554/19.07.00_60/ts_128554v190700p.pdf)

</details>

**0530.** 對突發流量 DRB，判定釋放前是否活動要查什麼？

<details><summary>看答案</summary>

**答案**　查釋放前最後 100 ms 內是否有上行或下行資料傳送。

**詳解**　TS 28.554 的擴充定義按流量型態處理。突發流量與連續流量的活動條件應分開。

**出處**　[3GPP TS 28.554 §6.5.2.2](https://www.etsi.org/deliver/etsi_ts/128500_128599/128554/19.07.00_60/ts_128554v190700p.pdf)

</details>

**情境 107｜交通沿線 DRB 診斷**

同一統計維度有異常釋放 31 次，其中 8 次在釋放時未處於活動狀態。另有正常釋放 13 次。題設符合規格口徑的累計資料會話時間為 13800 s。

**0531.** ［計算題］異常釋放共 31 次，其中 8 次未活動。符合「異常且活動」的釋放共有幾次？

<details><summary>看答案</summary>

**答案**　23 次。

**詳解**　算式 `31−8 = 23` 次。

**出處**　[3GPP TS 28.554 §6.5.2.1](https://www.etsi.org/deliver/etsi_ts/128500_128599/128554/19.07.00_60/ts_128554v190700p.pdf)

</details>

**0532.** ［計算題］異常釋放 31 次，其中未活動 8 次，資料會話時間 13800 s。依 DRB Retainability 的原始比值求每秒活動異常釋放次數。（四捨五入至小數第 6 位）

<details><summary>看答案</summary>

**答案**　0.001667 次/s。

**詳解**　算式 `(31−8) ÷ 13800 ≈ 0.001667` 次/s。

**出處**　[3GPP TS 28.554 §6.5.2.1](https://www.etsi.org/deliver/etsi_ts/128500_128599/128554/19.07.00_60/ts_128554v190700p.pdf)

</details>

**0533.** 正常釋放 13 次要放進這項 KPI 的活動異常釋放分子嗎？

<details><summary>看答案</summary>

**答案**　正常釋放不進入該分子。

**詳解**　分子需同時符合異常釋放與活動狀態兩個條件。資料會話時間是獨立的分母。

**出處**　[3GPP TS 28.554 §6.5.2.1](https://www.etsi.org/deliver/etsi_ts/128500_128599/128554/19.07.00_60/ts_128554v190700p.pdf)

</details>

**0534.** 可否把這個每秒值當成「每百通掉話數」？

<details><summary>看答案</summary>

**答案**　兩者分母和量測對象要分別標註。

**詳解**　本題分母是資料會話秒數，量測對象是 DRB。每百通涉及呼叫樣本，還要定義哪些通話與掉話事件入列。

**出處**　[3GPP TS 28.554 §6.5.2.1](https://www.etsi.org/deliver/etsi_ts/128500_128599/128554/19.07.00_60/ts_128554v190700p.pdf)

</details>

**0535.** 對突發流量 DRB，判定釋放前是否活動要查什麼？

<details><summary>看答案</summary>

**答案**　查釋放前最後 100 ms 內是否有上行或下行資料傳送。

**詳解**　TS 28.554 的擴充定義按流量型態處理。突發流量與連續流量的活動條件應分開。

**出處**　[3GPP TS 28.554 §6.5.2.2](https://www.etsi.org/deliver/etsi_ts/128500_128599/128554/19.07.00_60/ts_128554v190700p.pdf)

</details>

**情境 108｜企業切片承載保持**

同一統計維度有異常釋放 17 次，其中 3 次在釋放時未處於活動狀態。另有正常釋放 8 次。題設符合規格口徑的累計資料會話時間為 7000 s。

**0536.** ［計算題］異常釋放共 17 次，其中 3 次未活動。符合「異常且活動」的釋放共有幾次？

<details><summary>看答案</summary>

**答案**　14 次。

**詳解**　算式 `17−3 = 14` 次。

**出處**　[3GPP TS 28.554 §6.5.2.1](https://www.etsi.org/deliver/etsi_ts/128500_128599/128554/19.07.00_60/ts_128554v190700p.pdf)

</details>

**0537.** ［計算題］異常釋放 17 次，其中未活動 3 次，資料會話時間 7000 s。依 DRB Retainability 的原始比值求每秒活動異常釋放次數。（四捨五入至小數第 6 位）

<details><summary>看答案</summary>

**答案**　0.002000 次/s。

**詳解**　算式 `(17−3) ÷ 7000 = 0.002000` 次/s。

**出處**　[3GPP TS 28.554 §6.5.2.1](https://www.etsi.org/deliver/etsi_ts/128500_128599/128554/19.07.00_60/ts_128554v190700p.pdf)

</details>

**0538.** 正常釋放 8 次要放進這項 KPI 的活動異常釋放分子嗎？

<details><summary>看答案</summary>

**答案**　正常釋放不進入該分子。

**詳解**　分子需同時符合異常釋放與活動狀態兩個條件。資料會話時間是獨立的分母。

**出處**　[3GPP TS 28.554 §6.5.2.1](https://www.etsi.org/deliver/etsi_ts/128500_128599/128554/19.07.00_60/ts_128554v190700p.pdf)

</details>

**情境 109｜高樓小區活動釋放**

同一統計維度有異常釋放 40 次，其中 7 次在釋放時未處於活動狀態。另有正常釋放 15 次。題設符合規格口徑的累計資料會話時間為 16500 s。

**0541.** ［計算題］異常釋放共 40 次，其中 7 次未活動。符合「異常且活動」的釋放共有幾次？

<details><summary>看答案</summary>

**答案**　33 次。

**詳解**　算式 `40−7 = 33` 次。

**出處**　[3GPP TS 28.554 §6.5.2.1](https://www.etsi.org/deliver/etsi_ts/128500_128599/128554/19.07.00_60/ts_128554v190700p.pdf)

</details>

**0542.** ［計算題］異常釋放 40 次，其中未活動 7 次，資料會話時間 16500 s。依 DRB Retainability 的原始比值求每秒活動異常釋放次數。（四捨五入至小數第 6 位）

<details><summary>看答案</summary>

**答案**　0.002000 次/s。

**詳解**　算式 `(40−7) ÷ 16500 = 0.002000` 次/s。

**出處**　[3GPP TS 28.554 §6.5.2.1](https://www.etsi.org/deliver/etsi_ts/128500_128599/128554/19.07.00_60/ts_128554v190700p.pdf)

</details>

**0543.** 正常釋放 15 次要放進這項 KPI 的活動異常釋放分子嗎？

<details><summary>看答案</summary>

**答案**　正常釋放不進入該分子。

**詳解**　分子需同時符合異常釋放與活動狀態兩個條件。資料會話時間是獨立的分母。

**出處**　[3GPP TS 28.554 §6.5.2.1](https://www.etsi.org/deliver/etsi_ts/128500_128599/128554/19.07.00_60/ts_128554v190700p.pdf)

</details>

### 4. 業者語音掉話口徑與樣本篩選

**情境 112｜園區語音尖峰**

本題採業者自訂通話掉話率＝已接通且非預期中斷的通話數 ÷ 已接通通話數 × 100%。先觀測已接通 820 通，其中非預期中斷 16 通。如另外排除受控測試，已接通樣本中有 50 通受控測試，其中 3 通非預期中斷。

**0556.** ［計算題］依題設，已接通 820 通，其中 16 通非預期中斷，若保留全樣本，掉話百分比是多少？（四捨五入至小數第 2 位）

<details><summary>看答案</summary>

**答案**　1.95%。

**詳解**　算式 `16 ÷ 820 × 100 ≈ 1.95`%。

**出處**　[3GPP TS 28.554 §6.5.2.1](https://www.etsi.org/deliver/etsi_ts/128500_128599/128554/19.07.00_60/ts_128554v190700p.pdf) · [ITU-T E.800，服務品質術語](https://www.itu.int/dms_pubrec/itu-t/rec/e/T-REC-E.800-200809-I%21%21SUM-HTM-E.htm)

</details>

**0557.** ［計算題］已接通 820 通、非預期中斷 16 通。依新報表口徑，排除 50 通已接通的受控測試，其中 3 通非預期中斷。重算掉話百分比。（四捨五入至小數第 2 位）

<details><summary>看答案</summary>

**答案**　1.69%。

**詳解**　本題是業者自訂口徑。排除同一個子樣本時，分子和分母各扣除符合條件的計數。 算式 `(16−3) ÷ (820−50) × 100 ≈ 1.69`%。

**出處**　[3GPP TS 28.554 §6.5.2.1](https://www.etsi.org/deliver/etsi_ts/128500_128599/128554/19.07.00_60/ts_128554v190700p.pdf) · [ITU-T E.800，服務品質術語](https://www.itu.int/dms_pubrec/itu-t/rec/e/T-REC-E.800-200809-I%21%21SUM-HTM-E.htm)

</details>

**0558.** 撥號後從未接通的呼叫應計入本題掉話率嗎？

<details><summary>看答案</summary>

**答案**　不納入這項 KPI 的分子或分母。

**詳解**　本題只以已接通通話為母體。未接通事件應交由相應的建立或接通指標追蹤。

**出處**　[3GPP TS 28.554 §6.2.5](https://www.etsi.org/deliver/etsi_ts/128500_128599/128554/19.07.00_60/ts_128554v190700p.pdf) · [3GPP TS 28.554 §6.5.2.1](https://www.etsi.org/deliver/etsi_ts/128500_128599/128554/19.07.00_60/ts_128554v190700p.pdf)

</details>

**0559.** 若使用者正常掛斷，為什麼不能依「釋放」一詞直接計為掉話？

<details><summary>看答案</summary>

**答案**　題設分子只計非預期中斷。

**詳解**　呼叫已釋放只表示通話結束。需依可核對的原因分類判定是否符合本報表的掉話定義。

**出處**　[3GPP TS 28.554 §6.5.2.1](https://www.etsi.org/deliver/etsi_ts/128500_128599/128554/19.07.00_60/ts_128554v190700p.pdf) · [ITU-T E.800，服務品質術語](https://www.itu.int/dms_pubrec/itu-t/rec/e/T-REC-E.800-200809-I%21%21SUM-HTM-E.htm)

</details>

**0560.** 把這個通話百分比與另一報表的 DRB 活動異常釋放／秒直接排序，有何問題？

<details><summary>看答案</summary>

**答案**　兩個指標的量測對象、單位與分母不一致。

**詳解**　通話掉話率每百通計數，3GPP DRB Retainability 以資料會話時間正規化。比較前須先選定一致口徑。

**出處**　[3GPP TS 28.554 §6.5.2.1](https://www.etsi.org/deliver/etsi_ts/128500_128599/128554/19.07.00_60/ts_128554v190700p.pdf)

</details>

**情境 113｜校園語音驗收**

本題採業者自訂通話掉話率＝已接通且非預期中斷的通話數 ÷ 已接通通話數 × 100%。先觀測已接通 420 通，其中非預期中斷 11 通。如另外排除受控測試，已接通樣本中有 20 通受控測試，其中 1 通非預期中斷。

**0561.** ［計算題］依題設，已接通 420 通，其中 11 通非預期中斷，若保留全樣本，掉話百分比是多少？（四捨五入至小數第 2 位）

<details><summary>看答案</summary>

**答案**　2.62%。

**詳解**　算式 `11 ÷ 420 × 100 ≈ 2.62`%。

**出處**　[3GPP TS 28.554 §6.5.2.1](https://www.etsi.org/deliver/etsi_ts/128500_128599/128554/19.07.00_60/ts_128554v190700p.pdf) · [ITU-T E.800，服務品質術語](https://www.itu.int/dms_pubrec/itu-t/rec/e/T-REC-E.800-200809-I%21%21SUM-HTM-E.htm)

</details>

**0562.** ［計算題］已接通 420 通、非預期中斷 11 通。依新報表口徑，排除 20 通已接通的受控測試，其中 1 通非預期中斷。重算掉話百分比。（四捨五入至小數第 2 位）

<details><summary>看答案</summary>

**答案**　2.50%。

**詳解**　本題是業者自訂口徑。排除同一個子樣本時，分子和分母各扣除符合條件的計數。 算式 `(11−1) ÷ (420−20) × 100 = 2.50`%。

**出處**　[3GPP TS 28.554 §6.5.2.1](https://www.etsi.org/deliver/etsi_ts/128500_128599/128554/19.07.00_60/ts_128554v190700p.pdf) · [ITU-T E.800，服務品質術語](https://www.itu.int/dms_pubrec/itu-t/rec/e/T-REC-E.800-200809-I%21%21SUM-HTM-E.htm)

</details>

**0563.** 撥號後從未接通的呼叫應計入本題掉話率嗎？

<details><summary>看答案</summary>

**答案**　不納入這項 KPI 的分子或分母。

**詳解**　本題只以已接通通話為母體。未接通事件應交由相應的建立或接通指標追蹤。

**出處**　[3GPP TS 28.554 §6.2.5](https://www.etsi.org/deliver/etsi_ts/128500_128599/128554/19.07.00_60/ts_128554v190700p.pdf) · [3GPP TS 28.554 §6.5.2.1](https://www.etsi.org/deliver/etsi_ts/128500_128599/128554/19.07.00_60/ts_128554v190700p.pdf)

</details>

**0564.** 若使用者正常掛斷，為什麼不能依「釋放」一詞直接計為掉話？

<details><summary>看答案</summary>

**答案**　題設分子只計非預期中斷。

**詳解**　呼叫已釋放只表示通話結束。需依可核對的原因分類判定是否符合本報表的掉話定義。

**出處**　[3GPP TS 28.554 §6.5.2.1](https://www.etsi.org/deliver/etsi_ts/128500_128599/128554/19.07.00_60/ts_128554v190700p.pdf) · [ITU-T E.800，服務品質術語](https://www.itu.int/dms_pubrec/itu-t/rec/e/T-REC-E.800-200809-I%21%21SUM-HTM-E.htm)

</details>

**0565.** 把這個通話百分比與另一報表的 DRB 活動異常釋放／秒直接排序，有何問題？

<details><summary>看答案</summary>

**答案**　兩個指標的量測對象、單位與分母不一致。

**詳解**　通話掉話率每百通計數，3GPP DRB Retainability 以資料會話時間正規化。比較前須先選定一致口徑。

**出處**　[3GPP TS 28.554 §6.5.2.1](https://www.etsi.org/deliver/etsi_ts/128500_128599/128554/19.07.00_60/ts_128554v190700p.pdf)

</details>

**情境 114｜站廳 VoNR 使用者回報**

本題採業者自訂通話掉話率＝已接通且非預期中斷的通話數 ÷ 已接通通話數 × 100%。先觀測已接通 650 通，其中非預期中斷 18 通。如另外排除受控測試，已接通樣本中有 25 通受控測試，其中 4 通非預期中斷。

**0566.** ［計算題］依題設，已接通 650 通，其中 18 通非預期中斷，若保留全樣本，掉話百分比是多少？（四捨五入至小數第 2 位）

<details><summary>看答案</summary>

**答案**　2.77%。

**詳解**　算式 `18 ÷ 650 × 100 ≈ 2.77`%。

**出處**　[3GPP TS 28.554 §6.5.2.1](https://www.etsi.org/deliver/etsi_ts/128500_128599/128554/19.07.00_60/ts_128554v190700p.pdf) · [ITU-T E.800，服務品質術語](https://www.itu.int/dms_pubrec/itu-t/rec/e/T-REC-E.800-200809-I%21%21SUM-HTM-E.htm)

</details>

**0567.** ［計算題］已接通 650 通、非預期中斷 18 通。依新報表口徑，排除 25 通已接通的受控測試，其中 4 通非預期中斷。重算掉話百分比。（四捨五入至小數第 2 位）

<details><summary>看答案</summary>

**答案**　2.24%。

**詳解**　本題是業者自訂口徑。排除同一個子樣本時，分子和分母各扣除符合條件的計數。 算式 `(18−4) ÷ (650−25) × 100 = 2.24`%。

**出處**　[3GPP TS 28.554 §6.5.2.1](https://www.etsi.org/deliver/etsi_ts/128500_128599/128554/19.07.00_60/ts_128554v190700p.pdf) · [ITU-T E.800，服務品質術語](https://www.itu.int/dms_pubrec/itu-t/rec/e/T-REC-E.800-200809-I%21%21SUM-HTM-E.htm)

</details>

**情境 115｜場館散場通話回顧**

本題採業者自訂通話掉話率＝已接通且非預期中斷的通話數 ÷ 已接通通話數 × 100%。先觀測已接通 1000 通，其中非預期中斷 21 通。如另外排除受控測試，已接通樣本中有 70 通受控測試，其中 5 通非預期中斷。

**0571.** ［計算題］依題設，已接通 1000 通，其中 21 通非預期中斷，若保留全樣本，掉話百分比是多少？（四捨五入至小數第 2 位）

<details><summary>看答案</summary>

**答案**　2.10%。

**詳解**　算式 `21 ÷ 1000 × 100 = 2.10`%。

**出處**　[3GPP TS 28.554 §6.5.2.1](https://www.etsi.org/deliver/etsi_ts/128500_128599/128554/19.07.00_60/ts_128554v190700p.pdf) · [ITU-T E.800，服務品質術語](https://www.itu.int/dms_pubrec/itu-t/rec/e/T-REC-E.800-200809-I%21%21SUM-HTM-E.htm)

</details>

**0572.** ［計算題］已接通 1000 通、非預期中斷 21 通。依新報表口徑，排除 70 通已接通的受控測試，其中 5 通非預期中斷。重算掉話百分比。（四捨五入至小數第 2 位）

<details><summary>看答案</summary>

**答案**　1.72%。

**詳解**　本題是業者自訂口徑。排除同一個子樣本時，分子和分母各扣除符合條件的計數。 算式 `(21−5) ÷ (1000−70) × 100 ≈ 1.72`%。

**出處**　[3GPP TS 28.554 §6.5.2.1](https://www.etsi.org/deliver/etsi_ts/128500_128599/128554/19.07.00_60/ts_128554v190700p.pdf) · [ITU-T E.800，服務品質術語](https://www.itu.int/dms_pubrec/itu-t/rec/e/T-REC-E.800-200809-I%21%21SUM-HTM-E.htm)

</details>

### 5. 小區 In-Service 時間與平均可用時間

**情境 116｜雙扇區園區網**

同一 gNB-CU 下恰有兩個作用中小區。共同觀測窗 1800 s，各小區的 In-Service 累計時間為 1740、1770 s，時間已裁切至窗口。

**0576.** ［計算題］兩個作用中小區的 In-Service 時間是 1740 s 和 1770 s，求 CellAvailAvgTimeCU 的原始算術平均，以秒表示。（四捨五入至小數第 2 位）

<details><summary>看答案</summary>

**答案**　1755.00 s。

**詳解**　算式 `(1740 + 1770) ÷ 2 = 1755.00` s。

**出處**　[3GPP TS 28.554 §6.11](https://www.etsi.org/deliver/etsi_ts/128500_128599/128554/19.07.00_60/ts_128554v190700p.pdf) · [3GPP TS 28.552 §5.1.4.1.1](https://www.etsi.org/deliver/etsi_ts/128500_128599/128552/19.06.00_60/ts_128552v190600p.pdf)

</details>

**0577.** ［計算題］共同觀測窗為 1800 s，兩個小區服務時間分別 1740、1770 s。若業者另計「兩小區合計服務秒數 ÷ 兩小區合計觀測秒數」的可用百分比，是多少？（四捨五入至小數第 2 位）

<details><summary>看答案</summary>

**答案**　97.50%。

**詳解**　本題另外定義正規化百分比。TS 28.554 的 CellAvailAvgTimeCU 本身以時間表示。 算式 `(1740 + 1770) ÷ (1800 × 2) × 100 = 97.50`%。

**出處**　[3GPP TS 28.554 §6.11](https://www.etsi.org/deliver/etsi_ts/128500_128599/128554/19.07.00_60/ts_128554v190700p.pdf) · [3GPP TS 28.552 §5.1.4.1.1](https://www.etsi.org/deliver/etsi_ts/128500_128599/128552/19.06.00_60/ts_128552v190600p.pdf)

</details>

**0578.** TS 28.554 的 CellAvailAvgTimeCU 分母是觀測秒數還是作用中的小區數？

<details><summary>看答案</summary>

**答案**　分母是作用中小區數，分子是小區服務時間的合計。

**詳解**　這個 KPI 報告每小區平均可用時間。若要得到另一定義的百分比則需有觀測秒數。

**出處**　[3GPP TS 28.554 §6.11](https://www.etsi.org/deliver/etsi_ts/128500_128599/128554/19.07.00_60/ts_128554v190700p.pdf)

</details>

**0579.** 某個 In-Service 時段跨到觀測窗以前，如何計入本窗服務時間？

<details><summary>看答案</summary>

**答案**　只累加與本觀測窗重疊的那一段。

**詳解**　TS 28.552 的小區服務時間來自狀態變更時戳，納入落在觀測範圍內的服務時間。

**出處**　[3GPP TS 28.552 §5.1.4.1.1](https://www.etsi.org/deliver/etsi_ts/128500_128599/128552/19.06.00_60/ts_128552v190600p.pdf)

</details>

**0580.** 若另一 gNB-CU 小區數量不同，可以把這兩個 CU 的平均秒數稱為「全網所有小區等權平均」嗎？

<details><summary>看答案</summary>

**答案**　需先確認是按 CU 等權還是按小區等權。

**詳解**　TS 28.554 的 RAN 可用時間另有按 CU 的聚合定義。直接平均 CU 值與逐小區平均在小區數不同時可以相異。

**出處**　[3GPP TS 28.554 §6.11](https://www.etsi.org/deliver/etsi_ts/128500_128599/128554/19.07.00_60/ts_128554v190700p.pdf)

</details>

**情境 117｜展演區兩小區彙整**

同一 gNB-CU 下恰有兩個作用中小區。共同觀測窗 3600 s，各小區的 In-Service 累計時間為 3480、3590 s，時間已裁切至窗口。

**0581.** ［計算題］兩個作用中小區的 In-Service 時間是 3480 s 和 3590 s，求 CellAvailAvgTimeCU 的原始算術平均，以秒表示。（四捨五入至小數第 2 位）

<details><summary>看答案</summary>

**答案**　3535.00 s。

**詳解**　算式 `(3480 + 3590) ÷ 2 = 3535.00` s。

**出處**　[3GPP TS 28.554 §6.11](https://www.etsi.org/deliver/etsi_ts/128500_128599/128554/19.07.00_60/ts_128554v190700p.pdf) · [3GPP TS 28.552 §5.1.4.1.1](https://www.etsi.org/deliver/etsi_ts/128500_128599/128552/19.06.00_60/ts_128552v190600p.pdf)

</details>

**0582.** ［計算題］共同觀測窗為 3600 s，兩個小區服務時間分別 3480、3590 s。若業者另計「兩小區合計服務秒數 ÷ 兩小區合計觀測秒數」的可用百分比，是多少？（四捨五入至小數第 2 位）

<details><summary>看答案</summary>

**答案**　98.19%。

**詳解**　本題另外定義正規化百分比。TS 28.554 的 CellAvailAvgTimeCU 本身以時間表示。 算式 `(3480 + 3590) ÷ (3600 × 2) × 100 ≈ 98.19`%。

**出處**　[3GPP TS 28.554 §6.11](https://www.etsi.org/deliver/etsi_ts/128500_128599/128554/19.07.00_60/ts_128554v190700p.pdf) · [3GPP TS 28.552 §5.1.4.1.1](https://www.etsi.org/deliver/etsi_ts/128500_128599/128552/19.06.00_60/ts_128552v190600p.pdf)

</details>

**0583.** TS 28.554 的 CellAvailAvgTimeCU 分母是觀測秒數還是作用中的小區數？

<details><summary>看答案</summary>

**答案**　分母是作用中小區數，分子是小區服務時間的合計。

**詳解**　這個 KPI 報告每小區平均可用時間。若要得到另一定義的百分比則需有觀測秒數。

**出處**　[3GPP TS 28.554 §6.11](https://www.etsi.org/deliver/etsi_ts/128500_128599/128554/19.07.00_60/ts_128554v190700p.pdf)

</details>

**0584.** 某個 In-Service 時段跨到觀測窗以前，如何計入本窗服務時間？

<details><summary>看答案</summary>

**答案**　只累加與本觀測窗重疊的那一段。

**詳解**　TS 28.552 的小區服務時間來自狀態變更時戳，納入落在觀測範圍內的服務時間。

**出處**　[3GPP TS 28.552 §5.1.4.1.1](https://www.etsi.org/deliver/etsi_ts/128500_128599/128552/19.06.00_60/ts_128552v190600p.pdf)

</details>

**0585.** 若另一 gNB-CU 小區數量不同，可以把這兩個 CU 的平均秒數稱為「全網所有小區等權平均」嗎？

<details><summary>看答案</summary>

**答案**　需先確認是按 CU 等權還是按小區等權。

**詳解**　TS 28.554 的 RAN 可用時間另有按 CU 的聚合定義。直接平均 CU 值與逐小區平均在小區數不同時可以相異。

**出處**　[3GPP TS 28.554 §6.11](https://www.etsi.org/deliver/etsi_ts/128500_128599/128554/19.07.00_60/ts_128554v190700p.pdf)

</details>

**情境 118｜港區無線值班**

同一 gNB-CU 下恰有兩個作用中小區。共同觀測窗 900 s，各小區的 In-Service 累計時間為 870、890 s，時間已裁切至窗口。

**0586.** ［計算題］兩個作用中小區的 In-Service 時間是 870 s 和 890 s，求 CellAvailAvgTimeCU 的原始算術平均，以秒表示。（四捨五入至小數第 2 位）

<details><summary>看答案</summary>

**答案**　880.00 s。

**詳解**　算式 `(870 + 890) ÷ 2 = 880.00` s。

**出處**　[3GPP TS 28.554 §6.11](https://www.etsi.org/deliver/etsi_ts/128500_128599/128554/19.07.00_60/ts_128554v190700p.pdf) · [3GPP TS 28.552 §5.1.4.1.1](https://www.etsi.org/deliver/etsi_ts/128500_128599/128552/19.06.00_60/ts_128552v190600p.pdf)

</details>

**0587.** ［計算題］共同觀測窗為 900 s，兩個小區服務時間分別 870、890 s。若業者另計「兩小區合計服務秒數 ÷ 兩小區合計觀測秒數」的可用百分比，是多少？（四捨五入至小數第 2 位）

<details><summary>看答案</summary>

**答案**　97.78%。

**詳解**　本題另外定義正規化百分比。TS 28.554 的 CellAvailAvgTimeCU 本身以時間表示。 算式 `(870 + 890) ÷ (900 × 2) × 100 ≈ 97.78`%。

**出處**　[3GPP TS 28.554 §6.11](https://www.etsi.org/deliver/etsi_ts/128500_128599/128554/19.07.00_60/ts_128554v190700p.pdf) · [3GPP TS 28.552 §5.1.4.1.1](https://www.etsi.org/deliver/etsi_ts/128500_128599/128552/19.06.00_60/ts_128552v190600p.pdf)

</details>

**情境 119｜車站月台雙小區**

同一 gNB-CU 下恰有兩個作用中小區。共同觀測窗 1200 s，各小區的 In-Service 累計時間為 1090、1180 s，時間已裁切至窗口。

**0591.** ［計算題］兩個作用中小區的 In-Service 時間是 1090 s 和 1180 s，求 CellAvailAvgTimeCU 的原始算術平均，以秒表示。（四捨五入至小數第 2 位）

<details><summary>看答案</summary>

**答案**　1135.00 s。

**詳解**　算式 `(1090 + 1180) ÷ 2 = 1135.00` s。

**出處**　[3GPP TS 28.554 §6.11](https://www.etsi.org/deliver/etsi_ts/128500_128599/128554/19.07.00_60/ts_128554v190700p.pdf) · [3GPP TS 28.552 §5.1.4.1.1](https://www.etsi.org/deliver/etsi_ts/128500_128599/128552/19.06.00_60/ts_128552v190600p.pdf)

</details>

**0592.** ［計算題］共同觀測窗為 1200 s，兩個小區服務時間分別 1090、1180 s。若業者另計「兩小區合計服務秒數 ÷ 兩小區合計觀測秒數」的可用百分比，是多少？（四捨五入至小數第 2 位）

<details><summary>看答案</summary>

**答案**　94.58%。

**詳解**　本題另外定義正規化百分比。TS 28.554 的 CellAvailAvgTimeCU 本身以時間表示。 算式 `(1090 + 1180) ÷ (1200 × 2) × 100 ≈ 94.58`%。

**出處**　[3GPP TS 28.554 §6.11](https://www.etsi.org/deliver/etsi_ts/128500_128599/128554/19.07.00_60/ts_128554v190700p.pdf) · [3GPP TS 28.552 §5.1.4.1.1](https://www.etsi.org/deliver/etsi_ts/128500_128599/128552/19.06.00_60/ts_128552v190600p.pdf)

</details>

### 6. 可用百分比、維護排除與比較

**情境 121｜回傳窗口維護彙整**

業者自訂可用百分比＝可用分鐘數 ÷ 納入分鐘數 × 100%。觀測 120 min，所有不可用共 16 min，其中 6 min 是預定維護。假設所有維護分鐘均不可用且沒有重疊扣除。

**0601.** ［計算題］總觀測 120 min、不可用 16 min，全部納入時的可用百分比為何？（四捨五入至小數第 2 位）

<details><summary>看答案</summary>

**答案**　86.67%。

**詳解**　算式 `(120−16) ÷ 120 × 100 ≈ 86.67`%。

**出處**　[3GPP TS 28.554 §6.11](https://www.etsi.org/deliver/etsi_ts/128500_128599/128554/19.07.00_60/ts_128554v190700p.pdf) · [3GPP TS 28.552 §5.1.4.1.1](https://www.etsi.org/deliver/etsi_ts/128500_128599/128552/19.06.00_60/ts_128552v190600p.pdf)

</details>

**0602.** ［計算題］總觀測 120 min、所有不可用 16 min，其中預定維護不可用 6 min。若完全排除這 6 min，剩餘時間的可用百分比為何？（四捨五入至小數第 2 位）

<details><summary>看答案</summary>

**答案**　91.23%。

**詳解**　排除的維護時間皆不可用，故可用分鐘數不變，觀測分母扣除維護分鐘。 算式 `(120−16) ÷ (120−6) × 100 ≈ 91.23`%。

**出處**　[3GPP TS 28.554 §6.11](https://www.etsi.org/deliver/etsi_ts/128500_128599/128554/19.07.00_60/ts_128554v190700p.pdf) · [3GPP TS 28.552 §5.1.4.1.1](https://www.etsi.org/deliver/etsi_ts/128500_128599/128552/19.06.00_60/ts_128552v190600p.pdf)

</details>

**0603.** 排除維護是不是所有 3GPP 可用率報表都必須採用的規則？

<details><summary>看答案</summary>

**答案**　維護排除依本題報表政策。

**詳解**　TS 28.552／28.554 的小區可用量測採其指定狀態與觀測時間。報表另行排除須寫清楚。

**出處**　[3GPP TS 28.554 §6.11](https://www.etsi.org/deliver/etsi_ts/128500_128599/128554/19.07.00_60/ts_128554v190700p.pdf) · [3GPP TS 28.552 §5.1.4.1.1](https://www.etsi.org/deliver/etsi_ts/128500_128599/128552/19.06.00_60/ts_128552v190600p.pdf)

</details>

**0604.** 甲報表含計畫維護，乙排除，能由兩者百分比差直接推論網路品質高低嗎？

<details><summary>看答案</summary>

**答案**　應先在同一觀測範圍和排除政策下重算。

**詳解**　不同排除改變分母和可能的不可用時間。百分比高低可能來自口徑差異。

**出處**　[3GPP TS 28.554 §6.11](https://www.etsi.org/deliver/etsi_ts/128500_128599/128554/19.07.00_60/ts_128554v190700p.pdf)

</details>

**0605.** 若改用應用端健康探測作為可用標準，能否直接沿用小區 In-Service 時間？

<details><summary>看答案</summary>

**答案**　應重新定義被觀測服務、健康條件和時間狀態。

**詳解**　小區服務狀態與應用可用性是不同層級。可將兩者時間線關聯查因，分別報告。

**出處**　[3GPP TS 28.554 §6.11](https://www.etsi.org/deliver/etsi_ts/128500_128599/128554/19.07.00_60/ts_128554v190700p.pdf) · [3GPP TS 28.552 §5.1.4.1.1](https://www.etsi.org/deliver/etsi_ts/128500_128599/128552/19.06.00_60/ts_128552v190600p.pdf)

</details>

**情境 123｜機場服務驗收窗口**

業者自訂可用百分比＝可用分鐘數 ÷ 納入分鐘數 × 100%。觀測 240 min，所有不可用共 18 min，其中 9 min 是預定維護。假設所有維護分鐘均不可用且沒有重疊扣除。

**0611.** ［計算題］總觀測 240 min、不可用 18 min，全部納入時的可用百分比為何？（四捨五入至小數第 2 位）

<details><summary>看答案</summary>

**答案**　92.50%。

**詳解**　算式 `(240−18) ÷ 240 × 100 = 92.50`%。

**出處**　[3GPP TS 28.554 §6.11](https://www.etsi.org/deliver/etsi_ts/128500_128599/128554/19.07.00_60/ts_128554v190700p.pdf) · [3GPP TS 28.552 §5.1.4.1.1](https://www.etsi.org/deliver/etsi_ts/128500_128599/128552/19.06.00_60/ts_128552v190600p.pdf)

</details>

**0612.** ［計算題］總觀測 240 min、所有不可用 18 min，其中預定維護不可用 9 min。若完全排除這 9 min，剩餘時間的可用百分比為何？（四捨五入至小數第 2 位）

<details><summary>看答案</summary>

**答案**　96.10%。

**詳解**　排除的維護時間皆不可用，故可用分鐘數不變，觀測分母扣除維護分鐘。 算式 `(240−18) ÷ (240−9) × 100 ≈ 96.10`%。

**出處**　[3GPP TS 28.554 §6.11](https://www.etsi.org/deliver/etsi_ts/128500_128599/128554/19.07.00_60/ts_128554v190700p.pdf) · [3GPP TS 28.552 §5.1.4.1.1](https://www.etsi.org/deliver/etsi_ts/128500_128599/128552/19.06.00_60/ts_128552v190600p.pdf)

</details>

**0613.** 排除維護是不是所有 3GPP 可用率報表都必須採用的規則？

<details><summary>看答案</summary>

**答案**　維護排除依本題報表政策。

**詳解**　TS 28.552／28.554 的小區可用量測採其指定狀態與觀測時間。報表另行排除須寫清楚。

**出處**　[3GPP TS 28.554 §6.11](https://www.etsi.org/deliver/etsi_ts/128500_128599/128554/19.07.00_60/ts_128554v190700p.pdf) · [3GPP TS 28.552 §5.1.4.1.1](https://www.etsi.org/deliver/etsi_ts/128500_128599/128552/19.06.00_60/ts_128552v190600p.pdf)

</details>

**0614.** 甲報表含計畫維護，乙排除，能由兩者百分比差直接推論網路品質高低嗎？

<details><summary>看答案</summary>

**答案**　應先在同一觀測範圍和排除政策下重算。

**詳解**　不同排除改變分母和可能的不可用時間。百分比高低可能來自口徑差異。

**出處**　[3GPP TS 28.554 §6.11](https://www.etsi.org/deliver/etsi_ts/128500_128599/128554/19.07.00_60/ts_128554v190700p.pdf)

</details>

**0615.** 若改用應用端健康探測作為可用標準，能否直接沿用小區 In-Service 時間？

<details><summary>看答案</summary>

**答案**　應重新定義被觀測服務、健康條件和時間狀態。

**詳解**　小區服務狀態與應用可用性是不同層級。可將兩者時間線關聯查因，分別報告。

**出處**　[3GPP TS 28.554 §6.11](https://www.etsi.org/deliver/etsi_ts/128500_128599/128554/19.07.00_60/ts_128554v190700p.pdf) · [3GPP TS 28.552 §5.1.4.1.1](https://www.etsi.org/deliver/etsi_ts/128500_128599/128552/19.06.00_60/ts_128552v190600p.pdf)

</details>

**情境 124｜沿海小區短時停讓**

業者自訂可用百分比＝可用分鐘數 ÷ 納入分鐘數 × 100%。觀測 90 min，所有不可用共 12 min，其中 4 min 是預定維護。假設所有維護分鐘均不可用且沒有重疊扣除。

**0616.** ［計算題］總觀測 90 min、不可用 12 min，全部納入時的可用百分比為何？（四捨五入至小數第 2 位）

<details><summary>看答案</summary>

**答案**　86.67%。

**詳解**　算式 `(90−12) ÷ 90 × 100 ≈ 86.67`%。

**出處**　[3GPP TS 28.554 §6.11](https://www.etsi.org/deliver/etsi_ts/128500_128599/128554/19.07.00_60/ts_128554v190700p.pdf) · [3GPP TS 28.552 §5.1.4.1.1](https://www.etsi.org/deliver/etsi_ts/128500_128599/128552/19.06.00_60/ts_128552v190600p.pdf)

</details>

**0617.** ［計算題］總觀測 90 min、所有不可用 12 min，其中預定維護不可用 4 min。若完全排除這 4 min，剩餘時間的可用百分比為何？（四捨五入至小數第 2 位）

<details><summary>看答案</summary>

**答案**　90.70%。

**詳解**　排除的維護時間皆不可用，故可用分鐘數不變，觀測分母扣除維護分鐘。 算式 `(90−12) ÷ (90−4) × 100 ≈ 90.70`%。

**出處**　[3GPP TS 28.554 §6.11](https://www.etsi.org/deliver/etsi_ts/128500_128599/128554/19.07.00_60/ts_128554v190700p.pdf) · [3GPP TS 28.552 §5.1.4.1.1](https://www.etsi.org/deliver/etsi_ts/128500_128599/128552/19.06.00_60/ts_128552v190600p.pdf)

</details>

**情境 125｜工廠園區夜間維護**

業者自訂可用百分比＝可用分鐘數 ÷ 納入分鐘數 × 100%。觀測 300 min，所有不可用共 22 min，其中 7 min 是預定維護。假設所有維護分鐘均不可用且沒有重疊扣除。

**0621.** ［計算題］總觀測 300 min、不可用 22 min，全部納入時的可用百分比為何？（四捨五入至小數第 2 位）

<details><summary>看答案</summary>

**答案**　92.67%。

**詳解**　算式 `(300−22) ÷ 300 × 100 ≈ 92.67`%。

**出處**　[3GPP TS 28.554 §6.11](https://www.etsi.org/deliver/etsi_ts/128500_128599/128554/19.07.00_60/ts_128554v190700p.pdf) · [3GPP TS 28.552 §5.1.4.1.1](https://www.etsi.org/deliver/etsi_ts/128500_128599/128552/19.06.00_60/ts_128552v190600p.pdf)

</details>

**0622.** ［計算題］總觀測 300 min、所有不可用 22 min，其中預定維護不可用 7 min。若完全排除這 7 min，剩餘時間的可用百分比為何？（四捨五入至小數第 2 位）

<details><summary>看答案</summary>

**答案**　94.88%。

**詳解**　排除的維護時間皆不可用，故可用分鐘數不變，觀測分母扣除維護分鐘。 算式 `(300−22) ÷ (300−7) × 100 ≈ 94.88`%。

**出處**　[3GPP TS 28.554 §6.11](https://www.etsi.org/deliver/etsi_ts/128500_128599/128554/19.07.00_60/ts_128554v190700p.pdf) · [3GPP TS 28.552 §5.1.4.1.1](https://www.etsi.org/deliver/etsi_ts/128500_128599/128552/19.06.00_60/ts_128552v190600p.pdf)

</details>

## 1.6.5 資源使用率：PRB、處理器、傳輸

### 1. 下行 PRB 使用率、剩餘與截位

**情境 126｜場館首輪進場**

同一個 NRCellDU 的下行觀測窗，已使用 7370 個完整 PRB 的累計計次，可用總數 8800 個。兩者為相同時段與計數口徑。

**0626.** ［計算題］使用 7370 個、可用 8800 個。依 TS 28.552 下行 PRB 使用率報告方式，求向下取整的百分比。

<details><summary>看答案</summary>

**答案**　83%。

**詳解**　先除以可用總數、乘 100，再向下取整。 floor 表示向下取整。 算式 `floor(7370 ÷ 8800 × 100) = 83`%。

**出處**　[3GPP TS 28.552 §5.1.1.2.1](https://www.etsi.org/deliver/etsi_ts/128500_128599/128552/19.06.00_60/ts_128552v190600p.pdf)

</details>

**0627.** ［計算題］可用 8800 個 PRB 的累計計次，已用 7370 個。尚未用的資源計次是多少？

<details><summary>看答案</summary>

**答案**　1430 個。

**詳解**　算式 `8800−7370 = 1430` 個。

**出處**　[3GPP TS 28.552 §5.1.1.2.1](https://www.etsi.org/deliver/etsi_ts/128500_128599/128552/19.06.00_60/ts_128552v190600p.pdf)

</details>

**0628.** 為何分母要用該時窗實際可用的累計 PRB 資源？

<details><summary>看答案</summary>

**答案**　使用量與可用量要對應同一批時頻資源。

**詳解**　只看載波標稱最大值會漏掉時間、頻寬、方向等可能差異。

**出處**　[3GPP TS 28.552 §5.1.1.2.1](https://www.etsi.org/deliver/etsi_ts/128500_128599/128552/19.06.00_60/ts_128552v190600p.pdf)

</details>

**0629.** 短時窗的 PRB 使用率偏高，能否當成整天都壅塞的結論？

<details><summary>看答案</summary>

**答案**　先查不同時段的樣本、吞吐量與排隊指標。

**詳解**　本數值描述該觀測窗的資源負載。其他時段的負載及品質需另讀。

**出處**　[3GPP TS 28.552 §5.1.1.2.1](https://www.etsi.org/deliver/etsi_ts/128500_128599/128552/19.06.00_60/ts_128552v190600p.pdf) · [3GPP TS 28.104，管理資料分析](https://www.etsi.org/deliver/etsi_ts/128100_128199/128104/18.06.00_60/ts_128104v180600p.pdf)

</details>

**0630.** 若同小區另有上行 PRB 使用率，可以沿用相同的下行分母嗎？

<details><summary>看答案</summary>

**答案**　上行須使用上行的可用 PRB 資源。

**詳解**　標準分別定義兩個方向的使用量與可用量，須按對應量測口徑取值。

**出處**　[3GPP TS 28.552 §5.1.1.2.1](https://www.etsi.org/deliver/etsi_ts/128500_128599/128552/19.06.00_60/ts_128552v190600p.pdf) · [3GPP TS 28.552 §5.1.1.2.2](https://www.etsi.org/deliver/etsi_ts/128500_128599/128552/19.06.00_60/ts_128552v190600p.pdf)

</details>

**情境 127｜園區下行備份**

同一個 NRCellDU 的下行觀測窗，已使用 4210 個完整 PRB 的累計計次，可用總數 6100 個。兩者為相同時段與計數口徑。

**0631.** ［計算題］使用 4210 個、可用 6100 個。依 TS 28.552 下行 PRB 使用率報告方式，求向下取整的百分比。

<details><summary>看答案</summary>

**答案**　69%。

**詳解**　先除以可用總數、乘 100，再向下取整。 floor 表示向下取整。 算式 `floor(4210 ÷ 6100 × 100) = 69`%。

**出處**　[3GPP TS 28.552 §5.1.1.2.1](https://www.etsi.org/deliver/etsi_ts/128500_128599/128552/19.06.00_60/ts_128552v190600p.pdf)

</details>

**0632.** ［計算題］可用 6100 個 PRB 的累計計次，已用 4210 個。尚未用的資源計次是多少？

<details><summary>看答案</summary>

**答案**　1890 個。

**詳解**　算式 `6100−4210 = 1890` 個。

**出處**　[3GPP TS 28.552 §5.1.1.2.1](https://www.etsi.org/deliver/etsi_ts/128500_128599/128552/19.06.00_60/ts_128552v190600p.pdf)

</details>

**0633.** 為何分母要用該時窗實際可用的累計 PRB 資源？

<details><summary>看答案</summary>

**答案**　使用量與可用量要對應同一批時頻資源。

**詳解**　只看載波標稱最大值會漏掉時間、頻寬、方向等可能差異。

**出處**　[3GPP TS 28.552 §5.1.1.2.1](https://www.etsi.org/deliver/etsi_ts/128500_128599/128552/19.06.00_60/ts_128552v190600p.pdf)

</details>

**0634.** 短時窗的 PRB 使用率偏高，能否當成整天都壅塞的結論？

<details><summary>看答案</summary>

**答案**　先查不同時段的樣本、吞吐量與排隊指標。

**詳解**　本數值描述該觀測窗的資源負載。其他時段的負載及品質需另讀。

**出處**　[3GPP TS 28.552 §5.1.1.2.1](https://www.etsi.org/deliver/etsi_ts/128500_128599/128552/19.06.00_60/ts_128552v190600p.pdf) · [3GPP TS 28.104，管理資料分析](https://www.etsi.org/deliver/etsi_ts/128100_128199/128104/18.06.00_60/ts_128104v180600p.pdf)

</details>

**0635.** 若同小區另有上行 PRB 使用率，可以沿用相同的下行分母嗎？

<details><summary>看答案</summary>

**答案**　上行須使用上行的可用 PRB 資源。

**詳解**　標準分別定義兩個方向的使用量與可用量，須按對應量測口徑取值。

**出處**　[3GPP TS 28.552 §5.1.1.2.1](https://www.etsi.org/deliver/etsi_ts/128500_128599/128552/19.06.00_60/ts_128552v190600p.pdf) · [3GPP TS 28.552 §5.1.1.2.2](https://www.etsi.org/deliver/etsi_ts/128500_128599/128552/19.06.00_60/ts_128552v190600p.pdf)

</details>

**情境 128｜車站尖峰小區**

同一個 NRCellDU 的下行觀測窗，已使用 8450 個完整 PRB 的累計計次，可用總數 9000 個。兩者為相同時段與計數口徑。

**0636.** ［計算題］使用 8450 個、可用 9000 個。依 TS 28.552 下行 PRB 使用率報告方式，求向下取整的百分比。

<details><summary>看答案</summary>

**答案**　93%。

**詳解**　先除以可用總數、乘 100，再向下取整。 floor 表示向下取整。 算式 `floor(8450 ÷ 9000 × 100) = 93`%。

**出處**　[3GPP TS 28.552 §5.1.1.2.1](https://www.etsi.org/deliver/etsi_ts/128500_128599/128552/19.06.00_60/ts_128552v190600p.pdf)

</details>

**0637.** ［計算題］可用 9000 個 PRB 的累計計次，已用 8450 個。尚未用的資源計次是多少？

<details><summary>看答案</summary>

**答案**　550 個。

**詳解**　算式 `9000−8450 = 550` 個。

**出處**　[3GPP TS 28.552 §5.1.1.2.1](https://www.etsi.org/deliver/etsi_ts/128500_128599/128552/19.06.00_60/ts_128552v190600p.pdf)

</details>

**情境 129｜校園晚間串流**

同一個 NRCellDU 的下行觀測窗，已使用 3900 個完整 PRB 的累計計次，可用總數 5600 個。兩者為相同時段與計數口徑。

**0641.** ［計算題］使用 3900 個、可用 5600 個。依 TS 28.552 下行 PRB 使用率報告方式，求向下取整的百分比。

<details><summary>看答案</summary>

**答案**　69%。

**詳解**　先除以可用總數、乘 100，再向下取整。 floor 表示向下取整。 算式 `floor(3900 ÷ 5600 × 100) = 69`%。

**出處**　[3GPP TS 28.552 §5.1.1.2.1](https://www.etsi.org/deliver/etsi_ts/128500_128599/128552/19.06.00_60/ts_128552v190600p.pdf)

</details>

**0642.** ［計算題］可用 5600 個 PRB 的累計計次，已用 3900 個。尚未用的資源計次是多少？

<details><summary>看答案</summary>

**答案**　1700 個。

**詳解**　算式 `5600−3900 = 1700` 個。

**出處**　[3GPP TS 28.552 §5.1.1.2.1](https://www.etsi.org/deliver/etsi_ts/128500_128599/128552/19.06.00_60/ts_128552v190600p.pdf)

</details>

**情境 130｜物流倉庫小區**

同一個 NRCellDU 的下行觀測窗，已使用 5425 個完整 PRB 的累計計次，可用總數 7500 個。兩者為相同時段與計數口徑。

**0646.** ［計算題］使用 5425 個、可用 7500 個。依 TS 28.552 下行 PRB 使用率報告方式，求向下取整的百分比。

<details><summary>看答案</summary>

**答案**　72%。

**詳解**　先除以可用總數、乘 100，再向下取整。 floor 表示向下取整。 算式 `floor(5425 ÷ 7500 × 100) = 72`%。

**出處**　[3GPP TS 28.552 §5.1.1.2.1](https://www.etsi.org/deliver/etsi_ts/128500_128599/128552/19.06.00_60/ts_128552v190600p.pdf)

</details>

頁次：[1](1-6-bank-1.md)　**2**　[3](1-6-bank-3.md)　[4](1-6-bank-4.md)
