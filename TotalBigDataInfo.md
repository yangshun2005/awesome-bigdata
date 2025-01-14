# 史上最全“大数据”学习资源整理

　　当前，整个互联网正在从IT时代向DT时代演进，大数据技术也正在助力企业和公众敲开DT世界大门。当今“大数据”一词的重点其实已经不仅在于数据规模的定义，它更代表着信息技术发展进入了一个新的时代，代表着爆炸性的数据信息给传统的计算技术和信息技术带来的技术挑战和困难，代表着大数据处理所需的新的技术和方法，也代表着大数据分析和应用所带来的新发明、新服务和新的发展机遇。
　　为了帮助更好深入了解大数据，翻译了GitHub Awesome Big Data资源，供大家参考。本资源类型主要包括：大数据框架、论文等实用资源集合。

## 资源列表：

### 关系数据库管理系统(RDBMS)
　　MySQL：世界最流行的开源数据库;
　　PostgreSQL：世界最先进的开源数据库;
　　Oracle 数据库：对象-关系型数据库管理系统。
 
### 框架
     Apache Hadoop：分布式处理架构，结合了 MapReduce(并行处理)、YARN(作业调度)和HDFS(分布式文件系统);
　　Tigon：高吞吐量实时流处理框架。
 
### 分布式编程
   AddThis Hydra ：最初在AddThis上开发的分布式数据处理和存储系统;
　　AMPLab SIMR：用在Hadoop MapReduce v1上运行Spark;
　　Apache Beam：为统一的模型以及一套用于定义和执行数据处理工作流的特定SDK语言;
　　Apache Crunch：一个简单的Java API，用于执行在普通的MapReduce实现时比较单调的连接、数据聚合等任务;
　　Apache DataFu：由LinkedIn开发的针对Hadoop and 和Pig的用户定义的函数集合;
　　Apache Flink：具有高性能的执行时间和自动程序优化;
　　Apache Gora：内存中的数据模型和持久性框架;
　　Apache Hama：BSP(整体同步并行)计算框架;
　　Apache MapReduce ：在集群上使用并行、分布式算法处理大数据集的编程模型;
　　Apache Pig ：Hadoop中，用于处理数据分析程序的高级查询语言;
　　Apache REEF ：用来简化和统一低层大数据系统的保留性评估执行框架;
　　Apache S4 ：S4中流处理与实现的框架;
　　Apache Spark ：内存集群计算框架;
　　Apache Spark Streaming ：流处理框架，同时是Spark的一部分;
　　Apache Storm ：Twitter流处理框架，也可用于YARN;
　　Apache Samza ：基于Kafka和YARN的流处理框架;
　　Apache Tez ：基于YARN，用于执行任务中的复杂DAG(有向无环图);
　　Apache Twill ：基于YARN的抽象概念，用于减少开发分布式应用程序的复杂度;
　　Cascalog：数据处理和查询库;
　　Cheetah ：在MapReduce之上的高性能、自定义数据仓库;
　　Concurrent Cascading ：在Hadoop上的数据管理/分析框架;
　　Damballa Parkour ：用于Clojure的MapReduce库;
　　Datasalt Pangool ：可选择的MapReduce范例;
　　DataTorrent StrAM ：为实时引擎，用于以尽可能畅通的方式、最小的开支和对性能最小的影响，实现分布式、异步、实时的内存大数据计算;
　　Facebook Corona ：为Hadoop做优化处理，从而消除单点故障;
　　Facebook Peregrine ：MapReduce框架;
　　Facebook Scuba ：分布式内存数据存储;
　　Google Dataflow ：创建数据管道，以帮助其分析框架;
　　Netflix PigPen ：为MapReduce，用于编译成Apache Pig;
　　Nokia Disco ：由Nokia开发的MapReduc获取、转换和分析数据;
　　Google MapReduce ：MapReduce框架;
　　Google MillWheel ：容错流处理框架;
　　JAQL ：用于处理结构化、半结构化和非结构化数据工作的声明性编程语言;
　　Kite ：为一组库、工具、实例和文档集，用于使在Hadoop的生态系统上建立系统更加容易;
　　Metamarkets Druid ：用于大数据集的实时e框架;
　　Onyx ：分布式云计算;
　　Pinterest Pinlater ：异步任务执行系统;
　　Pydoop ：用于Hadoop的Python MapReduce和HDFS API;
　　Rackerlabs Blueflood ：多租户分布式测度处理系统;
　　Stratosphere ：通用集群计算框架;
　　Streamdrill ：用于计算基于不同时间窗口的事件流的活动，并找到最活跃的一个;
　　Tuktu ：易于使用的用于分批处理和流计算的平台，通过Scala、 Akka和Play所建;
　　Twitter Scalding：基于Cascading，用于Map Reduce工作的Scala库;
　　Twitter Summingbird ：在Twitter上使用Scalding和Storm串流MapReduce;
　　Twitter TSAR ：Twitter上的时间序列聚合器。
 
