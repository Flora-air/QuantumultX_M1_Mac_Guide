# QuantumultX_M1_Mac_Guide
# QuantumultX在M1 Mac上的使用

首先你需要在Mac AppStore上下载并安装QuantumultX，并且最好不要用共享账号
大概率你已经在iPhone、iPad上已经使用过QuantumultX，前人之述备矣
重点解决两个问题

QuantumultX在Mac上怎么开启MitM（配置证书）

<img width="545" alt="image" src="https://user-images.githubusercontent.com/62434508/225943701-d3a2e409-be8e-48cb-8de9-5cff839827e0.png">
生成的证书rootCA.crt会下载下来
双击会到一个钥匙串访问的地方
保存到系统（不要选择iCloud）（如果只为你一个用户保存的话 保存到登陆）
<img width="877" alt="image" src="https://user-images.githubusercontent.com/62434508/225945000-493ac4d5-3578-440e-b569-d75c5df01756.png">

找到我们的证书-显示简介

<img width="877" alt="image" src="https://user-images.githubusercontent.com/62434508/225945240-0b6de6e5-d061-4f07-9807-5a5f4d3e3b2c.png">

勾选始终信任

<img width="877" alt="image" src="https://user-images.githubusercontent.com/62434508/225945411-76927eb2-b769-4284-a106-73dbece2a12d.png">


QuantumultX在Mac上怎么终端代理
好像quantumultx不需要配置终端代理就可以实现终端访问（存疑）
