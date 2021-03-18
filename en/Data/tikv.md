## Learn Tikv

---

![tikv_stack](https://github.com/tikv/tikv/raw/master/images/tikv_stack.png)

TiKV is an open-source, distributed, and transactional key-value database. Unlike other traditional NoSQL systems, TiKV not only provides classical key-value APIs, but also transactional APIs with ACID compliance. Built in Rust and powered by Raft, TiKV was originally created to complement TiDB, a distributed HTAP database compatible with the MySQL protocol.

The design of TiKV ('Ti' stands for titanium) is inspired by some great distributed systems from Google, such as BigTable, Spanner, and Percolator, and some of the latest achievements in academia in recent years, such as the Raft consensus algorithm.

- [source code reading](https://pingcap.com/blog-cn/tikv-source-code-reading-1/)
- [Quickstart](https://pingcap.com/blog-cn/#TiKV)
- [Who's using TiDB/Tikv in production?](https://pingcap.com/cases-cn/)