### 分布式文件系统
　　Apache HDFS：在多台机器上存储大型文件的方式;
　　BeeGFS：以前是FhGFS，并行分布式文件系统;
　　Ceph Filesystem：设计的软件存储平台;
　　Disco DDFS：分布式文件系统;
　　Facebook Haystack：对象存储系统;
　　Google Colossus：分布式文件系统(GFS2);
　　Google GFS：分布式文件系统;
　　Google Megastore：可扩展的、高度可用的存储;
　　GridGain：兼容GGFS、Hadoop内存的文件系统;
　　Lustre file system：高性能分布式文件系统;
　　Quantcast File System QFS：开源分布式文件系统;
　　Red Hat GlusterFS：向外扩展的附网存储(Network-attached Storage)文件系统;
　　Seaweed-FS：简单的、高度可扩展的分布式文件系统;
　　Alluxio：以可靠的存储速率在跨集群框架上文件共享;
　　Tahoe-LAFS：分布式云存储系统;
 
### 文件数据模型
　　Actian Versant：商用的面向对象数据库管理系统;
　　Crate Data：是一个开源的大规模可扩展的数据存储，需要零管理模式;
　　Facebook Apollo：Facebook的Paxos算法，类似于NoSQL数据库;
　　jumboDB：基于Hadoop的面向文档的数据存储;
　　LinkedIn Espresso：可横向扩展的面向文档的NoSQL数据存储;
　　MarkLogic：模式不可知的企业版NoSQL数据库技术;
　　MongoDB：面向文档的数据库系统;
　　RavenDB：一个事务性的，开源文档数据库;
　　RethinkDB：支持连接查询和群组依据等查询的文档型数据库。
 
### Key Map 数据模型
　　注意：业内存在一些术语混乱，有两个不同的东西都叫做“列式数据库”。这里列出的有一些是围绕“key-map”数据模型而建的分布式、持续型数据库，其中所有的数据都有(可能综合了)键，并与映射中的键-值对相关联。在一些系统中，多个这样的值映射可以与键相关联，并且这些映射被称为“列族”(具有映射值的键被称为“列”)。
　　另一组也可称为“列式数据库”的技术因其存储数据的方式而有别于前一组，它在磁盘上或在存储器中——而不是以传统方式，即所有既定键的键值都相邻着、逐行存储。这些系统也彼此相邻来存储所有列值，但是要得到给定列的所有值却不需要以前那么繁复的工作。
　　前一组在这里被称为“key map数据模型”，这两者和Key-value 数据模型之间的界限是相当模糊的。后者对数据模型有更多的存储格式，可在列式数据库中列出。若想了解更多关于这两种模型的区分，可阅读Daniel Abadi的博客：Distinguishing two major types of Column Stores。
　　Apache Accumulo：内置在Hadoop上的分布式键/值存储;
　　Apache Cassandra：由BigTable授权，面向列的分布式数据存储;
　　Apache HBase：由BigTable授权，面向列的分布式数据存储;
　　Facebook HydraBase：Facebook所开发的HBase的衍化品;
　　Google BigTable：面向列的分布式数据存储;
　　Google Cloud Datastore：为完全管理型的无模式数据库，用于存储在BigTable上非关系型数据;
　　Hypertable：由BigTable授权，面向列的分布式数据存储;
　　InfiniDB：通过MySQL的接口访问，并使用大规模并行处理进行并行查询;
　　Tephra：用于HBase处理;
　　Twitter Manhattan：Twitter的实时、多租户分布式数据库。
 
### 键-值数据模型
　　Aerospike：支持NoSQL的闪存优化，数据存储在内存。开源，“'C'(不是Java或Erlang)中的服务器代码可精确地调整从而避免上下文切换和内存拷贝”。
　　Amazon DynamoDB：分布式键/值存储，Dynamo论文的实现;
　　Edis：为替代Redis的协议兼容的服务器;
　　ElephantDB：专门研究Hadoop中数据导出的分布式数据库;
　　EventStore：分布式时间序列数据库;
　　GridDB：适用于存储在时间序列中的传感器数据;
　　LinkedIn Krati：简单的持久性数据存储，拥有低延迟和高吞吐量;
　　Linkedin Voldemort：分布式键/值存储系统;
　　Oracle NoSQL Database：Oracle公司开发的分布式键值数据库;
　　Redis：内存中的键值数据存储;
　　Riak：分散式数据存储;
　　Storehaus：Twitter开发的异步键值存储的库;
　　Tarantool：一个高效的NoSQL数据库和Lua应用服务器;
　　TiKV：由Google Spanner和HBase授权，Rust提供技术支持的分布式键值数据库;
　　TreodeDB：可复制、共享的键-值存储，能提供多行原子写入。
 
