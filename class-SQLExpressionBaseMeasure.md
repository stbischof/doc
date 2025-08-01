---
title: SQLExpressionBaseMeasure
group: Class
---

# SQLExpressionBaseMeasure<a name="class-sqlexpressionbasemeasure"></a>

Advanced measure implementation that enables sophisticated analytical calculations through custom SQL expressions, providing powerful capabilities for implementing complex business logic, mathematical computations, and data transformations that cannot be achieved through standard column-based measures or simple aggregation functions. SQLExpressionBaseMeasure represents the most flexible and powerful measure type in the OLAP framework, enabling data architects and business analysts to implement sophisticated analytical requirements including complex financial calculations with multiple variables and conditional logic, statistical computations that require advanced mathematical functions, data quality metrics that evaluate data completeness and accuracy across multiple dimensions, regulatory compliance calculations that implement specific industry formulas and business rules, and performance indicators that combine multiple data sources with complex weighting algorithms. This measure type supports advanced analytical scenarios where standard aggregation functions are insufficient, including weighted averages that consider varying importance factors, variance and standard deviation calculations for statistical analysis, time-weighted calculations for financial analysis, conditional aggregations that apply different logic based on dimensional context, and composite metrics that combine multiple underlying measures with sophisticated mathematical relationships. The SQL expression capability integrates seamlessly with the OLAP query processing engine to provide optimal performance through query optimization, supports database-specific SQL features and functions for maximum analytical flexibility, and enables dynamic expression evaluation that can adapt to different dimensional contexts and filtering conditions while maintaining query performance and result accuracy.
## Extends
- BaseMeasure [🔗](./class-BaseMeasure)
## Attributes

<table>
  <thead>
    <tr>
      <th>Name</th>
      <th>Id</th>
      <th>Typ</th>
      <th>Lower</th>
      <th>Upper</th>
    </tr>
  </thead>
  <tbody>
  </tbody>
</table>

## References

<table>
  <thead>
    <tr>
      <th>Name</th>
      <th>Typ</th>
      <th>Lower</th>
      <th>Upper</th>
      <th>Containment</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><strong>column</strong></td>
      <td>SQLExpressionColumn<a href="./class-SQLExpressionColumn">🔗</a></td>
      <td>1</td>
      <td>1</td>
      <td>false</td>
    </tr>
    <tr>
      <td colspan="5"><em>Reference to the SQLExpressionColumn that defines the custom SQL expression logic for this advanced measure implementation. The SQLExpressionColumn contains the sophisticated SQL formula, mathematical computations, conditional logic, and data transformations that enable complex analytical calculations beyond the capabilities of standard column-based aggregation functions. This relationship establishes the connection between the measure definition and its custom SQL implementation, enabling powerful analytical scenarios such as weighted averages with multiple factors, conditional aggregations based on dimensional context, statistical calculations requiring advanced mathematical functions, financial formulas implementing specific industry regulations, and composite metrics that combine multiple data sources with complex business rules. The referenced SQLExpressionColumn must provide a valid SQL expression that can be evaluated within the aggregation context, supporting database-specific functions and syntax while maintaining optimal query performance through intelligent SQL generation and optimization strategies that preserve both computational accuracy and analytical flexibility across diverse business intelligence requirements.</em></td>
    </tr>
  </tbody>
</table>



## Used by


## ClassDiagramm

```mermaid
classDiagram
  class SQLExpressionBaseMeasure {
  }

  BaseMeasure <|-- SQLExpressionBaseMeasure
  SQLExpressionBaseMeasure --> SQLExpressionColumn : column

```
