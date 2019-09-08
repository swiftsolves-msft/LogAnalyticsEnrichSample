# LogAnalyticsEnrichSample
The following exmaple is using an existing Log Anlytics table of Office 365 data and querying it out with a Azure Function. The Function take the Public IP in each unique rowe of results and queries another API to bring in a CountryofOrigin value that is not present in the original Office 365 Activity Data.

<a href="https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Fswiftsolves-msft%2FLogAnalyticsEnrichSample%2Fmaster%2Fo365enrichmentfunction.template.json" target="_blank">
    <img src="http://azuredeploy.net/deploybutton.png"/>
</a>
