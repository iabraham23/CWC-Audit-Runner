[![Netlify Status](https://api.netlify.com/api/v1/badges/61bd22ab-a197-4b8e-8022-42c493b1b4d2/deploy-status)](https://app.netlify.com/projects/cwc-audit-runner/deploys) 

This repo manages the live website to run composite automations for CWC Advisors @ https://cwc-audit-runner.netlify.app/ 

Input composite CSV's from Orion and download an excel sheet of a CWC style composite
Required CSV columns: 
- Included -- Bool, whether or not this data point is included in this composite 
- Reigstration Name
- Beginning Value
- Ending Value
- Gross Performance %
- Account Number
- Account Start Date
- Model 
