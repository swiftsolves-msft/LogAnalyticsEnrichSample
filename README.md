# LogAnalyticsEnrichSample
The following exmaple is using an existing Log Anlytics table of Office 365 data and querying it out with a Azure Function. The Function take the Public IP in each unique rowe of results and queries another API to bring in a CountryofOrigin value that is not present in the original Office 365 Activity Data.

<a href="https://raw.githubusercontent.com/swiftsolves-msft/LogAnalyticsEnrichSample/master/o365enrichmentfunction.template.json" target="_blank">
    <img src="http://azuredeploy.net/deploybutton.png"/>
</a>
