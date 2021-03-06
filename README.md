<h1>Media Indexer</h1>
The purpose of this QuickStart template is to provision Azure resources that will enable media files to be uploaded to BLOB storage and processed by Azure Media Indexer V2 to provide captions and content that can be used by Azure Search.
</br></br>
See the following resources:
<ul>
  <li>https://azure.microsoft.com/en-gb/resources/samples/media-services-dotnet-functions-integration/</li>
  <li>https://www.videobreakdown.com/</li>
</ul> 


<a href="https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Fdavesamuelson%2Fmediaindexer%2fmaster%2Fazuredeploy.json" target="_blank">
    <img src="http://azuredeploy.net/deploybutton.png"/>
</a>
<a href="http://armviz.io/#/?load=https://raw.githubusercontent.com/davesamuelson/mediaindexern/master/azuredeploy.json" target="_blank">
  <img src="http://armviz.io/visualizebutton.png"/>
</a>


<h2>Pre-Requisites</h2>
Before you can initiate the deployment of resources within this script, you  need:
* An Azure Susbcription
* An identifier for your team that is no more than 6 chars long, lowercase and does not contain any symbols or numbers.
* Username: demouser
* Password: demo@pass1


<h2>What does this script deploy?</h2>
The following resources are deployed:
* A general purpose Azure Storage Account 
* An Azure Media Services Account



<h3>NOTE</h3>
If you are creating templates that fail to Visualise, this usually indicates invalid JSON - try validating in http://jsonlint.com/



