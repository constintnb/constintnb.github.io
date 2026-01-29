---
title:          "Achieving High Energy Efficiency for NetworkSlicing-Enabled 5G O-RAN Base Stations"
date:           2024-12-12
selected:       false                        # 设置为 true 会在首页“精选论文”中显示
pub:            "IEEE International Conferences on High Performance Computing and Communications (HPCC2024)"
pub_date:       "2024"                      # 显示在会议名后面的年份
#pub_last:       ' <span class="badge badge-pill badge-publication badge-success">Spotlight</span>' # 可选：添加徽章 (Oral, Spotlight, Best Paper)

# 引用计数 (可选)
#semantic_scholar_id: 204e3073870fae3d05bcbc2f6a8e263d9b72e776

# 摘要 (支持 HTML 和 LaTeX 公式)
abstract: >-
  Abstract—t—With the rapid advancement of 5G networks, dataintensive 
  services has been surging and significantly increasingenergy consumption. 
  It is a critical challenge in addressingenergy efficiency 
  for 5G access networks. In this paper, wepropose an effective load 
  balancing algorithm that optimizesenergy efficiency as users access 
  multiple services from basestations (BS). Utilizing network slicing, 
  the physical network issegmented into multiple independent virtual 
  networks. We haveapplied graph neural networks (GNN) to extract 
  features fromdynamic traffic, model relationships between different 
  services,and manage resource competition among BSs and network slices,
  treating each network slice as a distinct node. The GNN modelpredicts 
  nodes workload, guiding the allocation of frequencydomain resources and 
  facilitating load balancing. Additionally,to reduce operational times 
  and minimize disparities amongslices at each BS, we propose a deep reinforcement 
  learning(DRL) strategy. This strategy is integrated with the C-statesmechanism 
  of CPUs on general x86 computing platforms tofurther enhance energy efficiency. 
  In simulations, our GNNalgorithm demonstrated high precision in predicting and 
  allocating frequency domain resources, achieving a high accuracyof 99.8%. Our DRL 
  algorithm showed a maximum globalenergy efficiency improvement of 12% compared to 
  benchmarkalgorithms. Overall, our approach enhanced energy efficiency byan 
  average of 3.155 B/J under conditions of resource competition,significantly
  outperforming strategies that allocate equal physicalresource blocks (PRB).
  Index Terms—5G access network slicing, resource allocation,reinforcement 
  learning, graph neural network, high energyefficiency, CPU C-states

# 封面图片 (可选)
cover:          

# 作者列表 (支持特殊标记)
authors:
  - Yuehan Liu
  - Leyu Zhao
  - Jingtong Wu
  - Di Liu
  - Xiaojun Hei


# 链接按钮 (自动生成对应的按钮)
links:
  Paper: https://hustdian.feishu.cn/file/IuZZb1BXxovOTaxzWyvcFI79n7d
---