### 图形数据模型
　　Apache Giraph：基于Hadoop的Pregel实现;
　　Apache Spark Bagel：可实现Pregel，为Spark的一部分;
　　ArangoDB：多层模型分布式数据库;
　　DGraph：一个可扩展的、分布式、低时延、高吞吐量的图形数据库，旨在为Google生产水平规模和吞吐量提供足够的低延迟，用于TB级的结构化数据的实时用户查询;
　　Facebook TAO：TAO是facebook广泛用来存储和服务于社交图形的分布式数据存储;
　　GCHQ Gaffer：GCHQ中的Gaffer是一个易于存储大规模图形的框架，其中节点和边缘都有统计数据;
　　Google Cayley：开源图形数据库;
　　Google Pregel ：图形处理框架;
　　GraphLab PowerGraph：核心C ++ GraphLab API和建立在GraphLab API之上的高性能机器学习和数据挖掘工具包的集合;
　　GraphX：Spark中的弹性分布式图形系统;
　　Gremlin：图形追踪语言;
　　Infovore：以RDF为中心的Map / Reduce框架;
　　Intel GraphBuilder：在Hadoop上构建大规模图形的工具;
　　MapGraph：用于在GPU上大规模并行图形处理;
　　Neo4j：完全用Java写入的图形数据库;
　　OrientDB：文档和图形数据库;
　　Phoebus：大型图形处理框架;
　　Titan：建于Cassandra的分布式图形数据库;
　　Twitter FlockDB：分布式图形数据库。
 
### NewSQL数据库 
　　Actian Ingres：由商业支持，开源的SQL关系数据库管理系统;
　　Amazon RedShift：基于PostgreSQL的数据仓库服务;
　　BayesDB：面向统计数值的SQL数据库;
　　CitusDB：通过分区和复制横向扩展PostgreSQL;
　　Cockroach：可扩展、地址可复制、交易型的数据库;
　　Datomic：旨在产生可扩展、灵活的智能应用的分布式数据库;
　　FoundationDB：由F1授意的分布式数据库;
　　Google F1：建立在Spanner上的分布式SQL数据库;
　　Google Spanner：全球性的分布式半关系型数据库;
　　H-Store：是一个实验性主存并行数据库管理系统，用于联机事务处理(OLTP)应用的优化;
　　Haeinsa：基于Percolator，HBase的线性可扩展多行多表交易库;
　　HandlerSocket：MySQL/MariaDB的NoSQL插件;
　　InfiniSQL：无限可扩展的RDBMS;
　　MemSQL：内存中的SQL数据库，其中有优化的闪存列存储;
　　NuoDB：SQL / ACID兼容的分布式数据库;
　　Oracle TimesTen in-Memory Database：内存中具有持久性和可恢复性的关系型数据库管理系统;
　　Pivotal GemFire XD：内存中低延时的分布式SQL数据存储，可为内存列表数据提供SQL接口，在HDFS中较持久化;
　　SAP HANA：是在内存中面向列的关系型数据库管理系统;
　　SenseiDB：分布式实时半结构化的数据库;
　　Sky：用于行为数据的灵活、高性能分析的数据库;
　　SymmetricDS：用于文件和数据库同步的开源软件;
　　Map-D：为GPU内存数据库，也为大数据分析和可视化平台;
　　TiDB：TiDB是分布式SQL数据库，基于谷歌F1的设计灵感;
　　VoltDB：自称为最快的内存数据库。
 
### 列式数据库
　　注意：请在键-值数据模型 阅读相关注释。
　　Columnar Storage：解释什么是列存储以及何时会需要用到它;
　　Actian Vector：面向列的分析型数据库;
　　C-Store：面向列的DBMS;
　　MonetDB：列存储数据库;
　　Parquet：Hadoop的列存储格式;
　　Pivotal Greenplum：专门设计的、专用的分析数据仓库，类似于传统的基于行的工具，提供了一个列式工具;
　　Vertica：用来管理大规模、快速增长的大量数据，当用于数据仓库时，能够提供非常快的查询性能;
　　Google BigQuery ：谷歌的云产品，由其在Dremel的创始工作提供支持;
　　Amazon Redshift ：亚马逊的云产品，它也是基于柱状数据存储后端。
 
### 时间序列数据库
　　Cube：使用MongoDB来存储时间序列数据;
　　Axibase Time Series Database：在HBase之上的分布式时间序列数据库，它包括内置的Rule Engine、数据预测和可视化;
　　Heroic：基于Cassandra和Elasticsearch的可扩展的时间序列数据库;
　　InfluxDB：分布式时间序列数据库;
　　Kairosdb：类似于OpenTSDB但会考虑到Cassandra;
　　OpenTSDB：在HBase上的分布式时间序列数据库;
　　Prometheus：一种时间序列数据库和服务监测系统;
　　Newts：一种基于Apache Cassandra的时间序列数据库。
 
