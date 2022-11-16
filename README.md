# ML-CW-2

PCR 1代表成功移除肿瘤，0代表未成功——>classification\
RFS 代表进行化疗后，人能存活的时间——>regression

**![img.png](img.png)**

testDatasetExamples文件只是一个样板，并不是真正的test set\
Classification用accuracy，Regression用MAE（absolute）

最后输出存到两个文件，一个是classification的输出，一个是regression的输出；第一列是ID，第二列是PCR或者RFS

你的FinalTestPCR/RFS文件中不需要保存cross validation（等evaluation method），只需要保存建立model的代码，完整的代码放到另一个文件中（会被检查）
