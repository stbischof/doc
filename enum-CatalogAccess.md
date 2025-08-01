---
title: CatalogAccess
group: Enum
---

# CatalogAccess<a name="enum-catalogaccess"></a>

Enumeration defining the access permission levels for OLAP catalogs within the role-based security framework, establishing the fundamental security boundaries that control whether users can access catalog resources and determining the overall scope of analytical capabilities available to specific roles. CatalogAccess represents the highest level of the OLAP security hierarchy and serves as the primary access control decision point that influences all subordinate security evaluations for cubes, dimensions, hierarchies, and members contained within the catalog. This enumeration supports sophisticated enterprise security scenarios including complete catalog isolation for multi-tenant deployments, selective access patterns for organizational security models, and metadata-only access for users who need dimensional information without access to sensitive measure data. The catalog access levels enable flexible security architectures that can accommodate diverse organizational needs while maintaining performance and usability through appropriate access scope definition.
- **NONE** (0)
- **ALL** (1)
- **CUSTOM** (2)
- **ALL_DIMENSIONS** (3)
