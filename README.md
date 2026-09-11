# 需要準備的材料：
1. 5M NaCl與10% CTAB。CTAB會結晶，用之前要加熱讓結晶消失才能用
2. PEB-SDS free
3. Proteinase K
4. PCI & Chloroform
5. 1000 uL與200 uL的tips，2.0與1.5的tube
6. TE buffer，0.8 % Agarose gel，Novel Juice (dye)，lambda DNA ladder



# CHAOS CTAB-PCI DNA extraction步驟

### Step 1. 稀釋黏稠的CHAOS並且增加體積讓後面比較好抽取
1. 取2.0 tube, 加**200uL PEB (SDS free)** 到每個tube裡面，然後**4 uL RNase**與**30uL的proteinase K**, 
2. 吸取CHAOS **200 uL**，記得要pipette幾次讓PEB與CHAOS混均勻。

### Step 2. 使用NaCl創造high ionic strength環境，讓CTAB在此情況下可以針對polysaccharide去抓。

3. 加**215 uL** 的5M NaCl，記得一定要pipette多次混均勻，讓他變成均勻的high ionic strength溶液，而不是局部high salt這種不均勻的solution
   - **注意順序一定要NaCl先，CTAB後，否則CTAB會去抓DNA**
4. 再把每管加入10%的CTAB **154uL**。
   - 注意CTAB會結晶，用之前一定要加熱讓結晶消失才能用
5. **incubation+ shake 60度C 1小時。**

### Step 3. 使用PCI來清理雜質(polysaccharide, portein, lipids等等)
6. 加入**800uL**的PCI (Phenol:Chloroform:Isoamyl Alcohol, 25:24:1 ratio)，輕輕的慢慢的pipette數次混合均勻
7. 常溫25度離心16000 rpm for 10 minutes
8. 用pipette抽小心的取上層的水層：取出抽上層的水層到新的1.5 tube，抽600就好，不要貪心。記得要把tips尖端剪掉一小部分讓開口比較大去抽，這樣抽取水層時的流速才不會那麼快，這個真的有差，尤其是越靠近交界層越明顯。小技巧：把tube擺在燈管上方就能很清楚看到分界層，用200ul tip分次去抽，不要用1000的。
### Step 4. 準備析出DNA
9. 加入70uL (1/10 volume)的3mol/L Sodium Acetate Buffer, 輕輕的慢慢的pipette數次混均勻(Na⁺ 中和 DNA 磷酸骨架的負電，讓 DNA 分子之間比較容易聚集)
10. 再加入730uL Isopropanol, 不要pipette，蓋上蓋子輕輕的invert數次就好，如果DNA夠多你會看到白霧狀的東西，輕輕的水平晃動幾次後就會看到DNA析出 (降低水相的介電常數與 DNA 溶解度，讓已經被陽離子屏蔽電荷的 DNA 從溶液中析出)
11. 放到-20冰箱1小時 (提高DNA被沉澱下來的機率)。實際測試擺過夜也可以，而且DNA總量會更多。一定要擺至少一小時，這步驟有做，DNA total quantity甚至可以大於3000ng(3μg)以上
12. 離心 at 13000 rpm for 30 minutes in 4 degree Celsius
13. 倒掉 ，輕輕加入600 μl 的70% ethanol 浸潤3分鐘吸收可能的殘留鹽分，要輕輕加，不然你很可能會把DNA pellets沖起來
14. 13 000 rpm for 5 minutes in 4 degree Celsius
15. 倒掉 ，再加600 μl 的70% ethanol 浸潤3分鐘吸收可能的殘留鹽分
16. 13 000 rpm for 15 minutes in 4 degree Celsius
17. 倒掉ethanol, 在tube上面輕輕蓋著錫箔紙防止污染，air dry殘留的ethanol到乾燥
18. 加60uL的TE buffer回溶DNA，TE Buffer可以先preheat 65°C 。回溶後記得要給時間讓DNA溶解，不要立刻去測DNA。
19. 跑膠檢查DNA quality：用0.8% Agarose / 100v 跑30分鐘。用 1uL的novel juice與2uL的DNA

