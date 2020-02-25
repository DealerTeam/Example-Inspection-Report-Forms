# Example Inspection Report Forms
Printable forms you can use to prepare or extend inspection reports.
## Getting Started
These instructions will walk you through installing the pages and resources.

### Deploy using Heroku
<a href="https://githubsfdeploy.herokuapp.com?owner=dealerTeam&repo=https://github.com/DealerTeam/Example-Inspection-Report-Forms&ref=Master">
  <img alt="Deploy to Salesforce"
       src="https://raw.githubusercontent.com/afawcett/githubsfdeploy/master/deploy.png">
</a>

### Installing Pages
1. Open the Developer Console under the settings gear

2. Under the File > New menu select Visualforce Page

3. Enter a descriptive name (e.g. VehicleReportCard) and select ok

4. Paste the contents of the example page and save (File > Save)

### Installing Static Resources
1. Open the Developer Console under the settings gear

2. Under the File > New menu select Static Resource

3. Enter a descriptive name (e.g. VehicleReportCardCSS) and select ok

4. Select text/css under MIME Type

5. Paste the contents of the example static resource and save (File > Save)

6. Note, you will need to update the stylesheet name on line 4 of the Visualforce page ````<apex:stylesheet value="{!URLFOR($Resource.VehicleReportCardCSS)}" />````

### Viewing Pages
To view your page(s) you will need to pass the DealID parameter. ````https://agility-ruby-6856-dev-ed--dealer.visualforce.com/apex/vehiclereportcard````


1. Click the App Launcher icon

2. Enter Inspection in the search area.

3. Click Inspection Reports.

4. Select the report # to open up the inspection report.

5. Copy the unique identifier from the URL between the slashes. **a0n17000003SP87AAG** is the report ID in the example below. ````https://agility-ruby-6856-dev-ed.lightning.force.com/lightning/r/dealer__Inspection_Report__c/a0n17000003SP87AAG/view````

6. Browse to your page appending the report ID.
````https://agility-ruby-6856-dev-ed.lightning.force.com/apex/vehiclereportcard?id=a0n17000003SP87AAG````

## Customizing Pages
The pages can be customized to meet your needs.