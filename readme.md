
<b>Tool:</b>

- SQL Server Engine (DBMS)
- SSMS
- Data Source: AdventureWorksOLTP2014.bak
- Visual Studio Data tools: SSIS, SSAS
- SQL Server Agent

<b>Description:</b>

- Business Case Study: Adventure Works
- Designing Data Warehouse:
    -   Staging Layer
    -   Design Star schema: identify Fact and Dimension and Type
-   Creating DW database
-   Creating Dim, Fact tables, View, Stored Procedure, ...
-   SSIS:
-   <b>ETL load Source to Staging: </b>
    - ![image](https://user-images.githubusercontent.com/59658937/224244013-457f8ffa-2a65-4e64-8279-944d3c47ba67.png)
    - ![image](https://user-images.githubusercontent.com/59658937/224244169-e73f7978-bfb0-439c-bbe4-f02adf0c179b.png)
    - ![image](https://user-images.githubusercontent.com/59658937/224244497-43c6099c-ade5-48f5-bb85-cd433531b4da.png)

-   <b>ETL load Staging to DW: </b>
    - ![image](https://user-images.githubusercontent.com/59658937/224246794-b8a25267-595e-4232-a0fa-929f4d3f6958.png)
    - ![image](https://user-images.githubusercontent.com/59658937/224247024-fa78af6a-c9b4-40f3-9f39-db82eedc0523.png)
    - ![image](https://user-images.githubusercontent.com/59658937/224247111-21bc1332-e916-45f9-807a-aadac11e4c6d.png)

-   <b>Control packages </b>
- Then using SQL Server Agent to create jobs running packages scheduled.
