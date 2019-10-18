# MLSE 国際シンポジウム
# Towards Verified Artificial Intelligence
### Sanjit Seshia 氏
Need Design Principles for Varified AI
https://github.com/BerkeleyLearnVerify


無理、メモ間にあわない。今回のじゃないけどおなじような発表の資料置いてあったよ
https://people.eecs.berkeley.edu/~sseshia/talks/Seshia-VerifiedAI-ATVA2018.pdf

Scenic usecase Data generation, test generation verification debugginng design environment

自動運転システム等の失敗ケースでモデルを責め立てるのは違うみたい

テンポラルロジック
"システム全体の"評価指標を見つけることが重要

---

精度が高いとはいえ、male:female=90:10の比率で、femaleの判別精度がどれだけ低かろうが、majorityであるmaleはminorityであるfemaleの判別よりも精度に大きく影響する。

魚か否かの分類問題で、クマノミ分類精度が高かったとしても、分類の役に立った画像がカサゴなどだったら、オレンジと白のシマシマが魚と分類する材料だったら危ない(あってるけど)

---

# Safety under Statistical and Environmental Uncertainties:Challenges in Cyber-Physical Systems with Machine-Learning Components
### 蓮尾 一郎 氏

機械学習が混ざっているけど、なにかあったら人命に関わるシステムに、どう向き合っているか

自動運転

perception
センサーデータ処理
object recognintion
物体認識
behavior planning path planning: HighレベルなPath
どの道を走るか
local planning path tracking
どのくらいハンドル切るか

外界からのuncertainties
* 交通
* 事故
* 隕石

内界のuncertainties
暗闇をランプを持って歩いている
暗闇：外界のuncertainties
ランプ：ブラックボックス：内界のuncertainties

Statisitical AI
Ground truth 
->noisy data
->approximationn by regression
見えないものから近似したものを信用してはいけない

ユーザーとAIのGround Truthの違い
ユーザーの考えるGround truth
ハスキー犬かどうか

Statisitial AIが考えたGround truth
雪があるかどうか

の場合がある

AI:すごい優秀だけど、ときどきとんでもないことをしでかす同僚として扱うべき

AIの決断は、あくまで提案(suggestion,pinch of salt)

ブリッジすべき項目
* statisical : logical
* continuous : discrete
* noisy : rigorous
* data-based : rule-based
* bottom-up : top-down

## Formal methods(形式検証)
### Verification
#### Theorem Proving
証明を書き出す。人間が書くと失敗する
Proof Asistantを使う(Coq,Agda,PVS,Isabelle)
#### Model Checking
Theorem Provingは、ソフトウェアを使ってもコストが高い
証明のアルゴリズム探索が、グラフアルゴリズムに帰着する
### Synthesis
### Specification

---

## Engineer's Responsibility in Machine Learning Era
### 榊原 彰 氏

AI reached Human parity
Vision:96%
Speech:94%
Translation:69%
Readinng:88%

Microsofts define
1. Fairness
2. Reliability and Safety
3. Privacy and Security
4. Innclusiveness
5. Transpairency
6. Accountability

Data: social bias
CEO:ほとんど男性、白人しか出てこない
CEOは、白人の男性の職業という概念がある

Automate
level1,Iot:monitoring
level2,Maintain
level3,Optimize
level4,Autonomus

level high, business influence become high

## Machine Teaching
機械学習の一部ではない
教えるのは人間。ある分野の専門家
学習するのは機械、AIのモデル

---

## Towards Debugging and Testing Deep Learning Systems
### Foutse Khomh 氏

