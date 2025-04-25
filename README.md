# 模型对比关键问题解答

1. **两个模型的核心差异体现在什么机制上？**  
   A. 字符编码方式不同  
   B. 是否考虑国家信息作为生成条件 ✅  
   C. RNN单元类型不同（GRU/LSTM）  
   D. 损失函数计算方式不同  

2. **条件生成模型中，国家信息通过什么方式影响生成过程？**  
   A. 作为额外的输入特征拼接  
   B. 作为GRU的初始隐藏状态 ✅  
   C. 作为注意力机制的key  
   D. 作为输出层的偏置项  

3. ** `nation_emb` 层的主要作用是？**  
   A. 将字符索引映射为稠密向量  
   B. 将国家标签转换为隐藏状态初始化向量 ✅  
   C. 生成姓氏的长度控制参数  
   D. 计算交叉熵损失的辅助参数  

4. ** `sample_from_model` 函数新增的关键参数是？**  
   A.  `temperature`   
   B.  `nationalities`  ✅  
   C.  `device`   
   D.  `max_length` 

# 截图

![屏幕截图(65)](https://github.com/user-attachments/assets/62d63b08-b267-4a2a-97a3-e20ab199c08a)
![屏幕截图(71)](https://github.com/user-attachments/assets/5e57d779-ee8c-4cc4-837e-729877865010)
![屏幕截图(67)](https://github.com/user-attachments/assets/7328ca3e-672e-4497-8ddf-9c328a521407)
![屏幕截图(66)](https://github.com/user-attachments/assets/da092fcf-cf9f-4008-9fe9-4d4fc09829b6)