### CHAOS+PEB比例
(Final conc. 1.4M NaCl& 2% CTAB)

| CHAOS |  PEB  |  5M NaCl  |  10% CTAB  |  總體積  |  差異  |
|-----------|----------|--------------|---------------|------------|------------|
| 100       | 400      | 269          | 192           | 961        |初始版本，盡量稀釋mucus並且讓水層容易抽取為目的
| 200       | 300      | 269          | 192           | 961        |CHAOS增量成兩倍，但一樣維持總體積上限
| 200       | 200      | 215          | 154           | 769        |減少一些PEB省試劑，測試後看不出與初始版本有太大差異
| 200       | 100      | 162          | 115           | 577        |再減少一些PEB，但nanodrop顯示DNA產量比較少一些

# Reference   

此protocol基於以下相關文獻之資料：

### The Function of CTAB : 
Cetyltrimethylammoniumbromide (CTAB)is a cationic detergentthat has the useful property of precipitating nucleic acids and acidic polysaccharides from solutions of low ionic strength.Under these conditions, proteins and neutral polysaccharides remain in solution.In solutions of high ionic strength,CTAB forms complexes with proteins and all but the most acidic polysaccharides,but will not precipitate nucleic acids (Jones and Walker 1963). The detergentis added to bacterial or celllysates that have been adjusted to high ionic strength(>0.7 M NaCl).After removing the CTAB/polysaccharide/protein complexes by sequential extraction with chloroform and phenol, the genomic DNA is recovered from the supernatant by precipitation with isopropanol or ethanol (Jones and Walker 1963; Wilson 1987)


### The extraction buffer for plant DNA isolation consists of EDTA (20 mM), Tris-HCl (100 mM), NaCl (1.5 M), CTAB (2%), and 1% β-mercaptoethanol. Samples are incubated at 60 °C for 30 minutes.
Sahu, S. K., Thangaraj, M., & Kathiresan, K. (2012). DNA extraction protocol for plants with high levels of secondary metabolites and polysaccharides without using liquid nitrogen and phenol. *ISRN Molecular Biology*, 2012, 1–6. https://doi.org/10.5402/2012/205049

### Most of the polysaccharides were removed effectively in a single high-salt precipitation at 1.0-2.5 M NaCl. At 3.0 M NaCl, the salt precipitated out of solution
Fang G, Hammar S, Grumet R. A quick and inexpensive method for removing polysaccharides from plant genomic DNA. Biotechniques. 1992 Jul;13(1):52-4, 56. PMID: 1503775. https://pubmed.ncbi.nlm.nih.gov/1503775/

### A CTAB–nucleic acid precipitate is formed when the NaCl concentration is reduced from 0.7 M to 0.35 M by the addition of one volume of 1× CTAB containing 50 mM Tris-HCl (pH 8.0) and 10 mM EDTA.
Murray MG, Thompson WF. Rapid isolation of high molecular weight plant DNA. Nucleic Acids Res. 1980 Oct 10;8(19):4321-5. doi: 10.1093/nar/8.19.4321. PMID: 7433111; PMCID: PMC324241. https://doi.org/10.1093/nar/8.19.4321

### Extraction buffer: 20 mM sodium EDTA and 100 mM tris-HC1; adjust pH to 8.0 with HC1, add 1.4 M NaC1 and 2.0% (w / v) CTAB. Dissolve CTAB by heating to 60~ Store at 37~ Add 0.2% of ~-mercaptoethanol just before use.
Lodhi, M.A., Ye, GN., Weeden, N.F. et al. A simple and efficient method for DNA extraction from grapevine cultivars andVitis species. Plant Mol Biol Rep 12, 6–13 (1994). https://doi.org/10.1007/BF02668658