### 类SQL处理
　　Actian SQL for Hadoop：高性能交互式的SQL，可访问所有的Hadoop数据;
　　Apache Drill：由Dremel授意的交互式分析框架;
　　Apache HCatalog：Hadoop的表格和存储管理层;
　　Apache Hive：Hadoop的类SQL数据仓库系统;
　　Apache Optiq：一种框架，可允许高效的查询翻译，其中包括异构性及联合性数据的查询;
　　Apache Phoenix：Apache Phoenix 是 HBase 的 SQL 驱动;
　　Cloudera Impala：由Dremel授意的交互式分析框架;
　　Concurrent Lingual：Cascading中的类SQL查询语言;
　　Datasalt Splout SQL：用于大数据集的完整的SQL查询工具;
　　Facebook PrestoDB：分布式SQL查询工具;
　　Google BigQuery：交互式分析框架，Dremel的实现;
　　Pivotal HAWQ：Hadoop的类SQL的数据仓库系统;
　　RainstorDB：用于存储大规模PB级结构化和半结构化数据的数据库;
　　Spark Catalyst：用于Spark和Shark的查询优化框架;
　　SparkSQL：使用Spark操作结构化数据;
　　Splice Machine：一个全功能的Hadoop上的SQL RDBMS，并带有ACID事务;
　　Stinger：用于Hive的交互式查询;
　　Tajo：Hadoop的分布式数据仓库系统;
　　Trafodion：为企业级的SQL-on-HBase针对大数据的事务或业务工作负载的解决方案。
 
### 数据摄取
　　Amazon Kinesis：大规模数据流的实时处理;
　　Apache Chukwa：数据采集系统;
　　Apache Flume：管理大量日志数据的服务;
　　Apache Kafka：分布式发布-订阅消息系统;
　　Apache Sqoop：在Hadoop和结构化的数据存储区之间传送数据的工具;
　　Cloudera Morphlines：帮助 Solr、HBase和HDFS完成ETL的框架;
　　Facebook Scribe：流日志数据聚合器;
　　Fluentd：采集事件和日志的工具;
　　Google Photon：实时连接多个数据流的分布式计算机系统，具有高可扩展性和低延迟性;
　　Heka：开源流处理软件系统;
　　HIHO：用Hadoop连接不同数据源的框架;
　　Kestrel：分布式消息队列系统;
　　LinkedIn Databus：对数据库更改捕获的事件流;
　　LinkedIn Kamikaze：压缩已分类整型数组的程序包;
　　LinkedIn White Elephant：日志聚合器和仪表板;
　　Logstash：用于管理事件和日志的工具;
　　Netflix Suro：像基于Chukwa 的Storm和Samza一样的日志聚合器;
　　Pinterest Secor：是实现Kafka日志持久性的服务;
　　Linkedin Gobblin：LinkedIn的通用数据摄取框架;
　　Skizze：是一种数据存储略图，使用概率性数据结构来处理计数、略图等相关的问题;
　　StreamSets Data Collector：连续大数据采集的基础设施，可简单地使用IDE。
 
### 服务编程
　　Akka Toolkit：JVM中分布性、容错事件驱动应用程序的运行时间;
　　Apache Avro：数据序列化系统;
　　Apache Curator：Apache ZooKeeper的Java库;
　　Apache Karaf：在任何OSGi框架之上运行的OSGi运行时间;
　　Apache Thrift：构建二进制协议的框架;
　　Apache Zookeeper：流程管理集中式服务;
　　Google Chubby：一种松耦合分布式系统锁服务;
　　Linkedin Norbert：集群管理器;
　　OpenMPI：消息传递框架;
　　Serf：服务发现和协调的分散化解决方案;
　　Spotify Luigi：一种构建批处理作业的复杂管道的Python包，它能够处理依赖性解析、工作流管理、可视化、故障处理、命令行一体化等等问题;
　　Spring XD：数据摄取、实时分析、批量处理和数据导出的分布式、可扩展系统;
　　Twitter Elephant Bird：LZO压缩数据的工作库;
　　Twitter Finagle：JVM的异步网络堆栈。
 
### 调度
　　Apache Aurora：在Apache Mesos之上运行的服务调度程序;
　　Apache Falcon：数据管理框架;
　　Apache Oozie：工作流作业调度程序;
　　Chronos：分布式容错调度;
　　Linkedin Azkaban：批处理工作流作业调度;
　　Schedoscope：Hadoop作业敏捷调度的Scala DSL;
　　Sparrow：调度平台;
　　Airflow：一个以编程方式编写、调度和监控工作流的平台。
 
