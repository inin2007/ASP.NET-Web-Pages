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

## ServerInfo
`ServerInfo.GetHtml()`

Renders status information about ASP.NET Web Pages.

## Twitter
`Twitter.Profile(twitterUserName)`

Renders a Twitter stream for the specified user.

`Twitter.Search(searchQuery)`

Renders a Twitter stream for the specified search text.

## Video
`Video.Flash(filename [, width, height])`

Renders a Flash video player for the specified file with optional width and height.

`Video.MediaPlayer(filename [, width, height])`

Renders a Windows Media player for the specified file with optional width and height.

`Video.Silverlight(filename, width, height)`

Renders a Silverlight player for the specified .xap file with required width and height.

## WebCache
`WebCache.Get(key)`

Returns the object specified by key, or null if the object is not found.

`WebCache.Remove(key)`

Removes the object specified by key from the cache.

`WebCache.Set(key, value [, minutesToCache] [, slidingExpiration])`

Puts value into the cache under the name specified by key.

## WebImage
`WebImage(path)`

Loads an image from the specified path.

`WebImage.AddImagesWatermark(image)`

Adds the specified image as a watermark.

`WebImage.AddTextWatermark(text)`

Adds the specified text to the image.

`WebImage.FlipHorizontal()` or `WebImage.FlipVertical()`

Flips the image horizontally or vertically.

`WebImage.GetImageFromRequest()`

Loads an image when an image is posted to a page during a file upload.

`WebImage.Resize(width, height)`

Resizes the image.

`WebImage.RotateLeft()` or `WebImage.RotateRight()`

Rotates the image to the left or the right.

`WebImage.Save(path [, imageFormat])`

Saves the image to the specified path.
