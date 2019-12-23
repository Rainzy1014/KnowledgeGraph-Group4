
<!-- **Financial Knowledge Graph** -->
<font size="66">**Financial Knowledge Graph**</font>

-------
# 项目介绍

这是一个金融领域知识图谱，并以该知识图谱完成自动问答与分析服务。


# 项目运行方式
1、配置要求：要求配置neo4j数据库及相应的python依赖包。neo4j数据库用户名密码记住，并修改相应文件。
2、知识图谱数据导入：python build_stockgraph.py
3、启动问答：python chat_graph.py

# 以下介绍详细方案
# 一、金融知识图谱构建


# 1.1 程序功能
prepare_data/build_stock_data.py：问财api获取数据生成json或者csv脚本
prepare_data/max_cut.py：基于词典的最大向前/向后切分
build_stockgraph.py：知识图谱构建    　　

# 1.2 金融领域知识图谱规模
1.2.1 neo4j图数据库存储规模
![image](https://github.com/rainzy09/KnowledgeGraph-Group4/blob/master/img/graph_summary.png)




# 二、基于金融知识图谱的自动问答


# 2.1 程序功能
question_classifier.py：问句类型分类
question_parser.py：问句解析脚本
chatbot_graph.py：问答程序脚本




# 结果示例

        问题:创元科技的老板是谁？
        王小四: 000551 创元科技的实际控制人是：苏州市人民政府(地方国资委)
        

