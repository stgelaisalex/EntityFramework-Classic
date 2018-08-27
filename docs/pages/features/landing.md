## Boost your performance
With Entity Framework Classic you can consult, merge, save or delete your data faster by either using Bulk or Batch operations. Both options allow you reduce the number of queries sent to the server therefore minimizing the round-trip between the application and the database.

With features like QueryCached or QuerryDefered, you have control over when and how the query is executed either. These options also allow you to optimize the round-trip between the application and the database by minimizing redundant calls.

## Compatible with .NET Core
While EF6 and EF Core are both develop by Microsoft, they have two different set of features. It is currently impossible to use EF6 inside .NET Core which leaves developers with tough choices. EF Classic bring a new option to the table by letting you use EF6 with .NET Core. Another advantage is that EF Classic continue to support EF6 but continuously improving it.

## Syntactic sugar methods
EF Classic introduce different method like ThenInclude and AlsoInclude to help your code readability and express the intent of you code with less effort.

## Test more with less effort
EF Classic support In-Memory provide like Effort or local database like SQL Compact to allow you to test without the need of complex infrastructure.

## Features Comparison
Entity Framework Classic comes in two editions. A free community version and enterprise edition.
Here's a comparison grid for both editions:


|Community Edition |Entreprise Edition|
|------------ | -------------|
|•	.NET Core support|•	Batch Operations (SaveChanges, Insert, Delete, etc)|
|•	Syntactic sugar method like Then/Also Include|•	Bulk Operations (Save, Insert, Delete, etc)|
|•	IQueryable Extensions (Deferred and Future)|•	C# Eval function|
||•	Audit|
||•	In-memory provider (Testing)|

