# ag-grid-demo

This example show how to connect to RDS and read data into ag-grid table for visualization. 

1) Add DB connection details 
edit ~\ag-grid-mx-debt-example\src\server\mxDebtAnalysis.js
set var connection = mysql.createConnection({host: 'xxxx', user: 'xxxx', password: 'xxxx'});

2) Define table columns and others
edit ~\ag-grid-mx-debt-example\src\client\exampleEnterpriseModel.js

If you do not have any data to work with, you can complete this project https://github.com/univercity2012/aws_rds_mex_debt_analysis.git first and then start this example.

Reference: this example is based on https://github.com/ag-grid/ag-grid-enterprise-mysql-example.git