### 机器学习
　　Apache Mahout：Hadoop的机器学习库;
　　brain：JavaScript中的神经网络;
　　Cloudera Oryx：实时大规模机器学习;
　　Concurrent Pattern：Cascading的机器学习库;
　　convnetjs：Javascript中的机器学习，在浏览器中训练卷积神经网络(或普通网络);
　　Decider：Ruby中灵活、可扩展的机器学习;
　　ENCOG：支持多种先进算法的机器学习框架，同时支持类的标准化和处理数据;
　　etcML：机器学习文本分类;
　　Etsy Conjecture：Scalding中可扩展的机器学习;
　　Google Sibyl：Google中的大规模机器学习系统;
　　GraphLab Create：Python的机器学习平台，包括ML工具包、数据工程和部署工具的广泛集合;
　　H2O：Hadoop统计性的机器学习和数学运行时间;
　　MLbase：用于BDAS堆栈的分布式机器学习库;
　　MLPNeuralNet：针对iOS和Mac OS X的快速多层感知神经网络库;
　　MonkeyLearn：使文本挖掘更为容易，从文本中提取分类数据;
　　nupic：智能计算的Numenta平台，它是一个启发大脑的机器智力平台，基于皮质学习算法的精准的生物神经网络;
　　PredictionIO：建于Hadoop、Mahout和Cascading上的机器学习服务器;
　　SAMOA：分布式流媒体机器学习框架;
　　scikit-learn：scikit-learn为Python中的机器学习;
　　Spark MLlib：Spark中一些常用的机器学习(ML)功能的实现;
　　Vowpal Wabbit：微软和雅虎发起的学习系统;
　　WEKA：机器学习软件套件;
　　BidMach：CPU和加速GPU的机器学习库。
 
### 基准测试
　　Apache Hadoop Benchmarking：测试Hadoop性能的微基准;
　　Berkeley SWIM Benchmark：现实大数据工作负载基准测试;
　　Intel HiBench：Hadoop基准测试套件;
　　PUMA Benchmarking：MapReduce应用的基准测试套件;
　　Yahoo Gridmix3：雅虎工程师团队的Hadoop集群基准测试。
 
### 安全性
　　Apache Knox Gateway：Hadoop集群安全访问的单点;
　　Apache Sentry：存储在Hadoop的数据安全模块。
 
 
## 系统部署
　　Apache Ambari：Hadoop管理的运作框架;
　　Apache Bigtop：Hadoop生态系统的部署框架;
　　Apache Helix：集群管理框架;
　　Apache Mesos：集群管理器;
　　Apache Slider：一种YARN应用，用来部署YARN中现有的分布式应用程序;
　　Apache Whirr：运行云服务的库集;
　　Apache YARN：集群管理器;
　　Brooklyn：用于简化应用程序部署和管理的库;
　　Buildoop：基于Groovy语言，和Apache BigTop类似;
　　Cloudera HUE：和Hadoop进行交互的Web应用程序;
　　Facebook Prism：多数据中心复制系统;
　　Google Borg：作业调度和监控系统;
　　Google Omega：作业调度和监控系统;
　　Hortonworks HOYA：可在YARN上部署HBase集群的应用;
　　Marathon：用于长期运行服务的Mesos框架。
 
 
### 应用程序
　　Adobe spindle：使用Scala、Spark和Parquet处理的下一代web分析;
　　Apache Kiji：基于HBase，实时采集和分析数据的框架;
　　Apache Nutch：开源网络爬虫;
　　Apache OODT：用于NASA科学档案中数据的捕获、处理和共享;
　　Apache Tika：内容分析工具包;
　　Argus：时间序列监测和报警平台;
　　Countly：基于Node.js和MongoDB，开源的手机和网络分析平台;
　　Domino：运行、规划、共享和部署模型——没有任何基础设施;
　　Eclipse BIRT：基于Eclipse的报告系统;
　　Eventhub：开源的事件分析平台;
　　Hermes：建于Kafka上的异步消息代理;
　　HIPI Library：在Hadoop's MapReduce上执行图像处理任务的API;
　　Hunk：Hadoop的Splunk分析;
　　Imhotep：大规模分析平台;
　　MADlib：RDBMS的用于数据分析的数据处理库;
　　Kylin：来自eBay的开源分布式分析工具;
　　PivotalR：Pivotal HD / HAWQ和PostgreSQL中的R;
　　Qubole：为自动缩放Hadoop集群，内置的数据连接器;
　　Sense：用于数据科学和大数据分析的云平台;
　　SnappyData：用于实时运营分析的分布式内存数据存储，提供建立在Spark单一集成集群中的数据流分析、OLTP(联机事务处理)和OLAP(联机分析处理);
　　Snowplow：企业级网络和事件分析，由Hadoop、Kinesis、Redshift 和Postgres提供技术支持;
　　SparkR：Spark的R前端;
　　Splunk：用于机器生成的数据的分析;
　　Sumo Logic：基于云的分析仪，用于分析机器生成的数据;
　　Talend：用于YARN、Hadoop、HBASE、Hive、HCatalog和Pig的统一开源环境;
　　Warp：利用大数据(OS X app)的实例查询工具。
 
