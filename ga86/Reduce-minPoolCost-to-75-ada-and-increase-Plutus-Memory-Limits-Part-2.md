# Governance Action ID  
`gov_action14dr5yg75pchr2sz42djtuflpvx5qnsek29qg7s7cft8lzrqt5vrqqtqntpk`

## Summary  
We consider this governance action to be constitutional.

## Rationale Statement  
This proposal is a Parameter Update Governance Action by Intersect's Parameter Committee regarding "Reduce minPoolCost to 75 ada and increase Plutus Memory Limits (Part 2)." This proposal recommends lowering minPoolCost from 170 ada to 75 ada, and raising maxTxExecutionUnits[memory] from 16,500,000 to 17,500,000 and maxBlockExecutionUnits[memory] from 72,000,000 to 77,500,000. Regarding Article 2, Section 6, Paragraphs 1 and 2 of the Cardano Constitution, this proposal refers to the proposal document on IPFS and presents a title, summary, justification, and relevant supplementary materials; we therefore determine that it complies with these requirements. Regarding Article 2, Section 6, Paragraph 3 of the Cardano Constitution, in addition to the deliberation process regarding the change to minPoolCost, the proposal explains the Parameter Committee's recommendation regarding the Plutus memory limit, the Technical Steering Committee's approval, implementation on the Preview testnet, and performance evaluations using node versions 10.2 and 10.3. We therefore determine that the necessary technical reviews and verifications have been conducted. The change to minPoolCost of 75 ADA meets the requirements of MPC-01 and MPC-02, and the economic rationale for this setting is explained in MPC-03. We have also confirmed that the 90-day advance notice requirement specified in PARAM-06a has been met. Regarding the Plutus memory limit, consistency with MTEU-M-01 through MTEU-M-04, MBEU-M-01 through MBEU-M-04a, and MEU-M-01 has been demonstrated, and consistency with NETWORK-01 and NETWORK-02 has also been explained. It also confirms compliance with the 90-day advance notice requirement specified in PARAM-04a. Furthermore, it explains that, due to the change in maxBlockExecutionUnits[memory], an SPO vote based on PARAM-03a will be required. Therefore, since no clear conflict with the Cardano Constitution has been identified, we determine that this proposal is constitutional.

## Precedent Discussion  
None

## Counterargument Discussion  
One member argued that this was unconstitutional for the following reason: It violates MPC-03 (x - "should") minPoolCost should be set in line with the economic cost for operating a pool. While the rationale for setting the value at 75 ADA is explained from the perspectives of security and competitiveness, there is no explanation that confirms it was set in accordance with the "economic cost for operating a pool." In fact, even if a small-scale pool generates just one block per month, the reward would be 75 ADA × 30 yen = 2,250 yen; therefore, it cannot be said that the setting is based on the economic cost of operation. Separately, Appendix I §2.6 requires that the Reversion/Recovery Plan include methods for network recovery in the event of a catastrophic failure. While this proposal outlines specific methods to revert minPoolCost to 170 ADA, maxTxExecutionUnits[memory] to 16,500,000, and maxBlockExecutionUnits[memory] to 72,000,000, it does not explicitly specify the network recovery procedures in the event of a catastrophic failure. However, based on this point alone, this Governance Action cannot be deemed to clearly violate the Cardano Constitution.

## Conclusion  
For the reasons stated above, we determine that it is constitutional.

## Internal Vote  
- Constitutional: 3  
- Unconstitutional: 1  
- Abstain: 0  
- Did Not Vote: 0  

## References  
[CARDANO BLOCKCHAIN ECOSYSTEM CONSTITUTION](https://ipfs.io/ipfs/bafkreieyuknozbtewyurfqoagvplvykadn6a4u6wglupavdz46bbsnnl6e)  