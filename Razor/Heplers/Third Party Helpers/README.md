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

## Gravatar Object Reference
`Gravatar.GetHtml(email [, imageSize] [, defaultImage] [, rating] [, imageExtension] [, attributes])`

Renders the Gravatar image for the specified email address.

## Json
`Json.Encode(object)`

Converts a data object to a string in the JavaScript Object Notation (JSON) format.

## LinkShare
`LinkShare.GetHtml(pageTitle [, pageLinkBack] [, twitterUserName] [, additionalTweetText] [, linkSites])`

Renders social networking links using the specified title and optional URL.

## ModelState
`ModelStateDictionary.AddError(key, errorMessage)`

Associates an error message with a form field. Use the ModelState helper to access this member.

`ModelStateDictionary.AddFormError(errorMessage)`

Associates an error message with a form. Use the ModelState helper to access this member.

`ModelStateDictionary.IsValid`

Returns true if there are no validation errors. Use the ModelState helper to access this member.

## ObjectInfo
`ObjectInfo.Print(value [, depth] [, enumerationLength])`

Renders the properties and values of an object and any child objects.

## Recaptcha
`Recaptcha.GetHtml([, publicKey] [, theme] [, language] [, tabIndex])`

Renders the reCAPTCHA verification test.

`ReCaptcha.PublicKey` and `ReCaptcha.PrivateKey`

Sets public and private keys for the reCAPTCHA service. Normally you set these properties in the _AppStart page.

`ReCaptcha.Validate([, privateKey])`

Returns the result of the reCAPTCHA test.
