---
title: MemberFormatter
group: Class
---

# MemberFormatter<a name="class-memberformatter"></a>

Specialized formatter for controlling how dimensional members are displayed in hierarchical browsers, filter lists, axis labels, and other dimensional navigation interfaces, enabling sophisticated member presentation that can include custom naming schemes, contextual information, visual indicators, and hierarchical styling that enhances dimensional navigation and member selection experiences. MemberFormatter supports advanced presentation scenarios including hierarchical indentation and visual styling that clearly communicates level relationships and member hierarchy structure, conditional member styling where visual presentation adapts based on member properties, usage patterns, or business significance, custom member naming that can combine multiple attributes or apply business-specific naming conventions, cultural and linguistic adaptation where member names are presented according to user language preferences and regional conventions, and contextual information display where additional member details are presented to aid user understanding and selection. This formatting capability is particularly valuable for complex dimensional structures with deep hierarchies, business-specific terminology, or cultural variations where standard member names may not provide sufficient context for effective user navigation and analysis.
## Extends
- Formatter [🔗](./class-Formatter)- IMemberFormatter [🔗](./class-IMemberFormatter)
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

- Level[🔗](./class-Level) → memberFormatter

## ClassDiagramm

```mermaid
classDiagram
  class MemberFormatter {
  }

  Formatter <|-- MemberFormatter  IMemberFormatter <|-- MemberFormatter

```
