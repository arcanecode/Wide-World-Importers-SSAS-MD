# Wide-World-Importers-SSAS-MD
SQL Server 2016 Analysis Services Multi-Dimensional Project

This project is built off of the WideWorldImportersDW database from Microsoft. You can find their sample project at: https://github.com/Microsoft/sql-server-samples/tree/master/samples/databases/wide-world-importers

The main purpose for creating this is to support my "So you think MDX is hard?" demo, which you can also find on my repository. If all you want is a backup of the MDF file, you can find it there.

The project was kept fairly simple, it just has some basic calculations (Current YTD and Previous YTD).

It has some KPIs, they are somewhat unrealisitc but were created such that there would be some red, green, and yellow results. In addition I used a variety of gauges just to show the different types.

I left most of the attributes and calculations visible, even attributes in heirarchies. I can't predict what people may wish to use for demos, so left them available.

11/1/2016
I added new updates to the date dimension. In the source it only held day, month, and year levels. I added calculated fields in the DSV to add quarters. I also added numeric keys for year/quater and year/month. Finally I added Beginning of Month and Beginning of Quarter dates. 
