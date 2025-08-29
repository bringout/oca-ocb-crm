# Reports

Report definitions and templates in crm.

```mermaid
classDiagram
    class ActivityReport
    Model <|-- ActivityReport
```

## Available Reports

### Analytical/Dashboard Reports
- **Leads Analysis** (Analysis/Dashboard)
- **Pipeline Analysis** (Analysis/Dashboard)
- **Activities** (Analysis/Dashboard)
- **Pipeline Activities** (Analysis/Dashboard)


## Report Files

- **crm_activity_report.py** (Python logic)
- **crm_activity_report_views.xml** (XML template/definition)
- **crm_opportunity_report_views.xml** (XML template/definition)
- **__init__.py** (Python logic)

## Notes
- Named reports above are accessible through Odoo's reporting menu
- Python files define report logic and data processing
- XML files contain report templates, definitions, and formatting
- Reports are integrated with Odoo's printing and email systems
