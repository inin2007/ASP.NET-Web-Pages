## Analytics (Google)
`Analytics.GetGoogleHtml(webPropertyId)`

Renders the Google Analytics JavaScript code for the specified ID.

`Analytics.GetStatCounterHtml(project, security)`

Renders the StatCounter Analytics JavaScript code for the specified project.

`Analytics.GetYahooHtml(account)`

Renders the Yahoo Analytics JavaScript code for the specified account.

## Bing
`Bing.SearchBox([boxWidth])`

Passes a search to Bing. To specify the site to search and a title for the search box, you can set the Bing.SiteUrl and Bing.SiteTitle properties. Normally you set these properties in the _AppStart page.

`Bing.AdvancedSearchBox([, boxWidth] [, resultWidth] [, resultHeight] [, themeColor] [, locale])`
  
 Displays Bing search results in the page with optional formatting. To specify the site to search and a title for the search box, you  can set the Bing.SiteUrl and Bing.SiteTitle properties. Normally you set these properties in the _AppStart page.
  
## Crypto
`Crypto.Hash(string [, algorithm]) ` or `Crypto.Hash(bytes [, algorithm])`
  
Returns a hash for the specified data. The default algorithm is sha256.
  
## Facebook
`Facebook.LikeButton(href [, buttonLayout] [, showFaces] [, width] [, height] [, action] [, font] [, colorScheme] [, refLabel])`
  
Lets Facebook users make a connection to pages.
  
## FileUpload
  
`FileUpload.GetHtml([initialNumberOfFiles] [, allowMoreFilesToBeAdded] [, includeFormTag] [, addText] [, uploadText])`
  
Renders UI for uploading files.
  
## GamerCard
`GamerCard.GetHtml(gamerTag)`

Renders the specified Xbox gamer tag.
