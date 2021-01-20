# StudyPaddlePaddle
学习百度飞桨


#### 创建虚拟环境

    python3 -m venv venv
    
    # linux下进入venv环境
    source venv/bin/activate
    
    # venv环境下导出依赖
    pip freeze > requirements.txt
    
    # venv环境下安装依赖
    pip install -r requirements.txt


#### 安装飞桨环境
    # 安装百度飞桨 1.8.5
    python -m pip install paddlepaddle==1.8.5 -i https://mirror.baidu.com/pypi/simple
