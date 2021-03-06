## 測度論
測度とは集合の「サイズ」  
- 完全加法族
### 測度
写像μ: S -> [0, ∞] (SはXの完全加法族)が以下を満たす.
1. 空集合の測度は0. μ(Φ) = 0
2. 完全加法性.
### 測度空間
Xを集合, SをX上の完全加法族, μをX上の測度のとき, (X, S, μ)を測度空間という.
- (X, S, μ)の完備性
- 測度の性質... -> ある意味当たり前な結果

### 特性関数
### ルベーグ積分の定義
### リーマン積分とルベーグ積分との関係
### almost everywhere
- 集合Aの元が高々可算個しかない場合, Aの測度を|A|=0とし, 測度が0であるような集合を零集合という.
- ex... lim(j->∞)f[j] = f(x) が a.e. x∈G で成立

### 単調収束定理
- 「非負ルベーグ可測関数列が単調増加列」かつ「f = lim(j->∞)f[j]」のとき順序交換可能.
### ルベーグの優収束定理
- 「上から抑えられる」かつ「関数列f[j]の極限がf」 -> fはX上ルベーグ積分可能で極限と和(インテグラル)の順序交換ができる. 
### Fubiniの定理

### ラドン=ニコディムの定理
ある可測空間(X, Σ)が与えられたとき, (X, Σ)上にあるσ-有限測度vが別の(X, Σ)上のσ-有限測度μに関して絶対連続であるなら, 任意の可測部分集合A⊂Xに対して次を満たす可測関数f: X->[0, ∞) が存在する.  
v(A) = ∫[A]fdμ  
fはラドン＝ニコディム微分
- 確率論におけるアイディアを, 実数上で定義される確率密度から, 任意の集合上で定義される確率測度へと拡張する上で非常に重要. ある確率測度を別のものへ変化させることが可能か, また可能であればどのようにできるか, という事実を示唆する.  
- 数理ファイナンス: 確率測度の変化はデリバティブの合理価格設定を行う上での基本であり, 実際の確率をリスク中立確率に転換する上で用いられる.  
- 絶対連続: 同じ可測空間上の２つの測度μ, vについて, μ(A)=0 となる可測集合が必ず v(A)=0 を満たす時, vはμに関して絶対連続であるといい, v<<μとかく.