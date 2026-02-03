# XML_Projekt

## Generic Project Structure
```
/project-root
│
├── /data                 # Exclusive XML data storage 
│   ├── main_data.xml     # Primary data records
│   └── users.xml         # User management data (if applicable)
│
├── /schemas              # XSD files for data validation 
│   └── data_schema.xsd   # Must validate all updates here
│
├── /stylesheets          # Transformation and styling
│   ├── transform.xsl     # XSLT for at least one feature 
│   ├── report_fo.xsl     # FO stylesheet for PDF generation [cite: 82, 83]
│   └── style.css         # General UI styling [cite: 69]
│
├── /views                # Front-end templates
│   ├── index.xhtml       # XHTML compliant landing page [cite: 81]
│   └── dashboard.xhtml   # Main feature interface [cite: 48]
│
├── /public               # Static assets
│   └── visualization.svg # Scalable Vector Graphics [cite: 82]
│
├── /docs                 # Project artifacts [cite: 87]
│   ├── FactSheet.pdf     # 2-page project summary [cite: 52, 71]
│   └── Presentation.pdf  # 5-slide elevator pitch [cite: 54, 63]
│
├── app.js                # Node.js / Express server entry point 
├── package.json          # Project dependencies (e.g., libxmljs, xslt-processor)
└── .gitignore
```
