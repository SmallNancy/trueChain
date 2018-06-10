# trueChain
trueChain 翻译<br>
##主要内容：
<p>因此，我们正在制定一种混合共识机制，它的运行主要遵循以下几点：</p>
1.已被许可的BFT是在基于POW共识机制的网络中的几个节点上运行的。<br>
2.BFT委员会是一个轮值委员会，能够有效地防止腐败现象的发生。<br>
3.BFT委员会负责交易验证，而POW节点只负责根据我们得出和重新定义在以太坊黄皮书中提到的一些规则来选择或者选举委员会成员！<br>
4.据猜测，新许可的虚拟机（VM）灵感是源自以太坊虚拟机（EVM）。但是它又有不同于EVM的区块状态和事物执行流程。<br>
5.当前，POW链中的无许可以太坊虚拟机和新的许可虚拟机共存（这种虚拟机被称为初链虚拟机-TVM）。<br>
6.根据当前的讨论，初链虚拟机（TVM）将成为验证任何交易的一种方式，而EVM需要重新工作，不是为了共识而采取行动，而是轻量级钱包交易的BFT选举。<br>
7.这种激励模式，需要重新开展工作，使其基于TVM，也就是我们仍然以某种方式奖励POW链中的矿工。<br>
8.我们最终会支持分享BFT委员会的节点，提高可扩展性。<br>
9.补偿基础结构，如果节点规格不一致性（比如在节点池中不同的CPU /内存/网络带宽等）最终都会将成为共识的一部分，加快交易。<br>
10.因此，智能合约的执行只会发生在TVM（BFT节点），我们确实认为在混合设置中应该从POW节点支持部署，从而引发关于状态复制的问题。<br>
**注意：我们可能需要改变稳固性以及以太坊目前的轻钱包，这正是我们把它作为框架的选择。<br>**
###时间线：
####TODO:在时间线中添加规范或者伪代码的细节<br>
<table border=0 cellpadding=0 cellspacing=0 width=635 style='border-collapse:
 collapse;table-layout:fixed;width:477pt'>
 <col width=50 style='mso-width-source:userset;mso-width-alt:1600;width:38pt'>
 <col width=47 style='mso-width-source:userset;mso-width-alt:1504;width:35pt'>
 <col width=115 style='mso-width-source:userset;mso-width-alt:3680;width:86pt'>
 <col width=137 style='mso-width-source:userset;mso-width-alt:4384;width:103pt'>
 <col width=286 style='mso-width-source:userset;mso-width-alt:9152;width:215pt'>
 <tr height=38 style='height:28.5pt'>
  <td height=38 width=50 style='height:28.5pt;width:38pt'>章节</td>
  <td class=xl69 width=47 style='width:35pt'>时间(起点)</td>
  <td width=115 style='width:86pt'>阶段</td>
  <td width=137 style='width:103pt'>详细</td>
  <td width=286 style='width:215pt'>备注</td>
 </tr>
 <tr height=19 style='height:14.25pt'>
  <td height=19 style='height:14.25pt'>Q1/18</td>
  <td></td>
  <td>Project.init()</td>
  <td>V&lt;3 Python</td>
  <td>V also&lt;3 GoLang</td>
 </tr>
 <tr height=19 style='height:14.25pt'>
  <td height=19 style='height:14.25pt'>Q1/18</td>
  <td></td>
  <td>白皮书发布</td>
  <td></td>
  <td class=xl65><a href="https://www.truechain.pro/EnTruechain.pdf"
  target="_parent">https://www.truechain.pro/EnTruechain.pdf</a></td>
 </tr>
 <tr height=38 style='height:28.5pt'>
  <td height=38 style='height:28.5pt'>Q2/18</td>
  <td></td>
  <td>黄皮书第一草案</td>
  <td class=xl69 width=137 style='width:103pt'>混合共识文档收录在 arXiv上</td>
  <td class=xl65><a href="https://arxiv.org/abs/1805.01457" target="_parent">https://arxiv.org/abs/1805.01457</a></td>
 </tr>
 <tr height=55 style='mso-height-source:userset;height:41.25pt'>
  <td rowspan=41 height=1581 style='height:1185.75pt'></td>
  <td colspan=2 style='mso-ignore:colspan'></td>
  <td class=xl67>基本的TVM</td>
  <td class=xl66>EVM (POW) +TVM(BFT)==&gt;PBFT+POW在单个节点上</td>
 </tr>
 <tr height=59 style='mso-height-source:userset;height:44.25pt'>
  <td height=59 colspan=2 style='height:44.25pt;mso-ignore:colspan'></td>
  <td class=xl67>激励计划</td>
  <td class=xl70 width=286 style='width:215pt'>为新的虚拟机组合制定激励计划，考虑一个不同的Txn费用模型</td>
 </tr>
 <tr height=19 style='height:14.25pt'>
  <td height=19 style='height:14.25pt'></td>
  <td>黄皮书TIP-1</td>
  <td colspan=2 style='mso-ignore:colspan'></td>
 </tr>
 <tr height=23 style='mso-height-source:userset;height:17.25pt'>
  <td height=23 colspan=2 style='height:17.25pt;mso-ignore:colspan'></td>
  <td class=xl68>更新arXiv上的论文</td>
  <td></td>
 </tr>
 <tr height=23 style='mso-height-source:userset;height:17.25pt'>
  <td height=23 colspan=2 style='height:17.25pt;mso-ignore:colspan'></td>
  <td class=xl68 colspan=2 style='mso-ignore:colspan'>混合共识伪代码发布</td>
 </tr>
 <tr height=76 style='height:57.0pt'>
  <td height=76 colspan=2 style='height:57.0pt;mso-ignore:colspan'></td>
  <td class=xl70 width=137 style='width:103pt'><br>
    去耦和耦合/重新排列以太坊来适应共识</td>
  <td></td>
 </tr>
 <tr height=38 style='height:28.5pt'>
  <td height=38 colspan=2 style='height:28.5pt;mso-ignore:colspan'></td>
  <td class=xl69 width=137 style='width:103pt'>调整以太坊Gas的经济模式</td>
  <td></td>
 </tr>
 <tr height=19 style='height:14.25pt'>
  <td height=19 style='height:14.25pt'></td>
  <td>代码</td>
  <td colspan=2 style='mso-ignore:colspan'>实施混合共识代码库</td>
 </tr>
 <tr height=63 style='mso-height-source:userset;height:47.25pt'>
  <td height=63 style='height:47.25pt'></td>
  <td class=xl69 width=115 style='width:86pt'>根据时间的重要性和依赖，重新排序，很快又进一步细分</td>
  <td></td>
  <td class=xl69 width=286 style='width:215pt'>初始化节点：<span
  style='mso-spacerun:yes'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
  </span>1. forkVirtualNodeBFT()<br>
    2. SpawnBFTnode()</td>
 </tr>
 <tr height=133 style='height:99.75pt'>
  <td height=133 colspan=3 style='height:99.75pt;mso-ignore:colspan'></td>
  <td class=xl69 width=286 style='width:215pt'>验证：<br>
    1. onChainValidation()<br>
    a. validateFromPOW()<br>
    b. FetchTxnHistory()<br>
    2. reElect()<br>
    3. checkTxnOrder()<br>
    4. updateSnailchain()</td>
 </tr>
 <tr height=57 style='height:42.75pt'>
  <td height=57 colspan=3 style='height:42.75pt;mso-ignore:colspan'></td>
  <td class=xl69 width=286 style='width:215pt'>对于视图更改和节点损坏的检测/更改<br>
    1. ViewChange()<br>
    2. complainToSnailChain()</td>
 </tr>
 <tr height=76 style='height:57.0pt'>
  <td height=76 colspan=3 style='height:57.0pt;mso-ignore:colspan'></td>
  <td class=xl69 width=286 style='width:215pt'>特征：<br>
    1. keygen()<br>
    2. SignLog()<br>
    3. Keccak256/ECDSA wrappers</td>
 </tr>
 <tr height=76 style='height:57.0pt'>
  <td height=76 colspan=3 style='height:57.0pt;mso-ignore:colspan'></td>
  <td class=xl69 width=286 style='width:215pt'>日志：<br>
    1. dailyLogOutput()<br>
    2. CreateLOG()<br>
    3. createTxTuple()</td>
 </tr>
 <tr height=133 style='height:99.75pt'>
  <td height=133 colspan=3 style='height:99.75pt;mso-ignore:colspan'></td>
  <td class=xl69 width=286 style='width:215pt'>交易池:<br>
    1. mempoolSubprotocol()<br>
    a. propose()<br>
    b. query()<br>
    c. others..<br>
    2. DailyOffchainProtocol()<br>
    3.</td>
 </tr>
 <tr height=57 style='height:42.75pt'>
  <td height=57 colspan=3 style='height:42.75pt;mso-ignore:colspan'></td>
  <td class=xl69 width=286 style='width:215pt'>选择和 VRF:<br>
    1. SeedSelectorVRF()<br>
    2. proposeStakeTransactions()</td>
 </tr>
 <tr height=19 style='height:14.25pt'>
  <td height=19 colspan=3 style='height:14.25pt;mso-ignore:colspan'></td>
  <td class=xl69 width=286 style='width:215pt'>简要说明：</td>
 </tr>
 <tr height=19 style='height:14.25pt'>
  <td height=19 colspan=3 style='height:14.25pt;mso-ignore:colspan'></td>
  <td>1. createSnapShot()</td>
 </tr>
 <tr height=38 style='height:28.5pt'>
  <td height=38 colspan=3 style='height:28.5pt;mso-ignore:colspan'></td>
  <td class=xl69 width=286 style='width:215pt'>交流：<br>
    1. gossipTxn()</td>
 </tr>
 <tr height=19 style='height:14.25pt'>
  <td height=19 colspan=3 style='height:14.25pt;mso-ignore:colspan'></td>
  <td class=xl69 width=286 style='width:215pt'>分享和补偿基础措施</td>
 </tr>
 <tr height=38 style='height:28.5pt'>
  <td height=38 colspan=3 style='height:28.5pt;mso-ignore:colspan'></td>
  <td class=xl69 width=286 style='width:215pt'>基本的测试：集成测试、功能测试、单元测试</td>
 </tr>
 <tr height=19 style='height:14.25pt'>
  <td height=19 colspan=2 style='height:14.25pt;mso-ignore:colspan'></td>
  <td>工程再造</td>
  <td></td>
 </tr>
 <tr height=19 style='height:14.25pt'>
  <td height=19 colspan=2 style='height:14.25pt;mso-ignore:colspan'></td>
  <td>基础设施监控/建设</td>
  <td></td>
 </tr>
 <tr height=19 style='height:14.25pt'>
  <td height=19 colspan=2 style='height:14.25pt;mso-ignore:colspan'></td>
  <td>安全审查</td>
  <td></td>
 </tr>
 <tr height=19 style='height:14.25pt'>
  <td height=19 colspan=2 style='height:14.25pt;mso-ignore:colspan'></td>
  <td>服务器安全强化</td>
  <td></td>
 </tr>
 <tr height=19 style='height:14.25pt'>
  <td height=19 colspan=2 style='height:14.25pt;mso-ignore:colspan'></td>
  <td>轻量级钱包再造</td>
  <td></td>
 </tr>
 <tr height=19 style='height:14.25pt'>
  <td height=19 colspan=2 style='height:14.25pt;mso-ignore:colspan'></td>
  <td>前端</td>
  <td></td>
 </tr>
 <tr height=38 style='height:28.5pt'>
  <td height=38 colspan=2 style='height:28.5pt;mso-ignore:colspan'></td>
  <td class=xl69 width=137 style='width:103pt'>发布设计文档，用于智能合约执行</td>
  <td class=xl68>公开在github /其他地方</td>
 </tr>
 <tr height=28 style='mso-height-source:userset;height:21.0pt'>
  <td height=28 colspan=2 style='height:21.0pt;mso-ignore:colspan'></td>
  <td class=xl69 width=137 style='width:103pt'><br>
    自定义Dapps</td>
  <td></td>
 </tr>
 <tr height=19 style='height:14.25pt'>
  <td height=19 style='height:14.25pt'></td>
  <td colspan=2 style='mso-ignore:colspan'>实验版本-r1-v0.?</td>
  <td></td>
 </tr>
 <tr height=19 style='height:14.25pt'>
  <td height=19 colspan=2 style='height:14.25pt;mso-ignore:colspan'></td>
  <td colspan=2 style='mso-ignore:colspan'>开发者文档达成共识</td>
 </tr>
 <tr height=19 style='height:14.25pt'>
  <td height=19 colspan=4 style='height:14.25pt;mso-ignore:colspan'></td>
 </tr>
 <tr height=57 style='height:42.75pt'>
  <td height=57 style='height:42.75pt'></td>
  <td class=xl69 width=115 style='width:86pt'>规模实验：建立在公有、私有、云</td>
  <td colspan=2 style='mso-ignore:colspan'></td>
 </tr>
 <tr height=38 style='height:28.5pt'>
  <td height=38 colspan=2 style='height:28.5pt;mso-ignore:colspan'></td>
  <td class=xl69 width=137 style='width:103pt'>在全球各地区，建立内部规模实验室</td>
  <td></td>
 </tr>
 <tr height=19 style='height:14.25pt'>
  <td height=19 style='height:14.25pt'></td>
  <td>仿真和测试</td>
  <td colspan=2 style='mso-ignore:colspan'></td>
 </tr>
 <tr height=19 style='height:14.25pt'>
  <td height=19 colspan=2 style='height:14.25pt;mso-ignore:colspan'></td>
  <td>实验准备</td>
  <td></td>
 </tr>
 <tr height=38 style='height:28.5pt'>
  <td height=38 colspan=2 style='height:28.5pt;mso-ignore:colspan'></td>
  <td class=xl69 width=137 style='width:103pt'>模拟基本服务器负荷/成本</td>
  <td></td>
 </tr>
 <tr height=38 style='height:28.5pt'>
  <td height=38 colspan=2 style='height:28.5pt;mso-ignore:colspan'></td>
  <td class=xl69 width=137 style='width:103pt'>调整，修复bug，性能改进</td>
  <td></td>
 </tr>
 <tr height=19 style='height:14.25pt'>
  <td height=19 style='height:14.25pt'></td>
  <td colspan=2 style='mso-ignore:colspan'>实验版本-r2-v0.?</td>
  <td></td>
 </tr>
 <tr height=19 style='height:14.25pt'>
  <td height=19 colspan=2 style='height:14.25pt;mso-ignore:colspan'></td>
  <td>测试网</td>
  <td></td>
 </tr>
 <tr height=38 style='height:28.5pt'>
  <td height=38 colspan=2 style='height:28.5pt;mso-ignore:colspan'></td>
  <td class=xl69 width=137 style='width:103pt'>调整，修复bug，性能改进</td>
  <td></td>
 </tr>
 <tr height=19 style='height:14.25pt'>
  <td height=19 style='height:14.25pt'></td>
  <td colspan=2 style='mso-ignore:colspan'>实验版本-r3-v0.?</td>
  <td></td>
 </tr>
 <tr height=19 style='height:14.25pt'>
  <td height=19 style='height:14.25pt'>Q3/18</td>
  <td colspan=2 style='mso-ignore:colspan'></td>
  <td>在以太坊Dapps dev</td>
  <td></td>
 </tr>
 <tr height=19 style='height:14.25pt'>
  <td rowspan=4 height=152 style='height:114.0pt'></td>
  <td colspan=2 style='mso-ignore:colspan'></td>
  <td>主要网络</td>
  <td></td>
 </tr>
 <tr height=76 style='height:57.0pt'>
  <td height=76 style='height:57.0pt'></td>
  <td class=xl69 width=115 style='width:86pt'>特征请求、增强功能(RFES)和方法(TrueChain)，改进建议</td>
  <td colspan=2 style='mso-ignore:colspan'></td>
 </tr>
 <tr height=19 style='height:14.25pt'>
  <td height=19 style='height:14.25pt'></td>
  <td>X86 平台</td>
  <td colspan=2 style='mso-ignore:colspan'></td>
 </tr>
 <tr height=38 style='height:28.5pt'>
  <td height=38 style='height:28.5pt'></td>
  <td class=xl69 width=115 style='width:86pt'>一些未来的发展规划</td>
  <td colspan=2 style='mso-ignore:colspan'></td>
 </tr>
 <![if supportMisalignedColumns]>
 <tr height=0 style='display:none'>
  <td width=50 style='width:38pt'></td>
  <td width=47 style='width:35pt'></td>
  <td width=115 style='width:86pt'></td>
  <td width=137 style='width:103pt'></td>
  <td width=286 style='width:215pt'></td>
 </tr>
 <![endif]>
</table>
  <right>(Q1)1、2、3月</right>
  <p text-align="right">(Q1)1、2、3月</p>
