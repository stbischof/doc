---
title: ColumnInternalDataType
group: Enum
---

# ColumnInternalDataType<a name="enum-columninternaldatatype"></a>

Enumeration that defines the internal data type classifications used throughout the OLAP framework for consistent data handling, SQL generation, comparison operations, formatting, and type validation across different database systems and analytical contexts. ColumnInternalDataType provides a unified type system that abstracts database-specific data type variations while maintaining the semantic information necessary for proper analytical processing, measure aggregation, dimensional sorting, and user interface presentation. This internal type system is essential for cross-database compatibility where the same OLAP model needs to work with different database platforms that may have varying data type names, precision specifications, and behavioral characteristics. The enumeration supports sophisticated type handling scenarios including automatic type conversion between database systems, appropriate SQL generation that respects database-specific type requirements, measure aggregation logic that considers type compatibility and precision requirements, comparison and sorting operations that handle different data types appropriately, and user interface formatting that presents data according to type-specific conventions. The internal data type system enables robust OLAP applications that can handle diverse data sources while maintaining consistent analytical behavior and user experiences regardless of the underlying database platform or data type variations.
## Enumeration Literals

### STRING - (0)

<em>Text data type for character strings, names, descriptions, and categorical values in dimensions and member properties.</em>

### NUMERIC - (1)

<em>Decimal numeric data type for measure values, calculated metrics, and precise numerical data requiring decimal precision.</em>

### INTEGER - (2)

<em>Whole number data type for counts, ordinal values, and integer-based measures and dimension keys.</em>

### BOOLEAN - (3)

<em>Boolean data type for true/false flags, binary indicators, and yes/no categorical data in dimensional attributes.</em>

### DATE - (4)

<em>Date data type for calendar dates without time components, used in time dimensions and date-based analytical operations.</em>

### TIME - (5)

<em>Time data type for time-of-day values without date components, used for intraday analysis and time-based dimensions.</em>

### TIMESTAMP - (6)

<em>Timestamp data type combining date and time components for precise temporal data, event tracking, and time-series analysis.</em>

