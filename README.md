# flink-sql-benchmark

## Run benchmark in flink

- Step 1: Prepare your flink environment.

  - Prepare flink-conf.yaml: [Recommended Conf]().

  - Setup hive integration: [Hive dependencies](https://ci.apache.org/projects/flink/flink-docs-master/dev/table/hive/#dependencies).
  
  - Setup hadoop integration: [Hadoop environment](https://ci.apache.org/projects/flink/flink-docs-release-1.9/ops/deployment/hadoop.html).
  
  - Setup flink cluster: [standalone cluster](https://ci.apache.org/projects/flink/flink-docs-master/ops/deployment/cluster_setup.html) or [Yarn session](https://ci.apache.org/projects/flink/flink-docs-master/ops/deployment/yarn_setup.html#flink-yarn-session).
  
  - Recommended environment for 10T: 20 machines. 63 processors. 1 SSD. Multi SATA.
  
## Run benchmark in other systems

Because the prepared test data is standard hive data, other calculation frameworks integrated with hive data can also run benchmark very simply. Please build your own environment and test it.


If you have any questions, please contact:
- Jingsong Lee (jingsonglee0@gmail.com)
- Rui Li (lirui@apache.org)
