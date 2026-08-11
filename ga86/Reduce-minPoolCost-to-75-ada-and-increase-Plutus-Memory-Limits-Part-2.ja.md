# Governance Action ID
`gov_action14dr5yg75pchr2sz42djtuflpvx5qnsek29qg7s7cft8lzrqt5vrqqtqntpk`

## 要約
本ガバナンスアクションは合憲であると判断します。

## 根拠説明
本提案は、IntersectのParameter Committeeによる「Reduce minPoolCost to 75 ada and increase Plutus Memory Limits (Part 2)」に関するParameter Update Governance Actionです。本提案は、minPoolCostを170 adaから75 adaへ引き下げ、maxTxExecutionUnits[memory]を16,500,000から17,500,000へ、maxBlockExecutionUnits[memory]を72,000,000から77,500,000へ引き上げることを推奨しています。Cardano憲法第2条第6節第1項および第2項について、本提案はIPFS上の提案文書を参照し、題名、概要、正当化および関連する補足資料を提示しているため、これらの要件に適合していると判断します。Cardano憲法第2条第6節第3項について、本提案は、minPoolCostの変更に関する審議プロセスに加え、Plutusメモリ上限に関するParameter Committeeの推奨、Technical Steering Committeeの承認、Preview testnetでの実装、およびnode version 10.2と10.3を使用したパフォーマンス評価について説明しています。したがって、必要な技術的レビューおよび検証が実施されていると判断します。minPoolCostを75 ADAへ変更することはMPC-01およびMPC-02の要件を満たしており、この設定の経済的根拠についてもMPC-03で説明されています。また、PARAM-06aに規定される90日前の事前通知要件が満たされていることも確認しました。Plutusメモリ上限については、MTEU-M-01からMTEU-M-04、MBEU-M-01からMBEU-M-04a、およびMEU-M-01との整合性が示されており、NETWORK-01およびNETWORK-02との整合性についても説明されています。また、PARAM-04aに規定される90日前の事前通知要件への適合も確認されています。さらに、maxBlockExecutionUnits[memory]の変更に伴い、PARAM-03aに基づくSPO投票が必要となることが説明されています。以上より、Cardano憲法との明確な抵触は認められないため、本提案は合憲であると判断します。

## 先例に関する議論
なし

## 反対意見に関する議論
1名のメンバーは、以下の理由により本提案は違憲であると主張しました。MPC-03（x - 「should」）では、minPoolCostはプール運営の経済的コストに沿って設定されるべきとされています。75 ADAという値を設定する根拠については、セキュリティおよび競争力の観点から説明されていますが、「プール運営の経済的コスト」に従って設定されたことを確認できる説明はありません。実際、小規模なプールが月にわずか1ブロックを生成した場合でも、報酬は75 ADA × 30円 = 2,250円となるため、この設定が運営の経済的コストに基づいているとは言えません。これとは別に、Appendix I §2.6では、Reversion/Recovery Planに壊滅的な障害が発生した場合のネットワーク復旧方法を含めることが求められています。本提案では、minPoolCostを170 ADA、maxTxExecutionUnits[memory]を16,500,000、maxBlockExecutionUnits[memory]を72,000,000へ戻す具体的な方法が示されていますが、壊滅的な障害が発生した場合のネットワーク復旧手順については明示されていません。しかし、この点のみをもって、本Governance ActionがCardano憲法に明確に違反していると判断することはできません。

## 結論
以上の理由により、本提案は合憲であると判断します。

## 内部投票
- 合憲: 3
- 違憲: 1
- 棄権: 0
- 未投票: 0

## 参考資料
[CARDANO BLOCKCHAIN ECOSYSTEM CONSTITUTION](https://ipfs.io/ipfs/bafkreieyuknozbtewyurfqoagvplvykadn6a4u6wglupavdz46bbsnnl6e)