### CHAOS solution (4 M guanidine thiocyanate, 0.5% N-lauroylsarcosine sodium salt, 0.1 M 2-mercaptoethanol, 25 mM Tris-HCl pH 8.0). 2×CTAB buffer (100 mM Tris, 20 mM EDTA, 1.4 M NaCl, 4% CTAB, pH 8.0), incubated at 65 °C for 60 min
Manalili, S. E. N., Mezaki, T., Taguchi, T., & Kubota, S. (2026). High-contiguity temperate coral genome reveals thematic gene enrichment and assembly quality effects in comparative genomics. Conservation Genetics, 27(2), 28. https://doi.org/10.1007/s10592-026-01760-3

https://www.intechopen.com/chapters/72074

https://onlinelibrary.wiley.com/doi/10.1155/2009/574398





## Stock配方

### CHAOS配法
# CHAOS solution


| Reagent | 100 mL | 500 mL | 1000 mL | Final concentration |
|---|---:|---:|---:|---:|
| Guanidine thiocyanate powder | 50 g | 250 g | 500 g | 4 M |
| N-lauroyl sarcosine sodium powder | 0.5 g | 2.5 g | 5 g | 0.5% |
| 1 M Tris pH 8 Stock | 2.5 mL | 12.5 mL | 25 mL | 25 mM |
| 2-mercaptoethanol stock solution | 0.7 mL | 3.5 mL | 7 mL | 0.1 M |
| ddH₂O | Up to 100 mL | Up to 500 mL | Up to 1000 mL | — |


## 注意事項
- 不建議一開始就先將粉末加入空瓶後再加水，因為 guanidine thiocyanate 用量很大，容易在底部結塊並形成高濃度粉泥，會使溶解變慢且不均勻。
- 一開始也不要直接加入最終體積的 ddH₂O，否則加入粉末與其他試劑後會超過目標體積。
- 建議先加入約50%最終體積的 ddH₂O，再慢慢加入粉末並攪拌至完全溶解，然後再補其他的，最後補水至目標體積。
- 2-mercaptoethanol有毒要小心，最後加入，並在 fume hood 內操作。
- 空瓶 → 加入約 50% 目標體積的 ddH₂O → 慢慢加入 guanidine thiocyanate 粉末並攪拌溶解 → 加入 N-lauroyl sarcosine sodium 粉末並攪拌溶解 → 加入 1 M Tris pH 8 → 最後在 fume hood 加入 2-mercaptoethanol 原液 → 用 ddH₂O 補至最終體積 → 混合 30 分鐘至 1 小時。
 
### 5 M NaCl stock, 100 mL
1. NaCl 29.22 g
2. ddH2O to 100 mL
   
先以約 60 到 70 mL ddH2O 溶解 NaCl，完全溶解後定容至 100 mL。

### 10% CTAB stock, 100 mL
1. CTAB: 10.0 g
2. ddH2O to 100 ml
   
先以約 60 到 70 mL ddH2O 加熱至 60 到 65°C，分批加入 CTAB 並攪拌至完全溶解，最後定容至 100 mL。室溫保存，若析晶則使用前加熱回溶。

### SDS-free PEB (phenol extraction buffer)
1.此版本僅含 Tris-HCl 與 EDTA，適用於需搭配 CTAB 的 DNA 抽取流程，以避免 SDS 與 CTAB 形成沉澱。  
2. PEB的Stock溶液的pH必須為8.0  

### 配製 500 mL PEB（不含 SDS）

| 成分 | Stock 濃度 | 目標濃度 | 所需體積 |
|------|------------|----------|----------|
| Tris-HCl (pH 8.0) | 1 M | 100 mM | 50 mL |
| EDTA (pH 8.0) | 0.5 M | 10 mM | 10 mL |
| ddH₂O | — | — | 440 mL |
| **總體積** | — | — | **500 mL** |

