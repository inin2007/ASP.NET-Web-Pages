# Folder Patchs
ASP.NET has 3 folder paths: the Href method, the ~ operator, and the Server.MapPath method.

## The Href method
`@{var styleSheet = "~/Shared/style.css";}`

`<link rel="stylesheet" type="text/css" href="/style.css" />`

or

`<link rel="stylesheet" type="text/css" href="@Href(styleSheet)" />`

## The ~ operator
Example:

`var myImages = "~/images";`
## The Server.MapPath method
Example:

`var path = "~/data.txt";`

`var file = Server.MapPath(path);`
