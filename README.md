# hoge-mermaid

```mermaid
    gitGraph
      branch dev
      checkout dev
      commit
      branch aaa
      branch bbb
      branch ccc
      checkout aaa
      commit
      commit
      checkout bbb
      merge aaa
      commit
      commit
      checkout ccc
      merge aaa
      commit
      commit
      checkout aaa
      merge bbb
      merge ccc
      checkout dev
      merge aaa
```