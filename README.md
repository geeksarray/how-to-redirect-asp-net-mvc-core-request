# HOW To Redirect ASP.NET MVC Core Request

There are often requests that needs to be redirect temporarily or permanently from current request to other request. ASP.NET MVC Core RedirectResult, RedirectToActionResult, RedirectToRouteResult, LocalRedirectResult can be used for redirection.

Each Redirect Result has different way of redirection and execution. This redirection can be absolute or relative URL. All following return statements redirect the client to the Index action method of the Product Controller with some difference in execution.

## Files

1. [HomeController](https://github.com/geeksarray/how-to-redirect-asp-net-mvc-core-request/blob/main/ActionResultTypes/Controllers/HomeController.cs) - having code for all variations of  RedirectResult, RedirectPreserveMethod, RedirectPermanentPreserveMethod, LocalRedirectResult, RedirectToActionResult, RedirectToRouteResult.

Implementation of ##RedirectPermanent

![ASP.NET Core MVC RedirectPermanent](https://geeksarray.com/images/blog/aspnet-core-redirectpermanenttest.png)

For more detailed description of each redirect resuls of ASP.NET Core MVC please visit - https://geeksarray.com/blog/how-to-redirect-asp-net-mvc-core-request
