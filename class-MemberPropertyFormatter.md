---
title: MemberPropertyFormatter
group: Class
---

# MemberPropertyFormatter<a name="class-memberpropertyformatter"></a>

Specialized formatter for controlling the presentation of member properties in dimensional browsers, tooltip displays, drill-through results, and other contexts where additional member attributes need to be presented in user-friendly, contextually appropriate formats. MemberPropertyFormatter enables sophisticated property presentation including data type-specific formatting where dates, numbers, currencies, and other typed values are presented according to appropriate cultural and business conventions, conditional property highlighting where certain property values are visually emphasized based on business significance or exception conditions, composite property displays where multiple related properties are combined into meaningful summary presentations, and contextual property organization where properties are grouped, ordered, or filtered based on user context, analytical purpose, or business relevance. This formatting capability is essential for rich dimensional experiences where users need access to detailed member information for analysis, decision-making, or data exploration, enabling sophisticated analytical workflows where dimensional context and member details can be seamlessly integrated into analytical interfaces without overwhelming users with excessive detail or poorly formatted information.
## Extends
- Formatter [🔗](./class-Formatter)- IMemberPropertyFormatter [🔗](./class-IMemberPropertyFormatter)
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
  </tbody>
</table>



## Used by

- MemberProperty[🔗](./class-MemberProperty) → formatter

## ClassDiagramm

```mermaid
classDiagram
  class MemberPropertyFormatter {
  }

  Formatter <|-- MemberPropertyFormatter  IMemberPropertyFormatter <|-- MemberPropertyFormatter

```
