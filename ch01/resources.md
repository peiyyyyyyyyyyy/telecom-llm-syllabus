# 網路題庫與外部練習

| 適用章節 | 公開練習 | 作答與核對方式 |
| --- | --- | --- |
| 1.1、1.2 | [UMass 4G 無線隧道](https://gaia.cs.umass.edu/kurose_ross/interactive/4g_tunneling.php) | 沿路徑依序核對內外層位址與傳輸協定，題頁提供解答。 |
| 1.2 | [UMass 子網定址](https://gaia.cs.umass.edu/kurose_ross/interactive/subnet_addressing.php) | 練習配置 CIDR 子網、廣播位址及主機位址。 |
| 1.6 | [UMass 端到端吞吐量](https://gaia.cs.umass.edu/kurose_ross/interactive/end-end-throughput-simple.php) | 練習共享鏈路的瓶頸與利用率，題頁提供算式。 |
| 1.7 | [UMass 4G 換手](https://gaia.cs.umass.edu/kurose_ross/interactive/4g_handover.php) | 先追蹤 LTE 行動性訊息和資料轉送，再用題頁解答核對。 |
| 1.8 | [Google SRE 事故案例](https://sre.google/workbook/incident-response/) | 先讀事故線索，寫出分工、處置與驗證方式，再對照案例經過。 |
| 1.2、1.6 進階 | [MIT 6.829 電腦網路作業](https://ocw.mit.edu/courses/6-829-computer-networks-fall-2002/pages/assignments/) | 練習進階網路分析，作業 1 有官方解答。 |
| 1.1 至 1.9 自評 | [GSMA Open Telco 完整集](https://huggingface.co/datasets/GSMA/ot-full) 與 [精簡評測集](https://huggingface.co/datasets/GSMA/ot-lite) | 依原課綱附錄 B 選用 TeleQnA、ORANBench 等題型，以資料集標準答案評分。 |

GSMA 題庫按各題型提供標準答案。TeleQnA 的原始資料集另有 Explanation 欄位可查。本章 20 道題的中文詳解則附在各題下方。[TeleQnA 原始資料集欄位](https://huggingface.co/datasets/netop/TeleQnA)

若用於 LLM 訓練及評估，可保留 ot-lite 作評測，並對訓練題與保留試題做重複及近似題比對。依課綱附錄映射挑選題目時，避免將保留試題的變形納入訓練集。[原課綱附錄 B](https://pyyy.gitbook.io/itri-docs/fu-lu/b-gsma-map) [GSMA Open Telco 資料說明](https://huggingface.co/datasets/GSMA/ot-lite)
