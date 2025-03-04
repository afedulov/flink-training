# Lab: Advanced Tuning & Troubleshooting: Checkpointing

## Exercise

* Run [`CheckpointingJob`](src/main/java/com/ververica/flink/training/exercises/CheckpointingJob.java)
  - once with `FsStateBackend` (default mode if run locally)
  - once with `RocksDBStateBackend` (set your Flink cluster to use that; locally you can pass `--useRocksDB` to the job)
* Observe the job's healthiness.
* Fix the job so that checkpoints are not timing out (2 minutes)

**There are more ways of solving this exercise than by the provided solutions. Can you find more?**

-----

[**Back to Tuning & Troubleshooting Labs Overview**](../README.md)
