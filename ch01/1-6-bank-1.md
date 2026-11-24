# 1.6 指標與名詞　補充練習題（656 題）（第 1／4 頁）

所屬：[1.6 指標與名詞](1-6.md)

GSMA 這個細項題目不足，以下為補充題（情境與數據為出題用的假設資料）。另有留存題不放在書上，只用來評估。換頁時若從情境中間開始，情境內容請看上一頁。

頁次：**1**　[2](1-6-bank-2.md)　[3](1-6-bank-3.md)　[4](1-6-bank-4.md)

## 1.6.1 訊號強度：RSRP、RSSI

### 1. SS-RSRP 與同步訊號量測

**情境 001｜高架車站進站路測**

在月台和天橋使用同一終端與相同 SS/PBCH block、頻段及量測設定。兩點 SS-RSRP 分別為 -92 dBm、-84 dBm。

**0001.** 若要確認同步訊號的接收強度，應讀哪一欄？

<details><summary>看答案</summary>

**答案**　SS-RSRP。

**詳解**　其量測定義以承載次同步訊號的資源元素功率作線性平均。若用了規格允許的其他參考訊號，仍須遵循對應量測配置。

**出處**　[3GPP TS 38.215 §5.1.1](https://www.etsi.org/deliver/etsi_ts/138200_138299/138215/18.03.00_60/ts_138215v180300p.pdf)

</details>

**0002.** ［計算題］天橋相對月台的 SS-RSRP 有符號差值是多少？兩點依序為 -92、-84 dBm。

<details><summary>看答案</summary>

**答案**　8 dB。

**詳解**　兩個以相同 1 mW 為基準的功率讀值相減，差值是 dB。 算式 `−84−(−92) = 8` dB。

**出處**　[3GPP TS 38.215 §5.1.1](https://www.etsi.org/deliver/etsi_ts/138200_138299/138215/18.03.00_60/ts_138215v180300p.pdf) · [NIST SP 811 §8.7](https://www.nist.gov/pml/special-publication-811/nist-guide-si-chapter-8)

</details>

**0003.** ［計算題］SS-RSRP 為 -92 dBm 時，功率是 -84 dBm 時的幾倍？四捨五入至小數第三位。

<details><summary>看答案</summary>

**答案**　0.158 倍。

**詳解**　功率比的方向是月台除以天橋。 算式 `10^((−92−(−84)) ÷ 10) ≈ 0.158` 倍。

**出處**　[3GPP TS 38.215 §5.1.1](https://www.etsi.org/deliver/etsi_ts/138200_138299/138215/18.03.00_60/ts_138215v180300p.pdf) · [NIST SP 811 §8.7](https://www.nist.gov/pml/special-publication-811/nist-guide-si-chapter-8)

</details>

**0004.** 若另一份表把時間窗內的總接收功率也寫成 SS-RSRP，應如何更正？

<details><summary>看答案</summary>

**答案**　依實際量測配置標為適用的 RSSI，並保留其量測資源範圍。

**詳解**　SS-RSRP 聚焦指定參考訊號資源元素的功率。載波 RSSI 涵蓋指定資源內的總接收功率。

**出處**　[3GPP TS 38.215 §5.1.1](https://www.etsi.org/deliver/etsi_ts/138200_138299/138215/18.03.00_60/ts_138215v180300p.pdf) · [3GPP TS 38.215 §5.1.3](https://www.etsi.org/deliver/etsi_ts/138200_138299/138215/18.03.00_60/ts_138215v180300p.pdf)

</details>

**0005.** 只因月台與天橋的 SS-RSRP 不同，可以斷定資料下載速度也按同一倍數改變嗎？

<details><summary>看答案</summary>

**答案**　無法由這兩筆 SS-RSRP 推定下載速度。

**詳解**　功率之外還有干擾與雜訊、可分配的資源、負載和其他鏈路限制。可用同條件的品質與吞吐量觀測驗證。

**出處**　[3GPP TS 38.215 §5.1.1](https://www.etsi.org/deliver/etsi_ts/138200_138299/138215/18.03.00_60/ts_138215v180300p.pdf) · [3GPP TS 28.552 §5.1.1.3](https://www.etsi.org/deliver/etsi_ts/128500_128599/128552/19.06.00_60/ts_128552v190600p.pdf)

</details>

**情境 002｜夜間港區固定探測**

在岸邊和倉庫外使用同一終端與相同 SS/PBCH block、頻段及量測設定。兩點 SS-RSRP 分別為 -99 dBm、-86 dBm。

**0006.** 若要確認同步訊號的接收強度，應讀哪一欄？

<details><summary>看答案</summary>

**答案**　SS-RSRP。

**詳解**　其量測定義以承載次同步訊號的資源元素功率作線性平均。若用了規格允許的其他參考訊號，仍須遵循對應量測配置。

**出處**　[3GPP TS 38.215 §5.1.1](https://www.etsi.org/deliver/etsi_ts/138200_138299/138215/18.03.00_60/ts_138215v180300p.pdf)

</details>

**0007.** ［計算題］倉庫外相對岸邊的 SS-RSRP 有符號差值是多少？兩點依序為 -99、-86 dBm。

<details><summary>看答案</summary>

**答案**　13 dB。

**詳解**　兩個以相同 1 mW 為基準的功率讀值相減，差值是 dB。 算式 `−86−(−99) = 13` dB。

**出處**　[3GPP TS 38.215 §5.1.1](https://www.etsi.org/deliver/etsi_ts/138200_138299/138215/18.03.00_60/ts_138215v180300p.pdf) · [NIST SP 811 §8.7](https://www.nist.gov/pml/special-publication-811/nist-guide-si-chapter-8)

</details>

**0008.** ［計算題］SS-RSRP 為 -99 dBm 時，功率是 -86 dBm 時的幾倍？四捨五入至小數第三位。

<details><summary>看答案</summary>

**答案**　0.050 倍。

**詳解**　功率比的方向是岸邊除以倉庫外。 算式 `10^((−99−(−86)) ÷ 10) ≈ 0.050` 倍。

**出處**　[3GPP TS 38.215 §5.1.1](https://www.etsi.org/deliver/etsi_ts/138200_138299/138215/18.03.00_60/ts_138215v180300p.pdf) · [NIST SP 811 §8.7](https://www.nist.gov/pml/special-publication-811/nist-guide-si-chapter-8)

</details>

**0009.** 若另一份表把時間窗內的總接收功率也寫成 SS-RSRP，應如何更正？

<details><summary>看答案</summary>

**答案**　依實際量測配置標為適用的 RSSI，並保留其量測資源範圍。

**詳解**　SS-RSRP 聚焦指定參考訊號資源元素的功率。載波 RSSI 涵蓋指定資源內的總接收功率。

**出處**　[3GPP TS 38.215 §5.1.1](https://www.etsi.org/deliver/etsi_ts/138200_138299/138215/18.03.00_60/ts_138215v180300p.pdf) · [3GPP TS 38.215 §5.1.3](https://www.etsi.org/deliver/etsi_ts/138200_138299/138215/18.03.00_60/ts_138215v180300p.pdf)

</details>

**0010.** 只因岸邊與倉庫外的 SS-RSRP 不同，可以斷定資料下載速度也按同一倍數改變嗎？

<details><summary>看答案</summary>

**答案**　無法由這兩筆 SS-RSRP 推定下載速度。

**詳解**　功率之外還有干擾與雜訊、可分配的資源、負載和其他鏈路限制。可用同條件的品質與吞吐量觀測驗證。

**出處**　[3GPP TS 38.215 §5.1.1](https://www.etsi.org/deliver/etsi_ts/138200_138299/138215/18.03.00_60/ts_138215v180300p.pdf) · [3GPP TS 28.552 §5.1.1.3](https://www.etsi.org/deliver/etsi_ts/128500_128599/128552/19.06.00_60/ts_128552v190600p.pdf)

</details>

**情境 003｜山腰道路覆蓋確認**

在彎道入口和彎道出口使用同一終端與相同 SS/PBCH block、頻段及量測設定。兩點 SS-RSRP 分別為 -106 dBm、-97 dBm。

**0012.** ［計算題］彎道出口相對彎道入口的 SS-RSRP 有符號差值是多少？兩點依序為 -106、-97 dBm。

<details><summary>看答案</summary>

**答案**　9 dB。

**詳解**　兩個以相同 1 mW 為基準的功率讀值相減，差值是 dB。 算式 `−97−(−106) = 9` dB。

**出處**　[3GPP TS 38.215 §5.1.1](https://www.etsi.org/deliver/etsi_ts/138200_138299/138215/18.03.00_60/ts_138215v180300p.pdf) · [NIST SP 811 §8.7](https://www.nist.gov/pml/special-publication-811/nist-guide-si-chapter-8)

</details>

**0013.** ［計算題］SS-RSRP 為 -106 dBm 時，功率是 -97 dBm 時的幾倍？四捨五入至小數第三位。

<details><summary>看答案</summary>

**答案**　0.126 倍。

**詳解**　功率比的方向是彎道入口除以彎道出口。 算式 `10^((−106−(−97)) ÷ 10) ≈ 0.126` 倍。

**出處**　[3GPP TS 38.215 §5.1.1](https://www.etsi.org/deliver/etsi_ts/138200_138299/138215/18.03.00_60/ts_138215v180300p.pdf) · [NIST SP 811 §8.7](https://www.nist.gov/pml/special-publication-811/nist-guide-si-chapter-8)

</details>

**0015.** 只因彎道入口與彎道出口的 SS-RSRP 不同，可以斷定資料下載速度也按同一倍數改變嗎？

<details><summary>看答案</summary>

**答案**　無法由這兩筆 SS-RSRP 推定下載速度。

**詳解**　功率之外還有干擾與雜訊、可分配的資源、負載和其他鏈路限制。可用同條件的品質與吞吐量觀測驗證。

**出處**　[3GPP TS 38.215 §5.1.1](https://www.etsi.org/deliver/etsi_ts/138200_138299/138215/18.03.00_60/ts_138215v180300p.pdf) · [3GPP TS 28.552 §5.1.1.3](https://www.etsi.org/deliver/etsi_ts/128500_128599/128552/19.06.00_60/ts_128552v190600p.pdf)

</details>

**情境 004｜商辦大廳室內測試**

在大門和電梯口使用同一終端與相同 SS/PBCH block、頻段及量測設定。兩點 SS-RSRP 分別為 -81 dBm、-94 dBm。

**0017.** ［計算題］電梯口相對大門的 SS-RSRP 有符號差值是多少？兩點依序為 -81、-94 dBm。

<details><summary>看答案</summary>

**答案**　-13 dB。

**詳解**　兩個以相同 1 mW 為基準的功率讀值相減，差值是 dB。 算式 `−94−(−81) = -13` dB。

**出處**　[3GPP TS 38.215 §5.1.1](https://www.etsi.org/deliver/etsi_ts/138200_138299/138215/18.03.00_60/ts_138215v180300p.pdf) · [NIST SP 811 §8.7](https://www.nist.gov/pml/special-publication-811/nist-guide-si-chapter-8)

</details>

**0018.** ［計算題］SS-RSRP 為 -81 dBm 時，功率是 -94 dBm 時的幾倍？四捨五入至小數第三位。

<details><summary>看答案</summary>

**答案**　19.953 倍。

**詳解**　功率比的方向是大門除以電梯口。 算式 `10^((−81−(−94)) ÷ 10) ≈ 19.953` 倍。

**出處**　[3GPP TS 38.215 §5.1.1](https://www.etsi.org/deliver/etsi_ts/138200_138299/138215/18.03.00_60/ts_138215v180300p.pdf) · [NIST SP 811 §8.7](https://www.nist.gov/pml/special-publication-811/nist-guide-si-chapter-8)

</details>

**0020.** 只因大門與電梯口的 SS-RSRP 不同，可以斷定資料下載速度也按同一倍數改變嗎？

<details><summary>看答案</summary>

**答案**　無法由這兩筆 SS-RSRP 推定下載速度。

**詳解**　功率之外還有干擾與雜訊、可分配的資源、負載和其他鏈路限制。可用同條件的品質與吞吐量觀測驗證。

**出處**　[3GPP TS 38.215 §5.1.1](https://www.etsi.org/deliver/etsi_ts/138200_138299/138215/18.03.00_60/ts_138215v180300p.pdf) · [3GPP TS 28.552 §5.1.1.3](https://www.etsi.org/deliver/etsi_ts/128500_128599/128552/19.06.00_60/ts_128552v190600p.pdf)

</details>

**情境 005｜會展中心入口抽測**

在售票區和外廣場使用同一終端與相同 SS/PBCH block、頻段及量測設定。兩點 SS-RSRP 分別為 -89 dBm、-82 dBm。

**0022.** ［計算題］外廣場相對售票區的 SS-RSRP 有符號差值是多少？兩點依序為 -89、-82 dBm。

<details><summary>看答案</summary>

**答案**　7 dB。

**詳解**　兩個以相同 1 mW 為基準的功率讀值相減，差值是 dB。 算式 `−82−(−89) = 7` dB。

**出處**　[3GPP TS 38.215 §5.1.1](https://www.etsi.org/deliver/etsi_ts/138200_138299/138215/18.03.00_60/ts_138215v180300p.pdf) · [NIST SP 811 §8.7](https://www.nist.gov/pml/special-publication-811/nist-guide-si-chapter-8)

</details>

**0023.** ［計算題］SS-RSRP 為 -89 dBm 時，功率是 -82 dBm 時的幾倍？四捨五入至小數第三位。

<details><summary>看答案</summary>

**答案**　0.200 倍。

**詳解**　功率比的方向是售票區除以外廣場。 算式 `10^((−89−(−82)) ÷ 10) ≈ 0.200` 倍。

**出處**　[3GPP TS 38.215 §5.1.1](https://www.etsi.org/deliver/etsi_ts/138200_138299/138215/18.03.00_60/ts_138215v180300p.pdf) · [NIST SP 811 §8.7](https://www.nist.gov/pml/special-publication-811/nist-guide-si-chapter-8)

</details>

**0025.** 只因售票區與外廣場的 SS-RSRP 不同，可以斷定資料下載速度也按同一倍數改變嗎？

<details><summary>看答案</summary>

**答案**　無法由這兩筆 SS-RSRP 推定下載速度。

**詳解**　功率之外還有干擾與雜訊、可分配的資源、負載和其他鏈路限制。可用同條件的品質與吞吐量觀測驗證。

**出處**　[3GPP TS 38.215 §5.1.1](https://www.etsi.org/deliver/etsi_ts/138200_138299/138215/18.03.00_60/ts_138215v180300p.pdf) · [3GPP TS 28.552 §5.1.1.3](https://www.etsi.org/deliver/etsi_ts/128500_128599/128552/19.06.00_60/ts_128552v190600p.pdf)

</details>

### 2. CSI-RS 的量測對象與基準

**情境 008｜工廠門機波束測試**

同一 UE 在轉角與控制室量到 CSI-RSRP -91 和 -85 dBm。兩筆使用同一指定 CSI-RS 資源和受控的接收設定。

**0036.** CSI-RSRP 應以哪一類資源元素來量測？

<details><summary>看答案</summary>

**答案**　以用於 RSRP 量測的 CSI-RS 所對應資源元素為基礎。

**詳解**　TS 38.215 規定對這些參考訊號資源元素的功率作線性平均，具體資源由量測配置決定。

**出處**　[3GPP TS 38.215 §5.1.2](https://www.etsi.org/deliver/etsi_ts/138200_138299/138215/18.03.00_60/ts_138215v180300p.pdf)

</details>

**0037.** ［計算題］取 -91 dBm 和 -85 dBm 中較強者，較強者比另一筆強多少 dB？

<details><summary>看答案</summary>

**答案**　6 dB。

**詳解**　較大的 dBm 代表較大的功率。 算式 `−85−(−91) = 6` dB。

**出處**　[3GPP TS 38.215 §5.1.2](https://www.etsi.org/deliver/etsi_ts/138200_138299/138215/18.03.00_60/ts_138215v180300p.pdf) · [NIST SP 811 §8.7](https://www.nist.gov/pml/special-publication-811/nist-guide-si-chapter-8)

</details>

**0038.** ［計算題］若 -91 dBm 再提高 3.00 dB，新 CSI-RSRP 為多少？

<details><summary>看答案</summary>

**答案**　-88 dBm。

**詳解**　dB 表示相對功率變化，可加到以 dBm 表示的功率讀值。 算式 `−91 + 3 = -88` dBm。

**出處**　[3GPP TS 38.215 §5.1.2](https://www.etsi.org/deliver/etsi_ts/138200_138299/138215/18.03.00_60/ts_138215v180300p.pdf) · [NIST SP 811 §8.7](https://www.nist.gov/pml/special-publication-811/nist-guide-si-chapter-8)

</details>

**0039.** 同一點另有 SS-RSRP。若要合成 CSI-RSRP 趨勢，應直接把 SS-RSRP 當作同一欄嗎？

<details><summary>看答案</summary>

**答案**　應保留各自的欄位與量測資源。

**詳解**　兩者的參考訊號與配置可能不同。標註資源集、頻段與時段後，可並列作為不同觀測來源。

**出處**　[3GPP TS 38.215 §5.1.1](https://www.etsi.org/deliver/etsi_ts/138200_138299/138215/18.03.00_60/ts_138215v180300p.pdf) · [3GPP TS 38.215 §5.1.2](https://www.etsi.org/deliver/etsi_ts/138200_138299/138215/18.03.00_60/ts_138215v180300p.pdf)

</details>

**0040.** 下一輪重測若更換了 CSI-RS 資源，最低限度要記下什麼才可解讀差異？

<details><summary>看答案</summary>

**答案**　記錄資源識別與配置、量測位置、時間窗及接收條件。

**詳解**　若資源或波束改變，讀值變化可能來自量測對象或現場條件。保留標記才能做同條件比對。

**出處**　[3GPP TS 38.215 §5.1.2](https://www.etsi.org/deliver/etsi_ts/138200_138299/138215/18.03.00_60/ts_138215v180300p.pdf)

</details>

**情境 009｜圖書館室內波束細測**

同一 UE 在入口與閱覽區量到 CSI-RSRP -87 和 -93 dBm。兩筆使用同一指定 CSI-RS 資源和受控的接收設定。

**0041.** CSI-RSRP 應以哪一類資源元素來量測？

<details><summary>看答案</summary>

**答案**　以用於 RSRP 量測的 CSI-RS 所對應資源元素為基礎。

**詳解**　TS 38.215 規定對這些參考訊號資源元素的功率作線性平均，具體資源由量測配置決定。

**出處**　[3GPP TS 38.215 §5.1.2](https://www.etsi.org/deliver/etsi_ts/138200_138299/138215/18.03.00_60/ts_138215v180300p.pdf)

</details>

**0042.** ［計算題］取 -87 dBm 和 -93 dBm 中較強者，較強者比另一筆強多少 dB？

<details><summary>看答案</summary>

**答案**　6 dB。

**詳解**　較大的 dBm 代表較大的功率。 算式 `−87−(−93) = 6` dB。

**出處**　[3GPP TS 38.215 §5.1.2](https://www.etsi.org/deliver/etsi_ts/138200_138299/138215/18.03.00_60/ts_138215v180300p.pdf) · [NIST SP 811 §8.7](https://www.nist.gov/pml/special-publication-811/nist-guide-si-chapter-8)

</details>

**0043.** ［計算題］若 -87 dBm 再提高 3.00 dB，新 CSI-RSRP 為多少？

<details><summary>看答案</summary>

**答案**　-84 dBm。

**詳解**　dB 表示相對功率變化，可加到以 dBm 表示的功率讀值。 算式 `−87 + 3 = -84` dBm。

**出處**　[3GPP TS 38.215 §5.1.2](https://www.etsi.org/deliver/etsi_ts/138200_138299/138215/18.03.00_60/ts_138215v180300p.pdf) · [NIST SP 811 §8.7](https://www.nist.gov/pml/special-publication-811/nist-guide-si-chapter-8)

</details>

**0044.** 同一點另有 SS-RSRP。若要合成 CSI-RSRP 趨勢，應直接把 SS-RSRP 當作同一欄嗎？

<details><summary>看答案</summary>

**答案**　應保留各自的欄位與量測資源。

**詳解**　兩者的參考訊號與配置可能不同。標註資源集、頻段與時段後，可並列作為不同觀測來源。

**出處**　[3GPP TS 38.215 §5.1.1](https://www.etsi.org/deliver/etsi_ts/138200_138299/138215/18.03.00_60/ts_138215v180300p.pdf) · [3GPP TS 38.215 §5.1.2](https://www.etsi.org/deliver/etsi_ts/138200_138299/138215/18.03.00_60/ts_138215v180300p.pdf)

</details>

**0045.** 下一輪重測若更換了 CSI-RS 資源，最低限度要記下什麼才可解讀差異？

<details><summary>看答案</summary>

**答案**　記錄資源識別與配置、量測位置、時間窗及接收條件。

**詳解**　若資源或波束改變，讀值變化可能來自量測對象或現場條件。保留標記才能做同條件比對。

**出處**　[3GPP TS 38.215 §5.1.2](https://www.etsi.org/deliver/etsi_ts/138200_138299/138215/18.03.00_60/ts_138215v180300p.pdf)

</details>

**情境 010｜展演館看台波束巡測**

同一 UE 在前排與後排量到 CSI-RSRP -76 和 -93 dBm。兩筆使用同一指定 CSI-RS 資源和受控的接收設定。

**0047.** ［計算題］取 -76 dBm 和 -93 dBm 中較強者，較強者比另一筆強多少 dB？

<details><summary>看答案</summary>

**答案**　17 dB。

**詳解**　較大的 dBm 代表較大的功率。 算式 `−76−(−93) = 17` dB。

**出處**　[3GPP TS 38.215 §5.1.2](https://www.etsi.org/deliver/etsi_ts/138200_138299/138215/18.03.00_60/ts_138215v180300p.pdf) · [NIST SP 811 §8.7](https://www.nist.gov/pml/special-publication-811/nist-guide-si-chapter-8)

</details>

**0048.** ［計算題］若 -76 dBm 再提高 3.00 dB，新 CSI-RSRP 為多少？

<details><summary>看答案</summary>

**答案**　-73 dBm。

**詳解**　dB 表示相對功率變化，可加到以 dBm 表示的功率讀值。 算式 `−76 + 3 = -73` dBm。

**出處**　[3GPP TS 38.215 §5.1.2](https://www.etsi.org/deliver/etsi_ts/138200_138299/138215/18.03.00_60/ts_138215v180300p.pdf) · [NIST SP 811 §8.7](https://www.nist.gov/pml/special-publication-811/nist-guide-si-chapter-8)

</details>

**情境 011｜企業園區玻璃走廊**

同一 UE 在窗邊與走廊口量到 CSI-RSRP -82 和 -90 dBm。兩筆使用同一指定 CSI-RS 資源和受控的接收設定。

**0052.** ［計算題］取 -82 dBm 和 -90 dBm 中較強者，較強者比另一筆強多少 dB？

<details><summary>看答案</summary>

**答案**　8 dB。

**詳解**　較大的 dBm 代表較大的功率。 算式 `−82−(−90) = 8` dB。

**出處**　[3GPP TS 38.215 §5.1.2](https://www.etsi.org/deliver/etsi_ts/138200_138299/138215/18.03.00_60/ts_138215v180300p.pdf) · [NIST SP 811 §8.7](https://www.nist.gov/pml/special-publication-811/nist-guide-si-chapter-8)

</details>

**0053.** ［計算題］若 -82 dBm 再提高 3.00 dB，新 CSI-RSRP 為多少？

<details><summary>看答案</summary>

**答案**　-79 dBm。

**詳解**　dB 表示相對功率變化，可加到以 dBm 表示的功率讀值。 算式 `−82 + 3 = -79` dBm。

**出處**　[3GPP TS 38.215 §5.1.2](https://www.etsi.org/deliver/etsi_ts/138200_138299/138215/18.03.00_60/ts_138215v180300p.pdf) · [NIST SP 811 §8.7](https://www.nist.gov/pml/special-publication-811/nist-guide-si-chapter-8)

</details>

**情境 012｜捷運站廳 CSI 回報**

同一 UE 在閘門與站廳量到 CSI-RSRP -104 和 -91 dBm。兩筆使用同一指定 CSI-RS 資源和受控的接收設定。

**0057.** ［計算題］取 -104 dBm 和 -91 dBm 中較強者，較強者比另一筆強多少 dB？

<details><summary>看答案</summary>

**答案**　13 dB。

**詳解**　較大的 dBm 代表較大的功率。 算式 `−91−(−104) = 13` dB。

**出處**　[3GPP TS 38.215 §5.1.2](https://www.etsi.org/deliver/etsi_ts/138200_138299/138215/18.03.00_60/ts_138215v180300p.pdf) · [NIST SP 811 §8.7](https://www.nist.gov/pml/special-publication-811/nist-guide-si-chapter-8)

</details>

**0058.** ［計算題］若 -104 dBm 再提高 3.00 dB，新 CSI-RSRP 為多少？

<details><summary>看答案</summary>

**答案**　-101 dBm。

**詳解**　dB 表示相對功率變化，可加到以 dBm 表示的功率讀值。 算式 `−104 + 3 = -101` dBm。

**出處**　[3GPP TS 38.215 §5.1.2](https://www.etsi.org/deliver/etsi_ts/138200_138299/138215/18.03.00_60/ts_138215v180300p.pdf) · [NIST SP 811 §8.7](https://www.nist.gov/pml/special-publication-811/nist-guide-si-chapter-8)

</details>

### 3. dBm、mW 與差值

**情境 014｜入廠接收校驗**

在導線量測鏈量測參考訊號功率。起始讀值 -70 dBm，受控測試中降低 6 dB。

**0066.** ［計算題］起始讀值 -70 dBm 換成 mW 是多少？（四捨五入至小數第 10 位）

<details><summary>看答案</summary>

**答案**　0.0000001000 mW。

**詳解**　dBm 的基準為 1 mW。 算式 `10^(−70 ÷ 10) = 0.0000001000` mW。

**出處**　[NIST SP 811 §8.7](https://www.nist.gov/pml/special-publication-811/nist-guide-si-chapter-8)

</details>

**0067.** ［計算題］起始為 -70 dBm，降低 6 dB 後的新功率讀值是多少？

<details><summary>看答案</summary>

**答案**　-76 dBm。

**詳解**　功率的對數讀值以原 dBm 減相對衰減。 算式 `−70−6 = -76` dBm。

**出處**　[NIST SP 811 §8.7](https://www.nist.gov/pml/special-publication-811/nist-guide-si-chapter-8)

</details>

**0068.** 記錄中的 dBm 與 dB 各代表什麼？

<details><summary>看答案</summary>

**答案**　dBm 是以 1 mW 為基準的功率讀值，dB 在此表示功率比。

**詳解**　兩個 dBm 讀值相減得到 dB。用線性量相加時，先將各讀值轉成相同線性單位。

**出處**　[NIST SP 811 §8.7](https://www.nist.gov/pml/special-publication-811/nist-guide-si-chapter-8)

</details>

**0069.** 讀值是負 dBm，是否代表接收器量到負功率？

<details><summary>看答案</summary>

**答案**　功率仍是正值，負號表示低於 1 mW 的基準。

**詳解**　正的功率除以 1 mW 若小於 1，取十進對數會是負值。

**出處**　[NIST SP 811 §8.7](https://www.nist.gov/pml/special-publication-811/nist-guide-si-chapter-8)

</details>

**0070.** 若另一個探測器將 RSSI 與 RSRP 都以 dBm 顯示，如何辨認兩欄互不相同？

<details><summary>看答案</summary>

**答案**　查看量測欄位與資源定義。

**詳解**　單位只表示功率的對數基準，量測對象分別由總接收功率或參考訊號資源元素的規格定義決定。

**出處**　[3GPP TS 38.215 §5.1.1](https://www.etsi.org/deliver/etsi_ts/138200_138299/138215/18.03.00_60/ts_138215v180300p.pdf) · [3GPP TS 38.215 §5.1.3](https://www.etsi.org/deliver/etsi_ts/138200_138299/138215/18.03.00_60/ts_138215v180300p.pdf)

</details>

**情境 015｜室內掃描接收校準**

在校驗路徑量測參考訊號功率。起始讀值 -90 dBm，受控測試中降低 10 dB。

**0071.** ［計算題］起始讀值 -90 dBm 換成 mW 是多少？（四捨五入至小數第 10 位）

<details><summary>看答案</summary>

**答案**　0.0000000010 mW。

**詳解**　dBm 的基準為 1 mW。 算式 `10^(−90 ÷ 10) = 0.0000000010` mW。

**出處**　[NIST SP 811 §8.7](https://www.nist.gov/pml/special-publication-811/nist-guide-si-chapter-8)

</details>

**0072.** ［計算題］起始為 -90 dBm，降低 10 dB 後的新功率讀值是多少？

<details><summary>看答案</summary>

**答案**　-100 dBm。

**詳解**　功率的對數讀值以原 dBm 減相對衰減。 算式 `−90−10 = -100` dBm。

**出處**　[NIST SP 811 §8.7](https://www.nist.gov/pml/special-publication-811/nist-guide-si-chapter-8)

</details>

**0073.** 記錄中的 dBm 與 dB 各代表什麼？

<details><summary>看答案</summary>

**答案**　dBm 是以 1 mW 為基準的功率讀值，dB 在此表示功率比。

**詳解**　兩個 dBm 讀值相減得到 dB。用線性量相加時，先將各讀值轉成相同線性單位。

**出處**　[NIST SP 811 §8.7](https://www.nist.gov/pml/special-publication-811/nist-guide-si-chapter-8)

</details>

**0074.** 讀值是負 dBm，是否代表接收器量到負功率？

<details><summary>看答案</summary>

**答案**　功率仍是正值，負號表示低於 1 mW 的基準。

**詳解**　正的功率除以 1 mW 若小於 1，取十進對數會是負值。

**出處**　[NIST SP 811 §8.7](https://www.nist.gov/pml/special-publication-811/nist-guide-si-chapter-8)

</details>

**0075.** 若另一個探測器將 RSSI 與 RSRP 都以 dBm 顯示，如何辨認兩欄互不相同？

<details><summary>看答案</summary>

**答案**　查看量測欄位與資源定義。

**詳解**　單位只表示功率的對數基準，量測對象分別由總接收功率或參考訊號資源元素的規格定義決定。

**出處**　[3GPP TS 38.215 §5.1.1](https://www.etsi.org/deliver/etsi_ts/138200_138299/138215/18.03.00_60/ts_138215v180300p.pdf) · [3GPP TS 38.215 §5.1.3](https://www.etsi.org/deliver/etsi_ts/138200_138299/138215/18.03.00_60/ts_138215v180300p.pdf)

</details>

**情境 016｜便攜接收器零點校驗**

在衰減器支路量測參考訊號功率。起始讀值 -80 dBm，受控測試中降低 12 dB。

**0076.** ［計算題］起始讀值 -80 dBm 換成 mW 是多少？（四捨五入至小數第 10 位）

<details><summary>看答案</summary>

**答案**　0.0000000100 mW。

**詳解**　dBm 的基準為 1 mW。 算式 `10^(−80 ÷ 10) = 0.0000000100` mW。

**出處**　[NIST SP 811 §8.7](https://www.nist.gov/pml/special-publication-811/nist-guide-si-chapter-8)

</details>

**0077.** ［計算題］起始為 -80 dBm，降低 12 dB 後的新功率讀值是多少？

<details><summary>看答案</summary>

**答案**　-92 dBm。

**詳解**　功率的對數讀值以原 dBm 減相對衰減。 算式 `−80−12 = -92` dBm。

**出處**　[NIST SP 811 §8.7](https://www.nist.gov/pml/special-publication-811/nist-guide-si-chapter-8)

</details>

**情境 017｜低功率感測端測試**

在屏蔽箱接收鏈量測參考訊號功率。起始讀值 -100 dBm，受控測試中降低 5 dB。

**0081.** ［計算題］起始讀值 -100 dBm 換成 mW 是多少？（四捨五入至小數第 10 位）

<details><summary>看答案</summary>

**答案**　0.0000000001 mW。

**詳解**　dBm 的基準為 1 mW。 算式 `10^(−100 ÷ 10) = 0.0000000001` mW。

**出處**　[NIST SP 811 §8.7](https://www.nist.gov/pml/special-publication-811/nist-guide-si-chapter-8)

</details>

**0082.** ［計算題］起始為 -100 dBm，降低 5 dB 後的新功率讀值是多少？

<details><summary>看答案</summary>

**答案**　-105 dBm。

**詳解**　功率的對數讀值以原 dBm 減相對衰減。 算式 `−100−5 = -105` dBm。

**出處**　[NIST SP 811 §8.7](https://www.nist.gov/pml/special-publication-811/nist-guide-si-chapter-8)

</details>

**情境 018｜實驗室雙路接收校驗**

在分配器輸出鏈量測參考訊號功率。起始讀值 -50 dBm，受控測試中降低 9 dB。

**0086.** ［計算題］起始讀值 -50 dBm 換成 mW 是多少？（四捨五入至小數第 10 位）

<details><summary>看答案</summary>

**答案**　0.0000100000 mW。

**詳解**　dBm 的基準為 1 mW。 算式 `10^(−50 ÷ 10) = 0.0000100000` mW。

**出處**　[NIST SP 811 §8.7](https://www.nist.gov/pml/special-publication-811/nist-guide-si-chapter-8)

</details>

**0087.** ［計算題］起始為 -50 dBm，降低 9 dB 後的新功率讀值是多少？

<details><summary>看答案</summary>

**答案**　-59 dBm。

**詳解**　功率的對數讀值以原 dBm 減相對衰減。 算式 `−50−9 = -59` dBm。

**出處**　[NIST SP 811 §8.7](https://www.nist.gov/pml/special-publication-811/nist-guide-si-chapter-8)

</details>

### 4. 線性平均與數值尺度

**情境 019｜兩個同步資源元素**

示意量測只取兩個等權、同類型有效資源元素。功率是 2 nW、4 nW，依 SS-RSRP 適用的資源量測。

**0091.** ［計算題］兩個等權資源元素功率為 2 和 4 nW，線性平均是多少？（四捨五入至小數第 1 位）

<details><summary>看答案</summary>

**答案**　3.0 nW。

**詳解**　先以相同的線性功率單位做平均。 算式 `(2 + 4) ÷ 2 = 3.0` nW。

**出處**　[3GPP TS 38.215 §5.1.1](https://www.etsi.org/deliver/etsi_ts/138200_138299/138215/18.03.00_60/ts_138215v180300p.pdf)

</details>

**0092.** ［計算題］求 2 與 4 nW 的等權線性平均後再換成 dBm，取小數第二位。

<details><summary>看答案</summary>

**答案**　-55.23 dBm。

**詳解**　1 mW＝1,000,000 nW。對平均功率和 1 mW 的比值取對數。 算式 `10 × log₁₀(((2 + 4) ÷ 2) ÷ 1000000) ≈ -55.23` dBm。

**出處**　[NIST SP 811 §8.7](https://www.nist.gov/pml/special-publication-811/nist-guide-si-chapter-8)

</details>

**0093.** 若兩筆是有效資源元素的 dBm 讀值，要按線性功率定義做平均，步驟是什麼？

<details><summary>看答案</summary>

**答案**　分別換成同一線性功率單位，取平均後再視需要換回 dBm。

**詳解**　對數轉換與算術平均一般不能互換。SS-RSRP 的平均對象是功率。

**出處**　[3GPP TS 38.215 §5.1.1](https://www.etsi.org/deliver/etsi_ts/138200_138299/138215/18.03.00_60/ts_138215v180300p.pdf) · [NIST SP 811 §8.7](https://www.nist.gov/pml/special-publication-811/nist-guide-si-chapter-8)

</details>

**0094.** 設備同時提供兩個元素的功率總和。可以直接拿總和填到 SS-RSRP 欄嗎？

<details><summary>看答案</summary>

**答案**　應依規格計算符合條件的元素平均值。

**詳解**　總和會隨納入元素數而變動。若兩個元素同權，平均值為總和除以 2。

**出處**　[3GPP TS 38.215 §5.1.1](https://www.etsi.org/deliver/etsi_ts/138200_138299/138215/18.03.00_60/ts_138215v180300p.pdf)

</details>

**0095.** 若其中一筆來自另一參考訊號資源，這筆合併平均還能代表原量測嗎？

<details><summary>看答案</summary>

**答案**　先核對配置是否允許合併與歸屬的量測對象。

**詳解**　同樣單位無法證明兩筆屬於同一資源集合。量測報告應先保留對應資源與配置。

**出處**　[3GPP TS 38.215 §5.1.1](https://www.etsi.org/deliver/etsi_ts/138200_138299/138215/18.03.00_60/ts_138215v180300p.pdf)

</details>

**情境 020｜教室波束接收樣本**

示意量測只取兩個等權、同類型有效資源元素。功率是 3 nW、7 nW，依 CSI-RSRP 適用的資源量測。

**0096.** ［計算題］兩個等權資源元素功率為 3 和 7 nW，線性平均是多少？（四捨五入至小數第 1 位）

<details><summary>看答案</summary>

**答案**　5.0 nW。

**詳解**　先以相同的線性功率單位做平均。 算式 `(3 + 7) ÷ 2 = 5.0` nW。

**出處**　[3GPP TS 38.215 §5.1.2](https://www.etsi.org/deliver/etsi_ts/138200_138299/138215/18.03.00_60/ts_138215v180300p.pdf)

</details>

**0097.** ［計算題］求 3 與 7 nW 的等權線性平均後再換成 dBm，取小數第二位。

<details><summary>看答案</summary>

**答案**　-53.01 dBm。

**詳解**　1 mW＝1,000,000 nW。對平均功率和 1 mW 的比值取對數。 算式 `10 × log₁₀(((3 + 7) ÷ 2) ÷ 1000000) ≈ -53.01` dBm。

**出處**　[NIST SP 811 §8.7](https://www.nist.gov/pml/special-publication-811/nist-guide-si-chapter-8)

</details>

**0098.** 若兩筆是有效資源元素的 dBm 讀值，要按線性功率定義做平均，步驟是什麼？

<details><summary>看答案</summary>

**答案**　分別換成同一線性功率單位，取平均後再視需要換回 dBm。

**詳解**　對數轉換與算術平均一般不能互換。CSI-RSRP 的平均對象是功率。

**出處**　[3GPP TS 38.215 §5.1.2](https://www.etsi.org/deliver/etsi_ts/138200_138299/138215/18.03.00_60/ts_138215v180300p.pdf) · [NIST SP 811 §8.7](https://www.nist.gov/pml/special-publication-811/nist-guide-si-chapter-8)

</details>

**0099.** 設備同時提供兩個元素的功率總和。可以直接拿總和填到 CSI-RSRP 欄嗎？

<details><summary>看答案</summary>

**答案**　應依規格計算符合條件的元素平均值。

**詳解**　總和會隨納入元素數而變動。若兩個元素同權，平均值為總和除以 2。

**出處**　[3GPP TS 38.215 §5.1.2](https://www.etsi.org/deliver/etsi_ts/138200_138299/138215/18.03.00_60/ts_138215v180300p.pdf)

</details>

**0100.** 若其中一筆來自另一參考訊號資源，這筆合併平均還能代表原量測嗎？

<details><summary>看答案</summary>

**答案**　先核對配置是否允許合併與歸屬的量測對象。

**詳解**　同樣單位無法證明兩筆屬於同一資源集合。量測報告應先保留對應資源與配置。

**出處**　[3GPP TS 38.215 §5.1.2](https://www.etsi.org/deliver/etsi_ts/138200_138299/138215/18.03.00_60/ts_138215v180300p.pdf)

</details>

**情境 022｜園區 CSI 受控量測**

示意量測只取兩個等權、同類型有效資源元素。功率是 1 nW、9 nW，依 CSI-RSRP 適用的資源量測。

**0106.** ［計算題］兩個等權資源元素功率為 1 和 9 nW，線性平均是多少？（四捨五入至小數第 1 位）

<details><summary>看答案</summary>

**答案**　5.0 nW。

**詳解**　先以相同的線性功率單位做平均。 算式 `(1 + 9) ÷ 2 = 5.0` nW。

**出處**　[3GPP TS 38.215 §5.1.2](https://www.etsi.org/deliver/etsi_ts/138200_138299/138215/18.03.00_60/ts_138215v180300p.pdf)

</details>

**0107.** ［計算題］求 1 與 9 nW 的等權線性平均後再換成 dBm，取小數第二位。

<details><summary>看答案</summary>

**答案**　-53.01 dBm。

**詳解**　1 mW＝1,000,000 nW。對平均功率和 1 mW 的比值取對數。 算式 `10 × log₁₀(((1 + 9) ÷ 2) ÷ 1000000) ≈ -53.01` dBm。

**出處**　[NIST SP 811 §8.7](https://www.nist.gov/pml/special-publication-811/nist-guide-si-chapter-8)

</details>

**0109.** 設備同時提供兩個元素的功率總和。可以直接拿總和填到 CSI-RSRP 欄嗎？

<details><summary>看答案</summary>

**答案**　應依規格計算符合條件的元素平均值。

**詳解**　總和會隨納入元素數而變動。若兩個元素同權，平均值為總和除以 2。

**出處**　[3GPP TS 38.215 §5.1.2](https://www.etsi.org/deliver/etsi_ts/138200_138299/138215/18.03.00_60/ts_138215v180300p.pdf)

</details>

**情境 023｜雙資源測試床**

示意量測只取兩個等權、同類型有效資源元素。功率是 4 nW、12 nW，依 CSI-RSRP 適用的資源量測。

**0111.** ［計算題］兩個等權資源元素功率為 4 和 12 nW，線性平均是多少？（四捨五入至小數第 1 位）

<details><summary>看答案</summary>

**答案**　8.0 nW。

**詳解**　先以相同的線性功率單位做平均。 算式 `(4 + 12) ÷ 2 = 8.0` nW。

**出處**　[3GPP TS 38.215 §5.1.2](https://www.etsi.org/deliver/etsi_ts/138200_138299/138215/18.03.00_60/ts_138215v180300p.pdf)

</details>

**0112.** ［計算題］求 4 與 12 nW 的等權線性平均後再換成 dBm，取小數第二位。

<details><summary>看答案</summary>

**答案**　-50.97 dBm。

**詳解**　1 mW＝1,000,000 nW。對平均功率和 1 mW 的比值取對數。 算式 `10 × log₁₀(((4 + 12) ÷ 2) ÷ 1000000) ≈ -50.97` dBm。

**出處**　[NIST SP 811 §8.7](https://www.nist.gov/pml/special-publication-811/nist-guide-si-chapter-8)

</details>

### 5. 載波 RSSI 與干擾／雜訊線索

**情境 024｜商圈尖峰前後比對**

午前與晚尖峰的 SS-RSRP 分別為 -96、-96 dBm，NR carrier RSSI 分別為 -68、-60 dBm。設定、頻寬及觀測地點一致。

**0116.** ［計算題］SS-RSRP 由 -96 dBm 變成 -96 dBm，有符號變化是多少？

<details><summary>看答案</summary>

**答案**　0 dB。

**詳解**　算式 `−96−(−96) = 0` dB。

**出處**　[3GPP TS 38.215 §5.1.1](https://www.etsi.org/deliver/etsi_ts/138200_138299/138215/18.03.00_60/ts_138215v180300p.pdf) · [NIST SP 811 §8.7](https://www.nist.gov/pml/special-publication-811/nist-guide-si-chapter-8)

</details>

**0117.** ［計算題］NR carrier RSSI 由 -68 dBm 變成 -60 dBm，有符號變化是多少？

<details><summary>看答案</summary>

**答案**　8 dB。

**詳解**　算式 `−60−(−68) = 8` dB。

**出處**　[3GPP TS 38.215 §5.1.3](https://www.etsi.org/deliver/etsi_ts/138200_138299/138215/18.03.00_60/ts_138215v180300p.pdf) · [NIST SP 811 §8.7](https://www.nist.gov/pml/special-publication-811/nist-guide-si-chapter-8)

</details>

**0118.** 兩個時段中，哪一欄包含來自同頻訊號、干擾和熱雜訊的接收功率？

<details><summary>看答案</summary>

**答案**　NR carrier RSSI。

**詳解**　指定量測資源內的總接收功率可來自多種來源。RSRP 只有指定參考訊號的功率貢獻。

**出處**　[3GPP TS 38.215 §5.1.3](https://www.etsi.org/deliver/etsi_ts/138200_138299/138215/18.03.00_60/ts_138215v180300p.pdf)

</details>

**0119.** 晚尖峰的 NR carrier RSSI 較高。能否單靠這一欄認定干擾上升？

<details><summary>看答案</summary>

**答案**　需要品質或干擾資料佐證。

**詳解**　RSSI 也含期望訊號和其他訊號。可比對同波束同口徑的 SS-SINR、SS-RSRQ、相鄰小區與負載。

**出處**　[3GPP TS 38.215 §5.1.3](https://www.etsi.org/deliver/etsi_ts/138200_138299/138215/18.03.00_60/ts_138215v180300p.pdf) · [3GPP TS 38.215 §5.1.5](https://www.etsi.org/deliver/etsi_ts/138200_138299/138215/18.03.00_60/ts_138215v180300p.pdf)

</details>

**0120.** 若同時發現 RSSI 變高與 SS-RSRP 只小幅變動，優先查核哪些口徑？

<details><summary>看答案</summary>

**答案**　先確認使用同一頻寬、符號／時段、接收設定、位置與波束。

**詳解**　只有在可比較的條件下，才能解讀總功率與參考訊號功率的變化。

**出處**　[3GPP TS 38.215 §5.1.1](https://www.etsi.org/deliver/etsi_ts/138200_138299/138215/18.03.00_60/ts_138215v180300p.pdf) · [3GPP TS 38.215 §5.1.3](https://www.etsi.org/deliver/etsi_ts/138200_138299/138215/18.03.00_60/ts_138215v180300p.pdf)

</details>

**情境 026｜室內同頻負載觀察**

使用前與使用中的 SS-RSRP 分別為 -94、-95 dBm，NR carrier RSSI 分別為 -72、-64 dBm。設定、頻寬及觀測地點一致。

**0126.** ［計算題］SS-RSRP 由 -94 dBm 變成 -95 dBm，有符號變化是多少？

<details><summary>看答案</summary>

**答案**　-1 dB。

**詳解**　算式 `−95−(−94) = -1` dB。

**出處**　[3GPP TS 38.215 §5.1.1](https://www.etsi.org/deliver/etsi_ts/138200_138299/138215/18.03.00_60/ts_138215v180300p.pdf) · [NIST SP 811 §8.7](https://www.nist.gov/pml/special-publication-811/nist-guide-si-chapter-8)

</details>

**0127.** ［計算題］NR carrier RSSI 由 -72 dBm 變成 -64 dBm，有符號變化是多少？

<details><summary>看答案</summary>

**答案**　8 dB。

**詳解**　算式 `−64−(−72) = 8` dB。

**出處**　[3GPP TS 38.215 §5.1.3](https://www.etsi.org/deliver/etsi_ts/138200_138299/138215/18.03.00_60/ts_138215v180300p.pdf) · [NIST SP 811 §8.7](https://www.nist.gov/pml/special-publication-811/nist-guide-si-chapter-8)

</details>

**0128.** 兩個時段中，哪一欄包含來自同頻訊號、干擾和熱雜訊的接收功率？

<details><summary>看答案</summary>

**答案**　NR carrier RSSI。

**詳解**　指定量測資源內的總接收功率可來自多種來源。RSRP 只有指定參考訊號的功率貢獻。

**出處**　[3GPP TS 38.215 §5.1.3](https://www.etsi.org/deliver/etsi_ts/138200_138299/138215/18.03.00_60/ts_138215v180300p.pdf)

</details>

**0129.** 使用中的 NR carrier RSSI 較高。能否單靠這一欄認定干擾上升？

<details><summary>看答案</summary>

**答案**　需要品質或干擾資料佐證。

**詳解**　RSSI 也含期望訊號和其他訊號。可比對同波束同口徑的 SS-SINR、SS-RSRQ、相鄰小區與負載。

**出處**　[3GPP TS 38.215 §5.1.3](https://www.etsi.org/deliver/etsi_ts/138200_138299/138215/18.03.00_60/ts_138215v180300p.pdf) · [3GPP TS 38.215 §5.1.5](https://www.etsi.org/deliver/etsi_ts/138200_138299/138215/18.03.00_60/ts_138215v180300p.pdf)

</details>

**0130.** 若同時發現 RSSI 變高與 SS-RSRP 只小幅變動，優先查核哪些口徑？

<details><summary>看答案</summary>

**答案**　先確認使用同一頻寬、符號／時段、接收設定、位置與波束。

**詳解**　只有在可比較的條件下，才能解讀總功率與參考訊號功率的變化。

**出處**　[3GPP TS 38.215 §5.1.1](https://www.etsi.org/deliver/etsi_ts/138200_138299/138215/18.03.00_60/ts_138215v180300p.pdf) · [3GPP TS 38.215 §5.1.3](https://www.etsi.org/deliver/etsi_ts/138200_138299/138215/18.03.00_60/ts_138215v180300p.pdf)

</details>

**情境 027｜倉儲相鄰區擴容**

擴容前與擴容後的 SS-RSRP 分別為 -90、-90 dBm，NR carrier RSSI 分別為 -65、-61 dBm。設定、頻寬及觀測地點一致。

**0131.** ［計算題］SS-RSRP 由 -90 dBm 變成 -90 dBm，有符號變化是多少？

<details><summary>看答案</summary>

**答案**　0 dB。

**詳解**　算式 `−90−(−90) = 0` dB。

**出處**　[3GPP TS 38.215 §5.1.1](https://www.etsi.org/deliver/etsi_ts/138200_138299/138215/18.03.00_60/ts_138215v180300p.pdf) · [NIST SP 811 §8.7](https://www.nist.gov/pml/special-publication-811/nist-guide-si-chapter-8)

</details>

**0132.** ［計算題］NR carrier RSSI 由 -65 dBm 變成 -61 dBm，有符號變化是多少？

<details><summary>看答案</summary>

**答案**　4 dB。

**詳解**　算式 `−61−(−65) = 4` dB。

**出處**　[3GPP TS 38.215 §5.1.3](https://www.etsi.org/deliver/etsi_ts/138200_138299/138215/18.03.00_60/ts_138215v180300p.pdf) · [NIST SP 811 §8.7](https://www.nist.gov/pml/special-publication-811/nist-guide-si-chapter-8)

</details>

**0134.** 擴容後的 NR carrier RSSI 較高。能否單靠這一欄認定干擾上升？

<details><summary>看答案</summary>

**答案**　需要品質或干擾資料佐證。

**詳解**　RSSI 也含期望訊號和其他訊號。可比對同波束同口徑的 SS-SINR、SS-RSRQ、相鄰小區與負載。

**出處**　[3GPP TS 38.215 §5.1.3](https://www.etsi.org/deliver/etsi_ts/138200_138299/138215/18.03.00_60/ts_138215v180300p.pdf) · [3GPP TS 38.215 §5.1.5](https://www.etsi.org/deliver/etsi_ts/138200_138299/138215/18.03.00_60/ts_138215v180300p.pdf)

</details>

**情境 028｜碼頭臨時容量調度**

清晨與中午的 SS-RSRP 分別為 -101、-99 dBm，NR carrier RSSI 分別為 -75、-67 dBm。設定、頻寬及觀測地點一致。

**0136.** ［計算題］SS-RSRP 由 -101 dBm 變成 -99 dBm，有符號變化是多少？

<details><summary>看答案</summary>

**答案**　2 dB。

**詳解**　算式 `−99−(−101) = 2` dB。

**出處**　[3GPP TS 38.215 §5.1.1](https://www.etsi.org/deliver/etsi_ts/138200_138299/138215/18.03.00_60/ts_138215v180300p.pdf) · [NIST SP 811 §8.7](https://www.nist.gov/pml/special-publication-811/nist-guide-si-chapter-8)

</details>

**0137.** ［計算題］NR carrier RSSI 由 -75 dBm 變成 -67 dBm，有符號變化是多少？

<details><summary>看答案</summary>

**答案**　8 dB。

**詳解**　算式 `−67−(−75) = 8` dB。

**出處**　[3GPP TS 38.215 §5.1.3](https://www.etsi.org/deliver/etsi_ts/138200_138299/138215/18.03.00_60/ts_138215v180300p.pdf) · [NIST SP 811 §8.7](https://www.nist.gov/pml/special-publication-811/nist-guide-si-chapter-8)

</details>

**0139.** 中午的 NR carrier RSSI 較高。能否單靠這一欄認定干擾上升？

<details><summary>看答案</summary>

**答案**　需要品質或干擾資料佐證。

**詳解**　RSSI 也含期望訊號和其他訊號。可比對同波束同口徑的 SS-SINR、SS-RSRQ、相鄰小區與負載。

**出處**　[3GPP TS 38.215 §5.1.3](https://www.etsi.org/deliver/etsi_ts/138200_138299/138215/18.03.00_60/ts_138215v180300p.pdf) · [3GPP TS 38.215 §5.1.5](https://www.etsi.org/deliver/etsi_ts/138200_138299/138215/18.03.00_60/ts_138215v180300p.pdf)

</details>

### 6. 門檻判讀與覆蓋抽樣

**情境 029｜深地下連通道**

使用同一 SS-RSRP 設定，走道甲為 -98 dBm，走道乙為 -108 dBm。這項抽測以 ≥ -105 dBm 作為站內驗收門檻。

**0141.** ［計算題］走道甲為 -98 dBm，門檻 -105 dBm。相對門檻高出多少 dB？低於以負值表示。

<details><summary>看答案</summary>

**答案**　7 dB。

**詳解**　算式 `−98−(−105) = 7` dB。

**出處**　[3GPP TS 38.215 §5.1.1](https://www.etsi.org/deliver/etsi_ts/138200_138299/138215/18.03.00_60/ts_138215v180300p.pdf) · [NIST SP 811 §8.7](https://www.nist.gov/pml/special-publication-811/nist-guide-si-chapter-8)

</details>

**0142.** ［計算題］走道乙為 -108 dBm，門檻 -105 dBm。相對門檻差是多少 dB？

<details><summary>看答案</summary>

**答案**　-3 dB。

**詳解**　算式 `−108−(−105) = -3` dB。

**出處**　[3GPP TS 38.215 §5.1.1](https://www.etsi.org/deliver/etsi_ts/138200_138299/138215/18.03.00_60/ts_138215v180300p.pdf) · [NIST SP 811 §8.7](https://www.nist.gov/pml/special-publication-811/nist-guide-si-chapter-8)

</details>

**0143.** 依題設驗收規則，哪個測點達標？

<details><summary>看答案</summary>

**答案**　走道甲達標。

**詳解**　比較原讀值與門檻，達標條件為不低於 -105 dBm。本題只有一個測點達到。

**出處**　[3GPP TS 38.215 §5.1.1](https://www.etsi.org/deliver/etsi_ts/138200_138299/138215/18.03.00_60/ts_138215v180300p.pdf)

</details>

**0144.** 若其中一個測點符合 RSRP 門檻，能把未量測的區域一併判為達標嗎？

<details><summary>看答案</summary>

**答案**　未量測的區域需要單獨抽測。

**詳解**　RSRP 隨位置、波束、遮蔽與接收條件而變。單點讀值只代表該量測條件和位置。

**出處**　[3GPP TS 38.215 §5.1.1](https://www.etsi.org/deliver/etsi_ts/138200_138299/138215/18.03.00_60/ts_138215v180300p.pdf)

</details>

**0145.** 將這個門檻移用到另一頻段前，應確認哪種依據？

<details><summary>看答案</summary>

**答案**　查驗收規則是否覆蓋新頻段，並確認量測對象及接收設定一致。

**詳解**　本題門檻來自案例設定。TS 38.215 定義量測項目，業者驗收門檻依具體服務與部署制定。

**出處**　[3GPP TS 38.215 §5.1.1](https://www.etsi.org/deliver/etsi_ts/138200_138299/138215/18.03.00_60/ts_138215v180300p.pdf)

</details>

**情境 031｜偏鄉衛生站外圍**

使用同一 SS-RSRP 設定，門口為 -98 dBm，坡頂為 -91 dBm。這項抽測以 ≥ -95 dBm 作為站內驗收門檻。

**0151.** ［計算題］門口為 -98 dBm，門檻 -95 dBm。相對門檻高出多少 dB？低於以負值表示。

<details><summary>看答案</summary>

**答案**　-3 dB。

**詳解**　算式 `−98−(−95) = -3` dB。

**出處**　[3GPP TS 38.215 §5.1.1](https://www.etsi.org/deliver/etsi_ts/138200_138299/138215/18.03.00_60/ts_138215v180300p.pdf) · [NIST SP 811 §8.7](https://www.nist.gov/pml/special-publication-811/nist-guide-si-chapter-8)

</details>

**0152.** ［計算題］坡頂為 -91 dBm，門檻 -95 dBm。相對門檻差是多少 dB？

<details><summary>看答案</summary>

**答案**　4 dB。

**詳解**　算式 `−91−(−95) = 4` dB。

**出處**　[3GPP TS 38.215 §5.1.1](https://www.etsi.org/deliver/etsi_ts/138200_138299/138215/18.03.00_60/ts_138215v180300p.pdf) · [NIST SP 811 §8.7](https://www.nist.gov/pml/special-publication-811/nist-guide-si-chapter-8)

</details>

**0153.** 依題設驗收規則，哪個測點達標？

<details><summary>看答案</summary>

**答案**　坡頂達標。

**詳解**　比較原讀值與門檻，達標條件為不低於 -95 dBm。本題只有一個測點達到。

**出處**　[3GPP TS 38.215 §5.1.1](https://www.etsi.org/deliver/etsi_ts/138200_138299/138215/18.03.00_60/ts_138215v180300p.pdf)

</details>

**0154.** 若其中一個測點符合 RSRP 門檻，能把未量測的區域一併判為達標嗎？

<details><summary>看答案</summary>

**答案**　未量測的區域需要單獨抽測。

**詳解**　RSRP 隨位置、波束、遮蔽與接收條件而變。單點讀值只代表該量測條件和位置。

**出處**　[3GPP TS 38.215 §5.1.1](https://www.etsi.org/deliver/etsi_ts/138200_138299/138215/18.03.00_60/ts_138215v180300p.pdf)

</details>

**0155.** 將這個門檻移用到另一頻段前，應確認哪種依據？

<details><summary>看答案</summary>

**答案**　查驗收規則是否覆蓋新頻段，並確認量測對象及接收設定一致。

**詳解**　本題門檻來自案例設定。TS 38.215 定義量測項目，業者驗收門檻依具體服務與部署制定。

**出處**　[3GPP TS 38.215 §5.1.1](https://www.etsi.org/deliver/etsi_ts/138200_138299/138215/18.03.00_60/ts_138215v180300p.pdf)

</details>

**情境 032｜科學園區北門**

使用同一 SS-RSRP 設定，崗哨為 -89 dBm，停車口為 -97 dBm。這項抽測以 ≥ -94 dBm 作為站內驗收門檻。

**0156.** ［計算題］崗哨為 -89 dBm，門檻 -94 dBm。相對門檻高出多少 dB？低於以負值表示。

<details><summary>看答案</summary>

**答案**　5 dB。

**詳解**　算式 `−89−(−94) = 5` dB。

**出處**　[3GPP TS 38.215 §5.1.1](https://www.etsi.org/deliver/etsi_ts/138200_138299/138215/18.03.00_60/ts_138215v180300p.pdf) · [NIST SP 811 §8.7](https://www.nist.gov/pml/special-publication-811/nist-guide-si-chapter-8)

</details>

**0157.** ［計算題］停車口為 -97 dBm，門檻 -94 dBm。相對門檻差是多少 dB？

<details><summary>看答案</summary>

**答案**　-3 dB。

**詳解**　算式 `−97−(−94) = -3` dB。

**出處**　[3GPP TS 38.215 §5.1.1](https://www.etsi.org/deliver/etsi_ts/138200_138299/138215/18.03.00_60/ts_138215v180300p.pdf) · [NIST SP 811 §8.7](https://www.nist.gov/pml/special-publication-811/nist-guide-si-chapter-8)

</details>

**0158.** 依題設驗收規則，哪個測點達標？

<details><summary>看答案</summary>

**答案**　崗哨達標。

**詳解**　比較原讀值與門檻，達標條件為不低於 -94 dBm。本題只有一個測點達到。

**出處**　[3GPP TS 38.215 §5.1.1](https://www.etsi.org/deliver/etsi_ts/138200_138299/138215/18.03.00_60/ts_138215v180300p.pdf)

</details>

**情境 033｜港區夜間工作面**

使用同一 SS-RSRP 設定，起重區為 -107 dBm，門禁區為 -103 dBm。這項抽測以 ≥ -106 dBm 作為站內驗收門檻。

**0161.** ［計算題］起重區為 -107 dBm，門檻 -106 dBm。相對門檻高出多少 dB？低於以負值表示。

<details><summary>看答案</summary>

**答案**　-1 dB。

**詳解**　算式 `−107−(−106) = -1` dB。

**出處**　[3GPP TS 38.215 §5.1.1](https://www.etsi.org/deliver/etsi_ts/138200_138299/138215/18.03.00_60/ts_138215v180300p.pdf) · [NIST SP 811 §8.7](https://www.nist.gov/pml/special-publication-811/nist-guide-si-chapter-8)

</details>

**0162.** ［計算題］門禁區為 -103 dBm，門檻 -106 dBm。相對門檻差是多少 dB？

<details><summary>看答案</summary>

**答案**　3 dB。

**詳解**　算式 `−103−(−106) = 3` dB。

**出處**　[3GPP TS 38.215 §5.1.1](https://www.etsi.org/deliver/etsi_ts/138200_138299/138215/18.03.00_60/ts_138215v180300p.pdf) · [NIST SP 811 §8.7](https://www.nist.gov/pml/special-publication-811/nist-guide-si-chapter-8)

</details>

**0163.** 依題設驗收規則，哪個測點達標？

<details><summary>看答案</summary>

**答案**　門禁區達標。

**詳解**　比較原讀值與門檻，達標條件為不低於 -106 dBm。本題只有一個測點達到。

**出處**　[3GPP TS 38.215 §5.1.1](https://www.etsi.org/deliver/etsi_ts/138200_138299/138215/18.03.00_60/ts_138215v180300p.pdf)

</details>

## 1.6.2 訊號品質：RSRQ、SINR、CQI

### 1. SS-RSRQ 同資源計算

**情境 034｜站廳同頻量測**

SS-RSRP 為 2 nW，NR carrier RSSI 為 240 nW，兩者使用同一組 24 個資源區塊。

**0166.** ［計算題］若 SS-RSRP＝2 nW、NR carrier RSSI＝240 nW、N＝24，請求 SS-RSRQ 的線性比值。（四捨五入至小數第 4 位）

<details><summary>看答案</summary>

**答案**　0.2000。

**詳解**　分子為 N 乘參考訊號功率，分母為同一組資源區塊的 RSSI。 算式 `24 × 2 ÷ 240 = 0.2000`。

**出處**　[3GPP TS 38.215 §5.1.3](https://www.etsi.org/deliver/etsi_ts/138200_138299/138215/18.03.00_60/ts_138215v180300p.pdf)

</details>

**0167.** ［計算題］根據 SS-RSRP 2 nW、NR carrier RSSI 240 nW、N＝24，將 SS-RSRQ 換成 dB，取小數第二位。

<details><summary>看答案</summary>

**答案**　-6.99 dB。

**詳解**　算式 `10 × log₁₀(24 × 2 ÷ 240) ≈ -6.99` dB。

**出處**　[3GPP TS 38.215 §5.1.3](https://www.etsi.org/deliver/etsi_ts/138200_138299/138215/18.03.00_60/ts_138215v180300p.pdf) · [NIST SP 811 §8.7](https://www.nist.gov/pml/special-publication-811/nist-guide-si-chapter-8)

</details>

**0168.** ［計算題］若 SS-RSRP 維持 2 nW、N 維持 24，要使 SS-RSRQ 線性值正好為 0.25，對應的 NR carrier RSSI 是多少？（四捨五入至小數第 2 位）

<details><summary>看答案</summary>

**答案**　192.00 nW。

**詳解**　由定義式移項，以 N × SS-RSRP 除以線性目標值。 算式 `24 × 2 ÷ 0.25 = 192.00` nW。

**出處**　[3GPP TS 38.215 §5.1.3](https://www.etsi.org/deliver/etsi_ts/138200_138299/138215/18.03.00_60/ts_138215v180300p.pdf)

</details>

**0169.** 若分子取本波束資料，分母改用不同資源區塊集合的讀值，能否作為 SS-RSRQ？

<details><summary>看答案</summary>

**答案**　應先取得屬於同一組資源區塊的量測。

**詳解**　TS 38.215 要求分子與分母使用同一組資源區塊。數字即使有相同單位，也必須核對實際量測集合。

**出處**　[3GPP TS 38.215 §5.1.3](https://www.etsi.org/deliver/etsi_ts/138200_138299/138215/18.03.00_60/ts_138215v180300p.pdf)

</details>

**0170.** 在 SS-RSRP 和 N 固定的受控比較中，若 NR carrier RSSI 升高，SS-RSRQ 會往哪個方向變化？

<details><summary>看答案</summary>

**答案**　線性比值下降，換成 dB 後也下降。

**詳解**　固定的分子除以較大的正分母會變小。RSSI 的變化可能來自不只一種接收成分。

**出處**　[3GPP TS 38.215 §5.1.3](https://www.etsi.org/deliver/etsi_ts/138200_138299/138215/18.03.00_60/ts_138215v180300p.pdf)

</details>

**情境 036｜住宅小區同步掃描**

SS-RSRP 為 2 nW，NR carrier RSSI 為 800 nW，兩者使用同一組 48 個資源區塊。

**0176.** ［計算題］若 SS-RSRP＝2 nW、NR carrier RSSI＝800 nW、N＝48，請求 SS-RSRQ 的線性比值。（四捨五入至小數第 4 位）

<details><summary>看答案</summary>

**答案**　0.1200。

**詳解**　分子為 N 乘參考訊號功率，分母為同一組資源區塊的 RSSI。 算式 `48 × 2 ÷ 800 = 0.1200`。

**出處**　[3GPP TS 38.215 §5.1.3](https://www.etsi.org/deliver/etsi_ts/138200_138299/138215/18.03.00_60/ts_138215v180300p.pdf)

</details>

**0177.** ［計算題］根據 SS-RSRP 2 nW、NR carrier RSSI 800 nW、N＝48，將 SS-RSRQ 換成 dB，取小數第二位。

<details><summary>看答案</summary>

**答案**　-9.21 dB。

**詳解**　算式 `10 × log₁₀(48 × 2 ÷ 800) ≈ -9.21` dB。

**出處**　[3GPP TS 38.215 §5.1.3](https://www.etsi.org/deliver/etsi_ts/138200_138299/138215/18.03.00_60/ts_138215v180300p.pdf) · [NIST SP 811 §8.7](https://www.nist.gov/pml/special-publication-811/nist-guide-si-chapter-8)

</details>

**0178.** ［計算題］若 SS-RSRP 維持 2 nW、N 維持 48，要使 SS-RSRQ 線性值正好為 0.16，對應的 NR carrier RSSI 是多少？（四捨五入至小數第 2 位）

<details><summary>看答案</summary>

**答案**　600.00 nW。

**詳解**　由定義式移項，以 N × SS-RSRP 除以線性目標值。 算式 `48 × 2 ÷ 0.16 = 600.00` nW。

**出處**　[3GPP TS 38.215 §5.1.3](https://www.etsi.org/deliver/etsi_ts/138200_138299/138215/18.03.00_60/ts_138215v180300p.pdf)

</details>

**0179.** 若分子取本波束資料，分母改用不同資源區塊集合的讀值，能否作為 SS-RSRQ？

<details><summary>看答案</summary>

**答案**　應先取得屬於同一組資源區塊的量測。

**詳解**　TS 38.215 要求分子與分母使用同一組資源區塊。數字即使有相同單位，也必須核對實際量測集合。

**出處**　[3GPP TS 38.215 §5.1.3](https://www.etsi.org/deliver/etsi_ts/138200_138299/138215/18.03.00_60/ts_138215v180300p.pdf)

</details>

**0180.** 在 SS-RSRP 和 N 固定的受控比較中，若 NR carrier RSSI 升高，SS-RSRQ 會往哪個方向變化？

<details><summary>看答案</summary>

**答案**　線性比值下降，換成 dB 後也下降。

**詳解**　固定的分子除以較大的正分母會變小。RSSI 的變化可能來自不只一種接收成分。

**出處**　[3GPP TS 38.215 §5.1.3](https://www.etsi.org/deliver/etsi_ts/138200_138299/138215/18.03.00_60/ts_138215v180300p.pdf)

</details>

**情境 037｜隧道入段同步量測**

SS-RSRP 為 5 nW，NR carrier RSSI 為 500 nW，兩者使用同一組 20 個資源區塊。

**0181.** ［計算題］若 SS-RSRP＝5 nW、NR carrier RSSI＝500 nW、N＝20，請求 SS-RSRQ 的線性比值。（四捨五入至小數第 4 位）

<details><summary>看答案</summary>

**答案**　0.2000。

**詳解**　分子為 N 乘參考訊號功率，分母為同一組資源區塊的 RSSI。 算式 `20 × 5 ÷ 500 = 0.2000`。

**出處**　[3GPP TS 38.215 §5.1.3](https://www.etsi.org/deliver/etsi_ts/138200_138299/138215/18.03.00_60/ts_138215v180300p.pdf)

</details>

**0182.** ［計算題］根據 SS-RSRP 5 nW、NR carrier RSSI 500 nW、N＝20，將 SS-RSRQ 換成 dB，取小數第二位。

<details><summary>看答案</summary>

**答案**　-6.99 dB。

**詳解**　算式 `10 × log₁₀(20 × 5 ÷ 500) ≈ -6.99` dB。

**出處**　[3GPP TS 38.215 §5.1.3](https://www.etsi.org/deliver/etsi_ts/138200_138299/138215/18.03.00_60/ts_138215v180300p.pdf) · [NIST SP 811 §8.7](https://www.nist.gov/pml/special-publication-811/nist-guide-si-chapter-8)

</details>

**0183.** ［計算題］若 SS-RSRP 維持 5 nW、N 維持 20，要使 SS-RSRQ 線性值正好為 0.4，對應的 NR carrier RSSI 是多少？（四捨五入至小數第 2 位）

<details><summary>看答案</summary>

**答案**　250.00 nW。

**詳解**　由定義式移項，以 N × SS-RSRP 除以線性目標值。 算式 `20 × 5 ÷ 0.4 = 250.00` nW。

**出處**　[3GPP TS 38.215 §5.1.3](https://www.etsi.org/deliver/etsi_ts/138200_138299/138215/18.03.00_60/ts_138215v180300p.pdf)

</details>

**情境 038｜高架匝道同步回報**

SS-RSRP 為 1 nW，NR carrier RSSI 為 300 nW，兩者使用同一組 36 個資源區塊。

**0186.** ［計算題］若 SS-RSRP＝1 nW、NR carrier RSSI＝300 nW、N＝36，請求 SS-RSRQ 的線性比值。（四捨五入至小數第 4 位）

<details><summary>看答案</summary>

**答案**　0.1200。

**詳解**　分子為 N 乘參考訊號功率，分母為同一組資源區塊的 RSSI。 算式 `36 × 1 ÷ 300 = 0.1200`。

**出處**　[3GPP TS 38.215 §5.1.3](https://www.etsi.org/deliver/etsi_ts/138200_138299/138215/18.03.00_60/ts_138215v180300p.pdf)

</details>

**0187.** ［計算題］根據 SS-RSRP 1 nW、NR carrier RSSI 300 nW、N＝36，將 SS-RSRQ 換成 dB，取小數第二位。

<details><summary>看答案</summary>

**答案**　-9.21 dB。

**詳解**　算式 `10 × log₁₀(36 × 1 ÷ 300) ≈ -9.21` dB。

**出處**　[3GPP TS 38.215 §5.1.3](https://www.etsi.org/deliver/etsi_ts/138200_138299/138215/18.03.00_60/ts_138215v180300p.pdf) · [NIST SP 811 §8.7](https://www.nist.gov/pml/special-publication-811/nist-guide-si-chapter-8)

</details>

**0188.** ［計算題］若 SS-RSRP 維持 1 nW、N 維持 36，要使 SS-RSRQ 線性值正好為 0.12，對應的 NR carrier RSSI 是多少？（四捨五入至小數第 2 位）

<details><summary>看答案</summary>

**答案**　300.00 nW。

**詳解**　由定義式移項，以 N × SS-RSRP 除以線性目標值。 算式 `36 × 1 ÷ 0.12 = 300.00` nW。

**出處**　[3GPP TS 38.215 §5.1.3](https://www.etsi.org/deliver/etsi_ts/138200_138299/138215/18.03.00_60/ts_138215v180300p.pdf)

</details>

**情境 039｜戶外廣場同步品質**

SS-RSRP 為 4 nW，NR carrier RSSI 為 1000 nW，兩者使用同一組 50 個資源區塊。

**0191.** ［計算題］若 SS-RSRP＝4 nW、NR carrier RSSI＝1000 nW、N＝50，請求 SS-RSRQ 的線性比值。（四捨五入至小數第 4 位）

<details><summary>看答案</summary>

**答案**　0.2000。

**詳解**　分子為 N 乘參考訊號功率，分母為同一組資源區塊的 RSSI。 算式 `50 × 4 ÷ 1000 = 0.2000`。

**出處**　[3GPP TS 38.215 §5.1.3](https://www.etsi.org/deliver/etsi_ts/138200_138299/138215/18.03.00_60/ts_138215v180300p.pdf)

</details>

**0192.** ［計算題］根據 SS-RSRP 4 nW、NR carrier RSSI 1000 nW、N＝50，將 SS-RSRQ 換成 dB，取小數第二位。

<details><summary>看答案</summary>

**答案**　-6.99 dB。

**詳解**　算式 `10 × log₁₀(50 × 4 ÷ 1000) ≈ -6.99` dB。

**出處**　[3GPP TS 38.215 §5.1.3](https://www.etsi.org/deliver/etsi_ts/138200_138299/138215/18.03.00_60/ts_138215v180300p.pdf) · [NIST SP 811 §8.7](https://www.nist.gov/pml/special-publication-811/nist-guide-si-chapter-8)

</details>

**0193.** ［計算題］若 SS-RSRP 維持 4 nW、N 維持 50，要使 SS-RSRQ 線性值正好為 0.25，對應的 NR carrier RSSI 是多少？（四捨五入至小數第 2 位）

<details><summary>看答案</summary>

**答案**　800.00 nW。

**詳解**　由定義式移項，以 N × SS-RSRP 除以線性目標值。 算式 `50 × 4 ÷ 0.25 = 800.00` nW。

**出處**　[3GPP TS 38.215 §5.1.3](https://www.etsi.org/deliver/etsi_ts/138200_138299/138215/18.03.00_60/ts_138215v180300p.pdf)

</details>

### 2. CSI-RSRQ 與 CSI-RSSI

**情境 040｜工廠專網 CSI 探測**

CSI-RSRP 為 2 nW，CSI-RSSI 為 400 nW，兩者使用同一組 30 個資源區塊。

**0196.** ［計算題］若 CSI-RSRP＝2 nW、CSI-RSSI＝400 nW、N＝30，請求 CSI-RSRQ 的線性比值。（四捨五入至小數第 4 位）

<details><summary>看答案</summary>

**答案**　0.1500。

**詳解**　分子為 N 乘參考訊號功率，分母為同一組資源區塊的 RSSI。 算式 `30 × 2 ÷ 400 = 0.1500`。

**出處**　[3GPP TS 38.215 §5.1.4](https://www.etsi.org/deliver/etsi_ts/138200_138299/138215/18.03.00_60/ts_138215v180300p.pdf)

</details>

**0197.** ［計算題］根據 CSI-RSRP 2 nW、CSI-RSSI 400 nW、N＝30，將 CSI-RSRQ 換成 dB，取小數第二位。

<details><summary>看答案</summary>

**答案**　-8.24 dB。

**詳解**　算式 `10 × log₁₀(30 × 2 ÷ 400) ≈ -8.24` dB。

**出處**　[3GPP TS 38.215 §5.1.4](https://www.etsi.org/deliver/etsi_ts/138200_138299/138215/18.03.00_60/ts_138215v180300p.pdf) · [NIST SP 811 §8.7](https://www.nist.gov/pml/special-publication-811/nist-guide-si-chapter-8)

</details>

**0198.** ［計算題］若 CSI-RSRP 維持 2 nW、N 維持 30，要使 CSI-RSRQ 線性值正好為 0.24，對應的 CSI-RSSI 是多少？（四捨五入至小數第 2 位）

<details><summary>看答案</summary>

**答案**　250.00 nW。

**詳解**　由定義式移項，以 N × CSI-RSRP 除以線性目標值。 算式 `30 × 2 ÷ 0.24 = 250.00` nW。

**出處**　[3GPP TS 38.215 §5.1.4](https://www.etsi.org/deliver/etsi_ts/138200_138299/138215/18.03.00_60/ts_138215v180300p.pdf)

</details>

**0199.** 若分子取本波束資料，分母改用不同資源區塊集合的讀值，能否作為 CSI-RSRQ？

<details><summary>看答案</summary>

**答案**　應先取得屬於同一組資源區塊的量測。

**詳解**　TS 38.215 要求分子與分母使用同一組資源區塊。數字即使有相同單位，也必須核對實際量測集合。

**出處**　[3GPP TS 38.215 §5.1.4](https://www.etsi.org/deliver/etsi_ts/138200_138299/138215/18.03.00_60/ts_138215v180300p.pdf)

</details>

**0200.** 在 CSI-RSRP 和 N 固定的受控比較中，若 CSI-RSSI 升高，CSI-RSRQ 會往哪個方向變化？

<details><summary>看答案</summary>

**答案**　線性比值下降，換成 dB 後也下降。

**詳解**　固定的分子除以較大的正分母會變小。RSSI 的變化可能來自不只一種接收成分。

**出處**　[3GPP TS 38.215 §5.1.4](https://www.etsi.org/deliver/etsi_ts/138200_138299/138215/18.03.00_60/ts_138215v180300p.pdf)

</details>

**情境 041｜倉庫波束 CSI 巡檢**

CSI-RSRP 為 3 nW，CSI-RSSI 為 640 nW，兩者使用同一組 32 個資源區塊。

**0201.** ［計算題］若 CSI-RSRP＝3 nW、CSI-RSSI＝640 nW、N＝32，請求 CSI-RSRQ 的線性比值。（四捨五入至小數第 4 位）

<details><summary>看答案</summary>

**答案**　0.1500。

**詳解**　分子為 N 乘參考訊號功率，分母為同一組資源區塊的 RSSI。 算式 `32 × 3 ÷ 640 = 0.1500`。

**出處**　[3GPP TS 38.215 §5.1.4](https://www.etsi.org/deliver/etsi_ts/138200_138299/138215/18.03.00_60/ts_138215v180300p.pdf)

</details>

**0202.** ［計算題］根據 CSI-RSRP 3 nW、CSI-RSSI 640 nW、N＝32，將 CSI-RSRQ 換成 dB，取小數第二位。

<details><summary>看答案</summary>

**答案**　-8.24 dB。

**詳解**　算式 `10 × log₁₀(32 × 3 ÷ 640) ≈ -8.24` dB。

**出處**　[3GPP TS 38.215 §5.1.4](https://www.etsi.org/deliver/etsi_ts/138200_138299/138215/18.03.00_60/ts_138215v180300p.pdf) · [NIST SP 811 §8.7](https://www.nist.gov/pml/special-publication-811/nist-guide-si-chapter-8)

</details>

**0203.** ［計算題］若 CSI-RSRP 維持 3 nW、N 維持 32，要使 CSI-RSRQ 線性值正好為 0.3，對應的 CSI-RSSI 是多少？（四捨五入至小數第 2 位）

<details><summary>看答案</summary>

**答案**　320.00 nW。

**詳解**　由定義式移項，以 N × CSI-RSRP 除以線性目標值。 算式 `32 × 3 ÷ 0.3 = 320.00` nW。

**出處**　[3GPP TS 38.215 §5.1.4](https://www.etsi.org/deliver/etsi_ts/138200_138299/138215/18.03.00_60/ts_138215v180300p.pdf)

</details>

**0204.** 若分子取本波束資料，分母改用不同資源區塊集合的讀值，能否作為 CSI-RSRQ？

<details><summary>看答案</summary>

**答案**　應先取得屬於同一組資源區塊的量測。

**詳解**　TS 38.215 要求分子與分母使用同一組資源區塊。數字即使有相同單位，也必須核對實際量測集合。

**出處**　[3GPP TS 38.215 §5.1.4](https://www.etsi.org/deliver/etsi_ts/138200_138299/138215/18.03.00_60/ts_138215v180300p.pdf)

</details>

**0205.** 在 CSI-RSRP 和 N 固定的受控比較中，若 CSI-RSSI 升高，CSI-RSRQ 會往哪個方向變化？

<details><summary>看答案</summary>

**答案**　線性比值下降，換成 dB 後也下降。

**詳解**　固定的分子除以較大的正分母會變小。RSSI 的變化可能來自不只一種接收成分。

**出處**　[3GPP TS 38.215 §5.1.4](https://www.etsi.org/deliver/etsi_ts/138200_138299/138215/18.03.00_60/ts_138215v180300p.pdf)

</details>

**情境 042｜校舍配置 CSI 品質**

CSI-RSRP 為 4 nW，CSI-RSSI 為 800 nW，兩者使用同一組 25 個資源區塊。

**0206.** ［計算題］若 CSI-RSRP＝4 nW、CSI-RSSI＝800 nW、N＝25，請求 CSI-RSRQ 的線性比值。（四捨五入至小數第 4 位）

<details><summary>看答案</summary>

**答案**　0.1250。

**詳解**　分子為 N 乘參考訊號功率，分母為同一組資源區塊的 RSSI。 算式 `25 × 4 ÷ 800 = 0.1250`。

**出處**　[3GPP TS 38.215 §5.1.4](https://www.etsi.org/deliver/etsi_ts/138200_138299/138215/18.03.00_60/ts_138215v180300p.pdf)

</details>

**0207.** ［計算題］根據 CSI-RSRP 4 nW、CSI-RSSI 800 nW、N＝25，將 CSI-RSRQ 換成 dB，取小數第二位。

<details><summary>看答案</summary>

**答案**　-9.03 dB。

**詳解**　算式 `10 × log₁₀(25 × 4 ÷ 800) ≈ -9.03` dB。

**出處**　[3GPP TS 38.215 §5.1.4](https://www.etsi.org/deliver/etsi_ts/138200_138299/138215/18.03.00_60/ts_138215v180300p.pdf) · [NIST SP 811 §8.7](https://www.nist.gov/pml/special-publication-811/nist-guide-si-chapter-8)

</details>

**0208.** ［計算題］若 CSI-RSRP 維持 4 nW、N 維持 25，要使 CSI-RSRQ 線性值正好為 0.25，對應的 CSI-RSSI 是多少？（四捨五入至小數第 2 位）

<details><summary>看答案</summary>

**答案**　400.00 nW。

**詳解**　由定義式移項，以 N × CSI-RSRP 除以線性目標值。 算式 `25 × 4 ÷ 0.25 = 400.00` nW。

**出處**　[3GPP TS 38.215 §5.1.4](https://www.etsi.org/deliver/etsi_ts/138200_138299/138215/18.03.00_60/ts_138215v180300p.pdf)

</details>

**情境 043｜機廠測試 CSI 資源**

CSI-RSRP 為 2 nW，CSI-RSSI 為 900 nW，兩者使用同一組 45 個資源區塊。

**0211.** ［計算題］若 CSI-RSRP＝2 nW、CSI-RSSI＝900 nW、N＝45，請求 CSI-RSRQ 的線性比值。（四捨五入至小數第 4 位）

<details><summary>看答案</summary>

**答案**　0.1000。

**詳解**　分子為 N 乘參考訊號功率，分母為同一組資源區塊的 RSSI。 算式 `45 × 2 ÷ 900 = 0.1000`。

**出處**　[3GPP TS 38.215 §5.1.4](https://www.etsi.org/deliver/etsi_ts/138200_138299/138215/18.03.00_60/ts_138215v180300p.pdf)

</details>

**0212.** ［計算題］根據 CSI-RSRP 2 nW、CSI-RSSI 900 nW、N＝45，將 CSI-RSRQ 換成 dB，取小數第二位。

<details><summary>看答案</summary>

**答案**　-10.00 dB。

**詳解**　算式 `10 × log₁₀(45 × 2 ÷ 900) = -10.00` dB。

**出處**　[3GPP TS 38.215 §5.1.4](https://www.etsi.org/deliver/etsi_ts/138200_138299/138215/18.03.00_60/ts_138215v180300p.pdf) · [NIST SP 811 §8.7](https://www.nist.gov/pml/special-publication-811/nist-guide-si-chapter-8)

</details>

**0213.** ［計算題］若 CSI-RSRP 維持 2 nW、N 維持 45，要使 CSI-RSRQ 線性值正好為 0.15，對應的 CSI-RSSI 是多少？（四捨五入至小數第 2 位）

<details><summary>看答案</summary>

**答案**　600.00 nW。

**詳解**　由定義式移項，以 N × CSI-RSRP 除以線性目標值。 算式 `45 × 2 ÷ 0.15 = 600.00` nW。

**出處**　[3GPP TS 38.215 §5.1.4](https://www.etsi.org/deliver/etsi_ts/138200_138299/138215/18.03.00_60/ts_138215v180300p.pdf)

</details>

**情境 044｜展廳波束 CSI 對照**

CSI-RSRP 為 5 nW，CSI-RSSI 為 960 nW，兩者使用同一組 24 個資源區塊。

**0216.** ［計算題］若 CSI-RSRP＝5 nW、CSI-RSSI＝960 nW、N＝24，請求 CSI-RSRQ 的線性比值。（四捨五入至小數第 4 位）

<details><summary>看答案</summary>

**答案**　0.1250。

**詳解**　分子為 N 乘參考訊號功率，分母為同一組資源區塊的 RSSI。 算式 `24 × 5 ÷ 960 = 0.1250`。

**出處**　[3GPP TS 38.215 §5.1.4](https://www.etsi.org/deliver/etsi_ts/138200_138299/138215/18.03.00_60/ts_138215v180300p.pdf)

</details>

**0217.** ［計算題］根據 CSI-RSRP 5 nW、CSI-RSSI 960 nW、N＝24，將 CSI-RSRQ 換成 dB，取小數第二位。

<details><summary>看答案</summary>

**答案**　-9.03 dB。

**詳解**　算式 `10 × log₁₀(24 × 5 ÷ 960) ≈ -9.03` dB。

**出處**　[3GPP TS 38.215 §5.1.4](https://www.etsi.org/deliver/etsi_ts/138200_138299/138215/18.03.00_60/ts_138215v180300p.pdf) · [NIST SP 811 §8.7](https://www.nist.gov/pml/special-publication-811/nist-guide-si-chapter-8)

</details>

**0218.** ［計算題］若 CSI-RSRP 維持 5 nW、N 維持 24，要使 CSI-RSRQ 線性值正好為 0.2，對應的 CSI-RSSI 是多少？（四捨五入至小數第 2 位）

<details><summary>看答案</summary>

**答案**　600.00 nW。

**詳解**　由定義式移項，以 N × CSI-RSRP 除以線性目標值。 算式 `24 × 5 ÷ 0.2 = 600.00` nW。

**出處**　[3GPP TS 38.215 §5.1.4](https://www.etsi.org/deliver/etsi_ts/138200_138299/138215/18.03.00_60/ts_138215v180300p.pdf)

</details>

### 3. SINR 線性功率、對數與降干擾

**情境 047｜地下連通道匹配量測**

同一 SS 量測的題設線性等效功率為訊號 10 nW、干擾 3 nW 與雜訊 2 nW，已對齊規格要求的量測資源。

**0231.** ［計算題］訊號 10 nW、干擾 3 nW、雜訊 2 nW，線性 SINR 是多少？（四捨五入至小數第 4 位）

<details><summary>看答案</summary>

**答案**　2.0000。

**詳解**　先在線性尺度加總干擾和雜訊。 算式 `10 ÷ (3 + 2) = 2.0000`。

**出處**　[3GPP TS 38.215 §5.1.5](https://www.etsi.org/deliver/etsi_ts/138200_138299/138215/18.03.00_60/ts_138215v180300p.pdf)

</details>

**0232.** ［計算題］將訊號 10 nW 除以干擾 3 nW 與雜訊 2 nW 的總和，再以 dB 表示 SINR。（四捨五入至小數第 2 位）

<details><summary>看答案</summary>

**答案**　3.01 dB。

**詳解**　算式 `10 × log₁₀(10 ÷ (3 + 2)) ≈ 3.01` dB。

**出處**　[3GPP TS 38.215 §5.1.5](https://www.etsi.org/deliver/etsi_ts/138200_138299/138215/18.03.00_60/ts_138215v180300p.pdf) · [NIST SP 811 §8.7](https://www.nist.gov/pml/special-publication-811/nist-guide-si-chapter-8)

</details>

**0233.** ［計算題］訊號維持 10 nW、雜訊維持 2 nW，只把原干擾 3 nW 減半。新 SINR 是多少 dB？（四捨五入至小數第 2 位）

<details><summary>看答案</summary>

**答案**　4.56 dB。

**詳解**　只調整分母中的干擾項。 算式 `10 × log₁₀(10 ÷ (3 ÷ 2 + 2)) ≈ 4.56` dB。

**出處**　[3GPP TS 38.215 §5.1.5](https://www.etsi.org/deliver/etsi_ts/138200_138299/138215/18.03.00_60/ts_138215v180300p.pdf) · [NIST SP 811 §8.7](https://www.nist.gov/pml/special-publication-811/nist-guide-si-chapter-8)

</details>

**0234.** 求分母時可把干擾與雜訊的 dBm 讀值直接加總嗎？

<details><summary>看答案</summary>

**答案**　應先換成同一線性功率單位再加總。

**詳解**　以 dBm 表示的讀值相加不等於功率的線性總和。

**出處**　[NIST SP 811 §8.7](https://www.nist.gov/pml/special-publication-811/nist-guide-si-chapter-8)

</details>

**0235.** 若相同強度測點的 SINR 偏低，為何要先確認干擾與雜訊？

<details><summary>看答案</summary>

**答案**　相同的訊號功率可遇到不同的干擾與雜訊總功率。

**詳解**　分母上升會使 SINR 下降。線索應配合同波束與同時段的干擾量測核實。

**出處**　[3GPP TS 38.215 §5.1.5](https://www.etsi.org/deliver/etsi_ts/138200_138299/138215/18.03.00_60/ts_138215v180300p.pdf)

</details>

**情境 048｜工廠波束干擾掃描**

同一 CSI 量測的題設線性等效功率為訊號 45 nW、干擾 7 nW 與雜訊 2 nW，已對齊規格要求的量測資源。

**0236.** ［計算題］訊號 45 nW、干擾 7 nW、雜訊 2 nW，線性 SINR 是多少？（四捨五入至小數第 4 位）

<details><summary>看答案</summary>

**答案**　5.0000。

**詳解**　先在線性尺度加總干擾和雜訊。 算式 `45 ÷ (7 + 2) = 5.0000`。

**出處**　[3GPP TS 38.215 §5.1.6](https://www.etsi.org/deliver/etsi_ts/138200_138299/138215/18.03.00_60/ts_138215v180300p.pdf)

</details>

**0237.** ［計算題］將訊號 45 nW 除以干擾 7 nW 與雜訊 2 nW 的總和，再以 dB 表示 SINR。（四捨五入至小數第 2 位）

<details><summary>看答案</summary>

**答案**　6.99 dB。

**詳解**　算式 `10 × log₁₀(45 ÷ (7 + 2)) ≈ 6.99` dB。

**出處**　[3GPP TS 38.215 §5.1.6](https://www.etsi.org/deliver/etsi_ts/138200_138299/138215/18.03.00_60/ts_138215v180300p.pdf) · [NIST SP 811 §8.7](https://www.nist.gov/pml/special-publication-811/nist-guide-si-chapter-8)

</details>

**0238.** ［計算題］訊號維持 45 nW、雜訊維持 2 nW，只把原干擾 7 nW 減半。新 SINR 是多少 dB？（四捨五入至小數第 2 位）

<details><summary>看答案</summary>

**答案**　9.13 dB。

**詳解**　只調整分母中的干擾項。 算式 `10 × log₁₀(45 ÷ (7 ÷ 2 + 2)) ≈ 9.13` dB。

**出處**　[3GPP TS 38.215 §5.1.6](https://www.etsi.org/deliver/etsi_ts/138200_138299/138215/18.03.00_60/ts_138215v180300p.pdf) · [NIST SP 811 §8.7](https://www.nist.gov/pml/special-publication-811/nist-guide-si-chapter-8)

</details>

**0239.** 求分母時可把干擾與雜訊的 dBm 讀值直接加總嗎？

<details><summary>看答案</summary>

**答案**　應先換成同一線性功率單位再加總。

**詳解**　以 dBm 表示的讀值相加不等於功率的線性總和。

**出處**　[NIST SP 811 §8.7](https://www.nist.gov/pml/special-publication-811/nist-guide-si-chapter-8)

</details>

**0240.** 若相同強度測點的 SINR 偏低，為何要先確認干擾與雜訊？

<details><summary>看答案</summary>

**答案**　相同的訊號功率可遇到不同的干擾與雜訊總功率。

**詳解**　分母上升會使 SINR 下降。線索應配合同波束與同時段的干擾量測核實。

**出處**　[3GPP TS 38.215 §5.1.6](https://www.etsi.org/deliver/etsi_ts/138200_138299/138215/18.03.00_60/ts_138215v180300p.pdf)

</details>

**情境 049｜受控平台射頻擾動**

同一 CSI 量測的題設線性等效功率為訊號 32 nW、干擾 6 nW 與雜訊 2 nW，已對齊規格要求的量測資源。

**0241.** ［計算題］訊號 32 nW、干擾 6 nW、雜訊 2 nW，線性 SINR 是多少？（四捨五入至小數第 4 位）

<details><summary>看答案</summary>

**答案**　4.0000。

**詳解**　先在線性尺度加總干擾和雜訊。 算式 `32 ÷ (6 + 2) = 4.0000`。

**出處**　[3GPP TS 38.215 §5.1.6](https://www.etsi.org/deliver/etsi_ts/138200_138299/138215/18.03.00_60/ts_138215v180300p.pdf)

</details>

**0242.** ［計算題］將訊號 32 nW 除以干擾 6 nW 與雜訊 2 nW 的總和，再以 dB 表示 SINR。（四捨五入至小數第 2 位）

<details><summary>看答案</summary>

**答案**　6.02 dB。

**詳解**　算式 `10 × log₁₀(32 ÷ (6 + 2)) ≈ 6.02` dB。

**出處**　[3GPP TS 38.215 §5.1.6](https://www.etsi.org/deliver/etsi_ts/138200_138299/138215/18.03.00_60/ts_138215v180300p.pdf) · [NIST SP 811 §8.7](https://www.nist.gov/pml/special-publication-811/nist-guide-si-chapter-8)

</details>

**0243.** ［計算題］訊號維持 32 nW、雜訊維持 2 nW，只把原干擾 6 nW 減半。新 SINR 是多少 dB？（四捨五入至小數第 2 位）

<details><summary>看答案</summary>

**答案**　8.06 dB。

**詳解**　只調整分母中的干擾項。 算式 `10 × log₁₀(32 ÷ (6 ÷ 2 + 2)) ≈ 8.06` dB。

**出處**　[3GPP TS 38.215 §5.1.6](https://www.etsi.org/deliver/etsi_ts/138200_138299/138215/18.03.00_60/ts_138215v180300p.pdf) · [NIST SP 811 §8.7](https://www.nist.gov/pml/special-publication-811/nist-guide-si-chapter-8)

</details>

**情境 050｜校園鄰網比對**

同一 SS 量測的題設線性等效功率為訊號 20 nW、干擾 8 nW 與雜訊 2 nW，已對齊規格要求的量測資源。

**0246.** ［計算題］訊號 20 nW、干擾 8 nW、雜訊 2 nW，線性 SINR 是多少？（四捨五入至小數第 4 位）

<details><summary>看答案</summary>

**答案**　2.0000。

**詳解**　先在線性尺度加總干擾和雜訊。 算式 `20 ÷ (8 + 2) = 2.0000`。

**出處**　[3GPP TS 38.215 §5.1.5](https://www.etsi.org/deliver/etsi_ts/138200_138299/138215/18.03.00_60/ts_138215v180300p.pdf)

</details>

**0247.** ［計算題］將訊號 20 nW 除以干擾 8 nW 與雜訊 2 nW 的總和，再以 dB 表示 SINR。（四捨五入至小數第 2 位）

<details><summary>看答案</summary>

**答案**　3.01 dB。

**詳解**　算式 `10 × log₁₀(20 ÷ (8 + 2)) ≈ 3.01` dB。

**出處**　[3GPP TS 38.215 §5.1.5](https://www.etsi.org/deliver/etsi_ts/138200_138299/138215/18.03.00_60/ts_138215v180300p.pdf) · [NIST SP 811 §8.7](https://www.nist.gov/pml/special-publication-811/nist-guide-si-chapter-8)

</details>

**0248.** ［計算題］訊號維持 20 nW、雜訊維持 2 nW，只把原干擾 8 nW 減半。新 SINR 是多少 dB？（四捨五入至小數第 2 位）

<details><summary>看答案</summary>

**答案**　5.23 dB。

**詳解**　只調整分母中的干擾項。 算式 `10 × log₁₀(20 ÷ (8 ÷ 2 + 2)) ≈ 5.23` dB。

**出處**　[3GPP TS 38.215 §5.1.5](https://www.etsi.org/deliver/etsi_ts/138200_138299/138215/18.03.00_60/ts_138215v180300p.pdf) · [NIST SP 811 §8.7](https://www.nist.gov/pml/special-publication-811/nist-guide-si-chapter-8)

</details>

**情境 051｜小區射頻改頻前評估**

同一 CSI 量測的題設線性等效功率為訊號 12 nW、干擾 9 nW 與雜訊 3 nW，已對齊規格要求的量測資源。

**0251.** ［計算題］訊號 12 nW、干擾 9 nW、雜訊 3 nW，線性 SINR 是多少？（四捨五入至小數第 4 位）

<details><summary>看答案</summary>

**答案**　1.0000。

**詳解**　先在線性尺度加總干擾和雜訊。 算式 `12 ÷ (9 + 3) = 1.0000`。

**出處**　[3GPP TS 38.215 §5.1.6](https://www.etsi.org/deliver/etsi_ts/138200_138299/138215/18.03.00_60/ts_138215v180300p.pdf)

</details>

**0252.** ［計算題］將訊號 12 nW 除以干擾 9 nW 與雜訊 3 nW 的總和，再以 dB 表示 SINR。（四捨五入至小數第 2 位）

<details><summary>看答案</summary>

**答案**　0.00 dB。

**詳解**　算式 `10 × log₁₀(12 ÷ (9 + 3)) = 0.00` dB。

**出處**　[3GPP TS 38.215 §5.1.6](https://www.etsi.org/deliver/etsi_ts/138200_138299/138215/18.03.00_60/ts_138215v180300p.pdf) · [NIST SP 811 §8.7](https://www.nist.gov/pml/special-publication-811/nist-guide-si-chapter-8)

</details>

**0253.** ［計算題］訊號維持 12 nW、雜訊維持 3 nW，只把原干擾 9 nW 減半。新 SINR 是多少 dB？（四捨五入至小數第 2 位）

<details><summary>看答案</summary>

**答案**　2.04 dB。

**詳解**　只調整分母中的干擾項。 算式 `10 × log₁₀(12 ÷ (9 ÷ 2 + 3)) ≈ 2.04` dB。

**出處**　[3GPP TS 38.215 §5.1.6](https://www.etsi.org/deliver/etsi_ts/138200_138299/138215/18.03.00_60/ts_138215v180300p.pdf) · [NIST SP 811 §8.7](https://www.nist.gov/pml/special-publication-811/nist-guide-si-chapter-8)

</details>

### 4. 強度與品質的交叉判讀

**情境 052｜晚間商場服務退化**

開店時和閉店前採用同一 SS 量測資源集合配置。SS-RSRP 為 -83、-84 dBm，SS-SINR 為 17、2 dB，NR carrier RSSI 為 -62、-53 dBm。

**0256.** ［計算題］閉店前相對開店時的 SS-RSRP 改變多少？原值 -83 dBm，新值 -84 dBm。

<details><summary>看答案</summary>

**答案**　-1 dB。

**詳解**　算式 `−84−(−83) = -1` dB。

**出處**　[3GPP TS 38.215 §5.1.1](https://www.etsi.org/deliver/etsi_ts/138200_138299/138215/18.03.00_60/ts_138215v180300p.pdf) · [NIST SP 811 §8.7](https://www.nist.gov/pml/special-publication-811/nist-guide-si-chapter-8)

</details>

**0257.** ［計算題］以 17 dB 及 2 dB 的 SS-SINR 比較，閉店前的線性 SINR 是開店時的幾倍？（四捨五入至小數第 3 位）

<details><summary>看答案</summary>

**答案**　0.032 倍。

**詳解**　算式 `10^((2−(17)) ÷ 10) ≈ 0.032` 倍。

**出處**　[3GPP TS 38.215 §5.1.5](https://www.etsi.org/deliver/etsi_ts/138200_138299/138215/18.03.00_60/ts_138215v180300p.pdf) · [NIST SP 811 §8.7](https://www.nist.gov/pml/special-publication-811/nist-guide-si-chapter-8)

</details>

**0258.** ［計算題］RSSI 從 -62 dBm 變成 -53 dBm。依對數差，總接收功率增加多少 dB？

<details><summary>看答案</summary>

**答案**　9 dB。

**詳解**　算式 `−53−(−62) = 9` dB。

**出處**　[3GPP TS 38.215 §5.1.3](https://www.etsi.org/deliver/etsi_ts/138200_138299/138215/18.03.00_60/ts_138215v180300p.pdf) · [NIST SP 811 §8.7](https://www.nist.gov/pml/special-publication-811/nist-guide-si-chapter-8)

</details>

**0259.** 哪一點或時段的參考訊號品質較好？依據本案哪個量測？

<details><summary>看答案</summary>

**答案**　開店時的 SS-SINR 較高。

**詳解**　雖然參考訊號功率相近，開店時的 SS-SINR 為 17 dB，高於閉店前的 2 dB。

**出處**　[3GPP TS 38.215 §5.1.5](https://www.etsi.org/deliver/etsi_ts/138200_138299/138215/18.03.00_60/ts_138215v180300p.pdf)

</details>

**0260.** 閉店前若同時回報較低 CQI，可以直接把原因定為服務小區功率不足嗎？

<details><summary>看答案</summary>

**答案**　目前應優先驗證干擾、雜訊及量測／回報配置。

**詳解**　SS-RSRP 相近而 SINR 明顯變差。CQI 另取決於配置的表和參考資源，不能由單一 RSRP 值定因。

**出處**　[3GPP TS 38.215 §5.1.1](https://www.etsi.org/deliver/etsi_ts/138200_138299/138215/18.03.00_60/ts_138215v180300p.pdf) · [3GPP TS 38.215 §5.1.5](https://www.etsi.org/deliver/etsi_ts/138200_138299/138215/18.03.00_60/ts_138215v180300p.pdf) · [3GPP TS 38.214 §5.2.2.1](https://www.etsi.org/deliver/etsi_ts/138200_138299/138214/18.07.00_60/ts_138214v180700p.pdf)

</details>

**情境 053｜場館進場前後**

進場前和滿場時採用同一 SS 量測資源集合配置。SS-RSRP 為 -88、-87 dBm，SS-SINR 為 12、0 dB，NR carrier RSSI 為 -65、-55 dBm。

**0261.** ［計算題］滿場時相對進場前的 SS-RSRP 改變多少？原值 -88 dBm，新值 -87 dBm。

<details><summary>看答案</summary>

**答案**　1 dB。

**詳解**　算式 `−87−(−88) = 1` dB。

**出處**　[3GPP TS 38.215 §5.1.1](https://www.etsi.org/deliver/etsi_ts/138200_138299/138215/18.03.00_60/ts_138215v180300p.pdf) · [NIST SP 811 §8.7](https://www.nist.gov/pml/special-publication-811/nist-guide-si-chapter-8)

</details>

**0262.** ［計算題］以 12 dB 及 0 dB 的 SS-SINR 比較，滿場時的線性 SINR 是進場前的幾倍？（四捨五入至小數第 3 位）

<details><summary>看答案</summary>

**答案**　0.063 倍。

**詳解**　算式 `10^((0−(12)) ÷ 10) ≈ 0.063` 倍。

**出處**　[3GPP TS 38.215 §5.1.5](https://www.etsi.org/deliver/etsi_ts/138200_138299/138215/18.03.00_60/ts_138215v180300p.pdf) · [NIST SP 811 §8.7](https://www.nist.gov/pml/special-publication-811/nist-guide-si-chapter-8)

</details>

**0263.** ［計算題］RSSI 從 -65 dBm 變成 -55 dBm。依對數差，總接收功率增加多少 dB？

<details><summary>看答案</summary>

**答案**　10 dB。

**詳解**　算式 `−55−(−65) = 10` dB。

**出處**　[3GPP TS 38.215 §5.1.3](https://www.etsi.org/deliver/etsi_ts/138200_138299/138215/18.03.00_60/ts_138215v180300p.pdf) · [NIST SP 811 §8.7](https://www.nist.gov/pml/special-publication-811/nist-guide-si-chapter-8)

</details>

**0264.** 哪一點或時段的參考訊號品質較好？依據本案哪個量測？

<details><summary>看答案</summary>

**答案**　進場前的 SS-SINR 較高。

**詳解**　雖然參考訊號功率相近，進場前的 SS-SINR 為 12 dB，高於滿場時的 0 dB。

**出處**　[3GPP TS 38.215 §5.1.5](https://www.etsi.org/deliver/etsi_ts/138200_138299/138215/18.03.00_60/ts_138215v180300p.pdf)

</details>

**0265.** 滿場時若同時回報較低 CQI，可以直接把原因定為服務小區功率不足嗎？

<details><summary>看答案</summary>

**答案**　目前應優先驗證干擾、雜訊及量測／回報配置。

**詳解**　SS-RSRP 相近而 SINR 明顯變差。CQI 另取決於配置的表和參考資源，不能由單一 RSRP 值定因。

**出處**　[3GPP TS 38.215 §5.1.1](https://www.etsi.org/deliver/etsi_ts/138200_138299/138215/18.03.00_60/ts_138215v180300p.pdf) · [3GPP TS 38.215 §5.1.5](https://www.etsi.org/deliver/etsi_ts/138200_138299/138215/18.03.00_60/ts_138215v180300p.pdf) · [3GPP TS 38.214 §5.2.2.1](https://www.etsi.org/deliver/etsi_ts/138200_138299/138214/18.07.00_60/ts_138214v180700p.pdf)

</details>

**情境 054｜兩段月台走測**

北端和南端採用同一 SS 量測資源集合配置。SS-RSRP 為 -91、-90 dBm，SS-SINR 為 14、1 dB，NR carrier RSSI 為 -70、-59 dBm。

**0266.** ［計算題］南端相對北端的 SS-RSRP 改變多少？原值 -91 dBm，新值 -90 dBm。

<details><summary>看答案</summary>

**答案**　1 dB。

**詳解**　算式 `−90−(−91) = 1` dB。

**出處**　[3GPP TS 38.215 §5.1.1](https://www.etsi.org/deliver/etsi_ts/138200_138299/138215/18.03.00_60/ts_138215v180300p.pdf) · [NIST SP 811 §8.7](https://www.nist.gov/pml/special-publication-811/nist-guide-si-chapter-8)

</details>

**0267.** ［計算題］以 14 dB 及 1 dB 的 SS-SINR 比較，南端的線性 SINR 是北端的幾倍？（四捨五入至小數第 3 位）

<details><summary>看答案</summary>

**答案**　0.050 倍。

**詳解**　算式 `10^((1−(14)) ÷ 10) ≈ 0.050` 倍。

**出處**　[3GPP TS 38.215 §5.1.5](https://www.etsi.org/deliver/etsi_ts/138200_138299/138215/18.03.00_60/ts_138215v180300p.pdf) · [NIST SP 811 §8.7](https://www.nist.gov/pml/special-publication-811/nist-guide-si-chapter-8)

</details>

**0268.** ［計算題］RSSI 從 -70 dBm 變成 -59 dBm。依對數差，總接收功率增加多少 dB？

<details><summary>看答案</summary>

**答案**　11 dB。

**詳解**　算式 `−59−(−70) = 11` dB。

**出處**　[3GPP TS 38.215 §5.1.3](https://www.etsi.org/deliver/etsi_ts/138200_138299/138215/18.03.00_60/ts_138215v180300p.pdf) · [NIST SP 811 §8.7](https://www.nist.gov/pml/special-publication-811/nist-guide-si-chapter-8)

</details>

**0269.** 哪一點或時段的參考訊號品質較好？依據本案哪個量測？

<details><summary>看答案</summary>

**答案**　北端的 SS-SINR 較高。

**詳解**　雖然參考訊號功率相近，北端的 SS-SINR 為 14 dB，高於南端的 1 dB。

**出處**　[3GPP TS 38.215 §5.1.5](https://www.etsi.org/deliver/etsi_ts/138200_138299/138215/18.03.00_60/ts_138215v180300p.pdf)

</details>

**0270.** 南端若同時回報較低 CQI，可以直接把原因定為服務小區功率不足嗎？

<details><summary>看答案</summary>

**答案**　目前應優先驗證干擾、雜訊及量測／回報配置。

**詳解**　SS-RSRP 相近而 SINR 明顯變差。CQI 另取決於配置的表和參考資源，不能由單一 RSRP 值定因。

**出處**　[3GPP TS 38.215 §5.1.1](https://www.etsi.org/deliver/etsi_ts/138200_138299/138215/18.03.00_60/ts_138215v180300p.pdf) · [3GPP TS 38.215 §5.1.5](https://www.etsi.org/deliver/etsi_ts/138200_138299/138215/18.03.00_60/ts_138215v180300p.pdf) · [3GPP TS 38.214 §5.2.2.1](https://www.etsi.org/deliver/etsi_ts/138200_138299/138214/18.07.00_60/ts_138214v180700p.pdf)

</details>

**情境 055｜企業雙點定測**

一樓和夾層採用同一 SS 量測資源集合配置。SS-RSRP 為 -80、-80 dBm，SS-SINR 為 20、4 dB，NR carrier RSSI 為 -61、-51 dBm。

**0271.** ［計算題］夾層相對一樓的 SS-RSRP 改變多少？原值 -80 dBm，新值 -80 dBm。

<details><summary>看答案</summary>

**答案**　0 dB。

**詳解**　算式 `−80−(−80) = 0` dB。

**出處**　[3GPP TS 38.215 §5.1.1](https://www.etsi.org/deliver/etsi_ts/138200_138299/138215/18.03.00_60/ts_138215v180300p.pdf) · [NIST SP 811 §8.7](https://www.nist.gov/pml/special-publication-811/nist-guide-si-chapter-8)

</details>

**0272.** ［計算題］以 20 dB 及 4 dB 的 SS-SINR 比較，夾層的線性 SINR 是一樓的幾倍？（四捨五入至小數第 3 位）

<details><summary>看答案</summary>

**答案**　0.025 倍。

**詳解**　算式 `10^((4−(20)) ÷ 10) ≈ 0.025` 倍。

**出處**　[3GPP TS 38.215 §5.1.5](https://www.etsi.org/deliver/etsi_ts/138200_138299/138215/18.03.00_60/ts_138215v180300p.pdf) · [NIST SP 811 §8.7](https://www.nist.gov/pml/special-publication-811/nist-guide-si-chapter-8)

</details>

**0273.** ［計算題］RSSI 從 -61 dBm 變成 -51 dBm。依對數差，總接收功率增加多少 dB？

<details><summary>看答案</summary>

**答案**　10 dB。

**詳解**　算式 `−51−(−61) = 10` dB。

**出處**　[3GPP TS 38.215 §5.1.3](https://www.etsi.org/deliver/etsi_ts/138200_138299/138215/18.03.00_60/ts_138215v180300p.pdf) · [NIST SP 811 §8.7](https://www.nist.gov/pml/special-publication-811/nist-guide-si-chapter-8)

</details>

**0274.** 哪一點或時段的參考訊號品質較好？依據本案哪個量測？

<details><summary>看答案</summary>

**答案**　一樓的 SS-SINR 較高。

**詳解**　雖然參考訊號功率相近，一樓的 SS-SINR 為 20 dB，高於夾層的 4 dB。

**出處**　[3GPP TS 38.215 §5.1.5](https://www.etsi.org/deliver/etsi_ts/138200_138299/138215/18.03.00_60/ts_138215v180300p.pdf)

</details>

**0275.** 夾層若同時回報較低 CQI，可以直接把原因定為服務小區功率不足嗎？

<details><summary>看答案</summary>

**答案**　目前應優先驗證干擾、雜訊及量測／回報配置。

**詳解**　SS-RSRP 相近而 SINR 明顯變差。CQI 另取決於配置的表和參考資源，不能由單一 RSRP 值定因。

**出處**　[3GPP TS 38.215 §5.1.1](https://www.etsi.org/deliver/etsi_ts/138200_138299/138215/18.03.00_60/ts_138215v180300p.pdf) · [3GPP TS 38.215 §5.1.5](https://www.etsi.org/deliver/etsi_ts/138200_138299/138215/18.03.00_60/ts_138215v180300p.pdf) · [3GPP TS 38.214 §5.2.2.1](https://www.etsi.org/deliver/etsi_ts/138200_138299/138214/18.07.00_60/ts_138214v180700p.pdf)

</details>

### 5. CQI 候選索引與錯誤機率

**情境 058｜工廠寬頻 CQI 選擇**

依 TS 38.214 的 table2 條件，某參考資源只比較 CQI 6、7、8。題設錯誤機率由等量的 200 個傳輸區塊受控試驗估算，這三個索引分別有 7、17、30 個錯誤。假設其餘更高索引均超出門檻。

**0286.** ［計算題］CQI 6 有 7 個錯誤，總共 200 個傳輸區塊。其估計錯誤百分比為何？（四捨五入至小數第 6 位）

<details><summary>看答案</summary>

**答案**　3.500000%。

**詳解**　算式 `7 ÷ 200 × 100 = 3.500000`%。

**出處**　[3GPP TS 38.214 §5.2.2.1](https://www.etsi.org/deliver/etsi_ts/138200_138299/138214/18.07.00_60/ts_138214v180700p.pdf)

</details>

**0287.** ［計算題］CQI 7 與 8 分別錯 17 和 30 個，各測 200 個傳輸區塊。CQI 8 的錯誤百分比高出幾個百分點？（四捨五入至小數第 6 位）

<details><summary>看答案</summary>

**答案**　6.500000 個百分點。

**詳解**　算式 `(30−17) ÷ 200 × 100 = 6.500000` 個百分點。

**出處**　[3GPP TS 38.214 §5.2.2.1](https://www.etsi.org/deliver/etsi_ts/138200_138299/138214/18.07.00_60/ts_138214v180700p.pdf)

</details>

**0288.** ［計算題］門檻為機率 0.1，若共 200 個傳輸區塊，最多容許幾個錯誤才不超過門檻？

<details><summary>看答案</summary>

**答案**　20 個。

**詳解**　以總數乘機率門檻，允許次數取不高於上限的整數。 floor 表示向下取整。 算式 `floor(200 × 0.1) = 20` 個。

**出處**　[3GPP TS 38.214 §5.2.2.1](https://www.etsi.org/deliver/etsi_ts/138200_138299/138214/18.07.00_60/ts_138214v180700p.pdf)

</details>

**0289.** 依題設，最高可選哪個 CQI 候選索引？

<details><summary>看答案</summary>

**答案**　CQI 7。

**詳解**　CQI 6 與 7 的估計錯誤機率均不超過 0.1，CQI 8 超過。同時符合時選可符合條件的最高索引。

**出處**　[3GPP TS 38.214 §5.2.2.1](https://www.etsi.org/deliver/etsi_ts/138200_138299/138214/18.07.00_60/ts_138214v180700p.pdf)

</details>

**0290.** 只看實驗現場的 CQI 索引，能否直接認定實際調度的 MCS 索引相等？

<details><summary>看答案</summary>

**答案**　兩者須分別核對。

**詳解**　CQI 是終端對參考資源的通道品質回報。實際採用的 MCS 還取決於配置、調度及其他鏈路條件。

**出處**　[3GPP TS 38.214 §5.2.2.1](https://www.etsi.org/deliver/etsi_ts/138200_138299/138214/18.07.00_60/ts_138214v180700p.pdf) · [3GPP TS 38.214 §5.1.3.1](https://www.etsi.org/deliver/etsi_ts/138200_138299/138214/18.07.00_60/ts_138214v180700p.pdf)

</details>

**情境 059｜園區波束 CQI 回報**

依 TS 38.214 的 table1 條件，某參考資源只比較 CQI 6、7、8。題設錯誤機率由等量的 100 個傳輸區塊受控試驗估算，這三個索引分別有 2、9、12 個錯誤。假設其餘更高索引均超出門檻。

**0291.** ［計算題］CQI 6 有 2 個錯誤，總共 100 個傳輸區塊。其估計錯誤百分比為何？（四捨五入至小數第 6 位）

<details><summary>看答案</summary>

**答案**　2.000000%。

**詳解**　算式 `2 ÷ 100 × 100 = 2.000000`%。

**出處**　[3GPP TS 38.214 §5.2.2.1](https://www.etsi.org/deliver/etsi_ts/138200_138299/138214/18.07.00_60/ts_138214v180700p.pdf)

</details>

**0292.** ［計算題］CQI 7 與 8 分別錯 9 和 12 個，各測 100 個傳輸區塊。CQI 8 的錯誤百分比高出幾個百分點？（四捨五入至小數第 6 位）

<details><summary>看答案</summary>

**答案**　3.000000 個百分點。

**詳解**　算式 `(12−9) ÷ 100 × 100 = 3.000000` 個百分點。

**出處**　[3GPP TS 38.214 §5.2.2.1](https://www.etsi.org/deliver/etsi_ts/138200_138299/138214/18.07.00_60/ts_138214v180700p.pdf)

</details>

**0293.** ［計算題］門檻為機率 0.1，若共 100 個傳輸區塊，最多容許幾個錯誤才不超過門檻？

<details><summary>看答案</summary>

**答案**　10 個。

**詳解**　以總數乘機率門檻，允許次數取不高於上限的整數。 floor 表示向下取整。 算式 `floor(100 × 0.1) = 10` 個。

**出處**　[3GPP TS 38.214 §5.2.2.1](https://www.etsi.org/deliver/etsi_ts/138200_138299/138214/18.07.00_60/ts_138214v180700p.pdf)

</details>

**0294.** 依題設，最高可選哪個 CQI 候選索引？

<details><summary>看答案</summary>

**答案**　CQI 7。

**詳解**　CQI 6 與 7 的估計錯誤機率均不超過 0.1，CQI 8 超過。同時符合時選可符合條件的最高索引。

**出處**　[3GPP TS 38.214 §5.2.2.1](https://www.etsi.org/deliver/etsi_ts/138200_138299/138214/18.07.00_60/ts_138214v180700p.pdf)

</details>

**0295.** 只看實驗現場的 CQI 索引，能否直接認定實際調度的 MCS 索引相等？

<details><summary>看答案</summary>

**答案**　兩者須分別核對。

**詳解**　CQI 是終端對參考資源的通道品質回報。實際採用的 MCS 還取決於配置、調度及其他鏈路條件。

**出處**　[3GPP TS 38.214 §5.2.2.1](https://www.etsi.org/deliver/etsi_ts/138200_138299/138214/18.07.00_60/ts_138214v180700p.pdf) · [3GPP TS 38.214 §5.1.3.1](https://www.etsi.org/deliver/etsi_ts/138200_138299/138214/18.07.00_60/ts_138214v180700p.pdf)

</details>

**情境 060｜實驗室高可靠 CQI 測例**

依 TS 38.214 的 table3 條件，某參考資源只比較 CQI 6、7、8。題設錯誤機率由等量的 1000000 個傳輸區塊受控試驗估算，這三個索引分別有 2、8、14 個錯誤。假設其餘更高索引均超出門檻。

**0296.** ［計算題］CQI 6 有 2 個錯誤，總共 1000000 個傳輸區塊。其估計錯誤百分比為何？（四捨五入至小數第 6 位）

<details><summary>看答案</summary>

**答案**　0.000200%。

**詳解**　算式 `2 ÷ 1000000 × 100 = 0.000200`%。

**出處**　[3GPP TS 38.214 §5.2.2.1](https://www.etsi.org/deliver/etsi_ts/138200_138299/138214/18.07.00_60/ts_138214v180700p.pdf)

</details>

**0297.** ［計算題］CQI 7 與 8 分別錯 8 和 14 個，各測 1000000 個傳輸區塊。CQI 8 的錯誤百分比高出幾個百分點？（四捨五入至小數第 6 位）

<details><summary>看答案</summary>

**答案**　0.000600 個百分點。

**詳解**　算式 `(14−8) ÷ 1000000 × 100 = 0.000600` 個百分點。

**出處**　[3GPP TS 38.214 §5.2.2.1](https://www.etsi.org/deliver/etsi_ts/138200_138299/138214/18.07.00_60/ts_138214v180700p.pdf)

</details>

**0298.** ［計算題］門檻為機率 0.00001，若共 1000000 個傳輸區塊，最多容許幾個錯誤才不超過門檻？

<details><summary>看答案</summary>

**答案**　10 個。

**詳解**　以總數乘機率門檻，允許次數取不高於上限的整數。 floor 表示向下取整。 算式 `floor(1000000 × 0.00001) = 10` 個。

**出處**　[3GPP TS 38.214 §5.2.2.1](https://www.etsi.org/deliver/etsi_ts/138200_138299/138214/18.07.00_60/ts_138214v180700p.pdf)

</details>

**情境 061｜固定終端 CQI 門檻**

依 TS 38.214 的 table3 條件，某參考資源只比較 CQI 6、7、8。題設錯誤機率由等量的 2000000 個傳輸區塊受控試驗估算，這三個索引分別有 9、20、26 個錯誤。假設其餘更高索引均超出門檻。

**0301.** ［計算題］CQI 6 有 9 個錯誤，總共 2000000 個傳輸區塊。其估計錯誤百分比為何？（四捨五入至小數第 6 位）

<details><summary>看答案</summary>

**答案**　0.000450%。

**詳解**　算式 `9 ÷ 2000000 × 100 = 0.000450`%。

**出處**　[3GPP TS 38.214 §5.2.2.1](https://www.etsi.org/deliver/etsi_ts/138200_138299/138214/18.07.00_60/ts_138214v180700p.pdf)

</details>

**0302.** ［計算題］CQI 7 與 8 分別錯 20 和 26 個，各測 2000000 個傳輸區塊。CQI 8 的錯誤百分比高出幾個百分點？（四捨五入至小數第 6 位）

<details><summary>看答案</summary>

**答案**　0.000300 個百分點。

**詳解**　算式 `(26−20) ÷ 2000000 × 100 = 0.000300` 個百分點。

**出處**　[3GPP TS 38.214 §5.2.2.1](https://www.etsi.org/deliver/etsi_ts/138200_138299/138214/18.07.00_60/ts_138214v180700p.pdf)

</details>

**0303.** ［計算題］門檻為機率 0.00001，若共 2000000 個傳輸區塊，最多容許幾個錯誤才不超過門檻？

<details><summary>看答案</summary>

**答案**　20 個。

**詳解**　以總數乘機率門檻，允許次數取不高於上限的整數。 floor 表示向下取整。 算式 `floor(2000000 × 0.00001) = 20` 個。

**出處**　[3GPP TS 38.214 §5.2.2.1](https://www.etsi.org/deliver/etsi_ts/138200_138299/138214/18.07.00_60/ts_138214v180700p.pdf)

</details>

### 6. CQI 回報與 MCS 調度核對

**情境 062｜商圈調度觀測**

UE 回報 table1 的 CQI 10，工程師另取得兩筆實際下行配置，調變階數 Qₘ 分別為 2、4，編碼率分子分別為 449、490（分母 1024）。另抽測 200 個首傳區塊，13 個錯誤。配置數字直接由本題給定。

**0306.** ［計算題］第一筆 Qₘ＝2、目標編碼率 449/1024。忽略其他開銷，名目值 Qₘ × 編碼率為何？（四捨五入至小數第 4 位）

<details><summary>看答案</summary>

**答案**　0.8770 bit／調變符號。

**詳解**　算式 `2 × 449 ÷ 1024 ≈ 0.8770` bit／調變符號。

**出處**　[3GPP TS 38.214 §5.1.3.1](https://www.etsi.org/deliver/etsi_ts/138200_138299/138214/18.07.00_60/ts_138214v180700p.pdf)

</details>

**0307.** ［計算題］第一筆 Qₘ＝2、編碼率 449/1024，第二筆 Qₘ＝4、編碼率 490/1024。第二筆的 Qₘ × 編碼率比第一筆多多少？（四捨五入至小數第 4 位）

<details><summary>看答案</summary>

**答案**　1.0371 bit／調變符號。

**詳解**　算式 `(4 × 490−2 × 449) ÷ 1024 ≈ 1.0371` bit／調變符號。

**出處**　[3GPP TS 38.214 §5.1.3.1](https://www.etsi.org/deliver/etsi_ts/138200_138299/138214/18.07.00_60/ts_138214v180700p.pdf)

</details>

**0308.** ［計算題］抽測 200 個首傳區塊，其中 13 個錯誤，測得的首傳區塊錯誤百分比為何？（四捨五入至小數第 2 位）

<details><summary>看答案</summary>

**答案**　6.50%。

**詳解**　算式 `13 ÷ 200 × 100 = 6.50`%。

**出處**　[3GPP TS 28.552 §§5.1.1.7.1–5.1.1.7.2](https://www.etsi.org/deliver/etsi_ts/128500_128599/128552/19.06.00_60/ts_128552v190600p.pdf)

</details>

**0309.** 跨兩次測試比較 CQI 10 時，為何須一起記下 table1 這個配置？

<details><summary>看答案</summary>

**答案**　同一索引在不同 CQI 表的解釋和適用條件可能不同。

**詳解**　表的配置決定索引對應的調變／編碼描述及目標錯誤機率。

**出處**　[3GPP TS 38.214 §5.2.2.1](https://www.etsi.org/deliver/etsi_ts/138200_138299/138214/18.07.00_60/ts_138214v180700p.pdf)

</details>

**0310.** 若較高調變配置的計算名目值較大，可以推定應用層有效吞吐量必然較大嗎？

<details><summary>看答案</summary>

**答案**　仍需以實測的有效資料量與時間驗證。

**詳解**　排程資源、傳輸區塊大小、錯誤、重傳和應用開銷都會影響實際交付速率。

**出處**　[3GPP TS 38.214 §5.1.3.1](https://www.etsi.org/deliver/etsi_ts/138200_138299/138214/18.07.00_60/ts_138214v180700p.pdf) · [3GPP TS 28.552 §5.1.1.3](https://www.etsi.org/deliver/etsi_ts/128500_128599/128552/19.06.00_60/ts_128552v190600p.pdf)

</details>

**情境 063｜車站下行調度**

UE 回報 table2 的 CQI 11，工程師另取得兩筆實際下行配置，調變階數 Qₘ 分別為 4、6，編碼率分子分別為 378、466（分母 1024）。另抽測 400 個首傳區塊，28 個錯誤。配置數字直接由本題給定。

**0311.** ［計算題］第一筆 Qₘ＝4、目標編碼率 378/1024。忽略其他開銷，名目值 Qₘ × 編碼率為何？（四捨五入至小數第 4 位）

<details><summary>看答案</summary>

**答案**　1.4766 bit／調變符號。

**詳解**　算式 `4 × 378 ÷ 1024 ≈ 1.4766` bit／調變符號。

**出處**　[3GPP TS 38.214 §5.1.3.1](https://www.etsi.org/deliver/etsi_ts/138200_138299/138214/18.07.00_60/ts_138214v180700p.pdf)

</details>

**0312.** ［計算題］第一筆 Qₘ＝4、編碼率 378/1024，第二筆 Qₘ＝6、編碼率 466/1024。第二筆的 Qₘ × 編碼率比第一筆多多少？（四捨五入至小數第 4 位）

<details><summary>看答案</summary>

**答案**　1.2539 bit／調變符號。

**詳解**　算式 `(6 × 466−4 × 378) ÷ 1024 ≈ 1.2539` bit／調變符號。

**出處**　[3GPP TS 38.214 §5.1.3.1](https://www.etsi.org/deliver/etsi_ts/138200_138299/138214/18.07.00_60/ts_138214v180700p.pdf)

</details>

**0313.** ［計算題］抽測 400 個首傳區塊，其中 28 個錯誤，測得的首傳區塊錯誤百分比為何？（四捨五入至小數第 2 位）

<details><summary>看答案</summary>

**答案**　7.00%。

**詳解**　算式 `28 ÷ 400 × 100 = 7.00`%。

**出處**　[3GPP TS 28.552 §§5.1.1.7.1–5.1.1.7.2](https://www.etsi.org/deliver/etsi_ts/128500_128599/128552/19.06.00_60/ts_128552v190600p.pdf)

</details>

**0314.** 跨兩次測試比較 CQI 11 時，為何須一起記下 table2 這個配置？

<details><summary>看答案</summary>

**答案**　同一索引在不同 CQI 表的解釋和適用條件可能不同。

**詳解**　表的配置決定索引對應的調變／編碼描述及目標錯誤機率。

**出處**　[3GPP TS 38.214 §5.2.2.1](https://www.etsi.org/deliver/etsi_ts/138200_138299/138214/18.07.00_60/ts_138214v180700p.pdf)

</details>

頁次：**1**　[2](1-6-bank-2.md)　[3](1-6-bank-3.md)　[4](1-6-bank-4.md)
