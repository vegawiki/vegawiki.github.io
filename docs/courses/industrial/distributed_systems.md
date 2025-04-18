---
title: Распределённые системы
nav_order: 2
parent: industrial
---

# Распределённые системы


## Описание 

В рамках курса рассматривается архитектура распределённых систем: общие принципы и популярные распределённые алгоритмы и то, и как они применяются в реальных промышленных продуктах. Разбираются сложности при разработке таких систем, а также вопросы консистентности, масштабируемости и отказоустойчивости.  

Программа: 

- Модель распределённой системы.
- Время и високосные секунды.
- Репликация и линеаризуемость. Линеаризуемый регистр, алгоритм ABD.
- State Machine Replication, Atomic Broadcast, Consensus.
- Impossibility of Consensus.
- Single-Decree Paxos / Локальное хранилище: LSM, снимки состояния.
- Multi-Paxos / Google File System.
- RAFT / Дизайн KV хранилища, Google BigTable.
- Paxos Made Live.
- Формальные методы, TLA+.
- Транзакции, Two-Phase Locking, Snapshot Isolation.
- Распределённые транзакции: Spanner, Calvin.
- PBFT / CRDT.
- Bitcoin.
- MapReduce.   


## Предварительные требования:

- **[Алгоритмы и структуры данных]({% link docs/courses/basic/basics_of_algorithms.md %})**: кирпичики, из которых строятся распределенные системы

- **[Методы программирования]({% link docs/courses/fundamental/programming_practices.md %})**: нужно знать программирование на более низком уровне для построения распределенных систем


## Используется в:


## Смотреть также:

## Ссылки

[ШАД](https://shad.yandex.ru/courses)