1. SDS-free PEB 是給 CTAB–NaCl 方法使用，可避免界面活性劑間的沉澱反應。
2. EDTA 可螯合二價金屬離子，抑制核酸酶活性並保護 DNA。
3. Tris-HCl 提供穩定的緩衝環境以維持 DNA 穩定性。  

 
### 1 M Tris HCl pH 8.0，500 mL
需要
- Tris base 60.57 g
- ddH2O滅菌水
- 濃鹽酸 HCl 用來滴定 pH，建議用3M以上濃度
- 1 L beaker 或燒杯
- 磁石攪拌器
- pH meter (小心玻璃頭很容易破、要記得先做三點校正)

#注意：pH 8.0很重要，如果沒有調整到pH8，PCI抽取時DNA會跑去中間層甚至有機層，不會留在水層。

步驟
1.	先在燒杯中加入約 350 mL ddH2O，再加入 Tris base 60.57 g，攪拌至完全溶解。
2.	開始量 pH: Tris base 溶於水後，pH 會偏高，所以要用 HCl 慢慢往下調。
3.	一邊攪拌，一邊緩慢加入濃鹽酸。前面可以先稍微快一點加，但接近 pH 8.3 之後要放慢，改成一滴一滴加。每加一次，等讀值穩定後再繼續。
4.	調到 pH 8.0。最好先停在 pH 8.05 到 8.1 附近，再慢慢修到 8.0，避免一次過頭。
5.	把溶液移到 500 mL 量瓶或量筒定容容器中。
6.	用 ddH2O 補到最終體積 500 mL。
7.	混勻。
   
注意： Tris 的 pH 會受溫度影響，所以最好在室溫下調 pH，不要趁很熱的時候調，不然放回室溫後 pH 會跑掉。
 
### 0.5 M EDTA pH 8.0，500 mL
- EDTA (Na2EDTA·2H2O): 93.05 g
-ddH2O滅菌水
- NaOH溶液 用來滴定 pH
- 1 L beaker 或燒杯
- 磁石攪拌器
- pH meter (小心玻璃頭很容易破、要記得先做三點校正)

步驟
1.	先在燒杯中加入約 350 mL ddH2O。
2.	加入 EDTA 93.05 g，開始攪拌。這時通常不會立刻完全溶掉，這是正常的。
3.	一邊攪拌，一邊慢慢加入 NaOH 調 pH。EDTA 在 pH 不夠高時很難溶，隨著 pH 往上升，溶液會慢慢變清、越來越容易溶。
4.	持續加 NaOH，直到 pH 8.0。接近 pH 8.0 時改成慢慢滴加，不要一次過頭。
5.	確認固體已完全溶解。若還有少量未溶，可以繼續攪拌一下。必要時可稍微加溫，但不要高溫長時間加熱。
6.	把溶液移到 500 mL 量瓶或定容容器中。
7.	用 ddH2O 補到最終體積 500 mL。
8.	混勻。
   
### 5 M NaOH，500 mL配法

### 記得！！！要先放水，然後慢慢地把NaOH加到水裡！！
如果你先放NaOH，然後將水倒入氫氧化鈉中，水會迅速吸收大量熱量並瞬間汽化，體積劇烈膨脹，導致溶液連同未溶解的顆粒一起噴出（像火山噴發一樣）。
噴出的液體是高濃度強鹼，會對皮膚、眼睛造成嚴重灼傷
NaOH 很腐蝕，配的時候要戴手套和護目鏡！  

需要NaOH 100.0 g，ddH2O滅菌水  

(5 mol/L × 0.5 L × 40.00 g/mol = 100.0 g)

步驟
1. 先加約 300 到 350 mL ddH2O。
2. 慢慢分批加入 100.0 g NaOH，一邊攪拌。等完全溶解並放涼。
3. 再補 ddH2O 到 500 mL。