### 搜索引擎与框架 
　　Apache Lucene：搜索引擎库;
　　Apache Solr：用于Apache Lucene的搜索平台;
　　ElasticSearch：基于Apache Lucene的搜索和分析引擎;
　　Enigma.io：为免费增值的健壮性web应用，用于探索、筛选、分析、搜索和导出来自网络的大规模数据集;
　　Facebook Unicorn：社交图形搜索平台;
　　Google Caffeine：连续索引系统;
　　Google Percolator：连续索引系统;
　　TeraGoogle：大型搜索索引;
　　HBase Coprocessor：为Percolator的实现，HBase的一部分;
　　Lily HBase Indexer：快速、轻松地搜索存储在HBase的任何内容;
　　LinkedIn Bobo：完全由Java编写的分面搜索的实现，为Apache Lucene的延伸;
　　LinkedIn Cleo：为一个一个灵活的软件库，使得局部、无序、实时预输入的搜索实现了快速发展;
　　LinkedIn Galene：LinkedIn搜索架构;
　　LinkedIn Zoie：是用Java编写的实时搜索/索引系统;
　　Sphinx Search Server：全文搜索引擎
 
### MySQL的分支和演化 
　　Amazon RDS：亚马逊云的MySQL数据库;
　　Drizzle：MySQL的6.0的演化;
　　Google Cloud SQL：谷歌云的MySQL数据库;
　　MariaDB：MySQL的增强版嵌入式替代品;
　　MySQL Cluster：使用NDB集群存储引擎的MySQL实现;
　　Percona Server：MySQL的增强版嵌入式替代品;
　　ProxySQL：MySQL的高性能代理;
　　TokuDB：用于MySQL和 MariaDB的存储引擎;
　　WebScaleSQL：运行MySQL时面临类似挑战的几家公司，它们的工程师之间的合作。
 
### PostgreSQL的分支和演化
　　Yahoo Everest - multi-peta-byte database / MPP derived by PostgreSQL.
　　HadoopDB：MapReduce和DBMS的混合体;
　　IBM Netezza：高性能数据仓库设备;
　　Postgres-XL：基于PostgreSQL，可扩展的开源数据库集群;
　　RecDB：完全建立在PostgreSQL内部的开源推荐引擎;
　　Stado：开源MPP数据库系统，只针对数据仓库和数据集市的应用程序;
　　Yahoo Everest：PostgreSQL可以推导多字节P比特数据库/MPP。
 
### Memcached的分支和演化
　　Facebook McDipper：闪存的键/值缓存;
　　Facebook Memcached：Memcache的分支;
　　Twemproxy：Memcached和Redis的快速、轻型代理;
　　Twitter Fatcache：闪存的键/值缓存;
　　Twitter Twemcache：Memcache的分支。
 
### 嵌入式数据库
　　Actian PSQL：Pervasive Software公司开发的ACID兼容的DBMS，在应用程序中嵌入了优化;
　　BerkeleyDB：为键/值数据提供一个高性能的嵌入式数据库的一个软件库;
　　HanoiDB：Erlang LSM BTree存储;
　　LevelDB：谷歌写的一个快速键-值存储库，它提供了从字符串键到字符串值的有序映射;
　　LMDB：Symas开发的超快、超紧凑的键-值嵌入的式数据存储;
　　RocksDB：基于性LevelDB，用于快速存储的嵌入式持续性键-值存储。
　　商业智能
　　BIME Analytics：商业智能云平台;
　　Chartio：精益业务智能平台，用于可视化和探索数据;
　　datapine：基于云的自助服务商业智能工具;
　　Jaspersoft：功能强大的商业智能套件;
　　Jedox Palo：定制的商业智能平台;
　　Microsoft：商业智能软件和平台;
　　Microstrategy：商业智能、移动智能和网络应用软件平台;
　　Pentaho：商业智能平台;
　　Qlik：商业智能和分析平台;
　　Saiku：开源的分析平台;
　　SpagoBI：开源商业智能平台;
　　Tableau：商业智能平台;
　　Zoomdata：大数据分析;
　　Jethrodata：交互式大数据分析。
 
