## Improve Performance
With Entity Framework Classic save you data faster by either using Bulk or Batch operations. By doing opeation in bulk or batch you reduce the number of queries sent to the server therefore minimizing the round-trip between the application and the database.

With features like QueryCached or QuerryDefered, you have control over when the query is executed either by controling the cache or it's execution window.

## .NET Core Support
EF6 and EF Core are two differents products and both have their own set of features. Since, EF Core is missing some key features from EF6 and that EF6 support is limited. That leaves developers with tough choices. EF Classic bring a new option to the table by letting you use EF6 inside .NET Core.

## Features Comparaison
Entity Framework Classic comes in two editions. A free communtity version and enterprise edition.

Here's an comparaison grid for both editions:

|Community Edition |Entreprise Edition|
|------------ | -------------|
|•	.NET Core support|•	Batch Operations(SaveChanges, Insert, Delete, etc)|
|•	Syntactic sugar method like Then/Also Include|•	Bulk Operations(Save, Insert, Delete, etc)|
|•	IQueryable Extensions (Deferred and Future)|•	C# Eval function|
||•	Audit|
||•	In-memory provider (Testing)|

