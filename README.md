# LangChain experiments

With the goal of providing Cassandra / Astra DB support in the form of
classes, practices and extensions.

## Phase I - LLM caching

See [this page](phase1_llmcaching.md).

## Phase II - CQLChain

See [this page](phase2_cqlchain.md).

## Phase III - Memory

See [this page](phase3_memory.md)

## Phase IV - Agents

Some exploration on how to create custom agents is in
`01_other-backends/agent-exp-01.ipynb`.

Mostly this is about making sure structured input is accepted
and dependency injection (say, a DB connection, etc) is ok.

Also, packaging a "toolkit" is understood and exemplified.

#### Cassandra

Trying to come up with a reasonable CQL minimal agent
packaged as a toolkit.

`02_cassandra-astra/cqlagent-Cassandra_01` is the notebook
and `02_cassandra-astra/CQLAgentToolkit.py` is where the implementation is.