### 数据可视化 
　　Airpal：用于PrestoDB的网页UI;
　　Arbor：利用网络工作者和jQuery的图形可视化库;
　　Banana：对存储在Kibana中Solr. Port的日志和时戳数据进行可视化;
　　Bokeh：一个功能强大的Python交互式可视化库，它针对要展示的现代web浏览器，旨在为D3.js风格的新奇的图形提供优雅简洁的设计，同时在大规模数据或流数据集中，通过高性能交互性来表达这种能力;
　　C3：基于D3可重复使用的图表库;
　　CartoDB：开源或免费增值的虚拟主机，用于带有强大的前端编辑功能和API的地理空间数据库;
　　chartd：只带Img标签的反应灵敏、兼容Retina的图表;
　　Chart.js：开源的HTML5图表可视化效果;
　　Chartist.js：另一个开源HTML5图表可视化效果;
　　Crossfilter：JavaScript库，用于在浏览器中探索多元大数据集，用Dc.js和D3.js.效果很好;
　　Cubism：用于时间序列可视化的JavaScript库;
　　Cytoscape：用于可视化复杂网络的JavaScript库;
　　DC.js：维度图表，和Crossfilter一起使用，通过D3.js呈现出来，它比较擅长连接图表/附加的元数据，从而徘徊在D3的事件附近;
　　D3：操作文件的JavaScript库;
　　D3.compose：从可重复使用的图表和组件构成复杂的、数据驱动的可视化;
　　D3Plus：一组相当强大的可重用的图表，还有D3.js的样式;
　　Echarts：百度企业场景图表;
　　Envisionjs：动态HTML5可视化;
　　FnordMetric：写SQL查询，返回SVG图表，而不是表;
　　Freeboard：针对IOT和其他Web混搭的开源实时仪表盘构建;
　　Gephi：屡获殊荣的开源平台，可视化和操纵大型图形和网络连接，有点像Photoshop，但是针对于图表，适用于Windows和Mac OS X;
　　Google Charts：简单的图表API;
　　Grafana：石墨仪表板前端、编辑器和图形组合器;
　　Graphite：可扩展的实时图表;
　　Highcharts：简单而灵活的图表API;
　　IPython：为交互式计算提供丰富的架构;
　　Kibana：可视化日志和时间标记数据;
　　Matplotlib：Python绘图;
　　Metricsgraphic.js：建立在D3之上的库，针对时间序列数据进行最优化;
　　NVD3：d3.js的图表组件;
　　Peity：渐进式SVG条形图，折线和饼图;
　　Plot.ly：易于使用的Web服务，它允许快速创建从热图到直方图等复杂的图表，使用图表Plotly的在线电子表格上传数据进行创建和设计;
　　Plotly.js：支持plotly的开源JavaScript图形库;
　　Recline：简单但功能强大的库，纯粹利用JavaScript和HTML构建数据应用;
　　Redash：查询和可视化数据的开源平台;
　　Shiny：针对R的Web应用程序框架;
　　Sigma.js：JavaScript库，专门用于图形绘制;
　　Vega：一个可视化语法;
　　Zeppelin：一个笔记本式的协作数据分析;
　　Zing Charts：用于大数据的JavaScript图表库。
 
### 物联网和传感器
　　TempoIQ：基于云的传感器分析;
　　2lemetry：物联网平台;
　　Pubnub：数据流网络;
　　ThingWorx：ThingWorx 是让企业快速创建和运行互联应用程序平台;
　　IFTTT：IFTTT 是一个被称为 “网络自动化神器” 的创新型互联网服务，它的全称是 If this then that，意思是“如果这样，那么就那样”;
　　Evrythng：Evrythng则是一款真正意义上的大众物联网平台，使得身边的很多产品变得智能化。
 
## 文章推荐
　　NoSQL Comparison(NoSQL 比较)- Cassandra vs MongoDB vs CouchDB vs Redis vs Riak vs HBase vs Couchbase vs Neo4j vs Hypertable vs ElasticSearch vs Accumulo vs VoltDB vs Scalaris comparison;
　　Big Data Benchmark(大数据基准)- Redshift, Hive, Shark, Impala and Stiger/Tez的基准;
　　The big data successor of the spreadsheet(电子表格的大数据继承者) - 电子表格的继承者应该是大数据。
 
