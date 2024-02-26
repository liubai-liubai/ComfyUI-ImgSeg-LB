一个comfyui自定义节点的创建指南

安装：不需要安装任何其他包，只需要把0x_erthor_node文件夹复制到custom_nodes文件夹下，就能安装成功。

a1：展示了代码结构，表明了每一块代码的作用是什么，哪里是输入，哪里是参数栏，哪里是输出。

a2：如何加入各种comfyui支持的数据类型，包括img，latent等。👇

![111](https://github.com/erthorpabar/guide-to-write-comfyui-custom-node/assets/161300602/af6bdef8-4728-45b5-8833-85c6f430f4ef)


a3：如何使用comfyui自带的库去索引参数，如ckpt，vae，clip等。👇

![333](https://github.com/erthorpabar/guide-to-write-comfyui-custom-node/assets/161300602/5e8aba93-0e6d-4fb1-b57e-9db492a408b5)


a4：一个最简的可以运行的节点，它创建一个空的torch.Tensor向量空间，并输出。需要连接最基础的previewimage节点才能展示出来。👇

![44](https://github.com/erthorpabar/guide-to-write-comfyui-custom-node/assets/161300602/59673717-5a72-4af2-9105-b3fd5ce06ff8)


a5：通用最简模板，日常编写节点可直接复制并在此基础上编写。


