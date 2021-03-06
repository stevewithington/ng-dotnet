# ng-dotnet

This project was originally created with `dotnet new angular`. See [Use the Angular project template with ASP.NET Core](https://docs.microsoft.com/en-us/aspnet/core/client-side/spa/angular?view=aspnetcore-2.2&tabs=visual-studio) for details.

However, as of the date I created this project, it was using [Angular v6](https://v6.angular.io). I've upgraded it to use [Angular v7](https://angular.io/), and included [PrimeNG](https://www.primefaces.org/primeng/#/) for UI.

Assuming you want to publish and host your app somehwere, check out [Publish an ASP.NET Core app to Azure with Visual Studio](https://docs.microsoft.com/en-us/aspnet/core/tutorials/publish-to-azure-webapp-using-vs?view=aspnetcore-2.2).

![GitHub tag (latest by date)](https://img.shields.io/github/v/tag/stevewithington/ng-dotnet)
[![GitHub stars](https://img.shields.io/github/stars/stevewithington/ng-dotnet)](https://github.com/stevewithington/ng-dotnet/stargazers)
[![GitHub issues](https://img.shields.io/github/issues/stevewithington/ng-dotnet)](https://github.com/stevewithington/ng-dotnet/issues)
[![GitHub forks](https://img.shields.io/github/forks/stevewithington/ng-dotnet)](https://github.com/stevewithington/ng-dotnet/network)

## dotnet run

Once you have [.NET Core command-line interface (CLI) tools](https://docs.microsoft.com/en-us/dotnet/core/tools/?tabs=netcore2x) installed, from your command line, you should be able to `dotnet run` and see the app running in your browser.

## Azure Hosting + Deployment

For hosting and deployment on Azure, see <https://docs.microsoft.com/en-us/aspnet/core/host-and-deploy/index?view=aspnetcore-2.2>.

## !important

If you don't want to run NG from .NET, use `npm start` to launch the Angular CLI development server, not `ng serve`, so that the configuration in `package.json` is respected. To pass additional parameters to the Angular CLI server, add them to the relevant scripts line in your `package.json` file.

## Resources

* [.NET Core 2.2](https://docs.microsoft.com/en-us/dotnet/core/)
* [Angular](https://angular.io/)
* [Angular CLI](https://github.com/angular/angular-cli)
* [PrimeNG](https://www.primefaces.org/primeng/#/)
* [Short and relevant series on Angular + .NET + Azure](https://blog.jeremylikness.com/get-started-with-angular-on-net-core-2-1-part-one-2effcfe8fae9)

## License

[MIT](LICENSE.md)
