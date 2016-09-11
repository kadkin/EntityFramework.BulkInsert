# EntityFramework.BulkInsert
This is a Fork of https://efbulkinsert.codeplex.com/

# Added following extensions for Async support:

      Task BulkInsertAsync<T>(this DbContext context, IEnumerable<T> entities, BulkInsertOptions options)

      Task BulkInsertAsync<T>(this DbContext context, IEnumerable<T> entities, int? batchSize = null)

 
      Task BulkInsertAsync<T>(this DbContext context, IEnumerable<T> entities, SqlBulkCopyOptions sqlBulkCopyOptions, int? batchSize = null)


      Task BulkInsertAsync<T>(this DbContext context, IEnumerable<T> entities, IDbTransaction transaction, SqlBulkCopyOptions sqlBulkCopyOptions = SqlBulkCopyOptions.Default, int? batchSize = null)

