---
creation date: <% tp.file.last_modified_date("L") %> | <% tp.file.last_modified_date("LT") %>
tags:
  - Data-Structure
  - Specialization
  - <%tp.file.title%>
Specialization:
cssclases:
---

## Concept Overview
#### Description
<%*
if (tp.frontmatter.tags.includes("Specialization")) {
    tR += "#### Additional Properties\n";
    tR += "\n"; // Añade una línea vacía para mejor formato
    tR += "## Generic Implementation\n";
    tR += "\n";
    tR += "## Common Applications\n";
    tR += "\n";
    tR += `## Algorithms In ${tp.file.title}\n`; // Usa template strings para insertar tp.file.title correctamente
} else {
    tR += "#### Main Properties\n";
    tR += "\n";
    tR += "## Common Applications\n";
    tR += "\n";
    tR += "## Comparative Analysis\n";
    tR += "\n";
    tR += "#### Differences In Specialization\n";
    tR += "#### Pros And Cons Between Specializations\n";
}
%>
