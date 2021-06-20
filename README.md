说明

对话框.py是包含图片素描转化的代码，该代码运行后可以生成一个对话框，先选择最左侧的"Select"按钮上传您需要转化的图片，接着按"Transform"按钮完成转化，最后按"Show"按钮完成转化后的图片的展示。

CPU.ipynb的运行需要上传一个内容图片和一个风格图片。

GPU任意风格迁移.ipynb文件的运行需要自行下载数据集，根据代码中的提示去修改地址。建议您在Colab中运行您的代码。

加载模型快速迁移.ipynb文件需要在模型中加载仓库中已经提供的infwnet文件，在加载完毕已经训练完毕的模型后，您可以直接对上传的内容图片进行转化。由于该风格已经训练完毕，所以您无法进行更改模型的风格图片，原代码是利用上传的数据集进行随机选取图片，您也可以自行上传图片数据集进行风格迁移。

GPU(final).ipynb文件可以快速地对图片的风格进行迁移，您可以修改对应的风格图片和内容图片，由于该模型采用阶梯式训练和GPU加速，所以该模型大概等2分钟即可得到转化后的结果。