## 论文
　　2015 - 2016
　　2015 - Facebook - One Trillion Edges: Graph Processing at Facebook-Scale.(一兆边：Facebook规模的图像处理)
　　2013 - 2014
　　2014 - Stanford - Mining of Massive Datasets.(海量数据集挖掘)
　　2013 - AMPLab - Presto: Distributed Machine Learning and Graph Processing with Sparse Matrices. (Presto： 稀疏矩阵的分布式机器学习和图像处理)
　　2013 - AMPLab - MLbase: A Distributed Machine-learning System. (MLbase：分布式机器学习系统)
　　2013 - AMPLab - Shark: SQL and Rich Analytics at Scale. (Shark: 大规模的SQL 和丰富的分析)
　　2013 - AMPLab - GraphX: A Resilient Distributed Graph System on Spark. (GraphX:基于Spark的弹性分布式图计算系统)
　　2013 - Google - HyperLogLog in Practice: Algorithmic Engineering of a State of The Art Cardinality Estimation Algorithm. (HyperLogLog实践:一个艺术形态的基数估算算法)
　　2013 - Microsoft - Scalable Progressive Analytics on Big Data in the Cloud.(云端大数据的可扩展性渐进分析)
　　2013 - Metamarkets - Druid: A Real-time Analytical Data Store. (Druid：实时分析数据存储)
　　2013 - Google - Online, Asynchronous Schema Change in F1.(F1中在线、异步模式的转变)
　　2013 - Google - F1: A Distributed SQL Database That Scales. (F1: 分布式SQL数据库)
　　2013 - Google - MillWheel: Fault-Tolerant Stream Processing at Internet Scale.(MillWheel: 互联网规模下的容错流处理)
　　2013 - Facebook - Scuba: Diving into Data at Facebook. (Scuba: 深入Facebook的数据世界)
　　2013 - Facebook - Unicorn: A System for Searching the Social Graph. (Unicorn: 一种搜索社交图的系统)
　　2013 - Facebook - Scaling Memcache at Facebook. (Facebook 对 Memcache 伸缩性的增强)
　　2011 - 2012
　　2012 - Twitter - The Unified Logging Infrastructure for Data Analytics at Twitter. (Twitter数据分析的统一日志基础结构)
　　2012 - AMPLab –Blink and It’s Done: Interactive Queries on Very Large Data. (Blink及其完成：超大规模数据的交互式查询)
　　2012 - AMPLab –Fast and Interactive Analytics over Hadoop Data with Spark. (Spark上 Hadoop数据的快速交互式分析)
　　2012 - AMPLab –Shark: Fast Data Analysis Using Coarse-grained Distributed Memory. (Shark：使用粗粒度的分布式内存快速数据分析)
　　2012 - Microsoft –Paxos Replicated State Machines as the Basis of a High-Performance Data Store. (Paxos的复制状态机——高性能数据存储的基础)
　　2012 - Microsoft –Paxos Made Parallel. (Paxos算法实现并行)
　　2012 - AMPLab – BlinkDB：BlinkDB: Queries with Bounded Errors and Bounded Response Times on Very Large Data.(超大规模数据中有限误差与有界响应时间的查询)
　　2012 - Google –Processing a trillion cells per mouse click.(每次点击处理一兆个单元格)
　　2012 - Google –Spanner: Google’s Globally-Distributed Database.(Spanner：谷歌的全球分布式数据库)
　　2011 - AMPLab –Scarlett: Coping with Skewed Popularity Content in MapReduce Clusters.(Scarlett：应对MapReduce集群中的偏向性内容)
　　2011 - AMPLab –Mesos: A Platform for Fine-Grained Resource Sharing in the Data Center.(Mesos：数据中心中细粒度资源共享的平台)
　　2011 - Google –Megastore: Providing Scalable, Highly Available Storage for Interactive Services.(Megastore：为交互式服务提供可扩展，高度可用的存储)
　　2001 - 2010
　　2010 - Facebook - Finding a needle in Haystack: Facebook’s photo storage.(探究Haystack中的细微之处： Facebook图片存储)
　　2010 - AMPLab - Spark: Cluster Computing with Working Sets.(Spark:工作组上的集群计算)
　　2010 - Google - Storage Architecture and Challenges.(存储架构与挑战)
　　2010 - Google - Pregel: A System for Large-Scale Graph Processing.(Pregel: 一种大型图形处理系统)
　　2010 - Google - Large-scale Incremental Processing Using Distributed Transactions and Notiﬁcations base of Percolator and Caffeine.(使用基于Percolator 和 Caffeine平台分布式事务和通知的大规模增量处理)
　　2010 - Google - Dremel: Interactive Analysis of Web-Scale Datasets.(Dremel: Web规模数据集的交互分析)
　　2010 - Yahoo - S4: Distributed Stream Computing Platform.(S4:分布式流计算平台)
　　2009 - HadoopDB：An Architectural Hybrid of MapReduce and DBMS Technologies for Analytical Workloads.(混合MapReduce和DBMS技术用于分析工作负载的的架构)
　　2008 - AMPLab - Chukwa: A large-scale monitoring system.(Chukwa: 大型监控系统)
　　2007 - Amazon - Dynamo: Amazon’s Highly Available Key-value Store.(Dynamo: 亚马逊的高可用的关键价值存储)
　　2006 - Google - The Chubby lock service for loosely-coupled distributed systems.(面向松散耦合的分布式系统的锁服务)
　　2006 - Google - Bigtable: A Distributed Storage System for Structured Data.(Bigtable: 结构化数据的分布式存储系统)
　　2004 - Google - MapReduce: Simplied Data Processing on Large Clusters.(MapReduce: 大型集群上简化数据处理)
　　2003 - Google - The Google File System.(谷歌文件系统)
