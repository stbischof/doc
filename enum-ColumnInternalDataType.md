---
title: ColumnInternalDataType
group: Enum
---

# ColumnInternalDataType<a name="enum-columninternaldatatype"></a>

Enumeration that defines the internal data type classifications used throughout the OLAP framework for consistent data handling, SQL generation, comparison operations, formatting, and type validation across different database systems and analytical contexts. ColumnInternalDataType provides a unified type system that abstracts database-specific data type variations while maintaining the semantic information necessary for proper analytical processing, measure aggregation, dimensional sorting, and user interface presentation. This internal type system is essential for cross-database compatibility where the same OLAP model needs to work with different database platforms that may have varying data type names, precision specifications, and behavioral characteristics. The enumeration supports sophisticated type handling scenarios including automatic type conversion between database systems, appropriate SQL generation that respects database-specific type requirements, measure aggregation logic that considers type compatibility and precision requirements, comparison and sorting operations that handle different data types appropriately, and user interface formatting that presents data according to type-specific conventions. The internal data type system enables robust OLAP applications that can handle diverse data sources while maintaining consistent analytical behavior and user experiences regardless of the underlying database platform or data type variations.
- **STRING** (0)
- **NUMERIC** (1)
- **INTEGER** (2)
- **BOOLEAN** (3)
- **DATE** (4)
- **TIME** (5)
- **TIMESTAMP** (6)
