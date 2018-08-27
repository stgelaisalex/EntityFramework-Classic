Include Feature

EF Classic improve the existing Include method by returning an IncludeDbQuery instead of an IQueryable. This allows you to chain multiple related objects by using AlsoInclude and ThenInclude. Both Also and Then Include are syntactic sugar method to make it easier and clearer to include multiple related objects.
