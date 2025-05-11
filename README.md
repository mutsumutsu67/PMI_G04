# PMI_G04
## PMI日本支部フォーラム2025のG_04の実演データになります。
## Difyの使ったAI Agentのworkflowデータ：
## 1,Dify(workflow) :
### 
## 2, 患者データ(Dummy):
### 患者1 : patient_data1.txt
### 患者2 : patient_data2.json
### 患者3 : patient_data3.json
### 患者4 : patient_data4.json
### データについて：
### 形式はJson. データは"基本情報","バイタル記録","リハビリ記録","生活観察"を入力しています。
#### 基礎情報　　：介護患者の基礎情報
#### バイタル記録：一週間分のバイタルデータ。
#### リハビリ記録：一週間分のバイタルデータ。
#### 生活観察　　：一週間分の生活観察記録。
## 3,実行について
###   1,Data download (yaml , patient_data*.*)
###   2,Difyを立ち上げ後、yamlを読込。workflowとして取り込まれます。
###   3.DifyのLLM APIの設定
###   4,AIエージェントの実行(inputにpatient_dataをfileとして入力。）
###  
###
