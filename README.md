# ag-grid-demo

This example show how to connect to RDS and read data into ag-grid table for visualization. 

1) Add DB connection details 
edit ~\ag-grid-mx-debt-example\src\server\mxDebtAnalysis.js
set var connection = mysql.createConnection({host: 'xxxx', user: 'xxxx', password: 'xxxx'});

2) Define table columns and others
edit ~\ag-grid-mx-debt-example\src\client\exampleEnterpriseModel.js

Reference: this example is based on https://github.com/ag-grid/ag-grid-enterprise-mysql-example.git
