# sQLi.desktop


1. InnoDB: This is the default storage engine for MySQL 5.5 and higher versions. 
It supports transactions, row-level locking, and foreign keys, making it suitable for high-performance applications.

2. MyISAM: This is the default storage engine for MySQL versions prior to 5.5. 
It does not support transactions or foreign keys but is known for its fast read performance.

3. Memory: This engine stores data in memory rather than on disk,
making it very fast but also volatile since data is lost when the server restarts.

4. CSV: This engine stores data in comma-separated values (CSV) format,
making it easy to import and export data from other applications.

5. Archive: This engine is designed for storing large amounts of rarely accessed data efficiently 
by compressing it on disk.

6. Blackhole: This engine accepts data but does not store it, 
making it useful for replicating data to multiple servers or testing replication setups.
