# 什么时TinkerPop
Apache TinkerPop是一种图计算框架，即可用于图数据库，也可以用于图分析系统。

# 更多细节
TinkerPop位于一个大开发生态圈的中心，基于TinkerPop的核心接口、集成点和思路扩展出了许多组件和库。如下所述：

## Graph Systems
1. Blazegraph - 支持OLTP的RDF图数据库
2. ChronoGraph - 一个版本化的图数据库
3. DSEGraph - 支持OLTP和OLAP的图数据库
4. GRAKN.AI - 分布式OLTP/OLAP知识图系统
5. Hadoop (Giraph) - 基于Giraph实现的OLAP图处理组件
6. Hadoop (Spark) - 基于Spark实现的OLAP图处理组件
7. HGraphDB - 运行在HBase之上的OLTP图数据库
8. IBM Graph - OLTP图数据库提供为一个服务
9. Neo4j - OLTP图数据库(支持嵌入式和高可用的部署)
10. neo4j-gremlin-bolt - OLTP图数据库(使用Bolt协议)
11. OrientDB - OLTP图数据库
12. Sqlg - 基于HSQLDB和Postresql实现的关系型数据库OLTP
13. Stardog - 支持OLTP和OLAP的RDF图数据库
14. TinkerGraph - 内存OLTP和OLAP参考实现
15. Titan - 支持BerkeleyDB、Cassandra和HBase的分布式OLTP和OLAP图数据库
16. Titan (Amazon) - The Amazon DynamoDB storage backend for Titan
17. Titan (Tupl) - The Tupl storage backend for Titan
18. Unipop - OLTP Elasticsearch and JDBC backed graph

## Query Languages
1. gremlin-python (python/variant) - Gremlin hosted in Python for use with any Python-based VM
2. gremlin-py (python/variant) - Write pure Python Gremlin that can be sent to Gremlin Server
3. gremlin-scala (scala/variant) - A Scala-based Gremlin language variant for TinkerPop3
4. gremlin-template-string (js/variant) - A Gremlin language builder
5. ipython-gremlin (python/variant) - Gremlin in IPython and Jupyter
6. ogre (clojure/variant) - A Clojure language wrapper for TinkerPop3
7. Peapod (java/dsl) - An object-graph-wrapper
8. sparql-gremlin (sparql/distinct) - A SPARQL to Gremlin traversal compiler
9. sql-gremlin (sql/distinct) - An SQL to Gremlin traversal compiler

## Language Drivers
1. Goblin (python) - An asynchronous Python 3.5 toolkit for Gremlin Server.
2. gremlinclient (python) - An asynchronous Python 2/3 client for Gremlin Server that allows for flexible coroutine syntax - Trollius, Tornado, Asyncio.
3. gremlin_client (ruby) - A Gremlin Server driver for Ruby.
4. gremlin-driver (java) - A Gremlin Server driver for Java.
5. gremlin-javascript (js) - A Gremlin Server driver for JavaScript.
6. gremgo (go) - A Gremlin Server driver for Go.
7. gremlinrestclient (python) - Python 2/3 library that uses HTTP to communicate with the Gremlin Server over REST.
8. gremlin-php (php) - A Gremlin Server driver for PHP.
9. python-gremlin-rest (python) - A REST-based client for Gremlin Server.
10. reactive-gremlin (scala) - An Akka HTTP Websocket Connector.
11. scalajs-gremlin-client (scala) - A Gremlin-Server client with ad-hoc extensible, reactive, typeclass based API.
12. Teva Gremlin (.NET - C#) - A Gremlin Server driver for .NET.
13. ts-tinkerpop (typescript) - A helper library for Typescript applications via node-java.
