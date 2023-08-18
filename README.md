# Reference documentation for stored procedures

This is the reference documentation to correctly execute stored procedures of this database project.

## Get all outstanding issues (all products)
- SP: dbo.GetAllOutstandingIssuesForAllProducts
- Param 1: StatusId, value: No value.

## Get all outstanding issues for a product (all versions)
- SP: dbo.GetAllOutstandingIssuesForAProduct
- Param 1: StatusId, value: No value.
- Param 2: ProductId, value: 1

## Get all outstanding issues for a product (single version)
- SP: dbo.GetAllOutstandingIssuesForAProductAndASingleVersion
- Param 1: StatusId, value: No value.
- Param 2: ProductId, value: 1
- Param 3: VersionId, value: 4

## Get all outstanding issues within date range for a product (all versions)
- SP: dbo.GetAllOutstandingIssuesWithinDateRangeForAProduct
- Param 1: StatusId, value: No value.
- Param 2: ProductId, value: 1
- Param 3: Date1, value: 2016
- Param 4: Date2, value: 2018

## Get all outstanding issues within date range for a product (single version)
- SP: dbo.GetAllOutstandingIssuesWithinDateRangeForAProductAndASingleVersion
- Param 1: StatusId, value: No value.
- Param 2: ProductId, value: 1
- Param 3: VersionId, value: 4
- Param 4: Date1, value: 2015
- Param 5: Date2, value: 2021

## Get all outstanding issues containing list of keywords (all products)
- SP: dbo.GetAllOutstandingIssuesContainingListOfKeywordsForAllProducts
- Param 1: Keywords, value: Linux, Windows

## Get all outstanding issues for a product containing list of keywords (all versions)
- SP: dbo.GetAllOustandingIssuesForAProductContainingListOfKeywords
- Param 1: Keywords, value: Linux, Windows
- Param 2: ProductId, value: 3

## Get all outstanding issues for a product containing list of keywords (single version)
- SP: dbo.GetAllOutstandingIssuesForAProductContainingListOfKeywordsAndSingleVersion
- Param 1: Keywords, value: MacOs, Windows Mobile
- Param 2: ProductId, value: 3
- Param 3: VersionId, value: 2
- Param 4: , value:
- Param 5: , value:

## Get all outstanding issues within date range for a product containing list of keywords (all versions)
- SP: dbo.GetAllOutstandingIssuesWithinDateRangeForAProductContainingListOfKeywords
- Param 1: Keywords, value: Android, Windows
- Param 2: ProductId, value: 4
- Param 3: Date1, value: 2015
- Param 4: Date2, value: 2016

## Get all outstanding issues within date range for a product containing list of keywords (single version)
- SP: dbo.GetAllOutstandingIssuesWithinDateRangeForAProductContainingListOfKeywordsSingleVersion
- Param 1: Keywords, value: iOS, Android
- Param 2: ProductId, value: 3
- Param 3: VersionId, value: 5
- Param 4: Date1, value: 2015
- Param 5: Date2, value: 2021

## Get all resolved issues (all products)
- SP: dbo.GetAllResolvedIssuesForAllProducts
- Param 1: StatusId, value: No value.

## Get all resolved issues for a product (all versions)
- SP: dbo.GetAllResolvedIssuesForAProduct
- Param 1: StatusId, value: No value.
- Param 2: ProductId, value: 1

## Get all resolved issues for a product (single version)
- SP: dbo.GetAllResolvedIssuesForAProductAndASingleVersion
- Param 1: StatusId, value: No value.
- Param 2: ProductId, value: 1
- Param 3: VersionId, value: 4

## Get all resolved issues within date range for a product (all versions)
- SP: dbo.GetAllResolvedIssuesWithinDateRangeForAProduct
- Param 1: StatusId, value: No value.
- Param 2: ProductId, value: 1
- Param 3: Date1, value: 2016
- Param 4: Date2, value: 2018

## Get all resolved issues within date range for a product (single version)
- SP: dbo.GetAllResolvedIssuesWithinDateRangeForAProductAndASingleVersion
- Param 1: StatusId, value: No value.
- Param 2: ProductId, value: 1
- Param 3: VersionId, value: 4
- Param 4: Date1, value: 2015
- Param 5: Date2, value: 2021

## Get all resolved issues containing list of keywords (all products)
- SP: dbo.GetAllResolvedIssuesContainingListOfKeywordsForAllProducts
- Param 1: Keywords, value: Linux, Windows

## Get all resolved issues for a product containing list of keywords (all versions)
- SP: dbo.GetAllResolvedIssuesForAProductContainingListOfKeywords
- Param 1: Keywords, value: Linux, Windows
- Param 2: ProductId, value: 3

## Get all resolved issues for a product containing list of keywords (single version)
- SP: dbo.GetAllResolvedIssuesForAProductContainingListOfKeywordsAndSingleVersion
- Param 1: Keywords, value: MacOs, Windows Mobile
- Param 2: ProductId, value: 3
- Param 3: VersionId, value: 2
- Param 4: , value:
- Param 5: , value:

## Get all resolved issues within date range for a product containing list of keywords (all versions)
- SP: dbo.GetAllResolvedIssuesWithinDateRangeForAProductContainingListOfKeywords
- Param 1: Keywords, value: Android, Windows
- Param 2: ProductId, value: 4
- Param 3: Date1, value: 2015
- Param 4: Date2, value: 2016

## Get all resolved issues within date range for a product containing list of keywords (single version)
- SP: dbo.GetAllResolvedIssuesWithinDateRangeForAProductContainingListOfKeywordsSingleVersion
- Param 1: Keywords, value: iOS, Android
- Param 2: ProductId, value: 3
- Param 3: VersionId, value: 5
- Param 4: Date1, value: 2015
- Param 5: Date2, value: 2021
